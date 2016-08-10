#### Test 79751015c075caf_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-10 14:10:44.497  5730  5730 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-10 14:10:44.582  5730  5730 D LgDataFeature: LgDataFeature() Constructor: none
08-10 14:10:44.583  5730  5730 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 14:10:44.643  5730  5730 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-10 14:10:44.666  5730  5730 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-10 14:10:44.667  5730  5730 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-10 14:10:44.682  5730  5730 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-10 14:10:44.683  5730  5730 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
08-10 14:10:44.693  1025  2030 I ActivityManager: Killing 4747:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-10 14:10:44.818  5768  5768 D AndroidRuntime: 
08-10 14:10:44.818  5768  5768 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-10 14:10:44.822  5768  5768 D AndroidRuntime: CheckJNI is OFF
08-10 14:10:44.849  1025  2083 W libprocessgroup: failed to open /acct/uid_10085/pid_4747/cgroup.procs: No such file or directory
08-10 14:10:44.865  3130  3651 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-10 14:10:44.866  3130  3651 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3eebac04 on behalf of 5730
08-10 14:10:44.873  4327  5779 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-10 14:10:44.923  1025  2064 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5791 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 14:10:44.939  5730  5730 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-10 14:10:44.962  5768  5768 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-10 14:10:44.966  1025  2083 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 14:10:44.973  5730  5730 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-10 14:10:44.975  1965  1981 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-10 14:10:44.979  1025  2083 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-10 14:10:44.980  1025  2083 D ActivityManager: setTaskToReturnTo : TaskRecord{2b73952d #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 14:10:44.980  1025  2083 D ActivityManager: setTaskToReturnTo : TaskRecord{2b73952d #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 14:10:44.981  1025  2083 D WindowStateEx: AppWindowTokenEx init.. 
08-10 14:10:44.982   343   351 E GBMv2   : DFP En is all cleared set to be enabled
08-10 14:10:45.019  1025  2083 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5818 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-10 14:10:45.021  5768  5768 D AndroidRuntime: Shutting down VM
08-10 14:10:45.067  1965  3731 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-10 14:10:45.068  1965  3731 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3c0f205c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-10 14:10:45.069  1965  1982 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-10 14:10:45.070  1965  1982 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1174ff65 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-10 14:10:45.118  5818  5818 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-10 14:10:45.173  5818  5818 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-10 14:10:45.179  5818  5818 I LibraryLoader: Loading: webviewchromium
08-10 14:10:45.182  5818  5818 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8392-8395)
08-10 14:10:45.182  5818  5818 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 14:10:45.193  5818  5818 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3dc49d0d}
,08-10 14:10:45.195  5818  5818 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 14:10:45.195  5818  5818 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 14:10:45.201  5818  5818 I BrowserStartupController: Initializing chromium process, renderers=0
08-10 14:10:45.202  5818  5818 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 14:10:45.252  5818  5839 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-10 14:10:45.257   327  1376 V AudioPolicyService: registerClient() client 0xb1007c40, uid 10118
08-10 14:10:45.261  1025  1087 D BluetoothManagerService: Message: 20
08-10 14:10:45.261  1025  1087 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2667d26b:true
08-10 14:10:45.262  5818  5843 D BluetoothAdapter: 966722754: getState() :  mService = null. Returning STATE_OFF
08-10 14:10:45.272  5791  5791 D DocsApplication: Installing DEX configuration.
08-10 14:10:45.277  5818  5818 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 14:10:45.277  5818  5818 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=23 off=46780 len=2953
08-10 14:10:45.278  5818  5818 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-10 14:10:45.285  5818  5818 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 14:10:45.285  5818  5818 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 14:10:45.285  5818  5818 I Adreno-EGL: Build Date: 12/12/14 금
08-10 14:10:45.285  5818  5818 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 14:10:45.285  5818  5818 I Adreno-EGL: Remote Branch: 
08-10 14:10:45.285  5818  5818 I Adreno-EGL: Local Patches: 
08-10 14:10:45.285  5818  5818 I Adreno-EGL: Reconstruct Branch: 
08-10 14:10:45.285  5791  5791 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-10 14:10:45.287  5791  5791 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{2250d35b com.google.android.apps.docs}
08-10 14:10:45.299  5791  5791 D TAG     : onCreate()
08-10 14:10:45.313  5791  5791 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-10 14:10:45.339  5818  5849 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-10 14:10:45.341  5818  5818 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-10 14:10:45.360  5818  5818 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 14:10:45.365  5818  5818 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-10 14:10:45.368  5818  5818 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-10 14:10:45.371  5818  5818 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-10 14:10:45.371  5818  5818 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-10 14:10:45.385  5818  5818 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-10 14:10:45.393  5818  5818 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 14:10:45.393  5818  5818 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 14:10:45.417  5818  5864 D OpenGLRenderer: Render dirty regions requested: true
08-10 14:10:45.417  5818  5864 I OpenGLRenderer: Initialized EGL, version 1.4
08-10 14:10:45.423  5818  5864 D OpenGLRenderer: Enabling debug mode 0
08-10 14:10:45.430  5818  5818 D Atlas   : Validating map...
08-10 14:10:45.437  1025  1999 D SplitWindow: check instance of lgWin Window{2110803c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 14:10:45.476  1025  2030 V SIM_STK : Menu title from STK is T-Mobile
08-10 14:10:45.479  5818  5862 D LgDataFeature: LgDataFeature() Constructor: none
08-10 14:10:45.479  5818  5862 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 14:10:45.534  4327  5779 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 659 ms] updated apps [took 658 ms] 
08-10 14:10:45.551  1025  1088 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +485ms (total +568ms)
08-10 14:10:45.552  1025  1088 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5786a62 u0 com.test.thalitest/.MainActivity t6} time:108766
08-10 14:10:45.553  5818  5818 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@22103a79 time:108766
08-10 14:10:45.620  5818  5818 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-10 14:10:45.656  5818  5818 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-10 14:10:45.656  5818  5818 I chromium: 
08-10 14:10:45.667  5818  5862 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-10 14:10:45.667  5818  5862 I chromium: 
08-10 14:10:45.773  5818  5881 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435148288
08-10 14:10:45.785  5818  5881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 14:10:45.785  5818  5881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 14:10:45.785  5818  5881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 14:10:45.785  5818  5881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 14:10:45.785  5818  5881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-10 14:10:45.786  5818  5881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27d9a5ed added. We now have 1 listener(s)
08-10 14:10:45.790  1025  1040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:10:45.792  5818  5881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-10 14:10:45.795  5818  5881 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 14:10:45.796  5818  5881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 14:10:45.796  5818  5881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 14:10:45.804  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 14:10:45.805  5818  5881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e798470 added. We now have 1 listener(s)
08-10 14:10:45.805  5818  5881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:10:45.808  1025  1537 D WifiService: New client listening to asynchronous messages
08-10 14:10:45.812  5818  5881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 14:10:45.812  5818  5881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 14:10:45.812  5818  5881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 14:10:45.812  5818  5881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 14:10:45.812  5818  5881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 14:10:45.814  5818  5881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:10:45.815  1025  1903 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:10:45.815  5818  5881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-10 14:10:45.827  5818  5881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:10:45.828  5818  5881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:10:45.828  5818  5881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:10:45.828  5818  5881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:10:45.828  5818  5881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:10:45.828  5818  5881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:10:45.828  5818  5881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:10:45.828  5818  5881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:10:45.828  5818  5881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:10:45.828  5818  5881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 14:10:45.828  5818  5881 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 14:10:45.829  5818  5881 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 14:10:45.862  5818  5818 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 14:10:46.371  5791  5791 D LgDataFeature: LgDataFeature() Constructor: none
08-10 14:10:46.371  5791  5791 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 14:10:46.537  1834  4476 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-10 14:10:46.589  1025  1765 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5892 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-10 14:10:46.591  1025  1765 I ActivityManager: Killing 4876:com.lge.bnr/1000 (adj 15): empty #17
08-10 14:10:46.643   343   353 E GBMv2   : DFP En is all cleared set to be enabled
,08-10 14:10:46.643   343   353 E GBMv2   : Set value is all cleared set the max
08-10 14:10:46.643   343   353 I GBMv2   : DFP Enabled. Ignore VFP set
08-10 14:10:46.669  1025  2083 W libprocessgroup: failed to open /acct/uid_1000/pid_4876/cgroup.procs: No such file or directory
,08-10 14:10:46.694  5791  5791 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-10 14:10:46.737  5892  5892 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-10 14:10:46.754  5818  5887 W jxcore-log: Initializing JXcore engine
08-10 14:10:46.754  5818  5887 W jxcore-log: JXcore engine is ready
,08-10 14:10:46.757  5892  5892 I LockScreenSettings: New app installed broadcast received ..
08-10 14:10:46.760  5892  5892 I LockScreenSettings: Number of installed packages  1
08-10 14:10:46.764  1834  4476 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-10 14:10:46.811  1025  1709 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5913 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-10 14:10:46.832  5887  5887 W Thread-647: type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[6144]" dev="sockfs" ino=6144 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-10 14:10:46.832  5887  5887 W Thread-647: type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-10 14:10:46.832  5887  5887 W Thread-647: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10010]" dev="sockfs" ino=10010 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-10 14:10:46.832  5887  5887 W Thread-647: type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-10 14:10:46.832  5887  5887 W Thread-647: type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[28970]" dev="sockfs" ino=28970 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-10 14:10:46.861  5818  5887 W jxcore-log: Starting JXcore engine
,08-10 14:10:46.880  5913  5913 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 14:10:46.885  1834  4476 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-10 14:10:47.010  5818  5887 W jxcore-log: Platform android
08-10 14:10:47.010  5818  5887 W jxcore-log: 
08-10 14:10:47.010  5818  5887 W jxcore-log: Process ARCH arm
08-10 14:10:47.010  5818  5887 W jxcore-log: 
,08-10 14:10:47.474  5818  5887 I jxcore-log: JXcore Cordova bridge is ready!
08-10 14:10:47.474  5818  5887 I jxcore-log: 
,08-10 14:10:47.476  5818  5887 W jxcore-log: JXcore engine is started
08-10 14:10:47.482  5818  5881 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-10 14:10:47.484  5818  5818 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-10 14:10:47.501  1025  1041 V SIM_STK : Menu title from STK is T-Mobile
,08-10 14:10:47.541  1025  1903 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5949 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 14:10:47.618  5949  5949 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-10 14:10:47.618  5949  5949 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-10 14:10:47.678  1025  1921 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5974 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-10 14:10:47.679  1025  1921 I ActivityManager: Killing 5244:com.google.android.gm/u0a64 (adj 15): empty #17
,08-10 14:10:47.838  1025  1765 W libprocessgroup: failed to open /acct/uid_10064/pid_5244/cgroup.procs: No such file or directory
,08-10 14:10:47.927  5974  5974 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-10 14:10:47.951  5974  5974 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-10 14:10:47.956  1025  1568 I ActivityManager: Killing 5022:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-10 14:10:47.967  4993  4993 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-10 14:10:47.967  4993  4993 W System.err: android.os.DeadObjectException
08-10 14:10:47.967  4993  4993 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 14:10:47.967  4993  4993 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 14:10:47.967  4993  4993 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-10 14:10:47.968  4993  4993 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-10 14:10:47.968  4993  4993 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-10 14:10:47.968  4993  4993 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-10 14:10:47.968  4993  4993 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 14:10:47.968  4993  4993 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 14:10:47.968  4993  4993 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 14:10:47.968  4993  4993 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 14:10:47.968  4993  4993 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:10:47.968  4993  4993 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 14:10:47.968  4993  4993 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 14:10:47.968  4993  4993 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 14:10:47.968  4993  4993 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-10 14:10:47.968  4993  4993 W System.err: android.os.DeadObjectException
08-10 14:10:47.969  4993  4993 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 14:10:47.969  4993  4993 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 14:10:47.969  4993  4993 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-10 14:10:47.969  4993  4993 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-10 14:10:47.969  4993  4993 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-10 14:10:47.969  4993  4993 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-10 14:10:47.969  4993  4993 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 14:10:47.969  4993  4993 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 14:10:47.969  4993  4993 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 14:10:47.969  4993  4993 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 14:10:47.969  4993  4993 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:10:47.969  4993  4993 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 14:10:47.969  4993  4993 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 14:10:47.969  4993  4993 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 14:10:47.969  4993  4993 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-10 14:10:47.970  4993  4993 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-10 14:10:48.221  1025  1765 W libprocessgroup: failed to open /acct/uid_1000/pid_5022/cgroup.procs: No such file or directory
08-10 14:10:48.222  1025  1765 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-10 14:10:48.239  4993  4993 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-10 14:10:48.242  4993  4993 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-10 14:10:48.295  1025  1963 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=5996 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 14:10:48.296  4993  4993 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-10 14:10:48.443  1025  2083 I art     : Explicit concurrent mark sweep GC freed 23234(1154KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 42MB/64MB, paused 1.732ms total 111.100ms
,08-10 14:10:48.464  5996  5996 D UEI.SmartControl: Quickset Services start...
08-10 14:10:48.466  5996  5996 I UEI.SmartControl: Manufacture = LGE
08-10 14:10:48.466  5996  5996 D UEI.SmartControl: Id = LGNevo
08-10 14:10:48.467  5996  5996 D UEI.SmartControl: File observer start...
08-10 14:10:48.467  5996  5996 E UEI.SmartControl: IR Port is disabled: false
08-10 14:10:48.467  5996  5996 D UEI.SmartControl: Starting file observer...
08-10 14:10:48.467  5996  5996 D UEI.SmartControl: Extracting JNI libs...
08-10 14:10:48.467  5996  5996 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-10 14:10:48.523  5996  5996 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-10 14:10:48.523  5996  5996 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-10 14:10:48.523  5996  5996 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-10 14:10:48.547  5996  5996 I UEI.SmartControl: --- Selecting new region: 6
08-10 14:10:48.548  5996  5996 I UEI.SmartControl: Model = LG-D855
08-10 14:10:48.549  5996  5996 D UEI.SmartControl: QS Service created
,08-10 14:10:48.559  5996  5996 I UEI.SmartControl: Service initServices...
08-10 14:10:48.562  5996  5996 D UEI.SmartControl: QS start get config
,08-10 14:10:48.602  5996  5996 D UEI.SmartControl: Loading JNI Libs...
,08-10 14:10:48.890  5996  5996 I UEI.SmartControl: Supports setup maps: true
,08-10 14:10:48.893  5996  5996 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 14:10:48.893  5996  5996 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-10 14:10:48.893  5996  5996 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 14:10:48.893  5996  5996 I UEI.SmartControl: ### init IR Blaster...
08-10 14:10:48.898  5996  5996 D serial_port: Configuring serial port
08-10 14:10:48.901  5996  5996 E UEI.SmartControl: UEIBLaster setting for 616
08-10 14:10:48.901  5996  5996 I UEI.SmartControl: Setting serial record hearder size = 2
,08-10 14:10:48.901  5996  5996 I UEI.SmartControl: configuring settings for MAXQ616
08-10 14:10:48.901  5996  5996 I UEI.SmartControl: Get version...
08-10 14:10:48.917  5996  6022 D UEI.SmartControl: serial port data available: 21
,08-10 14:10:48.944  5996  5996 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-10 14:10:48.944  5996  5996 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 14:10:48.944  5996  5996 I UEI.SmartControl: QS saving settings...
08-10 14:10:48.944  5996  5996 D UEI.SmartControl: IR Blaster version: 25672567
,08-10 14:10:48.960  5996  6022 D UEI.SmartControl: serial port data available: 4
,08-10 14:10:48.995  5996  6026 I UEI.SmartControl: Device manager: loading config....
,08-10 14:10:48.997  5996  6026 D UEI.SmartControl: ----------- loading internal config...
08-10 14:10:49.001  5996  5996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-10 14:10:49.006  5996  5996 E UEI.SmartControl: Services init done
08-10 14:10:49.006  5996  5996 D UEI.SmartControl: QS Service init finished
08-10 14:10:49.008  5996  5996 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 14:10:49.008  5996  5996 D UEI.SmartControl: QS Service version code: 201091
08-10 14:10:49.009  5996  5996 D UEI.SmartControl: Service requested: Control
,08-10 14:10:49.016  5996  6026 E UEI.SmartControl: Loading SETTINGS...
08-10 14:10:49.020  5996  5996 D UEI.SmartControl: Request IControl service: devices are loaded...
08-10 14:10:49.021  1025  2064 I ActivityManager: Killing 4993:com.lge.qremote/u0a112 (adj 15): empty #17
08-10 14:10:49.026  5996  6026 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-10 14:10:49.034  5996  6025 I UEI.SmartControl: Notify AllClients services are ready: 0
08-10 14:10:49.034  5996  6025 D UEI.SmartControl: -----service ready thread exits
08-10 14:10:49.188  5996  5996 D UEI.SmartControl: Internal service binding...
08-10 14:10:49.188  1025  1040 W libprocessgroup: failed to open /acct/uid_10112/pid_4993/cgroup.procs: No such file or directory
,08-10 14:10:49.691  2190  2190 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19989
,08-10 14:10:50.489  5791  5791 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-10 14:10:50.492  1025  2106 I ActivityManager: Killing 4928:com.android.calendar/u0a13 (adj 15): empty #17
08-10 14:10:50.558  1025  1568 W libprocessgroup: failed to open /acct/uid_10013/pid_4928/cgroup.procs: No such file or directory
,08-10 14:10:51.453  5791  5888 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-10 14:10:52.463  1025  1963 I ActivityManager: Killing 5284:com.google.android.talk/u0a72 (adj 15): empty #17
,08-10 14:10:52.570  1025  1041 W libprocessgroup: failed to open /acct/uid_10072/pid_5284/cgroup.procs: No such file or directory
,08-10 14:10:52.621  1834  5587 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-10 14:10:52.624   323  6043 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-10 14:10:52.625  1025  1085 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 14:10:52.625  1834  5587 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-10 14:10:52.627  1834  1834 I ConfigFetchService: fetch service done; releasing wakelock
08-10 14:10:52.628  1834  1834 I ConfigFetchService: stopping self
08-10 14:10:52.631  2232  2232 I ConfigService: onDestroy
08-10 14:10:53.979  5996  6023 D serial_port: close(fd = 25)
,08-10 14:10:53.986  5996  6023 I UEI.SmartControl: Serial port is closed.
,08-10 14:10:54.001  5996  6027 D UEI.SmartControl: Internal timer expired: 1
,08-10 14:10:54.007  5996  6027 D UEI.SmartControl: unbind internal service
08-10 14:10:54.015  5996  5996 D UEI.SmartControl: Service.onUnbind: IControl
,08-10 14:10:54.027  5996  5996 D UEI.SmartControl: Service.onDestroy
08-10 14:10:54.027  5996  5996 D UEI.SmartControl: Lock is in USE false
08-10 14:10:54.027  5996  5996 D UEI.SmartControl: unbind internal service
08-10 14:10:54.027  5996  5996 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3eaafd09
08-10 14:10:54.027  5996  5996 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-10 14:10:54.027  5996  5996 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-10 14:10:54.027  5996  5996 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-10 14:10:54.028  5996  5996 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-10 14:10:54.028  5996  5996 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-10 14:10:54.028  5996  5996 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-10 14:10:54.028  5996  5996 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-10 14:10:54.028  5996  5996 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-10 14:10:54.028  5996  5996 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:10:54.028  5996  5996 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 14:10:54.028  5996  5996 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 14:10:54.028  5996  5996 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:10:54.028  5996  5996 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 14:10:54.028  5996  5996 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 14:10:54.028  5996  5996 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 14:10:54.028  5996  5996 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3eaafd09
08-10 14:10:54.028  5996  5996 I UEI.SmartControl: Serial port is closed.
08-10 14:10:54.028  5996  5996 I UEI.SmartControl: Serial port is closed.
08-10 14:10:54.028  5996  5996 D UEI.SmartControl: Blaster closed
08-10 14:10:54.028  5996  5996 D UEI.SmartControl: Shut down QS...
08-10 14:10:54.028  5996  5996 D UEI.SmartControl: Stopping QS lib
08-10 14:10:54.029  5996  5996 D UEI.SmartControl: QS lib stop result = true
08-10 14:10:54.029  5996  5996 D UEI.SmartControl: Stopped QS lib
,08-10 14:10:54.032  5996  5996 D UEI.SmartControl: Stopped file observer...
,08-10 14:10:54.033  5996  5996 D UEI.SmartControl: QS shutdown complete
,08-10 14:10:57.661  1025  1083 I ActivityManager: Waited long enough for: ServiceRecord{1d5b9d9f u0 com.google.android.gms/.wearable.service.WearableService}
,08-10 14:11:00.046  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 14:11:00.046  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 14:11:00.046  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:11:00.047  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:11:00.051  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:11:00.051  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:11:00.051  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:11:00.052  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:11:04.044  1025  1369 D PowerManagerServiceEx: acquireWakeLockInternal: lock=705746151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,08-10 14:11:04.064  1025  1369 V AlarmManager: RTC_WAKEUP set : Alarm{18ab3821 type 0 when 1470831059687 com.android.vending} when 1470831059687
,08-10 14:11:04.114  2629  2629 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 14:11:04.135  1025  1025 D PowerManagerServiceEx: releaseWakeLockInternal: lock=705746151 [*alarm*], flags=0x0
,08-10 14:11:04.173  4225  6062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-10 14:11:04.208  1025  1041 V SIM_STK : Menu title from STK is T-Mobile
,08-10 14:11:04.445  5730  5730 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-10 14:11:08.398  5818  5887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 14:11:08.398  5818  5887 I jxcore-log: 
08-10 14:11:08.402  5818  5887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 14:11:08.402  5818  5887 I jxcore-log: 
,08-10 14:11:08.407  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:08.407  5818  5887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:11:08.407  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:08.407  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:11:08.407  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:11:08.407  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:11:08.407  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:08.407  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:08.407  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:08.408  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:08.408  5818  5887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:08.412  5818  5887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 14:11:08.412  5818  5887 I jxcore-log: 
08-10 14:11:08.415  5818  5887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 14:11:08.415  5818  5887 I jxcore-log: 
08-10 14:11:09.115  5818  5887 D ExecuteNativeTests: Running unit tests
,08-10 14:11:09.252  5818  5887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 14:11:09.252  5818  5887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 added. We now have 2 listener(s)
,08-10 14:11:09.254  1025  2106 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:09.257  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 14:11:09.257  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 14:11:09.257  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 14:11:09.257  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 14:11:09.257  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 added. We now have 2 listener(s)
08-10 14:11:09.257  5818  5887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:11:09.258  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 14:11:09.259  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:11:09.260  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:09.260  5818  5887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:11:09.260  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:09.260  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:11:09.260  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:11:09.260  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:11:09.260  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:09.260  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:09.260  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:09.260  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:09.260  5818  5887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:09.261  5818  5887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 14:11:09.265  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 14:11:09.268  5818  5887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 14:11:09.268  5818  5887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 14:11:09.275  5818  5887 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-10 14:11:09.277  5818  5887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 14:11:09.277  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 14:11:09.277  5818  5887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 14:11:09.277  5818  5887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 14:11:09.280  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 14:11:09.284  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.284  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.285  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.285  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.285  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 14:11:09.285  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 14:11:09.285  5818  5887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 removed from the list
08-10 14:11:09.286  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.286  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 removed from the list
08-10 14:11:09.286  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.286  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.287  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.287  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.287  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.288  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.288  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.288  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.290  5818  5887 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-10 14:11:09.290  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.290  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.290  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.291  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.291  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.291  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.291  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.291  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.291  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not i,n the list
08-10 14:11:09.291  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.291  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.291  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.291  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.291  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 14:11:09.295  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.295  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.295  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.295  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 14:11:09.304  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 14:11:09.305  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 14:11:09.305  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 14:11:09.305  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 14:11:09.305  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 14:11:09.305  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 14:11:09.305  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 14:11:09.305  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 14:11:09.305  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 14:11:09.305  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 14:11:09.305  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.305  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.305  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 14:11:09.310  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.310  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.310  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.310  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.310  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.311  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.311  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.312  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.312  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.312  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.312  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.313  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.313  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.313  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.313  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.314  5818  5887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 14:11:09.315  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:11:09.316  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:09.316  5818  5887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:11:09.316  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:09.316  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:11:09.316  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:11:09.316  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:11:09.316  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:09.316  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:09.316  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:09.316  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:09.316  5818  5887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:09.316  5818  5887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 14:11:09.317  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity:, NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 14:11:09.317  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 14:11:09.317  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 14:11:09.317  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:11:09.317  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 14:11:09.320  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,08-10 14:11:09.323  5818  5887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 14:11:09.325  5818  5818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 14:11:09.326  5818  5887 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 14:11:09.326  5818  5887 I io.jxcore.node.ConnectionHelper: start: OK
08-10 14:11:09.328  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:09.329  5818  5887 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-10 14:11:09.330  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.330  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.330  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 14:11:09.330  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.330  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 14:11:09.330  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 14:11:09.330  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 14:11:09.330  5818  5887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 14:11:09.330  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 14:11:09.332  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 14:11:09.334  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 14:11:09.335  5818  5887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:11:09.336  5818  5818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:11:09.336  5818  5818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:11:09.336  5818  5818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:11:09.337  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.337  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.337  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 14:11:09.337  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.337  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.337  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.337  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.337  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.338  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.338  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.338  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.338  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.338  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.338  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.340  5818  5887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 14:11:09.341  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:11:09.342  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:09.342  5818  5887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:11:09.342  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:09.342  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:11:09.342  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:11:09.342  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:11:09.342  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:09.342  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:09.342  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - activ,e network type is Wi-Fi: false
08-10 14:11:09.342  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:09.342  5818  5887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:09.342  5818  5887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 14:11:09.342  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 14:11:09.342  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 14:11:09.342  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 14:11:09.342  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:11:09.342  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 14:11:09.344  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,08-10 14:11:09.347  5818  5887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 14:11:09.349  5818  5818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 14:11:09.349  5818  5887 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 14:11:09.350  5818  5887 I io.jxcore.node.ConnectionHelper: start: OK
08-10 14:11:09.350  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.350  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.350  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 14:11:09.350  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.350  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 14:11:09.350  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 14:11:09.350  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 14:11:09.350  5818  5887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 14:11:09.350  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 14:11:09.350  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 14:11:09.351  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 14:11:09.351  5818  5887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:11:09.352  5818  5818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:11:09.352  5818  5818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:11:09.352  5818  5818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:11:09.353  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.353  5818  5887 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 14:11:09.353  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.353  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.353  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.354  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.354  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 14:11:09.354  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thalipr,oject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.354  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.354  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.354  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.354  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.354  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.355  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.355  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.355  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.355  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.355  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.356  5818  5887 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-10 14:11:09.356  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.356  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.357  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 14:11:09.360  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.361  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.361  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.361  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.361  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.361  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.361  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.361  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.361  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.361  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.361  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.363  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.363  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.363  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.363  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.365  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 14:11:09.365  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.365  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.365  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.366  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.366  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.366  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.366  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.366  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.366  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.366  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.366  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.366  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager,: release: 1 listener(s) left
08-10 14:11:09.366  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.366  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.367  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.367  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.367  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.367  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.368  5818  5887 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-10 14:11:09.368  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.368  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.368  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.369  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.369  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.369  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.369  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
,08-10 14:11:09.369  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.369  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.369  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.369  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.369  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.369  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 14:11:09.369  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 14:11:09.375  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.376  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.376  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.376  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.377  5818  5887 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-10 14:11:09.378  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.378  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.378  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.378  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.378  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.378  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.378  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.378  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.378  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.378  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.378  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.378  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.378  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.378  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.379  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.379  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.379  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.379  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.380  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 14:11:09.382  5818  5887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 14:11:09.382  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 14:11:09.382  5818  5887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 14:11:09.382  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerS,ettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 14:11:09.382  5818  5887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 14:11:09.383  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.383  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.383  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.389  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.389  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.389  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.389  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.389  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.389  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.390  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.390  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.390  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.390  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.390  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.392  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.392  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.392  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.392  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.393  5818  5887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 14:11:09.393  5818  5887 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 14:11:09.393  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 14:11:09.397  5818  5887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 14:11:09.397  5818  5887 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-10 14:11:09.397  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 14:11:09.397  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 14:11:09.397  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 14:11:09.397  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 14:11:09.398  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 14:11:09.406  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 14:11:09.406  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 14:11:09.406  5818  5887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 14:11:09.407  5818  5887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 14:11:09.407  5818  5887 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 14:11:09.407  5818  5887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 14:11:09.407  5818  5887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 14:11:09.407  5818  5887 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 14:11:09.407  5818  5887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 14:11:09.407  5818  5887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 14:11:09.407  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 14:11:09.408  5818  5887 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-10 14:11:09.408  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-10 14:11:09.411  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 14:11:09.411  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-10 14:11:09.412  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-10 14:11:09.412  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-10 14:11:09.412  5818  5887 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-10 14:11:09.413  5818  5887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 14:11:09.413  5818  5887 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-10 14:11:09.413  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.413  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.413  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 14:11:09.416  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.417  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.417  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.417  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-10 14:11:09.419  5818  6097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 711)
08-10 14:11:09.423  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.423  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.424  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.424  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.424  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.424  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.424  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.424  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.424  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.424  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.424  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.424  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.425  5818  5887 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-10 14:11:09.426  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.426  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.426  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.427  5818  6098 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 711
08-10 14:11:09.427  5818  6098 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 711)
08-10 14:11:09.428  5818  6098 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 711)
08-10 14:11:09.428  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.428  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.428  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.428  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.428  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.429  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.429  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.429  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.429  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.429  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.429  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.429  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.429  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.429  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.429  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.430  5818  5887 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-10 14:11:09.431  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.431  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.431  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.431  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.431  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.431  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.431  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.431  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.431  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.431  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.431  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.431  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.431  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.431  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.432  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.432  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.432  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.432  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.433  5818  5887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 14:11:09.433  5818  5887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-10 14:11:09.433  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 14:11:09.433  5818  5887 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 14:11:09.433  5818  5887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 14:11:09.433  5818  5887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 14:11:09.434  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 14:11:09.434  5818  5887 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 14:11:09.434  5818  5887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 14:11:09.434  5818  5887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 14:11:09.434  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 14:11:09.434  5818  5887 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-10 14:11:09.434  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.434  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.434  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.434  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.434  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.434  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.434  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.435  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.435  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.435  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.435  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.435  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.435  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.435  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.435  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.435  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.435  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.435  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.436  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.436  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.436  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.436  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.436  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.436  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.436  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.436  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.436  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.437  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.437  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.437  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.437  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.437  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.437  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.437  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.437  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.437  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.441  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.442  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.442  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.442  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.442  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.442  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.442  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.442  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.442  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.442  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.442  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.442  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.442  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.442  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.442  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.445  5818  5887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 14:11:09.445  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:11:09.445  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-10 14:11:09.445  5818  5887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-10 14:11:09.445  5818  5818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-10 14:11:09.445  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 14:11:09.446  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.446  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 14:11:09.446  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.446  5818  5887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-10 14:11:09.447  5818  5818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 14:11:09.447  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.447  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.447  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 14:11:09.447  5818  5887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 14:11:09.447  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 14:11:09.447  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.447  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.447  5818  5887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:11:09.448  5818  5818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:11:09.448  5818  5818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:11:09.448  5818  5818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:11:09.448  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.448  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.448  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.448  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.448  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.448  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.448  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.448  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.448  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.448  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.448  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.448  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.448  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.448  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.448  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 14:11:09.449  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.449  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.449  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.449  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.450  5818  5887 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-10 14:11:09.450  5818  5887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 14:11:09.450  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 14:11:09.452  5818  5887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 14:11:09.452  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.452  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.452  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.453  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.453  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.453  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.453  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.453  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.453  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.453  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.453  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.453  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.453  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.453  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.453  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.453  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.453  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.453  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.456  1025  2064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:09.456  1025  1040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:09.457  1025  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:09.457  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.457  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.457  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.457  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.457  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.457  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.457  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.457  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.457  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.457  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.457  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.457  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.457  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.457  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.458  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.458  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.458  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.458  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.459  5818  5887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:11:09.459  5818  5887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:11:09.459  5818  5887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:11:09.459  5818  5887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:11:09.459  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.459  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.459  5818  5887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b91ad7 not in the list
08-10 14:11:09.459  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.459  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.459  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:11:09.459  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.459  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.459  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:11:09.459  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:11:09.460  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:11:09.460  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:11:09.460  5818  5887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:11:09.460  5818  5887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c481fc4 not in the list
08-10 14:11:09.461  5818  5887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-10 14:11:09.461  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 14:11:09.462  5818  5887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 14:11:09.462  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 14:11:09.462  5818  5887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-10 14:11:09.462  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 14:11:09.464  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 14:11:09.464  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-10 14:11:09.465  5818  5887 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-10 14:11:09.465  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 14:11:09.465  5818  5887 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-10 14:11:09.465  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 14:11:09.465  5818  5887 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-10 14:11:09.465  5818  5887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-10 14:11:09.466  5818  5887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-10 14:11:09.466  5818  5887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-10 14:11:09.467  5818  5887 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-10 14:11:09.467  5818  5887 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 14:11:09.467  5818  5887 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-10 14:11:09.467  5818  5887 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-10 14:11:09.469  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 14:11:09.469  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f819e2e added. We now have 2 listener(s)
08-10 14:11:09.469  5818  5887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:11:09.471  1025  1903 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:09.471  1025  1903 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-10 14:11:09.483  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 14:11:09.483  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 14:11:09.483  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-10 14:11:09.484  1025  1087 D BluetoothManagerService: Message: 1
08-10 14:11:09.484  1025  1087 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-10 14:11:09.499  5818  6097 E BluetoothDevice: BT not enabled. Cannot get bond state
,08-10 14:11:09.500  5818  6097 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-10 14:11:09.500  5818  6097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 711)
08-10 14:11:09.535  1025  1087 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6110 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-10 14:11:09.536  1025  1964 D WifiServiceImplEx: setWifiEnabled: true pid=5818, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-10 14:11:09.537  1025  1964 D WifiService: setWifiEnabled: true pid=5818, uid=10118
08-10 14:11:09.537  1025  1964 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 14:11:09.548  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 14:11:09.548  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 14:11:09.548  1025  1025 D Ulp_jni : JNI:system_update. Event-4
,08-10 14:11:09.550  1025  1531 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-10 14:11:09.550  1025  1531 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-10 14:11:09.551  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 14:11:09.551  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3df68dcf added. We now have 3 listener(s)
08-10 14:11:09.551  5818  5887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:11:09.552  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1025] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-10 14:11:09.552  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 14:11:09.552  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:09.552  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1025] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-10 14:11:09.552  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 14:11:09.552  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:09.552  1025  1531 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-10 14:11:09.552  1025  1531 E WifiHW  : unknown target_country: EU , set to default
08-10 14:11:09.552  1025  1531 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-10 14:11:09.552  1025  1531 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-10 14:11:09.552  1025  1531 I WifiUtil: gEnableBmps=1
08-10 14:11:09.553  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 14:11:09.553  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e49a35c added. We now have 4 listener(s)
08-10 14:11:09.553  5818  5887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:11:09.555  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 14:11:09.555  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a48c665 added. We now have 5 listener(s)
08-10 14:11:09.555  5818  5887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:11:09.561  1025  2030 D WifiServiceImplEx: setWifiEnabled: true pid=5818, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 14:11:09.561  1025  2030 D WifiService: setWifiEnabled: true pid=5818, uid=10118
08-10 14:11:09.561  1025  2030 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 14:11:09.562  1025  1709 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:09.562  1025  1709 D BluetoothManagerService: enable():  mBluetooth =null mBinding = true
08-10 14:11:09.563  1025  1087 D BluetoothManagerService: Message: 1
08-10 14:11:09.563  1025  1087 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-10 14:11:09.564  1025  1537 D WifiController: Mismatch in the state 1
08-10 14:11:09.565  5818  5887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:11:09.565  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:09.566  5818  5887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:11:09.566  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:09.566  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:11:09.566  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:11:09.566  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:11:09.566  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:09.566  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:09.566  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:09.566  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:09.566  5818  5887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:09.566  5818  5887 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 14:11:09.607  6110  6110 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-10 14:11:09.607  6110  6110 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 14:11:09.608  6110  6110 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-10 14:11:09.609  6110  6110 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-10 14:11:09.645  6110  6110 D BluetoothAdapterApp: Loading JNI Library
,08-10 14:11:09.690  6110  6110 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2250d35b Instance Count = 1
08-10 14:11:09.691  2190  2190 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-10 14:11:09.694  2190  2190 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
08-10 14:11:09.701  6110  6110 D BluetoothAdapterApp: onCreate
,08-10 14:11:09.735  6110  6110 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-10 14:11:09.735  6110  6110 D ProfileConfigQcom: Adding HeadsetService
08-10 14:11:09.735  6110  6110 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-10 14:11:09.735  6110  6110 D ProfileConfigQcom: Adding A2dpService
,08-10 14:11:09.735  6110  6110 D ProfileConfigQcom: [BTUI] HidService is supported
08-10 14:11:09.735  6110  6110 D ProfileConfigQcom: Adding HidService
,08-10 14:11:09.736  6110  6110 D ProfileConfigQcom: [BTUI] HealthService is supported
08-10 14:11:09.736  6110  6110 D ProfileConfigQcom: Adding HealthService
08-10 14:11:09.736  6110  6110 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-10 14:11:09.738  6110  6110 D ProfileConfigQcom: [BTUI] PanService is supported
08-10 14:11:09.738  6110  6110 D ProfileConfigQcom: Adding PanService
08-10 14:11:09.739  6110  6110 D ProfileConfigQcom: [BTUI] GattService is supported
08-10 14:11:09.739  6110  6110 D ProfileConfigQcom: Adding GattService
08-10 14:11:09.739  6110  6110 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-10 14:11:09.740  6110  6110 D ProfileConfigQcom: Adding BluetoothMapService
,08-10 14:11:09.740  6110  6110 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-10 14:11:09.753   323   868 D SoftapController: Softap fwReload - Ok
,08-10 14:11:09.756  1025  1087 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-10 14:11:09.758  1025  1087 D Tethering: InitialState.processMessage what=4
08-10 14:11:09.759   323   868 D CommandListener: Setting iface cfg
08-10 14:11:09.760   323   868 D CommandListener: Trying to bring down wlan0
08-10 14:11:09.761   323   868 D CommandListener: Clearing all IP addresses on wlan0
08-10 14:11:09.767  1025  1531 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-10 14:11:09.767   323  6138 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-10 14:11:09.767  1025  1085 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-10 14:11:09.772  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 14:11:09.772  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-10 14:11:09.772  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 14:11:09.772  6139  6139 W wpa_supplicant: type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:09.772  6139  6139 W wpa_supplicant: type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:09.793  6110  6110 D BluetoothAdapterState: make
,08-10 14:11:09.800  6110  6110 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-10 14:11:09.800  6110  6110 I bluedroid-qcom: init
08-10 14:11:09.801  6110  6140 I BluetoothAdapterState: Entering OffState
08-10 14:11:09.802  6110  6110 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-10 14:11:09.802  6110  6110 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-10 14:11:09.802  6110  6110 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 14:11:09.802  6110  6110 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 14:11:09.802  6110  6110 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-10 14:11:09.803  6139  6139 I wpa_supplicant: Successfully initialized wpa_supplicant
08-10 14:11:09.804  6110  6110 I bluedroid-qcom: get_profile_interface socket
08-10 14:11:09.804  6110  6144 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-10 14:11:09.804  6110  6110 I bluedroid-qcom: get_profile_interface map_client
08-10 14:11:09.792  6143  6143 W bdaddr_loader: type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:09.792  6143  6143 W bdaddr_loader: type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 14:11:09.810  6110  6144 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-10 14:11:09.811  6143  6143 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-10 14:11:09.811  6143  6143 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-10 14:11:09.812  6143  6143 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-10 14:11:09.816  6143  6143 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-10 14:11:09.821  1025  1083 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6145 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 14:11:09.822  1025  1087 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 14:11:09.822  1025  1087 D BluetoothManagerService: Message: 20
08-10 14:11:09.822  1025  1087 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@212d520b:true
08-10 14:11:09.823  6143  6143 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-10 14:11:09.823  6143  6143 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-10 14:11:09.823  1025  1531 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-10 14:11:09.823  1025  1531 D WifiMonitor: connecting to supplicant
08-10 14:11:09.825  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-10 14:11:09.826  6110  6144 D BluetoothAdapterProperties: Name is: G3
08-10 14:11:09.827  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-10 14:11:09.828  1025  1025 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-10 14:11:09.829  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:09.830  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:09.830  1025  1087 D BluetoothManagerService: Message: 40
08-10 14:11:09.830  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-10 14:11:09.831  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:09.831  1025  1025 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 14:11:09.831  1025  1025 D BluetoothManagerService: Stored Bluetooth name: G3
,08-10 14:11:09.838  6110  6127 I bluedroid-qcom: config_hci_snoop_log
08-10 14:11:09.839  1025  1087 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-10 14:11:09.839  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
08-10 14:11:09.841   363   363 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 20.200ms
08-10 14:11:09.842  6139  6139 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-10 14:11:09.843  6139  6139 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-10 14:11:09.852  6110  6129 V LGMDMManagerInternal: Create singleton instance
,08-10 14:11:09.859   363   363 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 354us total 16.676ms
08-10 14:11:09.875   363   363 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 281us total 14.298ms
,08-10 14:11:09.887  6145  6145 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 14:11:09.887  6145  6145 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-10 14:11:09.888  6145  6145 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 14:11:09.888  6145  6145 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-10 14:11:09.889  6145  6145 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 14:11:09.889  6145  6145 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-10 14:11:09.927  6139  6139 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-10 14:11:09.945  6110  6140 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-10 14:11:09.945  6110  6140 D BluetoothAdapterProperties: Setting state to 11
08-10 14:11:09.946  6110  6140 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-10 14:11:09.947  1025  1087 D BluetoothManagerService: Message: 60
08-10 14:11:09.948  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-10 14:11:09.948  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-10 14:11:09.948  5818  5818 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-10 14:11:09.949  6110  6140 I LGBluetoothServiceJni: classInitNative: succeeds
08-10 14:11:09.951  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:09.952  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 14:11:09.958  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:11:09.965  6110  6140 D BluetoothBondStateMachine: make
08-10 14:11:09.966  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:11:09.968  6110  6162 I BluetoothBondStateMachine: StableState(): Entering Off State
08-10 14:11:09.968  6110  6140 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:09.968  6110  6140 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-10 14:11:09.968  6110  6140 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:09.968  6110  6140 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-10 14:11:09.969  6110  6140 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-10 14:11:09.972  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 14:11:09.972  6145  6145 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-10 14:11:09.972  6145  6145 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 14:11:09.973  6145  6145 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 14:11:09.975  6110  6140 E BluetoothAdapterService: File transfer profiles supported!!
08-10 14:11:09.975  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 14:11:09.983  6110  6140 E BluetoothAdapterService: File transfer profiles supported!!
08-10 14:11:09.984  1025  1025 D BluetoothHeadset: Proxy object connected
08-10 14:11:09.985  1869  1869 D BluetoothHeadset: Proxy object connected
,08-10 14:11:09.987  6110  6110 D HeadsetService: Received start request. Starting profile...
08-10 14:11:09.987  6110  6110 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 14:11:09.987  6139  6139 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-10 14:11:09.987  6110  6110 D LGBluetoothHfpAdapter: Version 1.6
08-10 14:11:09.988  1869  1869 D BluetoothHeadset: Proxy object connected
08-10 14:11:09.988  1869  1869 D BluetoothHeadset: Proxy object connected
08-10 14:11:09.990  6110  6140 E BluetoothAdapterService: File transfer profiles supported!!
08-10 14:11:09.990  6110  6110 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 14:11:09.991  6110  6110 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 14:11:09.992  6110  6110 D HeadsetStateMachine: make
08-10 14:11:09.992  6139  6139 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-10 14:11:09.993  6139  6139 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-10 14:11:09.993  6110  6140 E BluetoothAdapterService: File transfer profiles supported!!
08-10 14:11:09.996  6110  6140 E BluetoothAdapterService: File transfer profiles supported!!
08-10 14:11:09.996  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-10 14:11:09.997  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,08-10 14:11:09.997  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-10 14:11:09.998  1025  1531 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-10 14:11:09.999  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
08-10 14:11:09.999  1025  6165 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-10 14:11:09.999  1025  6165 D WifiMonitor: Dropping event because (p2p0) is stopped
08-10 14:11:09.999  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-10 14:11:09.999  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:09.999  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-10 14:11:09.999  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:10.000  1025  6165 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-10 14:11:10.000  1025  6165 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-10 14:11:10.000  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:10.000  6110  6140 E BluetoothAdapterService: File transfer profiles supported!!
08-10 14:11:10.000  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:10.001  1025  1531 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-10 14:11:10.001  1025  1531 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-10 14:11:10.002  6145  6145 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 14:11:10.002  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-10 14:11:10.002  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 14:11:10.002  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 14:11:10.002  6145  6145 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 14:11:10.002  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-10 14:11:10.003  6145  6145 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 14:11:10.003  6110  6140 E BluetoothAdapterService: File transfer profiles supported!!
08-10 14:11:10.004  1025  1040 I ActivityManager: Killing 4654:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-10 14:11:10.005  1025  1531 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-10 14:11:10.005  1025  1531 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-10 14:11:10.006  1025  1531 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-10 14:11:10.029  6110  6110 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 14:11:10.029  6110  6110 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 14:11:10.048  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 14:11:10.048  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-10 14:11:10.048  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-10 14:11:10.049  1025  1765 W libprocessgroup: failed to open /acct/uid_10014/pid_4654/cgroup.procs: No such file or directory
,08-10 14:11:10.051  6110  6110 D HeadsetStateMachine: max_hf_connections = 1
08-10 14:11:10.051  6110  6110 I bluedroid-qcom: get_profile_interface handsfree
08-10 14:11:10.051  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.052  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.052  1025  1531 D WifiNative-wlan0: doBoolean: SET update_config 1
08-10 14:11:10.053  1025  1531 D WifiNative-wlan0: SET update_config 1: returned true
08-10 14:11:10.053  1025  1531 D WifiConfigStore: Loading config and enabling all networks 
08-10 14:11:10.053  1025  1531 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-10 14:11:10.053  6110  6110 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-10 14:11:10.054   327  1376 V AudioPolicyService: registerClient() client 0xb14b5480, uid 1002
08-10 14:11:10.054   327  1375 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-10 14:11:10.054   327  1375 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 14:11:10.054   327  1375 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 14:11:10.054  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:10.054  6110  6110 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-10 14:11:10.055   327  1377 V AudioFlinger: registerClient() client 0xb14330a0, pid 6110
08-10 14:11:10.055   327  1371 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:10.055  6110  6110 V ToneGenerator: Create Track: 0xb4928a80
08-10 14:11:10.056  6110  6110 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-10 14:11:10.055   327  1371 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 14:11:10.056  6110  6110 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-10 14:11:10.056  1025  2099 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:10.056  1025  2099 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 14:11:10.056   327  1375 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 14:11:10.056   327  1375 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-10 14:11:10.056   327  1375 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 14:11:10.056   327  1375 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 14:11:10.056  1025  1531 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-10 14:11:10.056  6110  6110 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-10 14:11:10.056  2190  2213 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:10.056  2190  2213 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 14:11:10.056  3108  3124 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:10.056  3108  3124 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 14:11:10.056  1869  2430 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:10.057  1869  2430 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 14:11:10.058  6110  6127 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:10.058  6110  6127 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-10 14:11:10.058  1596  1931 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:10.058  1596  1931 V AudioSystem: ioConfigChanged() opening already existing ,output! 4
08-10 14:11:10.059   327  1370 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:10.059   327  1370 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 14:11:10.059  1965  1965 D WfdService: Waiting for WifiP2p enabling
08-10 14:11:10.059  2190  2212 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:10.059  2190  2212 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 14:11:10.060  1869  3166 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:10.060  1869  3166 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 14:11:10.060  3108  3123 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:10.060  3108  3123 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 14:11:10.060  1025  1568 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:10.060  1025  1568 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 14:11:10.060  1596  4200 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:10.060  1596  4200 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 14:11:10.060  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-10 14:11:10.061   327   327 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 14:11:10.061  6110  6129 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:10.061   327  1376 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 14:11:10.062  6110  6129 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-10 14:11:10.062   327  1376 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-10 14:11:10.062   327  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 14:11:10.062   327  1376 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 14:11:10.062  6110  6110 V AudioSystem: getLatency() output 2, latency 50
08-10 14:11:10.063  6110  6110 V AudioSystem: getFrameCount() output 2, frameCount 960
08-10 14:11:10.063  6110  6110 V AudioTrack: createTrack_l() output 2 afLatency 50
08-10 14:11:10.063  1025  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-10 14:11:10.063   327  1377 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 14:11:10.063   327  1377 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 14:11:10.063   327  1377 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 14:11:10.064   327  1377 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 14:11:10.064   327  1377 V AudioFlinger: createTrack() lSessionId: 21
08-10 14:11:10.065  5818  5818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:10.065  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:10.065  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:10.065  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:11:10.065  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:10.065  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:11:10.065  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:10.065  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:10.065  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:10.065  6110  6110 V AudioTrack: AUDIO_OUTPUT_FLAG_,FAST successful; frameCount 480
08-10 14:11:10.066   327  1375 V AudioFlinger: acquiring 21 from 6110, for 6110
08-10 14:11:10.066   327  1375 V AudioFlinger:  added new entry for 21
08-10 14:11:10.066  5818  5818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:10.066  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:10.066  6110  6110 V ToneGenerator: ToneGenerator INIT OK, time: 133280
08-10 14:11:10.067  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:10.068  6110  6164 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-10 14:11:10.068  6110  6164 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 14:11:10.068  6110  6164 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 14:11:10.068  6110  6164 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-10 14:11:10.069  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:10.071  5818  5818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:10.071  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:10.071  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:10.071  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:11:10.071  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:10.071  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:11:10.071  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:10.071  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:10.071  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:10.071   327   327 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6110
08-10 14:11:10.072   327   327 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-10 14:11:10.072   327   327 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-10 14:11:10.072   327   327 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-10 14:11:10.072   327   327 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-10 14:11:10.072   327   327 V voice   : voice_set_parameters: exit with code(0)
08-10 14:11:10.072   327   327 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-10 14:11:10.072   327   327 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-10 14:11:10.072   327   327 V msm8974_platform: platform_set_parameters: exit with code(0)
08-10 14:11:10.072   327   327 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-10 14:11:10.072   327   327 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-10 14:11:10.072   327   327 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-10 14:11:10.073  5818  5818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:10.073  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:10.074  6110  6164 V ToneGenerator: ToneGenerator destructor
08-10 14:11:10.074  6110  6164 V ToneGenerator: stopTone
08-10 14:11:10.074  6110  6164 V ToneGenerator: Delete Track: 0xb4928a80
08-10 14:11:10.074  1025  1025 D BluetoothA2dp: Proxy object connected
08-10 14:11:10.074  6110  6110 D A2dpService: Received start request. Starting profile...
08-10 14:11:10.075  6110  6164 V AudioTrack: ~AudioTrack, releasing session id from 6110 on behalf of 6110
08-10 14:11:10.075   327  1375 V AudioFlinger: releasing 21 from 6110 for 6110
08-10 14:11:10.075   327  1375 V AudioFlinger:  decremented refcount to 0
08-10 14:11:10.075   327  1375 V AudioFlinger: purging stale effects
08-10 14:11:10.075   327  1375 V AudioPolicyService: AudioCommandThread() adding release output 2
08-10 14:11:10.075  6110  6110 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 14:11:10.075   327  1375 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-10 14:11:10.075   327  1251 V AudioPolicyService: AudioCommandThread() waking up
08-10 14:11:10.075   327  1251 V AudioPolicyService: AudioCommandThread() processing release output 2
08-10 14:11:10.075   327  1251 V AudioPolicyManager: releaseOutput() 2
08-10 14:11:10.075   327  1251 V AudioPolicyService: AudioCommandThread() going to sleep
08-10 14:11:10.076   327  1375 V AudioFlinger: PlaybackThread::Track destructor
08-10 14:11:10.076   327  1375 V AudioFlinger: removeClient_l() pid 6110, calling pid 327
08-10 14:11:10.076  6110  6110 V Avrcp   : make
08-10 14:11:10.077  6110  6110 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-10 14:11:10.077  6110  6110 I bluedroid-qcom: get_profile_interface avrcp
08-10 14:11:10.080  1025  1531 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-10 14:11:10.081  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 14:11:10.081  6145  6145 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 14:11:10.081  6145  6145 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 14:11:10.081  6145  6145 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 14:11:10.082  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 14:11:10.082  6145  6145 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 14:11:10.082  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 14:11:10.082  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 14:11:10.082  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 14:11:10.082  6145  6145 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 14:11:10.083  6145  6145 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 14:11:10.087  6110  6140 V LGMDMManager: Create singleton instance
08-10 14:11:10.090  1025  1531 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-10 14:11:10.090  1025  1531 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-10 14:11:10.091  6110  6140 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-10 14:11:10.092  6110  6110 V AudioManager: registerRemoteController: size of Media player list: 0
08-10 14:11:10.099  6110  6110 E AudioManager: No RCC entry present to update
08-10 14:11:10.099  6110  6110 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-10 14:11:10.102  6110  6110 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-10 14:11:10.105  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-10 14:11:10.105  6110  6110 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-10 14:11:10.124  1025  1040 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6169 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-10 14:11:10.127  1025  1531 D WifiStateMachine: enableVerboseLogging : level 2
08-10 14:11:10.127  1025  1531 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-10 14:11:10.128  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-10 14:11:10.129  1025  1531 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-10 14:11:10.129  1025  1531 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-10 14:11:10.130  1025  1531 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-10 14:11:10.131  1025  1531 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-10 14:11:10.132  1025  1531 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-10 14:11:10.132  1025  1531 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-10 14:11:10.133  1025  1531 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-10 14:11:10.133  1025  1531 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-10 14:11:10.133  1025  1531 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-10 14:11:10.134  1025  1531 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-10 14:11:10.134  1025  1531 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-10 14:11:10.135  1025  1531 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-10 14:11:10.135  1025  1531 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-10 14:11:10.188  1025  1531 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 14:11:10.188  1025  1531 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-10 14:11:10.188  1965  1965 D WfdsService: Supplicant Connection state is changed : true
,08-10 14:11:10.189  1965  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-10 14:11:10.189  1965  2345 D WfdsService: Set the WFDS Monitor: true
08-10 14:11:10.190  1025  1531 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-10 14:11:10.191  1025  1531 D WifiNative-HAL: Setting external_sim to 1
08-10 14:11:10.191  1025  1531 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-10 14:11:10.192  1025  1531 D WifiNative-wlan0: SET external_sim 1: returned true
08-10 14:11:10.192  1025  1531 I WifiNative-HAL: startHal
08-10 14:11:10.192  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x987e78dc
08-10 14:11:10.192  1025  1531 E WifiHAL : Could not connect handle
08-10 14:11:10.192  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401e3e
08-10 14:11:10.192  1025  1531 I WifiNative-HAL: Could not start hal
08-10 14:11:10.192  1025  1531 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 14:11:10.193  1025  1531 I WifiNative-HAL: startHal
08-10 14:11:10.193  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x987e785c
08-10 14:11:10.193  1025  1531 E WifiHAL : Could not connect handle
08-10 14:11:10.193  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401e36
08-10 14:11:10.193  1025  1531 I WifiNative-HAL: Could not start hal
08-10 14:11:10.193  1025  1531 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-10 14:11:10.194  1025  1531 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-10 14:11:10.194  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-10 14:11:10.194  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-10 14:11:10.195  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-10 14:11:10.197  1965  2345 D WfdsMonitor: WfdsMonitorThread create
08-10 14:11:10.197  1965  2345 D WfdsMonitor: WFDS Monitor is created and started
08-10 14:11:10.197  1965  2345 D WfdsService: WiFi: Supplicant connection re-established
08-10 14:11:10.200  1965  6186 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-10 14:11:10.201  1965  6186 E CtrlSupplicant: Succeed to open control connection
08-10 14:11:10.201  1965  6186 E CtrlSupplicant: Succeed to open monitor connection
08-10 14:11:10.202  1965  6186 D WfdsMonitor: Supplicant connection established
08-10 14:11:10.203  1965  2345 D WfdsService: Connected to the supplicant for wfds
,08-10 14:11:10.214  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 14:11:10.215  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 14:11:10.215  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 14:11:10.215  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-10 14:11:10.215  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-10 14:11:10.215  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-10 14:11:10.216  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 14:11:10.216  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-10 14:11:10.216  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 14:11:10.216  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 14:11:10.216  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 14:11:10.217  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 14:11:10.217  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-10 14:11:10.217  6139  6139 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-10 14:11:10.218  1025  1025 D WifiHS20: hidePasspointNotification off =false
08-10 14:11:10.219  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-10 14:11:10.219  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 14:11:10.219  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 14:11:10.219  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.219  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 14:11:10.220  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.221  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 14:11:10.221  1025  1531 E WifiNative: : [133,420,670 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-10 14:11:10.221  1025  1531 D WifiNative-wlan0: doBoolean: RECONNECT
08-10 14:11:10.221  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:10.221  1025  1531 D WifiNative-wlan0: RECONNECT: returned true
08-10 14:11:10.221  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:10.221  1025  1531 D WifiNative-wlan0: doString: [STATUS]
08-10 14:11:10.222  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-10 14:11:10.222  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-10 14:11:10.222  1025  1531 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 14:11:10.222  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-10 14:11:10.222  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-10 14:11:10.222  1025  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-10 14:11:10.223  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 14:11:10.223  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:10.223  1025  1531 D WifiNative-wlan0: SET ps 1: returned true
08-10 14:11:10.224  1025  1528 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.225   323   868 D CommandListener: Setting iface cfg
08-10 14:11:10.225   323   868 D CommandListener: Trying to bring up p2p0
08-10 14:11:10.226  1025  1537 D WifiService: New client listening to asynchronous messages
08-10 14:11:10.226  1025  1528 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-10 14:11:10.226  1025  1528 D LGWifiP2pService: P2pEnablingState
08-10 14:11:10.226  1025  1528 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.227  1025  1528 D LGWifiP2pService: P2p socket connection successful
08-10 14:11:10.227  1025  1528 D LGWifiP2pService: P2pEnabledState
08-10 ,14:11:10.229  1025  1528 D LGWifiP2pService: sending p2p connection changed broadcast
08-10 14:11:10.229  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-10 14:11:10.229  1965  1965 D WfdsService: WifiP2pState is changed : true
,08-10 14:11:10.232  1025  1528 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-10 14:11:10.233  1025  1528 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-10 14:11:10.233  1025  1528 D WifiNative-p2p0: doBoolean: SET device_name G3
08-10 14:11:10.233  1025  1528 D WifiNative-p2p0: SET device_name G3: returned true
08-10 14:11:10.233  1025  1528 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-10 14:11:10.233  1025  1528 D LGWifiP2pService: before postfix = G3
08-10 14:11:10.233  1025  1528 D WifiServerServiceExt: postfix byte check : 2
08-10 14:11:10.234  1025  1528 D LGWifiP2pService: after postfix = G3
08-10 14:11:10.234  1025  1528 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-10 14:11:10.234  1025  1528 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-10 14:11:10.234  1965  2345 D WfdsService: Receive the WFDS_ENABLE Method
08-10 14:11:10.235  1965  2345 D WfdsService: Set the WFDS Monitor: true
08-10 14:11:10.235  1965  2345 D WfdsService: Connected to the supplicant for wfds
08-10 14:11:10.235  1965  2345 D WfdsJNI : doCommand: WFDS_SET TRUE
08-10 14:11:10.235  6139  6139 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-10 14:11:10.236  1025  1528 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-10 14:11:10.237  1025  1528 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-10 14:11:10.237  1025  1528 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-10 14:11:10.237  1965  2345 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
08-10 14:11:10.237  6139  6139 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-10 14:11:10.237  1965  2345 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-10 14:11:10.238  1025  1528 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-10 14:11:10.238  1025  1528 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-10 14:11:10.238  1965  2345 D WfdsService: selectPreferredScanChannel [36]
08-10 14:11:10.238  1965  2345 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-10 14:11:10.239  1025  1528 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-10 14:11:10.239  1025  1528 D WifiNative-HAL: p2pGetDeviceAddress
08-10 14:11:10.240  1025  1025 D WifiScanningService: SCAN_AVAILABLE : 3
08-10 14:11:10.240  1025  1528 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-10 14:11:10.240  1025  1549 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.240  1025  1549 I WifiNative-HAL: startHal
08-10 14:11:10.240  1025  1549 E wifi    : getStaticLongField sWifiHalHandle 0x94b8799c
08-10 14:11:10.240  1025  1549 E WifiHAL : Could not connect handle
08-10 14:11:10.240  1025  1549 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401d2e
08-10 14:11:10.240  1025  1549 I WifiNative-HAL: Could not start hal
08-10 14:11:10.240  1025  1549 E WifiScanningService: could not start HAL
08-10 14:11:10.241  1025  1025 D RttService: SCAN_AVAILABLE : 3
08-10 14:11:10.241  1025  1550 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.242  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-10 14:11:10.242  1965  1965 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-10 14:11:10.242  1025  1531 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-10 14:11:10.242  1025  1531 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-10 14:11:10.243  1965  1965 D WfdsService: isConnected: false
08-10 14:11:10.243  1025  1531 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-10 14:11:10.243  1025  1531 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
08-10 14:11:10.244  1025  1531 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLI,CANT 0 0
08-10 14:11:10.244  1025  1531 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
08-10 14:11:10.244  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
08-10 14:11:10.244  1025  1531 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
08-10 14:11:10.245  1025  1531 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-10 14:11:10.245  1025  1531 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-10 14:11:10.245  1025  1531 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-10 14:11:10.246  1025  1531 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-10 14:11:10.246  1025  1528 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
,08-10 14:11:10.246  1025  1528 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-10 14:11:10.246  6139  6139 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-10 14:11:10.248  1025  1528 D WifiNative-p2p0: P2P_FLUSH: returned true
08-10 14:11:10.248  1025  1528 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-10 14:11:10.248  1025  1528 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-10 14:11:10.249  1025  1528 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-10 14:11:10.249  1025  1528 D WifiNative-p2p0:    returned OK
08-10 14:11:10.249  1025  1528 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-10 14:11:10.252  1025  1531 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-10 14:11:10.253  1025  1531 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-10 14:11:10.253  1025  1531 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-10 14:11:10.253  1025  1531 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-10 14:11:10.256  1965  1965 I WfdStateTracker: handleP2pThisDeviceChanged
08-10 14:11:10.257  1965  1965 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-10 14:11:10.257  1965  1965 D WfdsService: Update P2p Interface State: 3
,08-10 14:11:10.264  1025  2099 V SIM_STK : Menu title from STK is T-Mobile
08-10 14:11:10.264  1025  2099 V SIM_STK : Menu title from STK is T-Mobile
,08-10 14:11:10.295  1025  1999 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6192 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 14:11:10.299  6169  6190 W FormManager: Network not available. Please check & try again.
08-10 14:11:10.304  6169  6191 V FormManager: Network unavailable.
08-10 14:11:10.306  6169  6191 V FormManager: Network unavailable.
,08-10 14:11:10.319  1025  1999 I ActivityManager: Killing 2190:com.lge.music/u0a34 (adj 15): empty #17
08-10 14:11:10.320  6139  6139 E wpa_supplicant: disconnect_rssi_lvl: -100
08-10 14:11:10.321  1025  1528 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-10 14:11:10.321  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
08-10 14:11:10.321  1025  1528 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-10 14:11:10.321  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
08-10 14:11:10.321  1025  1531 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
08-10 14:11:10.321  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-10 14:11:10.322  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 14:11:10.322  6139  6139 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:10.322  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 14:11:10.322  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:10.322  1025  6165 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:10.322  1025  6165 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:10.323  6139  6139 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 14:11:10.323  6139  6139 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.323  1965  6186 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:10.323  1025  6165 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:10.323  1025  6165 E WifiMonitor: WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.323  1025  6165 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.323  1025  6165 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.323  1025  1531 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-10 14:11:10.324  6139  6139 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.324  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-10 14:11:10.324  1965  6186 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:10.324  1025  6165 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:10.324  1025  6165 E WifiMonitor: WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.324  1025  6165 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.324  1025  6165 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.324  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-10 14:11:10.324  1025  1531 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-10 14:11:10.324  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-10 14:11:10.324  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-10 14:11:10.324  6139  6139 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 14:11:10.325  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-10 14:11:10.325  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 14:11:10.325  1025  6165 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 14:11:10.325  1025  6165 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-10 14:11:10.327  1025  1531 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-10 14:11:10.327  1025  1531 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-10 14:11:10.327  1025  1531 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-10 14:11:10.328  1025  1531 D WifiNative-wlan0: doBoolean: SCAN
08-10 14:11:10.328  1025  1531 D WifiNative-wlan0: SCAN: returned false
08-10 14:11:10.328  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=133529  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 14:11:10.339   327   327 V AudioFlinger: 2190 died, releasing its sessions
08-10 14:11:10.339   327   327 V AudioFlinger:  pid 1869 @ 0
08-10 14:11:10.339   327   327 V AudioFlinger:  pid 3108 @ 1
,08-10 14:11:10.339   327   327 V AudioFlinger:  pid 3108 @ 2
08-10 14:11:10.351  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 14:11:10.369  1025  2083 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-10 14:11:10.370  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=133570  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-10 14:11:10.370  1025  1528 D LGWifiP2pService: InactiveState
08-10 14:11:10.370  1025  1528 D LGWifiP2pService: InactiveState{ when=-122ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.370  1025  1531 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 14:11:10.370  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-122ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.370  1025  1528 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-10 14:11:10.371  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 14:11:10.371  6139  6139 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:10.372  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:10.372  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:10.372  6139  6139 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 14:11:10.372  6139  6139 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.372  1025  1528 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-10 14:11:10.373  6139  6139 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: InactiveState{ when=-49ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-49ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1025  1528 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.373  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:10.374  1965  6186 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 14:11:10.374  1965  2345 W WfdsService: DefaultState - msg [9441285] is not handled
08-10 14:11:10.374  1965  6186 D WfdsMonitor: Event [CTRL-EVENT-REG,DOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:10.374  1965  6186 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:10.374  1025  6165 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 14:11:10.374  1025  6165 E WifiMonitor: WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:10.374  1025  6165 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:10.374  1025  6165 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:10.374  1025  6165 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:10.374  1025  6165 E WifiMonitor: WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.374  1025  1025 E WifiServerServiceExt: No p2p device connected
08-10 14:11:10.374  1025  6165 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.374  1025  6165 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.374  1025  6165 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:10.374  1025  6165 E WifiMonitor: WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.374  1025  6165 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.374  1025  6165 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:10.375  1025  1531 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 14:11:10.375  1025  1531 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 14:11:10.375  1025  1531 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 14:11:10.375  1025  1709 W libprocessgroup: failed to open /acct/uid_10034/pid_2190/cgroup.procs: No such file or directory
08-10 14:11:10.375  1025  1531 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 14:11:10.376  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.376  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.376  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 14:11:10.377  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 14:11:10.378  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-10 14:11:10.378  1025  1025 D WifiServerServiceExt: setSupplicantStateSCANNING
08-10 14:11:10.382  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 14:11:10.383  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-10 14:11:10.383  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-10 14:11:10.384  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 14:11:10.384  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 14:11:10.384  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 14:11:10.384  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 14:11:10.384  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 14:11:10.384  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-10 14:11:10.384  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 14:11:10.384  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-10 14:11:10.385  6110  6110 I BluetoothA2dpServiceJni: classInitNative
08-10 14:11:10.386  6110  6110 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 14:11:10.386  6110  6110 D A2dpStateMachine: make
08-10 14:11:10.387  6110  6110 I bluedroid-qcom: get_profile_interface a2dp
08-10 14:11:10.388  6110  6216 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-10 14:11:10.390  1025  1537 D WifiService: New client listening to asynchronous messages
08-10 14:11:10.390  6110  6110 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-10 14:11:10.390  6110  6110 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-10 14:11:10.391  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:10.392  6110  6110 I BluetoothHidServiceJni: classInitNative: succeeds
08-10 14:11:10.393  6110  6214 D A2dpStateMachine: Enter Disconnected: -2
08-10 14:11:10.393  6110  6110 D HidService: Received start request. Starting profile...
08-10 14:11:10.393  6110  6110 I bluedroid-qcom: get_profile_interface hidhost
08-10 14:11:10.393  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:10.394  6110  6110 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-10 14:11:10.396  6110  6110 D HealthService: Received start request. Starting profile...
08-10 14:11:10.398  6110  6110 I bluedroid-qcom: get_profile_interface health
08-10 14:11:10.398  6110  6110 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-10 14:11:10.399  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:10.399  6110  6110 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-10 14:11:10.401  6110  6110 D PanService: Received start request. Starting profile...
08-10 14:11:10.401  6110  6110 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 14:11:10.401  6110  6110 I bluedroid-qcom: get_profile_interface pan
08-10 14:11:10.406  6110  6110 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-10 14:11:10.406  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
,08-10 14:11:10.407  6110  6110 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-10 14:11:10.412  6110  6110 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 14:11:10.412  6110  6110 D BtGatt.GattService: Received start request. Starting profile...
08-10 14:11:10.412  6110  6110 D BtGatt.GattService: start()
08-10 14:11:10.412  6110  6110 I bluedroid-qcom: get_profile_interface gatt
08-10 14:11:10.413  6110  6110 D BtGatt.AdvertiseManager: advertise manager created
08-10 14:11:10.417  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:10.417  6110  6110 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-10 14:11:10.418  6110  6110 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:10.418  6110  6110 V BluetoothPbapReceiver: ***********state = 11
08-10 14:11:10.421  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:10.421  6110  6110 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-10 14:11:10.421  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 14:11:10.422  6145  6145 D LgDataFeature: LgDataFeature() Constructor: none
08-10 14:11:10.422  6145  6145 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 14:11:10.422  6110  6110 V BluetoothMapService: BluetoothMapBinder()
08-10 14:11:10.422  6110  6110 D BluetoothMapService: Received start request. Starting profile...
08-10 14:11:10.423  6110  6110 D BluetoothMapService: start()
08-10 14:11:10.428  6145  6145 D WiFiOffLoadUpdatePriority: remove : truetruetrue
08-10 14:11:10.435  1025  1531 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
08-10 14:11:10.435  1025  1531 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,08-10 14:11:10.440  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
08-10 14:11:10.441  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
,08-10 14:11:10.441  1025  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 14:11:10.456  1025  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-10 14:11:10.459  6145  6145 D WiFiOffLoadUpdatePriority: remove1
08-10 14:11:10.460  6145  6145 V WiFiOffLoadSharedPrefsUtils: save remove
08-10 14:11:10.469  1025  1765 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6224 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-10 14:11:10.474  6110  6110 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-10 14:11:10.475  6110  6110 D BluetoothMapEmailAppObserver: createReceiver()
08-10 14:11:10.477  6145  6145 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
08-10 14:11:10.477  6110  6110 D BluetoothMapEmailAppObserver: initObservers()
08-10 14:11:10.477  6110  6110 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-10 14:11:10.477  6145  6145 D WiFiOffLoadBroadcast: S: false, R: false
08-10 14:11:10.481  1025  1531 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
08-10 14:11:10.482  1025  1531 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,08-10 14:11:10.483  6145  6145 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
08-10 14:11:10.483  6145  6145 D WiFiOffLoadUpdatePriority: connected SSID: null
08-10 14:11:10.483  6145  6145 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
08-10 14:11:10.485  1025  2064 D WifiServiceImplEx: addOrUpdateNetwork pid=6145, uid=1000, packageName=android.uid.system:1000
08-10 14:11:10.487  1025  2064 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
08-10 14:11:10.487  1025  1531 E WifiStateMachine:  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
08-10 14:11:10.488  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:10.488  6110  6110 D HeadsetStateMachine: Proxy object connected
08-10 14:11:10.488  1025  1531 E WifiStateMachine:  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
08-10 14:11:10.488  1025  1531 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
08-10 14:11:10.488  1025  1531 D WifiServerServiceExt: addOrUpdateNetwork: mThisIsFirstEnableing = false
08-10 14:11:10.489  6110  6110 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-10 14:11:10.489  6110  6110 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-10 14:11:10.489  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 ssid 4e47373030
08-10 14:11:10.490  1869  1869 D BluetoothPhoneService.BluetoothLTECall:  call mBluetoothHeadset.phoneStateChanged()
08-10 14:11:10.491  1869  1869 W BluetoothHeadset: Proxy not attached to service
08-10 14:11:10.491  6110  6164 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: java.lang.Throwable
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: 	at android.os.Looper.loop(Looper.java:135)
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 14:11:10.491  1869  1869 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 14:11:10.492  6110  6164 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 14:11:10.492  6110  6164 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-10 14:11:10.494  6110  6110 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-10 14:11:10.504  6110  6110 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 14:11:10.507  6110  6110 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-10 14:11:10.511  6110  6110 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 14:11:10.511  6110  6110 V PanService: [BTUI] SIM Extra State :ABSENT
08-10 14:11:10.514  6110  6110 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-10 14:11:10.517  6110  6110 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-10 14:11:10.518  6110  6110 V BluetoothMapService: Handler(): got msg=1
08-10 14:11:10.518  6110  6140 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-10 14:11:10.519  6110  6140 I bluedroid-qcom: enable
08-10 14:11:10.519  6110  6140 I bt_hci_bdroid: init
08-10 14:11:10.520  6110  6241 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-10 14:11:10.520  6110  6241 I bt-btu  : btu_task pending for preload complete event
,08-10 14:11:10.524  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 ssid 4e47373030: returned true
08-10 14:11:10.524  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
08-10 14:11:10.525  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 key_mgmt WPA-PSK: returned true
08-10 14:11:10.525  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 proto WPA RSN
08-10 14:11:10.525  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 proto WPA RSN: returned true
08-10 14:11:10.525  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
08-10 14:11:10.526  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 pairwise TKIP CCMP: returned true
08-10 14:11:10.526  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
08-10 14:11:10.526  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
08-10 14:11:10.526  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 priority 300
08-10 14:11:10.527  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 priority 300: returned true
08-10 14:11:10.527  1025  1531 E WifiConfigStore: will read network variables netId=0
08-10 14:11:10.529  6110  6140 I bt_vendor: bt-vendor : init
08-10 14:11:10.529  6110  6140 I bt_vendor: bt-vendor : get_bt_soc_type
08-10 14:11:10.529  6110  6140 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-10 14:11:10.529  6110  6140 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-10 14:11:10.529  6110  6140 D bt_userial_mct: userial_init
08-10 14:11:10.531  6110  6140 D bt_hci_bdroid: set_power 1
08-10 14:11:10.531  6110  6140 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-10 14:11:10.531  6110  6140 I bt_vendor: Starting hciattach daemon
08-10 14:11:10.531  6110  6140 I bt_vendor: try to set true
,08-10 14:11:10.522  6244  6244 W sh      : type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:10.522  6244  6244 W sh      : type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:10.533  1025  1531 E WifiConfigStore: writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
08-10 14:11:10.533  1025  1531 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
08-10 14:11:10.535  6145  6145 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
08-10 14:11:10.535  6145  6145 D WiFiOffLoadUpdatePriority: configuration updated: 0
08-10 14:11:10.536  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
08-10 14:11:10.536  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
08-10 14:11:10.536  1025  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 14:11:10.549  1025  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-10 14:11:10.551  6145  6145 D WiFiOffLoadUpdatePriority: configuration saved: true
08-10 14:11:10.552  1025  1765 I ActivityManager: Killing 5493:com.android.defcontainer/u0a4 (adj 15): empty #17
08-10 14:11:10.553  6245  6245 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
08-10 14:11:10.587  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-10 14:11:10.588  1025  6165 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-10 14:11:10.588  6139  6139 E wpa_supplicant: USIM:  scard_init function
08-10 14:11:10.588  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-10 14:11:10.588  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
,08-10 14:11:10.588  6139  6139 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-10 14:11:10.588  1025  6165 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-10 14:11:10.589  1025  1531 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-10 14:11:10.589  1025  1531 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-10 14:11:10.590  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-10 14:11:10.590  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-10 14:11:10.590  1025  1531 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-10 14:11:10.591  1025  1531 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-10 14:11:10.591  1025  1531 I WifiNative-HAL: startHal
08-10 14:11:10.591  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x987e78cc
08-10 14:11:10.591  1025  1531 E WifiHAL : Could not connect handle
08-10 14:11:10.591  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701c16
08-10 14:11:10.591  1025  1531 I WifiNative-HAL: Could not start hal
08-10 14:11:10.591  1025  1531 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-10 14:11:10.598  1025  2083 W libprocessgroup: failed to open /acct/uid_10004/pid_5493/cgroup.procs: No such file or directory
08-10 14:11:10.602  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=133802  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-10 14:11:10.603  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=133803  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-10 14:11:10.606  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:10.606  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:10.607  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:10.608  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.608  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.608  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 14:11:10.608  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.608  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.608  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 14:11:10.609  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 14:11:10.609  1025  1025 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-10 14:11:10.609  6224  6224 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-10 14:11:10.610  6224  6224 W LG Account v2.2: No ProfileInfo entries
08-10 14:11:10.610  6224  6224 I LG Account v2.2: isEnabled: false
08-10 14:11:10.610  6224  6224 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-10 14:11:10.610  6224  6224 I Feature : [Lifetracker]Country: EU
08-10 14:11:10.610  6224  6224 I Feature : [Lifetracker]Operator: OPEN
08-10 14:11:10.610  6224  6224 I Feature : [Lifetracker]Ranking support: false
08-10 14:11:10.610  6224  6224 I Feature : [Lifetracker]Comfort support: false
08-10 14:11:10.610  6224  6224 I Feature : [Lifetracker]Accessory: true
08-10 14:11:10.610  6224  6224 I Feature : [Lifetracker]Health device: true
08-10 14:11:10.610  6224  6224 I Feature : [Lifetracker]Extra Pedometer: false
08-10 14:11:10.610  6224  6224 I Feature : [Lifetracker]Blood glucose device: false
08-10 14:11:10.610  6224  6224 I Feature : [Lifetracker]Device Number: 3
08-10 14:11:10.611  6253  6253 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-10 14:11:10.621  6254  6254 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-10 14:11:10.627  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 14:11:10.627  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:10.628  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:10.633  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 14:11:10.640  6169  6258 W FormManager: Network not available. Please check & try again.
,08-10 14:11:10.641  6256  6256 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-10 14:11:10.642  6169  6259 V FormManager: Network unavailable.
08-10 14:11:10.643  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 14:11:10.648  6169  6259 V FormManager: Network unavailable.
08-10 14:11:10.650  6260  6260 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-10 14:11:10.651  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:10.652  6145  6145 D BluetoothPermissionRequest: onReceive
08-10 14:11:10.653  6145  6145 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-10 14:11:10.660  6261  6261 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-10 14:11:10.667  1025  1087 D BluetoothManagerService: Message: 20
08-10 14:11:10.667  1025  1087 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@355bbdb6:true
,08-10 14:11:10.669  6262  6262 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-10 14:11:10.672  1025  2106 I ActivityManager: Killing 5594:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-10 14:11:10.675  6145  6145 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 14:11:10.693  6265  6265 I libmdmdetect: ESOC framework not supported
,08-10 14:11:10.694  6265  6265 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-10 14:11:10.695  6139  6139 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-10 14:11:10.696  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-10 14:11:10.696  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-10 14:11:10.696  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-10 14:11:10.696  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-10 14:11:10.696  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 14:11:10.696  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 14:11:10.697  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=133897  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-10 14:11:10.697  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=133898  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 14:11:10.698  1025  1531 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=133899
08-10 14:11:10.698  1025  1531 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=133899
08-10 14:11:10.699  1025  1531 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=133899
08-10 14:11:10.699  6265  6265 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-10 14:11:10.699  6265  6265 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-10 14:11:10.699  6265  6265 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-10 14:11:10.699  6265  6265 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-10 14:11:10.699  6265  6265 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-10 14:11:10.699  6265  6265 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-10 14:11:10.699  6265  6265 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-10 14:11:10.700  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=133900
08-10 14:11:10.700  1025  1531 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=133901
08-10 14:11:10.701  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=133901  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 14:11:10.704  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 14:11:10.704  6139  6139 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 14:11:10.704  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-10 14:11:10.705  6139  6139 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 14:11:10.705  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-10 14:11:10.705  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 14:11:10.705  1025  6165 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 14:11:10.705  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-10 14:11:10.705  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 14:11:10.705  1025  6165 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 14:11:10.707  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 14:11:10.707  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 14:11:10.710  1025  1709 W libprocessgroup: failed to open /acct/uid_10008/pid_5594/cgroup.procs: No such file or directory
08-10 14:11:10.711  6110  6110 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-10 14:11:10.713  1025  1087 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-10 14:11:10.719  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:10.719  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:10.721  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:10.721  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.721  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.721  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 14:11:10.723  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=133923  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 14:11:10.724  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.725  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.725  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-10 14:11:10.730  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=133930  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 14:11:10.730  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-10 14:11:10.731  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=133932  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 14:11:10.734  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:10.734  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:10.735  1025  1531 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133935
08-10 14:11:10.735  1025  1531 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133936
08-10 14:11:10.730  1025  1025 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-10 14:11:10.736  6110  6110 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:10.737  1025  1531 D WifiNative-wlan0: doString: [STATUS]
08-10 14:11:10.738  1025  1531 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 14:11:10.738  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 14:11:10.738  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 14:11:10.740  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:10.740  1025  1531 I WifiServiceExtension: setVHTCapabilityType  : false
08-10 14:11:10.742  6110  6110 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 14:11:10.743  6110  6110 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 14:11:10.743  6110  6110 V BluetoothSapReceiver: SapReceiver onReceive 
,08-10 14:11:10.745  6110  6110 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:10.745  6110  6110 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-10 14:11:10.811  1025  1709 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6268 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 14:11:10.813  1025  1531 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-10 14:11:10.814  1025  1531 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-10 14:11:10.820  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 14:11:10.822  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.822  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.822  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 14:11:10.823  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 14:11:10.825  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 14:11:10.826  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:10.826  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 14:11:10.830  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:10.835  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.835  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:10.835  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 14:11:10.841  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:10.841  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 14:11:10.845  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:10.848  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 14:11:10.858  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 14:11:10.858  3065  6285 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 14:11:10.862  3065  6287 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 14:11:10.863  3065  6287 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 14:11:10.865  1025  1531 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-10 14:11:10.865  1025  1538 D ConnectivityService: Got NetworkAgent Messenger
08-10 14:11:10.866  1025  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-10 14:11:10.866  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 14:11:10.866  1025  1538 D ConnectivityService: NetworkAgent connected
08-10 14:11:10.867  1025  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 14:11:10.867  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 14:11:10.867  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 14:11:10.868  1025  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 14:11:10.869  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 14:11:10.869  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 14:11:10.873  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 14:11:10.880  1025  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 14:11:10.880  1025  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 14:11:10.881  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 14:11:10.881  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 14:11:10.881  1025  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 14:11:10.882  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:10.888  1025  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 14:11:10.890   323   868 D CommandListener: Setting iface cfg
08-10 14:11:10.898  6268  6268 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 14:11:10.933  1025  1709 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6290 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-10 14:11:10.938  1025  1709 I ActivityManager: Killing 5628:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-10 14:11:10.989  1025  1568 W libprocessgroup: failed to open /acct/uid_10011/pid_5628/cgroup.procs: No such file or directory
,08-10 14:11:10.997  1025  1531 E WifiStateMachine: Start Dhcp Watchdog 1
08-10 14:11:10.997  1025  6289 D DhcpStateMachine: StoppedState
08-10 14:11:10.997  1025  6289 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:10.998  1025  6289 D DhcpStateMachine: WaitBeforeStartState
08-10 14:11:10.998  1025  1531 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=134198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 14:11:10.998  1025  1531 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=134199  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 14:11:10.999  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=134199  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 14:11:11.000  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:11.000  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:11.001  1025  1531 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:11.001  1025  1531 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:11.001  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-10 14:11:11.002  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:11.003  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 14:11:11.003  1025  1025 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-10 14:11:11.004  1025  1531 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=134204  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 14:11:11.005  1025  1531 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=134205  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 14:11:11.005  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=134206  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 14:11:11.008  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1952255776] from screen [on:0 period:1952255776]
08-10 14:11:11.009  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1952255777]
08-10 14:11:11.009  1025  1531 I WifiNative-HAL: startHal
08-10 14:11:11.009  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x987e78bc
08-10 14:11:11.009  1025  1531 E WifiHAL : Could not connect handle
08-10 14:11:11.009  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x20181e
08-10 14:11:11.009  1025  1531 I WifiNative-HAL: Could not start hal
08-10 14:11:11.010  1025  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 14:11:11.015  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 14:11:11.016  1025  1538 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
08-10 14:11:11.017  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.017  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.018  1025  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.019  1025  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.020  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.021  6290  6290 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 14:11:11.021  1025  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.022  1025  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-10 14:11:11.023  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-10 14:11:11.023  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-10 14:11:11.024  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-10 14:11:11.036  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-10 14:11:11.037  1025  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-10 14:11:11.037  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 0
08-10 14:11:11.038  1025  1531 D WifiNative-wlan0: SET ps 0: returned true
08-10 14:11:11.038  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-10 14:11:11.038  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-10 14:11:11.038  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-10 14:11:11.039  1025  1531 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-10 14:11:11.039  1025  1528 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23320c31 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:11.039  1025  1531 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 14:11:11.039  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23320c31 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:11.039  1025  1531 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 14:11:11.039  1025  6289 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:11.039  1025  1531 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
,08-10 14:11:11.039  1025  6289 D DhcpStateMachine: DHCP Start wake lock is acquired.
,08-10 14:11:11.040  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 14:11:11.040  1025  1025 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-10 14:11:11.052  6290  6290 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-10 14:11:11.088  6290  6290 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-10 14:11:11.089  6290  6290 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-10 14:11:11.089  6290  6290 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-10 14:11:11.090  6290  6290 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-10 14:11:11.090  6290  6290 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-10 14:11:11.092  6290  6290 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-10 14:11:11.098  6290  6290 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-10 14:11:11.105  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 14:11:11.110  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 14:11:11.137  6290  6290 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-10 14:11:11.141  6290  6290 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-10 14:11:11.142  5974  5974 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-10 14:11:11.142  5974  5974 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-10 14:11:11.145  6290  6290 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-10 14:11:11.154  5974  5974 V [BNRBootReceiver]: Boot Receiver Return
,08-10 14:11:11.162  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:11.181  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 14:11:11.194  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 14:11:11.210  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:11.211  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 14:11:11.214  6290  6290 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 14:11:11.221  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-10 14:11:11.229  6145  6145 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-10 14:11:11.238  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:11.245  1025  6289 D DhcpStateMachine: DHCPV4 request on wlan0
,08-10 14:11:11.246  1025  6289 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-10 14:11:11.246  1025  6289 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-10 14:11:11.260  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 14:11:11.262  6314  6314 W dhcpcd  : type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file,
08-10 14:11:11.262  6314  6314 W dhcpcd  : type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:11.272  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:11.280  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:11.280  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:11.283  6290  6290 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-10 14:11:11.287  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:11.289  6314  6314 I dhcpcd  : version 5.5.6 starting
08-10 14:11:11.291  6314  6314 E dhcpcd  : get_duid: m
08-10 14:11:11.291  6314  6314 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-10 14:11:11.291  6314  6314 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-10 14:11:11.297  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 14:11:11.308  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 14:11:11.316  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:11.317  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:11.317  6290  6290 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 14:11:11.321  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-10 14:11:11.321  6145  6145 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 14:11:11.321  6145  6145 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 14:11:11.321  6145  6145 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 14:11:11.322  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 14:11:11.323  6145  6145 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 14:11:11.323  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-10 14:11:11.323  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 14:11:11.323  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 14:11:11.323  6145  6145 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 14:11:11.323  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-10 14:11:11.323  6145  6145 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 14:11:11.326  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:11.336  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 14:11:11.344  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:11.353  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 14:11:11.353  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:11.354  6290  6290 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 14:11:11.357  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:11.366  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 14:11:11.372  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:11.379  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:11.379  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:11.380  6290  6290 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 14:11:11.384  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:11.393  6314  6314 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 14:11:11.394  6314  6314 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 14:11:11.394  6314  6314 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-10 14:11:11.395  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 14:11:11.401  6314  6314 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-10 14:11:11.401  6314  6314 D dhcpcd  : wlan0: sending REQUEST (xid 0x4fae5067), next in 3.68 seconds
08-10 14:11:11.402  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:11.409  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:11.410  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:11.411  6290  6290 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 14:11:11.414  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:11.422  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 14:11:11.427  6314  6314 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-10 14:11:11.428  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:11.436  6314  6314 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-10 14:11:11.436  6314  6314 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-10 14:11:11.436  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 14:11:11.437  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:11.437  6314  6314 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-10 14:11:11.437  6314  6314 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-10 14:11:11.437  6314  6314 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-10 14:11:11.437  6290  6290 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 14:11:11.437  6314  6314 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 14:11:11.438  6314  6314 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 14:11:11.438  6314  6314 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-10 14:11:11.440  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.440  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.441  1025  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.442  1025  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.442  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.442  1025  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:11.443  1025  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-10 14:11:11.444  6290  6290 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 14:11:11.445  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 14:11:11.446  6290  6290 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-10 14:11:11.493  6290  6290 D LgDataFeature: LgDataFeature() Constructor: none
08-10 14:11:11.493  6290  6290 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 14:11:11.507  6290  6290 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-10 14:11:11.510  6290  6290 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
08-10 14:11:11.510  6290  6290 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
08-10 14:11:11.510  6290  6290 V SoundPool: doLoad: loading sample sampleID=1
08-10 14:11:11.511  6290  6290 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 14:11:11.512  6290  6329 V SoundPool: Start decode
08-10 14:11:11.512  6290  6329 V MediaPlayer[Native]: decode(30, 10857164, 17813)
08-10 14:11:11.514   327  1377 V MediaPlayerService: decode(22, 10857164, 17813)
08-10 14:11:11.514   327  1377 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-10 14:11:11.514   327  1377 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-10 14:11:11.514   327  1377 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-10 14:11:11.514   327  1377 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-10 14:11:11.514   327  1377 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-10 14:11:11.514   327  1377 V MediaPlayerService: player type = 3
08-10 14:11:11.515   327  1377 V AwesomePlayer: AwesomePlayer create()
08-10 14:11:11.515   327  1377 V AwesomePlayer: reset_l() 
08-10 14:11:11.515   327  1377 V AwesomePlayer: cancelPlayerEvents
08-10 14:11:11.515   327  1377 V AwesomePlayer: setAudioSink() 
08-10 14:11:11.515   327  1377 V AwesomePlayer: reset_l() 
08-10 14:11:11.515   327  1377 V AudioCache: notify(0xb14325c0, 8, 0, 0)
08-10 14:11:11.515   327  1377 V AudioCache: ignored
08-10 14:11:11.515   327  1377 V AwesomePlayer: cancelPlayerEvents
08-10 14:11:11.516   327  1377 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-10 14:11:11.516   327  1377 V AwesomePlayer: setDataSource_l dataSource
08-10 14:11:11.516   327  1377 V LGParserOSAL: SniffLGParser start
08-10 14:11:11.516   327  1377 V LGParserOSAL: MainType:5, SubType=0
08-10 14:11:11.516   327  1377 V LGParserOSAL: #### check Mime : application/ogg
08-10 14:11:11.516   327  1377 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-10 14:11:11.516   327  1377 E MediaExtractor: Use LGExtractor :application/ogg 
08-10 14:11:11.518  5996  5996 D UEI.SmartControl: QS Service created
08-10 14:11:11.527  6290  6290 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-10 14:11:11.531  6290  6290 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 14:11:11.531  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-10 14:11:11.546  6290  6290 V LGMDMManager: Create singleton instance
08-10 14:11:11.565   327  1377 V LGParserOSAL: supported mime: application/ogg
08-10 14:11:11.565   327  1377 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-10 14:11:11.565   327  1377 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-10 14:11:11.565   327  1377 V AwesomePlayer: mBitrate = -1 bits/sec
08-10 14:11:11.565   327  1377 V AwesomePlayer: AudioTrack Setting
08-10 14:11:11.565   327  1377 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-10 14:11:11.565   327  1377 V AwesomePlayer: setAudioSource() 
08-10 14:11:11.565   327  1377 V MediaPlayerService: prepare
08-10 14:11:11.565   327  1377 V AwesomePlayer: prepareAsync_l() 
08-10 14:11:11.565   327  1377 V MediaPlayerService: wait for prepare
08-10 14:11:11.565   327  6334 V AwesomePlayer: onPrepareAsyncEvent() 
08-10 14:11:11.565   327  6334 V AwesomePlayer: initAudioDecoder() 
08-10 14:11:11.565   327  6334 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 14:11:11.565   327  6334 V AudioSystem: isOffloadSupported()
08-10 14:11:11.565   327  6334 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 14:11:11.565   327  6334 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 14:11:11.565   327  6334 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 14:11:11.565   327  6334 V AwesomePlayer: getUseOffload() = 0 
08-10 14:11:11.565   327  6334 V OMXCodec: OMXCodec::Create
08-10 14:11:11.565   327  6334 V OMXCodec: findMatchingCodecs()
08-10 14:11:11.565   327  6334 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-10 14:11:11.566   327  6334 V OMXCodec: matchingCodecs.size()=1
08-10 14:11:11.566   327  6334 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-10 14:11:11.567   327  6334 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-10 14:11:11.567   327  6334 V LGCodecAdapter: LG Codec Adapter start
08-10 14:11:11.567   327  6334 V OMXCodec: OMXCodec Createtor
08-10 14:11:11.568   327  6334 V OMXCodec: setComponentRole
08-10 14:11:11.568   327  6334 V OMXCodec: configureCodec protected=0
08-10 14:11:11.568   327  6334 V LGCodecAdapter: called getLGCodecSpecificData
08-10 14:11:11.568   327  6334 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-10 14:11:11.568   327  6334 V LGCodecOSAL: Called LGconfigureCodecMETA
08-10 14:11:11.568   327  6334 V LGCodecOSAL: Called LGconfigureCodecMSG
08-10 14:11:11.568   327  6334 V LGCodecOSAL: Not support LGCodec
08-10 14:11:11.568   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 14:11:11.568   327  6334 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-10 14:11:11.568   327  6334 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-10 14:11:11.568   327  6334 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-10 14:11:11.568   327  6334 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 14:11:11.568   327  6334 V AudioSystem: isOffloadSupported()
08-10 14:11:11.568   327  6334 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 14:11:11.568   327  6334 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 14:11:11.568   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-10 14:11:11.568   327  6334 V OMXCodec: init()
08-10 14:11:11.568   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-10 14:11:11.568   327  6334 V OMXCodec: allocateBuffers
08-10 14:11:11.568   327  6334 V OMXCodec: allocateBuffersOnPort portIndex=0
08-10 14:11:11.568   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-10 14:11:11.569   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14343d0 on input port
08-10 14:11:11.569   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
08-10 14:11:11.569   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
08-10 14:11:11.569   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
08-10 14:11:11.569   327  6334 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 14:11:11.569   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 14:11:11.569   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
08-10 14:11:11.569   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
08-10 14:11:11.569   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14349c0 on output port
08-10 14:11:11.569   327  6334 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434dd0 on output port
08-10 14:11:11.569   327  6334 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 14:11:11.573   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 14:11:11.574   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 14:11:11.574   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-10 14:11:11.574   327  6334 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 14:11:11.575   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-10 14:11:11.575   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-10 14:11:11.575   32,7  6336 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-10 14:11:11.575   327  6334 V OMXCodec: init() mAsyncCompletion wait free! 
08-10 14:11:11.575   327  6334 V AwesomePlayer: finishAsyncPrepare_l() 
08-10 14:11:11.575   327  6334 V AudioCache: notify(0xb14325c0, 5, 0, 0)
08-10 14:11:11.575   327  6334 V AudioCache: ignored
08-10 14:11:11.575   327  6334 V AudioCache: notify(0xb14325c0, 1, 0, 0)
08-10 14:11:11.575   327  6334 V AudioCache: prepared
08-10 14:11:11.575   327  1377 V AudioCache: wait - success
08-10 14:11:11.576   327  1377 V MediaPlayerService: start
08-10 14:11:11.576   327  1377 V AwesomePlayer: play_l() 
08-10 14:11:11.576   327  1377 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-10 14:11:11.576   327  1377 V AwesomePlayer: createAudioPlayer_l
08-10 14:11:11.576   327  1377 V AwesomePlayer: seekAudioIfNecessary_l() 
08-10 14:11:11.576   327  1377 V AwesomePlayer: startAudioPlayer_l() 
08-10 14:11:11.576   327  1377 D AudioPlayer: start of Playback, useOffload 0
08-10 14:11:11.576   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 14:11:11.576   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 14:11:11.579   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-10 14:11:11.579   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-10 14:11:11.579   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-10 14:11:11.579   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-10 14:11:11.579   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-10 14:11:11.579   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 14:11:11.579   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975904
08-10 14:11:11.579   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 14:11:11.579   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976064
08-10 14:11:11.579   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977024
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 14:11:11.580  5996  5996 I UEI.SmartControl: Service initServices...
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978064
,08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
,08-10 14:11:11.580  5996  5996 D UEI.SmartControl: QS start get config
08-10 14:11:11.580   327  6336 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14349c0 on output port
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
,08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15250b0 on output port
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-10 14:11:11.580   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-10 14:11:11.581   327  1377 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-10 14:11:11.581   327  1377 V AudioCache: notify(0xb14325c0, 6, 0, 0)
,08-10 14:11:11.581   327  1377 V AudioCache: ignored
08-10 14:11:11.582   327  1377 V MediaPlayerService: wait for playback complete
,08-10 14:11:11.586   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.586   327  6338 V AudioCache: memcpy(0xac700000, 0xb11b7000, 4096)
,08-10 14:11:11.614   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.614   327  6338 V AudioCache: memcpy(0xac701000, 0xb11b7000, 4096)
,08-10 14:11:11.615   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.615   327  6338 V AudioCache: memcpy(0xac702000, 0xb11b7000, 4096)
08-10 14:11:11.616   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.616   327  6338 V AudioCache: memcpy(0xac703000, 0xb11b7000, 4096)
08-10 14:11:11.617   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.617   327  6338 V AudioCache: memcpy(0xac704000, 0xb11b7000, 4096)
08-10 14:11:11.618   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.618   327  6338 V AudioCache: memcpy(0xac705000, 0xb11b7000, 4096)
08-10 14:11:11.619   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.619   327  6338 V AudioCache: memcpy(0xac706000, 0xb11b7000, 4096)
08-10 14:11:11.619   327  6338 V AudioCache: write(0xb11b7000, 4096)
,08-10 14:11:11.619   327  6338 V AudioCache: memcpy(0xac707000, 0xb11b7000, 4096)
08-10 14:11:11.620   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.620   327  6338 V AudioCache: memcpy(0xac708000, 0xb11b7000, 4096)
08-10 14:11:11.621   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.621   327  6338 V AudioCache: memcpy(0xac709000, 0xb11b7000, 4096)
08-10 14:11:11.622   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.622   327  6338 V AudioCache: memcpy(0xac70a000, 0xb11b7000, 4096)
08-10 14:11:11.623   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.624   327  6338 V AudioCache: memcpy(0xac70b000, 0xb11b7000, 4096)
08-10 14:11:11.624   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.624   327  6338 V AudioCache: memcpy(0xac70c000, 0xb11b7000, 4096)
08-10 14:11:11.625   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.625   327  6338 V AudioCache: memcpy(0xac70d000, 0xb11b7000, 4096)
,08-10 14:11:11.628   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.628   327  6338 V AudioCache: memcpy(0xac70e000, 0xb11b7000, 4096)
08-10 14:11:11.629   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.629   327  6338 V AudioCache: memcpy(0xac70f000, 0xb11b7000, 4096)
08-10 14:11:11.629   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.629   327  6338 V AudioCache: memcpy(0xac710000, 0xb11b7000, 4096)
08-10 14:11:11.630   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.630   327  6338 V AudioCache: memcpy(0xac711000, 0xb11b7000, 4096)
08-10 14:11:11.631   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.631   327  6338 V AudioCache: memcpy(0xac712000, 0xb11b7000, 4096)
08-10 14:11:11.631   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.632   327  6338 V AudioCache: memcpy(0xac713000, 0xb11b7000, 4096)
08-10 14:11:11.632   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.632   327  6338 V AudioCache: memcpy(0xac714000, 0xb11b7000, 4096)
08-10 14:11:11.633   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.633   327  6338 V AudioCache: memcpy(0xac715000, 0xb11b7000, 4096)
08-10 14:11:11.634   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.634   327  6338 V AudioCache: memcpy(0xac716000, 0xb11b7000, 4096)
08-10 14:11:11.634   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.634   327  6338 V AudioCache: memcpy(0xac717000, 0xb11b7000, 4096)
08-10 14:11:11.635   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.635   327  6338 V AudioCache: memcpy(0xac718000, 0xb11b7000, 4096)
08-10 14:11:11.636   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.636   327  6338 V AudioCache: memcpy(0xac719000, 0xb11b7000, 4096)
08-10 14:11:11.637   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.637   327  6338 V AudioCache: memcpy(0xac71a000, 0xb11b7000, 4096)
08-10 14:11:11.638   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.638   327  6338 V AudioCache: memcpy(0xac71b000, 0xb11b7000, 4096)
,08-10 14:11:11.641   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.641   327  6338 V AudioCache: memcpy(0xac71c000, 0xb11b7000, 4096)
08-10 14:11:11.642   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.642   327  6338 V AudioCache: memcpy(0xac71d000, 0xb11b7000, 4096)
08-10 14:11:11.642   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.642   327  6338 V AudioCache: memcpy(0xac71e000, 0xb11b7000, 4096)
08-10 14:11:11.642   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.642   327  6338 V AudioCache: memcpy(0xac71f000, 0xb11b7000, 4096)
08-10 14:11:11.642   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.642   327  6338 V AudioCache: memcpy(0xac720000, 0xb11b7000, 4096)
08-10 14:11:11.645   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.645   327  6338 V AudioCache: memcpy(0xac721000, 0xb11b7000, 4096)
08-10 14:11:11.645   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.645   327  6338 V AudioCache: memcpy(0xac722000, 0xb11b7000, 4096)
08-10 14:11:11.645   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.645   327  6338 V AudioCache: memcpy(0xac723000, 0xb11b7000, 4096)
08-10 14:11:11.645   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.645   327  6338 V AudioCache: memcpy(0xac724000, 0xb11b7000, 4096)
08-10 14:11:11.648   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.648   327  6338 V AudioCache: memcpy(0xac725000, 0xb11b7000, 4096)
08-10 14:11:11.648   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.648   327  6338 V AudioCache: memcpy(0xac726000, 0xb11b7000, 4096)
08-10 14:11:11.648   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.648   327  6338 V AudioCache: memcpy(0xac727000, 0xb11b7000, 4096)
08-10 14:11:11.649   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.649   327  6338 V AudioCache: memcpy(0xac728000, 0xb11b7000, 4096)
08-10 14:11:11.650   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.650   327  6338 V AudioCache: memcpy(0xac729000, 0xb11b7000, 4096)
,08-10 14:11:11.651   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.651   327  6338 V AudioCache: memcpy(0xac72a000, 0xb11b7000, 4096)
08-10 14:11:11.653   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.653   327  6338 V AudioCache: memcpy(0xac72b000, 0xb11b7000, 4096)
08-10 14:11:11.654   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.654   327  6338 V AudioCache: memcpy(0xac72c000, 0xb11b7000, 4096)
08-10 14:11:11.654   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.654   327  6338 V AudioCache: memcpy(0xac72d000, 0xb11b7000, 4096)
08-10 14:11:11.655   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.655   327  6338 V AudioCache: memcpy(0xac72e000, 0xb11b7000, 4096)
08-10 14:11:11.656   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.656   327  6338 V AudioCache: memcpy(0xac72f000, 0xb11b7000, 4096)
08-10 14:11:11.657   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.657   327  6338 V AudioCache: memcpy(0xac730000, 0xb11b7000, 4096)
08-10 14:11:11.658   327  6338 V AudioCache: write(0xb11b7000, 4096)
08-10 14:11:11.658   327  6338 V AudioCache: memcpy(0xac731000, 0xb11b7000, 4096)
08-10 14:11:11.658   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-10 14:11:11.658   327  6338 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-10 14:11:11.658   327  6338 V AwesomePlayer: postAudioEOS() 
08-10 14:11:11.658   327  6338 V AudioCache: write(0xb11b7000, 280)
08-10 14:11:11.658   327  6338 V AudioCache: memcpy(0xac732000, 0xb11b7000, 280)
08-10 14:11:11.660   327  6334 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-10 14:11:11.660   327  6334 V AwesomePlayer: onStreamDone
08-10 14:11:11.660   327  6334 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-10 14:11:11.660   327  6334 V AudioCache: notify(0xb14325c0, 2, 0, 0)
08-10 14:11:11.660   327  6334 V AudioCache: playback complete
08-10 14:11:11.660   327  6334 V AwesomePlayer: pause_l() 
08-10 14:11:11.660   327  6334 V AudioCache: notify(0xb14325c0, 7, 0, 0)
08-10 14:11:11.660   327  6334 V AudioCache: ignored
08-10 14:11:11.660   327  6334 V AwesomePlayer: cancelPlayerEvents
08-10 14:11:11.660   327  1377 V AudioCache: wait - success
08-10 14:11:11.660   327  1377 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-10 14:11:11.660   327  6334 D AudioPlayer: Pause Playback at 1068125
08-10 14:11:11.661   327  1377 V AwesomePlayer: reset_l() 
08-10 14:11:11.661   327  1377 V AudioCache: notify(0xb14325c0, 8, 0, 0)
08-10 14:11:11.661   327  1377 V AudioCache: ignored
08-10 14:11:11.661   327  1377 V AwesomePlayer: cancelPlayerEvents
08-10 14:11:11.661   327  1377 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-10 14:11:11.661   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-10 14:11:11.661   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-10 14:11:11.661   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-10 14:11:11.661   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 14:11:11.662   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 14:11:11.662   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 14:11:11.662   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-10 14:11:11.662   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
08-10 14:11:11.662   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-10 14:11:11.663   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
08-10 14:11:11.663   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14343d0 on port 0
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb15250b0 on port 1
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 1
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 1
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14349c0 on port 1
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 14:11:11.664   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-10 14:11:11.665   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 14:11:11.665   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 14:11:11.665   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-10 14:11:11.665   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-10 14:11:11.665   327  6336 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-10 14:11:11.665   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 14:11:11.665   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-10 14:11:11.665   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-10 14:11:11.667   327  1377 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-10 14:11:11.667   327  1377 D AudioPlayer: AudioPlayer releasing audio source
08-10 14:11:11.667   327  1377 D AudioPlayer: AudioPlayer done releasing audio source
08-10 14:11:11.667   327  1377 V AwesomePlayer: reset_l() 
08-10 14:11:11.667   327  1377 V AwesomePlayer: cancelPlayerEvents
08-10 14:11:11.667   327  1377 V AwesomePlayer: ~AwesomePlayer call
08-10 14:11:11.674   327  1377 V AwesomePlayer: reset_l() 
08-10 14:11:11.674   327  1377 V AwesomePlayer: cancelPlayerEvents
,08-10 14:11:11.676  6290  6329 V SoundPool: close(30)
08-10 14:11:11.676  6290  6329 V SoundPool: pointer = 0x9fe89000, size = 205080, sampleRate = 48000, numChannels = 2
08-10 14:11:11.678  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 14:11:11.679  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-10 14:11:11.681  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5646
08-10 14:11:11.720  6265  6267 E QC-QMI  : qmi_client [6265] 13: failed to locate client data
,08-10 14:11:11.721   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-10 14:11:11.722   484   484 E QC-QMI  : QMUX qmux_client_id=13 not found in qmux client list, unable to remove
08-10 14:11:11.854  1025  6289 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-10 14:11:11.857  1025  6289 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-10 14:11:11.858  1025  6289 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-10 14:11:11.859  1025  6289 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-10 14:11:11.859  1025  6289 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-10 14:11:11.859  1025  6289 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 14:11:11.860  1025  6289 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-10 14:11:11.862  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-10 14:11:11.863  1025  6289 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-10 14:11:11.864  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-10 14:11:11.864  1025  6289 D DhcpStateMachine: RunningState
08-10 14:11:11.864  1025  1528 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:11.864  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:11.865  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 14:11:11.865  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 14:11:11.867  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 14:11:11.867  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-10 14:11:11.867  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-10 14:11:11.868  1025  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-10 14:11:11.868  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 14:11:11.877  6354  6354 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-10 14:11:11.885  1025  1531 D WifiNative-wlan0: SET ps 1: returned true
08-10 14:11:11.886  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 14:11:11.886  1025  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-10 14:11:11.887  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 14:11:11.887  1025  1531 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-10 14:11:11.887  1025  1538 D ConnectivityService: ignoring duplicate network state non-change
08-10 14:11:11.888  1025  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-10 14:11:11.889  1025  1538 D ConnectivityService: Adding iface wlan0 to network 100
,08-10 14:11:11.897  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:11.897  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:11.898  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 14:11:11.901  6355  6355 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-10 14:11:11.906  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:11.906  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:11.906  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 14:11:11.907  1025  1025 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-10 14:11:11.907  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:11.907  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:11.907  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 14:11:11.907  1025  1025 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-10 14:11:11.907  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:11.907  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:11.907  1025  1531 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-10 14:11:11.907  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 14:11:11.908  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:11.908  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:11.913  1025  1538 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-10 14:11:11.913  1025  1538 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-10 14:11:11.915  1025  1538 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-10 14:11:11.915  1965  1965 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-10 14:11:11.916  1025  1538 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-10 14:11:11.916  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:11.918  1025  1538 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-10 14:11:11.919  1025  1538 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-10 14:11:11.919  1025  1538 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-10 14:11:11.919  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 14:11:11.921  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:11.921  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:11.923  1025  1538 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-10 14:11:11.923  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:11.923  1025  1538 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-10 14:11:11.923  1025  1538 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-10 14:11:11.923  1025  1538 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-10 14:11:11.923  1025  6284 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:11.923  1025  1538 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 14:11:11.923  1025  6284 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-10 14:11:11.923  1025  1538 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 14:11:11.923  1025  1538 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 14:11:11.923  1025  6284 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:11.923  1025  1538 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:11.923  1025  1538 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-10 14:11:11.924  1025  1538 D ConnectivityService: currentScore = 0, newScore = 20
08-10 14:11:11.924  1025  6284 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-10 14:11:11.925  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:11.929  1596  1596 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 14:11:11.929  1025  1538 D ConnectivityService:    accepting network in place of null
08-10 14:11:11.929  1025  1538 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:11.929  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:11.930  1025  1531 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:11.930  1025  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 14:11:11.930   323  6360 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-10 14:11:11.931  1869  1869 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:11.931  1869  1869 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRU,STED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 14:11:11.930  1025  1538 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-10 14:11:11.936  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 14:11:11.937  1025  1538 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-10 14:11:11.937  1025  1538 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-10 14:11:11.937  1025  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 14:11:11.938  1025  1538 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:11.938  1025  1538 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-10 14:11:11.939  1025  1538 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-10 14:11:11.939  1025  1025 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-10 14:11:11.940  1025  1025 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 14:11:11.940  1025  1025 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 14:11:11.940  1025  1025 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 14:11:11.940  1025  1025 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-10 14:11:11.941  1025  1538 D ConnectivityService: validation of new default Network = false
08-10 14:11:11.941  1025  1538 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-10 14:11:11.941  1025  1538 D DSQN    : enableDataServiceNotify 
08-10 14:11:11.941  1025  1538 D DSQN    : start dsqn bin
08-10 14:11:11.942   323  6362 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 14:11:11.942   323  6362 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-10 14:11:11.942  6110  6140 I bt_vendor: bluetooth satus is on
08-10 14:11:11.942  6110  6140 D bt_hci_bdroid: preload
08-10 14:11:11.942  6110  6243 D bt_userial_mct: userial_open(port:0)
08-10 14:11:11.942  6110  6243 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-10 14:11:11.943  6110  6243 I bt_vendor: Done intiailizing UART
08-10 14:11:11.943  6110  6243 I bt_vendor: Done intiailizing UART
08-10 14:11:11.943  6110  6243 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-10 14:11:11.943  6110  6243 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-10 14:11:11.943  6110  6241 I bt-btu  : btu_task received preload complete event
08-10 14:11:11.944  6110  6241 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-10 14:11:11.944  6110  6241 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f,
08-10 14:11:11.946  6110  6241 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-10 14:11:11.946  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:11.947   323  6364 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 14:11:11.947   323  6364 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-10 14:11:11.947  6110  6363 D bt_userial_mct: Entering userial_read_thread()
,08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_HCI
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 14:11:11.948  6110  6241 I         : BTE_InitTraceLevels -- TRC_BTIF
08-10 14:11:11.952  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:11.952  1596  1596 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 14:11:11.952  1025  1538 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-10 14:11:11.952  1025  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:11.952  1025  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 14:11:11.952  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:11.953  1025  1538 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 14:11:11.953  1596  1804 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 14:11:11.942  6365  6365 W dsqn    : type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:11.942  6365  6365 W dsqn    : type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:11.957  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:11.957  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:11.962  6290  6290 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 14:11:11.964  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:11.969  6110  6241 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-10 14:11:11.969  6110  6241 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0195061 
08-10 14:11:11.969  6110  6241 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0195061 
08-10 14:11:11.973  6365  6365 E DSQN    : DSQN ssw
,08-10 14:11:11.975  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 14:11:11.975  6110  6144 E bt-btif : Calling BTA_HhEnable
08-10 14:11:11.975  6110  6144 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-10 14:11:11.976  6110  6144 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-10 14:11:11.976  6110  6241 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-10 14:11:11.977  6110  6241 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-10 14:11:11.977  6110  6241 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-10 14:11:11.977  6110  6241 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-10 14:11:11.977  6110  6241 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-10 14:11:11.979  6110  6144 D BluetoothAdapterProperties: Name is: G3
08-10 14:11:11.979  1025  1025 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 14:11:11.979  1025  1025 D BluetoothManagerService: Stored Bluetooth name: G3
08-10 14:11:11.980  6110  6144 D BluetoothAdapterProperties: Scan Mode:20
08-10 14:11:11.980  6110  6144 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 14:11:11.980  6110  6144 D bt_hci_bdroid: postload
08-10 14:11:11.980  6110  6243 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 14:11:11.980  6110  6241 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-10 14:11:11.981  6110  6243 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 14:11:11.981  6110  6144 D bte_conf: Device ID record 1 : primary
08-10 14:11:11.981  6110  6144 D bte_conf:   vendorId            = 00c4
08-10 14:11:11.981  6110  6144 D bte_conf:   vendorIdSource      = 0001
08-10 14:11:11.981  6110  6144 D bte_conf:   product             = 13a1
08-10 14:11:11.981  6110  6144 D bte_conf:   version             = 1000
08-10 14:11:11.981  6110  6144 D bte_conf:   clientExecutableURL = 
08-10 14:11:11.981  6110  6144 D bte_conf:   serviceDescription  = 
08-10 14:11:11.981  6110  6144 D bte_conf:   documentationURL    = 
08-10 14:11:11.981  6110  6144 D bte_conf: bte_load_did_conf no section named DID2.
08-10 14:11:11.981  6110  6243 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 14:11:11.981  6110  6243 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 14:11:11.972  6370  6370 W sh      : type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:11.972  6370  6370 W sh      : type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:11.983  6110  6144 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-10 14:11:11.983  6110  6140 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-10 14:11:11.983  6110  6140 D BluetoothAdapterProperties: ScanMode =  20
08-10 14:11:11.983  6110  6140 D BluetoothAdapterProperties: State =  11
08-10 14:11:11.983  6110  6140 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-10 14:11:11.984  6110  6140 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-10 14:11:11.984  6110  6140 D BluetoothAdapterProperties: Setting state to 12
08-10 14:11:11.984  6110  6140 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 14:11:11.984  1025  1087 D BluetoothManagerService: Message: 60
08-10 14:11:11.984  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-10 14:11:11.984  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 5 receivers.
08-10 14:11:11.985  6110  6140 I BluetoothAdapterState: Entering On State
08-10 14:11:11.986  6110  6144 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 14:11:11.987  6110  6241 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 14:11:11.987  6110  6241 W bt-smp  : Plain text(LSB ~ MSB) = ab 0e 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 14:11:11.987  6110  6241 W bt-smp  : Encrypted text(LSB ~ MSB) = c4 8f 68 11 f8 44 1d 64 62 aa f5 71 c4 49 9a f6 
08-10 14:11:11.987  6110  6241 W bt-btm  : Stopping oneshot timer
08-10 14:11:11.987  6110  6243 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 14:11:11.988  6110  6363 E bt_mct  : hci lib postload comp,leted
,08-10 14:11:11.989  1869  2430 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:11:11.994  6110  6140 D LGBluetoothServiceAdapter: [BTUI] OnState
08-10 14:11:11.994  6110  6140 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-10 14:11:11.995  6110  6140 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-10 14:11:11.995  1025  1087 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:11:11.995  1025  1087 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 14:11:11.995  1869  1885 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:11:11.996  6110  6140 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-10 14:11:11.996  5996  5996 I UEI.SmartControl: Supports setup maps: true
08-10 14:11:11.998  5818  5818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 14:11:11.998  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:11.998  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:11.998  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:11.998  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:11.998  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:11:11.998  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 14:11:11.998  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 14:11:11.998  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 14:11:11.998  5996  5996 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 14:11:11.998  5996  5996 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-10 14:11:11.998  5996  5996 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 14:11:11.998  5996  5996 I UEI.SmartControl: ### init IR Blaster...
08-10 14:11:11.998  1869  1884 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:11:12.000  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 14:11:12.000  1025  1087 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-10 14:11:12.000  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-10 14:11:12.002  5996  5996 D serial_port: Configuring serial port
08-10 14:11:12.002  5996  5996 E UEI.SmartControl: UEIBLaster setting for 616
08-10 14:11:12.002  5996  5996 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 14:11:12.002  5996  5996 I UEI.SmartControl: configuring settings for MAXQ616
08-10 14:11:12.002  5996  5996 I UEI.SmartControl: Get version...
08-10 14:11:12.004  6110  6241 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 14:11:12.004  6110  6241 W bt-smp  : Plain text(LSB ~ MSB) = eb c1 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 14:11:12.004  6110  6241 W bt-smp  : Encrypted text(LSB ~ MSB) = a4 32 a9 8c bb 97 10 d8 07 55 95 49 79 75 40 25 
08-10 14:11:12.004  6110  6241 W bt-btm  : Stopping oneshot timer
08-10 14:11:12.005  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:12.005  1965  2202 D LGBluetoothAPIService: Message: 1
08-10 14:11:12.005  1965  2202 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-10 14:11:12.013  6110  6241 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 14:11:12.013  6110  6241 W bt-smp  : Plain text(LSB ~ MSB) = 63 b7 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 14:11:12.014  6110  6241 W bt-smp  : Encrypted text(LSB ~ MSB) = a5 ee 9e 1a 94 29 ac 6c 95 42 e4 1f 74 ae 0f b8 
08-10 14:11:12.014  6110  6241 W bt-btm  : Stopping oneshot timer
,08-10 14:11:12.016  1025  1025 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-10 14:11:12.016  1025  1087 D BluetoothManagerService: Message: 40
08-10 14:11:12.017  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-10 14:11:12.019  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:12.020  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:12.020  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:12.020  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:12.020  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:12.020  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:11:12.020  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 14:11:12.020  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 14:11:12.020  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 14:11:12.021  6110  6241 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 14:11:12.021  6110  6241 W bt-smp  : Plain text(LSB ~ MSB) = 0e 3d 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 14:11:12.021  6110  6241 W bt-smp  : Encrypted text(LSB ~ MSB) = 10 61 55 ce 42 5a 27 aa ff 4c 35 07 f1 9e b1 10 
08-10 14:11:12.021  6110  6241 W bt-btm  : Stopping oneshot timer
08-10 14:11:12.021  5996  6373 D UEI.SmartControl: serial port data available: 21
08-10 14:11:12.022  1965  2202 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-10 14:11:12.022  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 14:11:12.022  6110  6110 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:12.023  6110  6110 D BluetoothMapService: STATE_ON
08-10 14:11:12.024  5818  5818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 14:11:12.025  6110  6110 D LGBluetoothAPIServer: [BTUI] onCreate()
08-10 14:11:12.025  5818  5818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 14:11:12.025  6110  6110 D LGBluetoothAPIServer: [BTUI] onBind()
,08-10 14:11:12.029  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:12.030  1965  1965 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-10 14:11:12.030  1965  2202 D LGBluetoothAPIService: Message: 100
08-10 14:11:12.030  1965  2202 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-10 14:11:12.031  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:12.032  6377  6377 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-10 14:11:12.035  6110  6140 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-10 14:11:12.037  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 14:11:12.038  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 14:11:12.038  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:12.038  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 14:11:12.042  6110  6241 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-10 14:11:12.042  6110  6241 W bt-smp  : Plain text(LSB ~ MSB) = 12 a5 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 14:11:12.042  6110  6241 W bt-smp  : Encrypted text(LSB ~ MSB) = 88 98 fe 3c d4 16 bc e6 2c 7a fb 5d bc 71 e4 3b 
08-10 14:11:12.042  6110  6241 W bt-btm  : Stopping oneshot timer
08-10 14:11:12.042  6145  6145 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 14:11:12.048  5996  5996 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-10 14:11:12.048  5996  5996 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 14:11:12.048  5996  5996 I UEI.SmartControl: QS saving settings...
08-10 14:11:12.051  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:12.051  6110  6110 V BluetoothPbapService: Pbap Service onCreate
08-10 14:11:12.051  6110  6110 V BluetoothPbapService: Starting PBAP service
,08-10 14:11:12.052  6110  6110 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-10 14:11:12.052  6110  6110 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:12.052  6110  6110 V BluetoothPbapService: state: 12
08-10 14:11:12.053  6110  6110 V BluetoothMapService: Handler(): got msg=1
08-10 14:11:12.053  6110  6110 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-10 14:11:12.053  6110  6110 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 14:11:12.053  6110  6110 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:12.053  6110  6110 V BluetoothPbapReceiver: ***********state = 12
08-10 14:11:12.054  6110  6379 D BluetoothMapMasInstance: MAS initSocket()
08-10 14:11:12.054  6110  6379 D BluetoothMapMasInstance:   masId = 00
08-10 14:11:12.054  6110  6379 D BluetoothMapMasInstance:   msgTypes = 0e
08-10 14:11:12.054  6110  6379 D BluetoothMapMasInstance:   masName = SMS/MMS
08-10 14:11:12.054  6110  6379 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-10 14:11:12.054  6110  6110 V BluetoothPbapService: Handler(): got msg=1
08-10 14:11:12.055  1025  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:12.055  6110  6110 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-10 14:11:12.055  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 14:11:12.056  2232  2232 D c       : Getting all permits...
08-10 14:11:12.056  2232  2232 D a       : Opening database...
08-10 14:11:12.056  6110  6379 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 14:11:12.057  6110  6380 V BluetoothPbapService: Pbap Service initSocket
08-10 14:11:12.057  6110  6379 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-10 14:11:12.057  6110  6379 V BluetoothMapMasInstance: Succeed to create listening socket 
08-10 14:11:12.058  6110  6379 D BluetoothMapMasInstance: Accepting socket connection...
08-10 14:11:12.058  1025  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:12.059  6110  6380 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 14:11:12.059  6110  6380 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-10 14:11:12.060  6110  6380 V BluetoothPbapService: Succeed to create listening socket 
08-10 14:11:12.060  6110  6380 V BluetoothPbapService: Accepting socket connection...
08-10 14:11:12.061  2232  2232 D a       : Opening database auth.proximity.permit_store...
08-10 14:11:12.062  2232  2232 D a       : Closing database...
,08-10 14:11:12.066  6145  6145 D LocalBluetoothProfileManager: Adding local A2DP profile
08-10 14:11:12.068  1025  1087 D BluetoothManagerService: Message: 30
08-10 14:11:12.069  6145  6145 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-10 14:11:12.071  1025  1087 D BluetoothManagerService: Message: 30
08-10 14:11:12.074  1025  1087 D BluetoothManagerService: Message: 30
,08-10 14:11:12.079  1025  1087 D BluetoothManagerService: Message: 30
08-10 14:11:12.081  6145  6145 D LocalBluetoothProfileManager: Adding local MAP profile
08-10 14:11:12.082  6145  6145 D BluetoothMap: Create BluetoothMap proxy object
08-10 14:11:12.082  1025  1087 D BluetoothManagerService: Message: 30
08-10 14:11:12.086  1025  1087 D BluetoothManagerService: Message: 30
,08-10 14:11:12.087  6145  6145 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-10 14:11:12.087  6110  6110 V BluetoothPbapService: Pbap Service onBind
08-10 14:11:12.092  6145  6145 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-10 14:11:12.094  6145  6145 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-10 14:11:12.101  6145  6145 D DockEventReceiver: finishStartingService: stopping service
,08-10 14:11:12.103  6145  6145 D BluetoothA2dp: Proxy object connected
,08-10 14:11:12.103  6145  6145 D A2dpProfile: Bluetooth service connected
08-10 14:11:12.119  6145  6145 D BluetoothHeadset: Proxy object connected
08-10 14:11:12.120  6145  6145 D HeadsetProfile: Bluetooth service connected
,08-10 14:11:12.121  6145  6145 D BluetoothInputDevice: Proxy object connected
08-10 14:11:12.122  6145  6145 D HidProfile: Bluetooth service connected
08-10 14:11:12.122  6145  6145 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 14:11:12.123  6145  6145 D PanProfile: Bluetooth service connected
08-10 14:11:12.124  6145  6145 D BluetoothMap: Proxy object connected
08-10 14:11:12.124  6145  6145 D MapProfile: Bluetooth service connected
08-10 14:11:12.124  6145  6145 D BluetoothMap: getConnectedDevices()
08-10 14:11:12.125  6110  6129 V BluetoothMapService: getConnectedDevices()
08-10 14:11:12.125  6145  6145 D BluetoothPbap: Proxy object connected
08-10 14:11:12.125  6145  6145 D PbapServerProfile: Bluetooth service connected
08-10 14:11:12.126  6145  6145 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-10 14:11:12.126  5996  5996 D UEI.SmartControl: IR Blaster version: 25672567
08-10 14:11:12.127  6145  6145 D BluetoothPermissionRequest: onReceive
08-10 14:11:12.129  6145  6145 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 14:11:12.129  6145  6145 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 14:11:12.129  6145  6145 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 14:11:12.131  6110  6110 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-10 14:11:12.132  6110  6110 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-10 14:11:12.139  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:12.140  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:12.140  5996  6373 D UEI.SmartControl: serial port data available: 4
08-10 14:11:12.142  6290  6290 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 14:11:12.144  6110  6110 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-10 14:11:12.144  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 14:11:12.152  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-10 14:11:12.156  6110  6144 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 14:11:12.156  6110  6144 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-10 14:11:12.157  6110  6110 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 14:11:12.157  6110  6110 V BtOppService: onCreate
08-10 14:11:12.157  6110  6144 D BluetoothAdapterProperties: Scan Mode:21
08-10 14:11:12.158  6110  6144 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-10 14:11:12.159  6110  6110 V BluetoothOppNotification: send message
08-10 14:11:12.160  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-10 14:11:12.162  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:12.163  6110  6110 V BtOppService: Starting RfcommListener
08-10 14:11:12.165  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:11:12.167  6110  6388 V BtOppService: Deleted complete outbound shares, number =  0
08-10 14:11:12.167  6110  6388 V BtOppService: Deleted complete inbound failed shares, number = 0
08-10 14:11:12.168  5996  5996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-10 14:11:12.168  6110  6388 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-10 14:11:12.168  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 14:11:12.168  5996  5996 E UEI.SmartControl: Services init done
08-10 14:11:12.168  5996  5996 D UEI.SmartControl: QS Service init finished
08-10 14:11:12.169  5996  5996 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 14:11:12.169  5996  5996 D UEI.SmartControl: QS Service version code: 201091
,08-10 14:11:12.170  5996  5996 D UEI.SmartControl: Service requested: Control
08-10 14:11:12.170  5996  6392 I UEI.SmartControl: Device manager: loading config....
08-10 14:11:12.171  5996  5996 D UEI.SmartControl: Internal service binding...
08-10 14:11:12.171  6290  6290 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-10 14:11:12.172  5996  6011 I UEI.SmartControl: ------ IControl API: 11
08-10 14:11:12.172  5996  6011 D UEI.SmartControl: File observer start...
08-10 14:11:12.172  5996  6011 E UEI.SmartControl: IR Port is disabled: false
08-10 14:11:12.172  6110  6388 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23a0d5ff on behalf of 
08-10 14:11:12.172  5996  6011 D UEI.SmartControl: Starting file observer...
08-10 14:11:12.172  5996  6392 D UEI.SmartControl: ----------- loading internal config...
08-10 14:11:12.173  5996  6011 I UEI.SmartControl: Registering callback...
08-10 14:11:12.173  5996  6012 I UEI.SmartControl: ------ IControl API: 19
08-10 14:11:12.174  5996  6012 I UEI.SmartControl: Registering Services Ready callback...
08-10 14:11:12.175  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:12.177  6110  6110 D BluetoothOppPreference: Dumping Names:  
08-10 14:11:12.177  6110  6110 D BluetoothOppPreference: {}
08-10 14:11:12.177  6110  6110 D BluetoothOppPreference: Dumping Channels:  
08-10 14:11:12.177  6110  6110 D BluetoothOppPreference: {}
08-10 14:11:12.177  6110  6110 V BtOppService: onStartCommand
08-10 14:11:12.180  6110  6394 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 14:11:12.180  6110  6394 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 14:11:12.181  5996  6392 E UEI.SmartControl: Loading SETTINGS...
,08-10 14:11:12.181  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:12.181  6110  6110 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:12.181  6110  6110 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 14:11:12.183  6110  6110 V BluetoothOppNotification: new notify threadi!
08-10 14:11:12.183  6110  6110 V BluetoothOppNotification: send delay message
08-10 14:11:12.184  6110  6110 V BtOppService: start RfcommListener
08-10 14:11:12.184  6110  6395 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 14:11:12.184  5996  6392 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-10 14:11:12.185  6110  6395 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1aed4215 on behalf of 
08-10 14:11:12.185  6110  6110 V BtOppService: RfcommListener started
08-10 14:11:12.185  6110  6110 V BtOppService: ContentObserver received notification
08-10 14:11:12.185  6110  6110 V BtOppService: ContentObserver received notification
08-10 14:11:12.186  6110  6395 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-10 14:11:12.186  6110  6396 V BtOppRfcommListener: Starting RFCOMM listener....
08-10 14:11:12.186  1025  1041 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:12.187  6110  6395 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 14:11:12.187  6110  6396 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 14:11:12.188  6110  6395 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3265b92a on behalf of 
08-10 14:11:12.188  5996  6391 I UEI.SmartControl: Notify AllClients services are ready: 0
08-10 14:11:12.188  5996  6391 D UEI.SmartControl: -----service ready thread exits
08-10 14:11:12.188  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:12.188  6110  6396 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-10 14:11:12.188  6110  6396 V BtOppRfcommListener: Started RFCOMM listener....
08-10 14:11:12.188  6110  6396 I BtOppRfcommListener: Accept thread started.
08-10 14:11:12.188  6290  6305 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-10 14:11:12.188  6110  6396 V BtOppRfcommListener: Accepting connection...
08-10 14:11:12.189  6290  6326 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-10 14:11:12.189  6290  6326 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-10 14:11:12.189  6110  6395 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 14:11:12.189  6290  6290 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 14:11:12.190  6110  6394 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1436d31b on behalf of 
08-10 14:11:12.190  6110  6395 V BluetoothOppNotification: outbound notification was removed.
08-10 14:11:12.190  6110  6395 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 14:11:12.191  6110  6394 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 14:11:12.191  6110  6394 V BluetoothOp,pProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 14:11:12.191  6290  6290 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-10 14:11:12.192  6290  6290 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-10 14:11:12.193  6110  6394 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@318c4cb8 on behalf of 
08-10 14:11:12.193  6110  6394 V BluetoothOppNotification: update too frequent, put in queue
08-10 14:11:12.194  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:12.194  6110  6394 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-10 14:11:12.194  6290  6290 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-10 14:11:12.194  6110  6110 V BluetoothFtpService: Ftp Service onCreate
08-10 14:11:12.194  6110  6110 I BluetoothFtpService: Ftp Service onCreate
08-10 14:11:12.194  6110  6395 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@266cea91 on behalf of 
08-10 14:11:12.194  6290  6290 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-10 14:11:12.195  5996  6011 I UEI.SmartControl: ------ IControl API: 8
08-10 14:11:12.194  6110  6110 V BluetoothFtpService: Ftp Service onStartCommand
08-10 14:11:12.195  6110  6395 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 14:11:12.195  6110  6110 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:12.195  6110  6110 V BluetoothFtpService: Starting Listening on sockets
08-10 14:11:12.195  6110  6110 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 14:11:12.196  6110  6110 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 14:11:12.196  6110  6110 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 14:11:12.196  6110  6110 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:12.196  6110  6110 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-10 14:11:12.196  6110  6395 V BluetoothOppNotification: inbound notification was removed.
08-10 14:11:12.196  6110  6395 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 14:11:12.196  6110  6110 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 14:11:12.197  6110  6395 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d6585f7 on behalf of 
08-10 14:11:12.197  6110  6110 V BluetoothFtpService: Handler(): got msg=1
08-10 14:11:12.197  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:12.198  6290  6290 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-10 14:11:12.198  6110  6110 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-10 14:11:12.198  6110  6110 V BluetoothFtpService: Ftp Service initSocket
08-10 14:11:12.199  6290  6290 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-10 14:11:12.199  6290  6290 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-10 14:11:12.199  6290  6290 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-10 14:11:12.199  6290  6290 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-10 14:11:12.199  6290  6290 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-10 14:11:12.200  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-10 14:11:12.200  6290  6290 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-10 14:11:12.200  1025  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 14:11:12.200  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-10 14:11:12.201  6110  6110 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 14:11:12.203  6290  6290 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-10 14:11:12.203  6110  6110 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,08-10 14:11:12.205  6110  6110 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-10 14:11:12.205   323  6362 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
08-10 14:11:12.206   323  6360 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-10 14:11:12.206  6110  6397 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-10 14:11:12.209  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 14:11:12.212  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:12.215  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:12.215  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:12.215  6290  6290 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 14:11:12.216  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:12.216  6290  6290 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-10 14:11:12.216  6110  6110 V BluetoothSapService: Sap Service onCreate
08-10 14:11:12.216  6290  6290 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-10 14:11:12.217  6110  6110 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:12.217  6110  6110 V BluetoothSapService: state: 12
08-10 14:11:12.217  6110  6110 V BluetoothSapService: Starting SAP server process
08-10 14:11:12.218  6110  6110 V BluetoothSapService: SAP Service startRfcommListenerThread
08-10 14:11:12.219  6110  6399 V BluetoothSapService: Sap Service initRfcommSocket
08-10 14:11:12.219   323  6364 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
08-10 14:11:12.220  1025  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:12.220  6110  6399 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 14:11:12.221  6110  6399 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-10 14:11:12.221  6110  6399 V BluetoothSapService: Succeed to create listening socket 
08-10 14:11:12.221  6110  6399 V BluetoothSapService: Accepting socket connection...
08-10 14:11:12.212  6398  6398 W sapd    : type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:12.212  6398  6398 W sapd    : type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:12.225  6290  6290 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 14:11:12.225  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 14:11:12.226  6290  6290 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 14:11:12.226  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-10 14:11:12.226  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 14:11:12.227  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-10 14:11:12.228  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-10 14:11:12.228  6398  6398 V BT_SAP  : Event pipe created
08-10 14:11:12.228  6398  6398 V BT_SAP  : create_server_socket qcom.sap.server
08-10 14:11:12.228  6398  6398 V BT_SAP  : created socket fd 6
08-10 14:11:12.228  6290  6290 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470831072228]
,08-10 14:11:12.229  1025  1040 I ActivityManager: Killing 5646:com.android.contacts/u0a19 (adj 15): empty #17
,08-10 14:11:12.237   323  6360 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-10 14:11:12.243  6290  6400 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-10 14:11:12.258  1025  6361 D LocSvc_java: NTP server : europe.pool.ntp.org
08-10 14:11:12.258  1025  6361 D LocSvc_java: NTP server returned: 1470831072047 (Wed Aug 10 14:11:12 GMT+02:00 2016) reference: 135458 certainty: 19 system time offset: -211
08-10 14:11:12.258  1025  6361 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
,08-10 14:11:12.268   323   867 D LGDataListener: argv[0]=dsqncommand
,08-10 14:11:12.268   323   867 D LGDataListener: argv[1]=wlan0
08-10 14:11:12.268   323   867 D LGDataListener: argv[2]=1
08-10 14:11:12.268   323   867 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-10 14:11:12.269  1025  1085 D DSQN    : DSQM DsqnNotification wlan0  1
08-10 14:11:12.270  1025  1085 D DSQN    : start to monitor internet connection
,08-10 14:11:12.284  1025  2098 W libprocessgroup: failed to open /acct/uid_10019/pid_5646/cgroup.procs: No such file or directory
,08-10 14:11:12.299  1025  6284 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 12:11:12 GMT], X-Android-Received-Millis=[1470831072299], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470831072267]}
,08-10 14:11:12.299  1025  6284 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-10 14:11:12.300  1025  6284 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-10 14:11:12.300  1025  1538 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
08-10 14:11:12.300  1025  1538 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-10 14:11:12.301  1025  1538 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 14:11:12.301  1025  1538 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 14:11:12.301  1025  1538 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 14:11:12.301  1025  1538 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
08-10 14:11:12.301  1025  1538 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-10 14:11:12.301  1025  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:12.301  1025  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 14:11:12.302  1025  1538 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 14:11:12.302  1025  1538 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:12.302  1025  1531 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:12.303  1025  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 14:11:12.303  1869  1869 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:12.303  1596  1804 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 14:11:12.303  1869  1869 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 14:11:12.303  1025  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 14:11:12.305  1025  1527 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-10 14:11:12.318  6290  6290 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-10 14:11:12.320  6290  6290 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-10 14:11:12.321  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-10 14:11:12.322  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-10 14:11:12.322  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-10 14:11:12.325  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-10 14:11:12.326  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-10 14:11:12.339  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 14:11:12.340  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:12.342  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:12.344  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-10 14:11:12.400  1025  1531 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 14:11:12.401  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 14:11:12.403  1025  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 14:11:12.404  1025  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 14:11:12.405  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 14:11:12.407  1025  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 14:11:12.409  1025  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
08-10 14:11:12.409  1025  1538 D ConnectivityService: identical MTU - not setting
08-10 14:11:12.410  1025  1538 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-10 14:11:12.410  1025  1538 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-10 14:11:12.411  1025  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:12.411  1025  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 14:11:12.412  1025  1538 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 14:11:12.414  1596  1804 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-10 14:11:12.573  1025  1999 D WifiServiceImplEx: setWifiEnabled: false pid=5818, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 14:11:12.573  1025  1999 D WifiService: setWifiEnabled: false pid=5818, uid=10118
08-10 14:11:12.573  1025  1999 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 14:11:12.600  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-10 14:11:12.600  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 14:11:12.600  1025  1025 D Ulp_jni : JNI:system_update. Event-4
,08-10 14:11:12.602  1025  1531 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 14:11:12.602  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 14:11:12.603  1025  1531 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-10 14:11:12.603  1025  1531 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-10 14:11:12.603  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-10 14:11:12.604  1025  1531 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 14:11:12.604  1025  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 14:11:12.604  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 14:11:12.608  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 14:11:12.608  1025  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-10 14:11:12.616  1025  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 14:11:12.617  1025  1528 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:12.617  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:12.617  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 14:11:12.618  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 14:11:12.618  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 14:11:12.618  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 14:11:12.619  1025  1531 D WifiNative-wlan0: SET ps 1: returned true
08-10 14:11:12.619  1025  6289 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:12.624   323   868 D CommandListener: Clearing all IP addresses on wlan0
,08-10 14:11:12.710  1025  1025 D WifiHS20: hidePasspointNotification off =false
,08-10 14:11:12.714  1965  1965 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-10 14:11:12.729  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:12.729  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:12.729  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 14:11:12.731  1025  1025 D WifiHS20: hidePasspointNotification off =false
08-10 14:11:12.733  1025  1528 D LGWifiP2pService: InactiveState{ when=-34ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:12.733  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-35ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:12.733  1025  1528 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3a257473
08-10 14:11:12.734  1025  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:12.735  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:12.735  1025  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:12.736  1025  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-10 14:11:12.743  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:12.743  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:12.743  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 14:11:12.744  1025  1025 D WifiScanningService: SCAN_AVAILABLE : 1
08-10 14:11:12.744  1025  1549 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:12.744  1025  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 14:11:12.744  1025  1538 D ConnectivityService: ignoring duplicate network state non-change
08-10 14:11:12.745  1025  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-10 14:11:12.749  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:12.749  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:12.750  1025  1025 D RttService: SCAN_AVAILABLE : 1
08-10 14:11:12.756  1025  1550 D RttService: EnabledState got{ when=-6ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 14:11:12.761  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:12.761  1025  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 14:11:12.762  1025  1531 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 14:11:12.799  1025  1528 D LGWifiP2pService: P2pDisablingState
08-10 14:11:12.799  1025  1528 D LGWifiP2pService: P2pDisablingState{ when=-66ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:12.799  1025  1528 D LGWifiP2pService: p2p socket connection lost
08-10 14:11:12.800  1025  1528 D LGWifiP2pService: P2pDisabledState
,08-10 14:11:12.804  1025  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-10 14:11:12.804  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 14:11:12.805  6139  6139 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 14:11:12.817  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 14:11:12.817  1965  1965 D WfdsService: WifiP2pState is changed : false
,08-10 14:11:12.819  1965  2345 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-10 14:11:12.819  1965  2345 D WfdsService: Set the WFDS Monitor: false
08-10 14:11:12.820  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:12.823  1965  2345 D WfdsMonitor: WFDS Monitor is stopped
08-10 14:11:12.823  1965  2345 D WfdsService: STATE : WfdsDisabledState - enter
08-10 14:11:12.824  1965  6186 D CtrlSupplicant: Received on exit socket, terminate
08-10 14:11:12.824  1965  6186 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-10 14:11:12.824  1965  6186 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-10 14:11:12.824  1965  6186 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-10 14:11:12.837  1965  2346 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,08-10 14:11:12.841  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:12.841  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:12.841  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 14:11:12.842  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 14:11:12.842  1025  1528 D LGWifiP2pService: P2pDisabledState{ when=-38ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:12.842  1025  1528 D LGWifiP2pService: DefaultState{ when=-38ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:12.842  1965  2345 W WfdsService: DefaultState - msg [9445378] is not handled
08-10 14:11:12.843  1025  1531 D WifiNative-wlan0: SET ps 1: returned true
08-10 14:11:12.851  1025  6289 D DhcpStateMachine: StoppedState
08-10 14:11:12.851  1025  6289 D DhcpStateMachine: StoppedState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 14:11:12.860  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:12.874   323   868 D CommandListener: Clearing all IP addresses on wlan0
08-10 14:11:12.875  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:12.876  1025  1538 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
,08-10 14:11:12.877  1025  1538 D DSQN    : disableDataServiceNotify
08-10 14:11:12.877  1025  1538 D DSQN    : stop dsqn bin
08-10 14:11:12.882  1025  1025 D WifiHS20: hidePasspointNotification off =false
08-10 14:11:12.883  1025  1538 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-10 14:11:12.883  1025  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:12.883  1025  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 14:11:12.884  1025  1538 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 14:11:12.884  1025  1531 D WifiNative-p2p0: doBoolean: TERMINATE
08-10 14:11:12.884  1025  1538 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-10 14:11:12.884  1025  6284 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:12.884  1025  6284 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:12.884  1025  6284 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-10 14:11:12.885  1025  1538 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-10 14:11:12.885  1025  1538 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-10 14:11:12.885  1025  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 14:11:12.885  1025  1531 D WifiNative-p2p0: TERMINATE: returned true
08-10 14:11:12.886  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 14:11:12.886  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-10 14:11:12.886  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 14:11:12.888  1596  1804 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-10 14:11:12.889  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-10 14:11:12.889  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:12.889  1025  1531 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-10 14:11:12.890  1025  1531 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-10 14:11:12.890  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:12.890  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:12.890  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 14:11:12.891  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 14:11:12.891  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 14:11:12.891  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 14:11:12.894  1025  1538 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:12.894  1025  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 14:11:12.894  1025  1025 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 14:11:12.895  1025  1527 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 14:11:12.900  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 14:11:12.900  1025  1538 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:12.901  1025  1538 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:12.901  1025  1538 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:12.901  1025  1531 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:12.901  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-10 14:11:12.901  1025  1538 D NetworkManagementService: Removing idletimer
,08-10 14:11:12.901  1025  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 14:11:12.901  1025  1025 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 14:11:12.902  1025  1025 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,08-10 14:11:12.902  1025  1025 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 14:11:12.902  1025  1538 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:12.902  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-10 14:11:12.902  1025  1025 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-10 14:11:12.902  1869  1869 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 14:11:12.903  1869  1869 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 14:11:12.905  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:12.906  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-10 14:11:12.908  1025  1527 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 14:11:12.909  1025  1025 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 14:11:12.909  1025  1025 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 14:11:12.909  1025  1025 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 14:11:12.909  1025  1025 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 14:11:12.919  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:12.919  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:12.919  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:12.919  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:11:12.919  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:11:12.919  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:12.919  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:12.919  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 14:11:12.922  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:12.925  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:12.927  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:12.927  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:12.927  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:12.927  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:11:12.927  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:11:12.927  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:12.927  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:12.927  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:12.929  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:12.933  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:12.933  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 14:11:12.939  6290  6290 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 14:11:12.942  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:12.947  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 14:11:12.947  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 14:11:12.947  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 14:11:12.952  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 14:11:12.959  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:12.966  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:12.968  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:12.971  6290  6290 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-10 14:11:12.975  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:12.975  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 14:11:12.978  6139  6139 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-10 14:11:12.978  6139  6139 I wpa_supplicant: monitor socket send errors count : 1
08-10 14:11:12.978  6139  6139 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1965-2\x00 that cannot receive messages
08-10 14:11:12.979  1025  6165 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-10 14:11:12.979  1025  6165 D WifiMonitor: Dropping event because (p2p0) is stopped
08-10 14:11:12.980  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:12.980  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 14:11:12.980  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 14:11:12.980  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 14:11:12.981  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:12.982  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:12.984  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 14:11:12.991  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:12.999  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 14:11:13.000  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 14:11:13.002  6290  6290 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 14:11:13.012  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 14:11:13.012  6139  6139 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-10 14:11:13.014  6139  6139 W wpa_supplicant: USIM:  scard_deinit function
08-10 14:11:13.015  1025  1087 D Tethering: InitialState.processMessage what=4
08-10 14:11:13.015  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-10 14:11:13.015  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 14:11:13.015  1025  6165 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 14:11:13.016  1025  6165 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-10 14:11:13.016  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 14:11:13.016  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 14:11:13.016  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 14:11:13.017  1025  1531 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=136217
08-10 14:11:13.017  1025  1531 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=136218
08-10 14:11:13.018  1025  1531 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=136218  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 14:11:13.019  1025  1531 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=136219  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 14:11:13.019  1025  1087 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 14:11:13.021  1025  1531 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:13.022  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-10 14:11:13.028  6169  6437 W FormManager: Network not available. Please check & try again.
08-10 14:11:13.030  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:13.030  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 14:11:13.031  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:13.032  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:13.037  6169  6438 V FormManager: Network unavailable.
,08-10 14:11:13.040  6169  6438 V FormManager: Network unavailable.
08-10 14:11:13.047  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 14:11:13.047  6145  6145 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 14:11:13.047  6145  6145 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 14:11:13.047  6145  6145 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 14:11:13.048  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 14:11:13.049  6145  6145 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 14:11:13.049  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 14:11:13.049  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 14:11:13.049  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 14:11:13.049  6145  6145 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 14:11:13.049  6145  6145 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-10 14:11:13.067  6139  6139 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-10 14:11:13.068  1025  6165 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-10 14:11:13.068  1025  6165 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-10 14:11:13.068  1025  6165 D WifiMonitor: Disconnecting from the supplicant, no more events
08-10 14:11:13.069  1025  1531 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-10 14:11:13.175  1965  1965 D WfdsService: Supplicant Connection state is changed : false
,08-10 14:11:13.176  1965  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-10 14:11:13.176  1965  2345 D WfdsService: Set the WFDS Monitor: false
08-10 14:11:13.176  1965  2345 D WfdsMonitor: WFDS Monitor is stopped
08-10 14:11:13.179  1025  1531 D WifiOffDelayIfNotUsed: stopMonitoring
08-10 14:11:13.179  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 14:11:13.179  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-10 14:11:13.179  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-10 14:11:13.182  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 14:11:13.183  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 14:11:13.184  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:13.186  6110  6110 V BluetoothOppNotification: new notify threadi!
08-10 14:11:13.187  6110  6110 V BluetoothOppNotification: send delay message
08-10 14:11:13.187  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 14:11:13.189  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-10 14:11:13.191  6110  6439 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-10 14:11:13.191  1025  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-10 14:11:13.192  1025  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,08-10 14:11:13.195  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 14:11:13.198  2468  2468 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:13.202  6110  6439 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d628a93 on behalf of 
08-10 14:11:13.204  6110  6439 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-10 14:11:13.204  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:13.204  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:13.204  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:13.204  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:11:13.204  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:11:13.204  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:13.204  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:13.204  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:11:13.205  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:13.207  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 14:11:13.208  6110  6439 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 14:11:13.213  6110  6439 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29dffad0 on behalf of 
08-10 14:11:13.214  6110  6439 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 14:11:13.214  3065  6440 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 14:11:13.217  6110  6439 V BluetoothOppNotification: outbound notification was removed.
08-10 14:11:13.217  6110  6439 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-10 14:11:13.218  6110  6439 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fa95ac9 on behalf of 
08-10 14:11:13.219  6110  6439 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 14:11:13.219  3065  6441 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 14:11:13.220  3065  6441 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 14:11:13.222  6192  6192 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-10 14:11:13.222  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 14:11:13.222  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 14:11:13.224  6110  6439 V BluetoothOppNotification: inbound notification was removed.
08-10 14:11:13.224  6110  6439 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 14:11:13.225  6110  6439 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@153b15ce on behalf of 
08-10 14:11:13.228  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 14:11:13.231  6169  6443 W FormManager: Network not available. Please check & try again.
,08-10 14:11:13.234  6169  6444 V FormManager: Network unavailable.
,08-10 14:11:13.236  6169  6444 V FormManager: Network unavailable.
08-10 14:11:13.236  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:14.018  1025  1531 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1952258786] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 14:11:14.021  1025  1531 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1952258788] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 14:11:14.940  1025  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 14:11:14.948  1025  1087 D Tethering: MasterInitialState.processMessage what=3
08-10 14:11:14.956  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:11:14.962  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:14.964  1025  1082 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:14.969  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-10 14:11:14.974  5096  5117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 14:11:14.989  5189  5189 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-10 14:11:15.042  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 14:11:15.113  1025  2099 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6470 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-10 14:11:15.212  6470  6470 I AppUp4:AppBoxCP: onCreate
08-10 14:11:15.213  6470  6470 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-10 14:11:15.223  6470  6470 I AppUp4:DB:  setFingerPrint start
08-10 14:11:15.223  6470  6470 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-10 14:11:15.233  6470  6470 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-10 14:11:15.233  6470  6470 I AppUp4:DB:  SDK version = 21
08-10 14:11:15.233  6470  6470 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-10 14:11:15.235  6470  6470 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-10 14:11:15.236  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 14:11:15.236  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:15.238  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 14:11:15.238  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 14:11:15.243  6470  6470 I AppUp4:CustModeStarterReceiver: onReceive
08-10 14:11:15.251  1025  1082 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:15.258  1025  1082 E GpsLocationProvider: No APN found to select.
,08-10 14:11:15.271  1025  1964 I art     : Explicit concurrent mark sweep GC freed 114246(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.029ms total 154.420ms
08-10 14:11:15.271  1834  6454 I CheckinService: active receiver: enabled
,08-10 14:11:15.282  6470  6470 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 14:11:15.283  6470  6470 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 14:11:15.290  6470  6470 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3dc49d0d
08-10 14:11:15.290  6470  6470 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 14:11:15.290  6470  6470 D AppUp4:CustFacade: isPhone : true
08-10 14:11:15.290  6470  6470 D AppUp4:CustModeStarterReceiver: begin check event
08-10 14:11:15.291  6470  6470 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-10 14:11:15.291  6470  6470 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-10 14:11:15.296  6470  6490 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-10 14:11:15.296  6470  6490 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-10 14:11:15.296  6470  6490 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-10 14:11:15.299  1025  1999 I ActivityManager: Killing 5671:com.lge.email/u0a23 (adj 15): empty #17
,08-10 14:11:15.348  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:15.349  1025  2064 W libprocessgroup: failed to open /acct/uid_10023/pid_5671/cgroup.procs: No such file or directory
08-10 14:11:15.349  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-10 14:11:15.354  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 14:11:15.356  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 14:11:15.369  3065  6494 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-10 14:11:15.372  3065  6495 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE,
08-10 14:11:15.373  3065  6495 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 14:11:15.418  1025  2030 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6496 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-10 14:11:15.521  6496  6496 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 14:11:15.522  6496  6496 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 14:11:15.523  6496  6496 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 14:11:15.524  6496  6496 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 14:11:15.607  1025  1040 D WifiServiceImplEx: setWifiEnabled: true pid=5818, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-10 14:11:15.608  1025  1040 D WifiService: setWifiEnabled: true pid=5818, uid=10118
08-10 14:11:15.608  1025  1040 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 14:11:15.621  1025  1531 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-10 14:11:15.621  1025  1531 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-10 14:11:15.624  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-10 14:11:15.624  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 14:11:15.625  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1025] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-10 14:11:15.625  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 14:11:15.625  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1025] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-10 14:11:15.625  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 14:11:15.626  1025  1531 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-10 14:11:15.626  1025  1531 E WifiHW  : unknown target_country: EU , set to default
08-10 14:11:15.626  1025  1531 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-10 14:11:15.626  1025  1531 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-10 14:11:15.627  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-10 14:11:15.628  1025  1531 I WifiUtil: gEnableBmps=1
08-10 14:11:15.642  6496  6496 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-10 14:11:15.658  6496  6496 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-10 14:11:15.704  6496  6496 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-10 14:11:15.745  6496  6496 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 14:11:15.745  6496  6496 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 14:11:15.895  1025  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:15.899  1025  1087 D Tethering: MasterInitialState.processMessage what=3
08-10 14:11:15.901  6496  6496 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 14:11:15.905  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:15.907  1025  1082 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:15.907  1025  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:15.911  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:15.916  5189  5189 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-10 14:11:15.917  1025  1087 D Tethering: MasterInitialState.processMessage what=3
,08-10 14:11:15.927  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:15.929  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:11:15.935  1025  1082 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:15.935  5189  5189 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-10 14:11:15.935  1025  1082 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:15.936  1025  1082 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 14:11:15.972  3108  3108 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 14:11:15.972  3108  3108 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:15.974  3108  3108 I LgeMiscReceiver: networkInfo.isConnected() = true
08-10 14:11:15.974  3108  3108 D PhoneState: setPdpRejectCasuse : false
,08-10 14:11:15.978  6496  6496 I HubEmail: JNI_OnLoad()
08-10 14:11:15.978  6496  6496 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 14:11:15.978  6496  6496 I HubEmail: registerNatives()
08-10 14:11:15.978  6496  6496 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 14:11:15.978  6496  6496 I HubEmail: registerNativeMethods()
08-10 14:11:15.978  6496  6496 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 14:11:15.979  6496  6496 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-10 14:11:16.015  1025  1041 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6537 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-10 14:11:16.023  6169  6525 W FormManager: Network not available. Please check & try again.
08-10 14:11:16.025  6496  6528 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:16.035  6169  6527 V FormManager: Network unavailable.
,08-10 14:11:16.040  6169  6527 V FormManager: Network unavailable.
08-10 14:11:16.046  1025  1709 I ActivityManager: Killing 5706:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-10 14:11:16.081  1025  1999 W libprocessgroup: failed to open /acct/uid_10027/pid_5706/cgroup.procs: No such file or directory
08-10 14:11:16.155  6537  6537 D LgDataFeature: LgDataFeature() Constructor: none
08-10 14:11:16.156  6537  6537 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 14:11:16.161  6537  6537 D PhoneMonitor: Register our PhoneStateListener
,08-10 14:11:16.190  6537  6537 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-10 14:11:16.195  6537  6537 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-10 14:11:16.222  6537  6537 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-10 14:11:16.228  6537  6537 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-10 14:11:16.229  6537  6537 D TelephonyAutoProfiling: [parse] Load xml
,08-10 14:11:16.236  6537  6537 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-10 14:11:16.236  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-10 14:11:16.236  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-10 14:11:16.237  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
,08-10 14:11:16.237  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-10 14:11:16.237  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-10 14:11:16.237  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-10 14:11:16.237  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-10 14:11:16.237  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-10 14:11:16.237  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-10 14:11:16.237  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-10 14:11:16.237  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-10 14:11:16.237  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-10 14:11:16.237  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-10 14:11:16.238  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-10 14:11:16.238  6537  6537 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-10 14:11:16.238  6537  6537 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-10 14:11:16.251  6537  6537 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-10 14:11:16.260  1025  2030 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6567 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-10 14:11:16.263  1025  2030 I ActivityManager: Killing 5791:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-10 14:11:16.333  1025  2064 W libprocessgroup: failed to open /acct/uid_10061/pid_5791/cgroup.procs: No such file or directory
08-10 14:11:16.377  1025  1087 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-10 14:11:16.382  1025  1087 D Tethering: InitialState.processMessage what=4
08-10 14:11:16.384  1025  1087 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 14:11:16.391   323   868 D SoftapController: Softap fwReload - Ok
,08-10 14:11:16.395  1025  1531 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (741ms)
08-10 14:11:16.398   323   868 D CommandListener: Setting iface cfg
08-10 14:11:16.398   323   868 D CommandListener: Trying to bring down wlan0
08-10 14:11:16.398   323   868 D CommandListener: Clearing all IP addresses on wlan0
08-10 14:11:16.401  1025  1531 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-10 14:11:16.403  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 14:11:16.403  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-10 14:11:16.403  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 14:11:16.404  1025  1531 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-10 14:11:16.404  1025  1531 D WifiMonitor: connecting to supplicant
08-10 14:11:16.405  1025  1531 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-10 14:11:16.407  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:16.407  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-10 14:11:16.402  6585  6585 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:16.402  6585  6585 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:16.413  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-10 14:11:16.415  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:16.417  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:11:16.432  6585  6585 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-10 14:11:16.468  6585  6585 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-10 14:11:16.468  6585  6585 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-10 14:11:16.556  6585  6585 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-10 14:11:16.570  6585  6585 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-10 14:11:16.583  6585  6585 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-10 14:11:16.616  6585  6585 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-10 14:11:16.717  1025  2030 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6587 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-10 14:11:16.719  1025  2030 I ActivityManager: Killing 5892:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-10 14:11:16.763  1025  1040 W libprocessgroup: failed to open /acct/uid_10080/pid_5892/cgroup.procs: No such file or directory
,08-10 14:11:16.813  6587  6587 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,08-10 14:11:16.815  6587  6587 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
08-10 14:11:16.824  6587  6587 V DrmService: Service onCreate
08-10 14:11:16.825  6587  6587 D DrmService: Received new request = 2
08-10 14:11:16.830  6587  6607 I DrmSntpClient: Start Sync process
,08-10 14:11:16.830  6587  6607 D DrmSntpClient: Server : 0
08-10 14:11:16.859  1025  1964 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6608 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-10 14:11:16.861  6587  6607 D DrmSntpClient: Automatic sync but WiFi isn't enabled
08-10 14:11:16.866  6587  6587 D DrmService: Completed !! request = 2
08-10 14:11:16.866  6587  6587 D DrmService: Request count = 0
08-10 14:11:16.867  6587  6587 V DrmService: Service onDestroy
08-10 14:11:16.868  1025  1963 I ActivityManager: Killing 5913:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-10 14:11:16.878   363   363 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 19.913ms
,08-10 14:11:16.898   363   363 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 581us total 19.408ms
,08-10 14:11:16.915   363   363 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 350us total 16.001ms
,08-10 14:11:16.926  1025  2106 W libprocessgroup: failed to open /acct/uid_10097/pid_5913/cgroup.procs: No such file or directory
,08-10 14:11:16.950  6608  6608 I art     : Almond Protected OAT
,08-10 14:11:17.000  6608  6608 D WeatherApplication: removeAccount
,08-10 14:11:17.001  6608  6608 D WeatherApplication: Account.length = 0
,08-10 14:11:17.002  6608  6608 E WeatherApplication: OPERATOR:OPEN
,08-10 14:11:17.007  6608  6608 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:11:17
,08-10 14:11:17.011  6608  6608 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-10 14:11:17.011  6608  6608 D Weather.Utils: 2 : All the weather widget is gone.
08-10 14:11:17.013  6608  6608 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-10 14:11:17.015  6608  6608 D WeatherAncestor: connectivity changed - connection : true
08-10 14:11:17.016  6608  6608 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-10 14:11:17.029  6608  6608 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 14:11:17.029  6608  6608 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 14:11:17.030  6608  6608 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-10 14:11:17.068  6608  6608 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 14:11:17.068  6608  6608 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:11:17
,08-10 14:11:17.129  1025  1963 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6626 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 14:11:17.130  1025  1963 I ActivityManager: Killing 5949:com.lge.eula/1000 (adj 15): empty #17
,08-10 14:11:17.167  5996  6393 D UEI.SmartControl: Internal timer expired: 2
08-10 14:11:17.168  5996  6393 D UEI.SmartControl: unbind internal service
,08-10 14:11:17.187  1025  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_5949/cgroup.procs: No such file or directory
,08-10 14:11:17.222  6585  6585 E wpa_supplicant: USIM:  scard_init function
,08-10 14:11:17.222  6585  6585 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-10 14:11:17.298   278   348 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 14:11:17.299   278   348 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 14:11:17.299   278   348 W Vold    : Returning OperationFailed - no handler for errno 0
,08-10 14:11:17.299  6626  6644 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 14:11:17.301   278   348 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 14:11:17.301   278   348 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 14:11:17.301   278   348 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 14:11:17.302  6626  6644 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 14:11:17.312   278   348 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 14:11:17.312   278   348 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 14:11:17.312   278   348 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 14:11:17.314  6626  6647 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-10 14:11:17.317   278   348 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 14:11:17.317   278   348 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 14:11:17.317   278   348 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 14:11:17.317  6626  6647 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 14:11:17.346  6585  6585 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 14:11:17.350  1025  1087 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-10 14:11:17.351  5996  6378 D serial_port: close(fd = 24)
08-10 14:11:17.355  5996  6378 I UEI.SmartControl: Serial port is closed.
08-10 14:11:17.357  6585  6585 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 14:11:17.357  6585  6585 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 14:11:17.408  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-10 14:11:17.409  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-10 14:11:17.409  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-10 14:11:17.409  1025  1531 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-10 14:11:17.410  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:17.410  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-10 14:11:17.411  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:17.411  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:17.412  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:17.412  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 14:11:17.412  1025  1531 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-10 14:11:17.412  1025  1531 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-10 14:11:17.413  1025  1531 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-10 14:11:17.413  1025  1531 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-10 14:11:17.413  1025  1531 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-10 14:11:17.414  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 14:11:17.414  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-10 14:11:17.414  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 14:11:17.414  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:17.414  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:17.414  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:17.414  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:17.414  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 14:11:17.415  1025  1531 D WifiNative-wlan0: doBoolean: SET update_config 1
08-10 14:11:17.415  1025  1531 D WifiNative-wlan0: SET update_config 1: returned true
08-10 14:11:17.415  1025  1531 D WifiConfigStore: Loading config and enabling all networks 
08-10 14:11:17.416  1025  1531 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-10 14:11:17.419  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:17.419  1025  1531 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-10 14:11:17.421  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-10 14:11:17.422  1025  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-10 14:11:17.424  1965  1965 D WfdService: Waiting for WifiP2p enabling
08-10 14:11:17.427  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:17.427  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:17.427  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:17.427  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:17.427  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:11:17.427  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:17.427  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:17.427  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:17.429  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:17.429  1025  1531 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-10 14:11:17.432  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:17.432  5818  5818 V ,io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:17.432  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:17.432  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:17.432  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:11:17.432  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:17.432  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:17.432  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:17.434  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 14:11:17.443  1025  1531 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-10 14:11:17.443  1025  1531 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-10 14:11:17.445  1025  1531 D WifiStateMachine: enableVerboseLogging : level 2
08-10 14:11:17.445  1025  1531 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-10 14:11:17.446  1025  1531 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-10 14:11:17.446  1025  1531 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-10 14:11:17.446  1025  1531 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-10 14:11:17.446  1025  1531 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-10 14:11:17.447  1025  1531 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-10 14:11:17.447  1025  1531 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-10 14:11:17.447  1025  1531 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-10 14:11:17.448  1025  1531 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-10 14:11:17.448  1025  1531 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-10 14:11:17.448  1025  1531 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-10 14:11:17.449  1025  1531 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-10 14:11:17.449  1025  1531 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-10 14:11:17.449  1025  1531 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-10 14:11:17.450  1025  1531 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 14:11:17.451  1025  1531 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-10 14:11:17.451  1025  1531 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-10 14:11:17.451  1025  1531 D WifiNative-HAL: Setting external_sim to 1
08-10 14:11:17.451  1025  1531 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-10 14:11:17.452  1025  1531 D WifiNative-wlan0: SET external_sim 1: returned true
08-10 14:11:17.452  1025  1531 I WifiNative-HAL: startHal
08-10 14:11:17.452  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x987e78dc
08-10 14:11:17.452  1965  1965 D WfdsService: Supplicant Connection state is changed : true
08-10 14:11:17.452  1965  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
,08-10 14:11:17.452  1965  2345 D WfdsService: Set the WFDS Monitor: true
08-10 14:11:17.452  1025  1531 E WifiHAL : Could not connect handle
08-10 14:11:17.452  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301d1e
08-10 14:11:17.452  1965  2345 D WfdsMonitor: WfdsMonitorThread create
,08-10 14:11:17.452  1025  1531 I WifiNative-HAL: Could not start hal
08-10 14:11:17.452  1025  1531 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 14:11:17.452  1025  1531 I WifiNative-HAL: startHal
08-10 14:11:17.452  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x987e785c
08-10 14:11:17.452  1965  2345 D WfdsMonitor: WFDS Monitor is created and started
08-10 14:11:17.452  1965  2345 D WfdsService: WiFi: Supplicant connection re-established
08-10 14:11:17.452  1025  1531 E WifiHAL : Could not connect handle
08-10 14:11:17.452  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501d16
08-10 14:11:17.452  1025  1531 I WifiNative-HAL: Could not start hal
08-10 14:11:17.452  1025  1531 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-10 14:11:17.453  1025  1531 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-10 14:11:17.453  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-10 14:11:17.453  6585  6585 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-10 14:11:17.454  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-10 14:11:17.454  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 14:11:17.454  6585  6585 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 14:11:17.454  1965  6651 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-10 14:11:17.455  1965  6651 E CtrlSupplicant: Succeed to open control connection
08-10 14:11:17.455  1965  6651 E CtrlSupplicant: Succeed to open monitor connection
08-10 14:11:17.455  1965  6651 D WfdsMonitor: Supplicant connection established
08-10 14:11:17.455  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 14:11:17.455  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-10 14:11:17.455  6585  6585 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-10 14:11:17.456  1965  2345 D WfdsService: Connected to the supplicant for wfds
08-10 14:11:17.456  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-10 14:11:17.456  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 14:11:17.456  6585  6585 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 14:11:17.456  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 14:11:17.456  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 14:11:17.457  6585  6585 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 14:11:17.457  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 14:11:17.457  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-10 14:11:17.457  6585  6585 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-10 14:11:17.458  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-10 14:11:17.458  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 14:11:17.458  6585  6585 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 14:11:17.458  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 14:11:17.459  1025  1531 E WifiNative: : [140,659,406 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-10 14:11:17.459  1025  1531 D WifiNative-wlan0: doBoolean: RECONNECT
08-10 14:11:17.460  1025  1531 D WifiNative-wlan0: RECONNECT: returned true
08-10 14:11:17.460  1025  1531 D WifiNative-wlan0: doString: [STATUS]
08-10 14:11:17.461  1025  6650 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 14:11:17.461  1025  6650 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 14:11:17.461  1025  1531 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_addres,s=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 14:11:17.461  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 14:11:17.462  1025  1531 D WifiNative-wlan0: SET ps 1: returned true
08-10 14:11:17.463  1025  1528 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.464   323   868 D CommandListener: Setting iface cfg
08-10 14:11:17.464   323   868 D CommandListener: Trying to bring up p2p0
08-10 14:11:17.465  1025  1528 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-10 14:11:17.465  1025  1025 D WifiScanningService: SCAN_AVAILABLE : 3
08-10 14:11:17.465  1025  1025 D RttService: SCAN_AVAILABLE : 3
08-10 14:11:17.465  1025  1549 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.465  1025  1549 I WifiNative-HAL: startHal
08-10 14:11:17.465  1025  1549 E wifi    : getStaticLongField sWifiHalHandle 0x94b8799c
08-10 14:11:17.466  1025  1549 E WifiHAL : Could not connect handle
08-10 14:11:17.466  1025  1549 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501cd2
08-10 14:11:17.466  1025  1549 I WifiNative-HAL: Could not start hal
08-10 14:11:17.466  1025  1549 E WifiScanningService: could not start HAL
08-10 14:11:17.466  1025  1550 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.466  1025  1528 D LGWifiP2pService: P2pEnablingState
08-10 14:11:17.466  1025  1528 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.466  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-10 14:11:17.466  1025  1528 D LGWifiP2pService: P2p socket connection successful
08-10 14:11:17.466  1025  1528 D LGWifiP2pService: P2pEnabledState
08-10 14:11:17.467  1025  1528 D LGWifiP2pService: sending p2p connection changed broadcast
,08-10 14:11:17.468  1965  1965 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-10 14:11:17.468  1965  1965 D WfdsService: WifiP2pState is changed : true
08-10 14:11:17.468  1965  2345 D WfdsService: Receive the WFDS_ENABLE Method
08-10 14:11:17.468  1965  2345 D WfdsService: Set the WFDS Monitor: true
08-10 14:11:17.468  1965  2345 D WfdsService: Connected to the supplicant for wfds
08-10 14:11:17.469  1965  2345 D WfdsJNI : doCommand: WFDS_SET TRUE
08-10 14:11:17.469  6585  6585 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-10 14:11:17.469  1965  2345 D WfdsService: selectPreferredScanChannel [36]
08-10 14:11:17.469  1965  2345 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-10 14:11:17.469  1025  1528 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-10 14:11:17.473  1025  1528 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-10 14:11:17.474  1025  1531 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-10 14:11:17.474  1965  1965 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-10 14:11:17.474  1025  1528 D WifiNative-p2p0: doBoolean: SET device_name G3
08-10 14:11:17.474  1025  1531 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-10 14:11:17.474  1025  1528 D WifiNative-p2p0: SET device_name G3: returned true
08-10 14:11:17.474  1025  1528 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-10 14:11:17.474  1025  1528 D LGWifiP2pService: before postfix = G3
08-10 14:11:17.474  1965  1965 D WfdsService: isConnected: false
08-10 14:11:17.474  1025  1528 D WifiServerServiceExt: postfix byte check : 2
08-10 14:11:17.474  1025  1528 D LGWifiP2pService: after postfix = G3
08-10 14:11:17.474  1025  1528 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-10 14:11:17.474  1025  1531 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-10 14:11:17.475  1025  1528 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-10 14:11:17.475  1025  1528 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-10 14:11:17.475  1025  1531 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-10 14:11:17.475  1025  1528 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-10 14:11:17.475  1025  1528 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-10 14:11:17.475  1025  1531 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-10 14:11:17.475  1025  1528 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-10 14:11:17.475  1025  1528 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-10 14:11:17.476  1025  1531 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-10 14:11:17.476  1025  1528 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-10 14:11:17.476  1025  1528 D WifiNative-HAL: p2pGetDeviceAddress
08-10 14:11:17.476  1025  1531 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-10 14:11:17.476  6585  6585 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-10 14:11:17.476  1025  1528 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-10 14:11:17.476  1025  1531 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-10 14:11:17.477  1025  1531 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-10 14:11:17.477  1025  1531 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-10 14:11:17.477  1025  1531 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-10 14:11:17.477  6585  6585 E wpa_supplicant: disconnect_rssi_lvl: -100
08-10 14:11:17.478  1965  1965 I WfdStateTracker: handleP2pThisDeviceChanged
08-10 14:11:17.478  1965  1965 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-10 14:11:17.478  1025  1528 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-10 14:11:17.478  1025  1528 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-10 14:11:17.478  1965  1965 D WfdsService: Update P2p Interface State: 3
08-,10 14:11:17.478  1025  1528 D WifiNative-p2p0: P2P_FLUSH: returned true
,08-10 14:11:17.478  1025  1528 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-10 14:11:17.479  1025  1528 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-10 14:11:17.479  1025  1528 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-10 14:11:17.479  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 14:11:17.479  1025  1528 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-10 14:11:17.479  1025  1528 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-10 14:11:17.479  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 14:11:17.480  1025  1531 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 14:11:17.480  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-10 14:11:17.501  1025  1528 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-10 14:11:17.501  1025  1528 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-10 14:11:17.502  1025  1528 D LGWifiP2pService: InactiveState
,08-10 14:11:17.502  6585  6585 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 14:11:17.502  1025  1528 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.502  6585  6585 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:17.503  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.503  1025  1528 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-10 14:11:17.503  6585  6585 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 14:11:17.503  6585  6585 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.503  1025  1531 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-10 14:11:17.504  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-10 14:11:17.504  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-10 14:11:17.505  6585  6585 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 14:11:17.505  1965  6651 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:17.505  1025  6650 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 14:11:17.505  1025  1531 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-10 14:11:17.505  1025  6650 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:17.505  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-10 14:11:17.505  6585  6585 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:17.506  6585  6585 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 14:11:17.506  6585  6585 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.506  1025  1528 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-10 14:11:17.506  1025  1528 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.506  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.506  1025  1528 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.507  6585  6585 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-10 14:11:17.507  6585  6585 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 14:11:17.507  1025  1528 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.507  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.507  1025  1528 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.507  1025  1528 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.507  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.507  1025  1528 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.507  6585  6585 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.508  1025  1531 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-10 14:11:17.508  1025  1531 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-10 14:11:17.508  1965  2345 W WfdsService: DefaultState - msg [9441285] is not handled
08-10 14:11:17.508  658,5  6585 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.508  1025  1528 D LGWifiP2pService: InactiveState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.508  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.508  1025  1528 D LGWifiP2pService: DefaultState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.509  1025  1025 E WifiServerServiceExt: No p2p device connected
08-10 14:11:17.509  1025  1528 D LGWifiP2pService: InactiveState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.509  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.509  1025  6650 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:17.509  1025  6650 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:17.509  1025  6650 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:17.509  1025  6650 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.509  1025  6650 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.509  1025  6650 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.509  1025  6650 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 14:11:17.509  1025  6650 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:17.510  1025  6650 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:17.510  1025  6650 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 14:11:17.510  1025  6650 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:17.510  1025  6650 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.510  1025  6650 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.510  1025  6650 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.510  1025  6650 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-10 14:11:17.510  1025  6650 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 14:11:17.510  1025  6650 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 14:11:17.510  1025  6650 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 14:11:17.510  1025  6650 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:17.510  1025  6650 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-10 14:11:17.510  1025  6650 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.510  1025  6650 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.510  1025  6650 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:17.510  1025  6650 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.510  1025  6650 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.510  1025  6650 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 14:11:17.510  1965  6651 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 14:11:17.511  1965  6651 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:17.511  1965  6651 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:17.511  1965  6651 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 14:11:17.511  1025  1531 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,08-10 14:11:17.511  1025  1531 D WifiNative-wlan0: doBoolean: SCAN
08-10 14:11:17.512  6585  6585 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-10 14:11:17.512  1025  1531 D WifiNative-wlan0: SCAN: returned true
08-10 14:11:17.512  1025  6650 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-10 14:11:17.512  1025  6650 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-10 14:11:17.512  1025  6650 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-10 14:11:17.512  1025  6650 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-10 14:11:17.512  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=140713  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 14:11:17.515  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 14:11:17.515  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 14:11:17.516  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 14:11:17.521  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:17.522  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:17.522  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 14:11:17.522  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=140722  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 14:11:17.523  1025  1531 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 14:11:17.523  1025  1531 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 14:11:17.524  1025  1531 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 14:11:17.524  1025  1531 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 14:11:17.525  1025  1531 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 14:11:17.526  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 14:11:17.526  1025  1025 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-10 14:11:17.589  6626  6626 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 14:11:17.614  6626  6626 I LibraryLoader: Loading: webviewchromium
,08-10 14:11:17.619  6626  6626 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 825-833)
,08-10 14:11:17.619  6626  6626 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 14:11:17.630  6626  6626 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {254ff3be}
,08-10 14:11:17.634  6626  6626 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 14:11:17.635  6626  6626 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 14:11:17.656  6626  6626 I BrowserStartupController: Initializing chromium process, renderers=0
08-10 14:11:17.657  6626  6626 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 14:11:17.674   327   327 V AudioPolicyService: registerClient() client 0xb14e7460, uid 10093
08-10 14:11:17.675  6626  6676 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-10 14:11:17.677  6626  6626 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 14:11:17.678  6626  6626 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-10 14:11:17.678  6626  6626 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-10 14:11:17.700  6626  6626 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 14:11:17.700  6626  6626 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 14:11:17.700  6626  6626 I Adreno-EGL: Build Date: 12/12/14 금
08-10 14:11:17.700  6626  6626 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 14:11:17.700  6626  6626 I Adreno-EGL: Remote Branch: 
08-10 14:11:17.700  6626  6626 I Adreno-EGL: Local Patches: 
08-10 14:11:17.700  6626  6626 I Adreno-EGL: Reconstruct Branch: 
,08-10 14:11:17.800  1025  1528 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.800  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 14:11:17.800  1025  1528 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:17.803  6626  6626 I NSApplication: Starting up...
08-10 14:11:17.880  1025  2064 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6692 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-10 14:11:17.882  1025  1041 I ActivityManager: Killing 5730:com.android.vending/u0a44 (adj 15): empty #17
,08-10 14:11:17.887  1025  1531 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 14:11:17.887  1025  1531 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 14:11:17.887  1025  1531 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 14:11:17.888  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 14:11:17.888  1025  1531 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-10 14:11:17.944  1025  1765 W libprocessgroup: failed to open /acct/uid_10044/pid_5730/cgroup.procs: No such file or directory
08-10 14:11:17.970  6692  6692 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 14:11:18.272  2232  2232 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-10 14:11:18.292  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-10 14:11:18.296  5096  5117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 14:11:18.326  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 14:11:18.341  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 14:11:18.341  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:18.341  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 14:11:18.341  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 14:11:18.344  6470  6470 I AppUp4:CustModeStarterReceiver: onReceive
08-10 14:11:18.347  1834  6719 I CheckinService: active receiver: enabled
,08-10 14:11:18.356  6470  6470 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3dc49d0d
08-10 14:11:18.356  6470  6470 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 14:11:18.356  6470  6470 D AppUp4:CustFacade: isPhone : true
08-10 14:11:18.357  6470  6470 D AppUp4:CustModeStarterReceiver: begin check event
08-10 14:11:18.357  6470  6470 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 14:11:18.361  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:18.361  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 14:11:18.363  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 14:11:18.367  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 14:11:18.379  3065  6729 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 14:11:18.379  6496  6496 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 14:11:18.381  3065  6730 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-10 14:11:18.381  3065  6730 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 14:11:18.407  3108  3108 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 14:11:18.407  3108  3108 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:18.408  3108  3108 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-10 14:11:18.409  6496  6732 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 14:11:18.414  6537  6537 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 14:11:18.415  6537  6537 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 14:11:18.418  6169  6739 W FormManager: Network not available. Please check & try again.
08-10 14:11:18.429  6608  6608 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:11:18
08-10 14:11:18.430  6169  6740 V FormManager: Network unavailable.
,08-10 14:11:18.432  6608  6608 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 14:11:18.432  6608  6608 D Weather.Utils: 2 : All the weather widget is gone.
08-10 14:11:18.432  6608  6608 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 14:11:18.432  6608  6608 D WeatherAncestor: connectivity changed - connection : true
08-10 14:11:18.432  6608  6608 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c3452d3
08-10 14:11:18.433  6608  6608 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 14:11:18.433  6608  6608 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 14:11:18.433  6608  6608 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 14:11:18.433  6608  6608 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 14:11:18.433  6608  6608 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:11:18
08-10 14:11:18.434  6169  6740 V FormManager: Network unavailable.
08-10 14:11:18.457  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-10 14:11:18.461  5096  5117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 14:11:18.485  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 14:11:18.492  1834  6743 I CheckinService: active receiver: enabled
08-10 14:11:18.505  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-10 14:11:18.505  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:18.506  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 14:11:18.506  6470  6470 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 14:11:18.510  6470  6470 I AppUp4:CustModeStarterReceiver: onReceive
,08-10 14:11:18.515  6470  6470 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3dc49d0d
08-10 14:11:18.515  6470  6470 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 14:11:18.515  6470  6470 D AppUp4:CustFacade: isPhone : true
08-10 14:11:18.515  6470  6470 D AppUp4:CustModeStarterReceiver: begin check event
08-10 14:11:18.516  6470  6470 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 14:11:18.521  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:18.521  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-10 14:11:18.523  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 14:11:18.526  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 14:11:18.534  6496  6496 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-10 14:11:18.534  3065  6744 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 14:11:18.545  3065  6745 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 14:11:18.546  3065  6745 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-10 14:11:18.550  6496  6746 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:11:18.562  6169  6749 W FormManager: Network not available. Please check & try again.
,08-10 14:11:18.566  3108  3108 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 14:11:18.566  3108  3108 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-10 14:11:18.567  3108  3108 I LgeMiscReceiver: networkInfo.isConnected() = false
08-10 14:11:18.570  6537  6537 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-10 14:11:18.570  6537  6537 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 14:11:18.584  6608  6608 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:11:18
,08-10 14:11:18.586  6608  6608 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 14:11:18.586  6169  6750 V FormManager: Network unavailable.
08-10 14:11:18.586  6608  6608 D Weather.Utils: 2 : All the weather widget is gone.
08-10 14:11:18.587  6608  6608 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 14:11:18.588  6608  6608 D WeatherAncestor: connectivity changed - connection : true
08-10 14:11:18.588  6608  6608 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c3452d3
08-10 14:11:18.588  6608  6608 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 14:11:18.588  6608  6608 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 14:11:18.588  6608  6608 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 14:11:18.588  6608  6608 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 14:11:18.589  6608  6608 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:11:18
08-10 14:11:18.589  6169  6750 V FormManager: Network unavailable.
08-10 14:11:18.612  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 14:11:18.613  6145  6145 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 14:11:18.613  6145  6145 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-10 14:11:18.613  6145  6145 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 14:11:18.613  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 14:11:18.614  6145  6145 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 14:11:18.614  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-10 14:11:18.614  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 14:11:18.614  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 14:11:18.614  6145  6145 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 14:11:18.614  6145  6145 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-10 14:11:18.614  6145  6145 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 14:11:18.623  1025  2106 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:18.623  1025  2106 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@f90159 mBinding = false
08-10 14:11:18.626  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 14:11:18.636  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 14:11:18.640  6169  6753 W FormManager: Network not available. Please check & try again.
,08-10 14:11:18.642  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 14:11:18.642  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 14:11:18.642  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-10 14:11:18.643  1025  1087 D BluetoothManagerService: Message: 2
08-10 14:11:18.644  1025  1087 D BluetoothManagerService: Sending off request.
08-10 14:11:18.645  6110  6374 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-10 14:11:18.645  6110  6140 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-10 14:11:18.645  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:18.645  6110  6140 D BluetoothAdapterProperties: Setting state to 13
08-10 14:11:18.645  6110  6140 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 14:11:18.648  6110  6140 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 14:11:18.648  6110  6140 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-10 14:11:18.651  6110  6144 D BluetoothAdapterProperties: Scan Mode:20
08-10 14:11:18.651  6110  6140 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-10 14:11:18.653  6110  6379 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-10 14:11:18.653  6110  6379 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 14:11:18.653  6110  6379 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-10 14:11:18.653  6110  6379 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-10 14:11:18.653  6110  6379 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-10 14:11:18.653  6110  6379 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-10 14:11:18.653  6110  6379 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-10 14:11:18.653  6110  6379 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-10 14:11:18.654  6110  6140 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 14:11:18.655  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-10 14:11:18.655  6110  6399 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-10 14:11:18.658  6110  6397 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 14:11:18.658  6110  6380 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 14:11:18.658  6110  6396 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 14:11:18.658  6110  6241 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-10 14:11:18.661  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 14:11:18.661  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 14:11:18.661  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 14:11:18.661  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 14:11:18.661  6110  6241 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 14:11:18.661  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 14:11:18.661  6110  6241 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 14:11:18.661  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 14:11:18.661  6110  6241 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 14:11:18.661  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-10 14:11:18.661  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-10 14:11:18.661  6110  6241 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 14:11:18.662  5818  5818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:18.662  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:18.662  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:18.662  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:18.662  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:18.662  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:11:18.662  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:18.662  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:18.662  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:18.663  5818  5818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:18.663  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:18.664  6169  6754 V FormManager: Network unavailable.
08-10 14:11:18.665  5818  5818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:18.665  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:18.665  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:18.665  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:18.665  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:18.665  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:11:,18.665  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:18.665  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:18.665  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:18.666  5818  5818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:18.666  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:18.672  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 14:11:18.674  6169  6754 V FormManager: Network unavailable.
08-10 14:11:18.677  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 14:11:18.684  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:18.684  6169  6756 W FormManager: Network not available. Please check & try again.
,08-10 14:11:18.695  6169  6757 V FormManager: Network unavailable.
08-10 14:11:18.699  6169  6757 V FormManager: Network unavailable.
08-10 14:11:18.700  1025  1087 D BluetoothManagerService: Message: 60
08-10 14:11:18.700  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-10 14:11:18.700  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-10 14:11:18.701  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 14:11:18.701  3065  3065 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 14:11:18.703  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 14:11:18.703  6110  6110 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:18.703  6110  6110 D BluetoothMapService: STATE_TURNING_OFF
08-10 14:11:18.704  6110  6110 V BtOppService: Receiver DISABLED_ACTION 
08-10 14:11:18.704  6110  6110 V BluetoothMapService: Handler(): got msg=4
08-10 14:11:18.704  6110  6110 D BluetoothMapService: MAP Service closeService in
08-10 14:11:18.704  6110  6110 D BluetoothMapMasInstance: MAP Service shutdown
08-10 14:11:18.704  6110  6110 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 14:11:18.704  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:18.704  6110  6110 V BluetoothMapService: MAP Service closeService out
08-10 14:11:18.704  6145  6145 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-10 14:11:18.704  6110  6110 I BtOppRfcommListener: stopping Accept Thread
08-10 14:11:18.704  6110  6110 V BtOppRfcommListener: close mBtServerSocket
08-10 14:11:18.705  6110  6110 V BtOppRfcommListener: waiting for thread to terminate
08-10 14:11:18.705  6110  6396 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 14:11:18.705  6110  6110 V BtOppRfcommListener: done waiting for thread to terminate
08-10 14:11:18.705  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:18.707  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:18.707  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 14:11:18.709  6110  6110 V BtOppService: onDestroy
08-10 14:11:18.710  6145  6145 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 14:11:18.712  3065  3065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 14:11:18.715  6110  6110 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-10 14:11:18.720  3065  6759 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 14:11:18.722  6110  6110 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 14:11:18.722  6110  6110 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:18.722  6110  6110 V BluetoothPbapReceiver: ***********state = 13
08-10 14:11:18.722  3065  6760 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 14:11:18.723  3065  6760 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 14:11:18.724  6110  6110 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-10 14:11:18.727  5974  5974 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-10 14:11:18.727  5974  5974 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-10 14:11:18.727  5974  5974 V [BNRBootReceiver]: Boot Receiver Return
08-10 14:11:18.730  6110  6110 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:18.730  6110  6110 V BluetoothPbapService: state: 13
08-10 14:11:18.730  6145  6145 D DockEventReceiver: finishStartingService: stopping service
08-10 14:11:18.730  6110  6110 V BluetoothPbapService: Pbap Service closeService in
08-10 14:11:18.732  6110  6110 V BluetoothPbapService: successfully stopped pbap service
08-10 14:11:18.732  6110  6110 V BluetoothPbapService: Pbap Service closeService out
08-10 14:11:18.733  6145  6145 D BluetoothPbap: Proxy object disconnected
08-10 14:11:18.733  6110  6110 V BluetoothPbapService: Pbap Service onDestroy
08-10 14:11:18.733  6110  6110 V BluetoothPbapService: Pbap Service closeService in
08-10 14:11:18.733  6110  6110 V BluetoothPbapService: Pbap Service closeService out
08-10 14:11:18.733  6110  6110 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-10 14:11:18.733  6145  6145 D PbapServerProfile: Bluetooth service disconnected
08-10 14:11:18.738  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 14:11:18.740  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 14:11:18.750  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 14:11:18.755  6145  6145 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 14:11:18.759  6145  6145 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-10 14:11:18.764  6145  6145 D BluetoothPermissionRequest: onReceive
08-10 14:11:18.764  6145  6145 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-10 14:11:18.767  6145  6145 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 14:11:18.772  6110  6110 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-10 14:11:18.773  6110  6110 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-10 14:11:18.773  6110  6110 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-10 14:11:18.784  6110  6110 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:18.785  6110  6110 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-10 14:11:18.785  6290  6290 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 14:11:18.785  6290  6290 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 14:11:18.785  6290  6290 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 14:11:18.786  6110  6110 V BluetoothFtpService: Ftp Service onStartCommand
08-10 14:11:18.786  6110  6110 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:18.786  6110  6110 V BluetoothFtpService: Ftp Service closeService
08-10 14:11:18.787  6110  6110 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-10 14:11:18.789  6110  6110 V BluetoothFtpService: successfully stopped ftp service
08-10 14:11:18.790  6110  6110 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 14:11:18.790  6110  6110 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 14:11:18.790  6110  6110 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 14:11:18.790  6110  6110 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:18.790  6110  6110 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-10 14:11:18.790  6110  6110 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 14:11:18.791  2232  2232 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-10 14:11:18.791  6110  6110 V BluetoothFtpService: Ftp Service onDestroy
08-10 14:11:18.791  6110  6110 V BluetoothFtpService: Ftp Service closeService
08-10 14:11:18.794  6110  6110 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:18.794  6110  6110 V BluetoothSapService: state: 13
08-10 14:11:18.794  6110  6110 V BluetoothSapService: Stopping SAP server process
08-10 14:11:18.795  6110  6110 V BluetoothSapService: Sap Service closeSapService in
08-10 14:11:18.795  6110  6110 V BluetoothSapService: Close listen Socket : 
08-10 14:11:18.795  6110  6110 V BluetoothSapService: Close rfcomm Socket : 
08-10 14:11:18.795  6110  6110 V BluetoothSapService: Close sapd  Socket : 
08-10 14:11:18.796  6110  6110 V BluetoothSapService: Sap Service closeSapService out
08-10 14:11:18.797  6110  6110 V BluetoothSapService: Sap Service onDestroy
08-10 14:11:18.797  6110  6110 V BluetoothSapService: Sap Service closeSapService in
08-10 14:11:18.797  6110  6110 V BluetoothSapService: Close listen Socket : 
08-10 14:11:18.797  6110  6110 V BluetoothSapService: Close rfcomm Socket : 
08-10 14:11:18.797  6110  6110 V BluetoothSapService: Close sapd  Socket : 
,08-10 14:11:18.799  6110  6110 V BluetoothSapService: Sap Service closeSapService out
,08-10 14:11:18.807  2232  2232 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-10 14:11:19.666  6110  6144 D bt_hci_bdroid: cleanup
,08-10 14:11:19.675  6110  6243 I bt_lpm  : LPM is already off!!!
08-10 14:11:19.676  6110  6363 I bt_userial_mct: exiting userial_read_thread
08-10 14:11:19.677  6110  6241 W bt-btif : ag scb idx 1 not allocated
08-10 14:11:19.677  6110  6241 E bt-btif : BTA AG is already disabled, ignoring ...
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 14:11:19.677  6110  6241 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 14:11:19.678  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 14:11:19.678  6110  6241 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 14:11:19.678  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 14:11:19.678  6110  6241 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 14:11:19.678  6110  6241 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 14:11:19.678  6110  6241 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 14:11:19.678  6110  6241 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 14:11:19.679  6110  6363 D bt_userial_mct: Leaving userial_evt_read_thread()
08-10 14:11:19.679  6110  6144 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-10 14:11:19.679  6110  6243 I bt_vendor: hw_epilog_process
08-10 14:11:19.679  6110  6144 D bt_hci_bdroid: cleanup Finalizing cleanup
08-10 14:11:19.679  6110  6144 D bt_userial_mct: userial_close
08-10 14:11:19.679  6110  6144 E bt_userial_mct: pthread_join() FAILED result:3
08-10 14:11:19.679  6110  6144 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-10 14:11:19.687  6110  6144 D bt_hci_bdroid: set_power 0
08-10 14:11:19.687  6110  6144 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-10 14:11:19.691  6110  6144 I bt_vendor: bluetooth satus is on
08-10 14:11:19.691  6110  6144 I bt_vendor: bt-vendor : resetting BT status
08-10 14:11:19.691  6110  6144 I bt_vendor: Starting hciattach daemon
08-10 14:11:19.691  6110  6144 I bt_vendor: try to set false
08-10 14:11:19.693  6110  6144 I bt_vendor: Starting hciattach daemon
08-10 14:11:19.694  6110  6144 I bt_vendor: try to set false
08-10 14:11:19.694  6110  6144 I bt_vendor: cleanup
08-10 14:11:19.695  6110  6241 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-10 14:11:19.696  6110  6144 I GKI_LINUX: GKI_exit_task 0 done
08-10 14:11:19.696  6110  6144 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-10 14:11:19.698  6110  6140 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-10 14:11:19.702  6110  6110 D HeadsetService: Received stop request...Stopping profile...
,08-10 14:11:19.708  6110  6110 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 14:11:19.708  6110  6110 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 14:11:19.708  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:19.709  6110  6164 D HeadsetStateMachine: Exit Disconnected: -1
08-10 14:11:19.714  1025  1025 D BluetoothHeadset: Proxy object disconnected
08-10 14:11:19.714  1025  1025 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-10 14:11:19.718  1869  1869 D BluetoothHeadset: Proxy object disconnected
08-10 14:11:19.718  1869  1869 D BluetoothHeadset: Proxy object disconnected
08-10 14:11:19.718  1869  1869 D BluetoothHeadset: Proxy object disconnected
08-10 14:11:19.720  6110  6110 D A2dpService: Received stop request...Stopping profile...
08-10 14:11:19.721  6110  6214 D A2dpStateMachine: Exit Disconnected: -1
08-10 14:11:19.722  6110  6140 D BluetoothAdapterState: Stopping profile services that were post enabled
08-10 14:11:19.723  6110  6110 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-10 14:11:19.724  6110  6110 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-10 14:11:19.724  6110  6110 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 14:11:19.724  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:19.726  1025  1025 D BluetoothA2dp: Proxy object disconnected
08-10 14:11:19.726  1025  1025 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-10 14:11:19.730  6110  6110 D HidService: Received stop request...Stopping profile...
08-10 14:11:19.730  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:19.732  6110  6110 D HealthService: Received stop request...Stopping profile...
08-10 14:11:19.733  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:19.735  6110  6110 D PanService: Received stop request...Stopping profile...
08-10 14:11:19.735  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:19.737  6110  6110 D HeadsetStateMachine: Unbinding service...
08-10 14:11:19.739  6110  6110 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 14:11:19.739  6110  6110 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 14:11:19.739  6110  6110 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 14:11:19.740  6110  6110 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 14:11:19.740  6110  6110 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 14:11:19.740  6110  6110 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 14:11:19.740  6110  6110 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 14:11:19.740  6110  6110 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 14:11:19.744  6110  6110 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 14:11:19.744  6110  6110 D BtGatt.GattService: stop()
08-10 14:11:19.744  6110  6110 D BtGatt.AdvertiseManager: advertise clients cleared
08-10 14:11:19.746  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:19.748  6110  6110 D BluetoothMapService: Received stop request...Stopping profile...
08-10 14:11:19.748  6110  6110 D BluetoothMapService: stop()
08-10 14:11:19.748  6110  6110 D BluetoothMapEmailAppObserver: deinitObservers()
08-10 14:11:19.749  6110  6110 D BluetoothMapEmailAppObserver: removeReceiver()
08-10 14:11:19.749  6110  6110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399f04c2
08-10 14:11:19.750  6110  6110 I BluetoothA2dpServiceJni: cleanupNative
08-10 14:11:19.751  6110  6216 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-10 14:11:19.751  6110  6110 I GKI_LINUX: GKI_exit_task 2 done
08-10 14:11:19.751  6110  6110 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-10 14:11:19.751  6110  6110 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 14:11:19.751  6110  6110 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 14:11:19.752  6110  6110 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 14:11:19.752  6110  6110 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 14:11:19.752  6110  6110 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 14:11:19.752  6110  6110 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 14:11:19.752  6110  6110 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-10 14:11:19.757  6110  6110 V BluetoothMapService: Handler(): got msg=4
08-10 14:11:19.757  6110  6110 D BluetoothMapService: MAP Service closeService in
08-10 14:11:19.757  6110  6110 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 14:11:19.757  6110  6110 V BluetoothMapService: MAP Service closeService out
08-10 14:11:19.758  6110  6140 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-10 14:11:19.759  6110  6140 D BluetoothAdapterProperties: Setting state to 10
08-10 14:11:19.759  6110  6140 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-10 14:11:19.759  1025  1087 D BluetoothManagerService: Message: 60
08-10 14:11:19.759  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-10 14:11:19.759  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-10 14:11:19.760  6110  6140 I BluetoothAdapterState: Entering OffState
08-10 14:11:19.760  6145  6160 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:11:19.761  6110  6110 D BluetoothMapService: cleanup()
08-10 14:11:19.761  6110  6110 D BluetoothMapService: MAP Service closeService in
08-10 14:11:19.761  6110  6110 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 14:11:19.761  6110  6110 V BluetoothMapService: MAP Service closeService out
08-10 14:11:19.765  6145  6161 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 14:11:19.769  1869  1884 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:11:19.771  6145  6160 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 14:11:19.772  1025  1087 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:11:19.772  6145  6161 D BluetoothPan: onBluetoothStateChange on: false
08-10 14:11:19.773  1025  1087 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 14:11:19.773  6145  6160 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 14:11:19.774  1869  3164 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:11:19.774  6145  6161 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 14:11:19.775  1869  1885 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:11:19.776  1025  1087 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-10 14:11:19.776  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-10 14:11:19.779  1025  1087 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-10 14:11:19.779  1025  1087 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-10 14:11:19.779  1025  1087 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@f90159 mBinding = false
,08-10 14:11:19.782  1025  1087 D BluetoothManagerService: Sending unbind request.
08-10 14:11:19.792  6110  6144 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-10 14:11:19.793  6110  6110 I GKI_LINUX: GKI_exit_task 1 done
08-10 14:11:19.793  6110  6110 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-10 14:11:19.795  6110  6110 I BluetoothServiceJni: cleanupNative: return from cleanup
08-10 14:11:19.795  6110  6110 I art     : --- WEIRD: removing null entry 246
08-10 14:11:19.795  6110  6110 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-10 14:11:19.795  6110  6110 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-10 14:11:19.796  6110  6110 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-10 14:11:19.797  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-10 14:11:19.799  6110  6110 I art     : System.exit called, status: 0
08-10 14:11:19.800  6110  6110 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-10 14:11:19.818   327  1376 V AudioFlinger: 6110 died, releasing its sessions
08-10 14:11:19.818   327  1376 V AudioFlinger:  pid 1869 @ 0
08-10 14:11:19.818   327  1376 V AudioFlinger:  pid 3108 @ 1
08-10 14:11:19.818   327  1376 V AudioFlinger:  pid 3108 @ 2
,08-10 14:11:19.822  1965  1965 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-10 14:11:19.823  1965  2202 D LGBluetoothAPIService: Message: 101
08-10 14:11:19.823  1965  2202 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-10 14:11:19.823  1965  2202 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-10 14:11:19.823  1965  2202 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-10 14:11:19.825  6145  6145 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-10 14:11:19.827  1025  2083 I ActivityManager: Process com.android.bluetooth (pid 6110) has died
08-10 14:11:19.828  1025  2083 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-10 14:11:19.828  1025  2083 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-10 14:11:19.834  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-10 14:11:19.837  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 14:11:19.838  1965  2202 D LGBluetoothAPIService: Message: 2
08-10 14:11:19.838  1965  2202 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
,08-10 14:11:19.839  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:19.839  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:19.852  6145  6145 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-10 14:11:19.854  1596  1596 D BluetoothAdapter: 392011708: getState() :  mService = null. Returning STATE_OFF
08-10 14:11:19.854  1596  1596 D BluetoothAdapter: 392011708: getState() :  mService = null. Returning STATE_OFF
08-10 14:11:19.856  6145  6145 D LGBluetoothEventManager: [BTUI] clear device connection state
08-10 14:11:19.859  6145  6145 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 14:11:19.915  1025  2098 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6788 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-10 14:11:19.918  6145  6145 D DockEventReceiver: finishStartingService: stopping service
,08-10 14:11:19.991  6788  6788 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-10 14:11:19.991  6788  6788 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 14:11:19.992  6788  6788 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-10 14:11:19.993  6788  6788 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-10 14:11:20.016  6788  6788 D BluetoothAdapterApp: Loading JNI Library
,08-10 14:11:20.054  6788  6788 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2250d35b Instance Count = 1
,08-10 14:11:20.061  6788  6788 D BluetoothAdapterApp: onCreate
08-10 14:11:20.088  6788  6788 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-10 14:11:20.088  6788  6788 D ProfileConfigQcom: Adding HeadsetService
08-10 14:11:20.088  6788  6788 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-10 14:11:20.088  6788  6788 D ProfileConfigQcom: Adding A2dpService
08-10 14:11:20.089  6788  6788 D ProfileConfigQcom: [BTUI] HidService is supported
08-10 14:11:20.089  6788  6788 D ProfileConfigQcom: Adding HidService
08-10 14:11:20.089  6788  6788 D ProfileConfigQcom: [BTUI] HealthService is supported
08-10 14:11:20.089  6788  6788 D ProfileConfigQcom: Adding HealthService
08-10 14:11:20.090  6788  6788 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-10 14:11:20.091  6788  6788 D ProfileConfigQcom: [BTUI] PanService is supported
08-10 14:11:20.091  6788  6788 D ProfileConfigQcom: Adding PanService
08-10 14:11:20.091  6788  6788 D ProfileConfigQcom: [BTUI] GattService is supported
08-10 14:11:20.091  6788  6788 D ProfileConfigQcom: Adding GattService
08-10 14:11:20.092  6788  6788 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-10 14:11:20.092  6788  6788 D ProfileConfigQcom: Adding BluetoothMapService
08-10 14:11:20.092  6788  6788 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-10 14:11:20.093  6788  6788 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 14:11:20.094  6788  6788 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:20.095  6788  6788 V BluetoothPbapReceiver: ***********state = 10
,08-10 14:11:20.097  6788  6788 V LGMDMManagerInternal: Create singleton instance
08-10 14:11:20.211  6788  6788 D LGBluetoothAPIServer: [BTUI] onCreate()
08-10 14:11:20.211  6788  6788 D LGBluetoothAPIServer: [BTUI] onBind()
08-10 14:11:20.213  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 14:11:20.213  1965  1965 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-10 14:11:20.213  1965  2202 D LGBluetoothAPIService: Message: 100
08-10 14:11:20.214  1965  2202 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-10 14:11:20.221  6145  6145 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-10 14:11:20.230  6145  6145 D BluetoothPermissionRequest: onReceive
,08-10 14:11:20.233  6145  6145 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 14:11:20.233  6145  6145 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-10 14:11:20.236  6145  6145 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 14:11:20.242  6788  6788 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-10 14:11:20.247  6788  6788 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:20.250  6788  6788 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 14:11:20.250  6788  6788 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 14:11:20.250  6788  6788 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 14:11:20.252  6788  6788 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:20.252  6788  6788 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-10 14:11:20.259  6268  6268 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-10 14:11:21.014  1025  6650 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-10 14:11:21.014  1025  6650 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-10 14:11:21.032  1965  6651 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-10 14:11:21.032  1965  6651 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-10 14:11:21.037  1025  6650 E WifiMonitor: WifiMonitor:p2p0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-10 14:11:21.037  1025  6650 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-10 14:11:21.038  1025  6650 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-10 14:11:21.038  1025  6650 E WifiMonitor: WifiMonitor:p2p0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-10 14:11:21.038  1025  6650 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-10 14:11:21.040  1025  1528 D LGWifiP2pService: InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:21.040  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:21.040  1025  1528 D LGWifiP2pService: DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:21.036  1025  1531 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 14:11:21.041  1025  1531 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 14:11:21.041  1025  1531 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 14:11:21.041  1025  1531 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 14:11:21.042  1025  1531 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-10 14:11:21.068  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-10 14:11:21.077  6145  6145 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-10 14:11:21.642  1025  1040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:21.643  1025  1040 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-10 14:11:21.659  1025  1087 D BluetoothManagerService: Message: 1
08-10 14:11:21.660  1025  1087 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-10 14:11:21.665  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 14:11:21.666  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 14:11:21.666  1025  1025 D Ulp_jni : JNI:system_update. Event-4
,08-10 14:11:21.690  1025  1087 D BluetoothManagerService: Message: 20
08-10 14:11:21.690  1025  1087 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1afdf5f6:true
,08-10 14:11:21.694  6788  6788 D BluetoothAdapterState: make
08-10 14:11:21.699  6788  6788 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-10 14:11:21.699  6788  6788 I bluedroid-qcom: init
08-10 14:11:21.701  6788  6820 I BluetoothAdapterState: Entering OffState
08-10 14:11:21.701  6788  6788 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-10 14:11:21.701  6788  6788 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-10 14:11:21.701  6788  6788 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 14:11:21.701  6788  6788 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 14:11:21.701  6788  6788 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-10 14:11:21.703  6788  6788 I bluedroid-qcom: get_profile_interface socket
08-10 14:11:21.703  6788  6788 I bluedroid-qcom: get_profile_interface map_client
,08-10 14:11:21.707  6788  6824 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-10 14:11:21.702  6823  6823 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:21.712  6788  6824 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-10 14:11:21.702  6823  6823 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:21.723  6823  6823 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-10 14:11:21.723  6823  6823 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-10 14:11:21.723  6823  6823 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-10 14:11:21.727  1025  1025 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-10 14:11:21.727  1025  1025 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 14:11:21.727  1025  1025 D BluetoothManagerService: Stored Bluetooth name: G3
08-10 14:11:21.727  1025  1087 D BluetoothManagerService: Message: 40
08-10 14:11:21.727  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-10 14:11:21.728  6788  6805 I bluedroid-qcom: config_hci_snoop_log
08-10 14:11:21.730  1025  1087 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-10 14:11:21.730  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-10 14:11:21.730  6823  6823 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-10 14:11:21.736  6823  6823 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-10 14:11:21.736  6823  6823 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-10 14:11:21.742  6788  6820 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-10 14:11:21.743  6788  6824 D BluetoothAdapterProperties: Name is: G3
08-10 14:11:21.743  6788  6820 D BluetoothAdapterProperties: Setting state to 11
08-10 14:11:21.743  6788  6820 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-10 14:11:21.744  1025  1087 D BluetoothManagerService: Message: 60
08-10 14:11:21.744  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-10 14:11:21.744  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-10 14:11:21.746  6788  6820 I LGBluetoothServiceJni: classInitNative: succeeds
08-10 14:11:21.768  6788  6820 D BluetoothBondStateMachine: make
,08-10 14:11:21.770  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:21.773  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:21.774  6145  6145 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-10 14:11:21.776  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 14:11:21.781  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:11:21.782  6788  6788 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 14:11:21.782  6788  6788 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:21.782  6788  6788 V BluetoothPbapReceiver: ***********state = 11
08-10 14:11:21.785  6788  6820 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:21.785  6788  6820 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-10 14:11:21.785  6788  6820 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:21.785  6788  6820 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-10 14:11:21.787  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 14:11:21.787  6788  6820 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-10 14:11:21.789  6788  6830 I BluetoothBondStateMachine: StableState(): Entering Off State
08-10 14:11:21.795  6788  6820 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 14:11:21.819  6788  6788 D HeadsetService: Received start request. Starting profile...
,08-10 14:11:21.820  6788  6788 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 14:11:21.820  6788  6788 D LGBluetoothHfpAdapter: Version 1.6
08-10 14:11:21.823  6788  6788 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 14:11:21.824  6788  6788 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 14:11:21.825  6788  6788 D HeadsetStateMachine: make
08-10 14:11:21.825  6788  6820 E BluetoothAdapterService: File transfer profiles supported!!
08-10 14:11:21.834  6145  6145 D BluetoothPermissionRequest: onReceive
08-10 14:11:21.839  6145  6145 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-10 14:11:21.842  6788  6820 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 14:11:21.849  6788  6820 E BluetoothAdapterService: File transfer profiles supported!!
08-10 14:11:21.853  6788  6820 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 14:11:21.859  6788  6820 E BluetoothAdapterService: File transfer profiles supported!!
08-10 14:11:21.864  6788  6820 E BluetoothAdapterService: File transfer profiles supported!!
08-10 14:11:21.865  6788  6788 D LgDataFeature: LgDataFeature() Constructor: none
08-10 14:11:21.866  6788  6788 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 14:11:21.884  6788  6820 V LGMDMManager: Create singleton instance
,08-10 14:11:21.887  6788  6820 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-10 14:11:22.005  1025  2030 I art     : Explicit concurrent mark sweep GC freed 63700(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.623ms total 133.541ms
,08-10 14:11:22.006  6788  6788 D HeadsetStateMachine: max_hf_connections = 1
08-10 14:11:22.006  6788  6788 I bluedroid-qcom: get_profile_interface handsfree
08-10 14:11:22.012  6788  6788 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-10 14:11:22.014   327  1376 V AudioPolicyService: registerClient() client 0xb14e79a0, uid 1002
08-10 14:11:22.015   327   327 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-10 14:11:22.015   327   327 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 14:11:22.015   327   327 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 14:11:22.016  6788  6788 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-10 14:11:22.017   327  1377 V AudioFlinger: registerClient() client 0xb14330e8, pid 6788
08-10 14:11:22.018   327  1370 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:22.018   327  1370 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-10 14:11:22.018  1596  2530 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:22.018  1596  2530 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 14:11:22.019  1869  3164 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:22.019  1869  3164 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 14:11:22.019  3108  3124 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:22.019  3108  3124 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 14:11:22.019   327  1371 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:22.019   327  1371 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 14:11:22.020  1025  1040 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:22.020  1025  1040 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 14:11:22.020  1025  1040 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:22.020  1025  1040 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 14:11:22.020  1869  1885 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:22.020  1869  1885 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 14:11:22.020  6788  6805 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 14:11:22.021  1596  4200 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:22.021  1596  4200 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 14:11:22.021  3108  3123 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:22.021  3108  3123 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 14:11:22.022  6788  6805 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-10 14:11:22.023  6788  6805 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 14:11:22.023  6788  6805 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-10 14:11:22.023  6788  6788 V ToneGenerator: Create Track: 0xb4928a80
08-10 14:11:22.023  6788  6788 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-10 14:11:22.023  6788  6788 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-10 14:11:22.023   327  1376 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 14:11:22.023   327  1376 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-10 14:11:22.023   327  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-10 14:11:22.023   327  1376 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 14:11:22.024   327   327 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 14:11:22.024   327  1377 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 14:11:22.024   327  1377 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-10 14:11:22.024   327  1377 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 14:11:22.024   327  1377 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 14:11:22.024  6788  6788 V AudioSystem: getLatency() output 2, latency 50
08-10 14:11:22.024  6788  6788 V AudioSystem: getFrameCount() output 2, frameCount 960
08-10 14:11:22.024  6788  6788 V AudioTrack: createTrack_l() output 2 afLatency 50
08-10 14:11:22.025   327  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
,08-10 14:11:22.025   327  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 14:11:22.025   327  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 14:11:22.025   327  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 14:11:22.025   327  1375 V AudioFlinger: createTrack() lSessionId: 22
08-10 14:11:22.027  6788  6788 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-10 14:11:22.027   327  1376 V AudioFlinger: acquiring 22 from 6788, for 6788
08-10 14:11:22.027   327  1376 V AudioFlinger:  added new entry for 22
08-10 14:11:22.027  6788  6788 V ToneGenerator: ToneGenerator INIT OK, time: 145241
08-10 14:11:22.027  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
,08-10 14:11:22.028  6788  6841 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-10 14:11:22.028  6788  6841 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 14:11:22.028  6788  6841 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 14:11:22.028  6788  6841 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-10 14:11:22.028   327  1377 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6788
08-10 14:11:22.029   327  1377 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-10 14:11:22.029   327  1377 V voice   : voice_set_parameters: enter: bt_samplerate=8000
,08-10 14:11:22.029   327  1377 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-10 14:11:22.029   327  1377 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-10 14:11:22.029  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:22.029   327  1377 V voice   : voice_set_parameters: exit with code(0)
08-10 14:11:22.029   327  1377 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-10 14:11:22.029   327  1377 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-10 14:11:22.029   327  1377 V msm8974_platform: platform_set_parameters: exit with code(0)
08-10 14:11:22.029   327  1377 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
,08-10 14:11:22.029   327  1377 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-10 14:11:22.029   327  1377 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-10 14:11:22.029  6788  6841 V ToneGenerator: ToneGenerator destructor
08-10 14:11:22.029  6788  6841 V ToneGenerator: stopTone
08-10 14:11:22.029  6788  6841 V ToneGenerator: Delete Track: 0xb4928a80
08-10 14:11:22.029  6788  6841 V AudioTrack: ~AudioTrack, releasing session id from 6788 on behalf of 6788
08-10 14:11:22.030   327   327 V AudioFlinger: releasing 22 from 6788 for 6788
,08-10 14:11:22.030   327   327 V AudioFlinger:  decremented refcount to 0
08-10 14:11:22.030   327   327 V AudioFlinger: purging stale effects
08-10 14:11:22.030   327   327 V AudioPolicyService: AudioCommandThread() adding release output 2
08-10 14:11:22.030   327   327 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-10 14:11:22.030   327   327 V AudioFlinger: PlaybackThread::Track destructor
08-10 14:11:22.030   327  1251 V AudioPolicyService: AudioCommandThread() waking up
08-10 14:11:22.030   327   327 V AudioFlinger: removeClient_l() pid 6788, calling pid 327
,08-10 14:11:22.030   327  1251 V AudioPolicyService: AudioCommandThread() processing release output 2
08-10 14:11:22.030   327  1251 V AudioPolicyManager: releaseOutput() 2
08-10 14:11:22.030   327  1251 V AudioPolicyService: AudioCommandThread() going to sleep
08-10 14:11:22.031  6788  6788 D A2dpService: Received start request. Starting profile...
08-10 14:11:22.032  6788  6788 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 14:11:22.033  6788  6788 V Avrcp   : make
08-10 14:11:22.033  6788  6788 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-10 14:11:22.033  6788  6788 I bluedroid-qcom: get_profile_interface avrcp
08-10 14:11:22.043  6788  6788 V AudioManager: registerRemoteController: size of Media player list: 0
08-10 14:11:22.045  6788  6788 E AudioManager: No RCC entry present to update
08-10 14:11:22.045  6788  6788 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 14:11:22.049  6788  6788 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-10 14:11:22.050  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-10 14:11:22.050  6788  6788 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-10 14:11:22.057  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-10 14:11:22.215  1025  1903 V SIM_STK : Menu title from STK is T-Mobile
,08-10 14:11:22.215  1025  1903 V SIM_STK : Menu title from STK is T-Mobile
,08-10 14:11:22.340  6626  6646 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-10 14:11:22.341  1025  2099 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-10 14:11:22.349  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-10 14:11:22.353  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-10 14:11:22.354  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-10 14:11:22.354  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 14:11:22.354  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 14:11:22.354  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 14:11:22.354  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 14:11:22.354  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 14:11:22.354  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,08-10 14:11:22.354  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 14:11:22.354  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-10 14:11:22.355  6788  6788 I BluetoothA2dpServiceJni: classInitNative
08-10 14:11:22.355  6788  6788 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 14:11:22.355  6788  6788 D A2dpStateMachine: make
08-10 14:11:22.358  6788  6788 I bluedroid-qcom: get_profile_interface a2dp
08-10 14:11:22.358  6788  6854 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-10 14:11:22.360  6788  6788 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-10 14:11:22.360  6788  6788 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-10 14:11:22.360  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:22.361  6788  6853 D A2dpStateMachine: Enter Disconnected: -2
08-10 14:11:22.361  6788  6788 I BluetoothHidServiceJni: classInitNative: succeeds
08-10 14:11:22.362  6788  6788 D HidService: Received start request. Starting profile...
08-10 14:11:22.363  6788  6788 I bluedroid-qcom: get_profile_interface hidhost
08-10 14:11:22.363  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:22.363  6788  6788 I BluetoothHealthServiceJni: classInitNative: succeeds
08-10 14:11:22.364  6788  6788 D HealthService: Received start request. Starting profile...
08-10 14:11:22.366  6788  6788 I bluedroid-qcom: get_profile_interface health
,08-10 14:11:22.367  6788  6788 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-10 14:11:22.367  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:22.367  6788  6788 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-10 14:11:22.369  6788  6788 D PanService: Received start request. Starting profile...
08-10 14:11:22.369  6788  6788 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 14:11:22.369  6788  6788 I bluedroid-qcom: get_profile_interface pan
08-10 14:11:22.375  6788  6788 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-10 14:11:22.375  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:22.376  6788  6788 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-10 14:11:22.379  6788  6788 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 14:11:22.381  6788  6788 D BtGatt.GattService: Received start request. Starting profile...
08-10 14:11:22.381  6788  6788 D BtGatt.GattService: start()
08-10 14:11:22.381  6788  6788 I bluedroid-qcom: get_profile_interface gatt
,08-10 14:11:22.381  6788  6788 D BtGatt.AdvertiseManager: advertise manager created
08-10 14:11:22.387  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:22.388  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:22.388  6788  6788 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-10 14:11:22.389  6788  6788 V BluetoothMapService: BluetoothMapBinder()
08-10 14:11:22.389  6788  6788 D BluetoothMapService: Received start request. Starting profile...
08-10 14:11:22.389  6788  6788 D BluetoothMapService: start()
08-10 14:11:22.392  6788  6788 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-10 14:11:22.392  6788  6788 D BluetoothMapEmailAppObserver: createReceiver()
08-10 14:11:22.393  6788  6788 D BluetoothMapEmailAppObserver: initObservers()
08-10 14:11:22.393  6788  6788 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-10 14:11:22.399  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:22.400  6788  6788 D HeadsetStateMachine: Proxy object connected
08-10 14:11:22.400  6788  6788 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-10 14:11:22.400  6788  6788 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-10 14:11:22.404  6788  6788 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 14:11:22.405  6788  6841 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-10 14:11:22.406  6788  6841 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 14:11:22.407  6788  6841 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-10 14:11:22.409  6788  6788 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-10 14:11:22.411  6788  6788 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 14:11:22.412  6788  6788 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:22.414  6788  6788 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 14:11:22.416  6788  6788 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 14:11:22.416  6788  6788 V PanService: [BTUI] SIM Extra State :ABSENT
08-10 14:11:22.418  6788  6788 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-10 14:11:22.418  6788  6788 V BluetoothMapService: Handler(): got msg=1
08-10 14:11:22.419  6788  6788 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 14:11:22.419  6788  6788 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 14:11:22.419  6788  6788 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 14:11:22.419  6788  6788 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:22.419  6788  6820 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-10 14:11:22.419  6788  6788 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-10 14:11:22.419  6788  6820 I bluedroid-qcom: enable
08-10 14:11:22.420  6788  6820 I bt_hci_bdroid: init
08-10 14:11:22.421  6788  6820 I bt_vendor: bt-vendor : init
08-10 14:11:22.421  6788  6820 I bt_vendor: bt-vendor : get_bt_soc_type
,08-10 14:11:22.424  6788  6820 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-10 14:11:22.424  6788  6820 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-10 14:11:22.424  6788  6820 D bt_userial_mct: userial_init
08-10 14:11:22.424  6788  6864 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-10 14:11:22.424  6788  6864 I bt-btu  : btu_task pending for preload complete event
08-10 14:11:22.424  6788  6820 D bt_hci_bdroid: set_power 1
08-10 14:11:22.424  6788  6820 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-10 14:11:22.424  6788  6820 I bt_vendor: Starting hciattach daemon
08-10 14:11:22.424  6788  6820 I bt_vendor: try to set true
08-10 14:11:22.422  6867  6867 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:22.422  6867  6867 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:22.439  6868  6868 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-10 14:11:22.482  6874  6874 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-10 14:11:22.506  6875  6875 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-10 14:11:22.542  6877  6877 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 14:11:22.555  6878  6878 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-10 14:11:22.567  6879  6879 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 14:11:22.580  6880  6880 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-10 14:11:22.608  6882  6882 I libmdmdetect: ESOC framework not supported
08-10 14:11:22.609  6882  6882 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-10 14:11:22.614  6882  6882 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-10 14:11:22.614  6882  6882 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-10 14:11:22.614  6882  6882 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-10 14:11:22.614  6882  6882 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-10 14:11:22.614  6882  6882 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-10 14:11:22.614  6882  6882 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-10 14:11:22.614  6882  6882 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-10 14:11:22.653  6882  6883 E QC-QMI  : qmi_client [6882] 14: failed to locate client data
,08-10 14:11:22.654   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-10 14:11:22.654   484   484 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-10 14:11:22.684  6884  6884 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-10 14:11:22.698  6885  6885 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-10 14:11:22.727  6788  6820 I bt_vendor: bluetooth satus is on
08-10 14:11:22.727  6788  6820 D bt_hci_bdroid: preload
,08-10 14:11:22.731  6788  6866 D bt_userial_mct: userial_open(port:0)
,08-10 14:11:22.731  6788  6866 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-10 14:11:22.732  6788  6866 I bt_vendor: Done intiailizing UART
,08-10 14:11:22.733  6788  6866 I bt_vendor: Done intiailizing UART
,08-10 14:11:22.733  6788  6866 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-10 14:11:22.733  6788  6866 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-10 14:11:22.733  6788  6864 I bt-btu  : btu_task received preload complete event
08-10 14:11:22.734  6788  6864 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-10 14:11:22.735  6788  6864 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-10 14:11:22.737  6788  6887 D bt_userial_mct: Entering userial_read_thread()
08-10 14:11:22.741  6788  6864 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_HCI
08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_AVDT,
08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_AVRC,
08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_PAN
,08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_GATT
,08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 14:11:22.750  6788  6864 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-10 14:11:22.751  6788  6864 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 14:11:22.791  6788  6864 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-10 14:11:22.791  6788  6864 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0195061 
08-10 14:11:22.791  6788  6864 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0195061 
,08-10 14:11:22.807  6788  6824 E bt-btif : Calling BTA_HhEnable
08-10 14:11:22.807  6788  6824 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-10 14:11:22.808  6788  6824 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-10 14:11:22.812  6788  6864 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-10 14:11:22.812  6788  6864 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-10 14:11:22.812  6788  6864 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-10 14:11:22.813  6788  6864 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-10 14:11:22.813  6788  6864 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-10 14:11:22.814  1025  1025 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 14:11:22.814  1025  1025 D BluetoothManagerService: Stored Bluetooth name: G3
08-10 14:11:22.815  6788  6824 D BluetoothAdapterProperties: Name is: G3
08-10 14:11:22.818  6788  6824 D BluetoothAdapterProperties: Scan Mode:20
08-10 14:11:22.818  6788  6824 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 14:11:22.818  6788  6824 D bt_hci_bdroid: postload
08-10 14:11:22.819  6788  6866 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 14:11:22.820  6788  6864 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-10 14:11:22.820  6788  6824 D bte_conf: Device ID record 1 : primary
08-10 14:11:22.820  6788  6824 D bte_conf:   vendorId            = 00c4
08-10 14:11:22.820  6788  6824 D bte_conf:   vendorIdSource      = 0001
08-10 14:11:22.820  6788  6824 D bte_conf:   product             = 13a1
08-10 14:11:22.820  6788  6824 D bte_conf:   version             = 1000
08-10 14:11:22.820  6788  6824 D bte_conf:   clientExecutableURL = 
08-10 14:11:22.820  6788  6824 D bte_conf:   serviceDescription  = 
08-10 14:11:22.821  6788  6824 D bte_conf:   documentationURL    = 
08-10 14:11:22.821  6788  6824 D bte_conf: bte_load_did_conf no section named DID2.
,08-10 14:11:22.824  6788  6864 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 14:11:22.825  6788  6864 W bt-smp  : Plain text(LSB ~ MSB) = 38 b3 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 14:11:22.825  6788  6864 W bt-smp  : Encrypted text(LSB ~ MSB) = b4 8a 37 56 8a 27 ce 05 1e 50 75 29 b3 20 c4 7c 
08-10 14:11:22.825  6788  6866 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 14:11:22.825  6788  6864 W bt-btm  : Stopping oneshot timer
08-10 14:11:22.825  6788  6866 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 14:11:22.829  6788  6820 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-10 14:11:22.829  6788  6820 D BluetoothAdapterProperties: ScanMode =  20
08-10 14:11:22.829  6788  6820 D BluetoothAdapterProperties: State =  11
08-10 14:11:22.829  6788  6820 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-10 14:11:22.829  6788  6820 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-10 14:11:22.830  6788  6820 D BluetoothAdapterProperties: Setting state to 12
08-10 14:11:22.830  6788  6820 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 14:11:22.830  6788  6824 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-10 14:11:22.831  6788  6824 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 14:11:22.832  1025  1087 D BluetoothManagerService: Message: 60
08-10 14:11:22.832  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-10 14:11:22.832  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-10 14:11:22.822  6889  6889 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:22.822  6889  6889 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 14:11:22.842  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:22.842  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:22.842  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:22.842  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:22.842  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:11:22.842  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:22.842  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:22.842  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:22.846  6145  6160 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:11:22.848  6788  6820 I BluetoothAdapterState: Entering On State
08-10 14:11:22.848  6788  6824 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 14:11:22.849  6788  6824 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-10 14:11:22.851  6788  6820 D LGBluetoothServiceAdapter: [BTUI] OnState
08-10 14:11:22.851  6788  6820 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-10 14:11:22.851  6788  6820 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-10 14:11:22.853  6788  6887 E bt_mct  : hci lib postload completed
08-10 14:11:22.855  6788  6820 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-10 14:11:22.856  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:22.860  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:22.860  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:22.860  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:22.860  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:22.860  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:11:22.860  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:22.860  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:22.860  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:11:22.862  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:22.868  6145  6161 D BluetoothMap: onBluetoothStateChange: up=true
,08-10 14:11:22.875  1869  3166 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:11:22.876  6788  6864 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 14:11:22.876  6788  6864 W bt-smp  : Plain text(LSB ~ MSB) = 47 68 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 14:11:22.876  6788  6864 W bt-smp  : Encrypted text(LSB ~ MSB) = d7 3e 3b 65 12 a3 01 48 e7 a1 7d 27 ab f0 19 05 
08-10 14:11:22.876  6788  6864 W bt-btm  : Stopping oneshot timer
08-10 14:11:22.878  6145  6145 D BluetoothHeadset: Proxy object connected
08-10 14:11:22.878  6145  6145 D HeadsetProfile: Bluetooth service connected
08-10 14:11:22.879  1869  1869 D BluetoothHeadset: Proxy object connected
08-10 14:11:22.880  6145  6161 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 14:11:22.884  6145  6145 D BluetoothMap: Proxy object connected
08-10 14:11:22.884  6145  6145 D MapProfile: Bluetooth service connected
08-10 14:11:22.884  6145  6145 D BluetoothMap: getConnectedDevices()
08-10 14:11:22.887  1025  1087 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:11:22.888  1025  1025 D BluetoothHeadset: Proxy object connected
08-10 14:11:22.889  6145  6161 D BluetoothPan: onBluetoothStateChange on: true
08-10 14:11:22.889  6145  6161 D BluetoothPan: onBluetoothStateChange call bindService
08-10 14:11:22.894  1025  1087 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 14:11:22.897  6788  6864 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 14:11:22.897  6788  6864 W bt-smp  : Plain text(LSB ~ MSB) = 50 ec 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 14:11:22.897  6788  6864 W bt-smp  : Encrypted text(LSB ~ MSB) = 20 2a 48 f3 82 60 f6 63 5b 2a 38 cc db 78 d1 e4 
08-10 14:11:22.897  6788  6864 W bt-btm  : Stopping oneshot timer
08-10 14:11:22.898  6788  6820 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-10 14:11:22.899  1025  1025 D BluetoothA2dp: Proxy object connected
08-10 14:11:22.899  6145  6161 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 14:11:22.901  1869  3164 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:11:22.902  6788  6805 V BluetoothMapService: getConnectedDevices()
08-10 14:11:22.903  6145  6145 D BluetoothInputDevice: Proxy object connected
08-10 14:11:22.903  6145  6145 D HidProfile: Bluetooth service connected
08-10 14:11:22.903  1869  1869 D BluetoothHeadset: Proxy object connected
08-10 14:11:22.904  6145  6160 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 14:11:22.905  6145  6145 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 14:11:22.905  6145  6145 D PanProfile: Bluetooth service connected
08-10 14:11:22.906  6788  6864 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 14:11:22.906  6788  6864 W bt-smp  : Plain text(LSB ~ MSB) = 08 7b 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 14:11:22.906  6788  6864 W bt-smp  : Encrypted text(LSB ~ MSB) = f9 79 93 b4 fe ef 8f b2 ad 7f cc 7b db 46 08 2e 
,08-10 14:11:22.906  6788  6864 W bt-btm  : Stopping oneshot timer
08-10 14:11:22.907  1025  1538 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-10 14:11:22.910  1869  2430 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:11:22.912  6145  6145 D BluetoothA2dp: Proxy object connected
08-10 14:11:22.912  6145  6145 D A2dpProfile: Bluetooth service connected
08-10 14:11:22.913  1869  1869 D BluetoothHeadset: Proxy object connected
08-10 14:11:22.914  1025  1087 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-10 14:11:22.914  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-10 14:11:22.915  1025  1025 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-10 14:11:22.916  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:22.917  6788  6864 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 14:11:22.917  6788  6864 W bt-smp  : Plain text(LSB ~ MSB) = f0 49 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 14:11:22.917  6788  6864 W bt-smp  : Encrypted text(LSB ~ MSB) = d4 61 1c 2b b5 ce 50 cc 78 f7 60 5a 77 fb a6 f5 
08-10 14:11:22.917  6788  6864 W bt-btm  : Stopping oneshot timer
08-10 14:11:22.917  1965  2202 D LGBluetoothAPIService: Message: 1
08-10 14:11:22.917  1965  2202 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-10 14:11:22.917  1965  2202 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
,08-10 14:11:22.917  1965  2202 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-10 14:11:22.920  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 14:11:22.922  6905  6905 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-10 14:11:22.925  1025  1087 D BluetoothManagerService: Message: 40
08-10 14:11:22.925  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-10 14:11:22.928  6788  6788 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:22.928  6788  6788 D BluetoothMapService: STATE_ON
08-10 14:11:22.928  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:22.931  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:22.934  6145  6145 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-10 14:11:22.935  6145  6145 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 14:11:22.945  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:22.945  6788  6788 V BluetoothPbapService: Pbap Service onCreate
08-10 14:11:22.945  6788  6788 V BluetoothPbapService: Starting PBAP service
08-10 14:11:22.947  6788  6788 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-10 14:11:22.947  6788  6788 V BluetoothMapService: Handler(): got msg=1
08-10 14:11:22.947  6788  6788 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-10 14:11:22.948  6788  6788 V BluetoothPbapService: Pbap Service onBind
,08-10 14:11:22.949  6788  6908 D BluetoothMapMasInstance: MAS initSocket()
08-10 14:11:22.950  6145  6145 D DockEventReceiver: finishStartingService: stopping service
08-10 14:11:22.950  6788  6788 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:22.951  6788  6788 V BluetoothPbapService: state: 12
08-10 14:11:22.951  6145  6145 D BluetoothPbap: Proxy object connected
08-10 14:11:22.951  6145  6145 D PbapServerProfile: Bluetooth service connected
08-10 14:11:22.951  6788  6788 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 14:11:22.951  6788  6788 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:22.951  6788  6788 V BluetoothPbapReceiver: ***********state = 12
08-10 14:11:22.951  6788  6908 D BluetoothMapMasInstance:   masId = 00
08-10 14:11:22.951  6788  6908 D BluetoothMapMasInstance:   msgTypes = 0e
08-10 14:11:22.951  6788  6908 D BluetoothMapMasInstance:   masName = SMS/MMS
08-10 14:11:22.951  6788  6908 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-10 14:11:22.955  6788  6788 V BluetoothPbapService: Handler(): got msg=1
08-10 14:11:22.955  6788  6788 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-10 14:11:22.956  1025  1709 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:22.957  6788  6910 V BluetoothPbapService: Pbap Service initSocket
08-10 14:11:22.957  6788  6908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 14:11:22.958  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 14:11:22.958  6788  6908 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-10 14:11:22.959  6788  6908 V BluetoothMapMasInstance: Succeed to create listening socket 
08-10 14:11:22.959  6788  6908 D BluetoothMapMasInstance: Accepting socket connection...
08-10 14:11:22.960  2232  2232 D c       : Getting all permits...
08-10 14:11:22.960  2232  2232 D a       : Opening database...
,08-10 14:11:22.963  1025  2083 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:22.963  6788  6824 D BluetoothAdapterProperties: Scan Mode:21
08-10 14:11:22.963  6788  6824 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-10 14:11:22.965  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:22.967  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:22.967  6788  6910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 14:11:22.968  2232  2232 D a       : Opening database auth.proximity.permit_store...
08-10 14:11:22.969  6788  6910 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-10 14:11:22.969  6788  6910 V BluetoothPbapService: Succeed to create listening socket 
08-10 14:11:22.969  6788  6910 V BluetoothPbapService: Accepting socket connection...
08-10 14:11:22.969  2232  2232 D a       : Closing database...
08-10 14:11:22.980  6145  6145 D BluetoothPermissionRequest: onReceive
,08-10 14:11:22.982  6145  6145 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 14:11:22.983  6145  6145 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 14:11:22.986  6788  6788 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-10 14:11:22.987  6788  6788 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-10 14:11:22.995  6788  6788 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-10 14:11:23.024  6788  6788 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-10 14:11:23.025  6788  6788 V BtOppService: onCreate
,08-10 14:11:23.029  6788  6788 V BluetoothOppNotification: send message
08-10 14:11:23.032  6788  6788 V BtOppService: Starting RfcommListener
08-10 14:11:23.038  6788  6788 D BluetoothOppPreference: Dumping Names:  
08-10 14:11:23.038  6788  6788 D BluetoothOppPreference: {}
08-10 14:11:23.038  6788  6788 D BluetoothOppPreference: Dumping Channels:  
08-10 14:11:23.038  6788  6788 D BluetoothOppPreference: {}
,08-10 14:11:23.041  6788  6788 V BtOppService: onStartCommand
08-10 14:11:23.044  6788  6913 V BtOppService: Deleted complete outbound shares, number =  0
08-10 14:11:23.045  6788  6916 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 14:11:23.045  6788  6788 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:23.045  6788  6788 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 14:11:23.046  6788  6913 V BtOppService: Deleted complete inbound failed shares, number = 0
08-10 14:11:23.047  6788  6913 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-10 14:11:23.048  6788  6788 V BluetoothOppNotification: new notify threadi!
08-10 14:11:23.049  6788  6788 V BluetoothOppNotification: send delay message
08-10 14:11:23.050  6788  6788 V BtOppService: start RfcommListener
,08-10 14:11:23.051  6788  6913 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ee8ffcc on behalf of 
,08-10 14:11:23.051  6788  6916 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 14:11:23.057  6788  6916 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1aed4215 on behalf of 
08-10 14:11:23.057  6788  6788 V BtOppService: RfcommListener started
08-10 14:11:23.057  6788  6788 V BtOppService: ContentObserver received notification
08-10 14:11:23.057  6788  6788 V BtOppService: ContentObserver received notification
08-10 14:11:23.062  6788  6919 V BtOppRfcommListener: Starting RFCOMM listener....
08-10 14:11:23.063  1025  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:23.063  6788  6918 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 14:11:23.064  6788  6919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 14:11:23.064  6788  6916 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 14:11:23.064  6788  6916 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 14:11:23.065  6788  6919 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-10 14:11:23.066  6788  6919 V BtOppRfcommListener: Started RFCOMM listener....
08-10 14:11:23.066  6788  6919 I BtOppRfcommListener: Accept thread started.
08-10 14:11:23.066  6788  6919 V BtOppRfcommListener: Accepting connection...
,08-10 14:11:23.068  6788  6916 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3265b92a on behalf of 
08-10 14:11:23.069  6788  6918 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1436d31b on behalf of 
,08-10 14:11:23.069  6788  6916 V BluetoothOppNotification: update too frequent, put in queue
08-10 14:11:23.070  6788  6916 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-10 14:11:23.072  6788  6918 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-10 14:11:23.074  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:23.075  6788  6788 V BluetoothFtpService: Ftp Service onCreate
08-10 14:11:23.075  6788  6788 I BluetoothFtpService: Ftp Service onCreate
08-10 14:11:23.075  6788  6788 V BluetoothFtpService: Ftp Service onStartCommand
08-10 14:11:23.075  6788  6788 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:23.075  6788  6788 V BluetoothFtpService: Starting Listening on sockets
08-10 14:11:23.075  6788  6788 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 14:11:23.076  6788  6788 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 14:11:23.076  6788  6788 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 14:11:23.076  6788  6788 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:23.076  6788  6788 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-10 14:11:23.076  6788  6788 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 14:11:23.079  6788  6918 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 14:11:23.080  6788  6788 V BluetoothFtpService: Handler(): got msg=1
08-10 14:11:23.080  6788  6788 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-10 14:11:23.080  6788  6788 V BluetoothFtpService: Ftp Service initSocket
08-10 14:11:23.081  6788  6918 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@266cea91 on behalf of 
,08-10 14:11:23.085  6788  6918 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 14:11:23.088  6788  6918 V BluetoothOppNotification: outbound notification was removed.
08-10 14:11:23.088  6788  6918 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 14:11:23.091  6788  6918 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8fe3df6 on behalf of 
08-10 14:11:23.092  6788  6918 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 14:11:23.093  1025  1041 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 14:11:23.094  6788  6788 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 14:11:23.096  6788  6918 V BluetoothOppNotification: inbound notification was removed.
08-10 14:11:23.096  6788  6918 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 14:11:23.098  6788  6788 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-10 14:11:23.098  6788  6788 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-10 14:11:23.098  6788  6918 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d6585f7 on behalf of 
08-10 14:11:23.101  6788  6920 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-10 14:11:23.114  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
,08-10 14:11:23.114  6788  6788 V BluetoothSapService: Sap Service onCreate
08-10 14:11:23.116  6788  6788 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:23.116  6788  6788 V BluetoothSapService: state: 12
08-10 14:11:23.116  6788  6788 V BluetoothSapService: Starting SAP server process
08-10 14:11:23.119  6788  6788 V BluetoothSapService: SAP Service startRfcommListenerThread
08-10 14:11:23.112  6921  6921 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:23.112  6921  6921 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 14:11:23.120  6788  6922 V BluetoothSapService: Sap Service initRfcommSocket
08-10 14:11:23.121  1025  1765 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:23.122  6788  6922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 14:11:23.123  6788  6922 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-10 14:11:23.123  6788  6922 V BluetoothSapService: Succeed to create listening socket 
08-10 14:11:23.123  6788  6922 V BluetoothSapService: Accepting socket connection...
08-10 14:11:23.132  6921  6921 V BT_SAP  : Event pipe created
08-10 14:11:23.132  6921  6921 V BT_SAP  : create_server_socket qcom.sap.server
08-10 14:11:23.132  6921  6921 V BT_SAP  : created socket fd 6
,08-10 14:11:23.283  1025  1921 I ActivityManager: Killing 6470:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-10 14:11:23.348  1025  1568 W libprocessgroup: failed to open /acct/uid_10011/pid_6470/cgroup.procs: No such file or directory
,08-10 14:11:24.051  6788  6788 V BluetoothOppNotification: new notify threadi!
,08-10 14:11:24.052  6788  6788 V BluetoothOppNotification: send delay message
,08-10 14:11:24.065  6788  6932 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 14:11:24.069  6788  6932 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d628a93 on behalf of 
08-10 14:11:24.071  6788  6932 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-10 14:11:24.074  6788  6932 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-10 14:11:24.075  6788  6932 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29dffad0 on behalf of 
,08-10 14:11:24.076  6788  6932 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 14:11:24.078  6788  6932 V BluetoothOppNotification: outbound notification was removed.
08-10 14:11:24.078  6788  6932 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 14:11:24.079  6788  6932 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fa95ac9 on behalf of 
,08-10 14:11:24.079  6788  6932 V BluetoothOppNotification: inbound: succ-0  fail-0,
,08-10 14:11:24.081  6788  6932 V BluetoothOppNotification: inbound notification was removed.
,08-10 14:11:24.081  6788  6932 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-10 14:11:24.082  6788  6932 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@153b15ce on behalf of 
,08-10 14:11:24.668  5818  5887 D io.jxcore.node.ConnectivityMonitor: stop,
,08-10 14:11:24.668  5818  5887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 14:11:24.773  1025  1531 E WifiStateMachine:  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:10751] from screen [on:0 period:1952269541]
,08-10 14:11:24.785  1025  1369 V AlarmManager: RTC_WAKEUP set : Alarm{162647c1 type 0 when 1470831077665 android} when 1470831077665
08-10 14:11:24.790  1025  1849 D AlarmManagerService: Setting time of day to sec=1470831084
08-10 14:11:24.573  1025  1849 W AlarmManagerService: Unable to set rtc to 1470831084: Invalid argument
08-10 14:11:24.585  1025  1531 E WifiStateMachine:  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):-185 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:-188] from screen [on:0 period:1952269353]
,08-10 14:11:24.590  1025  1531 E WifiStateMachine:  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):-184 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:1952269358]
08-10 14:11:24.590  1025  1531 D WifiNative-wlan0: doBoolean: SCAN
08-10 14:11:24.591  6585  6585 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-10 14:11:24.592  1025  6650 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-10 14:11:24.592  1025  6650 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-10 14:11:24.592  1025  6650 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-10 14:11:24.592  1025  6650 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-10 14:11:24.594  1025  1531 D WifiNative-wlan0: SCAN: returned true
08-10 14:11:24.612  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:11:24.617  1965  1965 I SecureClockService: Intent.ACTION_TIME_CHANGED 
08-10 14:11:24.618  1596  1596 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
08-10 14:11:24.625  2753  2753 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
,08-10 14:11:24.628  2753  2753 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-08-10 14:11:24...... Request
08-10 14:11:24.628  2753  2753 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 51, new day : false...... Request
08-10 14:11:24.628  2753  2753 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 51
08-10 14:11:24.628  2753  2753 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 6
08-10 14:11:24.630  2753  2753 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-08-10 14:11:24
08-10 14:11:24.639  1596  1596 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-10 14:11:24.644  1025  2030 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
08-10 14:11:24.650  2086  2086 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=10 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
08-10 14:11:24.653  2086  2086 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 10
,08-10 14:11:24.655  6290  6290 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-10 14:11:24.657  6290  6290 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5646
08-10 14:11:24.661  2086  2086 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 10
08-10 14:11:24.671  5096  5096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,08-10 14:11:24.695  2086  2086 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-10 14:11:24.741  1025  1999 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6935 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-10 14:11:24.770  1834  6934 I CheckinService: active receiver: enabled
08-10 14:11:24.780  2629  2629 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 14:11:24.855  6935  6969 D ALBootInit: ====action==>android.intent.action.TIME_SET
,08-10 14:11:24.863  6935  6969 D ALBootInit: Alarm ALBootInit: TIME_SET
,08-10 14:11:24.866  6935  6969 D Alarms  : [setNextAlert] start
08-10 14:11:24.882  6935  6969 D Alarms  : [setNextAlert] (1)
,08-10 14:11:24.886  6935  6969 D Alarms  :  minTime  = 0
,08-10 14:11:24.889  6935  6969 D Alarms  :  -- OK multi -- 0
08-10 14:11:24.890  6935  6969 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
08-10 14:11:24.890  6935  6969 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
08-10 14:11:24.917  6935  6969 I CommonUtil: BUILD Country: EU
08-10 14:11:24.919  6935  6969 D Alarms  : broadcastToWidgetProvider : false
,08-10 14:11:24.926  6935  6969 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
,08-10 14:11:24.946  1025  1999 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,08-10 14:11:24.954  6935  6935 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
08-10 14:11:24.957  6935  6935 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@399f04c2
08-10 14:11:24.959  6935  6935 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@399f04c2
08-10 14:11:24.964  6935  6935 D QuickCoverProvider: onReceiver
,08-10 14:11:24.978  1551  1551 I indal   : SmartCoverWidgetContext createApplicationContext
08-10 14:11:24.978  1551  1551 I indal   : SmartCoverWidgetContext createApplicationContext
,08-10 14:11:24.998  6608  6608 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:11:24
,08-10 14:11:25.002  6608  6608 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 14:11:25.002  6608  6608 D Weather.Utils: 2 : All the weather widget is gone.
,08-10 14:11:25.003  6608  6608 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-10 14:11:25.010  6608  6608 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c3452d3
,08-10 14:11:25.011  6608  6608 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 14:11:25.012  6608  6608 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-10 14:11:25.012  6608  6608 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 14:11:25.016  6608  6608 D Weather_cast: 2 : set auto-update time : 8/10 17:11
,08-10 14:11:25.024  6608  6608 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:11:25
,08-10 14:11:25.101  1025  1040 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6977 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 14:11:25.105  1025  1040 I ActivityManager: Killing 6567:com.android.chrome/u0a57 (adj 15): empty #17
,08-10 14:11:25.140  1025  1765 W libprocessgroup: failed to open /acct/uid_10057/pid_6567/cgroup.procs: No such file or directory
,08-10 14:11:25.193  6977  6977 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1470831085193
08-10 14:11:25.193  6977  6977 D         : TimeServiceNative: User Time to be set is 1470831085193
,08-10 14:11:25.193  6977  6977 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-10 14:11:25.193  6977  6977 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-10 14:11:25.193  6977  6977 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1470831085193
08-10 14:11:25.194  6977  6977 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-10 14:11:25.194   375  1024 D QC-time-services: Daemon: Connection accepted:time_genoff
08-10 14:11:25.194   375  6995 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1470831085193
08-10 14:11:25.194   375  6995 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1470831085193, operation = 0
08-10 14:11:25.194   375  6995 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/20/70 6:39:2
08-10 14:11:25.194   375  6995 D QC-time-services: Daemon:Value read from RTC seconds = 4343942000
08-10 14:11:25.195   375  6995 D QC-time-services: Daemon:new time 1470831085193 
08-10 14:11:25.195   375  6995 D QC-time-services: Daemon: delta 1466487143193 genoff 1466487143193 
,08-10 14:11:25.195   375  6995 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487143193 to memory
08-10 14:11:25.195   375  6995 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-10 14:11:25.195   375  6995 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-10 14:11:25.202   375  6995 D QC-time-services: Updating the TOD offset,
08-10 14:11:25.202   375  6995 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487143193 to memory
08-10 14:11:25.202   375  6995 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-10 14:11:25.202   375  6995 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-10 14:11:25.207   375  6995 E QC-time-services: Daemon:Update to modem bit set
08-10 14:11:25.207   375  6995 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-10 14:11:25.207   375  6995 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522343193
,08-10 14:11:25.207  6977  6977 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-10 14:11:25.210   375  1022 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-10 14:11:25.211   375  1024 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-10 14:11:25.215  5974  5974 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
08-10 14:11:25.217  5974  5974 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
08-10 14:11:25.219  1596  1596 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-10 14:11:25.219  1596  1596 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-10 14:11:25.220  1596  1596 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
,08-10 14:11:25.227  5974  5974 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
08-10 14:11:25.227  5974  5974 V [BNRBootReceiver]: Boot Receiver Return
08-10 14:11:25.287  1025  1999 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6996 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,08-10 14:11:25.291  1025  1999 I ActivityManager: Killing 6587:com.lge.drmservice/u0a62 (adj 15): empty #17
08-10 14:11:25.333  1025  1921 W libprocessgroup: failed to open /acct/uid_10062/pid_6587/cgroup.procs: No such file or directory
,08-10 14:11:25.375  6996  6996 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 14:11:25.423  6996  6996 D CalendarApplication: CalendarApplication.onCreate()
,08-10 14:11:25.439  6996  6996 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
,08-10 14:11:25.440  6996  6996 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3bbd84d1, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@38cf6b36, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@4bf4a37, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2b998ba4, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3dc49d0d, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@399f04c2, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2c3452d3, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@25b5be10, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3eaafd09, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@5dcab0e, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@15e7492f, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1520ab3c, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1f7d60c5, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@393c6a1a, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3129494b, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3deb3f28, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@b584441, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@4a70de6, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@7412f27, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@124925d4, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@28a3e37d, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2cc62272, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@50796c3, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@11fccb40, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@22103a79, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@254ff3be, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@242dc1f, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@34835b6c, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3510535, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@15138dca, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@22c31b3b, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@a00c258, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2599bfb1, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@ec4bc96, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2d3e3017, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3eebac04, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@27d9a5ed, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@a880c22, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@33ebb6b3, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2e798470, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2eb7b3e9, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyDa,ta@2c3ec86e,
08-10 14:11:25.447  6996  6996 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
08-10 14:11:25.457  6996  6996 D Config  : [init]
,08-10 14:11:25.459  6996  6996 I Config  : LGCalendar ver.4.40.16
08-10 14:11:25.459  6996  6996 I Config  : start check model
08-10 14:11:25.459  6996  6996 I Config  : start check native_ca
08-10 14:11:25.461  6996  6996 I Config  : Config Operator=OPEN, Country=EU
08-10 14:11:25.461  6996  6996 D Config  : [setDefaultValuesToPref]
08-10 14:11:25.461  6996  6996 D Config  : [parseProfiles]
08-10 14:11:25.467  6996  6996 D ProfilesParser: [debug_displayParseInfos] profile.country = null
08-10 14:11:25.468  6996  6996 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
08-10 14:11:25.468  6996  6996 D Config  : [updateProfiletoCountryInfo]
08-10 14:11:25.469  6996  6996 D GeneralPreference: [checkAndMigrateOldPreference]
08-10 14:11:25.500  6996  6996 E AgendaWidgetManager: [updateWidgets] 
,08-10 14:11:25.509  6996  7015 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
08-10 14:11:25.513  6996  7015 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
08-10 14:11:25.534  6996  7015 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,08-10 14:11:25.540  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
08-10 14:11:25.545  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
08-10 14:11:25.554  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,08-10 14:11:25.559  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
08-10 14:11:25.564  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
08-10 14:11:25.568  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
08-10 14:11:25.572  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,08-10 14:11:25.576  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
08-10 14:11:25.580  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
08-10 14:11:25.584  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
08-10 14:11:25.588  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
08-10 14:11:25.592  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
08-10 14:11:25.596  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,08-10 14:11:25.602  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
08-10 14:11:25.606  6996  7015 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
08-10 14:11:25.606  6996  7015 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
08-10 14:11:25.611  6996  7015 I AlertUtils: set default noti to content://media/internal/audio/media/41
08-10 14:11:25.617  6996  7015 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
08-10 14:11:25.664  6996  6996 D MonthWidgetProvider: [onReceive]
08-10 14:11:25.664  6996  6996 D CalendarWidgetProvider: [onReceive]
08-10 14:11:25.665  6996  6996 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
08-10 14:11:25.666  6996  7021 W HolidayIntentService: onHandleIntent
,08-10 14:11:25.669  6996  7021 D HolidayDataLoader: readJsonAsset : holiday.json
08-10 14:11:25.673  6996  6996 D CalendarTypeController: [onUpdateAndInitCalendarTime]
08-10 14:11:25.683  6996  6996 D WeekWidgetProvider: [onReceive]
08-10 14:11:25.683  6996  6996 D CalendarWidgetProvider: [onReceive]
08-10 14:11:25.683  6996  6996 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,08-10 14:11:25.685  6996  6996 D CalendarTypeController: [onUpdateAndInitCalendarTime]
08-10 14:11:25.690  2232  2232 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-10 14:11:25.712  6935  6935 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,08-10 14:11:25.716  6608  6608 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:11:25
08-10 14:11:25.717  6608  6608 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 14:11:25.717  6608  6608 D Weather.Utils: 2 : All the weather widget is gone.
08-10 14:11:25.718  6608  6608 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 14:11:25.719  6608  6608 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
08-10 14:11:25.719  6608  6608 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:11:25
08-10 14:11:25.724  2086  2086 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,08-10 14:11:25.728  5974  5974 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
08-10 14:11:25.728  2086  2840 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-10 14:11:25.728  5974  5974 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
08-10 14:11:25.728  2086  2840 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-10 14:11:25.728  2086  2840 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-10 14:11:25.729  2086  2840 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
08-10 14:11:25.730  2086  2840 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-10 14:11:25.731  1596  1596 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-10 14:11:25.731  1596  1596 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-10 14:11:25.731  1596  1596 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
08-10 14:11:25.733  5974  5974 V [BNRBootReceiver]: Boot Receiver Return
08-10 14:11:25.736  2086  2086 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,08-10 14:11:25.737  2086  5229 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-10 14:11:25.737  2086  5229 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-10 14:11:25.737  2086  5229 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-10 14:11:25.754  2086  5229 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
08-10 14:11:25.754  2086  5229 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
,08-10 14:11:25.757  6996  7021 E HolidayIntentService: onHandleIntent:holiday data empty
,08-10 14:11:25.760  1025  2106 I ActivityManager: Killing 6626:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-10 14:11:25.869  1025  1903 W libprocessgroup: failed to open /acct/uid_10093/pid_6626/cgroup.procs: No such file or directory
,08-10 14:11:27.476  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 14:11:27.476  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c0463e1 added. We now have 6 listener(s)
,08-10 14:11:27.477  5818  5887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 14:11:27.493  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 14:11:27.493  5818  5887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15534506 added. We now have 7 listener(s)
08-10 14:11:27.493  5818  5887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:11:27.494  5818  5887 I System.out: IsBluetoothEnabled
08-10 14:11:27.495  1025  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:27.495  1025  1963 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@ca55cc0 mBinding = false
08-10 14:11:27.514  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 14:11:27.515  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 14:11:27.515  1025  1025 D Ulp_jni : JNI:system_update. Event-4
,08-10 14:11:27.518  1025  1087 D BluetoothManagerService: Message: 2
08-10 14:11:27.519  1025  1087 D BluetoothManagerService: Sending off request.
08-10 14:11:27.520  6788  6804 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-10 14:11:27.521  6788  6820 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-10 14:11:27.521  6788  6820 D BluetoothAdapterProperties: Setting state to 13
08-10 14:11:27.521  6788  6820 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 14:11:27.522  6788  6820 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 14:11:27.522  6788  6820 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-10 14:11:27.525  6788  6824 D BluetoothAdapterProperties: Scan Mode:20
08-10 14:11:27.526  6788  6820 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-10 14:11:27.530  6788  6820 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 14:11:27.533  6788  6908 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-10 14:11:27.533  6788  6908 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 14:11:27.533  6788  6908 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-10 14:11:27.533  6788  6908 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-10 14:11:27.533  6788  6908 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-10 14:11:27.533  6788  6908 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-10 14:11:27.533  6788  6908 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-10 14:11:27.533  6788  6908 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-10 14:11:27.533  6788  6910 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 14:11:27.534  6788  6919 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 14:11:27.534  6788  6920 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 14:11:27.535  6788  6922 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 14:11:27.540  5818  5818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:27.540  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:27.540  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:27.540  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:27.540  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:27.540  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:11:27.540  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:27.540  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:27.540  5818  5818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:11:27.546  1025  1087 D BluetoothManagerService: Message: 60
08-10 14:11:27.546  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-10 14:11:27.546  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-10 14:11:27.548  5818  5818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:27.548  5818  5818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:27.557  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-10 14:11:27.557  6788  6864 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-10 14:11:27.564  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 14:11:27.564  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 14:11:27.564  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 14:11:27.564  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 14:11:27.564  6788  6864 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 14:11:27.564  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 14:11:27.564  6788  6864 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 14:11:27.564  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 14:11:27.564  6788  6864 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 14:11:27.564  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-10 14:11:27.564  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-10 14:11:27.564  6788  6864 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 14:11:27.571  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-10 14:11:27.575  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 14:11:27.581  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:27.583  6788  6788 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:27.583  6788  6788 D BluetoothMapService: STATE_TURNING_OFF
08-10 14:11:27.583  6788  6788 V BluetoothMapService: Handler(): got msg=4
08-10 14:11:27.583  6788  6788 D BluetoothMapService: MAP Service closeService in
08-10 14:11:27.583  6788  6788 D BluetoothMapMasInstance: MAP Service shutdown
08-10 14:11:27.584  6788  6788 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 14:11:27.584  6788  6788 V BluetoothMapService: MAP Service closeService out
,08-10 14:11:27.587  6788  6788 V BtOppService: Receiver DISABLED_ACTION 
08-10 14:11:27.587  6788  6788 I BtOppRfcommListener: stopping Accept Thread
08-10 14:11:27.587  6788  6788 V BtOppRfcommListener: close mBtServerSocket
08-10 14:11:27.587  6788  6919 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 14:11:27.588  6788  6788 V BtOppRfcommListener: waiting for thread to terminate
08-10 14:11:27.588  6788  6788 V BtOppRfcommListener: done waiting for thread to terminate
08-10 14:11:27.592  6145  6145 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-10 14:11:27.595  6145  6145 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-10 14:11:27.607  6788  6788 V BtOppService: onDestroy
,08-10 14:11:27.613  6788  6788 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-10 14:11:27.616  6788  6788 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 14:11:27.616  6788  6788 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:27.616  6788  6788 V BluetoothPbapReceiver: ***********state = 13
08-10 14:11:27.618  6788  6788 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-10 14:11:27.620  6788  6788 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:27.620  6788  6788 V BluetoothPbapService: state: 13
08-10 14:11:27.620  6788  6788 V BluetoothPbapService: Pbap Service closeService in
,08-10 14:11:27.625  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 14:11:27.632  6788  6788 V BluetoothPbapService: successfully stopped pbap service
08-10 14:11:27.632  6788  6788 V BluetoothPbapService: Pbap Service closeService out
08-10 14:11:27.635  6788  6788 V BluetoothPbapService: Pbap Service onDestroy
08-10 14:11:27.635  6788  6788 V BluetoothPbapService: Pbap Service closeService in
08-10 14:11:27.635  6788  6788 V BluetoothPbapService: Pbap Service closeService out
08-10 14:11:27.635  6788  6788 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-10 14:11:27.652  6145  6145 D DockEventReceiver: finishStartingService: stopping service
08-10 14:11:27.654  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:27.654  5818  5887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:11:27.654  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:11:27.654  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 14:11:27.654  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:11:27.654  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:11:27.654  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:11:27.654  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:11:27.654  5818  5887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:11:27.654  6145  6145 D BluetoothPbap: Proxy object disconnected
08-10 14:11:27.655  6145  6145 D PbapServerProfile: Bluetooth service disconnected
08-10 14:11:27.656  5818  5887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:11:27.656  5818  5887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:11:27.658  1025  1040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 14:11:27.658  1025  1040 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@ca55cc0 mBinding = false
08-10 14:11:27.660  6145  6145 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-10 14:11:27.665  6145  6145 D BluetoothPermissionRequest: onReceive
08-10 14:11:27.665  6145  6145 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-10 14:11:27.670  1025  1087 D BluetoothManagerService: Message: 1
08-10 14:11:27.670  1025  1087 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@ca55cc0
08-10 14:11:27.671  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 14:11:27.672  6788  6805 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
08-10 14:11:27.672  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 14:11:27.672  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-10 14:11:27.672  1025  1087 E BluetoothManagerService: IBluetooth.enable() returned false
08-10 14:11:27.674  6145  6145 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 14:11:27.677  6788  6788 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-10 14:11:27.678  6788  6788 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-10 14:11:27.678  6788  6788 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-10 14:11:27.683  6788  6788 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-10 14:11:27.683  6788  6788 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 14:11:27.684  6788  6788 V BluetoothFtpService: Ftp Service onStartCommand
08-10 14:11:27.684  6788  6788 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:27.684  6788  6788 V BluetoothFtpService: Ftp Service closeService
08-10 14:11:27.685  6788  6788 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-10 14:11:27.685  6788  6788 V BluetoothFtpService: successfully stopped ftp service
08-10 14:11:27.686  6788  6788 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 14:11:27.686  6788  6788 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 14:11:27.686  6788  6788 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 14:11:27.686  6788  6788 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:27.686  6788  6788 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-10 14:11:27.686  6788  6788 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 14:11:27.687  6788  6788 V BluetoothFtpService: Ftp Service onDestroy
08-10 14:11:27.687  6788  6788 V BluetoothFtpService: Ftp Service closeService
08-10 14:11:27.692  6788  6788 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:27.692  6788  6788 V BluetoothSapService: state: 13
08-10 14:11:27.692  6788  6788 V BluetoothSapService: Stopping SAP server process
08-10 14:11:27.693  6788  6788 V BluetoothSapService: Sap Service closeSapService in
08-10 14:11:27.693  6788  6788 V BluetoothSapService: Close listen Socket : 
08-10 14:11:27.693  6788  6788 V BluetoothSapService: Close rfcomm Socket : 
08-10 14:11:27.693  6788  6788 V BluetoothSapService: Close sapd  Socket : 
,08-10 14:11:27.697  6788  6788 V BluetoothSapService: Sap Service closeSapService out
08-10 14:11:27.697  6788  6788 V BluetoothSapService: Sap Service onDestroy
08-10 14:11:27.697  6788  6788 V BluetoothSapService: Sap Service closeSapService in
08-10 14:11:27.697  6788  6788 V BluetoothSapService: Close listen Socket : 
08-10 14:11:27.697  6788  6788 V BluetoothSapService: Close rfcomm Socket : 
08-10 14:11:27.697  6788  6788 V BluetoothSapService: Close sapd  Socket : 
08-10 14:11:27.697  6788  6788 V BluetoothSapService: Sap Service closeSapService out
08-10 14:11:28.075  1965  6651 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
,08-10 14:11:28.081  1025  6650 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-10 14:11:28.082  1025  6650 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-10 14:11:28.082  1025  6650 E WifiMonitor: WifiMonitor:p2p0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-10 14:11:28.082  1025  6650 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-10 14:11:28.082  1025  6650 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-10 14:11:28.082  1025  6650 E WifiMonitor: WifiMonitor:p2p0 cnt=37 dispatchEvent: WPS-AP-AVAILABLE 
08-10 14:11:28.082  1025  6650 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-10 14:11:28.083  1025  1531 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-10 14:11:28.083  1025  1531 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-10 14:11:28.084  1025  1531 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-10 14:11:28.084  1025  1531 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-10 14:11:28.084  1025  1531 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-10 14:11:28.086  1025  1528 D LGWifiP2pService: InactiveState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:28.086  1025  1528 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:28.086  1025  1528 D LGWifiP2pService: DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-10 14:11:28.075  1965  6651 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-10 14:11:28.105  6145  6145 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-10 14:11:28.115  6145  6145 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-10 14:11:28.574  6788  6824 D bt_hci_bdroid: cleanup
,08-10 14:11:28.582  6788  6866 I bt_lpm  : LPM is already off!!!
,08-10 14:11:28.583  6788  6887 I bt_userial_mct: exiting userial_read_thread
08-10 14:11:28.583  6788  6887 D bt_userial_mct: Leaving userial_evt_read_thread()
08-10 14:11:28.584  6788  6864 W bt-btif : ag scb idx 1 not allocated
,08-10 14:11:28.584  6788  6864 E bt-btif : BTA AG is already disabled, ignoring ...
08-10 14:11:28.584  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-10 14:11:28.584  6788  6864 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 14:11:28.584  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 14:11:28.584  6788  6864 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 14:11:28.585  6788  6864 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 14:11:28.585  6788  6864 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 14:11:28.588  6788  6824 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-10 14:11:28.590  6788  6866 I bt_vendor: hw_epilog_process
08-10 14:11:28.593  6788  6824 D bt_hci_bdroid: cleanup Finalizing cleanup
08-10 14:11:28.594  6788  6824 D bt_userial_mct: userial_close
08-10 14:11:28.594  6788  6824 E bt_userial_mct: pthread_join() FAILED result:3
08-10 14:11:28.594  6788  6824 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-10 14:11:28.619  6788  6824 D bt_hci_bdroid: set_power 0
08-10 14:11:28.619  6788  6824 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-10 14:11:28.620  6788  6824 I bt_vendor: bluetooth satus is on
08-10 14:11:28.620  6788  6824 I bt_vendor: bt-vendor : resetting BT status
08-10 14:11:28.620  6788  6824 I bt_vendor: Starting hciattach daemon
08-10 14:11:28.620  6788  6824 I bt_vendor: try to set false
,08-10 14:11:28.625  6788  6824 I bt_vendor: Starting hciattach daemon
08-10 14:11:28.625  6788  6824 I bt_vendor: try to set false
08-10 14:11:28.625  6788  6824 I bt_vendor: cleanup
08-10 14:11:28.626  6788  6864 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-10 14:11:28.626  6788  6824 I GKI_LINUX: GKI_exit_task 0 done
08-10 14:11:28.626  6788  6824 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-10 14:11:28.628  6788  6820 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-10 14:11:28.633  6788  6788 D HeadsetService: Received stop request...Stopping profile...
,08-10 14:11:28.638  6788  6788 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 14:11:28.638  6788  6788 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 14:11:28.639  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:28.640  6788  6841 D HeadsetStateMachine: Exit Disconnected: -1
08-10 14:11:28.645  6788  6820 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-10 14:11:28.648  1869  1869 D BluetoothHeadset: Proxy object disconnected
08-10 14:11:28.649  1869  1869 D BluetoothHeadset: Proxy object disconnected
08-10 14:11:28.649  1869  1869 D BluetoothHeadset: Proxy object disconnected
08-10 14:11:28.650  1025  1025 D BluetoothHeadset: Proxy object disconnected
08-10 14:11:28.650  1025  1025 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-10 14:11:28.651  6788  6788 D A2dpService: Received stop request...Stopping profile...
08-10 14:11:28.652  6788  6853 D A2dpStateMachine: Exit Disconnected: -1
08-10 14:11:28.653  6788  6788 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-10 14:11:28.654  6788  6788 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-10 14:11:28.655  6788  6788 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 14:11:28.655  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:28.657  6788  6788 D HidService: Received stop request...Stopping profile...
08-10 14:11:28.657  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:28.657  1025  1025 D BluetoothA2dp: Proxy object disconnected
08-10 14:11:28.657  1025  1025 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-10 14:11:28.662  6788  6788 D HealthService: Received stop request...Stopping profile...
08-10 14:11:28.662  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:28.664  6788  6788 D PanService: Received stop request...Stopping profile...
08-10 14:11:28.665  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:28.666  6788  6788 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 14:11:28.667  6788  6788 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 14:11:28.667  6788  6788 D BtGatt.GattService: stop()
08-10 14:11:28.667  6788  6788 D BtGatt.AdvertiseManager: advertise clients cleared
08-10 14:11:28.670  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
,08-10 14:11:28.675  6788  6788 D BluetoothMapService: Received stop request...Stopping profile...
08-10 14:11:28.675  6788  6788 D BluetoothMapService: stop()
08-10 14:11:28.677  6788  6788 D BluetoothMapEmailAppObserver: deinitObservers()
08-10 14:11:28.677  6788  6788 D BluetoothMapEmailAppObserver: removeReceiver()
08-10 14:11:28.677  6788  6788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25b5be10
08-10 14:11:28.680  6788  6788 D HeadsetStateMachine: Unbinding service...
08-10 14:11:28.681  6788  6788 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 14:11:28.681  6788  6788 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 14:11:28.681  6788  6788 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 14:11:28.681  6788  6788 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 14:11:28.681  6788  6788 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 14:11:28.681  6788  6788 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 14:11:28.681  6788  6788 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 14:11:28.681  6788  6788 I BluetoothA2dpServiceJni: cleanupNative
08-10 14:11:28.682  6788  6854 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-10 14:11:28.684  6788  6788 I GKI_LINUX: GKI_exit_task 2 done
08-10 14:11:28.684  6788  6788 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-10 14:11:28.685  6788  6788 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 14:11:28.685  6788  6788 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 14:11:28.685  6788  6788 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 14:11:28.686  6788  6788 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 14:11:28.686  6788  6788 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 14:11:28.686  6788  6788 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 14:11:28.686  6788  6788 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 14:11:28.688  6788  6788 V BluetoothMapService: Handler(): got msg=4
08-10 14:11:28.688  6788  6788 D BluetoothMapService: MAP Service closeService in
08-10 14:11:28.688  6788  6788 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 14:11:28.688  6788  6788 V BluetoothMapService: MAP Service closeService out
08-10 14:11:28.690  6788  6820 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-10 14:11:28.690  6788  6820 D BluetoothAdapterProperties: Setting state to 10
08-10 14:11:28.690  6788  6820 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-10 14:11:28.692  6788  6788 D BluetoothMapService: cleanup()
08-10 14:11:28.692  6788  6788 D BluetoothMapService: MAP Service closeService in
08-10 14:11:28.692  6788  6788 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 14:11:28.692  6788  6788 V BluetoothMapService: MAP Service closeService out
08-10 14:11:28.693  1025  1087 D BluetoothManagerService: Message: 60
08-10 14:11:28.693  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-10 14:11:28.693  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-10 14:11:28.696  6788  6820 I BluetoothAdapterState: Entering OffState
08-10 14:11:28.697  6145  6160 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:11:28.697  6145  6161 D BluetoothMap: onBluetoothStateChange: up=false
08-10 14:11:28.698  1869  1884 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:11:28.699  6145  6904 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 14:11:28.699  1025  1087 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:11:28.699  6145  6160 D BluetoothPan: onBluetoothStateChange on: false
08-10 14:11:28.701  1025  1087 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 14:11:28.702  6145  6161 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 14:11:28.702  1869  3164 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:11:28.703  6145  6904 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 14:11:28.703  1869  3166 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:11:28.704  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-10 14:11:28.708  1965  1965 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-10 14:11:28.710  1965  2202 D LGBluetoothAPIService: Message: 2
08-10 14:11:28.710  1965  2202 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3982d8c7 mBinding = false
08-10 14:11:28.711  1965  2202 D LGBluetoothAPIService: Sending unbind request.
08-10 14:11:28.714  5818  5818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:11:28.716  6145  6145 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-10 14:11:28.716  6145  6145 D LGBluetoothEventManager: [BTUI] clear device connection state
08-10 14:11:28.720  6145  6145 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-10 14:11:28.725  6788  6788 D LGBluetoothAPIServer: [BTUI] onUnbind()
08-10 14:11:28.725  6788  6788 D LGBluetoothAPIServer: [BTUI] cleanup() done
08-10 14:11:28.727  6788  6788 D LGBluetoothAPIServer: [BTUI] onDestroy()
08-10 14:11:28.729  6788  6788 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 14:11:28.729  6788  6788 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:11:28.730  6788  6788 V BluetoothPbapReceiver: ***********state = 10
08-10 14:11:28.733  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 14:11:28.738  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 14:11:28.754  6145  6145 D DockEventReceiver: finishStartingService: stopping service
,08-10 14:11:28.771  6145  6145 D BluetoothPermissionRequest: onReceive
,08-10 14:11:28.774  6145  6145 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 14:11:28.774  6145  6145 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-10 14:11:28.777  6145  6145 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 14:11:28.785  6788  6788 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-10 14:11:28.788  6788  6788 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-10 14:11:28.788  6788  6788 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-10 14:11:28.789  6788  6788 V BluetoothSapReceiver: SapReceiver onReceive 
,08-10 14:11:28.789  6788  6788 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-10 14:11:28.790  6788  6788 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-10 14:11:28.792  6268  6268 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-10 14:11:50.805  1025  1531 E WifiStateMachine:  DisconnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-10 14:11:50.806  1025  1531 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-10 14:11:50.808  1025  1531 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-10 14:11:50.821  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-10 14:11:50.822  1025  1531 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-10 14:11:52.186  1025  1369 V AlarmManager: ELAPSED_WAKEUP set : Alarm{11cbbb9f type 2 when 175597 com.google.android.gms} when 175597
,08-10 14:11:59.854  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:11:59.854  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:11:59.854  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-10 14:11:59.855  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:11:59.870  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:11:59.871  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:11:59.871  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:11:59.872  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:12:00.051  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 14:12:00.051  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 14:12:00.052  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:12:00.052  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:12:00.070  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:12:00.070  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:12:00.071  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:12:00.072  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:13:00.115  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:13:00.115  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 14:13:00.115  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated(),
08-10 14:13:00.116  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:13:00.132  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:13:00.132  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:13:00.133  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:13:00.134  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:13:05.092  1596  1596 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-10 14:13:05.092  1596  1596 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-10 14:13:05.110  1965  2162 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-10 14:13:05.110  1965  2162 D LEDHandler: Battery Level Remaining: 100%
08-10 14:13:05.110  1965  2162 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
,08-10 14:13:05.113  1596  1596 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-10 14:13:05.113  1596  1596 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-10 14:13:05.114  1025  1537 D WifiController: battery changed pluggedType: 2
08-10 14:13:05.115  1596  1596 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-10 14:13:05.121  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:13:05.121  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:13:05.123  5974  5974 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-10 14:13:17.495  1025  1369 D PowerManagerServiceEx: acquireWakeLockInternal: lock=705746151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,08-10 14:13:17.506  1025  1369 V AlarmManager: ELAPSED_WAKEUP set : Alarm{27e7b0b5 type 2 when 228497 android} when 228497
08-10 14:13:17.507  1025  1369 V AlarmManager: RTC_WAKEUP set : Alarm{367b934a type 0 when 1470831120295 com.google.android.gms} when 1470831120295
08-10 14:13:17.548  1834  7094 I EventLogService: Aggregate from 1470830493555 (log), 1470829320093 (data)
,08-10 14:13:17.562  2629  2629 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 14:13:17.586  1025  1025 D PowerManagerServiceEx: releaseWakeLockInternal: lock=705746151 [*alarm*], flags=0x0
,08-10 14:13:17.702  1834  7094 W EventLogAggregator: Unknown tag: snet_gcore
,08-10 14:13:17.702  1834  7094 W EventLogAggregator: Unknown tag: snet_launch_service
,08-10 14:14:00.095  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:14:00.095  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:14:00.096  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-10 14:14:00.096  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:14:00.112  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:14:00.112  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:14:00.114  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:14:00.116  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:14:29.844  1025  3296 I LocationManagerService: remove 19012305
,08-10 14:14:29.845  1025  3296 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-10 14:14:29.845  1025  3296 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 14:14:29.846  1025  3296 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-10 14:14:29.847  1025  3296 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-10 14:14:29.848  1025  3296 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-10 14:14:40.317  1025  1369 D PowerManagerServiceEx: acquireWakeLockInternal: lock=705746151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,08-10 14:14:40.379  2629  2629 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 14:14:40.404  1025  1025 D PowerManagerServiceEx: releaseWakeLockInternal: lock=705746151 [*alarm*], flags=0x0
,08-10 14:15:00.074  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:15:00.074  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:15:00.074  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:15:00.075  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:15:00.090  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:15:00.090  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:15:00.091  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:15:00.092  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:15:01.961  1025  1369 D PowerManagerServiceEx: acquireWakeLockInternal: lock=705746151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,08-10 14:15:01.979  6935  6935 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
08-10 14:15:01.982  6935  6935 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@399f04c2
,08-10 14:15:02.022  2629  2629 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 14:15:02.048  1025  1025 D PowerManagerServiceEx: releaseWakeLockInternal: lock=705746151 [*alarm*], flags=0x0
,08-10 14:16:00.109  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:16:00.110  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:16:00.110  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:16:00.110  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:16:00.125  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 14:16:00.125  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:16:00.127  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:16:00.131  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:17:00.115  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:17:00.115  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:17:00.116  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:17:00.116  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:17:00.131  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:17:00.131  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:17:00.132  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:17:00.133  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:17:05.733  1596  1596 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-10 14:17:05.733  1596  1596 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-10 14:17:05.758  1025  1537 D WifiController: battery changed pluggedType: 2
,08-10 14:17:05.763  1965  2162 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-10 14:17:05.763  1965  2162 D LEDHandler: Battery Level Remaining: 100%
08-10 14:17:05.763  1965  2162 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
08-10 14:17:05.765  1596  1596 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
08-10 14:17:05.765  1596  1596 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-10 14:17:05.767  1596  1596 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-10 14:17:05.770  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:17:05.770  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:17:05.773  5974  5974 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-10 14:17:51.776  1596  1596 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-10 14:17:51.776  1596  1596 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-10 14:17:51.792  1596  1596 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
08-10 14:17:51.792  1596  1596 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-10 14:17:51.796  1025  1537 D WifiController: battery changed pluggedType: 2
08-10 14:17:51.800  1965  2162 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-10 14:17:51.800  1965  2162 D LEDHandler: Battery Level Remaining: 100%
08-10 14:17:51.800  1965  2162 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
08-10 14:17:51.806  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:17:51.806  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 14:17:51.809  1596  1596 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-10 14:17:51.811  5974  5974 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-10 14:18:00.059  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 14:18:00.059  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 14:18:00.059  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:18:00.060  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:18:00.073  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 14:18:00.074  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:18:00.076  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:18:00.078  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:19:00.112  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:19:00.112  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:19:00.112  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:19:00.113  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:19:00.127  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:19:00.128  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:19:00.131  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:19:00.131  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:19:40.320  1025  1369 D PowerManagerServiceEx: acquireWakeLockInternal: lock=705746151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,08-10 14:19:40.386  2629  2629 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 14:19:40.411  1025  1025 D PowerManagerServiceEx: releaseWakeLockInternal: lock=705746151 [*alarm*], flags=0x0
,08-10 14:20:00.072  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:20:00.072  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:20:00.072  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:20:00.073  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:20:00.088  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:20:00.088  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:20:00.091  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:20:00.092  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:21:00.113  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:21:00.114  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated(),
08-10 14:21:00.114  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated(),
08-10 14:21:00.114  1596  1596 I [SystemUI]Clock: called onTimeUpdated(),
,08-10 14:21:00.133  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:21:00.133  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:21:00.134  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:21:00.134  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:22:00.113  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 14:22:00.113  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:22:00.113  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:22:00.114  1596  1596 I [SystemUI]Clock: called onTimeUpdated(),
,08-10 14:22:00.132  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:22:00.132  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:22:00.133  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:22:00.133  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:23:00.113  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:23:00.113  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 14:23:00.114  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-10 14:23:00.114  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:23:00.132  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:23:00.132  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:23:00.132  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:23:00.133  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:24:00.113  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:24:00.113  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 14:24:00.113  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-10 14:24:00.114  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:24:00.132  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:24:00.132  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:24:00.133  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:24:00.133  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:25:00.113  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:25:00.113  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 14:25:00.113  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-10 14:25:00.114  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:25:00.131  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:25:00.132  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:25:00.132  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:25:00.133  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:25:07.011  1596  1596 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-10 14:25:07.012  1596  1596 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-10 14:25:07.033  1025  1537 D WifiController: battery changed pluggedType: 2
,08-10 14:25:07.042  1596  1596 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
08-10 14:25:07.042  1596  1596 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-10 14:25:07.044  1965  2162 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-10 14:25:07.044  1965  2162 D LEDHandler: Battery Level Remaining: 100%
08-10 14:25:07.044  1965  2162 D LEDHandler: Battery Temp: 278, mChargingStatus=5, mChargingStop=false
08-10 14:25:07.046  1596  1596 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-10 14:25:07.052  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 14:25:07.052  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:25:07.054  5974  5974 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-10 14:26:00.107  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 14:26:00.107  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:26:00.107  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated(),
08-10 14:26:00.108  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:26:00.123  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:26:00.123  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:26:00.124  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:26:00.124  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:26:22.538  1025  1369 D PowerManagerServiceEx: acquireWakeLockInternal: lock=705746151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,08-10 14:26:22.554  1025  1369 V AlarmManager: ELAPSED_WAKEUP set : Alarm{bfa03d8 type 2 when 1045954 com.android.bluetooth} when 1045954
08-10 14:26:22.606  2629  2629 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 14:26:22.632  1025  1025 D PowerManagerServiceEx: releaseWakeLockInternal: lock=705746151 [*alarm*], flags=0x0
,08-10 14:27:00.080  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:27:00.080  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:27:00.080  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:27:00.081  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:27:00.096  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 14:27:00.097  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:27:00.101  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:27:00.102  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:27:56.460  1596  1596 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-10 14:27:56.460  1596  1596 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-10 14:27:56.471  1965  2162 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-10 14:27:56.471  1965  2162 D LEDHandler: Battery Level Remaining: 100%
08-10 14:27:56.471  1965  2162 D LEDHandler: Battery Temp: 276, mChargingStatus=5, mChargingStop=false
08-10 14:27:56.476  1596  1596 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
08-10 14:27:56.476  1596  1596 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-10 14:27:56.479  1025  1537 D WifiController: battery changed pluggedType: 2
08-10 14:27:56.486  1596  1596 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-10 14:27:56.489  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 14:27:56.489  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 14:27:56.492  5974  5974 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-10 14:28:00.058  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:28:00.059  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 14:28:00.059  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-10 14:28:00.060  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:28:00.075  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:28:00.076  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:28:00.078  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:28:00.083  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:29:00.117  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:29:00.117  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:29:00.118  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:29:00.118  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:29:00.132  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:29:00.132  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:29:00.133  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:29:00.134  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:29:16.753  1025  1082 I UsageStatsService: User[0] Flushing usage stats to disk
,08-10 14:30:00.109  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:30:00.110  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:30:00.110  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-10 14:30:00.110  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:30:00.126  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:30:00.126  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:30:00.128  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:30:00.131  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:30:01.983  1025  1369 D PowerManagerServiceEx: acquireWakeLockInternal: lock=705746151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,08-10 14:30:02.006  6935  6935 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-10 14:30:02.020  6935  6935 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@399f04c2
,08-10 14:30:02.054  2629  2629 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 14:30:02.081  1025  1025 D PowerManagerServiceEx: releaseWakeLockInternal: lock=705746151 [*alarm*], flags=0x0
,08-10 14:31:00.113  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:31:00.114  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 14:31:00.114  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-10 14:31:00.114  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:31:00.130  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:31:00.130  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:31:00.131  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:31:00.132  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:32:00.112  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:32:00.112  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:32:00.112  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:32:00.113  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-10 14:32:00.131  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:32:00.131  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:32:00.132  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:32:00.133  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 14:33:00.113  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 14:33:00.113  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 14:33:00.114  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 14:33:00.114  1596  1596 I [SystemUI]Clock: called onTimeUpdated(),
,08-10 14:33:00.132  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,08-10 14:33:00.132  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,08-10 14:33:00.133  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-10 14:33:00.134  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 14:34:00.114  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 14:34:00.115  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 14:34:00.115  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated(),
08-10 14:34:00.115  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
