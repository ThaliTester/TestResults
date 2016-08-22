#### Test 79763830f325397_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-22 12:03:30.279  5723  5723 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-22 12:03:30.355  5723  5723 D LgDataFeature: LgDataFeature() Constructor: none
08-22 12:03:30.355  5723  5723 D LgDataFeature: LgDataFeature() Constructor Done, null
08-22 12:03:30.422  5723  5723 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-22 12:03:30.441  5723  5723 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-22 12:03:30.442  5723  5723 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-22 12:03:30.458  5723  5723 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-22 12:03:30.458  5723  5723 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
08-22 12:03:30.471  1046  1764 I ActivityManager: Killing 5153:com.lge.clock/u0a10 (adj 15): empty #17
08-22 12:03:30.507  1046  1954 W libprocessgroup: failed to open /acct/uid_10010/pid_5153/cgroup.procs: No such file or directory
08-22 12:03:30.515  4341  5765 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-22 12:03:30.570  1046  2043 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5766 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 12:03:30.592  3404  4192 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-22 12:03:30.600  3404  4192 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@94727bb on behalf of 5723
08-22 12:03:30.634  5723  5723 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-22 12:03:30.664  5723  5723 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-22 12:03:30.738  5766  5766 D DocsApplication: Installing DEX configuration.
08-22 12:03:30.754  5766  5766 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-22 12:03:30.758  5766  5766 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{238b4c19 com.google.android.apps.docs}
08-22 12:03:30.773  5766  5766 D TAG     : onCreate()
08-22 12:03:30.793  5766  5766 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-22 12:03:30.908  1046  2013 V SIM_STK : Menu title from STK is T-Mobile
08-22 12:03:30.996  4341  5765 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 480 ms] updated apps [took 479 ms] 
,08-22 12:03:31.503  5805  5805 D AndroidRuntime: 
08-22 12:03:31.503  5805  5805 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 12:03:31.506  5805  5805 D AndroidRuntime: CheckJNI is OFF
08-22 12:03:31.689  5805  5805 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-22 12:03:31.696  1046  1945 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-22 12:03:31.705  1951  3767 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-22 12:03:31.707  1046  1945 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-22 12:03:31.708  1046  1945 D ActivityManager: setTaskToReturnTo : TaskRecord{32df01d5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-22 12:03:31.708  1046  1945 D ActivityManager: setTaskToReturnTo : TaskRecord{32df01d5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-22 12:03:31.709  1046  1945 D WindowStateEx: AppWindowTokenEx init.. 
08-22 12:03:31.710   346   358 E GBMv2   : DFP En is all cleared set to be enabled
08-22 12:03:31.742  1046  1945 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5820 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-22 12:03:31.744  5805  5805 D AndroidRuntime: Shutting down VM
08-22 12:03:31.808  1951  1968 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-22 12:03:31.808  1951  1968 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1afbe962 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-22 12:03:31.809  1951  1969 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-22 12:03:31.809  1951  1969 D SplitWindowPolicy: topRunningActivity=ActivityInfo{222a6af3 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-22 12:03:31.841  5820  5820 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-22 12:03:31.905  5820  5820 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-22 12:03:31.910  5820  5820 I LibraryLoader: Loading: webviewchromium
08-22 12:03:31.912  5820  5820 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 449-451)
08-22 12:03:31.912  5820  5820 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 12:03:31.922  5820  5820 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2bf49fdb}
08-22 12:03:31.922  5820  5820 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 12:03:31.923  5820  5820 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 12:03:31.929  5820  5820 I BrowserStartupController: Initializing chromium process, renderers=0
08-22 12:03:31.929  5820  5820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 12:03:31.934  5820  5843 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-22 12:03:31.940   320  1392 V AudioPolicyService: registerClient() client 0xb04104c0, uid 10118
08-22 12:03:31.942  5820  5820 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-22 12:03:31.943  5820  5820 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-22 12:03:31.943  5820  5820 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-22 12:03:31.944  1046  1128 D BluetoothManagerService: Message: 20
08-22 12:03:31.945  1046  1128 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28b347b7:true
08-22 12:03:31.946  5820  5847 D BluetoothAdapter: 1044314744: getState() :  mService = null. Returning STATE_OFF
,08-22 12:03:31.957  5820  5820 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-22 12:03:31.957  5820  5820 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-22 12:03:31.957  5820  5820 I Adreno-EGL: Build Date: 12/12/14 금
08-22 12:03:31.957  5820  5820 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-22 12:03:31.957  5820  5820 I Adreno-EGL: Remote Branch: 
08-22 12:03:31.957  5820  5820 I Adreno-EGL: Local Patches: 
08-22 12:03:31.957  5820  5820 I Adreno-EGL: Reconstruct Branch: 
08-22 12:03:32.003  1827  4498 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-22 12:03:32.012  5820  5820 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-22 12:03:32.015  5820  5853 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-22 12:03:32.026  5820  5820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:32.030  5820  5820 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-22 12:03:32.032  5820  5820 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-22 12:03:32.034  5820  5820 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-22 12:03:32.034  5820  5820 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-22 12:03:32.043  5820  5820 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-22 12:03:32.048  5820  5820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 12:03:32.048  5820  5820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:32.067  1827  4498 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-22 12:03:32.069  5820  5865 D OpenGLRenderer: Render dirty regions requested: true
08-22 12:03:32.069  5820  5865 I OpenGLRenderer: Initialized EGL, version 1.4
08-22 12:03:32.074  5820  5865 D OpenGLRenderer: Enabling debug mode 0
08-22 12:03:32.083  5820  5820 D Atlas   : Validating map...
,08-22 12:03:32.087  1046  1954 D SplitWindow: check instance of lgWin Window{246fabf9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-22 12:03:32.135  5820  5863 D LgDataFeature: LgDataFeature() Constructor: none
08-22 12:03:32.135  5820  5863 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-22 12:03:32.163  1827  4498 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-22 12:03:32.187  5766  5766 D LgDataFeature: LgDataFeature() Constructor: none
08-22 12:03:32.187  5766  5766 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-22 12:03:32.190  1046  1129 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +383ms (total +479ms)
08-22 12:03:32.193  1046  1129 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b40ddea u0 com.test.thalitest/.MainActivity t6} time:100732
08-22 12:03:32.195  5820  5820 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a0363a7 time:100734
08-22 12:03:32.282  5820  5820 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 12:03:32.301  5820  5820 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-22 12:03:32.301  5820  5820 I chromium: 
,08-22 12:03:32.319  5820  5863 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-22 12:03:32.319  5820  5863 I chromium: 
,08-22 12:03:32.404  5820  5888 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435161600
,08-22 12:03:32.412  5820  5888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 12:03:32.412  5820  5888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 12:03:32.412  5820  5888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 12:03:32.412  5820  5888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 12:03:32.412  5820  5888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-22 12:03:32.412  5820  5888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94727bb added. We now have 1 listener(s)
08-22 12:03:32.413  1046  1764 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5889 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-22 12:03:32.415  1046  1764 I ActivityManager: Killing 4718:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-22 12:03:32.463  1046  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 12:03:32.463  1046  2043 W libprocessgroup: failed to open /acct/uid_10085/pid_4718/cgroup.procs: No such file or directory
,08-22 12:03:32.465  5820  5888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-22 12:03:32.466  5820  5888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 12:03:32.467  5820  5888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 12:03:32.467  5820  5888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-22 12:03:32.474  5820  5888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dcf9316 added. We now have 1 listener(s)
08-22 12:03:32.474  5820  5888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 12:03:32.475   308   308 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
08-22 12:03:32.475   308   308 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
08-22 12:03:32.475   308   308 I rmt_storage: wakelock acquired: 1, error no: 42
08-22 12:03:32.476   308   924 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,08-22 12:03:32.485  1046  1553 D WifiService: New client listening to asynchronous messages
08-22 12:03:32.487  5766  5766 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-22 12:03:32.493  5820  5888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 12:03:32.493  5820  5888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-22 12:03:32.497  5820  5888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-22 12:03:32.497  5820  5888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 12:03:32.498  5820  5888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-22 12:03:32.506  5820  5888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 12:03:32.507  1046  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 12:03:32.507  5820  5888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-22 12:03:32.512  5820  5888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:32.513  5820  5888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:03:32.513  5820  5888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:03:32.513  5820  5888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 12:03:32.513  5820  5888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:03:32.513  5820  5888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:03:32.513  5820  5888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:03:32.513  5820  5888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:03:32.513  5820  5888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 12:03:32.513  5820  5888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-22 12:03:32.513  5820  5888 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 12:03:32.514  5820  5888 I io.jxcore.node.LifeCycleMonitor: start: OK
08-22 12:03:32.525  5889  5889 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-22 12:03:32.537  5889  5889 I LockScreenSettings: New app installed broadcast received ..
08-22 12:03:32.539  5820  5820 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-22 12:03:32.540  5889  5889 I LockScreenSettings: Number of installed packages  1
08-22 12:03:32.586  1046  1061 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5916 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-22 12:03:32.615   308   924 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
08-22 12:03:32.615   308   924 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
08-22 12:03:32.615   308   924 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
08-22 12:03:32.615   308   924 I rmt_storage: 
,08-22 12:03:32.617   308   308 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
08-22 12:03:32.617   911   923 E Diag_Lib: [IMS_FATAL]| 3347 | 923 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-22 12:03:32.656  5916  5916 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 12:03:33.123  1046  1954 V SIM_STK : Menu title from STK is T-Mobile
,08-22 12:03:33.182  1046  2043 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5958 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-22 12:03:33.252  5958  5958 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
,08-22 12:03:33.252  5958  5958 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-22 12:03:33.258  4858  4858 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-22 12:03:33.268   346   360 E GBMv2   : DFP En is all cleared set to be enabled
08-22 12:03:33.268   346   360 E GBMv2   : Set value is all cleared set the max
08-22 12:03:33.268   346   360 I GBMv2   : DFP Enabled. Ignore VFP set
,08-22 12:03:33.317  5820  5915 W jxcore-log: Initializing JXcore engine
08-22 12:03:33.317  5820  5915 W jxcore-log: JXcore engine is ready
,08-22 12:03:33.343  5915  5915 W Thread-647: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7331]" dev="sockfs" ino=7331 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-22 12:03:33.343  5915  5915 W Thread-647: type=1400 audit(0.0:151): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-22 12:03:33.343  5915  5915 W Thread-647: type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[7521]" dev="sockfs" ino=7521 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-22 12:03:33.343  5915  5915 W Thread-647: type=1400 audit(0.0:153): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-22 12:03:33.343  5915  5915 W Thread-647: type=1400 audit(0.0:154): avc: denied { ioctl } for path="socket:[28944]" dev="sockfs" ino=28944 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-22 12:03:33.363  5820  5915 W jxcore-log: Starting JXcore engine
08-22 12:03:33.417  1046  1945 I art     : Explicit concurrent mark sweep GC freed 31974(1495KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 42MB/64MB, paused 1.784ms total 149.397ms
,08-22 12:03:33.419  1046  2028 I ActivityManager: Killing 5235:com.google.android.gm/u0a64 (adj 15): empty #17
08-22 12:03:33.495  5820  5915 W jxcore-log: Platform android
08-22 12:03:33.495  5820  5915 W jxcore-log: 
08-22 12:03:33.495  5820  5915 W jxcore-log: Process ARCH arm
08-22 12:03:33.495  5820  5915 W jxcore-log: 
,08-22 12:03:33.523  1046  1914 W libprocessgroup: failed to open /acct/uid_10064/pid_5235/cgroup.procs: No such file or directory
,08-22 12:03:33.920  5820  5915 I jxcore-log: JXcore Cordova bridge is ready!
08-22 12:03:33.920  5820  5915 I jxcore-log: 
,08-22 12:03:33.920  5820  5915 W jxcore-log: JXcore engine is started
,08-22 12:03:33.928  5820  5888 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-22 12:03:33.935  5820  5820 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 12:03:34.702  2791  2791 I MusicWidget: mDelayedStopHandler : unbind
,08-22 12:03:34.707  2135  2135 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-22 12:03:34.707  2135  2135 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-22 12:03:34.708  2135  2135 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-22 12:03:34.716  2135  2135 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-22 12:03:34.716  2135  2135 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-22 12:03:34.717  2135  2135 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-22 12:03:34.721  2135  2135 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-22 12:03:34.722  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-22 12:03:34.723  1046  1945 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@34a1f1a8com.lge.music.MediaPlaybackService$5@108544c1
08-22 12:03:34.724  2135  2135 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-22 12:03:34.724  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-22 12:03:34.726  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-22 12:03:34.728  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-22 12:03:34.729  2135  2135 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@36135eb7
08-22 12:03:34.729  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-22 12:03:34.731  2135  2135 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-22 12:03:34.731  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-22 12:03:34.731  2135  2135 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-22 12:03:34.732  2135  2135 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-22 12:03:34.732  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-22 12:03:34.733  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-22 12:03:34.733  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-22 12:03:34.734  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-22 12:03:34.734  2135  2135 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-22 12:03:34.735  2135  2135 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-22 12:03:34.737  2135  2135 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-22 12:03:34.737  2135  2135 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-22 12:03:34.737  2135  2135 V MediaPlayer[Native]: reset
08-22 12:03:34.743  2135  2135 V MediaPlayer[Native]: setListener
08-22 12:03:34.743  2135  2135 V MediaPlayer[Native]: disconnect
08-22 12:03:34.743  2135  2135 V MediaPlayer[Native]: destructor
08-22 12:03:34.744   320  2163 V AudioFlinger: releasing 18 from 2135 for -1
08-22 12:03:34.744   320  2163 V AudioFlinger:  decremented refcount to 0
08-22 12:03:34.744   320  2163 V AudioFlinger: purging stale effects
08-22 12:03:34.744  2135  2135 V MediaPlayer[Native]: disconnect
08-22 12:03:34.745  2135  2135 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-22 12:03:34.746  2135  2135 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-22 12:03:34.747  2135  2135 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-22 12:03:34.748  2135  2135 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-22 12:03:34.748  2135  2135 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-22 12:03:34.748  2135  2135 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-22 12:03:34.749  2135  2135 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 301417574
08-22 12:03:34.749  2135  2135 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 301417574
,08-22 12:03:34.759  2135  2135 I SmartShareClient: [SmartShareManagerClient] terminate service: 2135/MediaPlaybackService/335253717
08-22 12:03:34.762  2135  2135 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-22 12:03:34.762  2135  2135 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@a0363a7
08-22 12:03:34.765  2135  2135 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-22 12:03:34.765  2135  2135 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-22 12:03:34.766  2135  2135 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-22 12:03:34.766  2135  2135 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-22 12:03:34.768  1046  1584 I ActivityManager: Killing 4996:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-22 12:03:34.769  2135  2135 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
,08-22 12:03:34.793  4969  4969 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-22 12:03:34.793  4969  4969 W System.err: android.os.DeadObjectException
08-22 12:03:34.793  4969  4969 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-22 12:03:34.793  4969  4969 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-22 12:03:34.793  4969  4969 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-22 12:03:34.793  4969  4969 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-22 12:03:34.793  4969  4969 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-22 12:03:34.793  4969  4969 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-22 12:03:34.793  4969  4969 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 12:03:34.794  4969  4969 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 12:03:34.794  4969  4969 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-22 12:03:34.794  4969  4969 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-22 12:03:34.794  4969  4969 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:34.794  4969  4969 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:34.794  4969  4969 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-22 12:03:34.794  4969  4969 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-22 12:03:34.794  4969  4969 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-22 12:03:34.794  4969  4969 W System.err: android.os.DeadObjectException
08-22 12:03:34.795  4969  4969 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-22 12:03:34.795  4969  4969 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-22 12:03:34.795  4969  4969 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-22 12:03:34.795  4969  4969 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-22 12:03:34.795  4969  4969 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-22 12:03:34.795  4969  4969 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-22 12:03:34.795  4969  4969 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 12:03:34.795  4969  4969 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 12:03:34.795  4969  4969 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-22 12:03:34.795  4969  4969 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-22 12:03:34.795  4969  4969 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:34.795  4969  4969 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:34.795  4969  4969 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-22 12:03:34.795  4969  4969 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-22 12:03:34.795  4969  4969 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-22 12:03:34.796  4969  4969 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-22 12:03:34.975  1046  1584 E libprocessgroup: failed to kill 1 processes for processgroup 4996
,08-22 12:03:35.151  1046  1915 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms,
,08-22 12:03:35.157  4969  4969 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,08-22 12:03:35.157  4969  4969 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-22 12:03:35.196  1046  1914 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=5992 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-22 12:03:35.197  4969  4969 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-22 12:03:35.257  5992  5992 D UEI.SmartControl: Quickset Services start...
08-22 12:03:35.259  5992  5992 I UEI.SmartControl: Manufacture = LGE
08-22 12:03:35.259  5992  5992 D UEI.SmartControl: Id = LGNevo
,08-22 12:03:35.262  5992  5992 D UEI.SmartControl: File observer start...
08-22 12:03:35.263  5992  5992 E UEI.SmartControl: IR Port is disabled: false
08-22 12:03:35.271  5992  5992 D UEI.SmartControl: Starting file observer...
08-22 12:03:35.271  5992  5992 D UEI.SmartControl: Extracting JNI libs...
08-22 12:03:35.271  5992  5992 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-22 12:03:35.372  5992  5992 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-22 12:03:35.372  5992  5992 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-22 12:03:35.372  5992  5992 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-22 12:03:35.406  5992  5992 I UEI.SmartControl: --- Selecting new region: 6
,08-22 12:03:35.408  5992  5992 I UEI.SmartControl: Model = LG-D855
08-22 12:03:35.410  5992  5992 D UEI.SmartControl: QS Service created
08-22 12:03:35.424  5992  5992 I UEI.SmartControl: Service initServices...
,08-22 12:03:35.428  5992  5992 D UEI.SmartControl: QS start get config
,08-22 12:03:35.469  5992  5992 D UEI.SmartControl: Loading JNI Libs...
,08-22 12:03:35.712  5992  5992 I UEI.SmartControl: Supports setup maps: true
08-22 12:03:35.715  5992  5992 D UEI.SmartControl: QS start statue = true Error code = 0
,08-22 12:03:35.715  5992  5992 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-22 12:03:35.715  5992  5992 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-22 12:03:35.715  5992  5992 I UEI.SmartControl: ### init IR Blaster...
08-22 12:03:35.719  5992  5992 D serial_port: Configuring serial port
08-22 12:03:35.722  5992  5992 E UEI.SmartControl: UEIBLaster setting for 616
08-22 12:03:35.722  5992  5992 I UEI.SmartControl: Setting serial record hearder size = 2
08-22 12:03:35.722  5992  5992 I UEI.SmartControl: configuring settings for MAXQ616
08-22 12:03:35.722  5992  5992 I UEI.SmartControl: Get version...
08-22 12:03:35.739  5992  6016 D UEI.SmartControl: serial port data available: 21
,08-22 12:03:35.766  5992  5992 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-22 12:03:35.766  5992  5992 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-22 12:03:35.767  5992  5992 I UEI.SmartControl: QS saving settings...
08-22 12:03:35.767  5992  5992 D UEI.SmartControl: IR Blaster version: 25672567
,08-22 12:03:35.784  5992  6016 D UEI.SmartControl: serial port data available: 4
,08-22 12:03:35.823  5992  6019 I UEI.SmartControl: Device manager: loading config....
,08-22 12:03:35.826  5992  6019 D UEI.SmartControl: ----------- loading internal config...
08-22 12:03:35.830  5992  5992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-22 12:03:35.833  5992  5992 E UEI.SmartControl: Services init done
08-22 12:03:35.833  5992  5992 D UEI.SmartControl: QS Service init finished
08-22 12:03:35.833  5992  5992 D UEI.SmartControl: QS Service version name: 2.1.91
08-22 12:03:35.834  5992  5992 D UEI.SmartControl: QS Service version code: 201091
08-22 12:03:35.841  5992  5992 D UEI.SmartControl: Service requested: Control
,08-22 12:03:35.848  5992  6019 E UEI.SmartControl: Loading SETTINGS...
08-22 12:03:35.852  5992  5992 D UEI.SmartControl: Request IControl service: devices are loaded...
08-22 12:03:35.857  1046  1988 I ActivityManager: Killing 4969:com.lge.qremote/u0a112 (adj 15): empty #17
,08-22 12:03:35.864  5992  6019 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-22 12:03:35.880  5992  6018 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-22 12:03:35.880  5992  6018 D UEI.SmartControl: -----service ready thread exits
,08-22 12:03:35.995  1046  1584 W libprocessgroup: failed to open /acct/uid_10112/pid_4969/cgroup.procs: No such file or directory
,08-22 12:03:35.998  5992  5992 D UEI.SmartControl: Internal service binding...
08-22 12:03:36.314  5766  5766 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-22 12:03:36.326  1046  1764 I ActivityManager: Killing 5278:com.google.android.talk/u0a72 (adj 15): empty #17
08-22 12:03:36.462  1046  1981 W libprocessgroup: failed to open /acct/uid_10072/pid_5278/cgroup.procs: No such file or directory
,08-22 12:03:37.260  5766  5884 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-22 12:03:38.102  1046  1945 I ActivityManager: Killing 4910:com.android.calendar/u0a13 (adj 15): empty #17
,08-22 12:03:38.195  1046  1725 W libprocessgroup: failed to open /acct/uid_10013/pid_4910/cgroup.procs: No such file or directory
,08-22 12:03:38.427  1827  5587 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-22 12:03:38.432   311  6045 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-22 12:03:38.433  1046  1126 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-22 12:03:38.433  1827  5587 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-22 12:03:38.434  1827  1827 I ConfigFetchService: fetch service done; releasing wakelock
08-22 12:03:38.435  1827  1827 I ConfigFetchService: stopping self
08-22 12:03:38.439  2234  2234 I ConfigService: onDestroy
,08-22 12:03:40.815  5992  6017 D serial_port: close(fd = 25)
,08-22 12:03:40.822  5992  6017 I UEI.SmartControl: Serial port is closed.
08-22 12:03:40.823  5992  6020 D UEI.SmartControl: Internal timer expired: 1
08-22 12:03:40.824  5992  6020 D UEI.SmartControl: unbind internal service
08-22 12:03:40.832  5992  5992 D UEI.SmartControl: Service.onUnbind: IControl
,08-22 12:03:40.836  5992  5992 D UEI.SmartControl: Service.onDestroy
,08-22 12:03:40.837  5992  5992 D UEI.SmartControl: Lock is in USE false
08-22 12:03:40.837  5992  5992 D UEI.SmartControl: unbind internal service
08-22 12:03:40.837  5992  5992 I UEI.SmartControl: Serial port is closed.
08-22 12:03:40.837  5992  5992 I UEI.SmartControl: Serial port is closed.
08-22 12:03:40.837  5992  5992 D UEI.SmartControl: Blaster closed
08-22 12:03:40.838  5992  5992 D UEI.SmartControl: Shut down QS...
,08-22 12:03:40.838  5992  5992 D UEI.SmartControl: Stopping QS lib
08-22 12:03:40.838  5992  5992 D UEI.SmartControl: QS lib stop result = true
08-22 12:03:40.839  5992  5992 D UEI.SmartControl: Stopped QS lib
08-22 12:03:40.840  5992  5992 D UEI.SmartControl: Stopped file observer...
08-22 12:03:40.841  5992  5992 D UEI.SmartControl: QS shutdown complete
,08-22 12:03:43.477  1046  1113 I ActivityManager: Waited long enough for: ServiceRecord{2cfb1546 u0 com.google.android.gms/.wearable.service.WearableService}
,08-22 12:03:44.585  5820  5915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 12:03:44.585  5820  5915 I jxcore-log: 
,08-22 12:03:44.589  5820  5915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 12:03:44.589  5820  5915 I jxcore-log: 
,08-22 12:03:44.593  5820  5915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:44.593  5820  5915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:03:44.593  5820  5915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:03:44.593  5820  5915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 12:03:44.593  5820  5915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:03:44.593  5820  5915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:03:44.593  5820  5915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:03:44.593  5820  5915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:03:44.593  5820  5915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 12:03:44.594  5820  5915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:44.594  5820  5915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 12:03:44.598  5820  5915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 12:03:44.598  5820  5915 I jxcore-log: 
08-22 12:03:44.601  5820  5915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 12:03:44.601  5820  5915 I jxcore-log: 
08-22 12:03:44.781  2135  2135 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19986
,08-22 12:03:45.556  5820  5915 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-22 12:03:45.557  5820  5915 I jxcore-log: Failed to execute UT.
08-22 12:03:45.557  5820  5915 I jxcore-log: 
08-22 12:03:45.557  5820  5915 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-22 12:03:45.557  5820  5915 I jxcore-log: 
,08-22 12:03:45.570  5820  5915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 12:03:45.570  5820  5915 I jxcore-log: 
08-22 12:03:45.576  5820  5820 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-22 12:03:45.773  1046  1410 V AlarmManager: RTC_WAKEUP set : Alarm{139e9ad9 type 0 when 1471860225463 com.android.vending} when 1471860225463
,08-22 12:03:45.918  4246  6051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-22 12:03:45.956  6049  6049 D AndroidRuntime: 
08-22 12:03:45.956  6049  6049 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-22 12:03:45.961  6049  6049 D AndroidRuntime: CheckJNI is OFF
08-22 12:03:45.970  1046  1915 V SIM_STK : Menu title from STK is T-Mobile
,08-22 12:03:46.086  6049  6049 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-22 12:03:46.097  1046  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-22 12:03:46.097  1046  1113 I ActivityManager: Killing 5820:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-22 12:03:46.144  5723  5723 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-22 12:03:46.174  1046  1553 D WifiService: Client connection lost with reason: 4
,08-22 12:03:46.175  1046  1915 I WindowState: WIN DEATH: Window{246fabf9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-22 12:03:46.183  1046  1915 D InputDispatcher: Window went away: Window{246fabf9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-22 12:03:46.310  1046  1113 I ActivityManager:   Force finishing activity ActivityRecord{1b40ddea u0 com.test.thalitest/.MainActivity t6}
,08-22 12:03:46.352   346   358 E GBMv2   : DFP En is all cleared set to be enabled
,08-22 12:03:46.357  1046  1134 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-22 12:03:46.359  1046  1134 I ActivityManager:   Force finishing activity ActivityRecord{1b40ddea u0 com.test.thalitest/.MainActivity t6 f}
08-22 12:03:46.359  1046  1134 W ActivityManager: Duplicate finish request for ActivityRecord{1b40ddea u0 com.test.thalitest/.MainActivity t6 f}
,08-22 12:03:46.396  1951  1968 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-22 12:03:46.397  1046  1914 W ActivityManager: Spurious death for ProcessRecord{a8c3c9e 5820:com.test.thalitest/u0a118}, curProc for 5820: null
08-22 12:03:46.397  1951  1968 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2397c3b0 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-22 12:03:46.397  2044  2044 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-22 12:03:46.399  2044  2044 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-22 12:03:46.400  1951  1969 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-22 12:03:46.401  1951  1969 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f5e2229 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-22 12:03:46.402  2044  2044 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-22 12:03:46.404  2044  2134 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-22 12:03:46.408  1611  1611 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-22 12:03:46.416  2006  2006 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-22 12:03:46.417  2742  2742 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-22 12:03:46.423  1046  1470 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-22 12:03:46.430  2482  2638 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 12:03:46.436  5057  5057 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-22 12:03:46.436  1916  1916 D ActionManagerService: notifyUserLog: 1000003
08-22 12:03:46.437  2742  4199 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-22 12:03:46.437  2044  2044 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-22 12:03:46.442  2044  2044 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-22 12:03:46.448   311  6092 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-22 12:03:46.448  1046  1126 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-22 12:03:46.451  1827  1827 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-22 12:03:46.452  2044  2044 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-22 12:03:46.453  2044  2044 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-22 12:03:46.456  1611  1611 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-22 12:03:46.456  1611  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-22 12:03:46.456  1611  1660 D KeyguardModel: createShortcutInfo...
08-22 12:03:46.456  1916  1916 D ActionManagerService: notifyUserLog: 1000004
08-22 12:03:46.457  2742  4199 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-22 12:03:46.457  2044  2044 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-22 12:03:46.460  1611  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-22 12:03:46.461  1611  1660 D KeyguardModel: createShortcutInfo...
08-22 12:03:46.462  2742  2759 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-22 12:03:46.469  4246  4246 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-22 12:03:46.469  4246  4246 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-22 12:03:46.469  4246  4246 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-22 12:03:46.470  4246  4246 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-22 12:03:46.470  4246  4246 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 12:03:46.470  4246  4246 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 12:03:46.470  4246  4246 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-22 12:03:46.470  4246  4246 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-22 12:03:46.470  4246  4246 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:46.470  4246  4246 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:46.470  4246  4246 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-22 12:03:46.470  4246  4246 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-22 12:03:46.473  1611  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 12:03:46.473  1611  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-22 12:03:46.474  2234  2234 I ConfigService: onCreate
08-22 12:03:46.475  2234  2234 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-22 12:03:46.484  1611  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-22 12:03:46.484  1611  1660 D KeyguardModel: createShortcutInfo...
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , create_time: 1430832262123
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , expire_time: 0
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , display: false
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , animation: false }
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , create_time: 1430832262287
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , expire_time: 0
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , display: false
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , animation: false }
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , create_time: 1471602816196
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , expire_time: 0
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , display: false
08-22 12:03:46.489  2044  2044 I GBoardWebViewUtils: , animation: false }
08-22 12:03:46.491  1611  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 12:03:46.491  1611  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-22 12:03:46.493  1827  1827 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-22 12:03:46.496  2234  2234 I ConfigService: onBind returning update interface
08-22 12:03:46.498  2234  2234 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-22 12:03:46.498  2234  2234 I ConfigService: onBind returning config service
08-22 12:03:46.503  1611  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-22 12:03:46.503  1611  1660 D KeyguardModel: createShortcutInfo...
08-22 12:03:46.505  1611  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 12:03:46.505  1611  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-22 12:03:46.511  4341  4341 I art     : Explicit concurrent mark sweep GC freed 383(28KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 814us total 142.296ms
,08-22 12:03:46.514  1611  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-22 12:03:46.514  1611  1660 D KeyguardModel: createShortcutInfo...
08-22 12:03:46.515  1879  1879 D SplitUIManager: split_name #11 / not available #0
08-22 12:03:46.516  1879  1879 D SplitUIService: removed split : 
08-22 12:03:46.522  1611  1611 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-22 12:03:46.522  1611  1611 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-22 12:03:46.523  2044  6094 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-22 12:03:46.526  1611  1611 D KeyguardModel: handleShortcutListChanged...
08-22 12:03:46.526  1611  1611 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-22 12:03:46.529  2044  2044 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-22 12:03:46.529  2044  2044 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-22 12:03:46.530  2234  2234 I ConfigService: onDestroy
08-22 12:03:46.532  1611  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-22 12:03:46.533  1611  1660 D KeyguardModel: createShortcutInfo...
08-22 12:03:46.544  1611  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-22 12:03:46.545  1611  1660 D KeyguardModel: createShortcutInfo...
08-22 12:03:46.546  1611  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 12:03:46.546  1611  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-22 12:03:46.547  1611  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-22 12:03:46.547  1611  1660 D KeyguardModel: createShortcutInfo...
,08-22 12:03:46.550  1611  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 12:03:46.550  1611  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-22 12:03:46.553  1611  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-22 12:03:46.553  1611  1660 D KeyguardModel: createShortcutInfo...
08-22 12:03:46.554  1611  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 12:03:46.554  1611  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-22 12:03:46.560  1611  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-22 12:03:46.560  1611  1660 D KeyguardModel: createShortcutInfo...
,08-22 12:03:46.562  1879  1879 D SplitUIManager: split_name #11 / not available #0
08-22 12:03:46.562  1879  1879 I SplitUIService: split app #11
08-22 12:03:46.569  1827  6103 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-22 12:03:46.571  1046  1046 I art     : Explicit concurrent mark sweep GC freed 18086(1349KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 42MB/64MB, paused 2.105ms total 187.404ms
08-22 12:03:46.573  1046  1134 I art     : WaitForGcToComplete blocked for 166.573ms for cause Explicit
,08-22 12:03:46.574  1611  1611 D KeyguardModel: handleShortcutListChanged...
08-22 12:03:46.574  1611  1611 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-22 12:03:46.587  1046  1111 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-22 12:03:46.602  1046  2013 V SIM_STK : Menu title from STK is T-Mobile
,08-22 12:03:46.611  2044  2044 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-22 12:03:46.624  5352  6109 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-22 12:03:46.637  1827  6111 I PeopleContactsSync: CP2 sync disabled
08-22 12:03:46.651  1827  4498 I Icing   : doRemovePackageData com.test.thalitest
08-22 12:03:46.654  5622  5622 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-22 12:03:46.669  5666  5666 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-22 12:03:46.691  2044  2044 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-22 12:03:46.691  2345  6113 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-22 12:03:46.693  2044  2044 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 12:03:46.695  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-22 12:03:46.695  1046  1062 V SIM_STK : Menu title from STK is T-Mobile
08-22 12:03:46.696  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-22 12:03:46.697  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-22 12:03:46.698  2006  2006 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-22 12:03:46.698  2006  2006 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-22 12:03:46.698  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-22 12:03:46.699  2006  2006 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-22 12:03:46.703  5057  5057 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-22 12:03:46.707  1827  6110 W GmsApplication: Using Auth Proxy for data requests.
08-22 12:03:46.710  1046  1046 D administrator: Handling package changes for user 0
08-22 12:03:46.711  1827  6110 W GmsApplication: Using Auth Proxy for data requests.
08-22 12:03:46.718  2044  2044 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,08-22 12:03:46.718  2044  2044 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 12:03:46.721  2044  2774 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-22 12:03:46.722  2044  2774 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-22 12:03:46.734  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-22 12:03:46.735  2044  2044 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-22 12:03:46.735  2044  2044 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 12:03:46.742  1046  1981 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6118 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-22 12:03:46.743  1046  1129 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2e66e140 u0 com.lge.launcher2/.Launcher t5} time:115283
08-22 12:03:46.744  2044  2044 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-22 12:03:46.748  2601  2601 D [Concierge]Service: onStartCommand(). Type : 8
08-22 12:03:46.748  2601  2601 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-22 12:03:46.750  2601  2601 D [Concierge]Service: Update widget ID : 11
08-22 12:03:46.751  2044  2044 D [Concierge]WidgetView: change position of spinner
08-22 12:03:46.751  2044  2044 I [Concierge]WidgetView: initWebView(). Time : 1471860226751
08-22 12:03:46.752  2601  2601 D [Concierge]Service: onStartCommand(). Type : 0
08-22 12:03:46.752   340   426 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-22 12:03:46.752  3216  6128 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-22 12:03:46.768  2044  2044 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 966954579
,08-22 12:03:46.768  2044  2044 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-22 12:03:46.769  2044  2044 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-22 12:03:46.772  2044  2044 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3403046b
08-22 12:03:46.772  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-22 12:03:46.773  2044  2044 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-22 12:03:46.774  2044  2044 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 12:03:46.779  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-22 12:03:46.779  2044  2044 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-22 12:03:46.780  2044  2044 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471860139522, New one : 1471860226751
08-22 12:03:46.781  2044  2044 D [Concierge]WidgetView: Unregister all receivers
,08-22 12:03:46.781  2044  2044 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-22 12:03:46.781  2044  2044 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 12:03:46.783  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-22 12:03:46.784  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-22 12:03:46.785  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-22 12:03:46.786  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-22 12:03:46.787  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-22 12:03:46.790  2044  2044 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 12:03:46.790  2044  2044 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-22 12:03:46.818  1827  6105 I art     : Explicit concurrent mark sweep GC freed 18517(1260KB) AllocSpace objects, 16(256KB) LOS objects, 51% free, 29MB/61MB, paused 656us total 22.413ms
,08-22 12:03:46.819  1827  1839 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-22 12:03:46.819  1827  1839 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-22 12:03:46.820  1827  1839 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-22 12:03:46.829  2044  2044 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-22 12:03:46.837  2044  2044 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-22 12:03:46.837  2044  2044 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-22 12:03:46.839  2044  2044 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-22 12:03:46.851  1046  1046 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-22 12:03:46.851  1046  1046 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-22 12:03:46.852  1046  1046 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-22 12:03:46.854  1046  1586 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-22 12:03:46.857  2044  2044 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-22 12:03:46.859  2044  2044 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ddf258b time:115398
08-22 12:03:46.862  6118  6118 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-22 12:03:46.862  6118  6118 W LG Account v2.2: No ProfileInfo entries
08-22 12:03:46.862  6118  6118 I LG Account v2.2: isEnabled: false
08-22 12:03:46.862  6118  6118 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-22 12:03:46.862  6118  6118 I Feature : [Lifetracker]Country: EU
08-22 12:03:46.862  6118  6118 I Feature : [Lifetracker]Operator: OPEN
08-22 12:03:46.862  6118  6118 I Feature : [Lifetracker]Ranking support: false
,08-22 12:03:46.863  6118  6118 I Feature : [Lifetracker]Comfort support: false
08-22 12:03:46.863  6118  6118 I Feature : [Lifetracker]Accessory: true
08-22 12:03:46.863  6118  6118 I Feature : [Lifetracker]Health device: true
08-22 12:03:46.863  6118  6118 I Feature : [Lifetracker]Extra Pedometer: false
08-22 12:03:46.863  6118  6118 I Feature : [Lifetracker]Blood glucose device: false
08-22 12:03:46.863  6118  6118 I Feature : [Lifetracker]Device Number: 3
08-22 12:03:46.863  6118  6118 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-22 12:03:46.876  1046  1134 I art     : Explicit concurrent mark sweep GC freed 7807(452KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 42MB/64MB, paused 2.265ms total 303.406ms
,08-22 12:03:46.893  1046  2061 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6140 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-22 12:03:46.895  1046  2061 I ActivityManager: Killing 4626:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-22 12:03:46.950  6049  6049 D AndroidRuntime: Shutting down VM
,08-22 12:03:46.966  1046  1111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 12:03:46.970  1046  1111 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-22 12:03:46.981  1046  1725 W libprocessgroup: failed to open /acct/uid_10014/pid_4626/cgroup.procs: No such file or directory
,08-22 12:03:46.991  2044  2044 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-22 12:03:46.995  6140  6140 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 12:03:46.995  6140  6140 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-22 12:03:46.995  6140  6140 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-22 12:03:46.995  6140  6140 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-22 12:03:46.996  6140  6140 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-22 12:03:46.996  6140  6140 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-22 12:03:47.056  2044  2044 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-22 12:03:47.071  6140  6140 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-22 12:03:47.078  6140  6140 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
,08-22 12:03:47.078  6140  6140 D HideNavigationAppsReceiver: replacing : false
08-22 12:03:47.080  6140  6140 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-22 12:03:47.082  6140  6140 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-22 12:03:47.082  6140  6140 D ButtonCombinationReceiver: replacing : false
,08-22 12:03:47.087  1046  1988 I ActivityManager: Killing 5592:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-22 12:03:47.109  2044  2867 I GBoardtInterface: onReloaded()
,08-22 12:03:47.112  2044  2044 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-22 12:03:47.206  1046  1061 W libprocessgroup: failed to open /acct/uid_10008/pid_5592/cgroup.procs: No such file or directory
,08-22 12:03:47.208  2742  2758 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-22 12:03:47.212  2742  2784 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-22 12:03:47.214  4341  6161 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-22 12:03:47.254  1046  1584 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6164 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-22 12:03:47.256  1046  1061 V SIM_STK : Menu title from STK is T-Mobile
,08-22 12:03:47.262   350   350 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.607ms total 11.610ms
08-22 12:03:47.269  1916  1916 D ActionManagerService: notifyUserLog: 1000001
08-22 12:03:47.270  2742  4199 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-22 12:03:47.270  2742  4199 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-22 12:03:47.275  1916  1916 D ActionManagerService: notifyUserLog: 1000001
,08-22 12:03:47.275   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 223us total 12.775ms
08-22 12:03:47.278  2742  4199 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-22 12:03:47.278  2742  4199 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-22 12:03:47.278  2742  2784 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-22 12:03:47.278  2742  4199 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-22 12:03:47.279  2742  4199 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-22 12:03:47.279  4341  6161 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-22 12:03:47.281  2044  2044 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-22 12:03:47.281  2044  2044 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-22 12:03:47.283  2044  2044 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-22 12:03:47.283  2044  2044 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-22 12:03:47.285   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.854ms
--------- beginning of crash
08-22 12:03:47.286  4341  6161 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-22 12:03:47.286  4341  6161 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4341
08-22 12:03:47.286  4341  6161 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at csx.d(PG:186)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at cun.g(PG:594)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at cuy.ub(PG:301)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at an,droid.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-22 12:03:47.286  4341  6161 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 12:03:47.286  2044  2044 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-22 12:03:47.286  2044  2044 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-22 12:03:47.293  4341  6161 I Process : Sending signal. PID: 4341 SIG: 9
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: Can't write: system_app_crash
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 12:03:47.295  1046  6182 E DropBoxManagerService: 	... 5 more
08-22 12:03:47.305  1046  1553 D WifiService: Client connection lost with reason: 4
,08-22 12:03:47.308  6164  6164 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
,08-22 12:03:47.350  1046  1061 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 4341) has died
08-22 12:03:47.350  1046  1061 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
08-22 12:03:47.351  1046  1061 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
,08-22 12:03:47.363  5889  5889 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-22 12:03:47.363  5889  5889 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-22 12:03:47.363  5889  5889 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-22 12:03:47.363  5889  5889 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-22 12:03:47.363  5889  5889 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-22 12:03:47.363  5889  5889 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true

```
