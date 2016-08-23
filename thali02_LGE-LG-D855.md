#### Test 79763830edacfaa_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-23 16:34:40.270  6659  6659 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-23 16:34:40.299   312   911 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
08-23 16:34:40.299   312   911 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
08-23 16:34:40.299   312   911 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
08-23 16:34:40.299   312   911 I rmt_storage: 
08-23 16:34:40.301   312   312 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
08-23 16:34:40.302   890   910 E Diag_Lib: [IMS_FATAL]| 3347 | 910 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-23 16:34:40.310  6659  6659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 16:34:40.343  6659  6659 D LgDataFeature: LgDataFeature() Constructor: none
08-23 16:34:40.344  6659  6659 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 16:34:40.467  6659  6659 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
--------- beginning of system
08-23 16:34:40.522  1034  1577 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6685 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-23 16:34:40.523  1034  1577 I ActivityManager: Killing 6182:com.android.vending/u0a44 (adj 15): empty #17
08-23 16:34:40.587  1034  1906 W libprocessgroup: failed to open /acct/uid_10044/pid_6182/cgroup.procs: No such file or directory
08-23 16:34:40.592  1814  1814 I ConfigFetchService: fetch service done; releasing wakelock
08-23 16:34:40.594  1814  1814 I ConfigFetchService: stopping self
08-23 16:34:40.613  2283  2283 I ConfigService: onDestroy
08-23 16:34:40.629  6685  6685 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 16:34:40.629  6685  6685 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 16:34:40.630  6685  6685 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 16:34:40.630  6685  6685 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 16:34:40.749  6685  6685 I AppConfig: Total System Memory = 2995761152
08-23 16:34:40.761  6685  6685 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-23 16:34:40.802  1034  1941 I ActivityManager: Killing 5362:com.lge.clock/u0a10 (adj 15): empty #17
08-23 16:34:40.906  1995  1995 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-23 16:34:40.906  1995  1995 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-23 16:34:40.909  1034  1050 W libprocessgroup: failed to open /acct/uid_10010/pid_5362/cgroup.procs: No such file or directory
08-23 16:34:40.914  1995  1995 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-23 16:34:40.938  6508  6508 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-23 16:34:40.945  6508  6508 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-23 16:34:40.990  1034  2012 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6711 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 16:34:41.057   344   344 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 61.774ms
08-23 16:34:41.091   344   344 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 32.320ms
08-23 16:34:41.113   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 430us total 21.236ms
,08-23 16:34:41.280  6711  6711 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-23 16:34:41.357  6711  6711 D LgDataFeature: LgDataFeature() Constructor: none
08-23 16:34:41.358  6711  6711 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 16:34:41.416  6711  6711 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-23 16:34:41.435  6711  6711 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-23 16:34:41.436  6711  6711 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-23 16:34:41.451  6711  6711 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 16:34:41.452  6711  6711 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-23 16:34:41.465  6749  6749 D AndroidRuntime: 
08-23 16:34:41.465  6749  6749 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 16:34:41.466  1034  1909 I ActivityManager: Killing 6253:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-23 16:34:41.468  6749  6749 D AndroidRuntime: CheckJNI is OFF
08-23 16:34:41.604  1034  1577 W libprocessgroup: failed to open /acct/uid_10097/pid_6253/cgroup.procs: No such file or directory
08-23 16:34:41.633  6749  6749 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 16:34:41.634  5101  6781 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 16:34:41.641  3492  3508 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-23 16:34:41.646  3492  3508 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@9473da0 on behalf of 6711
08-23 16:34:41.672  1034  1941 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6784 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 16:34:41.673  1034  2034 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 16:34:41.693  1034  1906 V SIM_STK : Menu title from STK is T-Mobile
08-23 16:34:41.698  1942  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-23 16:34:41.702  1034  2034 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-23 16:34:41.705  1034  2034 D ActivityManager: setTaskToReturnTo : TaskRecord{5d3f319 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 16:34:41.705  1034  2034 D ActivityManager: setTaskToReturnTo : TaskRecord{5d3f319 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 16:34:41.707  1034  2034 D WindowStateEx: AppWindowTokenEx init.. 
08-23 16:34:41.707   340   358 E GBMv2   : DFP En is all cleared set to be enabled
08-23 16:34:41.750  1034  2034 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6807 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 16:34:41.753  6749  6749 D AndroidRuntime: Shutting down VM
08-23 16:34:41.769  6711  6711 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-23 16:34:41.801  5101  6781 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 166 ms] updated apps [took 166 ms] 
08-23 16:34:41.803  6711  6711 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-23 16:34:41.805  1942  4463 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-23 16:34:41.805  1942  4463 D SplitWindowPolicy: topRunningActivity=ActivityInfo{d97de co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 16:34:41.807  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-23 16:34:41.807  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3dc37dbf co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 16:34:41.859  6807  6807 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-23 16:34:41.865  6784  6784 D DocsApplication: Installing DEX configuration.
08-23 16:34:41.876  6784  6784 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-23 16:34:41.878  6784  6784 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1c4338c2 com.google.android.apps.docs}
08-23 16:34:41.890  6784  6784 D TAG     : onCreate()
08-23 16:34:41.904  6784  6784 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-23 16:34:41.919  6807  6807 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-23 16:34:41.926  6807  6807 I LibraryLoader: Loading: webviewchromium
08-23 16:34:41.928  6807  6807 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2469-2472)
08-23 16:34:41.928  6807  6807 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 16:34:41.944  6807  6807 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4833f3c}
08-23 16:34:41.945  6807  6807 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 16:34:41.945  6807  6807 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 16:34:41.953  6807  6807 I BrowserStartupController: Initializing chromium process, renderers=0
08-23 16:34:41.954  6807  6807 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 16:34:41.967   323  2168 V AudioPolicyService: registerClient() client 0xb558a420, uid 10118
,08-23 16:34:41.968  6807  6807 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-23 16:34:41.969  6807  6807 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-23 16:34:41.969  6807  6807 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-23 16:34:41.970  1034  1110 D BluetoothManagerService: Message: 20
08-23 16:34:41.970  1034  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e76b924:true
08-23 16:34:41.983  6807  6807 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 16:34:41.983  6807  6807 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 16:34:41.983  6807  6807 I Adreno-EGL: Build Date: 12/12/14 금
08-23 16:34:41.983  6807  6807 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 16:34:41.983  6807  6807 I Adreno-EGL: Remote Branch: 
08-23 16:34:41.983  6807  6807 I Adreno-EGL: Local Patches: 
08-23 16:34:41.983  6807  6807 I Adreno-EGL: Reconstruct Branch: 
,08-23 16:34:42.087  6807  6840 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-23 16:34:42.091  6807  6807 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-23 16:34:42.102  6807  6807 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 16:34:42.106  6807  6807 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 16:34:42.108  6807  6807 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 16:34:42.110  6807  6807 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 16:34:42.110  6807  6807 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-23 16:34:42.119  6807  6807 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-23 16:34:42.124  6807  6807 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 16:34:42.124  6807  6807 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 16:34:42.166  6807  6855 D OpenGLRenderer: Render dirty regions requested: true
08-23 16:34:42.166  6807  6855 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 16:34:42.187  6807  6855 D OpenGLRenderer: Enabling debug mode 0
,08-23 16:34:42.195  6807  6807 D Atlas   : Validating map...
08-23 16:34:42.199  1034  1993 D SplitWindow: check instance of lgWin Window{71b153e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 16:34:42.236  6807  6853 D LgDataFeature: LgDataFeature() Constructor: none
,08-23 16:34:42.236  6807  6853 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 16:34:42.325  1034  1111 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +523ms (total +613ms)
,08-23 16:34:42.327  1034  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2da64fde u0 com.test.thalitest/.MainActivity t6} time:102871
08-23 16:34:42.342  6807  6807 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c16bf3b time:102886
,08-23 16:34:42.467  6807  6807 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-23 16:34:42.467  6807  6807 I chromium: 
,08-23 16:34:42.474  6807  6807 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-23 16:34:42.550  6807  6853 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-23 16:34:42.550  6807  6853 I chromium: 
,08-23 16:34:42.665  6807  6866 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435169792
,08-23 16:34:42.678  6807  6866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 16:34:42.678  6807  6866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 16:34:42.678  6807  6866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 16:34:42.678  6807  6866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 16:34:42.678  6807  6866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 16:34:42.678  6807  6866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ea36f0f added. We now have 1 listener(s)
,08-23 16:34:42.682  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 16:34:42.685  6807  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-23 16:34:42.687  6807  6866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 16:34:42.688  6807  6866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 16:34:42.688  6807  6866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 16:34:42.694  6807  6866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2073b17a added. We now have 1 listener(s)
08-23 16:34:42.695  6807  6866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 16:34:42.702  1034  1404 D WifiService: New client listening to asynchronous messages
,08-23 16:34:42.712  6807  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 16:34:42.712  6807  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 16:34:42.712  6807  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 16:34:42.713  6807  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 16:34:42.713  6807  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 16:34:42.717  6807  6866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 16:34:42.718  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 16:34:42.718  6807  6866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-23 16:34:42.730  6807  6866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-23 16:34:42.730  6807  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 16:34:42.730  6807  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 16:34:42.730  6807  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 16:34:42.730  6807  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 16:34:42.730  6807  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 16:34:42.730  6807  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 16:34:42.730  6807  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 16:34:42.730  6807  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 16:34:42.730  6807  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 16:34:42.731  6807  6866 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 16:34:42.733  6807  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 16:34:42.734  6807  6866 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 16:34:42.735  6807  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 16:34:42.767  6807  6807 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 16:34:42.802  1814  5277 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-23 16:34:42.822  1814  5277 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-23 16:34:42.855  1814  5277 I art     : Explicit concurrent mark sweep GC freed 25463(1641KB) AllocSpace objects, 11(176KB) LOS objects, 51% free, 29MB/61MB, paused 1.025ms total 26.110ms
,08-23 16:34:42.883  1814  5277 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-23 16:34:43.250   340   360 E GBMv2   : DFP En is all cleared set to be enabled
08-23 16:34:43.250   340   360 E GBMv2   : Set value is all cleared set the max
08-23 16:34:43.250   340   360 I GBMv2   : DFP Enabled. Ignore VFP set
,08-23 16:34:43.322  6784  6784 D LgDataFeature: LgDataFeature() Constructor: none
08-23 16:34:43.322  6784  6784 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 16:34:43.509  6807  6869 W jxcore-log: Initializing JXcore engine
08-23 16:34:43.509  6807  6869 W jxcore-log: JXcore engine is ready
,08-23 16:34:43.537  1034  1850 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6877 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-23 16:34:43.538  1034  1850 I ActivityManager: Killing 5561:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-23 16:34:43.561  6869  6869 W Thread-802: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7617]" dev="sockfs" ino=7617 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 16:34:43.561  6869  6869 W Thread-802: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-23 16:34:43.561  6869  6869 W Thread-802: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9893]" dev="sockfs" ino=9893 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 16:34:43.561  6869  6869 W Thread-802: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-23 16:34:43.571  6869  6869 W Thread-802: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33207]" dev="sockfs" ino=33207 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-23 16:34:43.585  6807  6869 W jxcore-log: Starting JXcore engine
08-23 16:34:43.662  6807  6869 W jxcore-log: Platform android
08-23 16:34:43.662  6807  6869 W jxcore-log: 
08-23 16:34:43.662  6807  6869 W jxcore-log: Process ARCH arm
08-23 16:34:43.662  6807  6869 W jxcore-log: 
,08-23 16:34:43.674  1034  2034 W libprocessgroup: failed to open /acct/uid_10085/pid_5561/cgroup.procs: No such file or directory
,08-23 16:34:43.688  6784  6784 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-23 16:34:43.749  6877  6877 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-23 16:34:43.762  6877  6877 I LockScreenSettings: New app installed broadcast received ..
,08-23 16:34:43.766  6877  6877 I LockScreenSettings: Number of installed packages  1
08-23 16:34:43.813  1034  1941 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6898 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-23 16:34:43.877  6807  6869 I jxcore-log: JXcore Cordova bridge is ready!
08-23 16:34:43.877  6807  6869 I jxcore-log: 
08-23 16:34:43.877  6807  6869 W jxcore-log: JXcore engine is started
,08-23 16:34:43.883  6807  6866 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-23 16:34:43.885  6807  6807 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-23 16:34:43.990  1034  2034 I art     : Explicit concurrent mark sweep GC freed 25042(1185KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.926ms total 137.686ms
,08-23 16:34:44.035  6898  6898 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 16:34:44.311  1034  2012 V SIM_STK : Menu title from STK is T-Mobile
,08-23 16:34:44.360  1034  1976 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6931 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 16:34:44.429  6931  6931 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-23 16:34:44.429  6931  6931 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-23 16:34:44.432  5674  5674 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-23 16:34:44.452  6508  6508 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-23 16:34:44.501  1034  1710 I ActivityManager: Killing 6291:com.google.android.gm/u0a64 (adj 15): empty #17
,08-23 16:34:44.767  1034  1906 W libprocessgroup: failed to open /acct/uid_10064/pid_6291/cgroup.procs: No such file or directory
,08-23 16:34:47.429  6784  6784 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-23 16:34:47.438  1034  1976 I ActivityManager: Killing 6071:com.google.android.talk/u0a72 (adj 15): empty #17
,08-23 16:34:47.547  1034  1869 W libprocessgroup: failed to open /acct/uid_10072/pid_6071/cgroup.procs: No such file or directory
,08-23 16:34:48.401  6784  6871 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-23 16:34:49.301  1034  2034 I ActivityManager: Killing 5830:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-23 16:34:49.322  5797  5797 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-23 16:34:49.323  5797  5797 W System.err: android.os.DeadObjectException
08-23 16:34:49.323  5797  5797 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 16:34:49.323  5797  5797 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 16:34:49.323  5797  5797 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-23 16:34:49.323  5797  5797 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-23 16:34:49.323  5797  5797 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-23 16:34:49.323  5797  5797 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-23 16:34:49.323  5797  5797 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 16:34:49.323  5797  5797 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 16:34:49.323  5797  5797 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 16:34:49.323  5797  5797 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 16:34:49.323  5797  5797 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:34:49.323  5797  5797 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 16:34:49.323  5797  5797 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 16:34:49.323  5797  5797 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 16:34:49.324  5797  5797 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-23 16:34:49.324  5797  5797 W System.err: android.os.DeadObjectException
08-23 16:34:49.324  5797  5797 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 16:34:49.324  5797  5797 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 16:34:49.324  5797  5797 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-23 16:34:49.324  5797  5797 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-23 16:34:49.324  5797  5797 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-23 16:34:49.324  5797  5797 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-23 16:34:49.324  5797  5797 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 16:34:49.324  5797  5797 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 16:34:49.324  5797  5797 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 16:34:49.324  5797  5797 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 16:34:49.324  5797  5797 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:34:49.325  5797  5797 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 16:34:49.325  5797  5797 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 16:34:49.325  5797  5797 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 16:34:49.325  5797  5797 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-23 16:34:49.325  5797  5797 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-23 16:34:49.537  1034  2028 W libprocessgroup: failed to open /acct/uid_1000/pid_5830/cgroup.procs: No such file or directory
,08-23 16:34:49.543  1034  2028 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-23 16:34:49.548  5797  5797 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-23 16:34:49.548  5797  5797 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-23 16:34:49.595  1034  2012 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6977 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 16:34:49.596  5797  5797 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-23 16:34:49.663  6977  6977 D UEI.SmartControl: Quickset Services start...
08-23 16:34:49.664  6977  6977 I UEI.SmartControl: Manufacture = LGE
08-23 16:34:49.665  6977  6977 D UEI.SmartControl: Id = LGNevo
,08-23 16:34:49.667  6977  6977 D UEI.SmartControl: File observer start...
08-23 16:34:49.668  6977  6977 E UEI.SmartControl: IR Port is disabled: false
08-23 16:34:49.668  6977  6977 D UEI.SmartControl: Starting file observer...
08-23 16:34:49.668  6977  6977 D UEI.SmartControl: Extracting JNI libs...
08-23 16:34:49.669  6977  6977 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-23 16:34:49.760  6977  6977 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-23 16:34:49.760  6977  6977 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-23 16:34:49.760  6977  6977 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-23 16:34:49.795  6977  6977 I UEI.SmartControl: --- Selecting new region: 6
,08-23 16:34:49.798  6977  6977 I UEI.SmartControl: Model = LG-D855
,08-23 16:34:49.799  6977  6977 D UEI.SmartControl: QS Service created
,08-23 16:34:49.815  6977  6977 I UEI.SmartControl: Service initServices...
,08-23 16:34:49.820  6977  6977 D UEI.SmartControl: QS start get config
,08-23 16:34:49.879  6977  6977 D UEI.SmartControl: Loading JNI Libs...
,08-23 16:34:50.154  6977  6977 I UEI.SmartControl: Supports setup maps: true
,08-23 16:34:50.161  6977  6977 D UEI.SmartControl: QS start statue = true Error code = 0
08-23 16:34:50.161  6977  6977 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-23 16:34:50.161  6977  6977 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-23 16:34:50.161  6977  6977 I UEI.SmartControl: ### init IR Blaster...
08-23 16:34:50.167  6977  6977 D serial_port: Configuring serial port
08-23 16:34:50.171  6977  6977 E UEI.SmartControl: UEIBLaster setting for 616
08-23 16:34:50.171  6977  6977 I UEI.SmartControl: Setting serial record hearder size = 2
08-23 16:34:50.171  6977  6977 I UEI.SmartControl: configuring settings for MAXQ616
08-23 16:34:50.171  6977  6977 I UEI.SmartControl: Get version...
,08-23 16:34:50.186  6977  7003 D UEI.SmartControl: serial port data available: 21
,08-23 16:34:50.215  6977  6977 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-23 16:34:50.215  6977  6977 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-23 16:34:50.215  6977  6977 I UEI.SmartControl: QS saving settings...
08-23 16:34:50.221  6977  6977 D UEI.SmartControl: IR Blaster version: 25672567
08-23 16:34:50.240  6977  7003 D UEI.SmartControl: serial port data available: 4
,08-23 16:34:50.278  6977  6977 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-23 16:34:50.285  6977  7006 I UEI.SmartControl: Device manager: loading config....
08-23 16:34:50.291  6977  6977 E UEI.SmartControl: Services init done
08-23 16:34:50.291  6977  6977 D UEI.SmartControl: QS Service init finished
08-23 16:34:50.292  6977  7006 D UEI.SmartControl: ----------- loading internal config...
,08-23 16:34:50.300  6977  6977 D UEI.SmartControl: QS Service version name: 2.1.91
08-23 16:34:50.300  6977  6977 D UEI.SmartControl: QS Service version code: 201091
08-23 16:34:50.301  6977  6977 D UEI.SmartControl: Service requested: Control
08-23 16:34:50.309  6977  7006 E UEI.SmartControl: Loading SETTINGS...
,08-23 16:34:50.312  6977  6977 D UEI.SmartControl: Request IControl service: devices are loaded...
08-23 16:34:50.315  1034  1923 I ActivityManager: Killing 5797:com.lge.qremote/u0a112 (adj 15): empty #17
08-23 16:34:50.319  6977  7006 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-23 16:34:50.328  6977  7005 I UEI.SmartControl: Notify AllClients services are ready: 0
08-23 16:34:50.328  6977  7005 D UEI.SmartControl: -----service ready thread exits
,08-23 16:34:50.429  1034  1941 W libprocessgroup: failed to open /acct/uid_10112/pid_5797/cgroup.procs: No such file or directory
,08-23 16:34:50.433  6977  6977 D UEI.SmartControl: Internal service binding...
,08-23 16:34:51.797  2782  2782 I MusicWidget: mDelayedStopHandler : unbind
,08-23 16:34:51.800  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-23 16:34:51.800  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-23 16:34:51.801  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-23 16:34:51.802  2161  2161 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-23 16:34:51.803  2161  2161 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-23 16:34:51.803  2161  2161 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-23 16:34:51.804  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-23 16:34:51.805  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-23 16:34:51.806  1034  1050 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2e9f41cacom.lge.music.MediaPlaybackService$5@c16bf3b
08-23 16:34:51.806  2161  2161 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-23 16:34:51.807  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-23 16:34:51.807  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-23 16:34:51.808  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-23 16:34:51.811  2161  2161 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2e31328
08-23 16:34:51.811  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-23 16:34:51.812  2161  2161 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-23 16:34:51.812  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-23 16:34:51.813  2161  2161 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-23 16:34:51.813  2161  2161 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-23 16:34:51.813  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-23 16:34:51.814  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-23 16:34:51.815  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-23 16:34:51.815  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-23 16:34:51.816  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-23 16:34:51.817  2161  2161 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-23 16:34:51.819  2161  2161 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-23 16:34:51.819  2161  2161 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-23 16:34:51.819  2161  2161 V MediaPlayer[Native]: reset
08-23 16:34:51.825  2161  2161 V MediaPlayer[Native]: setListener
08-23 16:34:51.826  2161  2161 V MediaPlayer[Native]: disconnect
08-23 16:34:51.826  2161  2161 V MediaPlayer[Native]: destructor
,08-23 16:34:51.828   323  2159 V AudioFlinger: releasing 16 from 2161 for -1
,08-23 16:34:51.828   323  2159 V AudioFlinger:  decremented refcount to 0
08-23 16:34:51.829   323  2159 V AudioFlinger: purging stale effects
08-23 16:34:51.829  2161  2161 V MediaPlayer[Native]: disconnect
08-23 16:34:51.830  2161  2161 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-23 16:34:51.832  2161  2161 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-23 16:34:51.832  2161  2161 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-23 16:34:51.833  2161  2161 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-23 16:34:51.834  2161  2161 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-23 16:34:51.834  2161  2161 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-23 16:34:51.834  2161  2161 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 915773016
08-23 16:34:51.834  2161  2161 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 915773016
08-23 16:34:51.844  2161  2161 I SmartShareClient: [SmartShareManagerClient] terminate service: 2161/MediaPlaybackService/9445134
,08-23 16:34:51.851  2161  2161 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-23 16:34:51.851  2161  2161 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@319003b1
08-23 16:34:51.853  2161  2161 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-23 16:34:51.853  2161  2161 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-23 16:34:51.854  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-23 16:34:51.854  2161  2161 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-23 16:34:51.857  1034  1923 I ActivityManager: Killing 5724:com.android.calendar/u0a13 (adj 15): empty #17
,08-23 16:34:51.866  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
08-23 16:34:51.937  1034  1941 W libprocessgroup: failed to open /acct/uid_10013/pid_5724/cgroup.procs: No such file or directory
,08-23 16:34:53.915  6807  6869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 16:34:53.915  6807  6869 I jxcore-log: 
,08-23 16:34:53.919  6807  6869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 16:34:53.919  6807  6869 I jxcore-log: 
,08-23 16:34:53.924  6807  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 16:34:53.924  6807  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 16:34:53.924  6807  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 16:34:53.924  6807  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 16:34:53.924  6807  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 16:34:53.924  6807  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 16:34:53.924  6807  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 16:34:53.924  6807  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 16:34:53.926  6807  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 16:34:53.929  6807  6869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 16:34:53.929  6807  6869 I jxcore-log: 
08-23 16:34:53.931  6807  6869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 16:34:53.931  6807  6869 I jxcore-log: 
,08-23 16:34:54.361  1034  1091 I ActivityManager: Waited long enough for: ServiceRecord{afbca6 u0 com.google.android.gms/.wearable.service.WearableService}
,08-23 16:34:54.433  6807  6869 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-23 16:34:54.434  6807  6869 I jxcore-log: Failed to execute UT.
08-23 16:34:54.434  6807  6869 I jxcore-log: 
08-23 16:34:54.436  6807  6869 I jxcore-log: Unit Test app is loaded
08-23 16:34:54.436  6807  6869 I jxcore-log: 
,08-23 16:34:54.446  6807  6807 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-23 16:34:54.458  6807  6869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 16:34:54.458  6807  6869 I jxcore-log: 
,08-23 16:34:54.477  6807  6869 I jxcore-log: My device name is: LGE-LG-D855
08-23 16:34:54.477  6807  6869 I jxcore-log: 
,08-23 16:34:55.278  6977  7007 D UEI.SmartControl: Internal timer expired: 1
,08-23 16:34:55.282  6977  7007 D UEI.SmartControl: unbind internal service
,08-23 16:34:55.291  6977  6977 D UEI.SmartControl: Service.onUnbind: IControl
08-23 16:34:55.292  6977  6977 D UEI.SmartControl: Service.onDestroy
08-23 16:34:55.293  6977  6977 D UEI.SmartControl: Lock is in USE false
08-23 16:34:55.293  6977  6977 D UEI.SmartControl: unbind internal service
08-23 16:34:55.293  6977  6977 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2e31328
08-23 16:34:55.294  6977  6977 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-23 16:34:55.294  6977  6977 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-23 16:34:55.295  6977  6977 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-23 16:34:55.295  6977  6977 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-23 16:34:55.295  6977  6977 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-23 16:34:55.295  6977  6977 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-23 16:34:55.295  6977  6977 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
,08-23 16:34:55.301  6977  7004 D serial_port: close(fd = 25)
,08-23 16:34:55.295  6977  6977 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-23 16:34:55.302  6977  6977 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 16:34:55.302  6977  6977 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 16:34:55.302  6977  6977 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 16:34:55.302  6977  6977 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:34:55.302  6977  6977 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 16:34:55.302  6977  6977 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 16:34:55.303  6977  6977 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 16:34:55.303  6977  6977 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2e31328
08-23 16:34:55.304  6977  7004 I UEI.SmartControl: Serial port is closed.
08-23 16:34:55.305  6977  6977 I UEI.SmartControl: Serial port is closed.
08-23 16:34:55.305  6977  6977 I UEI.SmartControl: Serial port is closed.
08-23 16:34:55.305  6977  6977 D UEI.SmartControl: Blaster closed
08-23 16:34:55.305  6977  6977 D UEI.SmartControl: Shut down QS...
08-23 16:34:55.306  6977  6977 D UEI.SmartControl: Stopping QS lib
08-23 16:34:55.306  6977  6977 D UEI.SmartControl: QS lib stop result = true
08-23 16:34:55.306  6977  6977 D UEI.SmartControl: Stopped QS lib
08-23 16:34:55.306  6977  6977 D UEI.SmartControl: Stopped file observer...
08-23 16:34:55.306  6977  6977 D UEI.SmartControl: QS shutdown complete
08-23 16:34:58.542  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 16:34:58.542  6807  6869 I jxcore-log: 
,08-23 16:34:58.728  1034  1378 V AlarmManager: RTC_WAKEUP set : Alarm{11f2e3dd type 0 when 1471962896456 com.android.vending} when 1471962896456
,08-23 16:34:58.787  4994  7016 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-23 16:34:58.873  1034  1869 V SIM_STK : Menu title from STK is T-Mobile
,08-23 16:34:59.030  6711  6711 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-23 16:34:59.473  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-23 16:34:59.473  6807  6869 I jxcore-log: 
,08-23 16:34:59.499  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-23 16:34:59.499  6807  6869 I jxcore-log: 
,08-23 16:34:59.504  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-23 16:34:59.504  6807  6869 I jxcore-log: 
08-23 16:34:59.520  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 16:34:59.520  6807  6869 I jxcore-log: 
,08-23 16:34:59.524  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-23 16:34:59.524  6807  6869 I jxcore-log: 
,08-23 16:35:00.045  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:35:00.045  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:35:00.046  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-23 16:35:00.046  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:35:00.048  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-23 16:35:00.049  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:35:00.050  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:35:00.050  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:35:01.883  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19972
,08-23 16:35:02.791  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 16:35:02.791  6807  6869 I jxcore-log: 
,08-23 16:35:02.805  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-23 16:35:02.805  6807  6869 I jxcore-log: 
,08-23 16:35:02.814  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-23 16:35:02.814  6807  6869 I jxcore-log: 
08-23 16:35:02.971  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-23 16:35:02.971  6807  6869 I jxcore-log: 
,08-23 16:35:03.777  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-23 16:35:03.777  6807  6869 I jxcore-log: 
,08-23 16:35:04.021  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-23 16:35:04.021  6807  6869 I jxcore-log: 
,08-23 16:35:04.028  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-23 16:35:04.028  6807  6869 I jxcore-log: 
,08-23 16:35:04.217  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-23 16:35:04.217  6807  6869 I jxcore-log: 
,08-23 16:35:04.239  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-23 16:35:04.239  6807  6869 I jxcore-log: 
,08-23 16:35:04.244  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-23 16:35:04.244  6807  6869 I jxcore-log: 
08-23 16:35:04.249  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-23 16:35:04.249  6807  6869 I jxcore-log: 
08-23 16:35:04.264  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-23 16:35:04.264  6807  6869 I jxcore-log: 
,08-23 16:35:04.283  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-23 16:35:04.283  6807  6869 I jxcore-log: 
,08-23 16:35:04.365  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-23 16:35:04.365  6807  6869 I jxcore-log: 
,08-23 16:35:04.372  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-23 16:35:04.372  6807  6869 I jxcore-log: 
,08-23 16:35:04.400  6807  6869 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-23 16:35:04.400  6807  6869 I jxcore-log: 
,08-23 16:35:04.411  6807  6869 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-23 16:35:04.414  6807  6869 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-23 16:35:04.414  6807  6869 I jxcore-log: 
,08-23 16:35:21.857  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-23 16:35:21.866  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-23 16:36:00.040  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:36:00.040  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:36:00.040  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:36:00.041  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:36:00.054  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-23 16:36:00.055  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:36:00.057  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:36:00.059  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:37:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:37:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:37:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-23 16:37:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated(),
,08-23 16:37:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:37:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:37:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:37:00.074  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:37:07.978  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:37:07.978  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:37:07.994  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:37:07.994  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:37:07.997  1034  1404 D WifiController: battery changed pluggedType: 2
08-23 16:37:07.998  4360  4480 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:37:08.000  1942  2095 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:37:08.000  1942  2095 D LEDHandler: Battery Level Remaining: 100%
08-23 16:37:08.000  1942  2095 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-23 16:37:08.001  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-23 16:37:08.002  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:37:08.003  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:37:08.008  5674  5674 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-23 16:37:35.435  1034  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1069976402, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-23 16:37:35.444  1034  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39687e23 type 2 when 221826 android} when 221826
08-23 16:37:35.486  2590  2590 D [Concierge]Service: onStartCommand(). Type : 9
,08-23 16:37:35.519  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1069976402 [*alarm*], flags=0x0
,08-23 16:38:00.055  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:38:00.055  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:38:00.062  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-23 16:38:00.063  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:38:00.069  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-23 16:38:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:38:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:38:00.074  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:38:34.454  1034  3553 I LocationManagerService: remove 1dd93fb1
,08-23 16:38:34.466  1034  3553 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-23 16:38:34.466  1034  3553 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 16:38:34.468  1034  3553 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-23 16:38:34.471  1034  3553 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-23 16:38:34.473  1034  3553 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-23 16:38:47.538  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:38:47.538  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:38:47.548  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
08-23 16:38:47.548  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:38:47.555  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:38:47.556  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:38:47.558  1034  1404 D WifiController: battery changed pluggedType: 2
08-23 16:38:47.560  1942  2095 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:38:47.560  1942  2095 D LEDHandler: Battery Level Remaining: 100%
08-23 16:38:47.560  1942  2095 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
08-23 16:38:47.562  4360  4480 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:38:47.563  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:38:47.567  5674  5674 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-23 16:38:52.149  1034  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1069976402, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-23 16:38:52.200  2590  2590 D [Concierge]Service: onStartCommand(). Type : 9
,08-23 16:38:52.232  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1069976402 [*alarm*], flags=0x0
,08-23 16:39:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:39:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:39:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:39:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:39:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-23 16:39:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:39:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:39:00.071  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:40:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:40:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:40:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:40:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:40:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-23 16:40:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:40:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:40:00.073  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:41:00.055  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:41:00.055  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:41:00.063  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:41:00.064  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
08-23 16:41:00.071  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:41:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:41:00.074  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:41:00.078  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:42:00.057  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:42:00.057  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:42:00.057  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:42:00.058  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:42:00.071  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:42:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:42:00.074  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:42:00.077  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:42:08.778  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:42:08.778  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:42:08.793  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:42:08.793  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:42:08.795  1034  1404 D WifiController: battery changed pluggedType: 2
08-23 16:42:08.796  4360  4480 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:42:08.799  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-23 16:42:08.799  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:42:08.801  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:42:08.802  1942  2095 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:42:08.802  1942  2095 D LEDHandler: Battery Level Remaining: 100%
08-23 16:42:08.802  1942  2095 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-23 16:42:08.806  5674  5674 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-23 16:43:00.055  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:43:00.055  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:43:00.055  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-23 16:43:00.064  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
08-23 16:43:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:43:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:43:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:43:00.074  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:44:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:44:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:44:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-23 16:44:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:44:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:44:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:44:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:44:00.073  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:44:48.418  1034  1051 I ActivityManager: Killing 6351:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-23 16:44:48.483  1034  1993 W libprocessgroup: failed to open /acct/uid_10014/pid_6351/cgroup.procs: No such file or directory
,08-23 16:45:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:45:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:45:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:45:00.055  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:45:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:45:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:45:00.073  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:45:00.074  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:45:01.261  1034  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1069976402, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-23 16:45:01.320  1034  1091 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7069 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-23 16:45:01.352  2590  2590 D [Concierge]Service: onStartCommand(). Type : 9
,08-23 16:45:01.498  7069  7069 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-23 16:45:01.504  7069  7069 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@36f3c109
08-23 16:45:01.505  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1069976402 [*alarm*], flags=0x0
,08-23 16:45:01.507  1034  2012 I ActivityManager: Killing 6439:com.android.defcontainer/u0a4 (adj 15): empty #17
08-23 16:45:01.540  1034  1923 W libprocessgroup: failed to open /acct/uid_10004/pid_6439/cgroup.procs: No such file or directory
,08-23 16:46:00.055  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:46:00.055  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:46:00.062  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-23 16:46:00.063  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:46:00.069  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:46:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:46:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:46:00.074  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:47:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:47:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:47:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-23 16:47:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated(),
,08-23 16:47:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-23 16:47:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:47:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:47:00.074  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:48:00.055  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:48:00.055  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:48:00.056  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:48:00.056  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:48:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:48:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:48:00.073  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:48:00.075  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:48:39.509  1034  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1069976402, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-23 16:48:39.530  1034  1378 V AlarmManager: RTC_WAKEUP set : Alarm{39fe8f20 type 0 when 1471963486496 com.google.android.gms} when 1471963486496
,08-23 16:48:39.544  1034  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{119e0a9e type 2 when 929456 com.google.android.gms} when 929456
,08-23 16:48:39.583  2590  2590 D [Concierge]Service: onStartCommand(). Type : 9
,08-23 16:48:39.611  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1069976402 [*alarm*], flags=0x0
,08-23 16:48:39.630  2283  2950 D GCM     : Message class com.google.e.a.a.h
08-23 16:48:39.647  1814  7111 I EventLogService: Aggregate from 1471962821561 (log), 1471961686395 (data)
,08-23 16:48:48.547  1034  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3bbad97f type 2 when 949058 com.android.bluetooth} when 949058
,08-23 16:48:48.553  4360  4558 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-23 16:48:48.553  4360  4558 W bt-smp  : Plain text(LSB ~ MSB) = ab b4 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-23 16:48:48.553  4360  4558 W bt-smp  : Encrypted text(LSB ~ MSB) = 35 53 e7 8d 7e 74 9b 05 5e e0 1c 7f b8 16 7f 7b 
08-23 16:48:48.554  4360  4558 W bt-btm  : Stopping oneshot timer
08-23 16:49:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:49:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:49:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:49:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:49:00.069  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-23 16:49:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:49:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:49:00.073  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:50:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:50:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:50:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:50:00.055  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:50:00.071  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:50:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:50:00.073  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:50:00.078  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:51:00.058  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:51:00.058  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:51:00.059  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:51:00.059  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:51:00.072  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:51:00.073  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:51:00.075  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:51:00.079  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:52:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:52:00.055  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:52:00.055  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-23 16:52:00.063  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
08-23 16:52:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-23 16:52:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:52:00.073  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:52:00.075  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:53:00.055  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:53:00.055  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:53:00.055  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:53:00.056  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:53:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-23 16:53:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:53:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:53:00.074  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:53:19.579  1034  1090 I UsageStatsService: User[0] Flushing usage stats to disk
,08-23 16:54:00.077  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:54:00.077  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:54:00.078  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:54:00.078  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:54:00.092  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:54:00.092  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:54:00.095  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:54:00.097  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:55:00.110  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:55:00.110  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:55:00.111  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:55:00.111  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:55:00.124  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:55:00.125  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:55:00.127  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:55:00.129  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:56:00.107  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-23 16:56:00.115  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:56:00.116  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:56:00.116  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
08-23 16:56:00.123  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:56:00.124  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:56:00.131  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:56:00.134  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:57:00.060  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:57:00.061  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:57:00.061  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:57:00.061  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:57:00.075  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-23 16:57:00.076  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-23 16:57:00.078  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:57:00.080  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:58:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:58:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:58:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 16:58:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
