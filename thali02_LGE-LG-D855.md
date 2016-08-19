#### Test 8180285644342f8_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-19 17:54:57.260  5904  5904 I AppConfig: Total System Memory = 2995761152
08-19 17:54:57.274  5904  5904 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
--------- beginning of system
08-19 17:54:57.302  1029  1996 I ActivityManager: Killing 5019:com.lge.bnr/1000 (adj 15): empty #17
08-19 17:54:57.324   333   412 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-19 17:54:57.325  3215  5928 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-19 17:54:57.340  1992  1992 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-19 17:54:57.340  1992  1992 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-19 17:54:57.343  1029  1883 W libprocessgroup: failed to open /acct/uid_1000/pid_5019/cgroup.procs: No such file or directory
08-19 17:54:57.354  1992  1992 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-19 17:54:57.366  3650  3650 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-19 17:54:57.369  3650  3650 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-19 17:54:57.394  4485  5933 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-19 17:54:57.436  1029  1782 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5934 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-19 17:54:57.454  1029  1955 V SIM_STK : Menu title from STK is T-Mobile
08-19 17:54:57.530  4485  5933 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 135 ms] updated apps [took 135 ms] 
08-19 17:54:57.598  5934  5934 D DocsApplication: Installing DEX configuration.
08-19 17:54:57.616  5934  5934 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-19 17:54:57.620  5934  5934 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{2f5ca56c com.google.android.apps.docs}
08-19 17:54:57.635  5934  5934 D TAG     : onCreate()
08-19 17:54:57.654  5934  5934 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-19 17:54:58.516  5952  5952 D AndroidRuntime: 
08-19 17:54:58.516  5952  5952 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-19 17:54:58.519  5952  5952 D AndroidRuntime: CheckJNI is OFF
08-19 17:54:58.533  1814  4551 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-19 17:54:58.628  1814  4551 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-19 17:54:58.662  5952  5952 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-19 17:54:58.666  5934  5934 D LgDataFeature: LgDataFeature() Constructor: none
08-19 17:54:58.666  5934  5934 D LgDataFeature: LgDataFeature() Constructor Done, null
08-19 17:54:58.678  1029  1982 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-19 17:54:58.688  1937  3186 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-19 17:54:58.690  1029  1982 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-19 17:54:58.691  1029  1982 D ActivityManager: setTaskToReturnTo : TaskRecord{8a29bbc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-19 17:54:58.691  1029  1982 D ActivityManager: setTaskToReturnTo : TaskRecord{8a29bbc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-19 17:54:58.692  1029  1982 D WindowStateEx: AppWindowTokenEx init.. 
08-19 17:54:58.693   346   355 E GBMv2   : DFP En is all cleared set to be enabled
08-19 17:54:58.723  1029  1982 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5974 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-19 17:54:58.727  5952  5952 D AndroidRuntime: Shutting down VM
08-19 17:54:58.748  1814  4551 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-19 17:54:58.767  1937  1953 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-19 17:54:58.768  1937  1953 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15d2b19a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-19 17:54:58.769  1937  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-19 17:54:58.769  1937  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{33eebacb co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-19 17:54:58.807  5974  5974 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-19 17:54:58.857  5934  5934 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-19 17:54:58.894  1029  1982 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5998 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-19 17:54:58.904  5974  5974 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-19 17:54:58.912  5974  5974 I LibraryLoader: Loading: webviewchromium
08-19 17:54:58.915  5974  5974 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 988-992)
08-19 17:54:58.915  5974  5974 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-19 17:54:58.930  5974  5974 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c43b696}
08-19 17:54:58.932  5974  5974 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-19 17:54:58.932  5974  5974 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-19 17:54:58.941  5974  5974 I BrowserStartupController: Initializing chromium process, renderers=0
08-19 17:54:58.942  5974  5974 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-19 17:54:58.951  5974  6017 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-19 17:54:58.955  5974  5974 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-19 17:54:58.956  5974  5974 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-19 17:54:58.956  5974  5974 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-19 17:54:58.957   322   322 V AudioPolicyService: registerClient() client 0xb57f5900, uid 10118
08-19 17:54:58.961  1029  1091 D BluetoothManagerService: Message: 20
08-19 17:54:58.961  1029  1091 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19ed6f2:true
08-19 17:54:58.970  5974  5974 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-19 17:54:58.970  5974  5974 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-19 17:54:58.970  5974  5974 I Adreno-EGL: Build Date: 12/12/14 금
08-19 17:54:58.970  5974  5974 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-19 17:54:58.970  5974  5974 I Adreno-EGL: Remote Branch: 
08-19 17:54:58.970  5974  5974 I Adreno-EGL: Local Patches: 
08-19 17:54:58.970  5974  5974 I Adreno-EGL: Reconstruct Branch: 
,08-19 17:54:58.972  5998  5998 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-19 17:54:58.983  5998  5998 I LockScreenSettings: New app installed broadcast received ..
,08-19 17:54:58.986  5998  5998 I LockScreenSettings: Number of installed packages  1
08-19 17:54:59.053  1029  1911 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6031 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-19 17:54:59.054  1029  1911 I ActivityManager: Killing 5375:com.google.android.gm/u0a64 (adj 15): empty #17
08-19 17:54:59.065   383   383 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 20.539ms
,08-19 17:54:59.086   383   383 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 20.224ms
,08-19 17:54:59.106   383   383 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 604us total 19.611ms
,08-19 17:54:59.115  1029  1571 W libprocessgroup: failed to open /acct/uid_10064/pid_5375/cgroup.procs: No such file or directory
,08-19 17:54:59.143  6031  6031 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-19 17:54:59.158  5974  6027 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-19 17:54:59.161  5974  5974 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-19 17:54:59.168   314   314 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
08-19 17:54:59.168   314   314 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
08-19 17:54:59.168   314   314 I rmt_storage: wakelock acquired: 1, error no: 42
08-19 17:54:59.169   314   904 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
08-19 17:54:59.180  5974  5974 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-19 17:54:59.193  5974  5974 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-19 17:54:59.199  5974  5974 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-19 17:54:59.204  5974  5974 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-19 17:54:59.204  5974  5974 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-19 17:54:59.221  5974  5974 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-19 17:54:59.229  5974  5974 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-19 17:54:59.229  5974  5974 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-19 17:54:59.237   314   904 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
08-19 17:54:59.237   314   904 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,08-19 17:54:59.237   314   904 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
08-19 17:54:59.237   314   904 I rmt_storage: 
08-19 17:54:59.239   896   903 E Diag_Lib: [IMS_FATAL]| 3347 | 903 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-19 17:54:59.239   314   314 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,08-19 17:54:59.265  5974  6056 D OpenGLRenderer: Render dirty regions requested: true
08-19 17:54:59.265  5974  6056 I OpenGLRenderer: Initialized EGL, version 1.4
08-19 17:54:59.266  1029  1087 W ActivityManager: Activity pause timeout for ActivityRecord{2817c745 u0 com.test.thalitest/.MainActivity t6}
08-19 17:54:59.274  5974  6056 D OpenGLRenderer: Enabling debug mode 0
,08-19 17:54:59.282  5974  5974 D Atlas   : Validating map...
08-19 17:54:59.286  1029  1782 D SplitWindow: check instance of lgWin Window{20ea81c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-19 17:54:59.318  5974  6054 D LgDataFeature: LgDataFeature() Constructor: none
,08-19 17:54:59.318  5974  6054 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-19 17:54:59.378  1029  1092 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +613ms (total +685ms)
08-19 17:54:59.378  1029  1092 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2817c745 u0 com.test.thalitest/.MainActivity t6} time:101455
08-19 17:54:59.378  5974  5974 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@690265d time:101455
08-19 17:54:59.494  5974  5974 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-19 17:54:59.494  5974  5974 I chromium: 
,08-19 17:54:59.526  5974  5974 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-19 17:54:59.634  5974  6071 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435132928
,08-19 17:54:59.645  5974  6071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-19 17:54:59.645  5974  6071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-19 17:54:59.645  5974  6071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-19 17:54:59.645  5974  6071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-19 17:54:59.645  5974  6071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-19 17:54:59.645  5974  6071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3efc8c91 added. We now have 1 listener(s)
08-19 17:54:59.649  1029  1571 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:54:59.651  5974  6071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-19 17:54:59.652  5974  6071 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:54:59.653  5974  6071 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-19 17:54:59.653  5974  6071 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-19 17:54:59.659  5974  6071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99b0664 added. We now have 1 listener(s)
08-19 17:54:59.659  5974  6071 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:54:59.662  1029  1540 D WifiService: New client listening to asynchronous messages
08-19 17:54:59.665  1029  1996 V SIM_STK : Menu title from STK is T-Mobile
08-19 17:54:59.665  5974  6071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:54:59.665  5974  6071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-19 17:54:59.667  5974  6071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-19 17:54:59.667  5974  6071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-19 17:54:59.667  5974  6071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-19 17:54:59.669  5974  6071 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:54:59.670  1029  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:54:59.671  5974  6071 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-19 17:54:59.678  5974  6071 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-19 17:54:59.678  5974  6071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:54:59.678  5974  6071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:59.678  5974  6071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:54:59.678  5974  6071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:54:59.678  5974  6071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:54:59.678  5974  6071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:54:59.678  5974  6071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:59.678  5974  6071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:54:59.678  5974  6071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-19 17:54:59.678  5974  6071 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:54:59.679  5974  6071 I io.jxcore.node.LifeCycleMonitor: start: OK
08-19 17:54:59.679  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:54:59.709   346   357 E GBMv2   : DFP En is all cleared set to be enabled
,08-19 17:54:59.709   346   357 E GBMv2   : Set value is all cleared set the max
08-19 17:54:59.709   346   357 I GBMv2   : DFP Enabled. Ignore VFP set
08-19 17:54:59.712  1029  1996 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6085 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-19 17:54:59.720  5974  6054 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-19 17:54:59.720  5974  6054 I chromium: 
,08-19 17:54:59.765  5974  5974 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-19 17:54:59.775  6085  6085 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-19 17:54:59.775  6085  6085 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-19 17:54:59.799  1029  1782 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6106 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-19 17:54:59.800  1029  1782 I ActivityManager: Killing 5413:com.google.android.talk/u0a72 (adj 15): empty #17
,08-19 17:54:59.854  1029  1996 W libprocessgroup: failed to open /acct/uid_10072/pid_5413/cgroup.procs: No such file or directory
,08-19 17:54:59.897  6106  6106 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-19 17:54:59.910  6106  6106 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-19 17:54:59.911  1029  1955 I ActivityManager: Killing 5176:com.lge.sync/1000 (adj 15): empty #17
08-19 17:54:59.975  1029  1996 W libprocessgroup: failed to open /acct/uid_1000/pid_5176/cgroup.procs: No such file or directory
,08-19 17:55:00.050  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-19 17:55:00.050  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-19 17:55:00.050  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-19 17:55:00.050  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
08-19 17:55:00.051  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
08-19 17:55:00.051  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
08-19 17:55:00.052  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
08-19 17:55:00.052  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
08-19 17:55:00.478  5974  6083 W jxcore-log: Initializing JXcore engine
08-19 17:55:00.478  5974  6083 W jxcore-log: JXcore engine is ready
,08-19 17:55:00.504  6083  6083 W Thread-672: type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[8636]" dev="sockfs" ino=8636 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-19 17:55:00.504  6083  6083 W Thread-672: type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-19 17:55:00.504  6083  6083 W Thread-672: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[10367]" dev="sockfs" ino=10367 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-19 17:55:00.504  6083  6083 W Thread-672: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-19 17:55:00.504  6083  6083 W Thread-672: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[29087]" dev="sockfs" ino=29087 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-19 17:55:00.525  5974  6083 W jxcore-log: Starting JXcore engine
08-19 17:55:00.654  5974  6083 W jxcore-log: Platform android
08-19 17:55:00.654  5974  6083 W jxcore-log: 
08-19 17:55:00.654  5974  6083 W jxcore-log: Process ARCH arm
08-19 17:55:00.654  5974  6083 W jxcore-log: 
,08-19 17:55:00.997  5974  6083 I jxcore-log: JXcore Cordova bridge is ready!
08-19 17:55:00.997  5974  6083 I jxcore-log: 
,08-19 17:55:00.997  5974  6083 W jxcore-log: JXcore engine is started
,08-19 17:55:01.006  5974  6071 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-19 17:55:01.009  5974  5974 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-19 17:55:02.614  2797  2797 I MusicWidget: mDelayedStopHandler : unbind
08-19 17:55:02.615  2145  2145 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-19 17:55:02.616  2145  2145 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
,08-19 17:55:02.616  2145  2145 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-19 17:55:02.617  2145  2145 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-19 17:55:02.618  2145  2145 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-19 17:55:02.618  2145  2145 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-19 17:55:02.619  2145  2145 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-19 17:55:02.619  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-19 17:55:02.620  1029  1919 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1df23f07com.lge.music.MediaPlaybackService$5@15c32834
08-19 17:55:02.621  2145  2145 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-19 17:55:02.621  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-19 17:55:02.621  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-19 17:55:02.622  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-19 17:55:02.623  2145  2145 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@29fca622
08-19 17:55:02.623  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-19 17:55:02.623  2145  2145 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-19 17:55:02.624  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-19 17:55:02.624  2145  2145 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-19 17:55:02.624  2145  2145 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-19 17:55:02.624  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-19 17:55:02.633  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-19 17:55:02.636  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-19 17:55:02.637  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-19 17:55:02.637  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-19 17:55:02.638  2145  2145 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-19 17:55:02.640  2145  2145 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-19 17:55:02.640  2145  2145 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-19 17:55:02.640  2145  2145 V MediaPlayer[Native]: reset
08-19 17:55:02.647  2145  2145 V MediaPlayer[Native]: setListener
08-19 17:55:02.647  2145  2145 V MediaPlayer[Native]: disconnect
08-19 17:55:02.647  2145  2145 V MediaPlayer[Native]: destructor
08-19 17:55:02.647   322  2138 V AudioFlinger: releasing 18 from 2145 for -1
08-19 17:55:02.647   322  2138 V AudioFlinger:  decremented refcount to 0
08-19 17:55:02.647   322  2138 V AudioFlinger: purging stale effects
08-19 17:55:02.647  2145  2145 V MediaPlayer[Native]: disconnect
,08-19 17:55:02.654  2145  2145 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-19 17:55:02.655  2145  2145 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-19 17:55:02.663  2145  2145 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
,08-19 17:55:02.666  2145  2145 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-19 17:55:02.666  2145  2145 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-19 17:55:02.667  2145  2145 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-19 17:55:02.667  2145  2145 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 110110301
08-19 17:55:02.667  2145  2145 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 110110301
08-19 17:55:02.675  2145  2145 I SmartShareClient: [SmartShareManagerClient] terminate service: 2145/MediaPlaybackService/975481944
08-19 17:55:02.679  2145  2145 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-19 17:55:02.679  2145  2145 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3ffedbd2
,08-19 17:55:02.684  2145  2145 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-19 17:55:02.684  2145  2145 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-19 17:55:02.685  2145  2145 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-19 17:55:02.685  2145  2145 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-19 17:55:02.688  1029  1782 I ActivityManager: Killing 5158:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-19 17:55:02.689  2145  2145 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29996
08-19 17:55:02.701  5124  5124 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-19 17:55:02.702  5124  5124 W System.err: android.os.DeadObjectException
,08-19 17:55:02.703  5124  5124 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-19 17:55:02.703  5124  5124 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-19 17:55:02.703  5124  5124 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-19 17:55:02.704  5124  5124 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-19 17:55:02.704  5124  5124 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-19 17:55:02.704  5124  5124 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-19 17:55:02.704  5124  5124 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:02.704  5124  5124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:02.704  5124  5124 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-19 17:55:02.704  5124  5124 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-19 17:55:02.704  5124  5124 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:02.704  5124  5124 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:02.704  5124  5124 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-19 17:55:02.704  5124  5124 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-19 17:55:02.705  5124  5124 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-19 17:55:02.705  5124  5124 W System.err: android.os.DeadObjectException
08-19 17:55:02.705  5124  5124 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-19 17:55:02.705  5124  5124 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-19 17:55:02.705  5124  5124 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-19 17:55:02.705  5124  5124 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-19 17:55:02.705  5124  5124 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-19 17:55:02.705  5124  5124 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-19 17:55:02.705  5124  5124 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-19 17:55:02.705  5124  5124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-19 17:55:02.705  5124  5124 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-19 17:55:02.705  5124  5124 W System.err: 	,at android.app.ActivityThread.main(ActivityThread.java:5274)
08-19 17:55:02.705  5124  5124 W System.err: ,	at java.lang.reflect.Method.invoke(Native Method)
,08-19 17:55:02.705  5124  5124 W System.err: 	,at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:02.705  5124  5124 W System.err: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-19 17:55:02.705  5124  5124 W System.err: 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704),
08-19 17:55:02.706  5124  5124 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-19 17:55:02.707  5124  5124 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-19 17:55:02.925  1029  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_5158/cgroup.procs: No such file or directory
08-19 17:55:02.925  1029  1046 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-19 17:55:02.935  5124  5124 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-19 17:55:02.935  5124  5124 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-19 17:55:02.936  1029  1389 D PowerManagerServiceEx: acquireWakeLockInternal: lock=752504908, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
08-19 17:55:02.987  5934  5934 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-19 17:55:02.989  1029  1947 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6131 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-19 17:55:02.999  1029  1782 I ActivityManager: Killing 5196:com.android.settings/1000 (adj 15): empty #17
,08-19 17:55:03.030  5124  5124 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-19 17:55:03.047  4375  6130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-19 17:55:03.164  1029  1783 W libprocessgroup: failed to open /acct/uid_1000/pid_5196/cgroup.procs: No such file or directory
08-19 17:55:03.187  2594  2594 D [Concierge]Service: onStartCommand(). Type : 9
,08-19 17:55:03.206  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=752504908 [*alarm*], flags=0x0
,08-19 17:55:03.220  6131  6131 D UEI.SmartControl: Quickset Services start...
08-19 17:55:03.222  6131  6131 I UEI.SmartControl: Manufacture = LGE
08-19 17:55:03.222  6131  6131 D UEI.SmartControl: Id = LGNevo
08-19 17:55:03.224  6131  6131 D UEI.SmartControl: File observer start...
08-19 17:55:03.224  6131  6131 E UEI.SmartControl: IR Port is disabled: false
08-19 17:55:03.225  6131  6131 D UEI.SmartControl: Starting file observer...
08-19 17:55:03.225  6131  6131 D UEI.SmartControl: Extracting JNI libs...
08-19 17:55:03.225  6131  6131 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-19 17:55:03.296  6131  6131 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-19 17:55:03.296  6131  6131 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-19 17:55:03.296  6131  6131 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-19 17:55:03.321  6131  6131 I UEI.SmartControl: --- Selecting new region: 6
,08-19 17:55:03.322  6131  6131 I UEI.SmartControl: Model = LG-D855
08-19 17:55:03.323  6131  6131 D UEI.SmartControl: QS Service created
08-19 17:55:03.333  6131  6131 I UEI.SmartControl: Service initServices...
,08-19 17:55:03.336  6131  6131 D UEI.SmartControl: QS start get config
08-19 17:55:03.380  6131  6131 D UEI.SmartControl: Loading JNI Libs...
,08-19 17:55:03.617  6131  6131 I UEI.SmartControl: Supports setup maps: true
,08-19 17:55:03.620  6131  6131 D UEI.SmartControl: QS start statue = true Error code = 0
,08-19 17:55:03.620  6131  6131 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-19 17:55:03.620  6131  6131 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-19 17:55:03.620  6131  6131 I UEI.SmartControl: ### init IR Blaster...
08-19 17:55:03.626  6131  6131 D serial_port: Configuring serial port
08-19 17:55:03.634  6131  6131 E UEI.SmartControl: UEIBLaster setting for 616
08-19 17:55:03.635  6131  6131 I UEI.SmartControl: Setting serial record hearder size = 2
08-19 17:55:03.636  6131  6131 I UEI.SmartControl: configuring settings for MAXQ616
08-19 17:55:03.636  6131  6131 I UEI.SmartControl: Get version...
08-19 17:55:03.652  6131  6171 D UEI.SmartControl: serial port data available: 21
,08-19 17:55:03.681  6131  6131 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-19 17:55:03.681  6131  6131 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-19 17:55:03.681  6131  6131 I UEI.SmartControl: QS saving settings...
,08-19 17:55:03.684  6131  6131 D UEI.SmartControl: IR Blaster version: 25672567
08-19 17:55:03.700  6131  6171 D UEI.SmartControl: serial port data available: 4
,08-19 17:55:03.740  6131  6131 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-19 17:55:03.743  6131  6131 E UEI.SmartControl: Services init done
,08-19 17:55:03.743  6131  6131 D UEI.SmartControl: QS Service init finished
08-19 17:55:03.744  6131  6131 D UEI.SmartControl: QS Service version name: 2.1.91
08-19 17:55:03.744  6131  6131 D UEI.SmartControl: QS Service version code: 201091
08-19 17:55:03.749  6131  6175 I UEI.SmartControl: Device manager: loading config....
08-19 17:55:03.751  6131  6175 D UEI.SmartControl: ----------- loading internal config...
08-19 17:55:03.755  6131  6131 D UEI.SmartControl: Service requested: Control
08-19 17:55:03.758  6131  6175 E UEI.SmartControl: Loading SETTINGS...
08-19 17:55:03.763  5934  5973 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
08-19 17:55:03.769  6131  6131 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-19 17:55:03.772  1029  2022 I ActivityManager: Killing 5124:com.lge.qremote/u0a112 (adj 15): empty #17
08-19 17:55:03.778  6131  6175 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-19 17:55:03.796  6131  6174 I UEI.SmartControl: Notify AllClients services are ready: 0
08-19 17:55:03.796  6131  6174 D UEI.SmartControl: -----service ready thread exits
,08-19 17:55:03.884  1029  1046 W libprocessgroup: failed to open /acct/uid_10112/pid_5124/cgroup.procs: No such file or directory
,08-19 17:55:03.886  6131  6131 D UEI.SmartControl: Internal service binding...
08-19 17:55:04.163  2772  2772 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-19 17:55:04.167  1029  2788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,08-19 17:55:04.167  1029  2788 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-19 17:55:04.167  1029  2788 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-19 17:55:04.167  1029  2788 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-19 17:55:04.736  1029  1919 I ActivityManager: Killing 5072:com.android.calendar/u0a13 (adj 15): empty #17
,08-19 17:55:04.835  1029  1645 W libprocessgroup: failed to open /acct/uid_10013/pid_5072/cgroup.procs: No such file or directory
,08-19 17:55:05.645  1814  5793 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-19 17:55:05.651   318  6182 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-19 17:55:05.652  1814  5793 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-19 17:55:05.652  1029  1089 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-19 17:55:05.652  1814  1814 I ConfigFetchService: fetch service done; releasing wakelock
08-19 17:55:05.653  1814  1814 I ConfigFetchService: stopping self
08-19 17:55:05.656  2177  2177 I ConfigService: onDestroy
08-19 17:55:06.381  1029  2788 E WifiMonitor: WifiMonitor:wlan0 cnt=66 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-19 17:55:06.382  1029  2788 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-19 17:55:06.384  1029  1534 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-19 17:55:06.387  2772  2772 I wpa_supplicant: [LGE_PATCH]scan interval[4] = 30 sec.
08-19 17:55:06.389  1937  2790 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-19 17:55:06.389  1029  1534 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-19 17:55:06.390  1029  1534 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-19 17:55:06.390  1029  1534 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-19 17:55:06.390  1029  1534 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-19 17:55:06.392  1029  2788 E WifiMonitor: WifiMonitor:p2p0 cnt=67 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-19 17:55:06.392  1029  2788 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-19 17:55:06.393  1029  1533 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:06.393  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:06.393  1029  1533 D LGWifiP2pService: DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:06.393  1029  1534 D WifiNative-wlan0: doString: [BSS RANGE=57- MASK=0x21987]
,08-19 17:55:08.743  6131  6176 D UEI.SmartControl: Internal timer expired: 1
08-19 17:55:08.743  6131  6176 D UEI.SmartControl: unbind internal service
,08-19 17:55:08.753  6131  6131 D UEI.SmartControl: Service.onUnbind: IControl
08-19 17:55:08.753  6131  6131 D UEI.SmartControl: Service.onDestroy
08-19 17:55:08.753  6131  6131 D UEI.SmartControl: Lock is in USE false
08-19 17:55:08.753  6131  6131 D UEI.SmartControl: unbind internal service
08-19 17:55:08.753  6131  6131 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@29fca622
08-19 17:55:08.753  6131  6131 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-19 17:55:08.753  6131  6131 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-19 17:55:08.753  6131  6131 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-19 17:55:08.753  6131  6131 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-19 17:55:08.753  6131  6131 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-19 17:55:08.753  6131  6131 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-19 17:55:08.753  6131  6131 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-19 17:55:08.753  6131  6131 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-19 17:55:08.753  6131  6131 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:55:08.753  6131  6131 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-19 17:55:08.753  6131  6131 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-19 17:55:08.753  6131  6131 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:55:08.753  6131  6131 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:08.754  6131  6131 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-19 17:55:08.754  6131  6131 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-19 17:55:08.754  6131  6131 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@29fca622
08-19 17:55:08.754  6131  6131 D serial_port: close(fd = 25)
08-19 17:55:08.757  6131  6131 I UEI.SmartControl: Serial port is closed.
08-19 17:55:08.758  6131  6131 I UEI.SmartControl: Serial port is closed.
08-19 17:55:08.758  6131  6131 D UEI.SmartControl: Blaster closed
08-19 17:55:08.758  6131  6131 D UEI.SmartControl: Shut down QS...
08-19 17:55:08.758  6131  6131 D UEI.SmartControl: Stopping QS lib
08-19 17:55:08.758  6131  6131 D UEI.SmartControl: QS lib stop result = true
08-19 17:55:08.758  6131  6131 D UEI.SmartControl: Stopped QS lib
,08-19 17:55:08.761  6131  6131 D UEI.SmartControl: Stopped file observer...
08-19 17:55:08.761  6131  6131 D UEI.SmartControl: QS shutdown complete
,08-19 17:55:10.759  1029  1087 I ActivityManager: Waited long enough for: ServiceRecord{29259593 u0 com.google.android.gms/.wearable.service.WearableService}
,08-19 17:55:10.967  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-19 17:55:10.967  5974  6083 I jxcore-log: 
,08-19 17:55:10.970  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-19 17:55:10.970  5974  6083 I jxcore-log: 
,08-19 17:55:10.975  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:10.975  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:10.975  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:10.975  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:10.975  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:10.975  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:10.975  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:10.975  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:10.978  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:10.981  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-19 17:55:10.981  5974  6083 I jxcore-log: 
,08-19 17:55:10.983  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-19 17:55:10.983  5974  6083 I jxcore-log: 
08-19 17:55:11.482  5974  6083 D ExecuteNativeTests: Running unit tests
,08-19 17:55:11.566  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:11.567  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b added. We now have 2 listener(s)
08-19 17:55:11.567  1029  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:11.569  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:55:11.569  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:11.569  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:11.569  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:11.569  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 added. We now have 2 listener(s)
08-19 17:55:11.569  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:11.570  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:55:11.572  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:11.574  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:11.574  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:11.574  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:11.574  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:11.574  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:11.574  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:11.574  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:11.574  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:11.576  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:11.576  5974  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:11.577  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:11.580  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-19 17:55:11.582  5974  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-19 17:55:11.582  5974  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-19 17:55:11.584  5974  6083 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-19 17:55:11.585  5974  6083 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-19 17:55:11.585  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-19 17:55:11.585  5974  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:55:11.585  5974  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:55:11.586  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.586  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.586  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.587  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.587  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.587  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:11.587  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:11.587  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b removed from the list
08-19 17:55:11.587  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.587  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 removed from the list
08-19 17:55:11.587  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.587  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.588  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.588  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.588  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.588  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.588  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.588  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.590  5974  6083 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-19 17:55:11.590  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.590  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.590  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.590  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.590  5974  6083 W org.thaliprojec,t.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.590  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.590  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.590  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.591  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.591  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.591  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.591  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.591  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.591  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.591  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.591  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.591  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.591  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:12,10:1210]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-19 17:55:11.596  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-19 17:55:11.597  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-19 17:55:11.597  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-19 17:55:11.597  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-19 17:55:11.597  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-19 17:55:11.597  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-19 17:55:11.597  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-19 17:55:11.597  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-19 17:55:11.597  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-19 17:55:11.597  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-19 17:55:11.597  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-19 17:55:11.597  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.597  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.597  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:55:11.601  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:55:11.602  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.602  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.603  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.603  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.605  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.605  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.605  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.605  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.605  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.605  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.606  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.606  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.606  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.606  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.607  5974  6083 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-19 17:55:11.608  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:11.612  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:11.612  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:11.612  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:11.612  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:11.612  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:11.612  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:11.612  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:11.612  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:11.615  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:11.615  5974  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:11.616  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:11.616  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:11.616  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:11.616  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:11.616  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:11.616  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:55:11.619  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-19 17:55:11.619  1029  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:11.622  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-19 17:55:11.626  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:55:11.628  5974  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-19 17:55:11.629  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:55:11.629  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:11.630  5974  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-19 17:55:11.630  5974  6083 I io.jxcore.node.ConnectionHelper: start: OK
08-19 17:55:11.632  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.632  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.632  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.632  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.632  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.632  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:11.632  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.632  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.632  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.632  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.632  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.633  5974  6083 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-19 17:55:11.634  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:11.636  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:11.636  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:11.636  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:11.636  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:11.636  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:11.636  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:11.636  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:11.636  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:11.637  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:11.637  5974  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:11.637  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:11.637  5974  6083 V io.jxcore.node.StartStopOperationHandler: execute,CurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:11.637  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:11.637  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:11.637  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:55:11.638  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:11.641  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:55:11.641  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:11.643  5974  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-19 17:55:11.643  5974  6083 I io.jxcore.node.ConnectionHelper: start: OK
08-19 17:55:11.644  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.644  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.644  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.644  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.645  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.645  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:11.645  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.645  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.645  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.645  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.645  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.645  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.645  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.646  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.646  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.647  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.647  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.647  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.647  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.647  5974  6083 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-19 17:55:11.648  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:11.650  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:11.650  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:11.650  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:11.650  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:11.650  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:11.650  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID na,me: null
08-19 17:55:11.650  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:11.650  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:11.651  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:11.651  5974  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:11.652  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:11.652  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:11.652  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:11.652  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:11.652  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:11.652  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:55:11.723  1029  1571 I art     : Explicit concurrent mark sweep GC freed 29134(1502KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.445ms total 70.418ms
,08-19 17:55:11.727  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:55:11.728  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:11.728  5974  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-19 17:55:11.729  5974  6083 I io.jxcore.node.ConnectionHelper: start: OK
08-19 17:55:11.729  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.729  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.729  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.729  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.729  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.729  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:55:11.730  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.730  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-19 17:55:11.730  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:55:11.730  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list,
08-19 17:55:11.730  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:11.730  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
,08-19 17:55:11.730  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
,08-19 17:55:11.730  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:11.730  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:11.730  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:11.731  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:55:11.731  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.731  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.731  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.731  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.731  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
,08-19 17:55:11.732  5974  6083 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-19 17:55:11.732  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.732  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.732  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:55:11.732  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.732  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.732  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.732  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.732  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.732  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.732  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.732  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.732  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:11.732  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.732  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.733  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.733  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.734  5974  6083 D BluetoothLeScanner: could not find callback wrapper,
08-19 17:55:11.734  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.734  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.734  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.735  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-19 17:55:11.735  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.735  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.735  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.736  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.736  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:11.736  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.736  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.736  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.736  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.736  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop,
08-19 17:55:11.736  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.736  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.736  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.736  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.738  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.738  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.748  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.748  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.748  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:11.748  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.749  5974  6083 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-19 17:55:11.749  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.749  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.749  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-19 17:55:11.749  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.749  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.749  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.749  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
,08-19 17:55:11.749  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.749  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.749  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.749  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.750  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-19 17:55:11.750  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.750  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.750  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.750  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:55:11.751  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.751  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.751  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.751  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.752  5974  6083 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted,
08-19 17:55:11.752  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.752  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.752  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:55:11.753  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-19 17:55:11.753  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.753  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.753  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.753  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:11.753  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list,
08-19 17:55:11.753  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.753  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.753  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-19 17:55:11.753  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.753  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.754  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.754  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.754  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.754  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.754  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.754  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
,08-19 17:55:11.755  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-19 17:55:11.756  5974  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-19 17:55:11.756  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-19 17:55:11.756  5974  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-19 17:55:11.756  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-19 17:55:11.756  5974  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-19 17:55:11.756  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.756  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-19 17:55:11.756  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.759  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.759  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.759  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:11.759  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.759  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.759  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.759  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.759  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.759  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.759  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.759  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-19 17:55:11.760  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.760  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.760  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.760  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.760  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-19 17:55:11.760  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.761  5974  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-19 17:55:11.761  5974  6083 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-19 17:55:11.761  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-19 17:55:11.764  5974  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:55:11.764  5974  6083 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer,
,08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-19 17:55:11.764  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-19 17:55:11.765  5974  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-19 17:55:11.765  5974  6083 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-19 17:55:11.765  5974  6083 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-19 17:55:11.765  5974  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:55:11.765  5974  6083 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-19 17:55:11.765  5974  6083 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-19 17:55:11.765  5974  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:55:11.765  5974  6083 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-19 17:55:11.765  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-19 17:55:11.770  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-19 17:55:11.771  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-19 17:55:11.771  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-19 17:55:11.771  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-19 17:55:11.771  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55,
08-19 17:55:11.771  5974  6083 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-19 17:55:11.771  5974  6083 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:55:11.771  5974  6083 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-19 17:55:11.772  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:11.772  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.772  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.774  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.774  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.774  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.775  5974  6190 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 736)
08-19 17:55:11.779  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-19 17:55:11.780  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.780  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.780  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.780  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.780  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.780  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.780  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.780  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.781  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.781  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.781  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.781  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.781  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.781  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.782  5974  6083 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-19 17:55:11.782  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.782  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.782  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.782  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.782  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.782  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.782  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.782  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.782  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.782  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.782  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.782  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.782  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably a,lready removed
08-19 17:55:11.783  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.784  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.784  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.784  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.784  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.784  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.784  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.785  5974  6083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-19 17:55:11.785  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.785  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.785  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.785  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.785  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.785  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.785  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.785  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.785  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.785  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.786  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.786  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.786  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.786  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.786  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.786  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.787  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.787  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.787  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.787  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.787  5974  6083 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-19 17:55:11.787  5974  6083 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-19 17:55:11.787  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:55:11.787  5974  6083 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-19 17:55:11.788  5974  6083 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-19 17:55:11.788  5974  6083 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-19 17:55:11.788  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-19 17:55:11.788  5974  6083 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-19 17:55:11.788  5974  6083 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-19 17:55:11.788  5974  6083 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-19 17:55:11.788  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-19 17:55:11.788  5974  6083 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-19 17:55:11.788  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.788  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.788  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.790  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.790  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.790  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.790  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.790  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.790  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.790  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.790  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.790  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.790  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.790  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.792  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.792  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.794  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.803  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.803  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.803  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.803  5974  6191 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 736
08-19 17:55:11.804  5974  6191 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 736)
08-19 17:55:11.804  5974  6191 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 736)
08-19 17:55:11.805  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.805  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.805  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.805  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.805  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.805  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.805  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.805  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.805  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.805  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.806  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.806  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.806  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.806  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.806  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.806  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.806  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.806  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.808  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.808  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.808  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.808  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.808  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.808  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.808  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.808  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.808  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.808  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.808  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.809  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.809  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.809  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.809  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.809  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.809  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.811  5974  6083 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-19 17:55:11.811  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:11.811  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-19 17:55:11.812  5974  6083 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-19 17:55:11.812  5974  6083 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-19 17:55:11.813  5974  5974 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-19 17:55:11.813  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-19 17:55:11.813  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:55:11.814  1029  1955 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:11.814  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.815  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-19 17:55:11.815  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-19 17:55:11.815  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-19 17:55:11.815  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.815  5974  6083 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-19 17:55:11.815  5974  6200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:11.815  5974  5974 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-19 17:55:11.816  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.816  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.816  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:55:11.816  5974  6083 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:55:11.816  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:55:11.816  3737  3834 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-19 17:55:11.817  5974  6200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-19 17:55:11.817  5974  6200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-19 17:55:11.817  5974  6200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-19 17:55:11.818  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:55:11.819  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:11.819  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:11.819  5974  6083 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:55:11.819  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.820  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.820  5974  6083 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:55:11.820  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.821  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.821  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.821  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.821  5974  5974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:11.821  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.821  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.821  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.821  5974  5974 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-19 17:55:11.821  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.821  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.821  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.821  5974  5974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:11.821  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.821  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.821  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.821  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.821  5974  5974 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:55:11.821  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.822  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.822  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.822  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.822  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.823  5974  6083 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-19 17:55:11.823  5974  6083 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-19 17:55:11.823  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-19 17:55:11.823  5974  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:55:11.823  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.823  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.823  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.823  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.824  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.824  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.824  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.824  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.824  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.824  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.824  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.824  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.824  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.824  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.824  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.824  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.824  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.824  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.825  1029  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:11.826  1029  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:11.827  1029  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:11.827  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.827  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.827  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.827  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.827  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.827  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.827  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.827  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.827  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.827  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.827  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.827  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.827  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.827  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.828  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.828  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.828  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.828  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.829  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:11.829  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:11.829  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:11.829  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:11.829  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.829  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.829  5974  6083 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfff2b not in the list
08-19 17:55:11.829  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.829  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.829  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:11.829  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.829  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.829  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:11.829  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:11.831  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:11.832  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:11.832  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:11.832  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c0ef88 not in the list
08-19 17:55:11.834  5974  6083 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-19 17:55:11.834  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:55:11.835  5974  6083 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-19 17:55:11.835  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:55:11.835  5974  6083 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-19 17:55:11.835  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-19 17:55:11.839  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-19 17:55:11.839  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-19 17:55:11.840  5974  6083 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-19 17:55:11.840  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-19 17:55:11.840  5974  6083 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-19 17:55:11.840  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-19 17:55:11.840  5974  6083 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-19 17:55:11.840  5974  6083 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-19 17:55:11.841  5974  6083 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-19 17:55:11.841  5974  6083 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-19 17:55:11.843  5974  6083 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-19 17:55:11.843  5974  6083 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-19 17:55:11.843  5974  6083 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-19 17:55:11.843  5974  6083 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-19 17:55:11.845  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:11.845  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@effcf59 added. We now have 2 listener(s)
08-19 17:55:11.845  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:11.846  5974  6083 D BluetoothAdapter: enable(): BT is already enabled..!
08-19 17:55:11.847  1029  1911 D WifiServiceImplEx: setWifiEnabled: true pid=5974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-19 17:55:11.848  1029  1911 D WifiService: setWifiEnabled: true pid=5974, uid=10118
08-19 17:55:11.848  1029  1911 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-19 17:55:11.849  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:11.849  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bee971e added. We now have 3 listener(s)
08-19 17:55:11.849  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:11.853  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:11.853  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5d5abff added. We now have 4 listener(s)
08-19 17:55:11.853  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:11.857  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:11.857  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c9c1dcc added. We now have 5 listener(s)
08-19 17:55:11.857  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:11.859  1029  1045 D WifiServiceImplEx: setWifiEnabled: false pid=5974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-19 17:55:11.859  1029  1045 D WifiService: setWifiEnabled: false pid=5974, uid=10118
08-19 17:55:11.859  1029  1045 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-19 17:55:11.878  1029  1534 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-19 17:55:11.878  1029  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:11.879  1029  1883 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@10b89f98 mBinding = false
08-19 17:55:11.879  1029  1534 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-19 17:55:11.880  1029  1534 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-19 17:55:11.880  1029  1534 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-19 17:55:11.881  1029  1533 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:11.881  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:11.881  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 1
08-19 17:55:11.881  1029  1029 D RttService: SCAN_AVAILABLE : 1
08-19 17:55:11.881  1029  1533 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@392e8524
08-19 17:55:11.881  1029  1552 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:11.881  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-19 17:55:11.882  1029  1533 D LGWifiP2pService: P2pDisablingState
08-19 17:55:11.882  1029  1533 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:11.882  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-19 17:55:11.882  1029  1533 D LGWifiP2pService: p2p socket connection lost
08-19 17:55:11.882  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-19 17:55:11.882  1029  1533 D LGWifiP2pService: P2pDisabledState
08-19 17:55:11.883  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-19 17:55:11.883  1937  1937 D WfdsService: WifiP2pState is changed : false
08-19 17:55:11.883  1029  1553 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:11.883  1937  2308 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-19 17:55:11.883  1937  2308 D WfdsService: Set the WFDS Monitor: false
08-19 17:55:11.884  1937  2308 D WfdsMonitor: WFDS Monitor is stopped
08-19 17:55:11.884  1937  2308 D WfdsService: STATE : WfdsDisabledState - enter
08-19 17:55:11.885  1029  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-19 17:55:11.885  1937  2309 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-19 17:55:11.885  1937  2790 D CtrlSupplicant: Received on exit socket, terminate
08-19 17:55:11.885  1937  2790 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-19 17:55:11.885  1937  2790 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-19 17:55:11.885  1937  2790 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-19 17:55:11.885   318   889 D CommandListener: Clearing all IP addresses on wlan0
08-19 17:55:11.886  1937  2308 W WfdsService: DefaultState - msg [9445378] is not handled
08-19 17:55:11.888  1029  1029 D WifiHS20: hidePasspointNotification off =false
08-19 17:55:11.888  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-19 17:55:11.888  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-19 17:55:11.890  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:11.890  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:11.890  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-19 17:55:11.891  3650  3650 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-19 17:55:11.891  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-19 17:55:11.898  1029  1029 D WifiHS20: hidePasspointNotification off =false
08-19 17:55:11.899  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:11.899  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:11.899  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-19 17:55:11.899  1029  1534 D WifiNative-p2p0: doBoolean: TERMINATE
08-19 17:55:11.900  1029  1534 D WifiNative-p2p0: TERMINATE: returned true
08-19 17:55:11.900  1029  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-19 17:55:11.900  1029  1534 E WifiStateMachine: useWiFiOffloading() : false
08-19 17:55:11.900  1029  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-19 17:55:11.904  1029  1091 D BluetoothManagerService: Message: 2
08-19 17:55:11.906  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-19 17:55:11.906  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-19 17:55:11.906  1029  1029 D Ulp_jni : JNI:system_update. Event-4
,08-19 17:55:11.906  1029  1091 D BluetoothManagerService: Sending off request.
08-19 17:55:11.908  3737  3756 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-19 17:55:11.909  3737  3825 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-19 17:55:11.909  3737  3825 D BluetoothAdapterProperties: Setting state to 13
08-19 17:55:11.909  3737  3825 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-19 17:55:11.909  3737  3825 D BluetoothAdapterProperties: onBluetoothDisable()
08-19 17:55:11.909  3737  3825 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-19 17:55:11.912  1029  1091 D BluetoothManagerService: Message: 60
08-19 17:55:11.912  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-19 17:55:11.912  1029  1091 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-19 17:55:11.913  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-19 17:55:11.913  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-19 17:55:11.914  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-19 17:55:11.936  5974  6190 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-19 17:55:11.938  5974  6190 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 736)
08-19 17:55:11.944  1029  1996 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6205 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-19 17:55:11.947  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:11.947  3737  3828 D BluetoothAdapterProperties: Scan Mode:20
08-19 17:55:11.947  3737  3825 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-19 17:55:11.948  3737  4185 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:55:11.948  3737  3825 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-19 17:55:11.948  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-19 17:55:11.948  3737  4201 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-19 17:55:11.949  3737  4099 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-19 17:55:11.949  3737  4099 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:55:11.949  3737  4099 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-19 17:55:11.949  3737  4099 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-19 17:55:11.949  3737  4099 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-19 17:55:11.949  3737  4099 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-19 17:55:11.949  3737  4099 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-19 17:55:11.949  3737  4099 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-19 17:55:11.950  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-19 17:55:11.950  3737  4106 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:55:11.950  3737  3896 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-19 17:55:11.951  3737  4184 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:55:11.952  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-19 17:55:11.952  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-19 17:55:11.952  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-19 17:55:11.952  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-19 17:55:11.952  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-19 17:55:11.952  3737  3896 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:11.952  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-19 17:55:11.952  3737  3896 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:11.952  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-19 17:55:11.952  3737  3896 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:11.952  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-19 17:55:11.952  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-19 17:55:11.952  3737  3896 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-19 17:55:11.954  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-19 17:55:11.954  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:11.954  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:11.954  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:11.954  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:11.954  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:11.954  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:11.954  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:11.954  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:11.954  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:11.955  1937  1937 D LGBluetooth,APIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:11.956  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:11.956  5974  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:11.958  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:11.958  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:11.958  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:11.958  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:11.958  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:11.958  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:11.958  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:11.958  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:11.958  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:11.958  3737  3737 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:11.958  3737  3737 D BluetoothMapService: STATE_TURNING_OFF
08-19 17:55:11.958  3737  3737 V BluetoothMapService: Handler(): got msg=4
08-19 17:55:11.959  3737  3737 D BluetoothMapService: MAP Service closeService in
08-19 17:55:11.959  3737  3737 D BluetoothMapMasInstance: MAP Service shutdown
08-19 17:55:11.959  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:11.959  3737  3737 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-19 17:55:11.959  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:11.959  3737  3737 V BluetoothMapService: MAP Service closeService out
08-19 17:55:11.959  5974  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:11.959  3737  3737 V BtOppService: Receiver DISABLED_ACTION 
08-19 17:55:11.960  3737  3737 I BtOppRfcommListener: stopping Accept Thread
08-19 17:55:11.960  3737  3737 V BtOppRfcommListener: close mBtServerSocket
08-19 17:55:11.960  3737  3737 V BtOppRfcommListener: waiting for thread to terminate
08-19 17:55:11.960  3737  4184 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-19 17:55:11.960  3737  3737 V BtOppRfcommListener: done waiting for thread to terminate
,08-19 17:55:11.964  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:11.965  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:11.966  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:11.967  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:11.967  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:11.974  2772  2772 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-19 17:55:11.975  2772  2772 I wpa_supplicant: monitor socket send errors count : 1
,08-19 17:55:11.975  2772  2772 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1937-2\x00 that cannot receive messages
08-19 17:55:11.976  2772  2772 W wpa_supplicant: USIM:  scard_deinit function
08-19 17:55:11.976  1029  2788 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-19 17:55:11.976  1029  2788 D WifiMonitor: Dropping event because (p2p0) is stopped
08-19 17:55:11.976  1029  2788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
08-19 17:55:11.976  1029  2788 E WifiMonitor: WifiMonitor:wlan0 cnt=68 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
,08-19 17:55:11.977  1029  1534 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 68 0 rt=114041  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
08-19 17:55:11.978  1029  1534 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 68 0 rt=114042  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
08-19 17:55:11.978  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-19 17:55:11.990  1029  1087 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6223 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-19 17:55:11.991  3737  3737 V BtOppService: onDestroy
08-19 17:55:11.992  3737  3737 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-19 17:55:12.031  6223  6223 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-19 17:55:12.031  6223  6223 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-19 17:55:12.032  6223  6223 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-19 17:55:12.032  6223  6223 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-19 17:55:12.033  6223  6223 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-19 17:55:12.033  6223  6223 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-19 17:55:12.041  6205  6205 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-19 17:55:12.043  6205  6205 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-19 17:55:12.043  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-19 17:55:12.046  1029  2022 I ActivityManager: Killing 4808:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-19 17:55:12.073  2772  2772 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-19 17:55:12.074  1029  2788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-19 17:55:12.074  1029  2788 E WifiMonitor: WifiMonitor:wlan0 cnt=69 dispatchEvent: CTRL-EVENT-TERMINATING 
08-19 17:55:12.074  1029  2788 D WifiMonitor: Disconnecting from the supplicant, no more events
08-19 17:55:12.074  1029  1534 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 69 0
,08-19 17:55:12.084  1029  1782 W libprocessgroup: failed to open /acct/uid_10014/pid_4808/cgroup.procs: No such file or directory
,08-19 17:55:12.125  6223  6223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-19 17:55:12.132  3737  3737 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-19 17:55:12.133  3737  3737 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:12.133  3737  3737 V BluetoothPbapReceiver: ***********state = 13
08-19 17:55:12.136  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-19 17:55:12.137  3737  3737 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-19 17:55:12.140  3737  3737 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:12.140  3737  3737 V BluetoothPbapService: state: 13
08-19 17:55:12.140  3737  3737 V BluetoothPbapService: Pbap Service closeService in
08-19 17:55:12.140  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-19 17:55:12.143  3737  3737 V BluetoothPbapService: successfully stopped pbap service
08-19 17:55:12.143  3737  3737 V BluetoothPbapService: Pbap Service closeService out
08-19 17:55:12.145  3737  3737 V BluetoothPbapService: Pbap Service onDestroy
08-19 17:55:12.146  3737  3737 V BluetoothPbapService: Pbap Service closeService in
08-19 17:55:12.146  3737  3737 V BluetoothPbapService: Pbap Service closeService out
08-19 17:55:12.146  3737  3737 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-19 17:55:12.211  6223  6223 D LgDataFeature: LgDataFeature() Constructor: none
08-19 17:55:12.211  6223  6223 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-19 17:55:12.217  1029  1571 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6245 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-19 17:55:12.219  1029  1534 D WifiOffDelayIfNotUsed: stopMonitoring
08-19 17:55:12.219  1029  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-19 17:55:12.219  1029  1534 E WifiStateMachine: useWiFiOffloading() : false
08-19 17:55:12.219  1029  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-19 17:55:12.219  1937  1937 D WfdsService: Supplicant Connection state is changed : false
08-19 17:55:12.220  1937  2308 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-19 17:55:12.220  1937  2308 D WfdsService: Set the WFDS Monitor: false
08-19 17:55:12.220  1937  2308 D WfdsMonitor: WFDS Monitor is stopped
08-19 17:55:12.222  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-19 17:55:12.223  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-19 17:55:12.223  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-19 17:55:12.224  1029  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-19 17:55:12.224  1029  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,08-19 17:55:12.228  2465  2465 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-19 17:55:12.228  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:12.230  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:12.236  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-19 17:55:12.249  1029  1091 D BluetoothManagerService: Message: 20
08-19 17:55:12.249  1029  1091 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@328eff62:true
08-19 17:55:12.260  1029  1091 D BluetoothManagerService: Message: 30
,08-19 17:55:12.270  1029  1091 D BluetoothManagerService: Message: 30
08-19 17:55:12.272  6223  6223 D LocalBluetoothProfileManager: Adding local MAP profile
08-19 17:55:12.274  6223  6223 D BluetoothMap: Create BluetoothMap proxy object
,08-19 17:55:12.274  1029  1091 D BluetoothManagerService: Message: 30
08-19 17:55:12.282  1029  1091 D BluetoothManagerService: Message: 30
08-19 17:55:12.285  6223  6223 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-19 17:55:12.285  6223  6223 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-19 17:55:12.301  6223  6223 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-19 17:55:12.309  6223  6223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-19 17:55:12.322  5974  5974 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-19 17:55:12.327  6223  6223 D DockEventReceiver: finishStartingService: stopping service
08-19 17:55:12.346  6223  6223 D BluetoothInputDevice: Proxy object connected
08-19 17:55:12.347  6223  6223 D HidProfile: Bluetooth service connected
,08-19 17:55:12.349  6223  6223 D BluetoothPan: BluetoothPAN Proxy object connected
08-19 17:55:12.350  6223  6223 D PanProfile: Bluetooth service connected
,08-19 17:55:12.351  6223  6223 D BluetoothMap: Proxy object connected
08-19 17:55:12.352  6223  6223 D MapProfile: Bluetooth service connected
08-19 17:55:12.352  6223  6223 D BluetoothMap: getConnectedDevices()
08-19 17:55:12.354  6223  6223 D BluetoothMap: Bluetooth is Not enabled
08-19 17:55:12.354  6223  6223 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-19 17:55:12.419  1029  1782 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6269 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-19 17:55:12.422  1029  1782 I ActivityManager: Killing 5666:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-19 17:55:12.464  1029  1955 W libprocessgroup: failed to open /acct/uid_10004/pid_5666/cgroup.procs: No such file or directory
,08-19 17:55:12.476  6245  6245 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-19 17:55:12.478  6245  6245 W LG Account v2.2: No ProfileInfo entries
08-19 17:55:12.478  6245  6245 I LG Account v2.2: isEnabled: false
08-19 17:55:12.479  6245  6245 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-19 17:55:12.479  6245  6245 I Feature : [Lifetracker]Country: EU
08-19 17:55:12.479  6245  6245 I Feature : [Lifetracker]Operator: OPEN
08-19 17:55:12.479  6245  6245 I Feature : [Lifetracker]Ranking support: false
08-19 17:55:12.479  6245  6245 I Feature : [Lifetracker]Comfort support: false
08-19 17:55:12.480  6245  6245 I Feature : [Lifetracker]Accessory: true
08-19 17:55:12.480  6245  6245 I Feature : [Lifetracker]Health device: true
08-19 17:55:12.480  6245  6245 I Feature : [Lifetracker]Extra Pedometer: false
08-19 17:55:12.480  6245  6245 I Feature : [Lifetracker]Blood glucose device: false
,08-19 17:55:12.480  6245  6245 I Feature : [Lifetracker]Device Number: 3
08-19 17:55:12.491  6223  6223 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-19 17:55:12.496  6223  6223 D BluetoothPermissionRequest: onReceive
,08-19 17:55:12.499  6223  6223 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-19 17:55:12.506  6269  6269 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-19 17:55:12.508  6223  6223 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-19 17:55:12.511  1029  1571 I ActivityManager: Killing 5796:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-19 17:55:12.558  3737  3737 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-19 17:55:12.558  1029  1645 W libprocessgroup: failed to open /acct/uid_10008/pid_5796/cgroup.procs: No such file or directory
08-19 17:55:12.558  3737  3737 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-19 17:55:12.559  3737  3737 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-19 17:55:12.566  6269  6269 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-19 17:55:12.568  3737  3737 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:12.568  3737  3737 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-19 17:55:12.573  3737  3737 V BluetoothFtpService: Ftp Service onStartCommand
08-19 17:55:12.573  3737  3737 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:12.574  3737  3737 V BluetoothFtpService: Ftp Service closeService
,08-19 17:55:12.574  3737  3737 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-19 17:55:12.576  3737  3737 V BluetoothFtpService: successfully stopped ftp service
08-19 17:55:12.576  3737  3737 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-19 17:55:12.576  3737  3737 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-19 17:55:12.576  3737  3737 V BluetoothSapReceiver: SapReceiver onReceive 
08-19 17:55:12.576  3737  3737 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:12.577  3737  3737 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-19 17:55:12.577  3737  3737 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-19 17:55:12.578  3737  3737 V BluetoothFtpService: Ftp Service onDestroy
08-19 17:55:12.578  3737  3737 V BluetoothFtpService: Ftp Service closeService
08-19 17:55:12.606  6269  6269 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-19 17:55:12.606  6269  6269 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-19 17:55:12.606  6269  6269 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-19 17:55:12.607  6269  6269 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-19 17:55:12.607  6269  6269 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-19 17:55:12.609  6269  6269 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-19 17:55:12.615  6269  6269 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-19 17:55:12.636  1029  1883 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6288 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-19 17:55:12.639  3737  3737 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:12.639  3737  3737 V BluetoothSapService: state: 13
08-19 17:55:12.639  3737  3737 V BluetoothSapService: Stopping SAP server process
08-19 17:55:12.640  3737  3737 V BluetoothSapService: Sap Service closeSapService in
08-19 17:55:12.640  3737  3737 V BluetoothSapService: Close listen Socket : 
08-19 17:55:12.641  3737  3737 V BluetoothSapService: Close rfcomm Socket : 
08-19 17:55:12.641  3737  3737 V BluetoothSapService: Close sapd  Socket : 
08-19 17:55:12.642  3737  3737 V BluetoothSapService: Sap Service closeSapService out
08-19 17:55:12.642  3737  3737 V BluetoothSapService: Sap Service onDestroy
08-19 17:55:12.642  3737  3737 V BluetoothSapService: Sap Service closeSapService in
08-19 17:55:12.642  3737  3737 V BluetoothSapService: Close listen Socket : 
08-19 17:55:12.642  3737  3737 V BluetoothSapService: Close rfcomm Socket : 
08-19 17:55:12.642  3737  3737 V BluetoothSapService: Close sapd  Socket : 
08-19 17:55:12.643  3737  3737 V BluetoothSapService: Sap Service closeSapService out
,08-19 17:55:12.648  6269  6269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-19 17:55:12.651  6269  6269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-19 17:55:12.663  6269  6269 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-19 17:55:12.665  6269  6269 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-19 17:55:12.668  3650  3650 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-19 17:55:12.670  6269  6269 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-19 17:55:12.676  6205  6205 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-19 17:55:12.676  6205  6205 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-19 17:55:12.676  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-19 17:55:12.682  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-19 17:55:12.693  2145  2145 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19992
,08-19 17:55:12.702  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-19 17:55:12.715  6269  6269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-19 17:55:12.715  6269  6269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-19 17:55:12.717  6269  6269 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-19 17:55:12.737  6288  6288 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-19 17:55:12.797  1029  1911 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6308 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-19 17:55:12.800  1029  1911 I ActivityManager: Killing 5827:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-19 17:55:12.858  1029  1645 W libprocessgroup: failed to open /acct/uid_10011/pid_5827/cgroup.procs: No such file or directory
,08-19 17:55:12.908  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-19 17:55:12.912  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:12.919  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-19 17:55:12.948  6308  6327 W FormManager: Network not available. Please check & try again.
,08-19 17:55:12.955  3737  3828 D bt_hci_bdroid: cleanup
08-19 17:55:12.955  3737  3896 W bt-btif : ag scb idx 1 not allocated
08-19 17:55:12.955  3737  3896 E bt-btif : BTA AG is already disabled, ignoring ...
08-19 17:55:12.955  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-19 17:55:12.955  3737  3896 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:12.955  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-19 17:55:12.955  3737  3896 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:12.955  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-19 17:55:12.955  3737  3896 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-19 17:55:12.956  3737  4085 I bt_userial_mct: exiting userial_read_thread
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:12.956  3737  4085 D bt_userial_mct: Leaving userial_evt_read_thread()
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-19 17:55:12.956  3737  3896 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:12.956  3737  3896 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-19 17:55:12.956  3737  3898 I bt_lpm  : LPM is already off!!!
08-19 17:55:12.956  3737  3828 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-19 17:55:12.957  3737  3898 I bt_vendor: hw_epilog_process
08-19 17:55:12.957  3737  3828 D bt_hci_bdroid: cleanup Finalizing cleanup
08-19 17:55:12.958  3737  3828 D bt_userial_mct: userial_close
08-19 17:55:12.958  3737  3828 E bt_userial_mct: pthread_join() FAILED result:3
08-19 17:55:12.958  3737  3828 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-19 17:55:12.970  4212  4212 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-19 17:55:12.971  4212  4212 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-19 17:55:12.976  4212  4212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-19 17:55:12.980  4212  4212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-19 17:55:12.992  6308  6328 V FormManager: Network unavailable.
,08-19 17:55:12.995  6205  6205 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-19 17:55:12.995  6205  6205 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-19 17:55:12.996  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-19 17:55:13.003  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:13.008  4212  6331 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-19 17:55:13.010  6308  6328 V FormManager: Network unavailable.
08-19 17:55:13.011  4212  6332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-19 17:55:13.013  4212  6332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-19 17:55:13.015  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-19 17:55:13.038  6269  6269 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-19 17:55:13.040  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-19 17:55:13.040  6269  6269 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-19 17:55:13.041  6308  6334 W FormManager: Network not available. Please check & try again.
08-19 17:55:13.043  6308  6335 V FormManager: Network unavailable.
08-19 17:55:13.045  6308  6335 V FormManager: Network unavailable.
08-19 17:55:13.051  1029  1045 I ActivityManager: Killing 5845:com.android.contacts/u0a19 (adj 15): empty #17
,08-19 17:55:13.083  3737  3828 D bt_hci_bdroid: set_power 0
,08-19 17:55:13.083  3737  3828 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-19 17:55:13.083  3737  3828 I bt_vendor: bluetooth satus is on
08-19 17:55:13.083  3737  3828 I bt_vendor: bt-vendor : resetting BT status
08-19 17:55:13.083  3737  3828 I bt_vendor: Starting hciattach daemon
08-19 17:55:13.083  3737  3828 I bt_vendor: try to set false
08-19 17:55:13.084  3737  3828 I bt_vendor: Starting hciattach daemon
08-19 17:55:13.084  3737  3828 I bt_vendor: try to set false
08-19 17:55:13.085  3737  3828 I bt_vendor: cleanup
08-19 17:55:13.086  3737  3896 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-19 17:55:13.100  6269  6269 D LgDataFeature: LgDataFeature() Constructor: none
08-19 17:55:13.101  6269  6269 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-19 17:55:13.115  1029  1883 W libprocessgroup: failed to open /acct/uid_10019/pid_5845/cgroup.procs: No such file or directory
08-19 17:55:13.116  6269  6269 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-19 17:55:13.119  3737  3828 I GKI_LINUX: GKI_exit_task 0 done
08-19 17:55:13.119  3737  3828 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-19 17:55:13.120  6269  6269 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-19 17:55:13.120  3737  3825 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-19 17:55:13.121  6269  6269 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-19 17:55:13.121  6269  6269 V SoundPool: doLoad: loading sample sampleID=1
08-19 17:55:13.125  6269  6338 V SoundPool: Start decode
08-19 17:55:13.125  3737  3737 D HeadsetService: Received stop request...Stopping profile...
08-19 17:55:13.125  6269  6338 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-19 17:55:13.127  6269  6269 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-19 17:55:13.127   322   322 V MediaPlayerService: decode(22, 10857164, 17813)
08-19 17:55:13.128   322   322 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,08-19 17:55:13.128   322   322 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-19 17:55:13.128   322   322 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
,08-19 17:55:13.128   322   322 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-19 17:55:13.128   322   322 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-19 17:55:13.128   322   322 V MediaPlayerService: player type = 3
08-19 17:55:13.128   322   322 V AwesomePlayer: AwesomePlayer create()
08-19 17:55:13.129  3737  3737 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-19 17:55:13.129  3737  3737 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-19 17:55:13.129  3737  3737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@187aa217
08-19 17:55:13.129  3737  3836 D HeadsetStateMachine: Exit Disconnected: -1
08-19 17:55:13.133   322   322 V AwesomePlayer: reset_l() 
08-19 17:55:13.133   322   322 V AwesomePlayer: cancelPlayerEvents
08-19 17:55:13.133   322   322 V AwesomePlayer: setAudioSink() 
08-19 17:55:13.134   322   322 V AwesomePlayer: reset_l() 
08-19 17:55:13.134   322   322 V AudioCache: notify(0xb0409680, 8, 0, 0)
,08-19 17:55:13.134  1029  1029 D BluetoothHeadset: Proxy object disconnected
08-19 17:55:13.134   322   322 V AudioCache: ignored
08-19 17:55:13.134   322   322 V AwesomePlayer: cancelPlayerEvents
08-19 17:55:13.134  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-19 17:55:13.134   322   322 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-19 17:55:13.134   322   322 V AwesomePlayer: setDataSource_l dataSource
08-19 17:55:13.134   322   322 V LGParserOSAL: SniffLGParser start
08-19 17:55:13.134   322   322 V LGParserOSAL: MainType:5, SubType=0
08-19 17:55:13.134   322   322 V LGParserOSAL: #### check Mime : application/ogg
08-19 17:55:13.134   322   322 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-19 17:55:13.134   322   322 E MediaExtractor: Use LGExtractor :application/ogg 
08-19 17:55:13.136  3737  3737 D A2dpService: Received stop request...Stopping profile...
08-19 17:55:13.136  3737  3875 D A2dpStateMachine: Exit Disconnected: -1
08-19 17:55:13.137  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-19 17:55:13.138  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-19 17:55:13.138  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-19 17:55:13.139  3737  3825 D BluetoothAdapterState: Stopping profile services that were post enabled
08-19 17:55:13.140  3737  3737 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-19 17:55:13.145  6131  6131 D UEI.SmartControl: QS Service created
08-19 17:55:13.146  6269  6269 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-19 17:55:13.149  3737  3737 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-19 17:55:13.149  3737  3737 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-19 17:55:13.149  3737  3737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@187aa217
08-19 17:55:13.152  3737  3737 D HidService: Received stop request...Stopping profile...
08-19 17:55:13.152  3737  3737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@187aa217
08-19 17:55:13.152  1029  1029 D BluetoothA2dp: Proxy object disconnected
08-19 17:55:13.152  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-19 17:55:13.155  6223  6223 D BluetoothInputDevice: Proxy object disconnected
08-19 17:55:13.155  3737  3737 D HealthService: Received stop request...Stopping profile...
08-19 17:55:13.155  3737  3737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@187aa217
08-19 17:55:13.156  6223  6223 D HidProfile: Bluetooth service disconnected
08-19 17:55:13.157  3737  3737 D PanService: Received stop request...Stopping profile...
08-19 17:55:13.157  6269  6269 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-19 17:55:13.158  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-19 17:55:13.158  3737  3737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@187aa217
08-19 17:55:13.159  6223  6223 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-19 17:55:13.160  6223  6223 D PanProfile: Bluetooth service disconnected
08-19 17:55:13.160  3737  3737 D HeadsetStateMachine: Unbinding service...
08-19 17:55:13.162  3737  3737 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-19 17:55:13.162  3737  3737 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-19 17:55:13.162  3737  3737 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-19 17:55:13.162  3737  3737 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-19 17:55:13.162  3737  3737 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-19 17:55:13.162  3737  3737 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-19 17:55:13.162  3737  3737 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-19 17:55:13.162  3737  3737 D BtGatt.DebugUtils: handleDebugAction() action=null
08-19 17:55:13.164  3737  3737 D BtGatt.GattService: Received stop request...Stopping profile...
08-19 17:55:13.164  3737  3737 D BtGatt.GattService: stop()
08-19 17:55:13.164  3737  3737 D BtGatt.AdvertiseManager: advertise clients cleared
08-19 17:55:13.165  3737  3737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@187aa217
,08-19 17:55:13.166  3737  3737 D BluetoothMapService: Received stop request...Stopping profile...
08-19 17:55:13.166  3737  3737 D BluetoothMapService: stop()
08-19 17:55:13.167  3737  3737 D BluetoothMapEmailAppObserver: deinitObservers()
08-19 17:55:13.167  3737  3737 D BluetoothMapEmailAppObserver: removeReceiver()
08-19 17:55:13.168  3737  3737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@187aa217
08-19 17:55:13.170  3737  3737 I BluetoothA2dpServiceJni: cleanupNative
08-19 17:55:13.170  3737  3876 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-19 17:55:13.171  3737  3737 I GKI_LINUX: GKI_exit_task 2 done
08-19 17:55:13.171  3737  3737 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-19 17:55:13.171  3737  3737 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-19 17:55:13.171  3737  3737 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-19 17:55:13.172  6223  6223 D BluetoothMap: Proxy object disconnected
,08-19 17:55:13.172  3737  3737 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-19 17:55:13.172  6223  6223 D MapProfile: Bluetooth service disconnected
08-19 17:55:13.172  3737  3737 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-19 17:55:13.172  3737  3737 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-19 17:55:13.172  3737  3737 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-19 17:55:13.172  3737  3737 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-19 17:55:13.174  3737  3737 V BluetoothMapService: Handler(): got msg=4
08-19 17:55:13.175  3737  3737 D BluetoothMapService: MAP Service closeService in
08-19 17:55:13.175  3737  3737 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-19 17:55:13.175  3737  3737 V BluetoothMapService: MAP Service closeService out
08-19 17:55:13.175  6269  6269 V LGMDMManager: Create singleton instance
08-19 17:55:13.176  3737  3825 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-19 17:55:13.176  3737  3825 D BluetoothAdapterProperties: Setting state to 10
08-19 17:55:13.176  3737  3825 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-19 17:55:13.176  1029  1091 D BluetoothManagerService: Message: 60
08-19 17:55:13.176  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-19 17:55:13.176  1029  1091 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-19 17:55:13.176  3737  3825 I BluetoothAdapterState: Entering OffState
08-19 17:55:13.176  3737  3737 D BluetoothMapService: cleanup()
08-19 17:55:13.176  3737  3737 D BluetoothMapService: MAP Service closeService in
08-19 17:55:13.176  3737  3737 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-19 17:55:13.177  3737  3737 V BluetoothMapService: MAP Service closeService out
08-19 17:55:13.177  6223  6238 D BluetoothMap: onBluetoothStateChange: up=false
08-19 17:55:13.178  1849  4306 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:55:13.179  6223  6239 D BluetoothPan: onBluetoothStateChange on: false
08-19 17:55:13.179  1029  1091 D BluetoothA2dp: onBluetoothStateChange: up=false
08-19 17:55:13.179  1029  1091 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:55:13.179  1849  4303 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:55:13.180  6223  6238 D BluetoothPbap: onBluetoothStateChange: up=false
08-19 17:55:13.181  1849  4302 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:55:13.181  6223  6239 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-19 17:55:13.182  1029  1091 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-19 17:55:13.182  1029  1091 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-19 17:55:13.184  1029  1091 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-19 17:55:13.185  1029  1091 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-19 17:55:13.185  1029  1091 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@10b89f98 mBinding = false
,08-19 17:55:13.185  1029  1091 D BluetoothManagerService: Sending unbind request.
08-19 17:55:13.188  1029  1091 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-19 17:55:13.193  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:13.193  1937  2116 D LGBluetoothAPIService: Message: 2
08-19 17:55:13.194  1937  2116 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1d9192a8 mBinding = false
08-19 17:55:13.194  1937  2116 D LGBluetoothAPIService: Sending unbind request.
08-19 17:55:13.195   322   322 V LGParserOSAL: supported mime: application/ogg
08-19 17:55:13.195   322   322 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-19 17:55:13.195   322   322 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-19 17:55:13.195   322   322 V AwesomePlayer: mBitrate = -1 bits/sec
08-19 17:55:13.195   322   322 V AwesomePlayer: AudioTrack Setting
08-19 17:55:13.195   322   322 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-19 17:55:13.195   322   322 V AwesomePlayer: setAudioSource() 
08-19 17:55:13.195   322   322 V MediaPlayerService: prepare
08-19 17:55:13.195   322   322 V AwesomePlayer: prepareAsync_l() 
08-19 17:55:13.195   322   322 V MediaPlayerService: wait for prepare
08-19 17:55:13.195   322  6339 V AwesomePlayer: onPrepareAsyncEvent() 
08-19 17:55:13.195   322  6339 V AwesomePlayer: initAudioDecoder() 
08-19 17:55:13.195   322  6339 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-19 17:55:13.195   322  6339 V AudioSystem: isOffloadSupported()
08-19 17:55:13.195  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-19 17:55:13.195   322  6339 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-19 17:55:13.195   322  6339 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-19 17:55:13.195   322  6339 I AudioFlinger: isAudioPlaybackHookOn() false
08-19 17:55:13.195   322  6339 V AwesomePlayer: getUseOffload() = 0 
08-19 17:55:13.196   322  6339 V OMXCodec: OMXCodec::Create
08-19 17:55:13.196   322  6339 V OMXCodec: findMatchingCodecs()
08-19 17:55:13.196   322  6339 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-19 17:55:13.196   322  6339 V OMXCodec: matchingCodecs.size()=1
08-19 17:55:13.196   322  6339 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-19 17:55:13.198   322  6339 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-19 17:55:13.198   322  6339 V LGCodecAdapter: LG Codec Adapter start
08-19 17:55:13.198   322  6339 V OMXCodec: OMXCodec Createtor
08-19 17:55:13.198   322  6339 V OMXCodec: setComponentRole
08-19 17:55:13.198   322  6339 V OMXCodec: configureCodec protected=0
08-19 17:55:13.198   322  6339 V LGCodecAdapter: called getLGCodecSpecificData
08-19 17:55:13.198   322  6339 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-19 17:55:13.198  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:13.198   322  6339 V LGCodecOSAL: Called LGconfigureCodecMETA
08-19 17:55:13.198   322  6339 V LGCodecOSAL: Called LGconfigureCodecMSG
08-19 17:55:13.198   322  6339 V LGCodecOSAL: Not support LGCodec
08-19 17:55:13.198   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-19 17:55:13.198   322  6339 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-19 17:55:13.198   322  6339 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-19 17:55:13.198   322  6339 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-19 17:55:13.198   322  6339 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-19 17:55:13.198   322  6339 V AudioSystem: isOffloadSupported()
08-19 17:55:13.198   322  6339 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-19 17:55:13.198   322  6339 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-19 17:55:13.198   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-19 17:55:13.198   322  6339 V OMXCodec: init()
08-19 17:55:13.198   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-19 17:55:13.198   322  6339 V OMXCodec: allocateBuffers
08-19 17:55:13.198   322  6339 V OMXCodec: allocateBuffersOnPort portIndex=0
08-19 17:55:13.198   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-19 17:55:13.199  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:13.199   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
08-19 17:55:13.199  3737  3828 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-19 17:55:13.199   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on input port
08-19 17:55:13.199   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on input port
08-19 17:55:13.199   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on input port
08-19 17:55:13.199   322  6339 V OMXCodec: allocateBuffersOnPort portIndex=1
08-19 17:55:13.199   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-19 17:55:13.199   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-19 17:55:13.199   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c04c0 on output port
08-19 17:55:13.199   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0560 on output port
08-19 17:55:13.199   322  6339 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0650 on output port
08-19 17:55:13.199   322  6339 V OMXCodec: init() mAsyncCompletion wait!!! 
08-19 17:55:13.199  3737  3737 I GKI_LINUX: GKI_exit_task 1 done
08-19 17:55:13.199  3737  3737 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-19 17:55:13.199  3737  3737 I BluetoothServiceJni: cleanupNative: return, from cleanup
08-19 17:55:13.200  3737  3737 I art     : --- WEIRD: removing null entry 246
08-19 17:55:13.200  3737  3737 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-19 17:55:13.200  3737  3737 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-19 17:55:13.200   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-19 17:55:13.200   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-19 17:55:13.200   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-19 17:55:13.200   322  6339 V OMXCodec: init() mAsyncCompletion wait!!! 
08-19 17:55:13.200   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-19 17:55:13.200   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-19 17:55:13.200   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-19 17:55:13.200   322  6339 V OMXCodec: init() mAsyncCompletion wait free! 
08-19 17:55:13.200   322  6339 V AwesomePlayer: finishAsyncPrepare_l() 
08-19 17:55:13.200   322  6339 V AudioCache: notify(0xb0409680, 5, 0, 0)
08-19 17:55:13.200   322  6339 V AudioCache: ignored
08-19 17:55:13.200   322  6339 V AudioCache: notify(0xb0409680, 1, 0, 0)
08-19 17:55:13.200   322  6339 V AudioCache: prepared
08-19 17:55:13.201   322   322 V AudioCache: wait - success
08-19 17:55:13.201   322   322 V MediaPlayerService: start
08-19 17:55:13.201   322   322 V AwesomePlayer: play_l() 
08-19 17:55:13.201   322   322 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-19 17:55:13.201   322   322 V AwesomePlayer: createAudioPlayer_l
08-19 17:55:13.201   322   322 V AwesomePlayer: seekAudioIfNecessary_l() 
08-19 17:55:13.201   322   322 V AwesomePlayer: startAudioPlayer_l() 
08-19 17:55:13.201   322   322 D AudioPlayer: start of Playback, useOffload 0
08-19 17:55:13.201   322   322 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-19 17:55:13.201   322   322 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-19 17:55:13.201  6223  6223 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-19 17:55:13.202  6223  6223 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-19 17:55:13.202  6223  6223 D LGBluetoothEventManager: [BTUI] clear device connection state
08-19 17:55:13.204   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-19 17:55:13.204   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-19 17:55:13.204   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-19 17:55:13.204   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-19 17:55:13.204   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-19 17:55:13.204   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044803776
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044803936
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-19 17:55:13.205  3737  3737 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044804176
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0,
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-19 17:55:13.205  6223  6223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-19 17:55:13.205   322  6341 V OMXCodec: allocateBuffersOnPort portIndex=1
08-19 17:55:13.205   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-19 17:55:13.206   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0560 on output port
08-19 17:55:13.206   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c04c0 on output port
08-19 17:55:13.206   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-19 17:55:13.206   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0880 on output port
08-19 17:55:13.206   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-19 17:55:13.206   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-19 17:55:13.207   322   322 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-19 17:55:13.207   322   322 V AudioCache: notify(0xb0409680, 6, 0, 0)
08-19 17:55:13.207   322   322 V AudioCache: ignored
08-19 17:55:13.208   322   322 V MediaPlayerService: wait for playback complete
08-19 17:55:13.210  6131  6131 I UEI.SmartControl: Service initServices...
08-19 17:55:13.210  6131  6131 D UEI.SmartControl: QS start get config
08-19 17:55:13.210  1599  1599 D BluetoothAdapter: 188806031: getState() :  mService = null. Returning STATE_OFF
08-19 17:55:13.210  1599  1599 D BluetoothAdapter: 188806031: getState() :  mService = null. Returning STATE_OFF
08-19 17:55:13.210  3737  3737 I art     : System.exit called, status: 0
08-19 17:55:13.211  3737  3737 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-19 17:55:13.211   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.211   322  6342 V AudioCache: memcpy(0xaf104000, 0xb0406000, 4096)
08-19 17:55:13.212   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.212   322  6342 V AudioCache: memcpy(0xaf105000, 0xb0406000, 4096)
08-19 17:55:13.213   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.213   322  6342 V AudioCache: memcpy(0xaf106000, 0xb0406000, 4096)
08-19 17:55:13.214   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.214   322  6342 V AudioCache: memcpy(0xaf107000, 0xb0406000, 4096)
08-19 17:55:13.215   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.215   322  6342 V AudioCache: memcpy(0xaf108000, 0xb0406000, 4096)
08-19 17:55:13.216   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.216   322  6342 V AudioCache: memcpy(0xaf109000, 0xb0406000, 4096)
08-19 17:55:13.217   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.217   322  6342 V AudioCache: memcpy(0xaf10a000, 0xb0406000, 4096)
08-19 17:55:13.217   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.217   322  6342 V AudioCache: memcpy(0xaf10b000, 0xb0406000, 4096)
08-19 17:55:13.218   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.218   322  6342 V AudioCache: memcpy(0xaf10c000, 0xb0406000, 4096)
08-19 17:55:13.218   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.218   322  6342 V AudioCache: memcpy(0xaf10d000, 0xb0406000, 4096)
08-19 17:55:13.219   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.219   322  6342 V AudioCache: memcpy(0xaf10e000, 0xb0406000, 4096)
08-19 17:55:13.220   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.220   322  6342 V AudioCache: memcpy(0xaf10f000, 0xb0406000, 4096)
08-19 17:55:13.220   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.220   322  6342 V AudioCache: memcpy(0xaf110000, 0xb0406000, 4096)
08-19 17:55:13.221   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.221   322  6342 V AudioCache: memcpy(0xaf111000, 0xb0406000, 4096)
08-19 17:55:13.222   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.222   322  6342 V AudioCache: memcpy(0xaf112000, 0xb0406000, 4096)
08-19 17:55:13.222   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.222   322  6342 V AudioCache: memcpy(0xaf113000, 0xb0406000, 4096)
08-19 17:55:13.223   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.223   322  6342 V AudioCache: memcpy(0xaf114000, 0xb0406000, 4096)
08-19 17:55:13.224   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.224   322  6342 V AudioCache: memcpy(0xaf115000, 0xb0406000, 4096)
,08-19 17:55:13.225   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.225   322  6342 V AudioCache: memcpy(0xaf116000, 0xb0406000, 4096)
08-19 17:55:13.225   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.225   322  6342 V AudioCache: memcpy(0xaf117000, 0xb0406000, 4096)
08-19 17:55:13.226   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.226   322  6342 V AudioCache: memcpy(0xaf118000, 0xb0406000, 4096)
08-19 17:55:13.226   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.226   322  6342 V AudioCache: memcpy(0xaf119000, 0xb0406000, 4096)
08-19 17:55:13.227   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.227   322  6342 V AudioCache: memcpy(0xaf11a000, 0xb0406000, 4096)
08-19 17:55:13.228   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.228   322  6342 V AudioCache: memcpy(0xaf11b000, 0xb0406000, 4096)
08-19 17:55:13.229  6223  6223 D DockEventReceiver: finishStartingService: stopping service
08-19 17:55:13.229   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.229   322  6342 V AudioCache: memcpy(0xaf11c000, 0xb0406000, 4096)
08-19 17:55:13.229   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.229   322  6342 V AudioCache: memcpy(0xaf11d000, 0xb0406000, 4096)
08-19 17:55:13.230   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.230   322  6342 V AudioCache: memcpy(0xaf11e000, 0xb0406000, 4096)
08-19 17:55:13.231   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.231   322  6342 V AudioCache: memcpy(0xaf11f000, 0xb0406000, 4096)
08-19 17:55:13.232   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.232   322  6342 V AudioCache: memcpy(0xaf120000, 0xb0406000, 4096)
08-19 17:55:13.232   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.232   322  6342 V AudioCache: memcpy(0xaf121000, 0xb0406000, 4096)
08-19 17:55:13.233   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.233   322  6342 V AudioCache: memcpy(0xaf122000, 0xb0406000, 4096)
08-19 17:55:13.233   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.233   322  6342 V AudioCache: memcpy(0xaf123000, 0xb0406000, 4096)
08-19 17:55:13.234   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.234   322  6342 V AudioCache: memcpy(0xaf124000, 0xb0406000, 4096)
08-19 17:55:13.235   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.235   322  6342 V AudioCache: memcpy(0xaf125000, 0xb0406000, 4096)
08-19 17:55:13.235   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.235   322  6342 V AudioCache: memcpy(0xaf126000, 0xb0406000, 4096)
08-19 17:55:13.236   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.236   322  6342 V AudioCache: memcpy(0xaf127000, 0xb0406000, 4096)
08-19 17:55:13.236   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.236   322  6342 V AudioCache: memcpy(0xaf128000, 0xb0406000, 4096)
08-19 17:55:13.237   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.237   322  6342 V AudioCache: memcpy(0xaf129000, 0xb0406000, 4096)
08-19 17:55:13.238   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.238   322  6342 V AudioCache: memcpy(0xaf12a000, 0xb0406000, 4096)
08-19 17:55:13.238   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.238   322  6342 V AudioCache: memcpy(0xaf12b000, 0xb0406000, 4096)
08-19 17:55:13.239   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.239   322  6342 V AudioCache: memcpy(0xaf12c000, 0xb0406000, 4096)
08-19 17:55:13.239   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.239   322  6342 V AudioCache: memcpy(0xaf12d000, 0xb0406000, 4096)
08-19 17:55:13.240   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.240   322  6342 V AudioCache: memcpy(0xaf12e000, 0xb0406000, 4096)
08-19 17:55:13.241   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.241   322  6342 V AudioCache: memcpy(0xaf12f000, 0xb0406000, 4096)
08-19 17:55:13.241   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.241   322  6342 V AudioCache: memcpy(0xaf130000, 0xb0406000, 4096)
08-19 17:55:13.242   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.242   322  6342 V AudioCache: memcpy(0xaf131000, 0xb0406000, 4096)
08-19 17:55:13.242   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.243   322  6342 V AudioCache: memcpy(0xaf132000, 0xb0406000, 4096)
08-19 17:55:13.243   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.243   322  6342 V AudioCache: memcpy(0xaf133000, 0xb0406000, 4096)
08-19 17:55:13.244   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.244   322  6342 V AudioCache: memcpy(0xaf134000, 0xb0406000, 4096)
08-19 17:55:13.244   322  6342 V AudioCache: write(0xb0406000, 4096)
08-19 17:55:13.244   322  6342 V AudioCache: memcpy(0xaf135000, 0xb0406000, 4096)
08-19 17:55:13.244   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-19 17:55:13.245   322  6342 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-19 17:55:13.245   322  6342 V AwesomePlayer: postAudioEOS() 
08-19 17:55:13.245   322  6342 V AudioCache: write(0xb0406000, 280)
08-19 17:55:13.245   322  6342 V AudioCache: memcpy(0xaf136000, 0xb0406000, 280)
08-19 17:55:13.246   322  1377 V AudioFlinger: 3737 died, releasing its sessions
08-19 17:55:13.246   322  1377 V AudioFlinger:  pid 1849 @ 0
08-19 17:55:13.246   322  1377 V AudioFlinger:  pid 3309 @ 1
08-19 17:55:13.246   322  1377 V AudioFlinger:  pid 3309 @ 2
08-19 17:55:13.246  6223  6223 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-19 17:55:13.249   322  6339 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-19 17:55:13.249   322  6339 V AwesomePlayer: onStreamDone
08-19 17:55:13.249   322  6339 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-19 17:55:13.249   322  6339 V AudioCache: notify(0xb0409680, 2, 0, 0)
08-19 17:55:13.249   322  6339 V AudioCache: playback complete
08-19 17:55:13.249   322  6339 V AwesomePlayer: pause_l() 
08-19 17:55:13.249   322  6339 V AudioCache: notify(0xb0409680, 7, 0, 0)
08-19 17:55:13.249   322  6339 V AudioCache: ignored
08-19 17:55:13.249   322  6339 V AwesomePlayer: cancelPlayerEvents
08-19 17:55:13.249   322   322 V AudioCache: wait - success
08-19 17:55:13.249   322   322 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-19 17:55:13.249   322  6339 D AudioPlayer: Pause Playback at 1068125
08-19 17:55:13.250   322   322 V AwesomePlayer: reset_l() 
08-19 17:55:13.250   322   322 V AudioCache: notify(0xb0409680, 8, 0, 0)
08-19 17:55:13.250   322   322 V AudioCache: ignored
08-19 17:55:13.250   322   322 V AwesomePlayer: cancelPlayerEvents
08-19 17:55:13.250   322   322 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-19 17:55:13.250   322   322 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-19 17:55:13.250   322   322 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-19 17:55:13.250   322   322 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-19 17:55:13.250   322   322 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-19 17:55:13.250   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-19 17:55:13.250   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-19 17:55:13.250   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-19 17:55:13.250   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 0
08-19 17:55:13.250   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 0
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 0
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c0880 on port 1
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c04c0 on port 1
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c0560 on port 1
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-19 17:55:13.251   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-19 17:55:13.252   322   322 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-19 17:55:13.252   322   322 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-19 17:55:13.252   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-19 17:55:13.252   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-19 17:55:13.252   322  6341 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-19 17:55:13.252   322   322 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-19 17:55:13.252   322   322 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-19 17:55:13.252   322   322 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-19 17:55:13.253   322   322 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-19 17:55:13.253   322   322 D AudioPlayer: AudioPlayer releasing audio source
08-19 17:55:13.253   322   322 D AudioPlayer: AudioPlayer done releasing audio source
08-19 17:55:13.254   322   322 V AwesomePlayer: reset_l() 
08-19 17:55:13.254   322   322 V AwesomePlayer: cancelPlayerEvents
08-19 17:55:13.254   322   322 V AwesomePlayer: ~AwesomePlayer call
08-19 17:55:13.254   322   322 V AwesomePlayer: reset_l() 
08-19 17:55:13.254   322   322 V AwesomePlayer: cancelPlayerEvents
08-19 17:55:13.254  6269  6338 V SoundPool: close(31)
08-19 17:55:13.254  6269  6338 V SoundPool: pointer = 0x9fe60000, size = 205080, sampleRate = 48000, numChannels = 2
08-19 17:55:13.277  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-19 17:55:13.278  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-19 17:55:13.313  1029  1782 I ActivityManager: Process com.android.bluetooth (pid 3737) has died
,08-19 17:55:13.313  1029  1782 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-19 17:55:13.317  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-19 17:55:13.318  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6032
08-19 17:55:13.337  6223  6223 D BluetoothPermissionRequest: onReceive
,08-19 17:55:13.340  6223  6223 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-19 17:55:13.340  6223  6223 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-19 17:55:13.343  6223  6223 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-19 17:55:13.409  1029  1947 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6345 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-19 17:55:13.468  6131  6131 I UEI.SmartControl: Supports setup maps: true
08-19 17:55:13.470  6131  6131 D UEI.SmartControl: QS start statue = true Error code = 0
08-19 17:55:13.470  6131  6131 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-19 17:55:13.470  6131  6131 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-19 17:55:13.470  6131  6131 I UEI.SmartControl: ### init IR Blaster...
08-19 17:55:13.475  6131  6131 D serial_port: Configuring serial port
08-19 17:55:13.475  6131  6131 E UEI.SmartControl: UEIBLaster setting for 616
08-19 17:55:13.475  6131  6131 I UEI.SmartControl: Setting serial record hearder size = 2
08-19 17:55:13.475  6131  6131 I UEI.SmartControl: configuring settings for MAXQ616
08-19 17:55:13.475  6131  6131 I UEI.SmartControl: Get version...
,08-19 17:55:13.479  6345  6345 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-19 17:55:13.479  6345  6345 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-19 17:55:13.479  6345  6345 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-19 17:55:13.480  6345  6345 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-19 17:55:13.491  6345  6345 D BluetoothAdapterApp: Loading JNI Library
08-19 17:55:13.492  6131  6362 D UEI.SmartControl: serial port data available: 21
,08-19 17:55:13.509  6345  6345 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2f5ca56c Instance Count = 1
,08-19 17:55:13.514  6345  6345 D BluetoothAdapterApp: onCreate
08-19 17:55:13.518  6131  6131 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-19 17:55:13.518  6131  6131 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-19 17:55:13.518  6131  6131 I UEI.SmartControl: QS saving settings...
08-19 17:55:13.520  6131  6131 D UEI.SmartControl: IR Blaster version: 25672567
08-19 17:55:13.537  6131  6362 D UEI.SmartControl: serial port data available: 4
,08-19 17:55:13.552  6345  6345 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-19 17:55:13.552  6345  6345 D ProfileConfigQcom: Adding HeadsetService
,08-19 17:55:13.552  6345  6345 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-19 17:55:13.552  6345  6345 D ProfileConfigQcom: Adding A2dpService
08-19 17:55:13.552  6345  6345 D ProfileConfigQcom: [BTUI] HidService is supported
08-19 17:55:13.553  6345  6345 D ProfileConfigQcom: Adding HidService
08-19 17:55:13.553  6345  6345 D ProfileConfigQcom: [BTUI] HealthService is supported
08-19 17:55:13.553  6345  6345 D ProfileConfigQcom: Adding HealthService
08-19 17:55:13.553  6345  6345 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-19 17:55:13.554  6345  6345 D ProfileConfigQcom: [BTUI] PanService is supported
08-19 17:55:13.554  6345  6345 D ProfileConfigQcom: Adding PanService
08-19 17:55:13.555  6345  6345 D ProfileConfigQcom: [BTUI] GattService is supported
08-19 17:55:13.555  6345  6345 D ProfileConfigQcom: Adding GattService
08-19 17:55:13.555  6345  6345 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-19 17:55:13.555  6345  6345 D ProfileConfigQcom: Adding BluetoothMapService
08-19 17:55:13.556  6345  6345 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-19 17:55:13.558  6345  6345 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-19 17:55:13.563  6223  6223 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-19 17:55:13.564  6345  6345 V LGMDMManagerInternal: Create singleton instance
,08-19 17:55:13.568  6131  6131 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-19 17:55:13.571  6131  6369 I UEI.SmartControl: Device manager: loading config....
08-19 17:55:13.571  6131  6369 D UEI.SmartControl: ----------- loading internal config...
08-19 17:55:13.576  6131  6131 E UEI.SmartControl: Services init done
08-19 17:55:13.576  6131  6131 D UEI.SmartControl: QS Service init finished
08-19 17:55:13.577  6131  6131 D UEI.SmartControl: QS Service version name: 2.1.91
08-19 17:55:13.577  6131  6131 D UEI.SmartControl: QS Service version code: 201091
08-19 17:55:13.578  6131  6131 D UEI.SmartControl: Service requested: Control
08-19 17:55:13.582  6131  6369 E UEI.SmartControl: Loading SETTINGS...
,08-19 17:55:13.585  6131  6131 D UEI.SmartControl: Request IControl service: devices are loaded...
08-19 17:55:13.588  6131  6131 D UEI.SmartControl: Internal service binding...
08-19 17:55:13.589  6269  6269 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-19 17:55:13.589  6131  6369 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-19 17:55:13.591  6131  6147 I UEI.SmartControl: ------ IControl API: 11
08-19 17:55:13.591  6131  6147 D UEI.SmartControl: File observer start...
08-19 17:55:13.592  6131  6147 E UEI.SmartControl: IR Port is disabled: false
08-19 17:55:13.592  6131  6147 D UEI.SmartControl: Starting file observer...
08-19 17:55:13.593  6131  6147 I UEI.SmartControl: Registering callback...
08-19 17:55:13.596  6131  6148 I UEI.SmartControl: ------ IControl API: 19
08-19 17:55:13.597  6131  6148 I UEI.SmartControl: Registering Services Ready callback...
08-19 17:55:13.616  6131  6368 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-19 17:55:13.619  6269  6285 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-19 17:55:13.619  6131  6368 D UEI.SmartControl: -----service ready thread exits
08-19 17:55:13.620  6269  6336 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-19 17:55:13.621  6269  6336 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-19 17:55:13.621  6269  6269 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-19 17:55:13.622  6269  6269 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,08-19 17:55:13.622  6131  6147 I UEI.SmartControl: ------ IControl API: 8
08-19 17:55:13.624  6269  6269 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-19 17:55:13.624  6269  6269 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-19 17:55:13.624  6269  6269 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-19 17:55:13.625  6269  6269 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-19 17:55:13.626  6269  6269 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-19 17:55:13.626  6269  6269 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-19 17:55:13.628  6269  6269 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-19 17:55:13.633  6269  6269 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-19 17:55:13.635  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-19 17:55:13.636  6269  6269 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-19 17:55:13.636  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-19 17:55:13.637  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-19 17:55:13.638  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-19 17:55:13.639  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-19 17:55:13.640  6269  6269 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471622113639]
08-19 17:55:13.643  6269  6269 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-19 17:55:13.649  1029  1919 I ActivityManager: Killing 5881:com.lge.email/u0a23 (adj 15): empty #17
08-19 17:55:13.680  6269  6371 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-19 17:55:13.685  1029  1955 W libprocessgroup: failed to open /acct/uid_10023/pid_5881/cgroup.procs: No such file or directory
08-19 17:55:13.685  6345  6345 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:13.691  6345  6345 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-19 17:55:13.691  6345  6345 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-19 17:55:13.691  6345  6345 V BluetoothSapReceiver: SapReceiver onReceive 
08-19 17:55:13.692  6345  6345 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:13.693  6345  6345 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-19 17:55:13.694  6269  6269 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-19 17:55:13.694  6269  6269 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-19 17:55:13.696  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-19 17:55:13.696  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-19 17:55:13.697  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-19 17:55:13.697  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-19 17:55:13.697  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-19 17:55:13.699  6288  6288 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-19 17:55:13.710  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-19 17:55:13.713  1029  2029 I ActivityManager: Killing 5904:com.android.gallery3d/u0a27 (adj 15): empty #17
08-19 17:55:13.744  1029  1045 W libprocessgroup: failed to open /acct/uid_10027/pid_5904/cgroup.procs: No such file or directory
,08-19 17:55:14.964  1029  1911 D WifiServiceImplEx: setWifiEnabled: true pid=5974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-19 17:55:14.966  1029  1911 D WifiService: setWifiEnabled: true pid=5974, uid=10118
,08-19 17:55:14.966  1029  1911 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-19 17:55:14.996  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-19 17:55:14.996  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-19 17:55:14.996  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-19 17:55:14.998  1029  1534 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-19 17:55:14.998  1029  1534 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-19 17:55:15.001  1029  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-19 17:55:15.001  1029  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-19 17:55:15.001  1029  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-19 17:55:15.001  1029  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-19 17:55:15.001  1029  1534 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-19 17:55:15.001  1029  1534 E WifiHW  : unknown target_country: EU , set to default
08-19 17:55:15.001  1029  1534 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-19 17:55:15.001  1029  1534 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-19 17:55:15.001  1029  1534 I WifiUtil: gEnableBmps=1
08-19 17:55:15.596   318   889 D SoftapController: Softap fwReload - Ok
,08-19 17:55:15.602  1029  1534 E NetdConnector: NDC Command {34 softap fwreload wlan0 STA} took too long (593ms)
08-19 17:55:15.605   318   889 D CommandListener: Setting iface cfg
08-19 17:55:15.605   318   889 D CommandListener: Trying to bring down wlan0
08-19 17:55:15.607  1029  1091 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-19 17:55:15.625   318   889 D CommandListener: Clearing all IP addresses on wlan0
08-19 17:55:15.626   318  6387 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-19 17:55:15.635  1029  1534 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-19 17:55:15.638  1029  1089 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-19 17:55:15.653  1029  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-19 17:55:15.653  1029  1534 E WifiStateMachine: useWiFiOffloading() : false
08-19 17:55:15.653  1029  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-19 17:55:15.644  6388  6388 W wpa_supplicant: type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:15.644  6388  6388 W wpa_supplicant: type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:15.662  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-19 17:55:15.663  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-19 17:55:15.688  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:15.708  1029  1534 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-19 17:55:15.708  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:15.708  1029  1534 D WifiMonitor: connecting to supplicant
08-19 17:55:15.709  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-19 17:55:15.718  6388  6388 I wpa_supplicant: Successfully initialized wpa_supplicant
08-19 17:55:15.725  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:15.725  6223  6223 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-19 17:55:15.725  6223  6223 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-19 17:55:15.725  6223  6223 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-19 17:55:15.728  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-19 17:55:15.732  6388  6388 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-19 17:55:15.732  6388  6388 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-19 17:55:15.735  1029  1091 D Tethering: InitialState.processMessage what=4
08-19 17:55:15.736  1029  1091 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-19 17:55:15.740  6223  6223 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-19 17:55:15.740  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-19 17:55:15.740  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-19 17:55:15.740  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-19 17:55:15.740  6223  6223 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-19 17:55:15.740  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-19 17:55:15.741  6223  6223 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-19 17:55:15.748  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-19 17:55:15.750  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:15.757  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-19 17:55:15.763  6308  6406 W FormManager: Network not available. Please check & try again.
08-19 17:55:15.767  6308  6407 V FormManager: Network unavailable.
,08-19 17:55:15.770  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:15.770  6223  6223 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-19 17:55:15.770  6223  6223 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-19 17:55:15.770  6223  6223 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-19 17:55:15.771  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-19 17:55:15.771  6308  6407 V FormManager: Network unavailable.
08-19 17:55:15.771  6223  6223 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-19 17:55:15.771  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-19 17:55:15.771  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-19 17:55:15.771  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-19 17:55:15.771  6223  6223 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-19 17:55:15.771  6223  6223 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-19 17:55:15.802  6388  6388 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-19 17:55:15.899  6388  6388 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-19 17:55:15.908  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED ,
,08-19 17:55:15.911  1029  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-19 17:55:15.911  1029  1534 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-19 17:55:15.912  1029  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-19 17:55:15.912  1029  1534 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-19 17:55:15.912  1029  1534 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-19 17:55:15.913  1029  6410 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-19 17:55:15.913  1029  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-19 17:55:15.913  1029  6410 E WifiMonitor: WifiMonitor:wlan0 cnt=69 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-19 17:55:15.913  1029  6410 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-19 17:55:15.913  1029  6410 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-19 17:55:15.913  1029  1534 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-19 17:55:15.914  1029  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-19 17:55:15.914  1029  1534 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-19 17:55:15.914  1029  1534 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-19 17:55:15.915  1029  1534 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,08-19 17:55:15.916  1029  1534 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-19 17:55:15.916  1029  1534 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-19 17:55:15.916  1029  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-19 17:55:15.916  1029  1534 E WifiStateMachine: useWiFiOffloading() : false
08-19 17:55:15.916  1029  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-19 17:55:15.917  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:15.917  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:15.917  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-19 17:55:15.917  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:15.917  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-19 17:55:15.918  1029  1534 D WifiNative-wlan0: doBoolean: SET update_config 1
08-19 17:55:15.918  1029  1534 D WifiNative-wlan0: SET update_config 1: returned true
08-19 17:55:15.918  1029  1534 D WifiConfigStore: Loading config and enabling all networks 
08-19 17:55:15.919  1029  1534 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-19 17:55:15.919  1029  1534 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-19 17:55:15.920  1937  1937 D WfdService: Waiting for WifiP2p enabling
08-19 17:55:15.921  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-19 17:55:15.924  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:15.924  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:15.924  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:15.924  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:15.924  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:15.924  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:15.924  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:15.924  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:15.924  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:15.924  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:15.924  5974  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:15.932  1029  1534 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-19 17:55:15.933  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:15.933  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:15.933  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:15.933  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:15.933  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:15.933  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:15.933  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:15.933  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:15.933  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:15.933  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:15.933  5974  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:15.936  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-19 17:55:15.938  1029  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-19 17:55:15.941  1029  1534 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-19 17:55:15.941  1029  1534 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-19 17:55:15.945  1029  1534 D WifiStateMachine: enableVerboseLogging : level 2
08-19 17:55:15.945  1029  1534 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-19 17:55:15.945  1029  1534 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-19 17:55:15.945  1029  1534 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-19 17:55:15.946  1029  1534 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-19 17:55:15.946  1029  1534 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-19 17:55:15.946  1029  1534 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-19 17:55:15.946  1029  1534 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,08-19 17:55:15.946  1029  1534 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-19 17:55:15.947  1029  1534 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-19 17:55:15.947  1029  1534 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-19 17:55:15.947  1029  1534 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-19 17:55:15.947  1029  1534 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-19 17:55:15.947  1029  1534 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-19 17:55:15.948  1029  1534 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-19 17:55:15.948  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-19 17:55:15.949  6308  6413 W FormManager: Network not available. Please check & try again.
08-19 17:55:15.956  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:15.957  1029  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-19 17:55:15.957  1029  1534 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,08-19 17:55:15.958  1029  1534 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-19 17:55:15.958  1029  1534 D WifiNative-HAL: Setting external_sim to 1
08-19 17:55:15.958  1029  1534 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-19 17:55:15.958  1937  1937 D WfdsService: Supplicant Connection state is changed : true
08-19 17:55:15.958  1937  2308 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-19 17:55:15.958  1937  2308 D WfdsService: Set the WFDS Monitor: true
08-19 17:55:15.958  1937  2308 D WfdsMonitor: WfdsMonitorThread create
08-19 17:55:15.958  1937  2308 D WfdsMonitor: WFDS Monitor is created and started
08-19 17:55:15.959  1937  2308 D WfdsService: WiFi: Supplicant connection re-established
08-19 17:55:15.959  1029  1534 D WifiNative-wlan0: SET external_sim 1: returned true
08-19 17:55:15.959  1029  1534 I WifiNative-HAL: startHal
08-19 17:55:15.959  1029  1534 D wifi    : setting scan oui 0xaf75b960
08-19 17:55:15.959  1029  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-19 17:55:15.959  1029  1534 I WifiNative-HAL: startHal
08-19 17:55:15.959  1029  1534 D wifi    : setting scan oui 0xaf75b960
08-19 17:55:15.960  1029  1534 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-19 17:55:15.960  1937  6415 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-19 17:55:15.960  1937  6415 E CtrlSupplicant: Succeed to open control connection
08-19 17:55:15.960  1937  6415 E CtrlSupplicant: Succeed to open monitor connection
08-19 17:55:15.961  1937  6415 D WfdsMonitor: Supplicant connection established
08-19 17:55:15.961  1937  2308 D WfdsService: Connected to the supplicant for wfds
08-19 17:55:15.961  1029  1534 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-19 17:55:15.961  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-19 17:55:15.961  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-19 17:55:15.962  1029  1534 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-19 17:55:15.962  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-19 17:55:15.962  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-19 17:55:15.963  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-19 17:55:15.963  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-19 17:55:15.963  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-19 17:55:15.963  6308  6414 V FormManager: Network unavailable.
08-19 17:55:15.964  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-19 17:55:15.964  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-19 17:55:15.964  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-19 17:55:15.964  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-19 17:55:15.964  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-19 17:55:15.964  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-19 17:55:15.965  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-19 17:55:15.965  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-19 17:55:15.965  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-19 17:55:15.965  6388  6388 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-19 17:55:15.966  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-19 17:55:15.966  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-19 17:55:15.966  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-19 17:55:15.966  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-19 17:55:15.967  1029  1534 E WifiNative: : [118,031,148 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-19 17:55:15.967  1029  1534 D WifiNative-wlan0: doBoolean: RECONNECT
08-19 17:55:15.968  1029  1534 D WifiNative-wlan0: RECONNECT: returned true
08-19 17:55:15.968  1029  1534 D WifiNative-wlan0: doString: [STATUS]
08-19 17:55:15.968  1029  6410 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-19 17:55:15.968  1029  6410 E WifiMonitor: WifiMonitor:wlan0 cnt=70 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-19 17:55:15.968  1029  1534 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-19 17:55:15.968  1029  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-19 17:55:15.969  1029  1534 D WifiNative-wlan0: SET ps 1: returned true
08-19 17:55:15.969  1029  1533 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:15.971   318   889 D CommandListener: Setting iface cfg
08-19 17:55:15.971   318   889 D CommandListener: Trying to bring up p2p0
08-19 17:55:15.971  1029  1533 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-19 17:55:15.971  1029  1533 D LGWifiP2pService: P2pEnablingState
08-19 17:55:15.971  1029  1533 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:15.972  1029  1533 D LGWifiP2pService: P2p socket connection successful
08-19 17:55:15.972  1029  1533 D LGWifiP2pService: P2pEnabledState
08-19 17:55:15.974  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 3
08-19 17:55:15.974  1029  1029 D RttService: SCAN_AVAILABLE : 3
08-19 17:55:15.974  1029  1552 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:15.974  1029  1552 I WifiNative-HAL: startHal
08-19 17:55:15.974  1029  1553 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:15.974  1029  1552 D wifi    : getting scan capabilities on interface[1] = 0xaf75b960
08-19 17:55:15.974  1029  1552 D wifi    : failed to get capabilities : -3
08-19 17:55:15.974  1029  1552 E WifiScanningService: could not get scan capabilities
08-19 17:55:15.974  1029  1534 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-19 17:55:15.975  1029  1534 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-19 17:55:15.975  1029  1534 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-19 17:55:15.976  1029  1534 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-19 17:55:15.976  1029  1534 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-19 17:55:15.977  1029  1534 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-19 17:55:15.977  1029  1534 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-19 17:55:15.977  1029  1534 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-19 17:55:15.977  6388  6388 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-19 17:55:15.978  1029  1534 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-19 17:55:15.978  1029  1534 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-19 17:55:15.979  1029  1534 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-19 17:55:15.973  6308  6414 V FormManager: Network unavailable.
08-19 17:55:15.979  1029  1534 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-19 17:55:15.979  6388  6388 E wpa_supplicant: disconnect_rssi_lvl: -100
08-19 17:55:15.979  1029  1534 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-19 17:55:15.980  1029  1534 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-19 17:55:15.981  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-19 17:55:15.981  1937  1937 D WfdsService: WifiP2pState is changed : true
08-19 17:55:15.981  1029  1533 D LGWifiP2pService: sending p2p connection changed broadcast
08-19 17:55:15.981  1937  2308 D WfdsService: Receive the WFDS_ENABLE Method
08-19 17:55:15.981  1937  2308 D WfdsService: Set the WFDS Monitor: true
08-19 17:55:15.981  1937  2308 D WfdsService: Connected to the supplicant for wfds
08-19 17:55:15.981  1937  2308 D WfdsJNI : doCommand: WFDS_SET TRUE
08-19 17:55:15.981  6388  6388 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-19 17:55:15.981  1937  2308 D WfdsService: selectPreferredScanChannel [36]
08-19 17:55:15.981  1937  2308 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-19 17:55:15.982  1029  1534 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-19 17:55:15.982  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-19 17:55:15.983  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-19 17:55:15.983  1937  1937 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-19 17:55:15.984  1937  1937 D WfdsService: isConnected: false
08-19 17:55:15.984  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-19 17:55:15.985  6388  6388 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-19 17:55:15.985  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:15.985  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:15.986  1029  6410 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-19 17:55:15.987  1029  6410 E WifiMonitor: WifiMonitor:wlan0 cnt=71 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:15.987  1029  6410 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:15.987  1029  6410 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:15.987  1029  6410 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:15.987  1029  6410 E WifiMonitor: WifiMonitor:p2p0 cnt=72 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:15.987  1029  6410 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:15.987  1029  6410 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:15.987  1029  6410 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:15.987  1029  6410 E WifiMonitor: WifiMonitor:p2p0 cnt=73 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:15.987  1029  6410 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:15.987  1029  6410 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:15.988  1937  6415 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:15.988  1029  1533 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-19 17:55:15.988  1937  6415 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:15.988  4212  4212 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-19 17:55:15.988  1029  1534 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-19 17:55:15.989  4212  4212 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-19 17:55:15.989  1029  1533 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-19 17:55:15.989  1029  1534 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-19 17:55:15.989  1029  1533 D WifiNative-p2p0: doBoolean: SET device_name G3
08-19 17:55:15.989  1029  1534 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-19 17:55:15.989  1029  1533 D WifiNative-p2p0: SET device_name G3: returned true
08-19 17:55:15.990  1029  1533 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-19 17:55:15.990  1029  1533 D LGWifiP2pService: before postfix = G3
08-19 17:55:15.990  1029  1533 D WifiServerServiceExt: postfix byte check : 2
08-19 17:55:15.990  1029  1533 D LGWifiP2pService: after postfix = G3
08-19 17:55:15.990  1029  1533 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-19 17:55:15.990  1029  1534 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-19 17:55:15.990  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-19 17:55:15.990  1029  1533 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-19 17:55:15.990  1029  1533 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-19 17:55:15.990  1029  1533 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-19 17:55:15.991  1029  1533 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-19 17:55:15.991  1029  1533 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-19 17:55:15.991  1029  1533 D WifiNative-p2p0: doBoolean: P2P_SET conc_p,ref p2p
08-19 17:55:15.991  1029  1533 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-19 17:55:15.992  1029  1533 D WifiNative-HAL: p2pGetDeviceAddress
08-19 17:55:15.992  1029  1533 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-19 17:55:15.992  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-19 17:55:15.992  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-19 17:55:15.993  1029  6410 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-19 17:55:15.993  1029  6410 E WifiMonitor: WifiMonitor:wlan0 cnt=74 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-19 17:55:15.993  1029  6410 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-19 17:55:15.993  1029  6410 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-19 17:55:15.993  4212  4212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-19 17:55:15.994  1029  1534 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-19 17:55:15.994  1029  1534 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-19 17:55:15.994  1029  1534 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-19 17:55:15.994  1029  1534 D WifiNative-wlan0: doBoolean: SCAN
08-19 17:55:15.995  1029  1534 D WifiNative-wlan0: SCAN: returned false
08-19 17:55:15.995  1029  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 70 0 rt=118059  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-19 17:55:15.997  4212  4212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-19 17:55:15.997  1029  1533 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-19 17:55:15.997  1029  1533 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-19 17:55:15.998  1029  1533 D WifiNative-p2p0: P2P_FLUSH: returned true
08-19 17:55:15.998  1029  1533 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-19 17:55:15.998  1029  1533 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-19 17:55:15.998  1029  1533 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-19 17:55:15.999  1029  1533 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-19 17:55:15.999  1029  1533 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-19 17:55:16.000  1937  1937 I WfdStateTracker: handleP2pThisDeviceChanged
08-19 17:55:16.000  1937  1937 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-19 17:55:16.000  1937  1937 D WfdsService: Update P2p Interface State: 3
08-19 17:55:16.003  1029  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 70 0 rt=118068  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-19 17:55:16.004  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-19 17:55:16.004  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-19 17:55:16.005  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:16.005  1029  1534 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-19 17:55:16.005  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:16.005  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-19 17:55:16.005  1029  1534 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-19 17:55:16.006  1029  1534 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-19 17:55:16.006  1029  1534 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-19 17:55:16.006  1029  1534 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-19 17:55:16.007  4212  6416 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-19 17:55:16.007  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-19 17:55:16.007  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-19 17:55:16.007  1029  1029 D WifiServerServiceExt: setSupplicantStateSCANNING
08-19 17:55:16.008  6106  6106 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-19 17:55:16.008  6106  6106 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-19 17:55:16.012  1029  1533 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-19 17:55:16.012  1029  1533 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-19 17:55:16.012  1029  1533 D LGWifiP2pService: InactiveState
08-19 17:55:16.012  1029  1533 D LGWifiP2pService: InactiveState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.012  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.012  1029  1533 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-19 17:55:16.013  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-19 17:55:16.013  4212  6417 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-19 17:55:16.013  4212  6417 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-19 17:55:16.014  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:16.014  1937  6415 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-19 17:55:16.014  1029  6410 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-19 17:55:16.014  1029  6410 E WifiMonitor: WifiMonitor:p2p0 cnt=75 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:16.014  1029  6410 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:16.014  1029  6410 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:16.014  6388  6388 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-19 17:55:16.014  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:16.015  1029  1533 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-19 17:55:16.015  1937  6415 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:16.015  1029  1533 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.015  1029  6410 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:16.015  1029  6410 E WifiMonitor: WifiMonitor:p2p0 cnt=76 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:16.015  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.015  1029  6410 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:16.015  1029  6410 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:16.015  1029  1533 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.015  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.015  1029  1533 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.015  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:16.015  1029  6410 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:16.015  1029  1533 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.015  1029  6410 E WifiMonitor: WifiMonitor:p2p0 cnt=77 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:16.015  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.015  1029  6410 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:16.015  1029  6410 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DR,IVER type=WORLD
08-19 17:55:16.015  1029  1533 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.016  1029  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.016  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.016  1029  1533 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.016  1029  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.016  1937  6415 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:16.016  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.016  1029  1533 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.016  1029  1029 E WifiServerServiceExt: No p2p device connected
08-19 17:55:16.017  1937  2308 W WfdsService: DefaultState - msg [9441285] is not handled
08-19 17:55:16.018  6106  6106 V [BNRBootReceiver]: Boot Receiver Return
08-19 17:55:16.021  3650  3650 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-19 17:55:16.030  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-19 17:55:16.036  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-19 17:55:16.042  6269  6269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-19 17:55:16.042  6269  6269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-19 17:55:16.044  6269  6269 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-19 17:55:16.507  6388  6388 I wpa_supplicant: [LGE_PATCH]scan interval[0] = 2 sec.
,08-19 17:55:16.519  1029  6410 E WifiMonitor: WifiMonitor:wlan0 cnt=78 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-19 17:55:16.519  1029  6410 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-19 17:55:16.521  1029  1534 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-19 17:55:16.524  1937  6415 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-19 17:55:16.526  1029  6410 E WifiMonitor: WifiMonitor:p2p0 cnt=79 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-19 17:55:16.526  1029  6410 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-19 17:55:16.526  1029  1533 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.526  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.526  1029  1533 D LGWifiP2pService: DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:16.526  1029  1534 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-19 17:55:16.527  1029  1534 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-19 17:55:16.527  1029  1534 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-19 17:55:16.527  1029  1534 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-19 17:55:16.555  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-19 17:55:16.562  6223  6223 D WiFiOffLoadBroadcast: Not supported operator for automatic switch,
08-19 17:55:16.883  1029  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-19 17:55:16.883  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-19 17:55:16.883  1029  1533 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-19 17:55:16.902  1029  1534 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-19 17:55:16.908  1029  1534 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-19 17:55:16.909  1029  1534 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-19 17:55:16.910  1029  1534 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-19 17:55:16.933  1029  1534 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-19 17:55:18.003  1029  1982 D WifiServiceImplEx: setWifiEnabled: false pid=5974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-19 17:55:18.004  1029  1982 D WifiService: setWifiEnabled: false pid=5974, uid=10118
,08-19 17:55:18.004  1029  1982 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-19 17:55:18.040  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-19 17:55:18.040  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-19 17:55:18.040  1029  1029 D Ulp_jni : JNI:system_update. Event-4
,08-19 17:55:18.044  1029  1534 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-19 17:55:18.045  1029  1534 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-19 17:55:18.045  1029  1534 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-19 17:55:18.045  1029  1534 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-19 17:55:18.055  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 1
08-19 17:55:18.055  1029  1029 D RttService: SCAN_AVAILABLE : 1
,08-19 17:55:18.058  1029  1552 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:18.058  1029  1553 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:18.058  1029  1533 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:18.059  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:18.059  1029  1533 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@392e8524
08-19 17:55:18.059  1029  1533 D LGWifiP2pService: P2pDisablingState
08-19 17:55:18.059  1029  1533 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:18.059  1029  1533 D LGWifiP2pService: p2p socket connection lost
08-19 17:55:18.059  1029  1533 D LGWifiP2pService: P2pDisabledState
08-19 17:55:18.062  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-19 17:55:18.062  1937  1937 D WfdsService: WifiP2pState is changed : false
08-19 17:55:18.062  1937  2308 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-19 17:55:18.062  1937  2308 D WfdsService: Set the WFDS Monitor: false
08-19 17:55:18.064  1937  2308 D WfdsMonitor: WFDS Monitor is stopped
08-19 17:55:18.064  1937  2308 D WfdsService: STATE : WfdsDisabledState - enter
08-19 17:55:18.065  1937  6415 D CtrlSupplicant: Received on exit socket, terminate
08-19 17:55:18.065  1937  6415 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-19 17:55:18.065  1937  6415 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-19 17:55:18.065  1937  6415 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-19 17:55:18.066  1937  2309 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-19 17:55:18.069  1937  2308 W WfdsService: DefaultState - msg [9445378] is not handled
,08-19 17:55:18.075  1029  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-19 17:55:18.075   318   889 D CommandListener: Clearing all IP addresses on wlan0
08-19 17:55:18.079  1029  1029 D WifiHS20: hidePasspointNotification off =false
08-19 17:55:18.080  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:18.080  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:18.080  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-19 17:55:18.082  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-19 17:55:18.082  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-19 17:55:18.087  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-19 17:55:18.093  1029  1029 D WifiHS20: hidePasspointNotification off =false
,08-19 17:55:18.100  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:18.100  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:18.100  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-19 17:55:18.101  1029  1534 D WifiNative-p2p0: doBoolean: TERMINATE
08-19 17:55:18.101  1029  1534 D WifiNative-p2p0: TERMINATE: returned true
08-19 17:55:18.102  1029  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-19 17:55:18.102  1029  1534 E WifiStateMachine: useWiFiOffloading() : false
08-19 17:55:18.102  1029  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-19 17:55:18.107  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-19 17:55:18.107  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-19 17:55:18.108  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-19 17:55:18.115  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:18.116  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:18.116  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:18.116  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:18.116  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:18.116  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:18.116  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:18.116  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:18.116  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:18.116  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:18.116  5974  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:18.117  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:18.117  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:18.117  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:18.117  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:18.117  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:18.117  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:18.117  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:18.117  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:18.117  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:18.117  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:18.117  5974  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:18.118  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-19 17:55:18.119  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-19 17:55:18.121  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-19 17:55:18.126  3650  3650 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-19 17:55:18.133  6205  6205 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-19 17:55:18.133  6205  6205 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-19 17:55:18.133  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-19 17:55:18.142  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-19 17:55:18.150  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-19 17:55:18.154  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-19 17:55:18.154  6388  6388 I wpa_supplicant: monitor socket send errors count : 1
08-19 17:55:18.154  6388  6388 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1937-4\x00 that cannot receive messages
,08-19 17:55:18.157  1029  6410 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-19 17:55:18.157  1029  6410 D WifiMonitor: Dropping event because (p2p0) is stopped
08-19 17:55:18.158  1029  6410 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
08-19 17:55:18.158  1029  6410 E WifiMonitor: WifiMonitor:wlan0 cnt=80 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
08-19 17:55:18.160  1029  1534 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 80 0 rt=120224  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
,08-19 17:55:18.160  1029  1534 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 80 0 rt=120225  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
08-19 17:55:18.178  6269  6269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-19 17:55:18.178  6269  6269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-19 17:55:18.180  6269  6269 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-19 17:55:18.187  3650  3650 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-19 17:55:18.191  6205  6205 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-19 17:55:18.191  6205  6205 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-19 17:55:18.191  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-19 17:55:18.194  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-19 17:55:18.199  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-19 17:55:18.205  6269  6269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-19 17:55:18.205  6269  6269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-19 17:55:18.207  6269  6269 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-19 17:55:18.215  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-19 17:55:18.221  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:18.222  6308  6446 W FormManager: Network not available. Please check & try again.
,08-19 17:55:18.228  6308  6447 V FormManager: Network unavailable.
08-19 17:55:18.229  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-19 17:55:18.234  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-19 17:55:18.234  1029  6410 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-19 17:55:18.234  1029  6410 E WifiMonitor: WifiMonitor:wlan0 cnt=81 dispatchEvent: CTRL-EVENT-TERMINATING 
08-19 17:55:18.234  1029  6410 D WifiMonitor: Disconnecting from the supplicant, no more events
08-19 17:55:18.235  1029  1534 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 81 0
,08-19 17:55:18.244  6308  6447 V FormManager: Network unavailable.
08-19 17:55:18.338  1937  1937 D WfdsService: Supplicant Connection state is changed : false
08-19 17:55:18.339  1937  2308 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-19 17:55:18.339  1937  2308 D WfdsService: Set the WFDS Monitor: false
08-19 17:55:18.339  1937  2308 D WfdsMonitor: WFDS Monitor is stopped
08-19 17:55:18.341  1029  1534 D WifiOffDelayIfNotUsed: stopMonitoring
08-19 17:55:18.342  1029  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-19 17:55:18.342  1029  1534 E WifiStateMachine: useWiFiOffloading() : false
08-19 17:55:18.342  1029  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-19 17:55:18.346  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-19 17:55:18.349  2465  2465 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:18.350  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-19 17:55:18.351  4212  4212 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-19 17:55:18.352  4212  4212 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-19 17:55:18.354  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-19 17:55:18.355  1029  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-19 17:55:18.355  1029  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-19 17:55:18.356  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:18.358  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:18.358  4212  4212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-19 17:55:18.365  4212  4212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-19 17:55:18.369  4212  6449 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-19 17:55:18.376  4212  6450 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-19 17:55:18.376  4212  6450 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-19 17:55:18.382  6205  6205 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-19 17:55:18.382  6205  6205 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-19 17:55:18.382  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-19 17:55:18.387  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:18.390  6308  6452 W FormManager: Network not available. Please check & try again.
08-19 17:55:18.394  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-19 17:55:18.396  6308  6454 V FormManager: Network unavailable.
08-19 17:55:18.402  6308  6454 V FormManager: Network unavailable.
08-19 17:55:18.566  6131  6370 D UEI.SmartControl: Internal timer expired: 2
,08-19 17:55:18.567  6131  6370 D UEI.SmartControl: unbind internal service
,08-19 17:55:18.798  6131  6366 D serial_port: close(fd = 24)
,08-19 17:55:18.808  6131  6366 I UEI.SmartControl: Serial port is closed.
08-19 17:55:20.496  1029  1389 V AlarmManager: RTC_WAKEUP set : Alarm{e3c453b type 0 when 1471622112380 com.android.vending} when 1471622112380
,08-19 17:55:20.506  6269  6269 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-19 17:55:20.506  6269  6269 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6032
08-19 17:55:20.599  1029  1919 V SIM_STK : Menu title from STK is T-Mobile
,08-19 17:55:20.712  5496  5496 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-19 17:55:21.055  1029  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-19 17:55:21.056  1029  2029 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-19 17:55:21.095  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-19 17:55:21.095  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-19 17:55:21.095  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-19 17:55:21.096  1029  1091 D BluetoothManagerService: Message: 1
08-19 17:55:21.096  1029  1091 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-19 17:55:21.122  1029  1091 D BluetoothManagerService: Message: 20
08-19 17:55:21.122  1029  1091 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@189aae04:true
,08-19 17:55:21.127  6345  6345 D BluetoothAdapterState: make
08-19 17:55:21.132  6345  6345 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-19 17:55:21.132  6345  6345 I bluedroid-qcom: init
08-19 17:55:21.134  6345  6465 I BluetoothAdapterState: Entering OffState
08-19 17:55:21.134  6345  6345 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-19 17:55:21.135  6345  6345 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-19 17:55:21.135  6345  6345 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-19 17:55:21.135  6345  6345 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-19 17:55:21.135  6345  6345 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
,08-19 17:55:21.139  6345  6345 I bluedroid-qcom: get_profile_interface socket
08-19 17:55:21.139  6345  6345 I bluedroid-qcom: get_profile_interface map_client
08-19 17:55:21.141  6345  6469 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-19 17:55:21.134  6468  6468 W bdaddr_loader: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:21.134  6468  6468 W bdaddr_loader: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:21.151  6468  6468 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-19 17:55:21.152  6468  6468 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-19 17:55:21.152  6468  6468 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-19 17:55:21.158  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-19 17:55:21.159  1029  1091 D BluetoothManagerService: Message: 40
08-19 17:55:21.159  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-19 17:55:21.160  6345  6361 I bluedroid-qcom: config_hci_snoop_log
08-19 17:55:21.161  1029  1091 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-19 17:55:21.161  1029  1091 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-19 17:55:21.165  6468  6468 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-19 17:55:21.172  6345  6465 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-19 17:55:21.173  6468  6468 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-19 17:55:21.173  6468  6468 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-19 17:55:21.175  6345  6469 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-19 17:55:21.176  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-19 17:55:21.177  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
,08-19 17:55:21.179  6345  6469 D BluetoothAdapterProperties: Name is: G3
08-19 17:55:21.179  6345  6465 D BluetoothAdapterProperties: Setting state to 11
08-19 17:55:21.180  6345  6465 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-19 17:55:21.180  1029  1091 D BluetoothManagerService: Message: 60
08-19 17:55:21.180  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-19 17:55:21.180  1029  1091 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-19 17:55:21.185  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:21.185  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-19 17:55:21.189  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:21.193  6223  6223 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-19 17:55:21.196  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:21.214  6345  6465 I LGBluetoothServiceJni: classInitNative: succeeds
,08-19 17:55:21.218  6345  6345 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-19 17:55:21.221  6345  6345 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:21.221  6345  6345 V BluetoothPbapReceiver: ***********state = 11
08-19 17:55:21.226  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:21.228  6345  6465 D BluetoothBondStateMachine: make
,08-19 17:55:21.232  6345  6465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:21.232  6345  6465 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-19 17:55:21.232  6345  6465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:21.232  6345  6465 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-19 17:55:21.233  6345  6465 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-19 17:55:21.233  6345  6483 I BluetoothBondStateMachine: StableState(): Entering Off State
08-19 17:55:21.237  6345  6465 E BluetoothAdapterService: File transfer profiles supported!!
08-19 17:55:21.246  6223  6223 D BluetoothPermissionRequest: onReceive
,08-19 17:55:21.248  6345  6345 D HeadsetService: Received start request. Starting profile...
08-19 17:55:21.249  6345  6345 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-19 17:55:21.249  6345  6345 D LGBluetoothHfpAdapter: Version 1.6
08-19 17:55:21.252  6345  6465 E BluetoothAdapterService: File transfer profiles supported!!
08-19 17:55:21.252  6345  6345 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-19 17:55:21.254  6345  6345 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-19 17:55:21.254  6345  6345 D HeadsetStateMachine: make
08-19 17:55:21.255  6223  6223 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-19 17:55:21.261  6345  6465 E BluetoothAdapterService: File transfer profiles supported!!
,08-19 17:55:21.268  6345  6465 E BluetoothAdapterService: File transfer profiles supported!!
,08-19 17:55:21.273  6345  6465 E BluetoothAdapterService: File transfer profiles supported!!
08-19 17:55:21.277  6345  6465 E BluetoothAdapterService: File transfer profiles supported!!
,08-19 17:55:21.282  6345  6465 E BluetoothAdapterService: File transfer profiles supported!!
08-19 17:55:21.297  6345  6465 V LGMDMManager: Create singleton instance
,08-19 17:55:21.299  6345  6465 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-19 17:55:21.302  6345  6345 D LgDataFeature: LgDataFeature() Constructor: none
08-19 17:55:21.302  6345  6345 D LgDataFeature: LgDataFeature() Constructor Done, null
08-19 17:55:21.307  6345  6345 D HeadsetStateMachine: max_hf_connections = 1
08-19 17:55:21.307  6345  6345 I bluedroid-qcom: get_profile_interface handsfree
08-19 17:55:21.310  6345  6345 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-19 17:55:21.310   322  1378 V AudioPolicyService: registerClient() client 0xb57f5780, uid 1002
08-19 17:55:21.311   322  1377 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-19 17:55:21.311   322  1377 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-19 17:55:21.311   322  1377 V AudioPolicyManagerEx: getOutput() returns output 2
08-19 17:55:21.311  6345  6345 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-19 17:55:21.311   322  2136 V AudioFlinger: registerClient() client 0xb5581568, pid 6345
08-19 17:55:21.312   322  1372 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:21.312  6345  6345 V ToneGenerator: Create Track: 0xb4928a80
08-19 17:55:21.312   322  1372 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:55:21.312  6345  6345 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-19 17:55:21.312  6345  6345 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-19 17:55:21.312   322   322 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-19 17:55:21.312   322   322 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-19 17:55:21.312  1029  1996 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:21.312   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-19 17:55:21.312  1029  1996 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:55:21.312   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
08-19 17:55:21.312  1599  2691 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:21.312  1599  2691 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:55:21.313  6345  6345 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-19 17:55:21.313   322  1373 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:21.313   322  1373 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:21.313  3309  3328 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:21.313  3309  3328 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:55:21.313  1029  1782 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:21.313  1029  1782 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:21.313  3309  3327 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:21.313  2145  2163 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:21.313  3309  3327 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:21.313  2145  2163 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:55:21.313  2145  2163 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:21.313  2145  2163 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:21.313   322  2136 I AudioFlinger: isAudioPlaybackHookOn() false
08-19 17:55:21.314  1599  2691 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:21.314  1599  2691 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:21.314   322  2138 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-19 17:55:21.314   322  2138 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-19 17:55:21.314   322  2138 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-19 17:55:21.314  1849  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:21.314   322  2138 V AudioPolicyManagerEx: getOutput() returns output 2
08-19 17:55:21.314  1849  1865 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:,55:21.314  1849  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:21.314  1849  1865 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:21.314  6345  6360 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:21.314  6345  6345 V AudioSystem: getLatency() output 2, latency 50
08-19 17:55:21.314  6345  6360 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-19 17:55:21.314  6345  6345 V AudioSystem: getFrameCount() output 2, frameCount 960
08-19 17:55:21.314  6345  6345 V AudioTrack: createTrack_l() output 2 afLatency 50
08-19 17:55:21.314  6345  6360 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:21.314  6345  6360 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-19 17:55:21.314   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-19 17:55:21.314   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-19 17:55:21.314   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-19 17:55:21.314   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-19 17:55:21.314   322   322 V AudioFlinger: createTrack() lSessionId: 22
08-19 17:55:21.315  6345  6345 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-19 17:55:21.315   322   322 V AudioFlinger: acquiring 22 from 6345, for 6345
08-19 17:55:21.315   322   322 V AudioFlinger:  added new entry for 22
08-19 17:55:21.316  6345  6345 V ToneGenerator: ToneGenerator INIT OK, time: 123393
08-19 17:55:21.316  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:21.317  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:21.318  6345  6486 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-19 17:55:21.318  6345  6486 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-19 17:55:21.318  6345  6486 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-19 17:55:21.318  6345  6486 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-19 17:55:21.318   322  1377 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6345
08-19 17:55:21.319   322  1377 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-19 17:55:21.319   322  1377 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-19 17:55:21.319   322  1377 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-19 17:55:21.319   322  1377 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-19 17:55:21.319   322  1377 V voice   : voice_set_parameters: exit with code(0)
08-19 17:55:21.319  6345  6345 D A2dpService: Received start request. Starting profile...
08-19 17:55:21.319   322  1377 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-19 17:55:21.319   322  1377 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-19 17:55:21.319   322  1377 V msm8974_platform: platform_set_parameters: exit with code(0)
08-19 17:55:21.319   322  1377 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-19 17:55:21.319   322  1377 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-19 17:55:21.319   322  1377 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-19 17:55:21.319  6345  6486 V ToneGenerator: ToneGenerator destructor
08-19 17:55:21.319  6345  6486 V ToneGenerator: stopTone
08-19 17:55:21.319  6345  6486 V ToneGenerator: Delete Track: 0xb4928a80
08-19 17:55:21.319  6345  6345 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-19 17:55:21.32,0  6345  6486 V AudioTrack: ~AudioTrack, releasing session id from 6345 on behalf of 6345
08-19 17:55:21.320   322  2136 V AudioPolicyService: AudioCommandThread() adding release output 2
08-19 17:55:21.320   322  2136 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-19 17:55:21.320   322  2138 V AudioFlinger: releasing 22 from 6345 for 6345
08-19 17:55:21.320   322  2138 V AudioFlinger:  decremented refcount to 0
08-19 17:55:21.320   322  2138 V AudioFlinger: purging stale effects
08-19 17:55:21.320   322  1222 V AudioPolicyService: AudioCommandThread() waking up
08-19 17:55:21.320   322  1222 V AudioPolicyService: AudioCommandThread() processing release output 2
08-19 17:55:21.320   322  1222 V AudioPolicyManager: releaseOutput() 2
08-19 17:55:21.320   322  1222 V AudioPolicyService: AudioCommandThread() going to sleep
08-19 17:55:21.320   322  2136 V AudioFlinger: PlaybackThread::Track destructor
08-19 17:55:21.320   322  2136 V AudioFlinger: removeClient_l() pid 6345, calling pid 322
08-19 17:55:21.320  6345  6345 V Avrcp   : make
08-19 17:55:21.321  6345  6345 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-19 17:55:21.321  6345  6345 I bluedroid-qcom: get_profile_interface avrcp
08-19 17:55:21.323  1029  1883 W Process : Unable to open /proc/6488/status
08-19 17:55:21.331  6345  6345 V AudioManager: registerRemoteController: size of Media player list: 0
08-19 17:55:21.335  6345  6345 E AudioManager: No RCC entry present to update
,08-19 17:55:21.335  6345  6345 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-19 17:55:21.339  6345  6345 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-19 17:55:21.340  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-19 17:55:21.340  6345  6345 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-19 17:55:21.346  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-19 17:55:21.480  1029  1783 V SIM_STK : Menu title from STK is T-Mobile
08-19 17:55:21.480  1029  1783 V SIM_STK : Menu title from STK is T-Mobile
,08-19 17:55:21.591  1029  1947 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-19 17:55:21.600  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-19 17:55:21.605  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-19 17:55:21.606  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-19 17:55:21.606  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-19 17:55:21.606  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-19 17:55:21.606  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-19 17:55:21.606  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-19 17:55:21.606  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-19 17:55:21.606  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-19 17:55:21.606  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-19 17:55:21.606  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-19 17:55:21.606  6345  6345 I BluetoothA2dpServiceJni: classInitNative
08-19 17:55:21.607  6345  6345 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-19 17:55:21.607  6345  6345 D A2dpStateMachine: make
08-19 17:55:21.608  6345  6345 I bluedroid-qcom: get_profile_interface a2dp
08-19 17:55:21.609  6345  6496 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-19 17:55:21.617  6345  6345 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-19 17:55:21.618  6345  6345 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-19 17:55:21.618  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
,08-19 17:55:21.621  6345  6345 I BluetoothHidServiceJni: classInitNative: succeeds
08-19 17:55:21.623  6345  6495 D A2dpStateMachine: Enter Disconnected: -2
08-19 17:55:21.623  6345  6345 D HidService: Received start request. Starting profile...
08-19 17:55:21.623  6345  6345 I bluedroid-qcom: get_profile_interface hidhost
08-19 17:55:21.623  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:21.623  6345  6345 I BluetoothHealthServiceJni: classInitNative: succeeds
08-19 17:55:21.624  6345  6345 D HealthService: Received start request. Starting profile...
08-19 17:55:21.626  6345  6345 I bluedroid-qcom: get_profile_interface health
08-19 17:55:21.626  6345  6345 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-19 17:55:21.626  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:21.627  6345  6345 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-19 17:55:21.628  6345  6345 D PanService: Received start request. Starting profile...
08-19 17:55:21.628  6345  6345 D BluetoothPanServiceJni: initializeNative(L110): pan
08-19 17:55:21.628  6345  6345 I bluedroid-qcom: get_profile_interface pan
,08-19 17:55:21.636  6345  6345 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-19 17:55:21.636  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:21.639  6345  6345 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-19 17:55:21.649  6345  6345 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-19 17:55:21.651  6345  6345 D BtGatt.GattService: Received start request. Starting profile...
08-19 17:55:21.651  6345  6345 D BtGatt.GattService: start()
08-19 17:55:21.651  6345  6345 I bluedroid-qcom: get_profile_interface gatt
08-19 17:55:21.652  6345  6345 D BtGatt.AdvertiseManager: advertise manager created
08-19 17:55:21.661  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
,08-19 17:55:21.664  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:21.664  6345  6345 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-19 17:55:21.665  6345  6345 V BluetoothMapService: BluetoothMapBinder()
08-19 17:55:21.666  6345  6345 D BluetoothMapService: Received start request. Starting profile...
08-19 17:55:21.666  6345  6345 D BluetoothMapService: start()
08-19 17:55:21.669  6345  6345 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-19 17:55:21.670  6345  6345 D BluetoothMapEmailAppObserver: createReceiver()
08-19 17:55:21.671  6345  6345 D BluetoothMapEmailAppObserver: initObservers()
08-19 17:55:21.672  6345  6345 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-19 17:55:21.681  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
,08-19 17:55:21.681  6345  6345 D HeadsetStateMachine: Proxy object connected
08-19 17:55:21.682  6345  6345 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-19 17:55:21.682  6345  6345 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-19 17:55:21.687  6345  6345 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-19 17:55:21.689  6345  6486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-19 17:55:21.689  6345  6486 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-19 17:55:21.690  6345  6486 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-19 17:55:21.693  6345  6345 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-19 17:55:21.696  6345  6345 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-19 17:55:21.698  6345  6345 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:21.704  6345  6345 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-19 17:55:21.705  6345  6345 V PanService: [BTUI] SIM Extra State :ABSENT
,08-19 17:55:21.714  6345  6345 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-19 17:55:21.718  6345  6345 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-19 17:55:21.718  6345  6345 V BluetoothMapService: Handler(): got msg=1
,08-19 17:55:21.719  6345  6465 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-19 17:55:21.719  6345  6465 I bluedroid-qcom: enable
08-19 17:55:21.719  6345  6465 I bt_hci_bdroid: init
08-19 17:55:21.721  6345  6345 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-19 17:55:21.721  6345  6345 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-19 17:55:21.721  6345  6345 V BluetoothSapReceiver: SapReceiver onReceive 
08-19 17:55:21.721  6345  6345 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:21.721  6345  6345 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-19 17:55:21.723  6345  6465 I bt_vendor: bt-vendor : init
08-19 17:55:21.723  6345  6465 I bt_vendor: bt-vendor : get_bt_soc_type
08-19 17:55:21.723  6345  6465 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-19 17:55:21.723  6345  6465 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-19 17:55:21.723  6345  6465 D bt_userial_mct: userial_init
08-19 17:55:21.729  6345  6465 D bt_hci_bdroid: set_power 1
08-19 17:55:21.729  6345  6465 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-19 17:55:21.729  6345  6506 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-19 17:55:21.729  6345  6465 I bt_vendor: Starting hciattach daemon
,08-19 17:55:21.729  6345  6506 I bt-btu  : btu_task pending for preload complete event
08-19 17:55:21.729  6345  6465 I bt_vendor: try to set true
08-19 17:55:21.724  6509  6509 W sh      : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:21.724  6509  6509 W sh      : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:21.768  6510  6510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-19 17:55:21.845  6516  6516 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-19 17:55:21.872  6517  6517 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-19 17:55:21.903  6519  6519 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-19 17:55:21.916  6520  6520 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-19 17:55:21.929  6521  6521 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-19 17:55:21.955  6522  6522 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-19 17:55:21.982  6525  6525 I libmdmdetect: ESOC framework not supported
,08-19 17:55:21.983  6525  6525 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-19 17:55:21.991  6525  6525 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-19 17:55:21.991  6525  6525 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-19 17:55:21.991  6525  6525 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-19 17:55:21.991  6525  6525 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-19 17:55:21.991  6525  6525 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-19 17:55:21.991  6525  6525 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-19 17:55:21.991  6525  6525 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-19 17:55:22.031  6525  6526 E QC-QMI  : qmi_client [6525] 14: failed to locate client data
08-19 17:55:22.032   475   475 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-19 17:55:22.032   475   475 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-19 17:55:22.079  6527  6527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-19 17:55:22.104  6528  6528 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-19 17:55:22.136  6345  6465 I bt_vendor: bluetooth satus is on
,08-19 17:55:22.136  6345  6465 D bt_hci_bdroid: preload
08-19 17:55:22.136  6345  6508 D bt_userial_mct: userial_open(port:0)
08-19 17:55:22.136  6345  6508 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-19 17:55:22.141  6345  6508 I bt_vendor: Done intiailizing UART
08-19 17:55:22.145  6345  6508 I bt_vendor: Done intiailizing UART
08-19 17:55:22.145  6345  6508 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-19 17:55:22.145  6345  6508 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-19 17:55:22.145  6345  6530 D bt_userial_mct: Entering userial_read_thread()
08-19 17:55:22.145  6345  6506 I bt-btu  : btu_task received preload complete event
08-19 17:55:22.146  6345  6506 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-19 17:55:22.146  6345  6506 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-19 17:55:22.150  6345  6506 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_HCI
,08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_A2D
08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_BNEP
08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_BTM
,08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_GAP
08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_PAN
,08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_SDP
08-19 17:55:22.157  6345  6506 I         : BTE_InitTraceLevels -- TRC_GATT
08-19 17:55:22.158  6345  6506 I         : BTE_InitTraceLevels -- TRC_SMP
08-19 17:55:22.158  6345  6506 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-19 17:55:22.158  6345  6506 I         : BTE_InitTraceLevels -- TRC_BTIF
08-19 17:55:22.257  6345  6506 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-19 17:55:22.257  6345  6506 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016c061 
08-19 17:55:22.257  6345  6506 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016c061 
,08-19 17:55:22.291  6345  6469 E bt-btif : Calling BTA_HhEnable
08-19 17:55:22.291  6345  6469 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-19 17:55:22.291  6345  6469 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-19 17:55:22.295  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-19 17:55:22.295  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
08-19 17:55:22.296  6345  6469 D BluetoothAdapterProperties: Name is: G3
08-19 17:55:22.297  6345  6469 D BluetoothAdapterProperties: Scan Mode:20
08-19 17:55:22.297  6345  6469 D BluetoothAdapterProperties: Discoverable Timeout:120
08-19 17:55:22.297  6345  6469 D bt_hci_bdroid: postload
08-19 17:55:22.298  6345  6469 D bte_conf: Device ID record 1 : primary
08-19 17:55:22.298  6345  6469 D bte_conf:   vendorId            = 00c4
08-19 17:55:22.298  6345  6469 D bte_conf:   vendorIdSource      = 0001
,08-19 17:55:22.298  6345  6469 D bte_conf:   product             = 13a1
08-19 17:55:22.298  6345  6469 D bte_conf:   version             = 1000
08-19 17:55:22.299  6345  6469 D bte_conf:   clientExecutableURL = 
08-19 17:55:22.299  6345  6469 D bte_conf:   serviceDescription  = 
08-19 17:55:22.299  6345  6469 D bte_conf:   documentationURL    = 
08-19 17:55:22.299  6345  6508 D bt_hci_bdroid: Used up Tx Cmd credits
08-19 17:55:22.299  6345  6469 D bte_conf: bte_load_did_conf no section named DID2.
08-19 17:55:22.302  6345  6465 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-19 17:55:22.302  6345  6465 D BluetoothAdapterProperties: ScanMode =  20
,08-19 17:55:22.307  6345  6465 D BluetoothAdapterProperties: State =  11
08-19 17:55:22.307  6345  6465 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-19 17:55:22.308  6345  6465 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-19 17:55:22.309  6345  6465 D BluetoothAdapterProperties: Setting state to 12
08-19 17:55:22.309  6345  6465 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-19 17:55:22.309  6345  6469 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-19 17:55:22.294  6535  6535 W sh      : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:22.294  6535  6535 W sh      : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:22.317  1029  1091 D BluetoothManagerService: Message: 60
08-19 17:55:22.317  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-19 17:55:22.317  1029  1091 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-19 17:55:22.325  6345  6508 D bt_hci_bdroid: Used up Tx Cmd credits
08-19 17:55:22.330  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:22.330  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:22.330  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:22.330  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:22.330  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:22.330  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:22.330  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:22.330  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:22.334  6345  6465 I BluetoothAdapterState: Entering On State
08-19 17:55:22.342  6345  6530 E bt_mct  : hci lib postload completed
,08-19 17:55:22.347  6345  6469 D BluetoothAdapterProperties: Discoverable Timeout:120
08-19 17:55:22.347  6345  6469 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-19 17:55:22.354  5974  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:22.364  6345  6465 D LGBluetoothServiceAdapter: [BTUI] OnState
08-19 17:55:22.364  6345  6465 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-19 17:55:22.364  6345  6465 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-19 17:55:22.365  6345  6465 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-19 17:55:22.371  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:22.371  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:22.371  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:22.371  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:22.371  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:22.371  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:22.371  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:22.371  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:22.382  6345  6465 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-19 17:55:22.384  5974  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:22.386  6345  6506 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-19 17:55:22.386  6345  6506 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-19 17:55:22.386  6345  6506 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-19 17:55:22.387  6345  6506 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-19 17:55:22.387  6345  6506 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-19 17:55:22.387  6345  6506 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-19 17:55:22.387  6345  6469 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-19 17:55:22.388  6223  6238 D BluetoothMap: onBluetoothStateChange: up=true
08-19 17:55:22.414  1849  4306 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-19 17:55:22.426  6345  6506 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-19 17:55:22.426  6345  6506 W bt-smp  : Plain text(LSB ~ MSB) = 14 d7 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-19 17:55:22.426  6345  6506 W bt-smp  : Encrypted text(LSB ~ MSB) = ca 41 de e1 40 1c dc eb 94 57 5d 97 b5 54 65 fe 
,08-19 17:55:22.428  6345  6506 W bt-btm  : Stopping oneshot timer
08-19 17:55:22.429  1849  1849 D BluetoothHeadset: Proxy object connected
08-19 17:55:22.430  6223  6239 D BluetoothPan: onBluetoothStateChange on: true
08-19 17:55:22.430  6223  6239 D BluetoothPan: onBluetoothStateChange call bindService
08-19 17:55:22.434  6541  6541 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-19 17:55:22.443  1029  1091 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-19 17:55:22.448  1029  1091 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:55:22.449  1029  1029 D BluetoothHeadset: Proxy object connected
08-19 17:55:22.452  1029  1029 D BluetoothA2dp: Proxy object connected
,08-19 17:55:22.456  1849  4302 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-19 17:55:22.461  6345  6506 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-19 17:55:22.461  6345  6506 W bt-smp  : Plain text(LSB ~ MSB) = 5e 67 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-19 17:55:22.461  6345  6506 W bt-smp  : Encrypted text(LSB ~ MSB) = c3 c4 fa 24 62 3c 51 19 ed 02 8a 11 80 f1 3a 8c 
08-19 17:55:22.462  6345  6506 W bt-btm  : Stopping oneshot timer
08-19 17:55:22.463  6223  6223 D BluetoothMap: Proxy object connected
08-19 17:55:22.463  6223  6223 D MapProfile: Bluetooth service connected
08-19 17:55:22.463  6223  6223 D BluetoothMap: getConnectedDevices()
08-19 17:55:22.465  1849  1849 D BluetoothHeadset: Proxy object connected
08-19 17:55:22.465  6223  6238 D BluetoothPbap: onBluetoothStateChange: up=true
08-19 17:55:22.467  6345  6360 V BluetoothMapService: getConnectedDevices()
08-19 17:55:22.468  1849  2527 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-19 17:55:22.470  1849  1849 D BluetoothHeadset: Proxy object connected
08-19 17:55:22.471  6223  6540 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-19 17:55:22.471  6223  6223 D BluetoothPan: BluetoothPAN Proxy object connected
08-19 17:55:22.472  6223  6223 D PanProfile: Bluetooth service connected
08-19 17:55:22.475  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-19 17:55:22.475  6223  6223 D BluetoothInputDevice: Proxy object connected
08-19 17:55:22.475  6223  6223 D HidProfile: Bluetooth service connected
08-19 17:55:22.476  1029  1091 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-19 17:55:22.476  1029  1091 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-19 17:55:22.476  6345  6506 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-19 17:55:22.476  6345  6506 W bt-smp  : Plain text(LSB ~ MSB) = 24 fe 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-19 17:55:22.476  6345  6506 W bt-smp  : Encrypted text(LSB ~ MSB) = 97 08 4c 87 9b a6 88 cb 48 08 bf b4 db ca 52 a6 
08-19 17:55:22.476  6345  6506 W bt-btm  : Stopping oneshot timer
08-19 17:55:22.477  1029  1091 D BluetoothManagerService: Message: 40
08-19 17:55:22.477  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-19 17:55:22.478  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:22.478  1937  2116 D LGBluetoothAPIService: Message: 1
08-19 17:55:22.478  1937  2116 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-19 17:55:22.479  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-19 17:55:22.484  5974  5974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-19 17:55:22.485  6345  6506 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-19 17:55:22.485  6345  6506 W bt-smp  : Plain text(LSB ~ MSB) = 27 31 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-19 17:55:22.485  6345  6506 W bt-smp  : Encrypted text(LSB ~ MSB) = ed f2 51 52 94 d3 9e 0a ce cf e2 13 e0 b7 c3 c2 
08-19 17:55:22.485  6345  6506 W bt-btm  : Stopping oneshot timer
,08-19 17:55:22.487  6345  6345 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:22.487  6345  6345 D BluetoothMapService: STATE_ON
08-19 17:55:22.487  1937  2116 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-19 17:55:22.488  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:22.489  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:22.490  6345  6345 D LGBluetoothAPIServer: [BTUI] onCreate()
08-19 17:55:22.490  6345  6345 D LGBluetoothAPIServer: [BTUI] onBind()
08-19 17:55:22.491  1937  1937 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-19 17:55:22.491  6223  6223 D LocalBluetoothProfileManager: Adding local A2DP profile
08-19 17:55:22.491  1937  2116 D LGBluetoothAPIService: Message: 100
08-19 17:55:22.491  1937  2116 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-19 17:55:22.493  1029  1091 D BluetoothManagerService: Message: 30
08-19 17:55:22.495  6345  6506 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-19 17:55:22.495  6345  6506 W bt-smp  : Plain text(LSB ~ MSB) = 89 36 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-19 17:55:22.495  6345  6506 W bt-smp  : Encrypted text(LSB ~ MSB) = 77 b5 cb 5a e3 d1 eb 03 0e 9c b9 3f 1f c7 58 0b 
08-19 17:55:22.495  6345  6506 W bt-btm  : Stopping oneshot timer
08-19 17:55:22.497  6223  6223 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-19 17:55:22.499  1029  1091 D BluetoothManagerService: Message: 30
,08-19 17:55:22.505  6223  6223 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-19 17:55:22.506  6223  6223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-19 17:55:22.508  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:22.508  6345  6345 V BluetoothPbapService: Pbap Service onCreate
08-19 17:55:22.508  6345  6345 V BluetoothPbapService: Starting PBAP service
08-19 17:55:22.510  6345  6345 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-19 17:55:22.510  6345  6345 V BluetoothPbapService: Pbap Service onBind
,08-19 17:55:22.511  6223  6223 D BluetoothA2dp: Proxy object connected
08-19 17:55:22.512  6223  6223 D A2dpProfile: Bluetooth service connected
08-19 17:55:22.514  6345  6345 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:22.514  6345  6345 V BluetoothPbapService: state: 12
08-19 17:55:22.514  6345  6345 V BluetoothMapService: Handler(): got msg=1
08-19 17:55:22.514  6345  6345 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-19 17:55:22.514  6345  6345 V BluetoothPbapService: Handler(): got msg=1
08-19 17:55:22.515  6345  6345 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-19 17:55:22.515  6223  6223 D BluetoothHeadset: Proxy object connected
08-19 17:55:22.516  6345  6561 D BluetoothMapMasInstance: MAS initSocket()
08-19 17:55:22.516  6345  6345 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-19 17:55:22.516  6345  6345 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:22.516  6345  6345 V BluetoothPbapReceiver: ***********state = 12
08-19 17:55:22.516  6345  6561 D BluetoothMapMasInstance:   masId = 00
08-19 17:55:22.516  6345  6561 D BluetoothMapMasInstance:   msgTypes = 0e
08-19 17:55:22.516  6345  6561 D BluetoothMapMasInstance:   masName = SMS/MMS
08-19 17:55:22.516  6345  6561 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-19 17:55:22.516  6223  6223 D HeadsetProfile: Bluetooth service connected
08-19 17:55:22.518  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-19 17:55:22.519  1029  1783 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:22.519  2177  2177 D c       : Getting all permits...
08-19 17:55:22.519  2177  2177 D a       : Opening database...
08-19 17:55:22.520  6345  6562 V BluetoothPbapService: Pbap Service initSocket
08-19 17:55:22.521  1029  1783 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:22.521  2177  2177 D a       : Opening database auth.proximity.permit_store...
,08-19 17:55:22.521  6345  6561 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:22.522  2177  2177 D a       : Closing database...
,08-19 17:55:22.524  6345  6561 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-19 17:55:22.525  6345  6561 V BluetoothMapMasInstance: Succeed to create listening socket 
08-19 17:55:22.525  6345  6561 D BluetoothMapMasInstance: Accepting socket connection...
08-19 17:55:22.526  6345  6562 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:22.527  6345  6562 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-19 17:55:22.528  6345  6562 V BluetoothPbapService: Succeed to create listening socket 
08-19 17:55:22.528  6345  6562 V BluetoothPbapService: Accepting socket connection...
08-19 17:55:22.530  6345  6469 D BluetoothAdapterProperties: Scan Mode:21
08-19 17:55:22.530  6345  6469 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-19 17:55:22.533  6223  6223 D DockEventReceiver: finishStartingService: stopping service
08-19 17:55:22.533  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:22.535  6223  6223 D BluetoothPbap: Proxy object connected
08-19 17:55:22.536  6223  6223 D PbapServerProfile: Bluetooth service connected
08-19 17:55:22.536  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:22.540  6223  6223 D BluetoothPermissionRequest: onReceive
08-19 17:55:22.542  6223  6223 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-19 17:55:22.543  6223  6223 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-19 17:55:22.546  6345  6345 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-19 17:55:22.549  6345  6345 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-19 17:55:22.554  6345  6345 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-19 17:55:22.572  6345  6345 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-19 17:55:22.573  6345  6345 V BtOppService: onCreate
,08-19 17:55:22.577  6345  6345 V BluetoothOppNotification: send message
08-19 17:55:22.580  6345  6345 V BtOppService: Starting RfcommListener
08-19 17:55:22.588  6345  6345 D BluetoothOppPreference: Dumping Names:  
,08-19 17:55:22.588  6345  6345 D BluetoothOppPreference: {}
08-19 17:55:22.588  6345  6345 D BluetoothOppPreference: Dumping Channels:  
08-19 17:55:22.588  6345  6345 D BluetoothOppPreference: {}
08-19 17:55:22.590  6345  6345 V BtOppService: onStartCommand
08-19 17:55:22.591  6345  6569 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-19 17:55:22.591  6345  6569 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-19 17:55:22.593  6345  6569 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@111fea39 on behalf of 
08-19 17:55:22.596  6345  6345 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:22.596  6345  6345 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-19 17:55:22.597  6345  6566 V BtOppService: Deleted complete outbound shares, number =  0
08-19 17:55:22.599  6345  6566 V BtOppService: Deleted complete inbound failed shares, number = 0
08-19 17:55:22.600  6345  6566 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-19 17:55:22.600  6345  6569 V BluetoothOppNotification: update too frequent, put in queue
,08-19 17:55:22.601  6345  6566 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@250a487e on behalf of 
08-19 17:55:22.602  6345  6345 V BluetoothOppNotification: new notify threadi!
08-19 17:55:22.604  6345  6569 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-19 17:55:22.604  6345  6345 V BluetoothOppNotification: send delay message
08-19 17:55:22.604  6345  6569 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-19 17:55:22.604  6345  6345 V BtOppService: start RfcommListener
08-19 17:55:22.609  6345  6345 V BtOppService: RfcommListener started
08-19 17:55:22.609  6345  6345 V BtOppService: ContentObserver received notification
08-19 17:55:22.609  6345  6345 V BtOppService: ContentObserver received notification
08-19 17:55:22.610  6345  6571 V BtOppRfcommListener: Starting RFCOMM listener....
08-19 17:55:22.610  1029  1911 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:22.611  6345  6571 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:22.612  6345  6570 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-19 17:55:22.612  6345  6571 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
,08-19 17:55:22.612  6345  6571 V BtOppRfcommListener: Started RFCOMM listener....
08-19 17:55:22.612  6345  6571 I BtOppRfcommListener: Accept thread started.
08-19 17:55:22.612  6345  6571 V BtOppRfcommListener: Accepting connection...
08-19 17:55:22.616  6345  6570 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36eb71df on behalf of 
08-19 17:55:22.617  6345  6570 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-19 17:55:22.618  6345  6569 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@106b9e2c on behalf of 
08-19 17:55:22.619  6345  6569 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-19 17:55:22.619  6345  6569 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-19 17:55:22.619  6345  6570 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-19 17:55:22.620  6345  6569 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a0bf0f5 on behalf of 
08-19 17:55:22.620  6345  6569 V BluetoothOppNotification: update too frequent, put in queue
08-19 17:55:22.621  6345  6570 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3cfe6e8a on behalf of 
08-19 17:55:22.621  6345  6569 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-19 17:55:22.622  6345  6570 V BluetoothOppNotification: outbound: succ-0  fail-0
08-19 17:55:22.624  6345  6570 V BluetoothOppNotification: outbound notification was removed.
08-19 17:55:22.624  6345  6570 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-19 17:55:22.627  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:22.627  6345  6345 V BluetoothFtpService: Ftp Service onCreate
08-19 17:55:22.627  6345  6345 I BluetoothFtpService: Ftp Service onCreate
08-19 17:55:22.627  6345  6345 V BluetoothFtpService: Ftp Service onStartCommand
08-19 17:55:22.627  6345  6345 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:22.628  6345  6345 V BluetoothFtpService: Starting Listening on sockets
08-19 17:55:22.628  6345  6570 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e0a7118 on behalf of 
08-19 17:55:22.628  6345  6345 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-19 17:55:22.628  6345  6345 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-19 17:55:22.628  6345  6345 V BluetoothSapReceiver: SapReceiver onReceive 
08-19 17:55:22.628  6345  6345 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:22.628  6345  6345 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-19 17:55:22.628  6345  6345 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-19 17:55:22.630  6345  6570 V BluetoothOppNotification: inbound: succ-0  fail-0
08-19 17:55:22.630  6345  6345 V BluetoothFtpService: Handler(): got msg=1
08-19 17:55:22.631  6345  6345 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-19 17:55:22.631  6345  6345 V BluetoothFtpService: Ftp Service initSocket
08-19 17:55:22.634  6345  6570 V BluetoothOppNotification: inbound notification was removed.
08-19 17:55:22.634  6345  6570 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-19 17:55:22.635  6345  6570 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1977a771 on behalf of 
08-19 17:55:22.636  1029  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-19 17:55:22.638  6345  6345 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:22.639  6345  6345 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-19 17:55:22.640  6345  6345 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-19 17:55:22.642  6345  6572 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-19 17:55:22.656  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
,08-19 17:55:22.656  6345  6345 V BluetoothSapService: Sap Service onCreate
,08-19 17:55:22.658  6345  6345 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:22.658  6345  6345 V BluetoothSapService: state: 12
08-19 17:55:22.659  6345  6345 V BluetoothSapService: Starting SAP server process
08-19 17:55:22.644  6573  6573 W sapd    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:22.662  6345  6345 V BluetoothSapService: SAP Service startRfcommListenerThread
08-19 17:55:22.644  6573  6573 W sapd    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:22.664  6345  6574 V BluetoothSapService: Sap Service initRfcommSocket
08-19 17:55:22.665  1029  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:22.666  6345  6574 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:22.667  6345  6574 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-19 17:55:22.667  6345  6574 V BluetoothSapService: Succeed to create listening socket 
08-19 17:55:22.667  6345  6574 V BluetoothSapService: Accepting socket connection...
08-19 17:55:22.674  6573  6573 V BT_SAP  : Event pipe created
08-19 17:55:22.674  6573  6573 V BT_SAP  : create_server_socket qcom.sap.server
08-19 17:55:22.674  6573  6573 V BT_SAP  : created socket fd 6
,08-19 17:55:23.065  1029  1533 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-19 17:55:23.065  1029  1533 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-19 17:55:23.108  1029  1534 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-19 17:55:23.110  1029  1534 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-19 17:55:23.605  6345  6345 V BluetoothOppNotification: new notify threadi!
,08-19 17:55:23.606  6345  6345 V BluetoothOppNotification: send delay message
,08-19 17:55:23.617  6345  6584 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-19 17:55:23.620  6345  6584 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e0e49ad on behalf of 
08-19 17:55:23.627  6345  6584 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-19 17:55:23.634  6345  6584 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-19 17:55:23.636  6345  6584 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f5644e2 on behalf of 
08-19 17:55:23.637  6345  6584 V BluetoothOppNotification: outbound: succ-0  fail-0
08-19 17:55:23.639  6345  6584 V BluetoothOppNotification: outbound notification was removed.
08-19 17:55:23.640  6345  6584 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-19 17:55:23.641  6345  6584 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39846073 on behalf of 
08-19 17:55:23.641  6345  6584 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-19 17:55:23.645  6345  6584 V BluetoothOppNotification: inbound notification was removed.
,08-19 17:55:23.645  6345  6584 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-19 17:55:23.647  6345  6584 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1eb24b30 on behalf of 
,08-19 17:55:24.116  1029  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-19 17:55:24.116  1029  1982 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@321ae292 mBinding = false
,08-19 17:55:24.155  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-19 17:55:24.156  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-19 17:55:24.156  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-19 17:55:24.157  1029  1091 D BluetoothManagerService: Message: 2
08-19 17:55:24.159  1029  1091 D BluetoothManagerService: Sending off request.
08-19 17:55:24.160  6345  6360 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-19 17:55:24.161  6345  6465 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-19 17:55:24.161  6345  6465 D BluetoothAdapterProperties: Setting state to 13
08-19 17:55:24.161  6345  6465 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-19 17:55:24.162  6345  6465 D BluetoothAdapterProperties: onBluetoothDisable()
08-19 17:55:24.162  6345  6465 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-19 17:55:24.164  6345  6469 D BluetoothAdapterProperties: Scan Mode:20
,08-19 17:55:24.170  6345  6465 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-19 17:55:24.171  6345  6465 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-19 17:55:24.173  6345  6562 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:55:24.174  6345  6571 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:55:24.174  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-19 17:55:24.174  6345  6506 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-19 17:55:24.175  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-19 17:55:24.175  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-19 17:55:24.175  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-19 17:55:24.175  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-19 17:55:24.175  6345  6506 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:24.175  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-19 17:55:24.175  6345  6506 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:24.175  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-19 17:55:24.175  6345  6506 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:24.175  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-19 17:55:24.175  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-19 17:55:24.175  6345  6506 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-19 17:55:24.177  6345  6561 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-19 17:55:24.177  6345  6561 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:55:24.177  6345  6561 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-19 17:55:24.177  6345  6561 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-19 17:55:24.177  6345  6561 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-19 17:55:24.177  6345  6561 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-19 17:55:24.177  6345  6561 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-19 17:55:24.177  6345  6561 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-19 17:55:24.183  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:24.183  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:24.183  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:24.183  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:24.183  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:24.183  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:24.183  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:24.183  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:24.183  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:24.189  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:24.189  5974  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:24.195  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:24.197  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:24.197  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:24.197  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:24.197  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:24.197  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:24.197  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:24.197  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:24.197  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:24.197  5974  5974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:24.197  5974  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:24.201  1029  1091 D BluetoothManagerService: Message: 60
08-19 17:55:24.201  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-19 17:55:24.201  1029  1091 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-19 17:55:24.206  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:24.208  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-19 17:55:24.214  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:24.217  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:24.219  6345  6345 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:24.219  6345  6345 D BluetoothMapService: STATE_TURNING_OFF
08-19 17:55:24.219  6345  6345 V BluetoothMapService: Handler(): got msg=4
08-19 17:55:24.219  6345  6345 D BluetoothMapService: MAP Service closeService in
08-19 17:55:24.219  6345  6345 D BluetoothMapMasInstance: MAP Service shutdown
08-19 17:55:24.220  6345  6345 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-19 17:55:24.220  6345  6345 V BluetoothMapService: MAP Service closeService out
08-19 17:55:24.221  6345  6345 V BtOppService: Receiver DISABLED_ACTION 
08-19 17:55:24.222  6345  6345 I BtOppRfcommListener: stopping Accept Thread
08-19 17:55:24.222  6345  6345 V BtOppRfcommListener: close mBtServerSocket
08-19 17:55:24.222  6345  6571 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-19 17:55:24.223  6345  6345 V BtOppRfcommListener: waiting for thread to terminate
08-19 17:55:24.223  6345  6345 V BtOppRfcommListener: done waiting for thread to terminate
08-19 17:55:24.226  6223  6223 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-19 17:55:24.232  6345  6572 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:55:24.236  6345  6574 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:55:24.242  6223  6223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-19 17:55:24.245  6345  6345 V BtOppService: onDestroy
08-19 17:55:24.247  6345  6345 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-19 17:55:24.252  6345  6345 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-19 17:55:24.252  6345  6345 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:24.252  6345  6345 V BluetoothPbapReceiver: ***********state = 13
08-19 17:55:24.254  6345  6345 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-19 17:55:24.259  6345  6345 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:24.259  6345  6345 V BluetoothPbapService: state: 13
08-19 17:55:24.259  6345  6345 V BluetoothPbapService: Pbap Service closeService in
08-19 17:55:24.263  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-19 17:55:24.264  6345  6345 V BluetoothPbapService: successfully stopped pbap service
08-19 17:55:24.264  6345  6345 V BluetoothPbapService: Pbap Service closeService out
08-19 17:55:24.265  6345  6345 V BluetoothPbapService: Pbap Service onDestroy
08-19 17:55:24.265  6345  6345 V BluetoothPbapService: Pbap Service closeService in
08-19 17:55:24.265  6345  6345 V BluetoothPbapService: Pbap Service closeService out
08-19 17:55:24.265  6345  6345 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-19 17:55:24.287  6223  6223 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:24.289  6223  6223 D BluetoothPbap: Proxy object disconnected
08-19 17:55:24.289  6223  6223 D PbapServerProfile: Bluetooth service disconnected
08-19 17:55:24.294  6223  6223 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-19 17:55:24.298  6223  6223 D BluetoothPermissionRequest: onReceive
08-19 17:55:24.298  6223  6223 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-19 17:55:24.308  6223  6223 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-19 17:55:24.312  6345  6345 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-19 17:55:24.312  6345  6345 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-19 17:55:24.313  6345  6345 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-19 17:55:24.318  6345  6345 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:24.318  6345  6345 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-19 17:55:24.319  6345  6345 V BluetoothFtpService: Ftp Service onStartCommand
08-19 17:55:24.319  6345  6345 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:24.320  6345  6345 V BluetoothFtpService: Ftp Service closeService
08-19 17:55:24.320  6345  6345 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-19 17:55:24.323  6345  6345 V BluetoothFtpService: successfully stopped ftp service
08-19 17:55:24.323  6345  6345 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-19 17:55:24.324  6345  6345 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-19 17:55:24.324  6345  6345 V BluetoothSapReceiver: SapReceiver onReceive 
08-19 17:55:24.324  6345  6345 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:24.324  6345  6345 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-19 17:55:24.324  6345  6345 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-19 17:55:24.328  6345  6345 V BluetoothFtpService: Ftp Service onDestroy
08-19 17:55:24.328  6345  6345 V BluetoothFtpService: Ftp Service closeService
08-19 17:55:24.334  6345  6345 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:24.334  6345  6345 V BluetoothSapService: state: 13
08-19 17:55:24.334  6345  6345 V BluetoothSapService: Stopping SAP server process
08-19 17:55:24.336  6345  6345 V BluetoothSapService: Sap Service closeSapService in
08-19 17:55:24.336  6345  6345 V BluetoothSapService: Close listen Socket : 
08-19 17:55:24.336  6345  6345 V BluetoothSapService: Close rfcomm Socket : 
08-19 17:55:24.336  6345  6345 V BluetoothSapService: Close sapd  Socket : 
,08-19 17:55:24.338  6345  6345 V BluetoothSapService: Sap Service closeSapService out
08-19 17:55:24.338  6345  6345 V BluetoothSapService: Sap Service onDestroy
08-19 17:55:24.338  6345  6345 V BluetoothSapService: Sap Service closeSapService in
08-19 17:55:24.338  6345  6345 V BluetoothSapService: Close listen Socket : 
08-19 17:55:24.338  6345  6345 V BluetoothSapService: Close rfcomm Socket : 
08-19 17:55:24.338  6345  6345 V BluetoothSapService: Close sapd  Socket : 
08-19 17:55:24.339  6345  6345 V BluetoothSapService: Sap Service closeSapService out
,08-19 17:55:25.162  6345  6469 D bt_hci_bdroid: cleanup
,08-19 17:55:25.167  6345  6508 I bt_lpm  : LPM is already off!!!
08-19 17:55:25.168  6345  6530 I bt_userial_mct: exiting userial_read_thread
08-19 17:55:25.168  6345  6530 D bt_userial_mct: Leaving userial_evt_read_thread()
08-19 17:55:25.169  6345  6506 W bt-btif : ag scb idx 1 not allocated
08-19 17:55:25.169  6345  6506 E bt-btif : BTA AG is already disabled, ignoring ...
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-19 17:55:25.169  6345  6506 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:25.170  6345  6506 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-19 17:55:25.172  6345  6469 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-19 17:55:25.172  6345  6508 I bt_vendor: hw_epilog_process
08-19 17:55:25.174  6345  6469 D bt_hci_bdroid: cleanup Finalizing cleanup
,08-19 17:55:25.174  6345  6469 D bt_userial_mct: userial_close,
08-19 17:55:25.174  6345  6469 E bt_userial_mct: pthread_join() FAILED result:3
,08-19 17:55:25.174  6345  6469 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0,
,08-19 17:55:25.184  6345  6469 D bt_hci_bdroid: set_power 0
,08-19 17:55:25.184  6345  6469 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
,08-19 17:55:25.184  6345  6469 I bt_vendor: bluetooth satus is on,
,08-19 17:55:25.184  6345  6469 I bt_vendor: bt-vendor : resetting BT status
08-19 17:55:25.184  6345  6469 I bt_vendor: Starting hciattach daemon
08-19 17:55:25.184  6345  6469 I bt_vendor: try to set false,
08-19 17:55:25.198  6345  6469 I bt_vendor: Starting hciattach daemon
,08-19 17:55:25.198  6345  6469 I bt_vendor: try to set false,
,08-19 17:55:25.204  6345  6469 I bt_vendor: cleanup
08-19 17:55:25.207  6345  6506 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-19 17:55:25.208  6345  6469 I GKI_LINUX: GKI_exit_task 0 done
08-19 17:55:25.208  6345  6469 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-19 17:55:25.210  6345  6465 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-19 17:55:25.217  6345  6345 D HeadsetService: Received stop request...Stopping profile...
,08-19 17:55:25.221  6345  6465 D BluetoothAdapterState: Stopping profile services that were post enabled
08-19 17:55:25.222  6345  6345 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-19 17:55:25.222  6345  6345 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-19 17:55:25.222  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:25.223  6345  6486 D HeadsetStateMachine: Exit Disconnected: -1
08-19 17:55:25.226  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-19 17:55:25.226  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-19 17:55:25.226  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-19 17:55:25.227  1029  1029 D BluetoothHeadset: Proxy object disconnected
08-19 17:55:25.227  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-19 17:55:25.228  6345  6345 D A2dpService: Received stop request...Stopping profile...
08-19 17:55:25.228  6345  6495 D A2dpStateMachine: Exit Disconnected: -1
08-19 17:55:25.230  6345  6345 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-19 17:55:25.235  6345  6345 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-19 17:55:25.235  6345  6345 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-19 17:55:25.235  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:25.237  6345  6345 D HidService: Received stop request...Stopping profile...
08-19 17:55:25.237  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:25.239  1029  1029 D BluetoothA2dp: Proxy object disconnected
08-19 17:55:25.239  1029  1029 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-19 17:55:25.239  6345  6345 D HealthService: Received stop request...Stopping profile...
08-19 17:55:25.239  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:25.241  6345  6345 D PanService: Received stop request...Stopping profile...
08-19 17:55:25.242  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:25.243  6345  6345 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-19 17:55:25.246  6345  6345 D BtGatt.GattService: Received stop request...Stopping profile...
08-19 17:55:25.247  6345  6345 D BtGatt.GattService: stop()
08-19 17:55:25.247  6345  6345 D BtGatt.AdvertiseManager: advertise clients cleared
08-19 17:55:25.248  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:25.250  6345  6345 D BluetoothMapService: Received stop request...Stopping profile...
08-19 17:55:25.250  6345  6345 D BluetoothMapService: stop()
08-19 17:55:25.251  6345  6345 D BluetoothMapEmailAppObserver: deinitObservers()
08-19 17:55:25.251  6345  6345 D BluetoothMapEmailAppObserver: removeReceiver()
08-19 17:55:25.251  6345  6345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e643604
08-19 17:55:25.252  6345  6345 V BluetoothMapService: Handler(): got msg=4
08-19 17:55:25.252  6345  6345 D BluetoothMapService: MAP Service closeService in
08-19 17:55:25.253  6345  6345 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-19 17:55:25.253  6345  6345 V BluetoothMapService: MAP Service closeService out
08-19 17:55:25.253  6345  6465 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-19 17:55:25.253  6345  6465 D BluetoothAdapterProperties: Setting state to 10
08-19 17:55:25.253  6345  6465 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-19 17:55:25.254  1029  1091 D BluetoothManagerService: Message: 60
08-19 17:55:25.254  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-19 17:55:25.254  1029  1091 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-19 17:55:25.255  6345  6465 I BluetoothAdapterState: Entering OffState
,08-19 17:55:25.257  6223  6239 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:55:25.261  6345  6345 D HeadsetStateMachine: Unbinding service...
08-19 17:55:25.263  6345  6345 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-19 17:55:25.264  6345  6345 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-19 17:55:25.264  6345  6345 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-19 17:55:25.264  6345  6345 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-19 17:55:25.264  6345  6345 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-19 17:55:25.264  6345  6345 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-19 17:55:25.264  6345  6345 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-19 17:55:25.264  6345  6345 I BluetoothA2dpServiceJni: cleanupNative
08-19 17:55:25.264  6345  6496 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-19 17:55:25.266  6345  6345 I GKI_LINUX: GKI_exit_task 2 done
08-19 17:55:25.266  6345  6345 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-19 17:55:25.266  6345  6345 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-19 17:55:25.267  6345  6345 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-19 17:55:25.267  6345  6345 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-19 17:55:25.269  6345  6345 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-19 17:55:25.269  6345  6345 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-19 17:55:25.270  6345  6345 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-19 17:55:25.270  6345  6345 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-19 17:55:25.273  6345  6345 D BluetoothMapService: cleanup()
08-19 17:55:25.273  6345  6345 D BluetoothMapService: MAP Service closeService in
08-19 17:55:25.273  6345  6345 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-19 17:55:25.273  6345  6345 V BluetoothMapService: MAP Service closeService out
08-19 17:55:25.274  6223  6239 D BluetoothMap: onBluetoothStateChange: up=false
08-19 17:55:25.275  1849  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:55:25.276  6223  6239 D BluetoothPan: onBluetoothStateChange on: false
08-19 17:55:25.276  1029  1091 D BluetoothA2dp: onBluetoothStateChange: up=false
08-19 17:55:25.276  1029  1091 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:55:25.277  1849  2527 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:55:25.277  6223  6239 D BluetoothA2dp: onBluetoothStateChange: up=false
08-19 17:55:25.278  6223  6239 D BluetoothPbap: onBluetoothStateChange: up=false
08-19 17:55:25.278  1849  4306 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-19 17:55:25.281  6223  6239 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-19 17:55:25.283  1029  1091 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-19 17:55:25.283  1029  1091 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-19 17:55:25.285  1029  1091 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-19 17:55:25.285  1029  1091 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-19 17:55:25.285  1029  1091 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@321ae292 mBinding = false
08-19 17:55:25.286  1029  1091 D BluetoothManagerService: Sending unbind request.
08-19 17:55:25.291  6345  6469 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-19 17:55:25.293  6345  6345 I GKI_LINUX: GKI_exit_task 1 done
08-19 17:55:25.293  6345  6345 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-19 17:55:25.294  6345  6345 I BluetoothServiceJni: cleanupNative: return from cleanup
08-19 17:55:25.294  6345  6345 I art     : --- WEIRD: removing null entry 248
08-19 17:55:25.294  6345  6345 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-19 17:55:25.294  6345  6345 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-19 17:55:25.295  6345  6345 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-19 17:55:25.297  1029  1091 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-19 17:55:25.299  6345  6345 I art     : System.exit called, status: 0
08-19 17:55:25.299  6345  6345 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-19 17:55:25.317   322  1377 V AudioFlinger: 6345 died, releasing its sessions
08-19 17:55:25.318   322  1377 V AudioFlinger:  pid 1849 @ 0
08-19 17:55:25.318   322  1377 V AudioFlinger:  pid 3309 @ 1
08-19 17:55:25.318   322  1377 V AudioFlinger:  pid 3309 @ 2
,08-19 17:55:25.321  1937  1937 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-19 17:55:25.322  1937  2116 D LGBluetoothAPIService: Message: 101
08-19 17:55:25.322  1937  2116 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-19 17:55:25.322  1937  2116 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-19 17:55:25.322  1937  2116 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-19 17:55:25.325  6223  6223 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-19 17:55:25.413  1029  1045 I ActivityManager: Process com.android.bluetooth (pid 6345) has died
08-19 17:55:25.414  1029  1045 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-19 17:55:25.414  1029  1045 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-19 17:55:25.421  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:25.422  1937  2116 D LGBluetoothAPIService: Message: 2
08-19 17:55:25.422  1937  2116 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-19 17:55:25.423  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-19 17:55:25.425  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:25.426  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:25.431  6223  6223 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-19 17:55:25.431  6223  6223 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-19 17:55:25.435  6223  6223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-19 17:55:25.438  1599  1599 D BluetoothAdapter: 188806031: getState() :  mService = null. Returning STATE_OFF
08-19 17:55:25.438  1599  1599 D BluetoothAdapter: 188806031: getState() :  mService = null. Returning STATE_OFF
08-19 17:55:25.503  1029  1919 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6634 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-19 17:55:25.504  6223  6223 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:25.523   383   383 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 503us total 24.728ms
,08-19 17:55:25.545   383   383 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 21.082ms
,08-19 17:55:25.567   383   383 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 414us total 21.505ms
,08-19 17:55:25.701  1029  1955 I art     : Explicit concurrent mark sweep GC freed 72865(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.441ms total 145.896ms
,08-19 17:55:25.722  6634  6634 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-19 17:55:25.722  6634  6634 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-19 17:55:25.723  6634  6634 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-19 17:55:25.723  6634  6634 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-19 17:55:25.742  6634  6634 D BluetoothAdapterApp: Loading JNI Library
,08-19 17:55:25.779  6634  6634 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2f5ca56c Instance Count = 1
,08-19 17:55:25.785  6634  6634 D BluetoothAdapterApp: onCreate
08-19 17:55:25.810  6634  6634 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-19 17:55:25.810  6634  6634 D ProfileConfigQcom: Adding HeadsetService
08-19 17:55:25.810  6634  6634 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-19 17:55:25.810  6634  6634 D ProfileConfigQcom: Adding A2dpService
08-19 17:55:25.811  6634  6634 D ProfileConfigQcom: [BTUI] HidService is supported
08-19 17:55:25.811  6634  6634 D ProfileConfigQcom: Adding HidService
08-19 17:55:25.811  6634  6634 D ProfileConfigQcom: [BTUI] HealthService is supported
08-19 17:55:25.811  6634  6634 D ProfileConfigQcom: Adding HealthService
08-19 17:55:25.812  6634  6634 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-19 17:55:25.813  6634  6634 D ProfileConfigQcom: [BTUI] PanService is supported
,08-19 17:55:25.814  6634  6634 D ProfileConfigQcom: Adding PanService
08-19 17:55:25.815  6634  6634 D ProfileConfigQcom: [BTUI] GattService is supported
08-19 17:55:25.815  6634  6634 D ProfileConfigQcom: Adding GattService
08-19 17:55:25.816  6634  6634 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-19 17:55:25.817  6634  6634 D ProfileConfigQcom: Adding BluetoothMapService
08-19 17:55:25.818  6634  6634 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-19 17:55:25.820  6634  6634 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-19 17:55:25.822  6634  6634 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:25.824  6634  6634 V BluetoothPbapReceiver: ***********state = 10
,08-19 17:55:25.831  6634  6634 V LGMDMManagerInternal: Create singleton instance
08-19 17:55:25.916  6634  6634 D LGBluetoothAPIServer: [BTUI] onCreate()
08-19 17:55:25.917  6634  6634 D LGBluetoothAPIServer: [BTUI] onBind()
,08-19 17:55:25.920  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-19 17:55:25.922  1937  1937 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-19 17:55:25.923  1937  2116 D LGBluetoothAPIService: Message: 100
08-19 17:55:25.923  1937  2116 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-19 17:55:25.928  6223  6223 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-19 17:55:25.939  6223  6223 D BluetoothPermissionRequest: onReceive
,08-19 17:55:25.942  6223  6223 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-19 17:55:25.942  6223  6223 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-19 17:55:25.945  6223  6223 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-19 17:55:25.953  6634  6634 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-19 17:55:25.960  6634  6634 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:25.966  6634  6634 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-19 17:55:25.967  6634  6634 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-19 17:55:25.968  6634  6634 V BluetoothSapReceiver: SapReceiver onReceive 
08-19 17:55:25.971  6634  6634 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:25.971  6634  6634 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-19 17:55:25.976  6288  6288 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-19 17:55:26.113  1599  1599 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-19 17:55:26.114  1599  1599 I [SystemUI]LGPowerUI: On Skip Timer : true
08-19 17:55:27.237  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:27.238  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:30.252  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:55:30.252  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a534ab8 added. We now have 6 listener(s)
,08-19 17:55:30.252  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:30.266  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:30.266  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@88b1091 added. We now have 7 listener(s)
08-19 17:55:30.266  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:30.266  5974  6083 I System.out: IsBluetoothEnabled
08-19 17:55:30.267  1029  1783 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:30.268  1029  1783 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-19 17:55:30.269  1029  1091 D BluetoothManagerService: Message: 2
08-19 17:55:30.273  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:30.275  1029  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:30.275  1029  2022 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-19 17:55:30.298  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-19 17:55:30.298  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-19 17:55:30.298  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-19 17:55:30.299  1029  1091 D BluetoothManagerService: Message: 1
08-19 17:55:30.299  1029  1091 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-19 17:55:30.355  1029  1091 D BluetoothManagerService: Message: 20
08-19 17:55:30.355  1029  1091 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ee325d5:true
,08-19 17:55:30.360  6634  6634 D BluetoothAdapterState: make
,08-19 17:55:30.371  6634  6634 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-19 17:55:30.371  6634  6634 I bluedroid-qcom: init
,08-19 17:55:30.375  6634  6666 I BluetoothAdapterState: Entering OffState
08-19 17:55:30.376  6634  6634 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-19 17:55:30.376  6634  6634 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-19 17:55:30.376  6634  6634 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-19 17:55:30.376  6634  6634 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-19 17:55:30.376  6634  6634 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-19 17:55:30.378  6634  6634 I bluedroid-qcom: get_profile_interface socket
08-19 17:55:30.378  6634  6634 I bluedroid-qcom: get_profile_interface map_client
08-19 17:55:30.380  6634  6670 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-19 17:55:30.365  6669  6669 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:30.375  6669  6669 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:30.391  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-19 17:55:30.393  1029  1091 D BluetoothManagerService: Message: 40
,08-19 17:55:30.393  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,08-19 17:55:30.394  6634  6650 I bluedroid-qcom: config_hci_snoop_log
,08-19 17:55:30.395  1029  1091 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-19 17:55:30.395  1029  1091 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-19 17:55:30.400  6669  6669 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-19 17:55:30.400  6669  6669 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
,08-19 17:55:30.400  6669  6669 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-19 17:55:30.409  6669  6669 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-19 17:55:30.415  6634  6670 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-19 17:55:30.417  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-19 17:55:30.418  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
08-19 17:55:30.419  6634  6670 D BluetoothAdapterProperties: Name is: G3
08-19 17:55:30.424  6634  6666 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-19 17:55:30.424  6634  6666 D BluetoothAdapterProperties: Setting state to 11
08-19 17:55:30.424  6634  6666 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-19 17:55:30.425  1029  1091 D BluetoothManagerService: Message: 60
08-19 17:55:30.425  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-19 17:55:30.425  1029  1091 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-19 17:55:30.426  6634  6666 I LGBluetoothServiceJni: classInitNative: succeeds
08-19 17:55:30.430  6669  6669 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-19 17:55:30.430  6669  6669 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-19 17:55:30.435  6223  6223 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-19 17:55:30.435  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:30.435  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-19 17:55:30.439  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:30.443  6634  6634 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-19 17:55:30.443  6634  6634 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:30.443  6634  6634 V BluetoothPbapReceiver: ***********state = 11
08-19 17:55:30.446  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:30.457  6223  6223 D BluetoothPermissionRequest: onReceive
08-19 17:55:30.462  6223  6223 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-19 17:55:30.464  6634  6666 D BluetoothBondStateMachine: make
08-19 17:55:30.472  6634  6687 I BluetoothBondStateMachine: StableState(): Entering Off State
08-19 17:55:30.472  6634  6666 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
08-19 17:55:30.472  6634  6666 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-19 17:55:30.472  6634  6666 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
,08-19 17:55:30.472  6634  6666 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-19 17:55:30.473  6634  6666 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-19 17:55:30.474  6634  6634 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:30.476  6634  6634 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-19 17:55:30.476  6634  6634 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-19 17:55:30.476  6634  6634 V BluetoothSapReceiver: SapReceiver onReceive 
08-19 17:55:30.476  6634  6634 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:30.476  6634  6634 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-19 17:55:30.481  6634  6666 E BluetoothAdapterService: File transfer profiles supported!!
08-19 17:55:30.488  6634  6634 D HeadsetService: Received start request. Starting profile...
08-19 17:55:30.489  6634  6634 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-19 17:55:30.489  6634  6634 D LGBluetoothHfpAdapter: Version 1.6
08-19 17:55:30.492  6634  6634 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-19 17:55:30.493  6634  6634 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-19 17:55:30.493  6634  6634 D HeadsetStateMachine: make
08-19 17:55:30.494  6634  6666 E BluetoothAdapterService: File transfer profiles supported!!
,08-19 17:55:30.498  6634  6666 E BluetoothAdapterService: File transfer profiles supported!!
08-19 17:55:30.502  6634  6666 E BluetoothAdapterService: File transfer profiles supported!!
08-19 17:55:30.505  6634  6666 E BluetoothAdapterService: File transfer profiles supported!!
08-19 17:55:30.509  6634  6666 E BluetoothAdapterService: File transfer profiles supported!!,
08-19 17:55:30.513  6634  6666 E BluetoothAdapterService: File transfer profiles supported!!
,08-19 17:55:30.527  6634  6634 D LgDataFeature: LgDataFeature() Constructor: none
08-19 17:55:30.527  6634  6634 D LgDataFeature: LgDataFeature() Constructor Done, null
08-19 17:55:30.528  6634  6666 V LGMDMManager: Create singleton instance
08-19 17:55:30.529  6634  6666 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-19 17:55:30.531  6634  6634 D HeadsetStateMachine: max_hf_connections = 1
08-19 17:55:30.531  6634  6634 I bluedroid-qcom: get_profile_interface handsfree
08-19 17:55:30.533  6634  6634 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-19 17:55:30.533   322  1378 V AudioPolicyService: registerClient() client 0xb57f62e0, uid 1002
08-19 17:55:30.533   322   322 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-19 17:55:30.533   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-19 17:55:30.533   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
08-19 17:55:30.533  6634  6634 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-19 17:55:30.534   322  2138 V AudioFlinger: registerClient() client 0xb1433058, pid 6634
,08-19 17:55:30.534   322  1372 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:30.534   322  1372 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:55:30.535  2145  4394 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:30.535  2145  4394 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:55:30.535  3309  3328 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:30.535  3309  3328 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:55:30.535  1029  1571 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:30.535  1029  1571 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:55:30.535  1599  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:30.535  1599  1619 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:55:30.535  1849  2527 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:30.535  1849  2527 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-19 17:55:30.535  6634  6651 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-19 17:55:30.535   322  1373 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:30.535   322  1373 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:30.535  1029  1046 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:30.535  1029  1046 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:30.535  3309  3327 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:30.536  3309  3327 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:30.536  1849  4306 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:30.536  1849  4306 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:30.536  1599  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:30.536  1599  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:30.536  2145  2162 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:30.536  2145  2162 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-19 17:55:30.536  6634  6651 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-19 17:55:30.536  6634  6651 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-19 17:55:30.536  6634  6651 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-19 17:55:30.536  6634  6634 V ToneGenerator: Create Track: 0xb4928080
08-19 17:55:30.536  6634  6634 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-19 17:55:30.536  6634  6634 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-19 17:55:30.536   322  2136 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-19 17:55:30.536   322  2136 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-19 17:55:30.536   322  2136 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-19 17:55:30.536   322  2136 V AudioPolicyManagerEx: getOutput() returns output 2
08-19 17:55:30.537   322  1378 I AudioFlinger: isAudioPlaybackHookOn() false
08-19 17:55:30.537   322   322 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-19 17:55:30.537   322   322 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-19 17:55:30.537   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-19 17:55:30.537   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
08-19 17:55:30.537  6634  6634 V AudioSystem: getLatency() output 2, latency 50
08-19 17:55:30.5,37  6634  6634 V AudioSystem: getFrameCount() output 2, frameCount 960
08-19 17:55:30.537  6634  6634 V AudioTrack: createTrack_l() output 2 afLatency 50
08-19 17:55:30.537   322  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-19 17:55:30.537   322  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-19 17:55:30.537   322  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-19 17:55:30.537   322  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-19 17:55:30.537   322  2138 V AudioFlinger: createTrack() lSessionId: 23
08-19 17:55:30.538  6634  6634 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-19 17:55:30.538   322  2138 V AudioFlinger: acquiring 23 from 6634, for 6634
08-19 17:55:30.538   322  2138 V AudioFlinger:  added new entry for 23
08-19 17:55:30.538  6634  6634 V ToneGenerator: ToneGenerator INIT OK, time: 132615
08-19 17:55:30.538  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
08-19 17:55:30.539  6634  6690 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-19 17:55:30.539  6634  6690 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-19 17:55:30.539  6634  6690 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-19 17:55:30.539  6634  6690 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-19 17:55:30.539   322  1377 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6634
08-19 17:55:30.540   322  1377 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-19 17:55:30.540   322  1377 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-19 17:55:30.540   322  1377 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-19 17:55:30.540   322  1377 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-19 17:55:30.540   322  1377 V voice   : voice_set_parameters: exit with code(0)
08-19 17:55:30.540   322  1377 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-19 17:55:30.540   322  1377 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-19 17:55:30.540   322  1377 V msm8974_platform: platform_set_parameters: exit with code(0)
08-19 17:55:30.540   322  1377 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-19 17:55:30.540   322  1377 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-19 17:55:30.540   322  1377 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-19 17:55:30.540  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
08-19 17:55:30.540  6634  6690 V ToneGenerator: ToneGenerator destructor
08-19 17:55:30.540  6634  6690 V ToneGenerator: stopTone
08-19 17:55:30.540  6634  6690 V ToneGenerator: Delete Track: 0xb4928080
08-19 17:55:30.540  6634  6690 V AudioTrack: ~AudioTrack, releasing session id from 6634 on behalf of 6634
08-19 17:55:30.540   322  2136 V AudioFlinger: releasing 23 from 6634 for 6634
08-19 17:55:30.540   322  2136 V AudioFlinger:  decremented refcount to 0
08-19 17:55:30.540   322  2136 V AudioFlinger: purging stale effects
08-19 17:55:30.540   322  2136 V AudioPolicyService: AudioCommandThread() adding release output 2
08-19 17:55:30.540   322  2136 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-19 17:55:30.540   322  1222 V AudioPolicyService: AudioCommandThread() waking up
08-19 17:55:30.540   322  1222 V AudioPolicyService: AudioCommandThread() processing release output 2
08-19 17:55:30.540   322  1222 V AudioPolicyManager: releaseOutput() 2
08-19 17:55:30.540   322  1222 V AudioPolicyService: AudioCommandThread() going to sleep
08-19 17:55:30.541   322  2136 V AudioFlinger: PlaybackThread::Track destructor
08-19 17:55:30.541   322  2136 V AudioFlinger: removeClient_l() pid 6634, calling pid 322
08-19 17:55:30.541  6634  6634 D A2dpService: Received start request. Starting profile...
08-19 17:55:30.541  6634  6634 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-19 17:55:30.542  6634  6634 V Avrcp   : make
08-19 17:55:30.542  6634  6634 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-19 17:55:30.542  6634  6634 I bluedroid-qcom: get_profile_interface avrcp
08-19 17:55:30.545  1029  1645 W Process : Unable to open /proc/6691/status
08-19 17:55:30.549  6634  6634 V AudioManager: registerRemoteController: size of Media player list: 0
,08-19 17:55:30.552  6634  6634 E AudioManager: No RCC entry present to update
08-19 17:55:30.552  6634  6634 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-19 17:55:30.555  6634  6634 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-19 17:55:30.556  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-19 17:55:30.556  6634  6634 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-19 17:55:30.558  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-19 17:55:30.654  1029  1045 V SIM_STK : Menu title from STK is T-Mobile
08-19 17:55:30.654  1029  1045 V SIM_STK : Menu title from STK is T-Mobile
,08-19 17:55:30.777  1029  1645 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-19 17:55:30.788  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-19 17:55:30.792  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-19 17:55:30.794  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-19 17:55:30.794  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-19 17:55:30.794  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,08-19 17:55:30.794  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-19 17:55:30.794  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-19 17:55:30.794  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-19 17:55:30.794  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-19 17:55:30.794  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-19 17:55:30.794  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-19 17:55:30.795  6634  6634 I BluetoothA2dpServiceJni: classInitNative
08-19 17:55:30.795  6634  6634 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-19 17:55:30.795  6634  6634 D A2dpStateMachine: make
08-19 17:55:30.798  6634  6634 I bluedroid-qcom: get_profile_interface a2dp
08-19 17:55:30.798  6634  6695 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-19 17:55:30.802  6634  6634 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-19 17:55:30.802  6634  6634 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-19 17:55:30.803  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
08-19 17:55:30.803  6634  6694 D A2dpStateMachine: Enter Disconnected: -2
08-19 17:55:30.803  6634  6634 I BluetoothHidServiceJni: classInitNative: succeeds
08-19 17:55:30.805  6634  6634 D HidService: Received start request. Starting profile...
08-19 17:55:30.805  6634  6634 I bluedroid-qcom: get_profile_interface hidhost
08-19 17:55:30.806  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
08-19 17:55:30.806  6634  6634 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-19 17:55:30.811  6634  6634 D HealthService: Received start request. Starting profile...
08-19 17:55:30.815  6634  6634 I bluedroid-qcom: get_profile_interface health
08-19 17:55:30.815  6634  6634 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-19 17:55:30.815  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
08-19 17:55:30.816  6634  6634 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-19 17:55:30.818  6634  6634 D PanService: Received start request. Starting profile...
08-19 17:55:30.818  6634  6634 D BluetoothPanServiceJni: initializeNative(L110): pan
08-19 17:55:30.818  6634  6634 I bluedroid-qcom: get_profile_interface pan
08-19 17:55:30.825  6634  6634 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-19 17:55:30.825  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
,08-19 17:55:30.826  6634  6634 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-19 17:55:30.830  6634  6634 D BtGatt.DebugUtils: handleDebugAction() action=null
08-19 17:55:30.831  6634  6634 D BtGatt.GattService: Received start request. Starting profile...
08-19 17:55:30.831  6634  6634 D BtGatt.GattService: start()
08-19 17:55:30.831  6634  6634 I bluedroid-qcom: get_profile_interface gatt
08-19 17:55:30.831  6634  6634 D BtGatt.AdvertiseManager: advertise manager created
08-19 17:55:30.839  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
,08-19 17:55:30.840  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
,08-19 17:55:30.841  6634  6634 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-19 17:55:30.841  6634  6634 V BluetoothMapService: BluetoothMapBinder()
08-19 17:55:30.842  6634  6634 D BluetoothMapService: Received start request. Starting profile...
08-19 17:55:30.842  6634  6634 D BluetoothMapService: start()
08-19 17:55:30.845  6634  6634 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-19 17:55:30.845  6634  6634 D BluetoothMapEmailAppObserver: createReceiver()
08-19 17:55:30.846  6634  6634 D BluetoothMapEmailAppObserver: initObservers()
08-19 17:55:30.846  6634  6634 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-19 17:55:30.852  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
08-19 17:55:30.852  6634  6634 D HeadsetStateMachine: Proxy object connected
08-19 17:55:30.853  6634  6634 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-19 17:55:30.853  6634  6634 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-19 17:55:30.856  6634  6634 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-19 17:55:30.857  6634  6690 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-19 17:55:30.857  6634  6690 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-19 17:55:30.857  6634  6690 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-19 17:55:30.860  6634  6634 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-19 17:55:30.864  6634  6634 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-19 17:55:30.866  6634  6634 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-19 17:55:30.866  6634  6634 V PanService: [BTUI] SIM Extra State :ABSENT
,08-19 17:55:30.869  6634  6634 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-19 17:55:30.872  6634  6634 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-19 17:55:30.872  6634  6634 V BluetoothMapService: Handler(): got msg=1
08-19 17:55:30.873  6634  6666 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-19 17:55:30.873  6634  6666 I bluedroid-qcom: enable
08-19 17:55:30.874  6634  6705 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-19 17:55:30.874  6634  6705 I bt-btu  : btu_task pending for preload complete event
08-19 17:55:30.874  6634  6666 I bt_hci_bdroid: init
08-19 17:55:30.877  6634  6666 I bt_vendor: bt-vendor : init
08-19 17:55:30.877  6634  6666 I bt_vendor: bt-vendor : get_bt_soc_type
08-19 17:55:30.877  6634  6666 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-19 17:55:30.877  6634  6666 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-19 17:55:30.877  6634  6666 D bt_userial_mct: userial_init
08-19 17:55:30.878  6634  6666 D bt_hci_bdroid: set_power 1
08-19 17:55:30.878  6634  6666 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-19 17:55:30.878  6634  6666 I bt_vendor: Starting hciattach daemon
08-19 17:55:30.878  6634  6666 I bt_vendor: try to set true
08-19 17:55:30.864  6708  6708 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-19 17:55:30.874  6708  6708 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:30.909  6709  6709 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-19 17:55:31.035  6715  6715 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-19 17:55:31.053  6716  6716 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-19 17:55:31.092  6721  6721 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-19 17:55:31.105  6722  6722 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-19 17:55:31.119  6723  6723 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-19 17:55:31.131  6724  6724 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-19 17:55:31.154  6726  6726 I libmdmdetect: ESOC framework not supported
,08-19 17:55:31.155  6726  6726 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-19 17:55:31.164  6726  6726 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-19 17:55:31.164  6726  6726 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-19 17:55:31.165  6726  6726 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-19 17:55:31.165  6726  6726 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-19 17:55:31.165  6726  6726 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-19 17:55:31.165  6726  6726 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-19 17:55:31.165  6726  6726 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-19 17:55:31.208  6726  6727 E QC-QMI  : qmi_client [6726] 15: failed to locate client data
,08-19 17:55:31.209   475   475 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-19 17:55:31.210   475   475 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-19 17:55:31.240  6728  6728 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-19 17:55:31.264  6729  6729 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-19 17:55:31.281  6634  6666 I bt_vendor: bluetooth satus is on
,08-19 17:55:31.281  6634  6666 D bt_hci_bdroid: preload
,08-19 17:55:31.282  6634  6707 D bt_userial_mct: userial_open(port:0)
08-19 17:55:31.282  6634  6707 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-19 17:55:31.285  6634  6707 I bt_vendor: Done intiailizing UART
08-19 17:55:31.286  6634  6707 I bt_vendor: Done intiailizing UART
08-19 17:55:31.286  6634  6707 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-19 17:55:31.287  6634  6707 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-19 17:55:31.287  6634  6731 D bt_userial_mct: Entering userial_read_thread()
08-19 17:55:31.287  6634  6705 I bt-btu  : btu_task received preload complete event
08-19 17:55:31.287  6634  6705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-19 17:55:31.287  6634  6705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-19 17:55:31.289  6634  6705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_HCI
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_AVDT
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_AVRC
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_A2D
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_BNEP
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_BTM
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_GAP
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_PAN
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_SDP
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_GATT
08-19 17:55:31.292  6634  6705 I         : BTE_InitTraceLevels -- TRC_SMP
08-19 17:55:31.293  6634  6705 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-19 17:55:31.293  6634  6705 I         : BTE_InitTraceLevels -- TRC_BTIF
08-19 17:55:31.341  6634  6705 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-19 17:55:31.341  6634  6705 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016c061 
08-19 17:55:31.341  6634  6705 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016c061 
,08-19 17:55:31.371  6634  6670 E bt-btif : Calling BTA_HhEnable
08-19 17:55:31.371  6634  6705 W bt-l2cap: btif_storage_get_adapter_property service_mask
08-19 17:55:31.371  6634  6670 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-19 17:55:31.371  6634  6705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-19 17:55:31.371  6634  6705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-19 17:55:31.371  6634  6705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-19 17:55:31.371  6634  6705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-19 17:55:31.372  6634  6670 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-19 17:55:31.374  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-19 17:55:31.375  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
,08-19 17:55:31.376  6634  6670 D BluetoothAdapterProperties: Name is: G3
08-19 17:55:31.380  6634  6670 D BluetoothAdapterProperties: Scan Mode:20
08-19 17:55:31.380  6634  6670 D BluetoothAdapterProperties: Discoverable Timeout:120
08-19 17:55:31.382  6634  6670 D bt_hci_bdroid: postload
08-19 17:55:31.383  6634  6707 D bt_hci_bdroid: Used up Tx Cmd credits
08-19 17:55:31.385  6634  6705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-19 17:55:31.387  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:31.388  6634  6670 D bte_conf: Device ID record 1 : primary
08-19 17:55:31.388  6634  6670 D bte_conf:   vendorId            = 00c4
08-19 17:55:31.388  6634  6670 D bte_conf:   vendorIdSource      = 0001
08-19 17:55:31.388  6634  6670 D bte_conf:   product             = 13a1
08-19 17:55:31.388  6634  6670 D bte_conf:   version             = 1000
08-19 17:55:31.388  6634  6670 D bte_conf:   clientExecutableURL = 
08-19 17:55:31.388  6634  6670 D bte_conf:   serviceDescription  = 
08-19 17:55:31.388  6634  6670 D bte_conf:   documentationURL    = 
08-19 17:55:31.388  6634  6670 D bte_conf: bte_load_did_conf no section named DID2.
08-19 17:55:31.390  6634  6705 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-19 17:55:31.391  6634  6705 W bt-smp  : Plain text(LSB ~ MSB) = 27 27 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-19 17:55:31.391  6634  6705 W bt-smp  : Encrypted text(LSB ~ MSB) = 5b ec b0 fa 9e 1d 67 db 6c 69 06 a7 d7 74 aa 96 
08-19 17:55:31.391  6634  6705 W bt-btm  : Stopping oneshot timer
08-19 17:55:31.392  6634  6707 D bt_hci_bdroid: Used up Tx Cmd credits
08-19 17:55:31.392  6634  6707 D bt_hci_bdroid: Used up Tx Cmd credits
08-19 17:55:31.384  6733  6733 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:31.384  6733  6733 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:31.403  6634  6666 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-19 17:55:31.404  6634  6666 D BluetoothAdapterProperties: ScanMode =  20
08-19 17:55:31.404  6634  6666 D BluetoothAdapterProperties: State =  11
08-19 17:55:31.404  6634  6707 D bt_hci_bdroid: Used up Tx Cmd credits
08-19 17:55:31.404  6634  6707 D bt_hci_bdroid: Used up Tx Cmd credits
08-19 17:55:31.404  6634  6666 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-19 17:55:31.404  6634  6670 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-19 17:55:31.404  6634  6666 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-19 17:55:31.404  6634  6666 D BluetoothAdapterProperties: Setting state to 12
08-19 17:55:31.404  6634  6666 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-19 17:55:31.405  1029  1091 D BluetoothManagerService: Message: 60
08-19 17:55:31.405  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-19 17:55:31.405  1029  1091 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-19 17:55:31.406  6634  6670 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-19 17:55:31.408  6634  6707 D bt_hci_bdroid: Used up Tx Cmd credits
08-19 17:55:31.408  6634  6707 D bt_hci_bdroid: Used up Tx Cmd credits
08-19 17:55:31.409  6634  6666 I BluetoothAdapterState: Entering On State
08-19 17:55:31.409  6634  6731 E bt_mct  : hci lib postload completed
,08-19 17:55:31.412  6634  6666 D LGBluetoothServiceAdapter: [BTUI] OnState
08-19 17:55:31.412  6634  6666 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-19 17:55:31.412  6634  6666 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-19 17:55:31.413  6634  6666 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-19 17:55:31.415  6223  6239 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:55:31.421  6223  6239 D BluetoothMap: onBluetoothStateChange: up=true
,08-19 17:55:31.427  6634  6705 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-19 17:55:31.427  6634  6705 W bt-smp  : Plain text(LSB ~ MSB) = ea 27 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-19 17:55:31.427  6634  6705 W bt-smp  : Encrypted text(LSB ~ MSB) = d0 af 0c 9f 9b 87 2a 73 6b ec 7f cc ad ad b0 84 
08-19 17:55:31.427  6634  6705 W bt-btm  : Stopping oneshot timer
08-19 17:55:31.435  1849  4302 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:55:31.436  6634  6670 D BluetoothAdapterProperties: Discoverable Timeout:120
08-19 17:55:31.436  6634  6670 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-19 17:55:31.438  1849  1849 D BluetoothHeadset: Proxy object connected
,08-19 17:55:31.439  6223  6540 D BluetoothPan: onBluetoothStateChange on: true
08-19 17:55:31.439  6223  6540 D BluetoothPan: onBluetoothStateChange call bindService
08-19 17:55:31.441  6223  6223 D BluetoothHeadset: Proxy object connected
08-19 17:55:31.441  6223  6223 D HeadsetProfile: Bluetooth service connected
08-19 17:55:31.445  1029  1091 D BluetoothA2dp: onBluetoothStateChange: up=true
08-19 17:55:31.445  1029  1091 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:55:31.447  1029  1029 D BluetoothHeadset: Proxy object connected
08-19 17:55:31.449  1029  1029 D BluetoothA2dp: Proxy object connected
08-19 17:55:31.451  1849  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:55:31.453  6634  6705 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-19 17:55:31.453  6634  6705 W bt-smp  : Plain text(LSB ~ MSB) = 48 bd 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-19 17:55:31.453  6634  6705 W bt-smp  : Encrypted text(LSB ~ MSB) = ab 4b c6 a7 a9 4f 5e 48 4a 11 3c b1 86 32 8a 1e 
08-19 17:55:31.453  6634  6705 W bt-btm  : Stopping oneshot timer
,08-19 17:55:31.456  1849  1849 D BluetoothHeadset: Proxy object connected
08-19 17:55:31.457  6223  6239 D BluetoothA2dp: onBluetoothStateChange: up=true
08-19 17:55:31.459  6223  6238 D BluetoothPbap: onBluetoothStateChange: up=true
08-19 17:55:31.461  6634  6666 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-19 17:55:31.463  1849  4306 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:55:31.466  1849  1849 D BluetoothHeadset: Proxy object connected
,08-19 17:55:31.468  6223  6540 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-19 17:55:31.468  6634  6705 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-19 17:55:31.468  6634  6705 W bt-smp  : Plain text(LSB ~ MSB) = 95 0f 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-19 17:55:31.468  6634  6705 W bt-smp  : Encrypted text(LSB ~ MSB) = cf b2 5a db 49 9d 00 f2 d3 ff 79 64 53 ba 8d 40 
08-19 17:55:31.468  6634  6705 W bt-btm  : Stopping oneshot timer
08-19 17:55:31.471  6223  6223 D BluetoothMap: Proxy object connected
08-19 17:55:31.472  6223  6223 D MapProfile: Bluetooth service connected
08-19 17:55:31.472  6223  6223 D BluetoothMap: getConnectedDevices()
08-19 17:55:31.473  6634  6651 V BluetoothMapService: getConnectedDevices()
08-19 17:55:31.478  6223  6223 D BluetoothPan: BluetoothPAN Proxy object connected
08-19 17:55:31.478  6223  6223 D PanProfile: Bluetooth service connected
,08-19 17:55:31.481  6738  6738 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-19 17:55:31.483  1029  1091 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-19 17:55:31.483  1029  1091 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-19 17:55:31.484  6223  6223 D BluetoothA2dp: Proxy object connected
08-19 17:55:31.484  6223  6223 D A2dpProfile: Bluetooth service connected
08-19 17:55:31.485  6634  6705 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-19 17:55:31.485  6634  6705 W bt-smp  : Plain text(LSB ~ MSB) = bb db 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-19 17:55:31.485  6634  6705 W bt-smp  : Encrypted text(LSB ~ MSB) = 48 76 c0 74 91 23 f8 d6 58 5d 74 15 2b b7 b4 58 
08-19 17:55:31.485  6634  6705 W bt-btm  : Stopping oneshot timer
08-19 17:55:31.488  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-19 17:55:31.488  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:31.489  1937  2116 D LGBluetoothAPIService: Message: 1
08-19 17:55:31.489  1937  2116 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-19 17:55:31.489  1937  2116 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-19 17:55:31.489  1937  2116 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-19 17:55:31.494  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:31.494  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:31.494  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:31.494  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:31.494  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:31.494  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:31.494  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:31.494  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:31.498  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-19 17:55:31.498  1029  1091 D BluetoothManagerService: Message: 40
08-19 17:55:31.498  1029  1091 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-19 17:55:31.501  6223  6223 D BluetoothInputDevice: Proxy object connected
08-19 17:55:31.501  6223  6223 D HidProfile: Bluetooth service connected
08-19 17:55:31.505  5974  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:31.508  6634  6634 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:31.508  6634  6634 D BluetoothMapService: STATE_ON
,08-19 17:55:31.511  6223  6223 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-19 17:55:31.512  6223  6223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-19 17:55:31.520  6223  6223 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:31.528  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
08-19 17:55:31.529  6634  6634 V BluetoothPbapService: Pbap Service onCreate
08-19 17:55:31.529  6634  6634 V BluetoothPbapService: Starting PBAP service
08-19 17:55:31.530  6634  6634 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-19 17:55:31.530  6634  6634 V BluetoothPbapService: Pbap Service onBind
08-19 17:55:31.531  6634  6634 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:31.531  6634  6634 V BluetoothPbapService: state: 12
08-19 17:55:31.531  6223  6223 D BluetoothPbap: Proxy object connected
08-19 17:55:31.531  6223  6223 D PbapServerProfile: Bluetooth service connected
08-19 17:55:31.531  6634  6634 V BluetoothMapService: Handler(): got msg=1
08-19 17:55:31.532  6634  6634 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-19 17:55:31.532  6634  6634 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-19 17:55:31.533  6634  6634 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:31.533  6634  6634 V BluetoothPbapReceiver: ***********state = 12
08-19 17:55:31.534  6634  6634 V BluetoothPbapService: Handler(): got msg=1
08-19 17:55:31.536  6634  6634 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-19 17:55:31.538  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-19 17:55:31.538  6634  6752 D BluetoothMapMasInstance: MAS initSocket()
08-19 17:55:31.538  2177  2177 D c       : Getting all permits...
08-19 17:55:31.538  2177  2177 D a       : Opening database...
08-19 17:55:31.539  6634  6752 D BluetoothMapMasInstance:   masId = 00
08-19 17:55:31.539  6634  6752 D BluetoothMapMasInstance:   msgTypes = 0e
08-19 17:55:31.539  6634  6752 D BluetoothMapMasInstance:   masName = SMS/MMS
08-19 17:55:31.539  6634  6752 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-19 17:55:31.539  6634  6754 V BluetoothPbapService: Pbap Service initSocket
08-19 17:55:31.540  1029  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:31.541  1029  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:31.542  6634  6754 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:31.542  6634  6752 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:31.543  2177  2177 D a       : Opening database auth.proximity.permit_store...
08-19 17:55:31.545  2177  2177 D a       : Closing database...
,08-19 17:55:31.547  6634  6754 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-19 17:55:31.547  6634  6752 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-19 17:55:31.547  6634  6752 V BluetoothMapMasInstance: Succeed to create listening socket 
08-19 17:55:31.548  6634  6752 D BluetoothMapMasInstance: Accepting socket connection...
08-19 17:55:31.548  6634  6754 V BluetoothPbapService: Succeed to create listening socket 
08-19 17:55:31.548  6634  6754 V BluetoothPbapService: Accepting socket connection...
08-19 17:55:31.553  6634  6670 D BluetoothAdapterProperties: Scan Mode:21
08-19 17:55:31.553  6634  6670 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-19 17:55:31.556  6634  6670 D BluetoothAdapterProperties: Scan Mode:21
08-19 17:55:31.556  6634  6670 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-19 17:55:31.558  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:31.559  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:31.568  6223  6223 D BluetoothPermissionRequest: onReceive
,08-19 17:55:31.570  6223  6223 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-19 17:55:31.571  6223  6223 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-19 17:55:31.575  6634  6634 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-19 17:55:31.576  6634  6634 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-19 17:55:31.582  6634  6634 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-19 17:55:31.601  6634  6634 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-19 17:55:31.601  6634  6634 V BtOppService: onCreate
,08-19 17:55:31.605  6634  6634 V BluetoothOppNotification: send message
08-19 17:55:31.608  6634  6634 V BtOppService: Starting RfcommListener
08-19 17:55:31.617  6634  6634 D BluetoothOppPreference: Dumping Names:  
08-19 17:55:31.617  6634  6634 D BluetoothOppPreference: {}
08-19 17:55:31.617  6634  6634 D BluetoothOppPreference: Dumping Channels:  
08-19 17:55:31.617  6634  6634 D BluetoothOppPreference: {}
08-19 17:55:31.620  6634  6634 V BtOppService: onStartCommand
,08-19 17:55:31.624  6634  6634 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:31.624  6634  6634 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-19 17:55:31.625  6634  6760 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-19 17:55:31.626  6634  6634 V BluetoothOppNotification: new notify threadi!
08-19 17:55:31.627  6634  6634 V BluetoothOppNotification: send delay message
08-19 17:55:31.628  6634  6634 V BtOppService: start RfcommListener
08-19 17:55:31.630  6634  6634 V BtOppService: RfcommListener started
08-19 17:55:31.634  6634  6763 V BtOppRfcommListener: Starting RFCOMM listener....
,08-19 17:55:31.635  6634  6757 V BtOppService: Deleted complete outbound shares, number =  0
08-19 17:55:31.635  6634  6762 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-19 17:55:31.636  6634  6760 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-19 17:55:31.638  6634  6757 V BtOppService: Deleted complete inbound failed shares, number = 0
08-19 17:55:31.638  6634  6757 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-19 17:55:31.638  1029  1645 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:31.640  6634  6763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:31.641  6634  6763 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-19 17:55:31.641  6634  6763 V BtOppRfcommListener: Started RFCOMM listener....
08-19 17:55:31.641  6634  6763 I BtOppRfcommListener: Accept thread started.
08-19 17:55:31.641  6634  6763 V BtOppRfcommListener: Accepting connection...
08-19 17:55:31.642  6634  6757 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@111fea39 on behalf of 
08-19 17:55:31.643  6634  6762 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@250a487e on behalf of 
08-19 17:55:31.646  6634  6760 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36eb71df on behalf of 
08-19 17:55:31.646  6634  6762 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-19 17:55:31.647  6634  6762 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-19 17:55:31.648  6634  6760 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-19 17:55:31.649  6634  6762 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@106b9e2c on behalf of 
08-19 17:55:31.649  6634  6762 V BluetoothOppNotification: outbound: succ-0  fail-0
08-19 17:55:31.651  6634  6762 V BluetoothOppNotification: outbound notification was removed.
08-19 17:55:31.651  6634  6762 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-19 17:55:31.653  6634  6762 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a0bf0f5 on behalf of 
08-19 17:55:31.654  6634  6762 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-19 17:55:31.656  6634  6762 V BluetoothOppNotification: inbound notification was removed.
08-19 17:55:31.656  6634  6762 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-19 17:55:31.657  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
08-19 17:55:31.657  6634  6634 V BluetoothFtpService: Ftp Service onCreate
08-19 17:55:31.657  6634  6634 I BluetoothFtpService: Ftp Service onCreate
08-19 17:55:31.657  6634  6634 V BluetoothFtpService: Ftp Service onStartCommand
08-19 17:55:31.657  6634  6634 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:31.657  6634  6634 V BluetoothFtpService: Starting Listening on sockets
08-19 17:55:31.658  6634  6634 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-19 17:55:31.658  6634  6762 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6bf4cfb on behalf of 
08-19 17:55:31.658  6634  6634 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-19 17:55:31.658  6634  6634 V BluetoothSapReceiver: SapReceiver onReceive 
08-19 17:55:31.658  6634  6634 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:31.658  6634  6634 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-19 17:55:31.658  6634  6634 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-19 17:55:31.660  6634  6634 V BtOppService: ContentObserver received notification
08-19 17:55:31.660  6634  6634 V BtOppService: ContentObserver received notification
08-19 17:55:31.660  6634  6634 V BluetoothFtpService: Handler(): got msg=1
08-19 17:55:31.661  6634  6634 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-19 17:55:31.661  6634  6634 V BluetoothFtpService: Ftp Service initSocket
,08-19 17:55:31.662  6634  6764 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-19 17:55:31.662  6634  6764 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-19 17:55:31.665  1029  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:31.665  6634  6634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:31.666  6634  6764 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e0a7118 on behalf of 
08-19 17:55:31.666  6634  6634 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-19 17:55:31.667  6634  6634 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-19 17:55:31.667  6634  6764 V BluetoothOppNotification: update too frequent, put in queue
08-19 17:55:31.668  6634  6764 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-19 17:55:31.669  6634  6765 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-19 17:55:31.692  6634  6634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@243867ed
,08-19 17:55:31.692  6634  6634 V BluetoothSapService: Sap Service onCreate
08-19 17:55:31.694  6634  6634 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:31.694  6634  6634 V BluetoothSapService: state: 12
,08-19 17:55:31.694  6634  6634 V BluetoothSapService: Starting SAP server process
08-19 17:55:31.696  6634  6634 V BluetoothSapService: SAP Service startRfcommListenerThread
08-19 17:55:31.684  6766  6766 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:31.684  6766  6766 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:31.699  6634  6767 V BluetoothSapService: Sap Service initRfcommSocket
08-19 17:55:31.699  1029  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:31.700  6634  6767 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:31.700  6634  6767 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-19 17:55:31.701  6634  6767 V BluetoothSapService: Succeed to create listening socket 
08-19 17:55:31.701  6634  6767 V BluetoothSapService: Accepting socket connection...
08-19 17:55:31.710  6766  6766 V BT_SAP  : Event pipe created
08-19 17:55:31.710  6766  6766 V BT_SAP  : create_server_socket qcom.sap.server
08-19 17:55:31.710  6766  6766 V BT_SAP  : created socket fd 6
,08-19 17:55:32.361  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:32.361  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:32.361  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:32.361  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:32.361  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:32.361  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:32.361  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:32.361  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:32.369  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:32.371  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:32.371  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23686bf6 added. We now have 8 listener(s)
08-19 17:55:32.371  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:32.374  1029  1571 D WifiServiceImplEx: setWifiEnabled: false pid=5974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-19 17:55:32.374  1029  1571 D WifiService: setWifiEnabled: false pid=5974, uid=10118
08-19 17:55:32.374  1029  1571 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-19 17:55:32.379  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:32.383  1029  1046 D WifiServiceImplEx: setWifiEnabled: true pid=5974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-19 17:55:32.384  1029  1046 D WifiService: setWifiEnabled: true pid=5974, uid=10118
08-19 17:55:32.384  1029  1046 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-19 17:55:32.411  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-19 17:55:32.411  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-19 17:55:32.411  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-19 17:55:32.413  1029  1534 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-19 17:55:32.413  1029  1534 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-19 17:55:32.422  1029  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-19 17:55:32.422  1029  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-19 17:55:32.422  1029  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-19 17:55:32.422  1029  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-19 17:55:32.422  1029  1534 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-19 17:55:32.422  1029  1534 E WifiHW  : unknown target_country: EU , set to default
08-19 17:55:32.422  1029  1534 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-19 17:55:32.422  1029  1534 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-19 17:55:32.422  1029  1534 I WifiUtil: gEnableBmps=1
,08-19 17:55:32.629  6634  6634 V BluetoothOppNotification: new notify threadi!
,08-19 17:55:32.637  6634  6634 V BluetoothOppNotification: send delay message
08-19 17:55:32.641  6634  6780 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-19 17:55:32.645  6634  6780 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9c186c4 on behalf of 
,08-19 17:55:32.645  6634  6780 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-19 17:55:32.648  6634  6780 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-19 17:55:32.652  6634  6780 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e0e49ad on behalf of 
,08-19 17:55:32.653  6634  6780 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-19 17:55:32.655  6634  6780 V BluetoothOppNotification: outbound notification was removed.
,08-19 17:55:32.655  6634  6780 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-19 17:55:32.656  6634  6780 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f5644e2 on behalf of 
08-19 17:55:32.656  6634  6780 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-19 17:55:32.659  6634  6780 V BluetoothOppNotification: inbound notification was removed.,
,08-19 17:55:32.659  6634  6780 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-19 17:55:32.660  6634  6780 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39846073 on behalf of 
08-19 17:55:32.690  2145  2145 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-19 17:55:32.706  2145  2145 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-19 17:55:33.015   318   889 D SoftapController: Softap fwReload - Ok
,08-19 17:55:33.021  1029  1534 E NetdConnector: NDC Command {46 softap fwreload wlan0 STA} took too long (590ms)
08-19 17:55:33.024   318   889 D CommandListener: Setting iface cfg
08-19 17:55:33.024   318   889 D CommandListener: Trying to bring down wlan0
08-19 17:55:33.034  1029  1091 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-19 17:55:33.034  1029  1091 D Tethering: InitialState.processMessage what=4
,08-19 17:55:33.044   318   889 D CommandListener: Clearing all IP addresses on wlan0
08-19 17:55:33.053   318  6788 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-19 17:55:33.065  1029  1089 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-19 17:55:33.067  1029  1091 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-19 17:55:33.070  1029  1534 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-19 17:55:33.064  6789  6789 W wpa_supplicant: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-19 17:55:33.086  1029  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-19 17:55:33.086  1029  1534 E WifiStateMachine: useWiFiOffloading() : false
08-19 17:55:33.086  1029  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-19 17:55:33.074  6789  6789 W wpa_supplicant: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-19 17:55:33.093  1029  1534 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-19 17:55:33.093  1029  1534 D WifiMonitor: connecting to supplicant
,08-19 17:55:33.119  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-19 17:55:33.122  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-19 17:55:33.127  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:33.128  6223  6223 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-19 17:55:33.128  6223  6223 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-19 17:55:33.128  6223  6223 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-19 17:55:33.129  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-19 17:55:33.129  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:33.130  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-19 17:55:33.130  6223  6223 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-19 17:55:33.130  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-19 17:55:33.130  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-19 17:55:33.130  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-19 17:55:33.131  6223  6223 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-19 17:55:33.131  6223  6223 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-19 17:55:33.142  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:33.142  6223  6223 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-19 17:55:33.142  6223  6223 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-19 17:55:33.142  6223  6223 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-19 17:55:33.142  6789  6789 I wpa_supplicant: Successfully initialized wpa_supplicant
08-19 17:55:33.144  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-19 17:55:33.145  6223  6223 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-19 17:55:33.145  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-19 17:55:33.145  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-19 17:55:33.145  6223  6223 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-19 17:55:33.145  6223  6223 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-19 17:55:33.145  6223  6223 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-19 17:55:33.154  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-19 17:55:33.162  6308  6807 W FormManager: Network not available. Please check & try again.
08-19 17:55:33.162  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:33.168  6308  6808 V FormManager: Network unavailable.
08-19 17:55:33.171  6308  6808 V FormManager: Network unavailable.
08-19 17:55:33.173  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-19 17:55:33.176  6789  6789 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-19 17:55:33.176  6789  6789 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-19 17:55:33.276  6789  6789 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-19 17:55:33.332  6789  6789 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-19 17:55:33.339  6789  6789 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-19 17:55:33.342  1029  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-19 17:55:33.342  1029  6810 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-19 17:55:33.343  1029  6810 E WifiMonitor: WifiMonitor:wlan0 cnt=81 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-19 17:55:33.343  1029  6810 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-19 17:55:33.343  1029  6810 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-19 17:55:33.344  1029  1534 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-19 17:55:33.345  1029  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-19 17:55:33.346  1029  1534 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-19 17:55:33.351  1029  1534 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-19 17:55:33.352  1029  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-19 17:55:33.354  1029  1534 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-19 17:55:33.355  1029  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-19 17:55:33.356  1029  1534 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-19 17:55:33.357  1029  1534 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-19 17:55:33.357  1029  1534 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-19 17:55:33.358  1029  1534 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-19 17:55:33.358  1029  1534 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-19 17:55:33.358  1029  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-19 17:55:33.358  1029  1534 E WifiStateMachine: useWiFiOffloading() : false
08-19 17:55:33.358  1029  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-19 17:55:33.359  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:33.359  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:33.359  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:33.359  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:33.359  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-19 17:55:33.363  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-19 17:55:33.365  1029  1534 D WifiNative-wlan0: doBoolean: SET update_config 1
08-19 17:55:33.365  1029  1534 D WifiNative-wlan0: SET update_config 1: returned true
08-19 17:55:33.366  1029  1534 D WifiConfigStore: Loading config and enabling all networks 
08-19 17:55:33.366  1029  1534 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-19 17:55:33.366  1937  1937 D WfdService: Waiting for WifiP2p enabling
08-19 17:55:33.366  1029  1534 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-19 17:55:33.371  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-19 17:55:33.371  1029  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-19 17:55:33.375  1029  1534 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-19 17:55:33.379  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:33.379  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:33.379  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:33.379  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:33.379  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:33.379  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:33.379  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:33.379  5974  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:33.382  6205  6205 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-19 17:55:33.384  5974  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:33.385  1029  1534 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-19 17:55:33.385  1029  1534 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-19 17:55:33.386  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:33.387  1029  1534 D WifiStateMachine: enableVerboseLogging : level 2
08-19 17:55:33.387  1029  1534 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-19 17:55:33.387  1029  1534 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-19 17:55:33.387  1029  1534 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-19 17:55:33.388  1029  1534 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-19 17:55:33.388  1029  1534 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-19 17:55:33.388  1029  1534 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-19 17:55:33.388  1029  1534 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,08-19 17:55:33.388  1029  1534 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-19 17:55:33.389  1029  1534 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-19 17:55:33.389  1029  1534 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-19 17:55:33.389  1029  1534 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-19 17:55:33.389  1029  1534 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-19 17:55:33.389  1029  1534 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-19 17:55:33.390  1029  1534 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-19 17:55:33.391  1029  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-19 17:55:33.391  1029  1534 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-19 17:55:33.392  1029  1534 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-19 17:55:33.392  1029  1534 D WifiNative-HAL: Setting external_sim to 1
08-19 17:55:33.392  1029  1534 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-19 17:55:33.393  1029  1534 D WifiNative-wlan0: SET external_sim 1: returned true
08-19 17:55:33.393  1029  1534 I WifiNative-HAL: startHal
08-19 17:55:33.393  1029  1534 D wifi    : setting scan oui 0xaf75b960
08-19 17:55:33.393  1029  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-19 17:55:33.393  1029  1534 I WifiNative-HAL: startHal
08-19 17:55:33.393  1029  1534 D wifi    : setting scan oui 0xaf75b960
08-19 17:55:33.394  1029  1534 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-19 17:55:33.396  1937  1937 D WfdsService: Supplicant Connection state is changed : true
08-19 17:55:33.396  1937  2308 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-19 17:55:33.396  1937  2308 D WfdsService: Set the WFDS Monitor: true
08-19 17:55:33.396  1937  2308 D WfdsMonitor: WfdsMonitorThread create
08-19 17:55:33.396  1937  2308 D WfdsMonitor: WFDS Monitor is created and started
08-19 17:55:33.396  1937  2308 D WfdsService: WiFi: Supplicant connection re-established
08-19 17:55:33.396  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-19 17:55:33.396  1029  1534 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-19 17:55:33.397  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-19 17:55:33.397  6789  6789 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-19 17:55:33.397  1029  1534 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-19 17:55:33.397  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-19 17:55:33.398  6789  6789 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-19 17:55:33.398  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-19 17:55:33.398  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-19 17:55:33.398  1937  6812 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-19 17:55:33.398  6789  6789 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-19 17:55:33.398  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-19 17:55:33.398  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-19 17:55:33.399  6789  6789 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-19 17:55:33.399  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-19 17:55:33.399  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-19 17:55:33.399  6789  6789 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-19 17:55:33.399  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-19 17:55:33.399  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-19 17:55:33.400  6789  6789 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,08-19 17:55:33.401  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-19 17:55:33.401  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-19 17:55:33.401  6789  6789 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-19 17:55:33.401  1029  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-19 17:55:33.402  1029  1534 E WifiNative: : [135,466,020 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-19 17:55:33.402  1029  1534 D WifiNative-wlan0: doBoolean: RECONNECT
08-19 17:55:33.402  1029  1534 D WifiNative-wlan0: RECONNECT: returned true
08-19 17:55:33.403  1029  1534 D WifiNative-wlan0: doString: [STATUS]
08-19 17:55:33.403  1029  6810 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-19 17:55:33.403  1029  6810 E WifiMonitor: WifiMonitor:wlan0 cnt=82 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-19 17:55:33.404  1029  1534 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-19 17:55:33.404  1029  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-19 17:55:33.405  1029  1534 D WifiNative-wlan0: SET ps 1: returned true
08-19 17:55:33.405  1029  1533 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-19 17:55:33.406  1937  6812 E CtrlSupplicant: Succeed to open control connection
08-19 17:55:33.406  1937  6812 E CtrlSupplicant: Succeed to open monitor connection
08-19 17:55:33.407  1937  6812 D WfdsMonitor: Supplicant connection established
08-19 17:55:33.407  1937  2308 D WfdsService: Connected to the supplicant for wfds
08-19 17:55:33.407  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 3
08-19 17:55:33.407  1029  1029 D RttService: SCAN_AVAILABLE : 3
08-19 17:55:33.408   318   889 D CommandListener: Setting iface cfg
08-19 17:55:33.408   318   889 D CommandListener: Trying to bring up p2p0
08-19 17:55:33.408  1029  1552 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.408  1029  1552 I WifiNative-HAL: startHal
08-19 17:55:33.408  1029  1552 D wifi    : getting scan capabilities on interface[1] = 0xaf75b960
08-19 17:55:33.408  1029  1552 D wifi    : failed to get capabilities : -3
08-19 17:55:33.408  1029  1552 E WifiScanningService: could not get scan capabilities
08-19 17:55:33.408  1029  1533 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-19 17:55:33.408  1029  1553 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.408  1029  1533 D LGWifiP2pService: P2pEnablingState
08-19 17:55:33.408  1029  1533 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.408  1029  1533 D LGWifiP2pService: P2p socket connection successful
08-19 17:55:33.408  1029  1533 D LGWifiP2pService: P2pEnabledState
08-19 17:55:33.409  1029  1533 D LGWifiP2pService: sending p2p connection changed broadcast
08-19 17:55:33.409  1029  1533 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-19 17:55:33.410  1029  1534 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-19 17:55:33.410  1029  1533 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-19 17:55:33.410  1029  1533 D WifiNative-p2p0: doBoolean: SET device_name G3
08-19 17:55:33.410  1029  1533 D WifiNative-p2p0: SET device_name G3: returned true
08-19 17:55:33.410  1029  1533 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-19 17:55:33.410  1029  1534 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-19 17:55:33.410  1029  1533 D LGWifiP2pService: before postfix = G3
08-19 17:55:33.410  1029  1533 D WifiServerServiceExt: postfix byte check : 2
08-19 17:55:33.410  1029  1533 D LGWifiP2pService: after postfix = G3
08-19 17:55:33.410  1029  1533 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-19 17:55:33.410  4212  4212 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-19 17:55:33.411  4212  4212 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-19 17:55:33.411  1029  1533 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-19 17:55:33.411  1029  1533 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-19 17:55:33.411  1029  1533 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-19 17:55:33.411  1029  1533 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-19 17:55:33.412  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-19 17:55:33.412  1937  1937 D WfdsService: WifiP2pState is changed : true
08-19 17:55:33.412  1029  1533 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-19 17:55:33.412  1029  1533 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-19 17:55:33.412  1937  1937 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-19 17:55:33.412  1937  2308 D WfdsService: Receive the WFDS_ENABLE Method
08-19 17:55:33.412  1937  2308 D WfdsService: Set the WFDS Monitor: true
08-19 17:55:33.412  1937  2308 D WfdsS,ervice: Connected to the supplicant for wfds
08-19 17:55:33.412  1937  2308 D WfdsJNI : doCommand: WFDS_SET TRUE
08-19 17:55:33.412  6789  6789 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-19 17:55:33.412  1937  2308 D WfdsService: selectPreferredScanChannel [36]
08-19 17:55:33.412  1937  1937 D WfdsService: isConnected: false
08-19 17:55:33.412  1937  2308 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-19 17:55:33.413  4212  4212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-19 17:55:33.413  1029  1533 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-19 17:55:33.413  1029  1533 D WifiNative-HAL: p2pGetDeviceAddress
08-19 17:55:33.413  1029  1533 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-19 17:55:33.414  1029  1533 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-19 17:55:33.414  1029  1533 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-19 17:55:33.414  1029  1534 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-19 17:55:33.414  1029  1533 D WifiNative-p2p0: P2P_FLUSH: returned true
08-19 17:55:33.414  1029  1533 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-19 17:55:33.414  1029  1534 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-19 17:55:33.415  1029  1533 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-19 17:55:33.415  1029  1533 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-19 17:55:33.415  1029  1534 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-19 17:55:33.415  1029  1533 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-19 17:55:33.415  1029  1533 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-19 17:55:33.415  1029  1534 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-19 17:55:33.416  1029  1534 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-19 17:55:33.416  1029  1534 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-19 17:55:33.416  1937  1937 I WfdStateTracker: handleP2pThisDeviceChanged
08-19 17:55:33.416  1937  1937 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-19 17:55:33.416  1937  1937 D WfdsService: Update P2p Interface State: 3
,08-19 17:55:33.424  6308  6813 W FormManager: Network not available. Please check & try again.
08-19 17:55:33.424  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:33.424  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:33.424  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:33.424  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:33.424  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:33.424  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:33.424  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:33.424  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:33.424  4212  4212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-19 17:55:33.427  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:33.429  6789  6789 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-19 17:55:33.432  5974  6083 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-19 17:55:33.432  1029  1534 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-19 17:55:33.432  1029  1533 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-19 17:55:33.432  1029  1533 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-19 17:55:33.433  1029  1534 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-19 17:55:33.433  6106  6106 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-19 17:55:33.433  6106  6106 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-19 17:55:33.433  6106  6106 V [BNRBootReceiver]: Boot Receiver Return
08-19 17:55:33.433  1029  1534 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-19 17:55:33.433  1029  1534 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-19 17:55:33.433  5974  6083 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-19 17:55:33.433  6789  6789 E wpa_supplicant: disconnect_rssi_lvl: -100
08-19 17:55:33.433  1029  1533 D LGWifiP2pService: InactiveState
08-19 17:55:33.434  1029  1534 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-19 17:55:33.434  1029  1533 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.434  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.434  1029  1533 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-19 17:55:33.434  1029  1534 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-19 17:55:33.435  6789  6789 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-19 17:55:33.435  5974  6083 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7c7db88 Bundle[{}]
08-19 17:55:33.435  6789  6789 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:33.435  6789  6789 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-19 17:55:33.435  1029  6810 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-19 17:55:33.436  1029  6810 E WifiMonitor: WifiMonitor:p2p0 cnt=83 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:33.436  6789  6789 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.436  5974  6083 I io.jxcore.node.LifeCycleMonitor: start: OK
08-19 17:55:33.436  1029  6810 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:33.436  1029  6810 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:33.436  1029  6810 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:33.436  5974  6083 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-19 17:55:33.436  1029  6810 E WifiMonitor: WifiMonitor:p2p0 cnt=84 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.436  1029  6810 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.436  1029  6810 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.436  6789  6789 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.436  5974  6083 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-19 17:55:33.437  1937  6812 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-19 17:55:33.437  1937  6812 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:33.437  1937  6812 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:33.437  1029  6810 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:33.437,  1029  6810 E WifiMonitor: WifiMonitor:p2p0 cnt=85 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.437  1029  6810 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.437  1029  6810 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.437  5974  6083 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-19 17:55:33.437  1029  1534 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-19 17:55:33.437  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-19 17:55:33.438  1029  1533 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-19 17:55:33.438  5974  6083 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-19 17:55:33.438  1029  1533 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.438  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.438  1029  1533 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.438  1029  1533 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.438  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.438  1029  1533 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.438  1029  1533 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.439  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.439  5974  6083 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-19 17:55:33.439  1029  1533 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.439  6789  6789 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-19 17:55:33.439  1029  1533 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.439  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.439  1029  1533 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.439  6789  6789 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:33.439  6789  6789 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-19 17:55:33.439  1029  1029 E WifiServerServiceExt: No p2p device connected
08-19 17:55:33.440  6789  6789 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.440  1029  1534 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-19 17:55:33.440  6789  6789 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.440  1029  1534 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-19 17:55:33.441  6308  6814 V FormManager: Network unavailable.
08-19 17:55:33.441  1029  6810 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-19 17:55:33.441  1029  6810 E WifiMonitor: WifiMonitor:wlan0 cnt=86 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:33.441  1029  6810 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:33.441  1029  6810 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-19 17:55:33.441 , 1029  6810 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:33.441  1029  6810 E WifiMonitor: WifiMonitor:p2p0 cnt=87 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.441  1029  6810 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.441  1029  6810 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.441  1937  2308 W WfdsService: DefaultState - msg [9441285] is not handled
08-19 17:55:33.441  1937  6812 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:33.441  1937  6812 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:33.441  1029  6810 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-19 17:55:33.441  1029  6810 E WifiMonitor: WifiMonitor:p2p0 cnt=88 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.442  1029  6810 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.442  1029  6810 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-19 17:55:33.442  1029  1534 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-19 17:55:33.442  1029  1533 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.442  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.442  1029  1534 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-19 17:55:33.442  1029  1534 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-19 17:55:33.442  6789  6789 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-19 17:55:33.442  6789  6789 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-19 17:55:33.442  1029  6810 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-19 17:55:33.442  1029  6810 E WifiMonitor: WifiMonitor:wlan0 cnt=89 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-19 17:55:33.442  6308  6814 V FormManager: Network unavailable.
08-19 17:55:33.442  1029  6810 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-19 17:55:33.443  1029  6810 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-19 17:55:33.443  1029  1534 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-19 17:55:33.443  1029  1534 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-19 17:55:33.443  1029  1534 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-19 17:55:33.443  1029  1534 D WifiNative-wlan0: doBoolean: SCAN
08-19 17:55:33.444  5974  6083 I System.out: Running OutgoingSocketThread
08-19 17:55:33.445  4212  6816 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-19 17:55:33.445  5974  6817 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 766)
08-19 17:55:33.446  5974  6817 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47043
08-19 17:55:33.447  5974  6817 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-19 17:55:33.447  1029  1534 D WifiNative-wlan0: SCAN: returned false
08-19 17:55:33.448  1029  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 82 0 rt=135512  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-19 17:55:33.449  1029  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 82 0 rt=135513  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-19 17:55:33.449  1029  1534 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-19 17:55:33.449  4212  6818 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-19 17:55:33.449  4212  6818 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-19 17:55:33.450  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-19 17:55:33.450  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-19 17:55:33.452  1029  1534 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-19 17:55:33.452  1029  1534 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-19 17:55:33.452  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:33.452  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:55:33.452  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-19 17:55:33.453  1029  1534 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-19 17:55:33.453  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-19 17:55:33.453  1029  1534 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-19 17:55:33.457  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-19 17:55:33.457  1029  1029 D WifiServerServiceExt: setSupplicantStateSCANNING
08-19 17:55:33.457  3650  3650 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-19 17:55:33.463  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-19 17:55:33.467  6223  6223 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-19 17:55:33.472  6269  6269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-19 17:55:33.472  6269  6269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-19 17:55:33.473  6269  6269 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-19 17:55:33.947  6789  6789 I wpa_supplicant: [LGE_PATCH]scan interval[0] = 2 sec.
,08-19 17:55:33.956  1029  6810 E WifiMonitor: WifiMonitor:wlan0 cnt=90 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-19 17:55:33.957  1029  6810 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-19 17:55:33.957  1029  1534 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-19 17:55:33.958  1029  1534 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-19 17:55:33.958  1029  1534 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-19 17:55:33.959  1029  1534 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-19 17:55:33.959  1029  1534 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-19 17:55:33.959  1937  6812 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-19 17:55:33.960  1029  6810 E WifiMonitor: WifiMonitor:p2p0 cnt=91 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-19 17:55:33.961  1029  6810 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-19 17:55:33.963  1029  1533 D LGWifiP2pService: InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.963  1029  1533 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.963  1029  1533 D LGWifiP2pService: DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:33.974  6223  6223 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-19 17:55:33.983  6223  6223 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-19 17:55:34.448  5974  6083 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 767)
,08-19 17:55:34.448  5974  6083 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 767)
,08-19 17:55:34.467  5974  6083 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 772)
08-19 17:55:34.468  5974  6083 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-19 17:55:34.468  5974  6083 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 773)
08-19 17:55:34.471  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:34.471  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a9f1bf7 added. We now have 2 listener(s)
08-19 17:55:34.472  1029  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-19 17:55:34.477  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:55:34.477  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:34.477  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:34.477  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:34.477  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@284e5a64 added. We now have 9 listener(s)
08-19 17:55:34.478  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:34.478  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:55:34.481  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:34.484  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:34.484  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:34.484  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:34.484  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:34.484  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:34.484  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:34.484  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:34.484  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:34.489  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:34.489  5974  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:34.491  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:34.491  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:34.491  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39a75182 added. We now have 3 listener(s)
08-19 17:55:34.492  1029  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:34.494  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:55:34.494  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:34.494  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:34.494  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:34.495  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@139f8093 added. We now have 10 listener(s)
08-19 17:55:34.495  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:34.495  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:34.495  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:34.495  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:34.496  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:34.496  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.496  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:34.496  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:34.496  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a9f1bf7 removed from the list
08-19 17:55:34.496  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.496  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@284e5a64 removed from the list
08-19 17:55:34.496  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:34.496  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.499  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.499  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:34.504  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:34.504  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:34.504  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.504  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@284e5a64 not in the list
08-19 17:55:34.504  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.504  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.505  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:34.505  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:34.505  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.506  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@139f8093 removed from the list
08-19 17:55:34.506  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:34.506  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.506  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.506  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:34.506  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39a75182 removed from the list
08-19 17:55:34.507  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:34.507  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38c8b8d0 added. We now have 2 listener(s)
08-19 17:55:34.507  1029  1783 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:34.510  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:55:34.510  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:34.510  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:34.510  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:34.510  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a640c9 added. We now have 9 listener(s)
08-19 17:55:34.510  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:34.514  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:55:34.519  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:34.522  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:34.522  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:34.522  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:34.522  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:34.522  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:34.522  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:34.522  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:34.522  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:34.523  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:34.524  5974  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:55:34.527  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:34.528  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:34.528  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@323792ef added. We now have 3 listener(s)
08-19 17:55:34.528  1029  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:34.531  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:55:34.531  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:34.531  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:34.531  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:34.531  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@244891fc added. We now have 10 listener(s)
08-19 17:55:34.531  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:34.532  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:34.532  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:34.532  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:34.532  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:34.532  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:55:34.536  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:55:34.539  1029  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:34.545  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-19 17:55:34.546  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-19 17:55:34.547  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:55:34.548  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:55:34.551  5974  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-19 17:55:34.552  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:34.552  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:34.555  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:34.555  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:34.555  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:34.555  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:34.555  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.555  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:34.555  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:34.555  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38c8b8d0 removed from the list
08-19 17:55:34.556  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.556  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a640c9 removed from the list
08-19 17:55:34.556  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:34.556  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.556  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.556  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.557  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:34.557  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:34.557  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.557  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a640c9 not in the list
08-19 17:55:34.557  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.557  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.558  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:34.559  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:34.559  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:34.559  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:34.559  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.559  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryMa,nagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@244891fc removed from the list
08-19 17:55:34.559  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:34.559  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.559  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.559  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:34.559  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@323792ef removed from the list
08-19 17:55:34.560  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:34.560  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21946f0b added. We now have 2 listener(s)
,08-19 17:55:34.565  1029  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:34.569  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:55:34.569  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:34.569  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:34.569  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:34.570  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@338ad1e8 added. We now have 9 listener(s)
08-19 17:55:34.570  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:34.570  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:55:34.573  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:34.578  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:34.578  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:34.578  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:34.578  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:34.578  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:34.578  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:34.578  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:34.578  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:34.580  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:34.580  5974  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:34.581  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:34.582  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:34.582  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ee1bea6 added. We now have 3 listener(s)
08-19 17:55:34.582  1029  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:34.584  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:55:34.585  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:34.585  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:34.585  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:34.585  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@898f0e7 added. We now have 10 listener(s)
08-19 17:55:34.585  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:34.585  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:34.586  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:34.586  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:34.586  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:34.586  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:34.586  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-19 17:55:34.592  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-19 17:55:34.594  1029  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:34.598  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-19 17:55:34.598  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:55:34.601  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:55:34.602  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:34.614  5974  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-19 17:55:34.615  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:34.615  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:34.615  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:34.616  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:34.616  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.616  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:34.616  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:34.616  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21946f0b removed from the list
08-19 17:55:34.616  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.616  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@338ad1e8 removed from the list
08-19 17:55:34.616  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:34.616  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.617  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.617  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.618  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:34.618  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:34.618  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.618  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@338ad1e8 not in the list
08-19 17:55:34.618  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.618  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.619  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:34.619  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:34.619  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:34.619  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:34.619  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.619  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@898f0e7 removed from the list
08-1,9 17:55:34.619  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:34.619  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.620  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.620  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:34.620  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ee1bea6 removed from the list
08-19 17:55:34.620  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:34.620  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cdb1f32 added. We now have 2 listener(s)
08-19 17:55:34.621  1029  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:34.623  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:55:34.623  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:34.623  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:34.624  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-19 17:55:34.624  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f79b483 added. We now have 9 listener(s)
08-19 17:55:34.624  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:34.624  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:55:34.627  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:34.631  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:34.631  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-19 17:55:34.631  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:34.631  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:34.631  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:34.631  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:34.631  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:34.631  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:34.632  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:34.633  5974  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:55:34.634  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:34.634  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:34.634  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@443ee39 added. We now have 3 listener(s)
08-19 17:55:34.635  1029  1645 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-19 17:55:34.637  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:55:34.637  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:34.637  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:34.637  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:34.637  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c97fc7e added. We now have 10 listener(s)
08-19 17:55:34.637  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:34.637  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:34.637  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:34.637  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:34.637  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:34.637  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:55:34.641  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-19 17:55:34.643  1029  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:34.649  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:55:34.652  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-19 17:55:34.653  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:55:34.655  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:34.656  5974  6083 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-19 17:55:34.658  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:34.658  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:34.658  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:34.659  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:34.659  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.659  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:34.659  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:34.659  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cdb1f32 removed from the list
08-19 17:55:34.659  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.659  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f79b483 removed from the list
08-19 17:55:34.659  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:34.659  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.659  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.659  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.660  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:34.660  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:34.660  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.660  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f79b483 not in the list
08-19 17:55:34.661  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.661  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:34.663  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:34.664  5974  6083 D BluetoothLeScanner: could not find callback wrapper
08-19 17:55:34.664  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:34.664  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:34.664  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.664  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c97fc7e removed from the list
08-19 17:55:34.664  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:34.664  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.664  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.664  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:34.664  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@443ee39 removed from the list
08-19 17:55:34.665  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:34.665  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256c34f5 added. We now have 2 listener(s)
08-19 17:55:34.665  1029  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:34.668  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:55:34.668  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:34.668  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:34.668  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:34.668  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11b3628a added. We now have 9 listener(s)
08-19 17:55:34.668  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:34.668  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:55:34.671  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:34.673  5974  6083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:34.673  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:34.673  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-19 17:55:34.673  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:34.673  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:34.673  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:34.673  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
0,8-19 17:55:34.673  5974  6083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:34.675  5974  6083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:34.675  5974  6083 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:34.676  5974  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:34.677  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:34.677  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f0a8518 added. We now have 3 listener(s)
08-19 17:55:34.677  1029  1571 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-19 17:55:34.680  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-19 17:55:34.680  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:34.680  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:55:34.680  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:34.680  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4982b71 added. We now have 10 listener(s)
08-19 17:55:34.680  5974  6083 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:34.681  5974  6083 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:34.681  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:34.681  5974  6083 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:34.681  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:34.681  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.681  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:34.681  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:34.681  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256c34f5 removed from the list
08-19 17:55:34.681  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.681  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11b3628a removed from the list
08-19 17:55:34.681  5974  6083 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:34.681  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.682  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.682  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.683  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:34.683  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:34.683  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.683  5974  6083 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11b3628a not in the list
08-19 17:55:34.683  5974  6083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.683  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.684  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:34.684  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:34.684  5974  6083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:34.684  5974  6083 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4982b71 removed from the list
08-19 17:55:34.684  5974  6083 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:34.684  5974  6083 W org.thaliproject.p,2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:34.684  5974  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:34.684  5974  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:34.684  5974  6083 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f0a8518 removed from the list
08-19 17:55:34.685  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-19 17:55:34.685  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-19 17:55:34.686  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-19 17:55:34.686  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:34.686  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-19 17:55:34.686  5974  6083 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:55:34.698  5974  6839 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 780, name: My test thread name)
08-19 17:55:34.698  5974  6839 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 780, thread name: My test thread name)
08-19 17:55:34.699  5974  6839 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 780, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-19 17:55:34.702  5974  6840 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 782, name: My test thread name)
08-19 17:55:34.702  5974  6840 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 782, thread name: My test thread name)
08-19 17:55:34.702  5974  6840 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 782, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-19 17:55:34.704  5974  6083 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-19 17:55:34.704  5974  6083 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-19 17:55:34.705  5974  6083 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-19 17:55:34.705  5974  6083 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-19 17:55:34.705  5974  6083 D com.test.thalitest.ThaliTestRunner: Total duration: 23140 ms
08-19 17:55:34.706  5974  6083 I jxcore-log: Total number of executed tests:  80
08-19 17:55:34.706  5974  6083 I jxcore-log: 
08-19 17:55:34.706  5974  6083 I jxcore-log: Number of passed tests:  80
08-19 17:55:34.706  5974  6083 I jxcore-log: 
08-19 17:55:34.706  5974  6083 I jxcore-log: Number of failed tests:  0
08-19 17:55:34.706  5974  6083 I jxcore-log: 
08-19 17:55:34.707  5974  6083 I jxcore-log: Number of ignored tests:  0
08-19 17:55:34.707  5974  6083 I jxcore-log: 
08-19 17:55:34.707  5974  6083 I jxcore-log: Total duration:  23140
08-19 17:55:34.707  5974  6083 I jxcore-log: 
,08-19 17:55:34.708  5974  6083 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-19 17:55:34.708  5974  6083 I jxcore-log: 
08-19 17:55:34.712  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.712  5974  6083 I jxcore-log: 
08-19 17:55:34.715  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.715  5974  6083 I jxcore-log: 
08-19 17:55:34.717  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.717  5974  6083 I jxcore-log: 
08-19 17:55:34.718  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.718  5974  6083 I jxcore-log: 
08-19 17:55:34.719  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.719  5974  6083 I jxcore-log: 
08-19 17:55:34.721  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:34.721  5974  6083 I jxcore-log: 
,08-19 17:55:34.722  5974  5974 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-19 17:55:34.724  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:34.724  5974  6083 I jxcore-log: 
08-19 17:55:34.726  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-19 17:55:34.726  5974  6083 I jxcore-log: 
08-19 17:55:34.728  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.728  5974  6083 I jxcore-log: 
08-19 17:55:34.729  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.729  5974  6083 I jxcore-log: 
08-19 17:55:34.729  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:34.729  5974  6083 I jxcore-log: 
08-19 17:55:34.731  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:34.731  5974  6083 I jxcore-log: 
08-19 17:55:34.732  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:34.732  5974  6083 I jxcore-log: 
08-19 17:55:34.733  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:34.733  5974  6083 I jxcore-log: 
,08-19 17:55:34.734  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:34.734  5974  6083 I jxcore-log: 
08-19 17:55:34.734  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:34.734  5974  6083 I jxcore-log: 
08-19 17:55:34.735  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:34.735  5974  6083 I jxcore-log: 
08-19 17:55:34.736  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:34.736  5974  6083 I jxcore-log: 
08-19 17:55:34.737  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.737  5974  6083 I jxcore-log: 
08-19 17:55:34.738  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.738  5974  6083 I jxcore-log: 
08-19 17:55:34.739  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.739  5974  6083 I jxcore-log: 
08-19 17:55:34.739  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.739  5974  6083 I jxcore-log: 
08-19 17:55:34.740  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.740  5974  6083 I jxcore-log: 
08-19 17:55:34.741  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.741  5974  6083 I jxcore-log: 
08-19 17:55:34.742  5974  6083 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:34.742  5974  6083 I jxcore-log: 
08-19 17:55:35.079  6841  6841 D AndroidRuntime: 
08-19 17:55:35.079  6841  6841 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-19 17:55:35.090  6841  6841 D AndroidRuntime: CheckJNI is OFF
08-19 17:55:35.318  6841  6841 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-19 17:55:35.340  1029  1087 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-19 17:55:35.340  1029  1087 I ActivityManager: Killing 5974:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-19 17:55:35.412  1029  1883 I WindowState: WIN DEATH: Window{20ea81c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-19 17:55:35.423  1029  1540 D WifiService: Client connection lost with reason: 4
08-19 17:55:35.434  1029  1883 D InputDispatcher: Window went away: Window{20ea81c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-19 17:55:35.578  1029  1087 E libprocessgroup: failed to kill 1 processes for processgroup 5974
,08-19 17:55:35.586  1029  1087 I ActivityManager:   Force finishing activity ActivityRecord{2817c745 u0 com.test.thalitest/.MainActivity t6}
,08-19 17:55:35.620   346   355 E GBMv2   : DFP En is all cleared set to be enabled
,08-19 17:55:35.624  1029  1955 W ActivityManager: Spurious death for ProcessRecord{2dfd226b 5974:com.test.thalitest/u0a118}, curProc for 5974: null
08-19 17:55:35.625  1029  1108 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-19 17:55:35.632  1029  1108 I ActivityManager:   Force finishing activity ActivityRecord{2817c745 u0 com.test.thalitest/.MainActivity t6 f}
08-19 17:55:35.632  1029  1108 W ActivityManager: Duplicate finish request for ActivityRecord{2817c745 u0 com.test.thalitest/.MainActivity t6 f}
,08-19 17:55:35.678  2030  2030 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-19 17:55:35.680  2030  2030 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-19 17:55:35.683  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-19 17:55:35.685  2030  2121 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-19 17:55:35.689  1901  1901 D ActionManagerService: notifyUserLog: 1000003
08-19 17:55:35.689  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-19 17:55:35.690  2743  4367 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-19 17:55:35.691  1937  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-19 17:55:35.691  1937  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{79ad1c1 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-19 17:55:35.692  2030  2030 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-19 17:55:35.693  2030  2030 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-19 17:55:35.694  2030  2030 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-19 17:55:35.696  4485  4485 I art     : Explicit concurrent mark sweep GC freed 410(30KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 680us total 46.619ms
,08-19 17:55:35.699  1901  1901 D ActionManagerService: notifyUserLog: 1000004
08-19 17:55:35.699  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-19 17:55:35.699  1937  3186 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-19 17:55:35.699  2743  4367 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-19 17:55:35.700  1937  3186 D SplitWindowPolicy: topRunningActivity=ActivityInfo{251a4d66 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-19 17:55:35.701  2743  2767 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-19 17:55:35.703  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-19 17:55:35.711  1029  1457 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-19 17:55:35.715  1992  1992 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-19 17:55:35.715  2743  2743 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-19 17:55:35.717  6634  6634 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-19 17:55:35.717  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-19 17:55:35.722  2465  2609 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-19 17:55:35.763  1599  1599 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-19 17:55:35.765  3650  3650 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-19 17:55:35.766  4375  4375 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-19 17:55:35.767  4375  4375 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-19 17:55:35.767  4375  4375 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-19 17:55:35.767  4375  4375 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-19 17:55:35.767  4375  4375 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:55:35.767  4375  4375 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:55:35.767  4375  4375 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-19 17:55:35.767  4375  4375 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-19 17:55:35.767  4375  4375 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-19 17:55:35.767  4375  4375 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:55:35.767  4375  4375 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-19 17:55:35.767  4375  4375 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , create_time: 1430832262123
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , display: false
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , animation: false }
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , create_time: 1430832262287
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , display: false
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , animation: false }
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , create_time: 1471602816196
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , display: false
08-19 17:55:35.771  2030  2030 I GBoardWebViewUtils: , animation: false }
08-19 17:55:35.771  1814  1814 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-19 17:55:35.771  1599  1662 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-19 17:55:35.771  1599  1662 D KeyguardModel: createShortcutInfo...
08-19 17:55:35.775  1599  1662 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-19 17:55:35.775  1599  1662 D KeyguardModel: createShortcutInfo...
08-19 17:55:35.780  2177  2177 I ConfigService: onCreate
08-19 17:55:35.780  2177  2177 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-19 17:55:35.782  1599  1662 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-19 17:55:35.789  1599  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-19 17:55:35.789  1599  1662 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-19 17:55:35.790  1599  1662 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-19 17:55:35.795  2030  6872 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-19 17:55:35.795  2177  2177 I ConfigService: onBind returning update interface
08-19 17:55:35.803  1814  1814 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-19 17:55:35.804  2177  2177 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-19 17:55:35.804  2177  2177 I ConfigService: onBind returning config service
08-19 17:55:35.805  1599  1599 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-19 17:55:35.805  1599  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-19 17:55:35.805  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-19 17:55:35.805  1599  1662 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-19 17:55:35.807   318  6873 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-19 17:55:35.808  1029  1089 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-19 17:55:35.811  1814  1814 I ConfigFetchService: service connected
08-19 17:55:35.811  1814  1814 I ConfigClient: service connected
,08-19 17:55:35.815  1599  1662 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-19 17:55:35.815  1599  1662 D KeyguardModel: createShortcutInfo...
08-19 17:55:35.820  1599  1662 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-19 17:55:35.820  1599  1662 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-19 17:55:35.820  1866  1866 D SplitUIManager: split_name #11 / not available #0
08-19 17:55:35.821  1599  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-19 17:55:35.821  1599  1662 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-19 17:55:35.821  1866  1866 D SplitUIService: removed split : 
08-19 17:55:35.825  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-19 17:55:35.829  1029  1045 V SIM_STK : Menu title from STK is T-Mobile
,08-19 17:55:35.834  1029  1086 W InputMethodInfo: Duplicated subtype definition found: , voice
08-19 17:55:35.835  2177  2177 I ConfigService: onDestroy
08-19 17:55:35.836  1814  6876 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-19 17:55:35.846  1599  1662 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-19 17:55:35.846  1599  1662 D KeyguardModel: createShortcutInfo...
,08-19 17:55:35.859  1599  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-19 17:55:35.859  1599  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-19 17:55:35.859  1599  1662 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-19 17:55:35.859  1599  1662 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-19 17:55:35.863  1599  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-19 17:55:35.863  1599  1662 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-19 17:55:35.875  1029  1029 I art     : Explicit concurrent mark sweep GC freed 46260(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.770ms total 198.024ms
,08-19 17:55:35.880  1029  1108 I art     : WaitForGcToComplete blocked for 203.659ms for cause Explicit
08-19 17:55:35.881  1599  1662 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-19 17:55:35.881  1599  1662 D KeyguardModel: createShortcutInfo...
08-19 17:55:35.889  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-19 17:55:35.895  2030  2030 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-19 17:55:35.902  1029  1955 V SIM_STK : Menu title from STK is T-Mobile
08-19 17:55:35.902  1029  1955 V SIM_STK : Menu title from STK is T-Mobile
08-19 17:55:35.904  1866  1866 D SplitUIManager: split_name #11 / not available #0
08-19 17:55:35.905  1866  1866 I SplitUIService: split app #11
08-19 17:55:35.909  5529  6880 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-19 17:55:35.916  1029  1046 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6882 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-19 17:55:35.921  2030  2046 I art     : Background partial concurrent mark sweep GC freed 7035(321KB) AllocSpace objects, 5(19MB) LOS objects, 34% free, 60MB/92MB, paused 5.685ms total 39.481ms
08-19 17:55:35.921  1599  1599 D KeyguardModel: handleShortcutListChanged...
08-19 17:55:35.921  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-19 17:55:35.925  1599  1662 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-19 17:55:35.925  1599  1662 D KeyguardModel: createShortcutInfo...
08-19 17:55:35.929  1599  1662 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-19 17:55:35.929  1599  1662 D KeyguardModel: createShortcutInfo...
08-19 17:55:35.930  1599  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-19 17:55:35.930  1599  1662 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-19 17:55:35.932  1599  1662 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-19 17:55:35.932  1599  1662 D KeyguardModel: createShortcutInfo...
08-19 17:55:35.933  1599  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-19 17:55:35.934  1599  1662 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-19 17:55:35.935   333   412 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-19 17:55:35.935  1599  1662 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-19 17:55:35.935  1599  1662 D KeyguardModel: createShortcutInfo...
08-19 17:55:35.936  3215  6899 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-19 17:55:35.936  1599  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-19 17:55:35.937  1599  1662 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-19 17:55:35.938  1599  1662 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-19 17:55:35.938  1599  1662 D KeyguardModel: createShortcutInfo...
08-19 17:55:35.940  1814  6881 W GmsApplication: Using Auth Proxy for data requests.
08-19 17:55:35.945  1814  6881 W GmsApplication: Using Auth Proxy for data requests.
,08-19 17:55:35.949  6789  6789 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-19 17:55:35.950  1029  6810 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-19 17:55:35.950  1029  6810 E WifiMonitor: WifiMonitor:wlan0 cnt=92 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-19 17:55:35.950  1029  6810 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-19 17:55:35.950  1029  6810 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-19 17:55:35.955  1814  6901 I PeopleContactsSync: CP2 sync disabled
08-19 17:55:35.956  1029  1955 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-19 17:55:35.957  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-19 17:55:35.957  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-19 17:55:35.957  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-19 17:55:35.957  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-19 17:55:35.957  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-19 17:55:35.957  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-19 17:55:35.957  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-19 17:55:35.957  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-19 17:55:35.957  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-19 17:55:35.957  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-19 17:55:35.957  6634  6634 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-19 17:55:35.959  1814  4551 I Icing   : doRemovePackageData com.test.thalitest
,08-19 17:55:35.974  1599  1599 D KeyguardModel: handleShortcutListChanged...
08-19 17:55:35.974  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-19 17:55:35.977  1029  1645 V SIM_STK : Menu title from STK is T-Mobile
,08-19 17:55:36.012  1029  1029 D administrator: Handling package changes for user 0
,08-19 17:55:36.035  6882  6882 I AppUp4:AppBoxCP: onCreate
,08-19 17:55:36.035  6882  6882 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-19 17:55:36.041  6882  6882 I AppUp4:DB:  setFingerPrint start
08-19 17:55:36.041  6882  6882 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-19 17:55:36.051  6882  6882 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-19 17:55:36.052  6882  6882 I AppUp4:DB:  SDK version = 21
08-19 17:55:36.052  6882  6882 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-19 17:55:36.054  6882  6882 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-19 17:55:36.065  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-19 17:55:36.067  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-19 17:55:36.069  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-19 17:55:36.070  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-19 17:55:36.071  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-19 17:55:36.072  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-19 17:55:36.087  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-19 17:55:36.088  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-19 17:55:36.090  1029  1092 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ab46d1c u0 com.lge.launcher2/.Launcher t5} time:138167
08-19 17:55:36.098  2030  2792 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-19 17:55:36.098  2030  2792 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-19 17:55:36.099  1814  1826 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-19 17:55:36.101  1814  6895 I art     : Explicit concurrent mark sweep GC freed 14471(926KB) AllocSpace objects, 9(144KB) LOS objects, 51% free, 29MB/61MB, paused 1.363ms total 33.184ms
08-19 17:55:36.101  1814  1826 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-19 17:55:36.102  1814  1826 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-19 17:55:36.103  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-19 17:55:36.103  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-19 17:55:36.103  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-19 17:55:36.108  1029  1029 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-19 17:55:36.108  1029  1029 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-19 17:55:36.108  1029  1029 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-19 17:55:36.110  1029  1573 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-19 17:55:36.110  2030  2030 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-19 17:55:36.111  2594  2594 D [Concierge]Service: onStartCommand(). Type : 8
08-19 17:55:36.111  2594  2594 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-19 17:55:36.112  2594  2594 D [Concierge]Service: Update widget ID : 11
08-19 17:55:36.114  2030  2030 D [Concierge]WidgetView: change position of spinner
08-19 17:55:36.114  6882  6882 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-19 17:55:36.115  2030  2030 I [Concierge]WidgetView: initWebView(). Time : 1471622136115
08-19 17:55:36.115  2594  2594 D [Concierge]Service: onStartCommand(). Type : 0
08-19 17:55:36.118  1029  1108 I art     : Explicit concurrent mark sweep GC freed 6930(364KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 5.166ms total 233.729ms
08-19 17:55:36.134  1029  1046 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6906 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-19 17:55:36.150  2030  2030 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 359548576
08-19 17:55:36.150  2030  2030 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-19 17:55:36.150  2030  2030 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-19 17:55:36.153  2030  2030 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2f868c9a
08-19 17:55:36.153  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-19 17:55:36.154  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-19 17:55:36.154  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-19 17:55:36.159  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-19 17:55:36.160  2030  2030 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-19 17:55:36.160  2030  2030 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-19 17:55:36.161  2030  2030 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471622025919, New one : 1471622136115
08-19 17:55:36.161  2030  2030 D [Concierge]WidgetView: Unregister all receivers
08-19 17:55:36.161  2030  2030 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-19 17:55:36.162  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-19 17:55:36.164  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-19 17:55:36.165  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-19 17:55:36.166  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-19 17:55:36.167  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-19 17:55:36.168  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-19 17:55:36.171  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-19 17:55:36.171  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-19 17:55:36.179  6906  6906 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-19 17:55:36.179  6906  6906 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-19 17:55:36.179  6906  6906 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-19 17:55:36.181  6906  6906 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-19 17:55:36.181  6906  6906 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-19 17:55:36.209  6841  6841 D AndroidRuntime: Shutting down VM
,08-19 17:55:36.214  2030  2030 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-19 17:55:36.222  2030  2030 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-19 17:55:36.222  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-19 17:55:36.224  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-19 17:55:36.227  1029  1086 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-19 17:55:36.234  1029  1086 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-19 17:55:36.241  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-19 17:55:36.248  2030  2030 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f205406 time:138325
,08-19 17:55:36.252  6906  6906 I SystemConfig: BUILD Country: EU
08-19 17:55:36.252  6906  6906 I SystemConfig: BUILD Operator: OPEN
08-19 17:55:36.284  1029  1982 I ActivityManager: Killing 5934:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-19 17:55:36.359  2030  2030 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-19 17:55:36.374  1029  2029 W libprocessgroup: failed to open /acct/uid_10061/pid_5934/cgroup.procs: No such file or directory
,08-19 17:55:36.378  6906  6924 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-19 17:55:36.378  6906  6924 I SystemConfig: existFile = false
08-19 17:55:36.378  6906  6924 I SystemConfig: canReadFile = false
08-19 17:55:36.378  6906  6924 I SystemConfig: systemFeature RCS result false
08-19 17:55:36.378  6906  6924 D SystemConfig: refreshRcsSupport() :false
08-19 17:55:36.381  2330  6926 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-19 17:55:36.399  2030  2838 I GBoardtInterface: onReloaded()
,08-19 17:55:36.401  2030  2030 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-19 17:55:36.407  1029  1996 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6927 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-19 17:55:36.408  2743  4355 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-19 17:55:36.410  2743  2767 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-19 17:55:36.415  1901  1901 D ActionManagerService: notifyUserLog: 1000001
08-19 17:55:36.416  2743  4367 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-19 17:55:36.416  2743  4367 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-19 17:55:36.419  1901  1901 D ActionManagerService: notifyUserLog: 1000001
08-19 17:55:36.420  2743  4367 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-19 17:55:36.420  2743  4367 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-19 17:55:36.420  2743  4367 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-19 17:55:36.420  2743  4367 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-19 17:55:36.421  2743  4355 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-19 17:55:36.422  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-19 17:55:36.423  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-19 17:55:36.424  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-19 17:55:36.424  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-19 17:55:36.426  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-19 17:55:36.426  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-19 17:55:36.439  6927  6927 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-19 17:55:36.439  6927  6927 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-19 17:55:36.440  6927  6927 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-19 17:55:36.440  6927  6927 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-19 17:55:36.458  1029  1108 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6944 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-19 17:55:36.490  6927  6927 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-19 17:55:36.498  1029  1955 I ActivityManager: Killing 6031:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-19 17:55:36.511  6927  6927 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-19 17:55:36.531  6927  6927 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-19 17:55:36.543  1029  1919 W libprocessgroup: failed to open /acct/uid_10097/pid_6031/cgroup.procs: No such file or directory
,08-19 17:55:36.560  6927  6927 D LgDataFeature: LgDataFeature() Constructor: none
08-19 17:55:36.561  6927  6927 D LgDataFeature: LgDataFeature() Constructor Done, null

```
