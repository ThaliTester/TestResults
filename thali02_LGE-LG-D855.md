#### Test 8291407379492e1_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-29 10:23:48.137   310   310 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
08-29 10:23:48.137   310   310 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
08-29 10:23:48.137   310   310 I rmt_storage: wakelock acquired: 1, error no: 42
08-29 10:23:48.137   310   903 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
08-29 10:23:48.214   310   903 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
08-29 10:23:48.214   310   903 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
08-29 10:23:48.214   310   903 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
08-29 10:23:48.214   310   903 I rmt_storage: 
08-29 10:23:48.217   310   310 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
08-29 10:23:48.218   894   901 E Diag_Lib: [IMS_FATAL]| 3347 | 901 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
--------- beginning of system
08-29 10:23:48.222  1029  1952 I ActivityManager: Killing 5272:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-29 10:23:48.266  1990  1990 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-29 10:23:48.266  1990  1990 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-29 10:23:48.267  1029  2025 W libprocessgroup: failed to open /acct/uid_10037/pid_5272/cgroup.procs: No such file or directory
08-29 10:23:48.271  1990  1990 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-29 10:23:48.273  3731  3731 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-29 10:23:48.278  3731  3731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-29 10:23:48.313  1029  1917 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5897 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 10:23:48.553  5897  5897 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-29 10:23:48.682  5897  5897 D LgDataFeature: LgDataFeature() Constructor: none
08-29 10:23:48.683  5897  5897 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 10:23:48.752  5897  5897 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-29 10:23:48.775  5897  5897 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 10:23:48.777  5897  5897 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 10:23:48.794  5897  5897 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 10:23:48.795  5897  5897 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-29 10:23:48.812  1029  1989 I ActivityManager: Killing 5305:com.lge.clock/u0a10 (adj 15): empty #17
08-29 10:23:48.877  1029  1952 W libprocessgroup: failed to open /acct/uid_10010/pid_5305/cgroup.procs: No such file or directory
08-29 10:23:48.907  3470  3485 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-29 10:23:48.912  4528  5940 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-29 10:23:48.912  3470  3485 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34c33a6a on behalf of 5897
08-29 10:23:48.974  1029  1724 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5941 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 10:23:49.018  5897  5897 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-29 10:23:49.046  5897  5897 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-29 10:23:49.262  5941  5941 D DocsApplication: Installing DEX configuration.
08-29 10:23:49.278  5941  5941 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-29 10:23:49.281  5941  5941 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{18474b9 com.google.android.apps.docs}
08-29 10:23:49.288  5961  5961 D AndroidRuntime: 
08-29 10:23:49.288  5961  5961 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 10:23:49.291  5961  5961 D AndroidRuntime: CheckJNI is OFF
08-29 10:23:49.300  5941  5941 D TAG     : onCreate()
08-29 10:23:49.320  5941  5941 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-29 10:23:49.405  5961  5961 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 10:23:49.408  1029  2026 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 10:23:49.416  1935  2901 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-29 10:23:49.418  1029  2026 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-29 10:23:49.420  1029  2026 D ActivityManager: setTaskToReturnTo : TaskRecord{f5460e8 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 10:23:49.420  1029  2026 D ActivityManager: setTaskToReturnTo : TaskRecord{f5460e8 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 10:23:49.420  1029  2026 D WindowStateEx: AppWindowTokenEx init.. 
08-29 10:23:49.421   351   365 E GBMv2   : DFP En is all cleared set to be enabled
08-29 10:23:49.425  1029  1045 V SIM_STK : Menu title from STK is T-Mobile
08-29 10:23:49.454  1029  2026 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5976 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 10:23:49.456  5961  5961 D AndroidRuntime: Shutting down VM
08-29 10:23:49.491  1935  2901 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-29 10:23:49.491  1935  2901 D SplitWindowPolicy: topRunningActivity=ActivityInfo{28ea44ef co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 10:23:49.493  1935  1951 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-29 10:23:49.493  1935  1951 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c9a5bfc co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 10:23:49.497  4528  5940 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 582 ms] updated apps [took 582 ms] 
08-29 10:23:49.529  5976  5976 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-29 10:23:49.622  5976  5976 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-29 10:23:49.630  5976  5976 I LibraryLoader: Loading: webviewchromium
08-29 10:23:49.633  5976  5976 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2155-2158)
08-29 10:23:49.633  5976  5976 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 10:23:49.649  5976  5976 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {99b837b}
08-29 10:23:49.650  5976  5976 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 10:23:49.651  5976  5976 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 10:23:49.659  5976  5976 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 10:23:49.660  5976  5976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 10:23:49.665  5976  6001 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-29 10:23:49.670   336   336 V AudioPolicyService: registerClient() client 0xb558ac00, uid 10118
08-29 10:23:49.672  5976  5976 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 10:23:49.673  5976  5976 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-29 10:23:49.674  5976  5976 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-29 10:23:49.674  1029  1111 D BluetoothManagerService: Message: 20
08-29 10:23:49.674  1029  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7b06500:true
08-29 10:23:49.686  5976  5976 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 10:23:49.686  5976  5976 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 10:23:49.686  5976  5976 I Adreno-EGL: Build Date: 12/12/14 금
08-29 10:23:49.686  5976  5976 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 10:23:49.686  5976  5976 I Adreno-EGL: Remote Branch: 
08-29 10:23:49.686  5976  5976 I Adreno-EGL: Local Patches: 
08-29 10:23:49.686  5976  5976 I Adreno-EGL: Reconstruct Branch: 
,08-29 10:23:49.750  5976  6011 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-29 10:23:49.750  5976  5976 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-29 10:23:49.763  5976  5976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 10:23:49.767  5976  5976 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 10:23:49.770  5976  5976 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-29 10:23:49.773  5976  5976 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-29 10:23:49.773  5976  5976 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-29 10:23:49.788  5976  5976 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-29 10:23:49.795  5976  5976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 10:23:49.795  5976  5976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 10:23:49.825  5976  6023 D OpenGLRenderer: Render dirty regions requested: true
08-29 10:23:49.825  5976  6023 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 10:23:49.845  5976  6023 D OpenGLRenderer: Enabling debug mode 0
,08-29 10:23:49.856  5976  5976 D Atlas   : Validating map...
,08-29 10:23:49.862  1029  1863 D SplitWindow: check instance of lgWin Window{1f2e393a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 10:23:49.913  5976  6021 D LgDataFeature: LgDataFeature() Constructor: none
08-29 10:23:49.913  5976  6021 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 10:23:50.022  1029  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +534ms (total +601ms)
08-29 10:23:50.023  1029  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{17e42301 u0 com.test.thalitest/.MainActivity t6} time:102548
,08-29 10:23:50.023  5976  5976 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6cbfc86 time:102548
08-29 10:23:50.129  1029  1372 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1a36af06 type 2 when 102642 com.google.android.gms} when 102642
,08-29 10:23:50.156  5976  5976 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-29 10:23:50.156  5976  5976 I chromium: 
,08-29 10:23:50.185  5976  5976 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 10:23:50.240  5976  6021 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-29 10:23:50.240  5976  6021 I chromium: 
,08-29 10:23:50.354  5976  6036 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-29 10:23:50.373  5976  6036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 10:23:50.373  5976  6036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 10:23:50.373  5976  6036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 10:23:50.373  5976  6036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 10:23:50.373  5976  6036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 10:23:50.373  5976  6036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c33a6a added. We now have 1 listener(s)
,08-29 10:23:50.387  1029  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 10:23:50.391  5976  6036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-29 10:23:50.393  5976  6036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:23:50.395  5976  6036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:23:50.396  5976  6036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 10:23:50.405  5976  6036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19b44cd1 added. We now have 1 listener(s)
,08-29 10:23:50.405  5976  6036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:23:50.409  1029  1436 D WifiService: New client listening to asynchronous messages
08-29 10:23:50.412  5976  6036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:23:50.412  5976  6036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 10:23:50.413  5976  6036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 10:23:50.413  5976  6036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 10:23:50.413  5976  6036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 10:23:50.416  5976  6036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:50.419  1029  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:23:50.420  5976  6036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-29 10:23:50.428  5976  6036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-29 10:23:50.429  5976  6036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:50.429  5976  6036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:50.429  5976  6036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:23:50.429  5976  6036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:50.429  5976  6036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:50.429  5976  6036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:50.429  5976  6036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:50.429  5976  6036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:23:50.429  5976  6036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 10:23:50.429  5976  6036 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:23:50.430  5976  6036 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 10:23:50.432  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:50.467  5976  5976 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 10:23:50.501  1810  4667 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-29 10:23:50.544  1810  4667 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-29 10:23:50.615  1810  4667 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-29 10:23:50.718  5941  5941 D LgDataFeature: LgDataFeature() Constructor: none
08-29 10:23:50.718  5941  5941 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 10:23:50.896  1029  1953 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6049 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 10:23:50.909  5941  5941 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-29 10:23:50.921   358   358 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 367us total 24.655ms
,08-29 10:23:50.936   358   358 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 302us total 14.312ms
,08-29 10:23:50.950   358   358 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 12.808ms
,08-29 10:23:50.963  6049  6049 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-29 10:23:50.971  6049  6049 I LockScreenSettings: New app installed broadcast received ..
08-29 10:23:50.974  6049  6049 I LockScreenSettings: Number of installed packages  1
08-29 10:23:51.006  1029  1044 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6073 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-29 10:23:51.008  1029  1044 I ActivityManager: Killing 4920:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-29 10:23:51.076  1029  2025 W libprocessgroup: failed to open /acct/uid_10085/pid_4920/cgroup.procs: No such file or directory
,08-29 10:23:51.110  6073  6073 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 10:23:51.305   351   367 E GBMv2   : DFP En is all cleared set to be enabled
08-29 10:23:51.305   351   367 E GBMv2   : Set value is all cleared set the max
08-29 10:23:51.306   351   367 I GBMv2   : DFP Enabled. Ignore VFP set
,08-29 10:23:51.323  5976  6039 W jxcore-log: Initializing JXcore engine
08-29 10:23:51.323  5976  6039 W jxcore-log: JXcore engine is ready
,08-29 10:23:51.344  6039  6039 W Thread-676: type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[7657]" dev="sockfs" ino=7657 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 10:23:51.344  6039  6039 W Thread-676: type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-29 10:23:51.344  6039  6039 W Thread-676: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[10365]" dev="sockfs" ino=10365 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-29 10:23:51.344  6039  6039 W Thread-676: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-29 10:23:51.344  6039  6039 W Thread-676: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[27373]" dev="sockfs" ino=27373 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-29 10:23:51.380  5976  6039 W jxcore-log: Starting JXcore engine
,08-29 10:23:51.528  5976  6039 W jxcore-log: Platform android
08-29 10:23:51.528  5976  6039 W jxcore-log: 
08-29 10:23:51.528  5976  6039 W jxcore-log: Process ARCH arm
08-29 10:23:51.528  5976  6039 W jxcore-log: 
,08-29 10:23:51.635  1029  1044 V SIM_STK : Menu title from STK is T-Mobile
,08-29 10:23:51.720  1029  2025 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6116 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 10:23:51.729  5976  6039 I jxcore-log: JXcore Cordova bridge is ready!
08-29 10:23:51.729  5976  6039 I jxcore-log: 
08-29 10:23:51.729  5976  6039 W jxcore-log: JXcore engine is started
08-29 10:23:51.733  5976  6036 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 10:23:51.736  5976  5976 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 10:23:51.826  6116  6116 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-29 10:23:51.826  6116  6116 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-29 10:23:51.829  5047  5047 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-29 10:23:51.842  1029  2025 I ActivityManager: Killing 5386:com.google.android.gm/u0a64 (adj 15): empty #17
,08-29 10:23:52.115  1029  1971 W libprocessgroup: failed to open /acct/uid_10064/pid_5386/cgroup.procs: No such file or directory
,08-29 10:23:53.428  2778  2778 I MusicWidget: mDelayedStopHandler : unbind
,08-29 10:23:53.432  2165  2165 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-29 10:23:53.432  2165  2165 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-29 10:23:53.432  2165  2165 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-29 10:23:53.434  2165  2165 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-29 10:23:53.434  2165  2165 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
,08-29 10:23:53.434  2165  2165 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-29 10:23:53.436  2165  2165 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-29 10:23:53.436  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,08-29 10:23:53.574  1029  1917 I art     : Explicit concurrent mark sweep GC freed 21960(1045KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.615ms total 130.223ms
,08-29 10:23:53.574  1029  1917 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@399ca4c8com.lge.music.MediaPlaybackService$5@3c974961
08-29 10:23:53.575  2165  2165 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-29 10:23:53.583  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 10:23:53.588  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 10:23:53.588  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 10:23:53.589  2165  2165 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@ed4dc57
08-29 10:23:53.589  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 10:23:53.590  2165  2165 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-29 10:23:53.590  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 10:23:53.590  2165  2165 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-29 10:23:53.590  2165  2165 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-29 10:23:53.591  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 10:23:53.591  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 10:23:53.592  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 10:23:53.592  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 10:23:53.593  2165  2165 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 10:23:53.593  2165  2165 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,08-29 10:23:53.597  2165  2165 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-29 10:23:53.597  2165  2165 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-29 10:23:53.597  2165  2165 V MediaPlayer[Native]: reset
08-29 10:23:53.602  2165  2165 V MediaPlayer[Native]: setListener
08-29 10:23:53.602  2165  2165 V MediaPlayer[Native]: disconnect
08-29 10:23:53.602  2165  2165 V MediaPlayer[Native]: destructor
08-29 10:23:53.603   336  1391 V AudioFlinger: releasing 16 from 2165 for -1
08-29 10:23:53.603   336  1391 V AudioFlinger:  decremented refcount to 0
08-29 10:23:53.603   336  1391 V AudioFlinger: purging stale effects
08-29 10:23:53.603  2165  2165 V MediaPlayer[Native]: disconnect
08-29 10:23:53.604  2165  2165 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-29 10:23:53.605  2165  2165 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-29 10:23:53.605  2165  2165 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-29 10:23:53.606  2165  2165 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-29 10:23:53.606  2165  2165 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-29 10:23:53.607  2165  2165 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-29 10:23:53.607  2165  2165 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 114031750
08-29 10:23:53.607  2165  2165 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 114031750
,08-29 10:23:53.611  2165  2165 I SmartShareClient: [SmartShareManagerClient] terminate service: 2165/MediaPlaybackService/544121717
08-29 10:23:53.615  2165  2165 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-29 10:23:53.615  2165  2165 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@216f8947
08-29 10:23:53.616  2165  2165 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-29 10:23:53.617  2165  2165 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-29 10:23:53.617  2165  2165 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-29 10:23:53.618  2165  2165 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-29 10:23:53.619  1029  1952 I ActivityManager: Killing 5443:com.google.android.talk/u0a72 (adj 15): empty #17
,08-29 10:23:53.625  2165  2165 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
08-29 10:23:53.717  1029  1898 W libprocessgroup: failed to open /acct/uid_10072/pid_5443/cgroup.procs: No such file or directory
,08-29 10:23:54.804  5941  5941 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-29 10:23:54.809  1029  1863 I ActivityManager: Killing 5201:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-29 10:23:54.827  5175  5175 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-29 10:23:54.827  5175  5175 W System.err: android.os.DeadObjectException
08-29 10:23:54.827  5175  5175 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 10:23:54.827  5175  5175 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 10:23:54.827  5175  5175 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 10:23:54.827  5175  5175 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 10:23:54.827  5175  5175 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 10:23:54.827  5175  5175 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 10:23:54.827  5175  5175 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 10:23:54.827  5175  5175 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 10:23:54.827  5175  5175 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 10:23:54.827  5175  5175 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 10:23:54.828  5175  5175 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:54.828  5175  5175 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:54.828  5175  5175 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 10:23:54.828  5175  5175 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 10:23:54.828  5175  5175 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 10:23:54.828  5175  5175 W System.err: android.os.DeadObjectException
08-29 10:23:54.828  5175  5175 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 10:23:54.828  5175  5175 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 10:23:54.828  5175  5175 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,08-29 10:23:54.828  5175  5175 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-29 10:23:54.828  5175  5175 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-29 10:23:54.828  5175  5175 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317),
08-29 10:23:54.828  5175  5175 W System.err: ,	at android.os.Handler.handleCallback(Handler.java:739)
,08-29 10:23:54.828  5175  5175 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-29 10:23:54.828  5175  5175 W System.err: 	at android.os.Looper.loop(Looper.java:135),
08-29 10:23:54.828  5175  5175 W System.err: ,	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 10:23:54.828  5175  5175 W System.err: 	,at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:54.828  5175  5175 W System.err: ,	,at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:54.828  5175  5175 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 10:23:54.828  5175  5175 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-29 10:23:54.828  5175  5175 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 10:23:54.828  5175  5175 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-29 10:23:55.037  1029  1952 W libprocessgroup: failed to open /acct/uid_1000/pid_5201/cgroup.procs: No such file or directory
08-29 10:23:55.037  1029  1952 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 10:23:55.058  5175  5175 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 10:23:55.058  5175  5175 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-29 10:23:55.097  1029  1044 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6142 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 10:23:55.097  5175  5175 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 10:23:55.186  6142  6142 D UEI.SmartControl: Quickset Services start...
08-29 10:23:55.188  6142  6142 I UEI.SmartControl: Manufacture = LGE
08-29 10:23:55.188  6142  6142 D UEI.SmartControl: Id = LGNevo
08-29 10:23:55.189  6142  6142 D UEI.SmartControl: File observer start...
08-29 10:23:55.190  6142  6142 E UEI.SmartControl: IR Port is disabled: false
08-29 10:23:55.190  6142  6142 D UEI.SmartControl: Starting file observer...
08-29 10:23:55.190  6142  6142 D UEI.SmartControl: Extracting JNI libs...
08-29 10:23:55.190  6142  6142 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-29 10:23:55.278  6142  6142 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 10:23:55.278  6142  6142 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 10:23:55.278  6142  6142 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 10:23:55.311  6142  6142 I UEI.SmartControl: --- Selecting new region: 6
08-29 10:23:55.312  6142  6142 I UEI.SmartControl: Model = LG-D855
08-29 10:23:55.314  6142  6142 D UEI.SmartControl: QS Service created
08-29 10:23:55.328  6142  6142 I UEI.SmartControl: Service initServices...
08-29 10:23:55.332  6142  6142 D UEI.SmartControl: QS start get config
,08-29 10:23:55.382  6142  6142 D UEI.SmartControl: Loading JNI Libs...
,08-29 10:23:55.600  6142  6142 I UEI.SmartControl: Supports setup maps: true
08-29 10:23:55.603  6142  6142 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 10:23:55.603  6142  6142 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 10:23:55.603  6142  6142 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-29 10:23:55.605  6142  6142 I UEI.SmartControl: ### init IR Blaster...
08-29 10:23:55.609  6142  6142 D serial_port: Configuring serial port
,08-29 10:23:55.612  6142  6142 E UEI.SmartControl: UEIBLaster setting for 616
08-29 10:23:55.612  6142  6142 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 10:23:55.612  6142  6142 I UEI.SmartControl: configuring settings for MAXQ616
08-29 10:23:55.612  6142  6142 I UEI.SmartControl: Get version...
08-29 10:23:55.628  6142  6160 D UEI.SmartControl: serial port data available: 21
,08-29 10:23:55.655  6142  6142 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 10:23:55.655  6142  6142 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 10:23:55.655  6142  6142 I UEI.SmartControl: QS saving settings...
08-29 10:23:55.655  6142  6142 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 10:23:55.669  6142  6160 D UEI.SmartControl: serial port data available: 4
,08-29 10:23:55.700  6142  6142 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 10:23:55.704  6142  6163 I UEI.SmartControl: Device manager: loading config....
08-29 10:23:55.705  6142  6142 E UEI.SmartControl: Services init done
08-29 10:23:55.705  6142  6163 D UEI.SmartControl: ----------- loading internal config...
08-29 10:23:55.713  6142  6142 D UEI.SmartControl: QS Service init finished
,08-29 10:23:55.717  6142  6142 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 10:23:55.717  6142  6142 D UEI.SmartControl: QS Service version code: 201091
08-29 10:23:55.718  6142  6142 D UEI.SmartControl: Service requested: Control
08-29 10:23:55.720  1029  1916 I ActivityManager: Killing 5175:com.lge.qremote/u0a112 (adj 15): empty #17
08-29 10:23:55.720  6142  6163 E UEI.SmartControl: Loading SETTINGS...
08-29 10:23:55.727  6142  6163 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-29 10:23:55.754  6142  6162 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 10:23:55.755  6142  6162 D UEI.SmartControl: -----service ready thread exits
,08-29 10:23:55.815  1029  1953 W libprocessgroup: failed to open /acct/uid_10112/pid_5175/cgroup.procs: No such file or directory
,08-29 10:23:55.825  6142  6142 D UEI.SmartControl: Internal service binding...
08-29 10:23:55.845  5941  6045 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-29 10:23:56.621  1029  1916 I ActivityManager: Killing 5090:com.android.calendar/u0a13 (adj 15): empty #17
,08-29 10:23:56.698  1029  1045 W libprocessgroup: failed to open /acct/uid_10013/pid_5090/cgroup.procs: No such file or directory
,08-29 10:24:00.001  1029  1372 D PowerManagerServiceEx: acquireWakeLockInternal: lock=413131145, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,08-29 10:24:00.041  2593  2593 D [Concierge]Service: onStartCommand(). Type : 9
,08-29 10:24:00.044  1595  1595 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-29 10:24:00.044  1595  1595 I KeyguardUpdateMonitor: called onTimeUpdated()
08-29 10:24:00.045  1595  1595 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-29 10:24:00.045  1595  1595 I [SystemUI]Clock: called onTimeUpdated()
08-29 10:24:00.046  1595  1595 I LgeClockWidgetControlView: called onTimeUpdated()
08-29 10:24:00.046  1595  1595 I [SystemUI]DateView: called onTimeUpdated()
08-29 10:24:00.046  1595  1595 I [SystemUI]DateView: called onTimeUpdated()
08-29 10:24:00.048  1595  1595 D KeyguardUpdateMonitor: handleTimeUpdate
08-29 10:24:00.085  4419  6167 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-29 10:24:00.089  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=413131145 [*alarm*], flags=0x0
,08-29 10:24:00.705  6142  6164 D UEI.SmartControl: Internal timer expired: 1
,08-29 10:24:00.705  6142  6164 D UEI.SmartControl: unbind internal service
,08-29 10:24:00.713  6142  6161 D serial_port: close(fd = 25)
08-29 10:24:00.722  6142  6142 D UEI.SmartControl: Service.onUnbind: IControl
08-29 10:24:00.723  6142  6142 D UEI.SmartControl: Service.onDestroy
08-29 10:24:00.723  6142  6142 D UEI.SmartControl: Lock is in USE false
08-29 10:24:00.723  6142  6142 D UEI.SmartControl: unbind internal service
08-29 10:24:00.724  6142  6142 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@ed4dc57
,08-29 10:24:00.728  6142  6142 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-29 10:24:00.728  6142  6142 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-29 10:24:00.728  6142  6142 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-29 10:24:00.728  6142  6142 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-29 10:24:00.729  6142  6142 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-29 10:24:00.729  6142  6142 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-29 10:24:00.729  6142  6142 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-29 10:24:00.729  6142  6142 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-29 10:24:00.729  6142  6142 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:00.729  6142  6142 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 10:24:00.729  6142  6142 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 10:24:00.729  6142  6142 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:00.729  6142  6142 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:24:00.729  6142  6142 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 10:24:00.729  6142  6142 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 10:24:00.729  6142  6142 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@ed4dc57
08-29 10:24:00.733  6142  6161 I UEI.SmartControl: Serial port is closed.
08-29 10:24:00.734  6142  6142 I UEI.SmartControl: Serial port is closed.
08-29 10:24:00.734  6142  6142 I UEI.SmartControl: Serial port is closed.
08-29 10:24:00.734  6142  6142 D UEI.SmartControl: Blaster closed
08-29 10:24:00.735  6142  6142 D UEI.SmartControl: Shut down QS...
08-29 10:24:00.735  6142  6142 D UEI.SmartControl: Stopping QS lib
08-29 10:24:00.735  6142  6142 D UEI.SmartControl: QS lib stop result = true
08-29 10:24:00.735  6142  6142 D UEI.SmartControl: Stopped QS lib
08-29 10:24:00.735  6142  6142 D UEI.SmartControl: Stopped file observer...
,08-29 10:24:00.736  6142  6142 D UEI.SmartControl: QS shutdown complete,
08-29 10:24:01.487  1029  1095 I ActivityManager: Waited long enough for: ServiceRecord{f3269c2 u0 com.google.android.gms/.wearable.service.WearableService},
,08-29 10:24:01.759  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 10:24:01.759  5976  6039 I jxcore-log: 
,08-29 10:24:01.762  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 10:24:01.762  5976  6039 I jxcore-log: 
,08-29 10:24:01.765  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:01.765  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:01.765  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:01.765  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:01.765  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:01.765  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:01.765  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:01.765  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:01.767  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:01.770  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 10:24:01.770  5976  6039 I jxcore-log: 
08-29 10:24:01.771  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 10:24:01.771  5976  6039 I jxcore-log: 
08-29 10:24:02.270  5976  6039 D executeNativeTests: Running unit tests
,08-29 10:24:02.352  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:02.352  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc added. We now have 2 listener(s)
,08-29 10:24:02.353  1029  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:02.355  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:24:02.355  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:02.355  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:02.355  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:02.355  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 added. We now have 2 listener(s)
08-29 10:24:02.355  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:02.356  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:24:02.357  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:02.359  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:02.359  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:02.359  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:02.359  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:02.359  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:02.359  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:02.359  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:02.359  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:02.361  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:02.361  5976  6039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:24:02.363  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:02.364  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:24:02.364  5976  6039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:24:02.364  5976  6039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:24:02.366  5976  6039 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 10:24:02.366  5976  6039 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 10:24:02.366  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:24:02.366  5976  6039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:24:02.366  5976  6039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:24:02.367  5976  6039 I io.jxcore.node.ConnectionHelpe,r: stop: Stopping all activities and killing connections
,08-29 10:24:02.367  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.368  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.368  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.368  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.368  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:02.368  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:02.368  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc removed from the list
08-29 10:24:02.368  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.368  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 removed from the list
08-29 10:24:02.368  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.368  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.370  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.370  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.371  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.371  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.371  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.371  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.373  5976  6039 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 10:24:02.374  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.374  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.374  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.374  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.374  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.374  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.374  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.374  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.374  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not i,n the list
08-29 10:24:02.374  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.374  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.374  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.374  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.374  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.375  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.375  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.375  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.375  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 10:24:02.380  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910],
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410],
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 10:24:02.381  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
08-29 10:24:02.381  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.381  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.381  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.382  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:24:02.382  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 10:24:02.382  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.382  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.382  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.382  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
,08-29 10:24:02.382  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 10:24:02.382  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.382  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.382  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:02.382  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 10:24:02.383  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.383  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.383  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.383  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
,08-29 10:24:02.383  5976  6039 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 10:24:02.387  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:02.388  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:02.388  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:02.388  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:02.388  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:02.388  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-29 10:24:02.388  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:02.388  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:02.388  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:02.389  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:02.389  5976  6039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:24:02.390  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:02.390  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:02.390  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:24:02.390  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:24:02.390  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:02.390  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:24:02.393  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:24:02.393  1029  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:02.396  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:24:02.400  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:24:02.402  5976  6039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 10:24:02.403  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:24:02.403  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:02.404  5976  6039 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 10:24:02.404  5976  6039 I io.jxcore.node.ConnectionHelper: start: OK
08-29 10:24:02.406  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.406  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.406  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.407  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.407  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.407  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:02.407  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.407  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.407  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.407  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.407  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.407  5976  6039 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 10:24:02.408  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:02.410  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:02.410  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:02.410  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:02.410  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:02.410  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:02.410  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:02.410  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:02.410  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:02.411  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:02.411  5976  6039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:24:02.412  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:02.412  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:02.412  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:24:02.412  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:24:02.412  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:02.412  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:24:02.415  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:24:02.415  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:02.416  5976  6039 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 10:24:02.416  5976  6039 I io.jxcore.node.ConnectionHelper: start: OK
08-29 10:24:02.417  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.417  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.417  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.417  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.417  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.417  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:02.418  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.418  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.418  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.418  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.418  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.418  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.418  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.418  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.419  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.420  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:02.420  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.420  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.420  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.420  5976  6039 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 10:24:02.421  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:02.423  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:02.423  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:02.423  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:02.423  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:02.423  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:02.423  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:02.423  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:02.423  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:02.425  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:02.425  5976  6039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:24:02.425  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:02.426  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:02.426  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:24:02.426  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:24:02.426  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:02.426  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:24:02.428  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:24:02.428  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:02.429  5976  6039 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 10:24:02.429  5976  6039 I io.jxcore.node.ConnectionHelper: start: OK
08-29 10:24:02.429  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.429  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.429  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.430  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.430  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.430  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.430  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.430  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.430  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:02.430  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.430  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.430  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.430  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.430  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.430  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.430  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.431  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.431  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.431  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:02.431  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.431  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.431  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.431  5976  6039 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 10:24:02.432  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.432  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.432  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.432  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.432  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.432  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.432  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.432  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.432  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.432  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.432  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.432  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.432  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.432  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.433  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.433  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.434  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:02.434  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.434  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.434  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.435  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 10:24:02.435  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.435  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.435  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.435  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.435  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.435  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.435  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.435  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.435  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.435  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.435  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.435  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.435  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.435  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.436  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.436  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.436  5976  6039 D BluetoothLeScanner: could not find callback wrapper,
08-29 10:24:02.436  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.436  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.436  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.437  5976  6039 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 10:24:02.437  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.437  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.437  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.437  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.437  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.437  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.437  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.437  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.437  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.437  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.437  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.437  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.437  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.437  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.438  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.438  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.438  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:02.438  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.438  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.439  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.439  5976  6039 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 10:24:02.439  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.439  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.439  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.439  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.439  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.439  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.440  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.440  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.440  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.440  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.440  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.440  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.440  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.440  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.440  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.440  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.441  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:02.441  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.441  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.441  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.441  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:24:02.442  5976  6039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:24:02.442  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:24:02.442  5976  6039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:24:02.442  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:24:02.442  5976  6039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:24:02.442  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.442  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.442  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.443  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.443  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.443  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.443  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.443  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.443  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.443  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.443  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.443  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.443  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.443  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.444  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.444  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.445  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:02.445  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.445  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.445  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.446  5976  6039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:24:02.446  5976  6039 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 10:24:02.446  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 10:24:02.447  5976  6039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:24:02.448  5976  6039 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 10:24:02.448  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 10:24:02.448  5976  6039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 10:24:02.448  5976  6039 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:24:02.449  5976  6039 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 10:24:02.449  5976  6039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:24:02.449  5976  6039 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:24:02.449  5976  6039 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 10:24:02.449  5976  6039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:24:02.449  5976  6039 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:24:02.449  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 10:24:02.451  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 10:24:02.451  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 10:24:02.451  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 10:24:02.452  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 10:24:02.452  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 10:24:02.452  5976  6039 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 10:24:02.452  5976  6039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:24:02.452  5976  6039 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 10:24:02.452  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.452  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.452  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.453  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.453  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.453  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:02.453  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 10:24:02.453  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
,08-29 10:24:02.453  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.453  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.453  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:24:02.453  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.453  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.453  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.453  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.454  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.454  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.455  5976  6039 D BluetoothLeScanner: could not find callback wrapper
,08-29 10:24:02.455  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.455  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.455  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.455  5976  6039 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 10:24:02.455  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:24:02.455  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.455  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.456  5976  6191 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 740)
08-29 10:24:02.463  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.463  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.464  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.464  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.464  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:02.464  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.464  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.464  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.464  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.464  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.464  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.465  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.465  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.465  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:02.465  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.465  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.465  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.473  5976  6192 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 740
08-29 10:24:02.473  5976  6192 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 740)
08-29 10:24:02.473  5976  6192 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 740)
08-29 10:24:02.474  5976  6039 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-29 10:24:02.476  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.476  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.476  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.477  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.477  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.477  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.478  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.478  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.478  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.478  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:24:02.478  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.478  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.478  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.478  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.482  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.482  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.483  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:02.483  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 10:24:02.483  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.484  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.485  5976  6039 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 10:24:02.485  5976  6039 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 10:24:02.486  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:24:02.486  5976  6039 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 10:24:02.486  5976  6039 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 10:24:02.486  5976  6039 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 10:24:02.486  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 10:24:02.486  5976  6039 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 10:24:02.486  5976  6039 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 10:24:02.486  5976  6039 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 10:24:02.486  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:24:02.486  5976  6039 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 10:24:02.486  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:24:02.486  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:24:02.486  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.487  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.487  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.487  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.487  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.487  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.487  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.487  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.487  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.487  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:02.487  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.487  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.489  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.489  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.489  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:02.489  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.489  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.489  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.490  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.490  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.490  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.490  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.490  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.490  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.490  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:24:02.490  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.490  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.491  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.491  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.491  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.491  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.491  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.491  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.491  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.491  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.491  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.492  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.492  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.492  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.492  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.492  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:02.492  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.492  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.492  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.492  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.492  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.492  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.493  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.493  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.494  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:02.494  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.494  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.494  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.496  5976  6039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 10:24:02.496  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:02.497  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 10:24:02.498  5976  6039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 10:24:02.498  5976  6039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 10:24:02.499  5976  5976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 10:24:02.499  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 10:24:02.499  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 10:24:02.501  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.501  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-29 10:24:02.502  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 10:24:02.502  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 10:24:02.502  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.502  5976  6039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 10:24:02.503  5976  5976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 10:24:02.503  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.503  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.503  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:24:02.503  5976  6039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:24:02.503  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:24:02.504  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:24:02.514  1029  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 10:24:02.515  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:02.515  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:02.515  5976  6039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:24:02.515  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.515  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.517  5976  6039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:24:02.517  5976  6205 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:02.517  3822  3839 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-29 10:24:02.517  5976  5976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:24:02.518  5976  5976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:24:02.518  5976  5976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:24:02.518  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.518  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.518  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.518  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.518  5976  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 10:24:02.518  5976  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 10:24:02.518  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.518  5976  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 10:24:02.518  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.518  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.518  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.518  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.518  5976  5976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 10:24:02.518  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.518  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.518  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.519  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.,BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.519  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.519  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.519  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.519  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.519  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.519  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.520  5976  6039 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 10:24:02.521  5976  6039 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 10:24:02.521  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:24:02.522  5976  6039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:24:02.522  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.523  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.523  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.523  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.523  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.523  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.523  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.523  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.523  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.523  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.523  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.523  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.523  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.523  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.524  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.524  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.524  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.524  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSe,ttings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.526  1029  1724 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:02.529  1029  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:02.530  1029  1863 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:02.530  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.530  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.530  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.530  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.530  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.531  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.531  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.531  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.531  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.531  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.531  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.531  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.531  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.531  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.532  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.532  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.532  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.532  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.533  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:02.533  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:02.533  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:02.533  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:02.533  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.533  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.533  5976  6039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2204cadc not in the list
08-29 10:24:02.533  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.533  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.533  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:02.533  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.533  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.533  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:02.533  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:02.534  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:02.534  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:02.534  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:02.534  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340197e5 not in the list
08-29 10:24:02.536  5976  6039 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 10:24:02.536  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:24:02.536  5976  6039 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 10:24:02.536  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:24:02.536  5976  6039 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 10:24:02.536  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:24:02.538  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 10:24:02.538  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 10:24:02.539  5976  6039 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 10:24:02.540  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 10:24:02.540  5976  6039 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 10:24:02.540  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 10:24:02.540  5976  6039 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 10:24:02.540  5976  6039 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 10:24:02.541  5976  6039 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 10:24:02.541  5976  6039 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 10:24:02.542  5976  6039 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 10:24:02.543  5976  6039 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 10:24:02.543  5976  6039 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 10:24:02.543  5976  6039 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 10:24:02.544  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:02.545  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2bf7cf12 added. We now have 2 listener(s)
08-29 10:24:02.545  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:02.546  5976  6039 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 10:24:02.547  1029  1971 D WifiServiceImplEx: setWifiEnabled: true pid=5976, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 10:24:02.547  1029  1971 D WifiService: setWifiEnabled: true pid=5976, uid=10118
08-29 10:24:02.547  1029  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 10:24:02.549  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:02.549  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3386d6e3 added. We now have 3 listener(s)
08-29 10:24:02.549  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:02.552  5976  6191 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-29 10:24:02.552  5976  6191 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 740)
,08-29 10:24:02.554  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:02.554  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c74d8e0 added. We now have 4 listener(s)
08-29 10:24:02.554  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:02.556  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:02.556  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1514c799 added. We now have 5 listener(s)
08-29 10:24:02.556  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:02.558  1029  1989 D WifiServiceImplEx: setWifiEnabled: false pid=5976, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 10:24:02.558  1029  1989 D WifiService: setWifiEnabled: false pid=5976, uid=10118
08-29 10:24:02.558  1029  1989 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 10:24:02.568  1029  1384 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-29 10:24:02.568  1029  1384 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 10:24:02.568  1029  1916 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:02.569  1029  1916 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3dcdfbbb mBinding = false
08-29 10:24:02.569  1029  1384 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 10:24:02.569  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 10:24:02.570  1029  1383 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:02.570  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:02.571  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 10:24:02.571  1029  1029 D RttService: SCAN_AVAILABLE : 1
08-29 10:24:02.571  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 10:24:02.571  1029  1549 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:02.571  1029  1550 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:02.572  1029  1383 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@12480891
08-29 10:24:02.572  1029  1383 D LGWifiP2pService: P2pDisablingState
08-29 10:24:02.572  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 10:24:02.572  1029  1383 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:02.572  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-29 10:24:02.572  1029  1383 D LGWifiP2pService: p2p socket connection lost
08-29 10:24:02.572  1029  1383 D LGWifiP2pService: P2pDisabledState
08-29 10:24:02.573  1029  1384 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 10:24:02.573  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 10:24:02.573  1935  1935 D WfdsService: WifiP2pState is changed : false
08-29 10:24:02.573  1935  2295 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 10:24:02.574  1935  2295 D WfdsService: Set the WFDS Monitor: false
08-29 10:24:02.574   330   887 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:24:02.575  1935  2295 D WfdsMonitor: WFDS Monitor is stopped
08-29 10:24:02.575  1935  2295 D WfdsService: STATE : WfdsDisabledState - enter
08-29 10:24:02.575  1935  2297 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 10:24:02.576  1935  2825 D CtrlSupplicant: Received on exit socket, terminate
08-29 10:24:02.576  1935  2825 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 10:24:02.576  1935  2825 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 10:24:02.576  1935  2825 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 10:24:02.576  1935  2295 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 10:24:02.577  1029  1111 D BluetoothManagerService: Message: 2
08-29 10:24:02.578  1029  1384 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 10:24:02.578  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 10:24:02.578  1029  1111 D BluetoothManagerService: Sending off request.
08-29 10:24:02.578  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 10:24:02.578  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-29 10:24:02.579  3822  6206 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 10:24:02.579  3822  3901 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 10:24:02.579  3822  3901 D BluetoothAdapterProperties: Setting state to 13
08-29 10:24:02.579  3822  3901 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 10:24:02.580  3822  3901 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 10:24:02.580  3822  3901 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 10:24:02.581  1029  1111 D BluetoothManagerService: Message: 60
08-29 10:24:02.581  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 10:24:02.581  1029  1111 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 10:24:02.582  1029  1384 D WifiNative-p2p0: TERMINATE: returned true
08-29 10:24:02.582  1029  1384 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 10:24:02.582  1029  1384 E WifiStateMachine: useWiFiOffloading() : false
08-29 10:24:02.582  1029  1384 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 10:24:02.582  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 10:24:02.582  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:02.584  1029  1029 D WifiHS20: hidePasspointNotification off =false
08-29 10:24:02.584  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:02.584  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:02.585  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 10:24:02.585  1029  1029 D WifiHS20: hidePasspointNotification off =false
08-29 10:24:02.585  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:02.589  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:02.589  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:02.589  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 10:24:02.592  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:02.593  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:02.594  3822  3822 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:02.594  3822  3822 D BluetoothMapService: STATE_TURNING_OFF
08-29 10:24:02.595  3822  3822 V BtOppService: Receiver DISABLED_ACTION 
08-29 10:24:02.595  3822  3822 V BluetoothMapService: Handler(): got msg=4
08-29 10:24:02.595  3822  3822 D BluetoothMapService: MAP Service closeService in
08-29 10:24:02.595  3822  3822 D BluetoothMapMasInstance: MAP Service shutdown
08-29 10:24:02.596  3822  4138 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 10:24:02.596  3822  4138 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:24:02.596  3822  4138 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 10:24:02.596  3822  4138 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 10:24:02.596  3822  4138 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 10:24:02.596  3822  4138 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 10:24:02.596  3822  4138 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 10:24:02.596  3822  4138 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 10:24:02.596  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:02.596  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:02.596  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:02.596  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:02.596  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:02.596  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:02.596  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:02.596  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:02.596  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:02.597  3822  3822 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 10:24:02.597  3822  3822 V BluetoothMapService: MAP Service closeService out
08-29 10:24:02.597  3822  3822 I BtOppRfcommListener: stopping Accept Thread
08-29 10:24:02.597  3822  3822 V BtOppRfcommListener: close mBtServerSocket
08-29 10:24:02.597  3822  3822 V BtOppRfcommListener: waiting for thread to terminate
08-29 10:24:02.597  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:02.597  5976  5976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:02.597  3822  4162 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 10:24:02.599  3822  4162 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 10:24:02.599  3822  3822 V BtOppRfcommListener: done waiting for thread to terminate
08-29 10:24:02.618  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 10:24:02.618  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:02.621  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:02.623  1029  1095 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6209 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 10:24:02.624  3822  3905 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:24:02.625  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:02.625  3822  3901 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 10:24:02.625  3822  4142 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:24:02.625  3822  4186 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:24:02.625  3822  3901 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 10:24:02.626  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 10:24:02.626  3822  4009 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 10:24:02.627  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 10:24:02.627  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 10:24:02.627  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 10:24:02.627  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 10:24:02.628  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 10:24:02.628  3822  4009 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:24:02.628  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 10:24:02.628  3822  4009 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:24:02.628  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 10:24:02.628  3822  4009 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:24:02.628  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 10:24:02.628  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 10:24:02.628  3822  4009 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 10:24:02.628  3822  4182 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:24:02.629  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:24:02.629  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:02.629  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:02.629  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:02.629  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:02.629  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:02.629  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:02.629  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:02.629  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:02.629  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:02.629  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 10:24:02.630  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:02.630  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:02.630  5976  6039 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:24:02.631  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:02.632  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:02.633  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:02.656  2631  2631 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 10:24:02.656  2631  2631 I wpa_supplicant: monitor socket send errors count : 1
08-29 10:24:02.656  2631  2631 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1935-2\x00 that cannot receive messages
08-29 10:24:02.657  1029  2815 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 10:24:02.657  1029  2815 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-29 10:24:02.666  1029  2025 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6226 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 10:24:02.667  3822  3822 V BtOppService: onDestroy
08-29 10:24:02.667  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 10:24:02.668  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:02.670  3822  3822 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 10:24:02.671  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-29 10:24:02.671  1029  1029 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 10:24:02.683  6209  6209 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 10:24:02.683  6209  6209 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-29 10:24:02.684  6209  6209 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 10:24:02.684  6209  6209 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-29 10:24:02.685  6209  6209 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 10:24:02.685  6209  6209 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 10:24:02.688  2631  2631 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 10:24:02.689  1029  2815 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 10:24:02.689  1029  2815 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 10:24:02.689  1029  2815 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 10:24:02.689  2631  2631 W wpa_supplicant: USIM:  scard_deinit function
08-29 10:24:02.689  1029  2815 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 10:24:02.689  1029  2815 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 10:24:02.689  1029  2815 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 10:24:02.690  1029  1111 D Tethering: InitialState.processMessage what=4
08-29 10:24:02.690  1029  1384 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=115203
08-29 10:24:02.690  1029  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 10:24:02.690  1029  1384 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=115204
08-29 10:24:02.691  1029  1384 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=115204  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 10:24:02.691  1029  1384 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=115204  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 10:24:02.692  1029  1384 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:02.692  1029  1384 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:02.692   330  6243 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 10:24:02.692  1029  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-29 10:24:02.726  6226  6226 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 10:24:02.732  6226  6226 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-29 10:24:02.733  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 10:24:02.735  1029  1045 I ActivityManager: Killing 4829:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-29 10:24:02.767  1029  1916 W libprocessgroup: failed to open /acct/uid_10014/pid_4829/cgroup.procs: No such file or directory
,08-29 10:24:02.777  2631  2631 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 10:24:02.777  1029  2815 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 10:24:02.777  1029  2815 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 10:24:02.777  1029  2815 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 10:24:02.778  1029  1384 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
08-29 10:24:02.820  6209  6209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 10:24:02.826  3822  3822 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 10:24:02.826  3822  3822 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:02.826  3822  3822 V BluetoothPbapReceiver: ***********state = 13
08-29 10:24:02.829  3822  3822 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 10:24:02.831  3822  3822 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:02.831  3822  3822 V BluetoothPbapService: state: 13
08-29 10:24:02.831  3822  3822 V BluetoothPbapService: Pbap Service closeService in
08-29 10:24:02.833  3822  3822 V BluetoothPbapService: successfully stopped pbap service
08-29 10:24:02.833  3822  3822 V BluetoothPbapService: Pbap Service closeService out
08-29 10:24:02.833  2265  2265 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:24:02.833  3822  3822 V BluetoothPbapService: Pbap Service onDestroy
08-29 10:24:02.833  3822  3822 V BluetoothPbapService: Pbap Service closeService in
08-29 10:24:02.833  3822  3822 V BluetoothPbapService: Pbap Service closeService out
08-29 10:24:02.833  3822  3822 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-29 10:24:02.851  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:02.890  6209  6209 D LgDataFeature: LgDataFeature() Constructor: none
08-29 10:24:02.890  6209  6209 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 10:24:02.897  1029  1568 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6248 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-29 10:24:02.901  1029  1384 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 10:24:02.901  1029  1384 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 10:24:02.901  1029  1384 E WifiStateMachine: useWiFiOffloading() : false
08-29 10:24:02.901  1029  1384 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 10:24:02.904  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:02.904  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:02.905  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-29 10:24:02.907  1935  1935 D WfdsService: Supplicant Connection state is changed : false
08-29 10:24:02.907  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 10:24:02.907  1029  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 10:24:02.907  1029  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 10:24:02.907  1935  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 10:24:02.907  1935  2295 D WfdsService: Set the WFDS Monitor: false
08-29 10:24:02.908  1935  2295 D WfdsMonitor: WFDS Monitor is stopped
,08-29 10:24:02.910  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:02.913  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:02.918  1029  1111 D BluetoothManagerService: Message: 20
08-29 10:24:02.918  1029  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15b9826d:true
08-29 10:24:02.921  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:02.929  1029  1111 D BluetoothManagerService: Message: 30
08-29 10:24:02.932  1029  1111 D BluetoothManagerService: Message: 30
08-29 10:24:02.935  6209  6209 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 10:24:02.936  6209  6209 D BluetoothMap: Create BluetoothMap proxy object
08-29 10:24:02.937  1029  1111 D BluetoothManagerService: Message: 30
08-29 10:24:02.941  1029  1111 D BluetoothManagerService: Message: 30
08-29 10:24:02.943  6209  6209 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 10:24:02.944  6209  6209 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-29 10:24:02.959  6209  6209 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-29 10:24:02.961  6209  6209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-29 10:24:02.969  6209  6209 D DockEventReceiver: finishStartingService: stopping service
08-29 10:24:02.976  6209  6209 D BluetoothInputDevice: Proxy object connected
,08-29 10:24:02.977  6209  6209 D HidProfile: Bluetooth service connected
08-29 10:24:02.977  6209  6209 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:24:02.978  6209  6209 D PanProfile: Bluetooth service connected
08-29 10:24:02.979  6209  6209 D BluetoothMap: Proxy object connected
08-29 10:24:02.980  6209  6209 D MapProfile: Bluetooth service connected
08-29 10:24:02.980  6209  6209 D BluetoothMap: getConnectedDevices()
08-29 10:24:02.980  6209  6209 D BluetoothMap: Bluetooth is Not enabled
08-29 10:24:02.981  6209  6209 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 10:24:03.018  5976  5976 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:24:03.040  1029  1724 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6272 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-29 10:24:03.043  1029  1724 I ActivityManager: Killing 5743:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-29 10:24:03.119  1029  2025 W libprocessgroup: failed to open /acct/uid_10008/pid_5743/cgroup.procs: No such file or directory
08-29 10:24:03.119  6248  6248 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-29 10:24:03.120  6248  6248 W LG Account v2.2: No ProfileInfo entries
08-29 10:24:03.121  6248  6248 I LG Account v2.2: isEnabled: false
08-29 10:24:03.122  6248  6248 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 10:24:03.122  6248  6248 I Feature : [Lifetracker]Country: EU
08-29 10:24:03.122  6248  6248 I Feature : [Lifetracker]Operator: OPEN
08-29 10:24:03.122  6248  6248 I Feature : [Lifetracker]Ranking support: false
08-29 10:24:03.123  6248  6248 I Feature : [Lifetracker]Comfort support: false
08-29 10:24:03.123  6248  6248 I Feature : [Lifetracker]Accessory: true
08-29 10:24:03.123  6248  6248 I Feature : [Lifetracker]Health device: true
08-29 10:24:03.123  6248  6248 I Feature : [Lifetracker]Extra Pedometer: false
08-29 10:24:03.123  6248  6248 I Feature : [Lifetracker]Blood glucose device: false
08-29 10:24:03.124  6248  6248 I Feature : [Lifetracker]Device Number: 3
08-29 10:24:03.149  6209  6209 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 10:24:03.156  6209  6209 D BluetoothPermissionRequest: onReceive
08-29 10:24:03.161  6209  6209 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 10:24:03.170  6272  6272 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 10:24:03.177  6209  6209 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 10:24:03.179  1029  1989 I ActivityManager: Killing 5773:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-29 10:24:03.237  3822  3822 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-29 10:24:03.237  3822  3822 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 10:24:03.239  1029  1916 W libprocessgroup: failed to open /acct/uid_10011/pid_5773/cgroup.procs: No such file or directory
08-29 10:24:03.239  3822  3822 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 10:24:03.243  6272  6272 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-29 10:24:03.253  3822  3822 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:03.253  3822  3822 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-29 10:24:03.255  3822  3822 V BluetoothFtpService: Ftp Service onStartCommand
08-29 10:24:03.256  3822  3822 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:03.256  3822  3822 V BluetoothFtpService: Ftp Service closeService
08-29 10:24:03.257  3822  3822 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 10:24:03.262  3822  3822 V BluetoothFtpService: successfully stopped ftp service
08-29 10:24:03.263  3822  3822 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 10:24:03.263  3822  3822 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 10:24:03.263  3822  3822 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 10:24:03.263  3822  3822 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:03.263  3822  3822 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 10:24:03.263  3822  3822 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 10:24:03.266  3822  3822 V BluetoothFtpService: Ftp Service onDestroy
08-29 10:24:03.266  3822  3822 V BluetoothFtpService: Ftp Service closeService
,08-29 10:24:03.296  6272  6272 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-29 10:24:03.296  6272  6272 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-29 10:24:03.297  6272  6272 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-29 10:24:03.297  6272  6272 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,08-29 10:24:03.298  6272  6272 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-29 10:24:03.300  6272  6272 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 10:24:03.306  6272  6272 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-29 10:24:03.320  1029  1044 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6291 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 10:24:03.324  3822  3822 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:03.324  3822  3822 V BluetoothSapService: state: 13
08-29 10:24:03.324  3822  3822 V BluetoothSapService: Stopping SAP server process
08-29 10:24:03.325  3822  3822 V BluetoothSapService: Sap Service closeSapService in
08-29 10:24:03.325  3822  3822 V BluetoothSapService: Close listen Socket : 
08-29 10:24:03.325  3822  3822 V BluetoothSapService: Close rfcomm Socket : 
08-29 10:24:03.325  3822  3822 V BluetoothSapService: Close sapd  Socket : 
08-29 10:24:03.327  3822  3822 V BluetoothSapService: Sap Service closeSapService out
08-29 10:24:03.327  3822  3822 V BluetoothSapService: Sap Service onDestroy
08-29 10:24:03.327  3822  3822 V BluetoothSapService: Sap Service closeSapService in
08-29 10:24:03.327  3822  3822 V BluetoothSapService: Close listen Socket : 
08-29 10:24:03.327  3822  3822 V BluetoothSapService: Close rfcomm Socket : 
08-29 10:24:03.327  3822  3822 V BluetoothSapService: Close sapd  Socket : 
08-29 10:24:03.328  3822  3822 V BluetoothSapService: Sap Service closeSapService out
08-29 10:24:03.339  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 10:24:03.343  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:03.372  6272  6272 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 10:24:03.377  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:03.378  6272  6272 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 10:24:03.385  6272  6272 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-29 10:24:03.387  6226  6226 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 10:24:03.387  6226  6226 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-29 10:24:03.387  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 10:24:03.393  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:03.400  6291  6291 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 10:24:03.401  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:03.410  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:03.410  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:03.412  6272  6272 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 10:24:03.463  1029  1724 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6314 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 10:24:03.467  1029  1724 I ActivityManager: Killing 5791:com.android.contacts/u0a19 (adj 15): empty #17
08-29 10:24:03.528  1029  2026 W libprocessgroup: failed to open /acct/uid_10019/pid_5791/cgroup.procs: No such file or directory
,08-29 10:24:03.595  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 10:24:03.599  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 10:24:03.608  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 10:24:03.623  6314  6333 W FormManager: Network not available. Please check & try again.
,08-29 10:24:03.630  3822  4009 W bt-btif : ag scb idx 1 not allocated
08-29 10:24:03.630  3822  3905 D bt_hci_bdroid: cleanup
08-29 10:24:03.630  3822  4011 I bt_lpm  : LPM is already off!!!
08-29 10:24:03.630  3822  4009 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 10:24:03.630  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 10:24:03.630  3822  4009 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:24:03.630  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 10:24:03.630  3822  4009 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:24:03.630  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 10:24:03.630  3822  4009 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:24:03.630  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 10:24:03.631  3822  4105 I bt_userial_mct: exiting userial_read_thread
08-29 10:24:03.631  3822  4009 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:24:03.631  3822  4105 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 10:24:03.631  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 10:24:03.631  3822  4009 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:24:03.631  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 10:24:03.631  3822  4009 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:24:03.631  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 10:24:03.631  3822  4009 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:24:03.631  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 10:24:03.631  3822  3905 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 10:24:03.631  3822  4009 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:24:03.631  3822  4009 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 10:24:03.631  3822  4009 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:24:03.631  3822  4011 I bt_vendor: hw_epilog_process
08-29 10:24:03.631  3822  4009 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 10:24:03.631  3822  3905 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 10:24:03.631  3822  3905 D bt_userial_mct: userial_close
08-29 10:24:03.631  3822  3905 E bt_userial_mct: pthread_join() FAILED result:3
08-29 10:24:03.631  3822  3905 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-29 10:24:03.635  2165  2165 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19983
08-29 10:24:03.642  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 10:24:03.642  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 10:24:03.642  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 10:24:03.642  6209  6209 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 10:24:03.643  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-29 10:24:03.648  6314  6334 V FormManager: Network unavailable.
08-29 10:24:03.650  6314  6334 V FormManager: Network unavailable.
08-29 10:24:03.656  6209  6209 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 10:24:03.656  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 10:24:03.656  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 10:24:03.656  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 10:24:03.657  6209  6209 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 10:24:03.657  6209  6209 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 10:24:03.662  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 10:24:03.662  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 10:24:03.664  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 10:24:03.667  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 10:24:03.675  6226  6226 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 10:24:03.675  6226  6226 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 10:24:03.675  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 10:24:03.681  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 10:24:03.683  6314  6339 W FormManager: Network not available. Please check & try again.
08-29 10:24:03.685  4258  6341 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 10:24:03.685  6314  6340 V FormManager: Network unavailable.
,08-29 10:24:03.687  4258  6338 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 10:24:03.688  4258  6341 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 10:24:03.690  6314  6340 V FormManager: Network unavailable.
08-29 10:24:03.693  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:03.700  1029  1863 I ActivityManager: Killing 5601:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-29 10:24:03.725  3822  3905 D bt_hci_bdroid: set_power 0
08-29 10:24:03.725  3822  3905 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 10:24:03.725  3822  3905 I bt_vendor: bluetooth satus is on
,08-29 10:24:03.725  3822  3905 I bt_vendor: bt-vendor : resetting BT status
08-29 10:24:03.725  3822  3905 I bt_vendor: Starting hciattach daemon
08-29 10:24:03.725  3822  3905 I bt_vendor: try to set false
08-29 10:24:03.727  3822  3905 I bt_vendor: Starting hciattach daemon
08-29 10:24:03.727  3822  3905 I bt_vendor: try to set false
08-29 10:24:03.728  3822  3905 I bt_vendor: cleanup
08-29 10:24:03.731  3822  4009 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 10:24:03.756  1029  2026 W libprocessgroup: failed to open /acct/uid_10004/pid_5601/cgroup.procs: No such file or directory
,08-29 10:24:03.769  3822  3905 I GKI_LINUX: GKI_exit_task 0 done
,08-29 10:24:03.769  3822  3905 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 10:24:03.771  3822  3901 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 10:24:03.776  3822  3822 D HeadsetService: Received stop request...Stopping profile...
08-29 10:24:03.778  3822  3822 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 10:24:03.778  3822  3822 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 10:24:03.778  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2568a598
08-29 10:24:03.779  3822  3936 D HeadsetStateMachine: Exit Disconnected: -1
08-29 10:24:03.779  1029  1029 D BluetoothHeadset: Proxy object disconnected
08-29 10:24:03.779  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 10:24:03.780  1846  1846 D BluetoothHeadset: Proxy object disconnected
08-29 10:24:03.780  1846  1846 D BluetoothHeadset: Proxy object disconnected
08-29 10:24:03.780  1846  1846 D BluetoothHeadset: Proxy object disconnected
,08-29 10:24:03.784  6272  6272 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 10:24:03.786  3822  3822 D A2dpService: Received stop request...Stopping profile...
08-29 10:24:03.786  3822  3991 D A2dpStateMachine: Exit Disconnected: -1
08-29 10:24:03.788  3822  3822 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 10:24:03.789  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-29 10:24:03.791  3822  3901 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 10:24:03.791  3822  3822 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 10:24:03.791  3822  3822 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 10:24:03.791  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2568a598
08-29 10:24:03.792  1029  1029 D BluetoothA2dp: Proxy object disconnected
08-29 10:24:03.792  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 10:24:03.793  3822  3822 D HeadsetStateMachine: Unbinding service...
,08-29 10:24:03.794  3822  3822 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 10:24:03.794  3822  3822 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 10:24:03.794  3822  3822 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 10:24:03.794  3822  3822 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 10:24:03.795  3822  3822 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 10:24:03.795  3822  3822 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 10:24:03.795  3822  3822 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 10:24:03.796  6272  6272 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-29 10:24:03.797  3822  3822 D HidService: Received stop request...Stopping profile...
08-29 10:24:03.797  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2568a598
08-29 10:24:03.798  3822  3822 D HealthService: Received stop request...Stopping profile...
08-29 10:24:03.799  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2568a598
08-29 10:24:03.800  6209  6209 D BluetoothInputDevice: Proxy object disconnected
08-29 10:24:03.800  3822  3822 D PanService: Received stop request...Stopping profile...
08-29 10:24:03.800  6209  6209 D HidProfile: Bluetooth service disconnected
08-29 10:24:03.800  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2568a598
08-29 10:24:03.801  3822  3822 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:24:03.801  6209  6209 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 10:24:03.802  6209  6209 D PanProfile: Bluetooth service disconnected
08-29 10:24:03.802  3822  3822 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 10:24:03.802  3822  3822 D BtGatt.GattService: stop()
08-29 10:24:03.802  3822  3822 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 10:24:03.803  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2568a598
08-29 10:24:03.804  3822  3822 D BluetoothMapService: Received stop request...Stopping profile...
08-29 10:24:03.804  3822  3822 D BluetoothMapService: stop()
,08-29 10:24:03.808  3822  3822 D BluetoothMapEmailAppObserver: deinitObservers()
,08-29 10:24:03.808  3822  3822 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 10:24:03.809  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2568a598
08-29 10:24:03.811  3822  3822 I BluetoothA2dpServiceJni: cleanupNative
08-29 10:24:03.811  3822  3993 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 10:24:03.811  6209  6209 D BluetoothMap: Proxy object disconnected
08-29 10:24:03.811  6209  6209 D MapProfile: Bluetooth service disconnected
08-29 10:24:03.811  3822  3822 I GKI_LINUX: GKI_exit_task 2 done
08-29 10:24:03.811  3822  3822 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 10:24:03.811  3822  3822 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 10:24:03.811  3822  3822 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 10:24:03.812  3822  3822 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 10:24:03.812  3822  3822 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 10:24:03.812  3822  3822 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 10:24:03.812  3822  3822 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 10:24:03.812  3822  3822 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 10:24:03.813  3822  3822 V BluetoothMapService: Handler(): got msg=4
08-29 10:24:03.813  3822  3822 D BluetoothMapService: MAP Service closeService in
08-29 10:24:03.813  3822  3822 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 10:24:03.813  3822  3822 V BluetoothMapService: MAP Service closeService out
08-29 10:24:03.814  3822  3901 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 10:24:03.814  3822  3901 D BluetoothAdapterProperties: Setting state to 10
08-29 10:24:03.814  3822  3901 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 10:24:03.814  1029  1111 D BluetoothManagerService: Message: 60
08-29 10:24:03.814  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 10:24:03.815  3822  3901 I BluetoothAdapterState: Entering OffState
08-29 10:24:03.815  1029  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-29 10:24:03.815  3822  3822 D BluetoothMapService: cleanup()
08-29 10:24:03.815  3822  3822 D BluetoothMapService: MAP Service closeService in
08-29 10:24:03.815  3822  3822 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 10:24:03.815  3822  3822 V BluetoothMapService: MAP Service closeService out
08-29 10:24:03.815  6209  6225 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 10:24:03.815  1029  1111 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:24:03.816  1846  2722 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:24:03.816  6209  6224 D BluetoothMap: onBluetoothStateChange: up=false
08-29 10:24:03.817  1029  1111 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:24:03.817  6209  6225 D BluetoothPan: onBluetoothStateChange on: false
,08-29 10:24:03.818  6209  6224 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 10:24:03.819  1846  2447 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:24:03.819  1846  1862 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:24:03.820  1029  1111 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 10:24:03.820  1029  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 10:24:03.823  1029  1111 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 10:24:03.823  1029  1111 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 10:24:03.823  1029  1111 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3dcdfbbb mBinding = false
08-29 10:24:03.824  1029  1111 D BluetoothManagerService: Sending unbind request.
08-29 10:24:03.825  1029  1111 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 10:24:03.831  3822  3905 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 10:24:03.832  3822  3822 I GKI_LINUX: GKI_exit_task 1 done
08-29 10:24:03.832  3822  3822 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-29 10:24:03.832  3822  3822 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 10:24:03.832  3822  3822 I art     : --- WEIRD: removing null entry 246
08-29 10:24:03.833  3822  3822 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-29 10:24:03.833  3822  3822 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 10:24:03.838  6209  6209 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 10:24:03.839  6209  6209 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 10:24:03.839  6209  6209 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 10:24:03.839  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 10:24:03.839  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:03.840  1935  2096 D LGBluetoothAPIService: Message: 2
08-29 10:24:03.840  1935  2096 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@6a82285 mBinding = false
08-29 10:24:03.840  1935  2096 D LGBluetoothAPIService: Sending unbind request.
08-29 10:24:03.841  1029  1372 V AlarmManager: RTC_WAKEUP set : Alarm{6f23ae4 type 0 when 1472459043800 com.android.vending} when 1472459043800
08-29 10:24:03.841  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:03.842  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:03.843  6209  6209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 10:24:03.847  3822  3822 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 10:24:03.851  3822  3822 I art     : System.exit called, status: 0
08-29 10:24:03.851  3822  3822 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 10:24:03.854  1595  1595 D BluetoothAdapter: 593180019: getState() :  mService = null. Returning STATE_OFF
08-29 10:24:03.863  1595  1595 D BluetoothAdapter: 593180019: getState() :  mService = null. Returning STATE_OFF,
,08-29 10:24:03.870  6209  6209 D DockEventReceiver: finishStartingService: stopping service
08-29 10:24:03.876   336   336 V AudioFlinger: 3822 died, releasing its sessions
08-29 10:24:03.876   336   336 V AudioFlinger:  pid 1846 @ 0
08-29 10:24:03.876   336   336 V AudioFlinger:  pid 3411 @ 1
08-29 10:24:03.876   336   336 V AudioFlinger:  pid 3411 @ 2
08-29 10:24:03.876  6209  6209 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 10:24:03.883  6272  6272 D LgDataFeature: LgDataFeature() Constructor: none
08-29 10:24:03.883  6272  6272 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 10:24:03.890  6272  6272 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-29 10:24:03.891  6272  6272 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 10:24:03.891  6272  6272 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-29 10:24:03.891  6272  6272 V SoundPool: doLoad: loading sample sampleID=1
08-29 10:24:03.892  6272  6272 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 10:24:03.892  6272  6351 V SoundPool: Start decode
08-29 10:24:03.892  6272  6351 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-29 10:24:03.893   336  2180 V MediaPlayerService: decode(23, 10857164, 17813)
08-29 10:24:03.893   336  2180 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-29 10:24:03.893   336  2180 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 10:24:03.893   336  2180 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 10:24:03.893   336  2180 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 10:24:03.893   336  2180 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 10:24:03.893   336  2180 V MediaPlayerService: player type = 3
08-29 10:24:03.893   336  2180 V AwesomePlayer: AwesomePlayer create()
08-29 10:24:03.893   336  2180 V AwesomePlayer: reset_l() 
08-29 10:24:03.893   336  2180 V AwesomePlayer: cancelPlayerEvents
08-29 10:24:03.894   336  2180 V AwesomePlayer: setAudioSink() 
08-29 10:24:03.894   336  2180 V AwesomePlayer: reset_l() 
08-29 10:24:03.894   336  2180 V AudioCache: notify(0xb5474580, 8, 0, 0)
08-29 10:24:03.894   336  2180 V AudioCache: ignored
08-29 10:24:03.894   336  2180 V AwesomePlayer: cancelPlayerEvents
08-29 10:24:03.894   336  2180 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 10:24:03.894   336  2180 V AwesomePlayer: setDataSource_l dataSource
08-29 10:24:03.894   336  2180 V LGParserOSAL: SniffLGParser start
08-29 10:24:03.894   336  2180 V LGParserOSAL: MainType:5, SubType=0
08-29 10:24:03.894   336  2180 V LGParserOSAL: #### check Mime : application/ogg
08-29 10:24:03.894   336  2180 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 10:24:03.894   336  2180 E MediaExtractor: Use LGExtractor :application/ogg 
08-29 10:24:03.915  1029  1898 V SIM_STK : Menu title from STK is T-Mobile
,08-29 10:24:03.940   336  2180 V LGParserOSAL: supported mime: application/ogg
08-29 10:24:03.940   336  2180 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 10:24:03.940   336  2180 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 10:24:03.940   336  2180 V AwesomePlayer: mBitrate = -1 bits/sec
08-29 10:24:03.940   336  2180 V AwesomePlayer: AudioTrack Setting
08-29 10:24:03.940   336  2180 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 10:24:03.940   336  2180 V AwesomePlayer: setAudioSource() 
08-29 10:24:03.940   336  2180 V MediaPlayerService: prepare
08-29 10:24:03.940   336  2180 V AwesomePlayer: prepareAsync_l() 
08-29 10:24:03.940   336  2180 V MediaPlayerService: wait for prepare
08-29 10:24:03.940   336  6353 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 10:24:03.940   336  6353 V AwesomePlayer: initAudioDecoder() 
08-29 10:24:03.940   336  6353 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 10:24:03.940   336  6353 V AudioSystem: isOffloadSupported()
08-29 10:24:03.940   336  6353 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 10:24:03.940   336  6353 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 10:24:03.940   336  6353 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 10:24:03.940   336  6353 V AwesomePlayer: getUseOffload() = 0 
08-29 10:24:03.940   336  6353 V OMXCodec: OMXCodec::Create
08-29 10:24:03.940   336  6353 V OMXCodec: findMatchingCodecs()
08-29 10:24:03.941   336  6353 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 10:24:03.941   336  6353 V OMXCodec: matchingCodecs.size()=1
08-29 10:24:03.941   336  6353 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-29 10:24:03.943   336  6353 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 10:24:03.943   336  6353 V LGCodecAdapter: LG Codec Adapter start
08-29 10:24:03.943   336  6353 V OMXCodec: OMXCodec Createtor
08-29 10:24:03.943   336  6353 V OMXCodec: setComponentRole
08-29 10:24:03.943   336  6353 V OMXCodec: configureCodec protected=0
08-29 10:24:03.943   336  6353 V LGCodecAdapter: called getLGCodecSpecificData
08-29 10:24:03.943   336  6353 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 10:24:03.943   336  6353 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 10:24:03.943   336  6353 V LGCodecOSAL: Called LGconfigureCodecMSG
,08-29 10:24:03.943   336  6353 V LGCodecOSAL: Not support LGCodec
08-29 10:24:03.943   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 10:24:03.943   336  6353 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 10:24:03.943   336  6353 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 10:24:03.943   336  6353 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 10:24:03.944   336  6353 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 10:24:03.944   336  6353 V AudioSystem: isOffloadSupported()
,08-29 10:24:03.944   336  6353 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 10:24:03.944   336  6353 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 10:24:03.944   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-29 10:24:03.944   336  6353 V OMXCodec: init()
08-29 10:24:03.944   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-29 10:24:03.944   336  6353 V OMXCodec: allocateBuffers
08-29 10:24:03.944   336  6353 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 10:24:03.944   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 10:24:03.944  1029  1971 I ActivityManager: Process com.android.bluetooth (pid 3822) has died
08-29 10:24:03.945   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-29 10:24:03.945   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-29 10:24:03.945   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-29 10:24:03.945  1029  1971 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-29 10:24:03.945   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on input port
08-29 10:24:03.945   336  6353 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 10:24:03.945   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 10:24:03.945   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-29 10:24:03.945   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c12e0 on output port
08-29 10:24:03.945   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c13d0 on output port
08-29 10:24:03.945   336  6353 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1510 on output port
08-29 10:24:03.945   336  6353 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 10:24:03.945   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 10:24:03.945   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 10:24:03.946   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 10:24:03.946   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 10:24:03.946   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 10:24:03.946   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 10:24:03.946   336  6353 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 10:24:03.946   336  6353 V AwesomePlayer: finishAsyncPrepare_l() 
08-29 10:24:03.946   336  6353 V AudioCache: notify(0xb5474580, 5, 0, 0)
08-29 10:24:03.946   336  6353 V AudioCache: ignored
08-29 10:24:03.946   336  6353 V AudioCache: notify(0xb5474580, 1, 0, 0)
08-29 10:24:03.946   336  6353 V AudioCache: prepared
08-29 10:24:03.946   336  2180 V AudioCache: wait - success
08-29 10:24:03.946   336  2180 V MediaPlayerService: start
08-29 10:24:03.946   336  2180 V AwesomePlayer: play_l() 
08-29 10:24:03.946   336  2180 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-29 10:24:03.946   336  2180 V AwesomePlayer: createAudioPlayer_l
08-29 10:24:03.946   336  2180 V AwesomePlayer: seekAudioIfNecessary_l() 
08-29 10:24:03.946   336  2180 V AwesomePlayer: startAudioPlayer_l() 
08-29 10:24:03.946   336  2180 D AudioPlayer: start of Playback, useOffload 0
08-29 10:24:03.946   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 10:24:03.946   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 10:24:03.950  6142  6142 D UEI.SmartControl: QS Service created
08-29 10:24:03.9,51  2265  2265 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044807392
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044807632
08-29 10:24:03.952   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 10:24:03.953   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044807952
08-29 10:24:03.953   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 10:24:03.953   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-29 10:24:03.953   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 10:24:03.953   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-29 10:24:03.953   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 10:24:03.953   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-29 10:24:03.954   336  6355 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 10:24:03.954   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 10:24:03.954   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c13d0 on output port
08-29 10:24:03.954   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c12e0 on output port
08-29 10:24:03.954   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-29 10:24:03.954   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-29 10:24:03.954   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-29 10:24:03.954   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-29 10:24:03.956   336  2180 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-29 10:24:03.958   336  2180 V AudioCache: notify(0xb5474580, 6, 0, 0)
08-29 10:24:03.958   336  2180 V AudioCache: ignored
08-29 10:24:03.959   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.959   336  6357 V AudioCache: memcpy(0xaf006000, 0xb16a8000, 4096)
08-29 10:24:03.961   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.961   336  6357 V AudioCache: memcpy(0xaf007000, 0xb16a8000, 4096)
08-29 10:24:03.961   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.961   336  6357 V AudioCache: memcpy(0xaf008000, 0xb16a8000, 4096)
08-29 10:24:03.961   336  2180 V MediaPlayerService: wait for playback complete
08-29 10:24:03.963  6209  6209 D BluetoothPermissionRequest: onReceive
08-29 10:24:03.963   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.963   336  6357 V AudioCache: memcpy(0xaf009000, 0xb16a8000, 4096)
08-29 10:24:03.963   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.963   336  6357 V AudioCache: memcpy(0xaf00a000, 0xb16a8000, 4096)
08-29 10:24:03.963   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.963   336  6357 V AudioCache: memcpy(0xaf00b000, 0xb16a8000, 4096)
08-29 10:24:03.964   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.964   336  6357 V AudioCache: memcpy(0xaf00c000, 0xb16a8000, 4096)
08-29 10:24:03.965   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.965   336  6357 V AudioCache: memcpy(0xaf00d000, 0xb16a8000, 4096)
08-29 10:24:03.966  6209  6209 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 10:24:03.966  6209  6209 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 10:24:03.967   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.967   336  6357 V AudioCache: memcpy(0xaf00e000, 0xb16a8000, 4096)
08-29 10:24:03.967   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.967   336  6357 V AudioCache: memcpy(0xaf00f000, 0xb16a8000, 4096)
,08-29 10:24:03.967   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.967   336  6357 V AudioCache: memcpy(0xaf010000, 0xb16a8000, 4096)
08-29 10:24:03.968   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.968   336  6357 V AudioCache: memcpy(0xaf011000, 0xb16a8000, 4096)
08-29 10:24:03.969   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.969   336  6357 V AudioCache: memcpy(0xaf012000, 0xb16a8000, 4096)
08-29 10:24:03.970   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.970  6209  6209 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 10:24:03.970   336  6357 V AudioCache: memcpy(0xaf013000, 0xb16a8000, 4096)
08-29 10:24:03.970  6272  6272 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 10:24:03.970   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.970   336  6357 V AudioCache: memcpy(0xaf014000, 0xb16a8000, 4096)
08-29 10:24:03.971   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.971   336  6357 V AudioCache: memcpy(0xaf015000, 0xb16a8000, 4096)
08-29 10:24:03.972   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.972   336  6357 V AudioCache: memcpy(0xaf016000, 0xb16a8000, 4096)
08-29 10:24:03.973  6142  6142 I UEI.SmartControl: Service initServices...
08-29 10:24:03.973  6272  6272 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 10:24:03.973   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.973   336  6357 V AudioCache: memcpy(0xaf017000, 0xb16a8000, 4096)
08-29 10:24:03.973  6142  6142 D UEI.SmartControl: QS start get config
08-29 10:24:03.973  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 10:24:03.974   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.974   336  6357 V AudioCache: memcpy(0xaf018000, 0xb16a8000, 4096)
08-29 10:24:03.975   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.975   336  6357 V AudioCache: memcpy(0xaf019000, 0xb16a8000, 4096)
08-29 10:24:03.976   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.976   336  6357 V AudioCache: memcpy(0xaf01a000, 0xb16a8000, 4096)
08-29 10:24:03.976   336  6357 V AudioCache: write(0xb16a8000, 4096)
,08-29 10:24:03.976   336  6357 V AudioCache: memcpy(0xaf01b000, 0xb16a8000, 4096)
08-29 10:24:03.977   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.977   336  6357 V AudioCache: memcpy(0xaf01c000, 0xb16a8000, 4096)
08-29 10:24:03.978   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.978   336  6357 V AudioCache: memcpy(0xaf01d000, 0xb16a8000, 4096)
08-29 10:24:03.978   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.979   336  6357 V AudioCache: memcpy(0xaf01e000, 0xb16a8000, 4096)
08-29 10:24:03.979   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.979   336  6357 V AudioCache: memcpy(0xaf01f000, 0xb16a8000, 4096)
08-29 10:24:03.980   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.980   336  6357 V AudioCache: memcpy(0xaf020000, 0xb16a8000, 4096)
08-29 10:24:03.981   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.981   336  6357 V AudioCache: memcpy(0xaf021000, 0xb16a8000, 4096)
08-29 10:24:03.981   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.981   336  6357 V AudioCache: memcpy(0xaf022000, 0xb16a8000, 4096)
08-29 10:24:03.982   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.982   336  6357 V AudioCache: memcpy(0xaf023000, 0xb16a8000, 4096)
08-29 10:24:03.983   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.983   336  6357 V AudioCache: memcpy(0xaf024000, 0xb16a8000, 4096)
08-29 10:24:03.983   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.983   336  6357 V AudioCache: memcpy(0xaf025000, 0xb16a8000, 4096)
08-29 10:24:03.984   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.984   336  6357 V AudioCache: memcpy(0xaf026000, 0xb16a8000, 4096)
08-29 10:24:03.985   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.985   336  6357 V AudioCache: memcpy(0xaf027000, 0xb16a8000, 4096)
08-29 10:24:03.986   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.986   336  6357 V AudioCache: memcpy(0xaf028000, 0xb16a8000, 4096)
08-29 10:24:03.986   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.986   336  6357 V AudioCache: memcpy(0xaf029000, 0xb16a8000, 4096)
08-29 10:24:03.987   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.987   336  6357 V AudioCache: memcpy(0xaf02a000, 0xb16a8000, 4096)
08-29 10:24:03.988   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.988   336  6357 V AudioCache: memcpy(0xaf02b000, 0xb16a8000, 4096)
,08-29 10:24:03.988   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.989   336  6357 V AudioCache: memcpy(0xaf02c000, 0xb16a8000, 4096)
08-29 10:24:03.989  6272  6272 V LGMDMManager: Create singleton instance
08-29 10:24:03.989   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.989   336  6357 V AudioCache: memcpy(0xaf02d000, 0xb16a8000, 4096)
08-29 10:24:03.990   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.990   336  6357 V AudioCache: memcpy(0xaf02e000, 0xb16a8000, 4096)
,08-29 10:24:03.991   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.991   336  6357 V AudioCache: memcpy(0xaf02f000, 0xb16a8000, 4096)
08-29 10:24:03.991   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.991   336  6357 V AudioCache: memcpy(0xaf030000, 0xb16a8000, 4096)
08-29 10:24:03.992   336  6357 V AudioCache: write(0xb16a8000, 4096)
,08-29 10:24:03.992   336  6357 V AudioCache: memcpy(0xaf031000, 0xb16a8000, 4096)
08-29 10:24:03.993   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.993   336  6357 V AudioCache: memcpy(0xaf032000, 0xb16a8000, 4096)
08-29 10:24:03.994   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.994   336  6357 V AudioCache: memcpy(0xaf033000, 0xb16a8000, 4096)
,08-29 10:24:03.995   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.995   336  6357 V AudioCache: memcpy(0xaf034000, 0xb16a8000, 4096)
08-29 10:24:03.995   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.995   336  6357 V AudioCache: memcpy(0xaf035000, 0xb16a8000, 4096)
,08-29 10:24:03.996   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.996   336  6357 V AudioCache: memcpy(0xaf036000, 0xb16a8000, 4096)
08-29 10:24:03.996   336  6357 V AudioCache: write(0xb16a8000, 4096)
08-29 10:24:03.997   336  6357 V AudioCache: memcpy(0xaf037000, 0xb16a8000, 4096)
08-29 10:24:03.997   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-29 10:24:03.997   336  6357 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 10:24:03.997   336  6357 V AwesomePlayer: postAudioEOS() 
08-29 10:24:03.997   336  6357 V AudioCache: write(0xb16a8000, 280)
08-29 10:24:03.997   336  6357 V AudioCache: memcpy(0xaf038000, 0xb16a8000, 280)
08-29 10:24:04.000   336  6353 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 10:24:04.000   336  6353 V AwesomePlayer: onStreamDone
08-29 10:24:04.000   336  6353 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 10:24:04.000   336  6353 V AudioCache: notify(0xb5474580, 2, 0, 0)
08-29 10:24:04.000   336  6353 V AudioCache: playback complete
08-29 10:24:04.000   336  6353 V AwesomePlayer: pause_l() 
08-29 10:24:04.000   336  6353 V AudioCache: notify(0xb5474580, 7, 0, 0)
08-29 10:24:04.000   336  6353 V AudioCache: ignored
08-29 10:24:04.000   336  6353 V AwesomePlayer: cancelPlayerEvents
08-29 10:24:04.000   336  6353 D AudioPlayer: Pause Playback at 1068125
08-29 10:24:04.000   336  2180 V AudioCache: wait - success
08-29 10:24:04.000   336  2180 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-29 10:24:04.001   336  2180 V AwesomePlayer: reset_l() 
08-29 10:24:04.001   336  2180 V AudioCache: notify(0xb5474580, 8, 0, 0)
08-29 10:24:04.001   336  2180 V AudioCache: ignored
08-29 10:24:04.001   336  2180 V AwesomePlayer: cancelPlayerEvents
08-29 10:24:04.001   336  2180 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 10:24:04.001   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 10:24:04.001   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 10:24:04.001   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 10:24:04.001   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 10:24:04.001   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 10:24:04.001   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 10:24:04.001   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 10:24:04.001   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 0
08-29 10:24:04.001   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 10:24:04.001   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-29 10:24:04.001   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 10:24:04.001   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-29 10:24:04.001   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 10:24:04.001   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-29 10:24:04.001   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 1
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder], freeing buffer 0xb57c12e0 on port 1
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c13d0 on port 1
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 10:24:04.002   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 10:24:04.002   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 10:24:04.002   336  6355 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 10:24:04.003   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 10:24:04.003   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 10:24:04.003   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-29 10:24:04.004   336  2180 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 10:24:04.004   336  2180 D AudioPlayer: AudioPlayer releasing audio source
08-29 10:24:04.004   336  2180 D AudioPlayer: AudioPlayer done releasing audio source
08-29 10:24:04.005   336  2180 V AwesomePlayer: reset_l() 
08-29 10:24:04.005   336  2180 V AwesomePlayer: cancelPlayerEvents
08-29 10:24:04.005   336  2180 V AwesomePlayer: ~AwesomePlayer call
08-29 10:24:04.005   336  2180 V AwesomePlayer: reset_l() 
08-29 10:24:04.005   336  2180 V AwesomePlayer: cancelPlayerEvents
08-29 10:24:04.005  6272  6351 V SoundPool: close(31)
08-29 10:24:04.005  6272  6351 V SoundPool: pointer = 0xa0014000, size = 205080, sampleRate = 48000, numChannels = 2
,08-29 10:24:04.018  1029  1952 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6358 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 10:24:04.059  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 10:24:04.060  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-29 10:24:04.062  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3733
08-29 10:24:04.063  6358  6358 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 10:24:04.064  6358  6358 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 10:24:04.064  6358  6358 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 10:24:04.065  6358  6358 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 10:24:04.077  6358  6358 D BluetoothAdapterApp: Loading JNI Library
,08-29 10:24:04.098  6358  6358 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@18474b9 Instance Count = 1
,08-29 10:24:04.102  6358  6358 D BluetoothAdapterApp: onCreate
08-29 10:24:04.115  6358  6358 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 10:24:04.115  6358  6358 D ProfileConfigQcom: Adding HeadsetService
08-29 10:24:04.115  6358  6358 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 10:24:04.115  6358  6358 D ProfileConfigQcom: Adding A2dpService
08-29 10:24:04.116  6358  6358 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 10:24:04.116  6358  6358 D ProfileConfigQcom: Adding HidService
08-29 10:24:04.116  6358  6358 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 10:24:04.116  6358  6358 D ProfileConfigQcom: Adding HealthService
08-29 10:24:04.117  6358  6358 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-29 10:24:04.117  6358  6358 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 10:24:04.118  6358  6358 D ProfileConfigQcom: Adding PanService
08-29 10:24:04.118  6358  6358 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 10:24:04.118  6358  6358 D ProfileConfigQcom: Adding GattService
08-29 10:24:04.118  6358  6358 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 10:24:04.119  6358  6358 D ProfileConfigQcom: Adding BluetoothMapService
08-29 10:24:04.119  6358  6358 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 10:24:04.121  6358  6358 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 10:24:04.129  6209  6209 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-29 10:24:04.130  6358  6358 V LGMDMManagerInternal: Create singleton instance
,08-29 10:24:04.143  5897  5897 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-29 10:24:04.175  6358  6358 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:04.177  6358  6358 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-29 10:24:04.178  6358  6358 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 10:24:04.178  6358  6358 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 10:24:04.178  6358  6358 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:04.178  6358  6358 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 10:24:04.185  6291  6291 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-29 10:24:04.248  6142  6142 I UEI.SmartControl: Supports setup maps: true
08-29 10:24:04.251  6142  6142 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 10:24:04.251  6142  6142 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 10:24:04.251  6142  6142 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 10:24:04.251  6142  6142 I UEI.SmartControl: ### init IR Blaster...
,08-29 10:24:04.255  6142  6142 D serial_port: Configuring serial port
08-29 10:24:04.255  6142  6142 E UEI.SmartControl: UEIBLaster setting for 616
08-29 10:24:04.255  6142  6142 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 10:24:04.255  6142  6142 I UEI.SmartControl: configuring settings for MAXQ616
08-29 10:24:04.255  6142  6142 I UEI.SmartControl: Get version...
08-29 10:24:04.269  6142  6378 D UEI.SmartControl: serial port data available: 21
,08-29 10:24:04.296  6142  6142 D UEI.SmartControl: MAXQ616 A2-X4 software.,
,08-29 10:24:04.296  6142  6142 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 10:24:04.296  6142  6142 I UEI.SmartControl: QS saving settings...
08-29 10:24:04.298  6142  6142 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 10:24:04.317  6142  6378 D UEI.SmartControl: serial port data available: 4
,08-29 10:24:04.348  6142  6381 I UEI.SmartControl: Device manager: loading config....
,08-29 10:24:04.352  6142  6381 D UEI.SmartControl: ----------- loading internal config...
08-29 10:24:04.352  6142  6142 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 10:24:04.355  6142  6142 E UEI.SmartControl: Services init done
08-29 10:24:04.356  6142  6142 D UEI.SmartControl: QS Service init finished
08-29 10:24:04.358  6142  6142 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 10:24:04.358  6142  6142 D UEI.SmartControl: QS Service version code: 201091
08-29 10:24:04.359  6142  6142 D UEI.SmartControl: Service requested: Control
08-29 10:24:04.359  6142  6381 E UEI.SmartControl: Loading SETTINGS...
08-29 10:24:04.361  6272  6272 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 10:24:04.361  6142  6142 D UEI.SmartControl: Internal service binding...
,08-29 10:24:04.362  6142  6158 I UEI.SmartControl: ------ IControl API: 11
08-29 10:24:04.362  6142  6158 D UEI.SmartControl: File observer start...
08-29 10:24:04.363  6142  6158 E UEI.SmartControl: IR Port is disabled: false
08-29 10:24:04.363  6142  6158 D UEI.SmartControl: Starting file observer...
08-29 10:24:04.364  6142  6158 I UEI.SmartControl: Registering callback...
08-29 10:24:04.365  6142  6157 I UEI.SmartControl: ------ IControl API: 19
08-29 10:24:04.367  6142  6157 I UEI.SmartControl: Registering Services Ready callback...
08-29 10:24:04.373  6142  6381 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 10:24:04.387  6142  6380 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 10:24:04.388  6272  6287 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-29 10:24:04.390  6272  6349 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 10:24:04.390  6272  6349 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 10:24:04.391  6142  6380 D UEI.SmartControl: -----service ready thread exits
08-29 10:24:04.391  6272  6272 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 10:24:04.393  6272  6272 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 10:24:04.394  6142  6158 I UEI.SmartControl: ------ IControl API: 8
08-29 10:24:04.397  6272  6272 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 10:24:04.398  6272  6272 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 10:24:04.399  6272  6272 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 10:24:04.400  6272  6272 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-29 10:24:04.402  6272  6272 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 10:24:04.403  6272  6272 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-29 10:24:04.406  6272  6272 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 10:24:04.409  6272  6272 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 10:24:04.411  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 10:24:04.413  6272  6272 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 10:24:04.414  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-29 10:24:04.416  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-29 10:24:04.418  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-29 10:24:04.419  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 10:24:04.420  6272  6272 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472459044419]
08-29 10:24:04.421  6272  6272 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-29 10:24:04.428  1029  1045 I ActivityManager: Killing 5853:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-29 10:24:04.463  6272  6383 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-29 10:24:04.536  1029  1045 I ActivityManager: Killing 5817:com.lge.email/u0a23 (adj 15): empty #18
,08-29 10:24:04.601  1029  2025 W libprocessgroup: failed to open /acct/uid_10027/pid_5853/cgroup.procs: No such file or directory
,08-29 10:24:04.607  1029  1953 W libprocessgroup: failed to open /acct/uid_10023/pid_5817/cgroup.procs: No such file or directory
08-29 10:24:04.613  6272  6272 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-29 10:24:04.615  6272  6272 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-29 10:24:04.616  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-29 10:24:04.617  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-29 10:24:04.618  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-29 10:24:04.619  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-29 10:24:04.620  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-29 10:24:04.630  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-29 10:24:05.635  1029  1917 D WifiServiceImplEx: setWifiEnabled: true pid=5976, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 10:24:05.637  1029  1917 D WifiService: setWifiEnabled: true pid=5976, uid=10118
,08-29 10:24:05.637  1029  1917 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:24:05.661  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 10:24:05.662  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 10:24:05.662  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-29 10:24:05.663  1029  1384 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 10:24:05.663  1029  1384 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 10:24:05.666  1029  1384 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 10:24:05.666  1029  1384 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 10:24:05.666  1029  1384 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 10:24:05.666  1029  1384 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 10:24:05.666  1029  1384 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 10:24:05.666  1029  1384 E WifiHW  : unknown target_country: EU , set to default
08-29 10:24:05.666  1029  1384 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 10:24:05.666  1029  1384 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 10:24:05.666  1029  1384 I WifiUtil: gEnableBmps=1
08-29 10:24:06.263   330   887 D SoftapController: Softap fwReload - Ok
,08-29 10:24:06.268  1029  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 10:24:06.272  1029  1384 E NetdConnector: NDC Command {36 softap fwreload wlan0 STA} took too long (600ms)
08-29 10:24:06.287   330   887 D CommandListener: Setting iface cfg
08-29 10:24:06.287   330   887 D CommandListener: Trying to bring down wlan0
,08-29 10:24:06.292   330   887 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:24:06.295   330  6401 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 10:24:06.306  1029  1384 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-29 10:24:06.308  1029  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 10:24:06.294  6402  6402 W wpa_supplicant: type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:06.316  1029  1384 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 10:24:06.316  1029  1384 E WifiStateMachine: useWiFiOffloading() : false
08-29 10:24:06.316  1029  1384 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 10:24:06.304  6402  6402 W wpa_supplicant: type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 10:24:06.336  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 10:24:06.344  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 10:24:06.355  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:06.362  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:06.362  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-29 10:24:06.364  1029  1384 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 10:24:06.364  1029  1384 D WifiMonitor: connecting to supplicant
08-29 10:24:06.380  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-29 10:24:06.380  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 10:24:06.384  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 10:24:06.384  6209  6209 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 10:24:06.385  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 10:24:06.387  6402  6402 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 10:24:06.387  6209  6209 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 10:24:06.388  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 10:24:06.388  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 10:24:06.388  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 10:24:06.388  6209  6209 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 10:24:06.388  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 10:24:06.389  6209  6209 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 10:24:06.403  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 10:24:06.409  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 10:24:06.415  6314  6420 W FormManager: Network not available. Please check & try again.
,08-29 10:24:06.420  6314  6421 V FormManager: Network unavailable.
08-29 10:24:06.424  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:06.427  6314  6421 V FormManager: Network unavailable.
08-29 10:24:06.428  6402  6402 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 10:24:06.428  6402  6402 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 10:24:06.431  1029  1111 D Tethering: InitialState.processMessage what=4
08-29 10:24:06.436  1029  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 10:24:06.440  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 10:24:06.440  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 10:24:06.440  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 10:24:06.440  6209  6209 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 10:24:06.440  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-29 10:24:06.442  6209  6209 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 10:24:06.442  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 10:24:06.442  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 10:24:06.442  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 10:24:06.442  6209  6209 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 10:24:06.442  6209  6209 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 10:24:06.483  6402  6402 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 10:24:06.525  6402  6402 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 10:24:06.537  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-29 10:24:06.540  1029  6423 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 10:24:06.540  1029  6423 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 10:24:06.541  1029  1384 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 10:24:06.542  1029  1384 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 10:24:06.544  1029  1384 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 10:24:06.544  1029  1384 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 10:24:06.545  1029  1384 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:06.545  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 10:24:06.545  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 10:24:06.546  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 10:24:06.546  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 10:24:06.546  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 10:24:06.546  1029  6423 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 10:24:06.546  1029  6423 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 10:24:06.546  1029  1384 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:06.547  1029  1384 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:06.548  1029  1384 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 10:24:06.550  1029  1384 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 10:24:06.550  1029  1384 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 10:24:06.551  1029  1384 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 10:24:06.551  1029  1384 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 10:24:06.552  1029  1384 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 10:24:06.552  1029  1384 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 10:24:06.552  1029  1384 E WifiStateMachine: useWiFiOffloading() : false
08-29 10:24:06.552  1029  1384 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 10:24:06.553  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:06.553  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:06.553  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:06.553  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:06.553  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 10:24:06.556  1029  1384 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 10:24:06.556  1029  1384 D WifiNative-wlan0: SET update_config 1: returned true
08-29 10:24:06.557  1029  1384 D WifiConfigStore: Loading config and enabling all networks 
08-29 10:24:06.557  1029  1384 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 10:24:06.557  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:06.557  1029  1384 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 10:24:06.561  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:24:06.561  1935  1935 D WfdService: Waiting for WifiP2p enabling
08-29 10:24:06.561  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:06.561  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:06.561  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:06.561  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:06.561  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:06.561  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:06.561  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:06.561  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:06.561  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:06.561  5976  5976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:06.568  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:06.569  1029  1384 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 10:24:06.569  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:06.569  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:06.569  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:06.569  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:06.569  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:06.569  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:06.569  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:06.569  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:06.569  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:06.569  5976  5976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:06.571  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 10:24:06.571  1029  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 10:24:06.577  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 10:24:06.580  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:24:06.584  1029  1384 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 10:24:06.584  1029  1384 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 10:24:06.585  1029  1384 D WifiStateMachine: enableVerboseLogging : level 2
08-29 10:24:06.585  1029  1384 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 10:24:06.586  1029  1384 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 10:24:06.586  1029  1384 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 10:24:06.586  1029  1384 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 10:24:06.586  1029  1384 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 10:24:06.587  1029  1384 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 10:24:06.587  1029  1384 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 10:24:06.587  1029  1384 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 10:24:06.587  1029  1384 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 10:24:06.587  1029  1384 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 10:24:06.587  1029  1384 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 10:24:06.588  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:06.588  1029  1384 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 10:24:06.588  1029  1384 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 10:24:06.589  1029  1384 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 10:24:06.595  1935  1935 D WfdsService: Supplicant Connection state is changed : true
08-29 10:24:06.595  1029  1384 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 10:24:06.596  1029  1384 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 10:24:06.596  1029  1384 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 10:24:06.596  1029  1384 D WifiNative-HAL: Setting external_sim to 1
08-29 10:24:06.596  1029  1384 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 10:24:06.597  1029  1384 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 10:24:06.597  1029  1384 I WifiNative-HAL: startHal
08-29 10:24:06.597  1029  1384 D wifi    : setting scan oui 0xaf66f0a0
08-29 10:24:06.597  1029  1384 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 10:24:06.597  1029  1384 I WifiNative-HAL: startHal
08-29 10:24:06.597  1935  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 10:24:06.597  1935  2295 D WfdsService: Set the WFDS Monitor: true
08-29 10:24:06.597  1029  1384 D wifi    : setting scan oui 0xaf66f0a0
08-29 10:24:06.597  1935  2295 D WfdsMonitor: WfdsMonitorThread create
08-29 10:24:06.597  1029  1384 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 10:24:06.598  1935  2295 D WfdsMonitor: WFDS Monitor is created and started
08-29 10:24:06.598  1935  2295 D WfdsService: WiFi: Supplicant connection re-established
08-29 10:24:06.598  1029  1384 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 10:24:06.598  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 10:24:06.599  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 10:24:06.599  1935  6427 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 10:24:06.599  1029  1384 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 10:24:06.599  1935  6427 E CtrlSupplicant: Succeed to open control connection
08-29 10:24:06.599  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 10:24:06.599  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 10:24:06.599  1935  6427 E CtrlSupplicant: Succeed to open monitor connection
08-29 10:24:06.600  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned tr,ue
08-29 10:24:06.600  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 10:24:06.600  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 10:24:06.601  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 10:24:06.601  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 10:24:06.601  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 10:24:06.601  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 10:24:06.601  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 10:24:06.601  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 10:24:06.602  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 10:24:06.602  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 10:24:06.602  6402  6402 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 10:24:06.602  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 10:24:06.603  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 10:24:06.603  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 10:24:06.603  1935  6427 D WfdsMonitor: Supplicant connection established
08-29 10:24:06.603  1935  2295 D WfdsService: Connected to the supplicant for wfds
08-29 10:24:06.603  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 10:24:06.604  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 10:24:06.604  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 10:24:06.604  1029  1384 E WifiNative: : [119,117,071 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 10:24:06.604  1029  1384 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 10:24:06.605  1029  1384 D WifiNative-wlan0: RECONNECT: returned true
08-29 10:24:06.605  1029  1384 D WifiNative-wlan0: doString: [STATUS]
,08-29 10:24:06.606  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 10:24:06.606  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 10:24:06.606  1029  1384 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 10:24:06.606  1029  1384 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 10:24:06.606  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 10:24:06.607  1029  1384 D WifiNative-wlan0: SET ps 1: returned true
08-29 10:24:06.607  1029  1383 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.608   330   887 D CommandListener: Setting iface cfg
08-29 10:24:06.609   330   887 D CommandListener: Trying to bring up p2p0
08-29 10:24:06.609  6314  6425 W FormManager: Network not available. Please check & try again.
08-29 10:24:06.609  1029  1383 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 10:24:06.609  1029  1383 D LGWifiP2pService: P2pEnablingState
08-29 10:24:06.609  1029  1383 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.609  1029  1383 D LGWifiP2pService: P2p socket connection successful
08-29 10:24:06.609  1029  1383 D LGWifiP2pService: P2pEnabledState
08-29 10:24:06.610  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 10:24:06.610  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 10:24:06.611  1029  1029 D RttService: SCAN_AVAILABLE : 3
08-29 10:24:06.611  1029  1549 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.611  1029  1549 I WifiNative-HAL: startHal
08-29 10:24:06.611  1029  1383 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 10:24:06.611  1029  1549 D wifi    : getting scan capabilities on interface[1] = 0xaf66f0a0
08-29 10:24:06.611  1029  1549 D wifi    : failed to get capabilities : -3
08-29 10:24:06.611  1029  1549 E WifiScanningService: could not get scan capabilities
08-29 10:24:06.611  1029  1550 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.611  1029  1384 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 10:24:06.611  1029  1384 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 10:24:06.612  1029  1384 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 10:24:06.612  1029  1384 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 10:24:06.612  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=119126  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 10:24:06.613  1029  1383 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 10:24:06.613  1029  1383 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 10:24:06.613  1029  1383 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 10:24:06.614  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 10:24:06.614  1935  1935 D WfdsService: WifiP2pState is changed : true
08-,29 10:24:06.614  1029  1383 D WifiNative-p2p0: SET device_name G3: returned true
08-29 10:24:06.614  1029  1383 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 10:24:06.614  1029  1383 D LGWifiP2pService: before postfix = G3
08-29 10:24:06.614  1029  1383 D WifiServerServiceExt: postfix byte check : 2
08-29 10:24:06.614  1029  1383 D LGWifiP2pService: after postfix = G3
08-29 10:24:06.614  1029  1383 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 10:24:06.614  1935  2295 D WfdsService: Receive the WFDS_ENABLE Method
08-29 10:24:06.614  1935  2295 D WfdsService: Set the WFDS Monitor: true
08-29 10:24:06.614  1029  1383 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 10:24:06.614  1029  1383 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 10:24:06.614  1935  2295 D WfdsService: Connected to the supplicant for wfds
08-29 10:24:06.615  1935  2295 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 10:24:06.615  6402  6402 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 10:24:06.615  1935  1935 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 10:24:06.615  1935  1935 D WfdsService: isConnected: false
08-29 10:24:06.616  1029  1383 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 10:24:06.616  1935  2295 D WfdsService: selectPreferredScanChannel [36]
08-29 10:24:06.616  1029  1383 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 10:24:06.616  1935  2295 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 10:24:06.616  1029  1383 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true,
08-29 10:24:06.616  1029  1383 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 10:24:06.617  5047  5047 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 10:24:06.617  1029  1383 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 10:24:06.617  1029  1383 D WifiNative-HAL: p2pGetDeviceAddress
08-29 10:24:06.617  5047  5047 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-29 10:24:06.617  1029  1383 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,08-29 10:24:06.619  1029  1383 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 10:24:06.619  1029  1383 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 10:24:06.619  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=119132  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 10:24:06.619  1029  1383 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 10:24:06.619  1029  1383 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 10:24:06.619  1029  1384 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 10:24:06.620  1029  1383 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 10:24:06.620  1029  1384 E WifiStateMachine:  ConnectModeState what:132106 1 0
,08-29 10:24:06.620  1029  1383 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 10:24:06.620  1029  1384 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 10:24:06.620  1029  1384 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 10:24:06.620  1029  1383 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 10:24:06.620  6402  6402 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 10:24:06.620  1029  1383 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 10:24:06.621  1029  1383 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 10:24:06.621  1029  1383 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-29 10:24:06.621  5047  5047 V [BNRBootReceiver]: Boot Receiver Return
,08-29 10:24:06.623  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:06.623  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:06.623  4258  6429 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 10:24:06.625  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 10:24:06.625  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:06.625  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 10:24:06.625  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:06.626  1935  1935 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 10:24:06.627  1935  1935 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 10:24:06.627  1029  1383 D LGWifiP2pService: InactiveState
08-29 10:24:06.627  1935  1935 D WfdsService: Update P2p Interface State: 3
08-29 10:24:06.627  1029  1383 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.627  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.627  1029  1383 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 10:24:06.631  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:06.632  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 10:24:06.633  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:06.633  1029  6423 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 10:24:06.633  1029  6423 E WifiMonitor: WifiMonitor:p2p0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:06.633  1029  6423 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:06.633  1029  6423 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:06.634  6402  6402 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 10:24:06.634  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.634  1029  6423 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:06.634  1029  6423 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.634  1029  6423 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.634  1029  6423 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.635  4258  6430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 10:24:06.635  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.635  1029  6423 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:06.635  1029  6423 E WifiMonitor: WifiMonitor:p2p0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-29 10:24:06.635  1029  6423 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.635  1029  6423 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.635  1935  6427 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 10:24:06.635  1935  6427 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:06.635  4258  6430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 10:24:06.635  1935  6427 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:06.636  1029  1383 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 10:24:06.636  1029  1383 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.636  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.636  1029  1383 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.636  1029  1383 D LGWifiP2pService: InactiveState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.636  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.636  1029  1383 D LGWifiP2pService: DefaultState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.636  1029  1383 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.636  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.637  1029  1383 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.637  1029  1383 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.637  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.637  1029  1383 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.637  1029  1384 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 10:24:06.638  1029  1384 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 10:24:06.639  1029  1029 E WifiServerServiceExt: No p2p device connected
08-29 10:24:06.639  1029  1384 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 10:24:06.639  1029  1384 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 10:24:06.639  6402  6402 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 10:24:06.640  1029  1384 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 10:24:06.640  1029  1384 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 10:24:06.641  1029  1384 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 10:24:06.641  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 10:24:06.641  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 10:24:06.642  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:06.642  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 10:24:06.642  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:06.642  6314  6426 V FormManager: Network unavailable.
08-29 10:24:06.642  1029  6423 E W,ifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:06.642  1029  6423 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:06.643  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:06.643  6402  6402 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 10:24:06.643  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.643  1029  6423 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:06.643  1029  6423 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.643  1029  6423 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.643  1029  6423 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.643  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.643  1029  6423 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:06.643  1029  6423 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.644  1029  6423 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.644  1029  6423 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:06.644  6314  6426 V FormManager: Network unavailable.
08-29 10:24:06.644  1935  6427 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:06.644  1935  6427 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-29 10:24:06.648  1935  2295 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 10:24:06.648  1029  1384 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 10:24:06.649  1029  1384 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 10:24:06.649  1029  1383 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.649  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:06.649  1029  1384 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 10:24:06.650  1029  1384 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 10:24:06.650  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 10:24:06.650  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 10:24:06.650  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 10:24:06.650  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 10:24:06.650  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 10:24:06.650  1029  6423 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-29 10:24:06.650  1029  6423 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 10:24:06.651  1029  1384 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 10:24:06.651  1029  1384 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 10:24:06.651  1029  1384 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 10:24:06.651  1029  1384 D WifiNative-wlan0: doBoolean: SCAN
08-29 10:24:06.652  1029  1384 D WifiNative-wlan0: SCAN: returned false
08-29 10:24:06.652  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=119166  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 10:24:06.653  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:06.654  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=119167  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 10:24:06.654  1029  1384 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 10:24:06.655  1029  1384 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 10:24:06.655  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:06.655  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:06.655  1029  1384 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 10:24:06.656  1029  1384 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 10:24:06.656  1029  1384 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 10:24:06.656  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:06.657  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:06.657  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:06.657  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 10:24:06.659  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:06.659  1029  1029 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 10:24:06.660  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:06.660  1029  1029 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-29 10:24:06.662  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:06.662  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:06.663  6272  6272 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 10:24:06.666  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:06.671  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:06.675  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 10:24:06.679  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 10:24:06.679  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 10:24:06.680  6272  6272 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 10:24:07.217  6402  6402 E wpa_supplicant: USIM:  scard_init function
08-29 10:24:07.218  6402  6402 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-29 10:24:07.235  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 10:24:07.235  1029  6423 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 10:24:07.236  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 10:24:07.236  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
08-29 10:24:07.236  1029  6423 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 10:24:07.236  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 10:24:07.236  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 10:24:07.237  1029  1384 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 10:24:07.237  1029  1384 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 10:24:07.238  1029  1384 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 10:24:07.238  1029  1384 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 10:24:07.238  1029  1384 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 10:24:07.260  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=119773  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 10:24:07.267  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=119780  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 10:24:07.270  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:07.270  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:07.270  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 10:24:07.272  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:07.273  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 10:24:07.276  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:07.276  1029  1029 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 10:24:07.279  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:07.284  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-29 10:24:07.291  6209  6209 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 10:24:07.299  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 10:24:07.316  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:07.326  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:07.334  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:07.334  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 10:24:07.336  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:07.354  6402  6402 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 10:24:07.361  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 10:24:07.361  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 10:24:07.361  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 10:24:07.361  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 10:24:07.361  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 10:24:07.361  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 10:24:07.365  1029  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 10:24:07.368  6402  6402 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 10:24:07.368  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 10:24:07.373  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=119886  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-29 10:24:07.374  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=119887  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-29 10:24:07.379  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 10:24:07.379  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 10:24:07.379  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,08-29 10:24:07.380  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 10:24:07.380  1029  6423 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 10:24:07.380  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 10:24:07.380  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 10:24:07.387  1029  1384 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119900
,08-29 10:24:07.388  1029  1384 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119901
08-29 10:24:07.389  1029  6423 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 10:24:07.389  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-29 10:24:07.389  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-29 10:24:07.397  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 10:24:07.397  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 10:24:07.397  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 10:24:07.397  6209  6209 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 10:24:07.398  1029  1384 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119912
08-29 10:24:07.399  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119912
08-29 10:24:07.399  1029  1384 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119913
08-29 10:24:07.400  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=119913  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 10:24:07.401  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 10:24:07.402  6209  6209 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 10:24:07.402  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 10:24:07.402  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 10:24:07.402  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 10:24:07.402  6209  6209 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 10:24:07.402  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 10:24:07.402  6209  6209 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 10:24:07.404  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:07.404  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:07.404  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 10:24:07.406  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:07.406  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 10:24:07.409  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:07.411  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:07.412  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=119925  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 10:24:07.412  1029  1384 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:07.413  1029  1384 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:07.413  1029  1384 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:07.413  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:07.414  1029  1384 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:07.414  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:07.414  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:07.414  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 10:24:07.418  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:07.419  1029  1029 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 10:24:07.419  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=119932  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 10:24:07.419  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=119933  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 10:24:07.420  1029  1384 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=119933
08-29 10:24:07.420  1029  1384 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=119934
08-29 10:24:07.420  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:07.421  1029  1384 D WifiNative-wlan0: doString: [STATUS]
08-29 10:24:07.421  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 10:24:07.421  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-29 10:24:07.422  1029  1384 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-29 10:24:07.423  1029  1384 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 10:24:07.426  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:07.429  1029  1384 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 10:24:07.429  1029  1384 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 10:24:07.432  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:07.432  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:07.432  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 10:24:07.434  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:07.434  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:07.434  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 10:24:07.434  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:07.434  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 10:24:07.436  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:07.437  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:07.437  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:07.438  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:07.440  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:07.440  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:07.440  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:07.442  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:07.442  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:07.442  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:07.446  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:07.448  1029  1384 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 10:24:07.448  1029  1439 D ConnectivityService: Got NetworkAgent Messenger
08-29 10:24:07.448  1029  1384 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:24:07.448  1029  1384 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 10:24:07.449  1029  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 10:24:07.449  1029  1439 D ConnectivityService: NetworkAgent connected
08-29 10:24:07.450  1029  1384 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 10:24:07.450  1029  1384 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 10:24:07.455  1029  1384 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 10:24:07.456  1029  1384 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:24:07.456  1029  1384 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 10:24:07.456  1029  1384 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 10:24:07.456  1029  1384 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 10:24:07.457  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:07.459  1029  1384 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-29 10:24:07.461   330   887 D CommandListener: Setting iface cfg
08-29 10:24:07.463  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:07.466  1029  1384 E WifiStateMachine: Start Dhcp Watchdog 1
08-29 10:24:07.466  1029  6458 D DhcpStateMachine: StoppedState
08-29 10:24:07.466  1029  6458 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:07.466  1029  6458 D DhcpStateMachine: WaitBeforeStartState
08-29 10:24:07.466  1029  1384 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=119979  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:07.466  1029  1384 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=119980  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:07.467  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=119980  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:07.467  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:07.468  1029  1029 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 10:24:07.468  1029  1384 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=119981  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:07.468  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:07.468  1029  1029 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 10:24:07.468  1029  1384 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=119982  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:07.469  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=119982  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:07.470  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-714735058] from screen [on:0 period:-714735058]
08-29 10:24:07.471  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-714735057]
08-29 10:24:07.471  1029  1384 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 10:24:07.471  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:07.472  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 10:24:07.472  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:07.475  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:07.477  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:07.479  1029  1439 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
08-29 10:24:07.479  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:07.479  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:07.480  1029  1384 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:07.480  1029  1384 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:07.480  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:07.481  1029  1384 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:07.481  1029  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-29 10:24:07.482  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-29 10:24:07.482  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-29 10:24:07.482  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 10:24:07.483  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 10:24:07.483  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:07.483  1029  1384 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
,08-29 10:24:07.483  1029  1384 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 10:24:07.484  1029  1384 D WifiNative-wlan0: SET ps 0: returned true
08-29 10:24:07.484  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 10:24:07.484  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 10:24:07.485  1029  1384 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 10:24:07.485  1029  1384 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 10:24:07.485  1029  1383 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fc24ae3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:07.485  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fc24ae3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:07.485  1029  1384 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 10:24:07.485  1029  6458 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:07.485  1029  1384 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 10:24:07.485  1029  1384 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-29 10:24:07.485  1029  6458 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 10:24:07.486  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:07.487  1029  1029 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 10:24:07.488  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:07.492  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:07.493  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:07.493  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 10:24:07.496  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 10:24:07.502  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:07.507  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:07.511  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:07.512  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:07.512  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:07.572  1029  1383 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:07.573  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:07.573  1029  1383 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:24:07.583  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 10:24:07.585  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 10:24:07.586  1029  1384 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 10:24:07.587  1029  1384 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-29 10:24:07.590  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 10:24:07.591  1029  1384 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 10:24:07.689  1029  6458 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 10:24:07.691  1029  6458 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 10:24:07.691  1029  6458 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-29 10:24:07.704  6460  6460 W dhcpcd  : type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:07.704  6460  6460 W dhcpcd  : type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 10:24:07.741  6460  6460 I dhcpcd  : version 5.5.6 starting
,08-29 10:24:07.743  6460  6460 E dhcpcd  : get_duid: m
08-29 10:24:07.743  6460  6460 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 10:24:07.743  6460  6460 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 10:24:07.833  6460  6460 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 10:24:07.834  6460  6460 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 10:24:07.834  6460  6460 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-29 10:24:07.837  6460  6460 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-29 10:24:07.837  6460  6460 D dhcpcd  : wlan0: sending REQUEST (xid 0xfb6a4377), next in 3.96 seconds
08-29 10:24:07.860  6460  6460 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-29 10:24:07.865  6460  6460 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 10:24:07.865  6460  6460 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 10:24:07.868  6460  6460 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 10:24:07.868  6460  6460 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 10:24:07.869  6460  6460 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 10:24:07.869  6460  6460 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 10:24:07.870  6460  6460 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 10:24:07.870  6460  6460 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 10:24:07.870  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:07.872  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:07.874  1029  1384 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:07.875  1029  1384 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:07.877  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:07.878  1029  1384 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 10:24:07.882  1029  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,08-29 10:24:08.299  1029  6458 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-29 10:24:08.303  1029  6458 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-29 10:24:08.306  1029  6458 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 10:24:08.306  1029  6458 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,08-29 10:24:08.307  1029  6458 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 10:24:08.307  1029  6458 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 10:24:08.307  1029  6458 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true,
08-29 10:24:08.308  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 10:24:08.308  1029  6458 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-29 10:24:08.308  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-29 10:24:08.309  1029  1383 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.309  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.309  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-29 10:24:08.309  1029  6458 D DhcpStateMachine: RunningState
08-29 10:24:08.309  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 10:24:08.310  1029  1384 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-29 10:24:08.310  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 10:24:08.310  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 10:24:08.311  1029  1384 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,08-29 10:24:08.311  1029  1384 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 10:24:08.328  1029  1384 D WifiNative-wlan0: SET ps 1: returned true
08-29 10:24:08.331  1029  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,08-29 10:24:08.331  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 10:24:08.333  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 10:24:08.334  1029  1384 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-29 10:24:08.336  1029  1439 D ConnectivityService: ignoring duplicate network state non-change
,08-29 10:24:08.344  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.344  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.355  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-29 10:24:08.361  1029  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 10:24:08.363  1029  1439 D ConnectivityService: Adding iface wlan0 to network 100
08-29 10:24:08.365  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.365  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.365  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 10:24:08.368  1029  1384 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 10:24:08.371  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-29 10:24:08.377  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.377  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.377  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 10:24:08.380  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 10:24:08.381  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:08.381  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:08.392  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.393  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.393  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 10:24:08.396  1935  1935 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-29 10:24:08.405  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.409  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:08.409  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 10:24:08.411  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.414  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:08.417  1029  1439 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 10:24:08.418  1029  1439 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-29 10:24:08.419  1029  1439 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-29 10:24:08.420  1595  1595 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,08-29 10:24:08.421  1029  1439 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-29 10:24:08.421  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.422  1029  1439 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 10:24:08.422  1029  1439 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-29 10:24:08.422  1029  1439 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-29 10:24:08.425  1029  1439 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 10:24:08.425  1029  1439 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 10:24:08.425  1029  1439 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-29 10:24:08.426  1029  6457 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.426  1029  6457 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 10:24:08.426  1029  6457 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.427  1029  6457 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 10:24:08.432   330  6497 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 10:24:08.432  1029  1439 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-29 10:24:08.433  1029  1439 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:24:08.433  1029  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:08.433  1029  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 10:24:08.433  1029  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.433  1029  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 10:24:08.433  1029  1439 D ConnectivityService: currentScore = 0, newScore = 20
08-29 10:24:08.434  1029  1439 D ConnectivityService:    accepting network in place of null
08-29 10:24:08.434  1029  1439 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 10:24:08.435  1029  1384 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.436  1029  1439 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-29 10:24:08.441  1029  1439 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 10:24:08.441  1029  1439 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 10:24:08.442  1029  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 10:24:08.445  1029  1029 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 10:24:08.446  1029  1439 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:08.446  1029  1439 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
,08-29 10:24:08.451  1029  1384 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:24:08.452  1846  1846 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.453  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 10:24:08.453  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 10:24:08.453  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 10:24:08.453  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 10:24:08.453  1029  1029 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-29 10:24:08.454  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:08.455  1595  1595 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 10:24:08.456  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.458  1029  1439 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 10:24:08.459   330  6507 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-29 10:24:08.460   330  6507 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-29 10:24:08.462   330  6507 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
08-29 10:24:08.465  1029  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 10:24:08.466  1029  1439 D ConnectivityService: validation of new default Network = false
08-29 10:24:08.466   330  6509 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 10:24:08.467  1029  1439 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 10:24:08.467   330  6509 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-29 10:24:08.467  1029  1439 D DSQN    : enableDataServiceNotify 
08-29 10:24:08.467  1029  1439 D DSQN    : start dsqn bin
,08-29 10:24:08.478  1029  1439 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-29 10:24:08.478  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.479  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:08.479  1029  1439 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 10:24:08.480  1595  1823 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 10:24:08.485  1029  1382 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 10:24:08.474  6511  6511 W dsqn    : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:08.474  6511  6511 W dsqn    : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 10:24:08.492  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:08.493   330  6497 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-29 10:24:08.507  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 10:24:08.507  6511  6511 E DSQN    : DSQN ssw
08-29 10:24:08.509  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.509  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.516  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:08.517   330  6509 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
,08-29 10:24:08.521  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 10:24:08.525   330  6497 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-29 10:24:08.530  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:08.530  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 10:24:08.536  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:08.538  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:08.545  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:08.549  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:08.554  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:08.554  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:08.555  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:08.559  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 10:24:08.562  6226  6226 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 10:24:08.565   330   886 D LGDataListener: argv[0]=dsqncommand
08-29 10:24:08.565   330   886 D LGDataListener: argv[1]=wlan0
08-29 10:24:08.565   330   886 D LGDataListener: argv[2]=1
08-29 10:24:08.565   330   886 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-29 10:24:08.566  1029  1109 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 10:24:08.566  1029  1109 D DSQN    : start to monitor internet connection
08-29 10:24:08.567  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 10:24:08.570  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:08.570  1029  6506 D LocSvc_java: NTP server : europe.pool.ntp.org
,08-29 10:24:08.571  1029  6506 D LocSvc_java: NTP server returned: 1472459048634 (Mon Aug 29 10:24:08 GMT+02:00 2016) reference: 121083 certainty: 25 system time offset: 64
08-29 10:24:08.571  1029  6506 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
08-29 10:24:08.575  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:08.580  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:08.581  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:08.582  6272  6272 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 10:24:08.583  6272  6272 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-29 10:24:08.583  6272  6272 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 10:24:08.586  1029  1384 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:08.586  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:08.586  1029  1384 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:08.587  1029  1384 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:08.587  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:08.587  1029  1384 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:08.588  1029  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
08-29 10:24:08.588  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:08.588  1029  1439 D ConnectivityService: identical MTU - not setting
08-29 10:24:08.588  1029  1439 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 10:24:08.588  1029  1439 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 10:24:08.589  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.589  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:08.589  1029  1439 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:08.590  1595  1823 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 10:24:08.593  6226  6226 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 10:24:08.594  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 10:24:08.597  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:08.601  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:08.607  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:08.608  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:08.609  6272  6272 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-29 10:24:08.611  6272  6272 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 10:24:08.612  6272  6272 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-29 10:24:08.618  1029  6457 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 08:24:08 GMT], X-Android-Received-Millis=[1472459048617], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472459048564]}
08-29 10:24:08.619  1029  6457 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 10:24:08.619  1029  6457 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-29 10:24:08.620  1029  1439 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
08-29 10:24:08.620  1029  1439 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-29 10:24:08.620  1029  1439 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:24:08.620  1029  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:08.620  1029  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 10:24:08.620  1029  1439 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
08-29 10:24:08.620  1029  1439 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-29 10:24:08.620  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.620  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:08.621  1029  1439 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:08.621  1029  1439 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.621  1595  1823 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 10:24:08.621  1029  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 10:24:08.622  1846  1846 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.622  1029  1384 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.622  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 10:24:08.622  1029  1384 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 10:24:08.641  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-29 10:24:08.641  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 10:24:08.642  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.665  1029  2025 D WifiServiceImplEx: setWifiEnabled: false pid=5976, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 10:24:08.665  1029  2025 D WifiService: setWifiEnabled: false pid=5976, uid=10118
08-29 10:24:08.665  1029  2025 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:24:08.686  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 10:24:08.686  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 10:24:08.687  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-29 10:24:08.688  1029  1384 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 10:24:08.689  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 10:24:08.690  1029  1384 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 10:24:08.691  1029  1384 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 10:24:08.692  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 10:24:08.693  1029  1384 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 10:24:08.693  1029  1384 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:24:08.693  1029  1384 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 10:24:08.693  1029  1384 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 10:24:08.693  1029  1384 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 10:24:08.707  1029  1384 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 10:24:08.708  1029  1383 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.708  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.708  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 10:24:08.708  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 10:24:08.708  1029  1384 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 10:24:08.708  1029  1384 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 10:24:08.709  1029  1384 D WifiNative-wlan0: SET ps 1: returned true
08-29 10:24:08.709   330   887 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:24:08.709  1029  6458 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.751  1029  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 10:24:08.751  1029  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-29 10:24:08.754  1029  1029 D WifiHS20: hidePasspointNotification off =false
,08-29 10:24:08.756  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:08.756  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:08.757  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.757  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.757  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 10:24:08.758  1029  1029 D WifiHS20: hidePasspointNotification off =false
08-29 10:24:08.759  1935  1935 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 10:24:08.759  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.763  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.764  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.764  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-29 10:24:08.773  1029  1383 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.773  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.773  1029  1383 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@12480891
08-29 10:24:08.773  1029  1384 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:08.773  1029  1383 D LGWifiP2pService: P2pDisablingState
08-29 10:24:08.773  1029  1383 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.773  1029  1383 D LGWifiP2pService: p2p socket connection lost
08-29 10:24:08.773  1029  1383 D LGWifiP2pService: P2pDisabledState
08-29 10:24:08.773  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:08.774  1029  1384 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:08.775  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 10:24:08.775  1029  1549 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.775  1029  1029 D RttService: SCAN_AVAILABLE : 1
08-29 10:24:08.775  1029  1550 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.777  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 10:24:08.777  1935  1935 D WfdsService: WifiP2pState is changed : false
08-29 10:24:08.777  1935  2295 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 10:24:08.778  1935  2295 D WfdsService: Set the WFDS Monitor: false
08-29 10:24:08.778  1935  2295 D WfdsMonitor: WFDS Monitor is stopped
08-29 10:24:08.779  1935  2295 D WfdsService: STATE : WfdsDisabledState - enter
08-29 10:24:08.779  1935  2297 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 10:24:08.779  1029  1384 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:08.779  1935  6427 D CtrlSupplicant: Received on exit socket, terminate
08-29 10:24:08.779  1935  6427 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 10:24:08.779  1935  6427 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 10:24:08.779  1935  6427 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 10:24:08.779  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:08.780  1029  1384 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:08.780  1935  2295 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 10:24:08.781  1029  1384 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 10:24:08.781  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:08.781  1029  1384 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-29 10:24:08.782  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:08.782  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:08.784  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.785  1029  1383 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.785  1029  1383 D LGWifiP2pService: DefaultState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.785  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 10:24:08.786  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 10:24:08.787  1029  1384 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 10:24:08.787  1029  1384 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 10:24:08.787  1029  1384 D WifiNative-wlan0: SET ps 1: returned true
08-29 10:24:08.789  6226  6226 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 10:24:08.789  6226  6226 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 10:24:08.789  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 10:24:08.793  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:08.799  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:08.807  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:08.807  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 10:24:08.809  6272  6272 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 10:24:08.811  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:08.816  6226  6226 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 10:24:08.816  6226  6226 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 10:24:08.816  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 10:24:08.820  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:08.821   330   887 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:24:08.822  1029  1439 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 10:24:08.822  1029  1439 D DSQN    : disableDataServiceNotify
08-29 10:24:08.822  1029  1439 D DSQN    : stop dsqn bin
08-29 10:24:08.824  1029  1384 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 10:24:08.825  1029  1029 D WifiHS20: hidePasspointNotification off =false
08-29 10:24:08.825  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 10:24:08.825  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:08.825  1029  1384 D WifiNative-p2p0: TERMINATE: returned true
08-29 10:24:08.825  1029  1384 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 10:24:08.825  1029  1384 E WifiStateMachine: useWiFiOffloading() : false
08-29 10:24:08.825  1029  1384 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 10:24:08.826  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.826  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.826  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 10:24:08.827  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.828  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 10:24:08.828  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 10:24:08.829  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.829  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:08.829  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:08.829  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:08.829  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:08.829  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:08.829  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:08.829  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:08.829  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:08.829  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:08.829  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:24:08.829  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:08.829  5976  5976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:08.830  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:08.831  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:08.831  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:08.831  5976  5976 V io.jxcore.node.Con,nectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:08.831  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:08.831  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:08.831  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:08.831  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:08.831  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:24:08.831  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:08.831  5976  5976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:08.831  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:08.831  1029  1029 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 10:24:08.835  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:08.835  1029  1439 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 10:24:08.836  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.836  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:08.836  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:08.836  1029  1439 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:08.836  1029  1439 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 10:24:08.836  1029  6457 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.836  1029  6457 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:08.836  1029  6457 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 10:24:08.836  1595  1823 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 10:24:08.837  1029  1439 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 10:24:08.837  1029  1439 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 10:24:08.838  1029  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 10:24:08.838  1029  1439 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:08.838  1029  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 10:24:08.839  1029  1382 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-29 10:24:08.840  1029  1439 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:08.840  1029  1029 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 10:24:08.840  1029  1439 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.840  1029  1439 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.840  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 10:24:08.840  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 10:24:08.840  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 10:24:08.840  1029  1439 D NetworkManagementService: Removing idletimer
08-29 10:24:08.840  1029  1384 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.840  1029  1384 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:24:08.841  1029  1382 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 10:24:08.842  1029  1439 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:08.842  1029  1029 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 10:24:08.842  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 10:24:08.842  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 10:24:08.842  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 10:24:08.842  1846  1846 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:08.842  1029  1439 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 10:24:08.842  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 10:24:08.843  6272  6272 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 10:24:08.847  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:08.851  6226  6226 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 10:24:08.851  6226  6226 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 10:24:08.851  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 10:24:08.856  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:08.863  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:08.865  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 10:24:08.866  6402  6402 I wpa_supplicant: monitor socket send errors count : 1
08-29 10:24:08.866  6402  6402 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1935-4\x00 that cannot receive messages
08-29 10:24:08.866  1029  6423 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 10:24:08.866  1029  6423 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-29 10:24:08.872  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:08.872  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:08.874  6272  6272 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 10:24:08.884  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 10:24:08.892  6314  6525 W FormManager: Network not available. Please check & try again.
08-29 10:24:08.896  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 10:24:08.897  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 10:24:08.898  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 10:24:08.899  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 10:24:08.899  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 10:24:08.899  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 10:24:08.899  1029  6423 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 10:24:08.899  1029  6423 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 10:24:08.900  6402  6402 W wpa_supplicant: USIM:  scard_deinit function
08-29 10:24:08.900  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 10:24:08.900  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 10:24:08.900  1029  1111 D Tethering: InitialState.processMessage what=4
08-29 10:24:08.901  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 10:24:08.901  1029  1384 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121414
08-29 10:24:08.901  1029  1384 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121415
08-29 10:24:08.902  1029  1384 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=121415  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 10:24:08.902  1029  1384 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=121416  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 10:24:08.904  1029  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 10:24:08.907  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:08.909  1029  1384 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
,08-29 10:24:08.909  1029  1384 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 10:24:08.914  6314  6526 V FormManager: Network unavailable.
08-29 10:24:08.917  6314  6526 V FormManager: Network unavailable.
08-29 10:24:08.927  1029  6458 D DhcpStateMachine: StoppedState
08-29 10:24:08.928  1029  6458 D DhcpStateMachine: StoppedState{ when=-140ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:24:08.931  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-29 10:24:08.931  1029  1384 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 10:24:08.931  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 10:24:08.931  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 10:24:08.931  6209  6209 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 10:24:08.931  1029  1384 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 10:24:08.932  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 10:24:08.933  6209  6209 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 10:24:08.933  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 10:24:08.933  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 10:24:08.933  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 10:24:08.933  6209  6209 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 10:24:08.933  6209  6209 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 10:24:08.941  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-29 10:24:08.942  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.943  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:08.956  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 10:24:08.957  1029  6423 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 10:24:08.957  1029  6423 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 10:24:08.957  1029  6423 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-29 10:24:08.957  1029  1384 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 37 0
,08-29 10:24:09.059  1029  1384 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 10:24:09.060  1029  1384 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 10:24:09.060  1029  1384 E WifiStateMachine: useWiFiOffloading() : false
08-29 10:24:09.060  1029  1384 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-29 10:24:09.066  1935  1935 D WfdsService: Supplicant Connection state is changed : false
08-29 10:24:09.068  1935  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 10:24:09.068  1935  2295 D WfdsService: Set the WFDS Monitor: false
08-29 10:24:09.068  1935  2295 D WfdsMonitor: WFDS Monitor is stopped
08-29 10:24:09.068  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 10:24:09.069  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:09.071  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:09.075  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:09.075  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:09.075  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:09.075  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:09.075  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:09.075  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:09.075  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:09.075  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:09.075  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:09.076  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:09.076  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:09.076  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:09.076  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:09.076  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:09.076  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:09.076  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:09.076  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:09.076  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:09.080  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 10:24:09.081  1029  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
,08-29 10:24:09.081  1029  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 10:24:09.084  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 10:24:09.084  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 10:24:09.086  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 10:24:09.088  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 10:24:09.096  4258  6527 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 10:24:09.101  4258  6528 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-29 10:24:09.101  4258  6528 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 10:24:09.102  6226  6226 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 10:24:09.102  6226  6226 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 10:24:09.102  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 10:24:09.107  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 10:24:09.110  6314  6530 W FormManager: Network not available. Please check & try again.
,08-29 10:24:09.112  6314  6531 V FormManager: Network unavailable.
,08-29 10:24:09.114  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:09.119  6314  6531 V FormManager: Network unavailable.
08-29 10:24:09.350  6142  6382 D UEI.SmartControl: Internal timer expired: 2
08-29 10:24:09.350  6142  6382 D UEI.SmartControl: unbind internal service
,08-29 10:24:09.538  6142  6379 D serial_port: close(fd = 24)
,08-29 10:24:09.549  6142  6379 I UEI.SmartControl: Serial port is closed.
,08-29 10:24:10.482  1029  1384 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-714732046] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-29 10:24:10.484  1029  1384 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-714732044] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-29 10:24:11.448  1029  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:11.460  1029  1111 D Tethering: MasterInitialState.processMessage what=3
08-29 10:24:11.463  1029  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:11.482  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:11.488  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:11.495  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 10:24:11.500  3731  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 10:24:11.512  5325  5325 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 10:24:11.582  1029  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 10:24:11.599  2265  2265 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:11.690  1029  2025 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6558 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-29 10:24:11.692  1029  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 10:24:11.692  1029  1952 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-29 10:24:11.698  1029  1093 E GpsLocationProvider: No APN found to select.
08-29 10:24:11.699  1810  6541 I CheckinService: active receiver: enabled
08-29 10:24:11.705   358   358 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 461us total 20.863ms
,08-29 10:24:11.711  1029  1111 D BluetoothManagerService: Message: 1
08-29 10:24:11.711  1029  1111 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 10:24:11.712  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 10:24:11.712  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 10:24:11.712  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-29 10:24:11.724  1029  1111 D BluetoothManagerService: Message: 20
08-29 10:24:11.724  1029  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f7e4c2:true
08-29 10:24:11.725  6358  6358 D BluetoothAdapterState: make
,08-29 10:24:11.728  6358  6358 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 10:24:11.728  6358  6358 I bluedroid-qcom: init
08-29 10:24:11.729  6358  6577 I BluetoothAdapterState: Entering OffState
08-29 10:24:11.729  6358  6358 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 10:24:11.729  6358  6358 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 10:24:11.729  6358  6358 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 10:24:11.729  6358  6358 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 10:24:11.729  6358  6358 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 10:24:11.730  6358  6358 I bluedroid-qcom: get_profile_interface socket
08-29 10:24:11.730  6358  6580 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 10:24:11.730  6358  6358 I bluedroid-qcom: get_profile_interface map_client
08-29 10:24:11.714  6581  6581 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:11.714  6581  6581 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:11.732  6358  6580 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 10:24:11.733  6358  6580 D BluetoothAdapterProperties: Name is: G3
08-29 10:24:11.733  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 10:24:11.733  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 10:24:11.736  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 10:24:11.737  1029  1111 D BluetoothManagerService: Message: 40
08-29 10:24:11.737  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 10:24:11.737  6358  6373 I bluedroid-qcom: config_hci_snoop_log
08-29 10:24:11.737  6581  6581 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 10:24:11.737  6581  6581 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 10:24:11.737  6581  6581 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-29 10:24:11.738  1029  1111 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 10:24:11.738  1029  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 10:24:11.742  6581  6581 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 10:24:11.743  6358  6577 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 10:24:11.744  6358  6577 D BluetoothAdapterProperties: Setting state to 11
08-29 10:24:11.744  6358  6577 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 10:24:11.744  1029  1111 D BluetoothManagerService: Message: 60
08-29 10:24:11.744  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 10:24:11.744  1029  1111 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 10:24:11.745  6358  6577 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 10:24:11.747   358   358 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.372ms total 40.655ms
08-29 10:24:11.747  6209  6209 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-29 10:24:11.748  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:11.748  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 10:24:11.749  6581  6581 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 10:24:11.749  6581  6581 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 10:24:11.751  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:11.752  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:11.753  6358  6358 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 10:24:11.754  6358  6358 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:11.754  6358  6358 V BluetoothPbapReceiver: ***********state = 11
08-29 10:24:11.756  2265  2265 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:24:11.757  6358  6577 D BluetoothBondStateMachine: make
08-29 10:24:11.759  6358  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:11.759  6358  6577 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 10:24:11.759  6358  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:11.759  6358  6577 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 10:24:11.760  6358  6577 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 10:24:11.761  6358  6585 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 10:24:11.762  6358  6577 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:11.764  6209  6209 D BluetoothPermissionRequest: onReceive
08-29 10:24:11.767   358   358 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 19.314ms
,08-29 10:24:11.769  6358  6577 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:11.770  6209  6209 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 10:24:11.770  6358  6358 D HeadsetService: Received start request. Starting profile...
08-29 10:24:11.771  6358  6358 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 10:24:11.771  6358  6358 D LGBluetoothHfpAdapter: Version 1.6
08-29 10:24:11.773  6358  6358 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 10:24:11.774  6358  6358 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 10:24:11.774  6358  6358 D HeadsetStateMachine: make
08-29 10:24:11.776  6358  6577 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:11.780  6358  6577 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 10:24:11.784  6358  6577 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:11.788  6358  6577 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:11.792  6358  6577 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:11.794  6558  6558 I AppUp4:AppBoxCP: onCreate
,08-29 10:24:11.795  6558  6558 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-29 10:24:11.798  6358  6358 D LgDataFeature: LgDataFeature() Constructor: none
08-29 10:24:11.799  6358  6358 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 10:24:11.802  6358  6358 D HeadsetStateMachine: max_hf_connections = 1
08-29 10:24:11.802  6358  6358 I bluedroid-qcom: get_profile_interface handsfree
08-29 10:24:11.803  6358  6358 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 10:24:11.804   336   336 V AudioPolicyService: registerClient() client 0xb558a280, uid 1002
08-29 10:24:11.804   336  2183 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 10:24:11.804   336  2183 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 10:24:11.804   336  2183 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 10:24:11.804  6558  6558 I AppUp4:DB:  setFingerPrint start
08-29 10:24:11.804  6358  6358 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 10:24:11.804  6558  6558 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 10:24:11.804   336  1391 V AudioFlinger: registerClient() client 0xb55815e0, pid 6358
08-29 10:24:11.805   336  1385 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:11.805   336  1385 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 10:24:11.805  1029  1724 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:11.805  6358  6358 V ToneGenerator: Create Track: 0xb4928080
08-29 10:24:11.805  1029  1724 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 10:24:11.805  6358  6358 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 10:24:11.805  6358  6358 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 10:24:11.805   336   336 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 10:24:11.805   336   336 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 10:24:11.805   336   336 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 10:24:11.805   336  1386 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:11.805   336  1386 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 10:24:11.805  2165  2184 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:11.805  2165  2184 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 10:24:11.805  6358  6577 V LGMDMManager: Create singleton instance
08-29 10:24:11.805   336   336 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 10:24:11.805  2165  2184 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:11.805  2165  2184 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 10:24:11.805  6358  6358 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-29 10:24:11.806  6358  6583 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:11.806  6358  6583 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 10:24:11.806  6358  6583 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:11.806  6358  6583 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 10:24:11.807  1029  1971 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:11.807  1029  1971 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 10:24:11.807  1846  1861 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:11.807  1846  1861 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 10:24:11.807  1846  1861 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:11.807  1846  1861 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 10:24:11.807  1595  2102 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:11.807  1595  2102 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 10:24:11.807  1595  2102 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:11.807  1595  2102 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 10:24:11.807   336  1391 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 10:24:11.807   336  1390 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 10:24:11.807   336  1390 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 10:24:11.807   336  1390 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 10:24:11.807   336  1390 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 10:24:11.808  6358  6358 V AudioSystem: getLatency() output 2, latency 50
08-29 10:24:11.808  6358  6358 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 10:24:11.808  6358  6358 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 10:24:11.808   336  2180 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 10:24:11.808   336  2180 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
,08-29 10:24:11.808   336  2180 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 10:24:11.808   336  2180 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 10:24:11.808   336  2180 V AudioFlinger: createTrack() lSessionId: 20
08-29 10:24:11.809  6358  6358 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 10:24:11.809  3411  3431 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:11.809  3411  3431 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 10:24:11.809  3411  3431 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:11.809  3411  3431 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 10:24:11.809   336   336 V AudioFlinger: acquiring 20 from 6358, for 6358
08-29 10:24:11.809   336   336 V AudioFlinger:  added new entry for 20
08-29 10:24:11.809  6358  6358 V ToneGenerator: ToneGenerator INIT OK, time: 124334
08-29 10:24:11.809  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:11.810  6358  6587 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 10:24:11.810  6358  6587 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 10:24:11.810  6358  6587 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 10:24:11.810  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:11.810  6358  6587 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 10:24:11.811  6358  6358 D A2dpService: Received start request. Starting profile...
08-29 10:24:11.811   336  2183 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6358
08-29 10:24:11.811   336  2183 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 10:24:11.812   336  2183 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 10:24:11.812   336  2183 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 10:24:11.812   336  2183 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 10:24:11.812   336  2183 V voice   : voice_set_parameters: exit with code(0)
08-29 10:24:11.812   336  2183 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 10:24:11.812   336  2183 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 10:24:11.812  6358  6358 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 10:24:11.812   336  2183 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 10:24:11.812   336  2183 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 10:24:11.812   336  2183 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 10:24:11.812   336  2183 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 10:24:11.812  6358  6587 V ToneGenerator: ToneGenerator destructor
08-29 10:24:11.812  6358  6587 V ToneGenerator: stopTone
08-29 10:24:11.812  6358  6587 V ToneGenerator: Delete Track: 0xb4928080
08-29 10:24:11.812  6358  6587 V AudioTrack: ~AudioTrack, releasing session id from 6358 on behalf of 6358
08-29 10:24:11.812   336  1390 V AudioFlinger: releasing 20 from 6358 for 6358
08-29 10:24:11.812   336  1390 V AudioFlinger:  decremented refcount to 0
08-29 10:24:11.812   336  1390 V AudioFlinger: purging stale effects
08-29 10:24:11.812  6358  6358 V Avrcp   : make
08-29 10:24:11.812   336  1390 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 10:24:11.812   336  1390 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 10:24:11.812   336  1266 V AudioPolicyService: AudioCommandThread() waking up
08-29 10:24:11.812   336  1266 V AudioPolicyService: AudioCommandThread() processing release output 2
08-,29 10:24:11.812   336  1266 V AudioPolicyManager: releaseOutput() 2
08-29 10:24:11.812   336  1266 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 10:24:11.812   336  1390 V AudioFlinger: PlaybackThread::Track destructor
08-29 10:24:11.812   336  1390 V AudioFlinger: removeClient_l() pid 6358, calling pid 336
08-29 10:24:11.813  6358  6358 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 10:24:11.813  6358  6358 I bluedroid-qcom: get_profile_interface avrcp
08-29 10:24:11.813  6358  6577 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 10:24:11.815  6558  6558 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 10:24:11.815  6558  6558 I AppUp4:DB:  SDK version = 21
08-29 10:24:11.815  6558  6558 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-29 10:24:11.816  1029  1044 W Process : Unable to open /proc/6588/status
08-29 10:24:11.816  6558  6558 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-29 10:24:11.817  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 10:24:11.818  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:11.819  6358  6358 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 10:24:11.819  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 10:24:11.820  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-29 10:24:11.825  6358  6358 E AudioManager: No RCC entry present to update
08-29 10:24:11.825  6358  6358 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 10:24:11.826  6558  6558 I AppUp4:CustModeStarterReceiver: onReceive
08-29 10:24:11.828  6358  6358 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 10:24:11.829  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 10:24:11.829  6358  6358 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 10:24:11.831  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-29 10:24:11.844  1029  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:11.854  6558  6558 D LgDataFeature: LgDataFeature() Constructor: none
08-29 10:24:11.854  6558  6558 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 10:24:11.859  6558  6558 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@99b837b
08-29 10:24:11.859  6558  6558 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 10:24:11.860  6558  6558 D AppUp4:CustFacade: isPhone : true
08-29 10:24:11.882  6558  6558 D AppUp4:CustModeStarterReceiver: begin check event
,08-29 10:24:11.883  1029  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:11.885  1029  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:11.885  1029  1111 D Tethering: MasterInitialState.processMessage what=3
08-29 10:24:11.890  6558  6558 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-29 10:24:11.893  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:11.895  1029  1111 D Tethering: MasterInitialState.processMessage what=3
08-29 10:24:11.896  6558  6558 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-29 10:24:11.898  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:11.905  5325  5325 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 10:24:11.905  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:11.907  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:11.908  1029  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:11.908  5325  5325 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 10:24:11.909  1029  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:11.910  1029  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 10:24:11.915  6558  6590 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-29 10:24:11.915  6558  6590 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-29 10:24:11.916  6558  6590 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-29 10:24:11.919  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:11.919  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 10:24:11.921  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 10:24:11.923  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 10:24:11.928  4258  6593 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 10:24:11.932  4258  6594 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:11.932  4258  6594 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 10:24:11.946  1029  2025 V SIM_STK : Menu title from STK is T-Mobile
08-29 10:24:11.946  1029  2025 V SIM_STK : Menu title from STK is T-Mobile
,08-29 10:24:11.973  1029  1724 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6595 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 10:24:12.033  1029  1045 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 10:24:12.042  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 10:24:12.046  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 10:24:12.047  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 10:24:12.047  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 10:24:12.047  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 10:24:12.047  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 10:24:12.047  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 10:24:12.047  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 10:24:12.047  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 10:24:12.047  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 10:24:12.047  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 10:24:12.047  6358  6358 I BluetoothA2dpServiceJni: classInitNative
08-29 10:24:12.048  6358  6358 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 10:24:12.048  6358  6358 D A2dpStateMachine: make
,08-29 10:24:12.050  6358  6358 I bluedroid-qcom: get_profile_interface a2dp
08-29 10:24:12.050  6358  6613 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 10:24:12.053  6358  6358 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 10:24:12.053  6358  6358 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 10:24:12.054  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:12.056  6358  6358 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 10:24:12.056  6358  6612 D A2dpStateMachine: Enter Disconnected: -2
08-29 10:24:12.058  6358  6358 D HidService: Received start request. Starting profile...
08-29 10:24:12.058  6358  6358 I bluedroid-qcom: get_profile_interface hidhost
08-29 10:24:12.058  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:12.059  6358  6358 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 10:24:12.060  6358  6358 D HealthService: Received start request. Starting profile...
,08-29 10:24:12.062  6358  6358 I bluedroid-qcom: get_profile_interface health
08-29 10:24:12.062  6358  6358 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 10:24:12.062  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:12.063  6358  6358 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 10:24:12.065  6358  6358 D PanService: Received start request. Starting profile...
08-29 10:24:12.065  6358  6358 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 10:24:12.065  6358  6358 I bluedroid-qcom: get_profile_interface pan
08-29 10:24:12.067  6595  6595 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 10:24:12.067  6595  6595 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 10:24:12.068  6595  6595 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 10:24:12.069  6595  6595 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 10:24:12.075  6358  6358 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-29 10:24:12.075  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:12.078  6358  6358 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 10:24:12.087  6358  6358 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 10:24:12.087  6358  6358 D BtGatt.GattService: Received start request. Starting profile...
08-29 10:24:12.087  6358  6358 D BtGatt.GattService: start()
08-29 10:24:12.087  6358  6358 I bluedroid-qcom: get_profile_interface gatt
08-29 10:24:12.088  6358  6358 D BtGatt.AdvertiseManager: advertise manager created
08-29 10:24:12.093  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:12.095  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:12.095  6358  6358 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 10:24:12.096  6358  6358 V BluetoothMapService: BluetoothMapBinder()
08-29 10:24:12.097  6358  6358 D BluetoothMapService: Received start request. Starting profile...
08-29 10:24:12.097  6358  6358 D BluetoothMapService: start()
08-29 10:24:12.099  6358  6358 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 10:24:12.100  6358  6358 D BluetoothMapEmailAppObserver: createReceiver()
08-29 10:24:12.101  6358  6358 D BluetoothMapEmailAppObserver: initObservers()
08-29 10:24:12.101  6358  6358 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-29 10:24:12.113  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
,08-29 10:24:12.113  6358  6358 D HeadsetStateMachine: Proxy object connected
08-29 10:24:12.114  6358  6358 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-29 10:24:12.115  6358  6358 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 10:24:12.120  6358  6358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 10:24:12.120  6358  6587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 10:24:12.121  6358  6587 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 10:24:12.121  6358  6587 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 10:24:12.122  6358  6358 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:12.127  6595  6595 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-29 10:24:12.127  6358  6358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 10:24:12.130  6358  6358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 10:24:12.133  6358  6358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 10:24:12.133  6358  6358 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 10:24:12.135  6358  6358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 10:24:12.138  6358  6358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 10:24:12.138  6358  6358 V BluetoothMapService: Handler(): got msg=1
08-29 10:24:12.138  6358  6358 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 10:24:12.138  6358  6358 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 10:24:12.138  6358  6358 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 10:24:12.139  6358  6358 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:12.139  6358  6358 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-29 10:24:12.139  6358  6577 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 10:24:12.139  6358  6577 I bluedroid-qcom: enable
08-29 10:24:12.139  6358  6577 I bt_hci_bdroid: init
08-29 10:24:12.140  6358  6621 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 10:24:12.141  6358  6577 I bt_vendor: bt-vendor : init
08-29 10:24:12.141  6358  6577 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 10:24:12.141  6358  6577 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 10:24:12.141  6358  6577 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 10:24:12.141  6358  6577 D bt_userial_mct: userial_init
08-29 10:24:12.141  6358  6621 I bt-btu  : btu_task pending for preload complete event
08-29 10:24:12.142  6358  6577 D bt_hci_bdroid: set_power 1
08-29 10:24:12.142  6358  6577 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 10:24:12.142  6358  6577 I bt_vendor: Starting hciattach daemon
08-29 10:24:12.142  6358  6577 I bt_vendor: try to set true
08-29 10:24:12.144  6595  6595 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-29 10:24:12.134  6624  6624 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:12.134  6624  6624 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:12.163  6626  6626 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 10:24:12.181  6595  6595 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 10:24:12.217  6595  6595 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 10:24:12.218  6595  6595 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 10:24:12.236  6635  6635 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 10:24:12.248  6637  6637 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 10:24:12.271  6639  6639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 10:24:12.281  6640  6640 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-29 10:24:12.292  6643  6643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 10:24:12.304  6644  6644 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 10:24:12.324  6646  6646 I libmdmdetect: ESOC framework not supported
08-29 10:24:12.325  6646  6646 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-29 10:24:12.334  6646  6646 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-29 10:24:12.334  6646  6646 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 10:24:12.334  6646  6646 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 10:24:12.334  6646  6646 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-29 10:24:12.334  6646  6646 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 10:24:12.334  6646  6646 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 10:24:12.334  6646  6646 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 10:24:12.362  6595  6595 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 10:24:12.369  6646  6647 E QC-QMI  : qmi_client [6646] 14: failed to locate client data
08-29 10:24:12.371   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-29 10:24:12.371   467   467 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-29 10:24:12.395  6595  6595 I HubEmail: JNI_OnLoad()
08-29 10:24:12.395  6595  6595 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 10:24:12.395  6595  6595 I HubEmail: registerNatives()
08-29 10:24:12.395  6595  6595 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 10:24:12.396  6595  6595 I HubEmail: registerNativeMethods()
08-29 10:24:12.396  6595  6595 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 10:24:12.396  6595  6595 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-29 10:24:12.413  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 10:24:12.414  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:12.419  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = true
08-29 10:24:12.419  3411  3411 D PhoneState: setPdpRejectCasuse : false
08-29 10:24:12.420  6653  6653 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 10:24:12.422  6595  6649 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 10:24:12.432  6654  6654 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 10:24:12.472  1029  2026 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6656 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-29 10:24:12.477  6314  6651 W FormManager: Network not available. Please check & try again.
08-29 10:24:12.482  6314  6652 V FormManager: Network unavailable.
08-29 10:24:12.485  6314  6652 V FormManager: Network unavailable.
,08-29 10:24:12.493  6358  6577 I bt_vendor: bluetooth satus is on
08-29 10:24:12.493  6358  6577 D bt_hci_bdroid: preload
08-29 10:24:12.494  6358  6623 D bt_userial_mct: userial_open(port:0)
08-29 10:24:12.494  6358  6623 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 10:24:12.497  6358  6623 I bt_vendor: Done intiailizing UART
08-29 10:24:12.497  1029  2025 I ActivityManager: Killing 5941:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-29 10:24:12.498  6358  6623 I bt_vendor: Done intiailizing UART
08-29 10:24:12.498  6358  6623 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 10:24:12.498  6358  6623 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 10:24:12.498  6358  6621 I bt-btu  : btu_task received preload complete event
08-29 10:24:12.498  6358  6673 D bt_userial_mct: Entering userial_read_thread()
08-29 10:24:12.499  6358  6621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 10:24:12.499  6358  6621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 10:24:12.501  6358  6621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 10:24:12.504  6358  6621 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 10:24:12.505  6358  6621 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 10:24:12.539  1029  1971 W libprocessgroup: failed to open /acct/uid_10061/pid_5941/cgroup.procs: No such file or directory
,08-29 10:24:12.556  6358  6621 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 10:24:12.556  6358  6621 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0222061 
08-29 10:24:12.556  6358  6621 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0222061 
,08-29 10:24:12.578  6358  6580 E bt-btif : Calling BTA_HhEnable
08-29 10:24:12.578  6358  6580 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 10:24:12.579  6358  6621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 10:24:12.579  6358  6621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 10:24:12.579  6358  6621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-29 10:24:12.579  6358  6580 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 10:24:12.579  6358  6621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 10:24:12.579  6358  6621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 10:24:12.581  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 10:24:12.582  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 10:24:12.582  6358  6580 D BluetoothAdapterProperties: Name is: G3
,08-29 10:24:12.586  6358  6580 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:24:12.587  6358  6580 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:24:12.587  6358  6580 D bt_hci_bdroid: postload
08-29 10:24:12.587  6358  6623 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 10:24:12.588  6358  6621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 10:24:12.588  6358  6580 D bte_conf: Device ID record 1 : primary
08-29 10:24:12.588  6358  6580 D bte_conf:   vendorId            = 00c4
08-29 10:24:12.588  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:12.588  6358  6580 D bte_conf:   vendorIdSource      = 0001
08-29 10:24:12.588  6358  6580 D bte_conf:   product             = 13a1
08-29 10:24:12.588  6358  6580 D bte_conf:   version             = 1000
08-29 10:24:12.588  6358  6580 D bte_conf:   clientExecutableURL = 
08-29 10:24:12.588  6358  6580 D bte_conf:   serviceDescription  = 
08-29 10:24:12.588  6358  6580 D bte_conf:   documentationURL    = 
08-29 10:24:12.589  6358  6580 D bte_conf: bte_load_did_conf no section named DID2.
08-29 10:24:12.589  6358  6623 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 10:24:12.590  6358  6623 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 10:24:12.590  6358  6623 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 10:24:12.590  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:12.593  6358  6580 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 10:24:12.593  6358  6577 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 10:24:12.593  6358  6577 D BluetoothAdapterProperties: ScanMode =  20
08-29 10:24:12.593  6358  6577 D BluetoothAdapterProperties: State =  11
08-29 10:24:12.594  6358  6577 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 10:24:12.594  6358  6577 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 10:24:12.594  6358  6577 D BluetoothAdapterProperties: Setting state to 12
08-29 10:24:12.594  6358  6577 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 10:24:12.595  6358  6580 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 10:24:12.597  1029  1111 D BluetoothManagerService: Message: 60
08-29 10:24:12.597  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 10:24:12.597  1029  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-29 10:24:12.598  6358  6577 I BluetoothAdapterState: Entering On State
08-29 10:24:12.600  6358  6577 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 10:24:12.600  6358  6577 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 10:24:12.600  6358  6577 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 10:24:12.601  6358  6577 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 10:24:12.601  6209  6225 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 10:24:12.574  6675  6675 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:12.574  6675  6675 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:12.605  1029  1111 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:12.607  1846  1862 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:24:12.614  6358  6621 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 10:24:12.614  6358  6621 W bt-smp  : Plain text(LSB ~ MSB) = 6c 39 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 10:24:12.614  6358  6621 W bt-smp  : Encrypted text(LSB ~ MSB) = ef 37 90 cc e8 f5 d7 84 b6 65 61 a9 ba 7e a8 b9 
08-29 10:24:12.614  6358  6621 W bt-btm  : Stopping oneshot timer
08-29 10:24:12.615  6358  6623 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 10:24:12.615  6358  6673 E bt_mct  : hci lib postload completed
08-29 10:24:12.636  6358  6580 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:24:12.636  6358  6580 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-29 10:24:12.637  6358  6621 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 10:24:12.637  6358  6621 W bt-smp  : Plain text(LSB ~ MSB) = a2 40 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 10:24:12.637  6358  6621 W bt-smp  : Encrypted text(LSB ~ MSB) = 61 b7 c8 fa 21 6b ba d9 c4 3f ca 63 b8 e3 0f 8e 
08-29 10:24:12.637  6358  6621 W bt-btm  : Stopping oneshot timer
08-29 10:24:12.648  6358  6577 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-29 10:24:12.661  6656  6656 D LgDataFeature: LgDataFeature() Constructor: none
08-29 10:24:12.661  6656  6656 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 10:24:12.664  6358  6621 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 10:24:12.665  6358  6621 W bt-smp  : Plain text(LSB ~ MSB) = cc 71 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 10:24:12.665  6358  6621 W bt-smp  : Encrypted text(LSB ~ MSB) = b8 20 df d6 50 8f 42 37 1a bc 04 1f 03 2c c1 78 
08-29 10:24:12.665  6358  6621 W bt-btm  : Stopping oneshot timer
08-29 10:24:12.667  6656  6656 D PhoneMonitor: Register our PhoneStateListener
08-29 10:24:12.673  6680  6680 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-29 10:24:12.677  6358  6621 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 10:24:12.677  6358  6621 W bt-smp  : Plain text(LSB ~ MSB) = 8f 61 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 10:24:12.677  6358  6621 W bt-smp  : Encrypted text(LSB ~ MSB) = 77 e9 22 4d b8 52 7f 97 38 fc d1 2a 71 a4 48 b4 
08-29 10:24:12.677  6358  6621 W bt-btm  : Stopping oneshot timer
08-29 10:24:12.689  6358  6621 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 10:24:12.689  6358  6621 W bt-smp  : Plain text(LSB ~ MSB) = 33 c9 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 10:24:12.689  6358  6621 W bt-smp  : Encrypted text(LSB ~ MSB) = 68 c6 24 8c 09 fe 77 c2 45 82 af 8d 8d 5c bf ab 
08-29 10:24:12.689  6358  6621 W bt-btm  : Stopping oneshot timer
,08-29 10:24:12.783  1029  1568 I art     : Explicit concurrent mark sweep GC freed 132844(6MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.315ms total 172.675ms
,08-29 10:24:12.785  1029  1029 D BluetoothHeadset: Proxy object connected
08-29 10:24:12.786  1846  1846 D BluetoothHeadset: Proxy object connected
08-29 10:24:12.787  6209  6224 D BluetoothMap: onBluetoothStateChange: up=true
08-29 10:24:12.794  6209  6209 D BluetoothMap: Proxy object connected
08-29 10:24:12.794  6209  6209 D MapProfile: Bluetooth service connected
08-29 10:24:12.794  6209  6209 D BluetoothMap: getConnectedDevices()
08-29 10:24:12.796  6358  6373 V BluetoothMapService: getConnectedDevices()
08-29 10:24:12.799  1029  1111 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 10:24:12.803  1029  1029 D BluetoothA2dp: Proxy object connected
08-29 10:24:12.804  6209  6225 D BluetoothPan: onBluetoothStateChange on: true
08-29 10:24:12.804  6209  6225 D BluetoothPan: onBluetoothStateChange call bindService
08-29 10:24:12.807  6209  6209 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:24:12.807  6209  6209 D PanProfile: Bluetooth service connected
08-29 10:24:12.808  6209  6686 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 10:24:12.810  1846  2722 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:12.812  1846  1846 D BluetoothHeadset: Proxy object connected
08-29 10:24:12.812  6656  6656 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 10:24:12.812  6209  6209 D BluetoothInputDevice: Proxy object connected
08-29 10:24:12.812  1846  1862 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:12.812  6209  6209 D HidProfile: Bluetooth service connected
08-29 10:24:12.813  6656  6656 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 10:24:12.814  1846  1846 D BluetoothHeadset: Proxy object connected
,08-29 10:24:12.841  6656  6656 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-29 10:24:12.841  6656  6656 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-29 10:24:12.842  6656  6656 D TelephonyAutoProfiling: [parse] Load xml
08-29 10:24:12.843  1029  1916 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6690 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 10:24:12.844  1029  1916 I ActivityManager: Killing 6049:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-29 10:24:12.846  6656  6656 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-29 10:24:12.846  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-29 10:24:12.846  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-29 10:24:12.846  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-29 10:24:12.846  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-29 10:24:12.846  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-29 10:24:12.846  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-29 10:24:12.846  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-29 10:24:12.846  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-29 10:24:12.846  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-29 10:24:12.846  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-29 10:24:12.847  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-29 10:24:12.847  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-29 10:24:12.847  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-29 10:24:12.847  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-29 10:24:12.847  6656  6656 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-29 10:24:12.847  6656  6656 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-29 10:24:12.854  6656  6656 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-29 10:24:12.886  1029  1917 W libprocessgroup: failed to open /acct/uid_10080/pid_6049/cgroup.procs: No such file or directory
08-29 10:24:12.886  1029  1111 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 10:24:12.886  1029  1111 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-29 10:24:12.895  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 10:24:12.895  1029  1111 D BluetoothManagerService: Message: 40
08-29 10:24:12.895  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 10:24:12.896  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:12.897  1935  2096 D LGBluetoothAPIService: Message: 1
08-29 10:24:12.897  1935  2096 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 10:24:12.899  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 10:24:12.909  5976  5976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 10:24:12.917  6358  6358 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:12.917  6358  6358 D BluetoothMapService: STATE_ON
08-29 10:24:12.917  1935  2096 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-29 10:24:12.917  6209  6209 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 10:24:12.919  6358  6358 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 10:24:12.919  6358  6358 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 10:24:12.920  1935  1935 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 10:24:12.920  1935  2096 D LGBluetoothAPIService: Message: 100
08-29 10:24:12.920  1935  2096 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 10:24:12.921  1029  1111 D BluetoothManagerService: Message: 30
08-29 10:24:12.923  6209  6209 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-29 10:24:12.925  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:12.925  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:12.925  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:12.925  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:12.925  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:12.925  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:12.925  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:12.925  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:12.927  5976  5976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:12.928  1029  1111 D BluetoothManagerService: Message: 30
08-29 10:24:12.934  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:12.934  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:12.934  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:12.934  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:12.934  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:12.934  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:12.934  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:12.934  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:12.938  5976  5976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:12.938  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:12.938  6358  6358 V BluetoothPbapService: Pbap Service onCreate
08-29 10:24:12.938  6358  6358 V BluetoothPbapService: Starting PBAP service
08-29 10:24:12.938  6209  6209 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 10:24:12.939  6358  6358 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 10:24:12.939  6358  6358 V BluetoothPbapService: Pbap Service onBind
08-29 10:24:12.940  6358  6358 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:12.941  6358  6358 V BluetoothPbapService: state: 12
08-29 10:24:12.941  6358  6358 V BluetoothMapService: Handler(): got msg=1
08-29 10:24:12.941  6209  6209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 10:24:12.942  6358  6358 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 10:24:12.943  6209  6209 D BluetoothA2dp: Proxy object connected
08-29 10:24:12.943  6358  6358 V BluetoothPbapService: Handler(): got msg=1
08-29 10:24:12.943  6209  6209 D A2dpProfile: Bluetooth service connected
08-29 10:24:12.944  6358  6358 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 10:24:12.944  6358  6708 D BluetoothMapMasInstance: MAS initSocket()
08-29 10:24:12.946  6358  6358 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 10:24:12.946  6358  6358 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:12.946  6358  6708 D BluetoothMapMasInstance:   masId = 00
08-29 10:24:12.946  6358  6708 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 10:24:12.946  6358  6708 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 10:24:12.946  6358  6708 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 10:24:12.946  6358  6358 V BluetoothPbapReceiver: ***********state = 12
08-29 10:24:12.947  6209  6209 D BluetoothHeadset: Proxy object connected
08-29 10:24:12.947  1029  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:12.948  6209  6209 D HeadsetProfile: Bluetooth service connected
08-29 10:24:12.948  6358  6709 V BluetoothPbapService: Pbap Service initSocket
08-29 10:24:12.949  1029  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 10:24:12.950  2265  2265 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:24:12.951  2265  2265 D c       : Getting all permits...
08-29 10:24:12.951  2265  2265 D a       : Opening database...
08-29 10:24:12.951  6358  6708 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:12.952  6358  6709 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:12.953  6358  6708 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 10:24:12.953  6358  6708 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 10:24:12.953  6358  6709 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 10:24:12.953  6358  6708 D BluetoothMapMasInstance: Accepting socket connection...
08-29 10:24:12.953  6358  6709 V BluetoothPbapService: Succeed to create listening socket 
08-29 10:24:12.953  6358  6709 V BluetoothPbapService: Accepting socket connection...
08-29 10:24:12.954  6209  6209 D BluetoothPbap: Proxy object connected
08-29 10:24:12.954  6358  6580 D BluetoothAdapterProperties: Scan Mode:21
08-29 10:24:12.954  6358  6580 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 10:24:12.955  6209  6209 D PbapServerProfile: Bluetooth service connected
08-29 10:24:12.957  2265  2265 D a       : Opening database auth.proximity.permit_store...
08-29 10:24:12.958  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:12.959  2265  2265 D a       : Closing database...
08-29 10:24:12.959  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:12.960  6209  6209 D DockEventReceiver: finishStartingService: stopping service
08-29 10:24:12.972  6209  6209 D BluetoothPermissionRequest: onReceive
,08-29 10:24:12.974  6209  6209 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 10:24:12.975  6209  6209 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 10:24:12.979  6358  6358 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 10:24:12.980  6358  6358 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 10:24:12.986  6358  6358 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 10:24:13.006  6358  6358 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 10:24:13.006  6358  6358 V BtOppService: onCreate
,08-29 10:24:13.010  6358  6358 V BluetoothOppNotification: send message
08-29 10:24:13.015  6358  6358 V BtOppService: Starting RfcommListener
08-29 10:24:13.018  6358  6358 D BluetoothOppPreference: Dumping Names:  
08-29 10:24:13.018  6358  6358 D BluetoothOppPreference: {}
08-29 10:24:13.018  6358  6358 D BluetoothOppPreference: Dumping Channels:  
08-29 10:24:13.018  6358  6358 D BluetoothOppPreference: {}
,08-29 10:24:13.018  6358  6358 V BtOppService: onStartCommand
08-29 10:24:13.019  6358  6716 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 10:24:13.022  6358  6358 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:13.022  6358  6358 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 10:24:13.024  6358  6358 V BluetoothOppNotification: new notify threadi!
08-29 10:24:13.025  6358  6358 V BluetoothOppNotification: send delay message
08-29 10:24:13.025  6358  6358 V BtOppService: start RfcommListener
08-29 10:24:13.028  6358  6716 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 10:24:13.029  6358  6358 V BtOppService: RfcommListener started
08-29 10:24:13.029  6358  6717 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-29 10:24:13.031  6358  6718 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 10:24:13.035  1029  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:13.036  6358  6718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:13.037  6358  6713 V BtOppService: Deleted complete outbound shares, number =  0
08-29 10:24:13.039  6358  6718 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-29 10:24:13.040  6358  6718 V BtOppRfcommListener: Started RFCOMM listener....
08-29 10:24:13.040  6358  6718 I BtOppRfcommListener: Accept thread started.
08-29 10:24:13.040  6358  6718 V BtOppRfcommListener: Accepting connection...
08-29 10:24:13.041  6358  6716 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@138dca72 on behalf of 
,08-29 10:24:13.043  6358  6713 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 10:24:13.043  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:13.043  6358  6358 V BluetoothFtpService: Ftp Service onCreate
08-29 10:24:13.043  6358  6713 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 10:24:13.043  6358  6358 I BluetoothFtpService: Ftp Service onCreate
08-29 10:24:13.044  6358  6358 V BluetoothFtpService: Ftp Service onStartCommand
08-29 10:24:13.044  6358  6717 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d3a1ec3 on behalf of 
08-29 10:24:13.044  6358  6358 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:13.044  6358  6358 V BluetoothFtpService: Starting Listening on sockets
08-29 10:24:13.044  6358  6713 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@349a0279 on behalf of 
08-29 10:24:13.045  6358  6358 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 10:24:13.045  6358  6358 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 10:24:13.045  6358  6358 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 10:24:13.045  6358  6358 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:13.045  6358  6717 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-29 10:24:13.045  6358  6358 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 10:24:13.046  6358  6358 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 10:24:13.047  6358  6717 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 10:24:13.048  6358  6717 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34ea1bbe on behalf of 
08-29 10:24:13.048  6358  6716 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 10:24:13.049  6358  6716 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 10:24:13.049  6358  6717 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 10:24:13.050  6358  6358 V BtOppService: ContentObserver received notification
08-29 10:24:13.050  6358  6358 V BtOppService: ContentObserver received notification
08-29 10:24:13.050  6358  6358 V BluetoothFtpService: Handler(): got msg=1
08-29 10:24:13.051  6358  6358 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 10:24:13.051  6358  6358 V BluetoothFtpService: Ftp Service initSocket
08-29 10:24:13.054  6358  6717 V BluetoothOppNotification: outbound notification was removed.
08-29 10:24:13.054  6358  6717 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 10:24:13.055  6358  6717 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f15e41f on behalf of 
08-29 10:24:13.055  6358  6716 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26cdc36c on behalf of 
08-29 10:24:13.057  6358  6717 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 10:24:13.057  6358  6716 V BluetoothOppNotification: update too frequent, put in queue
08-29 10:24:13.058  1029  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 10:24:13.059  6358  6358 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:13.059  6358  6358 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
08-29 10:24:13.060  6358  6358 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-29 10:24:13.063  6358  6719 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-29 10:24:13.063  6358  6717 V BluetoothOppNotification: inbound notification was removed.
08-29 10:24:13.063  6358  6716 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 10:24:13.063  6358  6717 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 10:24:13.063  6358  6716 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 10:24:13.065  6358  6717 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8af4d35 on behalf of 
08-29 10:24:13.067  6358  6716 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@82835ca on behalf of 
08-29 10:24:13.067  6358  6716 V BluetoothOppNotification: update too frequent, put in queue
08-29 10:24:13.069  6358  6716 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 10:24:13.070  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:13.070  6358  6358 V BluetoothSapService: Sap Service onCreate
,08-29 10:24:13.071  6358  6358 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:13.071  6358  6358 V BluetoothSapService: state: 12
08-29 10:24:13.071  6358  6358 V BluetoothSapService: Starting SAP server process
08-29 10:24:13.054  6720  6720 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:13.054  6720  6720 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:13.073  6358  6358 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 10:24:13.075  6358  6721 V BluetoothSapService: Sap Service initRfcommSocket
08-29 10:24:13.078  1029  1863 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:13.079  6358  6721 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:13.080  6358  6721 V BluetoothSapService: Succeed to create listening socket 
08-29 10:24:13.080  6358  6721 V BluetoothSapService: Accepting socket connection...
08-29 10:24:13.081  6720  6720 V BT_SAP  : Event pipe created
08-29 10:24:13.081  6720  6720 V BT_SAP  : create_server_socket qcom.sap.server
08-29 10:24:13.081  6720  6720 V BT_SAP  : created socket fd 6
08-29 10:24:13.324  1029  1916 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6726 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-29 10:24:13.326  1029  1916 I ActivityManager: Killing 6073:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-29 10:24:13.437  1029  1971 W libprocessgroup: failed to open /acct/uid_10097/pid_6073/cgroup.procs: No such file or directory
,08-29 10:24:13.525  6726  6726 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,08-29 10:24:13.528  6726  6726 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,08-29 10:24:13.536  6726  6726 V DrmService: Service onCreate
08-29 10:24:13.537  6726  6726 D DrmService: Received new request = 2
08-29 10:24:13.546  6726  6743 I DrmSntpClient: Start Sync process
08-29 10:24:13.546  6726  6743 D DrmSntpClient: Server : 0
,08-29 10:24:13.589  1029  1916 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6744 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 10:24:13.592  6726  6743 D DrmSntpClient: Automatic sync but WiFi isn't enabled
08-29 10:24:13.594  6726  6726 D DrmService: Completed !! request = 2
08-29 10:24:13.594  6726  6726 D DrmService: Request count = 0
08-29 10:24:13.596  6726  6726 V DrmService: Service onDestroy
08-29 10:24:13.601  1029  1724 I ActivityManager: Killing 6116:com.lge.eula/1000 (adj 15): empty #17
08-29 10:24:13.646  1029  2025 W libprocessgroup: failed to open /acct/uid_1000/pid_6116/cgroup.procs: No such file or directory
,08-29 10:24:13.682  6744  6744 I art     : Almond Protected OAT
,08-29 10:24:13.761  6744  6744 D WeatherApplication: removeAccount
,08-29 10:24:13.763  6744  6744 D WeatherApplication: Account.length = 0
08-29 10:24:13.763  6744  6744 E WeatherApplication: OPERATOR:OPEN
,08-29 10:24:13.770  6744  6744 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:24:13
08-29 10:24:13.774  6744  6744 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 10:24:13.774  6744  6744 D Weather.Utils: 2 : All the weather widget is gone.
08-29 10:24:13.775  1029  1383 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:13.775  1029  1383 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:24:13.780  6744  6744 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 10:24:13.787  6744  6744 D WeatherAncestor: connectivity changed - connection : true
,08-29 10:24:13.790  6744  6744 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-29 10:24:13.814  6744  6744 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 10:24:13.814  6744  6744 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 10:24:13.815  6744  6744 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-29 10:24:13.831  1029  1384 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-29 10:24:13.832  1029  1384 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 10:24:13.846  6744  6744 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-29 10:24:13.846  6744  6744 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:24:13
,08-29 10:24:13.907  1029  1971 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6762 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 10:24:13.911  1029  1971 I ActivityManager: Killing 2165:com.lge.music/u0a34 (adj 15): empty #17
08-29 10:24:13.933   336  1390 V AudioFlinger: 2165 died, releasing its sessions
08-29 10:24:13.933   336  1390 V AudioFlinger:  pid 1846 @ 0
08-29 10:24:13.933   336  1390 V AudioFlinger:  pid 3411 @ 1
08-29 10:24:13.933   336  1390 V AudioFlinger:  pid 3411 @ 2
,08-29 10:24:13.965  1029  1045 W libprocessgroup: failed to open /acct/uid_10034/pid_2165/cgroup.procs: No such file or directory
,08-29 10:24:14.025  6358  6358 V BluetoothOppNotification: new notify threadi!
08-29 10:24:14.026  6358  6358 V BluetoothOppNotification: send delay message
,08-29 10:24:14.029  6358  6779 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 10:24:14.031  6358  6779 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@227be496 on behalf of 
,08-29 10:24:14.033  6358  6779 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 10:24:14.035  6358  6779 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 10:24:14.037  6358  6779 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@106a3817 on behalf of 
08-29 10:24:14.038  6358  6779 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 10:24:14.040  6358  6779 V BluetoothOppNotification: outbound notification was removed.
08-29 10:24:14.040  6358  6779 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-29 10:24:14.043  6358  6779 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@131b1404 on behalf of 
08-29 10:24:14.045  6358  6779 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 10:24:14.049  6358  6779 V BluetoothOppNotification: inbound notification was removed.
08-29 10:24:14.049  6358  6779 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 10:24:14.052  6358  6779 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21b8eded on behalf of 
08-29 10:24:14.080   278   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 10:24:14.080   278   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 10:24:14.080   278   325 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 10:24:14.085  6762  6781 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 10:24:14.089   278   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 10:24:14.089   278   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 10:24:14.090   278   325 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 10:24:14.090  6762  6781 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 10:24:14.106   278   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 10:24:14.106   278   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-29 10:24:14.106   278   325 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 10:24:14.108  6762  6785 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 10:24:14.110   278   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 10:24:14.110   278   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 10:24:14.110   278   325 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 10:24:14.111  6762  6785 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 10:24:14.365  6762  6762 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 10:24:14.386  6762  6762 I LibraryLoader: Loading: webviewchromium
,08-29 10:24:14.391  6762  6762 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 6910-6916)
,08-29 10:24:14.391  6762  6762 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 10:24:14.401  6762  6762 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c3b4574}
,08-29 10:24:14.404  6762  6762 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 10:24:14.404  6762  6762 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 10:24:14.419  6762  6762 I BrowserStartupController: Initializing chromium process, renderers=0
,08-29 10:24:14.421  6762  6762 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 10:24:14.442   336  2180 V AudioPolicyService: registerClient() client 0xb558ad40, uid 10093
,08-29 10:24:14.446  6762  6806 W AudioManagerAndroid: Requires BLUETOOTH permission
08-29 10:24:14.446  6762  6762 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 10:24:14.448  6762  6762 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-29 10:24:14.449  6762  6762 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-29 10:24:14.466  6762  6762 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 10:24:14.466  6762  6762 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 10:24:14.466  6762  6762 I Adreno-EGL: Build Date: 12/12/14 금
08-29 10:24:14.466  6762  6762 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 10:24:14.466  6762  6762 I Adreno-EGL: Remote Branch: 
08-29 10:24:14.466  6762  6762 I Adreno-EGL: Local Patches: 
08-29 10:24:14.466  6762  6762 I Adreno-EGL: Reconstruct Branch: 
,08-29 10:24:14.569  6762  6762 I NSApplication: Starting up...
,08-29 10:24:14.679  1029  1953 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6820 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-29 10:24:14.682  1029  1953 I ActivityManager: Killing 5897:com.android.vending/u0a44 (adj 15): empty #17
08-29 10:24:14.738  1029  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:14.738  1029  1971 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@d4250af mBinding = false
,08-29 10:24:14.740  1029  1728 W libprocessgroup: failed to open /acct/uid_10044/pid_5897/cgroup.procs: No such file or directory
08-29 10:24:14.762  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 10:24:14.762  1029  1111 D BluetoothManagerService: Message: 2
08-29 10:24:14.763  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-29 10:24:14.763  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-29 10:24:14.765  1029  1111 D BluetoothManagerService: Sending off request.
08-29 10:24:14.766  6358  6707 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 10:24:14.767  6358  6577 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 10:24:14.767  6358  6577 D BluetoothAdapterProperties: Setting state to 13
08-29 10:24:14.767  6358  6577 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 10:24:14.768  1029  1111 D BluetoothManagerService: Message: 60
08-29 10:24:14.768  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 10:24:14.768  1029  1111 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 10:24:14.768  6358  6577 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 10:24:14.768  6358  6577 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 10:24:14.770  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 10:24:14.773  6358  6358 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:14.773  6358  6358 D BluetoothMapService: STATE_TURNING_OFF
08-29 10:24:14.773  6358  6358 V BluetoothMapService: Handler(): got msg=4
08-29 10:24:14.774  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:14.774  6358  6358 D BluetoothMapService: MAP Service closeService in
08-29 10:24:14.774  6358  6358 D BluetoothMapMasInstance: MAP Service shutdown
,08-29 10:24:14.776  6358  6708 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 10:24:14.776  6358  6708 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:24:14.776  6358  6708 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 10:24:14.776  6358  6708 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 10:24:14.776  6358  6708 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 10:24:14.776  6358  6708 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 10:24:14.776  6358  6708 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 10:24:14.776  6358  6708 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 10:24:14.777  6358  6358 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 10:24:14.777  6358  6358 V BluetoothMapService: MAP Service closeService out
08-29 10:24:14.778  6358  6358 V BtOppService: Receiver DISABLED_ACTION 
08-29 10:24:14.778  6358  6358 I BtOppRfcommListener: stopping Accept Thread
08-29 10:24:14.778  6358  6358 V BtOppRfcommListener: close mBtServerSocket
08-29 10:24:14.778  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:14.778  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:14.778  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:14.778  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:14.778  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:14.778  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:14.778  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:14.778  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:14.778  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:14.779  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:14.779  5976  5976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:14.780  6358  6718 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:24:14.780  6358  6718 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 10:24:14.781  6358  6358 V BtOppRfcommListener: waiting for thread to terminate
08-29 10:24:14.781  6358  6358 V BtOppRfcommListener: done waiting for thread to terminate
08-29 10:24:14.781  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:14.781  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:14.781  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:14.781  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:14.781  5976  5976 V io.jxcore.node.Connecti,vityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:14.781  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:14.781  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:14.781  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:14.781  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:14.783  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:14.783  5976  5976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:14.783  6209  6209 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-29 10:24:14.785  6358  6580 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:24:14.785  6358  6577 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 10:24:14.786  6358  6709 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:24:14.786  6358  6721 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:24:14.786  6358  6577 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 10:24:14.786  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 10:24:14.786  6358  6719 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:24:14.787  6358  6621 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-29 10:24:14.790  6358  6358 V BtOppService: onDestroy
08-29 10:24:14.792  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 10:24:14.792  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 10:24:14.792  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 10:24:14.792  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 10:24:14.792  6358  6621 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:24:14.792  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 10:24:14.792  6358  6621 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 10:24:14.792  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 10:24:14.792  6358  6621 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:24:14.792  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 10:24:14.792  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 10:24:14.793  6358  6621 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 10:24:14.794  6209  6209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 10:24:14.794  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:14.795  6358  6358 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 10:24:14.795  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:14.800  6358  6358 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 10:24:14.800  6358  6358 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:14.800  6358  6358 V BluetoothPbapReceiver: ***********state = 13
08-29 10:24:14.802  6209  6209 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:24:14.804  6358  6358 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 10:24:14.808  6358  6358 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:14.808  6358  6358 V BluetoothPbapService: state: 13
08-29 10:24:14.808  6358  6358 V BluetoothPbapService: Pbap Service closeService in
08-29 10:24:14.811  2265  2265 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:24:14.811  6209  6209 D BluetoothPbap: Proxy object disconnected
08-29 10:24:14.811  6209  6209 D PbapServerProfile: Bluetooth service disconnected
08-29 10:24:14.812  6358  6358 V BluetoothPbapService: successfully stopped pbap service
08-29 10:24:14.812  6358  6358 V BluetoothPbapService: Pbap Service closeService out
08-29 10:24:14.812  6358  6358 V BluetoothPbapService: Pbap Service onDestroy
08-29 10:24:14.812  6358  6358 V BluetoothPbapService: Pbap Service closeService in
08-29 10:24:14.812  6358  6358 V BluetoothPbapService: Pbap Service closeService out
08-29 10:24:14.812  6358  6358 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 10:24:14.820  6820  6820 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 10:24:14.822  6209  6209 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 10:24:14.828  6209  6209 D BluetoothPermissionRequest: onReceive
08-29 10:24:14.828  6209  6209 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 10:24:14.837  6209  6209 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 10:24:14.840  6358  6358 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 10:24:14.840  6358  6358 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 10:24:14.840  6358  6358 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 10:24:14.844  6358  6358 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:14.844  6358  6358 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 10:24:14.845  6358  6358 V BluetoothFtpService: Ftp Service onStartCommand
08-29 10:24:14.845  6358  6358 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:14.845  6358  6358 V BluetoothFtpService: Ftp Service closeService
08-29 10:24:14.845  6358  6358 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 10:24:14.849  6358  6358 V BluetoothFtpService: successfully stopped ftp service
08-29 10:24:14.849  6358  6358 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 10:24:14.849  6358  6358 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 10:24:14.849  6358  6358 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 10:24:14.849  6358  6358 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:14.849  6358  6358 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 10:24:14.849  6358  6358 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 10:24:14.850  6358  6358 V BluetoothFtpService: Ftp Service onDestroy
08-29 10:24:14.851  6358  6358 V BluetoothFtpService: Ftp Service closeService
08-29 10:24:14.851  6358  6358 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:14.851  6358  6358 V BluetoothSapService: state: 13
08-29 10:24:14.851  6358  6358 V BluetoothSapService: Stopping SAP server process
08-29 10:24:14.854  6358  6358 V BluetoothSapService: Sap Service closeSapService in
08-29 10:24:14.854  6358  6358 V BluetoothSapService: Close listen Socket : 
08-29 10:24:14.854  6358  6358 V BluetoothSapService: Close rfcomm Socket : 
08-29 10:24:14.854  6358  6358 V BluetoothSapService: Close sapd  Socket : 
08-29 10:24:14.856  6358  6358 V BluetoothSapService: Sap Service closeSapService out
08-29 10:24:14.856  6358  6358 V BluetoothSapService: Sap Service onDestroy
08-29 10:24:14.856  6358  6358 V BluetoothSapService: Sap Service closeSapService in
08-29 10:24:14.856  6358  6358 V BluetoothSapService: Close listen Socket : 
08-29 10:24:14.856  6358  6358 V BluetoothSapService: Close rfcomm Socket : 
08-29 10:24:14.856  6358  6358 V BluetoothSapService: Close sapd  Socket : 
08-29 10:24:14.857  6358  6358 V BluetoothSapService: Sap Service closeSapService out
,08-29 10:24:15.128  2265  2265 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-29 10:24:15.145  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 10:24:15.147  3731  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 10:24:15.178  2265  2265 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:15.191  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 10:24:15.191  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:15.191  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 10:24:15.191  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 10:24:15.194  6558  6558 I AppUp4:CustModeStarterReceiver: onReceive
08-29 10:24:15.195  1810  6857 I CheckinService: active receiver: enabled
08-29 10:24:15.203  6558  6558 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@99b837b
08-29 10:24:15.203  6558  6558 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 10:24:15.203  6558  6558 D AppUp4:CustFacade: isPhone : true
,08-29 10:24:15.206  6558  6558 D AppUp4:CustModeStarterReceiver: begin check event
08-29 10:24:15.207  6558  6558 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 10:24:15.210  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:15.210  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 10:24:15.212  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 10:24:15.215  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 10:24:15.223  4258  6861 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 10:24:15.227  6595  6595 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 10:24:15.240  4258  6862 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:15.241  4258  6862 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 10:24:15.250  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 10:24:15.251  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:15.251  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 10:24:15.256  6595  6869 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 10:24:15.260  6314  6871 W FormManager: Network not available. Please check & try again.
08-29 10:24:15.263  6656  6656 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 10:24:15.263  6656  6656 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 10:24:15.264  6314  6872 V FormManager: Network unavailable.
08-29 10:24:15.278  6744  6744 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:24:15
,08-29 10:24:15.280  6314  6872 V FormManager: Network unavailable.
08-29 10:24:15.285  6744  6744 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 10:24:15.285  6744  6744 D Weather.Utils: 2 : All the weather widget is gone.
08-29 10:24:15.286  6744  6744 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 10:24:15.288  6744  6744 D WeatherAncestor: connectivity changed - connection : true
08-29 10:24:15.288  6744  6744 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3b9301f1
08-29 10:24:15.290  6744  6744 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-29 10:24:15.290  6744  6744 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 10:24:15.290  6744  6744 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 10:24:15.290  6744  6744 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 10:24:15.290  6744  6744 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:24:15
08-29 10:24:15.315  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 10:24:15.319  3731  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 10:24:15.346  2265  2265 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:15.351  1810  6874 I CheckinService: active receiver: enabled
08-29 10:24:15.357  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-29 10:24:15.357  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:15.357  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 10:24:15.357  6558  6558 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 10:24:15.361  6558  6558 I AppUp4:CustModeStarterReceiver: onReceive
08-29 10:24:15.366  6558  6558 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@99b837b
08-29 10:24:15.366  6558  6558 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 10:24:15.366  6558  6558 D AppUp4:CustFacade: isPhone : true
08-29 10:24:15.367  6558  6558 D AppUp4:CustModeStarterReceiver: begin check event
08-29 10:24:15.367  6558  6558 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 10:24:15.371  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:15.371  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 10:24:15.373  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 10:24:15.376  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 10:24:15.382  4258  6875 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 10:24:15.384  4258  6876 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:15.384  4258  6876 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 10:24:15.385  6595  6595 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 10:24:15.408  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-29 10:24:15.408  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:15.408  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 10:24:15.409  6595  6878 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:15.414  6656  6656 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 10:24:15.415  6656  6656 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 10:24:15.419  6314  6879 W FormManager: Network not available. Please check & try again.
08-29 10:24:15.420  6314  6881 V FormManager: Network unavailable.
,08-29 10:24:15.436  6744  6744 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:24:15
,08-29 10:24:15.439  6314  6881 V FormManager: Network unavailable.
08-29 10:24:15.440  6744  6744 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 10:24:15.441  6744  6744 D Weather.Utils: 2 : All the weather widget is gone.
08-29 10:24:15.441  6744  6744 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 10:24:15.441  6744  6744 D WeatherAncestor: connectivity changed - connection : true
08-29 10:24:15.442  6744  6744 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3b9301f1
08-29 10:24:15.443  6744  6744 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 10:24:15.443  6744  6744 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 10:24:15.443  6744  6744 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 10:24:15.443  6744  6744 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 10:24:15.445  6744  6744 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:24:15
08-29 10:24:15.486  2265  2265 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-29 10:24:15.516  2265  2265 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-29 10:24:15.699  6358  6580 D bt_hci_bdroid: cleanup
08-29 10:24:15.700  6358  6623 I bt_lpm  : LPM is already off!!!
08-29 10:24:15.700  6358  6673 I bt_userial_mct: exiting userial_read_thread
08-29 10:24:15.700  6358  6673 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 10:24:15.701  6358  6621 W bt-btif : ag scb idx 1 not allocated
08-29 10:24:15.701  6358  6621 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 10:24:15.701  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 10:24:15.701  6358  6621 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:24:15.701  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 10:24:15.701  6358  6621 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:24:15.701  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 10:24:15.701  6358  6621 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:24:15.701  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-29 10:24:15.701  6358  6621 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:24:15.701  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 10:24:15.701  6358  6621 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:24:15.702  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 10:24:15.702  6358  6621 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:24:15.702  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 10:24:15.702  6358  6621 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:24:15.702  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 10:24:15.702  6358  6621 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:24:15.702  6358  6621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 10:24:15.702  6358  6621 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:24:15.702  6358  6621 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 10:24:15.702  6358  6580 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-29 10:24:15.702  6358  6623 I bt_vendor: hw_epilog_process
08-29 10:24:15.703  6358  6580 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 10:24:15.703  6358  6580 D bt_userial_mct: userial_close
08-29 10:24:15.703  6358  6580 E bt_userial_mct: pthread_join() FAILED result:3
,08-29 10:24:15.704  6358  6580 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 10:24:15.734  6358  6580 D bt_hci_bdroid: set_power 0,
,08-29 10:24:15.734  6358  6580 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 10:24:15.734  6358  6580 I bt_vendor: bluetooth satus is on
08-29 10:24:15.734  6358  6580 I bt_vendor: bt-vendor : resetting BT status
08-29 10:24:15.734  6358  6580 I bt_vendor: Starting hciattach daemon
08-29 10:24:15.734  6358  6580 I bt_vendor: try to set false
08-29 10:24:15.735  6358  6580 I bt_vendor: Starting hciattach daemon
08-29 10:24:15.735  6358  6580 I bt_vendor: try to set false
08-29 10:24:15.737  6358  6580 I bt_vendor: cleanup
08-29 10:24:15.737  6358  6621 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 10:24:15.738  6358  6580 I GKI_LINUX: GKI_exit_task 0 done
08-29 10:24:15.738  6358  6580 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 10:24:15.739  6358  6577 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 10:24:15.741  6358  6358 D HeadsetService: Received stop request...Stopping profile...
08-29 10:24:15.742  6358  6358 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 10:24:15.742  6358  6358 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 10:24:15.742  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:15.743  6358  6587 D HeadsetStateMachine: Exit Disconnected: -1
08-29 10:24:15.744  6209  6209 D BluetoothHeadset: Proxy object disconnected
08-29 10:24:15.744  6209  6209 D HeadsetProfile: Bluetooth service disconnected
08-29 10:24:15.745  6358  6358 D A2dpService: Received stop request...Stopping profile...
08-29 10:24:15.745  6358  6612 D A2dpStateMachine: Exit Disconnected: -1
08-29 10:24:15.747  1846  1846 D BluetoothHeadset: Proxy object disconnected
08-29 10:24:15.747  1846  1846 D BluetoothHeadset: Proxy object disconnected
08-29 10:24:15.748  1846  1846 D BluetoothHeadset: Proxy object disconnected
,08-29 10:24:15.749  1029  1029 D BluetoothHeadset: Proxy object disconnected
08-29 10:24:15.749  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 10:24:15.749  6358  6358 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 10:24:15.753  6358  6577 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 10:24:15.753  6358  6358 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 10:24:15.753  6358  6358 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 10:24:15.753  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:15.755  6358  6358 D HidService: Received stop request...Stopping profile...
08-29 10:24:15.755  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:15.755  6209  6209 D BluetoothA2dp: Proxy object disconnected
08-29 10:24:15.755  6209  6209 D A2dpProfile: Bluetooth service disconnected
08-29 10:24:15.756  1029  1029 D BluetoothA2dp: Proxy object disconnected
08-29 10:24:15.756  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 10:24:15.757  6209  6209 D BluetoothInputDevice: Proxy object disconnected
08-29 10:24:15.757  6209  6209 D HidProfile: Bluetooth service disconnected
08-29 10:24:15.757  6358  6358 D HealthService: Received stop request...Stopping profile...
08-29 10:24:15.757  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:15.758  6358  6358 D HeadsetStateMachine: Unbinding service...
08-29 10:24:15.759  6358  6358 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 10:24:15.759  6358  6358 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 10:24:15.759  6358  6358 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 10:24:15.759  6358  6358 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 10:24:15.759  6358  6358 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 10:24:15.759  6358  6358 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 10:24:15.759  6358  6358 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 10:24:15.760  6358  6358 D PanService: Received stop request...Stopping profile...
08-29 10:24:15.761  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:15.764  6358  6358 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:24:15.765  6358  6358 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 10:24:15.765  6358  6358 D BtGatt.GattService: stop()
08-29 10:24:15.765  6209  6209 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 10:24:15.765  6209  6209 D PanProfile: Bluetooth service disconnected
08-29 10:24:15.765  6358  6358 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 10:24:15.766  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:15.767  6358  6358 D BluetoothMapService: Received stop request...Stopping profile...
08-29 10:24:15.767  6358  6358 D BluetoothMapService: stop()
08-29 10:24:15.768  6358  6358 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 10:24:15.768  6358  6358 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 10:24:15.768  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:15.769  6209  6209 D BluetoothMap: Proxy object disconnected
08-29 10:24:15.769  6209  6209 D MapProfile: Bluetooth service disconnected
08-29 10:24:15.770  6358  6358 I BluetoothA2dpServiceJni: cleanupNative
08-29 10:24:15.770  6358  6613 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 10:24:15.771  6358  6358 I GKI_LINUX: GKI_exit_task 2 done
08-29 10:24:15.771  6358  6358 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 10:24:15.771  6358  6358 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 10:24:15.771  6358  6358 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 10:24:15.771  6358  6358 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 10:24:15.772  6358  6358 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 10:24:15.772  6358  6358 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 10:24:15.772  6358  6358 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 10:24:15.772  6358  6358 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 10:24:15.776  6358  6358 V BluetoothMapService: Handler(): got msg=4
,08-29 10:24:15.776  6358  6358 D BluetoothMapService: MAP Service closeService in
08-29 10:24:15.776  6358  6358 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 10:24:15.776  6358  6358 V BluetoothMapService: MAP Service closeService out
08-29 10:24:15.777  6358  6577 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 10:24:15.777  6358  6577 D BluetoothAdapterProperties: Setting state to 10
08-29 10:24:15.777  6358  6577 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 10:24:15.777  1029  1111 D BluetoothManagerService: Message: 60
08-29 10:24:15.777  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 10:24:15.777  1029  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-29 10:24:15.778  6358  6358 D BluetoothMapService: cleanup()
08-29 10:24:15.778  6358  6358 D BluetoothMapService: MAP Service closeService in
08-29 10:24:15.778  6358  6358 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 10:24:15.778  6358  6358 V BluetoothMapService: MAP Service closeService out
08-29 10:24:15.778  6209  6224 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 10:24:15.779  6358  6577 I BluetoothAdapterState: Entering OffState
08-29 10:24:15.779  1029  1111 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:24:15.779  1846  1862 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:24:15.780  6209  6225 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:24:15.780  6209  6686 D BluetoothMap: onBluetoothStateChange: up=false
08-29 10:24:15.781  1029  1111 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:24:15.781  6209  6224 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:24:15.781  6209  6225 D BluetoothPan: onBluetoothStateChange on: false
08-29 10:24:15.782  6209  6686 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 10:24:15.783  1846  2447 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 10:24:15.783  1846  2722 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:24:15.784  1029  1111 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 10:24:15.784  1029  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 10:24:15.786  1029  1111 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 10:24:15.786  1029  1111 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 10:24:15.786  1029  1111 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@d4250af mBinding = false
08-29 10:24:15.787  1029  1111 D BluetoothManagerService: Sending unbind request.
,08-29 10:24:15.792  1029  1111 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 10:24:15.795  6358  6580 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 10:24:15.795  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:15.795  1935  2096 D LGBluetoothAPIService: Message: 2
08-29 10:24:15.795  1935  2096 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@7f968da mBinding = false
08-29 10:24:15.795  1935  2096 D LGBluetoothAPIService: Sending unbind request.
08-29 10:24:15.798  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:15.799  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:15.799  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 10:24:15.804  1595  1595 D BluetoothAdapter: 593180019: getState() :  mService = null. Returning STATE_OFF
08-29 10:24:15.804  1595  1595 D BluetoothAdapter: 593180019: getState() :  mService = null. Returning STATE_OFF
08-29 10:24:15.805  6358  6579 E BluetoothAdapterService(999490033): Repeated wake lock release; aborting release: bluedroid_timer
08-29 10:24:15.806  6358  6579 E GKI_LINUX: alarm_service_reschedule unable to release wake lock with no timers: 1
08-29 10:24:15.806  6358  6358 I GKI_LINUX: GKI_exit_task 1 done
08-29 10:24:15.806  6358  6358 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 10:24:15.806  6358  6358 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 10:24:15.806  6358  6358 I art     : --- WEIRD: removing null entry 248
08-29 10:24:15.806  6358  6358 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-29 10:24:15.806  6358  6358 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-29 10:24:15.810  6209  6209 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 10:24:15.810  6209  6209 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 10:24:15.811  6358  6358 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 10:24:15.813  6358  6358 I art     : System.exit called, status: 0
08-29 10:24:15.813  6358  6358 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 10:24:15.816  6209  6209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 10:24:15.825  6209  6209 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:24:15.838   336  2180 V AudioFlinger: 6358 died, releasing its sessions
08-29 10:24:15.838   336  2180 V AudioFlinger:  pid 1846 @ 0
08-29 10:24:15.838   336  2180 V AudioFlinger:  pid 3411 @ 1
08-29 10:24:15.838   336  2180 V AudioFlinger:  pid 3411 @ 2
08-29 10:24:15.838  6209  6209 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-29 10:24:15.854  1029  1568 I ActivityManager: Process com.android.bluetooth (pid 6358) has died
08-29 10:24:15.855  1029  1568 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-29 10:24:15.863  2265  2265 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:24:15.875  6209  6209 D BluetoothPermissionRequest: onReceive
08-29 10:24:15.878  6209  6209 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 10:24:15.878  6209  6209 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 10:24:15.881  6209  6209 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 10:24:15.928  1029  1045 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6895 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 10:24:15.982  6895  6895 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 10:24:15.983  6895  6895 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 10:24:15.983  6895  6895 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 10:24:15.984  6895  6895 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 10:24:16.019  6895  6895 D BluetoothAdapterApp: Loading JNI Library
,08-29 10:24:16.056  6895  6895 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@18474b9 Instance Count = 1
,08-29 10:24:16.067  6895  6895 D BluetoothAdapterApp: onCreate
,08-29 10:24:16.101  6895  6895 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 10:24:16.101  6895  6895 D ProfileConfigQcom: Adding HeadsetService
,08-29 10:24:16.101  6895  6895 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 10:24:16.102  6895  6895 D ProfileConfigQcom: Adding A2dpService
08-29 10:24:16.103  6895  6895 D ProfileConfigQcom: [BTUI] HidService is supported
,08-29 10:24:16.103  6895  6895 D ProfileConfigQcom: Adding HidService
08-29 10:24:16.110  6895  6895 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-29 10:24:16.110  6895  6895 D ProfileConfigQcom: Adding HealthService
,08-29 10:24:16.111  6895  6895 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-29 10:24:16.112  6895  6895 D ProfileConfigQcom: [BTUI] PanService is supported
,08-29 10:24:16.113  6895  6895 D ProfileConfigQcom: Adding PanService
,08-29 10:24:16.113  6895  6895 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 10:24:16.113  6895  6895 D ProfileConfigQcom: Adding GattService
08-29 10:24:16.113  6895  6895 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 10:24:16.113  6895  6895 D ProfileConfigQcom: Adding BluetoothMapService
08-29 10:24:16.114  6895  6895 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 10:24:16.117  6895  6895 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 10:24:16.125  6209  6209 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 10:24:16.127  6895  6895 V LGMDMManagerInternal: Create singleton instance
,08-29 10:24:16.218  6895  6895 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:16.223  6895  6895 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-29 10:24:16.225  6895  6895 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 10:24:16.225  6895  6895 V BluetoothSapReceiver: SapReceiver onReceive 
,08-29 10:24:16.226  6895  6895 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:16.226  6895  6895 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 10:24:16.232  6291  6291 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-29 10:24:16.234  1029  1044 I ActivityManager: Killing 5047:com.lge.bnr/1000 (adj 15): empty #17
,08-29 10:24:16.266  1029  1724 W libprocessgroup: failed to open /acct/uid_1000/pid_5047/cgroup.procs: No such file or directory
,08-29 10:24:17.762  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:17.762  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:18.852  1029  1439 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-29 10:24:19.111  6762  6783 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-29 10:24:20.130  1029  1989 I ActivityManager: Killing 6142:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-29 10:24:20.151  6272  6272 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-29 10:24:20.151  6272  6272 W System.err: android.os.DeadObjectException
08-29 10:24:20.152  6272  6272 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 10:24:20.152  6272  6272 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 10:24:20.152  6272  6272 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 10:24:20.152  6272  6272 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 10:24:20.152  6272  6272 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 10:24:20.152  6272  6272 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 10:24:20.152  6272  6272 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 10:24:20.152  6272  6272 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 10:24:20.152  6272  6272 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 10:24:20.152  6272  6272 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 10:24:20.152  6272  6272 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:20.152  6272  6272 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:24:20.152  6272  6272 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 10:24:20.152  6272  6272 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 10:24:20.153  6272  6272 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 10:24:20.153  6272  6272 W System.err: android.os.DeadObjectException
08-29 10:24:20.153  6272  6272 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 10:24:20.153  6272  6272 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 10:24:20.153  6272  6272 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 10:24:20.153  6272  6272 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 10:24:20.153  6272  6272 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 10:24:20.153  6272  6272 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 10:24:20.153  6272  6272 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 10:24:20.153  6272  6272 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 10:24:20.153  6272  6272 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 10:24:20.153  6272  6272 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 10:24:20.153  6272  6272 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:20.153  6272  6272 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:24:20.154  6272  6272 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 10:24:20.154  6272  6272 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 10:24:20.154  6272  6272 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 10:24:20.154  6272  6272 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-29 10:24:20.188  1029  1728 W libprocessgroup: failed to open /acct/uid_1000/pid_6142/cgroup.procs: No such file or directory
08-29 10:24:20.188  1029  1728 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 10:24:20.195  6272  6272 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 10:24:20.196  6272  6272 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 10:24:20.256  1029  1917 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6923 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 10:24:20.285  6272  6272 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 10:24:20.353  6923  6923 D UEI.SmartControl: Quickset Services start...
,08-29 10:24:20.358  6923  6923 I UEI.SmartControl: Manufacture = LGE
08-29 10:24:20.359  6923  6923 D UEI.SmartControl: Id = LGNevo
08-29 10:24:20.360  6923  6923 D UEI.SmartControl: File observer start...
08-29 10:24:20.360  6923  6923 E UEI.SmartControl: IR Port is disabled: false
08-29 10:24:20.360  6923  6923 D UEI.SmartControl: Starting file observer...
08-29 10:24:20.361  6923  6923 D UEI.SmartControl: Extracting JNI libs...
08-29 10:24:20.361  6923  6923 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-29 10:24:20.421  6923  6923 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 10:24:20.422  6923  6923 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 10:24:20.422  6923  6923 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 10:24:20.449  6923  6923 I UEI.SmartControl: --- Selecting new region: 6
,08-29 10:24:20.453  6923  6923 I UEI.SmartControl: Model = LG-D855
08-29 10:24:20.454  6923  6923 D UEI.SmartControl: QS Service created
08-29 10:24:20.465  6923  6923 I UEI.SmartControl: Service initServices...
08-29 10:24:20.468  6923  6923 D UEI.SmartControl: QS start get config
,08-29 10:24:20.506  6923  6923 D UEI.SmartControl: Loading JNI Libs...
,08-29 10:24:20.734  6923  6923 I UEI.SmartControl: Supports setup maps: true
,08-29 10:24:20.737  6923  6923 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 10:24:20.737  6923  6923 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 10:24:20.737  6923  6923 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 10:24:20.738  6923  6923 I UEI.SmartControl: ### init IR Blaster...
08-29 10:24:20.743  6923  6923 D serial_port: Configuring serial port
08-29 10:24:20.747  6923  6923 E UEI.SmartControl: UEIBLaster setting for 616
08-29 10:24:20.747  6923  6923 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 10:24:20.747  6923  6923 I UEI.SmartControl: configuring settings for MAXQ616
08-29 10:24:20.747  6923  6923 I UEI.SmartControl: Get version...
08-29 10:24:20.764  6923  6947 D UEI.SmartControl: serial port data available: 21
,08-29 10:24:20.772  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:20.773  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37614455 added. We now have 6 listener(s)
08-29 10:24:20.773  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:20.775  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:20.775  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25fa2e6a added. We now have 7 listener(s)
08-29 10:24:20.775  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:20.776  5976  6039 I System.out: IsBluetoothEnabled
08-29 10:24:20.777  1029  1863 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:20.777  1029  1863 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-29 10:24:20.778  1029  1111 D BluetoothManagerService: Message: 2
,08-29 10:24:20.780  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:20.780  1029  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:20.780  1029  1045 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-29 10:24:20.793  6923  6923 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-29 10:24:20.796  1029  1111 D BluetoothManagerService: Message: 1
08-29 10:24:20.796  1029  1111 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 10:24:20.798  6923  6923 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 10:24:20.799  6923  6923 I UEI.SmartControl: QS saving settings...
08-29 10:24:20.799  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 10:24:20.799  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 10:24:20.800  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-29 10:24:20.807  6923  6923 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 10:24:20.824  6923  6947 D UEI.SmartControl: serial port data available: 4
,08-29 10:24:20.831  1029  1111 D BluetoothManagerService: Message: 20
08-29 10:24:20.831  1029  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1377925:true
08-29 10:24:20.831  6895  6895 D BluetoothAdapterState: make
08-29 10:24:20.835  6895  6895 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
,08-29 10:24:20.835  6895  6895 I bluedroid-qcom: init
08-29 10:24:20.836  6895  6952 I BluetoothAdapterState: Entering OffState
08-29 10:24:20.837  6895  6895 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 10:24:20.837  6895  6895 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 10:24:20.837  6895  6895 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 10:24:20.837  6895  6895 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 10:24:20.837  6895  6895 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 10:24:20.824  6955  6955 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:20.824  6955  6955 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:20.839  6895  6895 I bluedroid-qcom: get_profile_interface socket
08-29 10:24:20.839  6895  6895 I bluedroid-qcom: get_profile_interface map_client
08-29 10:24:20.842  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 10:24:20.843  6895  6956 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 10:24:20.843  6955  6955 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 10:24:20.843  6955  6955 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 10:24:20.843  6955  6955 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 10:24:20.843  1029  1111 D BluetoothManagerService: Message: 40
08-29 10:24:20.843  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 10:24:20.844  6895  6911 I bluedroid-qcom: config_hci_snoop_log
08-29 10:24:20.845  6895  6956 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 10:24:20.845  6955  6955 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 10:24:20.846  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 10:24:20.846  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 10:24:20.847  6895  6956 D BluetoothAdapterProperties: Name is: G3
,08-29 10:24:20.858  6923  6923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 10:24:20.858  6955  6955 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 10:24:20.858  6955  6955 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-29 10:24:20.861  6923  6923 E UEI.SmartControl: Services init done
08-29 10:24:20.861  6923  6923 D UEI.SmartControl: QS Service init finished
08-29 10:24:20.863  6923  6958 I UEI.SmartControl: Device manager: loading config....
08-29 10:24:20.864  6923  6958 D UEI.SmartControl: ----------- loading internal config...
08-29 10:24:20.865  6923  6923 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 10:24:20.865  6923  6923 D UEI.SmartControl: QS Service version code: 201091
08-29 10:24:20.865  6923  6923 D UEI.SmartControl: Service requested: Control
08-29 10:24:20.871  6923  6958 E UEI.SmartControl: Loading SETTINGS...
,08-29 10:24:20.875  6923  6923 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 10:24:20.878  6923  6923 D UEI.SmartControl: Internal service binding...
08-29 10:24:20.879  6272  6272 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 10:24:20.879  6923  6939 I UEI.SmartControl: ------ IControl API: 11
08-29 10:24:20.879  6923  6939 I UEI.SmartControl: Registering callback...
08-29 10:24:20.880  6923  6938 I UEI.SmartControl: ------ IControl API: 19
08-29 10:24:20.881  6923  6938 I UEI.SmartControl: Registering Services Ready callback...
08-29 10:24:20.925  6923  6958 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-29 10:24:20.939  6923  6957 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-29 10:24:20.940  6272  6287 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-29 10:24:20.941  6923  6957 D UEI.SmartControl: -----service ready thread exits
08-29 10:24:20.941  6272  6349 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 10:24:20.941  6272  6349 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 10:24:20.942  6272  6272 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 10:24:20.942  6272  6272 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 10:24:20.942  6923  6939 I UEI.SmartControl: ------ IControl API: 8
08-29 10:24:20.942  6272  6272 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 10:24:20.943  6272  6272 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 10:24:20.943  6272  6272 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 10:24:20.943  6272  6272 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 10:24:20.943  6272  6272 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 10:24:20.944  6272  6272 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-29 10:24:20.944  6272  6272 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 10:24:20.946  6272  6272 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 10:24:20.947  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 10:24:20.947  6272  6272 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 10:24:20.948  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 10:24:20.948  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 10:24:20.949  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-29 10:24:20.949  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 10:24:20.949  6272  6272 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472459060949]
08-29 10:24:20.958  6272  6960 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-29 10:24:20.961  6272  6272 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-29 10:24:20.962  6272  6272 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 10:24:20.962  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-29 10:24:20.962  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-29 10:24:20.962  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-29 10:24:20.962  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,08-29 10:24:20.963  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-29 10:24:20.964  6272  6272 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-29 10:24:20.982  1029  1111 I art     : Explicit concurrent mark sweep GC freed 32334(1564KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.287ms total 135.701ms
,08-29 10:24:20.985  1029  1111 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 10:24:20.985  1029  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-29 10:24:20.989  6895  6952 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 10:24:20.989  6895  6952 D BluetoothAdapterProperties: Setting state to 11
08-29 10:24:20.990  6895  6952 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 10:24:20.990  1029  1111 D BluetoothManagerService: Message: 60
08-29 10:24:20.990  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 10:24:20.990  1029  1111 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 10:24:20.991  6895  6952 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 10:24:20.993  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:20.993  6209  6209 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 10:24:20.993  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 10:24:20.997  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:21.001  6895  6895 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 10:24:21.002  6895  6895 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:21.002  6895  6895 V BluetoothPbapReceiver: ***********state = 11
08-29 10:24:21.005  2265  2265 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:24:21.012  6895  6952 D BluetoothBondStateMachine: make
,08-29 10:24:21.019  6895  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:21.019  6895  6961 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 10:24:21.020  6895  6952 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 10:24:21.020  6895  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:21.020  6895  6952 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 10:24:21.020  6895  6952 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 10:24:21.021  6209  6209 D BluetoothPermissionRequest: onReceive
08-29 10:24:21.023  6209  6209 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 10:24:21.030  6895  6952 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:21.032  6895  6895 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:21.035  6895  6895 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 10:24:21.035  6895  6895 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 10:24:21.035  6895  6895 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 10:24:21.035  6895  6895 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:21.035  6895  6895 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 10:24:21.043  6895  6952 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:21.044  6895  6895 D HeadsetService: Received start request. Starting profile...
08-29 10:24:21.045  6895  6895 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 10:24:21.045  6895  6895 D LGBluetoothHfpAdapter: Version 1.6
08-29 10:24:21.048  6895  6895 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 10:24:21.048  6895  6895 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 10:24:21.049  6895  6895 D HeadsetStateMachine: make
,08-29 10:24:21.053  6895  6952 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:21.060  6895  6952 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:21.065  6895  6952 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 10:24:21.070  6895  6952 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:21.075  6895  6952 E BluetoothAdapterService: File transfer profiles supported!!
08-29 10:24:21.086  6895  6952 V LGMDMManager: Create singleton instance
,08-29 10:24:21.088  6895  6952 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 10:24:21.102  6895  6895 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 10:24:21.102  6895  6895 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 10:24:21.106  6895  6895 D HeadsetStateMachine: max_hf_connections = 1
08-29 10:24:21.106  6895  6895 I bluedroid-qcom: get_profile_interface handsfree
08-29 10:24:21.108  6895  6895 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 10:24:21.109   336  2183 V AudioPolicyService: registerClient() client 0xb558a760, uid 1002
08-29 10:24:21.109   336  2180 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 10:24:21.109   336  2180 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 10:24:21.109   336  2180 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 10:24:21.109  6895  6895 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 10:24:21.110   336  1390 V AudioFlinger: registerClient() client 0xb1433850, pid 6895
08-29 10:24:21.110   336  1386 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:21.110   336  1386 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 10:24:21.110  3411  3431 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:21.110  3411  3431 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 10:24:21.110  1029  2026 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:21.110  1029  2026 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 10:24:21.111  6895  6895 V ToneGenerator: Create Track: 0xb4928a80
08-29 10:24:21.111  1595  1614 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:21.111  6895  6895 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
,08-29 10:24:21.111  1595  1614 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 10:24:21.111  6895  6895 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 10:24:21.111   336  2183 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 10:24:21.111   336  2183 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 10:24:21.111   336  2183 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 10:24:21.111   336  2183 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 10:24:21.111  6895  6912 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:21.111  6895  6912 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 10:24:21.111   336  1385 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:21.111   336  1385 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 10:24:21.111  6895  6895 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 10:24:21.112  1595  3468 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:21.112  1595  3468 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 10:24:21.112  1029  1863 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:21.112  1029  1863 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 10:24:21.112  3411  3430 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:21.112  3411  3430 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 10:24:21.112  6895  6912 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:21.112  1846  2722 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 10:24:21.112  1846  2722 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 10:24:21.112  6895  6912 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 10:24:21.112  1846  2722 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 10:24:21.112  1846  2722 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 10:24:21.112   336   336 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 10:24:21.112   336  2183 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 10:24:21.112   336  2183 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 10:24:21.112   336  2183 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 10:24:21.112   336  2183 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 10:24:21.112  6895  6895 V AudioSystem: getLatency() output 2, latency 50
08-29 10:24:21.112  6895  6895 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 10:24:21.112  6895  6895 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 10:24:21.113   336  1390 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 10:24:21.113   336  1390 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 10:24:21.113   336  1390 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 10:24:21.113   336  1390 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 10:24:21.113   336  1390 V AudioFlinger: createTrack() lSessionId: 21
08-29 10:24:21.114  6895  6895 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 10:24:21.115   336  1390 V AudioFlinger: acquiring 21 from 6895, for 6895
08-29 10:24:21.115   336  1390 V AudioFlinger:  added new entry for 21
08-29 10:24:21.115  6895  6895 V ToneGenerator: ToneGenerator INIT OK, time: 133640
08-29 10:24:21.115  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.Adapte,rService@3b9301f1
,08-29 10:24:21.116  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:21.118  6895  6895 D A2dpService: Received start request. Starting profile...
08-29 10:24:21.118  6895  6962 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 10:24:21.119  6895  6962 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 10:24:21.119  6895  6895 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 10:24:21.120  6895  6895 V Avrcp   : make
08-29 10:24:21.121  6895  6895 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 10:24:21.121  6895  6895 I bluedroid-qcom: get_profile_interface avrcp
08-29 10:24:21.121  6895  6962 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 10:24:21.121  6895  6962 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 10:24:21.122   336  2180 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6895
08-29 10:24:21.122   336  2180 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 10:24:21.122   336  2180 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 10:24:21.122   336  2180 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 10:24:21.122   336  2180 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 10:24:21.122   336  2180 V voice   : voice_set_parameters: exit with code(0)
08-29 10:24:21.122   336  2180 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 10:24:21.122   336  2180 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 10:24:21.122   336  2180 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 10:24:21.122   336  2180 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 10:24:21.122   336  2180 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 10:24:21.122   336  2180 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 10:24:21.123  6895  6962 V ToneGenerator: ToneGenerator destructor
08-29 10:24:21.123  6895  6962 V ToneGenerator: stopTone
08-29 10:24:21.123  6895  6962 V ToneGenerator: Delete Track: 0xb4928a80
08-29 10:24:21.123   336   336 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 10:24:21.123   336   336 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 10:24:21.123   336   336 V AudioFlinger: PlaybackThread::Track destructor
08-29 10:24:21.123   336  1266 V AudioPolicyService: AudioCommandThread() waking up
08-29 10:24:21.123   336  1266 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 10:24:21.123   336   336 V AudioFlinger: removeClient_l() pid 6895, calling pid 336
08-29 10:24:21.123   336  1266 V AudioPolicyManager: releaseOutput() 2
08-29 10:24:21.123   336  1266 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 10:24:21.123  6895  6962 V AudioTrack: ~AudioTrack, releasing session id from 6895 on behalf of 6895
08-29 10:24:21.123   336  1390 V AudioFlinger: releasing 21 from 6895 for 6895
08-29 10:24:21.123   336  1390 V AudioFlinger:  decremented refcount to 0
08-29 10:24:21.123   336  1390 V AudioFlinger: purging stale effects
08-29 10:24:21.129  6895  6895 V AudioManager: registerRemoteController: size of Media player list: 0
,08-29 10:24:21.133  6895  6895 E AudioManager: No RCC entry present to update
08-29 10:24:21.133  6895  6895 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 10:24:21.136  6895  6895 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 10:24:21.137  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 10:24:21.137  6895  6895 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 10:24:21.140  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 10:24:21.247  1029  1971 V SIM_STK : Menu title from STK is T-Mobile
08-29 10:24:21.247  1029  1971 V SIM_STK : Menu title from STK is T-Mobile
,08-29 10:24:21.349  1029  1728 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 10:24:21.363  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-29 10:24:21.369  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-29 10:24:21.372  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 10:24:21.372  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 10:24:21.372  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 10:24:21.372  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 10:24:21.372  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 10:24:21.372  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 10:24:21.372  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 10:24:21.373  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 10:24:21.373  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 10:24:21.373  6895  6895 I BluetoothA2dpServiceJni: classInitNative
08-29 10:24:21.374  6895  6895 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 10:24:21.374  6895  6895 D A2dpStateMachine: make
08-29 10:24:21.376  6895  6895 I bluedroid-qcom: get_profile_interface a2dp
08-29 10:24:21.376  6895  6984 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 10:24:21.379  6895  6895 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 10:24:21.379  6895  6895 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 10:24:21.381  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:21.382  6895  6895 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 10:24:21.386  6895  6983 D A2dpStateMachine: Enter Disconnected: -2
08-29 10:24:21.386  6895  6895 D HidService: Received start request. Starting profile...
08-29 10:24:21.387  6895  6895 I bluedroid-qcom: get_profile_interface hidhost
08-29 10:24:21.387  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:21.389  6895  6895 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 10:24:21.393  6895  6895 D HealthService: Received start request. Starting profile...
08-29 10:24:21.395  6895  6895 I bluedroid-qcom: get_profile_interface health
,08-29 10:24:21.396  6895  6895 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 10:24:21.396  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:21.397  6895  6895 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 10:24:21.399  6895  6895 D PanService: Received start request. Starting profile...
08-29 10:24:21.399  6895  6895 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 10:24:21.399  6895  6895 I bluedroid-qcom: get_profile_interface pan
08-29 10:24:21.407  6895  6895 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-29 10:24:21.407  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:21.408  6895  6895 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-29 10:24:21.416  6895  6895 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:24:21.416  6895  6895 D BtGatt.GattService: Received start request. Starting profile...
08-29 10:24:21.416  6895  6895 D BtGatt.GattService: start()
08-29 10:24:21.416  6895  6895 I bluedroid-qcom: get_profile_interface gatt
08-29 10:24:21.417  6895  6895 D BtGatt.AdvertiseManager: advertise manager created
08-29 10:24:21.423  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
,08-29 10:24:21.426  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:21.426  6895  6895 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 10:24:21.427  6895  6895 V BluetoothMapService: BluetoothMapBinder()
08-29 10:24:21.428  6895  6895 D BluetoothMapService: Received start request. Starting profile...
08-29 10:24:21.428  6895  6895 D BluetoothMapService: start()
08-29 10:24:21.431  6895  6895 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 10:24:21.431  6895  6895 D BluetoothMapEmailAppObserver: createReceiver()
08-29 10:24:21.433  6895  6895 D BluetoothMapEmailAppObserver: initObservers()
08-29 10:24:21.433  6895  6895 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-29 10:24:21.442  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:21.443  6895  6895 D HeadsetStateMachine: Proxy object connected
08-29 10:24:21.443  6895  6895 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 10:24:21.444  6895  6895 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-29 10:24:21.445  6895  6962 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-29 10:24:21.449  6895  6962 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 10:24:21.449  6895  6962 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 10:24:21.452  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 10:24:21.456  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 10:24:21.459  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 10:24:21.464  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 10:24:21.465  6895  6895 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 10:24:21.468  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 10:24:21.472  6895  6895 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 10:24:21.472  6895  6895 V BluetoothMapService: Handler(): got msg=1
,08-29 10:24:21.474  6895  6952 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 10:24:21.474  6895  6952 I bluedroid-qcom: enable
08-29 10:24:21.475  6895  6991 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 10:24:21.475  6895  6991 I bt-btu  : btu_task pending for preload complete event
08-29 10:24:21.475  6895  6952 I bt_hci_bdroid: init
08-29 10:24:21.477  6895  6952 I bt_vendor: bt-vendor : init
08-29 10:24:21.477  6895  6952 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 10:24:21.477  6895  6952 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 10:24:21.477  6895  6952 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 10:24:21.477  6895  6952 D bt_userial_mct: userial_init
08-29 10:24:21.477  6895  6952 D bt_hci_bdroid: set_power 1
08-29 10:24:21.477  6895  6952 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 10:24:21.477  6895  6952 I bt_vendor: Starting hciattach daemon
08-29 10:24:21.477  6895  6952 I bt_vendor: try to set true
08-29 10:24:21.464  6994  6994 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:21.464  6994  6994 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:21.507  6995  6995 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 10:24:21.591  7001  7001 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 10:24:21.603  7002  7002 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 10:24:21.629  7004  7004 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 10:24:21.642  7005  7005 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 10:24:21.654  7006  7006 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 10:24:21.666  7007  7007 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 10:24:21.688  7009  7009 I libmdmdetect: ESOC framework not supported
,08-29 10:24:21.690  7009  7009 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 10:24:21.700  7009  7009 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-29 10:24:21.700  7009  7009 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 10:24:21.700  7009  7009 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 10:24:21.700  7009  7009 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 10:24:21.700  7009  7009 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 10:24:21.700  7009  7009 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 10:24:21.700  7009  7009 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 10:24:21.735  7009  7010 E QC-QMI  : qmi_client [7009] 15: failed to locate client data
08-29 10:24:21.735   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 10:24:21.735   467   467 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-29 10:24:21.783  7011  7011 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 10:24:21.798  7012  7012 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 10:24:21.830  6895  6952 I bt_vendor: bluetooth satus is on
08-29 10:24:21.830  6895  6952 D bt_hci_bdroid: preload
,08-29 10:24:21.830  6895  6993 D bt_userial_mct: userial_open(port:0)
08-29 10:24:21.830  6895  6993 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 10:24:21.834  6895  6993 I bt_vendor: Done intiailizing UART
08-29 10:24:21.836  6895  6993 I bt_vendor: Done intiailizing UART
08-29 10:24:21.836  6895  6993 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 10:24:21.836  6895  6993 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 10:24:21.837  6895  6991 I bt-btu  : btu_task received preload complete event
08-29 10:24:21.837  6895  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 10:24:21.837  6895  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 10:24:21.839  6895  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 10:24:21.836  6895  7014 D bt_userial_mct: Entering userial_read_thread()
08-29 10:24:21.843  6895  6991 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 10:24:21.843  6895  6991 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 10:24:21.843  6895  6991 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 10:24:21.843  6895  6991 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 10:24:21.843  6895  6991 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 10:24:21.843  6895  6991 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 10:24:21.843  6895  6991 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 10:24:21.843  6895  6991 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 10:24:21.844  6895  6991 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 10:24:21.844  6895  6991 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 10:24:21.844  6895  6991 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 10:24:21.844  6895  6991 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 10:24:21.844  6895  6991 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 10:24:21.844  6895  6991 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 10:24:21.844  6895  6991 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 10:24:21.844  6895  6991 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 10:24:21.957  6895  6991 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-29 10:24:21.957  6895  6991 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0222061 
,08-29 10:24:21.957  6895  6991 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0222061 
,08-29 10:24:22.019  6895  6956 E bt-btif : Calling BTA_HhEnable
,08-29 10:24:22.019  6895  6956 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 10:24:22.020  6895  6956 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 10:24:22.032  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 10:24:22.033  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 10:24:22.035  6895  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 10:24:22.035  6895  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 10:24:22.035  6895  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 10:24:22.035  6895  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 10:24:22.035  6895  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 10:24:22.037  6895  6956 D BluetoothAdapterProperties: Name is: G3
08-29 10:24:22.043  6895  6956 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:24:22.044  6895  6956 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:24:22.044  6895  6956 D bt_hci_bdroid: postload
,08-29 10:24:22.048  6895  6993 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 10:24:22.049  6895  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 10:24:22.050  6895  6956 D bte_conf: Device ID record 1 : primary
08-29 10:24:22.050  6895  6956 D bte_conf:   vendorId            = 00c4
08-29 10:24:22.050  6895  6956 D bte_conf:   vendorIdSource      = 0001
08-29 10:24:22.050  6895  6956 D bte_conf:   product             = 13a1
08-29 10:24:22.050  6895  6956 D bte_conf:   version             = 1000
08-29 10:24:22.050  6895  6956 D bte_conf:   clientExecutableURL = 
08-29 10:24:22.050  6895  6956 D bte_conf:   serviceDescription  = 
08-29 10:24:22.050  6895  6956 D bte_conf:   documentationURL    = 
08-29 10:24:22.050  6895  6956 D bte_conf: bte_load_did_conf no section named DID2.
08-29 10:24:22.053  6895  6993 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 10:24:22.055  6895  6952 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 10:24:22.055  6895  6952 D BluetoothAdapterProperties: ScanMode =  20
08-29 10:24:22.055  6895  6952 D BluetoothAdapterProperties: State =  11
08-29 10:24:22.055  6895  6952 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 10:24:22.056  6895  6952 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 10:24:22.056  6895  6952 D BluetoothAdapterProperties: Setting state to 12
08-29 10:24:22.056  6895  6952 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 10:24:22.057  6895  6993 D bt_hci_bdroid: Used up Tx Cmd credits
,08-29 10:24:22.044  7019  7019 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:22.044  7019  7019 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:22.065  1029  1111 D BluetoothManagerService: Message: 60
08-29 10:24:22.067  6895  6952 I BluetoothAdapterState: Entering On State
08-29 10:24:22.068  6895  6991 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 10:24:22.068  6895  6991 W bt-smp  : Plain text(LSB ~ MSB) = 3b 68 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 10:24:22.068  6895  6991 W bt-smp  : Encrypted text(LSB ~ MSB) = 8d b0 a0 7a 0d 7d d0 6f d7 a8 d7 b0 ef 57 06 b8 
,08-29 10:24:22.070  6895  6993 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 10:24:22.070  6895  6991 W bt-btm  : Stopping oneshot timer
08-29 10:24:22.072  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 10:24:22.072  1029  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-29 10:24:22.073  6895  7014 E bt_mct  : hci lib postload completed
08-29 10:24:22.073  6895  6956 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 10:24:22.073  6895  6956 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 10:24:22.089  6895  6952 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 10:24:22.089  6895  6952 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 10:24:22.089  6895  6952 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-29 10:24:22.093  6895  6952 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 10:24:22.112  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:22.112  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:22.112  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:22.112  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:22.112  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:22.112  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:22.112  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:22.112  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:22.119  5976  5976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:22.120  6895  6952 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 10:24:22.125  6895  6991 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 10:24:22.125  6895  6991 W bt-smp  : Plain text(LSB ~ MSB) = 35 8d 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 10:24:22.125  6895  6991 W bt-smp  : Encrypted text(LSB ~ MSB) = 27 63 b6 f1 e2 cc 7a 97 cb 5d 48 f1 87 8a c9 94 
,08-29 10:24:22.128  6895  6991 W bt-btm  : Stopping oneshot timer
08-29 10:24:22.140  6895  6956 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:24:22.140  6895  6956 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-29 10:24:22.146  6895  6991 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 10:24:22.146  6895  6991 W bt-smp  : Plain text(LSB ~ MSB) = a5 1e 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 10:24:22.146  6895  6991 W bt-smp  : Encrypted text(LSB ~ MSB) = d2 4e aa 2d 9a f3 60 6c 69 34 e3 56 c1 79 c4 24 
08-29 10:24:22.146  6895  6991 W bt-btm  : Stopping oneshot timer
08-29 10:24:22.181  7024  7024 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 10:24:22.182  6209  6224 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 10:24:22.189  1029  1111 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:22.190  1846  1862 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:22.191  1029  1029 D BluetoothHeadset: Proxy object connected
08-29 10:24:22.193  6895  6991 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 10:24:22.193  6895  6991 W bt-smp  : Plain text(LSB ~ MSB) = 67 3c 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 10:24:22.193  6895  6991 W bt-smp  : Encrypted text(LSB ~ MSB) = ed 07 58 b5 ec 7c ec 78 ce f5 df 43 30 c2 b9 26 
08-29 10:24:22.194  6895  6991 W bt-btm  : Stopping oneshot timer
08-29 10:24:22.195  1846  1846 D BluetoothHeadset: Proxy object connected
08-29 10:24:22.196  6209  6225 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:24:22.198  6209  6209 D BluetoothHeadset: Proxy object connected
08-29 10:24:22.198  6209  6209 D HeadsetProfile: Bluetooth service connected
08-29 10:24:22.199  6209  6224 D BluetoothMap: onBluetoothStateChange: up=true
08-29 10:24:22.202  1029  1111 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:24:22.203  6209  6225 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:24:22.203  1029  1029 D BluetoothA2dp: Proxy object connected
08-29 10:24:22.204  6209  6209 D BluetoothMap: Proxy object connected
08-29 10:24:22.204  6209  6209 D MapProfile: Bluetooth service connected
08-29 10:24:22.204  6209  6209 D BluetoothMap: getConnectedDevices()
08-29 10:24:22.205  6895  7037 V BluetoothMapService: getConnectedDevices()
08-29 10:24:22.206  6209  6686 D BluetoothPan: onBluetoothStateChange on: true
08-29 10:24:22.206  6209  6686 D BluetoothPan: onBluetoothStateChange call bindService
08-29 10:24:22.207  6895  6991 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 10:24:22.207  6895  6991 W bt-smp  : Plain text(LSB ~ MSB) = 94 72 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 10:24:22.207  6895  6991 W bt-smp  : Encrypted text(LSB ~ MSB) = 11 04 40 05 d1 fb d7 57 bf da 2b 7f db dd f3 30 
08-29 10:24:22.207  6895  6991 W bt-btm  : Stopping oneshot timer
08-29 10:24:22.207  6209  6209 D BluetoothA2dp: Proxy object connected
08-29 10:24:22.207  6209  6209 D A2dpProfile: Bluetooth service connected
,08-29 10:24:22.210  6209  6224 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 10:24:22.213  6209  6209 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:24:22.213  6209  6209 D PanProfile: Bluetooth service connected
08-29 10:24:22.213  1846  2722 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:22.215  6209  6209 D BluetoothInputDevice: Proxy object connected
08-29 10:24:22.215  6209  6209 D HidProfile: Bluetooth service connected
08-29 10:24:22.216  1846  1846 D BluetoothHeadset: Proxy object connected
08-29 10:24:22.217  1846  1862 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:22.219  1846  1846 D BluetoothHeadset: Proxy object connected
,08-29 10:24:22.220  1029  1111 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 10:24:22.220  1029  1111 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 10:24:22.223  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:22.223  1935  2096 D LGBluetoothAPIService: Message: 1
08-29 10:24:22.223  1935  2096 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-29 10:24:22.224  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 10:24:22.232  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 10:24:22.234  1029  1111 D BluetoothManagerService: Message: 40
08-29 10:24:22.234  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-29 10:24:22.236  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:22.238  1935  2096 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-29 10:24:22.240  6895  6895 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:22.240  6895  6895 D BluetoothMapService: STATE_ON
08-29 10:24:22.242  6895  6895 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 10:24:22.242  6895  6895 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 10:24:22.246  1935  1935 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-29 10:24:22.249  1935  2096 D LGBluetoothAPIService: Message: 100
08-29 10:24:22.250  1935  2096 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 10:24:22.253  6209  6209 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 10:24:22.260  6209  6209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 10:24:22.262  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:22.262  6895  6895 V BluetoothPbapService: Pbap Service onCreate
08-29 10:24:22.262  6895  6895 V BluetoothPbapService: Starting PBAP service
08-29 10:24:22.263  6895  6895 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 10:24:22.263  6895  6895 V BluetoothMapService: Handler(): got msg=1
,08-29 10:24:22.264  6895  6895 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 10:24:22.265  6895  6895 V BluetoothPbapService: Pbap Service onBind
08-29 10:24:22.266  6895  6895 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:22.266  6895  6895 V BluetoothPbapService: state: 12
08-29 10:24:22.267  6895  6895 V BluetoothPbapService: Handler(): got msg=1
08-29 10:24:22.267  6895  7043 D BluetoothMapMasInstance: MAS initSocket()
08-29 10:24:22.268  6895  7043 D BluetoothMapMasInstance:   masId = 00
08-29 10:24:22.268  6895  7043 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 10:24:22.268  6895  7043 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 10:24:22.268  6895  7043 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 10:24:22.268  6895  6895 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 10:24:22.269  1029  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:22.269  6895  6895 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 10:24:22.269  6895  6895 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:22.269  6895  6895 V BluetoothPbapReceiver: ***********state = 12
08-29 10:24:22.270  6895  7045 V BluetoothPbapService: Pbap Service initSocket
08-29 10:24:22.270  6895  7043 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:22.270  1029  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:22.272  6895  7043 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 10:24:22.273  6895  7043 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 10:24:22.273  6895  7043 D BluetoothMapMasInstance: Accepting socket connection...
,08-29 10:24:22.274  2265  2265 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:24:22.275  6895  6956 D BluetoothAdapterProperties: Scan Mode:21
08-29 10:24:22.275  6895  6956 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 10:24:22.276  2265  2265 D c       : Getting all permits...
08-29 10:24:22.276  2265  2265 D a       : Opening database...
08-29 10:24:22.276  6209  6209 D DockEventReceiver: finishStartingService: stopping service
08-29 10:24:22.277  6209  6209 D BluetoothPbap: Proxy object connected
08-29 10:24:22.278  6209  6209 D PbapServerProfile: Bluetooth service connected
08-29 10:24:22.278  6895  7045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:22.280  2265  2265 D a       : Opening database auth.proximity.permit_store...
08-29 10:24:22.280  6895  7045 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 10:24:22.281  6895  7045 V BluetoothPbapService: Succeed to create listening socket 
08-29 10:24:22.281  6895  7045 V BluetoothPbapService: Accepting socket connection...
08-29 10:24:22.281  2265  2265 D a       : Closing database...
08-29 10:24:22.284  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:22.289  6209  6209 D BluetoothPermissionRequest: onReceive
08-29 10:24:22.291  6209  6209 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 10:24:22.292  6209  6209 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 10:24:22.295  6895  6895 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 10:24:22.296  6895  6895 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-29 10:24:22.300  6895  6895 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-29 10:24:22.316  6895  6895 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 10:24:22.316  6895  6895 V BtOppService: onCreate
,08-29 10:24:22.319  6895  6895 V BluetoothOppNotification: send message
08-29 10:24:22.322  6895  6895 V BtOppService: Starting RfcommListener
08-29 10:24:22.325  6895  6895 D BluetoothOppPreference: Dumping Names:  
08-29 10:24:22.325  6895  6895 D BluetoothOppPreference: {}
08-29 10:24:22.325  6895  6895 D BluetoothOppPreference: Dumping Channels:  
08-29 10:24:22.325  6895  6895 D BluetoothOppPreference: {}
08-29 10:24:22.326  6895  6895 V BtOppService: onStartCommand
08-29 10:24:22.329  6895  6895 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:22.329  6895  7052 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 10:24:22.329  6895  6895 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-29 10:24:22.332  6895  7049 V BtOppService: Deleted complete outbound shares, number =  0
08-29 10:24:22.332  6895  6895 V BluetoothOppNotification: new notify threadi!
08-29 10:24:22.333  6895  7052 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 10:24:22.333  6895  6895 V BluetoothOppNotification: send delay message
08-29 10:24:22.333  6895  6895 V BtOppService: start RfcommListener
08-29 10:24:22.333  6895  7049 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 10:24:22.334  6895  7049 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 10:24:22.335  6895  7053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 10:24:22.335  6895  7049 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@138dca72 on behalf of 
08-29 10:24:22.336  6895  7053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d3a1ec3 on behalf of 
08-29 10:24:22.336  6895  6895 V BtOppService: RfcommListener started
08-29 10:24:22.337  6895  6895 V BtOppService: ContentObserver received notification
08-29 10:24:22.340  6895  7054 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 10:24:22.340  1029  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:22.340  6895  7052 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24f0b340 on behalf of 
08-29 10:24:22.341  6895  7053 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-29 10:24:22.343  6895  7054 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:22.345  6895  7053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 10:24:22.347  6895  7054 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-29 10:24:22.347  6895  7054 V BtOppRfcommListener: Started RFCOMM listener....
08-29 10:24:22.347  6895  7054 I BtOppRfcommListener: Accept thread started.
08-29 10:24:22.348  6895  7054 V BtOppRfcommListener: Accepting connection...
08-29 10:24:22.349  6895  7052 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 10:24:22.349  6895  7052 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 10:24:22.349  6895  7053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@349a0279 on behalf of 
08-29 10:24:22.350  6895  7053 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 10:24:22.352  6895  7052 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34ea1bbe on behalf of 
08-29 10:24:22.353  6895  7052 V BluetoothOppNotification: update too frequent, put in queue
,08-29 10:24:22.354  6895  7053 V BluetoothOppNotification: outbound notification was removed.
08-29 10:24:22.354  6895  7052 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 10:24:22.354  6895  7053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 10:24:22.356  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
08-29 10:24:22.356  6895  6895 V BluetoothFtpService: Ftp Service onCreate
08-29 10:24:22.356  6895  6895 I BluetoothFtpService: Ftp Service onCreate
08-29 10:24:22.357  6895  6895 V BluetoothFtpService: Ftp Service onStartCommand
08-29 10:24:22.357  6895  6895 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:22.357  6895  7053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26cdc36c on behalf of 
08-29 10:24:22.357  6895  6895 V BluetoothFtpService: Starting Listening on sockets
08-29 10:24:22.357  6895  6895 V BtOppService: ContentObserver received notification
,08-29 10:24:22.358  6895  6895 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 10:24:22.358  6895  6895 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 10:24:22.358  6895  6895 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 10:24:22.358  6895  6895 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:22.358  6895  6895 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 10:24:22.358  6895  6895 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 10:24:22.359  6895  7055 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 10:24:22.359  6895  7055 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 10:24:22.360  6895  7053 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 10:24:22.361  6895  7055 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8af4d35 on behalf of 
08-29 10:24:22.362  6895  6895 V BluetoothFtpService: Handler(): got msg=1
08-29 10:24:22.362  6895  7055 V BluetoothOppNotification: update too frequent, put in queue
08-29 10:24:22.362  6895  6895 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 10:24:22.363  6895  6895 V BluetoothFtpService: Ftp Service initSocket
08-29 10:24:22.363  6895  7055 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 10:24:22.366  6895  7053 V BluetoothOppNotification: inbound notification was removed.
08-29 10:24:22.366  6895  7053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-29 10:24:22.368  6895  7053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@82835ca on behalf of 
08-29 10:24:22.369  1029  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:22.371  6895  6895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:22.372  6895  6895 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-29 10:24:22.373  6895  6895 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 10:24:22.376  6895  7056 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 10:24:22.389  6895  6895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9301f1
,08-29 10:24:22.389  6895  6895 V BluetoothSapService: Sap Service onCreate
08-29 10:24:22.391  6895  6895 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:22.391  6895  6895 V BluetoothSapService: state: 12
08-29 10:24:22.391  6895  6895 V BluetoothSapService: Starting SAP server process
08-29 10:24:22.392  6895  6895 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 10:24:22.374  7057  7057 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:22.374  7057  7057 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:22.395  6895  7058 V BluetoothSapService: Sap Service initRfcommSocket
08-29 10:24:22.395  1029  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 10:24:22.396  6895  7058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:22.398  6895  7058 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-29 10:24:22.398  6895  7058 V BluetoothSapService: Succeed to create listening socket 
08-29 10:24:22.398  6895  7058 V BluetoothSapService: Accepting socket connection...
08-29 10:24:22.410  7057  7057 V BT_SAP  : Event pipe created
08-29 10:24:22.410  7057  7057 V BT_SAP  : create_server_socket qcom.sap.server
08-29 10:24:22.410  7057  7057 V BT_SAP  : created socket fd 6
,08-29 10:24:22.822  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:22.822  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:22.822  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:22.822  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:22.822  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:22.822  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:22.822  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:22.822  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:22.830  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:22.832  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:22.832  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35a63f5b added. We now have 8 listener(s)
08-29 10:24:22.832  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:22.835  1029  2026 D WifiServiceImplEx: setWifiEnabled: false pid=5976, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 10:24:22.836  1029  2026 D WifiService: setWifiEnabled: false pid=5976, uid=10118
08-29 10:24:22.836  1029  2026 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 10:24:22.841  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:22.847  1029  1953 D WifiServiceImplEx: setWifiEnabled: true pid=5976, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 10:24:22.848  1029  1953 D WifiService: setWifiEnabled: true pid=5976, uid=10118
08-29 10:24:22.848  1029  1953 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 10:24:22.864  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 10:24:22.865  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 10:24:22.865  1029  1029 D Ulp_jni : JNI:system_update. Event-4
,08-29 10:24:22.868  1029  1384 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-29 10:24:22.869  1029  1384 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-29 10:24:22.871  1029  1384 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 10:24:22.871  1029  1384 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 10:24:22.872  1029  1384 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 10:24:22.872  1029  1384 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 10:24:22.872  1029  1384 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 10:24:22.872  1029  1384 E WifiHW  : unknown target_country: EU , set to default
08-29 10:24:22.872  1029  1384 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 10:24:22.872  1029  1384 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 10:24:22.872  1029  1384 I WifiUtil: gEnableBmps=1
08-29 10:24:23.336  6895  6895 V BluetoothOppNotification: new notify threadi!
08-29 10:24:23.337  6895  6895 V BluetoothOppNotification: send delay message
,08-29 10:24:23.349  6895  7077 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 10:24:23.352  6895  7077 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@227be496 on behalf of 
08-29 10:24:23.353  6895  7077 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 10:24:23.357  6895  7077 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-29 10:24:23.362  6895  7077 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@106a3817 on behalf of 
08-29 10:24:23.364  6895  7077 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 10:24:23.367  6895  7077 V BluetoothOppNotification: outbound notification was removed.
08-29 10:24:23.367  6895  7077 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 10:24:23.368  6895  7077 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@131b1404 on behalf of 
08-29 10:24:23.369  6895  7077 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 10:24:23.372  6895  7077 V BluetoothOppNotification: inbound notification was removed.
,08-29 10:24:23.372  6895  7077 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 10:24:23.374  6895  7077 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21b8eded on behalf of 
,08-29 10:24:23.463   330   887 D SoftapController: Softap fwReload - Ok
,08-29 10:24:23.471  1029  1384 E NetdConnector: NDC Command {66 softap fwreload wlan0 STA} took too long (595ms)
08-29 10:24:23.485  1029  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 10:24:23.485  1029  1111 D Tethering: InitialState.processMessage what=4
08-29 10:24:23.486  1029  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 10:24:23.496   330   887 D CommandListener: Setting iface cfg
08-29 10:24:23.496   330   887 D CommandListener: Trying to bring down wlan0
08-29 10:24:23.505   330   887 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:24:23.508   330  7079 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 10:24:23.521  1029  1384 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-29 10:24:23.523  1029  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 10:24:23.535  1029  1384 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 10:24:23.535  1029  1384 E WifiStateMachine: useWiFiOffloading() : false
08-29 10:24:23.535  1029  1384 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-29 10:24:23.524  7080  7080 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:23.524  7080  7080 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:23.555  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-29 10:24:23.566  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:23.567  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-29 10:24:23.575  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:23.584  1029  1384 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 10:24:23.584  1029  1384 D WifiMonitor: connecting to supplicant
,08-29 10:24:23.606  7080  7080 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 10:24:23.617  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 10:24:23.617  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 10:24:23.617  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 10:24:23.618  6209  6209 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 10:24:23.620  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 10:24:23.621  6209  6209 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-29 10:24:23.622  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 10:24:23.622  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 10:24:23.622  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 10:24:23.622  6209  6209 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 10:24:23.622  6209  6209 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 10:24:23.628  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 10:24:23.629  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 10:24:23.629  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 10:24:23.629  6209  6209 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 10:24:23.630  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 10:24:23.632  6209  6209 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 10:24:23.632  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 10:24:23.632  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 10:24:23.632  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 10:24:23.632  6209  6209 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 10:24:23.632  6209  6209 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 10:24:23.647  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 10:24:23.653  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 10:24:23.660  6314  7098 V FormManager: Network unavailable.
,08-29 10:24:23.660  7080  7080 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 10:24:23.661  7080  7080 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-29 10:24:23.666  6314  7097 W FormManager: Network not available. Please check & try again.
08-29 10:24:23.668  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:23.669  6314  7098 V FormManager: Network unavailable.
08-29 10:24:23.737  7080  7080 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 10:24:23.758  7080  7080 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 10:24:23.764  7080  7080 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-29 10:24:23.766  1029  1384 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 10:24:23.766  1029  1384 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 10:24:23.767  1029  1384 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 10:24:23.767  1029  1384 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 10:24:23.768  1029  1384 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:23.768  1029  7102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 10:24:23.768  1029  1384 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:23.768  1029  7102 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 10:24:23.769  1029  1384 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 10:24:23.769  1029  1384 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 10:24:23.769  1029  1384 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 10:24:23.770  1029  1384 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 10:24:23.770  1029  1384 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 10:24:23.771  1029  1384 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 10:24:23.771  1029  1384 E WifiStateMachine: useWiFiOffloading() : false
08-29 10:24:23.771  1029  1384 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 10:24:23.771  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:23.771  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:23.771  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:23.771  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:23.771  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 10:24:23.773  1935  1935 D WfdService: Waiting for WifiP2p enabling
08-29 10:24:23.775  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 10:24:23.777  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-29 10:24:23.777  1029  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 10:24:23.778  1029  1384 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 10:24:23.779  1029  1384 D WifiNative-wlan0: SET update_config 1: returned true
08-29 10:24:23.779  1029  1384 D WifiConfigStore: Loading config and enabling all networks 
08-29 10:24:23.779  1029  1384 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 10:24:23.779  1029  1384 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 10:24:23.786  1029  1384 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 10:24:23.788  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:23.788  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:23.788  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:23.788  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:23.788  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:23.788  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:23.788  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:23.788  5976  5976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:23.792  5976  5976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:23.796  7080  7080 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 10:24:23.796  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 10:24:23.796  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 10:24:23.796  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 10:24:23.796  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 10:24:23.796  1029  7102 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 10:24:23.796  1029  7102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 10:24:23.798  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 10:24:23.799  1029  1384 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 10:24:23.799  1029  1384 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 10:24:23.804  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 10:24:23.807  1029  1384 D WifiStateMachine: enableVerboseLogging : level 2
08-29 10:24:23.807  1029  1384 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-29 10:24:23.808  1029  1384 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 10:24:23.808  1029  1384 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 10:24:23.808  1029  1384 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 10:24:23.808  1029  1384 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 10:24:23.809  1029  1384 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 10:24:23.809  1029  1384 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 10:24:23.810  1029  1384 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 10:24:23.810  1029  1384 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 10:24:23.810  1029  1384 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 10:24:23.810  1029  1384 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 10:24:23.811  1029  1384 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 10:24:23.811  1029  1384 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 10:24:23.811  1029  1384 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 10:24:23.812  1029  1384 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 10:24:23.812  1029  1384 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 10:24:23.812  1935  1935 D WfdsService: Supplicant Connection state is changed : true
,08-29 10:24:23.812  1935  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 10:24:23.812  1029  1384 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 10:24:23.812  1029  1384 D WifiNative-HAL: Setting external_sim to 1
08-29 10:24:23.812  1935  2295 D WfdsService: Set the WFDS Monitor: true
08-29 10:24:23.812  1029  1384 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 10:24:23.812  1935  2295 D WfdsMonitor: WfdsMonitorThread create
08-29 10:24:23.813  1935  2295 D WfdsMonitor: WFDS Monitor is created and started
08-29 10:24:23.813  1935  2295 D WfdsService: WiFi: Supplicant connection re-established
08-29 10:24:23.813  1029  1384 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 10:24:23.813  1029  1384 I WifiNative-HAL: startHal
08-29 10:24:23.813  1029  1384 D wifi    : setting scan oui 0xaf66f0a0
08-29 10:24:23.813  6314  7104 W FormManager: Network not available. Please check & try again.
08-29 10:24:23.813  1029  1384 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 10:24:23.813  1029  1384 I WifiNative-HAL: startHal
08-29 10:24:23.813  1029  1384 D wifi    : setting scan oui 0xaf66f0a0
08-29 10:24:23.814  1029  1384 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 10:24:23.815  1029  1384 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 10:24:23.815  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 10:24:23.815  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 10:24:23.815  1029  1384 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 10:24:23.816  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 10:24:23.816  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-29 10:24:23.816  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 10:24:23.816  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 10:24:23.816  1935  7106 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 10:24:23.816  6314  7105 V FormManager: Network unavailable.
08-29 10:24:23.817  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 10:24:23.817  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 10:24:23.817  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 10:24:23.817  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 10:24:23.818  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 10:24:23.818  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 10:24:23.818  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 10:24:23.818  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:23.818  6314  7105 V FormManager: Network unavailable.
08-29 10:24:23.820  1935  7106 E CtrlSupplicant: Succeed to open control connection
08-29 10:24:23.820  1935  7106 E CtrlSupplicant: Succeed to open monitor connection
08-29 10:24:23.821  1935  7106 D WfdsMonitor: Supplicant connection established
08-29 10:24:23.821  1935  2295 D WfdsService: Connected to the supplicant for wfds
,08-29 10:24:23.822  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 10:24:23.822  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 10:24:23.823  7080  7080 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 10:24:23.824  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 10:24:23.824  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 10:24:23.825  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 10:24:23.825  1029  1384 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 10:24:23.826  1029  1384 E WifiNative: : [136,338,775 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 10:24:23.826  1029  1384 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 10:24:23.826  1029  1384 D WifiNative-wlan0: RECONNECT: returned true
08-29 10:24:23.826  1029  1384 D WifiNative-wlan0: doString: [STATUS]
08-29 10:24:23.827  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 10:24:23.827  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 10:24:23.827  1029  1384 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 10:24:23.827  1029  1384 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 10:24:23.827  1029  1384 D WifiNative-wlan0: SET ps 1: returned true
08-29 10:24:23.827  1029  1383 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.829   330   887 D CommandListener: Setting iface cfg
08-29 10:24:23.829   330   887 D CommandListener: Trying to bring up p2p0
08-29 10:24:23.829  1029  1383 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 10:24:23.829  1029  1383 D LGWifiP2pService: P2pEnablingState
08-29 10:24:23.829  1029  1383 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.829  1029  1383 D LGWifiP2pService: P2p socket connection successful
08-29 10:24:23.829  1029  1383 D LGWifiP2pService: P2pEnabledState
08-29 10:24:23.830  1029  1383 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 10:24:23.831  1029  1384 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,08-29 10:24:23.832  1029  1384 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 10:24:23.832  1029  1384 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 10:24:23.833  1029  1384 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 10:24:23.833  1029  1384 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 10:24:23.831  1029  1383 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 10:24:23.833  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 10:24:23.834  1029  1384 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 10:24:23.834  1029  1383 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 10:24:23.834  1029  1384 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 10:24:23.834  1029  1384 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 10:24:23.834  1029  1383 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 10:24:23.834  7080  7080 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 10:24:23.835  1029  1383 D WifiNative-p2p0: SET device_name G3: returned true
08-29 10:24:23.835  1029  1383 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 10:24:23.835  1029  1383 D LGWifiP2pService: before postfix = G3
08-29 10:24:23.835  1029  1383 D WifiServerServiceExt: postfix byte check : 2
08-29 10:24:23.835  1029  1383 D LGWifiP2pService: after postfix = G3
08-29 10:24:23.835  1029  1383 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 10:24:23.835  1029  1384 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 10:24:23.835  1029  1383 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 10:24:23.835  1029  1383 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 10:24:23.835  1935  1935 D WfdsService: WifiP2pState is changed : true
08-29 10:24:23.835  1029  1383 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 10:24:23.835  1029  1384 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 10:24:23.835  1029  1383 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 10:24:23.835  1935  1935 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 10:24:23.836  1029  1383 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 10:24:23.836  1029  1383 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 10:24:23.836  1935  2295 D WfdsService: Receive the WFDS_ENABLE Method
08-29 10:24:23.836  1935  2295 D WfdsService: Set the WFDS Monitor: true
08-29 10:24:23.836  1029  1383 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 10:24:23.836  1029  1383 D WifiNative-HAL: p2pGetDeviceAddress
08-29 10:24:23.836  1935  2295 D WfdsService: Connected to the supplicant for wfds
08-29 10:24:23.836  1935  2295 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 10:24:23.836  7080  7080 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 10:24:23.836  1029  1383 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 10:24:23.836  1935  1935 D WfdsService: isConnected: false
08-29 10:24:23.837  1935  2295 D WfdsService: selectPreferredScanChannel [36]
08-29 10:24:23.837  1935  2295 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 10:24:23.837  1029  1384 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 10:24:23.837  1029  1383 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 10:24:23.837  1029  1384 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 10:24:23.837  1029  1383 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 10:24:23.837  7080  7080 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 10:24:23.837  1029  1383 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 10:24:23.837  1029  1383 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 10:24:23.838  1029  1383 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
0,8-29 10:24:23.838  1029  1383 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 10:24:23.838  1029  1383 D WifiNative-p2p0:    returned OK
08-29 10:24:23.838  1029  1383 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 10:24:23.838  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 10:24:23.838  1029  1029 D RttService: SCAN_AVAILABLE : 3
08-29 10:24:23.838  1029  1549 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.838  1029  1549 I WifiNative-HAL: startHal
08-29 10:24:23.838  1029  1550 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.839  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=136352  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 10:24:23.839  1935  1935 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 10:24:23.839  1935  1935 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 10:24:23.840  1935  1935 D WfdsService: Update P2p Interface State: 3
08-29 10:24:23.842  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 10:24:23.842  4258  4258 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 10:24:23.843  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=136356  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 10:24:23.844  1029  1384 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 10:24:23.844  1029  1384 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 10:24:23.845  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 10:24:23.845  1029  1384 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 10:24:23.845  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 10:24:23.845  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:23.846  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:23.846  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 10:24:23.846  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:23.846  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:23.847  1029  1383 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 10:24:23.848  1029  1383 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 10:24:23.848  1029  1549 D wifi    : getting scan capabilities on interface[1] = 0xaf66f0a0
08-29 10:24:23.848  1029  1549 D wifi    : failed to get capabilities : -3
08-29 10:24:23.848  1029  1549 E WifiScanningService: could not get scan capabilities
08-29 10:24:23.849  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:23.850  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 10:24:23.850  7080  7080 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:23.850  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 10:24:23.850  1029  1383 D LGWifiP2pService: InactiveState
08-29 10:24:23.850  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:23.850  1029  7102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:23.850  1029  7102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:23.850  1029  1383 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.851  7080  7080 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 10:24:23.850  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.851  7080  7080 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-29 10:24:23.851  1029  1383 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 10:24:23.851  4258  4258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 10:24:23.852  7080  7080 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.852  1935  7106 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:23.852  1935  7106 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:23.853  1029  1384 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 10:24:23.853  1029  7102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:23.853  1029  7102 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.853  1029  7102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.853  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 10:24:23.853  1029  7102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.853  1029  7102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:23.853  1029  7102 E WifiMonitor: WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.853  1029  7102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.853  7080  7080 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:23.854  7080  7080 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 10:24:23.854  7080  7080 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.854  1029  1383 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 10:24:23.855  1029  1383 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.855  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.855  1029  1383 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.855  7080  7080 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.856  1935  7106 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 10:24:23.856  1935  7106 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:23.856  1935  7106 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:23.856  1029  1384 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 10:24:23.857  1029  1384 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 10:24:23.857  1029  1384 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 10:24:23.857  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 10:24:23.857  4258  7107 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 10:24:23.857  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 10:24:23.857  7080  7080 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 10:24:23.853  1029  7102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.858  1029  7102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 10:24:23.858  1029  7102 E WifiMonitor:, WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:23.858  1029  7102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:23.858  1029  7102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 10:24:23.858  1029  7102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:23.858  1029  7102 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.858  1029  7102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.858  1029  7102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.858  1029  7102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 10:24:23.858  1029  7102 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.858  1029  7102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.858  1029  7102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 10:24:23.858  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 10:24:23.858  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 10:24:23.859  1029  7102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 10:24:23.859  1029  7102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 10:24:23.859  1029  1384 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 10:24:23.859  1029  1384 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 10:24:23.859  1029  1384 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 10:24:23.859  1029  1384 D WifiNative-wlan0: doBoolean: SCAN
08-29 10:24:23.859  1029  1384 D WifiNative-wlan0: SCAN: returned false
08-29 10:24:23.860  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=136373  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 10:24:23.861  4258  7108 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 10:24:23.861  4258  7108 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 10:24:23.861  1029  1383 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.862  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.862  1029  1383 D LGWifiP2pService: DefaultState{ when=-11ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.862  1029  1383 D LGWifiP2pService: InactiveState{ when=-9ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.862  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.862  1029  1383 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.862  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.862  1029  1383 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.862  1935  2295 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 10:24:23.862  1029  1383 D LGWifiP2pService: InactiveState{ when=-8ms what=139283 arg2=6 target=com.android.internal.util.StateMac,hine$SmHandler }
08-29 10:24:23.862  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.862  1029  1383 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:23.862  1029  1029 E WifiServerServiceExt: No p2p device connected
08-29 10:24:23.880  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:23.880  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:23.880  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:23.880  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:23.880  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:23.880  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:23.880  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:23.880  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:23.882  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:23.886  5976  6039 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 10:24:23.887  5976  6039 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 10:24:23.889  5976  6039 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c3053e5 Bundle[{}]
08-29 10:24:23.890  5976  6039 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 10:24:23.890  5976  6039 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 10:24:23.891  5976  6039 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 10:24:23.891  5976  6039 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 10:24:23.892  5976  6039 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 10:24:23.892  1029  2026 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7109 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-29 10:24:23.893  5976  6039 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 10:24:23.895  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=136409  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 10:24:23.896  1029  1384 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 10:24:23.897  1029  1384 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 10:24:23.897  1029  1384 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 10:24:23.897  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:23.898  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:23.898  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 10:24:23.898  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:23.898  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:23.898  1029  1384 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 10:24:23.898  1029  1384 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 10:24:23.899  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:23.899  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:23.899  1029  1029 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 10:24:23.899  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:23.900  1029  1029 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 10:24:23.902  5976  6039 I System.out: Running OutgoingSocketThread
08-29 10:24:23.903  5976  7120 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 770)
08-29 10:24:23.904  5976  7120 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39920
08-29 10:24:23.905  5976  7120 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 10:24:23.962  7109  7109 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 10:24:23.962  7109  7109 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 10:24:23.970  7109  7109 V [BNRBootReceiver]: Boot Receiver Return
08-29 10:24:23.970  7109  7109 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 10:24:23.977  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 10:24:23.991  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:23.999  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:24.005  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 10:24:24.005  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:24.006  6272  6272 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 10:24:24.009  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:24.014  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:24.020  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 10:24:24.028  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 10:24:24.028  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:24.029  6272  6272 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 10:24:24.031  1029  1952 I ActivityManager: Killing 6558:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-29 10:24:24.099  1029  1568 W libprocessgroup: failed to open /acct/uid_10011/pid_6558/cgroup.procs: No such file or directory
,08-29 10:24:24.470  7080  7080 E wpa_supplicant: USIM:  scard_init function
,08-29 10:24:24.471  7080  7080 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-29 10:24:24.482  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 10:24:24.483  1029  7102 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 10:24:24.483  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 10:24:24.483  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: WPS-AP-AVAILABLE 
08-29 10:24:24.483  1029  7102 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 10:24:24.484  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 10:24:24.484  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 10:24:24.491  1029  1384 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 10:24:24.491  1029  1384 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 10:24:24.492  1029  1384 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 10:24:24.492  1029  1384 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 10:24:24.492  1029  1384 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-29 10:24:24.509  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=137023  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 10:24:24.516  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:24.516  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:24.518  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:24.523  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.523  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.523  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-29 10:24:24.527  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=137040  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 10:24:24.528  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:24.528  1029  1029 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 10:24:24.533  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-29 10:24:24.545  6209  6209 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 10:24:24.550  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 10:24:24.562  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:24.570  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:24.578  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:24.579  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:24.579  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 10:24:24.601  7080  7080 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 10:24:24.609  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 10:24:24.609  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 10:24:24.610  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 10:24:24.610  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 10:24:24.610  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 10:24:24.610  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 10:24:24.612  7080  7080 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 10:24:24.612  7080  7080 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 10:24:24.618  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=137131  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 10:24:24.619  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=137132  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-29 10:24:24.624  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 10:24:24.625  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 10:24:24.626  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 10:24:24.626  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 10:24:24.626  1029  7102 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 10:24:24.626  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 10:24:24.626  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 10:24:24.626  1029  7102 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 10:24:24.626  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 10:24:24.626  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 10:24:24.628  1029  1384 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137141
08-29 10:24:24.628  1029  1384 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137141
08-29 10:24:24.629  1029  1384 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137142
08-29 10:24:24.629  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137142
08-29 10:24:24.629  1029  1384 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137143
08-29 10:24:24.630  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=137143  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 10:24:24.635  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.635  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.635  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-29 10:24:24.640  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:24.641  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:24.644  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:24.649  1029  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 10:24:24.671  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 10:24:24.671  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 10:24:24.679  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:24.679  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:24.680  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=137193  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 10:24:24.681  1029  1384 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=137194  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 10:24:24.682  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=137195  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 10:24:24.685  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.685  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.685  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 10:24:24.695  1029  1384 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=137209
08-29 10:24:24.696  1029  1384 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=137209
08-29 10:24:24.696  1029  1384 D WifiNative-wlan0: doString: [STATUS]
,08-29 10:24:24.697  1029  7102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 10:24:24.697  1029  7102 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 10:24:24.698  1029  1384 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 10:24:24.698  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:24.698  1029  1029 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 10:24:24.699  1029  1384 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 10:24:24.704  1029  1384 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 10:24:24.704  1029  1384 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-29 10:24:24.713  1029  1384 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 10:24:24.714  1029  1384 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:24:24.714  1029  1384 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 10:24:24.714  1029  1439 D ConnectivityService: Got NetworkAgent Messenger
08-29 10:24:24.714  1029  1384 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 10:24:24.714  1029  1384 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 10:24:24.714  1029  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 10:24:24.715  1029  1439 D ConnectivityService: NetworkAgent connected
,08-29 10:24:24.716  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.716  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.716  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 10:24:24.717  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:24.717  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:24.719  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:24.721  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:24.721  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:24.722  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.722  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.722  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 10:24:24.723  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:24.724  1029  1384 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 10:24:24.724  1029  1384 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:24:24.724  1029  1384 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-29 10:24:24.725  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:24.725  1029  1384 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 10:24:24.725  1029  1384 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 10:24:24.730  1029  1384 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 10:24:24.731  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:24.732   330   887 D CommandListener: Setting iface cfg
08-29 10:24:24.734  1029  1384 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 10:24:24.735  1029  1384 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=137248  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:24.736  1029  1384 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=137249  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:24.736  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=137249  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:24.737  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,08-29 10:24:24.737  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:24.737  1029  1384 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:24.738  1029  1384 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:24.738  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:24.738  1029  7155 D DhcpStateMachine: StoppedState
08-29 10:24:24.739  1029  7155 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:24.739  1029  1384 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 10:24:24.739  1029  7155 D DhcpStateMachine: WaitBeforeStartState
08-29 10:24:24.739  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:24.739  1029  1029 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 10:24:24.740  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:24.740  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:24.740  1029  1384 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=137254  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:24.741  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:24.741  1029  1384 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=137254  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:24.741  1029  1384 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=137255  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 10:24:24.741  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:24.742  1029  1029 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 10:24:24.743  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14250] from screen [on:0 period:-714717785] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 10:24:24.744  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-714717784] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 10:24:24.744  1029  1384 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 10:24:24.748  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 10:24:24.748  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 10:24:24.748  6209  6209 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 10:24:24.748  6209  6209 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-29 10:24:24.749  1029  1439 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-29 10:24:24.749  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:24.749  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:24.750  1029  1384 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 10:24:24.750  1029  1384 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:24.750  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:24.751  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 10:24:24.751  1029  1384 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 10:24:24.751  1029  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 10:24:24.752  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:24.752  1029  1029 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 10:24:24.753  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=12,0,0
08-29 10:24:24.753  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=12,0,0
08-29 10:24:24.753  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 10:24:24.753  6209  6209 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-29 10:24:24.753  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 10:24:24.753  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 10:24:24.754  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 10:24:24.754  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 10:24:24.754  6209  6209 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 10:24:24.754  6209  6209 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 10:24:24.754  6209  6209 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 10:24:24.755  1029  1384 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 10:24:24.755  1029  1384 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 10:24:24.755  1029  1384 D WifiNative-wlan0: SET ps 0: returned true
08-29 10:24:24.755  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 10:24:24.755  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 10:24:24.756  1029  1384 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 10:24:24.756  1029  1384 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 10:24:24.756  1029  1384 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 10:24:24.756  1029  1384 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 10:24:24.757   330   887 D CommandListener: Setting iface cfg
08-29 10:24:24.757   330   887 D CommandListener: Trying to bring up wlan0
08-29 10:24:24.757  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:24.758  1029  1384 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 10:24:24.758  1029  1383 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38a77a9c target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:24.759  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38a77a9c target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:24.759  1029  7155 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:24.759  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-29 10:24:24.759  1029  7155 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 10:24:24.759  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 10:24:24.759  1029  1029 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 10:24:24.759  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-29 10:24:24.759  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 10:24:24.760  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 10:24:24.760  1029  1383 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:24.760  1029  1383 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:24.760  1029  1384 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 10:24:24.760  1029  1384 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 10:24:24.760  7080  7080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 10:24:24.761  1029  1384 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 10:24:24.761  1029  1384 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 10:24:24.766  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroa,dcast: android.net.wifi.STATE_CHANGE
08-29 10:24:24.767  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:24.772  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:24.777  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:24.777  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:24.778  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:24.780  1029  1384 D WifiNative-wlan0: SET ps 1: returned true
08-29 10:24:24.780  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:24.781  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:24.781  1029  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 10:24:24.781  1029  1384 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:24.781  1029  1384 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:24.782  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:24.782  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:24.782  1029  1384 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:24.783  1029  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 10:24:24.783  1029  1384 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 10:24:24.783  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 10:24:24.783  1029  1384 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 10:24:24.784  1029  1439 D ConnectivityService: ignoring duplicate network state non-change
08-29 10:24:24.786  1029  1439 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 10:24:24.787  1029  1439 D ConnectivityService: Adding iface wlan0 to network 101
08-29 10:24:24.789  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.789  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.789  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 10:24:24.790  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:24.790  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 10:24:24.793  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.793  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.793  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 10:24:24.794  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 10:24:24.795  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 10:24:24.797  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:24.797  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 10:24:24.798  1935  1935 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 10:24:24.798  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:24.799  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.799  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.799  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 10:24:24.802  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:24.803  1029  1384 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 10:24:24.806  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-29 10:24:24.815  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.815  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:24.815  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 10:24:24.816  1029  1439 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 10:24:24.816  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:24.816  1029  1439 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-29 10:24:24.816  1595  1595 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 10:24:24.816  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:24.817  1029  1439 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 10:24:24.818  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:24.818   330   887 E Netd    : netlink response contains error (File exists)
,08-29 10:24:24.820  1029  1439 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 10:24:24.820  1029  1439 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 10:24:24.820  1029  1439 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-29 10:24:24.820  1029  1439 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-29 10:24:24.821  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:24.822  1595  1595 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 10:24:24.822  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:24.822  1029  1439 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 10:24:24.822  1029  1439 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 10:24:24.822  1029  1439 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 10:24:24.823  1029  1439 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 10:24:24.823  1029  1439 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:24:24.823  1029  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:24.823  1029  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 10:24:24.823  1029  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:24.823  1029  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 10:24:24.823  1029  1439 D ConnectivityService: currentScore = 0, newScore = 20
08-29 10:24:24.823  1029  1439 D ConnectivityService:    accepting network in place of null
08-29 10:24:24.823  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:24.823  1029  1439 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:24.823  1029  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:24.823  1029  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 10:24:24.823  1029  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:24.823  1029  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 10:24:24.824  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:24.824  1029  1384 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:24.824  1029  1384 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:24:24.825  1846  1846 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:24.825  6272  6272 I QRemote : [WiFiStateReceiver.java:,201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:24.825  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 10:24:24.826  1029  1439 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 10:24:24.827  1029  1439 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 10:24:24.827  1029  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 10:24:24.827  1029  1439 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:24.827   330  7160 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 10:24:24.827  1029  1439 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 10:24:24.827  1029  1439 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 10:24:24.828  1029  1029 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 10:24:24.829  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 10:24:24.829  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 10:24:24.829  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 10:24:24.829   330  7161 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 10:24:24.829   330  7161 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-29 10:24:24.829  1029  1439 D ConnectivityService: validation of new default Network = false
08-29 10:24:24.829  1029  1439 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 10:24:24.829  1029  1439 D DSQN    : enableDataServiceNotify 
08-29 10:24:24.829  1029  1439 D DSQN    : start dsqn bin
08-29 10:24:24.824  7162  7162 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:24.824  7162  7162 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:24.837  1029  1439 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 10:24:24.837  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:24.837  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:24.838  1029  1439 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:24.838  1595  1823 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 10:24:24.845  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:24.849  7162  7162 E DSQN    : DSQN ssw
08-29 10:24:24.853  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:24.861  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:24.865  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 10:24:24.866  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:24.867  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:24.867  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:24.868  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:24.868  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:24.868  1810  7166 I CheckinService: active receiver: enabled
08-29 10:24:24.871  1810  7166 I CheckinService: Preparing to send checkin request
08-29 10:24:24.871  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:24.871  1810  7166 I EventLogService: Accumulating logs since 1472457424540
08-29 10:24:24.876  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:24.876   330  7161 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
08-29 10:24:24.881  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:24.887  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:24.888  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:24.891  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:24.898   330  7160 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-29 10:24:24.899  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:24.904  5976  6039 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 771)
08-29 10:24:24.904  5976  6039 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 771)
08-29 10:24:24.907  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 10:24:24.913  1029  1382 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 10:24:24.913  5976  6039 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 776)
08-29 10:24:24.915  5976  6039 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 10:24:24.915  5976  6039 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 777)
08-29 10:24:24.917  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:24.918  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:24.918  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a78e3f8 added. We now have 2 listener(s)
08-29 10:24:24.919  1029  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:24.921  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:24:24.921  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:24.921  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:24.922  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:24.922  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24bed0d1 added. We now have 9 listener(s)
08-29 10:24:24.922  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:24.922  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:24:24.926  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:24.926  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:24.926  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:24.926  6272  6272 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 10:24:24.929  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:24.932   330  7160 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-29 10:24:24.932  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:24.932  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:24.932  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:24.932  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:24.932  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:24.932  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:24.932  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:24.932  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:24:24.932  1810  7166 W EventLogAggregator: Unknown tag: snet_gcore
08-29 10:24:24.932  1810  7166 W EventLogAggregator: Unknown tag: snet_launch_service
,08-29 10:24:24.934  6226  6226 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 10:24:24.934  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:24.934  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 10:24:24.934  5976  6039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:24:24.934  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:24.934  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ff7637 added. We now have 3 listener(s)
08-29 10:24:24.936  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:24.937  1029  1724 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:24.938  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:24.939  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:24:24.940  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:24.940  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:24.940  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:24.940  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395447a4 added. We now have 10 listener(s)
08-29 10:24:24.940  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:24.940  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:24.940  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:24.940  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:24.940  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:24.940  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:24.940  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:24.940  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:24.940  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a78e3f8 removed from the list
08-29 10:24:24.940  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:24.940  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24bed0d1 removed from the list
08-29 10:24:24.940  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:24.940  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) ,left
08-29 10:24:24.940  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:24.941  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:24.941  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:24.941  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:24.941  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:24.941  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:24.941  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24bed0d1 not in the list
08-29 10:24:24.941  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:24.941  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:24.943  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:24.943  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:24:24.943  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:24.943  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395447a4 removed from the list
08-29 10:24:24.943  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:24.943  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:24.943  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:24.943  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:24.943  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ff7637 removed from the list
08-29 10:24:24.944  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:24.944  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@238ea90d added. We now have 2 listener(s)
08-29 10:24:24.944  1029  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:24.946  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:24:24.946  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:24.946  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:24.946  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:24.946  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@284e20c2 added. We now have 9 listener(s)
08-29 10:24:24.946  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:24.946  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:24:24.948  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:24.950  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:24.954  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:24.954  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:24.954  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:24.954  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:24.954  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:24.954  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:24.954  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:24.954  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:24:24.956  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:24.956  59,76  6039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:24:24.956  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:24.956  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a603a10 added. We now have 3 listener(s)
08-29 10:24:24.957  1029  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:24.958  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:24.959  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:24.959  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:24:24.959  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:24.959  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:24.959  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:24.959  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:24.959  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@509c909 added. We now have 10 listener(s)
08-29 10:24:24.959  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:24.959  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:24.959  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:24:24.959  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:24:24.959  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:24.959  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:24:24.959  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:24.960  6272  6272 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 10:24:24.961  1029  7155 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 10:24:24.962  1029  7155 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 10:24:24.962  1029  7155 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 10:24:24.962  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:24:24.954  7168  7168 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:24.962  1029  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:24.954  7168  7168 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 10:24:24.967   330   886 D LGDataListener: argv[0]=dsqncommand
08-29 10:24:24.967   330   886 D LGDataListener: argv[1]=wlan0
08-29 10:24:24.967   330   886 D LGDataListener: argv[2]=1
08-29 10:24:24.967   330   886 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-29 10:24:24.967  1029  1109 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 10:24:24.967  1029  1109 D DSQN    : start to monitor internet connection
08-29 10:24:24.967  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:24:24.969  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:24:24.970  6272  6272 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 10:24:24.970  6272  6272 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 10:24:24.971  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:24:24.971  7168  7168 I dhcpcd  : version 5.5.6 starting
08-29 10:24:24.971  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:24.972  7168  7168 E dhcpcd  : get_duid: m
08-29 10:24:24.972  7168  7168 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 10:24:24.972  7168  7168 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 10:24:24.974  5976  6039 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 10:24:24.974  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:24.974  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:24:24.976  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:24.976  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:24.976  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:24.976  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:24.976  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:24.976  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 10:24:24.976  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:24.976  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:24.976  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@238ea90d removed from the list
08-29 10:24:24.976  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:24.976  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@284e20c2 removed from the list
08-29 10:24:24.976  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:24.976  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:24.979  6226  6226 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 10:24:24.980  6226  6226 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 10:24:24.980  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:24.980  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:24.981  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:24.981  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:24.981  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:24.981  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@284e20c2 not in the list
08-29 10:24:24.981  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:24.981  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:24.982  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:24.983  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:24.983  6209  6209 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 10:24:24.983  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:24.983  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:24.983  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:24.983  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.,p2p.btconnectorlib.DiscoveryManager@509c909 removed from the list
08-29 10:24:24.983  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:24.984  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:24.984  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:24.984  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:24.984  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a603a10 removed from the list
08-29 10:24:24.985  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:24.985  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e73c added. We now have 2 listener(s)
08-29 10:24:24.985  1029  1724 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 10:24:24.988  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:24:24.988  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:24.988  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:24.988  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:24.988  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1afcecc5 added. We now have 9 listener(s)
08-29 10:24:24.988  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:24.989  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:24:24.991  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:24.996  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:24.996  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:24.996  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:24.996  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:24.996  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:24.996  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:24.996  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:24.996  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:24:24.998  1810  7166 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-29 10:24:24.998  6209  6209 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 10:24:24.998  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:24.998  5976  6039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:24:24.998  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:24.998  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab1b54b added. We now have 3 listener(s)
,08-29 10:24:25.000  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:25.002  1029  1568 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:25.002  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:25.005  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:24:25.005  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:25.005  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:25.005  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:25.005  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e93b28 added. We now have 10 listener(s)
08-29 10:24:25.005  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:25.005  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:25.005  1029  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 08:24:25 GMT], X-Android-Received-Millis=[1472459065005], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472459064966]}
08-29 10:24:25.005  1029  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 10:24:25.005  1029  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-29 10:24:25.006  1029  1439 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-29 10:24:25.006  1029  1439 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 10:24:25.006  1029  1439 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:24:25.006  1029  1439 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:25.006  1029  1439 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 10:24:25.006  1029  1439 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-29 10:24:25.006  1029  1439 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 10:24:25.006  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:25.006  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:25.006  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:24:25.006  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:25.006  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:24:25.006  ,5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:25.006  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:24:25.006  1029  1439 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:25.006  1029  1439 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:25.006  6272  6272 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 10:24:25.007  1029  1439 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 10:24:25.007  1029  1384 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:25.007  1029  1384 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:24:25.007  1846  1846 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:25.007  1595  1823 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 10:24:25.008  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 10:24:25.010  6272  6272 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 10:24:25.010  6272  6272 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 10:24:25.011  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:24:25.011  6272  6272 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 10:24:25.011  1029  1863 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:25.011  6272  6272 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-29 10:24:25.016  7168  7168 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 10:24:25.016  7168  7168 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 10:24:25.016  7168  7168 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 10:24:25.017  7168  7168 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 10:24:25.017  7168  7168 D dhcpcd  : wlan0: sending REQUEST (xid 0x64f93b34), next in 4.09 seconds
08-29 10:24:25.019  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:24:25.019  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:24:25.020  1029  1436 D WifiService: New client listening to asynchronous messages
08-29 10:24:25.021  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:24:25.022  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:25.024  5976  6039 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-29 10:24:25.024  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:25.024  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:25.024  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:25.024  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:25.024  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.024  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:25.024  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:25.024  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e73c removed from the list
08-29 10:24:25.024  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:25.024  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1afcecc5 removed from the list
08-29 10:24:25.024  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:25.024  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:25.026  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.026  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:25.027  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:25.027  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:25.027  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:25.027  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1afcecc5 not in the list
08-29 10:24:25.027  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.027  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:25.028  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:25.028  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:25.028  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:25.028  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:25.028  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:25.028  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e93b28 removed from the list
08-29 10:24:25.028  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:25.028  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.028  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 1,0:24:25.028  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:25.028  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab1b54b removed from the list
08-29 10:24:25.029  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:25.029  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee45b27 added. We now have 2 listener(s)
08-29 10:24:25.029  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 10:24:25.029  1029  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:25.031  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:24:25.031  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:25.031  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:25.031  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:25.031  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122ae1d4 added. We now have 9 listener(s)
08-29 10:24:25.031  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:25.031  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:25.031  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:24:25.032  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 10:24:25.033  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:25.035  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:25.035  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:25.035  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:25.035  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:25.035  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:25.035  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:25.035  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:25.035  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:24:25.036  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:25.036  5976  6039 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:24:25.037  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:25.037  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23743e72 added. We now have 3 listener(s)
08-29 10:24:25.037  1029  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:25.037  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:25.039  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:25.040  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:24:25.040  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:25.040  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:25.040  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:25.040  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b182c3 added. We now have 10 listener(s)
08-29 10:24:25.040  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:25.040  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:25.040  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:24:25.040  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:24:25.040  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:25.040  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:24:25.042  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:24:25.042  1029  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:25.044  7168  7168 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-29 10:24:25.045  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:24:25.045  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:24:25.046  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:24:25.046  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:25.047  5976  6039 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-29 10:24:25.051  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:25.051  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:25.051  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:25.051  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:25.051  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.051  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:25.051  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:25.051  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee45b27 removed from the list
08-29 10:24:25.051  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:25.051  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122ae1d4 removed from the list
08-29 10:24:25.051  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:25.051  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:25.051  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.051  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:25.052  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:25.052  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:25.052  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:25.052  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122ae1d4 not in the list
08-29 10:24:25.052  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.052  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:25.053  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:25.053  5976  6039 D BluetoothLeScanner: could not find callback wrapper
08-29 10:24:25.053  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:25.053  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:25.053  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:25.053  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b182c3 removed from the list
08-29 10:24:25.053  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:25.053  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.053  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10,:24:25.053  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:25.053  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23743e72 removed from the list
08-29 10:24:25.054  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:25.054  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec3cfbe added. We now have 2 listener(s)
08-29 10:24:25.054  1029  1863 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:25.054  7168  7168 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 10:24:25.054  7168  7168 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 10:24:25.054  7168  7168 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 10:24:25.055  7168  7168 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 10:24:25.055  7168  7168 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 10:24:25.055  7168  7168 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 10:24:25.055  7168  7168 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 10:24:25.055  7168  7168 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 10:24:25.056  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:24:25.056  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:25.056  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:25.056  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:25.056  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d9f881f added. We now have 9 listener(s)
08-29 10:24:25.056  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:25.057  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:24:25.058  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:25.061  5976  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:25.061  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:25.061  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 10:24:25.061  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:25.061  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:25.061  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:25.061  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:25.061  5976  6039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:24:25.062  5976  6039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:25.062  5976  6039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:24:25.062  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:25.062  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13cb9135 added. We now have 3 listener(s)
08-29 10:24:25.062  1029  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 10:24:25.064  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 10:24:25.064  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:25.064  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:25.065  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:25.065  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e929ca added. We now have 10 listener(s)
08-29 10:24:25.065  5976  6039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:25.065  5976  6039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:25.065  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:25.065  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:25.065  5976  6039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:25.065  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:25.065  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.065  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:25.065  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:25.065  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec3cfbe removed from the list
08-29 10:24:25.065  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:25.065  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d9f881f removed from the list
08-29 10:24:25.067  5976  5976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:25.067  5976  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:25.067  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:25.067  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.067  5976  6039 D org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:25.068  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:25.068  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:25.068  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:25.068  5976  6039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d9f881f not in the list
08-29 10:24:25.068  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.068  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:25.069  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:25.069  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:25.069  5976  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:25.069  5976  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e929ca removed from the list
08-29 10:24:25.069  5976  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:25.069  5976  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:25.069  5976  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:25.069  5976  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:25.069  5976  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13cb9135 removed from the list
08-29 10:24:25.070  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 10:24:25.070  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 10:24:25.070  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 10:24:25.070  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:25.071  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 10:24:25.071  5976  6039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:24:25.080  5976  7182 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 784, name: My test thread name)
08-29 10:24:25.081  5976  7182 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 784, thread name: My test thread name)
08-29 10:24:25.081  5976  7182 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 784, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 10:24:25.084  5976  7184 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 786, name: My test thread name)
08-29 10:24:25.084  5976  7184 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 786, thread name: My test thread name)
08-29 10:24:25.084  5976  7184 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 786, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 10:24:25.086  5976  6039 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 10:24:25.086  5976  6039 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 10:24:25.086  5976  6039 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-29 10:24:25.086  5976  6039 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 10:24:25.086  5976  6039 D com.test.thalitest.ThaliTestRunner: Total duration: 22736 ms
08-29 10:24:25.087  5976  6039 I jxcore-log: *Native tests were executed*
08-29 10:24:25.087  5976  6039 I jxcore-log: 
08-29 10:24:25.087  5976  6039 I jxcore-log: Total number of executed tests:  80
08-29 10:24:25.087  5976  6039 I jxcore-log: 
08-29 10:24:25.087  5976  6039 I jxcore-log: Number of passed tests:  80
08-29 10:24:25.087  5976  6039 I jxcore-log: 
08-29 10:24:25.088  5976  6039 I jxcore-log: Number of failed tests:  0
08-29 10:24:25.088  5976  6039 I jxcore-log: 
08-29 10:24:25.088  5976  6039 I jxcore-log: Number of ignored tests:  0
08-29 10:24:25.088  5976  6039 I jxcore-log: 
08-29 10:24:25.088  5976  6039 I jxcore-log: Total duration:  22736
08-29 10:24:25.088  5976  6039 I jxcore-log: 
08-29 10:24:25.088  5976  6039 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 10:24:25.088  5976  6039 I jxcore-log: 
08-29 10:24:25.091  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:25.091  5976  6039 I jxcore-log: 
08-29 10:24:25.093  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:25.093  5976  6039 I jxcore-log: 
08-29 10:24:25.095  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:25.095  5976  6039 I jxcore-log: 
08-29 10:24:25.096  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:25.096  5976  6039 I jxcore-log: 
08-29 10:24:25.097  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:25.097  5976  6039 I jxcore-log: 
08-29 10:24:25.098  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:25.098  5976  6039 I jxcore-log: 
08-29 10:24:25.101  5976  5976 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 10:24:25.102  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:25.102  5976  6039 I jxcore-log: 
08-29 10:24:25.104  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:24:25.104  5976  6039 I jxcore-log: 
08-29 10:24:25.105  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:24:25.105  5976  6039 I jxcore-log: 
08-29 10:24:25.105  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:24:25.105  5976  6039 I jxcore-log: 
08-29 10:24:25.106  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:25.106  5976  6039 I jxcore-log: 
08-29 10:24:25.107  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:25.107  5976  6039 I jxcore-log: 
08-29 10:24:25.108  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:24:25.108  5976  6039 I jxcore-log: 
08-29 10:24:25.109  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:24:25.109  5976  6039 I jxcore-log: 
08-29 10:24:25.109  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:25.109  5976  6039 I jxcore-log: 
08-29 10:24:25.110  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:25.110  5976  6039 I jxcore-log: 
08-29 10:24:25.111  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:24:25.111  5976  6039 I jxcore-log: 
08-29 10:24:25.111  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:24:25.111  5976  6039 I jxcore-log: 
08-29 10:24:25.112  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:25.112  5976  6039 I jxcore-log: 
,08-29 10:24:25.113  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:25.113  5976  6039 I jxcore-log: 
08-29 10:24:25.113  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:25.113  5976  6039 I jxcore-log: 
08-29 10:24:25.114  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:25.114  5976  6039 I jxcore-log: 
08-29 10:24:25.115  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:25.115  5976  6039 I jxcore-log: 
08-29 10:24:25.116  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:25.116  5976  6039 I jxcore-log: 
08-29 10:24:25.117  5976  6039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:25.117  5976  6039 I jxcore-log: 
08-29 10:24:25.151  1029  2025 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7194 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-29 10:24:25.171   358   358 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 959us total 19.381ms
,08-29 10:24:25.188   358   358 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 16.629ms
,08-29 10:24:25.189  7194  7194 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 10:24:25.189  7194  7194 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-29 10:24:25.204   358   358 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 296us total 14.468ms
08-29 10:24:25.210  7194  7194 I MultiDex: VM with version 2.1.0 has multidex support
08-29 10:24:25.210  7194  7194 I MultiDex: install
08-29 10:24:25.210  7194  7194 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 10:24:25.222  7194  7194 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-29 10:24:25.225  2265  2265 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-29 10:24:25.230  2265  2265 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-29 10:24:25.231  2265  2265 D c       : Getting all permits...
08-29 10:24:25.231  2265  2265 D a       : Opening database...
08-29 10:24:25.234  2265  2265 D a       : Opening database auth.proximity.permit_store...
,08-29 10:24:25.234  2265  2265 D a       : Closing database...
08-29 10:24:25.316  7212  7212 D AndroidRuntime: 
08-29 10:24:25.316  7212  7212 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 10:24:25.318  7212  7212 D AndroidRuntime: CheckJNI is OFF
,08-29 10:24:25.365  1029  7155 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 10:24:25.366  1029  7155 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 10:24:25.366  1029  7155 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 10:24:25.366  1029  7155 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 10:24:25.366  1029  7155 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 10:24:25.366  1029  7155 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 10:24:25.366  1029  7155 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 10:24:25.366  1029  7155 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 10:24:25.366  1029  7155 D DhcpStateMachine: RunningState
,08-29 10:24:25.444  7212  7212 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 10:24:25.454  1029  1095 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-29 10:24:25.454  1029  1095 I ActivityManager: Killing 5976:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-29 10:24:25.540  1029  1953 I WindowState: WIN DEATH: Window{1f2e393a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 10:24:25.541  1029  1436 D WifiService: Client connection lost with reason: 4
,08-29 10:24:25.557  1029  1953 D InputDispatcher: Window went away: Window{1f2e393a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 10:24:25.730  1029  1095 I ActivityManager:   Force finishing activity ActivityRecord{17e42301 u0 com.test.thalitest/.MainActivity t6}
,08-29 10:24:25.759   351   365 E GBMv2   : DFP En is all cleared set to be enabled
08-29 10:24:25.761  1029  1916 W ActivityManager: Spurious death for ProcessRecord{3c17a185 5976:com.test.thalitest/u0a118}, curProc for 5976: null
08-29 10:24:25.763  1935  1950 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-29 10:24:25.764  1935  1950 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15c0410b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-29 10:24:25.766  1029  1117 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-29 10:24:25.769  1029  1117 I ActivityManager:   Force finishing activity ActivityRecord{17e42301 u0 com.test.thalitest/.MainActivity t6 f}
08-29 10:24:25.769  1029  1117 W ActivityManager: Duplicate finish request for ActivityRecord{17e42301 u0 com.test.thalitest/.MainActivity t6 f}
08-29 10:24:25.769  1935  1951 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-29 10:24:25.771  1935  1951 D SplitWindowPolicy: topRunningActivity=ActivityInfo{302f3be8 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-29 10:24:25.803  1595  1595 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-29 10:24:25.811  1029  1374 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 10:24:25.815  1990  1990 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-29 10:24:25.815  3700  3700 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-29 10:24:25.816  6895  6895 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-29 10:24:25.816  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 10:24:25.818  2508  2668 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 10:24:25.862  4528  4528 I art     : Explicit concurrent mark sweep GC freed 746(43KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 1.040ms total 73.636ms
08-29 10:24:25.862  6923  6959 D UEI.SmartControl: Internal timer expired: 1
08-29 10:24:25.863  6923  6959 D UEI.SmartControl: unbind internal service
08-29 10:24:25.863  1029  2026 V SIM_STK : Menu title from STK is T-Mobile
,08-29 10:24:25.874  4419  4419 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-29 10:24:25.875  4419  4419 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-29 10:24:25.875  4419  4419 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-29 10:24:25.875  4419  4419 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-29 10:24:25.875  4419  4419 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 10:24:25.875  4419  4419 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 10:24:25.875  4419  4419 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 10:24:25.875  4419  4419 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 10:24:25.875  4419  4419 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:25.875  4419  4419 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:24:25.875  4419  4419 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 10:24:25.875  4419  4419 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 10:24:25.880  3731  3731 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-29 10:24:25.891  1029  1029 D administrator: Handling package changes for user 0
08-29 10:24:25.899  7194  7209 D LgDataFeature: LgDataFeature() Constructor: none
08-29 10:24:25.899  7194  7209 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 10:24:25.908  1029  1953 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7244 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-29 10:24:25.909  2028  2028 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-29 10:24:25.910  1595  1595 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-29 10:24:25.910  2028  2028 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-29 10:24:25.912  2028  2028 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-29 10:24:25.913  2028  2103 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-29 10:24:25.968  1810  1810 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-29 10:24:25.974  7244  7244 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,08-29 10:24:25.979  1864  1864 D SplitUIManager: split_name #11 / not available #0
08-29 10:24:25.979  1864  1864 D SplitUIService: removed split : 
,08-29 10:24:25.994  2028  2028 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-29 10:24:25.994  1899  1899 D ActionManagerService: notifyUserLog: 1000003
08-29 10:24:25.995  3700  4409 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-29 10:24:25.996  2265  2265 I ConfigService: onCreate
08-29 10:24:25.996  2265  2265 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-29 10:24:25.997  1029  1093 W InputMethodInfo: Duplicated subtype definition found: , voice
08-29 10:24:26.001  2265  2265 I ConfigService: onBind returning update interface
08-29 10:24:26.009  1029  1952 V SIM_STK : Menu title from STK is T-Mobile
,08-29 10:24:26.010  1029  1989 V SIM_STK : Menu title from STK is T-Mobile
08-29 10:24:26.010  1029  1989 V SIM_STK : Menu title from STK is T-Mobile
08-29 10:24:26.011  2028  2028 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-29 10:24:26.013  2265  2265 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-29 10:24:26.013  2265  2265 I ConfigService: onBind returning config service
08-29 10:24:26.015  1810  1810 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-29 10:24:26.016  2028  2028 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-29 10:24:26.019  2028  2028 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-29 10:24:26.023  1595  1595 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-29 10:24:26.023  1595  1595 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-29 10:24:26.023  2028  2028 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-29 10:24:26.024  3700  3715 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 10:24:26.025  1899  1899 D ActionManagerService: notifyUserLog: 1000004
,08-29 10:24:26.025  3700  4409 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , create_time: 1430832262123
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , expire_time: 0
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , display: false
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , animation: false }
08-29 10:24:26.027  1864  1864 D SplitUIManager: split_name #11 / not available #0
08-29 10:24:26.027  1864  1864 I SplitUIService: split app #11
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , create_time: 1430832262287
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , expire_time: 0
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , display: false
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , animation: false }
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , create_time: 1472216588858
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , expire_time: 0
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , display: false
08-29 10:24:26.027  2028  2028 I GBoardWebViewUtils: , animation: false }
08-29 10:24:26.028  1810  1810 I ConfigFetchService: service connected
08-29 10:24:26.028  1810  1810 I ConfigClient: service connected
08-29 10:24:26.034  2028  7264 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-29 10:24:26.036  2265  2265 I ConfigService: onDestroy
,08-29 10:24:26.042  1810  7265 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-29 10:24:26.044  1595  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 10:24:26.044  1595  1647 D KeyguardModel: createShortcutInfo...
08-29 10:24:26.049  1595  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 10:24:26.049  1595  1647 D KeyguardModel: createShortcutInfo...
,08-29 10:24:26.050  2028  2028 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 10:24:26.051  2028  2028 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-29 10:24:26.051  1595  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 10:24:26.051  1595  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 10:24:26.052  1595  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 10:24:26.052  1595  1647 D KeyguardModel: createShortcutInfo...
08-29 10:24:26.056  1595  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 10:24:26.056  1595  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 10:24:26.058  1595  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 10:24:26.058  1595  1647 D KeyguardModel: createShortcutInfo...
08-29 10:24:26.061  1595  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 10:24:26.061  1595  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 10:24:26.070  1029  1989 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7269 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-29 10:24:26.071  1029  1917 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 10:24:26.072  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 10:24:26.072  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 10:24:26.072  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 10:24:26.072  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 10:24:26.072  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 10:24:26.072  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 10:24:26.072  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 10:24:26.072  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 10:24:26.072  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 10:24:26.072  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 10:24:26.072  6895  6895 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-29 10:24:26.074  1595  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 10:24:26.075  1595  1647 D KeyguardModel: createShortcutInfo...
08-29 10:24:26.078  1595  1595 D KeyguardModel: handleShortcutListChanged...
08-29 10:24:26.078  1595  1595 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 10:24:26.082  1595  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 10:24:26.082  1595  1647 D KeyguardModel: createShortcutInfo...
08-29 10:24:26.084  1595  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 10:24:26.084  1595  1647 D KeyguardModel: createShortcutInfo...
08-29 10:24:26.091  1595  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 10:24:26.092  1595  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-29 10:24:26.097  1595  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 10:24:26.097  1595  1647 D KeyguardModel: createShortcutInfo...
08-29 10:24:26.099  1595  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 10:24:26.099  1595  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 10:24:26.101  1595  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 10:24:26.101  1595  1647 D KeyguardModel: createShortcutInfo...
08-29 10:24:26.107  1595  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 10:24:26.107  1595  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 10:24:26.109  1595  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 10:24:26.109  1595  1647 D KeyguardModel: createShortcutInfo...
,08-29 10:24:26.120  5506  7285 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-29 10:24:26.128  2028  2028 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-29 10:24:26.128  1029  1917 I ActivityManager: Killing 6595:com.lge.email/u0a23 (adj 15): empty #17
08-29 10:24:26.137  1810  1828 I art     : Explicit concurrent mark sweep GC freed 19646(1359KB) AllocSpace objects, 17(272KB) LOS objects, 51% free, 29MB/61MB, paused 5.453ms total 60.835ms
,08-29 10:24:26.145  7286  7286 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-29 10:24:26.174   345   445 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-29 10:24:26.174  3125  7296 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-29 10:24:26.191  7269  7269 I AppUp4:AppBoxCP: onCreate
08-29 10:24:26.191  7269  7269 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-29 10:24:26.196  7269  7269 I AppUp4:DB:  setFingerPrint start
08-29 10:24:26.196  7269  7269 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 10:24:26.202  7269  7269 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 10:24:26.202  7269  7269 I AppUp4:DB:  SDK version = 21
08-29 10:24:26.202  7269  7269 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-29 10:24:26.203  7286  7286 I dex2oat : dex2oat took 57.695ms (threads: 4)
08-29 10:24:26.209  1029  1029 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-29 10:24:26.210  1029  1029 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 10:24:26.210  1029  1029 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 10:24:26.219  7194  7209 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 10:24:26.219  7194  7209 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 10:24:26.219  7194  7209 I Adreno-EGL: Build Date: 12/12/14 금
08-29 10:24:26.219  7194  7209 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 10:24:26.219  7194  7209 I Adreno-EGL: Remote Branch: 
08-29 10:24:26.219  7194  7209 I Adreno-EGL: Local Patches: 
08-29 10:24:26.219  7194  7209 I Adreno-EGL: Reconstruct Branch: 
08-29 10:24:26.225  2028  2028 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-29 10:24:26.228  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 10:24:26.230  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-29 10:24:26.231  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-29 10:24:26.232  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-29 10:24:26.233  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-29 10:24:26.261  2028  2028 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-29 10:24:26.262  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 10:24:26.263  2028  2791 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-29 10:24:26.263  2028  2791 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-29 10:24:26.265  1595  1595 D KeyguardModel: handleShortcutListChanged...
08-29 10:24:26.265  1595  1595 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 10:24:26.266  1810  7295 I PeopleContactsSync: CP2 sync disabled
08-29 10:24:26.270  1029  1724 W libprocessgroup: failed to open /acct/uid_10023/pid_6595/cgroup.procs: No such file or directory
08-29 10:24:26.273  1029  1570 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-29 10:24:26.274  1029  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{279182eb u0 com.lge.launcher2/.Launcher t5} time:138800
,08-29 10:24:26.275  7269  7269 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-29 10:24:26.278  1810  4667 I Icing   : doRemovePackageData com.test.thalitest
08-29 10:24:26.285  1029  1384 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:26.286  1029  1384 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:26.286  1029  1384 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:26.286  1029  1384 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:26.286  1029  1384 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 10:24:26.287  1029  1384 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-29 10:24:26.289  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-29 10:24:26.291  2028  2028 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 10:24:26.291  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 10:24:26.291  1029  1439 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-29 10:24:26.292  1029  1439 D ConnectivityService: identical MTU - not setting
08-29 10:24:26.292  1029  1439 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 10:24:26.292  1029  1439 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 10:24:26.292  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:26.292  1029  1439 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:26.292  1029  1439 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 10:24:26.293  1029  1117 I art     : Explicit concurrent mark sweep GC freed 85486(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.521ms total 374.728ms
08-29 10:24:26.294  1595  1823 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 10:24:26.298  1810  7291 W GmsApplication: Using Auth Proxy for data requests.
08-29 10:24:26.300  2028  2028 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-29 10:24:26.301  2593  2593 D [Concierge]Service: onStartCommand(). Type : 8
08-29 10:24:26.301  2593  2593 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-29 10:24:26.302  1810  7291 W GmsApplication: Using Auth Proxy for data requests.
08-29 10:24:26.302  2593  2593 D [Concierge]Service: Update widget ID : 11
08-29 10:24:26.303  2028  2028 D [Concierge]WidgetView: change position of spinner
08-29 10:24:26.303  2028  2028 I [Concierge]WidgetView: initWebView(). Time : 1472459066303
08-29 10:24:26.304  2593  2593 D [Concierge]Service: onStartCommand(). Type : 0
,08-29 10:24:26.320  7194  7209 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 10:24:26.320  7194  7209 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 10:24:26.320  7194  7209 I Adreno-EGL: Build Date: 12/12/14 금
08-29 10:24:26.320  7194  7209 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 10:24:26.320  7194  7209 I Adreno-EGL: Remote Branch: 
08-29 10:24:26.320  7194  7209 I Adreno-EGL: Local Patches: 
08-29 10:24:26.320  7194  7209 I Adreno-EGL: Reconstruct Branch: 
,08-29 10:24:26.361  7194  7209 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 10:24:26.361  7194  7209 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 10:24:26.361  7194  7209 I Adreno-EGL: Build Date: 12/12/14 금
08-29 10:24:26.361  7194  7209 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 10:24:26.361  7194  7209 I Adreno-EGL: Remote Branch: 
08-29 10:24:26.361  7194  7209 I Adreno-EGL: Local Patches: 
08-29 10:24:26.361  7194  7209 I Adreno-EGL: Reconstruct Branch: 
08-29 10:24:26.362  6923  6949 D serial_port: close(fd = 25)
,08-29 10:24:26.365  6923  6949 I UEI.SmartControl: Serial port is closed.
08-29 10:24:26.368  2028  2028 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 31903842
08-29 10:24:26.368  2028  2028 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-29 10:24:26.368  2028  2028 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 10:24:26.370  7269  7269 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-29 10:24:26.371  2028  2028 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@29d243da
08-29 10:24:26.371  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-29 10:24:26.373  2028  2028 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 10:24:26.373  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 10:24:26.378  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-29 10:24:26.378  2028  2028 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
,08-29 10:24:26.379  2028  2028 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-29 10:24:26.383  1029  1093 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 10:24:26.385  7212  7212 D AndroidRuntime: Shutting down VM
08-29 10:24:26.398  1029  1093 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-29 10:24:26.399  1029  1044 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7302 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-29 10:24:26.400  1029  1044 I ActivityManager: Killing 6690:com.android.chrome/u0a57 (adj 15): empty #17
,08-29 10:24:26.496  2028  2028 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472458955384, New one : 1472459066303
08-29 10:24:26.496  2028  2028 D [Concierge]WidgetView: Unregister all receivers
08-29 10:24:26.496  2028  2028 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-29 10:24:26.533  1029  1117 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7319 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 10:24:26.534  1029  1971 W libprocessgroup: failed to open /acct/uid_10057/pid_6690/cgroup.procs: No such file or directory
,08-29 10:24:26.549  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 10:24:26.551  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-29 10:24:26.552  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-29 10:24:26.553  2265  2285 I art     : Explicit concurrent mark sweep GC freed 4587(266KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 855us total 17.759ms
08-29 10:24:26.553  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-29 10:24:26.554  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-29 10:24:26.555  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-29 10:24:26.556  2028  2028 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-29 10:24:26.557  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 10:24:26.558  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 10:24:26.576  7302  7302 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 10:24:26.577  7302  7302 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 10:24:26.577  1029  1917 I ActivityManager: Killing 6726:com.lge.drmservice/u0a62 (adj 15): empty #17
08-29 10:24:26.577  7302  7302 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 10:24:26.578  7302  7302 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-29 10:24:26.578  7302  7302 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 10:24:26.596  2028  2028 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-29 10:24:26.603  2028  2028 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-29 10:24:26.603  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-29 10:24:26.605  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 10:24:26.626  2028  2028 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d1ad12b time:139151
,08-29 10:24:26.645  1029  1045 W libprocessgroup: failed to open /acct/uid_10062/pid_6726/cgroup.procs: No such file or directory
,08-29 10:24:26.669  7302  7302 I SystemConfig: BUILD Country: EU
08-29 10:24:26.669  7302  7302 I SystemConfig: BUILD Operator: OPEN
,08-29 10:24:26.688   330  7341 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 10:24:26.688   330  7341 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-29 10:24:26.703  1029  1728 I ActivityManager: Killing 6744:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-29 10:24:26.722   330  7341 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-29 10:24:26.746  1029  1989 W libprocessgroup: failed to open /acct/uid_10085/pid_6744/cgroup.procs: No such file or directory
,08-29 10:24:26.747  2352  2473 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-29 10:24:26.748  2352  2473 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 10:24:26.751  2352  7345 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 10:24:26.756  2352  7345 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-29 10:24:26.757  2352  7345 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 10:24:26.757  2352  7345 E AndroidRuntime: Process: android.process.acore, PID: 2352
08-29 10:24:26.757  2352  7345 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-29 10:24:26.757  2352  7345 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 10:24:26.763  2028  2028 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-29 10:24:26.778  1029  1971 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7346 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 10:24:26.783  7302  7342 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-29 10:24:26.783  7302  7342 I SystemConfig: existFile = false
08-29 10:24:26.783  2352  7345 I Process : Sending signal. PID: 2352 SIG: 9
08-29 10:24:26.785  7302  7342 I SystemConfig: canReadFile = false
08-29 10:24:26.785  7302  7342 I SystemConfig: systemFeature RCS result false
08-29 10:24:26.785  7302  7342 D SystemConfig: refreshRcsSupport() :false
08-29 10:24:26.808  2028  2864 I GBoardtInterface: onReloaded()
,08-29 10:24:26.810  2028  2028 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: Can't write: system_app_crash
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 10:24:26.817  1029  7353 E DropBoxManagerService: 	... 5 more
08-29 10:24:26.844  1029  1728 I ActivityManager: Process android.process.acore (pid 2352) has died
08-29 10:24:26.844  1029  1728 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
,08-29 10:24:26.845  1029  1728 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 11000ms
08-29 10:24:26.849  3700  4404 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 10:24:26.852  3700  3715 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 10:24:26.860  1810  7166 I CheckinTask: Sending checkin request (7969 bytes)
,08-29 10:24:26.862  1899  1899 D ActionManagerService: notifyUserLog: 1000001
08-29 10:24:26.863  3700  4409 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 10:24:26.863  3700  4409 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 10:24:26.865  1899  1899 D ActionManagerService: notifyUserLog: 1000001
08-29 10:24:26.866  3700  4409 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 10:24:26.867  3700  4409 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 10:24:26.867  3700  4409 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-29 10:24:26.867  3700  4409 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-29 10:24:26.867  3700  4404 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 10:24:26.869  2028  2028 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-29 10:24:26.869  2028  2028 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-29 10:24:26.871  2028  2028 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-29 10:24:26.871  2028  2028 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 10:24:26.872  2028  2028 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-29 10:24:26.872  2028  2028 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-29 10:24:26.873  7346  7346 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 10:24:26.873  7346  7346 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 10:24:26.874  7346  7346 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 10:24:26.874  7346  7346 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.jav,a:372)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 10:24:26.915  7346  7346 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-29 10:24:26.915  7346  7346 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:26.915  7346  7346 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,08-29 10:24:26.915  7346  7346 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 10:24:26.915  7346  7346 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-29 10:24:26.915  7346  7346 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-29 10:24:26.916  7346  7346 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:26.916  7346  7346 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 10:24:26.916  7346  7346 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-29 10:24:26.916  7346  7346 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:26.916  7346  7346 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:24:26.916  7346  7346 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 10:24:26.916  7346  7346 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:24:26.923  7346  7346 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 10:24:26.92,3  7346  7346 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 10:24:26.924  7346  7346 D AndroidRuntime: Shutting down VM
08-29 10:24:26.925  7346  7346 E AndroidRuntime: FATAL EXCEPTION: main
08-29 10:24:26.925  7346  7346 E AndroidRuntime: Process: com.lge.email, PID: 7346
08-29 10:24:26.925  7346  7346 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:171,4)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-29 10:24:26.925  7346  7346 E AndroidRuntime: 	... 11 more
08-29 10:24:26.927  7346  7346 I Process : Sending signal. PID: 7346 SIG: 9
,08-29 10:24:26.928  1029  7366 E DropBoxManagerService: Can't write: system_app_crash
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 10:24:26.928  1029  7366 E DropBoxManagerService: 	... 5 more
08-29 10:24:27.004  1029  1989 I ActivityManager: Process com.lge.email (pid 7346) has died

```
