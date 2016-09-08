#### Test 83627337315fde5_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-08 14:31:27.580  5886  5886 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-08 14:31:27.657  5886  5886 D LgDataFeature: LgDataFeature() Constructor: none
09-08 14:31:27.657  5886  5886 D LgDataFeature: LgDataFeature() Constructor Done, null
09-08 14:31:27.703  5886  5886 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-08 14:31:27.725  5886  5886 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-08 14:31:27.726  5886  5886 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-08 14:31:27.753  5886  5886 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-08 14:31:27.754  5886  5886 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
09-08 14:31:27.772  1030  1578 I ActivityManager: Killing 5309:com.lge.clock/u0a10 (adj 15): empty #17
09-08 14:31:27.805  1030  1941 W libprocessgroup: failed to open /acct/uid_10010/pid_5309/cgroup.procs: No such file or directory
09-08 14:31:27.814  3381  3400 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-08 14:31:27.815  3381  3400 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3aa47a96 on behalf of 5886
09-08 14:31:27.818  4437  5928 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-08 14:31:27.857  1030  1941 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5929 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:31:27.872  5886  5886 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-08 14:31:27.913  5886  5886 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-08 14:31:28.142  5929  5929 D DocsApplication: Installing DEX configuration.
09-08 14:31:28.159  5929  5929 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-08 14:31:28.162  5929  5929 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{22164e55 com.google.android.apps.docs}
09-08 14:31:28.177  5929  5929 D TAG     : onCreate()
09-08 14:31:28.195  5929  5929 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-08 14:31:28.323  1030  1941 V SIM_STK : Menu title from STK is T-Mobile
09-08 14:31:28.359   304   304 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
09-08 14:31:28.359   304   304 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
09-08 14:31:28.359   304   304 I rmt_storage: wakelock acquired: 1, error no: 42
09-08 14:31:28.359   304   909 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
09-08 14:31:28.409  4437  5928 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 590 ms] updated apps [took 590 ms] 
09-08 14:31:28.423   304   909 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
09-08 14:31:28.423   304   909 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,09-08 14:31:28.423   304   909 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
09-08 14:31:28.423   304   909 I rmt_storage: 
09-08 14:31:28.425   304   304 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
09-08 14:31:28.426   895   906 E Diag_Lib: [IMS_FATAL]| 3347 | 906 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
09-08 14:31:28.790  5964  5964 D AndroidRuntime: 
09-08 14:31:28.790  5964  5964 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-08 14:31:28.806  5964  5964 D AndroidRuntime: CheckJNI is OFF
09-08 14:31:28.989  5964  5964 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-08 14:31:28.995  1030  1959 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 14:31:29.013  1924  3792 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-08 14:31:29.015  1030  1959 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-08 14:31:29.016  1030  1959 D ActivityManager: setTaskToReturnTo : TaskRecord{206e59fb #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-08 14:31:29.016  1030  1959 D ActivityManager: setTaskToReturnTo : TaskRecord{206e59fb #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-08 14:31:29.017  1030  1959 D WindowStateEx: AppWindowTokenEx init.. 
09-08 14:31:29.018   330   346 E GBMv2   : DFP En is all cleared set to be enabled
09-08 14:31:29.038  1030  1959 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5982 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-08 14:31:29.040  5964  5964 D AndroidRuntime: Shutting down VM
09-08 14:31:29.074  1924  3792 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-08 14:31:29.074  1924  3792 D SplitWindowPolicy: topRunningActivity=ActivityInfo{103484cf co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-08 14:31:29.075  1924  1939 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-08 14:31:29.075  1924  1939 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2dedce5c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-08 14:31:29.106  5982  5982 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-08 14:31:29.182  5982  5982 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-08 14:31:29.189  5982  5982 I LibraryLoader: Loading: webviewchromium
09-08 14:31:29.192  5982  5982 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1687-1691)
09-08 14:31:29.192  5982  5982 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:31:29.207  5982  5982 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e7c3037}
09-08 14:31:29.208  5982  5982 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:31:29.208  5982  5982 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 14:31:29.223  5982  5982 I BrowserStartupController: Initializing chromium process, renderers=0
09-08 14:31:29.224  5982  5982 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 14:31:29.234  5982  6006 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
09-08 14:31:29.238  5982  5982 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-08 14:31:29.239  5982  5982 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46780 len=2953
09-08 14:31:29.239  5982  5982 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:34 off:229536 len:643667
09-08 14:31:29.254   312  1377 V AudioPolicyService: registerClient() client 0xb558a420, uid 10118
,09-08 14:31:29.273  1030  1112 D BluetoothManagerService: Message: 20
09-08 14:31:29.273  1030  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bceead:true
,09-08 14:31:29.275  5982  5982 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:31:29.275  5982  5982 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:31:29.275  5982  5982 I Adreno-EGL: Build Date: 12/12/14 금
09-08 14:31:29.275  5982  5982 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 14:31:29.275  5982  5982 I Adreno-EGL: Remote Branch: 
09-08 14:31:29.275  5982  5982 I Adreno-EGL: Local Patches: 
09-08 14:31:29.275  5982  5982 I Adreno-EGL: Reconstruct Branch: 
09-08 14:31:29.352  5982  6016 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-08 14:31:29.360  5982  5982 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-08 14:31:29.379  5982  5982 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 14:31:29.384  5982  5982 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-08 14:31:29.387  5982  5982 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-08 14:31:29.391  5982  5982 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-08 14:31:29.391  5982  5982 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-08 14:31:29.407  5982  5982 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-08 14:31:29.410  1799  4608 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-08 14:31:29.414  5982  5982 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 14:31:29.414  5982  5982 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 14:31:29.447  5982  6029 D OpenGLRenderer: Render dirty regions requested: true
09-08 14:31:29.447  5982  6029 I OpenGLRenderer: Initialized EGL, version 1.4
09-08 14:31:29.453  5982  6029 D OpenGLRenderer: Enabling debug mode 0
09-08 14:31:29.462  1799  4608 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,09-08 14:31:29.463  5982  5982 D Atlas   : Validating map...
,09-08 14:31:29.469  1030  1637 D SplitWindow: check instance of lgWin Window{169208bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-08 14:31:29.505  5982  6026 D LgDataFeature: LgDataFeature() Constructor: none
09-08 14:31:29.505  5982  6026 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 14:31:29.529  1799  4608 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,09-08 14:31:29.539  5929  5929 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 14:31:29.540  5929  5929 D LgDataFeature: LgDataFeature() Constructor Done, null
09-08 14:31:29.592  1030  1113 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +519ms (total +574ms)
,09-08 14:31:29.593  1030  1113 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{188fa18 u0 com.test.thalitest/.MainActivity t6} time:102092
09-08 14:31:29.598  5982  5982 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@18204072 time:102097
09-08 14:31:29.691  5982  5982 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 14:31:29.725  5982  5982 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-08 14:31:29.725  5982  5982 I chromium: 
,09-08 14:31:29.741  5982  6026 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-08 14:31:29.741  5982  6026 I chromium: 
,09-08 14:31:29.746  1030  1578 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6043 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
09-08 14:31:29.748  1030  1578 I ActivityManager: Killing 4894:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-08 14:31:29.792  1030  1941 W libprocessgroup: failed to open /acct/uid_10085/pid_4894/cgroup.procs: No such file or directory
,09-08 14:31:29.796  5929  5929 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
09-08 14:31:29.818  6043  6043 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-08 14:31:29.832  6043  6043 I LockScreenSettings: New app installed broadcast received ..
09-08 14:31:29.834  6043  6043 I LockScreenSettings: Number of installed packages  1
09-08 14:31:29.864  5982  6064 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435144192
,09-08 14:31:29.869  1030  1995 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6065 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-08 14:31:29.880  5982  6064 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 14:31:29.880  5982  6064 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 14:31:29.880  5982  6064 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 14:31:29.880  5982  6064 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 14:31:29.880  5982  6064 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-08 14:31:29.880  5982  6064 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3aa47a96 added. We now have 1 listener(s)
,09-08 14:31:29.885  1030  1750 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:29.887  5982  6064 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-08 14:31:29.890  5982  6064 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 14:31:29.891  5982  6064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:29.891  5982  6064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 14:31:29.899  5982  6064 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@292fbed added. We now have 1 listener(s)
09-08 14:31:29.899  5982  6064 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:29.903  1030  1451 D WifiService: New client listening to asynchronous messages
,09-08 14:31:29.906  5982  6064 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:29.906  5982  6064 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 14:31:29.906  5982  6064 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 14:31:29.906  5982  6064 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 14:31:29.906  5982  6064 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-08 14:31:29.908  5982  6064 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:29.909  1030  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:29.909  5982  6064 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-08 14:31:29.915  5982  6064 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-08 14:31:29.915  5982  6064 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:29.915  5982  6064 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:29.915  5982  6064 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:29.915  5982  6064 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:29.915  5982  6064 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:29.915  5982  6064 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:29.915  5982  6064 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:29.915  5982  6064 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:29.916  5982  6064 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 14:31:29.916  5982  6064 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:29.917  5982  6064 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 14:31:29.927  6065  6065 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:31:29.948  5982  5982 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 14:31:30.289   330   348 E GBMv2   : DFP En is all cleared set to be enabled
,09-08 14:31:30.289   330   348 E GBMv2   : Set value is all cleared set the max
09-08 14:31:30.289   330   348 I GBMv2   : DFP Enabled. Ignore VFP set
,09-08 14:31:30.367  1030  1749 V SIM_STK : Menu title from STK is T-Mobile
,09-08 14:31:30.442  1030  1994 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6102 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 14:31:30.467   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 456us total 24.935ms
,09-08 14:31:30.487   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 397us total 19.114ms
,09-08 14:31:30.507   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 414us total 19.857ms
,09-08 14:31:30.536  6102  6102 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-08 14:31:30.536  6102  6102 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,09-08 14:31:30.539  5024  5024 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
09-08 14:31:30.552  1030  1995 I ActivityManager: Killing 5393:com.google.android.gm/u0a64 (adj 15): empty #17
,09-08 14:31:30.596  1030  1578 I art     : Explicit concurrent mark sweep GC freed 32170(1565KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.467ms total 84.763ms
,09-08 14:31:30.643  1030  1905 W libprocessgroup: failed to open /acct/uid_10064/pid_5393/cgroup.procs: No such file or directory
,09-08 14:31:30.694  5982  6084 W jxcore-log: Initializing JXcore engine
09-08 14:31:30.694  5982  6084 W jxcore-log: JXcore engine is ready
,09-08 14:31:30.723  6084  6084 W Thread-666: type=1400 audit(0.0:154): avc: denied { ioctl } for path="socket:[6125]" dev="sockfs" ino=6125 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-08 14:31:30.723  6084  6084 W Thread-666: type=1400 audit(0.0:155): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-08 14:31:30.723  6084  6084 W Thread-666: type=1400 audit(0.0:156): avc: denied { ioctl } for path="socket:[7536]" dev="sockfs" ino=7536 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-08 14:31:30.723  6084  6084 W Thread-666: type=1400 audit(0.0:157): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-08 14:31:30.723  6084  6084 W Thread-666: type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[29364]" dev="sockfs" ino=29364 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-08 14:31:30.767  5982  6084 W jxcore-log: Starting JXcore engine
,09-08 14:31:30.849  5982  6084 W jxcore-log: Platform android
09-08 14:31:30.849  5982  6084 W jxcore-log: 
09-08 14:31:30.849  5982  6084 W jxcore-log: Process ARCH arm
09-08 14:31:30.849  5982  6084 W jxcore-log: 
,09-08 14:31:31.048  5982  6084 I jxcore-log: JXcore Cordova bridge is ready!
09-08 14:31:31.048  5982  6084 I jxcore-log: 
09-08 14:31:31.049  5982  6084 W jxcore-log: JXcore engine is started
,09-08 14:31:31.057  5982  6064 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-08 14:31:31.060  5982  5982 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 14:31:31.912  2763  2763 I MusicWidget: mDelayedStopHandler : unbind
,09-08 14:31:31.941  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-08 14:31:31.941  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-08 14:31:31.942  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,09-08 14:31:32.055  2127  2127 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-08 14:31:32.055  2127  2127 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-08 14:31:32.056  2127  2127 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,09-08 14:31:32.059  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-08 14:31:32.059  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-08 14:31:32.060  1030  1045 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2abbb97dcom.lge.music.MediaPlaybackService$5@18204072
09-08 14:31:32.062  2127  2127 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-08 14:31:32.062  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 14:31:32.068  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-08 14:31:32.069  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 14:31:32.071  2127  2127 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3bd998d3
09-08 14:31:32.072  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 14:31:32.074  2127  2127 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-08 14:31:32.074  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 14:31:32.075  2127  2127 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-08 14:31:32.076  2127  2127 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-08 14:31:32.077  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 14:31:32.078  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-08 14:31:32.079  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-08 14:31:32.080  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 14:31:32.082  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 14:31:32.084  2127  2127 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-08 14:31:32.086  2127  2127 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-08 14:31:32.086  2127  2127 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-08 14:31:32.086  2127  2127 V MediaPlayer[Native]: reset
09-08 14:31:32.098  2127  2127 V MediaPlayer[Native]: setListener
09-08 14:31:32.098  2127  2127 V MediaPlayer[Native]: disconnect
09-08 14:31:32.098  2127  2127 V MediaPlayer[Native]: destructor
09-08 14:31:32.098   312   312 V AudioFlinger: releasing 17 from 2127 for -1
09-08 14:31:32.098   312   312 V AudioFlinger:  decremented refcount to 0
09-08 14:31:32.098   312   312 V AudioFlinger: purging stale effects
,09-08 14:31:32.098  2127  2127 V MediaPlayer[Native]: disconnect
09-08 14:31:32.100  2127  2127 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-08 14:31:32.102  2127  2127 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-08 14:31:32.102  2127  2127 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-08 14:31:32.104  2127  2127 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-08 14:31:32.104  2127  2127 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-08 14:31:32.104  2127  2127 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-08 14:31:32.104  2127  2127 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 596270275
09-08 14:31:32.104  2127  2127 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 596270275
09-08 14:31:32.114  2127  2127 I SmartShareClient: [SmartShareManagerClient] terminate service: 2127/MediaPlaybackService/112884433
09-08 14:31:32.118  2127  2127 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
,09-08 14:31:32.118  2127  2127 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@bff1940
09-08 14:31:32.120  2127  2127 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-08 14:31:32.121  2127  2127 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-08 14:31:32.122  2127  2127 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-08 14:31:32.122  2127  2127 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-08 14:31:32.125  2127  2127 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29998
09-08 14:31:32.125  1030  1905 I ActivityManager: Killing 5148:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-08 14:31:32.147  5127  5127 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,09-08 14:31:32.148  5127  5127 W System.err: android.os.DeadObjectException
09-08 14:31:32.148  5127  5127 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 14:31:32.148  5127  5127 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 14:31:32.148  5127  5127 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-08 14:31:32.148  5127  5127 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-08 14:31:32.148  5127  5127 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 14:31:32.148  5127  5127 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 14:31:32.148  5127  5127 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:31:32.148  5127  5127 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:31:32.148  5127  5127 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:31:32.148  5127  5127 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 14:31:32.148  5127  5127 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:32.148  5127  5127 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:32.148  5127  5127 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 14:31:32.148  5127  5127 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 14:31:32.149  5127  5127 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-08 14:31:32.149  5127  5127 W System.err: android.os.DeadObjectException
09-08 14:31:32.151  5127  5127 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 14:31:32.151  5127  5127 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 14:31:32.151  5127  5127 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-08 14:31:32.151  5127  5127 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-08 14:31:32.151  5127  5127 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 14:31:32.151  5127  5127 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 14:31:32.151  5127  5127 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:31:32.152  5127  5127 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:31:32.152  5127  5127 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:31:32.152  5127  5127 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 14:31:32.152  5127  5127 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:32.152  5127  5127 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:32.152  5127  5127 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 14:31:32.152  5127  5127 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 14:31:32.153  5127  5127 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-08 14:31:32.154  5127  5127 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-08 14:31:32.442  1030  1923 W libprocessgroup: failed to open /acct/uid_1000/pid_5148/cgroup.procs: No such file or directory
09-08 14:31:32.442  1030  1923 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-08 14:31:32.451  5127  5127 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-08 14:31:32.451  5127  5127 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-08 14:31:32.497  1030  1750 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6161 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 14:31:32.499  5127  5127 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-08 14:31:32.578  6161  6161 D UEI.SmartControl: Quickset Services start...
09-08 14:31:32.580  6161  6161 I UEI.SmartControl: Manufacture = LGE
09-08 14:31:32.581  6161  6161 D UEI.SmartControl: Id = LGNevo
,09-08 14:31:32.583  6161  6161 D UEI.SmartControl: File observer start...
09-08 14:31:32.584  6161  6161 E UEI.SmartControl: IR Port is disabled: false
09-08 14:31:32.584  6161  6161 D UEI.SmartControl: Starting file observer...
09-08 14:31:32.584  6161  6161 D UEI.SmartControl: Extracting JNI libs...
09-08 14:31:32.584  6161  6161 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-08 14:31:32.678  6161  6161 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-08 14:31:32.678  6161  6161 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-08 14:31:32.679  6161  6161 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-08 14:31:32.714  6161  6161 I UEI.SmartControl: --- Selecting new region: 6,
,09-08 14:31:32.717  6161  6161 I UEI.SmartControl: Model = LG-D855
09-08 14:31:32.719  6161  6161 D UEI.SmartControl: QS Service created
09-08 14:31:32.735  6161  6161 I UEI.SmartControl: Service initServices...
,09-08 14:31:32.739  6161  6161 D UEI.SmartControl: QS start get config
09-08 14:31:32.797  6161  6161 D UEI.SmartControl: Loading JNI Libs...
,09-08 14:31:33.034  6161  6161 I UEI.SmartControl: Supports setup maps: true
09-08 14:31:33.036  6161  6161 D UEI.SmartControl: QS start statue = true Error code = 0
09-08 14:31:33.036  6161  6161 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-08 14:31:33.036  6161  6161 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-08 14:31:33.037  6161  6161 I UEI.SmartControl: ### init IR Blaster...
,09-08 14:31:33.041  6161  6161 D serial_port: Configuring serial port
09-08 14:31:33.045  6161  6161 E UEI.SmartControl: UEIBLaster setting for 616
09-08 14:31:33.045  6161  6161 I UEI.SmartControl: Setting serial record hearder size = 2
09-08 14:31:33.045  6161  6161 I UEI.SmartControl: configuring settings for MAXQ616
09-08 14:31:33.046  6161  6161 I UEI.SmartControl: Get version...
09-08 14:31:33.062  6161  6186 D UEI.SmartControl: serial port data available: 21
,09-08 14:31:33.092  6161  6161 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-08 14:31:33.092  6161  6161 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-08 14:31:33.093  6161  6161 I UEI.SmartControl: QS saving settings...
09-08 14:31:33.094  6161  6161 D UEI.SmartControl: IR Blaster version: 25672567
09-08 14:31:33.110  6161  6186 D UEI.SmartControl: serial port data available: 4
,09-08 14:31:33.146  6161  6189 I UEI.SmartControl: Device manager: loading config....
09-08 14:31:33.146  6161  6189 D UEI.SmartControl: ----------- loading internal config...
,09-08 14:31:33.148  6161  6161 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-08 14:31:33.150  6161  6161 E UEI.SmartControl: Services init done
09-08 14:31:33.150  6161  6161 D UEI.SmartControl: QS Service init finished
09-08 14:31:33.154  6161  6161 D UEI.SmartControl: QS Service version name: 2.1.91
09-08 14:31:33.154  6161  6161 D UEI.SmartControl: QS Service version code: 201091
09-08 14:31:33.155  6161  6161 D UEI.SmartControl: Service requested: Control
09-08 14:31:33.163  6161  6189 E UEI.SmartControl: Loading SETTINGS...
,09-08 14:31:33.166  6161  6161 D UEI.SmartControl: Request IControl service: devices are loaded...
09-08 14:31:33.173  1030  1045 I ActivityManager: Killing 5127:com.lge.qremote/u0a112 (adj 15): empty #17
09-08 14:31:33.179  6161  6189 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-08 14:31:33.204  6161  6188 I UEI.SmartControl: Notify AllClients services are ready: 0
09-08 14:31:33.204  6161  6188 D UEI.SmartControl: -----service ready thread exits
,09-08 14:31:33.243  6161  6161 D UEI.SmartControl: Internal service binding...
,09-08 14:31:33.244  1030  1959 W libprocessgroup: failed to open /acct/uid_10112/pid_5127/cgroup.procs: No such file or directory
,09-08 14:31:33.649  5929  5929 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
09-08 14:31:33.651  1030  1923 I ActivityManager: Killing 5432:com.google.android.talk/u0a72 (adj 15): empty #17
,09-08 14:31:33.752  1030  1941 W libprocessgroup: failed to open /acct/uid_10072/pid_5432/cgroup.procs: No such file or directory
,09-08 14:31:34.607  5929  6038 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-08 14:31:35.411  1030  1923 I ActivityManager: Killing 5071:com.android.calendar/u0a13 (adj 15): empty #17
,09-08 14:31:35.521  1030  1941 W libprocessgroup: failed to open /acct/uid_10013/pid_5071/cgroup.procs: No such file or directory
,09-08 14:31:38.134  6161  6187 D serial_port: close(fd = 25)
,09-08 14:31:38.140  6161  6187 I UEI.SmartControl: Serial port is closed.
,09-08 14:31:38.147  6161  6190 D UEI.SmartControl: Internal timer expired: 1
09-08 14:31:38.148  6161  6190 D UEI.SmartControl: unbind internal service
,09-08 14:31:38.160  6161  6161 D UEI.SmartControl: Service.onUnbind: IControl
,09-08 14:31:38.163  6161  6161 D UEI.SmartControl: Service.onDestroy
,09-08 14:31:38.164  6161  6161 D UEI.SmartControl: Lock is in USE false
,09-08 14:31:38.164  6161  6161 D UEI.SmartControl: unbind internal service
09-08 14:31:38.164  6161  6161 I UEI.SmartControl: Serial port is closed.
09-08 14:31:38.164  6161  6161 I UEI.SmartControl: Serial port is closed.
09-08 14:31:38.164  6161  6161 D UEI.SmartControl: Blaster closed
09-08 14:31:38.164  6161  6161 D UEI.SmartControl: Shut down QS...
09-08 14:31:38.165  6161  6161 D UEI.SmartControl: Stopping QS lib
,09-08 14:31:38.165  6161  6161 D UEI.SmartControl: QS lib stop result = true,
09-08 14:31:38.165  6161  6161 D UEI.SmartControl: Stopped QS lib
,09-08 14:31:38.167  6161  6161 D UEI.SmartControl: Stopped file observer...
,09-08 14:31:38.167  6161  6161 D UEI.SmartControl: QS shutdown complete
,09-08 14:31:40.877  1030  1104 I ActivityManager: Waited long enough for: ServiceRecord{2956e84b u0 com.google.android.gms/.wearable.service.WearableService}
,09-08 14:31:41.179  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 14:31:41.179  5982  6084 I jxcore-log: 
,09-08 14:31:41.182  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 14:31:41.182  5982  6084 I jxcore-log: 
09-08 14:31:41.187  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:41.187  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:41.187  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:41.187  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:41.187  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:41.187  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:41.187  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:41.187  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:41.189  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:41.192  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 14:31:41.192  5982  6084 I jxcore-log: 
09-08 14:31:41.193  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 14:31:41.193  5982  6084 I jxcore-log: 
,09-08 14:31:41.701  5982  6084 I jxcore-log: Unit Test app is loaded
09-08 14:31:41.701  5982  6084 I jxcore-log: 
09-08 14:31:41.705  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:31:41.705  5982  6084 I jxcore-log: 
,09-08 14:31:41.711  1030  1941 D WifiServiceImplEx: setWifiEnabled: true pid=5982, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 14:31:41.712  1030  1941 D WifiService: setWifiEnabled: true pid=5982, uid=10118
09-08 14:31:41.712  1030  1941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-08 14:31:41.727  1030  1886 D WifiServiceImplEx: disconnect pid=5982, uid=10118, packageName=com.test.thalitest
09-08 14:31:41.727  1030  1994 D WifiServiceImplEx: reconnect pid=5982, uid=10118, packageName=com.test.thalitest
,09-08 14:31:41.730  5982  6084 D executeNativeTests: Running unit tests
09-08 14:31:41.731  5982  6084 D BluetoothAdapter: enable(): BT is already enabled..!
09-08 14:31:41.732  1030  1578 D WifiServiceImplEx: setWifiEnabled: true pid=5982, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 14:31:41.732  1030  1578 D WifiService: setWifiEnabled: true pid=5982, uid=10118
09-08 14:31:41.732  1030  1578 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-08 14:31:41.732  1030  1408 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-08 14:31:41.732  1030  1408 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-08 14:31:41.733  1030  1451 D WifiController: Mismatch in the state 1
09-08 14:31:41.734  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:31:41.735  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:31:41.735  1030  1030 D Ulp_jni : JNI:system_update. Event-4
09-08 14:31:41.736  5982  5982 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-08 14:31:41.736  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-08 14:31:41.736  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 14:31:41.736  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-08 14:31:41.736  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 14:31:41.736  1030  1408 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-08 14:31:41.736  1030  1408 E WifiHW  : unknown target_country: EU , set to default
09-08 14:31:41.736  1030  1408 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-08 14:31:41.736  1030  1408 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-08 14:31:41.736  1030  1408 I WifiUtil: gEnableBmps=1
09-08 14:31:41.945   308   888 D SoftapController: Softap fwReload - Ok
,09-08 14:31:41.957   308   888 D CommandListener: Setting iface cfg
09-08 14:31:41.958   308   888 D CommandListener: Trying to bring down wlan0
,09-08 14:31:41.962   308   888 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:31:41.970  1030  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-08 14:31:41.974   308  6206 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-08 14:31:41.979  1030  1112 D Tethering: InitialState.processMessage what=4
09-08 14:31:41.982  1030  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-08 14:31:41.984  1030  1408 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-08 14:31:41.999  1030  1408 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 14:31:41.999  1030  1408 E WifiStateMachine: useWiFiOffloading() : false
09-08 14:31:41.999  1030  1408 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-08 14:31:41.993  6211  6211 W wpa_supplicant: type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:41.993  6211  6211 W wpa_supplicant: type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:42.017  1030  1104 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6213 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-08 14:31:42.018  1030  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-08 14:31:42.024  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:42.027  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-08 14:31:42.027  1030  1408 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-08 14:31:42.027  1030  1408 D WifiMonitor: connecting to supplicant
09-08 14:31:42.030  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-08 14:31:42.038  6211  6211 I wpa_supplicant: Successfully initialized wpa_supplicant
09-08 14:31:42.042  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:42.080  6211  6211 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 14:31:42.081  6211  6211 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-08 14:31:42.104  6213  6213 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:31:42.104  6213  6213 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-08 14:31:42.104  6213  6213 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 14:31:42.105  6213  6213 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-08 14:31:42.106  6213  6213 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 14:31:42.106  6213  6213 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-08 14:31:42.131  2127  2127 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19991
,09-08 14:31:42.162  6211  6211 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 14:31:42.240  6211  6211 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-08 14:31:42.254  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-08 14:31:42.254  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-08 14:31:42.254  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:31:42.254  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:31:42.255  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:31:42.258  6211  6211 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-08 14:31:42.258  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-08 14:31:42.259  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-08 14:31:42.259  6211  6211 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-08 14:31:42.260  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-08 14:31:42.260  1030  1408 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-08 14:31:42.261  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_DISCONNECT 0 0
09-08 14:31:42.261  1030  1408 E WifiStateMachine:  DefaultState CMD_DISCONNECT 0 0
09-08 14:31:42.261  1030  6236 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-08 14:31:42.262  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_RECONNECT 0 0
09-08 14:31:42.262  1030  6236 D WifiMonitor: Dropping event because (p2p0) is stopped
09-08 14:31:42.262  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-08 14:31:42.262  1030  1408 E WifiStateMachine:  DefaultState CMD_RECONNECT 0 0
09-08 14:31:42.263  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-08 14:31:42.263  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-08 14:31:42.263  1030  6236 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-08 14:31:42.263  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:42.263  1030  6236 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-08 14:31:42.264  1030  1408 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:42.264  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:42.265  1030  1408 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:42.265  1030  1408 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-08 14:31:42.266  1030  1408 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-08 14:31:42.267  1030  1408 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-08 14:31:42.268  1030  1408 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-08 14:31:42.268  1030  1408 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-08 14:31:42.269  1030  1408 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 14:31:42.269  1030  1408 E WifiStateMachine: useWiFiOffloading() : false
09-08 14:31:42.269  1030  1408 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 14:31:42.269  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:42.269  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:31:42.272  1924  1924 D WfdService: Waiting for WifiP2p enabling
09-08 14:31:42.273  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-08 14:31:42.273  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:42.276  1030  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-08 14:31:42.276  1030  1408 D WifiNative-wlan0: doBoolean: SET update_config 1
09-08 14:31:42.278  1030  1408 D WifiNative-wlan0: SET update_config 1: returned true
09-08 14:31:42.278  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:31:42.278  1030  1408 D WifiConfigStore: Loading config and enabling all networks 
09-08 14:31:42.278  1030  1408 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-08 14:31:42.279  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 14:31:42.279  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:31:42.279  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:31:42.279  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:31:42.279  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:42.279  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:42.279  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:42.279  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:42.279  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:42.279  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:42.279  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:42.279  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:42.279  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 14:31:42.280  1030  1408 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-08 14:31:42.281  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:31:42.281  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:31:42.285  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:31:42.285  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:31:42.286  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:31:42.286  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:31:42.286  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:31:42.287  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:31:42.287  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-08 14:31:42.287  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:31:42.287  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:31:42.287  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:31:42.287  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:31:42.297  1030  1408 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-08 14:31:42.306  1030  1408 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-08 14:31:42.307  1030  1408 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 14:31:42.338  1030  1995 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6239 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-08 14:31:42.339  1030  1408 D WifiStateMachine: enableVerboseLogging : level 2
09-08 14:31:42.340  1030  1408 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-08 14:31:42.340  1030  1408 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-08 14:31:42.340  1030  1408 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-08 14:31:42.341  1030  1995 I ActivityManager: Killing 4789:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-08 14:31:42.341  1030  1408 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-08 14:31:42.341  1030  1408 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-08 14:31:42.341  1030  1408 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-08 14:31:42.341  1030  1408 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-08 14:31:42.342  1030  1408 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-08 14:31:42.342  1030  1408 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-08 14:31:42.342  1030  1408 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-08 14:31:42.343  1030  1408 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-08 14:31:42.343  1030  1408 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-08 14:31:42.343  1030  1408 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-08 14:31:42.344  1030  1408 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-08 14:31:42.393  1030  1941 W libprocessgroup: failed to open /acct/uid_10014/pid_4789/cgroup.procs: No such file or directory
,09-08 14:31:42.393  1030  1408 D WifiStateMachine: Setting OUI to DA-A1-19,
09-08 14:31:42.393  1030  1408 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-08 14:31:42.395  1030  1408 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
,09-08 14:31:42.395  1030  1408 D WifiNative-HAL: Setting external_sim to 1,
09-08 14:31:42.395  1030  1408 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-08 14:31:42.396  1030  1408 D WifiNative-wlan0: SET external_sim 1: returned true
09-08 14:31:42.396  1030  1408 I WifiNative-HAL: startHal
,09-08 14:31:42.396  1030  1408 E wifi    : getStaticLongField sWifiHalHandle 0x9886e8dc
09-08 14:31:42.397  1030  1408 E WifiHAL : Could not connect handle
09-08 14:31:42.397  1030  1408 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x30229e
09-08 14:31:42.397  1924  1924 D WfdsService: Supplicant Connection state is changed : true
09-08 14:31:42.397  1030  1408 I WifiNative-HAL: Could not start hal
09-08 14:31:42.398  1924  2250 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-08 14:31:42.398  1030  1408 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:31:42.398  1030  1408 I WifiNative-HAL: startHal
09-08 14:31:42.398  1924  2250 D WfdsService: Set the WFDS Monitor: true
09-08 14:31:42.398  1030  1408 E wifi    : getStaticLongField sWifiHalHandle 0x9886e85c
09-08 14:31:42.398  1030  1408 E WifiHAL : Could not connect handle
09-08 14:31:42.398  1030  1408 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x20228a
09-08 14:31:42.398  1030  1408 I WifiNative-HAL: Could not start hal
09-08 14:31:42.398  1030  1408 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-08 14:31:42.399  1924  2250 D WfdsMonitor: WfdsMonitorThread create
09-08 14:31:42.399  1924  2250 D WfdsMonitor: WFDS Monitor is created and started
09-08 14:31:42.399  1924  2250 D WfdsService: WiFi: Supplicant connection re-established
09-08 14:31:42.400  1030  1408 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-08 14:31:42.400  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-08 14:31:42.400  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-08 14:31:42.401  1924  6256 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-08 14:31:42.401  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-08 14:31:42.402  1924  6256 E CtrlSupplicant: Succeed to open control connection
09-08 14:31:42.402  1924  6256 E CtrlSupplicant: Succeed to open monitor connection
09-08 14:31:42.402  1924  6256 D WfdsMonitor: Supplicant connection established
09-08 14:31:42.404  1924  2250 D WfdsService: Connected to the supplicant for wfds
09-08 14:31:42.407  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 14:31:42.407  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 14:31:42.408  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 14:31:42.408  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-08 14:31:42.408  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-08 14:31:42.408  1030  1030 D WifiHS20: hidePasspointNotification off =false
,09-08 14:31:42.410  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:42.410  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:42.410  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:42.410  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-08 14:31:42.410  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 14:31:42.411  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 14:31:42.411  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 14:31:42.411  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 14:31:42.411  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 14:31:42.412  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 14:31:42.412  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-08 14:31:42.412  6211  6211 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-08 14:31:42.412  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-08 14:31:42.412  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 14:31:42.413  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 14:31:42.413  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 14:31:42.414  1030  1408 E WifiNative: : [114,900,432 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-08 14:31:42.414  1030  1408 D WifiNative-wlan0: doBoolean: RECONNECT
09-08 14:31:42.415  1030  1408 D WifiNative-wlan0: RECONNECT: returned true
09-08 14:31:42.415  1030  1408 D WifiNative-wlan0: doString: [STATUS]
09-08 14:31:42.416  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-08 14:31:42.416  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 14:31:42.416  1030  1408 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-08 14:31:42.416  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-08 14:31:42.416  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-08 14:31:42.417  1030  1408 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-08 14:31:42.417  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:42.417  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 14:31:42.417  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:42.418  1030  1408 D WifiNative-wlan0: SET ps 1: returned true
09-08 14:31:42.418  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:42.418  1030  1370 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.419  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 14:31:42.419  1030  1538 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.419  1030  1538 I WifiNative-HAL: startHal
09-08 14:31:42.420  1030  1538 E wifi    : getStaticLongField sWifiHalHandle 0x94d6899c
09-08 14:31:42.420  1030  1538 E WifiHAL : Could not connect handle
09-08 14:31:42.420  1030  1538 D wifi    : halHandle = 0x0, mVM = 0x,b487c280, mCls = 0x20218e
09-08 14:31:42.420  1030  1538 I WifiNative-HAL: Could not start hal
09-08 14:31:42.420  1030  1030 D RttService: SCAN_AVAILABLE : 3
09-08 14:31:42.420  1030  1538 E WifiScanningService: could not start HAL
09-08 14:31:42.420  1030  1539 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.420  1030  1408 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-08 14:31:42.421  1030  1408 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-08 14:31:42.421  1030  1408 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-08 14:31:42.421   308   888 D CommandListener: Setting iface cfg
09-08 14:31:42.422   308   888 D CommandListener: Trying to bring up p2p0
09-08 14:31:42.422  1030  1370 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 14:31:42.422  1030  1408 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-08 14:31:42.422  1030  1370 D LGWifiP2pService: P2pEnablingState
09-08 14:31:42.422  1030  1370 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.422  1030  1370 D LGWifiP2pService: P2p socket connection successful
09-08 14:31:42.422  1030  1370 D LGWifiP2pService: P2pEnabledState
09-08 14:31:42.422  1030  1408 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-08 14:31:42.423  1030  1408 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-08 14:31:42.423  1030  1370 D LGWifiP2pService: sending p2p connection changed broadcast
09-08 14:31:42.423  1030  1408 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-08 14:31:42.424  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-08 14:31:42.424  1030  1408 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-08 14:31:42.425  1030  1408 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-08 14:31:42.425  1030  1408 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-08 14:31:42.425  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-08 14:31:42.425  1924  1924 D WfdsService: WifiP2pState is changed : true
09-08 14:31:42.426  1924  2250 D WfdsService: Receive the WFDS_ENABLE Method
09-08 14:31:42.426  1030  1408 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-08 14:31:42.426  1924  2250 D WfdsService: Set the WFDS Monitor: true
09-08 14:31:42.426  1924  2250 D WfdsService: Connected to the supplicant for wfds
09-08 14:31:42.426  1030  1408 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-08 14:31:42.426  1924  2250 D WfdsJNI : doCommand: WFDS_SET TRUE
09-08 14:31:42.426  6211  6211 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-08 14:31:42.426  6211  6211 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-08 14:31:42.427  1030  1408 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-08 14:31:42.427  1030  1408 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-08 14:31:42.428  1030  1408 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-08 14:31:42.428  1030  1408 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-08 14:31:42.428  6211  6211 E wpa_supplicant: disconnect_rssi_lvl: -100
09-08 14:31:42.429  1924  2250 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
09-08 14:31:42.429  6211  6211 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
09-08 14:31:42.431  1924  2250 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
09-08 14:31:42.431  1924  2250 D WfdsService: selectPreferredScanChannel [36]
09-08 14:31:42.431  1924  2250 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-08 14:31:42.433  1030  1370 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-08 14:31:42.433  1030  1408 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
09-08 14:31:42.433  1030  1408 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
09-08 14:31:42.434  1030  1408 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
09-08 14:31:42.434  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-08 14:31:42.434  1030  1370 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-08 14:31:42.434  1030  1370 D WifiNative-p2p0: doBoolean: SET device_name G3
09-08 14:31:42.435  1030  1370 D WifiNative-p2p0: SET device_name G3: returned true
09-08 14:31:42.435  1030  1370 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-08 14:31:42.435  1030  1370 D LGWifiP2pService: before postfix = G3
09-08 14:31:42.435  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 14:31:42.435  1030  1370 D WifiServerServiceExt: postfix byte check : 2
09-08 14:31:42.435  1030  1370 D LGWifiP2pService: after postfix = G3
09-08 14:31:42.436  1030  1370 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-08 14:31:42.436  6211  6211 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:42.436  6211  6211 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 14:31:42.436  6211  6211 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.437  1030  1408 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-08 14:31:42.437  6211  6211 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.437  1030  1408 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-08 14:31:42.437  1924  1924 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-08 14:31:42.438  1030  1408 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-08 14:31:42.438  1924  6256 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:42.438  1924  6256 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:42.438  1030  1408 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-08 14:31:42.438  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-08 14:31:42.438  1924  1924 D WfdsService: isConnected: false
09-08 14:31:42.438  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-08 14:31:42.438  6211  6211 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:31:42.439  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 14:31:42.439  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:42.439  1030  6236 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:42.439  1030  6236 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:42.439  1030  6236 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:42.439  1030  6236 E WifiMonitor: WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.439  1030  6236 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.439  1030  6236 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.439  1030  6236 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:42.439  1030  6236 E WifiMonitor: WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.439  1030  6236 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.439  1030  6236 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.439  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-08 14:31:42.439  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:31:42.440  1030  6236 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:31:42.440  1030  6236 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:31:42.441  1030  1408 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-08 14:31:42.441  1030  1408 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-08 14:31:42.442  1030  1408 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-08 14:31:42.442  1030  1408 D WifiNative-wlan0: doBoolean: SCAN
09-08 14:31:42.443  1030  1408 D WifiNative-wlan0: SCAN: returned false
09-08 14:31:42.444  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=114930  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 14:31:42.445  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=114932  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 14:31:42.446  1030  1408 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:31:42.446  1030  1408 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:31:42.447  1030  1370 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-08 14:31:42.447  1030  1370 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-08 14:31:42.447  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:42.447  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:42.447  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:31:42.448  1030  1408 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:31:42.448  1030  1370 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-08 14:31:42.448  1030  1370 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-08 14:31:42.448  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:42.448  1030  1408 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:31:42.448  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:42.449  1030  1370 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-08 14:31:42.449  1030  1408 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:31:42.449  1030  1370 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-08 14:31:42.450  1030  1370 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-08 14:31:42.450  1030  1370 D WifiNative-HAL: p2pGetDeviceAddress
09-08 14:31:42.450  1030  1451 D WifiService: New client listening to asynchronous messages
09-08 14:31:42.450  1030  1370 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-08 14:31:42.451  1030  1370 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-08 14:31:42.451  1030  1370 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-08 14:31:42.452  1030  1370 D WifiNative-p2p0: P2P_FLUSH: returned true
09-08 14:31:42.452  1030  1370 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-08 14:31:42.452  1030  1370 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-08 14:31:42.453  1030  1370 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,09-08 14:31:42.453  1030  1370 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-08 14:31:42.453  1030  1370 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-08 14:31:42.454  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:42.455  1924  1924 I WfdStateTracker: handleP2pThisDeviceChanged
09-08 14:31:42.455  1924  1924 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-08 14:31:42.455  1924  1924 D WfdsService: Update P2p Interface State: 3
09-08 14:31:42.455  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:42.456  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 14:31:42.474  1030  1370 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-08 14:31:42.474  1030  1370 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,09-08 14:31:42.476  1030  1370 D LGWifiP2pService: InactiveState
09-08 14:31:42.476  1030  1370 D LGWifiP2pService: InactiveState{ when=-38ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.476  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-39ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.476  1030  1370 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-08 14:31:42.476  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 14:31:42.477  6211  6211 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:42.477  1030  6236 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 14:31:42.477  1030  6236 E WifiMonitor: WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:42.477  1030  6236 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:42.477  1030  6236 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:42.477  1924  6256 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 14:31:42.477  6211  6211 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 14:31:42.478  6211  6211 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.478  6211  6211 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.479  1030  6236 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:42.479  1030  1370 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-08 14:31:42.479  1030  6236 E WifiMonitor: WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.479  1030  6236 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.479  1030  6236 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.479  1030  1370 D LGWifiP2pService: InactiveState{ when=-27ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.479  1030  6236 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:42.479  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.479  1030  6236 E WifiMonitor: WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.479  1030  6236 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.479  1030  1370 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.480  1030  6236 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:42.480  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.480  1030  1370 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.480  1030  1370 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.480  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.480  1030  1370 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.480  1030  1370 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.480  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-1ms ,what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.480  1030  1370 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.480  1030  1370 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.480  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.480  1030  1370 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:42.481  1030  1030 E WifiServerServiceExt: No p2p device connected
09-08 14:31:42.481  1924  6256 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:42.481  1924  6256 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:42.481  1924  2250 W WfdsService: DefaultState - msg [9441285] is not handled
09-08 14:31:42.511  1030  1905 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6262 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 14:31:42.517  6239  6260 W FormManager: Network not available. Please check & try again.
09-08 14:31:42.520  6239  6261 V FormManager: Network unavailable.
09-08 14:31:42.522  6239  6261 V FormManager: Network unavailable.
,09-08 14:31:42.536  1030  1995 I ActivityManager: Killing 5614:com.android.defcontainer/u0a4 (adj 15): empty #17
,09-08 14:31:42.569  1030  1905 W libprocessgroup: failed to open /acct/uid_10004/pid_5614/cgroup.procs: No such file or directory
09-08 14:31:42.615  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:31:42.647  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:42.657  1030  1451 D WifiService: New client listening to asynchronous messages
09-08 14:31:42.711  6213  6213 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 14:31:42.711  6213  6213 D LgDataFeature: LgDataFeature() Constructor Done, null
09-08 14:31:42.720  6213  6213 D WiFiOffLoadUpdatePriority: remove : truetruetrue
,09-08 14:31:42.730  1030  1408 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
09-08 14:31:42.732  1030  1408 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
09-08 14:31:42.740  1030  1408 E WifiStateMachine:  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
,09-08 14:31:42.741  1030  1408 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
,09-08 14:31:42.742  1030  1408 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 14:31:42.757  1030  1408 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-08 14:31:42.764  6213  6213 D WiFiOffLoadUpdatePriority: remove1
09-08 14:31:42.765  6213  6213 V WiFiOffLoadSharedPrefsUtils: save remove
09-08 14:31:42.779  6213  6213 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
09-08 14:31:42.780  6213  6213 D WiFiOffLoadBroadcast: S: false, R: false
,09-08 14:31:42.785  1030  1408 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
09-08 14:31:42.786  1030  1408 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
09-08 14:31:42.789  6213  6213 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
09-08 14:31:42.789  6213  6213 D WiFiOffLoadUpdatePriority: connected SSID: null
09-08 14:31:42.789  6213  6213 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
09-08 14:31:42.792  1030  1045 D WifiServiceImplEx: addOrUpdateNetwork pid=6213, uid=1000, packageName=android.uid.system:1000
,09-08 14:31:42.793  1030  1045 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
09-08 14:31:42.794  1030  1408 E WifiStateMachine:  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
09-08 14:31:42.795  1030  1408 E WifiStateMachine:  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
09-08 14:31:42.796  1030  1408 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
09-08 14:31:42.796  1030  1408 D WifiServerServiceExt: addOrUpdateNetwork: mThisIsFirstEnableing = false
09-08 14:31:42.797  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 ssid 4e47373030
09-08 14:31:42.830  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 ssid 4e47373030: returned true
09-08 14:31:42.830  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
,09-08 14:31:42.830  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 key_mgmt WPA-PSK: returned true,
09-08 14:31:42.831  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 proto WPA RSN
09-08 14:31:42.831  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 proto WPA RSN: returned true,
09-08 14:31:42.832  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
,09-08 14:31:42.832  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 pairwise TKIP CCMP: returned true
09-08 14:31:42.832  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
,09-08 14:31:42.833  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
09-08 14:31:42.833  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 priority 300
09-08 14:31:42.833  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 priority 300: returned true
09-08 14:31:42.835  1030  1408 E WifiConfigStore: will read network variables netId=0
09-08 14:31:42.842  1030  1408 E WifiConfigStore: writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
,09-08 14:31:42.843  1030  1408 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
,09-08 14:31:42.845  6213  6213 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
,09-08 14:31:42.846  6213  6213 D WiFiOffLoadUpdatePriority: configuration updated: 0
09-08 14:31:42.847  1030  1408 E WifiStateMachine:  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
09-08 14:31:42.847  1030  1408 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
,09-08 14:31:42.847  1030  1408 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 14:31:42.856  1030  1408 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-08 14:31:42.860  6213  6213 D WiFiOffLoadUpdatePriority: configuration saved: true
09-08 14:31:42.863  1030  1994 I ActivityManager: Killing 5750:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-08 14:31:42.892  1030  1904 W libprocessgroup: failed to open /acct/uid_10008/pid_5750/cgroup.procs: No such file or directory
,09-08 14:31:42.930  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:31:42.937  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:42.947  6211  6211 E wpa_supplicant: USIM:  scard_init function
09-08 14:31:42.948  6211  6211 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-08 14:31:42.948  6239  6289 W FormManager: Network not available. Please check & try again.
09-08 14:31:42.949  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-08 14:31:42.949  1030  6236 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-08 14:31:42.949  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-08 14:31:42.949  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
09-08 14:31:42.950  1030  6236 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-08 14:31:42.950  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-08 14:31:42.950  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-08 14:31:42.951  1030  1408 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
09-08 14:31:42.952  1030  1408 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
09-08 14:31:42.953  1030  1408 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
09-08 14:31:42.953  1030  1408 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
09-08 14:31:42.953  1030  1408 I WifiNative-HAL: startHal
09-08 14:31:42.953  1030  1408 E wifi    : getStaticLongField sWifiHalHandle 0x9886e8cc
09-08 14:31:42.953  1030  1408 E WifiHAL : Could not connect handle
09-08 14:31:42.954  1030  1408 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x4020a2
09-08 14:31:42.954  1030  1408 I WifiNative-HAL: Could not start hal
09-08 14:31:42.954  1030  1408 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-08 14:31:42.954  6239  6290 V FormManager: Network unavailable.
,09-08 14:31:42.957  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:42.964  6239  6290 V FormManager: Network unavailable.
,09-08 14:31:42.972  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=115459  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-08 14:31:42.977  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:42.977  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:42.980  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:42.980  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:42.980  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:31:42.982  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:31:42.986  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:31:42.986  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:31:42.988  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:31:42.990  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=115477  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-08 14:31:42.991  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:42.991  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:42.991  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:31:42.994  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 14:31:42.994  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:42.994  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-08 14:31:43.003  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:43.003  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:43.003  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:43.004  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:43.011  4152  6292 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-08 14:31:43.013  6262  6262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:31:43.013  4152  6291 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:31:43.014  4152  6292 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:31:43.016  6262  6262 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:43.016  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:43.020  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:43.029  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:43.061  6211  6211 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 14:31:43.064  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-08 14:31:43.064  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-08 14:31:43.065  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-08 14:31:43.065  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-08 14:31:43.065  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:31:43.065  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:31:43.066  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=115553  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 14:31:43.067  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=115554  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 14:31:43.068  1030  1408 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=115555
09-08 14:31:43.069  1030  1408 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=115556
09-08 14:31:43.069  1030  1408 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=115556
09-08 14:31:43.070  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=115557
09-08 14:31:43.071  1030  1408 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=115557
09-08 14:31:43.072  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=115558  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-08 14:31:43.073  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:31:43.073  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-08 14:31:43.073  6211  6211 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:31:43.074  6211  6211 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 14:31:43.075  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-08 14:31:43.075  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:31:43.076  1030  6236 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:31:43.076  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-08 14:31:43.076  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 14:31:43.076  1030  6236 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 14:31:43.077  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:31:43.077  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:31:43.102  1030  1886 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6295 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-08 14:31:43.105  1030  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-08 14:31:43.110  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:43.110  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:43.110  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:43.110  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:43.110  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:31:43.110  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=115597  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-08 14:31:43.112  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:43.113  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:43.114  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:43.114  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-08 14:31:43.114  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:43.114  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:43.116  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=115602  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 14:31:43.116  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:43.116  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,09-08 14:31:43.117  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=115603  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 14:31:43.118  1030  1408 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=115604
09-08 14:31:43.118  1030  1408 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=115605
09-08 14:31:43.120  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:43.122  1030  1408 D WifiNative-wlan0: doString: [STATUS]
09-08 14:31:43.123  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:31:43.123  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:31:43.123  1030  1408 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-08 14:31:43.125  1030  1408 I WifiServiceExtension: setVHTCapabilityType  : false
09-08 14:31:43.133  1030  1408 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-08 14:31:43.133  1030  1408 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-08 14:31:43.142  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:43.142  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:43.142  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 14:31:43.148  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:43.148  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:43.148  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:43.148  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:43.148  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-08 14:31:43.149  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:43.152  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:43.152  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:43.154  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:43.160  1030  1408 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-08 14:31:43.160  1030  1464 D ConnectivityService: Got NetworkAgent Messenger
,09-08 14:31:43.161  1030  1464 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 14:31:43.162  1030  1464 D ConnectivityService: NetworkAgent connected
09-08 14:31:43.162  1030  1408 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:31:43.162  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 14:31:43.163  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 14:31:43.163  1030  1408 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 14:31:43.167  1030  1408 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 14:31:43.167  1030  1408 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:31:43.167  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 14:31:43.170  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 14:31:43.170  1030  1408 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 14:31:43.175  1030  1408 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-08 14:31:43.177   308   888 D CommandListener: Setting iface cfg
09-08 14:31:43.182  1030  6313 D DhcpStateMachine: StoppedState
09-08 14:31:43.182  1030  6313 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:43.183  1030  6313 D DhcpStateMachine: WaitBeforeStartState
09-08 14:31:43.183  1030  1408 E WifiStateMachine: Start Dhcp Watchdog 1
,09-08 14:31:43.184  1030  1408 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=115670  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:31:43.184  1030  1408 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=115671  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:31:43.185  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=115671  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:31:43.186  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:43.186  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:43.186  1030  1030 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-08 14:31:43.186  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:43.187  1030  1408 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:43.187  1030  1408 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:43.188  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:43.188  1030  1408 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:43.189  1030  1408 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=115675  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:31:43.189  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:43.189  1030  1030 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-08 14:31:43.189  1030  1408 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=115676  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:31:43.190  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=115677  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:31:43.192  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:164120664] from screen [on:0 period:164120664]
09-08 14:31:43.193  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:164120665]
09-08 14:31:43.193  1030  1408 I WifiNative-HAL: startHal
09-08 14:31:43.193  1030  1408 E wifi    : getStaticLongField sWifiHalHandle 0x9886e8bc
09-08 14:31:43.194  1030  1408 E WifiHAL : Could not connect handle
09-08 14:31:43.194  1030  1408 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x402002
09-08 14:31:43.194  1030  1408 I WifiNative-HAL: Could not start hal
09-08 14:31:43.194  1030  1408 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-08 14:31:43.197  6295  6295 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 14:31:43.199  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:43.201  1030  1464 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
09-08 14:31:43.201  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-08 14:31:43.202  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:43.202  1030  1408 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,09-08 14:31:43.203  1030  1408 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:43.203  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:43.203  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:43.204  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
09-08 14:31:43.205  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
09-08 14:31:43.205  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
09-08 14:31:43.206  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-08 14:31:43.221  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-08 14:31:43.221  1030  1408 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-08 14:31:43.222  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 0
09-08 14:31:43.222  1030  1408 D WifiNative-wlan0: SET ps 0: returned true
,09-08 14:31:43.223  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-08 14:31:43.223  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-08 14:31:43.223  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-08 14:31:43.224  1030  1408 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-08 14:31:43.224  1030  1408 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:31:43.224  1030  1370 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24fc6d11 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:43.224  1030  1408 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:31:43.224  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24fc6d11 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:43.224  1030  1408 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
09-08 14:31:43.225  1030  6313 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:43.226  1030  6313 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-08 14:31:43.226  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:43.226  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 14:31:43.228  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:43.228  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 14:31:43.232  6295  6295 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-08 14:31:43.267  6295  6295 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-08 14:31:43.268  6295  6295 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-08 14:31:43.268  6295  6295 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-08 14:31:43.269  6295  6295 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-08 14:31:43.269  6295  6295 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-08 14:31:43.271  6295  6295 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-08 14:31:43.278  6295  6295 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-08 14:31:43.286  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 14:31:43.292  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:43.329  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 14:31:43.337  6295  6295 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-08 14:31:43.340  5024  5024 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 14:31:43.340  5024  5024 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-08 14:31:43.345  5024  5024 V [BNRBootReceiver]: Boot Receiver Return
09-08 14:31:43.345  6295  6295 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-08 14:31:43.354  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:43.364  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:43.374  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:43.382  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:43.383  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 14:31:43.385  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 14:31:43.387  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-08 14:31:43.391  6213  6213 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-08 14:31:43.394  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:43.401  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:43.407  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:43.419  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:43.419  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:43.421  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 14:31:43.425  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:43.430  1030  6313 D DhcpStateMachine: DHCPV4 request on wlan0
09-08 14:31:43.432  1030  6313 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-08 14:31:43.432  1030  6313 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-08 14:31:43.438  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:43.433  6322  6322 W dhcpcd  : type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:43.433  6322  6322 W dhcpcd  : type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:43.449  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:43.462  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 14:31:43.463  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:43.464  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:43.472  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:43.477  6322  6322 I dhcpcd  : version 5.5.6 starting
,09-08 14:31:43.483  6322  6322 E dhcpcd  : get_duid: m
09-08 14:31:43.483  6322  6322 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-08 14:31:43.483  6322  6322 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-08 14:31:43.484  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:43.501  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:43.521  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:43.521  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:43.522  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 14:31:43.527  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:31:43.527  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:31:43.527  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:31:43.527  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:31:43.528  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:31:43.528  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:31:43.529  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 14:31:43.529  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:31:43.529  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:31:43.529  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:31:43.529  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 14:31:43.529  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:31:43.536  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:31:43.549  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:43.556  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:43.563  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:43.563  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 14:31:43.564  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:43.567  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:43.573  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:43.579  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:43.585  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:43.586  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:43.586  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:43.589  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:31:43.592  6322  6322 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 14:31:43.592  6322  6322 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 14:31:43.592  6322  6322 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 14:31:43.595  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:43.600  6322  6322 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-08 14:31:43.600  6322  6322 D dhcpcd  : wlan0: sending REQUEST (xid 0xdcfeba1e), next in 3.24 seconds
,09-08 14:31:43.601  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:43.608  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:43.608  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:43.608  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:43.613  6295  6295 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-08 14:31:43.616  1030  1358 V AlarmManager: RTC_WAKEUP set : Alarm{251f913 type 0 when 1473337902762 com.android.vending} when 1473337902762
09-08 14:31:43.616  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-08 14:31:43.616  6295  6295 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-08 14:31:43.646  6322  6322 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-08 14:31:43.666  6295  6295 D LgDataFeature: LgDataFeature() Constructor: none
09-08 14:31:43.666  6295  6295 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 14:31:43.674  6295  6295 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-08 14:31:43.674  6295  6295 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-08 14:31:43.675  6295  6295 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-08 14:31:43.675  6295  6295 V SoundPool: doLoad: loading sample sampleID=1
09-08 14:31:43.675  6295  6295 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-08 14:31:43.678  6295  6334 V SoundPool: Start decode
09-08 14:31:43.678  6295  6334 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,09-08 14:31:43.679  6295  6295 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-08 14:31:43.679   312  1377 V MediaPlayerService: decode(22, 10857164, 17813)
09-08 14:31:43.679   312  1377 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-08 14:31:43.679   312  1377 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-08 14:31:43.679   312  1377 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-08 14:31:43.679   312  1377 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-08 14:31:43.679   312  1377 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-08 14:31:43.679   312  1377 V MediaPlayerService: player type = 3
09-08 14:31:43.679   312  1377 V AwesomePlayer: AwesomePlayer create()
09-08 14:31:43.680   312  1377 V AwesomePlayer: reset_l() 
09-08 14:31:43.680   312  1377 V AwesomePlayer: cancelPlayerEvents
09-08 14:31:43.680   312  1377 V AwesomePlayer: setAudioSink() 
09-08 14:31:43.680   312  1377 V AwesomePlayer: reset_l() 
09-08 14:31:43.680   312  1377 V AudioCache: notify(0xb1013480, 8, 0, 0)
09-08 14:31:43.680   312  1377 V AudioCache: ignored
09-08 14:31:43.680   312  1377 V AwesomePlayer: cancelPlayerEvents
09-08 14:31:43.680   312  1377 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-08 14:31:43.680   312  1377 V AwesomePlayer: setDataSource_l dataSource
09-08 14:31:43.680   312  1377 V LGParserOSAL: SniffLGParser start
09-08 14:31:43.680   312  1377 V LGParserOSAL: MainType:5, SubType=0
09-08 14:31:43.680   312  1377 V LGParserOSAL: #### check Mime : application/ogg
09-08 14:31:43.680   312  1377 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-08 14:31:43.680   312  1377 E MediaExtractor: Use LGExtractor :application/ogg 
09-08 14:31:43.681  6322  6322 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-08 14:31:43.681  6161  6161 D UEI.SmartControl: QS Service created
09-08 14:31:43.681  6322  6322 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-08 14:31:43.682  6322  6322 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-08 14:31:43.683  6322  6322 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-08 14:31:43.683  6322  6322 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 14:31:43.684  6322  6322 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 14:31:43.684  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:43.684  6322  6322 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 14:31:43.684  6322  6322 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-08 14:31:43.684  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:43.684  1030  1408 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:43.685  1030  1408 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:43.685  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:43.686  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:43.686  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
09-08 14:31:43.692  6295  6295 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,09-08 14:31:43.693  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-08 14:31:43.713  6295  6295 V LGMDMManager: Create singleton instance
,09-08 14:31:43.726  6161  6161 I UEI.SmartControl: Service initServices...
09-08 14:31:43.727  6161  6161 D UEI.SmartControl: QS start get config
09-08 14:31:43.742   312  1377 V LGParserOSAL: supported mime: application/ogg
09-08 14:31:43.743   312  1377 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-08 14:31:43.743   312  1377 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-08 14:31:43.743   312  1377 V AwesomePlayer: mBitrate = -1 bits/sec
09-08 14:31:43.743   312  1377 V AwesomePlayer: AudioTrack Setting
09-08 14:31:43.743   312  1377 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-08 14:31:43.743   312  1377 V AwesomePlayer: setAudioSource() 
09-08 14:31:43.743   312  1377 V MediaPlayerService: prepare
09-08 14:31:43.743   312  1377 V AwesomePlayer: prepareAsync_l() 
09-08 14:31:43.743   312  1377 V MediaPlayerService: wait for prepare
09-08 14:31:43.743   312  6340 V AwesomePlayer: onPrepareAsyncEvent() 
09-08 14:31:43.743   312  6340 V AwesomePlayer: initAudioDecoder() 
09-08 14:31:43.743   312  6340 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-08 14:31:43.743   312  6340 V AudioSystem: isOffloadSupported()
09-08 14:31:43.743   312  6340 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-08 14:31:43.743   312  6340 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-08 14:31:43.743   312  6340 I AudioFlinger: isAudioPlaybackHookOn() false
09-08 14:31:43.743   312  6340 V AwesomePlayer: getUseOffload() = 0 
09-08 14:31:43.743   312  6340 V OMXCodec: OMXCodec::Create
09-08 14:31:43.743   312  6340 V OMXCodec: findMatchingCodecs()
09-08 14:31:43.743   312  6340 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-08 14:31:43.743   312  6340 V OMXCodec: matchingCodecs.size()=1
09-08 14:31:43.743   312  6340 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,09-08 14:31:43.745   312  6340 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-08 14:31:43.745   312  6340 V LGCodecAdapter: LG Codec Adapter start
09-08 14:31:43.745   312  6340 V OMXCodec: OMXCodec Createtor
09-08 14:31:43.745   312  6340 V OMXCodec: setComponentRole
09-08 14:31:43.745   312  6340 V OMXCodec: configureCodec protected=0
09-08 14:31:43.745   312  6340 V LGCodecAdapter: called getLGCodecSpecificData
09-08 14:31:43.745   312  6340 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-08 14:31:43.745   312  6340 V LGCodecOSAL: Called LGconfigureCodecMETA
09-08 14:31:43.745   312  6340 V LGCodecOSAL: Called LGconfigureCodecMSG
09-08 14:31:43.745   312  6340 V LGCodecOSAL: Not support LGCodec
09-08 14:31:43.745   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-08 14:31:43.745   312  6340 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-08 14:31:43.745   312  6340 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-08 14:31:43.746   312  6340 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-08 14:31:43.746   312  6340 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-08 14:31:43.746   312  6340 V AudioSystem: isOffloadSupported()
09-08 14:31:43.746   312  6340 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-08 14:31:43.746   312  6340 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-08 14:31:43.746   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-08 14:31:43.746   312  6340 V OMXCodec: init()
09-08 14:31:43.746   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-08 14:31:43.746   312  6340 V OMXCodec: allocateBuffers
09-08 14:31:43.746   312  6340 V OMXCodec: allocateBuffersOnPort portIndex=0
09-08 14:31:43.746   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-08 14:31:43.746   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
09-08 14:31:43.746   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-08 14:31:43.746   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
09-08 14:31:43.746   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
09-08 14:31:43.746   312  6340 V OMXCodec: allocateBuffersOnPort portIndex=1
09-08 14:31:43.746   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-08 14:31:43.747   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-08 14:31:43.747   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-08 14:31:43.747   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
09-08 14:31:43.747   312  6340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fc510 on output port
09-08 14:31:43.747   312  6340 V OMXCodec: init() mAsyncCompletion wait!!! 
09-08 14:31:43.747   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-08 14:31:43.747   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-08 14:31:43.747   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-08 14:31:43.747   312  6340 V OMXCodec: init() mAsyncCompletion wait!!! 
09-08 14:31:43.747   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-08 14:31:43.747   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-08 14:31:43.747   31,2  6343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-08 14:31:43.747   312  6340 V OMXCodec: init() mAsyncCompletion wait free! 
09-08 14:31:43.747   312  6340 V AwesomePlayer: finishAsyncPrepare_l() 
09-08 14:31:43.747   312  6340 V AudioCache: notify(0xb1013480, 5, 0, 0)
09-08 14:31:43.747   312  6340 V AudioCache: ignored
09-08 14:31:43.747   312  6340 V AudioCache: notify(0xb1013480, 1, 0, 0)
09-08 14:31:43.747   312  6340 V AudioCache: prepared
09-08 14:31:43.747   312  1377 V AudioCache: wait - success
09-08 14:31:43.747   312  1377 V MediaPlayerService: start
09-08 14:31:43.747   312  1377 V AwesomePlayer: play_l() 
09-08 14:31:43.747   312  1377 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-08 14:31:43.747   312  1377 V AwesomePlayer: createAudioPlayer_l
09-08 14:31:43.747   312  1377 V AwesomePlayer: seekAudioIfNecessary_l() 
09-08 14:31:43.747   312  1377 V AwesomePlayer: startAudioPlayer_l() 
09-08 14:31:43.748   312  1377 D AudioPlayer: start of Playback, useOffload 0
09-08 14:31:43.748   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-08 14:31:43.748   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
09-08 14:31:43.750   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045049616
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-08 14:31:43.751   312  6343 V OMXCodec: allocateBuffersOnPort portIndex=1
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-08 14:31:43.751   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fc6f0 on output port
09-08 14:31:43.755   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-08 14:31:43.755   312  6343 V OMXCod,ec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-08 14:31:43.758   312  1377 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-08 14:31:43.761   312  1377 V AudioCache: notify(0xb1013480, 6, 0, 0)
09-08 14:31:43.761   312  1377 V AudioCache: ignored
09-08 14:31:43.761   312  1377 V MediaPlayerService: wait for playback complete
09-08 14:31:43.769  1030  1905 V SIM_STK : Menu title from STK is T-Mobile
09-08 14:31:43.775   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.775   312  6345 V AudioCache: memcpy(0xaf0f9000, 0xb0406000, 4096)
09-08 14:31:43.777   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.777   312  6345 V AudioCache: memcpy(0xaf0fa000, 0xb0406000, 4096)
09-08 14:31:43.780   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.780   312  6345 V AudioCache: memcpy(0xaf0fb000, 0xb0406000, 4096)
09-08 14:31:43.782   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.782   312  6345 V AudioCache: memcpy(0xaf0fc000, 0xb0406000, 4096)
09-08 14:31:43.790   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.790   312  6345 V AudioCache: memcpy(0xaf0fd000, 0xb0406000, 4096)
09-08 14:31:43.790   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.790   312  6345 V AudioCache: memcpy(0xaf0fe000, 0xb0406000, 4096)
09-08 14:31:43.792   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.792   312  6345 V AudioCache: memcpy(0xaf0ff000, 0xb0406000, 4096)
09-08 14:31:43.794   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.794   312  6345 V AudioCache: memcpy(0xaf100000, 0xb0406000, 4096)
,09-08 14:31:43.796   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.796   312  6345 V AudioCache: memcpy(0xaf101000, 0xb0406000, 4096)
09-08 14:31:43.797   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.797   312  6345 V AudioCache: memcpy(0xaf102000, 0xb0406000, 4096)
09-08 14:31:43.798   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.798   312  6345 V AudioCache: memcpy(0xaf103000, 0xb0406000, 4096)
09-08 14:31:43.799   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.799   312  6345 V AudioCache: memcpy(0xaf104000, 0xb0406000, 4096)
09-08 14:31:43.799   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.799   312  6345 V AudioCache: memcpy(0xaf105000, 0xb0406000, 4096)
09-08 14:31:43.800   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.800   312  6345 V AudioCache: memcpy(0xaf106000, 0xb0406000, 4096)
09-08 14:31:43.801   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.801   312  6345 V AudioCache: memcpy(0xaf107000, 0xb0406000, 4096)
09-08 14:31:43.802   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.802   312  6345 V AudioCache: memcpy(0xaf108000, 0xb0406000, 4096)
09-08 14:31:43.803   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.803   312  6345 V AudioCache: memcpy(0xaf109000, 0xb0406000, 4096)
09-08 14:31:43.803   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.803   312  6345 V AudioCache: memcpy(0xaf10a000, 0xb0406000, 4096)
09-08 14:31:43.804   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.804   312  6345 V AudioCache: memcpy(0xaf10b000, 0xb0406000, 4096)
09-08 14:31:43.805   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.805   312  6345 V AudioCache: memcpy(0xaf10c000, 0xb0406000, 4096)
,09-08 14:31:43.808   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.808   312  6345 V AudioCache: memcpy(0xaf10d000, 0xb0406000, 4096)
09-08 14:31:43.809   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.809   312  6345 V AudioCache: memcpy(0xaf10e000, 0xb0406000, 4096)
09-08 14:31:43.810   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.810   312  6345 V AudioCache: memcpy(0xaf10f000, 0xb0406000, 4096)
09-08 14:31:43.811   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.811   312  6345 V AudioCache: memcpy(0xaf110000, 0xb0406000, 4096)
09-08 14:31:43.811   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.811   312  6345 V AudioCache: memcpy(0xaf111000, 0xb0406000, 4096)
09-08 14:31:43.812   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.812   312  6345 V AudioCache: memcpy(0xaf112000, 0xb0406000, 4096)
09-08 14:31:43.813   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.813   312  6345 V AudioCache: memcpy(0xaf113000, 0xb0406000, 4096)
09-08 14:31:43.813   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.813   312  6345 V AudioCache: memcpy(0xaf114000, 0xb0406000, 4096)
09-08 14:31:43.813   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.813   312  6345 V AudioCache: memcpy(0xaf115000, 0xb0406000, 4096)
09-08 14:31:43.813   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.813   312  6345 V AudioCache: memcpy(0xaf116000, 0xb0406000, 4096)
09-08 14:31:43.816   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.816   312  6345 V AudioCache: memcpy(0xaf117000, 0xb0406000, 4096)
09-08 14:31:43.816   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.816   312  6345 V AudioCache: memcpy(0xaf118000, 0xb0406000, 4096)
09-08 14:31:43.816   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.816   312  6345 V AudioCache: memcpy(0xaf119000, 0xb0406000, 4096)
09-08 14:31:43.816   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.816   312  6345 V AudioCache: memcpy(0xaf11a000, 0xb0406000, 4096)
09-08 14:31:43.819   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.819   312  6345 V AudioCache: memcpy(0xaf11b000, 0xb0406000, 4096)
09-08 14:31:43.819   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.819   312  6345 V AudioCache: memcpy(0xaf11c000, 0xb0406000, 4096)
09-08 14:31:43.819   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.819   312  6345 V AudioCache: memcpy(0xaf11d000, 0xb0406000, 4096)
,09-08 14:31:43.821   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.821   312  6345 V AudioCache: memcpy(0xaf11e000, 0xb0406000, 4096)
09-08 14:31:43.821   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.821   312  6345 V AudioCache: memcpy(0xaf11f000, 0xb0406000, 4096)
09-08 14:31:43.822   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.822   312  6345 V AudioCache: memcpy(0xaf120000, 0xb0406000, 4096)
09-08 14:31:43.823   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.823   312  6345 V AudioCache: memcpy(0xaf121000, 0xb0406000, 4096)
09-08 14:31:43.823   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.824   312  6345 V AudioCache: memcpy(0xaf122000, 0xb0406000, 4096)
09-08 14:31:43.824   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.824   312  6345 V AudioCache: memcpy(0xaf123000, 0xb0406000, 4096)
09-08 14:31:43.825   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.825   312  6345 V AudioCache: memcpy(0xaf124000, 0xb0406000, 4096)
09-08 14:31:43.826   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.826   312  6345 V AudioCache: memcpy(0xaf125000, 0xb0406000, 4096)
09-08 14:31:43.826   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.827   312  6345 V AudioCache: memcpy(0xaf126000, 0xb0406000, 4096)
09-08 14:31:43.827   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.827   312  6345 V AudioCache: memcpy(0xaf127000, 0xb0406000, 4096)
09-08 14:31:43.828   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.828   312  6345 V AudioCache: memcpy(0xaf128000, 0xb0406000, 4096)
09-08 14:31:43.829   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.829   312  6345 V AudioCache: memcpy(0xaf129000, 0xb0406000, 4096)
09-08 14:31:43.829   312  6345 V AudioCache: write(0xb0406000, 4096)
09-08 14:31:43.829   312  6345 V AudioCache: memcpy(0xaf12a000, 0xb0406000, 4096)
09-08 14:31:43.830   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-08 14:31:43.830   312  6345 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-08 14:31:43.830   312  6345 V AwesomePlayer: postAudioEOS() 
09-08 14:31:43.830   312  6345 V AudioCache: write(0xb0406000, 280)
09-08 14:31:43.830   312  6345 V AudioCache: memcpy(0xaf12b000, 0xb0406000, 280)
09-08 14:31:43.836   312  6340 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-08 14:31:43.836   312  6340 V AwesomePlayer: onStreamDone
09-08 14:31:43.836   312  6340 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-08 14:31:43.836   312  6340 V AudioCache: notify(0xb1013480, 2, 0, 0)
09-08 14:31:43.836   312  6340 V AudioCache: playback complete
09-08 14:31:43.836   312  6340 V AwesomePlayer: pause_l() 
09-08 14:31:43.836   312  6340 V AudioCache: notify(0xb1013480, 7, 0, 0)
09-08 14:31:43.836   312  6340 V AudioCache: ignored
09-08 14:31:43.836   312  6340 V AwesomePlayer: cancelPlayerEvents
09-08 14:31:43.836   312  1377 V AudioCache: wait - success
09-08 14:31:43.836   312  1377 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-08 14:31:43.837   312  6340 D AudioPlayer: Pause Playback at 1068125
,09-08 14:31:43.838   312  1377 V AwesomePlayer: reset_l() 
09-08 14:31:43.838   312  1377 V AudioCache: notify(0xb1013480, 8, 0, 0)
09-08 14:31:43.838   312  1377 V AudioCache: ignored
09-08 14:31:43.838   312  1377 V AwesomePlayer: cancelPlayerEvents
09-08 14:31:43.838   312  1377 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-08 14:31:43.838   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-08 14:31:43.838   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-08 14:31:43.838   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-08 14:31:43.839   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57fc6f0 on port 1
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 14:31:43.839   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-08 14:31:43.839   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-08 14:31:43.839   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-08 14:31:43.840   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-08 14:31:43.840   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-08 14:31:43.840   312  6343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-08 14:31:43.840   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-08 14:31:43.840   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-08 14:31:43.840   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-08 14:31:43.841   312  1377 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-08 14:31:43.841   312  1377 D AudioPlayer: AudioPlayer releasing audio source
09-08 14:31:43.841   312  1377 D AudioPlayer: AudioPlayer done releasing audio source
09-08 14:31:43.841   312  1377 V AwesomePlayer: reset_l() 
09-08 14:31:43.841   312  1377 V AwesomePlayer: cancelPlayerEvents
09-08 14,:31:43.841   312  1377 V AwesomePlayer: ~AwesomePlayer call
09-08 14:31:43.842   312  1377 V AwesomePlayer: reset_l() 
09-08 14:31:43.842   312  1377 V AwesomePlayer: cancelPlayerEvents
09-08 14:31:43.842  6295  6334 V SoundPool: close(31)
09-08 14:31:43.842  6295  6334 V SoundPool: pointer = 0xa0026000, size = 205080, sampleRate = 48000, numChannels = 2
09-08 14:31:43.845  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-08 14:31:43.845  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-08 14:31:43.847  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7630
09-08 14:31:43.872  4316  6361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-08 14:31:44.037  1030  6313 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-08 14:31:44.039  1030  6313 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-08 14:31:44.039  1030  6313 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:31:44.039  1030  6313 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-08 14:31:44.039  1030  6313 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-08 14:31:44.039  1030  6313 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:31:44.039  1030  6313 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
09-08 14:31:44.040  1030  6313 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-08 14:31:44.040  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 14:31:44.040  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 14:31:44.040  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 14:31:44.041  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 14:31:44.041  1030  1370 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:44.041  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 14:31:44.041  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-08 14:31:44.041  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:44.041  1030  6313 D DhcpStateMachine: RunningState
09-08 14:31:44.041  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-08 14:31:44.041  1030  1408 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-08 14:31:44.041  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 14:31:44.060  1030  1408 D WifiNative-wlan0: SET ps 1: returned true
09-08 14:31:44.060  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,09-08 14:31:44.061  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 14:31:44.061  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 14:31:44.061  1030  1408 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 14:31:44.062  1030  1464 D ConnectivityService: ignoring duplicate network state non-change
09-08 14:31:44.065  5886  5886 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
09-08 14:31:44.067  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:44.067  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:44.067  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 14:31:44.072  1030  1464 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 14:31:44.075  1030  1464 D ConnectivityService: Adding iface wlan0 to network 100
09-08 14:31:44.077  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:44.078  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:44.078  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 14:31:44.078  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 14:31:44.082  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-08 14:31:44.083  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:44.083  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:44.083  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 14:31:44.085  1030  1408 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-08 14:31:44.087  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 14:31:44.091  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:44.091  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 14:31:44.092  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:44.092  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:44.092  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 14:31:44.093  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:44.093  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:44.095  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:44.095  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 14:31:44.096  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:44.098  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:44.099  1584  1584 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 14:31:44.100  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:44.108  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:44.113  1030  1464 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 14:31:44.114  1030  1464 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
09-08 14:31:44.115  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:44.115  1030  1464 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
09-08 14:31:44.116  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:44.116  1584  1584 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 14:31:44.116  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:44.116  1030  1464 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
09-08 14:31:44.117  1030  1464 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-08 14:31:44.117  1030  1464 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
09-08 14:31:44.117  1030  1464 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
09-08 14:31:44.121  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:44.122  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:44.122  1030  1464 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 14:31:44.122  1030  1464 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-08 14:31:44.122  1030  1464 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,09-08 14:31:44.123  1030  6311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:44.123  1030  6311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-08 14:31:44.123  1030  6311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:44.124  1030  6311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-08 14:31:44.125  1030  1464 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
09-08 14:31:44.125  1030  1464 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:44.126  1030  1464 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:44.126  1030  1464 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 14:31:44.126  1030  1464 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:44.126  1030  1464 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-08 14:31:44.126  1030  1464 D ConnectivityService: currentScore = 0, newScore = 20
09-08 14:31:44.126  1030  1464 D ConnectivityService:    accepting network in place of null
09-08 14:31:44.126  1030  1464 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:44.126  1030  1408 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:44.127  1030  1408 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:44.130  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:44.130  1030  1464 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
09-08 14:31:44.130  1835  1835 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:44.131  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 14:31:44.132   308  6376 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-08 14:31:44.133  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:44.137  1030  1464 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,09-08 14:31:44.137  1030  1464 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 14:31:44.137  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:44.138  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 14:31:44.138  1030  1464 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:44.138  1030  1464 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-08 14:31:44.139  1030  1464 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-08 14:31:44.140  1030  1030 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-08 14:31:44.140  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 14:31:44.141   308  6377 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 14:31:44.141  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 14:31:44.141  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 14:31:44.141  1030  1030 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
09-08 14:31:44.141   308  6377 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
09-08 14:31:44.141  1030  1464 D ConnectivityService: validation of new default Network = false
09-08 14:31:44.141  1030  1464 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-08 14:31:44.141  1030  1464 D DSQN    : enableDataServiceNotify 
09-08 14:31:44.141  1030  1464 D DSQN    : start dsqn bin
09-08 14:31:44.142   308  6377 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
09-08 14:31:44.143  1030  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-08 14:31:44.144   308  6379 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 14:31:44.144   308  6379 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,09-08 14:31:44.150  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:44.150  1030  1464 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
09-08 14:31:44.150  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:44.150  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:44.151  1030  1464 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:44.152  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:31:44.143  6380  6380 W dsqn    : type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:44.143  6380  6380 W dsqn    : type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:44.158  6161  6161 I UEI.SmartControl: Supports setup maps: true
09-08 14:31:44.163  6161  6161 D UEI.SmartControl: QS start statue = true Error code = 0
09-08 14:31:44.163  6161  6161 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-08 14:31:44.163  6161  6161 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-08 14:31:44.163  6161  6161 I UEI.SmartControl: ### init IR Blaster...
,09-08 14:31:44.164  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:44.165  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:44.165  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:44.168  6161  6161 D serial_port: Configuring serial port
09-08 14:31:44.168  6161  6161 E UEI.SmartControl: UEIBLaster setting for 616
09-08 14:31:44.168  6161  6161 I UEI.SmartControl: Setting serial record hearder size = 2
09-08 14:31:44.168  6161  6161 I UEI.SmartControl: configuring settings for MAXQ616
09-08 14:31:44.168  6161  6161 I UEI.SmartControl: Get version...
09-08 14:31:44.171  1030  1369 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-08 14:31:44.174  6380  6380 E DSQN    : DSQN ssw
09-08 14:31:44.175  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:31:44.179  6262  6262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 14:31:44.184  6161  6382 D UEI.SmartControl: serial port data available: 21
09-08 14:31:44.184  1584  1584 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:31:44.185  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:44.186  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:31:44.188  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:44.190  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:44.193  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:44.197  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:44.197  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:44.198  6295  6295 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-08 14:31:44.199   308  6376 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-08 14:31:44.199  6295  6295 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 14:31:44.200  6295  6295 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-08 14:31:44.203  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:44.206  6262  6262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 14:31:44.206  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:44.209  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:44.209  6161  6161 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-08 14:31:44.209  6161  6161 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-08 14:31:44.209  6161  6161 I UEI.SmartControl: QS saving settings...
09-08 14:31:44.210  6161  6161 D UEI.SmartControl: IR Blaster version: 25672567
,09-08 14:31:44.214  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:44.220  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:44.220   308  6379 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
09-08 14:31:44.220  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:44.221  6295  6295 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 14:31:44.222  6295  6295 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-08 14:31:44.224  6295  6295 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-08 14:31:44.226  6161  6382 D UEI.SmartControl: serial port data available: 4
09-08 14:31:44.232   308  6376 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-08 14:31:44.241  1030  6378 D LocSvc_java: NTP server : europe.pool.ntp.org
09-08 14:31:44.242  1030  6378 D LocSvc_java: NTP server returned: 1473337904874 (Thu Sep 08 14:31:44 GMT+02:00 2016) reference: 116727 certainty: 9 system time offset: 633
09-08 14:31:44.242  1030  6378 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
,09-08 14:31:44.257  6161  6387 I UEI.SmartControl: Device manager: loading config....
,09-08 14:31:44.261   308   887 D LGDataListener: argv[0]=dsqncommand
09-08 14:31:44.261   308   887 D LGDataListener: argv[1]=wlan0
09-08 14:31:44.261   308   887 D LGDataListener: argv[2]=1
09-08 14:31:44.261  6161  6387 D UEI.SmartControl: ----------- loading internal config...
09-08 14:31:44.261   308   887 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-08 14:31:44.263  1030  1110 D DSQN    : DSQM DsqnNotification wlan0  1
09-08 14:31:44.263  6161  6161 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-08 14:31:44.263  1030  1110 D DSQN    : start to monitor internet connection
09-08 14:31:44.266  6161  6161 E UEI.SmartControl: Services init done
09-08 14:31:44.266  6161  6161 D UEI.SmartControl: QS Service init finished
09-08 14:31:44.267  6161  6161 D UEI.SmartControl: QS Service version name: 2.1.91
09-08 14:31:44.267  6161  6161 D UEI.SmartControl: QS Service version code: 201091
09-08 14:31:44.269  6161  6161 D UEI.SmartControl: Service requested: Control
,09-08 14:31:44.275  6161  6387 E UEI.SmartControl: Loading SETTINGS...
09-08 14:31:44.279  6161  6161 D UEI.SmartControl: Request IControl service: devices are loaded...
09-08 14:31:44.280  6161  6387 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-08 14:31:44.282  6161  6161 D UEI.SmartControl: Internal service binding...
,09-08 14:31:44.284  6295  6295 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-08 14:31:44.286  6161  6177 I UEI.SmartControl: ------ IControl API: 11
09-08 14:31:44.286  6161  6177 D UEI.SmartControl: File observer start...
09-08 14:31:44.287  6161  6177 E UEI.SmartControl: IR Port is disabled: false
09-08 14:31:44.288  1030  6311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:31:44 GMT], X-Android-Received-Millis=[1473337904287], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473337904259]}
09-08 14:31:44.288  6161  6177 D UEI.SmartControl: Starting file observer...
09-08 14:31:44.288  1030  6311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 14:31:44.288  1030  6311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 14:31:44.289  1030  1464 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
09-08 14:31:44.289  1030  1464 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
09-08 14:31:44.289  1030  1464 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:44.289  1030  1464 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:44.289  1030  1464 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 14:31:44.289  1030  1464 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
09-08 14:31:44.289  1030  1464 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
09-08 14:31:44.289  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:44.289  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:44.290  6161  6177 I UEI.SmartControl: Registering callback...
09-08 14:31:44.290  1030  1464 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:44.290  1030  1464 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-08 14:31:44.291  1030  1408 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:44.291  1030  1408 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:44.291  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 14:31:44.291  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:31:44.292  1835  1835 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:44.292  6161  6176 I UEI.SmartControl: ------ IControl API: 19
09-08 14:31:44.292  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 14:31:44.294  6161  6176 I UEI.SmartControl: Registering Services Ready callback...
09-08 14:31:44.294  6161  6176 I UEI.SmartControl: Notify client services are ready...
09-08 14:31:44.295  6295  6310 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-08 14:31:44.295  6295  6332 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-08 14:31:44.295  6161  6386 I UEI.SmartControl: Notify AllClients services are ready: 0
09-08 14:31:44.295  6295  6332 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-08 14:31:44.296  6161  6386 D UEI.SmartControl: -----service ready thread exits
09-08 14:31:44.296  6295  6295 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-08 14:31:44.296  6295  6312 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-08 14:31:44.297  6295  6332 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-08 14:31:44.297  6295  6332 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-08 14:31:44.297  6295  6295 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,09-08 14:31:44.299  6161  6177 I UEI.SmartControl: ------ IControl API: 8
09-08 14:31:44.302  6295  6295 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-08 14:31:44.303  6295  6295 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-08 14:31:44.303  6295  6295 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-08 14:31:44.303  6295  6295 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-08 14:31:44.304  6295  6295 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-08 14:31:44.304  6295  6295 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-08 14:31:44.306  6295  6295 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-08 14:31:44.309  6295  6295 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
,09-08 14:31:44.310  6295  6295 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-08 14:31:44.314  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-08 14:31:44.316  6295  6295 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 14:31:44.316  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-08 14:31:44.318  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-08 14:31:44.322  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,09-08 14:31:44.322  1030  1408 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-08 14:31:44.323  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-08 14:31:44.323  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:31:44.324  1030  1408 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:31:44.325  1030  1408 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:31:44.325  6295  6295 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473337904323]
09-08 14:31:44.325  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:31:44.326  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:31:44.326  6295  6295 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-08 14:31:44.327  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
09-08 14:31:44.327  1030  1464 D ConnectivityService: identical MTU - not setting
09-08 14:31:44.328  1030  1464 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 14:31:44.328  1030  1464 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-08 14:31:44.328  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:44.328  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:44.329  1030  1464 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:44.330  1584  1584 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:31:44.330  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 14:31:44.331  1030  1959 I ActivityManager: Killing 5784:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-08 14:31:44.331  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:44.333  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:44.363  6295  6391 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-08 14:31:44.373  1030  1994 W libprocessgroup: failed to open /acct/uid_10011/pid_5784/cgroup.procs: No such file or directory
,09-08 14:31:44.379  6295  6295 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-08 14:31:44.380  6295  6295 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,09-08 14:31:44.381  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-08 14:31:44.381  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-08 14:31:44.382  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-08 14:31:44.382  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-08 14:31:44.382  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-08 14:31:44.393  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-08 14:31:44.884  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:44.884  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 added. We now have 2 listener(s)
,09-08 14:31:44.887  1030  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:44.890  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-08 14:31:44.890  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:44.890  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 14:31:44.890  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:44.890  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 added. We now have 2 listener(s)
09-08 14:31:44.890  5982  6084 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:44.891  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:44.894  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:44.899  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:44.899  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:44.899  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:44.899  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:44.899  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:44.899  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:44.899  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:44.899  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:44.905  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:44.905  5982  6084 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:44.907  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:44.914  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 14:31:44.918  5982  6084 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:31:44.918  5982  6084 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:31:44.920  5982  6084 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-08 14:31:44.921  5982  6084 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 14:31:44.921  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 14:31:44.921  5982  6084 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:31:44.921  5982  6084 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:31:44.922  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:44.922  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.922  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:44.922  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:31:44.922  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 removed from the list
09-08 14:31:44.922  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:44.922  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 removed from the list
09-08 14:31:44.922  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:44.923  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:44.926  5982  6084 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-08 14:31:44.927  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:44.927  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.927  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:44.927  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:44.927  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:44.927  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:44.927  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:44.927  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.927  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:44.942  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 14:31:44.942  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 14:31:44.942  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 14:31:44.942  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 14:31:44.942  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 14:31:44.943  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 14:31:44.944  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 14:31:44.944  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 14:31:44.944  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:44.944  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.944  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:44.944  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:44.944  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:44.944  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list,
09-08 14:31:44.944  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:44.944  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.944  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:44.945  5982  6084 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 14:31:44.954  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:44.958  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:44.958  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:44.958  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:44.958  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:44.958  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:44.958  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:44.958  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:44.958  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:44.959  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:44.959  5982  6084 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:31:44.966  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:44.967  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:31:44.967  5982  6084 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:31:44.968  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:31:44.968  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:44.968  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:31:44.973  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:31:44.975  1030  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-08 14:31:44.982  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 14:31:44.989  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:31:44.994  5982  6084 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-08 14:31:44.996  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:31:44.996  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:44.998  5982  6084 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:31:44.999  5982  6084 I io.jxcore.node.ConnectionHelper: start: OK
09-08 14:31:45.000  5982  6084 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-08 14:31:45.000  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 14:31:45.000  5982  6084 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:31:45.003  5982  6084 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 14:31:45.003  5982  6084 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-08 14:31:45.006  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 14:31:45.007  5982  6084 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:31:45.007  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:31:45.007  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:45.007  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:31:45.018  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:31:45.021  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:45.023  5982  6084 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:31:45.023  5982  6084 I io.jxcore.node.ConnectionHelper: start: OK
09-08 14:31:45.024  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.024  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.024  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:31:45.024  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.024  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.024  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.024  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.024  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.026  5982  6084 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 14:31:45.027  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:45.033  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:45.033  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.033  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:45.033  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:45.033  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.033  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:45.033  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:45.033  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:45.036  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:45.037  5982  6084 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:31:45.039  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:45.039  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:31:45.039  5982  6084 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:31:45.039  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:31:45.039  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:45.039  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:31:45.045  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:31:45.047  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:31:45.049  5982  6084 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:31:45.049  5982  6084 I io.jxcore.node.ConnectionHelper: start: OK
09-08 14:31:45.049  5982  6084 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-08 14:31:45.050  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 14:31:45.050  5982  6084 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:31:45.055  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.055  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.055  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:45.055  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.055  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.055  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.055  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.055  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.056  5982  6084 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 14:31:45.057  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.057  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.057  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.057  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.057  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.057  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.057  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.057  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.057  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.058  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 14:31:45.059  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.059  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.059  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.059  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list,
09-08 14:31:45.059  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.059  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.059  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.059  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.059  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.060  5982  6084 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 14:31:45.060  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.060  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.060  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.060  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.060  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.060  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.060  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.060  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.060  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.061  5982  6084 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 14:31:45.061  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.061  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.061  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.061  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.061  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.062  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.062  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.062  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.062  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.062  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 14:31:45.064  5982  6084 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:31:45.064  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 14:31:45.064  5982  6084 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:31:45.064  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 14:31:45.065  5982  6084 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:31:45.065  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.065  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.065  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.065  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.065  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.065  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.065  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.065  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.065  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.066  5982  6084 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:45.066  5982  6084 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 14:31:45.066  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 14:31:45.071  5982  6084 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:45.072  5982  6084 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 14:31:45.072  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 14:31:45.073  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 14:31:45.074  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 14:31:45.074  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 14:31:45.074  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 14:31:45.074  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 14:31:45.074  5982  6084 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 14:31:45.074  5982  6084 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:31:45.074  5982  6084 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 14:31:45.074  5982  6084 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:45.075  5982  6084 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:31:45.075  5982  6084 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 14:31:45.075  5982  6084 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:45.075  5982  6084 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:31:45.075  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 14:31:45.079  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 14:31:45.080  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 14:31:45.080  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 14:31:45.082  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 14:31:45.082  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 14:31:45.082  5982  6084 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 14:31:45.082  5982  6084 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:45.082  5982  6084 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 14:31:45.083  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.083  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.083  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.083  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 14:31:45.086  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.086  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.086  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.086  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.086  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.086  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.087  5982  6084 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 14:31:45.088  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.088  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.088  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.088  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.088  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.088  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.089  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.089  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.089  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.091  5982  6419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 764)
09-08 14:31:45.091  5982  6420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 764
09-08 14:31:45.095  5982  6084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 14:31:45.096  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.096  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.096  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.096  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.096  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.096  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.096  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.096  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.096  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.098  5982  6084 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 14:31:45.098  5982  6084 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 14:31:45.098  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:31:45.098  5982  6084 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 14:31:45.099  5982  6084 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 14:31:45.099  5982  6084 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-08 14:31:45.099  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:31:45.099  5982  6084 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 14:31:45.099  5982  6084 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 14:31:45.099  5982  6084 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 14:31:45.099  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:31:45.099  5982  6084 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 14:31:45.100  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.100  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.100  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.100  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.100  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.100  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.100  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.100  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.100  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.102  5982  6084 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 14:31:45.105  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:45.110  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:45.110  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.110  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:45.110  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:45.110  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.110  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:45.110  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:45.110  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:45.111  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:45.111  5982  6084 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:45.112  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:31:45.112  5982  6084 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:31:45.112  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:31:45.112  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:45.112  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:31:45.114  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:45.118  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:31:45.118  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:45.120  5982  6084 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:31:45.120  5982  6084 I io.jxcore.node.ConnectionHelper: start: OK
09-08 14:31:45.120  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.120  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.120  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:45.120  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.120  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.120  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.120  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.120  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.123  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.123  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.123  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.123  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.123  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.123  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.123  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.124  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.124  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.132  5982  6084 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 14:31:45.132  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:45.135  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 14:31:45.135  5982  6084 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 14:31:45.135  5982  6084 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:31:45.136  5982  5982 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
09-08 14:31:45.136  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 14:31:45.136  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:31:45.137  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:31:45.137  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:31:45.137  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:31:45.138  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:31:45.138  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.138  5982  6084 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:31:45.138  1030  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:45.138  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.138  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.138  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:31:45.138  5982  6084 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:31:45.138  5982  5982 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 14:31:45.138  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 14:31:45.139  5982  6424 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:31:45.139  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:31:45.140  3723  3742 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-08 14:31:45.141  5982  6424 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
09-08 14:31:45.141  5982  6424 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:31:45.141  5982  6424 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 14:31:45.142  5982  6084 D BluetoothLeScanner: could not find callback wrapper
09-08 14:31:45.142  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 14:31:45.142  5982  6084 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:31:45.142  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.142  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.143  5982  6084 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:31:45.144  5982  5982 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:31:45.144  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.144  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.144  5982  5982 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:31:45.144  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.144  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.144  5982  5982 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 14:31:45.144  5982  5982 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:31:45.145  5982  6084 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 14:31:45.145  5982  6084 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 14:31:45.145  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 14:31:45.148  5982  6084 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:31:45.148  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.148  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.148  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.148  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.148  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.148  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.148  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.148  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.148  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.150  1030  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:45.151  1030  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:45.152  1030  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:45.153  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.153  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.153  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.153  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.153  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.153  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.153  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.153  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:31:45.153  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.155  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.156  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.156  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.156  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29427fe6 not in the list
09-08 14:31:45.156  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.156  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262cb927 not in the list
09-08 14:31:45.156  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.156  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.156  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.158  5982  6084 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 14:31:45.158  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:31:45.158  5982  6084 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 14:31:45.159  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:31:45.159  5982  6084 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 14:31:45.159  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 14:31:45.161  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 14:31:45.161  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 14:31:45.163  5982  6084 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-08 14:31:45.163  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-08 14:31:45.163  5982  6084 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 14:31:45.163  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 14:31:45.164  5982  6084 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 14:31:45.164  5982  6084 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 14:31:45.165  5982  6084 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 14:31:45.165  5982  6084 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 14:31:45.166  5982  6084 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 14:31:45.166  5982  6084 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 14:31:45.166  5982  6084 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 14:31:45.166  5982  6084 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-08 14:31:45.182  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:45.182  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2409df35 added. We now have 2 listener(s)
09-08 14:31:45.182  1030  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-08 14:31:45.185  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 14:31:45.185  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:45.185  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:31:45.185  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:45.185  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32345fca added. We now have 2 listener(s)
09-08 14:31:45.185  5982  6084 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:45.186  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:31:45.189  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:45.192  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:45.192  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.192  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:45.192  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:45.192  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.192  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:45.192  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:45.192  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:45.193  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:45.194  5982  6084 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:45.195  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:45.197  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.197  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:31:45.197  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:31:45.197  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:31:45.197  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2409df35 removed from the list
09-08 14:31:45.197  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.197  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32345fca removed from the list
09-08 14:31:45.197  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.197  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.199  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:45.199  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecae458 added. We now have 2 listener(s)
09-08 14:31:45.199  1030  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:45.202  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 14:31:45.202  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:45.202  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 14:31:45.202  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:45.202  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220639b1 added. We now have 2 listener(s)
09-08 14:31:45.202  5982  6084 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:45.202  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:45.205  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:45.208  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:45.208  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.208  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:45.208  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:45.208  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.208  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:45.208  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:45.208  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:45.210  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:45.210  5982  6084 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:31:45.212  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:45.212  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:45.212  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:45.212  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:45.213  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:31:45.213  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecae458 removed from the list
09-08 14:31:45.213  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:45.213  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220639b1 removed from the list
09-08 14:31:45.213  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:45.213  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:45.214  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:45.214  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b203a17 added. We now have 2 listener(s)
09-08 14:31:45.214  1030  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:45.217  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 14:31:45.217  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:45.217  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:31:45.217  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:45.217  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3335ee04 added. We now have 2 listener(s)
09-08 14:31:45.217  5982  6084 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:45.218  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:45.220  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:45.222  5982  6419 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-08 14:31:45.224  5982  6419 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:31:45.225  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:45.225  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.225  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:45.225  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:45.225  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.225  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:45.225  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connectin,g to active network: true
09-08 14:31:45.225  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:45.226  3723  3742 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:45.226  3723  3968 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
09-08 14:31:45.227  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:45.227  5982  6084 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:45.230  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:45.234  1030  1994 D WifiServiceImplEx: setWifiEnabled: false pid=5982, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 14:31:45.234  1030  1994 D WifiService: setWifiEnabled: false pid=5982, uid=10118
09-08 14:31:45.234  1030  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:31:45.254  1030  1408 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-08 14:31:45.255  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-08 14:31:45.255  1030  1408 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-08 14:31:45.255  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:31:45.256  1030  1408 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-08 14:31:45.256  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:31:45.256  1030  1030 D Ulp_jni : JNI:system_update. Event-4
09-08 14:31:45.256  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-08 14:31:45.257  1030  1408 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 14:31:45.257  1030  1408 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:31:45.257  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-08 14:31:45.258  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 14:31:45.258  1030  1408 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 14:31:45.269  1030  1408 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 14:31:45.269  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 14:31:45.269  1030  1370 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.269  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.270  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 14:31:45.270  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 14:31:45.270  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 1
,09-08 14:31:45.272  1030  1408 D WifiNative-wlan0: SET ps 1: returned true
,09-08 14:31:45.272  1030  6313 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.272   308   888 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:31:45.314  1030  1464 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 14:31:45.314  1030  1464 D ConnectivityService: ignoring duplicate network state non-change
09-08 14:31:45.314  1030  1464 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-08 14:31:45.315  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:45.315  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:45.317  1030  1030 D WifiHS20: hidePasspointNotification off =false
09-08 14:31:45.318  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:45.320  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 0
,09-08 14:31:45.324  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:45.324  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:45.325  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:45.325  1030  1370 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.325  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.325  1030  1370 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2aab93ad
09-08 14:31:45.326  1030  1408 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:45.326  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:45.326  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:45.326  1030  1408 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 14:31:45.327  1030  1370 D LGWifiP2pService: P2pDisablingState
09-08 14:31:45.327  1030  1370 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.327  1030  1370 D LGWifiP2pService: p2p socket connection lost
09-08 14:31:45.327  1030  1370 D LGWifiP2pService: P2pDisabledState
09-08 14:31:45.328  1030  1030 D WifiHS20: hidePasspointNotification off =false
09-08 14:31:45.329  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:45.329  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:45.329  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:45.330  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-08 14:31:45.330  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 1
09-08 14:31:45.330  1924  1924 D WfdsService: WifiP2pState is changed : false
09-08 14:31:45.330  1924  2250 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-08 14:31:45.330  1924  2250 D WfdsService: Set the WFDS Monitor: false
09-08 14:31:45.332  1924  2250 D WfdsMonitor: WFDS Monitor is stopped
09-08 14:31:45.332  1030  1538 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.332  1924  2250 D WfdsService: STATE : WfdsDisabledState - enter
09-08 14:31:45.332  1924  6256 D CtrlSupplicant: Received on exit socket, terminate
09-08 14:31:45.332  1924  6256 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-08 14:31:45.332  1924  2251 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-08 14:31:45.332  1924  6256 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-08 14:31:45.332  1924  6256 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-08 14:31:45.332  1924  2250 W WfdsService: DefaultState - msg [9445378] is not handled
,09-08 14:31:45.335  1030  1408 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-08 14:31:45.335  1030  1370 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.335  1030  1370 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.335  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 14:31:45.336  6211  6211 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 14:31:45.336  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,09-08 14:31:45.336  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 14:31:45.336  1030  1408 D WifiNative-wlan0: SET ps 1: returned true
09-08 14:31:45.336  1030  1030 D RttService: SCAN_AVAILABLE : 1
09-08 14:31:45.337  1030  1539 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.340  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:45.346  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:45.346  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:45.349  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:31:45.352  6262  6262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:31:45.352  6262  6262 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:45.352  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:45.361  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:45.365   308   888 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:31:45.365  1030  1464 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-08 14:31:45.365  1030  1464 D DSQN    : disableDataServiceNotify
09-08 14:31:45.366  1030  1464 D DSQN    : stop dsqn bin
09-08 14:31:45.366  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:45.367  1030  1408 D WifiNative-p2p0: doBoolean: TERMINATE
09-08 14:31:45.367  1030  1030 D WifiHS20: hidePasspointNotification off =false
09-08 14:31:45.367  1030  1408 D WifiNative-p2p0: TERMINATE: returned true
09-08 14:31:45.367  1030  1408 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 14:31:45.367  1030  1408 E WifiStateMachine: useWiFiOffloading() : false
09-08 14:31:45.367  1030  1408 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 14:31:45.369  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:45.369  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:45.369  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 14:31:45.369  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:45.369  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:45.369  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-08 14:31:45.370  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:45.372  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:45.373  1030  1464 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 14:31:45.373  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:45.373  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:45.374  1030  1464 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:45.374  1030  1464 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-08 14:31:45.374  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-08 14:31:45.374  1030  1464 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-08 14:31:45.375  1030  1464 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 14:31:45.375  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 14:31:45.375  1030  6311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.375  1030  6311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.375  1030  6311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-08 14:31:45.376  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:45.376  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.376  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:45.376  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:45.376  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.376  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:45.376  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:45.376  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:45.377  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:45.377  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-08 14:31:45.377  1030  1464 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:45.378  1030  1369 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 14:31:45.377  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 14:31:45.379  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 14:31:45.379  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 14:31:45.379  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 14:31:45.379  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 14:31:45.381  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:45.382  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:45.382  1030  1464 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:45.382  1030  1464 D ConnectivityS,ervice: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:45.382  1030  1464 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:45.382  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:45.382  1030  1030 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-08 14:31:45.382  1030  1464 D NetworkManagementService: Removing idletimer
09-08 14:31:45.382  1030  1464 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:45.382  1030  1369 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 14:31:45.383  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 14:31:45.383  1030  1408 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:45.383  1030  1408 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:45.383  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 14:31:45.383  1835  1835 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:45.383  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 14:31:45.383  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 14:31:45.383  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 14:31:45.385  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 14:31:45.385  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:45.385  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.385  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:45.385  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:45.385  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.385  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:45.385  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:45.385  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:45.389  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:45.390  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:45.392  6262  6262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:31:45.392  6262  6262 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:45.392  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:45.396  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:45.403  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:45.410  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:45.410  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:45.411  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 14:31:45.413  6211  6211 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-08 14:31:45.413  6211  6211 I wpa_supplicant: monitor socket send errors count : 1
09-08 14:31:45.413  6211  6211 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1924-2\x00 that cannot receive messages
09-08 14:31:45.414  1030  6236 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-08 14:31:45.414  1030  6236 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-08 14:31:45.419  1584  1584 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:31:45.420  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:45.420  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:45.420  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:45.424  6262  6262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:31:45.425  6262  6262 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:45.425  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:31:45.429  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:45.436  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:45.445  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:45.445  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 14:31:45.447  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 14:31:45.451  1584  1584 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:31:45.452  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:45.453  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:45.455  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:45.458  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:45.461  6239  6433 W FormManager: Network not available. Please check & try again.
,09-08 14:31:45.465  6239  6434 V FormManager: Network unavailable.
09-08 14:31:45.466  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:45.472  6239  6434 V FormManager: Network unavailable.
,09-08 14:31:45.478  1030  6313 D DhcpStateMachine: StoppedState
09-08 14:31:45.478  1030  6313 D DhcpStateMachine: StoppedState{ when=-142ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.480  1030  1408 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-08 14:31:45.481  1030  1408 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-08 14:31:45.559  6211  6211 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 14:31:45.560  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-08 14:31:45.561  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 14:31:45.561  1030  6236 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 14:31:45.562  1030  6236 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,09-08 14:31:45.566  1030  1408 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118052
09-08 14:31:45.566  6211  6211 W wpa_supplicant: USIM:  scard_deinit function
09-08 14:31:45.567  1030  1112 D Tethering: InitialState.processMessage what=4
09-08 14:31:45.567  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:31:45.567  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:31:45.568  1030  1408 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118055
09-08 14:31:45.570  1030  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 14:31:45.573  1030  1408 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118060  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-08 14:31:45.574  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:31:45.574  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:31:45.574  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:31:45.575  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:31:45.575  1030  1408 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118061  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-08 14:31:45.575  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:31:45.575  1030  1408 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:45.576  1030  1408 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:45.576  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:31:45.576  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-08 14:31:45.576  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:31:45.576  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:31:45.576  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:31:45.577  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:31:45.592  6211  6211 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-08 14:31:45.592  1030  6236 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-08 14:31:45.592  1030  6236 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-08 14:31:45.593  1030  6236 D WifiMonitor: Disconnecting from the supplicant, no more events
09-08 14:31:45.593  1030  1408 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,09-08 14:31:45.645  5982  5982 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:31:45.696  1924  1924 D WfdsService: Supplicant Connection state is changed : false
,09-08 14:31:45.697  1924  2250 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,09-08 14:31:45.697  1924  2250 D WfdsService: Set the WFDS Monitor: false
09-08 14:31:45.697  1924  2250 D WfdsMonitor: WFDS Monitor is stopped
09-08 14:31:45.704  1030  1408 D WifiOffDelayIfNotUsed: stopMonitoring
09-08 14:31:45.704  1030  1408 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 14:31:45.704  1030  1408 E WifiStateMachine: useWiFiOffloading() : false
09-08 14:31:45.704  1030  1408 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 14:31:45.704  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:31:45.705  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:31:45.708  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:45.710  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-08 14:31:45.711  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 14:31:45.715  2473  2473 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:45.720  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-08 14:31:45.721  1030  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-08 14:31:45.725  1030  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-08 14:31:45.727  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:45.727  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.727  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:45.727  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:45.727  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.727  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:45.727  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:45.727  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:45.729  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 14:31:45.733  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:45.733  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.733  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:45.733  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:45.733  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.733  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:45.733  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:45.733  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:45.740  6262  6262 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-08 14:31:45.740  6262  6262 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:45.740  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:45.740  4152  6438 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 14:31:45.742  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:45.744  4152  6440 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:31:45.744  4152  6440 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:31:45.750  6239  6441 W FormManager: Network not available. Please check & try again.
09-08 14:31:45.750  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:45.761  1030  1995 D WifiServiceImplEx: setWifiEnabled: true pid=5982, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 14:31:45.762  1030  1995 D WifiService: setWifiEnabled: true pid=5982, uid=10118
09-08 14:31:45.762  1030  1995 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:31:45.764  6239  6442 V FormManager: Network unavailable.
09-08 14:31:45.768  6239  6442 V FormManager: Network unavailable.
09-08 14:31:45.781  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:31:45.782  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:31:45.782  1030  1030 D Ulp_jni : JNI:system_update. Event-4
,09-08 14:31:45.909  1030  1408 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-08 14:31:45.909  1030  1408 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-08 14:31:45.917  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,09-08 14:31:45.917  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 14:31:45.917  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-08 14:31:45.917  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 14:31:45.918  1030  1408 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-08 14:31:45.918  1030  1408 E WifiHW  : unknown target_country: EU , set to default
09-08 14:31:45.918  1030  1408 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-08 14:31:45.918  1030  1408 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-08 14:31:45.918  1030  1408 I WifiUtil: gEnableBmps=1
09-08 14:31:46.572   308   888 D SoftapController: Softap fwReload - Ok
,09-08 14:31:46.582  1030  1408 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (648ms)
09-08 14:31:46.584   308   888 D CommandListener: Setting iface cfg
09-08 14:31:46.584   308   888 D CommandListener: Trying to bring down wlan0
,09-08 14:31:46.606  1030  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 14:31:46.607   308   888 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:31:46.608   308  6458 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-08 14:31:46.623  1030  1408 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-08 14:31:46.626  1030  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-08 14:31:46.613  6459  6459 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-08 14:31:46.623  6459  6459 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:46.661  1030  1408 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 14:31:46.661  1030  1408 E WifiStateMachine: useWiFiOffloading() : false
09-08 14:31:46.661  1030  1408 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-08 14:31:46.667  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-08 14:31:46.670  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:46.670  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-08 14:31:46.687  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:46.687  1030  1408 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-08 14:31:46.688  1030  1408 D WifiMonitor: connecting to supplicant
09-08 14:31:46.693  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:46.695  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:31:46.696  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:31:46.696  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:31:46.696  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:31:46.697  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:31:46.699  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:31:46.699  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 14:31:46.700  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:31:46.700  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,09-08 14:31:46.700  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:31:46.700  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 14:31:46.700  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:31:46.702  6459  6459 I wpa_supplicant: Successfully initialized wpa_supplicant
09-08 14:31:46.717  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:46.724  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:46.730  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:46.738  6459  6459 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 14:31:46.738  6459  6459 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-08 14:31:46.741  1030  1112 D Tethering: InitialState.processMessage what=4
,09-08 14:31:46.743  1030  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 14:31:46.746  6239  6476 W FormManager: Network not available. Please check & try again.
09-08 14:31:46.750  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:31:46.751  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:31:46.751  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:31:46.751  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:31:46.752  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:31:46.753  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:31:46.753  6239  6477 V FormManager: Network unavailable.
09-08 14:31:46.753  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-08 14:31:46.753  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:31:46.753  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:31:46.753  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:31:46.754  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-08 14:31:46.758  6239  6477 V FormManager: Network unavailable.
09-08 14:31:46.829  6459  6459 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 14:31:46.846  6459  6459 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-08 14:31:46.856  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-08 14:31:46.857  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-08 14:31:46.857  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-08 14:31:46.858  1030  1408 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-08 14:31:46.859  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3659] from screen [on:0 period:164124331] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-08 14:31:46.860  1030  1408 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:164124332] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-08 14:31:46.861  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:46.862  1030  1408 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:46.864  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:46.865  1030  1408 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:46.865  1030  1408 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-08 14:31:46.865  1030  1408 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-08 14:31:46.866  1030  1408 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-08 14:31:46.867  1030  1408 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-08 14:31:46.867  1030  1408 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-08 14:31:46.868  1030  1408 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 14:31:46.868  1030  1408 E WifiStateMachine: useWiFiOffloading() : false
09-08 14:31:46.868  1030  1408 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 14:31:46.869  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:46.869  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:46.869  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:46.870  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:46.870  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:46.877  1924  1924 D WfdService: Waiting for WifiP2p enabling
09-08 14:31:46.879  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:31:46.882  1030  1408 D WifiNative-wlan0: doBoolean: SET update_config 1
09-08 14:31:46.885  1030  1408 D WifiNative-wlan0: SET update_config 1: returned true
09-08 14:31:46.885  1030  1408 D WifiConfigStore: Loading config and enabling all networks 
09-08 14:31:46.885  1030  1408 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-08 14:31:46.885  1030  1408 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-08 14:31:46.885  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:46.885  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:46.885  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:46.885  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:46.885  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:46.885  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:46.885  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:46.885  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:46.889  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-08 14:31:46.889  1030  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-08 14:31:46.890  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:46.892  6459  6459 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-08 14:31:46.893  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,09-08 14:31:46.893  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 14:31:46.893  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-08 14:31:46.893  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-08 14:31:46.893  1030  6480 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-08 14:31:46.893  1030  6480 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-08 14:31:46.896  1030  1408 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-08 14:31:46.899  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:46.899  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:46.899  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:46.899  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:46.899  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:46.899  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:46.899  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:46.899  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:46.903  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:46.908  1030  1408 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-08 14:31:46.908  1030  1408 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-08 14:31:46.909  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:46.909  1030  1408 D WifiStateMachine: enableVerboseLogging : level 2
09-08 14:31:46.909  1030  1408 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-08 14:31:46.910  1030  1408 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-08 14:31:46.910  1030  1408 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-08 14:31:46.911  1030  1408 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-08 14:31:46.911  1030  1408 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,09-08 14:31:46.912  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:46.913  1030  1408 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-08 14:31:46.913  1030  1408 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-08 14:31:46.913  1030  1408 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-08 14:31:46.914  1030  1408 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-08 14:31:46.914  1030  1408 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-08 14:31:46.914  1030  1408 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-08 14:31:46.914  1030  1408 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-08 14:31:46.915  1030  1408 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-08 14:31:46.915  1030  1408 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-08 14:31:46.916  1030  1408 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:31:46.916  1030  1408 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-08 14:31:46.916  1924  1924 D WfdsService: Supplicant Connection state is changed : true
09-08 14:31:46.916  1030  1408 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-08 14:31:46.916  1030  1408 D WifiNative-HAL: Setting external_sim to 1
09-08 14:31:46.916  1030  1408 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-08 14:31:46.916  1924  2250 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-08 14:31:46.916  1924  2250 D WfdsService: Set the WFDS Monitor: true
09-08 14:31:46.916  1924  2250 D WfdsMonitor: WfdsMonitorThread create
09-08 14:31:46.917  1924  2250 D WfdsMonitor: WFDS Monitor is created and started
09-08 14:31:46.917  1924  2250 D WfdsService: WiFi: Supplicant connection re-established
09-08 14:31:46.917  1030  1408 D WifiNative-wlan0: SET external_sim 1: returned true
09-08 14:31:46.917  1030  1408 I WifiNative-HAL: startHal
09-08 14:31:46.917  1030  1408 E wifi    : getStaticLongField sWifiHalHandle 0x9886e8dc
09-08 14:31:46.917  1030  1408 E WifiHAL : Could not connect handle
09-08 14:31:46.917  1030  1408 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301c4e
09-08 14:31:46.917  1030  1408 I WifiNative-HAL: Could not start hal
09-08 14:31:46.917  1030  1408 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:31:46.917  1030  1408 I WifiNative-HAL: startHal
09-08 14:31:46.917  1030  1408 E wifi    : getStaticLongField sWifiHalHandle 0x9886e85c
09-08 14:31:46.917  1030  1408 E WifiHAL : Could not connect handle
09-08 14:31:46.917  1030  1408 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401c4a
09-08 14:31:46.917  1030  1408 I WifiNative-HAL: Could not start hal
09-08 14:31:46.917  1030  1408 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-08 14:31:46.918  1030  1408 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-08 14:31:46.918  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-08 14:31:46.918  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-08 14:31:46.918  1924  6485 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-08 14:31:46.918  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-08 14:31:46.918  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 14:31:46.918  1924  6485 E CtrlSupplicant: Succeed to open control connection
09-08 14:31:46.918  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 14:31:46.919  1924  6485 E CtrlSupplicant: Succeed to open monitor connection
09-08 14:31:46.919  1924  6485 D WfdsMonitor: Supplicant connection established
09-08 14:31:46.919  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 14:31:46.919  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-08 14:31:46.919  1924  2250 D WfdsService: Connected to the supplicant for wfds
09-08 14:31:46.919  6459  6459 I wpa_suppl,icant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-08 14:31:46.919  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-08 14:31:46.919  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 14:31:46.919  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 14:31:46.920  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 14:31:46.920  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 14:31:46.920  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 14:31:46.920  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 14:31:46.920  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-08 14:31:46.920  6459  6459 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-08 14:31:46.920  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-08 14:31:46.921  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 14:31:46.921  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 14:31:46.921  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 14:31:46.921  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:46.922  1030  1408 E WifiNative: : [119,408,454 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-08 14:31:46.922  1030  1408 D WifiNative-wlan0: doBoolean: RECONNECT
09-08 14:31:46.922  1030  1408 D WifiNative-wlan0: RECONNECT: returned true
09-08 14:31:46.922  1030  1408 D WifiNative-wlan0: doString: [STATUS]
09-08 14:31:46.923  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-08 14:31:46.923  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 14:31:46.923  1030  1408 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-08 14:31:46.923  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 14:31:46.924  1030  1408 D WifiNative-wlan0: SET ps 1: returned true
09-08 14:31:46.925  1030  1370 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.927   308   888 D CommandListener: Setting iface cfg
09-08 14:31:46.927   308   888 D CommandListener: Trying to bring up p2p0
09-08 14:31:46.927  1030  1370 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 14:31:46.927  1030  1370 D LGWifiP2pService: P2pEnablingState
09-08 14:31:46.927  1030  1370 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.927  1030  1370 D LGWifiP2pService: P2p socket connection successful
09-08 14:31:46.927  1030  1370 D LGWifiP2pService: P2pEnabledState
09-08 14:31:46.928  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 3
,09-08 14:31:46.928  1030  1030 D RttService: SCAN_AVAILABLE : 3
09-08 14:31:46.929  1030  1538 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.929  1030  1538 I WifiNative-HAL: startHal
09-08 14:31:46.929  1030  1538 E wifi    : getStaticLongField sWifiHalHandle 0x94d6899c
09-08 14:31:46.929  1030  1539 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.929  1030  1538 E WifiHAL : Could not connect handle
09-08 14:31:46.929  1030  1538 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601c26
09-08 14:31:46.929  1030  1538 I WifiNative-HAL: Could not start hal
09-08 14:31:46.929  1030  1538 E WifiScanningService: could not start HAL
09-08 14:31:46.930  1030  1408 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-08 14:31:46.931  1030  1408 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-08 14:31:46.931  1030  1408 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-08 14:31:46.932  1030  1408 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
,09-08 14:31:46.932  1030  1408 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-08 14:31:46.933  1030  1408 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-08 14:31:46.933  6239  6483 W FormManager: Network not available. Please check & try again.
09-08 14:31:46.933  1030  1408 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-08 14:31:46.933  1030  1408 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-08 14:31:46.933  1030  1370 D LGWifiP2pService: sending p2p connection changed broadcast
09-08 14:31:46.933  6459  6459 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-08 14:31:46.934  1030  1408 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-08 14:31:46.934  1030  1408 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,09-08 14:31:46.935  1030  1408 E WifiStateMachine:  DriverStartedState what:132096 -100 0
,09-08 14:31:46.935  1030  1408 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-08 14:31:46.935  6459  6459 E wpa_supplicant: disconnect_rssi_lvl: -100
09-08 14:31:46.935  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-08 14:31:46.935  1924  1924 D WfdsService: WifiP2pState is changed : true
,09-08 14:31:46.936  1030  1370 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-08 14:31:46.936  1924  2250 D WfdsService: Receive the WFDS_ENABLE Method
09-08 14:31:46.936  1924  2250 D WfdsService: Set the WFDS Monitor: true
09-08 14:31:46.936  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=119423  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-08 14:31:46.936  1924  2250 D WfdsService: Connected to the supplicant for wfds
09-08 14:31:46.936  1924  2250 D WfdsJNI : doCommand: WFDS_SET TRUE
09-08 14:31:46.937  6459  6459 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-08 14:31:46.937  1924  2250 D WfdsService: selectPreferredScanChannel [36]
,09-08 14:31:46.937  1924  2250 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-08 14:31:46.938  1924  1924 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-08 14:31:46.938  1924  1924 D WfdsService: isConnected: false
,09-08 14:31:46.939  1030  1370 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-08 14:31:46.939  1030  1370 D WifiNative-p2p0: doBoolean: SET device_name G3
09-08 14:31:46.940  1030  1370 D WifiNative-p2p0: SET device_name G3: returned true
09-08 14:31:46.940  1030  1370 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix,
09-08 14:31:46.940  1030  1370 D LGWifiP2pService: before postfix = G3
09-08 14:31:46.940  1030  1370 D WifiServerServiceExt: postfix byte check : 2
09-08 14:31:46.940  1030  1370 D LGWifiP2pService: after postfix = G3
,09-08 14:31:46.940  1030  1370 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-08 14:31:46.940  1030  1370 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true,
,09-08 14:31:46.940  1030  1370 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-08 14:31:46.941  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:46.941  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 14:31:46.941  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:46.942  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:46.942  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:31:46.943  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:31:46.946  1030  1370 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-08 14:31:46.946  1030  1370 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-08 14:31:46.946  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=119432  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 14:31:46.946  1030  1370 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-08 14:31:46.946  1030  1370 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-08 14:31:46.946  1030  1370 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-08 14:31:46.947  1030  1370 D WifiNative-HAL: p2pGetDeviceAddress
09-08 14:31:46.947  1030  1370 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-08 14:31:46.947  1030  1408 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-08 14:31:46.947  1030  1408 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-08 14:31:46.948  1030  1408 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-08 14:31:46.948  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-08 14:31:46.949  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 14:31:46.950  6459  6459 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:46.950  6459  6459 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 14:31:46.950  6459  6459 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.951  1030  1408 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-08 14:31:46.951  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 14:31:46.951  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:46.952  1030  6480 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:46.952  6459  6459 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.952  1030  6480 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:46.952  1030  1408 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-08 14:31:46.952  1030  6480 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:46.952  1030  6480 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.952  1030  6480 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.952  1030  1408 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-08 14:31:46.952  1030  6480 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.952  1030  6480 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:46.952  1030  6480 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.952  1924  6485 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:46.952  1030  1408 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-08 14:31:46.952  1924  6485 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:46.952  1030  6480 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.952  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-08 14:31:46.952  1030  6480 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.953  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-08 14:31:46.953  6459  6459 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CO,RE type=UNKNOWN
09-08 14:31:46.953  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-08 14:31:46.953  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:31:46.953  1030  1408 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-08 14:31:46.953  1030  6480 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:31:46.954  1030  1408 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-08 14:31:46.954  1030  6480 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:31:46.954  1030  1408 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-08 14:31:46.954  1030  1408 D WifiNative-wlan0: doBoolean: SCAN
09-08 14:31:46.954  1030  1370 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-08 14:31:46.954  1030  1370 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-08 14:31:46.954  1030  1408 D WifiNative-wlan0: SCAN: returned false
09-08 14:31:46.954  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:31:46.955  1030  1370 D WifiNative-p2p0: P2P_FLUSH: returned true
09-08 14:31:46.955  1030  1370 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-08 14:31:46.955  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=119442  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 14:31:46.955  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:31:46.955  1924  1924 I WfdStateTracker: handleP2pThisDeviceChanged
09-08 14:31:46.956  1030  1370 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-08 14:31:46.956  1030  1370 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-08 14:31:46.956  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=119442  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 14:31:46.956  1924  1924 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-08 14:31:46.956  1924  1924 D WfdsService: Update P2p Interface State: 3
09-08 14:31:46.956  1030  1370 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-08 14:31:46.956  1030  1370 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-08 14:31:46.956  1030  1408 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:31:46.957  1030  1408 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:31:46.957  1030  1408 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:31:46.957  1030  1408 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:31:46.958  1030  1408 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:31:46.958  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:31:46.959  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:46.959  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:46.959  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-08 14:31:46.963  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:31:46.964  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:46.964  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 14:31:46.966  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:46.966  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:46.966  6239  6484 V FormManager: Network unavailable.
09-08 14:31:46.967  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:46.968  5024  5024 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 14:31:46.968  5024  5024 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-08 14:31:46.968  5024  5024 V [BNRBootReceiver]: Boot Receiver Return
09-08 14:31:46.968  1030  1370 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-08 14:31:46.968  1030  1370 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-08 14:31:46.968  1030  1370 D LGWifiP2pService: InactiveState
09-08 14:31:46.969  6239  6484 V FormManager: Network unavailable.
09-08 14:31:46.969  1030  1370 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.969  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.969  1030  1370 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-08 14:31:46.969  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 14:31:46.969  4152  6486 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:31:46.970  6459  6459 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:46.970  1924  6485 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 14:31:46.970  1030  6480 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 14:31:46.970  1030  6480 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:46.970  1030  6480 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:46.971  1030  6480 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:31:46.971  6459  6459 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 14:31:46.971  6459  6459 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.971  1030  6480 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:46.971  1030  1370 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-08 14:31:46.971  1030  6480 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.971  1030  1370 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.971  1030  6480 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.971  1030  6480 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.971  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 ob,j=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.971  1030  1370 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.971  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.971  1030  1370 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.971  6459  6459 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.971  1924  6485 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:46.972  1924  6485 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:46.972  1030  6480 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:31:46.972  1030  6480 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.972  1030  6480 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:31:46.972  1030  6480 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-08 14:31:46.976  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:46.976  1030  1370 D LGWifiP2pService: InactiveState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.977  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.977  1030  1370 D LGWifiP2pService: DefaultState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.978  1924  2250 W WfdsService: DefaultState - msg [9441285] is not handled
09-08 14:31:46.978  1030  1370 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.978  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.978  1030  1370 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.978  1030  1370 D LGWifiP2pService: InactiveState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.979  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.979  1030  1370 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:46.979  1030  1030 E WifiServerServiceExt: No p2p device connected
09-08 14:31:46.982  4152  6487 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:31:46.982  4152  6487 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:31:46.986  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:46.990  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:46.995  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:46.995  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:46.996  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 14:31:46.999  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:31:47.004  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:47.008  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:47.012  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:47.012  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:47.013  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 14:31:47.141  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:47.144  1030  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:47.147  1030  1112 D Tethering: MasterInitialState.processMessage what=3
09-08 14:31:47.153  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:47.156  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:47.157  1030  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:47.159  5352  5352 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-08 14:31:47.159  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-08 14:31:47.164  5224  5252 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 14:31:47.183  1030  1101 E GpsLocationProvider: No APN found to select.
,09-08 14:31:47.222  2187  2187 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:47.292  5982  6084 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 14:31:47.298  1030  1941 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6490 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-08 14:31:47.452  6490  6490 I AppUp4:AppBoxCP: onCreate
,09-08 14:31:47.453  6490  6490 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-08 14:31:47.463  6490  6490 I AppUp4:DB:  setFingerPrint start
09-08 14:31:47.464  6490  6490 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-08 14:31:47.473  6490  6490 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-08 14:31:47.473  6490  6490 I AppUp4:DB:  SDK version = 21
09-08 14:31:47.473  6490  6490 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-08 14:31:47.475  6490  6490 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-08 14:31:47.476  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 14:31:47.476  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:47.479  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 14:31:47.479  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 14:31:47.486  6490  6490 I AppUp4:CustModeStarterReceiver: onReceive
,09-08 14:31:47.539  6490  6490 D LgDataFeature: LgDataFeature() Constructor: none
09-08 14:31:47.539  6490  6490 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 14:31:47.547  6490  6490 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1e7c3037
09-08 14:31:47.547  6490  6490 D AppUp4:CustFacade: isCustomizationCompleted : false
,09-08 14:31:47.547  6490  6490 D AppUp4:CustFacade: isPhone : true
09-08 14:31:47.548  6490  6490 D AppUp4:CustModeStarterReceiver: begin check event
09-08 14:31:47.548  6490  6490 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-08 14:31:47.549  6490  6490 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-08 14:31:47.568  6490  6511 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-08 14:31:47.568  6490  6511 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-08 14:31:47.569  6490  6511 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-08 14:31:47.578  1030  1904 I ActivityManager: Killing 5803:com.android.contacts/u0a19 (adj 15): empty #17
09-08 14:31:47.613  1030  1995 W libprocessgroup: failed to open /acct/uid_10019/pid_5803/cgroup.procs: No such file or directory
,09-08 14:31:47.615  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:47.615  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:31:47.617  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:31:47.619  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:31:47.625  4152  6516 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 14:31:47.632  4152  6517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:47.632  4152  6517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:31:47.665  5829  5829 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-08 14:31:47.730  3281  3281 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 14:31:47.731  3281  3281 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:47.736  6239  6520 W FormManager: Network not available. Please check & try again.
09-08 14:31:47.740  6239  6521 V FormManager: Network unavailable.
09-08 14:31:47.742  3281  3281 I LgeMiscReceiver: networkInfo.isConnected() = true
09-08 14:31:47.742  3281  3281 D PhoneState: setPdpRejectCasuse : false
09-08 14:31:47.746  5829  5829 I HubEmail: JNI_OnLoad()
09-08 14:31:47.746  5829  5829 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:31:47.746  5829  5829 I HubEmail: registerNatives()
09-08 14:31:47.746  5829  5829 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:31:47.746  5829  5829 I HubEmail: registerNativeMethods()
09-08 14:31:47.746  5829  5829 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,09-08 14:31:47.751  5829  5829 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-08 14:31:47.782  1030  1886 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6523 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-08 14:31:47.788  6239  6521 V FormManager: Network unavailable.
09-08 14:31:47.800  5829  6522 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:31:47.899  6523  6523 D LgDataFeature: LgDataFeature() Constructor: none
09-08 14:31:47.899  6523  6523 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 14:31:47.905  6523  6523 D PhoneMonitor: Register our PhoneStateListener
,09-08 14:31:47.929  6523  6523 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-08 14:31:47.934  6523  6523 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-08 14:31:47.954  6523  6523 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-08 14:31:47.957  6523  6523 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-08 14:31:47.958  6523  6523 D TelephonyAutoProfiling: [parse] Load xml
,09-08 14:31:47.963  6523  6523 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-08 14:31:47.963  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-08 14:31:47.963  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-08 14:31:47.963  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-08 14:31:47.963  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-08 14:31:47.963  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-08 14:31:47.963  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-08 14:31:47.963  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-08 14:31:47.963  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-08 14:31:47.963  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-08 14:31:47.963  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-08 14:31:47.963  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-08 14:31:47.964  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-08 14:31:47.964  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-08 14:31:47.964  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-08 14:31:47.964  6523  6523 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-08 14:31:47.964  6523  6523 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-08 14:31:47.971  6523  6523 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-08 14:31:48.001  1030  1886 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6548 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:31:48.002  1030  1886 I ActivityManager: Killing 5861:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-08 14:31:48.052  1030  1749 W libprocessgroup: failed to open /acct/uid_10027/pid_5861/cgroup.procs: No such file or directory
,09-08 14:31:48.378  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:48.383  1030  1112 D Tethering: MasterInitialState.processMessage what=3
,09-08 14:31:48.384  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:48.391  1030  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:48.397  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:48.400  1030  1112 D Tethering: MasterInitialState.processMessage what=3
09-08 14:31:48.402  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:48.403  5352  5352 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-08 14:31:48.407  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:48.409  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:48.412  1030  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:48.412  1030  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:48.412  1030  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:48.416  5352  5352 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-08 14:31:48.463  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-08 14:31:48.463  1030  6480 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-08 14:31:48.463  6459  6459 E wpa_supplicant: USIM:  scard_init function
09-08 14:31:48.463  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-08 14:31:48.464  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
09-08 14:31:48.464  1030  6480 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-08 14:31:48.464  6459  6459 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-08 14:31:48.468  1030  1408 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-08 14:31:48.468  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-08 14:31:48.468  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-08 14:31:48.468  1030  1408 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-08 14:31:48.469  1030  1408 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-08 14:31:48.469  1030  1408 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-08 14:31:48.469  1030  1408 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-08 14:31:48.507  1030  1886 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6570 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-08 14:31:48.510  1030  1886 I ActivityManager: Killing 5929:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-08 14:31:48.566  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121052  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-08 14:31:48.569  1030  1749 W libprocessgroup: failed to open /acct/uid_10061/pid_5929/cgroup.procs: No such file or directory
09-08 14:31:48.571  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121058  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-08 14:31:48.576  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:48.576  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:48.577  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:48.579  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:48.579  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:48.580  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:31:48.580  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:48.580  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-08 14:31:48.607  6570  6570 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
09-08 14:31:48.609  6570  6570 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,09-08 14:31:48.618  6570  6570 V DrmService: Service onCreate
09-08 14:31:48.618  6570  6570 D DrmService: Received new request = 2
09-08 14:31:48.624  6570  6593 I DrmSntpClient: Start Sync process
09-08 14:31:48.625  6570  6593 D DrmSntpClient: Server : 0
,09-08 14:31:48.674  1030  1995 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6594 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:31:48.677  6570  6593 D DrmSntpClient: Automatic sync but WiFi isn't enabled
09-08 14:31:48.678  6570  6570 D DrmService: Completed !! request = 2
09-08 14:31:48.678  6570  6570 D DrmService: Request count = 0
,09-08 14:31:48.680  6570  6570 V DrmService: Service onDestroy
09-08 14:31:48.683  1030  1904 I ActivityManager: Killing 6043:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-08 14:31:48.722  1030  1637 W libprocessgroup: failed to open /acct/uid_10080/pid_6043/cgroup.procs: No such file or directory
,09-08 14:31:48.754  6594  6594 I art     : Almond Protected OAT
,09-08 14:31:48.827  6594  6594 D WeatherApplication: removeAccount
,09-08 14:31:48.829  6594  6594 D WeatherApplication: Account.length = 0
,09-08 14:31:48.830  6594  6594 E WeatherApplication: OPERATOR:OPEN
09-08 14:31:48.837  6594  6594 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:48
09-08 14:31:48.841  6594  6594 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 14:31:48.841  6594  6594 D Weather.Utils: 2 : All the weather widget is gone.
,09-08 14:31:48.843  6594  6594 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-08 14:31:48.848  6594  6594 D WeatherAncestor: connectivity changed - connection : true
,09-08 14:31:48.849  6594  6594 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-08 14:31:48.862  6594  6594 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-08 14:31:48.862  6594  6594 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 14:31:48.862  6594  6594 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-08 14:31:48.886  6594  6594 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,09-08 14:31:48.887  6594  6594 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:48
,09-08 14:31:48.944  1030  1994 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6612 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:31:48.948  1030  1994 I ActivityManager: Killing 6065:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-08 14:31:48.971   344   344 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 527us total 26.265ms
,09-08 14:31:48.993   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 20.885ms
,09-08 14:31:49.015   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 616us total 21.103ms
,09-08 14:31:49.022  1030  1941 W libprocessgroup: failed to open /acct/uid_10097/pid_6065/cgroup.procs: No such file or directory
09-08 14:31:49.126   278   450 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:31:49.127   278   450 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,09-08 14:31:49.127   278   450 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:31:49.128  6612  6630 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 14:31:49.131   278   450 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:31:49.131   278   450 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 14:31:49.132   278   450 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:31:49.132  6612  6630 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 14:31:49.146   278   450 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:31:49.146   278   450 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,09-08 14:31:49.146   278   450 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:31:49.147  6612  6632 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 14:31:49.153   278   450 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:31:49.153   278   450 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 14:31:49.153   278   450 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:31:49.154  6612  6632 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 14:31:49.259  6161  6388 D UEI.SmartControl: Internal timer expired: 2
09-08 14:31:49.260  6161  6388 D UEI.SmartControl: unbind internal service
,09-08 14:31:49.419  6161  6385 D serial_port: close(fd = 24)
,09-08 14:31:49.424  6161  6385 I UEI.SmartControl: Serial port is closed.
09-08 14:31:49.432  6612  6612 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-08 14:31:49.445  6612  6612 I LibraryLoader: Loading: webviewchromium
,09-08 14:31:49.448  6612  6612 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 1942-1947)
,09-08 14:31:49.449  6612  6612 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 14:31:49.458  6612  6612 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bff1940}
09-08 14:31:49.460  6612  6612 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 14:31:49.460  6612  6612 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 14:31:49.474  6612  6612 I BrowserStartupController: Initializing chromium process, renderers=0
09-08 14:31:49.475  6612  6612 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 14:31:49.507   312  2145 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10093
,09-08 14:31:49.508  6612  6612 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-08 14:31:49.510  6612  6612 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,09-08 14:31:49.510  6612  6654 W AudioManagerAndroid: Requires BLUETOOTH permission
09-08 14:31:49.510  6612  6612 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-08 14:31:49.530  6612  6612 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:31:49.530  6612  6612 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:31:49.530  6612  6612 I Adreno-EGL: Build Date: 12/12/14 금
09-08 14:31:49.530  6612  6612 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 14:31:49.530  6612  6612 I Adreno-EGL: Remote Branch: 
09-08 14:31:49.530  6612  6612 I Adreno-EGL: Local Patches: 
09-08 14:31:49.530  6612  6612 I Adreno-EGL: Reconstruct Branch: 
,09-08 14:31:49.636  6612  6612 I NSApplication: Starting up...
,09-08 14:31:49.718  1030  1046 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6667 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-08 14:31:49.722  1030  1994 I ActivityManager: Killing 6102:com.lge.eula/1000 (adj 15): empty #17
09-08 14:31:49.774  1030  1905 W libprocessgroup: failed to open /acct/uid_1000/pid_6102/cgroup.procs: No such file or directory
,09-08 14:31:49.809  6667  6667 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:31:50.125  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-08 14:31:50.126  5224  5252 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 14:31:50.146  2187  2187 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:50.157  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 14:31:50.157  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:50.157  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 14:31:50.157  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-08 14:31:50.161  6490  6490 I AppUp4:CustModeStarterReceiver: onReceive
09-08 14:31:50.164  6490  6490 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1e7c3037
09-08 14:31:50.164  6490  6490 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 14:31:50.164  6490  6490 D AppUp4:CustFacade: isPhone : true
09-08 14:31:50.165  6490  6490 D AppUp4:CustModeStarterReceiver: begin check event
09-08 14:31:50.165  6490  6490 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 14:31:50.169  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:50.169  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:31:50.171  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:31:50.174  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:31:50.181  5829  5829 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-08 14:31:50.182  4152  6695 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 14:31:50.192  4152  6696 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:50.192  4152  6696 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:31:50.217  5829  6703 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:31:50.220  3281  3281 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 14:31:50.220  3281  3281 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:50.220  3281  3281 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 14:31:50.223  6523  6523 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 14:31:50.223  6523  6523 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 14:31:50.235  6239  6706 W FormManager: Network not available. Please check & try again.
,09-08 14:31:50.239  6594  6594 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:50
09-08 14:31:50.241  6239  6707 V FormManager: Network unavailable.
09-08 14:31:50.242  6594  6594 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 14:31:50.242  6594  6594 D Weather.Utils: 2 : All the weather widget is gone.
09-08 14:31:50.244  6594  6594 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:31:50.244  6594  6594 D WeatherAncestor: connectivity changed - connection : true
09-08 14:31:50.244  6594  6594 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a9af30d
09-08 14:31:50.245  6239  6707 V FormManager: Network unavailable.
09-08 14:31:50.251  6594  6594 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 14:31:50.251  6594  6594 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 14:31:50.251  6594  6594 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 14:31:50.251  6594  6594 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 14:31:50.251  6594  6594 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:50
,09-08 14:31:50.331  1030  1370 D LGWifiP2pService: InactiveState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.331  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.331  1030  1370 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 14:31:50.370  1030  1408 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-08 14:31:50.370  1030  1408 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 14:31:50.371  1030  1408 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 14:31:50.371  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 14:31:50.372  1030  1408 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 14:31:50.424  1030  1046 I art     : Explicit concurrent mark sweep GC freed 155041(7MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 4.580ms total 176.957ms
,09-08 14:31:50.468  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-08 14:31:50.470  5224  5252 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 14:31:50.488  2187  2187 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:50.495  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 14:31:50.495  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:50.495  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 14:31:50.495  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 14:31:50.496  6490  6490 I AppUp4:CustModeStarterReceiver: onReceive
,09-08 14:31:50.500  6490  6490 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1e7c3037
09-08 14:31:50.500  6490  6490 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 14:31:50.500  6490  6490 D AppUp4:CustFacade: isPhone : true
09-08 14:31:50.501  6490  6490 D AppUp4:CustModeStarterReceiver: begin check event
09-08 14:31:50.501  6490  6490 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 14:31:50.504  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:50.505  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:31:50.507  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 14:31:50.510  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:31:50.514  4152  6719 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:31:50.515  4152  6720 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:50.515  4152  6720 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:31:50.516  5829  5829 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-08 14:31:50.528  6459  6459 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT bssid=f4:f2:6d:22:99:3e status_code=1
09-08 14:31:50.529  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=f4:f2:6d:22:99:3e status_code=1]
09-08 14:31:50.529  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=f4:f2:6d:22:99:3e status_code=1
09-08 14:31:50.529  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
09-08 14:31:50.529  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
,09-08 14:31:50.530  1030  1408 E WifiStateMachine:  DisconnectedState ASSOCIATION_REJECTION_EVENT 35 1 f4:f2:6d:22:99:3e blacklist=false rt=123017
09-08 14:31:50.531  1030  1408 E WifiStateMachine:  ConnectModeState ASSOCIATION_REJECTION_EVENT 35 1 f4:f2:6d:22:99:3e blacklist=false rt=123017
09-08 14:31:50.532  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123018  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
09-08 14:31:50.533  1030  1030 D WifiHS20: hidePasspointNotification off =false
09-08 14:31:50.534  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:50.534  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:50.535  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:50.536  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:50.536  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:50.536  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:50.537  5829  6721 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:50.541  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123028  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
,09-08 14:31:50.544  3281  3281 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-08 14:31:50.544  3281  3281 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:50.545  3281  3281 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 14:31:50.545  6239  6723 W FormManager: Network not available. Please check & try again.
09-08 14:31:50.546  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:50.546  1030  1030 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-08 14:31:50.550  6523  6523 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 14:31:50.550  6523  6523 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 14:31:50.559  6239  6724 V FormManager: Network unavailable.
,09-08 14:31:50.561  6594  6594 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:50
09-08 14:31:50.563  6239  6724 V FormManager: Network unavailable.
09-08 14:31:50.563  6594  6594 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 14:31:50.563  6594  6594 D Weather.Utils: 2 : All the weather widget is gone.
09-08 14:31:50.563  6594  6594 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:31:50.563  6594  6594 D WeatherAncestor: connectivity changed - connection : true
09-08 14:31:50.563  6594  6594 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a9af30d
09-08 14:31:50.564  6594  6594 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 14:31:50.564  6594  6594 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 14:31:50.564  6594  6594 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 14:31:50.564  6594  6594 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 14:31:50.564  6594  6594 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:50
09-08 14:31:50.583  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-08 14:31:50.588  6213  6213 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-08 14:31:50.592  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:50.603  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:50.609  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:50.624  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:50.624  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 14:31:50.625  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:50.629  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-08 14:31:50.630  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 14:31:50.630  6459  6459 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-08 14:31:50.631  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-08 14:31:50.631  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-08 14:31:50.631  1030  6480 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-08 14:31:50.631  1030  6480 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-08 14:31:50.631  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123118  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 14:31:50.636  1030  1030 D WifiHS20: hidePasspointNotification off =false
09-08 14:31:50.638  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:50.638  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:50.637  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:31:50.641  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:50.642  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:50.643  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:50.643  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:50.644  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123131  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 14:31:50.648  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:50.649  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:50.649  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:31:50.652  6262  6262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:31:50.652  6262  6262 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:50.652  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:50.653  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:50.653  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-08 14:31:50.660  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:50.663  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:50.663  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:50.664  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:31:50.670  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:50.676  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 14:31:50.677  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:50.678  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 14:31:50.684  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:50.687  6262  6262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:31:50.687  6262  6262 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:50.687  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:50.690  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:50.697  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:50.704  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 14:31:50.705  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:50.707  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 14:31:50.713  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:50.723  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:50.731  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 14:31:50.745  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:50.746  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:50.748  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 14:31:51.485  3723  3968 W bt-l2cap: L2CAP - st: CLOSED evt: 1
,09-08 14:31:51.485  3723  3968 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-08 14:31:51.485  3723  3968 E bt-btif : DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,09-08 14:31:51.495  3723  4133 W bt-btif : invalid rfc slot id: 7
09-08 14:31:51.496  5982  6419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 764)
09-08 14:31:52.317  1030  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:52.318  1030  1994 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1ceef015 mBinding = false
,09-08 14:31:52.361  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:31:52.362  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:31:52.362  1030  1030 D Ulp_jni : JNI:system_update. Event-4
09-08 14:31:52.363  1030  1112 D BluetoothManagerService: Message: 2
09-08 14:31:52.364  1030  1112 D BluetoothManagerService: Sending off request.
09-08 14:31:52.365  3723  3741 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-08 14:31:52.365  3723  3836 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-08 14:31:52.365  3723  3836 D BluetoothAdapterProperties: Setting state to 13
09-08 14:31:52.365  3723  3836 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 14:31:52.366  3723  3836 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 14:31:52.366  3723  3836 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-08 14:31:52.372  3723  3842 D BluetoothAdapterProperties: Scan Mode:20
,09-08 14:31:52.377  3723  3836 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-08 14:31:52.380  3723  4139 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-08 14:31:52.380  3723  4139 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 14:31:52.380  3723  4139 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-08 14:31:52.380  3723  4139 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-08 14:31:52.380  3723  4139 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-08 14:31:52.380  3723  4139 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-08 14:31:52.380  3723  4139 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-08 14:31:52.380  3723  4139 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-08 14:31:52.381  3723  4143 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 14:31:52.381  3723  4229 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 14:31:52.381  3723  4231 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 14:31:52.382  3723  4192 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 14:31:52.382  3723  3836 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-08 14:31:52.387  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
,09-08 14:31:52.390  3723  3968 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-08 14:31:52.393  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 14:31:52.393  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 14:31:52.393  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 14:31:52.393  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 14:31:52.393  3723  3968 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:31:52.393  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 14:31:52.393  3723  3968 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:31:52.393  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 14:31:52.393  3723  3968 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 14:31:52.393  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-08 14:31:52.393  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-08 14:31:52.393  3723  3968 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-08 14:31:52.395  5982  5982 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:52.396  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:52.396  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:52.396  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:52.396  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:52.396  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:31:52.396  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:52.396  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:52.396  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:52.397  5982  5982 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:52.397  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:52.403  5982  5982 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:52.403  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:52.403  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:52.403  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:52.403  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:52.403  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:31:52.403  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:52.403  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:52.403  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:31:52.415  5982  5982 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:52.415  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:31:52.422  1030  1112 D BluetoothManagerService: Message: 60
,09-08 14:31:52.422  1030  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-08 14:31:52.422  1030  1112 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-08 14:31:52.504  1030  1104 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6737 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-08 14:31:52.517  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:52.520  1584  1584 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-08 14:31:52.524  3723  3723 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:52.525  3723  3723 D BluetoothMapService: STATE_TURNING_OFF
09-08 14:31:52.525  3723  3723 V BluetoothMapService: Handler(): got msg=4
09-08 14:31:52.525  3723  3723 D BluetoothMapService: MAP Service closeService in
09-08 14:31:52.525  3723  3723 D BluetoothMapMasInstance: MAP Service shutdown
09-08 14:31:52.525  3723  3723 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 14:31:52.525  3723  3723 V BluetoothMapService: MAP Service closeService out
09-08 14:31:52.526  3723  3723 V BtOppService: Receiver DISABLED_ACTION 
09-08 14:31:52.526  3723  3723 I BtOppRfcommListener: stopping Accept Thread
09-08 14:31:52.526  3723  3723 V BtOppRfcommListener: close mBtServerSocket
09-08 14:31:52.526  3723  3723 V BtOppRfcommListener: waiting for thread to terminate
09-08 14:31:52.527  3723  4192 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 14:31:52.528  3723  3723 V BtOppRfcommListener: done waiting for thread to terminate
09-08 14:31:52.531  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:52.533  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:52.538  3723  3723 V BtOppService: onDestroy
09-08 14:31:52.539  3723  3723 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-08 14:31:52.547  6213  6213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-08 14:31:52.553  3723  3723 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-08 14:31:52.555  3723  3723 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:52.555  3723  3723 V BluetoothPbapReceiver: ***********state = 13
09-08 14:31:52.562  3723  3723 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-08 14:31:52.564  1030  1112 D BluetoothManagerService: Message: 20
09-08 14:31:52.564  1030  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e8452b8:true
09-08 14:31:52.565  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 14:31:52.565  3723  3723 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:52.565  3723  3723 V BluetoothPbapService: state: 13
09-08 14:31:52.565  3723  3723 V BluetoothPbapService: Pbap Service closeService in
,09-08 14:31:52.566  3723  3723 V BluetoothPbapService: successfully stopped pbap service
09-08 14:31:52.566  3723  3723 V BluetoothPbapService: Pbap Service closeService out
09-08 14:31:52.567  3723  3723 V BluetoothPbapService: Pbap Service onDestroy
09-08 14:31:52.567  3723  3723 V BluetoothPbapService: Pbap Service closeService in
09-08 14:31:52.567  3723  3723 V BluetoothPbapService: Pbap Service closeService out
09-08 14:31:52.567  3723  3723 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-08 14:31:52.578  1030  1112 D BluetoothManagerService: Message: 30
,09-08 14:31:52.587  1030  1112 D BluetoothManagerService: Message: 30
09-08 14:31:52.590  6213  6213 D LocalBluetoothProfileManager: Adding local MAP profile
09-08 14:31:52.592  6213  6213 D BluetoothMap: Create BluetoothMap proxy object
09-08 14:31:52.592  1030  1112 D BluetoothManagerService: Message: 30
09-08 14:31:52.596  1030  1112 D BluetoothManagerService: Message: 30
,09-08 14:31:52.598  6213  6213 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-08 14:31:52.599  6213  6213 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-08 14:31:52.614  6213  6213 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-08 14:31:52.616  6213  6213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-08 14:31:52.623  6213  6213 D DockEventReceiver: finishStartingService: stopping service
09-08 14:31:52.624  6213  6213 D BluetoothInputDevice: Proxy object connected
09-08 14:31:52.625  6213  6213 D HidProfile: Bluetooth service connected
09-08 14:31:52.625  6213  6213 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 14:31:52.626  6213  6213 D PanProfile: Bluetooth service connected
09-08 14:31:52.626  6213  6213 D BluetoothMap: Proxy object connected
09-08 14:31:52.627  6213  6213 D MapProfile: Bluetooth service connected
09-08 14:31:52.627  6213  6213 D BluetoothMap: getConnectedDevices()
09-08 14:31:52.627  6213  6213 D BluetoothMap: Bluetooth is Not enabled
09-08 14:31:52.627  6213  6213 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-08 14:31:52.642  6737  6737 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-08 14:31:52.642  6737  6737 W LG Account v2.2: No ProfileInfo entries
09-08 14:31:52.642  6737  6737 I LG Account v2.2: isEnabled: false
09-08 14:31:52.642  6737  6737 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-08 14:31:52.642  6737  6737 I Feature : [Lifetracker]Country: EU
09-08 14:31:52.642  6737  6737 I Feature : [Lifetracker]Operator: OPEN
09-08 14:31:52.642  6737  6737 I Feature : [Lifetracker]Ranking support: false
09-08 14:31:52.643  6737  6737 I Feature : [Lifetracker]Comfort support: false
09-08 14:31:52.643  6737  6737 I Feature : [Lifetracker]Accessory: true
09-08 14:31:52.643  6737  6737 I Feature : [Lifetracker]Health device: true
09-08 14:31:52.643  6737  6737 I Feature : [Lifetracker]Extra Pedometer: false
09-08 14:31:52.643  6737  6737 I Feature : [Lifetracker]Blood glucose device: false
09-08 14:31:52.643  6737  6737 I Feature : [Lifetracker]Device Number: 3
09-08 14:31:52.648  6213  6213 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-08 14:31:52.651  6213  6213 D BluetoothPermissionRequest: onReceive
09-08 14:31:52.654  6213  6213 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-08 14:31:52.661  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 14:31:52.663  1030  1941 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
09-08 14:31:52.683   312  1378 V AudioFlinger: 2127 died, releasing its sessions
09-08 14:31:52.683   312  1378 V AudioFlinger:  pid 1835 @ 0
09-08 14:31:52.683   312  1378 V AudioFlinger:  pid 3281 @ 1
09-08 14:31:52.683   312  1378 V AudioFlinger:  pid 3281 @ 2
,09-08 14:31:52.762  1030  1995 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
09-08 14:31:52.762  3723  3723 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-08 14:31:52.763  3723  3723 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-08 14:31:52.765  3723  3723 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-08 14:31:52.779  3723  3723 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:52.779  3723  3723 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-08 14:31:52.782  3723  3723 V BluetoothFtpService: Ftp Service onStartCommand
09-08 14:31:52.782  3723  3723 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:52.783  3723  3723 V BluetoothFtpService: Ftp Service closeService
09-08 14:31:52.783  3723  3723 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-08 14:31:52.791  3723  3723 V BluetoothFtpService: successfully stopped ftp service
09-08 14:31:52.793  3723  3723 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 14:31:52.793  3723  3723 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 14:31:52.793  3723  3723 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 14:31:52.794  3723  3723 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:52.794  3723  3723 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-08 14:31:52.794  3723  3723 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-08 14:31:52.798  3723  3723 V BluetoothFtpService: Ftp Service onDestroy
09-08 14:31:52.798  3723  3723 V BluetoothFtpService: Ftp Service closeService
09-08 14:31:52.873  1030  1994 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6784 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 14:31:52.874  3723  3723 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:31:52.874  3723  3723 V BluetoothSapService: state: 13
09-08 14:31:52.874  3723  3723 V BluetoothSapService: Stopping SAP server process
09-08 14:31:52.876  3723  3723 V BluetoothSapService: Sap Service closeSapService in
09-08 14:31:52.876  3723  3723 V BluetoothSapService: Close listen Socket : 
09-08 14:31:52.876  3723  3723 V BluetoothSapService: Close rfcomm Socket : 
09-08 14:31:52.876  3723  3723 V BluetoothSapService: Close sapd  Socket : 
09-08 14:31:52.878  3723  3723 V BluetoothSapService: Sap Service closeSapService out
09-08 14:31:52.878  3723  3723 V BluetoothSapService: Sap Service onDestroy
09-08 14:31:52.878  3723  3723 V BluetoothSapService: Sap Service closeSapService in
09-08 14:31:52.878  3723  3723 V BluetoothSapService: Close listen Socket : 
09-08 14:31:52.878  3723  3723 V BluetoothSapService: Close rfcomm Socket : 
09-08 14:31:52.878  3723  3723 V BluetoothSapService: Close sapd  Socket : 
09-08 14:31:52.879  3723  3723 V BluetoothSapService: Sap Service closeSapService out
,09-08 14:31:52.966  6784  6784 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 14:31:52.991  1030  1749 I ActivityManager: Killing 5886:com.android.vending/u0a44 (adj 15): empty #17
,09-08 14:31:53.053  1030  1904 W libprocessgroup: failed to open /acct/uid_10044/pid_5886/cgroup.procs: No such file or directory
,09-08 14:31:53.399  3723  3842 D bt_hci_bdroid: cleanup
,09-08 14:31:53.406  3723  3970 I bt_lpm  : LPM is already off!!!
09-08 14:31:53.407  3723  4115 I bt_userial_mct: exiting userial_read_thread
09-08 14:31:53.407  3723  4115 D bt_userial_mct: Leaving userial_evt_read_thread()
09-08 14:31:53.408  3723  3968 W bt-btif : ag scb idx 1 not allocated
09-08 14:31:53.408  3723  3968 E bt-btif : BTA AG is already disabled, ignoring ...
09-08 14:31:53.408  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 14:31:53.408  3723  3968 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:31:53.408  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 14:31:53.408  3723  3968 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 14:31:53.409  3723  3968 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 14:31:53.409  3723  3968 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-08 14:31:53.412  3723  3842 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-08 14:31:53.413  3723  3970 I bt_vendor: hw_epilog_process
09-08 14:31:53.413  3723  3842 D bt_hci_bdroid: cleanup Finalizing cleanup
09-08 14:31:53.413  3723  3842 D bt_userial_mct: userial_close
09-08 14:31:53.413  3723  3842 E bt_userial_mct: pthread_join() FAILED result:3
09-08 14:31:53.413  3723  3842 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-08 14:31:53.422  3723  3842 D bt_hci_bdroid: set_power 0
09-08 14:31:53.422  3723  3842 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-08 14:31:53.422  3723  3842 I bt_vendor: bluetooth satus is on
,09-08 14:31:53.422  3723  3842 I bt_vendor: bt-vendor : resetting BT status
09-08 14:31:53.426  3723  3842 I bt_vendor: Starting hciattach daemon
09-08 14:31:53.426  3723  3842 I bt_vendor: try to set false
09-08 14:31:53.428  3723  3842 I bt_vendor: Starting hciattach daemon
09-08 14:31:53.428  3723  3842 I bt_vendor: try to set false
09-08 14:31:53.430  3723  3842 I bt_vendor: cleanup
09-08 14:31:53.431  3723  3968 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-08 14:31:53.431  3723  3842 I GKI_LINUX: GKI_exit_task 0 done
09-08 14:31:53.431  3723  3842 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-08 14:31:53.433  3723  3836 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-08 14:31:53.439  3723  3723 D HeadsetService: Received stop request...Stopping profile...
,09-08 14:31:53.443  3723  3723 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-08 14:31:53.443  3723  3723 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 14:31:53.444  3723  3723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131b79a4
09-08 14:31:53.444  3723  3887 D HeadsetStateMachine: Exit Disconnected: -1
09-08 14:31:53.447  1030  1030 D BluetoothHeadset: Proxy object disconnected
09-08 14:31:53.447  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-08 14:31:53.448  1835  1835 D BluetoothHeadset: Proxy object disconnected
09-08 14:31:53.449  1835  1835 D BluetoothHeadset: Proxy object disconnected
09-08 14:31:53.449  1835  1835 D BluetoothHeadset: Proxy object disconnected
09-08 14:31:53.451  3723  3723 D A2dpService: Received stop request...Stopping profile...
,09-08 14:31:53.454  3723  3928 D A2dpStateMachine: Exit Disconnected: -1
09-08 14:31:53.456  3723  3723 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-08 14:31:53.456  3723  3836 D BluetoothAdapterState: Stopping profile services that were post enabled
09-08 14:31:53.457  3723  3723 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-08 14:31:53.457  3723  3723 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 14:31:53.457  3723  3723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131b79a4
09-08 14:31:53.460  3723  3723 D HidService: Received stop request...Stopping profile...
09-08 14:31:53.460  3723  3723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131b79a4
09-08 14:31:53.460  1030  1030 D BluetoothA2dp: Proxy object disconnected
09-08 14:31:53.460  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-08 14:31:53.461  3723  3723 D HealthService: Received stop request...Stopping profile...
09-08 14:31:53.462  3723  3723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131b79a4
09-08 14:31:53.464  3723  3723 D PanService: Received stop request...Stopping profile...
,09-08 14:31:53.467  3723  3723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131b79a4
09-08 14:31:53.470  3723  3723 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 14:31:53.470  3723  3723 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 14:31:53.470  3723  3723 D BtGatt.GattService: stop()
09-08 14:31:53.470  3723  3723 D BtGatt.AdvertiseManager: advertise clients cleared
09-08 14:31:53.471  3723  3723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131b79a4
09-08 14:31:53.473  3723  3723 D HeadsetStateMachine: Unbinding service...
09-08 14:31:53.475  3723  3723 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 14:31:53.475  3723  3723 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 14:31:53.475  3723  3723 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 14:31:53.475  3723  3723 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 14:31:53.475  3723  3723 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 14:31:53.475  3723  3723 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 14:31:53.475  3723  3723 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-08 14:31:53.477  3723  3723 D BluetoothMapService: Received stop request...Stopping profile...
09-08 14:31:53.477  3723  3723 D BluetoothMapService: stop()
,09-08 14:31:53.480  3723  3723 D BluetoothMapEmailAppObserver: deinitObservers()
09-08 14:31:53.480  3723  3723 D BluetoothMapEmailAppObserver: removeReceiver()
09-08 14:31:53.481  3723  3723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@131b79a4
09-08 14:31:53.482  3723  3723 V BluetoothMapService: Handler(): got msg=4
09-08 14:31:53.482  3723  3723 D BluetoothMapService: MAP Service closeService in
09-08 14:31:53.482  3723  3723 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 14:31:53.482  3723  3723 V BluetoothMapService: MAP Service closeService out
09-08 14:31:53.483  3723  3836 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-08 14:31:53.483  3723  3836 D BluetoothAdapterProperties: Setting state to 10
09-08 14:31:53.483  3723  3836 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-08 14:31:53.484  1030  1112 D BluetoothManagerService: Message: 60
09-08 14:31:53.484  1030  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-08 14:31:53.484  1030  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-08 14:31:53.485  3723  3836 I BluetoothAdapterState: Entering OffState
09-08 14:31:53.485  1835  3409 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:31:53.486  6213  6234 D BluetoothPan: onBluetoothStateChange on: false
09-08 14:31:53.486  1030  1112 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 14:31:53.487  1835  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 14:31:53.488  6213  6234 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 14:31:53.488  6213  6234 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 14:31:53.493  6213  6234 D BluetoothMap: onBluetoothStateChange: up=false
09-08 14:31:53.496  3723  3723 I BluetoothA2dpServiceJni: cleanupNative
09-08 14:31:53.496  3723  3929 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-08 14:31:53.497  3723  3723 I GKI_LINUX: GKI_exit_task 2 done
09-08 14:31:53.497  3723  3723 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-08 14:31:53.498  1030  1112 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:31:53.499  3723  3723 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 14:31:53.499  3723  3723 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 14:31:53.499  1835  3410 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:31:53.500  3723  3723 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-08 14:31:53.502  3723  3723 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 14:31:53.502  3723  3723 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 14:31:53.504  3723  3723 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 14:31:53.504  3723  3723 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 14:31:53.507  1030  1112 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-08 14:31:53.507  1030  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-08 14:31:53.507  3723  3723 D BluetoothMapService: cleanup()
09-08 14:31:53.507  3723  3723 D BluetoothMapService: MAP Service closeService in
09-08 14:31:53.507  3723  3723 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 14:31:53.507  3723  3723 V BluetoothMapService: MAP Service closeService out
09-08 14:31:53.510  1030  1112 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-08 14:31:53.510  1030  1112 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-08 14:31:53.510  1030  1112 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1ceef015 mBinding = false
09-08 14:31:53.514  1030  1112 D BluetoothManagerService: Sending unbind request.
,09-08 14:31:53.525  3723  3842 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-08 14:31:53.527  3723  3723 I GKI_LINUX: GKI_exit_task 1 done
09-08 14:31:53.527  3723  3723 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-08 14:31:53.528  3723  3723 I BluetoothServiceJni: cleanupNative: return from cleanup
09-08 14:31:53.528  3723  3723 I art     : --- WEIRD: removing null entry 246
09-08 14:31:53.528  3723  3723 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-08 14:31:53.529  3723  3723 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-08 14:31:53.530  3723  3723 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-08 14:31:53.531  1030  1112 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-08 14:31:53.533  3723  3723 I art     : System.exit called, status: 0
09-08 14:31:53.533  3723  3723 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-08 14:31:53.559   312  2145 V AudioFlinger: 3723 died, releasing its sessions
09-08 14:31:53.559   312  2145 V AudioFlinger:  pid 1835 @ 0
09-08 14:31:53.559  1924  1924 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-08 14:31:53.559   312  2145 V AudioFlinger:  pid 3281 @ 1
09-08 14:31:53.559   312  2145 V AudioFlinger:  pid 3281 @ 2
,09-08 14:31:53.559  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:53.560  1924  2103 D LGBluetoothAPIService: Message: 101
09-08 14:31:53.560  1924  2103 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-08 14:31:53.560  6213  6213 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-08 14:31:53.561  1924  2103 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-08 14:31:53.561  1924  2103 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-08 14:31:53.561  1924  2103 D LGBluetoothAPIService: Message: 2
09-08 14:31:53.562  1924  2103 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-08 14:31:53.567  6213  6213 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-08 14:31:53.568  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:53.569  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:53.569  6213  6213 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-08 14:31:53.569  6213  6213 D LGBluetoothEventManager: [BTUI] clear device connection state
09-08 14:31:53.570  1584  1584 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 14:31:53.572  6213  6213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-08 14:31:53.577  1584  1584 D BluetoothAdapter: 665013692: getState() :  mService = null. Returning STATE_OFF
09-08 14:31:53.577  1584  1584 D BluetoothAdapter: 665013692: getState() :  mService = null. Returning STATE_OFF
,09-08 14:31:53.622  1030  1749 I ActivityManager: Process com.android.bluetooth (pid 3723) has died
,09-08 14:31:53.622  1030  1749 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-08 14:31:53.623  1030  1749 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 11000ms
09-08 14:31:53.651  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-08 14:31:53.652  6459  6459 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-08 14:31:53.652  1030  6480 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-08 14:31:53.652  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,09-08 14:31:53.652  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: WPS-AP-AVAILABLE 
09-08 14:31:53.652  1030  6480 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-08 14:31:53.652  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-08 14:31:53.652  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-08 14:31:53.653  1030  1408 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
,09-08 14:31:53.653  1030  1408 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
09-08 14:31:53.654  1030  1408 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
09-08 14:31:53.654  1030  1408 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
09-08 14:31:53.654  1030  1408 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-08 14:31:53.669  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=126156  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-08 14:31:53.699  1030  1994 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6827 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-08 14:31:53.701  6213  6213 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:31:53.709  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:53.709  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:53.710  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.710  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.710  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:31:53.712  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:53.713  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=126200  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-08 14:31:53.717  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:31:53.719  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.719  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.719  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:31:53.719  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:53.720  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-08 14:31:53.727  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:53.736  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:53.739  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:53.739  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 14:31:53.740  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:53.745  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:53.746  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:53.749  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 14:31:53.752  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:31:53.769  6459  6459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-08 14:31:53.769  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:53.771  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,09-08 14:31:53.771  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-08 14:31:53.772  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-08 14:31:53.772  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-08 14:31:53.772  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:31:53.772  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:31:53.772  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=126259  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 14:31:53.773  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=126259  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 14:31:53.773  1030  1408 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 43 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126260
09-08 14:31:53.774  1030  1408 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 43 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126260
09-08 14:31:53.774  1030  1408 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 43 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126261
09-08 14:31:53.774  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 43 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126261
09-08 14:31:53.775  1030  1408 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 43 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126261
09-08 14:31:53.775  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=126262  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-08 14:31:53.776  1030  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 14:31:53.778  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:53.778  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:53.778  6827  6827 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-08 14:31:53.779  6827  6827 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 14:31:53.779  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:53.779  6827  6827 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-08 14:31:53.780  6827  6827 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-08 14:31:53.780  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.780  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.780  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:31:53.782  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=126268  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-08 14:31:53.782   308  6845 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-08 14:31:53.784  1030  1408 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:53.784  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.S,ettings.Global, returning read-only value.
09-08 14:31:53.784  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.784  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-08 14:31:53.784  1030  1408 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:53.784  1030  1408 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:53.785  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,09-08 14:31:53.785  1030  1408 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:31:53.786  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:53.786  1030  1030 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-08 14:31:53.787  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:31:53.787  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:31:53.787  6459  6459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:31:53.787  6459  6459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 14:31:53.788  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-08 14:31:53.788  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:31:53.788  1030  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-08 14:31:53.788  1030  6480 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:31:53.788  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-08 14:31:53.788  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 14:31:53.788  1030  6480 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 14:31:53.789  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:31:53.789  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:31:53.790  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=126276  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 14:31:53.790  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=126277  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 14:31:53.791  1030  1408 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=126278
09-08 14:31:53.791  1030  1408 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=126278
09-08 14:31:53.792  1030  1408 D WifiNative-wlan0: doString: [STATUS]
09-08 14:31:53.792  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:31:53.792  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:31:53.793  1030  1408 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-08 14:31:53.793  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:53.794  1030  1408 I WifiServiceExtension: setVHTCapabilityType  : false
09-08 14:31:53.799  1030  1408 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-08 14:31:53.799  1030  1408 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-08 14:31:53.799  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:53.799  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:53.799  6827  6827 D BluetoothAdapterApp: Loading JNI Library
09-08 14:31:53.800  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:53.805  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:53.805  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.805  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.805  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 14:31:53.805  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:53.805  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:53.807  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.807  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.807  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 14:31:53.808  1030  1408 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-08 14:31:53.808  1030  1464 D ConnectivityService: Got NetworkAgent Messenger
09-08 14:31:53.808  1030  1408 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:31:53.808  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 14:31:53.808  1030  1464 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 14:31:53.809  1030  1464 D ConnectivityService: NetworkAgent connected
09-08 14:31:53.809  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 14:31:53.809  1030  1408 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 14:31:53.810  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:31:53.814  1030  1408 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 14:31:53.814  1030  1408 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:31:53.814  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 14:31:53.814  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 14:31:53.814  1030  1408 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 14:31:53.816  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:53.819  1030  1408 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 14:31:53.820   308   888 D CommandListener: Setting iface cfg
09-08 14:31:53.820  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:53.820  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:53.821  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:53.822  1030  1408 E WifiStateMachine: Start Dhcp Watchdog 2
09-08 14:31:53.822  1030  1408 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=126309  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-08 14:31:53.823  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:53.823  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:53.823  1030  1408 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=126310  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:31:53.823  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=126310  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:31:53.824  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:53.824  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:31:53.825  1030  6847 D DhcpStateMachine: StoppedState
09-08 14:31:53.825  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:53.825  1030  6847 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:53.825  1030  1030 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-08 14:31:53.825  1030  6847 D DhcpStateMachine: WaitBeforeStartState
09-08 14:31:53.825  1030  1408 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=126312  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:31:53.826  1030  1408 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=126313  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:31:53.827  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=126313  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:31:53.827  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:6967] from screen [on:0 period:164131299] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-08 14:31:53.828  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:164131300] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-08 14:31:53.828  1030  1408 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-08 14:31:53.831  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:53.831  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:53.832  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:53.834  1030  1464 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-08 14:31:53.834  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:53.834  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:31:53.834  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:31:53.834  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:31:53.834  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:31:53.835  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:53.835  1030  1408 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,09-08 14:31:53.835  1030  1408 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:53.835  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:53.836  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:53.836  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-08 14:31:53.836  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=12,0,0
09-08 14:31:53.837  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:53.837  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 14:31:53.837  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=12,0,0
09-08 14:31:53.837  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-08 14:31:53.837  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-08 14:31:53.838  1030  1408 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-08 14:31:53.838  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 0
09-08 14:31:53.839  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:31:53.840  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:31:53.840  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 14:31:53.840  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:31:53.840  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:31:53.840  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:31:53.840  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 14:31:53.840  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:31:53.840  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:53.841  1030  1408 D WifiNative-wlan0: SET ps 0: returned true
09-08 14:31:53.841  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-08 14:31:53.841  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-08 14:31:53.843  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:53.843  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-08 14:31:53.844  1030  1370 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@317004f4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:53.844  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@317004f4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:53.844  1030  6847 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:53.844  1030  6847 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-08 14:31:53.844  1030  1408 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-08 14:31:53.844  1030  1408 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:31:53.845  1030  1408 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:31:53.845   308   888 D CommandListener: Setting iface cfg
09-08 14:31:53.845   308   888 D CommandListener: Trying to bring up wlan0
09-08 14:31:53.846  1030  1408 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,09-08 14:31:53.847  6827  6827 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@22164e55 Instance Count = 1
09-08 14:31:53.848  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:53.850  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:53.850  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 14:31:53.850  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:53.852  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:53.852  6827  6827 D BluetoothAdapterApp: onCreate
09-08 14:31:53.852  1030  1408 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:53.852  1030  1408 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:53.853  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:53.853  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:31:53.853  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,09-08 14:31:53.854  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 14:31:53.854  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 14:31:53.854  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 14:31:53.854  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:53.854  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 14:31:53.854  1030  1370 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:53.854  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:53.854  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 14:31:53.854  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-08 14:31:53.855  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-08 14:31:53.855  1030  1408 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-08 14:31:53.855  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 14:31:53.859  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:53.859  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:53.860  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 14:31:53.862  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:53.867  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:53.871  6827  6827 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-08 14:31:53.871  6827  6827 D ProfileConfigQcom: Adding HeadsetService
09-08 14:31:53.871  6827  6827 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-08 14:31:53.871  1030  1408 D WifiNative-wlan0: SET ps 1: returned true
09-08 14:31:53.871  6827  6827 D ProfileConfigQcom: Adding A2dpService
09-08 14:31:53.871  6827  6827 D ProfileConfigQcom: [BTUI] HidService is supported
09-08 14:31:53.872  6827  6827 D ProfileConfigQcom: Adding HidService
09-08 14:31:53.872  6827  6827 D ProfileConfigQcom: [BTUI] HealthService is supported
09-08 14:31:53.872  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 14:31:53.872  6827  6827 D ProfileConfigQcom: Adding HealthService
09-08 14:31:53.872  6827  6827 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-08 14:31:53.872  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 14:31:53.872  1030  1408 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 14:31:53.873  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-08 14:31:53.873  6827  6827 D ProfileConfigQcom: [BTUI] PanService is supported
09-08 14:31:53.873  1030  1464 D ConnectivityService: ignoring duplicate network state non-change
09-08 14:31:53.873  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:53.873  6827  6827 D ProfileConfigQcom: Adding PanService
09-08 14:31:53.873  6827  6827 D ProfileConfigQcom: [BTUI] GattService is supported
09-08 14:31:53.873  6827  6827 D ProfileConfigQcom: Adding GattService
09-08 14:31:53.874  6827  6827 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-08 14:31:53.874  6827  6827 D ProfileConfigQcom: Adding BluetoothMapService
09-08 14:31:53.874  6827  6827 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-08 14:31:53.874  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:53.874  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:53.875  6827  6827 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 14:31:53.875  6827  6827 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:53.876  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.876  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.876  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 14:31:53.876  6827  6827 V BluetoothPbapReceiver: ***********state = 10
09-08 14:31:53.876  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:53.877  6827  6827 V LGMDMManagerInternal: Create singleton instance
09-08 14:31:53.877  1030  1464 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 14:31:53.877  1030  1464 D ConnectivityService: Adding iface wlan0 to network 101
09-08 14:31:53.882  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.882  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.882  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_P,ORTAL_CHECK]
,09-08 14:31:53.887  1030  1408 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-08 14:31:53.892  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 14:31:53.892  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.892  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.892  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 14:31:53.892  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 14:31:53.892  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.892  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:53.893  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 14:31:53.893  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-08 14:31:53.897  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:53.897  1030  1464 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 14:31:53.897  1030  1464 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-08 14:31:53.897  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:53.897  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:53.898  1030  1464 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-08 14:31:53.898  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:53.898  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:53.898   308   888 E Netd    : netlink response contains error (File exists)
09-08 14:31:53.898  1030  1464 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-08 14:31:53.899  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:53.899  1030  1464 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-08 14:31:53.899  1030  1464 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-08 14:31:53.899  1030  1464 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-08 14:31:53.900  1030  1464 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 14:31:53.900  1030  1464 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 14:31:53.900  1030  1464 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-08 14:31:53.900  1030  1464 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-08 14:31:53.900  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:53.900  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-08 14:31:53.900  1030  1464 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:53.900  1030  1464 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:53.900  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:53.900  1030  1464 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 14:31:53.900  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-08 14:31:53.900  1030  1464 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:53.900  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:53.900  1030  1464 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-08 14:31:53.900  1030  1464 D ConnectivityService: currentScore = 0, newScore = 20
09-08 14:31:53.900  1030  1464 D ConnectivityService:    accepting network in place of null
09-08 14:31:53.9,00  1584  1584 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 14:31:53.901  1030  1464 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:53.901  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:53.901  1030  1408 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:53.901  1030  1408 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:53.901  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:53.903  1030  1464 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-08 14:31:53.903  1030  1464 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 14:31:53.903  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 14:31:53.903  1835  1835 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:53.903  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 14:31:53.904   308  6852 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-08 14:31:53.905  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 14:31:53.905  1584  1584 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 14:31:53.905  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:53.910  1030  1464 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:53.910  1030  1464 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-08 14:31:53.910  1030  1464 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-08 14:31:53.911  1030  1464 D ConnectivityService: validation of new default Network = false
,09-08 14:31:53.911  1030  1464 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-08 14:31:53.911  1030  1464 D DSQN    : enableDataServiceNotify 
09-08 14:31:53.911  1030  1464 D DSQN    : start dsqn bin
09-08 14:31:53.913  1030  1030 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-08 14:31:53.914  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 14:31:53.914  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 14:31:53.914  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 14:31:53.914   308  6853 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 14:31:53.915   308  6853 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
09-08 14:31:53.918  1030  1464 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-08 14:31:53.918  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:53.918  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:53.919  1030  1464 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-08 14:31:53.903  6854  6854 W dsqn    : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-08 14:31:53.903  6854  6854 W dsqn    : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:53.923  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:53.924  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:31:53.930  6854  6854 E DSQN    : DSQN ssw
,09-08 14:31:53.937  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 14:31:53.941  1584  1584 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:31:53.942  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:31:53.942  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:31:53.943  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:53.943  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:53.944  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:53.946  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:53.950  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:53.954  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:53.956  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:31:53.958  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:53.959  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:53.959  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:31:53.959  6213  6213 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-08 14:31:53.960  6827  6827 D LGBluetoothAPIServer: [BTUI] onCreate()
09-08 14:31:53.960  6827  6827 D LGBluetoothAPIServer: [BTUI] onBind()
09-08 14:31:53.961  1924  1924 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-08 14:31:53.961  1924  2103 D LGBluetoothAPIService: Message: 100
09-08 14:31:53.961  1924  2103 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-08 14:31:53.964  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:53.970  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:53.974  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:53.974  6213  6213 D BluetoothPermissionRequest: onReceive
09-08 14:31:53.976  6213  6213 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-08 14:31:53.976  6213  6213 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-08 14:31:53.977  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 14:31:53.979   308  6852 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-08 14:31:53.979   308  6853 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
,09-08 14:31:53.980  6827  6827 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-08 14:31:53.988  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:53.988  6827  6827 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:53.988  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:53.989  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 14:31:53.992  6827  6827 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 14:31:53.992  6827  6827 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 14:31:53.992  6827  6827 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 14:31:53.993  6827  6827 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:53.994  6827  6827 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-08 14:31:53.996  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:31:54.002  6262  6262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-08 14:31:54.002  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:54.004  6784  6784 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-08 14:31:54.007  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:54.013  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:54.013   308  6852 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-08 14:31:54.016  1030  1369 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-08 14:31:54.028  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 14:31:54.028  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:31:54.030  6295  6295 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 14:31:54.032  6295  6295 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 14:31:54.033  6295  6295 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-08 14:31:54.034  1799  6859 I CheckinService: active receiver: enabled
09-08 14:31:54.045  1030  6847 D DhcpStateMachine: DHCPV4 request on wlan0
09-08 14:31:54.046  1030  6847 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-08 14:31:54.046  1030  6847 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-08 14:31:54.033  6860  6860 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:54.033  6860  6860 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:54.054   308   887 D LGDataListener: argv[0]=dsqncommand
09-08 14:31:54.054   308   887 D LGDataListener: argv[1]=wlan0
09-08 14:31:54.054   308   887 D LGDataListener: argv[2]=1
09-08 14:31:54.054   308   887 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-08 14:31:54.055  1030  1110 D DSQN    : DSQM DsqnNotification wlan0  1
09-08 14:31:54.055  1030  1110 D DSQN    : start to monitor internet connection
09-08 14:31:54.065  6860  6860 I dhcpcd  : version 5.5.6 starting
,09-08 14:31:54.065  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:31:54.067  6860  6860 E dhcpcd  : get_duid: m
09-08 14:31:54.067  6860  6860 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-08 14:31:54.067  6860  6860 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-08 14:31:54.069  1799  6859 I CheckinService: Preparing to send checkin request
09-08 14:31:54.069  1799  6859 I EventLogService: Accumulating logs since 1473337409137
09-08 14:31:54.072  6262  6262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 14:31:54.073  6262  6262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:54.081  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:54.088  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:54.094  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:31:54 GMT], X-Android-Received-Millis=[1473337914094], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473337914053]}
09-08 14:31:54.094  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-08 14:31:54.094  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 14:31:54.096  1030  1464 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-08 14:31:54.096  1030  1464 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-08 14:31:54.096  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:31:54.096  1030  1464 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:54.096  1030  1464 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:54.096  1030  1464 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 14:31:54.096  1030  1464 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-08 14:31:54.096  1030  1464 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-08 14:31:54.096  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.096  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 14:31:54.096  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:54.097  1030  1464 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:54.097  1030  1464 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.097  6295  6295 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 14:31:54.097  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 14:31:54.098  1835  1835 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.098  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:31:54.098  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 14:31:54.099  1030  1408 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.099  1030  1408 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:54.099  6295  6295 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 14:31:54.100  6295  6295 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-08 14:31:54.120  1584  1584 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:31:54.121  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:31:54.122  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:31:54.134  6860  6860 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 14:31:54.135  6860  6860 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 14:31:54.135  6860  6860 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 14:31:54.135  6860  6860 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-08 14:31:54.135  6860  6860 D dhcpcd  : wlan0: sending REQUEST (xid 0xcf37f1d4), next in 3.88 seconds
,09-08 14:31:54.149  1799  6859 W EventLogAggregator: Unknown tag: snet_gcore
,09-08 14:31:54.149  1799  6859 W EventLogAggregator: Unknown tag: snet_launch_service
09-08 14:31:54.161  6612  6633 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-08 14:31:54.168  6860  6860 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-08 14:31:54.171  6860  6860 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-08 14:31:54.171  6860  6860 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-08 14:31:54.171  6860  6860 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-08 14:31:54.171  6860  6860 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-08 14:31:54.172  6860  6860 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 14:31:54.172  6860  6860 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 14:31:54.172  6860  6860 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 14:31:54.172  6860  6860 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-08 14:31:54.202  1799  6859 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-08 14:31:54.208  1030  1451 D WifiService: New client listening to asynchronous messages
,09-08 14:31:54.388  1030  1046 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6886 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-08 14:31:54.466  6886  6886 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-08 14:31:54.466  6886  6886 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 14:31:54.498  6886  6886 I MultiDex: VM with version 2.1.0 has multidex support
09-08 14:31:54.498  6886  6886 I MultiDex: install
09-08 14:31:54.499  6886  6886 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-08 14:31:54.516  6886  6886 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-08 14:31:54.522  2187  2187 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-08 14:31:54.535  2187  2187 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-08 14:31:54.536  2187  2187 D c       : Getting all permits...
09-08 14:31:54.536  2187  2187 D a       : Opening database...
,09-08 14:31:54.540  2187  2187 D a       : Opening database auth.proximity.permit_store...
09-08 14:31:54.542  2187  2187 D a       : Closing database...
09-08 14:31:54.652  1030  6847 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-08 14:31:54.654  1030  6847 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-08 14:31:54.655  1030  6847 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:31:54.655  1030  6847 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-08 14:31:54.655  1030  6847 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-08 14:31:54.655  1030  6847 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:31:54.655  1030  6847 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-08 14:31:54.655  1030  6847 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,09-08 14:31:54.655  1030  6847 D DhcpStateMachine: RunningState
,09-08 14:31:54.920  1030  1464 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 14:31:54.996  1584  1584 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,09-08 14:31:54.996  1584  1584 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-08 14:31:55.010  1030  1451 D WifiController: battery changed pluggedType: 2
,09-08 14:31:55.015  1924  2054 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-08 14:31:55.015  1924  2054 D LEDHandler: Battery Level Remaining: 100%
09-08 14:31:55.015  1924  2054 D LEDHandler: Battery Temp: 304, mChargingStatus=5, mChargingStop=false
09-08 14:31:55.018  1584  1584 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 304
09-08 14:31:55.019  1584  1584 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-08 14:31:55.020  1584  1584 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-08 14:31:55.021  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:55.021  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:55.022  5024  5024 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-08 14:31:55.057  6921  6921 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-08 14:31:55.136  1030  1923 I ActivityManager: Killing 5024:com.lge.bnr/1000 (adj 15): empty #17
,09-08 14:31:55.145  6921  6921 I dex2oat : dex2oat took 87.862ms (threads: 4)
09-08 14:31:55.168  6886  6907 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:31:55.168  6886  6907 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:31:55.168  6886  6907 I Adreno-EGL: Build Date: 12/12/14 금
09-08 14:31:55.168  6886  6907 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 14:31:55.168  6886  6907 I Adreno-EGL: Remote Branch: 
09-08 14:31:55.168  6886  6907 I Adreno-EGL: Local Patches: 
09-08 14:31:55.168  6886  6907 I Adreno-EGL: Reconstruct Branch: 
,09-08 14:31:55.193  1030  1750 W libprocessgroup: failed to open /acct/uid_1000/pid_5024/cgroup.procs: No such file or directory
,09-08 14:31:55.331  6886  6907 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:31:55.331  6886  6907 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:31:55.331  6886  6907 I Adreno-EGL: Build Date: 12/12/14 금
09-08 14:31:55.331  6886  6907 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 14:31:55.331  6886  6907 I Adreno-EGL: Remote Branch: 
09-08 14:31:55.331  6886  6907 I Adreno-EGL: Local Patches: 
09-08 14:31:55.331  6886  6907 I Adreno-EGL: Reconstruct Branch: 
,09-08 14:31:55.410  6886  6907 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:31:55.410  6886  6907 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:31:55.410  6886  6907 I Adreno-EGL: Build Date: 12/12/14 금
09-08 14:31:55.410  6886  6907 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 14:31:55.410  6886  6907 I Adreno-EGL: Remote Branch: 
09-08 14:31:55.410  6886  6907 I Adreno-EGL: Local Patches: 
09-08 14:31:55.410  6886  6907 I Adreno-EGL: Reconstruct Branch: 
,09-08 14:31:55.573  6886  6907 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 14:31:55.573  6886  6907 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 14:31:55.723  1030  1408 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-08 14:31:55.724  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:31:55.725  1030  1408 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:31:55.726  1030  1408 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-08 14:31:55.726  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:31:55.727  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:31:55.728  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-08 14:31:55.729  1030  1464 D ConnectivityService: identical MTU - not setting
09-08 14:31:55.729  1030  1464 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 14:31:55.729  1030  1464 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 14:31:55.729  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:55.729  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:55.730  1030  1464 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:55.736  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 14:31:55.782   308  6936 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 14:31:55.784   308  6936 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,09-08 14:31:55.822   308  6936 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,09-08 14:31:55.963  1799  6859 I CheckinTask: Sending checkin request (7995 bytes)
,09-08 14:31:56.182  1799  6859 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-08 14:31:56.192  1799  6859 I CheckinService: active receiver: disabled
,09-08 14:31:56.220  2187  2187 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-08 14:31:56.239  2187  2187 I GCM     : GCM config loaded
,09-08 14:31:56.262   308  6944 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-08 14:31:56.264   308  6944 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,09-08 14:31:56.270  6523  6523 V SetupWizard: Connected to Gservices successfully
,09-08 14:31:56.314   308  6944 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-08 14:31:56.488  2187  6941 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-08 14:31:56.572  1799  1799 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-08 14:31:56.586  1799  6947 I ConfigFetchService: running network task: configservice_periodic
,09-08 14:31:56.603  1799  6947 I ConfigFetchService: launchTask
,09-08 14:31:56.607  2187  2187 I ConfigService: onCreate
09-08 14:31:56.608  2187  2187 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-08 14:31:56.618  2187  2187 I ConfigService: onBind returning update interface
,09-08 14:31:56.626  2187  2187 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-08 14:31:56.626  2187  2187 I ConfigService: onBind returning config service
09-08 14:31:56.628  2187  6946 D GCM     : Connected
,09-08 14:31:56.670  2187  6946 D GCM     : Message class com.google.e.a.a.q
,09-08 14:31:56.748  1799  1799 I art     : Explicit concurrent mark sweep GC freed 23649(1720KB) AllocSpace objects, 20(316KB) LOS objects, 51% free, 29MB/61MB, paused 1.604ms total 123.822ms
09-08 14:31:56.749  1799  1799 I ConfigFetchService: service connected
09-08 14:31:56.749  1799  1799 I ConfigClient: service connected
,09-08 14:31:56.836  1030  1408 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:164134308] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 14:31:56.839  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:164134311] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 14:31:56.839  1030  1408 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-08 14:31:56.862  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:31:56.892  1030  1421 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-08 14:31:56.911  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:56.913  1030  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:56.916  1030  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:56.918  1030  1112 D Tethering: MasterInitialState.processMessage what=3
09-08 14:31:56.920  5982  5982 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:56.921  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:56.921  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:56.921  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:56.921  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:56.921  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:31:56.921  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:56.921  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:56.921  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:56.921  5982  5982 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:56.921  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:56.925  5352  5352 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-08 14:31:56.925  1030  1810 D AlarmManagerService: Setting time of day to sec=1473337917
09-08 14:31:57.556  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-08 14:31:57.556  1030  1810 W AlarmManagerService: Unable to set rtc to 1473337917: Invalid argument
09-08 14:31:57.559  5224  5252 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-08 14:31:57.562  5982  5982 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:57.562  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:57.562  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:57.562  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:57.562  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:57.562  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:31:57.562  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:57.562  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:57.562  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:57.563  5982  5982 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:57.563  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:57.584  1584  1584 D KeyguardUpdateMonitor: handleTimeUpdate
09-08 14:31:57.587  1924  1924 I SecureClockService: Intent.ACTION_TIME_CHANGED 
09-08 14:31:57.587  1584  1584 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
09-08 14:31:57.588  1584  1584 I LgeClockWidgetControlView: time changed, timezoneChanged : false
09-08 14:31:57.590  2740  2740 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
09-08 14:31:57.590  2740  2740 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-09-08 14:31:57...... Request
09-08 14:31:57.591  2740  2740 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 7, total count : 80, new day : false...... Request
09-08 14:31:57.591  2740  2740 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 80
09-08 14:31:57.591  2740  2740 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 7
09-08 14:31:57.592  1030  1046 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
09-08 14:31:57.592  2740  2740 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-09-08 14:31:57
09-08 14:31:57.594  2014  2014 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=8 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
09-08 14:31:57.595  2187  2187 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:57.596  2014  2014 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 8
,09-08 14:31:57.602  2014  2014 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 8
09-08 14:31:57.604  2014  2014 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 14:31:57.608  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 14:31:57.608  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:57.609  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 14:31:57.609  6490  6490 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 14:31:57.609  1030  1045 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-08 14:31:57.609  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:57.610  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:57.610  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-08 14:31:57.610  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:57.610  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-08 14:31:57.613  6490  6490 I AppUp4:CustModeStarterReceiver: onReceive
09-08 14:31:57.617  6490  6490 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1e7c3037
09-08 14:31:57.617  6490  6490 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 14:31:57.617  6490  6490 D AppUp4:CustFacade: isPhone : true
09-08 14:31:57.617  6490  6490 D AppUp4:CustModeStarterReceiver: begin check event
09-08 14:31:57.617  6490  6490 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 14:31:57.622  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:57.622  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:31:57.624  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:31:57.627  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:31:57.632  4152  6970 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:31:57.633  2624  2624 D [Concierge]Service: onStartCommand(). Type : 9
,09-08 14:31:57.635  3381  3381 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:57.636  4152  6971 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:57.636  4152  6971 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:31:57.638  3381  3381 V DownloadManager: DownloadService onCreate
09-08 14:31:57.640  4152  6970 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 14:31:57.640  5829  5829 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
09-08 14:31:57.643  3381  6972 I DownloadManager: in removeSpuriousFiles
09-08 14:31:57.644  3381  6972 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-08 14:31:57.648  3381  6972 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@292fbed on behalf of 3381
09-08 14:31:57.650  4152  6970 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 14:31:57.653  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:31:57 GMT], X-Android-Received-Millis=[1473337917652], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473337917612]}
09-08 14:31:57.653  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 14:31:57.653  4152  4152 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-08 14:31:57.653  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 14:31:57.653  1030  1464 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-08 14:31:57.653  1030  1464 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-08 14:31:57.653  1030  1464 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:57.653  1030  1464 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:57.654  1030  1464 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 14:31:57.654  1030  1464 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-08 14:31:57.654  1030  1464 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-08 14:31:57.654  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:57.654  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:57.654  3381  3381 V DownloadManager: DownloadService onStartCommand
09-08 14:31:57.654  3381  6973 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-08 14:31:57.655  1030  1464 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:57.655  4152  4152 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-08 14:31:57.655  4152  4152 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 14:31:57.656  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:31:57.663  3381  6972 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-08 14:31:57.663  3381  6972 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-08 14:31:57.663  3381  6972 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-08 14:31:57.663  3381  6972 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-08 14:31:57.663  3381  6972 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-08 14:31:57.663  3381  6972 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-08 14:31:57.664  4152  4152 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 14:31:57.666  3281  3281 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 14:31:57.666  3281  3281 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:57.666  3281  3281 I LgeMiscReceiver: networkInfo.isConnected() = true
09-08 14:31:57.666  3281  3281 D PhoneState: setPdpRejectCasuse : false
09-08 14:31:57.667  3381  6973 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2cab5270 on behalf of 3381
09-08 14:31:57.669  3381  6973 V DownloadManager: processing inserted download 1
09-08 14:31:57.670  3381  6972 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-08 14:31:57.670  3381  6972 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-08 14:31:57.670  3381  6972 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-08 14:31:57.670  3381  6972 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-08 14:31:57.670  3381  6972 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,09-08 14:31:57.671  3381  6972 I DownloadManager: in trimDatabase
09-08 14:31:57.671  3381  6972 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-08 14:31:57.672  3381  6973 V DownloadManager: processing inserted download 4
09-08 14:31:57.672  5829  6976 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:57.673  3381  6972 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2ab069e9 on behalf of 3381
09-08 14:31:57.674  6523  6523 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 14:31:57.675  4152  4152 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-08 14:31:57.675  6523  6523 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 14:31:57.679  3381  6973 V DownloadManager: processing inserted download 7
09-08 14:31:57.680  3381  6973 V DownloadManager: processing inserted download 8
09-08 14:31:57.683  3381  6973 V DownloadManager: processing inserted download 9
09-08 14:31:57.684  3381  6973 V DownloadManager: processing inserted download 10
09-08 14:31:57.685  3381  6973 V DownloadManager: processing inserted download 11
09-08 14:31:57.686  6594  6594 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:57
09-08 14:31:57.687  3381  6973 V DownloadManager: processing inserted download 12
09-08 14:31:57.688  6594  6594 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 14:31:57.688  6594  6594 D Weather.Utils: 2 : All the weather widget is gone.
09-08 14:31:57.688  6594  6594 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:31:57.688  6594  6594 D WeatherAncestor: connectivity changed - connection : true
09-08 14:31:57.688  3381  6973 V DownloadManager: processing inserted download 13
09-08 14:31:57.688  6594  6594 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a9af30d
09-08 14:31:57.689  6594  6594 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 14:31:57.689  6594  6594 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 14:31:57.689  6594  6594 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 14:31:57.689  6594  6594 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 14:31:57.689  6594  6594 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:57
09-08 14:31:57.689  3381  6973 V DownloadManager: processing inserted download 14
09-08 14:31:57.690  3381  6973 V DownloadManager: processing inserted download 16
09-08 14:31:57.696  3381  3381 V DownloadManager: DownloadService onDestroy
,09-08 14:31:57.724  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,09-08 14:31:57.764   308  6985 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 14:31:57.764   308  6985 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,09-08 14:31:57.799  1030  1749 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6987 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
09-08 14:31:57.802  1799  6983 I CheckinService: active receiver: disabled
,09-08 14:31:57.814   308  6985 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,09-08 14:31:57.856  6239  6979 V FormManager: There are no updated forms. The schedule will be deleted.
,09-08 14:31:57.859  6239  6979 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-08 14:31:57.937  6987  7004 D ALBootInit: ====action==>android.intent.action.TIME_SET
,09-08 14:31:57.942  6987  7004 D ALBootInit: Alarm ALBootInit: TIME_SET
09-08 14:31:57.949  6987  7004 D Alarms  : [setNextAlert] start
09-08 14:31:57.970  6987  7004 D Alarms  : [setNextAlert] (1)
,09-08 14:31:57.974  6987  7004 D Alarms  :  minTime  = 0
09-08 14:31:57.982  6987  7004 D Alarms  :  -- OK multi -- 0
09-08 14:31:57.984  6987  7004 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
09-08 14:31:57.984  6987  7004 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
,09-08 14:31:58.013  6987  7004 I CommonUtil: BUILD Country: EU
,09-08 14:31:58.015  6987  7004 D Alarms  : broadcastToWidgetProvider : false
,09-08 14:31:58.023  6987  7004 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
09-08 14:31:58.046  1030  1941 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,09-08 14:31:58.050  6987  6987 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
09-08 14:31:58.052  6987  6987 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@131b79a4
09-08 14:31:58.055  6987  6987 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@131b79a4
09-08 14:31:58.059  6987  6987 D QuickCoverProvider: onReceiver
,09-08 14:31:58.069  1540  1540 I indal   : SmartCoverWidgetContext createApplicationContext
09-08 14:31:58.069  1540  1540 I indal   : SmartCoverWidgetContext createApplicationContext
09-08 14:31:58.094  6594  6594 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:31:58
,09-08 14:31:58.096  6594  6594 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 14:31:58.096  6594  6594 D Weather.Utils: 2 : All the weather widget is gone.
09-08 14:31:58.097  6594  6594 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:31:58.098  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:58.098  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:58.100  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:58.100  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:58.100  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:58.100  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:31:58.100  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b203a17 removed from the list
09-08 14:31:58.101  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:58.101  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3335ee04 removed from the list
09-08 14:31:58.101  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:58.101  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:58.101  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:58.103  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:58.103  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cb11e22 added. We now have 2 listener(s)
09-08 14:31:58.104  1030  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:58.106  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 14:31:58.106  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:58.106  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:31:58.106  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:58.106  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ee460b3 added. We now have 2 listener(s)
09-08 14:31:58.106  5982  6084 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:58.108  6594  6594 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a9af30d
09-08 14:31:58.109  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:58.109  6594  6594 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 14:31:58.109  6594  6594 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 14:31:58.109  6594  6594 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,09-08 14:31:58.112  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:58.114  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:58.114  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:58.114  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:58.114  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:58.114  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:58.114  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:31:58.114  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:58.114  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:58.114  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:58.114  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:58.115  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:58.115  5982  6084 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:58.115  6594  6594 D Weather_cast: 2 : set auto-update time : 9/8 17:31
,09-08 14:31:58.116  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-08 14:31:58.116  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:58.116  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:58.116  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 14:31:58.116  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cb11e22 removed from the list
09-08 14:31:58.116  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:58.116  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ee460b3 removed from the list
09-08 14:31:58.123  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:58.123  6594  6594 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:31:58
,09-08 14:31:58.127  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:58.127  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:58.127  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:58.185  1030  1959 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7012 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 14:31:58.188  1030  1959 I ActivityManager: Killing 6737:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-08 14:31:58.244  1030  1637 W libprocessgroup: failed to open /acct/uid_10037/pid_6737/cgroup.procs: No such file or directory
09-08 14:31:58.245  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:58.245  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f96de9 added. We now have 2 listener(s)
,09-08 14:31:58.261  1030  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:58.264  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 14:31:58.264  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:58.264  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:31:58.264  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:58.264  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ce6fa6e added. We now have 2 listener(s)
09-08 14:31:58.264  5982  6084 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:58.265  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:58.267  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:58.269  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:58.269  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:58.269  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:58.269  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:58.269  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:58.269  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:31:58.269  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:58.269  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:58.269  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:58.269  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:58.269  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:58.269  5982  6084 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:58.271  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:58.272  1030  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:58.272  1030  1923 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-08 14:31:58.272  1030  1112 D BluetoothManagerService: Message: 2
09-08 14:31:58.274  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:58.325  7012  7012 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1473337918325
09-08 14:31:58.325  7012  7012 D         : TimeServiceNative: User Time to be set is 1473337918325
09-08 14:31:58.325  7012  7012 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
09-08 14:31:58.325  7012  7012 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
09-08 14:31:58.325  7012  7012 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1473337918325
09-08 14:31:58.325  7012  7012 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-08 14:31:58.325   404  1029 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-08 14:31:58.326   404  7030 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1473337918325
,09-08 14:31:58.326   404  7030 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1473337918325, operation = 0
09-08 14:31:58.326   404  7030 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/21/70 6:59:22
09-08 14:31:58.326   404  7030 D QC-time-services: Daemon:Value read from RTC seconds = 6850762000
,09-08 14:31:58.326   404  7030 D QC-time-services: Daemon:new time 1473337918325 
09-08 14:31:58.326   404  7030 D QC-time-services: Daemon: delta 1466487156325 genoff 1466487156325 
09-08 14:31:58.326   404  7030 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487156325 to memory
,09-08 14:31:58.327   404  7030 D QC-time-services: Daemon:Opening File: /data/time/ats_2
09-08 14:31:58.327   404  7030 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
09-08 14:31:58.337   404  7030 D QC-time-services: Updating the TOD offset
09-08 14:31:58.337   404  7030 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487156325 to memory
09-08 14:31:58.337   404  7030 D QC-time-services: Daemon:Opening File: /data/time/ats_1
09-08 14:31:58.337   404  7030 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-08 14:31:58.342   404  7030 E QC-time-services: Daemon:Update to modem bit set
09-08 14:31:58.342   404  7030 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
09-08 14:31:58.342   404  7030 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522356325
09-08 14:31:58.342  7012  7012 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
09-08 14:31:58.345   404  1027 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
09-08 14:31:58.346   404  1029 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-08 14:31:58.420  1030  1637 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7031 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-08 14:31:58.422  1030  1637 I ActivityManager: Killing 6784:com.lge.settings.easy/1000 (adj 15): empty #17
09-08 14:31:58.524  1030  1749 W libprocessgroup: failed to open /acct/uid_1000/pid_6784/cgroup.procs: No such file or directory
,09-08 14:31:58.606  7031  7031 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
,09-08 14:31:58.613  7031  7031 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
09-08 14:31:58.615  1584  1584 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
09-08 14:31:58.615  1584  1584 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
09-08 14:31:58.615  1584  1584 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
09-08 14:31:58.620  7031  7031 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
,09-08 14:31:58.622  7031  7031 V [BNRBootReceiver]: Boot Receiver Return
,09-08 14:31:58.624  7031  7031 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-08 14:31:58.684  1030  1959 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7049 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
09-08 14:31:58.685  1030  1959 I ActivityManager: Killing 6262:com.lge.sync/1000 (adj 15): empty #17
,09-08 14:31:58.742   308  7066 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 14:31:58.742   308  7066 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,09-08 14:31:58.753  1030  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_6262/cgroup.procs: No such file or directory
,09-08 14:31:58.775   308  7066 D libc-netbsd: res_queryN name = www.google.com succeed
,09-08 14:31:58.782  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:58.783   308  7068 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 14:31:58.783  1030  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:58.783   308  7068 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-08 14:31:58.783   308  7068 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-08 14:31:58.784  1030  1045 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-08 14:31:58.804  7049  7049 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:31:58.813  1030  1112 D BluetoothManagerService: Message: 1
,09-08 14:31:58.813  1030  1112 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-08 14:31:58.813  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:31:58.814  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:31:58.814  1030  1030 D Ulp_jni : JNI:system_update. Event-4
09-08 14:31:58.833  1030  1112 D BluetoothManagerService: Message: 20
09-08 14:31:58.833  1030  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e8b708f:true
09-08 14:31:58.834  6827  6827 D BluetoothAdapterState: make
,09-08 14:31:58.839  6827  6827 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-08 14:31:58.840  6827  6827 I bluedroid-qcom: init
09-08 14:31:58.841  6827  6827 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 14:31:58.841  6827  6827 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-08 14:31:58.842  6827  6827 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 14:31:58.842  6827  6827 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 14:31:58.842  6827  6827 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-08 14:31:58.842  6827  7071 I BluetoothAdapterState: Entering OffState
09-08 14:31:58.843  6827  6827 I bluedroid-qcom: get_profile_interface socket
09-08 14:31:58.843  6827  6827 I bluedroid-qcom: get_profile_interface map_client
09-08 14:31:58.848  1030  1422 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-08 14:31:58.851  7074  7074 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-08 14:31:58.851  7074  7074 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-08 14:31:58.851  7074  7074 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-08 14:31:58.836  7074  7074 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:58.836  7074  7074 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:58.857  6827  7075 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-08 14:31:58.859  7074  7074 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-08 14:31:58.860  6827  7075 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-08 14:31:58.866  7074  7074 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-08 14:31:58.866  7074  7074 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-08 14:31:59.005  1030  1905 I art     : Explicit concurrent mark sweep GC freed 74690(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.112ms total 151.721ms
,09-08 14:31:59.005  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-08 14:31:59.005  1030  1112 D BluetoothManagerService: Message: 40
09-08 14:31:59.005  1030  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-08 14:31:59.007  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-08 14:31:59.007  6827  7075 D BluetoothAdapterProperties: Name is: G3
09-08 14:31:59.007  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
09-08 14:31:59.008  7049  7049 D CalendarApplication: CalendarApplication.onCreate()
09-08 14:31:59.008  6827  6844 I bluedroid-qcom: config_hci_snoop_log
09-08 14:31:59.009  1030  1112 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-08 14:31:59.009  1030  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-08 14:31:59.018  6827  7071 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-08 14:31:59.018  6827  7071 D BluetoothAdapterProperties: Setting state to 11
09-08 14:31:59.018  6827  7071 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-08 14:31:59.019  6827  7071 I LGBluetoothServiceJni: classInitNative: succeeds
09-08 14:31:59.021  1030  1112 D BluetoothManagerService: Message: 60
09-08 14:31:59.021  1030  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-08 14:31:59.021  1030  1112 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,09-08 14:31:59.022  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:59.023  1584  1584 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 14:31:59.026  6213  6213 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-08 14:31:59.027  6827  7071 D BluetoothBondStateMachine: make
09-08 14:31:59.030  6827  6827 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 14:31:59.030  6827  6827 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:59.030  6827  6827 V BluetoothPbapReceiver: ***********state = 11
09-08 14:31:59.032  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:59.033  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 14:31:59.037  6827  7071 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
,09-08 14:31:59.037  6827  7071 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-08 14:31:59.037  6827  7071 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:31:59.037  6827  7071 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-08 14:31:59.037  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:59.037  6827  7071 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-08 14:31:59.038  6827  7078 I BluetoothBondStateMachine: StableState(): Entering Off State
09-08 14:31:59.040  6827  7071 E BluetoothAdapterService: File transfer profiles supported!!
09-08 14:31:59.045  7049  7049 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
09-08 14:31:59.051  7049  7049 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@35eb595b, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@21d0f5f8, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@6ba7ad1, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3d782936, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1e7c3037, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@131b79a4, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3a9af30d, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3315a2c2, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3bd998d3, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@e688c10, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2190b309, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@231f290e, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@19aef2f, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1132593c, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2a0876c5, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1b28c81a, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1b714f4b, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1469cd28, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@27eba41, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3bfb4be6, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@35039527, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2d2293d4, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2abbb97d, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@18204072, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@238a5cc3, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@bff1940, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1ccf7079, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2f2df1be, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@d2c021f, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@75c896c, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@9cd9b35, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@11d36bca, lg_preferences_alerts_popup=c,om.android.calendar.adaptation.PreferenceKey$KeyData@2a18a13b, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1c3ed058, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2649b5b1, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3aa47a96, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3b661617, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@11fc9a04, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@292fbed, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@27a5aa22, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@13abfcb3, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2cab527
,09-08 14:31:59.056  7049  7049 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
09-08 14:31:59.063  7049  7049 D Config  : [init]
09-08 14:31:59.064  7049  7049 I Config  : LGCalendar ver.4.40.16
09-08 14:31:59.064  7049  7049 I Config  : start check model
09-08 14:31:59.064  7049  7049 I Config  : start check native_ca
09-08 14:31:59.065  7049  7049 I Config  : Config Operator=OPEN, Country=EU
09-08 14:31:59.065  7049  7049 D Config  : [setDefaultValuesToPref]
09-08 14:31:59.065  7049  7049 D Config  : [parseProfiles]
,09-08 14:31:59.070  7049  7049 D ProfilesParser: [debug_displayParseInfos] profile.country = null
09-08 14:31:59.070  7049  7049 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
09-08 14:31:59.071  7049  7049 D Config  : [updateProfiletoCountryInfo]
09-08 14:31:59.072  7049  7049 D GeneralPreference: [checkAndMigrateOldPreference]
09-08 14:31:59.081  1030  1046 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7081 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-08 14:31:59.094  6827  6827 D HeadsetService: Received start request. Starting profile...
09-08 14:31:59.095  6827  6827 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 14:31:59.096  6827  6827 D LGBluetoothHfpAdapter: Version 1.6
,09-08 14:31:59.103  6827  6827 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-08 14:31:59.104  6827  6827 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 14:31:59.104  6827  6827 D HeadsetStateMachine: make
09-08 14:31:59.105  6827  7071 E BluetoothAdapterService: File transfer profiles supported!!
09-08 14:31:59.112  6827  7071 E BluetoothAdapterService: File transfer profiles supported!!
,09-08 14:31:59.116  7049  7049 E AgendaWidgetManager: [updateWidgets] 
09-08 14:31:59.120  6827  7071 E BluetoothAdapterService: File transfer profiles supported!!
09-08 14:31:59.122  7049  7104 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
09-08 14:31:59.124  7049  7104 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
09-08 14:31:59.126  6827  7071 E BluetoothAdapterService: File transfer profiles supported!!
,09-08 14:31:59.142  6827  7071 E BluetoothAdapterService: File transfer profiles supported!!
,09-08 14:31:59.146  6827  6827 D LgDataFeature: LgDataFeature() Constructor: none
09-08 14:31:59.146  6827  6827 D LgDataFeature: LgDataFeature() Constructor Done, null
09-08 14:31:59.146  7049  7104 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
09-08 14:31:59.149  6827  7071 E BluetoothAdapterService: File transfer profiles supported!!
09-08 14:31:59.150  6827  6827 D HeadsetStateMachine: max_hf_connections = 1
09-08 14:31:59.150  6827  6827 I bluedroid-qcom: get_profile_interface handsfree
09-08 14:31:59.152  6827  6827 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-08 14:31:59.153   312  1378 V AudioPolicyService: registerClient() client 0xb558a8c0, uid 1002
09-08 14:31:59.153   312  2145 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-08 14:31:59.153   312  2145 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 14:31:59.153   312  2145 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 14:31:59.153  6827  6827 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-08 14:31:59.154   312  1377 V AudioFlinger: registerClient() client 0xb5581610, pid 6827
09-08 14:31:59.154   312  1372 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 14:31:59.154   312  1372 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 14:31:59.154  6827  6827 V ToneGenerator: Create Track: 0xb4929480
09-08 14:31:59.154   312  1373 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 14:31:59.154   312  1373 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-08 14:31:59.154  6827  6827 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-08 14:31:59.155  6827  6827 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-08 14:31:59.156  1030  1886 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 14:31:59.156  1030  1886 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 14:31:59.156  1030  1886 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 14:31:59.156  1030  1886 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 14:31:59.156   312   312 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-08 14:31:59.156   312   312 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-08 14:31:59.156   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 14:31:59.156   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 14:31:59.156  6827  6827 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-08 14:31:59.156  6827  7077 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 14:31:59.156  6827  7077 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-08 14:31:59.156  6827  7077 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 14:31:59.156  6827  7077 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-08 14:31:59.156  1584  2074 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 14:31:59.156  1584  2074 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 14:31:59.156   312  1377 I AudioFlinger: isAudioPlaybackHookOn() false
09-08 14:31:59.156  1584  2074 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 14:31:59.157  1584  2074 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 14:31:59.157   312  2144 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-08 14:31:59.157   312  2144 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-08 14:31:59.157   312  2144 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 14:31:59.157   312  2144 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 14:31:59.157  1835  1851 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 14:31:59.157  1835  1851 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 14:31:59.157  6827  6827 V AudioSystem: getLatency() output 2, latency 50
09-08 14:31:59.157  6827  6827 V AudioSystem: getFrameCount() output 2, frameCount 960
09-08 14:31:59.157  6827  6827 V AudioTrack: createTrack_l() output 2 afLatency 50
09-08 14:31:59.157  1835  1851 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 14:31:59.157  1835  1851 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 14:31:59.157  3281  3300 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 14:31:59.157  3281  3300 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 14:31:59.157  3281  3300 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 14:31:59.157  3281  3300 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 14:31:59.157   312  1378 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-08 14:31:59.157   312  1378 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-08 14:31:59.157   312  1378 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-08 14:31:59.157   312  1378 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-08 14:31:59.157   312  1378 V AudioFlinger: createTrack() lSessionId: 21
09-08 14,:31:59.159  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
09-08 14:31:59.160  6827  6827 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-08 14:31:59.161   312   312 V AudioFlinger: acquiring 21 from 6827, for 6827
09-08 14:31:59.161   312   312 V AudioFlinger:  added new entry for 21
,09-08 14:31:59.165  6827  6827 V ToneGenerator: ToneGenerator INIT OK, time: 131034
09-08 14:31:59.165  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:31:59.166  6827  7102 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-08 14:31:59.166  6827  7102 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 14:31:59.166  6827  7102 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 14:31:59.166  6827  7102 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-08 14:31:59.167   312  2145 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6827
09-08 14:31:59.168   312  2145 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-08 14:31:59.168   312  2145 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-08 14:31:59.168   312  2145 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-08 14:31:59.168   312  2145 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-08 14:31:59.168   312  2145 V voice   : voice_set_parameters: exit with code(0)
09-08 14:31:59.168  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:31:59.168   312  2145 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-08 14:31:59.168   312  2145 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-08 14:31:59.168   312  2145 V msm8974_platform: platform_set_parameters: exit with code(0)
09-08 14:31:59.168   312  2145 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-08 14:31:59.168   312  2145 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-08 14:31:59.168   312  2145 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-08 14:31:59.168  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
09-08 14:31:59.169  6827  7102 V ToneGenerator: ToneGenerator destructor
09-08 14:31:59.169  6827  7102 V ToneGenerator: stopTone
09-08 14:31:59.169  6827  7102 V ToneGenerator: Delete Track: 0xb4929480
09-08 14:31:59.169  6827  7102 V AudioTrack: ~AudioTrack, releasing session id from 6827 on behalf of 6827
09-08 14:31:59.169   312  2144 V AudioPolicyService: AudioCommandThread() adding release output 2
09-08 14:31:59.169   312  2144 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-08 14:31:59.169   312  2144 V AudioFlinger: PlaybackThread::Track destructor
09-08 14:31:59.169   312  2144 V AudioFlinger: removeClient_l() pid 6827, calling pid 312
09-08 14:31:59.169   312  1377 V AudioFlinger: releasing 21 from 6827 for 6827
09-08 14:31:59.169   312  1377 V AudioFlinger:  decremented refcount to 0
09-08 14:31:59.169   312  1377 V AudioFlinger: purging stale effects
09-08 14:31:59.170   312  1269 V AudioPolicyService: AudioCommandThread() waking up
09-08 14:31:59.170   312  1269 V AudioPolicyService: AudioCommandThread() processing release output 2
09-08 14:31:59.170   312  1269 V AudioPolicyManager: releaseOutput() 2
09-08 14:31:59.170   312  1269 V AudioPolicyService: AudioCommandThread() going to sleep
09-08 14:31:59.170  6827  6827 D A2dpService: Received start request. Starting profile...
09-08 14:31:59.171  6827  6827 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 14:31:59.172  6827  6827 V Avrcp   : make
09-08 14:31:59.172  6827  6827 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-08 14:31:59.172  6827  6827 I bluedroid-qcom: get_profile_interface avrcp
09-08 14:31:59.175  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
09-08 14:31:59.175  6827  7071 V LGMDMManager: Create singleton instance
,09-08 14:31:59.178  6827  7071 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-08 14:31:59.182  6827  6827 V AudioManager: registerRemoteController: size of Media player list: 0
09-08 14:31:59.182  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
09-08 14:31:59.184  6827  6827 E AudioManager: No RCC entry present to update
09-08 14:31:59.184  6827  6827 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-08 14:31:59.187  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,09-08 14:31:59.188  6827  6827 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-08 14:31:59.189  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-08 14:31:59.189  6827  6827 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-08 14:31:59.191  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
09-08 14:31:59.192  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-08 14:31:59.194  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
09-08 14:31:59.197  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
09-08 14:31:59.200  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
09-08 14:31:59.203  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,09-08 14:31:59.207  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
09-08 14:31:59.210  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
09-08 14:31:59.213  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
09-08 14:31:59.216  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,09-08 14:31:59.220  7049  7104 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
09-08 14:31:59.221  7049  7104 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
09-08 14:31:59.222  7049  7104 I AlertUtils: set default noti to content://media/internal/audio/media/41
09-08 14:31:59.230  7081  7081 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-08 14:31:59.230  7081  7081 W LG Account v2.2: No ProfileInfo entries
09-08 14:31:59.231  7081  7081 I LG Account v2.2: isEnabled: false
09-08 14:31:59.231  7081  7081 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-08 14:31:59.231  7081  7081 I Feature : [Lifetracker]Country: EU
09-08 14:31:59.231  7081  7081 I Feature : [Lifetracker]Operator: OPEN
09-08 14:31:59.232  7081  7081 I Feature : [Lifetracker]Ranking support: false
09-08 14:31:59.232  7081  7081 I Feature : [Lifetracker]Comfort support: false
09-08 14:31:59.232  7081  7081 I Feature : [Lifetracker]Accessory: true
09-08 14:31:59.232  7081  7081 I Feature : [Lifetracker]Health device: true
09-08 14:31:59.232  7081  7081 I Feature : [Lifetracker]Extra Pedometer: false
09-08 14:31:59.232  7081  7081 I Feature : [Lifetracker]Blood glucose device: false
09-08 14:31:59.232  7081  7081 I Feature : [Lifetracker]Device Number: 3
09-08 14:31:59.238  7049  7104 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
09-08 14:31:59.245  6213  6213 D BluetoothPermissionRequest: onReceive
,09-08 14:31:59.250  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 14:31:59.254  1030  1578 I ActivityManager: Killing 6161:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-08 14:31:59.270  7049  7049 D MonthWidgetProvider: [onReceive]
09-08 14:31:59.270  7049  7049 D CalendarWidgetProvider: [onReceive]
09-08 14:31:59.270  7049  7049 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,09-08 14:31:59.271  7049  7113 W HolidayIntentService: onHandleIntent
09-08 14:31:59.272  7049  7049 D CalendarTypeController: [onUpdateAndInitCalendarTime]
09-08 14:31:59.273  7049  7113 D HolidayDataLoader: readJsonAsset : holiday.json
09-08 14:31:59.274  6295  6295 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-08 14:31:59.274  6295  6295 W System.err: android.os.DeadObjectException
09-08 14:31:59.274  6295  6295 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 14:31:59.274  6295  6295 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 14:31:59.274  6295  6295 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-08 14:31:59.274  6295  6295 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-08 14:31:59.274  6295  6295 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 14:31:59.274  6295  6295 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 14:31:59.274  6295  6295 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:31:59.275  6295  6295 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:31:59.275  6295  6295 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:31:59.275  6295  6295 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 14:31:59.275  6295  6295 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:59.275  6295  6295 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:59.275  6295  6295 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 14:31:59.275  6295  6295 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 14:31:59.275  6295  6295 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-08 14:31:59.275  6295  6295 W System.err: android.os.DeadObjectException
09-08 14:31:59.275  6295  6295 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 14:31:59.275  6295  6295 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 14:31:59.275  6295  6295 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-08 14:31:59.275  6295  6295 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-08 14:31:59.275  6295  6295 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 14:31:59.275  6295  6295 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 14:31:59.275  6295  6295 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:31:59.275  6295  6295 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:31:59.275  6295  6295 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:31:59.275  6295  6295 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 14:31:59.275  6295  6295 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:59.275  6295  6295 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:59.275  6295  6295 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 14:31:59.276  6295  6295 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 14:31:59.276  6295  6295 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-08 14:31:59.276  1030  1904 V SIM_STK : Menu title from STK is T-Mobile
09-08 14:31:59.276  1030  1904 V SIM_STK : Menu title from STK is T-Mobile
09-08 14:31:59.276  6295  6295 I QRemote : [RemoteControlManager,.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-08 14:31:59.328  7049  7113 E HolidayIntentService: onHandleIntent:holiday data empty
,09-08 14:31:59.471  1030  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_6161/cgroup.procs: No such file or directory
,09-08 14:31:59.472  1030  1046 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-08 14:31:59.484  1030  1941 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-08 14:31:59.485  6295  6295 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-08 14:31:59.486  6295  6295 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-08 14:31:59.517  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-08 14:31:59.535  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-08 14:31:59.537  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,09-08 14:31:59.537  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-08 14:31:59.537  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-08 14:31:59.538  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 14:31:59.538  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-08 14:31:59.538  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-08 14:31:59.538  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-08 14:31:59.538  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 14:31:59.538  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-08 14:31:59.545  6827  6827 I BluetoothA2dpServiceJni: classInitNative
09-08 14:31:59.545  6827  6827 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 14:31:59.546  6827  6827 D A2dpStateMachine: make
09-08 14:31:59.550  6827  6827 I bluedroid-qcom: get_profile_interface a2dp
09-08 14:31:59.551  6827  7118 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-08 14:31:59.561  6827  6827 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-08 14:31:59.562  6827  6827 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-08 14:31:59.563  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:31:59.564  6827  6827 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 14:31:59.567  6827  7117 D A2dpStateMachine: Enter Disconnected: -2
,09-08 14:31:59.571  6827  6827 D HidService: Received start request. Starting profile...
09-08 14:31:59.572  1030  1749 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7120 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-08 14:31:59.572  6827  6827 I bluedroid-qcom: get_profile_interface hidhost
09-08 14:31:59.572  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:31:59.575  6827  6827 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 14:31:59.577  6827  6827 D HealthService: Received start request. Starting profile...
09-08 14:31:59.583  7049  7049 D WeekWidgetProvider: [onReceive]
09-08 14:31:59.583  7049  7049 D CalendarWidgetProvider: [onReceive]
,09-08 14:31:59.583  7049  7049 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
09-08 14:31:59.585  7049  7049 D CalendarTypeController: [onUpdateAndInitCalendarTime]
09-08 14:31:59.591  6295  6295 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-08 14:31:59.591   344   344 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 486us total 21.123ms
09-08 14:31:59.592  6827  6827 I bluedroid-qcom: get_profile_interface health
09-08 14:31:59.593  6827  6827 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-08 14:31:59.593  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:31:59.594  6827  6827 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 14:31:59.596  6827  6827 D PanService: Received start request. Starting profile...
09-08 14:31:59.596  6827  6827 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 14:31:59.596  6827  6827 I bluedroid-qcom: get_profile_interface pan
,09-08 14:31:59.607  6827  6827 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-08 14:31:59.607  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:31:59.608  6827  6827 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-08 14:31:59.612   344   344 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 438us total 20.285ms
09-08 14:31:59.614  6827  6827 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 14:31:59.615  6827  6827 D BtGatt.GattService: Received start request. Starting profile...
09-08 14:31:59.615  6827  6827 D BtGatt.GattService: start()
09-08 14:31:59.616  6827  6827 I bluedroid-qcom: get_profile_interface gatt
09-08 14:31:59.617  6827  6827 D BtGatt.AdvertiseManager: advertise manager created
09-08 14:31:59.624  6295  6295 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-08 14:31:59.625  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7630
09-08 14:31:59.626  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:31:59.626  6827  6827 D HeadsetStateMachine: Proxy object connected
09-08 14:31:59.627  6827  6827 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-08 14:31:59.627  6827  6827 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-08 14:31:59.630  1030  1750 I ActivityManager: Killing 6490:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-08 14:31:59.631  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:31:59.631  6827  6827 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-08 14:31:59.632   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 19.465ms
09-08 14:31:59.633  6827  6827 V BluetoothMapService: BluetoothMapBinder()
09-08 14:31:59.633  6827  6827 D BluetoothMapService: Received start request. Starting profile...
09-08 14:31:59.633  6827  6827 D BluetoothMapService: start()
09-08 14:31:59.676  1030  1749 W libprocessgroup: failed to open /acct/uid_10011/pid_6490/cgroup.procs: No such file or directory
,09-08 14:31:59.687  2187  2187 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-08 14:31:59.689  6827  6827 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-08 14:31:59.690  6827  6827 D BluetoothMapEmailAppObserver: createReceiver()
,09-08 14:31:59.695  6827  6827 D BluetoothMapEmailAppObserver: initObservers()
09-08 14:31:59.695  6827  6827 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-08 14:31:59.705  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
,09-08 14:31:59.712  6827  6827 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 14:31:59.712  6827  7102 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-08 14:31:59.713  6827  7102 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 14:31:59.713  6827  7102 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-08 14:31:59.716  6827  6827 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 14:31:59.718  6987  6987 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,09-08 14:31:59.722  6827  6827 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 14:31:59.723  6594  6594 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:31:59
09-08 14:31:59.725  6594  6594 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 14:31:59.725  6594  6594 D Weather.Utils: 2 : All the weather widget is gone.
09-08 14:31:59.725  6827  6827 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 14:31:59.725  6827  6827 V PanService: [BTUI] SIM Extra State :ABSENT
09-08 14:31:59.727  6594  6594 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:31:59.728  6594  6594 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
09-08 14:31:59.728  6594  6594 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:31:59
09-08 14:31:59.729  6827  6827 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 14:31:59.733  2014  2014 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,09-08 14:31:59.733  6827  6827 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-08 14:31:59.734  6827  6827 V BluetoothMapService: Handler(): got msg=1
09-08 14:31:59.734  6827  7071 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-08 14:31:59.735  6827  7071 I bluedroid-qcom: enable
09-08 14:31:59.735  6827  7071 I bt_hci_bdroid: init
,09-08 14:31:59.735  6827  7147 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-08 14:31:59.735  6827  7147 I bt-btu  : btu_task pending for preload complete event
09-08 14:31:59.736  6827  7071 I bt_vendor: bt-vendor : init
09-08 14:31:59.736  2014  2830 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
09-08 14:31:59.736  6827  7071 I bt_vendor: bt-vendor : get_bt_soc_type
09-08 14:31:59.736  6827  7071 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-08 14:31:59.737  6827  7071 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-08 14:31:59.737  6827  7071 D bt_userial_mct: userial_init
09-08 14:31:59.737  2014  2830 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
09-08 14:31:59.737  2014  2830 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
09-08 14:31:59.737  6827  7071 D bt_hci_bdroid: set_power 1
09-08 14:31:59.737  6827  7071 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-08 14:31:59.737  6827  7071 I bt_vendor: Starting hciattach daemon
09-08 14:31:59.737  6827  7071 I bt_vendor: try to set true
09-08 14:31:59.740  6827  6827 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:59.726  7150  7150 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:59.726  7150  7150 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:31:59.740  7031  7031 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
09-08 14:31:59.740  7120  7120 D UEI.SmartControl: Quickset Services start...
09-08 14:31:59.740  7031  7031 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
09-08 14:31:59.743  7120  7120 I UEI.SmartControl: Manufacture = LGE
09-08 14:31:59.743  7120  7120 D UEI.SmartControl: Id = LGNevo
09-08 14:31:59.744  7120  7120 D UEI.SmartControl: File observer start...
09-08 14:31:59.745  6827  6827 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 14:31:59.745  6827  6827 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 14:31:59.745  6827  6827 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 14:31:59.745  6827  6827 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:59.745  6827  6827 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-08 14:31:59.747  7120  7120 E UEI.SmartControl: IR Port is disabled: false
,09-08 14:31:59.748  1584  1584 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
09-08 14:31:59.748  1584  1584 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
09-08 14:31:59.748  1584  1584 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
09-08 14:31:59.749  7120  7120 D UEI.SmartControl: Starting file observer...
09-08 14:31:59.749  7120  7120 D UEI.SmartControl: Extracting JNI libs...
09-08 14:31:59.749  7120  7120 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-08 14:31:59.753  2014  2830 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
09-08 14:31:59.753  2014  2830 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
09-08 14:31:59.754  7031  7031 V [BNRBootReceiver]: Boot Receiver Return
09-08 14:31:59.762  7152  7152 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-08 14:31:59.784  1030  1923 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7156 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 14:31:59.788  2014  2014 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
09-08 14:31:59.791  2014  5383 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
09-08 14:31:59.791  2014  5383 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
09-08 14:31:59.791  2014  5383 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
09-08 14:31:59.793  2014  5383 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
09-08 14:31:59.794  2014  5383 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
09-08 14:31:59.817  7178  7178 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-08 14:31:59.829  7179  7179 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-08 14:31:59.831  7156  7156 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 14:31:59.842  1030  1046 I ActivityManager: Killing 6239:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-08 14:31:59.847  7181  7181 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-08 14:31:59.853  7182  7182 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-08 14:31:59.859  7183  7183 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-08 14:31:59.866  7184  7184 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-08 14:31:59.876  7120  7120 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-08 14:31:59.876  7120  7120 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-08 14:31:59.876  7186  7186 I libmdmdetect: ESOC framework not supported
09-08 14:31:59.876  7120  7120 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-08 14:31:59.876  7186  7186 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-08 14:31:59.882  7186  7186 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-08 14:31:59.882  7186  7186 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-08 14:31:59.882  7186  7186 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-08 14:31:59.882  7186  7186 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-08 14:31:59.882  7186  7186 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-08 14:31:59.882  7186  7186 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-08 14:31:59.882  7186  7186 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-08 14:31:59.902  7120  7120 I UEI.SmartControl: --- Selecting new region: 6
09-08 14:31:59.903  7120  7120 I UEI.SmartControl: Model = LG-D855
,09-08 14:31:59.904  7120  7120 D UEI.SmartControl: QS Service created
09-08 14:31:59.913  1030  1045 W libprocessgroup: failed to open /acct/uid_10026/pid_6239/cgroup.procs: No such file or directory
09-08 14:31:59.916  7186  7187 E QC-QMI  : qmi_client [7186] 14: failed to locate client data
,09-08 14:31:59.916   480   480 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-08 14:31:59.916   480   480 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-08 14:31:59.933  7120  7120 I UEI.SmartControl: Service initServices...
,09-08 14:31:59.937  7120  7120 D UEI.SmartControl: QS start get config
09-08 14:32:00.007  7120  7120 D UEI.SmartControl: Loading JNI Libs...
,09-08 14:32:00.063  7188  7188 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-08 14:32:00.092  7189  7189 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-08 14:32:00.140  6827  7071 I bt_vendor: bluetooth satus is on
09-08 14:32:00.140  6827  7071 D bt_hci_bdroid: preload
09-08 14:32:00.140  6827  7149 D bt_userial_mct: userial_open(port:0)
09-08 14:32:00.140  6827  7149 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-08 14:32:00.141  6827  7149 I bt_vendor: Done intiailizing UART
09-08 14:32:00.141  6827  7149 I bt_vendor: Done intiailizing UART
09-08 14:32:00.141  6827  7149 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-08 14:32:00.142  6827  7149 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-08 14:32:00.142  6827  7147 I bt-btu  : btu_task received preload complete event
09-08 14:32:00.142  6827  7194 D bt_userial_mct: Entering userial_read_thread()
09-08 14:32:00.143  6827  7147 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-08 14:32:00.143  6827  7147 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-08 14:32:00.145  6827  7147 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_HCI
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 14:32:00.149  6827  7147 I         : BTE_InitTraceLevels -- TRC_BTIF
09-08 14:32:00.194  6827  7147 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-08 14:32:00.194  6827  7147 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0234061 
09-08 14:32:00.194  6827  7147 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0234061 
,09-08 14:32:00.207  6827  7075 E bt-btif : Calling BTA_HhEnable
09-08 14:32:00.207  6827  7147 W bt-l2cap: btif_storage_get_adapter_property service_mask
09-08 14:32:00.207  6827  7075 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-08 14:32:00.207  6827  7147 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-08 14:32:00.207  6827  7147 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-08 14:32:00.207  6827  7147 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,09-08 14:32:00.207  6827  7147 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-08 14:32:00.208  6827  7075 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-08 14:32:00.209  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-08 14:32:00.209  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
09-08 14:32:00.211  6827  7075 D BluetoothAdapterProperties: Name is: G3
09-08 14:32:00.213  6827  7075 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:32:00.213  6827  7075 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 14:32:00.214  6827  7075 D bt_hci_bdroid: postload
09-08 14:32:00.215  6827  7149 D bt_hci_bdroid: Used up Tx Cmd credits
,09-08 14:32:00.217  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.217  6827  7075 D bte_conf: Device ID record 1 : primary
09-08 14:32:00.217  6827  7075 D bte_conf:   vendorId            = 00c4
09-08 14:32:00.217  6827  7075 D bte_conf:   vendorIdSource      = 0001
09-08 14:32:00.217  6827  7075 D bte_conf:   product             = 13a1
09-08 14:32:00.217  6827  7075 D bte_conf:   version             = 1000
09-08 14:32:00.217  6827  7075 D bte_conf:   clientExecutableURL = 
09-08 14:32:00.217  6827  7075 D bte_conf:   serviceDescription  = 
09-08 14:32:00.217  6827  7075 D bte_conf:   documentationURL    = 
09-08 14:32:00.217  6827  7075 D bte_conf: bte_load_did_conf no section named DID2.
09-08 14:32:00.219  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.220  6827  7147 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-08 14:32:00.221  6827  7075 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 14:32:00.221  6827  7147 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 14:32:00.221  6827  7147 W bt-smp  : Plain text(LSB ~ MSB) = 8d dd 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 14:32:00.221  6827  7147 W bt-smp  : Encrypted text(LSB ~ MSB) = fc e6 b2 59 64 e9 af 53 62 da 31 1e 84 7e fb 8e 
09-08 14:32:00.221  6827  7071 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-08 14:32:00.221  6827  7071 D BluetoothAdapterProperties: ScanMode =  20
09-08 14:32:00.221  6827  7071 D BluetoothAdapterProperties: State =  11
09-08 14:32:00.222  6827  7071 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-08 14:32:00.222  6827  7071 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-08 14:32:00.216  7196  7196 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:32:00.216  7196  7196 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:32:00.222  6827  7071 D BluetoothAdapterProperties: Setting state to 12
09-08 14:32:00.222  6827  7071 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 14:32:00.223  6827  7149 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 14:32:00.223  6827  7147 W bt-btm  : Stopping oneshot timer
,09-08 14:32:00.227  1030  1112 D BluetoothManagerService: Message: 60
09-08 14:32:00.227  1030  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-08 14:32:00.227  1030  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-08 14:32:00.228  6827  7071 I BluetoothAdapterState: Entering On State
09-08 14:32:00.228  1835  3409 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:32:00.231  6827  7071 D LGBluetoothServiceAdapter: [BTUI] OnState
09-08 14:32:00.231  6827  7071 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-08 14:32:00.231  6827  7071 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-08 14:32:00.231  6827  7075 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-08 14:32:00.234  6827  7071 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-08 14:32:00.237  1835  1835 D BluetoothHeadset: Proxy object connected
09-08 14:32:00.237  6213  6232 D BluetoothPan: onBluetoothStateChange on: true
09-08 14:32:00.237  6213  6232 D BluetoothPan: onBluetoothStateChange call bindService
09-08 14:32:00.238  6827  7194 E bt_mct  : hci lib postload completed
,09-08 14:32:00.244  1030  1112 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:32:00.245  6213  6213 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 14:32:00.245  6213  6213 D PanProfile: Bluetooth service connected
09-08 14:32:00.247  1835  3410 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:32:00.248  1030  1030 D BluetoothA2dp: Proxy object connected
09-08 14:32:00.251  1835  1835 D BluetoothHeadset: Proxy object connected
09-08 14:32:00.251  6213  6234 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 14:32:00.254  6213  6232 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 14:32:00.257  6213  7198 D BluetoothMap: onBluetoothStateChange: up=true
09-08 14:32:00.259  6213  6213 D BluetoothInputDevice: Proxy object connected
09-08 14:32:00.259  6213  6213 D HidProfile: Bluetooth service connected
09-08 14:32:00.262  1030  1112 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:32:00.262  1030  1030 D BluetoothHeadset: Proxy object connected
09-08 14:32:00.262  1835  1850 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 14:32:00.264  6213  6213 D BluetoothMap: Proxy object connected
09-08 14:32:00.264  6213  6213 D MapProfile: Bluetooth service connected
09-08 14:32:00.264  6213  6213 D BluetoothMap: getConnectedDevices()
09-08 14:32:00.265  6827  7147 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 14:32:00.265  6827  7147 W bt-smp  : Plain text(LSB ~ MSB) = 7a 41 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 14:32:00.265  6827  7147 W bt-smp  : Encrypted text(LSB ~ MSB) = 90 95 ee a4 33 fb 0e 5a e1 5f 2d 10 82 f3 c2 85 
09-08 14:32:00.266  6827  7147 W bt-btm  : Stopping oneshot timer
09-08 14:32:00.266  6827  7077 V BluetoothMapService: getConnectedDevices()
09-08 14:32:00.268  1835  1835 D BluetoothHeadset: Proxy object connected
09-08 14:32:00.268  1030  1112 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-08 14:32:00.268  1030  1112 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-08 14:32:00.270  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-08 14:32:00.270  1030  1112 D BluetoothManagerService: Message: 40
09-08 14:32:00.271  1030  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-08 14:32:00.271  1584  1584 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 14:32:00.276  1924  1924 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:00.276  1924  2103 D LGBluetoothAPIService: Message: 1
09-08 14:32:00.276  1924  2103 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-08 14:32:00.276  1924  2103 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-08 14:32:00.276  1924  2103 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-08 14:32:00.278  6827  7071 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-08 14:32:00.282  6827  6827 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:00.282  6827  6827 D BluetoothMapService: STATE_ON
09-08 14:32:00.283  5982  5982 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-08 14:32:00.285  6827  7147 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 14:32:00.285  6827  7147 W bt-smp  : Plain text(LSB ~ MSB) = 08 42 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 14:32:00.285  6827  7147 W bt-smp  : Encrypted text(LSB ~ MSB) = 84 ff ec 2e cd bf d8 b8 15 8c 4b 5c cc ed a8 5d 
,09-08 14:32:00.285  6827  7147 W bt-btm  : Stopping oneshot timer
09-08 14:32:00.288  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:00.288  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:00.288  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:00.288  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:00.288  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:00.288  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.288  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:00.288  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:00.289  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.291  7202  7202 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-08 14:32:00.294  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:00.294  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:00.294  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:00.294  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:00.294  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:00.294  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.294  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:00.294  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:00.295  6827  7147 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 14:32:00.295  6827  7147 W bt-smp  : Plain text(LSB ~ MSB) = 3b 9a 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 14:32:00.295  6827  7147 W bt-smp  : Encrypted text(LSB ~ MSB) = 67 9f 27 03 c3 87 75 1d 0a 00 d3 c2 fc d7 43 0c 
09-08 14:32:00.295  6827  7147 W bt-btm  : Stopping oneshot timer
09-08 14:32:00.296  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.296  6213  6213 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-08 14:32:00.298  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:32:00.298  6827  6827 V BluetoothPbapService: Pbap Service onCreate
09-08 14:32:00.299  6827  6827 V BluetoothPbapService: Starting PBAP service
09-08 14:32:00.300  6827  6827 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-08 14:32:00.300  6827  6827 V BluetoothPbapService: Pbap Service onBind
09-08 14:32:00.301  1030  1112 D BluetoothManagerService: Message: 30
09-08 14:32:00.302  6827  6827 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:00.302  6827  6827 V BluetoothPbapService: state: 12
09-08 14:32:00.302  6827  6827 V BluetoothMapService: Handler(): got msg=1
09-08 14:32:00.303  6827  6827 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-08 14:32:00.303  6827  6827 V BluetoothPbapService: Handler(): got msg=1
09-08 14:32:00.303  6213  6213 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-08 14:32:00.304  6827  7203 D BluetoothMapMasInstance: MAS initSocket()
09-08 14:32:00.305  6827  7203 D BluetoothMapMasInstance:   masId = 00
09-08 14:32:00.305  6827  7203 D BluetoothMapMasInstance:   msgTypes = 0e
09-08 14:32:00.305  6827  7203 D BluetoothMapMasInstance:   masName = SMS/MMS
09-08 14:32:00.305  6827  7203 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,09-08 14:32:00.306  1030  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:00.306  6827  6827 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-08 14:32:00.308  6827  7203 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:32:00.308  6827  7204 V BluetoothPbapService: Pbap Service initSocket
09-08 14:32:00.309  6827  7203 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-08 14:32:00.309  1030  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:00.309  6827  7203 V BluetoothMapMasInstance: Succeed to create listening socket 
09-08 14:32:00.309  6827  7203 D BluetoothMapMasInstance: Accepting socket connection...
09-08 14:32:00.309  6827  7147 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 14:32:00.309  6827  7147 W bt-smp  : Plain text(LSB ~ MSB) = d5 5a 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 14:32:00.309  6827  7147 W bt-smp  : Encrypted text(LSB ~ MSB) = 12 26 94 38 72 0d 57 0b a1 ad e6 de 4a 28 61 5a 
09-08 14:32:00.309  6827  7147 W bt-btm  : Stopping oneshot timer
09-08 14:32:00.310  6827  7204 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:32:00.312  1030  1112 D BluetoothManagerService: Message: 30
09-08 14:32:00.312  6827  7204 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-08 14:32:00.312  6827  7204 V BluetoothPbapService: Succeed to create listening socket 
09-08 14:32:00.312  6827  7204 V BluetoothPbapService: Accepting socket connection...
09-08 14:32:00.318  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.318  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:00.318  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:00.318  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:00.318  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:00.318  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f96de9 removed from the list
09-08 14:32:00.319  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:00.319  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ce6fa6e removed from the list
09-08 14:32:00.319  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:00.319  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:00.326  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:32:00.326  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16daf99c added. We now have 2 listener(s)
09-08 14:32:00.326  1030  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:00.331  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 14:32:00.331  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:32:00.331  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 14:32:00.331  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:32:00.332  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1df1ffa5 added. We now have 2 listener(s)
09-08 14:32:00.332  5982  6084 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:32:00.334  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:32:00.335  6213  6213 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-08 14:32:00.336  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:00.337  6213  6213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-08 14:32:00.341  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:32:00.341  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:00.341  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:00.341  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:00.341  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:00.341  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.341  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:00.341  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:00.342  6213  6213 D BluetoothPbap: Proxy object connected
09-08 14:32:00.342  6827  6827 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-08 14:32:00.342  6213  6213 D PbapServerProfile: Bluetooth service connected
09-08 14:32:00.342  6213  6213 D BluetoothA2dp: Proxy object connected
09-08 14:32:00.342  6827  6827 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:32:00.342  6827  6827 V BluetoothPbapReceiver: ***********state = 12
09-08 14:32:00.343  6213  6213 D A2dpProfile: Bluetooth service connected
09-08 14:32:00.345  6213  6213 D BluetoothHeadset: Proxy object connected
09-08 14:32:00.346  6213  6213 D HeadsetProfile: Bluetooth service connected
09-08 14:32:00.346  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.346  5982  6084 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:32:00.349  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.351  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.352  1030  1749 D WifiServiceImplEx: setWifiEnabled: false pid=5982, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 14:32:00.352  1030  1749 D WifiService: setWifiEnabled: false pid=5982, uid=10118
09-08 14:32:00.352  1030  1749 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-08 14:32:00.352  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 14:32:00.353  2187  2187 D c       : Getting all permits...
09-08 14:32:00.353  2187  2187 D a       : Opening database...
09-08 14:32:00.356  6213  6213 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:32:00.364  2187  2187 D a       : Opening database auth.proximity.permit_store...
09-08 14:32:00.366  2187  2187 D a       : Closing database...
,09-08 14:32:00.377  6213  6213 D BluetoothPermissionRequest: onReceive
,09-08 14:32:00.379  6213  6213 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-08 14:32:00.381  6213  6213 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 14:32:00.384  6827  6827 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-08 14:32:00.385  6827  6827 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-08 14:32:00.390  6827  6827 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-08 14:32:00.406  6827  6827 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-08 14:32:00.406  6827  6827 V BtOppService: onCreate
,09-08 14:32:00.409  1030  1408 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-08 14:32:00.410  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:32:00.410  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-08 14:32:00.410  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:32:00.410  1030  1030 D Ulp_jni : JNI:system_update. Event-4
09-08 14:32:00.410  1030  1408 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-08 14:32:00.411  1030  1408 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-08 14:32:00.411  6827  6827 V BluetoothOppNotification: send message
09-08 14:32:00.411  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-08 14:32:00.411  1030  1408 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 14:32:00.411  1030  1408 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:32:00.411  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 14:32:00.412  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 14:32:00.412  1030  1408 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 14:32:00.412  6827  7075 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 14:32:00.413  6827  7075 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-08 14:32:00.414  6827  7075 D BluetoothAdapterProperties: Scan Mode:21
09-08 14:32:00.414  6827  7075 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-08 14:32:00.414  6827  6827 V BtOppService: Starting RfcommListener
09-08 14:32:00.416  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.416  1030  1408 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 14:32:00.416  1030  1370 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.416  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.417  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 14:32:00.417  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 14:32:00.417  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 14:32:00.417  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 14:32:00.417  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.417  1030  1408 D WifiNative-wlan0: SET ps 1: returned true
09-08 14:32:00.418  6827  6827 D BluetoothOppPreference: Dumping Names:  
09-08 14:32:00.418  1030  6847 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.418  6827  6827 D BluetoothOppPreference: {}
09-08 14:32:00.418  6827  6827 D BluetoothOppPreference: Dumping Channels:  
09-08 14:32:00.418  6827  6827 D BluetoothOppPreference: {}
09-08 14:32:00.419  6827  6827 V BtOppService: onStartCommand
,09-08 14:32:00.421   308   888 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:32:00.432  6827  6827 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:32:00.434  6827  6827 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-08 14:32:00.437  6827  7219 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-08 14:32:00.438  6827  6827 V BluetoothOppNotification: new notify threadi!
09-08 14:32:00.438  6827  7219 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-08 14:32:00.438  6827  6827 V BluetoothOppNotification: send delay message
09-08 14:32:00.439  6827  6827 V BtOppService: start RfcommListener
09-08 14:32:00.439  6827  7216 V BtOppService: Deleted complete outbound shares, number =  0
09-08 14:32:00.442  1030  1464 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 14:32:00.442  1030  1464 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-08 14:32:00.443  6827  6827 V BtOppService: RfcommListener started
09-08 14:32:00.443  6827  7221 V BtOppRfcommListener: Starting RFCOMM listener....
,09-08 14:32:00.445  1030  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:00.446  6827  7221 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:32:00.446  6827  7221 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-08 14:32:00.447  6827  7221 V BtOppRfcommListener: Started RFCOMM listener....
09-08 14:32:00.447  6827  7221 I BtOppRfcommListener: Accept thread started.
09-08 14:32:00.447  6827  7221 V BtOppRfcommListener: Accepting connection...
09-08 14:32:00.448  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:00.448  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:00.450  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-08 14:32:00.451  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:00.453  1030  1030 D WifiHS20: hidePasspointNotification off =false
09-08 14:32:00.453  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:00.454  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:00.454  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:32:00.454  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:32:00.456  1030  1030 D WifiHS20: hidePasspointNotification off =false
,09-08 14:32:00.458  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:00.458  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:00.458  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:32:00.459  6827  7220 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-08 14:32:00.465  6827  7219 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b59271e on behalf of 
09-08 14:32:00.466  6827  7216 V BtOppService: Deleted complete inbound failed shares, number = 0
09-08 14:32:00.466  6827  7216 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-08 14:32:00.467  6827  7220 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e14fbff on behalf of 
09-08 14:32:00.472  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:32:00.472  6827  6827 V BluetoothFtpService: Ftp Service onCreate
09-08 14:32:00.472  6827  6827 I BluetoothFtpService: Ftp Service onCreate
09-08 14:32:00.472  6827  6827 V BluetoothFtpService: Ftp Service onStartCommand
09-08 14:32:00.473  6827  6827 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:32:00.473  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:00.473  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:00.473  6827  6827 V BluetoothFtpService: Starting Listening on sockets
09-08 14:32:00.473  6827  6827 V BtOppService: ContentObserver received notification
09-08 14:32:00.473  6827  6827 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 14:32:00.473  6827  6827 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 14:32:00.473  6827  6827 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 14:32:00.473  6827  6827 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:00.473  6827  6827 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-08 14:32:00.473  6827  6827 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-08 14:32:00.474  6827  7216 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f6cd815 on behalf of 
09-08 14:32:00.474  6827  7220 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-08 14:32:00.475  6827  7220 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-08 14:32:00.476  6827  7219 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-08 14:32:00.476  6827  7219 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-08 14:32:00.477  6827  7220 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@306c972a on behalf of 
09-08 14:32:00.478  6827  7219 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8c7591b on behalf of 
09-08 14:32:00.478  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:00.479  6827  7219 V BluetoothOppNotification: update too frequent, put in queue
09-08 14:32:00.480  6827  7220 V BluetoothOppNotification: outbound: succ-0  fail-0
09-08 14:32:00.484  6827  7219 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-08 14:32:00.485  6827  7220 V BluetoothOppNotification: outbound notification was removed.
09-08 14:32:00.485  6827  7220 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-08 14:32:00.486  1030  1923 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7225 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-08 14:32:00.486  6827  7220 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fe95ab8 on behalf of 
09-08 14:32:00.487  6827  7220 V BluetoothOppNotification: inbound: succ-0  fail-0
09-08 14:32:00.488  6827  7220 V BluetoothOppNotification: inbound notification was removed.
09-08 14:32:00.488  6827  7220 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-08 14:32:00.490  1030  1464 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-08 14:32:00.490  1030  1464 D DSQN    : disableDataServiceNotify
09-08 14:32:00.490  1030  1464 D DSQN    : stop dsqn bin
09-08 14:32:00.490  1030  1370 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.490  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.490  1030  1370 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2aab93ad
09-08 14:32:00.490  1030  1408 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:00.490  1030  1370 D LGWifiP2pService: P2pDisablingState
09-08 14:32:00.491  1030  1370 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.491  1030  1370 D LGWifiP2pService: p2p socket connection lost
09-08 14:32:00.491  1030  1370 D LGWifiP2pService: P2pDisabledState
09-08 14:32:00.491  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:00.491  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:00.492  6827  6827 V BtOppService: ContentObserver received notification
09-08 14:32:00.492  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 1
09-08 14:32:00.492  6827  6827 V BluetoothFtpService: Handler(): got msg=1
09-08 14:32:00.492  1030  1030 D RttService: SCAN_AVAILABLE : 1
09-08 14:32:00.493  6827  7220 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@324fe091 on behalf of 
09-08 14:32:00.493  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-08 14:32:00.493  1924  1924 D WfdsService: WifiP2pState is changed : false
09-08 14:32:00.493  1030  1408 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:00.493  1924  2250 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-08 14:32:00.493  1924  2250 D WfdsService: Set the WFDS Monitor: false
09-08 14:32:00.493  6827  6827 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-08 14:32:00.493  6827  6827 V BluetoothFtpService: Ftp Service initSocket
09-08 14:32:00.493  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:00.494  1924  2250 D WfdsMonitor: WFDS Monitor is stopped
09-08 14:32:00.494  1924  2250 D WfdsService: STATE : WfdsDisabledState - enter
09-08 14:32:00.494  1924  6485 D CtrlSupplicant: Received on exit socket, terminate
09-08 14:32:00.494  1924  6485 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-08 14:32:00.494  1924  6485 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-08 14:32:00.494  1924  6485 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-08 14:32:00.494  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:00.494  1924  2251 W WfdsSession:Controller: DefaultState - msg [9441355] is, not handled
09-08 14:32:00.494  1924  2250 W WfdsService: DefaultState - msg [9445378] is not handled
09-08 14:32:00.494  1030  1538 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.494  1030  1539 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.495  1030  1408 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 14:32:00.497  1030  1464 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-08 14:32:00.497  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:00.497  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:00.497  1030  1464 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:00.497  1030  1464 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-08 14:32:00.497  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.497  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 14:32:00.497  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.497  1030  6846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-08 14:32:00.497  1030  1464 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-08 14:32:00.497  1030  1464 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 14:32:00.498  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-08 14:32:00.498  6827  7236 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-08 14:32:00.498  6827  7236 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-08 14:32:00.499  1030  1408 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-08 14:32:00.499  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 14:32:00.499  1030  1370 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.499  1030  1370 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.499  6459  6459 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 14:32:00.500  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 14:32:00.500  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 14:32:00.500  1030  1408 D WifiNative-wlan0: SET ps 1: returned true
09-08 14:32:00.501   308   888 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:32:00.501  1030  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:00.501  6827  7236 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@394fbf6 on behalf of 
09-08 14:32:00.502  6827  6827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:32:00.502  6827  7236 V BluetoothOppNotification: update too frequent, put in queue
09-08 14:32:00.502  1030  1464 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:00.502  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 14:32:00.503  6827  6827 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
09-08 14:32:00.503  6827  7236 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-08 14:32:00.503  6827  6827 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-08 14:32:00.504  6827  7243 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-08 14:32:00.505  1030  1369 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 14:32:00.505  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 14:32:00.506  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 14:32:00.506  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 14:32:00.506  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 14:32:00.507  1030  1464 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:00.507  1030  1464 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:00.507  1030  1464 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:00.507  1030  1464 D NetworkManagementService: Removing idletimer
09-08 14:32:00.507  1030  1464 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:00.507  1030  1464 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-08 14:32:00.508  1835  1835 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-0,8 14:32:00.508  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 14:32:00.508  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 14:32:00.508  1030  1369 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 14:32:00.508  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 14:32:00.508  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 14:32:00.508  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 14:32:00.511  6827  6827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3315a2c2
09-08 14:32:00.511  6827  6827 V BluetoothSapService: Sap Service onCreate
,09-08 14:32:00.513  1030  1408 D WifiNative-p2p0: doBoolean: TERMINATE
09-08 14:32:00.515  1030  1030 D WifiHS20: hidePasspointNotification off =false
09-08 14:32:00.517  6827  6827 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:00.517  6827  6827 V BluetoothSapService: state: 12
09-08 14:32:00.517  6827  6827 V BluetoothSapService: Starting SAP server process
09-08 14:32:00.518  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:00.518  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:00.518  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:32:00.518  1030  1408 D WifiNative-p2p0: TERMINATE: returned true
09-08 14:32:00.518  1030  1408 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 14:32:00.518  1030  1408 E WifiStateMachine: useWiFiOffloading() : false
09-08 14:32:00.518  1030  1408 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 14:32:00.505  7245  7245 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:32:00.505  7245  7245 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:32:00.523  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-08 14:32:00.526  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-08 14:32:00.519  1030  1408 E WifiStateMachine:  SupplicantStoppingState CMD_RSSI_POLL 2 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3655] from screen [on:0 period:164137991] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 14:32:00.527  1030  1408 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 2 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:164137999] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 14:32:00.528  1030  1408 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:00.528  1030  1408 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:00.529  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:00.529  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:00.529  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:00.529  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:32:00.529  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:00.529  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:00.529  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:00.529  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:32:00.530  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:32:00.530  7245  7245 V BT_SAP  : Event pipe created
09-08 14:32:00.530  7245  7245 V BT_SAP  : create_server_socket qcom.sap.server
09-08 14:32:00.530  7245  7245 V BT_SAP  : created socket fd 6
,09-08 14:32:00.533  6827  6827 V BluetoothSapService: SAP Service startRfcommListenerThread
09-08 14:32:00.534  6827  7246 V BluetoothSapService: Sap Service initRfcommSocket
09-08 14:32:00.535  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:00.535  1030  1030 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-08 14:32:00.536  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:00.536  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:00.536  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:00.536  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:32:00.536  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:00.536  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:00.536  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:00.536  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:32:00.537  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:32:00.538  1030  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:00.539  6827  7246 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:32:00.540  6827  7246 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-08 14:32:00.540  6827  7246 V BluetoothSapService: Succeed to create listening socket 
09-08 14:32:00.540  6827  7246 V BluetoothSapService: Accepting socket connection...
,09-08 14:32:00.547  1584  1584 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:32:00.548  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:00.550  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:32:00.564  1584  1584 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:32:00.565  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:00.565  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:00.565  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 14:32:00.565  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:00.566  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:00.567  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:00.570  7120  7120 I UEI.SmartControl: Supports setup maps: true
09-08 14:32:00.573  7120  7120 D UEI.SmartControl: QS start statue = true Error code = 0
09-08 14:32:00.573  7120  7120 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-08 14:32:00.573  7120  7120 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-08 14:32:00.573  7120  7120 I UEI.SmartControl: ### init IR Blaster...
09-08 14:32:00.577  7120  7120 D serial_port: Configuring serial port
,09-08 14:32:00.580  7120  7120 E UEI.SmartControl: UEIBLaster setting for 616
09-08 14:32:00.580  7120  7120 I UEI.SmartControl: Setting serial record hearder size = 2
,09-08 14:32:00.580  7120  7120 I UEI.SmartControl: configuring settings for MAXQ616
09-08 14:32:00.580  7120  7120 I UEI.SmartControl: Get version...
09-08 14:32:00.583  7225  7225 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:32:00.586  7225  7225 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:32:00.586  7225  7225 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:32:00.588  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:00.592  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 14:32:00.593  6459  6459 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-08 14:32:00.593  6459  6459 I wpa_supplicant: monitor socket send errors count : 1
09-08 14:32:00.593  6459  6459 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1924-4\x00 that cannot receive messages
09-08 14:32:00.594  1030  6480 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-08 14:32:00.594  1030  6480 D WifiMonitor: Dropping event because (p2p0) is stopped
09-08 14:32:00.597  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:32:00.597  7120  7249 D UEI.SmartControl: serial port data available: 21
09-08 14:32:00.597  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:00.598  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 14:32:00.600  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:32:00.603  7225  7225 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:32:00.603  7225  7225 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:32:00.603  7225  7225 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:32:00.604  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:00.608  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:00.612  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:32:00.613  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:00.614  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 14:32:00.616  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:32:00.619  7225  7225 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:32:00.619  7225  7225 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:32:00.619  7225  7225 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:32:00.622  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:00.624  7120  7120 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-08 14:32:00.624  7120  7120 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-08 14:32:00.624  7120  7120 I UEI.SmartControl: QS saving settings...
09-08 14:32:00.625  7120  7120 D UEI.SmartControl: IR Blaster version: 25672567
,09-08 14:32:00.626  6459  6459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 14:32:00.627  6459  6459 W wpa_supplicant: USIM:  scard_deinit function
09-08 14:32:00.628  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,09-08 14:32:00.628  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 14:32:00.628  1030  6480 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 14:32:00.628  1030  6480 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-08 14:32:00.628  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:32:00.628  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:32:00.629  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:00.629  1030  1408 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=132485
09-08 14:32:00.629  1030  1112 D Tethering: InitialState.processMessage what=4
09-08 14:32:00.630  1030  1408 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=132486
09-08 14:32:00.630  1030  1408 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=132486  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-08 14:32:00.631  1030  1408 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=132487  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-08 14:32:00.631  1030  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 14:32:00.632  1030  6847 D DhcpStateMachine: StoppedState
09-08 14:32:00.632  1030  6847 D DhcpStateMachine: StoppedState{ when=-132ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:00.632  1030  1408 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:00.633  1030  1408 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:00.633  1030  1408 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-08 14:32:00.633  1030  1408 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-08 14:32:00.638  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:32:00.638  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:00.639  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 14:32:00.642  7120  7249 D UEI.SmartControl: serial port data available: 4
09-08 14:32:00.666  1584  1584 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-08 14:32:00.666  1584  1584 I KeyguardUpdateMonitor: called onTimeUpdated()
09-08 14:32:00.666  1584  1584 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-08 14:32:00.667  1584  1584 I [SystemUI]Clock: called onTimeUpdated()
09-08 14:32:00.667  1584  1584 I LgeClockWidgetControlView: called onTimeUpdated()
09-08 14:32:00.667  1584  1584 I [SystemUI]DateView: called onTimeUpdated()
09-08 14:32:00.668  1584  1584 I [SystemUI]DateView: called onTimeUpdated()
09-08 14:32:00.668  1584  1584 D KeyguardUpdateMonitor: handleTimeUpdate
09-08 14:32:00.674  7120  7253 I UEI.SmartControl: Device manager: loading config....
09-08 14:32:00.675  7120  7253 D UEI.SmartControl: ----------- loading internal config...
09-08 14:32:00.677  7120  7120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-08 14:32:00.684  7120  7253 E UEI.SmartControl: Loading SETTINGS...
,09-08 14:32:00.693  7120  7253 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-08 14:32:00.696  1030  1578 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7255 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-08 14:32:00.697  1030  1578 I ActivityManager: Killing 6548:com.android.chrome/u0a57 (adj 15): empty #17
09-08 14:32:00.712  7120  7252 I UEI.SmartControl: Notify AllClients services are ready: 0
09-08 14:32:00.712  7120  7252 D UEI.SmartControl: -----service ready thread exits
,09-08 14:32:00.733  6459  6459 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-08 14:32:00.733  1030  6480 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,09-08 14:32:00.733  1030  6480 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-TERMINATING 
09-08 14:32:00.733  1030  6480 D WifiMonitor: Disconnecting from the supplicant, no more events
09-08 14:32:00.734  1030  1408 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 52 0
09-08 14:32:00.743  1030  1749 W libprocessgroup: failed to open /acct/uid_10057/pid_6548/cgroup.procs: No such file or directory
09-08 14:32:00.744  7120  7120 E UEI.SmartControl: Services init done
09-08 14:32:00.744  7120  7120 D UEI.SmartControl: QS Service init finished
09-08 14:32:00.744  7120  7120 D UEI.SmartControl: QS Service version name: 2.1.91
09-08 14:32:00.744  7120  7120 D UEI.SmartControl: QS Service version code: 201091
,09-08 14:32:00.745  7120  7120 D UEI.SmartControl: Service requested: Control
09-08 14:32:00.751  1030  1959 I ActivityManager: Killing 6570:com.lge.drmservice/u0a62 (adj 15): empty #17
09-08 14:32:00.752  6295  6295 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,09-08 14:32:00.752  7120  7137 I UEI.SmartControl: ------ IControl API: 11
09-08 14:32:00.753  7120  7137 I UEI.SmartControl: Registering callback...
09-08 14:32:00.754  7120  7140 I UEI.SmartControl: ------ IControl API: 19
09-08 14:32:00.755  7120  7140 I UEI.SmartControl: Registering Services Ready callback...
09-08 14:32:00.755  7120  7140 I UEI.SmartControl: Notify client services are ready...
09-08 14:32:00.756  6295  6312 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-08 14:32:00.756  6295  6332 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-08 14:32:00.756  6295  6332 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-08 14:32:00.757  6295  6295 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-08 14:32:00.757  6295  6295 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-08 14:32:00.757  7120  7137 I UEI.SmartControl: ------ IControl API: 8
09-08 14:32:00.758  6295  6295 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-08 14:32:00.758  6295  6295 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-08 14:32:00.758  6295  6295 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-08 14:32:00.758  6295  6295 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-08 14:32:00.759  6295  6295 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-08 14:32:00.759  6295  6295 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-08 14:32:00.792  1030  1886 W libprocessgroup: failed to open /acct/uid_10062/pid_6570/cgroup.procs: No such file or directory
09-08 14:32:00.793  7120  7120 D UEI.SmartControl: Internal service binding...
09-08 14:32:00.794  6295  6295 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-08 14:32:00.803  7225  7225 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:32:00.806  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:32:00.812  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:00.829  7255  7274 W FormManager: Network not available. Please check & try again.
,09-08 14:32:00.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:32:00.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:32:00.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:32:00.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:32:00.832  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:32:00.833  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:32:00.833  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-08 14:32:00.833  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:32:00.833  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:32:00.833  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:32:00.833  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:32:00.840  1030  1408 D WifiOffDelayIfNotUsed: stopMonitoring
09-08 14:32:00.840  1030  1408 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 14:32:00.840  1030  1408 E WifiStateMachine: useWiFiOffloading() : false
09-08 14:32:00.840  1030  1408 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 14:32:00.840  1924  1924 D WfdsService: Supplicant Connection state is changed : false
09-08 14:32:00.841  1924  2250 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-08 14:32:00.841  1924  2250 D WfdsService: Set the WFDS Monitor: false
09-08 14:32:00.841  1924  2250 D WfdsMonitor: WFDS Monitor is stopped
09-08 14:32:00.842  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-08 14:32:00.843  6295  6295 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-08 14:32:00.843  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-08 14:32:00.843  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:00.843  1030  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-08 14:32:00.843  1030  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,09-08 14:32:00.845  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.846  2473  2473 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:00.847  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-08 14:32:00.848  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.849  6295  6295 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 14:32:00.849  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-08 14:32:00.851  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-08 14:32:00.852  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-08 14:32:00.852  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-08 14:32:00.852  6295  6295 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473337920852]
09-08 14:32:00.857  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-08 14:32:00.858  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-08 14:32:00.860  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:32:00.864  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:32:00.867  6295  7277 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
09-08 14:32:00.871  4152  7278 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 14:32:00.873  7225  7225 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-08 14:32:00.873  7225  7225 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:32:00.873  7225  7225 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:32:00.874  7255  7275 V FormManager: Network unavailable.
09-08 14:32:00.875  4152  7279 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:32:00.875  4152  7279 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:32:00.878  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:00.882  7255  7275 V FormManager: Network unavailable.
,09-08 14:32:00.887  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:00.899  7255  7280 W FormManager: Network not available. Please check & try again.
,09-08 14:32:00.902  6295  6295 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-08 14:32:00.903  6295  6295 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 14:32:00.903  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-08 14:32:00.903  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-08 14:32:00.904  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-08 14:32:00.904  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-08 14:32:00.904  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-08 14:32:00.906  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
09-08 14:32:00.910  7255  7281 V FormManager: Network unavailable.
,09-08 14:32:00.913  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.914  7255  7281 V FormManager: Network unavailable.
09-08 14:32:00.914  1030  1904 D WifiServiceImplEx: setWifiEnabled: true pid=5982, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 14:32:00.915  1030  1904 D WifiService: setWifiEnabled: true pid=5982, uid=10118
09-08 14:32:00.915  1030  1904 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-08 14:32:00.919  1030  1905 I ActivityManager: Killing 6612:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-08 14:32:00.927  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-08 14:32:00.927  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:32:00.927  1030  1030 D Ulp_jni : JNI:system_update. Event-4
09-08 14:32:01.028  1030  1923 W libprocessgroup: failed to open /acct/uid_10093/pid_6612/cgroup.procs: No such file or directory
,09-08 14:32:01.044  1030  1408 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-08 14:32:01.045  1030  1408 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-08 14:32:01.048  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,09-08 14:32:01.048  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-08 14:32:01.048  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-08 14:32:01.049  1030  1408 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-08 14:32:01.049  1030  1408 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,09-08 14:32:01.049  1030  1408 E WifiHW  : unknown target_country: EU , set to default,
,09-08 14:32:01.049  1030  1408 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-08 14:32:01.049  1030  1408 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-08 14:32:01.049  1030  1408 I WifiUtil: gEnableBmps=1
,09-08 14:32:01.398  1030  1046 I ActivityManager: Killing 6667:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-08 14:32:01.441  6827  6827 V BluetoothOppNotification: new notify threadi!
,09-08 14:32:01.441  6827  6827 V BluetoothOppNotification: send delay message
,09-08 14:32:01.447  6827  7293 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-08 14:32:01.448  6827  7293 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@180ce182 on behalf of 
09-08 14:32:01.449  6827  7293 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-08 14:32:01.450  6827  7293 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-08 14:32:01.452  6827  7293 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16bdd093 on behalf of 
09-08 14:32:01.452  6827  7293 V BluetoothOppNotification: outbound: succ-0  fail-0
09-08 14:32:01.454  6827  7293 V BluetoothOppNotification: outbound notification was removed.
09-08 14:32:01.454  6827  7293 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-08 14:32:01.455  6827  7293 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2910c8d0 on behalf of 
09-08 14:32:01.457  6827  7293 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-08 14:32:01.460  6827  7293 V BluetoothOppNotification: inbound notification was removed.
,09-08 14:32:01.460  6827  7293 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-08 14:32:01.462  1030  1886 W libprocessgroup: failed to open /acct/uid_10097/pid_6667/cgroup.procs: No such file or directory
09-08 14:32:01.465  6827  7293 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a3510c9 on behalf of 
,09-08 14:32:01.701   308   888 D SoftapController: Softap fwReload - Ok
,09-08 14:32:01.733  1030  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 14:32:01.741  1030  1408 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (685ms)
,09-08 14:32:01.752   308   888 D CommandListener: Setting iface cfg
09-08 14:32:01.752   308   888 D CommandListener: Trying to bring down wlan0
09-08 14:32:01.753   308   888 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:32:01.762  1030  1408 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-08 14:32:01.772  1030  1408 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 14:32:01.772  1030  1408 E WifiStateMachine: useWiFiOffloading() : false
09-08 14:32:01.772  1030  1408 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 14:32:01.766  7301  7301 W wpa_supplicant: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-08 14:32:01.766  7301  7301 W wpa_supplicant: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-08 14:32:01.786  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-08 14:32:01.806  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-08 14:32:01.807  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:32:01.816  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:01.820  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:01.823  1030  1408 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-08 14:32:01.823  1030  1408 D WifiMonitor: connecting to supplicant
,09-08 14:32:01.830  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:32:01.830  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:32:01.830  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:32:01.830  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:32:01.831  7301  7301 I wpa_supplicant: Successfully initialized wpa_supplicant
09-08 14:32:01.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:32:01.831  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:32:01.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 14:32:01.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:32:01.831  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:32:01.832  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:32:01.832  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 14:32:01.832  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:32:01.843  7225  7225 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:32:01.849  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:32:01.857  7255  7314 W FormManager: Network not available. Please check & try again.
,09-08 14:32:01.859  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:01.871  7255  7315 V FormManager: Network unavailable.
,09-08 14:32:01.876  7255  7315 V FormManager: Network unavailable.
09-08 14:32:01.880  7301  7301 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 14:32:01.881  7301  7301 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-08 14:32:01.883  1030  1112 D Tethering: InitialState.processMessage what=4
,09-08 14:32:01.884  1030  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 14:32:01.887  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:32:01.887  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:32:01.887  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:32:01.887  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:32:01.888  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:32:01.888  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,09-08 14:32:01.889  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-08 14:32:01.889  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:32:01.889  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:32:01.889  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:32:01.889  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:32:01.984  7301  7301 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 14:32:01.996  7301  7301 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-08 14:32:02.003  7301  7301 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-08 14:32:02.004  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-08 14:32:02.004  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 14:32:02.005  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-08 14:32:02.005  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,09-08 14:32:02.005  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-08 14:32:02.005  1030  7321 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-08 14:32:02.005  1030  7321 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-08 14:32:02.007  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-08 14:32:02.008  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-08 14:32:02.009  1030  1408 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-08 14:32:02.011  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:02.012  1030  1408 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:02.014  1030  1408 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:02.015  1030  1408 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:02.016  1030  1408 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-08 14:32:02.017  1030  1408 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,09-08 14:32:02.021  1030  1408 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-08 14:32:02.021  1030  1408 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-08 14:32:02.022  1030  1408 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-08 14:32:02.023  1030  1408 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 14:32:02.023  1030  1408 E WifiStateMachine: useWiFiOffloading() : false
09-08 14:32:02.023  1030  1408 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-08 14:32:02.023  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.024  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.024  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.024  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.024  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:32:02.026  1030  1408 D WifiNative-wlan0: doBoolean: SET update_config 1
09-08 14:32:02.027  1030  1408 D WifiNative-wlan0: SET update_config 1: returned true
09-08 14:32:02.027  1030  1408 D WifiConfigStore: Loading config and enabling all networks 
09-08 14:32:02.027  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:02.027  1030  1408 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,09-08 14:32:02.030  1924  1924 D WfdService: Waiting for WifiP2p enabling
,09-08 14:32:02.031  1030  1408 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-08 14:32:02.042  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:02.042  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:02.042  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:02.042  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:02.042  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:02.042  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:02.042  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:02.042  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:32:02.044  1030  1408 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-08 14:32:02.047  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:32:02.049  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-08 14:32:02.049  1030  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-08 14:32:02.054  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:02.054  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:02.054  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:02.054  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:02.054  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:02.054  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:02.054  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:02.054  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:32:02.056  7225  7225 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:32:02.058  1030  1408 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-08 14:32:02.058  1030  1408 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 14:32:02.059  1030  1408 D WifiStateMachine: enableVerboseLogging : level 2
09-08 14:32:02.059  1030  1408 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-08 14:32:02.060  1030  1408 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-08 14:32:02.060  1030  1408 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-08 14:32:02.060  1030  1408 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-08 14:32:02.060  1030  1408 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-08 14:32:02.060  1030  1408 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-08 14:32:02.060  1030  1408 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-08 14:32:02.061  1030  1408 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-08 14:32:02.061  1030  1408 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-08 14:32:02.062  1030  1408 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-08 14:32:02.062  1030  1408 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,09-08 14:32:02.062  1030  1408 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-08 14:32:02.062  1030  1408 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-08 14:32:02.063  1030  1408 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-08 14:32:02.064  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:32:02.065  1030  1408 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:32:02.065  1030  1408 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-08 14:32:02.064  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:02.065  1030  1408 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-08 14:32:02.065  1030  1408 D WifiNative-HAL: Setting external_sim to 1
09-08 14:32:02.065  1030  1408 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-08 14:32:02.065  1924  1924 D WfdsService: Supplicant Connection state is changed : true
09-08 14:32:02.066  1924  2250 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-08 14:32:02.066  1924  2250 D WfdsService: Set the WFDS Monitor: true
09-08 14:32:02.066  1924  2250 D WfdsMonitor: WfdsMonitorThread create
09-08 14:32:02.066  1924  2250 D WfdsMonitor: WFDS Monitor is created and started
09-08 14:32:02.066  1924  2250 D WfdsService: WiFi: Supplicant connection re-established
09-08 14:32:02.066  1030  1408 D WifiNative-wlan0: SET external_sim 1: returned true
09-08 14:32:02.066  1030  1408 I WifiNative-HAL: startHal
09-08 14:32:02.066  1030  1408 E wifi    : getStaticLongField sWifiHalHandle 0x9886e8dc
09-08 14:32:02.066  1030  1408 E WifiHAL : Could not connect handle
09-08 14:32:02.066  1030  1408 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x20234e
09-08 14:32:02.067  1030  1408 I WifiNative-HAL: Could not start hal
09-08 14:32:02.067  1030  1408 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:32:02.067  1030  1408 I WifiNative-HAL: startHal
09-08 14:32:02.067  1030  1408 E wifi    : getStaticLongField sWifiHalHandle 0x9886e85c
,09-08 14:32:02.067  1030  1408 E WifiHAL : Could not connect handle
09-08 14:32:02.067  1030  1408 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x202346
09-08 14:32:02.067  1030  1408 I WifiNative-HAL: Could not start hal
09-08 14:32:02.067  1030  1408 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-08 14:32:02.067  1924  7327 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-08 14:32:02.068  1030  1408 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-08 14:32:02.068  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
,09-08 14:32:02.068  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-08 14:32:02.068  1924  7327 E CtrlSupplicant: Succeed to open control connection
09-08 14:32:02.069  1924  7327 E CtrlSupplicant: Succeed to open monitor connection
09-08 14:32:02.069  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-08 14:32:02.069  1924  7327 D WfdsMonitor: Supplicant connection established
09-08 14:32:02.069  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 14:32:02.069  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 14:32:02.069  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 14:32:02.070  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-08 14:32:02.070  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-08 14:32:02.070  1924  2250 D WfdsService: Connected to the supplicant for wfds
09-08 14:32:02.070  7255  7325 W FormManager: Network not available. Please check & try again.
09-08 14:32:02.071  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-08 14:32:02.071  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 14:32:02.071  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 14:32:02.071  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 14:32:02.071  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 14:32:02.072  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 14:32:02.072  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 14:32:02.072  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-08 14:32:02.073  7301  7301 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-08 14:32:02.073  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-08 14:32:02.073  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 14:32:02.073  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 14:32:02.074  1030  1408 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 14:32:02.074  1030  1408 E WifiNative: : [133,930,339 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-08 14:32:02.074  1030  1408 D WifiNative-wlan0: doBoolean: RECONNECT
09-08 14:32:02.075  1030  1408 D WifiNative-wlan0: RECONNECT: returned true
09-08 14:32:02.075  1030  1408 D WifiNative-wlan0: doString: [STATUS]
,09-08 14:32:02.076  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-08 14:32:02.076  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 14:32:02.076  1030  1408 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-08 14:32:02.076  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 1
,09-08 14:32:02.077  1030  1408 D WifiNative-wlan0: SET ps 1: returned true
09-08 14:32:02.077  1030  1370 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.078   308   888 D CommandListener: Setting iface cfg
09-08 14:32:02.079   308   888 D CommandListener: Trying to bring up p2p0
09-08 14:32:02.079  1030  1370 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 14:32:02.079  1030  1370 D LGWifiP2pService: P2pEnablingState
09-08 14:32:02.079  1030  1370 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.079  1030  1370 D LGWifiP2pService: P2p socket connection successful
09-08 14:32:02.079  1030  1370 D LGWifiP2pService: P2pEnabledState
09-08 14:32:02.079  7255  7326 V FormManager: Network unavailable.
09-08 14:32:02.080  1030  1370 D LGWifiP2pService: sending p2p connection changed broadcast
,09-08 14:32:02.080  1924  1924 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-08 14:32:02.080  1924  1924 D WfdsService: WifiP2pState is changed : true
09-08 14:32:02.081  1924  2250 D WfdsService: Receive the WFDS_ENABLE Method
09-08 14:32:02.081  1924  2250 D WfdsService: Set the WFDS Monitor: true
09-08 14:32:02.081  1924  2250 D WfdsService: Connected to the supplicant for wfds
09-08 14:32:02.081  1924  2250 D WfdsJNI : doCommand: WFDS_SET TRUE
09-08 14:32:02.081  7301  7301 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-08 14:32:02.081  1924  2250 D WfdsService: selectPreferredScanChannel [36]
09-08 14:32:02.081  1924  2250 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-08 14:32:02.083  1030  1370 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-08 14:32:02.084  1030  1408 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-08 14:32:02.084  1030  1370 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-08 14:32:02.084  1030  1408 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-08 14:32:02.084  1030  1370 D WifiNative-p2p0: doBoolean: SET device_name G3
09-08 14:32:02.084  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 14:32:02.084  1030  1408 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-08 14:32:02.084  1924  1924 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-08 14:32:02.085  1030  1030 D RttService: SCAN_AVAILABLE : 3
09-08 14:32:02.085  1030  1538 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.085  1030  1538 I WifiNative-HAL: startHal
,09-08 14:32:02.085  1030  1408 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-08 14:32:02.085  1030  1539 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.085  1924  1924 D WfdsService: isConnected: false
09-08 14:32:02.085  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:02.085  1030  1370 D WifiNative-p2p0: SET device_name G3: returned true
09-08 14:32:02.085  1030  1370 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-08 14:32:02.085  1030  1538 E wifi    : getStaticLongField sWifiHalHandle 0x94d6899c
09-08 14:32:02.085  1030  1370 D LGWifiP2pService: before postfix = G3
09-08 14:32:02.085  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=133942  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 14:32:02.085  1030  1370 D WifiServerServiceExt: postfix byte check : 2
09-08 14:32:02.085  7255  7326 V FormManager: Network unavailable.
09-08 14:32:02.085  1030  1370 D LGWifiP2pService: after postfix = G3
09-08 14:32:02.085  1030  1370 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-08 14:32:02.086  1030  1538 E WifiHAL : Could not connect handle
09-08 14:32:02.086  1030  1538 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x202322
09-08 14:32:02.086  1030  1538 I WifiNative-HAL: Could not start hal
09-08 14:32:02.086  1030  1538 E WifiScanningService: could not start HAL
09-08 14:32:02.086  1030  1370 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-08 14:32:02.086  1030  1370 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-08 14:32:02.086  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=133943  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 14:32:02.086  1030  1370 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-08 14:32:02.086  1030  1370 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-08 14:32:02.087  1030  1408 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-08 14:32:02.087  1030  1370 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-08 14:32:02.087  1030  1370 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-08 14:32:02.087  1030  1408 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-08 14:32:02.087  1030  1370 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-08 14:32:02.087  1030  1370 D WifiNative-HAL: p2pGetDeviceAddress
09-08 14:32:02.088  1030  1370 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-08 14:32:02.088  1030  1408 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-08 14:32:02.088  1030  1408 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-08 14:32:02.088  7301  7301 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-08 14:32:02.088  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.088  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.088  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:32:02.088  1030  1408 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-08 14:32:02.089  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:02.089  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:02.091  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:02.092  1030  1408 E WifiStateMachine:  C,onnectModeState what:132096 -100 0
09-08 14:32:02.093  1030  1408 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-08 14:32:02.093  1030  1408 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-08 14:32:02.093  7301  7301 E wpa_supplicant: disconnect_rssi_lvl: -100
09-08 14:32:02.094  1030  1370 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-08 14:32:02.094  1030  1370 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,09-08 14:32:02.095  1030  1408 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-08 14:32:02.096  1030  1408 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-08 14:32:02.096  1030  1408 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-08 14:32:02.096  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-08 14:32:02.102  1924  1924 I WfdStateTracker: handleP2pThisDeviceChanged
09-08 14:32:02.102  1924  1924 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-08 14:32:02.103  1924  1924 D WfdsService: Update P2p Interface State: 3
09-08 14:32:02.103  1030  1370 D WifiNative-p2p0: P2P_FLUSH: returned true
09-08 14:32:02.103  1030  1370 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-08 14:32:02.103  1030  1370 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-08 14:32:02.103  1030  1370 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-08 14:32:02.104  1030  1370 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-08 14:32:02.104  1030  1370 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-08 14:32:02.107  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-08 14:32:02.108  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:32:02.110  1030  1370 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-08 14:32:02.110  1030  1370 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-08 14:32:02.110  1030  1370 D LGWifiP2pService: InactiveState
09-08 14:32:02.111  1030  1370 D LGWifiP2pService: InactiveState{ when=-7ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.111  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.111  1030  1370 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-08 14:32:02.111  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 14:32:02.112  7301  7301 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:32:02.112  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 14:32:02.112  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:32:02.112  1030  7321 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:32:02.112  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:32:02.112  1030  7321 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:32:02.112  7301  7301 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 14:32:02.112  7301  7301 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.113  1030  1408 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-08 14:32:02.113  1030  1408 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-08 14:32:02.113  1924  7327 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:32:02.113  1030  1408 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-08 14:32:02.114  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 14:32:02.114  1030  1408 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-08 14:32:02.114  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-08 14:32:02.114  1030  7321 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:32:02.114  1030  7321 E WifiMonitor: WifiMonitor:p2p0 cnt=56 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.114  1030  7321 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.114  1030  7321 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.114  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:32:02.114  7301  7301 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:32:02.115  1030  7321 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 14:32:02.115  1030  7321 E WifiMonitor: WifiMonitor:p2p0 cnt=57 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:32:02.115  1030  7321 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha,2=CZ
09-08 14:32:02.115  1030  7321 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 14:32:02.115  7301  7301 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 14:32:02.115  7301  7301 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.115  1030  7321 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:32:02.115  1030  7321 E WifiMonitor: WifiMonitor:p2p0 cnt=58 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.115  1030  1370 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-08 14:32:02.115  1030  7321 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.115  1030  7321 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.115  1030  1370 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.116  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.116  1030  1370 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.116  1030  1370 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.116  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-08 14:32:02.116  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.116  7301  7301 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:32:02.116  1030  1370 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.116  1030  1370 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.116  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.116  1030  1370 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.116  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-08 14:32:02.116  1030  1370 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.116  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:32:02.116  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.116  1030  7321 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:32:02.116  1030  7321 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:32:02.117  7301  7301 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.117  1030  1408 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-08 14:32:02.117  1030  1408 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-08 14:32:02.117  1030  7321 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:32:02.117  1030  7321 E WifiMonitor: WifiMonitor:p2p0 cnt=60 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.117  1030  7321 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.117  1030  7321 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.117  1924  2250 W WfdsService: DefaultState -, msg [9441285] is not handled
09-08 14:32:02.116  1030  1370 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.117  7301  7301 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.117  1030  1408 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-08 14:32:02.117  1030  1408 D WifiNative-wlan0: doBoolean: SCAN
09-08 14:32:02.117  1030  1030 E WifiServerServiceExt: No p2p device connected
09-08 14:32:02.118  1030  7321 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:32:02.118  1030  7321 E WifiMonitor: WifiMonitor:p2p0 cnt=61 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.118  1030  1370 D LGWifiP2pService: InactiveState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.118  1030  7321 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.118  1030  7321 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 14:32:02.118  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:02.118  1924  7327 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 14:32:02.118  1924  7327 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:32:02.118  1924  7327 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:32:02.118  1924  7327 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 14:32:02.118  1030  1408 D WifiNative-wlan0: SCAN: returned false
09-08 14:32:02.119  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=133975  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 14:32:02.119  7031  7031 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 14:32:02.120  7031  7031 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-08 14:32:02.121  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:02.121  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:02.123  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:02.123  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.123  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.123  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:32:02.123  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=133980  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 14:32:02.124  1030  1408 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:32:02.124  1030  1408 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:32:02.125  1030  1408 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:32:02.125  1030  1408 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:32:02.126  1030  1408 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 14:32:02.126  4152  7328 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:32:02.127  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:02.127  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 14:32:02.128  4152  7329 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:32:02.128  7031  7031 V [BNRBootReceiver]: Boot Receiver Return
09-08 14:32:02.128  4152  7329 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:32:02.128  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:02.128  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 14:32:02.131  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:32:02.137  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:02.142  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:02.148  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 14:32:02.149  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:02.150  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 14:32:02.153  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:32:02.159  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:02.164  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:02.169  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:32:02.169  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:02.170  6295  6295 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 14:32:02.437  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:02.437  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:32:02.437  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:02.437  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:02.438  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:02.438  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16daf99c removed from the list
09-08 14:32:02.438  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:02.438  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1df1ffa5 removed from the list
09-08 14:32:02.438  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:02.438  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:02.462  5982  7333 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-08 14:32:02.462  5982  7333 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 14:32:02.732  7301  7301 E wpa_supplicant: USIM:  scard_init function
,09-08 14:32:02.733  7301  7301 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-08 14:32:02.746  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-08 14:32:02.746  1030  7321 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-08 14:32:02.746  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-08 14:32:02.747  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: WPS-AP-AVAILABLE 
09-08 14:32:02.747  1030  7321 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-08 14:32:02.747  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-08 14:32:02.747  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-08 14:32:02.755  1030  1408 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-08 14:32:02.756  1030  1408 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-08 14:32:02.756  1030  1408 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-08 14:32:02.757  1030  1408 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-08 14:32:02.757  1030  1408 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-08 14:32:02.775  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=134631  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-08 14:32:02.783  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:02.783  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:02.786  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:02.789  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.789  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.789  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-08 14:32:02.793  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=134649  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-08 14:32:02.794  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:02.794  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-08 14:32:02.798  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-08 14:32:02.812  6213  6213 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-08 14:32:02.816  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:32:02.827  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:02.836  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:02.843  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:32:02.844  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:02.844  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 14:32:02.911  7301  7301 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 14:32:02.920  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-08 14:32:02.920  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-08 14:32:02.920  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-08 14:32:02.920  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=66 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-08 14:32:02.920  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:32:02.920  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=67 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:32:02.923  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=134779  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 14:32:02.924  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=134780  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 14:32:02.926  1030  1408 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 66 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=134782
09-08 14:32:02.926  1030  1408 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 66 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=134782
09-08 14:32:02.926  1030  1408 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 66 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=134783
09-08 14:32:02.927  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 66 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=134783
09-08 14:32:02.927  1030  1408 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 66 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=134783
09-08 14:32:02.928  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 67 0 rt=134784  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-08 14:32:02.931  1030  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-08 14:32:02.937  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.937  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:02.937  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:32:02.941  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:02.941  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:02.944  7301  7301 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:32:02.944  7301  7301 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-08 14:32:02.950  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:32:02.950  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=68 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:32:02.951  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-08 14:32:02.952  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=69 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:32:02.952  1030  7321 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:32:02.952  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-08 14:32:02.952  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=70 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 14:32:02.952  1030  7321 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 14:32:02.952  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:32:02.952  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=71 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:32:02.954  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:32:02.976  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 67 0 rt=134832  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-08 14:32:02.977  1030  1408 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 68 0 rt=134833  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 14:32:02.977  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 68 0 rt=134833  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 14:32:02.978  1030  1408 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=134834
09-08 14:32:02.978  1030  1408 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=134834
09-08 14:32:02.979  1030  1408 D WifiNative-wlan0: doString: [STATUS]
,09-08 14:32:02.982  1030  7321 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 14:32:02.982  1030  7321 E WifiMonitor: WifiMonitor:wlan0 cnt=72 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 14:32:02.993  1030  1408 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-08 14:32:02.998  5982  7333 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-08 14:32:02.998  5982  7333 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:32:02.998  5982  7333 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:02.999  5982  7333 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:02.999  5982  7333 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 14:32:03.000  5982  7341 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-08 14:32:03.000  5982  7341 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:32:03.000  5982  7341 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:03.001  5982  7341 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:03.001  5982  7341 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 14:32:03.003  1030  1408 I WifiServiceExtension: setVHTCapabilityType  : false
09-08 14:32:03.014  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 14:32:03.021  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:03.021  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:03.023  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:03.026  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.027  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.027  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,09-08 14:32:03.032  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:03.032  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-08 14:32:03.036  1030  1408 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-08 14:32:03.036  1030  1408 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-08 14:32:03.042  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.042  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.042  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-08 14:32:03.046  5982  7345 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 825, name: OutgoingSocketThread/Receiver)
09-08 14:32:03.047  5982  7345 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 825, thread name: OutgoingSocketThread/Receiver)
09-08 14:32:03.047  5982  7345 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 14:32:03.047  5982  7344 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 824, name: OutgoingSocketThread/Sender)
09-08 14:32:03.047  5982  7345 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 825, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 14:32:03.048  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:03.048  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:03.049  5982  7346 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 826, name: IncomingSocketThread/Sender)
09-08 14:32:03.050  5982  7347 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 827, name: IncomingSocketThread/Receiver)
09-08 14:32:03.050  5982  7347 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 827, thread name: IncomingSocketThread/Receiver)
09-08 14:32:03.050  5982  7347 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 14:32:03.050  5982  7347 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 827, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 14:32:03.058  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:32:03.061  1030  1408 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-08 14:32:03.062  1030  1464 D ConnectivityService: Got NetworkAgent Messenger
,09-08 14:32:03.062  1030  1408 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:32:03.062  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 14:32:03.062  1030  1464 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 14:32:03.062  1030  1464 D ConnectivityService: NetworkAgent connected
09-08 14:32:03.062  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:03.064  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 14:32:03.065  1030  1408 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 14:32:03.068  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:32:03.068  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.069  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-08 14:32:03.072  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:03.073  1030  1408 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 14:32:03.073  1030  1408 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:32:03.073  1030  1408 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 14:32:03.074  1030  1408 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 14:32:03.074  1030  1408 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 14:32:03.080  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:03.080  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:03.081  1030  1408 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-08 14:32:03.084   308   888 D CommandListener: Setting iface cfg
09-08 14:32:03.084  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:03.086  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:32:03.086  1030  1408 E WifiStateMachine: Start Dhcp Watchdog 3
,09-08 14:32:03.086  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:03.087  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:32:03.087  1030  1408 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 71 0 rt=134943  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:32:03.087  1030  1408 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 71 0 rt=134943  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:32:03.087  1030  7365 D DhcpStateMachine: StoppedState
09-08 14:32:03.088  1030  7365 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:03.088  1030  7365 D DhcpStateMachine: WaitBeforeStartState
09-08 14:32:03.088  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 71 0 rt=134944  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:32:03.088  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:03.089  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:03.089  1030  1408 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:03.090  1030  1408 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:03.090  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:32:03.090  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:03.090  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:32:03.090  6213  6213 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:32:03.090  6213  6213 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:32:03.091  1030  1408 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 14:32:03.092  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:03.092  1030  1030 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,09-08 14:32:03.094  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:03.095  1030  1030 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-08 14:32:03.095  1030  1408 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 72 0 rt=134951  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:32:03.096  1030  1408 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 72 0 rt=134952  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:32:03.097  1030  1408 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 72 0 rt=134953  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 14:32:03.098  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 3 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2570] from screen [on:0 period:164140570] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 14:32:03.099  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:164140571] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 14:32:03.099  1030  1408 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-08 14:32:03.099  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:32:03.100  6213  6213 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:32:03.100  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 14:32:03.100  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:32:03.100  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:32:03.101  6213  6213 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:32:03.101  6213  6213 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 14:32:03.104  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:03.104  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:03.105  1030  1408 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:03.105  1030  1408 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:03.106  1030  1464 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-08 14:32:03.107  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:32:03.108  6213  6213 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:32:03.108  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:03.109  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:03.109  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-08 14:32:03.109  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=65,0,0
09-08 14:32:03.110  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=65,0,0
09-08 14:32:03.110  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-08 14:32:03.110  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-08 14:32:03.110  1030  1408 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-08 14:32:03.111  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 0
09-08 14:32:03.111  1030  1408 D WifiNative-wlan0: SET ps 0: returned true
09-08 14:32:03.111  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-08 14:32:03.111  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-08 14:32:03.112  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-08 14:32:03.112  1030  1408 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-08 14:32:03.112  1030  1370 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@abf5c21 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:03.112  1030  1408 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:32:03.112  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@abf5c21 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:03.112  1030  1408 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:32:03.112  1030  7365 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:03.112  1030  7365 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-08 14:32:03.113   308   888 D CommandListener: Setting iface cfg
09-08 14:32:03.113   308   888 D CommandListener: Trying to bring up wlan0
09-08 14:32:03.114  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:32:03.114  1030  1408 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-08 14:32:03.115  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:03.115  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 14:32:03.115  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:03.116  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:03.116  1030  1408 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:03.117  1030  1408 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-08 14:32:03.117  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-08 14:32:03.117  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 14:32:03.118  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-08 14:32:03.118  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 14:32:03.119  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 14:32:03.119  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 14:32:03.119  1030  1370 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:03.119  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:03.119  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 14:32:03.119  1030  1408 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 14:32:03.119  1030  1408 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-08 14:32:03.120  7301  7301 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-08 14:32:03.120  1030  1408 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-08 14:32:03.120  1030  1408 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 14:32:03.123  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:03.128  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:03.134  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 14:32:03.135  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:03.135  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:32:03.137  1030  1408 D WifiNative-wlan0: SET ps 1: returned true
09-08 14:32:03.138  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-08 14:32:03.138  1030  1408 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 14:32:03.139  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:32:03.139  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 14:32:03.139  1030  1408 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 14:32:03.139  1030  1464 D ConnectivityService: ignoring duplicate network state non-change
09-08 14:32:03.143  1030  1358 D PowerManagerServiceEx: acquireWakeLockInternal: lock=721509872, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
09-08 14:32:03.145  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:03.145  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 14:32:03.146  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:03.148  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.148  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.148  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 14:32:03.150  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:03.153  1030  1358 V AlarmManager: ELAPSED_WAKEUP set : Alarm{4127846 type 2 when 134998 com.google.android.gms} when 134998
09-08 14:32:03.154  1030  1464 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 14:32:03.154  1030  1464 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 14:32:03.161  1924  1924 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-08 14:32:03.161  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:03.165  1030  1408 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-08 14:32:03.168  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:03.168  1584  1584 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 14:32:03.174  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:03.175  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.175  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.175  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 14:32:03.175  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 14:32:03.176  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.176  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.176  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 14:32:03.176  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 14:32:03.176  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.176  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:03.176  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 14:32:03.179  1030  1464 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 14:32:03.179  1030  1464 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-08 14:32:03.179  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:03.180  1584  1584 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 14:32:03.180  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:03.180  1030  1464 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-08 14:32:03.181   308   888 E Netd    : netlink response contains error (File exists)
09-08 14:32:03.181  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:32:03.181  1030  1464 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-08 14:32:03.181  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:03.182  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:32:03.182  1030  1464 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-08 14:32:03.182  1030  1464 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-08 14:32:03.182  1030  1464 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-08 14:32:03.184  1584  1584 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 14:32:03.184  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:32:03.184  1584  1584 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,09-08 14:32:03.185  1030  1464 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 14:32:03.185  1030  1464 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 14:32:03.185  1030  1464 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-08 14:32:03.185  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:03.185  1030  1464 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-08 14:32:03.185  1030  1464 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:03.185  1030  1464 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:03.185  1030  1464 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 14:32:03.185  1030  1464 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:03.185  1030  1464 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
,09-08 14:32:03.185  1030  1464 D ConnectivityService: currentScore = 0, newScore = 20
09-08 14:32:03.185  1030  1464 D ConnectivityService:    accepting network in place of null
09-08 14:32:03.185  1030  1464 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:03.186  1030  7358 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:03.186  1030  7358 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-08 14:32:03.186  1030  7358 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:03.186  1030  7358 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-08 14:32:03.187  1030  1408 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:03.188  1030  1408 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:03.188  1835  1835 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:03.189  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 14:32:03.190  1030  1464 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-08 14:32:03.190  1030  1464 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-08 14:32:03.190  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 14:32:03.192   308  7371 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-08 14:32:03.194  1030  1464 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:03.194  1030  1464 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-08 14:32:03.194  1030  1464 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-08 14:32:03.196  1030  1464 D ConnectivityService: validation of new default Network = false
09-08 14:32:03.196  ,1030  1464 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-08 14:32:03.196  1030  1464 D DSQN    : enableDataServiceNotify 
09-08 14:32:03.196  1030  1464 D DSQN    : start dsqn bin
09-08 14:32:03.202  1030  1464 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-08 14:32:03.202  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:03.202  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:03.202  1030  1464 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-08 14:32:03.195  7372  7372 W dsqn    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:32:03.203  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:32:03.206  1030  1030 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-08 14:32:03.195  7372  7372 W dsqn    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:32:03.207  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 14:32:03.207  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 14:32:03.207  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 14:32:03.216  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:03.218  7372  7372 E DSQN    : DSQN ssw
09-08 14:32:03.223  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:03.230  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:32:03.230  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:03.231  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 14:32:03.239  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:32:03.249  1030  1369 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-08 14:32:03.252  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:03.257  1584  1584 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:32:03.257  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:03.258   308  7371 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-08 14:32:03.258  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:03.259  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:03.267  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:32:03.267  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 14:32:03.268  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:32:03.269  2624  2624 D [Concierge]Service: onStartCommand(). Type : 9
09-08 14:32:03.276   308  7377 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 14:32:03.276   308  7377 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-08 14:32:03.278  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:32:03.286  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:03.293  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:03.293  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=721509872 [*alarm*], flags=0x0
09-08 14:32:03.294   308  7371 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-08 14:32:03.300  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 14:32:03.301  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:03.302  6295  6295 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 14:32:03.306  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:32:03.309  7225  7225 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 14:32:03.313  7225  7225 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:32:03.314  1030  7365 D DhcpStateMachine: DHCPV4 request on wlan0
09-08 14:32:03.314   308  7377 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-08 14:32:03.314  1030  7365 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-08 14:32:03.314  1030  7365 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-08 14:32:03.305  7378  7378 W dhcpcd  : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:32:03.305  7378  7378 W dhcpcd  : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 14:32:03.319  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:03.321   308   887 D LGDataListener: argv[0]=dsqncommand
09-08 14:32:03.321   308   887 D LGDataListener: argv[1]=wlan0
09-08 14:32:03.321   308   887 D LGDataListener: argv[2]=1
09-08 14:32:03.321   308   887 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-08 14:32:03.322  1030  1110 D DSQN    : DSQM DsqnNotification wlan0  1
09-08 14:32:03.322  1030  1110 D DSQN    : start to monitor internet connection
,09-08 14:32:03.325  7378  7378 I dhcpcd  : version 5.5.6 starting
09-08 14:32:03.327  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:03.327  7378  7378 E dhcpcd  : get_duid: m
09-08 14:32:03.327  7378  7378 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-08 14:32:03.327  7378  7378 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-08 14:32:03.336  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 14:32:03.336  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:03.337  6295  6295 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 14:32:03.337  6295  6295 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 14:32:03.338  6295  6295 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-08 14:32:03.343  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 14:32:03.346  7225  7225 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 14:32:03.347  7225  7225 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:32:03.348  1030  7358 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:32:03 GMT], X-Android-Received-Millis=[1473337923347], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473337923320]}
09-08 14:32:03.348  1030  7358 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 14:32:03.348  1030  7358 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 14:32:03.348  1030  1464 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-08 14:32:03.348  1030  1464 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-08 14:32:03.348  1030  1464 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:03.348  1030  1464 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,09-08 14:32:03.348  1030  1464 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 14:32:03.348  1030  1464 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-08 14:32:03.349  1030  1464 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-08 14:32:03.349  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:03.349  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:03.349  1030  1464 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-08 14:32:03.349  1030  1464 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:03.350  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 14:32:03.350  1030  1408 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:03.350  1030  1408 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:03.350  1835  1835 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:03.350  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 14:32:03.351  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:32:03.351  6213  6213 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:03.380  1584  1584 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:32:03.381  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:03.381  6213  6213 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:03.382  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 14:32:03.389  6295  6295 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 14:32:03.389  6295  6295 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 14:32:03.390  6295  6295 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 14:32:03.391  6295  6295 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 14:32:03.391  6295  6295 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-08 14:32:03.404  7378  7378 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 14:32:03.404  7378  7378 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 14:32:03.404  7378  7378 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-08 14:32:03.404  7378  7378 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-08 14:32:03.404  7378  7378 D dhcpcd  : wlan0: sending REQUEST (xid 0x3940736a), next in 3.09 seconds
09-08 14:32:03.431  7378  7378 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-08 14:32:03.442  7378  7378 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,09-08 14:32:03.442  7378  7378 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-08 14:32:03.443  7378  7378 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-08 14:32:03.444  7378  7378 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-08 14:32:03.444  7378  7378 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 14:32:03.445  7378  7378 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 14:32:03.445  7378  7378 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 14:32:03.445  7378  7378 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-08 14:32:03.501  5982  6084 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 14:32:03.503  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:03.504  5982  6084 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-08 14:32:03.510  1030  1112 D Tethering: MasterInitialState.processMessage what=3
09-08 14:32:03.511  1030  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:03.513  5982  6084 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@27eba41 Bundle[{}]
09-08 14:32:03.514  5982  6084 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 14:32:03.514  5982  6084 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-08 14:32:03.515  5982  6084 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-08 14:32:03.517  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:03.517  5982  6084 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 14:32:03.518  5982  6084 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 14:32:03.520  5982  6084 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-08 14:32:03.520  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-08 14:32:03.523  1030  1112 D Tethering: MasterInitialState.processMessage what=3
09-08 14:32:03.525  5352  5352 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-08 14:32:03.526  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:03.526  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:03.526  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:03.526  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:03.526  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:03.526  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:03.526  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:03.526  5982  5982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:03.529  5224  5252 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-08 14:32:03.536  5982  5982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:03.538  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:03.538  5982  7393 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-08 14:32:03.538  5982  7393 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-08 14:32:03.541  1030  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 14:32:03.547  1030  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:03.547  1030  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:03.550  5982  7393 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-08 14:32:03.550  5982  7393 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:32:03.550  5982  7393 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:03.551  5982  7393 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:03.551  5982  7396 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-08 14:32:03.551  5982  7393 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 14:32:03.551  5982  7396 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:32:03.553  5982  7400 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 838, name: OutgoingSocketThread/Sender)
09-08 14:32:03.553  5352  5352 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-08 14:32:03.553  5982  7396 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:03.555  5982  7401 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 839, name: OutgoingSocketThread/Receiver)
09-08 14:32:03.555  5982  7401 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 839, thread name: OutgoingSocketThread/Receiver)
09-08 14:32:03.555  5982  7401 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 14:32:03.555  5982  7401 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 839, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 14:32:03.558  5982  7396 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:32:03.559  5982  7396 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 14:32:03.560  5982  7403 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 840, name: IncomingSocketThread/Sender)
09-08 14:32:03.562  5982  7404 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 841, name: IncomingSocketThread/Receiver)
09-08 14:32:03.562  5982  7404 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 841, thread name: IncomingSocketThread/Receiver)
09-08 14:32:03.562  5982  7404 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 14:32:03.563  5982  7404 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 841, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 14:32:03.568  2187  2187 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:03.585  2187  7388 D GCM     : Connected
,09-08 14:32:03.619  1030  1886 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7411 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-08 14:32:03.628  2187  7388 D GCM     : Message class com.google.e.a.a.q
,09-08 14:32:03.699  7411  7411 I AppUp4:AppBoxCP: onCreate
09-08 14:32:03.699  7411  7411 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-08 14:32:03.710  7411  7411 I AppUp4:DB:  setFingerPrint start
,09-08 14:32:03.710  7411  7411 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-08 14:32:03.718  1030  7365 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-08 14:32:03.719  7411  7411 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-08 14:32:03.719  7411  7411 I AppUp4:DB:  SDK version = 21
,09-08 14:32:03.719  7411  7411 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-08 14:32:03.720  1030  7365 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-08 14:32:03.721  1030  7365 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:32:03.721  1030  7365 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-08 14:32:03.721  1030  7365 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-08 14:32:03.721  1030  7365 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:32:03.721  1030  7365 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-08 14:32:03.722  1030  7365 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-08 14:32:03.722  7411  7411 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-08 14:32:03.723  1030  7365 D DhcpStateMachine: RunningState
09-08 14:32:03.724  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 14:32:03.725  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:03.728  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 14:32:03.728  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 14:32:03.736  7411  7411 I AppUp4:CustModeStarterReceiver: onReceive
,09-08 14:32:03.792  7411  7411 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 14:32:03.792  7411  7411 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 14:32:03.802  7411  7411 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1e7c3037
,09-08 14:32:03.803  7411  7411 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 14:32:03.803  7411  7411 D AppUp4:CustFacade: isPhone : true
09-08 14:32:03.803  7411  7411 D AppUp4:CustModeStarterReceiver: begin check event
09-08 14:32:03.804  7411  7411 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-08 14:32:03.804  7411  7411 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-08 14:32:03.805  7411  7434 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-08 14:32:03.805  7411  7434 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-08 14:32:03.805  7411  7434 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-08 14:32:03.809  1030  1904 I ActivityManager: Killing 5829:com.lge.email/u0a23 (adj 15): empty #17
,09-08 14:32:03.843  1030  1750 W libprocessgroup: failed to open /acct/uid_10023/pid_5829/cgroup.procs: No such file or directory
,09-08 14:32:03.846  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:03.847  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:32:03.851  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:32:03.856  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 14:32:03.863  3381  3381 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:03.868  3381  3381 V DownloadManager: DownloadService onCreate
09-08 14:32:03.872  4152  7436 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:32:03.872  4152  7437 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:03.873  4152  7437 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:32:03.872  3381  7438 I DownloadManager: in removeSpuriousFiles
,09-08 14:32:03.875  3381  7438 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-08 14:32:03.876  4152  7436 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 14:32:03.878  3381  7438 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@d5fb10f on behalf of 3381
09-08 14:32:03.879  3381  7438 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-08 14:32:03.879  3381  7438 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-08 14:32:03.879  3381  7438 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-08 14:32:03.879  3381  7438 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-08 14:32:03.879  3381  7438 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-08 14:32:03.879  3381  7438 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-08 14:32:03.879  3381  7438 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-08 14:32:03.879  3381  7438 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-08 14:32:03.880  3381  7438 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-08 14:32:03.880  3381  7438 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-08 14:32:03.880  3381  7438 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-08 14:32:03.883  3381  7438 I DownloadManager: in trimDatabase
,09-08 14:32:03.890  3381  7438 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-08 14:32:03.892  3381  7438 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@a1cbba5 on behalf of 3381
09-08 14:32:03.941  1030  1578 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7444 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-08 14:32:03.947  3381  3381 V DownloadManager: DownloadService onStartCommand
09-08 14:32:03.948  3381  7439 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-08 14:32:03.949  3381  7439 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@af04f2b on behalf of 3381
09-08 14:32:03.952  3381  7439 V DownloadManager: processing inserted download 1
09-08 14:32:03.953  3381  7439 V DownloadManager: processing inserted download 4
09-08 14:32:03.954  3381  7439 V DownloadManager: processing inserted download 7
09-08 14:32:03.955  3381  7439 V DownloadManager: processing inserted download 8
09-08 14:32:03.956  3381  7439 V DownloadManager: processing inserted download 9
09-08 14:32:03.957  3381  7439 V DownloadManager: processing inserted download 10
09-08 14:32:03.958  3381  7439 V DownloadManager: processing inserted download 11
09-08 14:32:03.959  4152  7436 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 14:32:03.960  3381  7439 V DownloadManager: processing inserted download 12
09-08 14:32:03.961  3381  7439 V DownloadManager: processing inserted download 13
09-08 14:32:03.962  3381  7439 V DownloadManager: processing inserted download 14
09-08 14:32:03.963  3381  7439 V DownloadManager: processing inserted download 16
,09-08 14:32:04.182  1030  1750 I art     : Explicit concurrent mark sweep GC freed 109575(5MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 3.057ms total 210.643ms
09-08 14:32:04.183  4152  4152 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-08 14:32:04.184  4152  4152 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-08 14:32:04.184  4152  4152 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 14:32:04.186  4152  4152 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-08 14:32:04.198  4152  4152 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-08 14:32:04.202  3381  3381 V DownloadManager: DownloadService onDestroy
09-08 14:32:04.202  1030  1464 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 14:32:04.221  7444  7444 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:32:04.221  7444  7444 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 14:32:04.223  7444  7444 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 14:32:04.223  7444  7444 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-08 14:32:04.309  7444  7444 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-08 14:32:04.338  7444  7444 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-08 14:32:04.344  1030  1408 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:32:04.345  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:32:04.346  1030  1408 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:32:04.347  1030  1408 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:32:04.348  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 14:32:04.350  1030  1408 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-08 14:32:04.351  1030  1464 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-08 14:32:04.351  1030  1464 D ConnectivityService: identical MTU - not setting
09-08 14:32:04.351  1030  1464 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 14:32:04.351  1030  1464 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 14:32:04.351  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:04.351  1030  1464 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:04.352  1030  1464 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:04.353  1584  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 14:32:04.408  7444  7444 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-08 14:32:04.447  7444  7444 D LgDataFeature: LgDataFeature() Constructor: none
09-08 14:32:04.447  7444  7444 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 14:32:04.606  7444  7444 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69),
,09-08 14:32:04.671  7444  7444 I HubEmail: JNI_OnLoad()
09-08 14:32:04.671  7444  7444 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:32:04.671  7444  7444 I HubEmail: registerNatives()
,09-08 14:32:04.671  7444  7444 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:32:04.671  7444  7444 I HubEmail: registerNativeMethods()
09-08 14:32:04.671  7444  7444 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:32:04.673  7444  7444 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-08 14:32:04.676  3281  3281 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 14:32:04.676  3281  3281 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:04.676  3281  3281 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 14:32:04.680  6523  6523 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 14:32:04.680  6523  6523 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-08 14:32:04.720  1030  1750 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7473 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:32:04.734  1584  1584 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-08 14:32:04.745  1584  1584 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-08 14:32:04.747  1584  1584 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-08 14:32:04.754  7444  7472 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:04.754  1030  1360 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-08 14:32:04.766  2014  2014 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-08 14:32:04.768   308  7499 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 14:32:04.769   308  7499 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
09-08 14:32:04.778  1030  1030 D administrator: Handling package changes for user 0
09-08 14:32:04.800  2014  2014 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-08 14:32:04.821   308  7499 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,09-08 14:32:04.857  7255  7470 V FormManager: There are no updated forms. The schedule will be deleted.
09-08 14:32:04.859  7255  7470 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-08 14:32:04.873  1030  1578 I ActivityManager: Killing 7012:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-08 14:32:04.886  1030  1030 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-08 14:32:04.886  1030  1030 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-08 14:32:04.919  1030  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:32:04.924  1030  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-08 14:32:04.943  1030  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_7012/cgroup.procs: No such file or directory
,09-08 14:32:04.952  2014  2014 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-08 14:32:05.010  1030  1637 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7505 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-08 14:32:05.011  1030  1637 I ActivityManager: Killing 7049:com.android.calendar/u0a13 (adj 15): empty #17
,09-08 14:32:05.137  2473  2473 V GmsNetworkLocationProvi: DISABLE
,09-08 14:32:05.138  1030  1045 W libprocessgroup: failed to open /acct/uid_10013/pid_7049/cgroup.procs: No such file or directory
,09-08 14:32:05.203  1030  1101 D LocationProviderProxy: applying state to connected service
,09-08 14:32:05.207  2473  2473 E GCoreFlp: Bound FusedProviderService with LocationManager
09-08 14:32:05.227  6594  6594 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:5
,09-08 14:32:05.230  6594  6594 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 14:32:05.230  6594  6594 D Weather.Utils: 2 : All the weather widget is gone.
09-08 14:32:05.230  6594  6594 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:32:05.231  6594  6594 D WeatherAncestor: connectivity changed - connection : true
09-08 14:32:05.231  6594  6594 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a9af30d
09-08 14:32:05.232  6594  6594 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 14:32:05.232  6594  6594 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 14:32:05.232  6594  6594 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 14:32:05.232  6594  6594 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 14:32:05.232  6594  6594 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:5
09-08 14:32:05.271  2187  2306 I art     : Explicit concurrent mark sweep GC freed 9922(587KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 1.236ms total 62.655ms
,09-08 14:32:05.291  1030  1994 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7523 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:05.292  1030  1994 I ActivityManager: Killing 6987:com.lge.clock/u0a10 (adj 15): empty #17
,09-08 14:32:05.396  1030  1045 W libprocessgroup: failed to open /acct/uid_10010/pid_6987/cgroup.procs: No such file or directory
,09-08 14:32:05.493  1030  1370 D LGWifiP2pService: InactiveState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:05.493  1030  1370 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:05.493  1030  1370 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 14:32:05.521  1030  1408 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-08 14:32:05.522  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 14:32:05.523  1030  1408 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 14:32:05.524  1030  1408 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 14:32:05.525  1030  1408 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 14:32:05.526  1030  1408 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 14:32:05.537   278   450 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:05.537   278   450 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 14:32:05.537   278   450 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:05.538  7523  7541 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-08 14:32:05.544   278   450 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:05.544   278   450 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 14:32:05.544   278   450 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:05.545  7523  7541 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-08 14:32:05.552   278   450 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:05.552   278   450 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 14:32:05.552   278   450 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:05.555  7523  7544 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-08 14:32:05.559   278   450 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:05.559   278   450 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 14:32:05.559   278   450 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:05.560  7523  7544 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 14:32:05.674  7120  7254 D UEI.SmartControl: Internal timer expired: 1
09-08 14:32:05.674  7120  7254 D UEI.SmartControl: unbind internal service
,09-08 14:32:05.806  7523  7523 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-08 14:32:05.818  7523  7523 I LibraryLoader: Loading: webviewchromium
09-08 14:32:05.822  7523  7523 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7685-7690)
,09-08 14:32:05.822  7523  7523 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 14:32:05.829  7523  7523 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f2df1be}
,09-08 14:32:05.831  7523  7523 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:32:05.831  7523  7523 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 14:32:05.846  7523  7523 I BrowserStartupController: Initializing chromium process, renderers=0
09-08 14:32:05.847  7523  7523 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 14:32:05.875   312   312 V AudioPolicyService: registerClient() client 0xb558a220, uid 10093
,09-08 14:32:05.875  7523  7523 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-08 14:32:05.878  7523  7568 W AudioManagerAndroid: Requires BLUETOOTH permission
09-08 14:32:05.878  7523  7523 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-08 14:32:05.880  7523  7523 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-08 14:32:05.910  7523  7523 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:05.910  7523  7523 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:05.910  7523  7523 I Adreno-EGL: Build Date: 12/12/14 금
09-08 14:32:05.910  7523  7523 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 14:32:05.910  7523  7523 I Adreno-EGL: Remote Branch: 
09-08 14:32:05.910  7523  7523 I Adreno-EGL: Local Patches: 
09-08 14:32:05.910  7523  7523 I Adreno-EGL: Reconstruct Branch: 
,09-08 14:32:06.014  7523  7523 I NSApplication: Starting up...
,09-08 14:32:06.053  7120  7251 D serial_port: close(fd = 25)
,09-08 14:32:06.065  7120  7251 I UEI.SmartControl: Serial port is closed.
,09-08 14:32:06.091  1030  1045 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7584 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-08 14:32:06.094  1030  1045 I ActivityManager: Killing 7081:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-08 14:32:06.106  1030  1408 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 3 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=32.5, 0.0, 0.0  rx=24.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:164143578] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 14:32:06.109  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=32.5, 0.0, 0.0  rx=24.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:164143580] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 14:32:06.109  1030  1408 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-08 14:32:06.167  1584  1584 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 14:32:06.177  1030  1923 W libprocessgroup: failed to open /acct/uid_10037/pid_7081/cgroup.procs: No such file or directory
09-08 14:32:06.181  1030  1421 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-08 14:32:06.196  1030  1464 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:06.201  1030  1112 D Tethering: MasterInitialState.processMessage what=3
09-08 14:32:06.202  1030  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:06.205  1030  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-08 14:32:06.211  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:06.216  5352  5352 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-08 14:32:06.228  7584  7584 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:32:06.515  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-08 14:32:06.517  5224  5252 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-08 14:32:06.533  2187  2187 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:06.543  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 14:32:06.543  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:06.543  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 14:32:06.546  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-08 14:32:06.549  7411  7411 I AppUp4:CustModeStarterReceiver: onReceive
09-08 14:32:06.550  5982  6084 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 850)
09-08 14:32:06.552  5982  6084 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-08 14:32:06.552  5982  6084 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 851)
09-08 14:32:06.554  7411  7411 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1e7c3037
09-08 14:32:06.554  7411  7411 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 14:32:06.554  7411  7411 D AppUp4:CustFacade: isPhone : true
09-08 14:32:06.554  7411  7411 D AppUp4:CustModeStarterReceiver: begin check event
09-08 14:32:06.554  7411  7411 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 14:32:06.558  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:32:06.558  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51332b added. We now have 2 listener(s)
,09-08 14:32:06.559  1030  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:06.561  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:06.563  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 14:32:06.564  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:32:06.564  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:32:06.564  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:32:06.564  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c1388 added. We now have 2 listener(s)
09-08 14:32:06.564  5982  6084 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:32:06.564  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:32:06.562  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:32:06.566  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:32:06.570  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 14:32:06.573  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:06.580  3381  3381 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:06.583  5982  6084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:32:06.583  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:06.583  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:06.583  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:06.583  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:06.583  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:06.583  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:06.583  5982  6084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:32:06.587  3381  3381 V DownloadManager: DownloadService onCreate
09-08 14:32:06.588  5982  6084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:06.588  5982  6084 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:32:06.592  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:06.592  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:06.592  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:06.592  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:06.592  5982  6084 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51332b removed from the list
09-08 14:32:06.592  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:06.592  4152  7619 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:32:06.592  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c1388 removed from the list
09-08 14:32:06.593  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:06.593  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:06.593  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:06.595  3381  7617 I DownloadManager: in removeSpuriousFiles
,09-08 14:32:06.596  4152  7621 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:06.596  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:32:06.596  5982  6084 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:32:06.596  4152  7621 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:32:06.596  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:32:06.596  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:06.596  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:32:06.598  3381  7617 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-08 14:32:06.602  4152  7619 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 14:32:06.606  3381  7617 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@f426d21 on behalf of 3381
09-08 14:32:06.607  3381  7617 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-08 14:32:06.607  3381  7617 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-08 14:32:06.607  3381  7617 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-08 14:32:06.607  3381  7617 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-08 14:32:06.607  3381  7617 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-08 14:32:06.607  3381  7617 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-08 14:32:06.607  3381  7617 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-08 14:32:06.607  3381  7617 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-08 14:32:06.607  3381  7617 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-08 14:32:06.607  3381  7617 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-08 14:32:06.608  3381  7617 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-08 14:32:06.608  5982  5982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:06.610  5982  6084 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 14:32:06.611  3381  7617 I DownloadManager: in trimDatabase
,09-08 14:32:06.612  3381  7617 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-08 14:32:06.613  1030  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:06.616  3381  3381 V DownloadManager: DownloadService onStartCommand
09-08 14:32:06.616  3381  7618 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-08 14:32:06.619  4152  7619 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 14:32:06.620  3381  7617 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@23c8c34 on behalf of 3381
09-08 14:32:06.622  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 14:32:06.622  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:32:06.624  3281  3281 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 14:32:06.624  3281  3281 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:06.624  3281  3281 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 14:32:06.625  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:32:06.627  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:06.629  4152  4152 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-08 14:32:06.629  5982  6084 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:32:06.630  4152  4152 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-08 14:32:06.630  4152  4152 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 14:32:06.632  6523  6523 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 14:32:06.632  6523  6523 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 14:32:06.632  4152  4152 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 14:32:06.628  3381  7618 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@ab7ba5d on behalf of 3381
09-08 14:32:06.635  3381  7618 V DownloadManager: processing inserted download 1
09-08 14:32:06.637  3381  7618 V DownloadManager: processing inserted download 4
09-08 14:32:06.638  3381  7618 V DownloadManager: processing inserted download 7
09-08 14:32:06.639  3381  7618 V DownloadManager: processing inserted download 8
09-08 14:32:06.640  3381  7618 V DownloadManager: processing inserted download 9
,09-08 14:32:06.642  7444  7623 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:06.643  4152  4152 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-08 14:32:06.644  3381  7618 V DownloadManager: processing inserted download 10
09-08 14:32:06.645  6594  6594 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:6
09-08 14:32:06.645  3381  7618 V DownloadManager: processing inserted download 11
09-08 14:32:06.646  6594  6594 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 14:32:06.646  6594  6594 D Weather.Utils: 2 : All the weather widget is gone.
09-08 14:32:06.646  3381  7618 V DownloadManager: processing inserted download 12
09-08 14:32:06.647  6594  6594 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:32:06.647  6594  6594 D WeatherAncestor: connectivity changed - connection : true
09-08 14:32:06.647  6594  6594 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a9af30d
09-08 14:32:06.647  3381  7618 V DownloadManager: processing inserted download 13
09-08 14:32:06.648  6594  6594 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 14:32:06.648  6594  6594 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 14:32:06.648  6594  6594 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 14:32:06.648  6594  6594 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 14:32:06.648  6594  6594 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:6
09-08 14:32:06.648  3381  7618 V DownloadManager: processing inserted download 14
09-08 14:32:06.650  3381  7618 V DownloadManager: processing inserted download 16
09-08 14:32:06.656  3381  3381 V DownloadManager: DownloadService onDestroy
,09-08 14:32:06.699  7255  7627 V FormManager: There are no updated forms. The schedule will be deleted.
,09-08 14:32:06.701  7255  7627 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-08 14:32:06.740  1030  1994 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7634 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-08 14:32:06.811  7634  7634 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-08 14:32:06.890  7634  7634 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 14:32:06.890  7634  7634 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 14:32:07.047  7634  7666 I Babel   : MmsConfig: mnc/mcc: 0/0
09-08 14:32:07.047  7634  7666 I Babel   : MmsConfig.loadMmsSettings
,09-08 14:32:07.054  7634  7666 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-08 14:32:07.054  7634  7666 I Babel   : MmsConfig.loadFromDatabase
,09-08 14:32:07.089  7634  7666 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-08 14:32:07.090  7634  7666 I Babel   : MmsConfig.loadFromResources
09-08 14:32:07.092  7634  7666 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-08 14:32:07.093  7634  7666 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-08 14:32:07.102  7634  7634 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:07.107  7634  7664 W AudioCapabilities: Unsupported mime audio/evrc
09-08 14:32:07.109  7634  7664 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 14:32:07.111  7634  7664 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:32:07.126  7634  7664 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-08 14:32:07.128  7634  7664 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 14:32:07.130  7634  7664 W AudioCapabilities: Unsupported mime audio/evrc
09-08 14:32:07.139  1799  7671 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-08 14:32:07.139  1799  7671 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-08 14:32:07.144  7411  7411 I AppUp4:CustModeStarterReceiver: onReceive
,09-08 14:32:07.163  7411  7411 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1e7c3037
09-08 14:32:07.163  7411  7411 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 14:32:07.163  7411  7411 D AppUp4:CustFacade: isPhone : true
09-08 14:32:07.164  7411  7411 D AppUp4:CustModeStarterReceiver: begin check event
09-08 14:32:07.164  7411  7411 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-08 14:32:07.169  7634  7664 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-08 14:32:07.171  1799  4608 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-08 14:32:07.172  7634  7664 W VideoCapabilities: Unsupported mime video/divx
,09-08 14:32:07.174  7634  7664 W VideoCapabilities: Unsupported mime video/divx311
09-08 14:32:07.177  7634  7664 W VideoCapabilities: Unsupported mime video/divx4
09-08 14:32:07.189  7634  7664 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-08 14:32:07.206  7634  7664 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-08 14:32:07.207  1030  1994 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7676 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-08 14:32:07.211  1030  1886 I ActivityManager: Killing 7156:com.lge.settings.easy/1000 (adj 15): empty #17
09-08 14:32:07.217  7634  7664 W AudioCapabilities: Unsupported mime audio/eac3
09-08 14:32:07.218  7634  7664 W AudioCapabilities: Unsupported mime audio/ac3
,09-08 14:32:07.221  7634  7664 W AudioCapabilities: Unsupported mime audio/g726
09-08 14:32:07.222  7634  7664 W AudioCapabilities: Unsupported mime audio/wma-voice
09-08 14:32:07.223  7634  7664 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-08 14:32:07.225  7634  7664 W AudioCapabilities: Unsupported mime audio/adpcm
09-08 14:32:07.227  7634  7664 W VideoCapabilities: Unsupported mime video/theora
09-08 14:32:07.227   344   344 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 414us total 20.152ms
09-08 14:32:07.229  7634  7664 W VideoCapabilities: Unsupported mime video/mjpg
09-08 14:32:07.246   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 394us total 18.263ms
,09-08 14:32:07.265   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 394us total 18.188ms
,09-08 14:32:07.353  1030  1941 W libprocessgroup: failed to open /acct/uid_1000/pid_7156/cgroup.procs: No such file or directory
09-08 14:32:07.384  7676  7676 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:07.385  7676  7676 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 14:32:07.385  7676  7676 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-08 14:32:07.386  7676  7676 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-08 14:32:07.386  7676  7676 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 14:32:07.387   308  7694 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 14:32:07.387   308  7694 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,09-08 14:32:07.416  1030  1886 V SIM_STK : Menu title from STK is T-Mobile
09-08 14:32:07.417   308  7694 D libc-netbsd: res_queryN name = www.google.com succeed
,09-08 14:32:07.420   308  7697 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 14:32:07.420   308  7697 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-08 14:32:07.421   308  7697 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-08 14:32:07.424  1799  6949 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-08 14:32:07.433   308  7699 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-08 14:32:07.434   308  7699 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-08 14:32:07.468   308  7699 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-08 14:32:07.470  7676  7676 I SystemConfig: BUILD Country: EU
,09-08 14:32:07.470  7676  7676 I SystemConfig: BUILD Operator: OPEN
09-08 14:32:07.475  1030  1422 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
09-08 14:32:07.516  1030  1578 I ActivityManager: Killing 6886:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-08 14:32:07.574  1030  1046 W libprocessgroup: failed to open /acct/uid_10005/pid_6886/cgroup.procs: No such file or directory
,09-08 14:32:07.641  1030  1941 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7702 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-08 14:32:07.652  7676  7700 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-08 14:32:07.652  7676  7700 I SystemConfig: existFile = false
09-08 14:32:07.652  7676  7700 I SystemConfig: canReadFile = false
09-08 14:32:07.652  7676  7700 I SystemConfig: systemFeature RCS result false
09-08 14:32:07.652  7676  7700 D SystemConfig: refreshRcsSupport() :false
,09-08 14:32:07.694  7702  7702 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:32:07.695  7702  7702 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 14:32:07.695  7702  7702 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-08 14:32:07.695  7702  7702 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-08 14:32:07.805  7702  7702 I AppConfig: Total System Memory = 2995761152
,09-08 14:32:07.815  7702  7702 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-08 14:32:07.848  1799  6949 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-08 14:32:07.909  1030  1994 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7724 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:07.911  1030  1994 I ActivityManager: Killing 7031:com.lge.bnr/1000 (adj 15): empty #17
09-08 14:32:07.956  1030  1886 W libprocessgroup: failed to open /acct/uid_1000/pid_7031/cgroup.procs: No such file or directory
,09-08 14:32:07.957  1799  1799 I ConfigFetchService: fetch service done; releasing wakelock
09-08 14:32:07.960  1799  1799 I ConfigFetchService: stopping self
09-08 14:32:08.025  2187  2187 I ConfigService: onDestroy
,09-08 14:32:08.181  1030  1750 I art     : Explicit concurrent mark sweep GC freed 32008(1600KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.435ms total 141.503ms
,09-08 14:32:08.297  7724  7724 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-08 14:32:08.411  7724  7724 D LgDataFeature: LgDataFeature() Constructor: none
09-08 14:32:08.412  7724  7724 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 14:32:08.465  7724  7724 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-08 14:32:08.485  7724  7724 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-08 14:32:08.486  7724  7724 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-08 14:32:08.508  7724  7724 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-08 14:32:08.508  7724  7724 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-08 14:32:08.538  1030  1637 I ActivityManager: Killing 7225:com.lge.sync/1000 (adj 15): empty #17
,09-08 14:32:08.596  1030  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_7225/cgroup.procs: No such file or directory
,09-08 14:32:08.606  3381  3807 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-08 14:32:08.607  3381  3807 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@282d78a3 on behalf of 7724
09-08 14:32:08.610  4437  7764 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-08 14:32:08.667  1030  1904 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7765 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:08.706  7724  7724 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-08 14:32:08.753  7724  7724 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-08 14:32:08.777  7765  7765 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-08 14:32:08.798  7765  7765 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,09-08 14:32:08.798  7765  7765 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-08 14:32:08.798  7765  7765 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-08 14:32:08.798  7765  7765 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-08 14:32:08.798  7765  7765 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-08 14:32:08.798  7765  7765 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-08 14:32:08.799  1030  1749 I ActivityManager: Killing 7120:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-08 14:32:08.812  6295  6295 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-08 14:32:08.812  6295  6295 W System.err: android.os.DeadObjectException
09-08 14:32:08.812  6295  6295 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 14:32:08.812  6295  6295 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 14:32:08.812  6295  6295 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-08 14:32:08.812  6295  6295 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-08 14:32:08.813  6295  6295 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 14:32:08.813  6295  6295 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 14:32:08.813  6295  6295 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:32:08.813  6295  6295 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:32:08.813  6295  6295 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:32:08.813  6295  6295 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 14:32:08.813  6295  6295 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:32:08.813  6295  6295 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:32:08.813  6295  6295 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 14:32:08.813  6295  6295 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 14:32:08.813  6295  6295 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-08 14:32:08.814  6295  6295 W System.err: android.os.DeadObjectException
,09-08 14:32:08.814  6295  6295 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,09-08 14:32:08.814  6295  6295 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 14:32:08.815  6295  6295 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,09-08 14:32:08.815  6295  6295 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-08 14:32:08.815  6295  6295 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 14:32:08.815  6295  6295 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 14:32:08.815  6295  6295 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:32:08.815  6295  6295 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:32:08.815  6295  6295 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:32:08.815  6295  6295 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 14:32:08.815  6295  6295 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:32:08.816  6295  6295 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:32:08.816  6295  6295 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 14:32:08.816  6295  6295 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 14:32:08.816  6295  6295 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-08 14:32:08.817  6295  6295 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-08 14:32:08.909  1030  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_7120/cgroup.procs: No such file or directory
09-08 14:32:08.911  1030  1995 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-08 14:32:08.926  6295  6295 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-08 14:32:08.927  6295  6295 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-08 14:32:09.006  1030  1750 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7798 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 14:32:09.007  6295  6295 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-08 14:32:09.017  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-08 14:32:09.019  5224  5252 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-08 14:32:09.042  2187  2187 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:09.051  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 14:32:09.051  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:09.051  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 14:32:09.051  7411  7411 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 14:32:09.053  7411  7411 I AppUp4:CustModeStarterReceiver: onReceive
,09-08 14:32:09.057  7411  7411 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1e7c3037
09-08 14:32:09.057  7411  7411 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 14:32:09.058  7411  7411 D AppUp4:CustFacade: isPhone : true
09-08 14:32:09.058  7411  7411 D AppUp4:CustModeStarterReceiver: begin check event
,09-08 14:32:09.058  7411  7411 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 14:32:09.061  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:09.062  4152  4152 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:32:09.063  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 14:32:09.072  4152  4152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 14:32:09.076  3381  3381 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:09.081  3381  3381 V DownloadManager: DownloadService onCreate
,09-08 14:32:09.083  3381  7816 I DownloadManager: in removeSpuriousFiles
,09-08 14:32:09.085  3381  7816 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-08 14:32:09.088  3381  7816 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@273037a0 on behalf of 3381
09-08 14:32:09.089  4152  7815 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:32:09.089  3381  7816 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-08 14:32:09.089  3381  7816 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-08 14:32:09.089  3381  7816 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-08 14:32:09.089  3381  7816 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-08 14:32:09.089  3381  7816 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-08 14:32:09.089  3381  7816 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-08 14:32:09.089  3381  7816 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-08 14:32:09.089  3381  7816 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-08 14:32:09.089  3381  7816 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-08 14:32:09.090  3381  7816 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-08 14:32:09.090  3381  7816 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-08 14:32:09.091  3381  7816 I DownloadManager: in trimDatabase
09-08 14:32:09.091  3381  7816 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-08 14:32:09.093  4152  7818 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:09.093  4152  7818 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:32:09.093  3381  7816 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1b59271e on behalf of 3381
09-08 14:32:09.096  4152  7815 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 14:32:09.099  3381  3381 V DownloadManager: DownloadService onStartCommand
09-08 14:32:09.100  3381  7817 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-08 14:32:09.103  7444  7820 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:09.104  3381  7817 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@29f12dcc on behalf of 3381
09-08 14:32:09.106  3381  7817 V DownloadManager: processing inserted download 1
09-08 14:32:09.107  3381  7817 V DownloadManager: processing inserted download 4
,09-08 14:32:09.108  3381  7817 V DownloadManager: processing inserted download 7
09-08 14:32:09.109  3381  7817 V DownloadManager: processing inserted download 8
09-08 14:32:09.109  3381  7817 V DownloadManager: processing inserted download 9
09-08 14:32:09.110  3381  7817 V DownloadManager: processing inserted download 10
09-08 14:32:09.112  3381  7817 V DownloadManager: processing inserted download 11
09-08 14:32:09.112  4152  7815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 14:32:09.114  3281  3281 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 14:32:09.114  3281  3281 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:09.114  3281  3281 I LgeMiscReceiver: networkInfo.isConnected() = true
09-08 14:32:09.115  3281  3281 D PhoneState: setPdpRejectCasuse : false
09-08 14:32:09.115  4152  4152 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-08 14:32:09.115  4152  4152 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-08 14:32:09.116  4152  4152 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 14:32:09.117  4152  4152 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 14:32:09.117  6523  6523 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 14:32:09.118  6523  6523 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 14:32:09.119  3381  7817 V DownloadManager: processing inserted download 12
09-08 14:32:09.120  7798  7798 D UEI.SmartControl: Quickset Services start...
09-08 14:32:09.120  3381  7817 V DownloadManager: processing inserted download 13
09-08 14:32:09.121  4152  4152 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-08 14:32:09.122  3381  7817 V DownloadManager: processing inserted download 14
09-08 14:32:09.122  7798  7798 I UEI.SmartControl: Manufacture = LGE
09-08 14:32:09.123  7798  7798 D UEI.SmartControl: Id = LGNevo
09-08 14:32:09.126  7798  7798 D UEI.SmartControl: File observer start...
,09-08 14:32:09.127  6594  6594 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:9
,09-08 14:32:09.128  6594  6594 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 14:32:09.128  6594  6594 D Weather.Utils: 2 : All the weather widget is gone.
09-08 14:32:09.128  6594  6594 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:32:09.128  3381  7817 V DownloadManager: processing inserted download 16
09-08 14:32:09.129  6594  6594 D WeatherAncestor: connectivity changed - connection : true
09-08 14:32:09.129  6594  6594 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a9af30d
09-08 14:32:09.129  7798  7798 E UEI.SmartControl: IR Port is disabled: false
09-08 14:32:09.129  7798  7798 D UEI.SmartControl: Starting file observer...
09-08 14:32:09.129  7798  7798 D UEI.SmartControl: Extracting JNI libs...
09-08 14:32:09.129  7798  7798 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-08 14:32:09.130  6594  6594 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 14:32:09.130  6594  6594 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 14:32:09.130  6594  6594 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 14:32:09.130  6594  6594 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 14:32:09.130  6594  6594 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:9
09-08 14:32:09.133  3381  3381 V DownloadManager: DownloadService onDestroy
,09-08 14:32:09.172  1030  1408 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 3 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=27.8, 0.0, 0.0  rx=22.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:164146644] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 14:32:09.173  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=27.8, 0.0, 0.0  rx=22.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:164146645] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 14:32:09.173  1030  1408 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-08 14:32:09.198  7255  7824 V FormManager: There are no updated forms. The schedule will be deleted.
,09-08 14:32:09.205  7255  7824 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-08 14:32:09.219  7798  7798 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-08 14:32:09.219  7798  7798 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-08 14:32:09.219  7798  7798 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-08 14:32:09.226  1030  1994 V SIM_STK : Menu title from STK is T-Mobile
09-08 14:32:09.240  4437  7764 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 630 ms] updated apps [took 630 ms] 
,09-08 14:32:09.245  7798  7798 I UEI.SmartControl: --- Selecting new region: 6
,09-08 14:32:09.247  7798  7798 I UEI.SmartControl: Model = LG-D855
09-08 14:32:09.248  7798  7798 D UEI.SmartControl: QS Service created
09-08 14:32:09.256  7798  7798 I UEI.SmartControl: Service initServices...
,09-08 14:32:09.259  7798  7798 D UEI.SmartControl: QS start get config
,09-08 14:32:09.285  7798  7798 D UEI.SmartControl: Loading JNI Libs...
,09-08 14:32:09.519  7798  7798 I UEI.SmartControl: Supports setup maps: true
,09-08 14:32:09.523  7798  7798 D UEI.SmartControl: QS start statue = true Error code = 0
09-08 14:32:09.523  7798  7798 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-08 14:32:09.523  7798  7798 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-08 14:32:09.523  7798  7798 I UEI.SmartControl: ### init IR Blaster...
09-08 14:32:09.533  7798  7798 D serial_port: Configuring serial port
09-08 14:32:09.536  7798  7798 E UEI.SmartControl: UEIBLaster setting for 616
09-08 14:32:09.537  7798  7798 I UEI.SmartControl: Setting serial record hearder size = 2
09-08 14:32:09.537  7798  7798 I UEI.SmartControl: configuring settings for MAXQ616
09-08 14:32:09.537  7798  7798 I UEI.SmartControl: Get version...
,09-08 14:32:09.554  7798  7832 D UEI.SmartControl: serial port data available: 21,
,09-08 14:32:09.582  7798  7798 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-08 14:32:09.582  7798  7798 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-08 14:32:09.587  7798  7798 I UEI.SmartControl: QS saving settings...
09-08 14:32:09.589  7798  7798 D UEI.SmartControl: IR Blaster version: 25672567
09-08 14:32:09.607  7798  7832 D UEI.SmartControl: serial port data available: 4
,09-08 14:32:09.630  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 14:32:09.630  5982  6084 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 14:32:09.636  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:09.636  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:09.636  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:09.636  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51332b not in the list
09-08 14:32:09.636  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:09.637  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c1388 not in the list
09-08 14:32:09.637  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:09.637  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:09.637  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:09.640  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:32:09.642  5982  6084 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-08 14:32:09.642  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-08 14:32:09.645  7798  7798 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-08 14:32:09.651  7798  7798 E UEI.SmartControl: Services init done
09-08 14:32:09.652  7798  7798 D UEI.SmartControl: QS Service init finished
,09-08 14:32:09.652  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:32:09.652  5982  6084 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 14:32:09.652  5982  6084 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 14:32:09.652  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:09.653  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 14:32:09.653  5982  6084 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 14:32:09.653  5982  6084 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:32:09.654  7798  7798 D UEI.SmartControl: QS Service version name: 2.1.91
09-08 14:32:09.654  7798  7798 D UEI.SmartControl: QS Service version code: 201091
09-08 14:32:09.654  5982  5982 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 14:32:09.656  7798  7836 I UEI.SmartControl: Device manager: loading config....
09-08 14:32:09.656  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 14:32:09.656  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 14:32:09.656  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:09.656  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:32:09.656  7798  7836 D UEI.SmartControl: ----------- loading internal config...
09-08 14:32:09.659  1030  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:09.664  5982  7838 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:32:09.665  6827  7079 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-08 14:32:09.666  5982  7838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-08 14:32:09.668  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:32:09.668  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:09.670  7798  7798 D UEI.SmartControl: Service requested: Control
09-08 14:32:09.670  5982  6084 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:32:09.670  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:09.670  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:32:09.670  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:32:09.670  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:32:09.671  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:09.671  5982  6084 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:32:09.671  5982  5982 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 14:32:09.671  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51332b not in the list
09-08 14:32:09.671  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:09.671  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c1388 not in the list
09-08 14:32:09.671  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:09.671  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:09.671  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:09.672  7798  7836 E UEI.SmartControl: Loading SETTINGS...
09-08 14:32:09.672  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:32:09.672  5982  6084 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:32:09.672  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:32:09.672  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:09.672  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:32:09.673  5982  7838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 14:32:09.673  5982  7838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:32:09.673  5982  7838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 14:32:09.674  5982  5982 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 14:32:09.677  1030  1905 I ActivityManager: Killing 6213:com.android.setting,s/1000 (adj 15): empty #17
,09-08 14:32:09.680  5982  6084 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:32:09.683  6295  6295 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-08 14:32:09.684  7798  7813 I UEI.SmartControl: ------ IControl API: 11
09-08 14:32:09.685  7798  7813 I UEI.SmartControl: Registering callback...
09-08 14:32:09.686  7798  7814 I UEI.SmartControl: ------ IControl API: 19
09-08 14:32:09.686  7798  7814 I UEI.SmartControl: Registering Services Ready callback...
09-08 14:32:09.693  7798  7836 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-08 14:32:09.702  1030  1451 D WifiService: Client connection lost with reason: 4
09-08 14:32:09.713  7798  7798 D UEI.SmartControl: Internal service binding...
09-08 14:32:09.713  1030  1578 W libprocessgroup: failed to open /acct/uid_1000/pid_6213/cgroup.procs: No such file or directory
,09-08 14:32:09.715  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:09.718  7798  7835 I UEI.SmartControl: Notify AllClients services are ready: 0
09-08 14:32:09.718  7798  7835 D UEI.SmartControl: -----service ready thread exits
09-08 14:32:09.719  6295  6310 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-08 14:32:09.719  6295  6332 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-08 14:32:09.719  6295  6332 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-08 14:32:09.721  5982  6084 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:32:09.721  6295  6295 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-08 14:32:09.721  6295  6295 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-08 14:32:09.722  7798  7813 I UEI.SmartControl: ------ IControl API: 8
09-08 14:32:09.723  6295  6295 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-08 14:32:09.723  6295  6295 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-08 14:32:09.723  6295  6295 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-08 14:32:09.723  6295  6295 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-08 14:32:09.724  6295  6295 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-08 14:32:09.724  6295  6295 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,09-08 14:32:09.726  6295  6295 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-08 14:32:09.730  6295  6295 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-08 14:32:09.731  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-08 14:32:09.732  6295  6295 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 14:32:09.732  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-08 14:32:09.734  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-08 14:32:09.735  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-08 14:32:09.735  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-08 14:32:09.736  6295  6295 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473337929735]
09-08 14:32:09.748  6295  7839 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-08 14:32:09.756  6295  6295 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-08 14:32:09.757  6295  6295 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 14:32:09.758  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-08 14:32:09.758  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-08 14:32:09.759  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-08 14:32:09.759  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-08 14:32:09.759  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-08 14:32:09.762  6295  6295 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-08 14:32:10.566  7523  7543 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-08 14:32:11.525  1030  1750 I ActivityManager: Killing 7634:com.google.android.talk/u0a72 (adj 15): empty #17
,09-08 14:32:11.557  1030  1904 W libprocessgroup: failed to open /acct/uid_10072/pid_7634/cgroup.procs: No such file or directory
,09-08 14:32:12.187  1030  1408 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 3 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=25.9, 0.0, 0.0  rx=20.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:164149658] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 14:32:12.190  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=25.9, 0.0, 0.0  rx=20.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:164149661] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 14:32:12.190  1030  1408 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-08 14:32:12.721  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:12.721  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:12.721  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:12.721  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51332b not in the list
09-08 14:32:12.722  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:12.722  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c1388 not in the list
09-08 14:32:12.722  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:12.722  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:12.722  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:12.723  5982  6084 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:12.723  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:12.723  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:12.723  5982  6084 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51332b not in the list
09-08 14:32:12.723  5982  6084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:12.723  5982  6084 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c1388 not in the list
09-08 14:32:12.723  5982  6084 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:12.723  5982  6084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:12.723  5982  6084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:12.724  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 14:32:12.724  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 14:32:12.724  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 14:32:12.725  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:32:12.725  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 14:32:12.725  5982  6084 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:32:12.742  5982  7860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: My test thread name)
,09-08 14:32:14.645  7798  7837 D UEI.SmartControl: Internal timer expired: 1
,09-08 14:32:14.645  7798  7837 D UEI.SmartControl: unbind internal service
,09-08 14:32:14.664  7798  7833 D serial_port: close(fd = 25)
,09-08 14:32:14.671  7798  7833 I UEI.SmartControl: Serial port is closed.
,09-08 14:32:14.740  5982  6084 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 870
,09-08 14:32:14.741  5982  6084 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 870, name: My test thread name)
,09-08 14:32:14.755  5982  7861 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 871, name: My test thread name)
09-08 14:32:14.755  5982  7861 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 871, thread name: My test thread name)
09-08 14:32:14.755  5982  7861 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 871, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-08 14:32:14.757  5982  6084 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:14.762  5982  7862 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: My test thread name)
09-08 14:32:14.762  5982  7862 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 875, thread name: My test thread name): Test exception.
09-08 14:32:14.763  5982  7862 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 875, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 14:32:14.768  5982  6084 I jxcore-log: Total number of executed tests:  82
09-08 14:32:14.768  5982  6084 I jxcore-log: 
09-08 14:32:14.768  5982  6084 I jxcore-log: Number of passed tests:  82
09-08 14:32:14.768  5982  6084 I jxcore-log: 
09-08 14:32:14.768  5982  6084 I jxcore-log: Number of failed tests:  0
09-08 14:32:14.768  5982  6084 I jxcore-log: 
09-08 14:32:14.769  5982  6084 I jxcore-log: Number of ignored tests:  0
09-08 14:32:14.769  5982  6084 I jxcore-log: 
09-08 14:32:14.769  5982  6084 I jxcore-log: Total duration:  29887
09-08 14:32:14.769  5982  6084 I jxcore-log: 
09-08 14:32:14.772  5982  6084 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-08 14:32:14.772  5982  6084 I jxcore-log: 
09-08 14:32:14.773  5982  6084 I jxcore-log: My device name is: LGE-LG-D855
09-08 14:32:14.773  5982  6084 I jxcore-log: 
09-08 14:32:14.776  5982  6084 I jxcore-log: WARN testUtils: myNameCallback not set!
09-08 14:32:14.776  5982  6084 I jxcore-log: 
09-08 14:32:14.790  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:32:14.790  5982  6084 I jxcore-log: 
,09-08 14:32:14.796  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.796  5982  6084 I jxcore-log: 
09-08 14:32:14.797  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.797  5982  6084 I jxcore-log: 
09-08 14:32:14.798  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.798  5982  6084 I jxcore-log: 
09-08 14:32:14.801  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.801  5982  6084 I jxcore-log: 
09-08 14:32:14.808  5982  7860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,09-08 14:32:14.813  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.813  5982  6084 I jxcore-log: 
09-08 14:32:14.814  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.814  5982  6084 I jxcore-log: 
09-08 14:32:14.814  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.814  5982  6084 I jxcore-log: 
09-08 14:32:14.815  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:32:14.815  5982  6084 I jxcore-log: 
09-08 14:32:14.817  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:32:14.817  5982  6084 I jxcore-log: 
09-08 14:32:14.818  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:32:14.818  5982  6084 I jxcore-log: 
09-08 14:32:14.819  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:32:14.819  5982  6084 I jxcore-log: 
09-08 14:32:14.820  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:32:14.820  5982  6084 I jxcore-log: 
09-08 14:32:14.821  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:32:14.821  5982  6084 I jxcore-log: 
,09-08 14:32:14.825  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:32:14.825  5982  6084 I jxcore-log: 
09-08 14:32:14.825  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.825  5982  6084 I jxcore-log: 
09-08 14:32:14.826  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.826  5982  6084 I jxcore-log: 
09-08 14:32:14.827  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.827  5982  6084 I jxcore-log: 
09-08 14:32:14.828  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.828  5982  6084 I jxcore-log: 
09-08 14:32:14.829  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.829  5982  6084 I jxcore-log: 
09-08 14:32:14.830  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.830  5982  6084 I jxcore-log: 
09-08 14:32:14.830  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.830  5982  6084 I jxcore-log: 
09-08 14:32:14.833  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:32:14.833  5982  6084 I jxcore-log: 
09-08 14:32:14.834  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:32:14.834  5982  6084 I jxcore-log: 
09-08 14:32:14.835  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:32:14.835  5982  6084 I jxcore-log: 
09-08 14:32:14.836  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:32:14.836  5982  6084 I jxcore-log: 
09-08 14:32:14.836  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.836  5982  6084 I jxcore-log: 
09-08 14:32:14.837  5982  6084 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:14.837  5982  6084 I jxcore-log: 
,09-08 14:32:15.120  7863  7863 D AndroidRuntime: 
09-08 14:32:15.120  7863  7863 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-08 14:32:15.123  7863  7863 D AndroidRuntime: CheckJNI is OFF
09-08 14:32:15.210  1030  1408 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 3 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=13.9, 0.0, 0.0  rx=10.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:164152682] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 14:32:15.211  1030  1408 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=13.9, 0.0, 0.0  rx=10.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:164152683] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 14:32:15.211  1030  1408 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-08 14:32:15.328  7863  7863 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-08 14:32:15.344  1030  1104 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-08 14:32:15.346  1030  1104 I ActivityManager: Killing 5982:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-08 14:32:15.418  1030  1941 I WindowState: WIN DEATH: Window{169208bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 14:32:15.419  1030  1451 D WifiService: Client connection lost with reason: 4
,09-08 14:32:15.431  1030  1941 D InputDispatcher: Window went away: Window{169208bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-08 14:32:15.573  1030  1104 I ActivityManager:   Force finishing activity ActivityRecord{188fa18 u0 com.test.thalitest/.MainActivity t6}
,09-08 14:32:15.598   330   346 E GBMv2   : DFP En is all cleared set to be enabled
09-08 14:32:15.600  1030  1994 W ActivityManager: Spurious death for ProcessRecord{31ae19e6 5982:com.test.thalitest/u0a118}, curProc for 5982: null
,09-08 14:32:15.602  1030  1118 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,09-08 14:32:15.609  1030  1118 I ActivityManager:   Force finishing activity ActivityRecord{188fa18 u0 com.test.thalitest/.MainActivity t6 f}
09-08 14:32:15.609  1030  1118 W ActivityManager: Duplicate finish request for ActivityRecord{188fa18 u0 com.test.thalitest/.MainActivity t6 f}
,09-08 14:32:15.643  2014  2014 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-08 14:32:15.644  1924  3792 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-08 14:32:15.644  1924  3792 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b463ec7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-08 14:32:15.645  2014  2014 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-08 14:32:15.645  1924  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-08 14:32:15.646  1924  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{28f38cf4 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-08 14:32:15.646  2014  2014 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-08 14:32:15.647  2014  2108 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-08 14:32:15.652  1887  1887 D ActionManagerService: notifyUserLog: 1000003
09-08 14:32:15.653  2740  4344 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-08 14:32:15.653  2014  2014 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-08 14:32:15.655  1584  1584 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-08 14:32:15.661  1977  1977 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,09-08 14:32:15.665  1030  1360 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-08 14:32:15.668  2473  2591 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 14:32:15.672  2740  2740 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-08 14:32:15.678  6827  6827 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-08 14:32:15.678  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-08 14:32:15.719  4437  4437 I art     : Explicit concurrent mark sweep GC freed 8238(470KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 1.373ms total 76.736ms
,09-08 14:32:15.742  5224  5224 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,09-08 14:32:15.743  1030  1923 V SIM_STK : Menu title from STK is T-Mobile
09-08 14:32:15.754  2014  2014 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-08 14:32:15.755  4316  4316 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-08 14:32:15.755  4316  4316 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-08 14:32:15.756  4316  4316 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-08 14:32:15.756  4316  4316 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-08 14:32:15.756  4316  4316 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,09-08 14:32:15.756  4316  4316 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:32:15.756  4316  4316 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:32:15.756  4316  4316 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 14:32:15.756  4316  4316 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:32:15.756  4316  4316 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:32:15.756  4316  4316 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 14:32:15.757  4316  4316 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 14:32:15.781  1852  1852 D SplitUIManager: split_name #11 / not available #0
,09-08 14:32:15.784  1852  1852 D SplitUIService: removed split : 
09-08 14:32:15.784  1584  1584 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-08 14:32:15.789  1799  1799 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-08 14:32:15.798  2014  2014 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-08 14:32:15.799  1584  1629 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-08 14:32:15.799  1584  1629 D KeyguardModel: createShortcutInfo...
,09-08 14:32:15.805  2014  2014 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-08 14:32:15.811  1887  1887 D ActionManagerService: notifyUserLog: 1000004
09-08 14:32:15.811  2014  2014 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-08 14:32:15.811  2740  4344 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-08 14:32:15.812  1584  1629 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-08 14:32:15.812  1584  1629 D KeyguardModel: createShortcutInfo...
09-08 14:32:15.813  2740  2760 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-08 14:32:15.813  2187  2187 I ConfigService: onCreate
09-08 14:32:15.813  2187  2187 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-08 14:32:15.821  1584  1629 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-08 14:32:15.821  1584  1629 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:15.821  1584  1629 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , create_time: 1430832262123
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , expire_time: 0
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , display: false
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , animation: false }
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , create_time: 1430832262287
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , expire_time: 0
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , display: false
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , animation: false }
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , create_time: 1472828323917
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , expire_time: 0
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , display: false
09-08 14:32:15.821  2014  2014 I GBoardWebViewUtils: , animation: false }
09-08 14:32:15.822  1799  1799 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-08 14:32:15.822  1584  1629 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-08 14:32:15.823  1584  1584 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-08 14:32:15.823  1584  1584 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-08 14:32:15.825  1584  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:32:15.825  1584  1629 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-08 14:32:15.827  1584  1629 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-08 14:32:15.827  1584  1629 D KeyguardModel: createShortcutInfo...
,09-08 14:32:15.831  2014  7897 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-08 14:32:15.833  1852  1852 D SplitUIManager: split_name #11 / not available #0
09-08 14:32:15.833  1852  1852 I SplitUIService: split app #11
,09-08 14:32:15.840  1584  1629 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-08 14:32:15.840  1584  1629 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 14:32:15.845  2014  2014 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-08 14:32:15.852  1584  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:32:15.852  1584  1629 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-08 14:32:15.853  1030  1030 I art     : Explicit concurrent mark sweep GC freed 29212(1681KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.502ms total 215.708ms
,09-08 14:32:15.855  2187  2187 I ConfigService: onBind returning update interface
09-08 14:32:15.855  1030  1118 I art     : WaitForGcToComplete blocked for 75.136ms for cause Explicit
09-08 14:32:15.857  1584  1629 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-08 14:32:15.857  1584  1629 D KeyguardModel: createShortcutInfo...
09-08 14:32:15.859  1030  1994 V SIM_STK : Menu title from STK is T-Mobile
09-08 14:32:15.859  1030  1994 V SIM_STK : Menu title from STK is T-Mobile
09-08 14:32:15.866  2187  2187 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-08 14:32:15.866  2187  2187 I ConfigService: onBind returning config service
,09-08 14:32:15.870  2187  2187 I ConfigService: onDestroy
09-08 14:32:15.877  1799  7899 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-08 14:32:15.884  1030  1030 D administrator: Handling package changes for user 0
09-08 14:32:15.884  1584  1629 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:15.884  1584  1629 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 14:32:15.884  1584  1629 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-08 14:32:15.884  1584  1629 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-08 14:32:15.885  1584  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:32:15.885  1584  1629 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-08 14:32:15.886  1584  1629 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-08 14:32:15.886  1584  1629 D KeyguardModel: createShortcutInfo...
,09-08 14:32:15.896  1584  1584 D KeyguardModel: handleShortcutListChanged...
09-08 14:32:15.896  1584  1584 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-08 14:32:15.911  1584  1629 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-08 14:32:15.911  1584  1629 D KeyguardModel: createShortcutInfo...
,09-08 14:32:15.916  1584  1629 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-08 14:32:15.916  1584  1629 D KeyguardModel: createShortcutInfo...
09-08 14:32:15.918  1584  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:32:15.918  1584  1629 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-08 14:32:15.919  2014  2014 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-08 14:32:15.923  2014  2014 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,09-08 14:32:15.923  1584  1629 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-08 14:32:15.923  1584  1629 D KeyguardModel: createShortcutInfo...
09-08 14:32:15.929  1030  1750 V SIM_STK : Menu title from STK is T-Mobile
09-08 14:32:15.930  1584  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:32:15.930  1584  1629 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-08 14:32:15.941  1584  1629 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-08 14:32:15.941  1584  1629 D KeyguardModel: createShortcutInfo...
,09-08 14:32:15.942  1799  7906 I PeopleContactsSync: CP2 sync disabled
09-08 14:32:15.942  1584  1629 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:32:15.942  1584  1629 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-08 14:32:15.943  1584  1629 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-08 14:32:15.943  1584  1629 D KeyguardModel: createShortcutInfo...
09-08 14:32:15.949  5490  7904 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-08 14:32:15.952  1584  1584 D KeyguardModel: handleShortcutListChanged...
09-08 14:32:15.952  1584  1584 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-08 14:32:15.954  1799  4608 I Icing   : doRemovePackageData com.test.thalitest
09-08 14:32:15.963  1030  1045 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-08 14:32:15.963  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-08 14:32:15.963  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-08 14:32:15.963  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-08 14:32:15.963  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-08 14:32:15.963  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-08 14:32:15.963  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 14:32:15.963  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-08 14:32:15.964  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-08 14:32:15.964  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-08 14:32:15.964  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 14:32:15.964  6827  6827 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-08 14:32:15.971  1030  1030 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-08 14:32:15.972  1030  1030 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-08 14:32:15.972  1030  1030 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-08 14:32:15.975  1030  1558 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-08 14:32:15.989  1799  7905 W GmsApplication: Using Auth Proxy for data requests.
,09-08 14:32:15.997  7411  7411 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-08 14:32:16.000  1799  7905 W GmsApplication: Using Auth Proxy for data requests.
09-08 14:32:16.001   324   417 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,09-08 14:32:16.003  3155  7909 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-08 14:32:16.026  2014  2014 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-08 14:32:16.030  2014  2014 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 14:32:16.032  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-08 14:32:16.033  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-08 14:32:16.034  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-08 14:32:16.036  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-08 14:32:16.037  7444  7444 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
09-08 14:32:16.046  2318  7910 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-08 14:32:16.051  1030  1113 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36f8c7f2 u0 com.lge.launcher2/.Launcher t5} time:147920
09-08 14:32:16.057  2014  2014 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-08 14:32:16.057  2014  2209 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-08 14:32:16.057  2014  2014 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 14:32:16.057  2014  2209 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-08 14:32:16.068  1977  1977 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-08 14:32:16.068  1977  1977 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-08 14:32:16.069  1977  1977 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,09-08 14:32:16.076  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-08 14:32:16.077  2014  2014 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-08 14:32:16.077  2014  2014 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 14:32:16.080  5224  5224 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,09-08 14:32:16.084  2014  2014 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-08 14:32:16.085  2624  2624 D [Concierge]Service: onStartCommand(). Type : 8
09-08 14:32:16.085  2624  2624 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-08 14:32:16.086  2624  2624 D [Concierge]Service: Update widget ID : 11
09-08 14:32:16.087  2014  2014 D [Concierge]WidgetView: change position of spinner
09-08 14:32:16.105  1030  1118 I art     : Explicit concurrent mark sweep GC freed 8395(575KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.188ms total 247.328ms
,09-08 14:32:16.121  1030  1749 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7915 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-08 14:32:16.124  2014  2014 I [Concierge]WidgetView: initWebView(). Time : 1473337936124
09-08 14:32:16.124  2624  2624 D [Concierge]Service: onStartCommand(). Type : 0
09-08 14:32:16.134  2014  2014 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 331123562
09-08 14:32:16.135  2014  2014 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-08 14:32:16.135  2014  2014 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-08 14:32:16.137  2014  2014 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@107e6992
09-08 14:32:16.138  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,09-08 14:32:16.139  2014  2014 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-08 14:32:16.140  2014  2014 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 14:32:16.145  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-08 14:32:16.145  2014  2014 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-08 14:32:16.145  2014  2014 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-08 14:32:16.146  2014  2014 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473337815982, New one : 1473337936124
09-08 14:32:16.146  2014  2014 D [Concierge]WidgetView: Unregister all receivers
09-08 14:32:16.146  2014  2014 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-08 14:32:16.146  2014  2014 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 14:32:16.148  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-08 14:32:16.149  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-08 14:32:16.150  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-08 14:32:16.151  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-08 14:32:16.152  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-08 14:32:16.157  2014  2014 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 14:32:16.157  2014  2014 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-08 14:32:16.180  7863  7863 D AndroidRuntime: Shutting down VM
,09-08 14:32:16.198  2014  2014 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-08 14:32:16.206  2014  2014 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-08 14:32:16.206  2014  2014 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-08 14:32:16.207  2014  2014 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-08 14:32:16.214  1030  1118 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7934 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-08 14:32:16.218  7915  7915 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-08 14:32:16.218  7915  7915 W LG Account v2.2: No ProfileInfo entries
09-08 14:32:16.218  7915  7915 I LG Account v2.2: isEnabled: false
09-08 14:32:16.218  7915  7915 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-08 14:32:16.218  7915  7915 I Feature : [Lifetracker]Country: EU
09-08 14:32:16.218  7915  7915 I Feature : [Lifetracker]Operator: OPEN
09-08 14:32:16.218  7915  7915 I Feature : [Lifetracker]Ranking support: false
09-08 14:32:16.218  7915  7915 I Feature : [Lifetracker]Comfort support: false
09-08 14:32:16.218  7915  7915 I Feature : [Lifetracker]Accessory: true
09-08 14:32:16.218  7915  7915 I Feature : [Lifetracker]Health device: true
09-08 14:32:16.218  7915  7915 I Feature : [Lifetracker]Extra Pedometer: false
09-08 14:32:16.218  7915  7915 I Feature : [Lifetracker]Blood glucose device: false
09-08 14:32:16.219  7915  7915 I Feature : [Lifetracker]Device Number: 3
09-08 14:32:16.219  7915  7915 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
09-08 14:32:16.226  2014  2014 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6640e7 time:148095
,09-08 14:32:16.249  1030  1923 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7951 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 14:32:16.250  1030  1923 I ActivityManager: Killing 7724:com.android.vending/u0a44 (adj 15): empty #17
,09-08 14:32:16.347  1030  1046 W libprocessgroup: failed to open /acct/uid_10044/pid_7724/cgroup.procs: No such file or directory
09-08 14:32:16.364  7951  7951 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:16.364  7951  7951 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-08 14:32:16.364  7951  7951 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 14:32:16.365  7951  7951 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-08 14:32:16.365  7951  7951 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 14:32:16.366  7951  7951 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 14:32:16.369  1030  1046 I ActivityManager: Killing 7255:com.lge.formmanager/u0a26 (adj 15): empty #17
09-08 14:32:16.383  2014  2014 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-08 14:32:16.419  2014  2876 I GBoardtInterface: onReloaded()
,09-08 14:32:16.420  2014  2014 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-08 14:32:16.422  1030  1994 W libprocessgroup: failed to open /acct/uid_10026/pid_7255/cgroup.procs: No such file or directory
09-08 14:32:16.424  2740  2761 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-08 14:32:16.426  2740  2757 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-08 14:32:16.432  1887  1887 D ActionManagerService: notifyUserLog: 1000001
09-08 14:32:16.432  2740  4344 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-08 14:32:16.432  2740  4344 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,09-08 14:32:16.435  1887  1887 D ActionManagerService: notifyUserLog: 1000001
09-08 14:32:16.436  2740  4344 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-08 14:32:16.436  2740  4344 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-08 14:32:16.436  2740  4344 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-08 14:32:16.436  2740  4344 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-08 14:32:16.436  2740  2757 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-08 14:32:16.438  2014  2014 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-08 14:32:16.438  2014  2014 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-08 14:32:16.440  2014  2014 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-08 14:32:16.440  2014  2014 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-08 14:32:16.441  2014  2014 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-08 14:32:16.441  2014  2014 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-08 14:32:16.481  7951  7951 D PackageIntentReceiver: Not supported Hotkey customization function 
,09-08 14:32:16.487  7951  7951 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-08 14:32:16.487  7951  7951 D HideNavigationAppsReceiver: replacing : false
09-08 14:32:16.489  7951  7951 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
09-08 14:32:16.491  7951  7951 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-08 14:32:16.491  7951  7951 D ButtonCombinationReceiver: replacing : false
09-08 14:32:16.519  1030  1886 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7971 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:32:16.520  1030  1886 I ActivityManager: Killing 6523:com.google.android.setupwizard/u0a46 (adj 15): empty #17

```
