#### Test 79763830cfa9ed9_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-26 15:42:31.314  6643  6643 D DocsApplication: Installing DEX configuration.
08-26 15:42:31.334  6643  6643 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-26 15:42:31.339  6643  6643 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{6a9115d com.google.android.apps.docs}
08-26 15:42:31.356  6643  6643 D TAG     : onCreate()
08-26 15:42:31.390  6643  6643 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-26 15:42:32.021   305   305 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
08-26 15:42:32.021   305   305 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
08-26 15:42:32.022   305   305 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 15:42:32.022   305   912 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
08-26 15:42:32.120   305   912 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
08-26 15:42:32.120   305   912 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
08-26 15:42:32.120   305   912 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
08-26 15:42:32.120   305   912 I rmt_storage: 
,08-26 15:42:32.122   305   305 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
08-26 15:42:32.123   889   911 E Diag_Lib: [IMS_FATAL]| 3347 | 911 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-26 15:42:32.228  1816  4783 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-26 15:42:32.287  1816  4783 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-26 15:42:32.387  6671  6671 D AndroidRuntime: 
08-26 15:42:32.387  6671  6671 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 15:42:32.389  6671  6671 D AndroidRuntime: CheckJNI is OFF
08-26 15:42:32.404  1816  4783 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-26 15:42:32.492  6671  6671 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 15:42:32.495  1032  1960 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 15:42:32.525  1943  4008 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-26 15:42:32.528  1032  1960 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-26 15:42:32.530  1032  1960 D ActivityManager: setTaskToReturnTo : TaskRecord{25566bfa #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 15:42:32.531  1032  1960 D ActivityManager: setTaskToReturnTo : TaskRecord{25566bfa #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 15:42:32.532  1032  1960 D WindowStateEx: AppWindowTokenEx init.. 
08-26 15:42:32.533   335   387 E GBMv2   : DFP En is all cleared set to be enabled
08-26 15:42:32.578  1032  1960 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6697 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 15:42:32.580  6671  6671 D AndroidRuntime: Shutting down VM
08-26 15:42:32.654  1943  4008 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-26 15:42:32.655  1943  4008 D SplitWindowPolicy: topRunningActivity=ActivityInfo{33aeac69 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 15:42:32.656  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-26 15:42:32.656  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3c1d96ee co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 15:42:32.662  6643  6643 D LgDataFeature: LgDataFeature() Constructor: none
08-26 15:42:32.662  6643  6643 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 15:42:32.701  6697  6697 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 15:42:32.773  6697  6697 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 15:42:32.781  6697  6697 I LibraryLoader: Loading: webviewchromium
08-26 15:42:32.783  6697  6697 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2131-2134)
08-26 15:42:32.784  6697  6697 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 15:42:32.804  6697  6697 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4639aff}
,08-26 15:42:32.805  6697  6697 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 15:42:32.806  6697  6697 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 15:42:32.815  6697  6697 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 15:42:32.816  6697  6697 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:42:32.839   317  1737 V AudioPolicyService: registerClient() client 0xb0410220, uid 10118
,08-26 15:42:32.840  6697  6697 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 15:42:32.841  6697  6697 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-26 15:42:32.841  6697  6697 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-26 15:42:32.845  1032  1095 D BluetoothManagerService: Message: 20
08-26 15:42:32.845  1032  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ab818b4:true
08-26 15:42:32.862  6161  6161 I LockScreenSettings: New app installed broadcast received ..
08-26 15:42:32.862  6697  6697 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 15:42:32.862  6697  6697 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 15:42:32.862  6697  6697 I Adreno-EGL: Build Date: 12/12/14 금
08-26 15:42:32.862  6697  6697 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 15:42:32.862  6697  6697 I Adreno-EGL: Remote Branch: 
08-26 15:42:32.862  6697  6697 I Adreno-EGL: Local Patches: 
08-26 15:42:32.862  6697  6697 I Adreno-EGL: Reconstruct Branch: 
,08-26 15:42:32.865  6161  6161 I LockScreenSettings: Number of installed packages  1
08-26 15:42:32.880  6643  6643 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-26 15:42:32.916  1032  2034 V SIM_STK : Menu title from STK is T-Mobile
,08-26 15:42:32.961  1032  2015 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6744 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 15:42:32.973  6697  6730 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-26 15:42:32.975  6697  6697 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-26 15:42:32.993  6697  6697 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:42:32.998  6697  6697 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 15:42:33.001  6697  6697 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-26 15:42:33.004  6697  6697 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 15:42:33.004  6697  6697 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-26 15:42:33.015  6744  6744 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-26 15:42:33.015  6744  6744 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-26 15:42:33.020  6697  6697 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-26 15:42:33.085  1032  1890 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6763 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 15:42:33.087  1032  1890 I ActivityManager: Killing 5851:com.google.android.gm/u0a64 (adj 15): empty #17
08-26 15:42:33.089  6697  6697 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:42:33.089  6697  6697 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:42:33.151  1032  2015 W libprocessgroup: failed to open /acct/uid_10064/pid_5851/cgroup.procs: No such file or directory
,08-26 15:42:33.154  1032  1091 W ActivityManager: Activity pause timeout for ActivityRecord{380e55ab u0 com.test.thalitest/.MainActivity t6}
08-26 15:42:33.168  6697  6791 D OpenGLRenderer: Render dirty regions requested: true
08-26 15:42:33.168  6697  6791 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 15:42:33.180  6697  6791 D OpenGLRenderer: Enabling debug mode 0
,08-26 15:42:33.186  6697  6697 D Atlas   : Validating map...
08-26 15:42:33.189  6697  6782 D LgDataFeature: LgDataFeature() Constructor: none
08-26 15:42:33.189  6697  6782 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 15:42:33.190  1032  1047 D SplitWindow: check instance of lgWin Window{3fd0058b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 15:42:33.225  6763  6763 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-26 15:42:33.241  6697  6697 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@cbc49da time:102592
,08-26 15:42:33.250  6763  6763 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 15:42:33.252  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-26 15:42:33.263  1032  1096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +612ms (total +729ms)
08-26 15:42:33.264  1032  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{380e55ab u0 com.test.thalitest/.MainActivity t6} time:102615
08-26 15:42:33.275  1032  1937 I ActivityManager: Killing 5889:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 15:42:33.341  1032  2034 W libprocessgroup: failed to open /acct/uid_10072/pid_5889/cgroup.procs: No such file or directory
,08-26 15:42:33.384  6697  6697 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-26 15:42:33.384  6697  6697 I chromium: 
,08-26 15:42:33.409  6697  6697 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 15:42:33.511  6697  6782 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-26 15:42:33.511  6697  6782 I chromium: 
,08-26 15:42:33.664  6697  6801 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435055616
,08-26 15:42:33.681  6697  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 15:42:33.681  6697  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 15:42:33.681  6697  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 15:42:33.681  6697  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 15:42:33.681  6697  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 15:42:33.681  6697  6801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dfdc77e added. We now have 1 listener(s)
,08-26 15:42:33.689  1032  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:42:33.691  6697  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-26 15:42:33.696  6697  6801 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-26 15:42:33.698  6697  6801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:42:33.699  6697  6801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 15:42:33.708  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 15:42:33.709  6697  6801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3278bbf5 added. We now have 1 listener(s)
,08-26 15:42:33.709  6697  6801 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:42:33.714  1032  1544 D WifiService: New client listening to asynchronous messages
08-26 15:42:33.719  6697  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:42:33.720  6697  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 15:42:33.722  6697  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 15:42:33.722  6697  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 15:42:33.722  6697  6801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 15:42:33.730  6697  6801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:33.731  1032  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:42:33.732  6697  6801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-26 15:42:33.749  6697  6801 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-26 15:42:33.749  6697  6801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:33.749  6697  6801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:33.749  6697  6801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:33.749  6697  6801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:33.749  6697  6801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:33.749  6697  6801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:33.749  6697  6801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:33.749  6697  6801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:33.750  6697  6801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 15:42:33.750  6697  6801 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:33.754  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:33.755  6697  6801 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 15:42:33.756  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:33.797  6697  6697 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 15:42:34.469   335   389 E GBMv2   : DFP En is all cleared set to be enabled
08-26 15:42:34.469   335   389 E GBMv2   : Set value is all cleared set the max
08-26 15:42:34.469   335   389 I GBMv2   : DFP Enabled. Ignore VFP set
,08-26 15:42:34.767  6697  6804 W jxcore-log: Initializing JXcore engine
08-26 15:42:34.767  6697  6804 W jxcore-log: JXcore engine is ready
,08-26 15:42:34.839  6804  6804 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8965]" dev="sockfs" ino=8965 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-26 15:42:34.839  6804  6804 W Thread-762: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2864 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-26 15:42:34.839  6804  6804 W Thread-762: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[9197]" dev="sockfs" ino=9197 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 15:42:34.839  6804  6804 W Thread-762: type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-26 15:42:34.839  6804  6804 W Thread-762: type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[32834]" dev="sockfs" ino=32834 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-26 15:42:34.877  6697  6804 W jxcore-log: Starting JXcore engine
,08-26 15:42:35.060  6697  6804 W jxcore-log: Platform android
08-26 15:42:35.060  6697  6804 W jxcore-log: 
08-26 15:42:35.060  6697  6804 W jxcore-log: Process ARCH arm
08-26 15:42:35.060  6697  6804 W jxcore-log: 
,08-26 15:42:35.305  6697  6804 I jxcore-log: JXcore Cordova bridge is ready!
08-26 15:42:35.305  6697  6804 I jxcore-log: 
08-26 15:42:35.305  6697  6804 W jxcore-log: JXcore engine is started
,08-26 15:42:35.313  6697  6801 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 15:42:35.322  6697  6697 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 15:42:36.642  2783  2783 I MusicWidget: mDelayedStopHandler : unbind
,08-26 15:42:36.660  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-26 15:42:36.661  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-26 15:42:36.661  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,08-26 15:42:36.690  2131  2131 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-26 15:42:36.690  2131  2131 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-26 15:42:36.690  2131  2131 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,08-26 15:42:36.740  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-26 15:42:36.740  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,08-26 15:42:36.781  1032  1996 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2ec014fccom.lge.music.MediaPlaybackService$5@2515e785
,08-26 15:42:36.784  2131  2131 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-26 15:42:36.785  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 15:42:36.787  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 15:42:36.789  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 15:42:36.791  2131  2131 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3ee0e81b
08-26 15:42:36.792  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 15:42:36.794  2131  2131 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-26 15:42:36.794  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 15:42:36.799  2131  2131 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-26 15:42:36.799  2131  2131 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-26 15:42:36.799  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 15:42:36.800  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 15:42:36.801  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 15:42:36.802  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 15:42:36.802  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 15:42:36.804  2131  2131 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-26 15:42:36.805  2131  2131 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-26 15:42:36.806  2131  2131 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-26 15:42:36.806  2131  2131 V MediaPlayer[Native]: reset
08-26 15:42:36.813  2131  2131 V MediaPlayer[Native]: setListener
08-26 15:42:36.813  2131  2131 V MediaPlayer[Native]: disconnect
08-26 15:42:36.813  2131  2131 V MediaPlayer[Native]: destructor
,08-26 15:42:36.815   317  1737 V AudioFlinger: releasing 18 from 2131 for -1
08-26 15:42:36.815   317  1737 V AudioFlinger:  decremented refcount to 0
08-26 15:42:36.815   317  1737 V AudioFlinger: purging stale effects
08-26 15:42:36.816  2131  2131 V MediaPlayer[Native]: disconnect
08-26 15:42:36.817  2131  2131 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-26 15:42:36.822  2131  2131 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-26 15:42:36.824  6643  6643 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-26 15:42:36.827  1032  1924 I ActivityManager: Killing 5702:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-26 15:42:36.838  2131  2131 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
,08-26 15:42:36.840  2131  2131 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-26 15:42:36.841  2131  2131 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-26 15:42:36.841  2131  2131 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-26 15:42:36.842  2131  2131 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 213666266
08-26 15:42:36.842  2131  2131 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 213666266
08-26 15:42:36.849  2131  2131 I SmartShareClient: [SmartShareManagerClient] terminate service: 2131/MediaPlaybackService/90859097
08-26 15:42:36.853  2131  2131 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-26 15:42:36.853  2131  2131 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3480e0b
08-26 15:42:36.858  5679  5679 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-26 15:42:36.859  5679  5679 W System.err: android.os.DeadObjectException
08-26 15:42:36.859  5679  5679 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 15:42:36.859  5679  5679 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 15:42:36.859  5679  5679 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 15:42:36.859  5679  5679 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 15:42:36.859  5679  5679 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 15:42:36.859  5679  5679 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 15:42:36.859  5679  5679 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:42:36.859  5679  5679 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:42:36.859  5679  5679 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:42:36.859  5679  5679 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 15:42:36.859  5679  5679 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:36.859  5679  5679 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:36.859  5679  5679 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 15:42:36.860  5679  5679 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 15:42:36.860  5679  5679 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 15:42:36.861  5679  5679 W System.err: android.os.DeadObjectException
08-26 15:42:36.861  5679  5679 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 15:42:36.861  5679  5679 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 15:42:36.861  5679  5679 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 15:42:36.861  5679  5679 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 15:42:36.861  5679  5679 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 15:42:36.861  5679  5679 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 15:42:36.861  5679  5679 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:42:36.861  5679  5679 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:42:36.862  5679  5679 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:42:36.862  5679  5679 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 15:42:36.862  5679  5679 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:36.862  5679  5679 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:36.862  5679  5679 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 15:42:36.862  5679  5679 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 15:42:36.862  5679  5679 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 15:42:36.862  5679  5679 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-26 15:42:37.038  1032  1924 E libprocessgroup: failed to kill 1 processes for processgroup 5702
,08-26 15:42:37.043  2131  2131 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
,08-26 15:42:37.044  2131  2131 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,08-26 15:42:37.046  2131  2131 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,08-26 15:42:37.047  2131  2131 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,08-26 15:42:37.169  1032  2015 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 15:42:37.173  5679  5679 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,08-26 15:42:37.173  5679  5679 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-26 15:42:37.192  2131  2131 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29855
,08-26 15:42:37.229  1032  1882 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6832 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 15:42:37.229  1032  1625 I ActivityManager: Killing 5679:com.lge.qremote/u0a112 (adj 15): empty #17
,08-26 15:42:37.351  1032  1890 W libprocessgroup: failed to open /acct/uid_10112/pid_5679/cgroup.procs: No such file or directory
,08-26 15:42:37.440  6832  6832 D UEI.SmartControl: Quickset Services start...
08-26 15:42:37.442  6832  6832 I UEI.SmartControl: Manufacture = LGE
08-26 15:42:37.442  6832  6832 D UEI.SmartControl: Id = LGNevo
08-26 15:42:37.443  6832  6832 D UEI.SmartControl: File observer start...
,08-26 15:42:37.449  6832  6832 E UEI.SmartControl: IR Port is disabled: false
08-26 15:42:37.450  6832  6832 D UEI.SmartControl: Starting file observer...
08-26 15:42:37.450  6832  6832 D UEI.SmartControl: Extracting JNI libs...
08-26 15:42:37.450  6832  6832 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 15:42:37.539  6832  6832 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 15:42:37.539  6832  6832 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 15:42:37.540  6832  6832 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 15:42:37.579  6832  6832 I UEI.SmartControl: --- Selecting new region: 6
,08-26 15:42:37.582  6832  6832 I UEI.SmartControl: Model = LG-D855
08-26 15:42:37.583  6832  6832 D UEI.SmartControl: QS Service created
,08-26 15:42:37.602  6832  6832 I UEI.SmartControl: Service initServices...
,08-26 15:42:37.607  6832  6832 D UEI.SmartControl: QS start get config
08-26 15:42:37.683  6832  6832 D UEI.SmartControl: Loading JNI Libs...
,08-26 15:42:37.737  6643  6714 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 15:42:37.982  6832  6832 I UEI.SmartControl: Supports setup maps: true
08-26 15:42:37.985  6832  6832 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 15:42:37.985  6832  6832 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 15:42:37.985  6832  6832 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 15:42:37.985  6832  6832 I UEI.SmartControl: ### init IR Blaster...
,08-26 15:42:37.991  6832  6832 D serial_port: Configuring serial port
08-26 15:42:38.005  6832  6832 E UEI.SmartControl: UEIBLaster setting for 616
08-26 15:42:38.005  6832  6832 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 15:42:38.006  6832  6832 I UEI.SmartControl: configuring settings for MAXQ616
08-26 15:42:38.007  6832  6832 I UEI.SmartControl: Get version...
,08-26 15:42:38.024  6832  6857 D UEI.SmartControl: serial port data available: 21
,08-26 15:42:38.053  6832  6832 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 15:42:38.053  6832  6832 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 15:42:38.053  6832  6832 I UEI.SmartControl: QS saving settings...
08-26 15:42:38.055  6832  6832 D UEI.SmartControl: IR Blaster version: 25672567
08-26 15:42:38.072  6832  6857 D UEI.SmartControl: serial port data available: 4
,08-26 15:42:38.107  6832  6860 I UEI.SmartControl: Device manager: loading config....
,08-26 15:42:38.108  6832  6860 D UEI.SmartControl: ----------- loading internal config...
08-26 15:42:38.110  6832  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 15:42:38.115  6832  6832 E UEI.SmartControl: Services init done
08-26 15:42:38.115  6832  6832 D UEI.SmartControl: QS Service init finished
08-26 15:42:38.119  6832  6832 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 15:42:38.119  6832  6832 D UEI.SmartControl: QS Service version code: 201091
08-26 15:42:38.124  6832  6832 D UEI.SmartControl: Service requested: Control
08-26 15:42:38.131  6832  6860 E UEI.SmartControl: Loading SETTINGS...
,08-26 15:42:38.135  6832  6832 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 15:42:38.141  1032  1890 I ActivityManager: Killing 6367:com.android.calendar/u0a13 (adj 15): empty #17
08-26 15:42:38.150  6832  6860 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 15:42:38.165  6832  6859 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 15:42:38.165  6832  6859 D UEI.SmartControl: -----service ready thread exits
,08-26 15:42:38.291  1032  1996 W libprocessgroup: failed to open /acct/uid_10013/pid_6367/cgroup.procs: No such file or directory
,08-26 15:42:38.292  6832  6832 D UEI.SmartControl: Internal service binding...
,08-26 15:42:40.395  1816  6551 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 15:42:40.411   313  6874 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-26 15:42:40.412   313  6874 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-26 15:42:40.412   313  6874 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-26 15:42:40.665  1816  1816 I ConfigFetchService: fetch service done; releasing wakelock
08-26 15:42:40.666  1816  1816 I ConfigFetchService: stopping self
,08-26 15:42:40.669  2229  2229 I ConfigService: onDestroy
,08-26 15:42:43.109  6832  6861 D UEI.SmartControl: Internal timer expired: 1
,08-26 15:42:43.109  6832  6861 D UEI.SmartControl: unbind internal service
,08-26 15:42:43.117  6832  6832 D UEI.SmartControl: Service.onUnbind: IControl
08-26 15:42:43.118  6832  6832 D UEI.SmartControl: Service.onDestroy
08-26 15:42:43.119  6832  6832 D UEI.SmartControl: Lock is in USE false
08-26 15:42:43.119  6832  6832 D UEI.SmartControl: unbind internal service
08-26 15:42:43.120  6832  6832 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3ee0e81b
08-26 15:42:43.120  6832  6832 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-26 15:42:43.121  6832  6832 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-26 15:42:43.121  6832  6832 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-26 15:42:43.121  6832  6832 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-26 15:42:43.121  6832  6832 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-26 15:42:43.121  6832  6832 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-26 15:42:43.121  6832  6832 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-26 15:42:43.121  6832  6832 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-26 15:42:43.121  6832  6832 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:43.121  6832  6832 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:42:43.122  6832  6832 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 15:42:43.122  6832  6832 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:43.122  6832  6832 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:43.122  6832  6832 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 15:42:43.122  6832  6832 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 15:42:43.122  6832  6832 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3ee0e81b
08-26 15:42:43.123  6832  6832 D serial_port: close(fd = 25)
08-26 15:42:43.130  6832  6832 I UEI.SmartControl: Serial port is closed.
08-26 15:42:43.130  6832  6832 I UEI.SmartControl: Serial port is closed.
08-26 15:42:43.130  6832  6832 D UEI.SmartControl: Blaster closed
,08-26 15:42:43.130  6832  6832 D UEI.SmartControl: Shut down QS...
08-26 15:42:43.130  6832  6832 D UEI.SmartControl: Stopping QS lib
08-26 15:42:43.131  6832  6832 D UEI.SmartControl: QS lib stop result = true
08-26 15:42:43.131  6832  6832 D UEI.SmartControl: Stopped QS lib
08-26 15:42:43.131  6832  6832 D UEI.SmartControl: Stopped file observer...
08-26 15:42:43.131  6832  6832 D UEI.SmartControl: QS shutdown complete
08-26 15:42:45.557  1032  1091 I ActivityManager: Waited long enough for: ServiceRecord{1a28f18e u0 com.google.android.gms/.wearable.service.WearableService}
,08-26 15:42:47.209  2131  2131 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19838
,08-26 15:42:47.395  1032  1423 V AlarmManager: RTC_WAKEUP set : Alarm{2789a34f type 0 when 1472218965971 com.android.vending} when 1472218965971
,08-26 15:42:47.499  4547  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-26 15:42:47.548  1032  1891 V SIM_STK : Menu title from STK is T-Mobile
,08-26 15:42:47.692  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 15:42:49.914  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 15:42:49.914  6697  6804 I jxcore-log: 
08-26 15:42:49.918  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 15:42:49.918  6697  6804 I jxcore-log: 
,08-26 15:42:49.925  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:49.925  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:49.925  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:49.925  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:49.925  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:49.925  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:49.925  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:49.925  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:49.928  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:49.932  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 15:42:49.932  6697  6804 I jxcore-log: 
08-26 15:42:49.935  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 15:42:49.935  6697  6804 I jxcore-log: 
,08-26 15:42:50.896  6697  6804 D executeNativeTests: Running unit tests
,08-26 15:42:51.035  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:42:51.035  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce added. We now have 2 listener(s)
,08-26 15:42:51.038  1032  1625 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:42:51.040  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 15:42:51.040  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:42:51.040  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:42:51.040  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:51.041  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef added. We now have 2 listener(s)
08-26 15:42:51.041  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:42:51.041  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:42:51.045  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.048  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.048  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.048  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.048  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.048  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:51.048  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.048  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.048  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.053  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.053  6697  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:51.055  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.056  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.060  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 15:42:51.063  6697  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:51.064  6697  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:51.067  6697  6804 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 15:42:51.068  6697  6804 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 15:42:51.069  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:51.071  6697  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:51.071  6697  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:51.072  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:51.075  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.076  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.076  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.076  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.076  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:51.077  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:42:51.077  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce removed from the list
08-26 15:42:51.077  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.077  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef removed from the list
08-26 15:42:51.077  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.077  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.078  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.078  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.080  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.080  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.081  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.081  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.083  6697  6804 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 15:42:51.083  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.083  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.083  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.084  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.084  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.084  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.084  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.084  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.084  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in ,the list
08-26 15:42:51.084  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.084  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.084  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.084  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.084  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.089  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.089  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.089  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.089  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.096  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:51.096  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 15:42:51.096  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 15:42:51.096  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 15:42:51.096  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 15:42:51.096  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 15:42:51.096  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 15:42:51.096  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 15:42:51.096  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 15:42:51.097  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 15:42:51.097  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.098  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.098  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:51.105  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.105  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.105  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.105  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.105  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.105  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.105  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.105  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.105  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.105  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.105  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.106  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.106  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.106  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.107  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.108  6697  6804 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 15:42:51.110  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.113  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.113  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.113  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.113  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.113  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:51.113  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.113  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.113  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.118  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.118  6697  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:51.120  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.121  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.122  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:51.122  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:51.122  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:51.122  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.122  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:42:51.127  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:42:51.130  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:42:51.136  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 15:42:51.143  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:42:51.147  6697  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 15:42:51.150  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:42:51.150  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:51.152  6697  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 15:42:51.153  6697  6804 I io.jxcore.node.ConnectionHelper: start: OK
08-26 15:42:51.157  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.157  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.157  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:51.160  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.160  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.160  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:51.160  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.160  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.160  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.160  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.160  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.161  6697  6804 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 15:42:51.163  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.166  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.166  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.166  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.166  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.166  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:51.166  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.166  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.166  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:51.168  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.168  6697  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:51.170  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.174  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.175  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:51.175  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:51.175  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:51.175  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.175  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:42:51.180  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:42:51.184  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:42:51.186  6697  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-26 15:42:51.187  6697  6804 I io.jxcore.node.ConnectionHelper: start: OK
08-26 15:42:51.188  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.188  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.188  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.188  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.188  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.188  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:51.188  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.188  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.188  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.188  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.189  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.189  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.189  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.190  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.190  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.192  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.192  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.192  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.192  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.192  6697  6804 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 15:42:51.194  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.197  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.197  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.197  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.197  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.197  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:51.197  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.197  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.197  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.199  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.199  6697  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:51.200  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:51.200  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:51.200  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:51.200  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.200  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:42:51.201  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.203  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.205  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:42:51.206  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:51.207  6697  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 15:42:51.207  6697  6804 I io.jxcore.node.ConnectionHelper: start: OK
08-26 15:42:51.207  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.207  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.207  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.208  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.208  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.208  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.209  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.209  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.209  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:51.210  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.210  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.210  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.210  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.210  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.210  6697  6804 W org.thaliproj,ect.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.210  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.211  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.211  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.211  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.211  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.211  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.211  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.213  6697  6804 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 15:42:51.213  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.213  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.213  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.213  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.213  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.213  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.214  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.214  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.214  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.214  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.214  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.214  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.214  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.214  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.215  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.215  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.215  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.215  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.215  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.215  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.216  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 15:42:51.217  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.217  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.217  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.217  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.217  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.217  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.217  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.217  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.217  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.217  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.217  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.217  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.217  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.217  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.219  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.219  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.219  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.219  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.219  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.219  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.220  6697  6804 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 15:42:51.220  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.220  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.220  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.220  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.220  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.220  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.220  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.220  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.220  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.221  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.221  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.221  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.221  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.221  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.222  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.222  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.223  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.223  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.223  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.223  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.224  6697  6804 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 15:42:51.224  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.224  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.224  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.225  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.225  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.225  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.225  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.225  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.225  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.225  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.225  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.225  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.225  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.225  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.226  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.226  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.226  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.226  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.227  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.227  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.227  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 15:42:51.227  6697  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:51.227  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:51.227  6697  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:51.228  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 15:42:51.228  6697  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:51.228  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.228  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.228  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.228  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.228  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.229  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.229  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.229  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.229  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.229  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.229  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.229  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.229  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.229  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.230  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.230  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.231  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.231  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.231  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.231  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.232  6697  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:51.232  6697  6804 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 15:42:51.232  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:51.235  6697  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:51.235  6697  6804 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 15:42:51.235  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 15:42:51.235  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 15:42:51.235  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 15:42:51.236  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 15:42:51.237  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 15:42:51.237  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 15:42:51.237  6697  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 15:42:51.237  6697  6804 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:51.237  6697  6804 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 15:42:51.237  6697  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:51.237  6697  6804 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:51.237  6697  6804 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 15:42:51.237  6697  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:51.237  6697  6804 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:51.237  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:51.240  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 15:42:51.243  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 15:42:51.243  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 15:42:51.245  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 15:42:51.246  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 15:42:51.246  6697  6804 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 15:42:51.246  6697  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:51.246  6697  6804 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 15:42:51.246  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.246  6697  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
08-26 15:42:51.247  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.247  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.247  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.247  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.247  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.247  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 15:42:51.248  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.248  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.248  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.248  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.248  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.248  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.250  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.250  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.251  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.251  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.251  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.251  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.251  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.252  6697  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
08-26 15:42:51.252  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.253  6697  6804 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 15:42:51.253  6697  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
08-26 15:42:51.253  6697  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
08-26 15:42:51.253  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.253  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.253  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.253  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.254  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.254  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.254  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.254  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.254  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.254  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.254  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.254  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.254  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.254  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.255  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.255  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.255  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.255  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.255  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.255  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.256  6697  6804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 15:42:51.257  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.257  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.257  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.258  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.259  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.259  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.259  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.259  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.259  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.259  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.259  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.259  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.259  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.259  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.260  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.260  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.260  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.260  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.260  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.260  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.261  6697  6804 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 15:42:51.261  6697  6804 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 15:42:51.261  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:51.261  6697  6804 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 15:42:51.261  6697  6804 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 15:42:51.261  6697  6804 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 15:42:51.261  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:51.262  6697  6804 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 15:42:51.262  6697  6804 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 15:42:51.262  6697  6804 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 15:42:51.262  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:51.262  6697  6804 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 15:42:51.262  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.262  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.262  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.263  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.263  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.263  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.263  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.263  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.263  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.263  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.263  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.263  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.263  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.263  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.264  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.264  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.265  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.265  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.265  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.265  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.265  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.265  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.265  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.265  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.265  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.265  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.266  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.266  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.266  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.269  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.269  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.269  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.269  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.269  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.269  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.269  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.269  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.269  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.271  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.271  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.271  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.271  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.271  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.271  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.271  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.271  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.271  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.271  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.271  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.272  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.272  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.272  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.272  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.272  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.272  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.274  6697  6804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 15:42:51.274  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.275  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 15:42:51.275  6697  6804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 15:42:51.276  6697  6804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 15:42:51.276  6697  6697 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 15:42:51.276  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 15:42:51.276  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:51.277  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.277  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 15:42:51.277  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 15:42:51.277  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 15:42:51.277  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.277  6697  6804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 15:42:51.278  6697  6697 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 15:42:51.278  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.278  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.278  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:51.278  6697  6804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:51.278  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:51.279  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:51.280  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:42:51.280  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.280  6697  6804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:42:51.280  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.280  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.281  6697  6804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:51.281  6697  6925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 15:42:51.281  6697  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:51.281  6697  6925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 15:42:51.281  6697  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:51.281  6697  6697 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:51.282  6697  6697 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 15:42:51.282  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.282  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.282  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.282  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.283  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.283  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.283  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.283  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.283  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.283  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.283  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.283  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.283  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.283  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.283  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.284  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.284  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.284  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:51.284  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.285  6697  6804 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 15:42:51.286  6697  6804 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 15:42:51.286  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 15:42:51.287  6697  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
08-26 15:42:51.287  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.287  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.287  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.288  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.288  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.288  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.288  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.288  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.288  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.288  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.288  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.288  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.288  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.288  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.298  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.298  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.298  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.299  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
,08-26 15:42:51.300  1032  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:42:51.303  1032  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:42:51.304  1032  1625 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:42:51.305  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.305  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.305  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.305  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.305  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.305  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.305  6697  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.305  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.305  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.305  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.305  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.305  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.305  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.305  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.309  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.309  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.309  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.309  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.310  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.310  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.310  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.310  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.310  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.311  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.311  6697  6804 E org.thaliproject.p2p.btconnectorlib.Co,nnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92c2ce not in the list
08-26 15:42:51.311  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.311  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.311  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.311  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.311  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.311  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.311  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.312  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.312  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.312  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.312  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122be5ef not in the list
08-26 15:42:51.314  6697  6804 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 15:42:51.314  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:51.315  6697  6804 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 15:42:51.315  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:51.315  6697  6804 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 15:42:51.315  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:51.317  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 15:42:51.317  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 15:42:51.318  6697  6804 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 15:42:51.318  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 15:42:51.319  6697  6804 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 15:42:51.319  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 15:42:51.319  6697  6804 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 15:42:51.319  6697  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 15:42:51.320  6697  6804 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 15:42:51.320  6697  6804 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 15:42:51.321  6697  6804 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 15:42:51.321  6697  6804 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 15:42:51.321  6697  6804 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 15:42:51.321  6697  6804 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 15:42:51.322  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:51.322  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a745b94 added. We now have 2 listener(s)
08-26 15:42:51.322  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:51.324  6697  6804 D BluetoothAdapter: enable(): BT is already enabled..!
,08-26 15:42:51.326  1032  1937 D WifiServiceImplEx: setWifiEnabled: true pid=6697, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 15:42:51.327  1032  1937 D WifiService: setWifiEnabled: true pid=6697, uid=10118
08-26 15:42:51.327  1032  1937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 15:42:51.329  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:51.329  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fea463d added. We now have 3 listener(s)
08-26 15:42:51.329  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:42:51.333  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:51.333  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2854ae32 added. We now have 4 listener(s)
08-26 15:42:51.333  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:42:51.335  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:51.335  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25cd9783 added. We now have 5 listener(s)
08-26 15:42:51.335  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:51.338  1032  1937 D WifiServiceImplEx: setWifiEnabled: false pid=6697, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 15:42:51.338  1032  1937 D WifiService: setWifiEnabled: false pid=6697, uid=10118
08-26 15:42:51.338  1032  1937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 15:42:51.351  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 15:42:51.351  1032  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:42:51.351  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 15:42:51.352  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-26 15:42:51.352  1032  2015 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2b68d0d1 mBinding = false
08-26 15:42:51.352  1032  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 15:42:51.352  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 15:42:51.353  1032  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 15:42:51.353  1032  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 15:42:51.354  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 15:42:51.354  1032  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 15:42:51.354  1032  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:42:51.354  1032  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 15:42:51.355  1032  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 15:42:51.355  1032  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 15:42:51.361  1032  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 15:42:51.361  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 15:42:51.361  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.361  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.362  2707  2707 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 15:42:51.362  1032  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 15:42:51.362  1032  1539 D WifiNative-wlan0: doBoolean: SET ps 1
,08-26 15:42:51.364  1032  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 15:42:51.365  1032  2858 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.365  1032  1095 D BluetoothManagerService: Message: 2
08-26 15:42:51.366  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 15:42:51.366  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 15:42:51.366  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-26 15:42:51.367  1032  1095 D BluetoothManagerService: Sending off request.
08-26 15:42:51.369  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.369  3903  3927 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 15:42:51.370  3903  3987 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 15:42:51.371  3903  3987 D BluetoothAdapterProperties: Setting state to 13
08-26 15:42:51.371  3903  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 15:42:51.371  3903  3987 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 15:42:51.372  3903  3987 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 15:42:51.372  3903  3995 D BluetoothAdapterProperties: Scan Mode:20
08-26 15:42:51.373  3903  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 15:42:51.377  1032  1095 D BluetoothManagerService: Message: 60
08-26 15:42:51.377  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 15:42:51.377  1032  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-26 15:42:51.377   313   907 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:42:51.378  3903  4283 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 15:42:51.378  3903  4283 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:42:51.378  3903  4283 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 15:42:51.378  3903  4283 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 15:42:51.378  3903  4283 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 15:42:51.378  3903  4283 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 15:42:51.378  3903  4283 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 15:42:51.378  3903  4283 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 15:42:51.380  3903  3987 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 15:42:51.381  3903  4284 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:42:51.381  3903  4344 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:42:51.382  3903  4347 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:42:51.382  3903  4353 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:42:51.382  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.383  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.383  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.383  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.383  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.383  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.383  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.383  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.383  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:51.383  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 15:42:51.383  3903  4096 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 15:42:51.383  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.383  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.384  6697  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:51.384  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 15:42:51.384  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 15:42:51.384  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 15:42:51.384  3903  4096 W bt-l2cap: L2CA,P - L2CA_Deregister() called for PSM: 0x0019
08-26 15:42:51.384  3903  4096 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:51.384  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 15:42:51.384  3903  4096 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:51.384  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 15:42:51.384  3903  4096 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:51.384  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 15:42:51.384  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 15:42:51.384  3903  4096 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 15:42:51.386  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.398  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.403  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.403  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.403  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.403  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.403  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.403  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.403  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.403  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.403  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:51.405  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.405  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.407  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.407  6697  6923 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-26 15:42:51.407  6697  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
,08-26 15:42:51.428  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 15:42:51.428  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-26 15:42:51.452  1032  1091 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6929 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-26 15:42:51.456  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:51.457  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 15:42:51.459  3903  3903 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:51.460  3903  3903 D BluetoothMapService: STATE_TURNING_OFF
08-26 15:42:51.460  3903  3903 V BluetoothMapService: Handler(): got msg=4
08-26 15:42:51.460  3903  3903 D BluetoothMapService: MAP Service closeService in
08-26 15:42:51.460  3903  3903 D BluetoothMapMasInstance: MAP Service shutdown
08-26 15:42:51.460  3903  3903 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 15:42:51.460  3903  3903 V BluetoothMapService: MAP Service closeService out
08-26 15:42:51.461  3903  3903 V BtOppService: Receiver DISABLED_ACTION 
08-26 15:42:51.461  3903  3903 I BtOppRfcommListener: stopping Accept Thread
08-26 15:42:51.461  3903  3903 V BtOppRfcommListener: close mBtServerSocket
08-26 15:42:51.461  3903  3903 V BtOppRfcommListener: waiting for thread to terminate
08-26 15:42:51.462  3903  4344 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 15:42:51.462  3903  3903 V BtOppRfcommListener: done waiting for thread to terminate
08-26 15:42:51.464  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.464  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.464  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.464  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.464  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.464  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.464  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:51.464  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:51.464  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:51.465  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.465  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:51.467  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.467  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.467  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.467  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.467  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.467  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.467  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:51.467  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:51.467  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:51.468  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:5,1.468  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:51.499  1032  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 15:42:51.500  1032  1545 D DSQN    : disableDataServiceNotify
08-26 15:42:51.500  1032  1545 D DSQN    : stop dsqn bin
,08-26 15:42:51.506  1032  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 15:42:51.506  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:51.506  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:42:51.506  1032  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:42:51.506  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 15:42:51.506  1603  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 15:42:51.507  1032  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 15:42:51.507  1032  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 15:42:51.507  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 15:42:51.508  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.508  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.508  1032  2854 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 15:42:51.516  1032  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6956 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 15:42:51.517  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-26 15:42:51.517  3903  3903 V BtOppService: onDestroy
08-26 15:42:51.519  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 15:42:51.519  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:51.519  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:51.519  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 15:42:51.520  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:51.520  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 15:42:51.520  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 15:42:51.521  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,08-26 15:42:51.530  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 15:42:51.530  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:51.531  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:51.532  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:51.532  1032  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:51.532  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.532  1032  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:51.532  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.532  1032  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2249dbb5
08-26 15:42:51.532  1032  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:51.532  1032  1537 D LGWifiP2pService: P2pDisablingState
08-26 15:42:51.532  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:51.533  1032  1537 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.533  1032  1537 D LGWifiP2pService: p2p socket connection lost
08-26 15:42:51.533  1032  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:51.533  1032  1537 D LGWifiP2pService: P2pDisabledState
08-26 15:42:51.533  1032  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 15:42:51.533  1032  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:51.533  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:51.534  1032  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:51.534  1032  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:51.534  3903  3903 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 15:42:51.535  1032  1545 D NetworkManagementService: Removing idletimer
08-26 15:42:51.535  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:51.535  1032  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:51.535  1032  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:51.535  1032  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 15:42:51.535  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:51.536  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.536  1032  1537 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.536  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 15:42:51.536  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 15:42:51.536  2707  2707 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 15:42:51.537  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 15:42:51.538  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 15:42:51.538  1943  1943 D WfdsService: WifiP2pState is changed : false
08-26 15:42:51.538  1943  2357 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 15:42:51.538  1943  2357 D WfdsService: Set the WFDS Monitor: false
08-26 15:42:51.539  1032  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 15:42:51.539  1032  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 15:42:51.539  1943  2357 D WfdsMonitor: WFDS Monitor is stopped
08-26 15:42:51.539  1943  2357 D WfdsService: STATE : WfdsDisabledState - enter
08-26 15:42:51.539  1943  2767 D CtrlSupplicant: Received on exit socket, terminate
08-26 15:42:51.539  1943  2767 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 15:42:51.539  1943  2767 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 15:42:51.539  1943  2767 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 15:42:51.540  1943  2358 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 15:42:51.540  1943  2357 W WfdsService: DefaultState - msg [9445378] is not handled
,08-26 15:42:51.541  1032  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 15:42:51.542   313   907 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:42:51.545  1032  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 15:42:51.545  1032  1539 D WifiNative-p2p0: TERMINATE: returned true
08-26 15:42:51.545  1032  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 15:42:51.545  1032  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 15:42:51.545  1032  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 15:42:51.546  1032  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:51.546  1032  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:51.550  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 15:42:51.552  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.552  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.552  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.552  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.552  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:51.552  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.552  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:51.552  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:51.552  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.552  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.552  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:51.554  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.554  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.554  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.554  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.554  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:51.554  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.554  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:51.554  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:51.554  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:51.555  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.555  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:51.562  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 15:42:51.563  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:51.564  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:51.565  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:51.565  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:51.566  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:51.578  1032  2858 D DhcpStateMachine: StoppedState
08-26 15:42:51.578  1032  2858 D DhcpStateMachine: StoppedState{ when=-36ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.578  6956  6956 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:42:51.578  6956  6956 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-26 15:42:51.579  6956  6956 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 15:42:51.579  1032  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 15:42:51.579  6956  6956 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-26 15:42:51.579  1032  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 15:42:51.580  6956  6956 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 15:42:51.580  6956  6956 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:42:51.590  1032  1890 I art     : Explicit concurrent mark sweep GC freed 33132(1611KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.874ms total 176.870ms
08-26 15:42:51.591  1032  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 15:42:51.591  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-26 15:42:51.592  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:51.592  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:51.592  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 15:42:51.592  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 15:42:51.592  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 15:42:51.592  1032  1032 D RttService: SCAN_AVAILABLE : 1
08-26 15:42:51.592  1032  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.592  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-26 15:42:51.592  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:51.592  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:51.592  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 15:42:51.592  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 15:42:51.593  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:42:51.593  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 15:42:51.593  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 15:42:51.593  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 15:42:51.593  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 15:42:51.593  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 15:42:51.593  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 15:42:51.593  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 15:42:51.595  1032  1556 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:51.613  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 15:42:51.613  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:51.614  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:51.614  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 15:42:51.614  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:51.615  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 15:42:51.616  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:51.645  6929  6929 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-26 15:42:51.645  6929  6929 W LG Account v2.2: No ProfileInfo entries
08-26 15:42:51.645  6929  6929 I LG Account v2.2: isEnabled: false
08-26 15:42:51.645  6929  6929 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 15:42:51.645  6929  6929 I Feature : [Lifetracker]Country: EU
08-26 15:42:51.645  6929  6929 I Feature : [Lifetracker]Operator: OPEN
08-26 15:42:51.645  6929  6929 I Feature : [Lifetracker]Ranking support: false
08-26 15:42:51.646  6929  6929 I Feature : [Lifetracker]Comfort support: false
08-26 15:42:51.646  6929  6929 I Feature : [Lifetracker]Accessory: true
08-26 15:42:51.646  6929  6929 I Feature : [Lifetracker]Health device: true
08-26 15:42:51.646  6929  6929 I Feature : [Lifetracker]Extra Pedometer: false
08-26 15:42:51.646  6929  6929 I Feature : [Lifetracker]Blood glucose device: false
08-26 15:42:51.646  6929  6929 I Feature : [Lifetracker]Device Number: 3
08-26 15:42:51.649  2707  2707 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 15:42:51.649  2707  2707 I wpa_supplicant: monitor socket send errors count : 1
08-26 15:42:51.649  2707  2707 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-2\x00 that cannot receive messages
08-26 15:42:51.650  1032  2721 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 15:42:51.650  1032  2721 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 15:42:51.652  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:51.679  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 15:42:51.686  1032  2052 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6976 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 15:42:51.687  2707  2707 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 15:42:51.687  1032  2052 I ActivityManager: Killing 6292:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-26 15:42:51.687  2707  2707 W wpa_supplicant: USIM:  scard_deinit function
08-26 15:42:51.687  1032  2721 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 15:42:51.687  1032  2721 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 15:42:51.687  1032  2721 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 15:42:51.688  1032  2721 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 15:42:51.688  1032  2721 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 15:42:51.688  1032  2721 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 15:42:51.688  1032  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121027
08-26 15:42:51.689  1032  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121028
08-26 15:42:51.689  1032  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=121028  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 15:42:51.690  1032  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=121028  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 15:42:51.690  1032  1095 D Tethering: InitialState.processMessage what=4
08-26 15:42:51.698   340   340 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 9.897ms
08-26 15:42:51.708   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 8.869ms
,08-26 15:42:51.718   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.886ms
08-26 15:42:51.727  1032  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 15:42:51.727  1032  1575 W libprocessgroup: failed to open /acct/uid_10014/pid_6292/cgroup.procs: No such file or directory
08-26 15:42:51.729  1032  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:51.729  1032  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:51.734  1032  1095 D BluetoothManagerService: Message: 20
08-26 15:42:51.734  1032  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10a53ed3:true
08-26 15:42:51.735  3903  3903 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 15:42:51.735  3903  3903 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:51.736  3903  3903 V BluetoothPbapReceiver: ***********state = 13
08-26 15:42:51.736  3903  3903 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 15:42:51.737  3903  3903 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:51.737  3903  3903 V BluetoothPbapService: state: 13
08-26 15:42:51.737  3903  3903 V BluetoothPbapService: Pbap Service closeService in
08-26 15:42:51.739  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:42:51.740  3903  3903 V BluetoothPbapService: successfully stopped pbap service
08-26 15:42:51.740  3903  3903 V BluetoothPbapService: Pbap Service closeService out
08-26 15:42:51.740  3903  3903 V BluetoothPbapService: Pbap Service onDestroy
08-26 15:42:51.740  3903  3903 V BluetoothPbapService: Pbap Service closeService in
08-26 15:42:51.740  3903  3903 V BluetoothPbapService: Pbap Service closeService out
08-26 15:42:51.741  3903  3903 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 15:42:51.748  1032  1095 D BluetoothManagerService: Message: 30
08-26 15:42:51.752  1032  1095 D BluetoothManagerService: Message: 30
,08-26 15:42:51.755  6956  6956 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 15:42:51.756  6956  6956 D BluetoothMap: Create BluetoothMap proxy object
08-26 15:42:51.756  1032  1095 D BluetoothManagerService: Message: 30
08-26 15:42:51.760  1032  1095 D BluetoothManagerService: Message: 30
08-26 15:42:51.762  6956  6956 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-26 15:42:51.763  6956  6956 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-26 15:42:51.767  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 15:42:51.770  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 15:42:51.770  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:42:51.772  1032  1924 I ActivityManager: Killing 6346:com.android.defcontainer/u0a4 (adj 15): empty #17
08-26 15:42:51.779  2707  2707 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 15:42:51.780  1032  2721 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 15:42:51.780  1032  2721 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 15:42:51.780  1032  2721 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 15:42:51.780  1032  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-26 15:42:51.782  6697  6697 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 15:42:51.803  1032  2034 W libprocessgroup: failed to open /acct/uid_10004/pid_6346/cgroup.procs: No such file or directory
,08-26 15:42:51.804  6956  6956 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-26 15:42:51.808  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-26 15:42:51.817  6956  6956 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:51.828  6956  6956 D BluetoothInputDevice: Proxy object connected
,08-26 15:42:51.830  6956  6956 D HidProfile: Bluetooth service connected
,08-26 15:42:51.832  6956  6956 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 15:42:51.833  6956  6956 D PanProfile: Bluetooth service connected
08-26 15:42:51.834  6956  6956 D BluetoothMap: Proxy object connected
08-26 15:42:51.834  6956  6956 D MapProfile: Bluetooth service connected
08-26 15:42:51.835  6956  6956 D BluetoothMap: getConnectedDevices()
08-26 15:42:51.835  6956  6956 D BluetoothMap: Bluetooth is Not enabled
08-26 15:42:51.852  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:51.881  1032  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 15:42:51.881  1032  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 15:42:51.881  1032  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 15:42:51.881  1032  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 15:42:51.882  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-26 15:42:51.883  1943  2357 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 15:42:51.883  1943  2357 D WfdsService: Set the WFDS Monitor: false
08-26 15:42:51.883  1943  2357 D WfdsMonitor: WFDS Monitor is stopped
,08-26 15:42:51.885  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:51.886  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 15:42:51.888  2501  2501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:51.894  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 15:42:51.894  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 15:42:51.895  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 15:42:51.896  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.896  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.896  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.896  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.896  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:51.896  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.896  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:51.896  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:51.896  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:51.900  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.900  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.900  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.900  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:51.900  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:51.900  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.900  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:51.900  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:51.900  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:51.926  6956  6956 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 15:42:51.927  6956  6956 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 15:42:51.936  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:51.936  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 15:42:51.939  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 15:42:51.943  6956  6956 D BluetoothPermissionRequest: onReceive
08-26 15:42:51.945  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 15:42:51.950  1032  2034 I ActivityManager: Killing 6558:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-26 15:42:51.952  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 15:42:52.044  1032  1625 W libprocessgroup: failed to open /acct/uid_10008/pid_6558/cgroup.procs: No such file or directory
08-26 15:42:52.045  3903  3903 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 15:42:52.045  3903  3903 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-26 15:42:52.048  3903  3903 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 15:42:52.146  1032  1891 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7005 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 15:42:52.147  3903  3903 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:52.148  3903  3903 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 15:42:52.151  3903  3903 V BluetoothFtpService: Ftp Service onStartCommand
08-26 15:42:52.151  3903  3903 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:52.151  3903  3903 V BluetoothFtpService: Ftp Service closeService
08-26 15:42:52.151  3903  3903 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 15:42:52.155  3903  3903 V BluetoothFtpService: successfully stopped ftp service
08-26 15:42:52.156  3903  3903 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 15:42:52.156  3903  3903 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-26 15:42:52.156  3903  3903 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 15:42:52.156  3903  3903 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:52.156  3903  3903 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 15:42:52.156  3903  3903 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 15:42:52.157  3903  3903 V BluetoothFtpService: Ftp Service onDestroy
08-26 15:42:52.157  3903  3903 V BluetoothFtpService: Ftp Service closeService
08-26 15:42:52.216  1032  1960 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7025 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 15:42:52.223  3903  3903 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:52.223  3903  3903 V BluetoothSapService: state: 13
08-26 15:42:52.224  3903  3903 V BluetoothSapService: Stopping SAP server process
08-26 15:42:52.225  3903  3903 V BluetoothSapService: Sap Service closeSapService in
08-26 15:42:52.226  3903  3903 V BluetoothSapService: Close listen Socket : 
08-26 15:42:52.226  3903  3903 V BluetoothSapService: Close rfcomm Socket : 
08-26 15:42:52.226  3903  3903 V BluetoothSapService: Close sapd  Socket : 
08-26 15:42:52.227  3903  3903 V BluetoothSapService: Sap Service closeSapService out
08-26 15:42:52.227  3903  3903 V BluetoothSapService: Sap Service onDestroy
08-26 15:42:52.227  3903  3903 V BluetoothSapService: Sap Service closeSapService in
08-26 15:42:52.227  3903  3903 V BluetoothSapService: Close listen Socket : 
08-26 15:42:52.227  3903  3903 V BluetoothSapService: Close rfcomm Socket : 
08-26 15:42:52.227  3903  3903 V BluetoothSapService: Close sapd  Socket : 
08-26 15:42:52.228  3903  3903 V BluetoothSapService: Sap Service closeSapService out
,08-26 15:42:52.261  7005  7005 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 15:42:52.274  7025  7025 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 15:42:52.289  7005  7005 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 15:42:52.296  1032  1937 I ActivityManager: Killing 6051:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-26 15:42:52.323  7005  7005 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-26 15:42:52.324  7005  7005 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 15:42:52.324  7005  7005 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 15:42:52.324  7005  7005 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 15:42:52.325  7005  7005 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-26 15:42:52.327  7005  7005 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 15:42:52.333  7005  7005 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 15:42:52.351  1032  1575 W libprocessgroup: failed to open /acct/uid_10011/pid_6051/cgroup.procs: No such file or directory
,08-26 15:42:52.373  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 15:42:52.378  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:42:52.394  3903  3995 D bt_hci_bdroid: cleanup
08-26 15:42:52.394  3903  4098 I bt_lpm  : LPM is already off!!!
,08-26 15:42:52.394  3903  4096 W bt-btif : ag scb idx 1 not allocated
08-26 15:42:52.394  3903  4271 I bt_userial_mct: exiting userial_read_thread
08-26 15:42:52.395  3903  4271 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 15:42:52.395  3903  4096 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 15:42:52.395  3903  4096 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:52.396  3903  4096 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 15:42:52.398  3903  3995 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 15:42:52.398  3903  4098 I bt_vendor: hw_epilog_process
08-26 15:42:52.399  3903  3995 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 15:42:52.399  3903  3995 D bt_userial_mct: userial_close
08-26 15:42:52.399  3903  3995 E bt_userial_mct: pthread_join() FAILED result:3
08-26 15:42:52.399  3903  3995 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 15:42:52.416  7005  7005 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 15:42:52.421  7005  7005 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-26 15:42:52.427  7005  7005 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 15:42:52.430  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:52.433  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 15:42:52.433  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 15:42:52.433  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:42:52.441  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:52.460  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 15:42:52.468  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:52.468  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:42:52.470  7005  7005 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 15:42:52.473  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 15:42:52.476  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 15:42:52.476  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 15:42:52.476  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:42:52.480  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 15:42:52.488  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 15:42:52.503  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:52.503  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 15:42:52.505  7005  7005 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 15:42:52.506  3903  3995 D bt_hci_bdroid: set_power 0
08-26 15:42:52.507  3903  3995 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 15:42:52.507  3903  3995 I bt_vendor: bluetooth satus is on
08-26 15:42:52.507  3903  3995 I bt_vendor: bt-vendor : resetting BT status
08-26 15:42:52.507  3903  3995 I bt_vendor: Starting hciattach daemon
08-26 15:42:52.507  3903  3995 I bt_vendor: try to set false
08-26 15:42:52.509  3903  3995 I bt_vendor: Starting hciattach daemon
08-26 15:42:52.509  3903  3995 I bt_vendor: try to set false
08-26 15:42:52.510  3903  3995 I bt_vendor: cleanup
08-26 15:42:52.511  3903  4096 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 15:42:52.568  1032  1960 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7046 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 15:42:52.577  3903  3995 I GKI_LINUX: GKI_exit_task 0 done
08-26 15:42:52.577  3903  3995 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 15:42:52.579  3903  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 15:42:52.583  3903  3903 D HeadsetService: Received stop request...Stopping profile...
,08-26 15:42:52.585  3903  3903 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 15:42:52.585  3903  3903 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 15:42:52.585  3903  3903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dce0cc
08-26 15:42:52.585  3903  4022 D HeadsetStateMachine: Exit Disconnected: -1
08-26 15:42:52.588  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 15:42:52.588  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 15:42:52.588  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 15:42:52.589  1032  1032 D BluetoothHeadset: Proxy object disconnected
08-26 15:42:52.589  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 15:42:52.590  3903  3903 D A2dpService: Received stop request...Stopping profile...
08-26 15:42:52.590  3903  3987 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 15:42:52.590  3903  4055 D A2dpStateMachine: Exit Disconnected: -1
08-26 15:42:52.591  3903  3903 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 15:42:52.593  3903  3903 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 15:42:52.593  3903  3903 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 15:42:52.593  3903  3903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dce0cc
08-26 15:42:52.594  1032  1032 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:52.594  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 15:42:52.595  3903  3903 D HidService: Received stop request...Stopping profile...
08-26 15:42:52.595  3903  3903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dce0cc
08-26 15:42:52.595  6956  6956 D BluetoothInputDevice: Proxy object disconnected
08-26 15:42:52.596  6956  6956 D HidProfile: Bluetooth service disconnected
08-26 15:42:52.596  3903  3903 D HealthService: Received stop request...Stopping profile...
08-26 15:42:52.596  3903  3903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dce0cc
,08-26 15:42:52.598  3903  3903 D PanService: Received stop request...Stopping profile...
08-26 15:42:52.598  3903  3903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dce0cc
08-26 15:42:52.599  3903  3903 D HeadsetStateMachine: Unbinding service...
08-26 15:42:52.600  3903  3903 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 15:42:52.600  3903  3903 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 15:42:52.600  3903  3903 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 15:42:52.600  3903  3903 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 15:42:52.600  3903  3903 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 15:42:52.601  3903  3903 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 15:42:52.601  3903  3903 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-26 15:42:52.601  3903  3903 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 15:42:52.601  3903  3903 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 15:42:52.601  3903  3903 D BtGatt.GattService: stop()
08-26 15:42:52.601  6956  6956 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:42:52.601  3903  3903 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 15:42:52.601  6956  6956 D PanProfile: Bluetooth service disconnected
08-26 15:42:52.602  3903  3903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dce0cc
08-26 15:42:52.603  3903  3903 D BluetoothMapService: Received stop request...Stopping profile...
08-26 15:42:52.603  3903  3903 D BluetoothMapService: stop()
08-26 15:42:52.604  3903  3903 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 15:42:52.604  3903  3903 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 15:42:52.604  3903  3903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dce0cc
08-26 15:42:52.605  6956  6956 D BluetoothMap: Proxy object disconnected
08-26 15:42:52.605  6956  6956 D MapProfile: Bluetooth service disconnected
08-26 15:42:52.606  3903  3903 I BluetoothA2dpServiceJni: cleanupNative
08-26 15:42:52.606  3903  4056 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 15:42:52.606  3903  3903 I GKI_LINUX: GKI_exit_task 2 done
08-26 15:42:52.606  3903  3903 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 15:42:52.607  3903  3903 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 15:42:52.607  3903  3903 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 15:42:52.607  3903  3903 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 15:42:52.607  3903  3903 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 15:42:52.607  3903  3903 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 15:42:52.607  3903  3903 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 15:42:52.607  3903  3903 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 15:42:52.609  3903  3903 V BluetoothMapService: Handler(): got msg=4
08-26 15:42:52.609  3903  3903 D BluetoothMapService: MAP Service closeService in
08-26 15:42:52.609  3903  3903 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 15:42:52.609  3903  3903 V BluetoothMapService: MAP Service closeService out
08-26 15:42:52.609  3903  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 15:42:52.610  3903  3987 D BluetoothAdapterProperties: Setting state to 10
08-26 15:42:52.610  3903  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 15:42:52.610  1032  1095 D BluetoothManagerService: Message: 60
08-26 15:42:52.610  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 15:42:52.610  1032  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-26 15:42:52.610  3903  3987 I BluetoothAdapterState: Entering OffState
08-26 15:42:52.611  6956  6972 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 15:42:52.611  3903  3903 D BluetoothMapService: cleanup()
08-26 15:42:52.611  3903  3903 D BluetoothMapService: MAP Service closeService in
08-26 15:42:52.611  3903  3903 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 15:42:52.611  3903  3903 V BluetoothMapService: MAP Service closeService out
08-26 15:42:52.612  1853  2476 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:42:52.613  6956  6971 D BluetoothMap: onBluetoothStateChange: up=false
08-26 15:42:52.613  1853  2718 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:42:52.614  1032  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:42:52.614  1032  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:42:52.614  6956  6972 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 15:42:52.615  6956  6971 D BluetoothPan: onBluetoothStateChange on: false
08-26 15:42:52.616  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:42:52.617  1032  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 15:42:52.617  1032  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 15:42:52.619  1032  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 15:42:52.619  1032  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 15:42:52.619  1032  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2b68d0d1 mBinding = false
08-26 15:42:52.620  1032  1095 D BluetoothManagerService: Sending unbind request.
08-26 15:42:52.622  1032  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 15:42:52.628  3903  3995 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 15:42:52.629  3903  3903 I GKI_LINUX: GKI_exit_task 1 done
08-26 15:42:52.629  3903  3903 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 15:42:52.630  3903  3903 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 15:42:52.630  3903  3903 I art     : --- WEIRD: removing null entry 246
08-26 15:42:52.630  3903  3903 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-26 15:42:52.630  3903  3903 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 15:42:52.631  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 15:42:52.634  3903  3903 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 15:42:52.636  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:52.636  1943  2130 D LGBluetoothAPIService: Message: 2
08-26 15:42:52.636  1943  2130 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@6a9f78f mBinding = false
08-26 15:42:52.636  1603  1603 D BluetoothAdapter: 331866596: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:52.636  1603  1603 D BluetoothAdapter: 331866596: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:52.636  1943  2130 D LGBluetoothAPIService: Sending unbind request.
08-26 15:42:52.637  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.638  6956  6956 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 15:42:52.638  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.639  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 15:42:52.639  6956  6956 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 15:42:52.640  3903  3903 I art     : System.exit called, status: 0
08-26 15:42:52.640  3903  3903 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 15:42:52.641  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 15:42:52.662   317  1382 V AudioFlinger: 3903 died, releasing its sessions
08-26 15:42:52.662   317  1382 V AudioFlinger:  pid 1853 @ 0
08-26 15:42:52.662   317  1382 V AudioFlinger:  pid 3453 @ 1
,08-26 15:42:52.662   317  1382 V AudioFlinger:  pid 3453 @ 2
08-26 15:42:52.662  6956  6956 D DockEventReceiver: finishStartingService: stopping service
08-26 15:42:52.664  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 15:42:52.692  1032  1575 I ActivityManager: Process com.android.bluetooth (pid 3903) has died
08-26 15:42:52.693  1032  1575 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-26 15:42:52.701  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 15:42:52.707  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 15:42:52.717  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:52.725  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:52.727  6956  6956 D BluetoothPermissionRequest: onReceive
08-26 15:42:52.728  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 15:42:52.729  6956  6956 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 15:42:52.732  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 15:42:52.783  1032  2034 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7075 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 15:42:52.805  7046  7074 V FormManager: Network unavailable.
,08-26 15:42:52.805  7046  7073 W FormManager: Network not available. Please check & try again.
,08-26 15:42:52.810  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:52.810  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 15:42:52.810  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 15:42:52.810  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 15:42:52.811  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 15:42:52.811  7046  7074 V FormManager: Network unavailable.
08-26 15:42:52.819  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 15:42:52.820  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 15:42:52.820  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 15:42:52.820  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 15:42:52.820  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 15:42:52.820  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-26 15:42:52.826  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 15:42:52.827  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 15:42:52.829  1032  1625 I ActivityManager: Killing 6073:com.android.contacts/u0a19 (adj 15): empty #17
08-26 15:42:52.830  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 15:42:52.865  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 15:42:52.866  1032  1996 W libprocessgroup: failed to open /acct/uid_10019/pid_6073/cgroup.procs: No such file or directory
08-26 15:42:52.882  4356  7094 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 15:42:52.887  7075  7075 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 15:42:52.887  7075  7075 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 15:42:52.888  7075  7075 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 15:42:52.889  7075  7075 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 15:42:52.890  6976  6976 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 15:42:52.890  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 15:42:52.890  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:42:52.892  4356  7095 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 15:42:52.892  4356  7095 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 15:42:52.895  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:52.904  7046  7097 W FormManager: Network not available. Please check & try again.
08-26 15:42:52.907  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:52.915  7046  7098 V FormManager: Network unavailable.
,08-26 15:42:52.920  7046  7098 V FormManager: Network unavailable.
08-26 15:42:52.929  7005  7005 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-26 15:42:52.930  7075  7075 D BluetoothAdapterApp: Loading JNI Library
08-26 15:42:52.932  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 15:42:52.933  7005  7005 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 15:42:52.964  7075  7075 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@6a9115d Instance Count = 1
,08-26 15:42:52.969  7075  7075 D BluetoothAdapterApp: onCreate
08-26 15:42:52.973  7005  7005 D LgDataFeature: LgDataFeature() Constructor: none
08-26 15:42:52.974  7005  7005 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 15:42:52.982  7005  7005 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-26 15:42:52.983  7005  7005 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 15:42:52.983  7005  7005 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 15:42:52.983  7005  7005 V SoundPool: doLoad: loading sample sampleID=1
08-26 15:42:52.984  7005  7005 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 15:42:52.987  7005  7101 V SoundPool: Start decode
08-26 15:42:52.987  7005  7101 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 15:42:52.988   317  1382 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 15:42:52.988   317  1382 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 15:42:52.988   317  1382 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 15:42:52.988   317  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 15:42:52.988   317  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 15:42:52.988   317  1382 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 15:42:52.988   317  1382 V MediaPlayerService: player type = 3
08-26 15:42:52.988   317  1382 V AwesomePlayer: AwesomePlayer create()
08-26 15:42:52.988  6832  6832 D UEI.SmartControl: QS Service created
08-26 15:42:52.989   317  1382 V AwesomePlayer: reset_l() 
08-26 15:42:52.989   317  1382 V AwesomePlayer: cancelPlayerEvents
08-26 15:42:52.989   317  1382 V AwesomePlayer: setAudioSink() 
08-26 15:42:52.989   317  1382 V AwesomePlayer: reset_l() 
08-26 15:42:52.989   317  1382 V AudioCache: notify(0xb54747c0, 8, 0, 0)
08-26 15:42:52.989   317  1382 V AudioCache: ignored
08-26 15:42:52.989   317  1382 V AwesomePlayer: cancelPlayerEvents
08-26 15:42:52.989   317  1382 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 15:42:52.989   317  1382 V AwesomePlayer: setDataSource_l dataSource
08-26 15:42:52.989   317  1382 V LGParserOSAL: SniffLGParser start
08-26 15:42:52.989   317  1382 V LGParserOSAL: MainType:5, SubType=0
08-26 15:42:52.989   317  1382 V LGParserOSAL: #### check Mime : application/ogg
08-26 15:42:52.989   317  1382 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 15:42:52.989   317  1382 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 15:42:52.993  7075  7075 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 15:42:52.994  7075  7075 D ProfileConfigQcom: Adding HeadsetService
08-26 15:42:52.994  7075  7075 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 15:42:52.994  7075  7075 D ProfileConfigQcom: Adding A2dpService
08-26 15:42:52.994  7075  7075 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 15:42:52.994  7075  7075 D ProfileConfigQcom: Adding HidService
08-26 15:42:52.995  7075  7075 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 15:42:52.995  7075  7075 D ProfileConfigQcom: Adding HealthService
08-26 15:42:52.995  7075  7075 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 15:42:52.996  7075  7075 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 15:42:52.996  7075  7075 D ProfileConfigQcom: Adding PanService
,08-26 15:42:52.996  7075  7075 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 15:42:52.996  7075  7075 D ProfileConfigQcom: Adding GattService
08-26 15:42:52.997  7075  7075 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-26 15:42:52.997  7075  7075 D ProfileConfigQcom: Adding BluetoothMapService
08-26 15:42:52.997  7075  7075 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-26 15:42:52.999  7075  7075 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 15:42:53.005  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 15:42:53.007  7075  7075 V LGMDMManagerInternal: Create singleton instance
08-26 15:42:53.007  7005  7005 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 15:42:53.011  7005  7005 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 15:42:53.012  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 15:42:53.027  7005  7005 V LGMDMManager: Create singleton instance
,08-26 15:42:53.030   317  1382 V LGParserOSAL: supported mime: application/ogg
08-26 15:42:53.030   317  1382 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 15:42:53.030   317  1382 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 15:42:53.030   317  1382 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 15:42:53.030   317  1382 V AwesomePlayer: AudioTrack Setting
08-26 15:42:53.030   317  1382 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 15:42:53.030   317  1382 V AwesomePlayer: setAudioSource() 
08-26 15:42:53.030   317  1382 V MediaPlayerService: prepare
08-26 15:42:53.030   317  1382 V AwesomePlayer: prepareAsync_l() 
08-26 15:42:53.030   317  1382 V MediaPlayerService: wait for prepare
08-26 15:42:53.030   317  7104 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 15:42:53.030   317  7104 V AwesomePlayer: initAudioDecoder() 
08-26 15:42:53.030   317  7104 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 15:42:53.030   317  7104 V AudioSystem: isOffloadSupported()
08-26 15:42:53.030   317  7104 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 15:42:53.030   317  7104 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 15:42:53.030   317  7104 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 15:42:53.030   317  7104 V AwesomePlayer: getUseOffload() = 0 
08-26 15:42:53.030   317  7104 V OMXCodec: OMXCodec::Create
08-26 15:42:53.030   317  7104 V OMXCodec: findMatchingCodecs()
08-26 15:42:53.031   317  7104 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 15:42:53.031   317  7104 V OMXCodec: matchingCodecs.size()=1
08-26 15:42:53.031   317  7104 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 15:42:53.032   317  7104 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 15:42:53.032   317  7104 V LGCodecAdapter: LG Codec Adapter start
08-26 15:42:53.032   317  7104 V OMXCodec: OMXCodec Createtor
08-26 15:42:53.032   317  7104 V OMXCodec: setComponentRole
08-26 15:42:53.032   317  7104 V OMXCodec: configureCodec protected=0
08-26 15:42:53.032   317  7104 V LGCodecAdapter: called getLGCodecSpecificData
08-26 15:42:53.032   317  7104 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 15:42:53.032   317  7104 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 15:42:53.032   317  7104 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 15:42:53.032   317  7104 V LGCodecOSAL: Not support LGCodec
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 15:42:53.033   317  7104 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 15:42:53.033   317  7104 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 15:42:53.033   317  7104 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 15:42:53.033   317  7104 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 15:42:53.033   317  7104 V AudioSystem: isOffloadSupported()
08-26 15:42:53.033   317  7104 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 15:42:53.033   317  7104 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 15:42:53.033   317  7104 V OMXCodec: init()
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-26 15:42:53.033   317  7104 V OMXCodec: allocateBuffers
08-26 15:42:53.033   317  7104 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on input port
08-26 15:42:53.033   317  7104 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-26 15:42:53.033   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
08-26 15:42:53.034   317  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc90 on output port
08-26 15:42:53.034   317  7104 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 15:42:53.037  6832  6832 I UEI.SmartControl: Service initServices...
08-26 15:42:53.037  6832  6832 D UEI.SmartControl: QS start get config
08-26 15:42:53.038   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 15:42:53.038   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 15:42:53.038   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 15:42:53.038   317  7104 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 15:42:53.038   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 15:42:53.038   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 15:42:53.038   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 15:42:53.038   317  7104 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 15:42:53.038   317  7104 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 15:42:53.038   317  7104 V AudioCache: notify(0xb54747c0, 5, 0, 0)
08-26 15:42:53.038   317  7104 V AudioCache: ignored
08-26 15:42:53.038   317  7104 V AudioCache: notify(0xb54747c0, 1, 0, 0)
08-26 15:42:53.038   317  7104 V AudioCache: prepared
08-26 15:42:53.038   317  1382 V AudioCache: wait - success
08-26 15:42:53.038   317  1382 V MediaPlayerService: start
08-26 15:42:53.038   317  1382 V AwesomePlayer: play_l() 
08-26 15:42:53.038   317  1382 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 15:42:53.038   317  1382 V AwesomePlayer: createAudioPlayer_l
08-26 15:42:53.038   317  1382 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 15:42:53.038   317  1382 V AwesomePlayer: startAudioPlayer_l() 
08-26 15:42:53.038   317  1382 D AudioPlayer: start of Playback, useOffload 0
08-26 15:42:53.038   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 15:42:53.038   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1,
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048896
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048976
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 15:42:53.054   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 15:42:53.055   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 15:42:53.055   317  7106 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 15:42:53.055   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 15:42:53.055   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
08-26 15:42:53.055   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-26 15:42:53.055   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-26 15:42:53.056   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-26 15:42:53.056   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 15:42:53.056   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 15:42:53.056   317  1382 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 15:42:53.056   317  1382 V AudioCache: notify(0xb54747c0, 6, 0, 0)
08-26 15:42:53.056   317  1382 V AudioCache: ignored
08-26 15:42:53.057   317  1382 V MediaPlayerService: wait for playback complete
08-26 15:42:53.059   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.059   317  7107 V AudioCache: memcpy(0xaf004000, 0xb57c2000, 4096)
08-26 15:42:53.062   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.062   317  7107 V AudioCache: memcpy(0xaf005000, 0xb57c2000, 4096)
08-26 15:42:53.063   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.063   317  7107 V AudioCache: memcpy(0xaf006000, 0xb57c2000, 4096)
08-26 15:42:53.064   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.064   317  7107 V AudioCache: memcpy(0xaf007000, 0xb57c2000, 4096)
08-26 15:42:53.064   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.064   317  7107 V AudioCache: memcpy(0xaf008000, 0xb57c2000, 4096)
08-26 15:42:53.065   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.065   317  7107 V AudioCache: memcpy(0xaf009000, 0xb57c2000, 4096)
08-26 15:42:53.066   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.066   317  7107 V AudioCache: memcpy(0xaf00a000, 0xb57c2000, 4096)
08-26 15:42:53.066   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.066   317  7107 V AudioCache: memcpy(0xaf00b000, 0xb57c2000, 4096)
08-26 15:42:53.066   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.067   317  7107 V AudioCache: memcpy(0xaf00c000, 0xb57c2000, 4096)
08-26 15:42:53.067   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.067   317  7107 V AudioCache: memcpy(0xaf00d000, 0xb57c2000, 4096)
08-26 15:42:53.069   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.069   317  7107 V AudioCache: memcpy(0xaf00e000, 0xb57c2000, 4096)
08-26 15:42:53.069   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.069   317  7107 V AudioCache: memcpy(0xaf00f000, 0xb57c2000, 4096)
08-26 15:42:53.069   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.070   317  7107 V AudioCache: memcpy(0xaf010000, 0xb57c2000, 4096)
08-26 15:42:53.070   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.070   317  7107 V AudioCache: memcpy(0xaf011000, 0xb57c2000, 4096)
08-26 15:42:53.072   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.072   317  7107 V AudioCache: memcpy(0xaf012000, 0xb57c2000, 4096)
08-26 15:42:53.072   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.072   317  7107 V AudioCache: memcpy(0xaf013000, 0xb57c2000, 4096)
08-26 15:42:53.072   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.072   317  7107 V AudioCache: memcpy(0xaf014000, 0xb57c2000, 4096)
08-26 15:42:53.074   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.074   317  7107 V AudioCache: memcpy(0xaf015000, 0xb57c2000, 4096)
08-26 15:42:53.074   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.074   317  7107 V AudioCache: memcpy(0xaf016000, 0xb57c2000, 4096)
08-26 15:42:53.075   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.075   317  7107 V AudioCache: memcpy(0xaf017000, 0xb57c2000, 4096)
08-26 15:42:53.075   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.075   317  7107 V AudioCache: memcpy(0xaf018000, 0xb57c2000, 4096)
08-26 15:42:53.076   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.076   317  7107 V AudioCache: memcpy(0xaf019000, 0xb57c2000, 4096)
08-26 15:42:53.077   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.077   317  7107 V AudioCache: memcpy(0xaf01a000, 0xb57c2000, 4096)
08-26 15:42:53.077   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.077   317  7107 V AudioCache: memcpy(0xaf01b000, 0xb57c2000, 4096)
08-26 15:42:53.078   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.078   317  7107 V AudioCache: memcpy(0xaf01c000, 0xb57c2000, 4096)
08-26 15:42:53.078   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.078   317  7107 V AudioCache: memcpy(0xaf01d000, 0xb57c2000, 4096)
08-26 15:42:53.079   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.079   317  7107 V AudioCache: memcpy(0xaf01e000, 0xb57c2000, 4096)
08-26 15:42:53.079  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:53.079   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.079   317  7107 V AudioCache: memcpy(0xaf01f000, 0xb57c2000, 4096)
08-26 15:42:53.080   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.080   317  7107 V AudioCache: memcpy(0xaf020000, 0xb57c2000, 4096)
08-26 15:42:53.081   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.081   317  7107 V AudioCache: memcpy(0xaf021000, 0xb57c2000, 4096)
08-26 15:42:53.081   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.081   317  7107 V AudioCache: memcpy(0xaf022000, 0xb57c2000, 4096)
08-26 15:42:53.082  7075  7075 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 15:42:53.082  7075  7075 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 15:42:53.082   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.082   317  7107 V AudioCache: memcpy(0xaf023000, 0xb57c2000, 4096)
08-26 15:42:53.082  7075  7075 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 15:42:53.083   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.083   317  7107 V AudioCache: memcpy(0xaf024000, 0xb57c2000, 4096)
08-26 15:42:53.083  7075  7075 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:53.083   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.083   317  7107 V AudioCache: memcpy(0xaf025000, 0xb57c2000, 4096)
08-26 15:42:53.083  7075  7075 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 15:42:53.084   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.084   317  7107 V AudioCache: memcpy(0xaf026000, 0xb57c2000, 4096)
08-26 15:42:53.085   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.085   317  7107 V AudioCache: memcpy(0xaf027000, 0xb57c2000, 4096)
08-26 15:42:53.086   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.086   317  7107 V AudioCache: memcpy(0xaf028000, 0xb57c2000, 4096)
08-26 15:42:53.086   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.087   317  7107 V AudioCache: memcpy(0xaf029000, 0xb57c2000, 4096)
08-26 15:42:53.087   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.087   317  7107 V AudioCache: memcpy(0xaf02a000, 0xb57c2000, 4096)
08-26 15:42:53.088   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.088   317  7107 V AudioCache: memcpy(0xaf02b000, 0xb57c2000, 4096)
08-26 15:42:53.089   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.089   317  7107 V AudioCache: memcpy(0xaf02c000, 0xb57c2000, 4096)
08-26 15:42:53.089   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.089   317  7107 V AudioCache: memcpy(0xaf02d000, 0xb57c2000, 4096)
08-26 15:42:53.090  7025  7025 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 15:42:53.090   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.090   317  7107 V AudioCache: memcpy(0xaf02e000, 0xb57c2000, 4096)
08-26 15:42:53.091   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.091   317  7107 V AudioCache: memcpy(0xaf02f000, 0xb57c2000, 4096)
08-26 15:42:53.091   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.091   317  7107 V AudioCache: memcpy(0xaf030000, 0xb57c2000, 4096)
08-26 15:42:53.092   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.092   317  7107 V AudioCache: memcpy(0xaf031000, 0xb57c2000, 4096)
08-26 15:42:53.093   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.093   317  7107 V AudioCache: memcpy(0xaf032000, 0xb57c2000, 4096)
,08-26 15:42:53.093   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.093   317  7107 V AudioCache: memcpy(0xaf033000, 0xb57c2000, 4096)
08-26 15:42:53.094   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.094   317  7107 V AudioCache: memcpy(0xaf034000, 0xb57c2000, 4096)
08-26 15:42:53.094   317  7107 V AudioCache: write(0xb57c2000, 4096)
08-26 15:42:53.094   317  7107 V AudioCache: memcpy(0xaf035000, 0xb57c2000, 4096)
08-26 15:42:53.095   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 15:42:53.095   317  7107 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 15:42:53.095   317  7107 V AwesomePlayer: postAudioEOS() 
08-26 15:42:53.095   317  7107 V AudioCache: write(0xb57c2000, 280)
08-26 15:42:53.095   317  7107 V AudioCache: memcpy(0xaf036000, 0xb57c2000, 280)
08-26 15:42:53.098   317  7104 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 15:42:53.098   317  7104 V AwesomePlayer: onStreamDone
08-26 15:42:53.098   317  7104 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 15:42:53.098   317  7104 V AudioCache: notify(0xb54747c0, 2, 0, 0)
08-26 15:42:53.098   317  7104 V AudioCache: playback complete
08-26 15:42:53.098   317  7104 V AwesomePlayer: pause_l() 
08-26 15:42:53.098   317  7104 V AudioCache: notify(0xb54747c0, 7, 0, 0)
08-26 15:42:53.098   317  1382 V AudioCache: wait - success
08-26 15:42:53.098   317  7104 V AudioCache: ignored
08-26 15:42:53.098   317  7104 V AwesomePlayer: cancelPlayerEvents
08-26 15:42:53.098   317  1382 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 15:42:53.099   317  7104 D AudioPlayer: Pause Playback at 1068125
08-26 15:42:53.099   317  1382 V AwesomePlayer: reset_l() 
08-26 15:42:53.099   317  1382 V AudioCache: notify(0xb54747c0, 8, 0, 0)
08-26 15:42:53.099   317  1382 V AudioCache: ignored
08-26 15:42:53.099   317  1382 V AwesomePlayer: cancelPlayerEvents
08-26 15:42:53.099   317  1382 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 15:42:53.099   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 15:42:53.099   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 15:42:53.099   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 15:42:53.099   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 0
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 15:42:53.099   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-26 15:42:53.100   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 15:42:53.100   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-26 15:42:53.100   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 15:42:53.100   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
08-26 15:42:53.100   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 15:42:53.100   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fc40 on port 1
08-26 15:42:53.100   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 15:42:53.100   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 15:42:53.100   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 15:42:53.100   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 15:42:53.100   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 15:42:53.100   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 15:42:53.100   317  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 15:42:53.100   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 15:42:53.100   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 15:42:53.100   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 15:42:53.101   317  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 15:42:53.101   317  1382 D AudioPlayer: AudioPlayer releasing audio source
08-26 15:42:53.101   317  1382 D AudioPlayer: AudioPlayer done releasing audio source
08-26 15:42:53.101   317  1382 V AwesomePlayer: reset_l() 
08-26 15:42:53.101   317  1382 V AwesomePlayer: cancelPlayerEvents
08-26 15:42:53.102   317  1382 V AwesomePlayer: ~AwesomePlayer call
08-26 15:42:53.102   317  1382 V AwesomePlayer: reset_l() 
08-26 15:42:53.102   317  1382 V AwesomePlayer: cancelPlayerEvents
08-26 15:42:53.102  7005  7101 V SoundPool: close(31)
08-26 15:42:53.102  7005  7101 V SoundPool: pointer = 0xa0040000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 15:42:53.108  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-26 15:42:53.109  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-26 15:42:53.111  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7823
08-26 15:42:53.309  6832  6832 I UEI.SmartControl: Supports setup maps: true
,08-26 15:42:53.312  6832  6832 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 15:42:53.312  6832  6832 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-26 15:42:53.312  6832  6832 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-26 15:42:53.312  6832  6832 I UEI.SmartControl: ### init IR Blaster...
08-26 15:42:53.315  6832  6832 D serial_port: Configuring serial port
08-26 15:42:53.316  6832  6832 E UEI.SmartControl: UEIBLaster setting for 616
08-26 15:42:53.316  6832  6832 I UEI.SmartControl: Setting serial record hearder size = 2
,08-26 15:42:53.316  6832  6832 I UEI.SmartControl: configuring settings for MAXQ616
08-26 15:42:53.316  6832  6832 I UEI.SmartControl: Get version...
08-26 15:42:53.335  6832  7109 D UEI.SmartControl: serial port data available: 21
,08-26 15:42:53.361  6832  6832 D UEI.SmartControl: MAXQ616 A2-X4 software.,
08-26 15:42:53.362  6832  6832 I UEI.SmartControl: IR Blaster version: 256702256704300002,
,08-26 15:42:53.362  6832  6832 I UEI.SmartControl: QS saving settings...
,08-26 15:42:53.363  6832  6832 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 15:42:53.380  6832  7109 D UEI.SmartControl: serial port data available: 4,
,08-26 15:42:53.417  6832  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 15:42:53.424  6832  6832 E UEI.SmartControl: Services init done
08-26 15:42:53.424  6832  6832 D UEI.SmartControl: QS Service init finished
08-26 15:42:53.427  6832  6832 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 15:42:53.427  6832  6832 D UEI.SmartControl: QS Service version code: 201091
08-26 15:42:53.428  6832  6832 D UEI.SmartControl: Service requested: Control
08-26 15:42:53.430  6832  7118 I UEI.SmartControl: Device manager: loading config....
08-26 15:42:53.430  6832  7118 D UEI.SmartControl: ----------- loading internal config...
08-26 15:42:53.431  7005  7005 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 15:42:53.432  6832  6832 D UEI.SmartControl: Internal service binding...
,08-26 15:42:53.433  6832  6853 I UEI.SmartControl: ------ IControl API: 11
08-26 15:42:53.433  6832  6853 D UEI.SmartControl: File observer start...
08-26 15:42:53.433  6832  6853 E UEI.SmartControl: IR Port is disabled: false
08-26 15:42:53.433  6832  6853 D UEI.SmartControl: Starting file observer...
08-26 15:42:53.435  6832  6853 I UEI.SmartControl: Registering callback...
08-26 15:42:53.436  6832  6851 I UEI.SmartControl: ------ IControl API: 19
08-26 15:42:53.437  6832  6851 I UEI.SmartControl: Registering Services Ready callback...
08-26 15:42:53.439  6832  7118 E UEI.SmartControl: Loading SETTINGS...
08-26 15:42:53.443  6832  7118 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 15:42:53.452  6832  7114 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 15:42:53.453  7005  7020 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 15:42:53.454  7005  7099 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 15:42:53.454  7005  7099 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-26 15:42:53.454  6832  7114 D UEI.SmartControl: -----service ready thread exits
08-26 15:42:53.455  7005  7005 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 15:42:53.456  7005  7005 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 15:42:53.456  6832  6853 I UEI.SmartControl: ------ IControl API: 8
08-26 15:42:53.458  7005  7005 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 15:42:53.458  7005  7005 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 15:42:53.458  7005  7005 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 15:42:53.459  7005  7005 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 15:42:53.459  7005  7005 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 15:42:53.460  7005  7005 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 15:42:53.461  7005  7005 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 15:42:53.464  7005  7005 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 15:42:53.465  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 15:42:53.466  7005  7005 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 15:42:53.466  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-26 15:42:53.467  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 15:42:53.468  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-26 15:42:53.469  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 15:42:53.470  7005  7005 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472218973470]
08-26 15:42:53.475  7005  7005 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 15:42:53.476  1032  2052 I ActivityManager: Killing 6099:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-26 15:42:53.498  7005  7120 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 15:42:53.509  1032  2052 I ActivityManager: Killing 6605:com.lge.email/u0a23 (adj 15): empty #18
,08-26 15:42:53.540  1032  1890 W libprocessgroup: failed to open /acct/uid_10027/pid_6099/cgroup.procs: No such file or directory
,08-26 15:42:53.547  1032  1575 W libprocessgroup: failed to open /acct/uid_10023/pid_6605/cgroup.procs: No such file or directory
08-26 15:42:53.548  7005  7005 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-26 15:42:53.548  7005  7005 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 15:42:53.549  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 15:42:53.549  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 15:42:53.550  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 15:42:53.550  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 15:42:53.550  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-26 15:42:53.564  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 15:42:54.401  1032  1047 D WifiServiceImplEx: setWifiEnabled: true pid=6697, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 15:42:54.403  1032  1047 D WifiService: setWifiEnabled: true pid=6697, uid=10118
08-26 15:42:54.403  1032  1047 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 15:42:54.426  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 15:42:54.426  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 15:42:54.426  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,08-26 15:42:54.430  1032  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-26 15:42:54.430  1032  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-26 15:42:54.432  1032  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-26 15:42:54.432  1032  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-26 15:42:54.432  1032  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin],
08-26 15:42:54.432  1032  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 15:42:54.433  1032  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 15:42:54.433  1032  1539 E WifiHW  : unknown target_country: EU , set to default
,08-26 15:42:54.433  1032  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
,08-26 15:42:54.433  1032  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-26 15:42:54.433  1032  1539 I WifiUtil: gEnableBmps=1
,08-26 15:42:54.523  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:54.556  1032  1095 D Tethering: MasterInitialState.processMessage what=3
,08-26 15:42:54.574  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:54.577  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:54.584  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:54.587  1032  1095 D Tethering: MasterInitialState.processMessage what=3
,08-26 15:42:54.597  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:54.599  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:54.601  1032  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:54.603  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 15:42:54.606  6510  6544 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 15:42:54.618  5800  5800 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 15:42:54.632  5800  5800 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 15:42:54.653  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:54.689  1032  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:54.739  1032  2015 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7137 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-26 15:42:54.746  1032  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:54.746  1032  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 15:42:54.817  7137  7137 I AppUp4:AppBoxCP: onCreate
08-26 15:42:54.818  7137  7137 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-26 15:42:54.828  7137  7137 I AppUp4:DB:  setFingerPrint start
08-26 15:42:54.829  7137  7137 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 15:42:54.837  7137  7137 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-26 15:42:54.837  7137  7137 I AppUp4:DB:  SDK version = 21
08-26 15:42:54.837  7137  7137 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-26 15:42:54.840  7137  7137 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-26 15:42:54.842  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 15:42:54.842  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:54.844  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 15:42:54.845  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 15:42:54.853  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 15:42:54.904  7137  7137 D LgDataFeature: LgDataFeature() Constructor: none
08-26 15:42:54.905  7137  7137 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 15:42:54.920  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4639aff
08-26 15:42:54.920  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 15:42:54.920  7137  7137 D AppUp4:CustFacade: isPhone : true
08-26 15:42:54.921  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-26 15:42:54.921  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-26 15:42:54.922  7137  7137 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-26 15:42:54.922  7137  7159 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-26 15:42:54.923  7137  7159 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-26 15:42:54.923  7137  7159 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-26 15:42:54.925  1032  2015 I ActivityManager: Killing 6643:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-26 15:42:54.985  1032  1047 W libprocessgroup: failed to open /acct/uid_10061/pid_6643/cgroup.procs: No such file or directory
,08-26 15:42:54.986  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:54.987  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 15:42:54.990  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 15:42:54.993  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 15:42:55.001  4356  7171 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 15:42:55.004  4356  7172 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:55.005  4356  7172 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 15:42:55.044  1032  1924 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7173 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 15:42:55.114  1032  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:42:55.114  1032  1095 D Tethering: InitialState.processMessage what=4
08-26 15:42:55.114   313   907 D SoftapController: Softap fwReload - Ok
08-26 15:42:55.115  1032  1539 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (676ms)
08-26 15:42:55.116  1032  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:42:55.120   313   907 D CommandListener: Setting iface cfg
08-26 15:42:55.120   313   907 D CommandListener: Trying to bring down wlan0
08-26 15:42:55.121   313   907 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:42:55.125  1032  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-26 15:42:55.129  1032  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 15:42:55.129  1032  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 15:42:55.129  1032  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 15:42:55.131  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:55.132  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 15:42:55.119  7191  7191 W wpa_supplicant: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:42:55.119  7191  7191 W wpa_supplicant: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:42:55.135  7173  7173 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:42:55.135  7173  7173 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 15:42:55.137  7173  7173 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 15:42:55.137  7173  7173 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 15:42:55.140  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 15:42:55.141  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:55.149  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:55.149  1032  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 15:42:55.149  1032  1539 D WifiMonitor: connecting to supplicant
,08-26 15:42:55.167  7191  7191 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 15:42:55.200  7191  7191 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 15:42:55.200  7191  7191 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 15:42:55.244  7173  7173 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 15:42:55.259  7173  7173 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-26 15:42:55.288  7191  7191 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 15:42:55.312  7173  7173 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 15:42:55.322  7191  7191 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-26 15:42:55.329  1032  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 15:42:55.329  1032  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 15:42:55.329  7191  7191 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-26 15:42:55.330  1032  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 15:42:55.330  1032  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 15:42:55.331  1032  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:55.331  1032  7198 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,08-26 15:42:55.331  1032  7198 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-26 15:42:55.331  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 15:42:55.331  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 15:42:55.331  7191  7191 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 15:42:55.332  1032  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:55.332  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 15:42:55.332  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 15:42:55.332  1032  7198 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 15:42:55.332  1032  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:55.332  1032  7198 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 15:42:55.332  1032  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:55.333  1032  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 15:42:55.333  1032  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 15:42:55.334  1032  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 15:42:55.334  1032  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 15:42:55.334  1032  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 15:42:55.335  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:55.336  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:55.336  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:55.336  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:55.336  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 15:42:55.336  1032  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 15:42:55.336  1032  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 15:42:55.336  1032  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 15:42:55.339  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:55.339  1032  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 15:42:55.340  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-26 15:42:55.340  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 15:42:55.341  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 15:42:55.342  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:55.342  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:55.342  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:55.342  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:55.342  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:55.342  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:55.342  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:55.342  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:4,2:55.342  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:55.342  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:55.342  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:55.343  1032  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-26 15:42:55.343  1032  1539 D WifiConfigStore: Loading config and enabling all networks 
08-26 15:42:55.343  1032  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 15:42:55.344  1032  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 15:42:55.345  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:55.345  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:55.345  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:55.345  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:55.345  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:55.345  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:55.345  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:55.345  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:55.345  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:55.345  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:55.345  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:55.353  1032  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 15:42:55.365  1032  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 15:42:55.365  1032  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 15:42:55.366  1032  1539 D WifiStateMachine: enableVerboseLogging : level 2
,08-26 15:42:55.366  1032  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 15:42:55.367  1032  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 15:42:55.367  1032  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 15:42:55.367  1032  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 15:42:55.367  1032  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 15:42:55.368  1032  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 15:42:55.368  1032  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,08-26 15:42:55.369  7173  7173 D LgDataFeature: LgDataFeature() Constructor: none
08-26 15:42:55.369  1032  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 15:42:55.369  7173  7173 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 15:42:55.370  1032  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 15:42:55.370  1032  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 15:42:55.371  1032  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 15:42:55.371  1032  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 15:42:55.371  1032  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 15:42:55.372  1032  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 15:42:55.373  1032  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 15:42:55.374  1032  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 15:42:55.374  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-26 15:42:55.374  1943  2357 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 15:42:55.374  1943  2357 D WfdsService: Set the WFDS Monitor: true
08-26 15:42:55.374  1943  2357 D WfdsMonitor: WfdsMonitorThread create
08-26 15:42:55.374  1943  2357 D WfdsMonitor: WFDS Monitor is created and started
08-26 15:42:55.374  1943  2357 D WfdsService: WiFi: Supplicant connection re-established
08-26 15:42:55.375  1032  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 15:42:55.375  1032  1539 D WifiNative-HAL: Setting external_sim to 1
08-26 15:42:55.375  1032  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 15:42:55.376  1943  7200 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 15:42:55.376  1032  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 15:42:55.376  1032  1539 I WifiNative-HAL: startHal
08-26 15:42:55.376  1032  1539 D wifi    : setting scan oui 0xaf731320
08-26 15:42:55.377  1943  7200 E CtrlSupplicant: Succeed to open control connection
08-26 15:42:55.377  1943  7200 E CtrlSupplicant: Succeed to open monitor connection
,08-26 15:42:55.378  1032  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 15:42:55.378  1032  1539 I WifiNative-HAL: startHal
08-26 15:42:55.378  1032  1539 D wifi    : setting scan oui 0xaf731320
08-26 15:42:55.378  1943  7200 D WfdsMonitor: Supplicant connection established
08-26 15:42:55.379  1943  2357 D WfdsService: Connected to the supplicant for wfds
08-26 15:42:55.379  1032  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 15:42:55.382  1032  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 15:42:55.382  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 15:42:55.382  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 15:42:55.383  1032  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 15:42:55.383  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 15:42:55.383  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 15:42:55.384  1032  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 15:42:55.384  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 15:42:55.384  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,08-26 15:42:55.384  1032  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 15:42:55.384  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 15:42:55.384  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 15:42:55.385  1032  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 15:42:55.385  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 15:42:55.385  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 15:42:55.386  1032  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 15:42:55.386  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 15:42:55.386  7191  7191 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 15:42:55.386  1032  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 15:42:55.386  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 15:42:55.386  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 15:42:55.387  1032  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 15:42:55.388  1032  1539 E WifiNative: : [124,726,172 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 15:42:55.388  1032  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 15:42:55.389  1032  1539 D WifiNative-wlan0: RECONNECT: returned true
08-26 15:42:55.389  1032  1539 D WifiNative-wlan0: doString: [STATUS]
08-26 15:42:55.389  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 15:42:55.389  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 15:42:55.390  1032  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 15:42:55.390  1032  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 15:42:55.390  1032  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 15:42:55.390  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.391  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 15:42:55.391  1032  1032 D RttService: SCAN_AVAILABLE : 3
08-26 15:42:55.391  1032  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.391  1032  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,08-26 15:42:55.392  1032  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 15:42:55.392  1032  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 15:42:55.392  1032  1556 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.392  1032  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 15:42:55.393  1032  1556 I WifiNative-HAL: startHal
08-26 15:42:55.393  1032  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf731320
08-26 15:42:55.393  1032  1556 D wifi    : failed to get capabilities : -3
08-26 15:42:55.393  1032  1556 E WifiScanningService: could not get scan capabilities
08-26 15:42:55.393  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=124732  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 15:42:55.394  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=124733  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 15:42:55.394   313   907 D CommandListener: Setting iface cfg
08-26 15:42:55.394   313   907 D CommandListener: Trying to bring up p2p0
08-26 15:42:55.395  1032  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 15:42:55.395  1032  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 15:42:55.395  1032  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 15:42:55.396  1032  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 15:42:55.396  7191  7191 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 15:42:55.396  1032  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 15:42:55.397  1032  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 15:42:55.397  1032  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 15:42:55.397  1032  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 15:42:55.397  7191  7191 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-26 15:42:55.399  1032  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 15:42:55.400  1032  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 15:42:55.400  1032  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 15:42:55.400  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 15:42:55.401  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:55.401  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:55.401  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 15:42:55.402  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:55.402  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:55.402  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 15:42:55.402  1032  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 15:42:55.402  1032  1537 D LGWifiP2pService: P2pEnablingState
08-26 15:42:55.402  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:55.402  7191  7191 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:42:55.404  7191  7191 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 15:42:55.404  7191  7191 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.404  1032  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.404  1032  1537 D LGWifiP2pService: P2p socket connection successful
08-26 15:42:55.404  1032  1537 D LGWifiP2pService: P2pEnabledState
08-26 15:42:55.404  7191  7191 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.405  1943  7200 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:42:55.405  1943  7200 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:42:55.405  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 15:42:55.405  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:42:55.406  1032  7198 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:42:55.406  1032  7198 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:42:55.406  1032  7198 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:42:55.406  1032  7198 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.406  1032  7198 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.406  1032  7198 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.406  1032  7198 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:42:55.406  1032  7198 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.406  1032  7198 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.406  1032  7198 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.407  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 ,15:42:55.407  1943  1943 D WfdsService: WifiP2pState is changed : true
08-26 15:42:55.407  1032  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 15:42:55.407  1943  2357 D WfdsService: Receive the WFDS_ENABLE Method
08-26 15:42:55.407  1943  2357 D WfdsService: Set the WFDS Monitor: true
08-26 15:42:55.408  1943  2357 D WfdsService: Connected to the supplicant for wfds
08-26 15:42:55.408  1943  2357 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 15:42:55.408  7191  7191 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 15:42:55.408  1943  2357 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
08-26 15:42:55.408  7191  7191 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-26 15:42:55.408  1943  2357 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-26 15:42:55.409  1943  2357 D WfdsService: selectPreferredScanChannel [36]
08-26 15:42:55.409  1943  2357 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 15:42:55.409  1032  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 15:42:55.409  1032  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 15:42:55.410  1032  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 15:42:55.410  1032  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 15:42:55.410  1032  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 15:42:55.410  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 15:42:55.410  1032  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 15:42:55.411  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 15:42:55.411  7191  7191 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 15:42:55.411  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 15:42:55.412  1032  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 15:42:55.412  1032  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 15:42:55.412  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 15:42:55.412  1032  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 15:42:55.412  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 15:42:55.412  1032  7198 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 15:42:55.412  1032  7198 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-26 15:42:55.412  1943  1943 D WfdsService: isConnected: false
08-26 15:42:55.412  1032  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 15:42:55.412  1032  1539 D WifiNative-wlan0: doBoolean: SCAN
08-26 15:42:55.413  1032  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-26 15:42:55.413  1032  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
,08-26 15:42:55.413  1032  1537 D LGWifiP2pService: before postfix = G3
08-26 15:42:55.413  1032  1537 D WifiServerServiceExt: postfix byte check : 2
08-26 15:42:55.413  1032  1537 D LGWifiP2pService: after postfix = G3
08-26 15:42:55.413  1032  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 15:42:55.413  1032  1539 D WifiNative-wlan0: SCAN: returned false
,08-26 15:42:55.413  1032  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 15:42:55.413  1032  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 15:42:55.414  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=124752  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 15:42:55.414  1032  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
,08-26 15:42:55.414  1032  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 15:42:55.414  1032  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 15:42:55.414  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 15:42:55.414  1032  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,08-26 15:42:55.415  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-26 15:42:55.415  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=124753  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 15:42:55.415  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 15:42:55.415  1032  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d,
08-26 15:42:55.415  1032  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 15:42:55.416  1032  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 15:42:55.416  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 15:42:55.416  1032  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,08-26 15:42:55.416  1032  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 15:42:55.417  1032  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 15:42:55.417  1032  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-26 15:42:55.418  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:55.418  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:55.418  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 15:42:55.418  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:42:55.418  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 15:42:55.421  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 15:42:55.421  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 15:42:55.421  1943  1943 D WfdsService: Update P2p Interface State: 3
08-26 15:42:55.422  1032  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 15:42:55.423  1032  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 15:42:55.423  1032  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 15:42:55.424  1032  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 15:42:55.424  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:55.424  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:55.424  1032  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 15:42:55.425  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:55.425  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:42:55.425  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 15:42:55.429  1032  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 15:42:55.429  1032  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 15:42:55.429  1032  1537 D LGWifiP2pService: InactiveState
08-26 15:42:55.430  1032  1537 D LGWifiP2pService: InactiveState{ when=-21ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.430  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.430  1032  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-26 15:42:55.431  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 15:42:55.431  7191  7191 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:42:55.432  7191  7191 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 15:42:55.432  7191  7191 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.432  7191  7191 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.433  1943  7200 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 15:42:55.433  1943  7200 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:42:55.433  1943  7200 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:42:55.433  1032  7198 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 15:42:55.434  1032  7198 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:42:55.434  1032  7198 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:42:55.434  1032  7198 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:42:55.434  1032  7198 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:42:55.434  1032  7198 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.434  1032  7198 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.434  1032  7198 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.434  1032  7198 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:42:55.434  1032  7198 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.434  1032  7198 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.434  1032  7198 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:42:55.435  1032  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 15:42:55.435  1032  1537 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.435  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.436  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.436  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.436  1032  1537 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.436  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.436  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.436  1032  1537 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.436  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.436  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.436  1032  1537 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.437  1032  1537 D LGW,ifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.437  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.437  1032  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:55.437  1943  2357 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 15:42:55.437  1032  1032 E WifiServerServiceExt: No p2p device connected
,08-26 15:42:55.503  7173  7173 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 15:42:55.536  7173  7173 I HubEmail: JNI_OnLoad()
,08-26 15:42:55.536  7173  7173 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 15:42:55.536  7173  7173 I HubEmail: registerNatives()
08-26 15:42:55.536  7173  7173 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 15:42:55.536  7173  7173 I HubEmail: registerNativeMethods()
08-26 15:42:55.536  7173  7173 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 15:42:55.537  7173  7173 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-26 15:42:55.562  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 15:42:55.562  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:55.563  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 15:42:55.565  7173  7205 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:55.606  1032  1047 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7209 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-26 15:42:55.610  7046  7206 W FormManager: Network not available. Please check & try again.
,08-26 15:42:55.614  7046  7207 V FormManager: Network unavailable.
08-26 15:42:55.618  7046  7207 V FormManager: Network unavailable.
08-26 15:42:55.626  1032  1924 I ActivityManager: Killing 6161:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-26 15:42:55.687  1032  1047 W libprocessgroup: failed to open /acct/uid_10080/pid_6161/cgroup.procs: No such file or directory
08-26 15:42:55.788  7209  7209 D LgDataFeature: LgDataFeature() Constructor: none
08-26 15:42:55.788  7209  7209 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 15:42:55.793  7209  7209 D PhoneMonitor: Register our PhoneStateListener
08-26 15:42:55.813  7209  7209 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 15:42:55.818  7209  7209 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 15:42:55.845  7209  7209 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-26 15:42:55.847  7209  7209 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-26 15:42:55.848  7209  7209 D TelephonyAutoProfiling: [parse] Load xml
08-26 15:42:55.854  7209  7209 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-26 15:42:55.855  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-26 15:42:55.856  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-26 15:42:55.856  7209  7209 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-26 15:42:55.856  7209  7209 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-26 15:42:55.870  7209  7209 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-26 15:42:55.878  1032  1048 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7231 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:55.879  1032  1048 I ActivityManager: Killing 6193:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-26 15:42:55.939  1032  1890 W libprocessgroup: failed to open /acct/uid_10097/pid_6193/cgroup.procs: No such file or directory
,08-26 15:42:55.944  7191  7191 E wpa_supplicant: USIM:  scard_init function
08-26 15:42:55.944  7191  7191 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 15:42:55.946  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 15:42:55.946  1032  7198 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 15:42:55.946  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 15:42:55.946  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-26 15:42:55.946  1032  7198 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 15:42:55.946  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 15:42:55.946  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 15:42:55.946  1032  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-26 15:42:55.947  1032  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-26 15:42:55.947  1032  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-26 15:42:55.948  1032  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-26 15:42:55.948  1032  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 15:42:55.956  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=125295  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 15:42:55.962  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:55.962  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:55.964  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:55.964  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:55.964  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:55.964  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 15:42:55.965  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=125303  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 15:42:55.966  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:42:55.966  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 15:42:56.062  7191  7191 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 15:42:56.065  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 15:42:56.065  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-26 15:42:56.067  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=125406  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 15:42:56.072  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 15:42:56.072  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 15:42:56.072  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 15:42:56.072  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 15:42:56.073  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=125407  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 15:42:56.073  1032  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=125412
08-26 15:42:56.074  1032  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=125413
08-26 15:42:56.074  1032  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=125413
08-26 15:42:56.075  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=125413
08-26 15:42:56.075  1032  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=125414
08-26 15:42:56.076  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=125414  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 15:42:56.076  7191  7191 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 15:42:56.076  7191  7191 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 15:42:56.078  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 15:42:56.078  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 15:42:56.078  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 15:42:56.078  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 15:42:56.078  1032  7198 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 15:42:56.078  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 15:42:56.078  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 15:42:56.078  1032  7198 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 15:42:56.079  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 15:42:56.079  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 15:42:56.080  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.081  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.081  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-26 15:42:56.081  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:56.081  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:56.082  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.085  1032  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 15:42:56.088  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=125426  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 15:42:56.089  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=125427  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 15:42:56.089  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=125428  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 15:42:56.090  1032  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=125429
08-26 15:42:56.090  1032  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=125429
08-26 15:42:56.091  1032  1539 D WifiNative-wlan0: doString: [STATUS]
08-26 15:42:56.091  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.091  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.091  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 15:42:56.091  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:42:56.091  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 15:42:56.092  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 15:42:56.092  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 15:42:56.092  1032  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 15:42:56.094  1032  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 15:42:56.103  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:56.103  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 15:42:56.104  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.108  1032  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 15:42:56.108  1032  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 15:42:56.112  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.112  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.113  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 15:42:56.115  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.115  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.115  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-26 15:42:56.125  1032  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 15:42:56.126  1032  1545 D ConnectivityService: Got NetworkAgent Messenger
08-26 15:42:56.126  1032  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:42:56.126  1032  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 15:42:56.126  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 15:42:56.126  1032  1545 D ConnectivityService: NetworkAgent connected
08-26 15:42:56.126  1032  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 15:42:56.126  1032  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 15:42:56.131  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:56.131  1032  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 15:42:56.131  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:56.131  1032  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:42:56.131  1032  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 15:42:56.132  1032  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 15:42:56.132  1032  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 15:42:56.135  1032  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 15:42:56.139   313   907 D CommandListener: Setting iface cfg
08-26 15:42:56.139  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.141  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:56.141  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:56.143  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.143  1032  1539 E WifiStateMachine: Start Dhcp Watchdog 2
08-26 15:42:56.144  1032  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=125482  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 15:42:56.144  1032  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=125483  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 15:42:56.145  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=125483  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 15:42:56.145  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:56.146  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:56.146  1032  7254 D DhcpStateMachine: StoppedState
08-26 15:42:56.146  1032  7254 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.146  1032  7254 D DhcpStateMachine: WaitBeforeStartState
08-26 15:42:56.146  1032  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:56.147  1032  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:56.147  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:56.147  1032  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-26 15:42:56.149  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:42:56.150  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 15:42:56.151  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:42:56.151  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 15:42:56.153  1032  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=125491  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 15:42:56.153  1032  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=125492  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 15:42:56.154  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=125492  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 15:42:56.155  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:79780] from screen [on:0 period:-954806373] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-26 15:42:56.156  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-954806372] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-26 15:42:56.156  1032  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 15:42:56.160  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.161  1032  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 15:42:56.161  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 15:42:56.161  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:56.162  1032  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 15:42:56.163  1032  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:56.164  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:56.166  1032  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:56.167  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 15:42:56.219  1032  1048 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7255 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-26 15:42:56.220  1032  1048 I ActivityManager: Killing 6744:com.lge.eula/1000 (adj 15): empty #17
,08-26 15:42:56.282  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
,08-26 15:42:56.283  1032  1575 W libprocessgroup: failed to open /acct/uid_1000/pid_6744/cgroup.procs: No such file or directory
08-26 15:42:56.284  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
08-26 15:42:56.284  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 15:42:56.285  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 15:42:56.286  1032  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 15:42:56.286  1032  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 15:42:56.287  1032  1539 D WifiNative-wlan0: SET ps 0: returned true
08-26 15:42:56.287  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 15:42:56.288  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 15:42:56.289  1032  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 15:42:56.290  1032  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@a35e248 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.290  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@a35e248 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.290  1032  7254 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.290  1032  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 15:42:56.290  1032  7254 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 15:42:56.290  1032  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 15:42:56.291  1032  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 15:42:56.292   313   907 D CommandListener: Setting iface cfg
08-26 15:42:56.293   313   907 D CommandListener: Trying to bring up wlan0
08-26 15:42:56.295  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:42:56.295  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 15:42:56.297  1032  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 15:42:56.299  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:56.299  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:42:56.299  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 15:42:56.300  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:56.301  1032  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 15:42:56.301  1032  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:56.302  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:56.303  1032  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:42:56.304  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 15:42:56.305  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 15:42:56.306  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 15:42:56.307  1032  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.307  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.307  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 15:42:56.308  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 15:42:56.309  1032  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 15:42:56.309  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 15:42:56.309  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 15:42:56.310  1032  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 15:42:56.310  1032  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 15:42:56.327  1032  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 15:42:56.328  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 15:42:56.328  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 15:42:56.328  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 15:42:56.328  1032  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 15:42:56.329  1032  1545 D ConnectivityService: ignoring duplicate network state non-change
,08-26 15:42:56.333  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:56.333  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:56.334  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.335  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.335  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.336  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 15:42:56.339  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 15:42:56.340  1032  1545 D ConnectivityService: Adding iface wlan0 to network 101
08-26 15:42:56.342  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.342  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:56.343  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 15:42:56.348  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 15:42:56.348  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-26 15:42:56.348  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.348  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.348  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 15:42:56.357  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:56.357  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 15:42:56.359  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.361  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:56.362  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 15:42:56.362  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.370  1032  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 15:42:56.371  1032  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 15:42:56.372  1032  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-26 15:42:56.373   313   907 E Netd    : netlink response contains error (File exists)
08-26 15:42:56.373  1032  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-26 15:42:56.374  1032  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 15:42:56.374  1032  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-26 15:42:56.374  1032  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-26 15:42:56.383  1032  1882 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7276 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:56.384  1032  1882 I ActivityManager: Killing 6763:com.lge.bnr/1000 (adj 15): empty #17
,08-26 15:42:56.491  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 15:42:56.491  1032  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 15:42:56.492  1032  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 15:42:56.492  1032  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 15:42:56.492  1032  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:56.493  1032  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.493  1032  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
,08-26 15:42:56.493  1032  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.493  1032  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 15:42:56.495  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:42:56.495  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 15:42:56.495  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 15:42:56.495  1032  7254 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 15:42:56.496  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 15:42:56.496  1032  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-26 15:42:56.496  1032  1545 D ConnectivityService:    accepting network in place of null
08-26 15:42:56.496  1032  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:56.497  1032  7254 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 15:42:56.497  1032  7254 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 15:42:56.498  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:56.503  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 15:42:56.504  1032  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 15:42:56.506  1032  1091 W ActivityManager: Failed to clear dns cache for: com.lge.bnr
08-26 15:42:56.489  7293  7293 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 15:42:56.515   313  7295 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-26 15:42:56.515   313  7295 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 15:42:56.489  7293  7293 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:42:56.517  1032  1997 W libprocessgroup: failed to open /acct/uid_1000/pid_6763/cgroup.procs: No such file or directory
08-26 15:42:56.521  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 15:42:56.526  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.526  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.526  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 15:42:56.530  7293  7293 I dhcpcd  : version 5.5.6 starting
,08-26 15:42:56.532  7293  7293 E dhcpcd  : get_duid: m
08-26 15:42:56.532  7293  7293 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 15:42:56.532  7293  7293 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 15:42:56.532  1032  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 15:42:56.532  1032  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 15:42:56.533  1032  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:56.533  1032  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:56.533  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 15:42:56.534  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:56.534  1032  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 15:42:56.535  1032  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 15:42:56.536  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 15:42:56.537  1032  1545 D ConnectivityService: validation of new default Network = false
08-26 15:42:56.537  1032  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 15:42:56.537  1032  1545 D DSQN    : enableDataServiceNotify 
,08-26 15:42:56.537  1032  1545 D DSQN    : start dsqn bin
08-26 15:42:56.541  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:56.541  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 15:42:56.542  1032  1537 D LGWifiP2pService: InactiveState{ when=-9ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.542  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.542  1032  1537 D LGWifiP2pService: DefaultState{ when=-9ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.543  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 15:42:56.543  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,08-26 15:42:56.543  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 15:42:56.544  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.546  1032  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 15:42:56.546  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:56.547  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:42:56.547  1032  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 15:42:56.547  1032  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:42:56.548  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 15:42:56.548  1032  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 15:42:56.539  7298  7298 W dsqn    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:42:56.539  7298  7298 W dsqn    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:42:56.550  1032  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 15:42:56.550  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 15:42:56.550  1603  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 15:42:56.551  1032  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 15:42:56.558  1032  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-26 15:42:56.560   313  7295 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-26 15:42:56.568  7298  7298 E DSQN    : DSQN ssw
,08-26 15:42:56.595   313  7295 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-26 15:42:56.603  7293  7293 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 15:42:56.603  7276  7276 I art     : Almond Protected OAT
08-26 15:42:56.603  7293  7293 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 15:42:56.603  7293  7293 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 15:42:56.603  7293  7293 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 15:42:56.603  7293  7293 D dhcpcd  : wlan0: sending REQUEST (xid 0xec6393e3), next in 4.80 seconds
08-26 15:42:56.603  1816  7305 I CheckinService: active receiver: enabled
08-26 15:42:56.607  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 15:42:56.608  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.609  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 15:42:56.619  1816  7305 I CheckinService: Preparing to send checkin request
08-26 15:42:56.619  1816  7305 I EventLogService: Accumulating logs since 1472218908162
,08-26 15:42:56.631  7293  7293 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-26 15:42:56.633   313   906 D LGDataListener: argv[0]=dsqncommand
08-26 15:42:56.634   313   906 D LGDataListener: argv[1]=wlan0
08-26 15:42:56.634   313   906 D LGDataListener: argv[2]=1
08-26 15:42:56.634   313   906 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 15:42:56.634  1032  1093 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 15:42:56.634  1032  1093 D DSQN    : start to monitor internet connection
08-26 15:42:56.659  7293  7293 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 15:42:56.659  7293  7293 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-26 15:42:56.659  7293  7293 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 15:42:56.660  7293  7293 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 15:42:56.660  7293  7293 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 15:42:56.661  7293  7293 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 15:42:56.661  7293  7293 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 15:42:56.661  7293  7293 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 15:42:56.661  1816  7305 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-26 15:42:56.672  7276  7276 D WeatherApplication: removeAccount
,08-26 15:42:56.674  1032  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 13:42:56 GMT], X-Android-Received-Millis=[1472218976673], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472218976633]}
08-26 15:42:56.674  1032  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 15:42:56.674  1032  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 15:42:56.675  7276  7276 D WeatherApplication: Account.length = 0
08-26 15:42:56.675  7276  7276 E WeatherApplication: OPERATOR:OPEN
08-26 15:42:56.675  1032  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-26 15:42:56.675  1032  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 15:42:56.675  1032  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:56.676  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:42:56.676  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 15:42:56.676  1032  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-26 15:42:56.676  1032  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 15:42:56.676  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:56.676  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:42:56.677  1032  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:42:56.679  1032  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:56.679  1032  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:56.679  1032  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:56.679  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 15:42:56.681  1603  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 15:42:56.681  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:56.681  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-26 15:42:56.685  7276  7276 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:42:56
08-26 15:42:56.692  7276  7276 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 15:42:56.692  7276  7276 D Weather.Utils: 2 : All the weather widget is gone.
,08-26 15:42:56.699  7276  7276 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 15:42:56.705  7276  7276 D WeatherAncestor: connectivity changed - connection : true
08-26 15:42:56.706  7276  7276 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-26 15:42:56.711  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 15:42:56.712  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.713  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:56.716  7276  7276 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 15:42:56.716  7276  7276 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 15:42:56.716  7276  7276 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-26 15:42:56.740  7276  7276 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 15:42:56.740  7276  7276 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:42:56
,08-26 15:42:56.798  1032  1937 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7323 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:56.799  1032  1937 I ActivityManager: Killing 2131:com.lge.music/u0a34 (adj 15): empty #17
08-26 15:42:56.827   340   340 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 454us total 29.017ms
,08-26 15:42:56.830   317  1737 V AudioFlinger: 2131 died, releasing its sessions
08-26 15:42:56.830   317  1737 V AudioFlinger:  pid 1853 @ 0
08-26 15:42:56.830   317  1737 V AudioFlinger:  pid 3453 @ 1
08-26 15:42:56.830   317  1737 V AudioFlinger:  pid 3453 @ 2
08-26 15:42:56.847   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 18.975ms
,08-26 15:42:56.865   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 361us total 17.183ms
,08-26 15:42:56.906  1032  7254 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-26 15:42:56.908  1032  7254 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 15:42:56.908  1032  7254 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 15:42:56.909  1032  7254 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 15:42:56.909  1032  7254 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 15:42:56.909  1032  7254 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 15:42:56.909  1032  7254 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 15:42:56.909  1032  7254 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 15:42:56.910  1032  7254 D DhcpStateMachine: RunningState
08-26 15:42:56.991  1032  1575 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7348 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-26 15:42:57.002  1032  1891 W libprocessgroup: failed to open /acct/uid_10034/pid_2131/cgroup.procs: No such file or directory
,08-26 15:42:57.061  7348  7348 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 15:42:57.061  7348  7348 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 15:42:57.094  7348  7348 I MultiDex: VM with version 2.1.0 has multidex support
08-26 15:42:57.094  7348  7348 I MultiDex: install
08-26 15:42:57.094  7348  7348 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 15:42:57.111  7348  7348 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-26 15:42:57.119   277   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 15:42:57.119   277   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 15:42:57.119   277   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 15:42:57.120  7323  7370 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 15:42:57.122   277   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 15:42:57.122   277   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 15:42:57.122   277   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 15:42:57.122  7323  7370 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-26 15:42:57.130   277   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 15:42:57.130   277   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 15:42:57.130   277   454 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:57.131  7323  7372 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 15:42:57.140  1032  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 15:42:57.141  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 15:42:57.141  1032  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 15:42:57.142  1032  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 15:42:57.142  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 15:42:57.143  1032  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 15:42:57.143  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-26 15:42:57.143  1032  1545 D ConnectivityService: identical MTU - not setting
08-26 15:42:57.144  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 15:42:57.144  1032  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 15:42:57.144  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:57.144  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:42:57.144  1032  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-26 15:42:57.147  1603  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 15:42:57.150   277   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 15:42:57.150   277   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 15:42:57.150   277   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 15:42:57.151  7323  7372 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-26 15:42:57.389  7323  7323 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 15:42:57.397  7323  7323 I LibraryLoader: Loading: webviewchromium
08-26 15:42:57.399  7323  7323 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6747-6751)
08-26 15:42:57.400  7323  7323 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 15:42:57.405  7323  7323 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3ea529a6}
,08-26 15:42:57.406  7323  7323 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 15:42:57.406  7323  7323 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 15:42:57.416  7323  7323 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 15:42:57.417  7323  7323 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:42:57.425   317  1381 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10093
08-26 15:42:57.426  7323  7402 W AudioManagerAndroid: Requires BLUETOOTH permission
08-26 15:42:57.426  7323  7323 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 15:42:57.427  7323  7323 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-26 15:42:57.427  7323  7323 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-26 15:42:57.432  1032  1961 D WifiServiceImplEx: setWifiEnabled: false pid=6697, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 15:42:57.432  1032  1961 D WifiService: setWifiEnabled: false pid=6697, uid=10118
08-26 15:42:57.432  1032  1961 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 15:42:57.441  1032  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 15:42:57.441  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 15:42:57.441  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 15:42:57.441  1032  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 15:42:57.441  1032  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 15:42:57.441  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 15:42:57.441  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-26 15:42:57.442  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 15:42:57.442  1032  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 15:42:57.442  1032  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:42:57.442  1032  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 15:42:57.442  1032  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 15:42:57.442  1032  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 15:42:57.446  7323  7323 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 15:42:57.446  7323  7323 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
,08-26 15:42:57.446  7323  7323 I Adreno-EGL: Build Date: 12/12/14 금
08-26 15:42:57.446  7323  7323 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 15:42:57.446  7323  7323 I Adreno-EGL: Remote Branch: 
08-26 15:42:57.446  7323  7323 I Adreno-EGL: Local Patches: 
08-26 15:42:57.446  7323  7323 I Adreno-EGL: Reconstruct Branch: 
,08-26 15:42:57.449  1032  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 15:42:57.449  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-26 15:42:57.449  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 15:42:57.449  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.449  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.450  1032  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 15:42:57.450  1032  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 15:42:57.450  1032  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 15:42:57.450  1032  7254 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.450   313   907 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:42:57.465  7397  7397 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 15:42:57.481  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 15:42:57.481  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-26 15:42:57.483  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:57.483  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:57.484  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:57.484  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 15:42:57.484  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-26 15:42:57.485  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:57.485  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:57.485  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 15:42:57.485  1032  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 15:42:57.485  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.485  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.485  1032  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2249dbb5
,08-26 15:42:57.486  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-26 15:42:57.494  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:57.494  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:57.494  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 15:42:57.494  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 15:42:57.494  1032  1032 D RttService: SCAN_AVAILABLE : 1
08-26 15:42:57.494  1032  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.494  1032  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.495  1032  1537 D LGWifiP2pService: P2pDisablingState
08-26 15:42:57.495  1032  1537 D LGWifiP2pService: P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.495  1032  1537 D LGWifiP2pService: p2p socket connection lost
08-26 15:42:57.495  1032  1537 D LGWifiP2pService: P2pDisabledState
08-26 15:42:57.495  1032  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 15:42:57.496  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 15:42:57.496  7191  7191 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 15:42:57.496  1032  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 15:42:57.496  1032  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 15:42:57.496  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.496  1032  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.498  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 15:42:57.498  1943  1943 D WfdsService: WifiP2pState is changed : false
08-26 15:42:57.498  1943  2357 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 15:42:57.498  1943  2357 D WfdsService: Set the WFDS Monitor: false
,08-26 15:42:57.499  1943  2357 D WfdsMonitor: WFDS Monitor is stopped
08-26 15:42:57.499  1943  2357 D WfdsService: STATE : WfdsDisabledState - enter
08-26 15:42:57.499  1943  7200 D CtrlSupplicant: Received on exit socket, terminate
08-26 15:42:57.499  1943  7200 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 15:42:57.499  1943  7200 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 15:42:57.499  1943  7200 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 15:42:57.499  1943  2358 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 15:42:57.499  1943  2357 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 15:42:57.500  1032  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 15:42:57.510  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 15:42:57.510  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:57.510  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:57.521   313   907 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:42:57.521  1032  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 15:42:57.521  1032  1545 D DSQN    : disableDataServiceNotify
08-26 15:42:57.521  1032  1545 D DSQN    : stop dsqn bin
08-26 15:42:57.522  1032  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 15:42:57.524  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-26 15:42:57.524  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:57.524  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:57.524  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 15:42:57.525  1032  1539 D WifiNative-p2p0: TERMINATE: returned true
08-26 15:42:57.525  1032  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 15:42:57.525  1032  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 15:42:57.525  1032  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 15:42:57.527  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 15:42:57.527  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:42:57.527  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 15:42:57.527  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 15:42:57.528  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:57.528  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:57.528  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:57.528  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:57.528  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:57.528  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:57.528  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:57.528  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:57.528  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:57.528  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:57.528  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:57.529  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 15:42:57.529  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:42:57.530  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:57.530  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:57.530  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:57.530  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:57.530  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:57.530  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:57.530  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:57.530  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:57.530  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:57.530  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:57.530  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:57.530  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:57.531  1032  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 15:42:57.531  1032  1545 D ConnectivityService:  sending notification for NetworkRe,quest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:57.531  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:42:57.531  1032  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:42:57.531  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:57.531  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 15:42:57.531  1032  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.531  1032  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.531  1032  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 15:42:57.531  1032  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 15:42:57.532  1032  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 15:42:57.532  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 15:42:57.532  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:57.532  1603  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 15:42:57.532  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 15:42:57.533  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 15:42:57.533  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:57.533  1032  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:57.533  1032  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:57.533  1032  1545 D NetworkManagementService: Removing idletimer
08-26 15:42:57.533  1032  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:57.533  1032  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 15:42:57.533  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 15:42:57.533  1032  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:57.533  1032  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:57.534  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 15:,42:57.534  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 15:42:57.534  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 15:42:57.534  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 15:42:57.534  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 15:42:57.534  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 15:42:57.534  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 15:42:57.534  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 15:42:57.534  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:57.535  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 15:42:57.537  7397  7397 I dex2oat : dex2oat took 71.548ms (threads: 4)
,08-26 15:42:57.547  1032  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-26 15:42:57.547  7348  7363 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 15:42:57.547  7348  7363 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 15:42:57.547  7348  7363 I Adreno-EGL: Build Date: 12/12/14 금
08-26 15:42:57.547  7348  7363 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 15:42:57.547  7348  7363 I Adreno-EGL: Remote Branch: 
08-26 15:42:57.547  7348  7363 I Adreno-EGL: Local Patches: 
08-26 15:42:57.547  7348  7363 I Adreno-EGL: Reconstruct Branch: 
08-26 15:42:57.554  7323  7323 I NSApplication: Starting up...
,08-26 15:42:57.567  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 15:42:57.567  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:57.568  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:57.602  1032  2052 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7427 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-26 15:42:57.603  1032  2052 I ActivityManager: Killing 6122:com.android.vending/u0a44 (adj 15): empty #17
,08-26 15:42:57.620  7348  7363 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 15:42:57.620  7348  7363 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 15:42:57.620  7348  7363 I Adreno-EGL: Build Date: 12/12/14 금
08-26 15:42:57.620  7348  7363 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 15:42:57.620  7348  7363 I Adreno-EGL: Remote Branch: 
08-26 15:42:57.620  7348  7363 I Adreno-EGL: Local Patches: 
08-26 15:42:57.620  7348  7363 I Adreno-EGL: Reconstruct Branch: 
,08-26 15:42:57.629  7191  7191 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 15:42:57.629  7191  7191 I wpa_supplicant: monitor socket send errors count : 1
08-26 15:42:57.629  7191  7191 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-4\x00 that cannot receive messages
08-26 15:42:57.630  1032  7198 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 15:42:57.630  1032  7198 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 15:42:57.660  1032  7254 D DhcpStateMachine: StoppedState
08-26 15:42:57.660  1032  7254 D DhcpStateMachine: StoppedState{ when=-160ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:57.677  7191  7191 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 15:42:57.677  7191  7191 W wpa_supplicant: USIM:  scard_deinit function
08-26 15:42:57.680  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 15:42:57.680  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 15:42:57.680  1032  1095 D Tethering: InitialState.processMessage what=4
08-26 15:42:57.680  1032  7198 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 15:42:57.680  1032  7198 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 15:42:57.681  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 15:42:57.681  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 15:42:57.681  1032  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=127020
08-26 15:42:57.681  1032  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=127020
08-26 15:42:57.682  1032  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=127020  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 15:42:57.682  1032  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=127021  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 15:42:57.693  1032  1890 W libprocessgroup: failed to open /acct/uid_10044/pid_6122/cgroup.procs: No such file or directory
,08-26 15:42:57.705  1032  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 15:42:57.706  1032  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-26 15:42:57.708  1032  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:57.708  1032  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:42:57.711  1032  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:42:57.724  7427  7427 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:42:57.737  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 15:42:57.739  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:57.740  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:57.749  7348  7363 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 15:42:57.749  7348  7363 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 15:42:57.749  7348  7363 I Adreno-EGL: Build Date: 12/12/14 금
08-26 15:42:57.749  7348  7363 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 15:42:57.749  7348  7363 I Adreno-EGL: Remote Branch: 
08-26 15:42:57.749  7348  7363 I Adreno-EGL: Local Patches: 
08-26 15:42:57.749  7348  7363 I Adreno-EGL: Reconstruct Branch: 
,08-26 15:42:57.830  7191  7191 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 15:42:57.830  1032  7198 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 15:42:57.830  1032  7198 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 15:42:57.830  1032  7198 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 15:42:57.830  1032  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,08-26 15:42:57.900  1032  1937 I art     : Explicit concurrent mark sweep GC freed 118267(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 5.106ms total 122.494ms
,08-26 15:42:57.931  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-26 15:42:57.932  1032  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 15:42:57.932  1032  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 15:42:57.932  1032  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 15:42:57.932  1032  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 15:42:57.932  1943  2357 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 15:42:57.932  1943  2357 D WfdsService: Set the WFDS Monitor: false
08-26 15:42:57.932  1943  2357 D WfdsMonitor: WFDS Monitor is stopped
,08-26 15:42:57.934  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:42:57.934  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 15:42:57.934  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 15:42:57.934  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 15:42:57.934  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 15:42:57.937  2501  2501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:57.937  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:57.937  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:57.937  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:57.937  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:57.937  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:57.937  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:57.937  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:57.937  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:57.937  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:57.938  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 15:42:57.938  6510  6544 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 15:42:57.942  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:57.942  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:57.942  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:57.942  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:42:57.942  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:57.942  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:57.942  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:57.942  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:57.942  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:57.953  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:57.960  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 15:42:57.960  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:57.960  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 15:42:57.960  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 15:42:57.962  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
08-26 15:42:57.964  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4639aff
,08-26 15:42:57.964  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 15:42:57.964  7137  7137 D AppUp4:CustFacade: isPhone : true
08-26 15:42:57.964  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-26 15:42:57.964  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 15:42:57.967  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:57.967  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 15:42:57.968  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 15:42:57.970  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 15:42:57.975  7173  7173 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 15:42:57.976  4356  7455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:57.976  4356  7455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 15:42:57.977  4356  7454 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 15:42:57.991  7173  7456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:57.999  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 15:42:57.999  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:57.999  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 15:42:58.002  7046  7459 W FormManager: Network not available. Please check & try again.
,08-26 15:42:58.004  7209  7209 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 15:42:58.004  7209  7209 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 15:42:58.007  7046  7462 V FormManager: Network unavailable.
08-26 15:42:58.013  7276  7276 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:42:58
,08-26 15:42:58.015  7046  7462 V FormManager: Network unavailable.
08-26 15:42:58.016  7276  7276 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 15:42:58.016  7276  7276 D Weather.Utils: 2 : All the weather widget is gone.
08-26 15:42:58.018  7276  7276 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 15:42:58.018  7276  7276 D WeatherAncestor: connectivity changed - connection : true
08-26 15:42:58.018  7276  7276 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1f520f15
08-26 15:42:58.020  7276  7276 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 15:42:58.020  7276  7276 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 15:42:58.020  7276  7276 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 15:42:58.020  7276  7276 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 15:42:58.020  7276  7276 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:42:58
08-26 15:42:58.034  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:58.034  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 15:42:58.034  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-26 15:42:58.034  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 15:42:58.034  7348  7363 D LgDataFeature: LgDataFeature() Constructor: none
08-26 15:42:58.035  7348  7363 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 15:42:58.035  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-26 15:42:58.037  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 15:42:58.037  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 15:42:58.037  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 15:42:58.037  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 15:42:58.037  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 15:42:58.038  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 15:42:58.042  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:42:58.044  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:58.049  7046  7465 W FormManager: Network not available. Please check & try again.
,08-26 15:42:58.053  7046  7466 V FormManager: Network unavailable.
08-26 15:42:58.054  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.056  7046  7466 V FormManager: Network unavailable.
08-26 15:42:58.065  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 15:42:58.066  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:58.070  7046  7468 W FormManager: Network not available. Please check & try again.
08-26 15:42:58.077  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 15:42:58.081  7046  7469 V FormManager: Network unavailable.
08-26 15:42:58.083  7046  7469 V FormManager: Network unavailable.
08-26 15:42:58.087  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 15:42:58.087  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 15:42:58.090  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 15:42:58.091  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 15:42:58.092   313  7471 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 15:42:58.093  1032  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 15:42:58.093  1816  7305 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-26 15:42:58.094  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:58.097  4356  7472 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 15:42:58.098  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 15:42:58.098  4356  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 15:42:58.098  4356  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 15:42:58.099  1816  7305 I CheckinService: active receiver: disabled
,08-26 15:42:58.103  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 15:42:58.127  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:58.127  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:42:58.128  7005  7005 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 15:42:58.159  1032  2052 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7474 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 15:42:58.311  7474  7474 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 15:42:58.311  7474  7474 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 15:42:58.323  7474  7474 V [BNRBootReceiver]: Boot Receiver Return
08-26 15:42:58.324  7474  7474 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 15:42:58.331  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 15:42:58.351  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.366  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.379  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 15:42:58.379  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:42:58.383  7005  7005 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 15:42:58.389  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-26 15:42:58.396  6956  6956 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 15:42:58.414  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:58.416  6832  7119 D UEI.SmartControl: Internal timer expired: 2
08-26 15:42:58.416  6832  7119 D UEI.SmartControl: unbind internal service
,08-26 15:42:58.430  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.443  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.453  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:58.454  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 15:42:58.455  7005  7005 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 15:42:58.461  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:58.470  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.483  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 15:42:58.495  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 15:42:58.496  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:42:58.497  7005  7005 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 15:42:58.504  6832  7113 D serial_port: close(fd = 24)
08-26 15:42:58.506  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:58.511  6832  7113 I UEI.SmartControl: Serial port is closed.
,08-26 15:42:58.519  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.525  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.533  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:58.533  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:42:58.533  7005  7005 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 15:42:58.537  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:58.547  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.554  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.562  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:58.562  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:42:58.563  7005  7005 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 15:42:58.566  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:58.572  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.579  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.586  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:58.587  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:42:58.587  7005  7005 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 15:42:58.594  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 15:42:58.607  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.616  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 15:42:58.626  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:58.626  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 15:42:58.631  7005  7005 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 15:42:58.636  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:58.645  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.652  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.660  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:58.661  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 15:42:58.662  7005  7005 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 15:42:58.667  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:58.671  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 15:42:58.680  1032  1544 D WifiService: New client listening to asynchronous messages
,08-26 15:42:58.681  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 15:42:58.686  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 15:42:58.692  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.701  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:58.701  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:42:58.704  7005  7005 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 15:42:58.706  7005  7005 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 15:42:58.707  7005  7005 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-26 15:42:58.716  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 15:42:58.722  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 15:42:58.724  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 15:42:58.730  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.741  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.751  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:58.751  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:42:58.752  7005  7005 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-26 15:42:58.753  7005  7005 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-26 15:42:58.754  7005  7005 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 15:42:58.759  1032  1961 I ActivityManager: Killing 6929:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-26 15:42:58.791  1032  1960 W libprocessgroup: failed to open /acct/uid_10037/pid_6929/cgroup.procs: No such file or directory
,08-26 15:42:58.796  2229  2229 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 15:42:58.810  2229  2229 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 15:42:58.811  2229  2229 D c       : Getting all permits...
08-26 15:42:58.811  2229  2229 D a       : Opening database...
08-26 15:42:58.817  2229  2229 D a       : Opening database auth.proximity.permit_store...
08-26 15:42:58.819  2229  2229 D a       : Closing database...
08-26 15:42:58.833  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 15:42:58.840  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 15:42:58.840  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 15:42:58.840  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:42:58.844  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.851  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.860  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:58.861  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 15:42:58.864  7005  7005 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 15:42:58.869  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:58.873  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 15:42:58.873  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 15:42:58.873  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:42:58.876  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.883  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.890  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:42:58.891  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 15:42:58.893  7005  7005 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 15:42:58.897  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:42:58.901  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 15:42:58.901  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 15:42:58.901  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:42:58.906  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.912  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.921  7005  7005 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 15:42:58.921  7005  7005 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 15:42:58.923  7005  7005 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 15:42:58.933  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:42:58.938  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:58.945  7046  7508 W FormManager: Network not available. Please check & try again.
08-26 15:42:58.951  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:58.961  7046  7509 V FormManager: Network unavailable.
,08-26 15:42:58.967  7046  7509 V FormManager: Network unavailable.
,08-26 15:42:58.979  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 15:42:58.980  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 15:42:58.982  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 15:42:58.988  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 15:42:59.001  6976  6976 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 15:42:59.001  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 15:42:59.001  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:42:59.002  4356  7510 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 15:42:59.009  4356  7514 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 15:42:59.010  4356  7514 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 15:42:59.011  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:59.015  7046  7512 W FormManager: Network not available. Please check & try again.
,08-26 15:42:59.021  7046  7513 V FormManager: Network unavailable.
08-26 15:42:59.023  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:42:59.024  7046  7513 V FormManager: Network unavailable.
08-26 15:42:59.042  2229  2229 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-26 15:42:59.140  1032  1423 V AlarmManager: ELAPSED_WAKEUP set : Alarm{31db356d type 2 when 128477 com.google.android.gms} when 128477
,08-26 15:42:59.153  7005  7005 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-26 15:42:59.153  7005  7005 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7823
,08-26 15:42:59.154   313  7516 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 15:42:59.159  1032  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-26 15:42:59.162  1032  1539 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-954803367] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 15:42:59.162  1032  1539 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-954803366] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 15:42:59.343  1032  1423 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3eb25a2 type 2 when 128679 com.google.android.gms} when 128679
,08-26 15:42:59.536  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:59.551  1032  1095 D Tethering: MasterInitialState.processMessage what=3
08-26 15:42:59.560  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:59.564  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:59.566  1032  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:59.570  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 15:42:59.572  6510  6544 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 15:42:59.582  5800  5800 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 15:42:59.607  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:59.635  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 15:42:59.635  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:59.635  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 15:42:59.635  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 15:42:59.641  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
08-26 15:42:59.645  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4639aff
08-26 15:42:59.645  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 15:42:59.645  7137  7137 D AppUp4:CustFacade: isPhone : true
08-26 15:42:59.645  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-26 15:42:59.646  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 15:42:59.651  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:59.651  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 15:42:59.653  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 15:42:59.661  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 15:42:59.671  7173  7173 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 15:42:59.705  1032  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 15:42:59.709  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 15:42:59.709  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:59.710  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = true
08-26 15:42:59.710  3453  3453 D PhoneState: setPdpRejectCasuse : false
,08-26 15:42:59.714  7209  7209 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 15:42:59.715  7209  7209 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 15:42:59.717  4356  7540 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 15:42:59.721  7173  7525 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:59.728  4356  7543 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:59.728  4356  7543 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 15:42:59.738  7046  7541 W FormManager: Network not available. Please check & try again.
,08-26 15:42:59.749  7276  7276 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:42:59
08-26 15:42:59.751  7046  7542 V FormManager: Network unavailable.
08-26 15:42:59.752  7276  7276 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 15:42:59.752  7276  7276 D Weather.Utils: 2 : All the weather widget is gone.
,08-26 15:42:59.752  7276  7276 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 15:42:59.752  7276  7276 D WeatherAncestor: connectivity changed - connection : true
08-26 15:42:59.752  7276  7276 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1f520f15
08-26 15:42:59.753  7276  7276 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 15:42:59.753  7276  7276 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 15:42:59.753  7276  7276 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 15:42:59.753  7276  7276 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 15:42:59.754  7276  7276 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:42:59
08-26 15:42:59.766  7046  7542 V FormManager: Network unavailable.
,08-26 15:43:00.038  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:43:00.038  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-26 15:43:00.038  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-26 15:43:00.039  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:43:00.044  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-26 15:43:00.044  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-26 15:43:00.046  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:43:00.048  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:43:00.340  1032  1423 D PowerManagerServiceEx: acquireWakeLockInternal: lock=79701382, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,08-26 15:43:00.356  1032  1423 V AlarmManager: ELAPSED_WAKEUP set : Alarm{27b414ab type 2 when 129675 com.google.android.gms} when 129675
,08-26 15:43:00.391  2594  2594 D [Concierge]Service: onStartCommand(). Type : 9
,08-26 15:43:00.420  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=79701382 [*alarm*], flags=0x0
,08-26 15:43:00.442  1032  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:00.442  1032  2015 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 15:43:00.456  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 15:43:00.456  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 15:43:00.456  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,08-26 15:43:00.458  1032  1095 D BluetoothManagerService: Message: 1
08-26 15:43:00.458  1032  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 15:43:00.483  1032  1095 D BluetoothManagerService: Message: 20
08-26 15:43:00.483  1032  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21ee9bb4:true
,08-26 15:43:00.487  7075  7075 D BluetoothAdapterState: make
08-26 15:43:00.498  7075  7075 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 15:43:00.498  7075  7075 I bluedroid-qcom: init
,08-26 15:43:00.503  7075  7558 I BluetoothAdapterState: Entering OffState
08-26 15:43:00.503  7075  7075 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 15:43:00.504  7075  7075 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 15:43:00.504  7075  7075 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 15:43:00.504  7075  7075 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 15:43:00.504  7075  7075 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 15:43:00.505  7075  7075 I bluedroid-qcom: get_profile_interface socket
08-26 15:43:00.505  7075  7075 I bluedroid-qcom: get_profile_interface map_client
08-26 15:43:00.489  7569  7569 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:00.499  7569  7569 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:00.508  7075  7570 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 15:43:00.512  7075  7570 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 15:43:00.515  7075  7570 D BluetoothAdapterProperties: Name is: G3
08-26 15:43:00.515  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 15:43:00.515  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 15:43:00.515  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 15:43:00.515  1032  1095 D BluetoothManagerService: Message: 40
08-26 15:43:00.515  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 15:43:00.516  7075  7092 I bluedroid-qcom: config_hci_snoop_log
08-26 15:43:00.517  7569  7569 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 15:43:00.517  7569  7569 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 15:43:00.517  7569  7569 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-26 15:43:00.518  1032  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 15:43:00.518  1032  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-26 15:43:00.521  7569  7569 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 15:43:00.529  7075  7558 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 15:43:00.529  7075  7558 D BluetoothAdapterProperties: Setting state to 11
08-26 15:43:00.529  7075  7558 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 15:43:00.530  7075  7558 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 15:43:00.531  1032  1095 D BluetoothManagerService: Message: 60
08-26 15:43:00.531  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 15:43:00.531  1032  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 15:43:00.532  7569  7569 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 15:43:00.532  7569  7569 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-26 15:43:00.533  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:00.534  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:00.536  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 15:43:00.538  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 15:43:00.539  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:00.540  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:00.542  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:00.544  7075  7558 D BluetoothBondStateMachine: make
08-26 15:43:00.547  7075  7558 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:00.547  7075  7075 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-26 15:43:00.547  7075  7558 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 15:43:00.547  7075  7558 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:00.548  7075  7558 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 15:43:00.549  7075  7075 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:00.549  7075  7075 V BluetoothPbapReceiver: ***********state = 11
08-26 15:43:00.551  7075  7558 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 15:43:00.552  1032  1095 D Tethering: MasterInitialState.processMessage what=3
08-26 15:43:00.553  1032  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:00.554  7075  7574 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 15:43:00.560  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:00.562  1032  1095 D Tethering: MasterInitialState.processMessage what=3
,08-26 15:43:00.564  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:00.571  7075  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-26 15:43:00.571  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:00.572  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 15:43:00.573  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:00.573  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 15:43:00.574  1032  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:00.576  5800  5800 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 15:43:00.579  6510  6544 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 15:43:00.616  1032  1882 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7579 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 15:43:00.628  7075  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-26 15:43:00.628  7075  7075 D HeadsetService: Received start request. Starting profile...
08-26 15:43:00.628  7075  7075 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 15:43:00.629  7075  7075 D LGBluetoothHfpAdapter: Version 1.6
08-26 15:43:00.632  7075  7075 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 15:43:00.633  1032  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:00.633  1032  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:00.633  7075  7075 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 15:43:00.634  7075  7075 D HeadsetStateMachine: make
,08-26 15:43:00.636  5800  5800 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 15:43:00.642  7075  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-26 15:43:00.647  7075  7558 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 15:43:00.654  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:00.657  7075  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-26 15:43:00.663  7075  7558 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 15:43:00.667  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 15:43:00.667  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:00.667  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 15:43:00.667  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 15:43:00.671  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
08-26 15:43:00.674  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4639aff
08-26 15:43:00.674  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 15:43:00.674  7137  7137 D AppUp4:CustFacade: isPhone : true
08-26 15:43:00.675  7075  7558 E BluetoothAdapterService: File transfer profiles supported!!
08-26 15:43:00.675  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-26 15:43:00.675  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-26 15:43:00.679  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:00.679  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 15:43:00.680  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 15:43:00.681  7075  7075 D LgDataFeature: LgDataFeature() Constructor: none
08-26 15:43:00.682  7075  7075 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 15:43:00.691  7075  7075 D HeadsetStateMachine: max_hf_connections = 1
08-26 15:43:00.691  7075  7075 I bluedroid-qcom: get_profile_interface handsfree
08-26 15:43:00.691  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 15:43:00.693  7075  7075 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 15:43:00.695   317  1737 V AudioPolicyService: registerClient() client 0xb0410a60, uid 1002
08-26 15:43:00.696   317  1381 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 15:43:00.696   317  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 15:43:00.696   317  1381 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 15:43:00.696  7075  7075 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 15:43:00.696   317   317 V AudioFlinger: registerClient() client 0xb1433148, pid 7075
08-26 15:43:00.697   317  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:00.697   317  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 15:43:00.697  1603  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:00.697  1603  1620 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-26 15:43:00.697  7075  7092 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:00.697  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:00.697  7075  7092 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 15:43:00.697  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 15:43:00.698  3453  3469 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:00.698  3453  3469 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 15:43:00.698   317  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:00.698   317  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 15:43:00.699  7075  7091 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:00.699  7075  7091 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 15:43:00.699  3453  3468 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:00.699  3453  3468 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 15:43:00.699  7075  7075 V ToneGenerator: Create Track: 0xb4928a80
08-26 15:43:00.699  7075  7075 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 15:43:00.699  1853  2476 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:00.699  7075  7075 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 15:43:00.699  1853  2476 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 15:43:00.699   317  1737 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 15:43:00.699   317  1737 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 15:43:00.699   317  1737 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 15:43:00.699   317  1737 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 15:43:00.699  1603  3237 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:00.699  4356  7599 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 15:43:00.699  1603  3237 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 15:43:00.700   317  1381 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 15:43:00.700   317   317 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 15:43:00.700   317   317 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 15:43:00.700   317   317 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 15:43:00.700   317   317 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 15:43:00.700  1032  1891 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:00.700  1032  1891 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 15:43:00.700  7075  7075 V AudioSystem: getLatency() output 2, latency 50
08-26 15:43:00.700  7075  7075 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 15:43:00.700  7075  7075 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 15:43:00.701   317  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 15:43:00.701   317  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 15:43:00.701   317  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 15:43:00.701   317  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 15:43:00.701   317  1382 V AudioFlinger: createTrack() lSessionId: 22
08-26 15:43:00.702  1032  1891 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:00.70,2  7075  7075 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 15:43:00.702  1032  1891 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 15:43:00.703   317  1381 V AudioFlinger: acquiring 22 from 7075, for 7075
08-26 15:43:00.703   317  1381 V AudioFlinger:  added new entry for 22
08-26 15:43:00.703  7075  7075 V ToneGenerator: ToneGenerator INIT OK, time: 130055
08-26 15:43:00.703  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:00.704  7075  7595 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 15:43:00.704  7075  7595 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 15:43:00.704  7075  7595 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 15:43:00.704  7075  7595 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 15:43:00.705   317   317 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7075
08-26 15:43:00.705   317   317 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 15:43:00.705   317   317 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 15:43:00.705   317   317 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 15:43:00.705   317   317 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 15:43:00.705   317   317 V voice   : voice_set_parameters: exit with code(0)
08-26 15:43:00.705   317   317 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 15:43:00.705   317   317 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 15:43:00.705   317   317 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 15:43:00.705   317   317 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 15:43:00.706   317   317 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 15:43:00.706   317   317 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 15:43:00.706  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:00.706  7075  7595 V ToneGenerator: ToneGenerator destructor
08-26 15:43:00.706  7075  7595 V ToneGenerator: stopTone
08-26 15:43:00.706  7075  7595 V ToneGenerator: Delete Track: 0xb4928a80
08-26 15:43:00.707  7075  7595 V AudioTrack: ~AudioTrack, releasing session id from 7075 on behalf of 7075
08-26 15:43:00.707   317  1382 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 15:43:00.707   317  1382 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 15:43:00.707   317   317 V AudioFlinger: releasing 22 from 7075 for 7075
08-26 15:43:00.707   317   317 V AudioFlinger:  decremented refcount to 0
08-26 15:43:00.707   317   317 V AudioFlinger: purging stale effects
08-26 15:43:00.707   317  1226 V AudioPolicyService: AudioCommandThread() waking up
08-26 15:43:00.707   317  1226 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 15:43:00.707   317  1226 V AudioPolicyManager: releaseOutput() 2
08-26 15:43:00.707   317  1226 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 15:43:00.707   317  1382 V AudioFlinger: PlaybackThread::Track destructor
08-26 15:43:00.707   317  1382 V AudioFlinger: removeClient_l() pid 7075, calling pid 317
08-26 15:43:00.707  7075  7558 V LGMDMManager: Create singleton instance
08-26 15:43:00.712  4356  7600 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:00.712  4356  7600 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 15:43:00.713  1032  2034 W Process : Unable to open /proc/7601/status
08-26 15:43:00.713  7075  7075 D A2dpService: Received start request. Starting profile...
08-26 15:43:00.713  7173  7173 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 15:43:00.714  7075  7075 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 15:43:00.715  7075  7075 V Avrcp   : make
08-26 15:43:00.715  7075  7558 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 15:43:00.716  7075  7075 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 15:43:00.716  7075  7075 I bluedroid-qcom: get_profile_interface avrcp
08-26 15:43:00.725  7075  7075 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 15:43:00.727  7075  7075 E AudioManager: No RCC entry present to update
08-26 15:43:00.727  7075  7075 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 15:43:00.731  7075  7075 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 15:43:00.731  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 15:43:00.731  7075  7075 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 15:43:00.736  7173  7604 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:00.736  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 15:43:00.737  7046  7605 W FormManager: Network not available. Please check & try again.
,08-26 15:43:00.797  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 15:43:00.797  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:00.798  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 15:43:00.802  7046  7606 V FormManager: Network unavailable.
08-26 15:43:00.803  7209  7209 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 15:43:00.804  7209  7209 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 15:43:00.813  7046  7606 V FormManager: Network unavailable.
08-26 15:43:00.816  7276  7276 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:43:0
,08-26 15:43:00.821  7276  7276 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 15:43:00.821  7276  7276 D Weather.Utils: 2 : All the weather widget is gone.
08-26 15:43:00.821  7276  7276 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 15:43:00.821  7276  7276 D WeatherAncestor: connectivity changed - connection : true
08-26 15:43:00.821  7276  7276 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1f520f15
08-26 15:43:00.822  7276  7276 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 15:43:00.822  7276  7276 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 15:43:00.822  7276  7276 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 15:43:00.822  7276  7276 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 15:43:00.822  7276  7276 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:43:0
08-26 15:43:00.841  7579  7579 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 15:43:00.841  7579  7579 W LG Account v2.2: No ProfileInfo entries
08-26 15:43:00.841  7579  7579 I LG Account v2.2: isEnabled: false
08-26 15:43:00.841  6510  6510 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 15:43:00.841  7579  7579 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 15:43:00.841  7579  7579 I Feature : [Lifetracker]Country: EU
08-26 15:43:00.841  7579  7579 I Feature : [Lifetracker]Operator: OPEN
08-26 15:43:00.842  7579  7579 I Feature : [Lifetracker]Ranking support: false
08-26 15:43:00.842  7579  7579 I Feature : [Lifetracker]Comfort support: false
08-26 15:43:00.842  7579  7579 I Feature : [Lifetracker]Accessory: true
08-26 15:43:00.842  7579  7579 I Feature : [Lifetracker]Health device: true
08-26 15:43:00.842  7579  7579 I Feature : [Lifetracker]Extra Pedometer: false
08-26 15:43:00.842  7579  7579 I Feature : [Lifetracker]Blood glucose device: false
08-26 15:43:00.842  7579  7579 I Feature : [Lifetracker]Device Number: 3
,08-26 15:43:00.843  6510  6544 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 15:43:00.859  6956  6956 D BluetoothPermissionRequest: onReceive
,08-26 15:43:00.862  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:00.866  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 15:43:00.874  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 15:43:00.874  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:00.874  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 15:43:00.874  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 15:43:00.875  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 15:43:00.877  1032  1961 V SIM_STK : Menu title from STK is T-Mobile
08-26 15:43:00.877  1032  1961 V SIM_STK : Menu title from STK is T-Mobile
08-26 15:43:00.879  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4639aff
08-26 15:43:00.879  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 15:43:00.879  7137  7137 D AppUp4:CustFacade: isPhone : true
08-26 15:43:00.879  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-26 15:43:00.880  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 15:43:00.885  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:00.886  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 15:43:00.889  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 15:43:00.893  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 15:43:00.901  4356  7612 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 15:43:00.902  7173  7173 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 15:43:00.907  4356  7613 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:00.907  4356  7613 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 15:43:00.923  7173  7614 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:43:00.935  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 15:43:00.935  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:00.935  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 15:43:00.942  7209  7209 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 15:43:00.942  7209  7209 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 15:43:00.943  7046  7616 W FormManager: Network not available. Please check & try again.
08-26 15:43:00.949  7046  7617 V FormManager: Network unavailable.
,08-26 15:43:00.956  7276  7276 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:43:0
08-26 15:43:00.959  7276  7276 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 15:43:00.959  7276  7276 D Weather.Utils: 2 : All the weather widget is gone.
08-26 15:43:00.960  7276  7276 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 15:43:00.960  7276  7276 D WeatherAncestor: connectivity changed - connection : true
08-26 15:43:00.960  7276  7276 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1f520f15
08-26 15:43:00.960  7046  7617 V FormManager: Network unavailable.
08-26 15:43:00.961  7276  7276 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 15:43:00.961  7276  7276 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 15:43:00.961  7276  7276 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 15:43:00.961  7276  7276 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 15:43:00.961  7276  7276 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:43:0
08-26 15:43:00.991  1032  1961 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 15:43:01.000  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-26 15:43:01.005  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 15:43:01.006  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 15:43:01.006  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-26 15:43:01.006  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 15:43:01.006  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 15:43:01.007  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
,08-26 15:43:01.007  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 15:43:01.007  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 15:43:01.007  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 15:43:01.007  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 15:43:01.008  7075  7075 I BluetoothA2dpServiceJni: classInitNative
08-26 15:43:01.008  7075  7075 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 15:43:01.008  7075  7075 D A2dpStateMachine: make
08-26 15:43:01.009  7075  7075 I bluedroid-qcom: get_profile_interface a2dp
08-26 15:43:01.010  7075  7620 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 15:43:01.012  7075  7075 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 15:43:01.012  7075  7075 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-26 15:43:01.013  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:01.013  7075  7619 D A2dpStateMachine: Enter Disconnected: -2
08-26 15:43:01.015  7075  7075 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 15:43:01.017  7075  7075 D HidService: Received start request. Starting profile...
08-26 15:43:01.017  7075  7075 I bluedroid-qcom: get_profile_interface hidhost
08-26 15:43:01.017  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:01.018  7075  7075 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 15:43:01.020  7075  7075 D HealthService: Received start request. Starting profile...
08-26 15:43:01.023  7075  7075 I bluedroid-qcom: get_profile_interface health
08-26 15:43:01.023  7075  7075 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 15:43:01.024  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:01.024  7075  7075 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 15:43:01.026  7075  7075 D PanService: Received start request. Starting profile...
08-26 15:43:01.026  7075  7075 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 15:43:01.027  7075  7075 I bluedroid-qcom: get_profile_interface pan
08-26 15:43:01.036  7075  7075 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-26 15:43:01.037  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:01.040  7075  7075 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-26 15:43:01.054  7075  7075 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 15:43:01.055  7075  7075 D BtGatt.GattService: Received start request. Starting profile...
08-26 15:43:01.055  7075  7075 D BtGatt.GattService: start()
08-26 15:43:01.055  7075  7075 I bluedroid-qcom: get_profile_interface gatt
,08-26 15:43:01.056  7075  7075 D BtGatt.AdvertiseManager: advertise manager created
08-26 15:43:01.067  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:01.069  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:01.069  7075  7075 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-26 15:43:01.070  7075  7075 V BluetoothMapService: BluetoothMapBinder()
,08-26 15:43:01.071  7075  7075 D BluetoothMapService: Received start request. Starting profile...
08-26 15:43:01.071  7075  7075 D BluetoothMapService: start()
08-26 15:43:01.076  7075  7075 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 15:43:01.076  7075  7075 D BluetoothMapEmailAppObserver: createReceiver()
08-26 15:43:01.077  7075  7075 D BluetoothMapEmailAppObserver: initObservers()
08-26 15:43:01.077  7075  7075 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 15:43:01.087  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:01.087  7075  7075 D HeadsetStateMachine: Proxy object connected
08-26 15:43:01.088  7075  7075 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 15:43:01.088  7075  7075 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-26 15:43:01.094  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 15:43:01.095  7075  7595 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:43:01.096  7075  7595 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 15:43:01.097  7075  7595 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 15:43:01.099  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 15:43:01.104  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 15:43:01.107  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 15:43:01.108  7075  7075 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 15:43:01.111  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 15:43:01.116  7075  7075 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 15:43:01.116  7075  7075 V BluetoothMapService: Handler(): got msg=1
08-26 15:43:01.117  7075  7558 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,08-26 15:43:01.117  7075  7558 I bluedroid-qcom: enable
08-26 15:43:01.119  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.119  7075  7627 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 15:43:01.119  7075  7558 I bt_hci_bdroid: init
08-26 15:43:01.121  7075  7075 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 15:43:01.121  7075  7075 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 15:43:01.121  7075  7075 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 15:43:01.121  7075  7075 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.121  7075  7075 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 15:43:01.123  7075  7627 I bt-btu  : btu_task pending for preload complete event
08-26 15:43:01.124  7075  7558 I bt_vendor: bt-vendor : init
08-26 15:43:01.124  7075  7558 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 15:43:01.125  7075  7558 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 15:43:01.125  7075  7558 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 15:43:01.125  7075  7558 D bt_userial_mct: userial_init
08-26 15:43:01.126  7075  7558 D bt_hci_bdroid: set_power 1
08-26 15:43:01.126  7075  7558 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 15:43:01.126  7075  7558 I bt_vendor: Starting hciattach daemon
08-26 15:43:01.126  7075  7558 I bt_vendor: try to set true
08-26 15:43:01.119  7630  7630 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:01.119  7630  7630 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 15:43:01.192  7631  7631 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 15:43:01.327  7640  7640 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 15:43:01.350  7641  7641 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 15:43:01.375  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 15:43:01.387  7644  7644 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 15:43:01.401  7645  7645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 15:43:01.425  7646  7646 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 15:43:01.450  7648  7648 I libmdmdetect: ESOC framework not supported
,08-26 15:43:01.451  7648  7648 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-26 15:43:01.460  7648  7648 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 15:43:01.460  7648  7648 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 15:43:01.460  7648  7648 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 15:43:01.460  7648  7648 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 15:43:01.460  7648  7648 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 15:43:01.460  7648  7648 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 15:43:01.460  7648  7648 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 15:43:01.503  7648  7649 E QC-QMI  : qmi_client [7648] 14: failed to locate client data
,08-26 15:43:01.504   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-26 15:43:01.504   468   468 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-26 15:43:01.552  7650  7650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 15:43:01.579  7651  7651 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 15:43:01.632  7075  7558 I bt_vendor: bluetooth satus is on
08-26 15:43:01.632  7075  7558 D bt_hci_bdroid: preload
,08-26 15:43:01.632  7075  7629 D bt_userial_mct: userial_open(port:0)
08-26 15:43:01.632  7075  7629 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 15:43:01.636  7075  7629 I bt_vendor: Done intiailizing UART
,08-26 15:43:01.640  7075  7629 I bt_vendor: Done intiailizing UART
,08-26 15:43:01.640  7075  7629 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-26 15:43:01.640  7075  7629 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-26 15:43:01.641  7075  7627 I bt-btu  : btu_task received preload complete event
,08-26 15:43:01.641  7075  7653 D bt_userial_mct: Entering userial_read_thread()
,08-26 15:43:01.642  7075  7627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 15:43:01.642  7075  7627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 15:43:01.649  7075  7627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-26 15:43:01.658  7075  7627 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 15:43:01.658  7075  7627 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 15:43:01.658  7075  7627 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 15:43:01.659  7075  7627 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 15:43:01.659  7075  7627 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 15:43:01.659  7075  7627 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 15:43:01.659  7075  7627 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 15:43:01.659  7075  7627 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 15:43:01.659  7075  7627 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-26 15:43:01.659  7075  7627 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 15:43:01.659  7075  7627 I         : BTE_InitTraceLevels -- TRC_PAN
,08-26 15:43:01.659  7075  7627 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 15:43:01.659  7075  7627 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 15:43:01.659  7075  7627 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 15:43:01.660  7075  7627 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 15:43:01.660  7075  7627 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 15:43:01.716  7075  7627 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-26 15:43:01.716  7075  7627 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c9061 
08-26 15:43:01.716  7075  7627 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c9061 
,08-26 15:43:01.750  7075  7570 E bt-btif : Calling BTA_HhEnable
08-26 15:43:01.750  7075  7627 W bt-l2cap: btif_storage_get_adapter_property service_mask
08-26 15:43:01.750  7075  7570 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 15:43:01.750  7075  7627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 15:43:01.750  7075  7627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 15:43:01.751  7075  7627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 15:43:01.751  7075  7627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 15:43:01.751  7075  7570 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 15:43:01.755  7075  7570 D BluetoothAdapterProperties: Name is: G3
08-26 15:43:01.756  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 15:43:01.756  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 15:43:01.758  7075  7570 D BluetoothAdapterProperties: Scan Mode:20
08-26 15:43:01.759  7075  7570 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 15:43:01.759  7075  7570 D bt_hci_bdroid: postload
08-26 15:43:01.759  7075  7629 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 15:43:01.761  7075  7627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 15:43:01.761  7075  7629 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 15:43:01.762  7075  7570 D bte_conf: Device ID record 1 : primary
08-26 15:43:01.762  7075  7629 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 15:43:01.762  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:01.762  7075  7629 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 15:43:01.763  7075  7570 D bte_conf:   vendorId            = 00c4
08-26 15:43:01.763  7075  7570 D bte_conf:   vendorIdSource      = 0001
08-26 15:43:01.763  7075  7570 D bte_conf:   product             = 13a1
08-26 15:43:01.763  7075  7570 D bte_conf:   version             = 1000
08-26 15:43:01.763  7075  7570 D bte_conf:   clientExecutableURL = 
08-26 15:43:01.763  7075  7570 D bte_conf:   serviceDescription  = 
08-26 15:43:01.763  7075  7570 D bte_conf:   documentationURL    = 
08-26 15:43:01.763  7075  7570 D bte_conf: bte_load_did_conf no section named DID2.
08-26 15:43:01.767  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.771  7075  7558 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 15:43:01.771  7075  7558 D BluetoothAdapterProperties: ScanMode =  20
08-26 15:43:01.771  7075  7558 D BluetoothAdapterProperties: State =  11
08-26 15:43:01.772  7075  7558 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 15:43:01.772  7075  7558 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 15:43:01.772  7075  7558 D BluetoothAdapterProperties: Setting state to 12
08-26 15:43:01.772  7075  7558 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 15:43:01.759  7658  7658 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:01.759  7658  7658 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:01.773  7075  7570 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 15:43:01.773  7075  7570 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 15:43:01.776  1032  1095 D BluetoothManagerService: Message: 60
08-26 15:43:01.776  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 15:43:01.776  1032  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-26 15:43:01.776  7075  7558 I BluetoothAdapterState: Entering On State
08-26 15:43:01.779  7075  7627 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 15:43:01.779  7075  7627 W bt-smp  : Plain text(LSB ~ MSB) = dd 0e 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 15:43:01.779  7075  7558 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 15:43:01.779  7075  7627 W bt-smp  : Encrypted text(LSB ~ MSB) = c7 d0 c9 3c 11 f3 6d 89 80 d9 9a 3f d7 99 49 69 
08-26 15:43:01.779  7075  7558 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 15:43:01.779  7075  7627 W bt-btm  : Stopping oneshot timer
08-26 15:43:01.779  7075  7558 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 15:43:01.780  7075  7629 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 15:43:01.780  6956  7449 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 15:43:01.782  7075  7558 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-26 15:43:01.783  7075  7653 E bt_mct  : hci lib postload completed
08-26 15:43:01.791  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:01.796  6956  6956 D BluetoothInputDevice: Proxy object connected
08-26 15:43:01.796  6956  6956 D HidProfile: Bluetooth service connected
,08-26 15:43:01.802  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 15:43:01.803  6956  6972 D BluetoothMap: onBluetoothStateChange: up=true
08-26 15:43:01.808  1853  2476 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 15:43:01.813  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 15:43:01.815  1032  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:01.818  1032  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:01.819  6956  6956 D BluetoothMap: Proxy object connected
08-26 15:43:01.820  7075  7627 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-26 15:43:01.821  7075  7627 W bt-smp  : Plain text(LSB ~ MSB) = 58 61 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 15:43:01.821  7075  7627 W bt-smp  : Encrypted text(LSB ~ MSB) = 31 c0 40 87 38 72 3f e5 1f 71 33 66 af 27 1f 91 
08-26 15:43:01.821  7075  7627 W bt-btm  : Stopping oneshot timer
08-26 15:43:01.822  1032  1032 D BluetoothA2dp: Proxy object connected
08-26 15:43:01.823  6956  6971 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 15:43:01.827  1032  1032 D BluetoothHeadset: Proxy object connected
08-26 15:43:01.830  7075  7558 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 15:43:01.819  6956  6956 D MapProfile: Bluetooth service connected
08-26 15:43:01.831  6956  6956 D BluetoothMap: getConnectedDevices()
08-26 15:43:01.832  6956  7449 D BluetoothPan: onBluetoothStateChange on: true
08-26 15:43:01.832  6956  7449 D BluetoothPan: onBluetoothStateChange call bindService
08-26 15:43:01.835  7075  7627 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 15:43:01.835  7075  7627 W bt-smp  : Plain text(LSB ~ MSB) = d1 9a 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 15:43:01.835  7075  7627 W bt-smp  : Encrypted text(LSB ~ MSB) = df 8c 11 5a 8e 9c df d9 df 80 b9 fd 5d 97 2c d8 
08-26 15:43:01.835  7075  7627 W bt-btm  : Stopping oneshot timer
08-26 15:43:01.837  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 15:43:01.841  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 15:43:01.846  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 15:43:01.846  1032  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 15:43:01.846  1032  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 15:43:01.848  1032  1095 D BluetoothManagerService: Message: 40
08-26 15:43:01.848  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 15:43:01.848  7075  7091 V BluetoothMapService: getConnectedDevices()
08-26 15:43:01.849  7075  7627 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 15:43:01.849  7075  7627 W bt-smp  : Plain text(LSB ~ MSB) = e0 6f 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 15:43:01.849  7075  7627 W bt-smp  : Encrypted text(LSB ~ MSB) = 73 a2 a3 4e 20 a9 33 59 af c0 4f c5 15 ba 7c 18 
08-26 15:43:01.850  7075  7627 W bt-btm  : Stopping oneshot timer
08-26 15:43:01.850  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.850  1943  2130 D LGBluetoothAPIService: Message: 1
08-26 15:43:01.850  1943  2130 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 15:43:01.851  7664  7664 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-26 15:43:01.858  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 15:43:01.861  6697  6697 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 15:43:01.867  7075  7627 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 15:43:01.867  7075  7627 W bt-smp  : Plain text(LSB ~ MSB) = 76 8b 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 15:43:01.867  7075  7627 W bt-smp  : Encrypted text(LSB ~ MSB) = c0 05 8c 51 88 62 04 ef 50 65 d1 08 4d f6 7d 9c 
08-26 15:43:01.867  7075  7627 W bt-btm  : Stopping oneshot timer
08-26 15:43:01.869  7075  7570 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 15:43:01.870  7075  7570 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-26 15:43:01.872  6956  6956 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 15:43:01.872  6956  6956 D PanProfile: Bluetooth service connected
08-26 15:43:01.874  7075  7075 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.874  7075  7075 D BluetoothMapService: STATE_ON
08-26 15:43:01.880  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:01.880  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:01.880  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:01.880  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:01.880  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:01.880  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:01.880  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:01.880  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:43:01.881  1943  2130 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-26 15:43:01.884  6956  6956 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 15:43:01.887  1032  1095 D BluetoothManagerService: Message: 30
08-26 15:43:01.887  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:01.892  6956  6956 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 15:43:01.894  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:01.894  7075  7075 V BluetoothPbapService: Pbap Service onCreate
08-26 15:43:01.894  7075  7075 V BluetoothPbapService: Starting PBAP service
,08-26 15:43:01.895  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:01.895  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:01.895  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:01.895  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:01.895  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:01.895  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:01.895  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:01.895  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:43:01.896  1032  1095 D BluetoothManagerService: Message: 30
08-26 15:43:01.898  7075  7075 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 15:43:01.899  7075  7075 V BluetoothPbapService: Pbap Service onBind
08-26 15:43:01.900  7075  7075 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.900  7075  7075 V BluetoothPbapService: state: 12
08-26 15:43:01.900  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:01.900  7075  7075 V BluetoothMapService: Handler(): got msg=1
08-26 15:43:01.901  7075  7075 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 15:43:01.903  7075  7677 D BluetoothMapMasInstance: MAS initSocket()
08-26 15:43:01.903  7075  7075 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 15:43:01.903  7075  7677 D BluetoothMapMasInstance:   masId = 00
08-26 15:43:01.903  7075  7677 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 15:43:01.903  7075  7677 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 15:43:01.903  7075  7677 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 15:43:01.903  7075  7075 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 15:43:01.903  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 15:43:01.905  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 15:43:01.905  1032  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:01.905  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 15:43:01.905  1943  2130 D LGBluetoothAPIService: Message: 100
08-26 15:43:01.905  1943  2130 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 15:43:01.905  7075  7075 V BluetoothPbapService: Handler(): got msg=1
08-26 15:43:01.906  7075  7075 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 15:43:01.907  6956  6956 D BluetoothA2dp: Proxy object connected
08-26 15:43:01.908  6956  6956 D A2dpProfile: Bluetooth service connected
,08-26 15:43:01.910  7075  7677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:01.911  7075  7075 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 15:43:01.911  7075  7075 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.911  7075  7075 V BluetoothPbapReceiver: ***********state = 12
08-26 15:43:01.911  7075  7678 V BluetoothPbapService: Pbap Service initSocket
08-26 15:43:01.912  1032  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:01.913  7075  7677 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 15:43:01.913  7075  7677 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 15:43:01.914  7075  7677 D BluetoothMapMasInstance: Accepting socket connection...
08-26 15:43:01.917  7075  7570 D BluetoothAdapterProperties: Scan Mode:21
08-26 15:43:01.917  7075  7570 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 15:43:01.918  6956  6956 D BluetoothPbap: Proxy object connected
08-26 15:43:01.918  7075  7678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:01.919  6956  6956 D PbapServerProfile: Bluetooth service connected
08-26 15:43:01.919  6956  6956 D BluetoothHeadset: Proxy object connected
08-26 15:43:01.920  7075  7678 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 15:43:01.920  7075  7678 V BluetoothPbapService: Succeed to create listening socket 
08-26 15:43:01.920  7075  7678 V BluetoothPbapService: Accepting socket connection...
08-26 15:43:01.920  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:01.922  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 15:43:01.922  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:01.922  2229  2229 D c       : Getting all permits...
,08-26 15:43:01.922  2229  2229 D a       : Opening database...
08-26 15:43:01.923  6956  6956 D HeadsetProfile: Bluetooth service connected
,08-26 15:43:01.928  2229  2229 D a       : Opening database auth.proximity.permit_store...
08-26 15:43:01.929  6956  6956 D DockEventReceiver: finishStartingService: stopping service
08-26 15:43:01.929  2229  2229 D a       : Closing database...
08-26 15:43:01.943  6956  6956 D BluetoothPermissionRequest: onReceive
,08-26 15:43:01.945  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 15:43:01.947  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 15:43:01.950  7075  7075 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 15:43:01.951  7075  7075 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 15:43:01.957  7075  7075 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 15:43:01.976  7075  7075 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 15:43:01.977  7075  7075 V BtOppService: onCreate
,08-26 15:43:01.981  7075  7075 V BluetoothOppNotification: send message
08-26 15:43:01.985  7075  7075 V BtOppService: Starting RfcommListener
08-26 15:43:01.992  7075  7075 D BluetoothOppPreference: Dumping Names:  
08-26 15:43:01.992  7075  7075 D BluetoothOppPreference: {}
08-26 15:43:01.992  7075  7075 D BluetoothOppPreference: Dumping Channels:  
08-26 15:43:01.992  7075  7075 D BluetoothOppPreference: {}
08-26 15:43:01.993  7075  7075 V BtOppService: onStartCommand
,08-26 15:43:01.997  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.998  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 15:43:01.999  7075  7686 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 15:43:02.000  7075  7075 V BluetoothOppNotification: new notify threadi!
08-26 15:43:02.001  7075  7075 V BluetoothOppNotification: send delay message
08-26 15:43:02.002  7075  7075 V BtOppService: start RfcommListener
08-26 15:43:02.007  7075  7686 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 15:43:02.009  7075  7075 V BtOppService: RfcommListener started
,08-26 15:43:02.011  7075  7683 V BtOppService: Deleted complete outbound shares, number =  0
08-26 15:43:02.015  7075  7683 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 15:43:02.016  7075  7683 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 15:43:02.016  7075  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 15:43:02.017  7075  7686 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a7a7306 on behalf of 
08-26 15:43:02.019  7075  7683 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31d2fdc7 on behalf of 
08-26 15:43:02.019  7075  7688 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 15:43:02.020  1032  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:02.023  7075  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f12dff4 on behalf of 
08-26 15:43:02.024  7075  7687 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-26 15:43:02.024  7075  7688 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:02.026  7075  7688 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=75
08-26 15:43:02.026  7075  7688 V BtOppRfcommListener: Started RFCOMM listener....
08-26 15:43:02.026  7075  7688 I BtOppRfcommListener: Accept thread started.
08-26 15:43:02.026  7075  7688 V BtOppRfcommListener: Accepting connection...
08-26 15:43:02.028  7075  7686 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 15:43:02.029  7075  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 15:43:02.032  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:02.032  7075  7075 V BluetoothFtpService: Ftp Service onCreate
08-26 15:43:02.032  7075  7075 I BluetoothFtpService: Ftp Service onCreate
08-26 15:43:02.033  7075  7075 V BluetoothFtpService: Ftp Service onStartCommand
08-26 15:43:02.033  7075  7075 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:02.033  7075  7075 V BluetoothFtpService: Starting Listening on sockets
08-26 15:43:02.033  7075  7075 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 15:43:02.033  7075  7075 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 15:43:02.033  7075  7075 V BluetoothSapReceiver: SapReceiver onReceive 
,08-26 15:43:02.033  7075  7075 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:02.033  7075  7075 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 15:43:02.034  7075  7075 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 15:43:02.038  7075  7075 V BtOppService: ContentObserver received notification
08-26 15:43:02.038  7075  7075 V BtOppService: ContentObserver received notification
08-26 15:43:02.038  7075  7075 V BluetoothFtpService: Handler(): got msg=1
08-26 15:43:02.039  7075  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3dbab992 on behalf of 
08-26 15:43:02.039  7075  7075 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 15:43:02.039  7075  7075 V BluetoothFtpService: Ftp Service initSocket
08-26 15:43:02.042  7075  7687 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 15:43:02.043  7075  7689 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 15:43:02.044  7075  7689 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 15:43:02.045  7075  7687 V BluetoothOppNotification: outbound notification was removed.
08-26 15:43:02.045  7075  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 15:43:02.045  1032  1625 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:02.046  7075  7689 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5f7af63 on behalf of 
08-26 15:43:02.047  7075  7075 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:02.047  7075  7689 V BluetoothOppNotification: update too frequent, put in queue
08-26 15:43:02.048  7075  7075 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 15:43:02.048  7075  7689 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-26 15:43:02.054  7075  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b780760 on behalf of 
08-26 15:43:02.056  7075  7687 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 15:43:02.057  7075  7687 V BluetoothOppNotification: inbound notification was removed.
08-26 15:43:02.057  7075  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 15:43:02.059  7075  7690 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 15:43:02.061  7075  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@89a9419 on behalf of 
08-26 15:43:02.067  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:02.067  7075  7075 V BluetoothSapService: Sap Service onCreate
,08-26 15:43:02.071  7075  7075 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:02.071  7075  7075 V BluetoothSapService: state: 12
08-26 15:43:02.071  7075  7075 V BluetoothSapService: Starting SAP server process
08-26 15:43:02.073  7075  7075 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 15:43:02.059  7691  7691 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:02.059  7691  7691 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:02.075  7075  7692 V BluetoothSapService: Sap Service initRfcommSocket
08-26 15:43:02.076  1032  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:02.077  7075  7692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:02.079  7075  7692 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-26 15:43:02.079  7075  7692 V BluetoothSapService: Succeed to create listening socket 
08-26 15:43:02.079  7075  7692 V BluetoothSapService: Accepting socket connection...
,08-26 15:43:02.085  7691  7691 V BT_SAP  : Event pipe created
08-26 15:43:02.085  7691  7691 V BT_SAP  : create_server_socket qcom.sap.server
08-26 15:43:02.085  7691  7691 V BT_SAP  : created socket fd 6
08-26 15:43:02.146  7323  7373 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-26 15:43:02.503  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=-8ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:43:02.513  1032  1537 D LGWifiP2pService: DefaultState{ when=-9ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:02.530  1032  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-26 15:43:02.530  1032  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 15:43:02.747  7427  7440 W art     : Suspending all threads took: 10.090ms
,08-26 15:43:02.961  1032  1937 I ActivityManager: Killing 7474:com.lge.bnr/1000 (adj 15): empty #17
,08-26 15:43:02.993  1032  1625 W libprocessgroup: failed to open /acct/uid_1000/pid_7474/cgroup.procs: No such file or directory
,08-26 15:43:03.002  7075  7075 V BluetoothOppNotification: new notify threadi!
08-26 15:43:03.002  7075  7075 V BluetoothOppNotification: send delay message
08-26 15:43:03.011  7075  7704 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 15:43:03.015  7075  7704 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@eb758d5 on behalf of 
08-26 15:43:03.015  7075  7704 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 15:43:03.017  7075  7704 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 15:43:03.018  7075  7704 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2adfe8ea on behalf of 
08-26 15:43:03.018  7075  7704 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 15:43:03.022  7075  7704 V BluetoothOppNotification: outbound notification was removed.
08-26 15:43:03.022  7075  7704 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 15:43:03.023  7075  7704 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@949a7db on behalf of 
08-26 15:43:03.024  7075  7704 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 15:43:03.028  7075  7704 V BluetoothOppNotification: inbound notification was removed.
08-26 15:43:03.029  7075  7704 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 15:43:03.031  7075  7704 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13e36278 on behalf of 
08-26 15:43:03.084  1032  1997 I ActivityManager: Killing 6976:com.lge.sync/1000 (adj 15): empty #17
,08-26 15:43:03.107  1032  1544 D WifiService: Client connection lost with reason: 4
,08-26 15:43:03.170  1032  1937 W libprocessgroup: failed to open /acct/uid_1000/pid_6976/cgroup.procs: No such file or directory
,08-26 15:43:03.462  1032  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 15:43:03.463  1032  1961 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@236c7a40 mBinding = false
,08-26 15:43:03.501  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 15:43:03.501  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 15:43:03.501  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,08-26 15:43:03.505  1032  1095 D BluetoothManagerService: Message: 2
08-26 15:43:03.506  1032  1095 D BluetoothManagerService: Sending off request.
08-26 15:43:03.507  7075  7674 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 15:43:03.508  7075  7558 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 15:43:03.508  7075  7558 D BluetoothAdapterProperties: Setting state to 13
08-26 15:43:03.508  7075  7558 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 15:43:03.509  7075  7558 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 15:43:03.509  7075  7558 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 15:43:03.511  7075  7570 D BluetoothAdapterProperties: Scan Mode:20
08-26 15:43:03.512  7075  7558 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 15:43:03.514  7075  7677 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 15:43:03.514  7075  7677 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:43:03.514  7075  7677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 15:43:03.514  7075  7677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 15:43:03.514  7075  7677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 15:43:03.514  7075  7677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 15:43:03.514  7075  7677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 15:43:03.514  7075  7677 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-26 15:43:03.519  7075  7678 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:43:03.519  7075  7688 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:43:03.520  7075  7690 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:43:03.520  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 15:43:03.521  7075  7627 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 15:43:03.522  7075  7558 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 15:43:03.527  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 15:43:03.527  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 15:43:03.527  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 15:43:03.527  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 15:43:03.527  7075  7627 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:43:03.527  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 15:43:03.527  7075  7627 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:43:03.527  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 15:43:03.527  7075  7627 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:43:03.527  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 15:43:03.527  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 15:43:03.527  7075  7627 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-26 15:43:03.533  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:43:03.533  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:03.533  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:03.533  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:03.533  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:03.533  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:43:03.533  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:03.533  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:03.533  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:43:03.542  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:43:03.542  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:03.548  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:43:03.549  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:03.549  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:03.549  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:03.549  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:03.549  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:43:03.549  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:03.549  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:03.549  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:43:03.551  6697  6697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:43:03.552  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:03.552  1032  1095 D BluetoothManagerService: Message: 60
08-26 15:43:03.552  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 15:43:03.552  1032  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 15:43:03.555  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:03.558  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 15:43:03.562  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:03.564  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:03.570  7075  7075 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:03.570  7075  7075 D BluetoothMapService: STATE_TURNING_OFF
08-26 15:43:03.570  7075  7075 V BluetoothMapService: Handler(): got msg=4
08-26 15:43:03.570  7075  7075 D BluetoothMapService: MAP Service closeService in
08-26 15:43:03.570  7075  7075 D BluetoothMapMasInstance: MAP Service shutdown
08-26 15:43:03.571  7075  7075 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 15:43:03.571  7075  7075 V BluetoothMapService: MAP Service closeService out
,08-26 15:43:03.574  7075  7075 V BtOppService: Receiver DISABLED_ACTION 
08-26 15:43:03.574  7075  7075 I BtOppRfcommListener: stopping Accept Thread
08-26 15:43:03.574  7075  7075 V BtOppRfcommListener: close mBtServerSocket
08-26 15:43:03.575  7075  7688 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 15:43:03.576  7075  7075 V BtOppRfcommListener: waiting for thread to terminate
08-26 15:43:03.576  7075  7075 V BtOppRfcommListener: done waiting for thread to terminate
08-26 15:43:03.579  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-26 15:43:03.580  7075  7692 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:43:03.587  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 15:43:03.592  7075  7075 V BtOppService: onDestroy
08-26 15:43:03.593  7075  7075 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 15:43:03.598  7075  7075 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 15:43:03.598  7075  7075 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:03.598  7075  7075 V BluetoothPbapReceiver: ***********state = 13
08-26 15:43:03.600  7075  7075 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-26 15:43:03.604  7075  7075 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:03.604  7075  7075 V BluetoothPbapService: state: 13
08-26 15:43:03.605  7075  7075 V BluetoothPbapService: Pbap Service closeService in
08-26 15:43:03.607  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 15:43:03.608  7075  7075 V BluetoothPbapService: successfully stopped pbap service
08-26 15:43:03.608  7075  7075 V BluetoothPbapService: Pbap Service closeService out
08-26 15:43:03.609  7075  7075 V BluetoothPbapService: Pbap Service onDestroy
08-26 15:43:03.610  7075  7075 V BluetoothPbapService: Pbap Service closeService in
08-26 15:43:03.610  7075  7075 V BluetoothPbapService: Pbap Service closeService out
08-26 15:43:03.610  7075  7075 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 15:43:03.629  6956  6956 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:03.633  6956  6956 D BluetoothPbap: Proxy object disconnected
08-26 15:43:03.633  6956  6956 D PbapServerProfile: Bluetooth service disconnected
08-26 15:43:03.646  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 15:43:03.653  6956  6956 D BluetoothPermissionRequest: onReceive
08-26 15:43:03.653  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 15:43:03.660  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 15:43:03.666  7075  7075 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 15:43:03.666  7075  7075 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 15:43:03.667  7075  7075 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 15:43:03.671  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:03.671  7075  7075 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 15:43:03.673  7075  7075 V BluetoothFtpService: Ftp Service onStartCommand
08-26 15:43:03.673  7075  7075 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:03.674  7075  7075 V BluetoothFtpService: Ftp Service closeService
08-26 15:43:03.674  7075  7075 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 15:43:03.675  7075  7075 V BluetoothFtpService: successfully stopped ftp service
08-26 15:43:03.675  7075  7075 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 15:43:03.675  7075  7075 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 15:43:03.675  7075  7075 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 15:43:03.675  7075  7075 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:03.675  7075  7075 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 15:43:03.675  7075  7075 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-26 15:43:03.677  7075  7075 V BluetoothFtpService: Ftp Service onDestroy
,08-26 15:43:03.677  7075  7075 V BluetoothFtpService: Ftp Service closeService
,08-26 15:43:03.678  7075  7075 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:03.678  7075  7075 V BluetoothSapService: state: 13
,08-26 15:43:03.678  7075  7075 V BluetoothSapService: Stopping SAP server process
08-26 15:43:03.680  7075  7075 V BluetoothSapService: Sap Service closeSapService in
08-26 15:43:03.680  7075  7075 V BluetoothSapService: Close listen Socket : 
,08-26 15:43:03.680  7075  7075 V BluetoothSapService: Close rfcomm Socket : 
08-26 15:43:03.680  7075  7075 V BluetoothSapService: Close sapd  Socket : 
08-26 15:43:03.682  7075  7075 V BluetoothSapService: Sap Service closeSapService out
08-26 15:43:03.682  7075  7075 V BluetoothSapService: Sap Service onDestroy,
08-26 15:43:03.682  7075  7075 V BluetoothSapService: Sap Service closeSapService in
08-26 15:43:03.682  7075  7075 V BluetoothSapService: Close listen Socket : 
08-26 15:43:03.682  7075  7075 V BluetoothSapService: Close rfcomm Socket : 
08-26 15:43:03.682  7075  7075 V BluetoothSapService: Close sapd  Socket : 
,08-26 15:43:03.685  7075  7075 V BluetoothSapService: Sap Service closeSapService out
08-26 15:43:04.427  7075  7570 D bt_hci_bdroid: cleanup
,08-26 15:43:04.442  7075  7629 I bt_lpm  : LPM is already off!!!
08-26 15:43:04.442  7075  7653 I bt_userial_mct: exiting userial_read_thread
08-26 15:43:04.442  7075  7653 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 15:43:04.443  7075  7627 W bt-btif : ag scb idx 1 not allocated
08-26 15:43:04.444  7075  7627 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 15:43:04.444  7075  7627 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:43:04.444  7075  7627 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 15:43:04.445  7075  7570 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 15:43:04.445  7075  7629 I bt_vendor: hw_epilog_process
08-26 15:43:04.445  7075  7570 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 15:43:04.445  7075  7570 D bt_userial_mct: userial_close
08-26 15:43:04.445  7075  7570 E bt_userial_mct: pthread_join() FAILED result:3
08-26 15:43:04.445  7075  7570 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 15:43:04.449  7075  7570 D bt_hci_bdroid: set_power 0
08-26 15:43:04.449  7075  7570 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 15:43:04.449  7075  7570 I bt_vendor: bluetooth satus is on
08-26 15:43:04.449  7075  7570 I bt_vendor: bt-vendor : resetting BT status
08-26 15:43:04.450  7075  7570 I bt_vendor: Starting hciattach daemon
08-26 15:43:04.450  7075  7570 I bt_vendor: try to set false
08-26 15:43:04.453  7075  7570 I bt_vendor: Starting hciattach daemon
08-26 15:43:04.453  7075  7570 I bt_vendor: try to set false
,08-26 15:43:04.458  7075  7570 I bt_vendor: cleanup
08-26 15:43:04.459  7075  7627 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 15:43:04.459  7075  7570 I GKI_LINUX: GKI_exit_task 0 done
08-26 15:43:04.459  7075  7570 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 15:43:04.461  7075  7558 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 15:43:04.466  7075  7075 D HeadsetService: Received stop request...Stopping profile...
,08-26 15:43:04.470  7075  7075 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 15:43:04.470  7075  7075 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 15:43:04.470  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:04.472  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 15:43:04.473  1032  1032 D BluetoothHeadset: Proxy object disconnected
08-26 15:43:04.473  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 15:43:04.474  7075  7595 D HeadsetStateMachine: Exit Disconnected: -1
08-26 15:43:04.476  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 15:43:04.477  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 15:43:04.477  7075  7075 D A2dpService: Received stop request...Stopping profile...
08-26 15:43:04.477  7075  7619 D A2dpStateMachine: Exit Disconnected: -1
,08-26 15:43:04.482  7075  7075 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 15:43:04.486  7075  7558 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 15:43:04.487  7075  7075 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 15:43:04.487  7075  7075 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 15:43:04.487  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:04.489  1032  1032 D BluetoothA2dp: Proxy object disconnected
08-26 15:43:04.489  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 15:43:04.490  7075  7075 D HidService: Received stop request...Stopping profile...
08-26 15:43:04.490  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
,08-26 15:43:04.494  7075  7075 D HeadsetStateMachine: Unbinding service...
08-26 15:43:04.496  7075  7075 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 15:43:04.496  7075  7075 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 15:43:04.496  7075  7075 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 15:43:04.496  7075  7075 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 15:43:04.496  7075  7075 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 15:43:04.496  7075  7075 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 15:43:04.496  7075  7075 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 15:43:04.497  7075  7075 D HealthService: Received stop request...Stopping profile...
08-26 15:43:04.497  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:04.500  7075  7075 D PanService: Received stop request...Stopping profile...
08-26 15:43:04.500  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:04.501  7075  7075 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 15:43:04.504  7075  7075 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 15:43:04.504  7075  7075 D BtGatt.GattService: stop()
08-26 15:43:04.504  7075  7075 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 15:43:04.505  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:04.508  7075  7075 D BluetoothMapService: Received stop request...Stopping profile...
08-26 15:43:04.508  7075  7075 D BluetoothMapService: stop()
08-26 15:43:04.509  7075  7075 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 15:43:04.509  7075  7075 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 15:43:04.510  7075  7075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f520f15
08-26 15:43:04.511  7075  7075 I BluetoothA2dpServiceJni: cleanupNative
08-26 15:43:04.511  7075  7620 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 15:43:04.511  7075  7075 I GKI_LINUX: GKI_exit_task 2 done
08-26 15:43:04.511  7075  7075 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 15:43:04.512  7075  7075 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 15:43:04.512  7075  7075 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 15:43:04.512  7075  7075 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 15:43:04.512  7075  7075 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 15:43:04.512  7075  7075 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 15:43:04.513  7075  7075 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 15:43:04.513  7075  7075 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 15:43:04.516  7075  7075 V BluetoothMapService: Handler(): got msg=4
08-26 15:43:04.516  7075  7075 D BluetoothMapService: MAP Service closeService in
08-26 15:43:04.516  7075  7075 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 15:43:04.516  7075  7075 V BluetoothMapService: MAP Service closeService out
,08-26 15:43:04.519  7075  7558 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 15:43:04.520  7075  7558 D BluetoothAdapterProperties: Setting state to 10
08-26 15:43:04.520  7075  7558 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 15:43:04.521  7075  7075 D BluetoothMapService: cleanup()
08-26 15:43:04.521  7075  7075 D BluetoothMapService: MAP Service closeService in
08-26 15:43:04.521  7075  7075 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 15:43:04.521  7075  7075 V BluetoothMapService: MAP Service closeService out
08-26 15:43:04.522  1032  1095 D BluetoothManagerService: Message: 60
08-26 15:43:04.522  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 15:43:04.522  1032  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-26 15:43:04.523  7075  7558 I BluetoothAdapterState: Entering OffState
08-26 15:43:04.523  6956  7449 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:43:04.526  6956  7449 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 15:43:04.526  1853  2718 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:43:04.527  6956  7449 D BluetoothMap: onBluetoothStateChange: up=false
08-26 15:43:04.528  6956  7449 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 15:43:04.531  1853  2476 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:43:04.533  1032  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:43:04.533  1032  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:43:04.533  6956  7449 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 15:43:04.534  6956  7449 D BluetoothPan: onBluetoothStateChange on: false
08-26 15:43:04.534  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:43:04.535  1032  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 15:43:04.535  1032  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 15:43:04.537  1032  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 15:43:04.537  1032  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 15:43:04.537  1032  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@236c7a40 mBinding = false
08-26 15:43:04.538  1032  1095 D BluetoothManagerService: Sending unbind request.
08-26 15:43:04.543  7075  7570 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 15:43:04.546  7075  7075 I GKI_LINUX: GKI_exit_task 1 done
08-26 15:43:04.546  7075  7075 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 15:43:04.546  7075  7075 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 15:43:04.546  7075  7075 I art     : --- WEIRD: removing null entry 248
08-26 15:43:04.546  7075  7075 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-26 15:43:04.546  7075  7075 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 15:43:04.547  7075  7075 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 15:43:04.549  1032  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 15:43:04.551  7075  7075 I art     : System.exit called, status: 0
08-26 15:43:04.551  7075  7075 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 15:43:04.571   317  1737 V AudioFlinger: 7075 died, releasing its sessions
08-26 15:43:04.571   317  1737 V AudioFlinger:  pid 1853 @ 0
08-26 15:43:04.571   317  1737 V AudioFlinger:  pid 3453 @ 1
08-26 15:43:04.571   317  1737 V AudioFlinger:  pid 3453 @ 2
,08-26 15:43:04.575  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-26 15:43:04.575  1943  2130 D LGBluetoothAPIService: Message: 101
08-26 15:43:04.575  1943  2130 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-26 15:43:04.576  1943  2130 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-26 15:43:04.576  1943  2130 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-26 15:43:04.577  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 15:43:04.609  1032  1960 I ActivityManager: Process com.android.bluetooth (pid 7075) has died
,08-26 15:43:04.609  1032  1960 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-26 15:43:04.610  1032  1960 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-26 15:43:04.616  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:04.616  1943  2130 D LGBluetoothAPIService: Message: 2
08-26 15:43:04.616  1943  2130 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-26 15:43:04.616  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 15:43:04.621  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:04.623  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:04.626  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 15:43:04.626  6956  6956 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 15:43:04.627  1603  1603 D BluetoothAdapter: 331866596: getState() :  mService = null. Returning STATE_OFF
08-26 15:43:04.628  1603  1603 D BluetoothAdapter: 331866596: getState() :  mService = null. Returning STATE_OFF
08-26 15:43:04.629  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 15:43:04.687  1032  1891 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7759 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 15:43:04.689  6956  6956 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:04.764  7759  7759 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 15:43:04.765  7759  7759 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 15:43:04.765  7759  7759 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 15:43:04.766  7759  7759 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:43:04.788  7759  7759 D BluetoothAdapterApp: Loading JNI Library
,08-26 15:43:04.822  7759  7759 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@6a9115d Instance Count = 1
,08-26 15:43:04.828  7759  7759 D BluetoothAdapterApp: onCreate
08-26 15:43:04.853  7759  7759 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 15:43:04.853  7759  7759 D ProfileConfigQcom: Adding HeadsetService
,08-26 15:43:04.854  7759  7759 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-26 15:43:04.854  7759  7759 D ProfileConfigQcom: Adding A2dpService
08-26 15:43:04.854  7759  7759 D ProfileConfigQcom: [BTUI] HidService is supported
,08-26 15:43:04.854  7759  7759 D ProfileConfigQcom: Adding HidService
08-26 15:43:04.854  7759  7759 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 15:43:04.855  7759  7759 D ProfileConfigQcom: Adding HealthService
08-26 15:43:04.855  7759  7759 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 15:43:04.856  7759  7759 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 15:43:04.856  7759  7759 D ProfileConfigQcom: Adding PanService
08-26 15:43:04.856  7759  7759 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 15:43:04.856  7759  7759 D ProfileConfigQcom: Adding GattService
08-26 15:43:04.856  7759  7759 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 15:43:04.857  7759  7759 D ProfileConfigQcom: Adding BluetoothMapService
08-26 15:43:04.857  7759  7759 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 15:43:04.858  7759  7759 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 15:43:04.859  7759  7759 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:04.860  7759  7759 V BluetoothPbapReceiver: ***********state = 10
08-26 15:43:04.861  7759  7759 V LGMDMManagerInternal: Create singleton instance
,08-26 15:43:04.943  7759  7759 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-26 15:43:04.943  7759  7759 D LGBluetoothAPIServer: [BTUI] onBind()
,08-26 15:43:04.948  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-26 15:43:04.949  1943  2130 D LGBluetoothAPIService: Message: 100
08-26 15:43:04.949  1943  2130 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 15:43:04.950  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 15:43:04.952  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 15:43:04.962  6956  6956 D BluetoothPermissionRequest: onReceive
,08-26 15:43:04.966  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 15:43:04.966  6956  6956 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 15:43:04.970  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 15:43:04.980  7759  7759 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-26 15:43:04.987  7759  7759 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:04.994  7759  7759 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-26 15:43:04.995  7759  7759 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 15:43:04.995  7759  7759 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 15:43:04.998  7759  7759 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:04.999  7759  7759 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 15:43:05.007  7025  7025 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-26 15:43:06.570  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:43:06.570  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:06.633  1032  1423 V AlarmManager: ELAPSED_WAKEUP set : Alarm{dbd971f type 2 when 135965 com.google.android.gms} when 135965
,08-26 15:43:06.652   313  7788 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-26 15:43:06.660  1032  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 15:43:06.686  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 15:43:06.721  1032  1477 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 15:43:06.794  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 15:43:06.797  1032  1032 D administrator: Handling package changes for user 0
08-26 15:43:06.807  1032  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7794 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 15:43:06.852  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 15:43:06.865  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 15:43:06.932  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-26 15:43:06.932  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 15:43:06.972  1032  1924 I art     : Explicit concurrent mark sweep GC freed 75466(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.012ms total 130.875ms
,08-26 15:43:06.977  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-26 15:43:06.986  7794  7794 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 15:43:07.028  1032  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:43:07.034  1032  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-26 15:43:07.043  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-26 15:43:07.044  7794  7794 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 15:43:07.044  7794  7794 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 15:43:07.046  2501  2501 V GmsNetworkLocationProvi: DISABLE
08-26 15:43:07.081  2501  2501 E GCoreFlp: Bound FusedProviderService with LocationManager
08-26 15:43:07.082  1032  1090 D LocationProviderProxy: applying state to connected service
,08-26 15:43:07.131  7794  7835 I Babel   : MmsConfig: mnc/mcc: 0/0
08-26 15:43:07.131  7794  7835 I Babel   : MmsConfig.loadMmsSettings
,08-26 15:43:07.135  7794  7835 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 15:43:07.135  7794  7835 I Babel   : MmsConfig.loadFromDatabase
,08-26 15:43:07.156  7794  7835 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 15:43:07.156  7794  7835 I Babel   : MmsConfig.loadFromResources
08-26 15:43:07.158  7794  7835 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-26 15:43:07.159  7794  7835 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-26 15:43:07.169  7794  7833 W AudioCapabilities: Unsupported mime audio/evrc
08-26 15:43:07.171  7794  7833 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 15:43:07.172  7794  7794 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:07.173  7794  7833 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 15:43:07.183  7794  7833 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-26 15:43:07.185  7794  7833 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 15:43:07.189  7794  7833 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 15:43:07.201  1816  7837 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-26 15:43:07.201  1816  7837 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-26 15:43:07.203  7794  7833 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 15:43:07.206  7794  7833 W VideoCapabilities: Unsupported mime video/divx
08-26 15:43:07.207  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 15:43:07.216  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4639aff
08-26 15:43:07.216  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 15:43:07.216  7137  7137 D AppUp4:CustFacade: isPhone : true
08-26 15:43:07.217  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-26 15:43:07.217  7137  7137 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-26 15:43:07.218  1816  4783 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-26 15:43:07.220  7794  7833 W VideoCapabilities: Unsupported mime video/divx311
08-26 15:43:07.224  7794  7833 W VideoCapabilities: Unsupported mime video/divx4
08-26 15:43:07.229  7794  7833 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 15:43:07.257  7794  7833 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-26 15:43:07.263  1032  1575 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7840 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-26 15:43:07.266  1032  1047 I ActivityManager: Killing 6832:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-26 15:43:07.268  7794  7833 W AudioCapabilities: Unsupported mime audio/eac3
08-26 15:43:07.269  7794  7833 W AudioCapabilities: Unsupported mime audio/ac3
08-26 15:43:07.270  7794  7833 W AudioCapabilities: Unsupported mime audio/g726
08-26 15:43:07.271  7794  7833 W AudioCapabilities: Unsupported mime audio/wma-voice
08-26 15:43:07.271  7794  7833 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-26 15:43:07.274  7794  7833 W AudioCapabilities: Unsupported mime audio/adpcm
08-26 15:43:07.276  7794  7833 W VideoCapabilities: Unsupported mime video/theora
08-26 15:43:07.278  7794  7833 W VideoCapabilities: Unsupported mime video/mjpg
,08-26 15:43:07.285  7005  7005 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 15:43:07.285  7005  7005 W System.err: android.os.DeadObjectException
08-26 15:43:07.285  7005  7005 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 15:43:07.285  7005  7005 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 15:43:07.285  7005  7005 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 15:43:07.285  7005  7005 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 15:43:07.285  7005  7005 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 15:43:07.285  7005  7005 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 15:43:07.285  7005  7005 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:43:07.285  7005  7005 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:43:07.285  7005  7005 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:43:07.285  7005  7005 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 15:43:07.285  7005  7005 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:07.286  7005  7005 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:07.286  7005  7005 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 15:43:07.286  7005  7005 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 15:43:07.286  7005  7005 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 15:43:07.286  7005  7005 W System.err: android.os.DeadObjectException
08-26 15:43:07.286  7005  7005 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 15:43:07.286  7005  7005 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 15:43:07.286  7005  7005 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 15:43:07.286  7005  7005 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 15:43:07.286  7005  7005 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 15:43:07.286  7005  7005 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 15:43:07.286  7005  7005 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:43:07.286  7005  7005 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:43:07.286  7005  7005 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:43:07.286  7005  7005 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 15:43:07.286  7005  7005 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:07.286  7005  7005 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:07.286  7005  7005 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 15:43:07.287  7005  7005 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 15:43:07.287  7005  7005 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 15:43:07.287  7005  7005 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-26 15:43:07.473  1032  1047 E libprocessgroup: failed to kill 1 processes for processgroup 6832
,08-26 15:43:07.559  1032  1924 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-26 15:43:07.565  7005  7005 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 15:43:07.566  7005  7005 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-26 15:43:07.593  7840  7840 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:43:07.594  7840  7840 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 15:43:07.594  7840  7840 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 15:43:07.596  7840  7840 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-26 15:43:07.596  7840  7840 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 15:43:07.637  1032  1882 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7860 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 15:43:07.642  7005  7005 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 15:43:07.722  7860  7860 D UEI.SmartControl: Quickset Services start...
08-26 15:43:07.724  7840  7840 I SystemConfig: BUILD Country: EU
08-26 15:43:07.724  7840  7840 I SystemConfig: BUILD Operator: OPEN
08-26 15:43:07.724  7860  7860 I UEI.SmartControl: Manufacture = LGE
08-26 15:43:07.725  7860  7860 D UEI.SmartControl: Id = LGNevo
,08-26 15:43:07.729  7860  7860 D UEI.SmartControl: File observer start...
08-26 15:43:07.730  7860  7860 E UEI.SmartControl: IR Port is disabled: false
08-26 15:43:07.731  7860  7860 D UEI.SmartControl: Starting file observer...
08-26 15:43:07.731  7860  7860 D UEI.SmartControl: Extracting JNI libs...
08-26 15:43:07.732  7860  7860 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 15:43:07.788  1032  1996 I ActivityManager: Killing 7005:com.lge.qremote/u0a112 (adj 15): empty #17
,08-26 15:43:07.820  7860  7860 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-26 15:43:07.820  7860  7860 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-26 15:43:07.820  7860  7860 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-26 15:43:07.846  7860  7860 I UEI.SmartControl: --- Selecting new region: 6
08-26 15:43:07.848  7860  7860 I UEI.SmartControl: Model = LG-D855
,08-26 15:43:07.849  7860  7860 D UEI.SmartControl: QS Service created
,08-26 15:43:07.861  1032  1891 W libprocessgroup: failed to open /acct/uid_10112/pid_7005/cgroup.procs: No such file or directory
,08-26 15:43:07.869  7840  7884 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-26 15:43:07.869  7840  7884 I SystemConfig: existFile = false
08-26 15:43:07.869  7840  7884 I SystemConfig: canReadFile = false
08-26 15:43:07.869  7840  7884 I SystemConfig: systemFeature RCS result false
08-26 15:43:07.869  7840  7884 D SystemConfig: refreshRcsSupport() :false
08-26 15:43:07.875  7860  7860 I UEI.SmartControl: Service initServices...
,08-26 15:43:07.878  7860  7860 D UEI.SmartControl: QS start get config
,08-26 15:43:07.909  1032  1961 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7887 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-26 15:43:07.918  7860  7860 D UEI.SmartControl: Loading JNI Libs...
,08-26 15:43:07.987  7887  7887 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:43:07.987  7887  7887 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 15:43:07.987  7887  7887 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 15:43:07.988  7887  7887 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 15:43:08.070  7887  7887 I AppConfig: Total System Memory = 2995761152
,08-26 15:43:08.077  7887  7887 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-26 15:43:08.137  1032  2015 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7906 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:43:08.137  1032  2015 I ActivityManager: Killing 7173:com.lge.email/u0a23 (adj 15): empty #17
,08-26 15:43:08.145  7860  7860 I UEI.SmartControl: Supports setup maps: true
08-26 15:43:08.148  7860  7860 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 15:43:08.148  7860  7860 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 15:43:08.148  7860  7860 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 15:43:08.148  7860  7860 I UEI.SmartControl: ### init IR Blaster...
,08-26 15:43:08.154  7860  7860 D serial_port: Configuring serial port
,08-26 15:43:08.158  7860  7860 E UEI.SmartControl: UEIBLaster setting for 616
08-26 15:43:08.158  7860  7860 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 15:43:08.159  7860  7860 I UEI.SmartControl: configuring settings for MAXQ616
08-26 15:43:08.159  7860  7860 I UEI.SmartControl: Get version...
08-26 15:43:08.175  7860  7915 D UEI.SmartControl: serial port data available: 21
,08-26 15:43:08.203  7860  7860 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 15:43:08.203  7860  7860 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 15:43:08.203  7860  7860 I UEI.SmartControl: QS saving settings...
,08-26 15:43:08.205  7860  7860 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 15:43:08.209  1032  1890 W libprocessgroup: failed to open /acct/uid_10023/pid_7173/cgroup.procs: No such file or directory
08-26 15:43:08.222  7860  7915 D UEI.SmartControl: serial port data available: 4
,08-26 15:43:08.260  7860  7926 I UEI.SmartControl: Device manager: loading config....
,08-26 15:43:08.263  7860  7926 D UEI.SmartControl: ----------- loading internal config...
,08-26 15:43:08.267  7860  7860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 15:43:08.272  7860  7860 E UEI.SmartControl: Services init done
08-26 15:43:08.272  7860  7860 D UEI.SmartControl: QS Service init finished
08-26 15:43:08.273  7860  7860 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 15:43:08.273  7860  7860 D UEI.SmartControl: QS Service version code: 201091
08-26 15:43:08.274  7860  7860 D UEI.SmartControl: Service requested: Control
08-26 15:43:08.282  7860  7926 E UEI.SmartControl: Loading SETTINGS...
,08-26 15:43:08.285  7860  7860 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 15:43:08.287  7860  7860 D UEI.SmartControl: Service.onUnbind: IControl
08-26 15:43:08.291  7860  7860 D UEI.SmartControl: Service.onDestroy
08-26 15:43:08.292  7860  7860 D UEI.SmartControl: Lock is in USE false
08-26 15:43:08.292  7860  7860 D UEI.SmartControl: unbind internal service
08-26 15:43:08.295  7860  7926 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 15:43:08.295  7860  7860 D serial_port: close(fd = 25)
08-26 15:43:08.297  7860  7925 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-26 15:43:08.297  7860  7925 D UEI.SmartControl: -----service ready thread exits
,08-26 15:43:08.299  7860  7860 I UEI.SmartControl: Serial port is closed.
08-26 15:43:08.299  7860  7860 I UEI.SmartControl: Serial port is closed.
08-26 15:43:08.299  7860  7860 D UEI.SmartControl: Blaster closed
08-26 15:43:08.299  7860  7860 D UEI.SmartControl: Shut down QS...
08-26 15:43:08.300  7860  7860 D UEI.SmartControl: Stopping QS lib
08-26 15:43:08.300  7860  7860 D UEI.SmartControl: QS lib stop result = true
08-26 15:43:08.300  7860  7860 D UEI.SmartControl: Stopped QS lib
08-26 15:43:08.301  7860  7860 D UEI.SmartControl: Stopped file observer...
08-26 15:43:08.301  7860  7860 D UEI.SmartControl: QS shutdown complete
08-26 15:43:08.302  7860  7860 D UEI.SmartControl: QS Service created
08-26 15:43:08.320  7860  7860 I UEI.SmartControl: Service initServices...
08-26 15:43:08.320  7860  7860 D UEI.SmartControl: QS start get config
,08-26 15:43:08.430  7906  7906 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 15:43:08.519  7906  7906 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 15:43:08.520  7906  7906 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 15:43:08.565  7906  7906 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 15:43:08.587  7906  7906 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 15:43:08.590  7906  7906 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 15:43:08.605  7906  7906 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 15:43:08.605  7906  7906 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-26 15:43:08.618  1032  1996 I ActivityManager: Killing 7046:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-26 15:43:08.695  1032  2034 W libprocessgroup: failed to open /acct/uid_10026/pid_7046/cgroup.procs: No such file or directory
,08-26 15:43:08.709  7860  7860 I UEI.SmartControl: Supports setup maps: true
,08-26 15:43:08.712  4649  7952 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-26 15:43:08.715  7860  7860 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 15:43:08.716  7860  7860 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 15:43:08.716  7860  7860 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 15:43:08.716  7860  7860 I UEI.SmartControl: ### init IR Blaster...
08-26 15:43:08.716  3523  3538 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 15:43:08.718  3523  3538 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3ac193e2 on behalf of 7906
08-26 15:43:08.722  7860  7860 D serial_port: Configuring serial port
08-26 15:43:08.722  7860  7860 E UEI.SmartControl: UEIBLaster setting for 616
08-26 15:43:08.722  7860  7860 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 15:43:08.722  7860  7860 I UEI.SmartControl: configuring settings for MAXQ616
08-26 15:43:08.722  7860  7860 I UEI.SmartControl: Get version...
08-26 15:43:08.738  7860  7953 D UEI.SmartControl: serial port data available: 21
,08-26 15:43:08.764  7860  7860 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 15:43:08.764  7860  7860 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 15:43:08.764  7860  7860 I UEI.SmartControl: QS saving settings...
08-26 15:43:08.766  7860  7860 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 15:43:08.783  1032  1625 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7955 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-26 15:43:08.784  7860  7953 D UEI.SmartControl: serial port data available: 4
08-26 15:43:08.807  7906  7906 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 15:43:08.810   340   340 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 24.461ms
08-26 15:43:08.825  7860  7860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 15:43:08.831  7860  7974 I UEI.SmartControl: Device manager: loading config....
08-26 15:43:08.832  7860  7974 D UEI.SmartControl: ----------- loading internal config...
08-26 15:43:08.832   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 705us total 20.661ms
08-26 15:43:08.833  7906  7906 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-26 15:43:08.838  7860  7860 E UEI.SmartControl: Services init done
,08-26 15:43:08.839  7860  7860 D UEI.SmartControl: QS Service init finished
08-26 15:43:08.843  7860  7860 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 15:43:08.843  7860  7860 D UEI.SmartControl: QS Service version code: 201091
08-26 15:43:08.843  7860  7860 D UEI.SmartControl: Service requested: Control
08-26 15:43:08.855  7860  7860 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 15:43:08.856  7860  7974 E UEI.SmartControl: Loading SETTINGS...
08-26 15:43:08.856  1032  1891 I ActivityManager: Killing 6510:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-26 15:43:08.861   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.327ms total 28.710ms
08-26 15:43:08.862  7860  7974 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 15:43:08.873  7860  7973 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 15:43:08.873  7860  7973 D UEI.SmartControl: -----service ready thread exits
,08-26 15:43:08.886  7955  7955 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 15:43:08.910  1032  1890 W libprocessgroup: failed to open /acct/uid_1000/pid_6510/cgroup.procs: No such file or directory
,08-26 15:43:08.910  7860  7860 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3ee0e81b that was originally bound here
08-26 15:43:08.910  7860  7860 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3ee0e81b that was originally bound here
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 15:43:08.910  7860  7860 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 15:43:08.914  7860  7860 D UEI.SmartControl: Internal service binding...
08-26 15:43:08.923  7955  7955 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-26 15:43:08.923  7955  7955 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-26 15:43:08.923  7955  7955 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-26 15:43:08.923  7955  7955 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-26 15:43:08.923  7955  7955 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-26 15:43:08.923  7955  7955 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-26 15:43:08.943  1032  2034 I ActivityManager: Killing 7209:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-26 15:43:08.973  1032  2052 W libprocessgroup: failed to open /acct/uid_10046/pid_7209/cgroup.procs: No such file or directory
,08-26 15:43:09.216  1032  1890 V SIM_STK : Menu title from STK is T-Mobile
,08-26 15:43:09.235  4649  7952 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 523 ms] updated apps [took 523 ms] 
,08-26 15:43:09.291  7860  7929 D UEI.SmartControl: Internal timer expired: 2
,08-26 15:43:09.585  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:09.585  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@293a0939 added. We now have 6 listener(s)
,08-26 15:43:09.586  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:09.600  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:09.600  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@179b7b7e added. We now have 7 listener(s)
08-26 15:43:09.601  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:09.601  6697  6804 I System.out: IsBluetoothEnabled
08-26 15:43:09.602  1032  1937 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:09.602  1032  1937 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-26 15:43:09.603  1032  1095 D BluetoothManagerService: Message: 2
08-26 15:43:09.607  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:09.611  1032  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:09.611  1032  1996 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-26 15:43:09.634  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 15:43:09.635  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 15:43:09.635  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,08-26 15:43:09.638  1032  1095 D BluetoothManagerService: Message: 1
08-26 15:43:09.639  1032  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-26 15:43:09.668  1032  1095 D BluetoothManagerService: Message: 20
08-26 15:43:09.669  1032  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1602ee31:true
,08-26 15:43:09.673  7759  7759 D BluetoothAdapterState: make
,08-26 15:43:09.678  7759  7759 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 15:43:09.678  7759  7759 I bluedroid-qcom: init
08-26 15:43:09.679  7759  7997 I BluetoothAdapterState: Entering OffState
08-26 15:43:09.680  7759  7759 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 15:43:09.680  7759  7759 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 15:43:09.680  7759  7759 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 15:43:09.680  7759  7759 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 15:43:09.680  7759  7759 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 15:43:09.682  7759  7759 I bluedroid-qcom: get_profile_interface socket
08-26 15:43:09.683  7759  7759 I bluedroid-qcom: get_profile_interface map_client
,08-26 15:43:09.688  7759  8001 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 15:43:09.679  8000  8000 W bdaddr_loader: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:09.679  8000  8000 W bdaddr_loader: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:09.699  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-26 15:43:09.702  1032  1095 D BluetoothManagerService: Message: 40
08-26 15:43:09.702  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 15:43:09.703  7759  7774 I bluedroid-qcom: config_hci_snoop_log
08-26 15:43:09.704  1032  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 15:43:09.704  1032  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 15:43:09.710  8000  8000 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 15:43:09.710  8000  8000 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 15:43:09.710  8000  8000 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-26 15:43:09.711  8000  8000 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-26 15:43:09.716  7759  7997 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 15:43:09.718  7759  7997 D BluetoothAdapterProperties: Setting state to 11
08-26 15:43:09.718  7759  7997 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 15:43:09.720  8000  8000 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 15:43:09.720  8000  8000 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 15:43:09.722  1032  1095 D BluetoothManagerService: Message: 60
08-26 15:43:09.722  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 15:43:09.722  1032  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-26 15:43:09.727  7759  8001 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 15:43:09.728  7759  7997 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 15:43:09.734  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:09.735  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 15:43:09.737  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:09.750  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-26 15:43:09.753  7759  8001 D BluetoothAdapterProperties: Name is: G3
08-26 15:43:09.754  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 15:43:09.754  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 15:43:09.757  7759  7759 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 15:43:09.757  7759  7759 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:09.757  7759  7759 V BluetoothPbapReceiver: ***********state = 11
08-26 15:43:09.762  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 15:43:09.763  7759  7997 D BluetoothBondStateMachine: make
08-26 15:43:09.768  7759  8016 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 15:43:09.768  7759  7997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
08-26 15:43:09.768  7759  7997 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 15:43:09.768  7759  7997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
08-26 15:43:09.768  7759  7997 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,08-26 15:43:09.769  7759  7997 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 15:43:09.775  7759  7997 E BluetoothAdapterService: File transfer profiles supported!!
08-26 15:43:09.777  6956  6956 D BluetoothPermissionRequest: onReceive
08-26 15:43:09.783  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 15:43:09.784  7759  7759 D HeadsetService: Received start request. Starting profile...
08-26 15:43:09.785  7759  7759 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 15:43:09.785  7759  7759 D LGBluetoothHfpAdapter: Version 1.6
08-26 15:43:09.788  7759  7997 E BluetoothAdapterService: File transfer profiles supported!!
08-26 15:43:09.790  7759  7759 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 15:43:09.791  7759  7759 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 15:43:09.792  7759  7759 D HeadsetStateMachine: make
08-26 15:43:09.794  7759  7997 E BluetoothAdapterService: File transfer profiles supported!!
08-26 15:43:09.799  7759  7997 E BluetoothAdapterService: File transfer profiles supported!!
08-26 15:43:09.804  7759  7997 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 15:43:09.810  7759  7997 E BluetoothAdapterService: File transfer profiles supported!!
08-26 15:43:09.814  7759  7997 E BluetoothAdapterService: File transfer profiles supported!!
08-26 15:43:09.830  7759  7997 V LGMDMManager: Create singleton instance
,08-26 15:43:09.831  7759  7759 D LgDataFeature: LgDataFeature() Constructor: none
08-26 15:43:09.831  7759  7759 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 15:43:09.832  7759  7997 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 15:43:09.836  7759  7759 D HeadsetStateMachine: max_hf_connections = 1
08-26 15:43:09.836  7759  7759 I bluedroid-qcom: get_profile_interface handsfree
08-26 15:43:09.838  7759  7759 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 15:43:09.839   317  1381 V AudioPolicyService: registerClient() client 0xb0410a00, uid 1002
08-26 15:43:09.839   317   317 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 15:43:09.839   317   317 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 15:43:09.839   317   317 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 15:43:09.839  7759  7759 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 15:43:09.839   317  1382 V AudioFlinger: registerClient() client 0xb5581850, pid 7759
08-26 15:43:09.840   317  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:09.840   317  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 15:43:09.840  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:09.840  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 15:43:09.840  3453  3468 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:09.840  3453  3468 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 15:43:09.840  1032  1924 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:09.840  1032  1924 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 15:43:09.841   317  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:09.841   317  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 15:43:09.841  1853  2476 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:09.841  1853  2476 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 15:43:09.841  3453  4921 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:09.841  3453  4921 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 15:43:09.841  7759  7775 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:09.841  7759  7775 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 15:43:09.841  7759  7759 V ToneGenerator: Create Track: 0xb4928a80
08-26 15:43:09.841  7759  7759 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 15:43:09.841  7759  7759 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 15:43:09.841  7759  7775 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:09.841  7759  7775 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 15:43:09.841   317  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 15:43:09.841   317  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 15:43:09.841   317  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 15:43:09.841   317  1381 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 15:43:09.841  1032  2015 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:09.841  1032  2015 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 15:43:09.842  1603  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 15:43:09.842  1603  1623 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 15:43:09.842  1603  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 15:43:09.842   317   317 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 15:43:09.842  1603  1623 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 ,15:43:09.842   317  1382 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 15:43:09.842   317  1382 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 15:43:09.842   317  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 15:43:09.842   317  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 15:43:09.842  7759  7759 V AudioSystem: getLatency() output 2, latency 50
08-26 15:43:09.842  7759  7759 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 15:43:09.842  7759  7759 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 15:43:09.842   317  1737 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 15:43:09.842   317  1737 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 15:43:09.842   317  1737 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 15:43:09.842   317  1737 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 15:43:09.842   317  1737 V AudioFlinger: createTrack() lSessionId: 23
08-26 15:43:09.843  7759  7759 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
,08-26 15:43:09.844   317  1381 V AudioFlinger: acquiring 23 from 7759, for 7759
08-26 15:43:09.844   317  1381 V AudioFlinger:  added new entry for 23
08-26 15:43:09.844  7759  7759 V ToneGenerator: ToneGenerator INIT OK, time: 139195
08-26 15:43:09.844  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
08-26 15:43:09.845  7759  8019 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 15:43:09.845  7759  8019 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 15:43:09.845  7759  8019 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,08-26 15:43:09.845  7759  8019 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 15:43:09.846   317   317 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7759
08-26 15:43:09.847   317   317 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 15:43:09.847   317   317 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 15:43:09.847   317   317 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 15:43:09.847   317   317 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 15:43:09.847   317   317 V voice   : voice_set_parameters: exit with code(0)
,08-26 15:43:09.847   317   317 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 15:43:09.847   317   317 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 15:43:09.847   317   317 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 15:43:09.847   317   317 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 15:43:09.847   317   317 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 15:43:09.847   317   317 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,08-26 15:43:09.847  7759  8019 V ToneGenerator: ToneGenerator destructor
08-26 15:43:09.847  7759  8019 V ToneGenerator: stopTone
08-26 15:43:09.847  7759  8019 V ToneGenerator: Delete Track: 0xb4928a80
08-26 15:43:09.848  7759  8019 V AudioTrack: ~AudioTrack, releasing session id from 7759 on behalf of 7759
08-26 15:43:09.848  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
08-26 15:43:09.848   317  1381 V AudioFlinger: releasing 23 from 7759 for 7759
,08-26 15:43:09.848   317  1381 V AudioFlinger:  decremented refcount to 0
08-26 15:43:09.848   317  1381 V AudioFlinger: purging stale effects
08-26 15:43:09.848   317  1381 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 15:43:09.848   317  1381 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 15:43:09.848   317  1226 V AudioPolicyService: AudioCommandThread() waking up
08-26 15:43:09.848   317  1226 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 15:43:09.848   317  1226 V AudioPolicyManager: releaseOutput() 2
,08-26 15:43:09.848   317  1226 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 15:43:09.848   317  1381 V AudioFlinger: PlaybackThread::Track destructor
08-26 15:43:09.848   317  1381 V AudioFlinger: removeClient_l() pid 7759, calling pid 317
,08-26 15:43:09.851  1032  1048 W Process : Unable to open /proc/8022/status
08-26 15:43:09.851  7759  7759 D A2dpService: Received start request. Starting profile...
08-26 15:43:09.852  7759  7759 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 15:43:09.853  7759  7759 V Avrcp   : make
08-26 15:43:09.853  7759  7759 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 15:43:09.853  7759  7759 I bluedroid-qcom: get_profile_interface avrcp
08-26 15:43:09.862  7759  7759 V AudioManager: registerRemoteController: size of Media player list: 0
,08-26 15:43:09.864  7759  7759 E AudioManager: No RCC entry present to update
08-26 15:43:09.864  7759  7759 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 15:43:09.867  7759  7759 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 15:43:09.868  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 15:43:09.868  7759  7759 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 15:43:09.872  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 15:43:09.982  1032  1882 V SIM_STK : Menu title from STK is T-Mobile
08-26 15:43:09.982  1032  1882 V SIM_STK : Menu title from STK is T-Mobile
,08-26 15:43:10.112  1032  1996 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 15:43:10.123  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-26 15:43:10.128  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 15:43:10.129  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 15:43:10.129  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 15:43:10.129  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 15:43:10.129  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 15:43:10.129  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 15:43:10.129  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 15:43:10.129  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 15:43:10.129  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 15:43:10.130  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 15:43:10.130  7759  7759 I BluetoothA2dpServiceJni: classInitNative
08-26 15:43:10.130  7759  7759 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 15:43:10.131  7759  7759 D A2dpStateMachine: make
08-26 15:43:10.137  7759  7759 I bluedroid-qcom: get_profile_interface a2dp
08-26 15:43:10.137  7759  8029 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 15:43:10.139  7759  7759 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 15:43:10.140  7759  7759 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 15:43:10.140  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
08-26 15:43:10.141  7759  8028 D A2dpStateMachine: Enter Disconnected: -2
08-26 15:43:10.141  7759  7759 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 15:43:10.143  7759  7759 D HidService: Received start request. Starting profile...
08-26 15:43:10.143  7759  7759 I bluedroid-qcom: get_profile_interface hidhost
08-26 15:43:10.143  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
08-26 15:43:10.143  7759  7759 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 15:43:10.145  7759  7759 D HealthService: Received start request. Starting profile...
,08-26 15:43:10.148  7759  7759 I bluedroid-qcom: get_profile_interface health
08-26 15:43:10.148  7759  7759 I LGBluetoothHealthServiceJni: classInitNative: succeeds,
08-26 15:43:10.148  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
,08-26 15:43:10.149  7759  7759 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 15:43:10.161  7759  7759 D PanService: Received start request. Starting profile...
,08-26 15:43:10.161  7759  7759 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 15:43:10.161  7759  7759 I bluedroid-qcom: get_profile_interface pan
,08-26 15:43:10.183  7759  7759 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-26 15:43:10.183  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
,08-26 15:43:10.191  7759  7759 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 15:43:10.203  7759  7759 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 15:43:10.204  7759  7759 D BtGatt.GattService: Received start request. Starting profile...
08-26 15:43:10.204  7759  7759 D BtGatt.GattService: start()
08-26 15:43:10.204  7759  7759 I bluedroid-qcom: get_profile_interface gatt
08-26 15:43:10.205  7759  7759 D BtGatt.AdvertiseManager: advertise manager created
08-26 15:43:10.213  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
08-26 15:43:10.215  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
08-26 15:43:10.216  7759  7759 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 15:43:10.217  7759  7759 V BluetoothMapService: BluetoothMapBinder()
,08-26 15:43:10.219  7759  7759 D BluetoothMapService: Received start request. Starting profile...
08-26 15:43:10.220  7759  7759 D BluetoothMapService: start()
08-26 15:43:10.227  7759  7759 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-26 15:43:10.227  7759  7759 D BluetoothMapEmailAppObserver: createReceiver()
08-26 15:43:10.230  7759  7759 D BluetoothMapEmailAppObserver: initObservers()
08-26 15:43:10.231  7759  7759 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 15:43:10.242  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
,08-26 15:43:10.244  7759  7759 D HeadsetStateMachine: Proxy object connected
,08-26 15:43:10.245  7759  7759 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 15:43:10.245  7759  7759 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 15:43:10.247  7759  8019 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 15:43:10.248  7759  8019 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 15:43:10.250  7759  8019 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 15:43:10.253  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 15:43:10.255  7759  7759 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:10.267  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 15:43:10.272  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 15:43:10.274  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 15:43:10.275  7759  7759 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 15:43:10.278  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 15:43:10.280  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 15:43:10.281  7759  7759 V BluetoothMapService: Handler(): got msg=1
,08-26 15:43:10.283  7759  7997 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 15:43:10.283  7759  7997 I bluedroid-qcom: enable
08-26 15:43:10.283  7759  8043 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 15:43:10.284  7759  7759 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 15:43:10.284  7759  7759 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 15:43:10.284  7759  7759 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 15:43:10.284  7759  7759 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:10.284  7759  7759 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 15:43:10.284  7759  8043 I bt-btu  : btu_task pending for preload complete event
08-26 15:43:10.284  7759  7997 I bt_hci_bdroid: init
08-26 15:43:10.285  7759  7997 I bt_vendor: bt-vendor : init
08-26 15:43:10.285  7759  7997 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 15:43:10.285  7759  7997 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 15:43:10.285  7759  7997 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 15:43:10.285  7759  7997 D bt_userial_mct: userial_init
08-26 15:43:10.285  7759  7997 D bt_hci_bdroid: set_power 1
08-26 15:43:10.285  7759  7997 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 15:43:10.285  7759  7997 I bt_vendor: Starting hciattach daemon
08-26 15:43:10.285  7759  7997 I bt_vendor: try to set true
08-26 15:43:10.269  8046  8046 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:10.269  8046  8046 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:10.302  8047  8047 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 15:43:10.356  8054  8054 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 15:43:10.364  8055  8055 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 15:43:10.383  8057  8057 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 15:43:10.393  8058  8058 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-26 15:43:10.404  8059  8059 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 15:43:10.415  8060  8060 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-26 15:43:10.435  8063  8063 I libmdmdetect: ESOC framework not supported
08-26 15:43:10.435  8063  8063 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 15:43:10.444  8063  8063 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-26 15:43:10.444  8063  8063 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 15:43:10.444  8063  8063 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 15:43:10.444  8063  8063 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 15:43:10.444  8063  8063 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 15:43:10.444  8063  8063 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 15:43:10.444  8063  8063 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 15:43:10.479  8063  8064 E QC-QMI  : qmi_client [8063] 15: failed to locate client data
,08-26 15:43:10.479   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-26 15:43:10.479   468   468 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-26 15:43:10.531  8065  8065 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 15:43:10.559  8066  8066 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 15:43:10.587  7759  7997 I bt_vendor: bluetooth satus is on
,08-26 15:43:10.587  7759  7997 D bt_hci_bdroid: preload
08-26 15:43:10.588  7759  8045 D bt_userial_mct: userial_open(port:0)
,08-26 15:43:10.588  7759  8045 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-26 15:43:10.592  7759  8045 I bt_vendor: Done intiailizing UART
,08-26 15:43:10.595  7759  8045 I bt_vendor: Done intiailizing UART
08-26 15:43:10.595  7759  8045 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 15:43:10.595  7759  8045 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 15:43:10.595  7759  8068 D bt_userial_mct: Entering userial_read_thread()
08-26 15:43:10.595  7759  8043 I bt-btu  : btu_task received preload complete event
08-26 15:43:10.596  7759  8043 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 15:43:10.596  7759  8043 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 15:43:10.601  7759  8043 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 15:43:10.608  7759  8043 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 15:43:10.722  7759  8043 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
,08-26 15:43:10.723  7759  8043 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c9061 
,08-26 15:43:10.723  7759  8043 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c9061 ,
,08-26 15:43:10.754  7759  8001 E bt-btif : Calling BTA_HhEnable
08-26 15:43:10.754  7759  8001 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 15:43:10.755  7759  8001 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 15:43:10.757  7759  8043 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-26 15:43:10.757  7759  8043 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 15:43:10.757  7759  8043 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 15:43:10.759  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 15:43:10.760  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 15:43:10.760  7759  8043 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 15:43:10.760  7759  8043 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 15:43:10.761  7759  8001 D BluetoothAdapterProperties: Name is: G3
08-26 15:43:10.762  7759  8001 D BluetoothAdapterProperties: Scan Mode:20
08-26 15:43:10.762  7759  8001 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 15:43:10.763  7759  8001 D bt_hci_bdroid: postload
08-26 15:43:10.763  7759  8045 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 15:43:10.764  7759  8001 D bte_conf: Device ID record 1 : primary
08-26 15:43:10.764  7759  8001 D bte_conf:   vendorId            = 00c4
08-26 15:43:10.764  7759  8001 D bte_conf:   vendorIdSource      = 0001
08-26 15:43:10.764  7759  8001 D bte_conf:   product             = 13a1
08-26 15:43:10.764  7759  8001 D bte_conf:   version             = 1000
08-26 15:43:10.764  7759  8001 D bte_conf:   clientExecutableURL = 
08-26 15:43:10.764  7759  8001 D bte_conf:   serviceDescription  = 
08-26 15:43:10.764  7759  8001 D bte_conf:   documentationURL    = 
08-26 15:43:10.764  7759  8001 D bte_conf: bte_load_did_conf no section named DID2.
08-26 15:43:10.765  7759  8043 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 15:43:10.765  7759  8045 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 15:43:10.770  7759  8045 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 15:43:10.775  7759  7997 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 15:43:10.775  7759  7997 D BluetoothAdapterProperties: ScanMode =  20
08-26 15:43:10.775  7759  7997 D BluetoothAdapterProperties: State =  11
08-26 15:43:10.775  7759  7997 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 15:43:10.776  7759  7997 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 15:43:10.776  7759  7997 D BluetoothAdapterProperties: Setting state to 12
08-26 15:43:10.776  7759  7997 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 15:43:10.776  7759  8001 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 15:43:10.777  7759  8001 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 15:43:10.759  8076  8076 W sh      : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:10.769  8076  8076 W sh      : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:10.784  1032  1095 D BluetoothManagerService: Message: 60
08-26 15:43:10.784  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 15:43:10.784  1032  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-26 15:43:10.788  7759  8043 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 15:43:10.788  7759  8043 W bt-smp  : Plain text(LSB ~ MSB) = b5 b4 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 15:43:10.788  7759  8043 W bt-smp  : Encrypted text(LSB ~ MSB) = 7c 34 ff 08 7f 51 f8 73 1f ad 76 ce b9 1c 88 92 
08-26 15:43:10.789  7759  8043 W bt-btm  : Stopping oneshot timer
08-26 15:43:10.788  7759  8068 E bt_mct  : hci lib postload completed
08-26 15:43:10.801  7759  7997 I BluetoothAdapterState: Entering On State
,08-26 15:43:10.816  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:10.816  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:10.816  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:10.816  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:10.816  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:10.816  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:10.816  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:10.816  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:10.829  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:10.831  7759  8043 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 15:43:10.831  7759  8043 W bt-smp  : Plain text(LSB ~ MSB) = b9 9b 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 15:43:10.831  7759  8043 W bt-smp  : Encrypted text(LSB ~ MSB) = 51 8c 1d 3f 22 6e 87 29 63 3f 4d b8 67 58 4e 1c 
08-26 15:43:10.832  7759  8043 W bt-btm  : Stopping oneshot timer
08-26 15:43:10.840  7759  7997 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 15:43:10.840  7759  7997 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
,08-26 15:43:10.842  7759  7997 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 15:43:10.844  7759  7997 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 15:43:10.845  6956  6972 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:10.853  7759  7997 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-26 15:43:10.861  6956  6972 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 15:43:10.864  7759  8043 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 15:43:10.864  7759  8043 W bt-smp  : Plain text(LSB ~ MSB) = e6 56 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 15:43:10.864  7759  8043 W bt-smp  : Encrypted text(LSB ~ MSB) = cd 1a ed 9f cc aa 76 4d e2 4b c8 a2 0e e9 5e 3b 
08-26 15:43:10.864  7759  8043 W bt-btm  : Stopping oneshot timer
08-26 15:43:10.869  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 15:43:10.885  7759  8043 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 15:43:10.885  7759  8043 W bt-smp  : Plain text(LSB ~ MSB) = 67 41 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 15:43:10.885  7759  8043 W bt-smp  : Encrypted text(LSB ~ MSB) = 5c 1d c3 e4 50 2d 85 e6 c0 60 ee dd ab 73 1a c9 
08-26 15:43:10.885  7759  8043 W bt-btm  : Stopping oneshot timer
,08-26 15:43:10.898  1853  1853 D BluetoothHeadset: Proxy object connected
,08-26 15:43:10.906  7759  8043 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 15:43:10.906  7759  8043 W bt-smp  : Plain text(LSB ~ MSB) = 6f a5 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-26 15:43:10.906  7759  8043 W bt-smp  : Encrypted text(LSB ~ MSB) = 36 56 37 07 e0 09 9f 4c 26 27 af 84 da ee f0 a2 
,08-26 15:43:10.906  7759  8043 W bt-btm  : Stopping oneshot timer
08-26 15:43:10.912  6956  7449 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 15:43:10.922  6956  6956 D BluetoothA2dp: Proxy object connected
08-26 15:43:10.922  6956  6956 D A2dpProfile: Bluetooth service connected
08-26 15:43:10.924  6956  6956 D BluetoothInputDevice: Proxy object connected
08-26 15:43:10.924  6956  6956 D HidProfile: Bluetooth service connected
08-26 15:43:10.930  6956  6972 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:10.931  8081  8081 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-26 15:43:10.935  6956  6956 D BluetoothMap: Proxy object connected
08-26 15:43:10.935  6956  6956 D MapProfile: Bluetooth service connected
08-26 15:43:10.935  6956  6956 D BluetoothMap: getConnectedDevices()
08-26 15:43:10.936  7759  8007 V BluetoothMapService: getConnectedDevices()
08-26 15:43:10.937  1853  2476 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:10.937  6956  6956 D BluetoothHeadset: Proxy object connected
08-26 15:43:10.937  6956  6956 D HeadsetProfile: Bluetooth service connected
08-26 15:43:10.939  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 15:43:10.940  1032  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:10.940  1032  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:10.940  1032  1032 D BluetoothA2dp: Proxy object connected
08-26 15:43:10.941  6956  6971 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 15:43:10.942  1032  1032 D BluetoothHeadset: Proxy object connected
08-26 15:43:10.944  6956  7449 D BluetoothPan: onBluetoothStateChange on: true
08-26 15:43:10.944  6956  7449 D BluetoothPan: onBluetoothStateChange call bindService
,08-26 15:43:10.948  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:10.948  6956  6956 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 15:43:10.948  6956  6956 D PanProfile: Bluetooth service connected
08-26 15:43:10.951  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 15:43:10.952  1032  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 15:43:10.952  1032  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 15:43:10.952  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 15:43:10.953  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:10.958  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 15:43:10.958  1943  2130 D LGBluetoothAPIService: Message: 1
08-26 15:43:10.958  1943  2130 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 15:43:10.959  1943  2130 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-26 15:43:10.959  1943  2130 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 15:43:10.965  1032  1095 D BluetoothManagerService: Message: 40
08-26 15:43:10.965  1032  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 15:43:10.967  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:10.968  7759  7759 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:10.968  7759  7759 D BluetoothMapService: STATE_ON
08-26 15:43:10.972  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 15:43:10.974  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 15:43:10.982  6956  6956 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:10.985  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
08-26 15:43:10.985  7759  7759 V BluetoothPbapService: Pbap Service onCreate
08-26 15:43:10.985  7759  7759 V BluetoothPbapService: Starting PBAP service
08-26 15:43:10.986  7759  7759 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 15:43:10.987  7759  7759 V BluetoothPbapService: Pbap Service onBind
08-26 15:43:10.990  7759  7759 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:10.990  7759  8001 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 15:43:10.990  7759  7759 V BluetoothPbapService: state: 12
08-26 15:43:10.990  7759  8001 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 15:43:10.990  7759  7759 V BluetoothMapService: Handler(): got msg=1
08-26 15:43:10.990  6956  6956 D BluetoothPbap: Proxy object connected
08-26 15:43:10.990  6956  6956 D PbapServerProfile: Bluetooth service connected
08-26 15:43:10.991  7759  7759 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 15:43:10.991  7759  7759 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 15:43:10.991  7759  7759 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:10.991  7759  7759 V BluetoothPbapReceiver: ***********state = 12
08-26 15:43:10.992  7759  8099 D BluetoothMapMasInstance: MAS initSocket()
08-26 15:43:10.993  7759  8099 D BluetoothMapMasInstance:   masId = 00
08-26 15:43:10.993  7759  8099 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 15:43:10.993  7759  8099 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 15:43:10.993  7759  8099 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 15:43:10.993  7759  7759 V BluetoothPbapService: Handler(): got msg=1
08-26 15:43:10.995  1032  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 15:43:10.996  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 15:43:10.996  2229  2229 D c       : Getting all permits...
08-26 15:43:10.997  2229  2229 D a       : Opening database...
08-26 15:43:10.997  7759  7759 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 15:43:10.998  7759  8100 V BluetoothPbapService: Pbap Service initSocket
08-26 15:43:10.998  7759  8099 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:10.998  1032  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:10.999  7759  8100 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:11.000  7759  8100 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 15:43:11.001  7759  8100 V BluetoothPbapService: Succeed to create listening socket 
08-26 15:43:11.001  7759  8001 D BluetoothAdapterProperties: Scan Mode:21
08-26 15:43:11.001  7759  8100 V BluetoothPbapService: Accepting socket connection...
08-26 15:43:11.001  7759  8001 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 15:43:11.001  7759  8099 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 15:43:11.001  7759  8099 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 15:43:11.001  7759  8099 D BluetoothMapMasInstance: Accepting socket connection...
08-26 15:43:11.002  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:11.004  2229  2229 D a       : Opening database auth.proximity.permit_store...
08-26 15:43:11.008  2229  2229 D a       : Closing database...
,08-26 15:43:11.019  6956  6956 D BluetoothPermissionRequest: onReceive
08-26 15:43:11.021  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 15:43:11.022  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 15:43:11.026  7759  7759 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 15:43:11.027  7759  7759 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 15:43:11.034  7759  7759 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 15:43:11.057  7759  7759 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 15:43:11.058  7759  7759 V BtOppService: onCreate
,08-26 15:43:11.063  7759  7759 V BluetoothOppNotification: send message
08-26 15:43:11.069  7759  7759 V BtOppService: Starting RfcommListener
08-26 15:43:11.078  7759  7759 D BluetoothOppPreference: Dumping Names:  
08-26 15:43:11.079  7759  7759 D BluetoothOppPreference: {}
08-26 15:43:11.079  7759  7759 D BluetoothOppPreference: Dumping Channels:  
08-26 15:43:11.079  7759  7759 D BluetoothOppPreference: {}
,08-26 15:43:11.080  7759  7759 V BtOppService: onStartCommand
08-26 15:43:11.081  7759  8108 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 15:43:11.088  7759  7759 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:11.088  7759  7759 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 15:43:11.090  7759  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 15:43:11.092  7759  8105 V BtOppService: Deleted complete outbound shares, number =  0
,08-26 15:43:11.095  7759  8105 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 15:43:11.095  7759  7759 V BluetoothOppNotification: new notify threadi!
08-26 15:43:11.095  7759  8105 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 15:43:11.096  7759  7759 V BluetoothOppNotification: send delay message
08-26 15:43:11.096  7759  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a7a7306 on behalf of 
08-26 15:43:11.097  7759  7759 V BtOppService: start RfcommListener
08-26 15:43:11.097  7759  8109 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 15:43:11.098  7759  8105 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31d2fdc7 on behalf of 
08-26 15:43:11.099  7759  8109 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f12dff4 on behalf of 
08-26 15:43:11.100  7759  8109 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 15:43:11.101  7759  7759 V BtOppService: RfcommListener started
08-26 15:43:11.102  7759  8108 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-26 15:43:11.102  7759  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.,
08-26 15:43:11.103  7759  7759 V BtOppService: ContentObserver received notification
,08-26 15:43:11.104  7759  8109 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-26 15:43:11.104  7759  8110 V BtOppRfcommListener: Starting RFCOMM listener....
,08-26 15:43:11.105  1032  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 15:43:11.106  7759  8110 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:11.107  7759  8110 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-26 15:43:11.107  7759  8110 V BtOppRfcommListener: Started RFCOMM listener....
08-26 15:43:11.107  7759  8110 I BtOppRfcommListener: Accept thread started.
08-26 15:43:11.107  7759  8110 V BtOppRfcommListener: Accepting connection...
08-26 15:43:11.112  7759  8109 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3dbab992 on behalf of 
08-26 15:43:11.112  7759  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15fde31d on behalf of 
08-26 15:43:11.113  7759  8108 V BluetoothOppNotification: update too frequent, put in queue
08-26 15:43:11.113  7759  8109 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 15:43:11.114  7759  8108 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 15:43:11.114  7759  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 15:43:11.135  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
,08-26 15:43:11.135  7759  7759 V BluetoothFtpService: Ftp Service onCreate
08-26 15:43:11.135  7759  7759 I BluetoothFtpService: Ftp Service onCreate
08-26 15:43:11.135  7759  7759 V BluetoothFtpService: Ftp Service onStartCommand
08-26 15:43:11.135  7759  7759 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:11.135  7759  7759 V BluetoothFtpService: Starting Listening on sockets
08-26 15:43:11.136  7759  7759 V BtOppService: ContentObserver received notification
08-26 15:43:11.136  7759  7759 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 15:43:11.136  7759  7759 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 15:43:11.136  7759  7759 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 15:43:11.136  7759  7759 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:11.136  7759  7759 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 15:43:11.136  7759  7759 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 15:43:11.138  7759  7759 V BluetoothFtpService: Handler(): got msg=1
08-26 15:43:11.141  7759  7759 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 15:43:11.141  7759  7759 V BluetoothFtpService: Ftp Service initSocket
08-26 15:43:11.145  1032  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:11.146  7759  7759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:11.147  7759  7759 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-26 15:43:11.147  7759  7759 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 15:43:11.159  7759  8111 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-26 15:43:11.164  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15c7022a
08-26 15:43:11.164  7759  7759 V BluetoothSapService: Sap Service onCreate
08-26 15:43:11.166  7759  7759 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:11.166  7759  7759 V BluetoothSapService: state: 12
08-26 15:43:11.166  7759  7759 V BluetoothSapService: Starting SAP server process
08-26 15:43:11.168  7759  7759 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 15:43:11.159  8112  8112 W sapd    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:11.171  7759  8113 V BluetoothSapService: Sap Service initRfcommSocket
08-26 15:43:11.172  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:11.159  8112  8112 W sapd    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:11.174  7759  8113 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:11.175  7759  8113 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=81
08-26 15:43:11.179  7759  8113 V BluetoothSapService: Succeed to create listening socket 
08-26 15:43:11.179  7759  8113 V BluetoothSapService: Accepting socket connection...
08-26 15:43:11.182  8112  8112 V BT_SAP  : Event pipe created
,08-26 15:43:11.182  8112  8112 V BT_SAP  : create_server_socket qcom.sap.server
08-26 15:43:11.182  8112  8112 V BT_SAP  : created socket fd 6
08-26 15:43:11.277  1032  1048 I art     : Explicit concurrent mark sweep GC freed 21759(1090KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.145ms total 161.019ms
08-26 15:43:11.278  7759  8109 V BluetoothOppNotification: outbound notification was removed.
08-26 15:43:11.278  7759  8109 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-26 15:43:11.279  7759  8109 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22bdebf on behalf of 
,08-26 15:43:11.279  7759  8109 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 15:43:11.280  7759  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1146398c on behalf of 
08-26 15:43:11.280  7759  8108 V BluetoothOppNotification: update too frequent, put in queue
,08-26 15:43:11.281  7759  8108 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 15:43:11.281  7759  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 15:43:11.281  7759  8109 V BluetoothOppNotification: inbound notification was removed.
,08-26 15:43:11.281  7759  8109 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 15:43:11.282  7759  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@eb758d5 on behalf of 
,08-26 15:43:11.283  7759  8108 V BluetoothOppNotification: update too frequent, put in queue
08-26 15:43:11.284  7759  8109 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2adfe8ea on behalf of 
08-26 15:43:11.285  7759  8108 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-26 15:43:11.671  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:11.671  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:11.671  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:11.671  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:11.671  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:11.671  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:11.671  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:11.671  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:11.685  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:11.691  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:11.691  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e4828df added. We now have 8 listener(s)
08-26 15:43:11.691  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:11.699  1032  1890 D WifiServiceImplEx: setWifiEnabled: false pid=6697, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 15:43:11.699  1032  1890 D WifiService: setWifiEnabled: false pid=6697, uid=10118
08-26 15:43:11.699  1032  1890 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 15:43:11.704  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:11.707  1032  1891 D WifiServiceImplEx: setWifiEnabled: true pid=6697, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 15:43:11.708  1032  1891 D WifiService: setWifiEnabled: true pid=6697, uid=10118
08-26 15:43:11.708  1032  1891 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 15:43:11.729  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 15:43:11.729  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 15:43:11.729  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-26 15:43:11.731  1032  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 15:43:11.731  1032  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 15:43:11.734  1032  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 15:43:11.734  1032  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 15:43:11.734  1032  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 15:43:11.734  1032  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 15:43:11.734  1032  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 15:43:11.734  1032  1539 E WifiHW  : unknown target_country: EU , set to default
08-26 15:43:11.734  1032  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 15:43:11.734  1032  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 15:43:11.734  1032  1539 I WifiUtil: gEnableBmps=1
08-26 15:43:12.097  7759  7759 V BluetoothOppNotification: new notify threadi!
08-26 15:43:12.098  7759  7759 V BluetoothOppNotification: send delay message
,08-26 15:43:12.117  7759  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 15:43:12.140  7759  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@949a7db on behalf of 
,08-26 15:43:12.151  7759  8127 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 15:43:12.164  7759  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-26 15:43:12.167  7759  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13e36278 on behalf of 
08-26 15:43:12.167  7759  8127 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 15:43:12.174  7759  8127 V BluetoothOppNotification: outbound notification was removed.
08-26 15:43:12.174  7759  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 15:43:12.175  7759  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20a1ad51 on behalf of 
08-26 15:43:12.175  7759  8127 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 15:43:12.181  7759  8127 V BluetoothOppNotification: inbound notification was removed.
08-26 15:43:12.181  7759  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 15:43:12.182  7759  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@54ba9b6 on behalf of 
08-26 15:43:12.315   313   907 D SoftapController: Softap fwReload - Ok
,08-26 15:43:12.321  1032  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:43:12.321  1032  1095 D Tethering: InitialState.processMessage what=4
08-26 15:43:12.321  1032  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 15:43:12.338  1032  1539 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (599ms)
08-26 15:43:12.348   313   907 D CommandListener: Setting iface cfg
08-26 15:43:12.348   313   907 D CommandListener: Trying to bring down wlan0
,08-26 15:43:12.354   313   907 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:43:12.359  1032  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-26 15:43:12.388  1032  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 15:43:12.388  1032  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 15:43:12.388  1032  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 15:43:12.379  8144  8144 W wpa_supplicant: type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 15:43:12.396  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 15:43:12.379  8144  8144 W wpa_supplicant: type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:12.409  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 15:43:12.414  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 15:43:12.421  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:12.422  1032  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 15:43:12.422  1032  1539 D WifiMonitor: connecting to supplicant
08-26 15:43:12.453  8144  8144 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 15:43:12.472  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 15:43:12.472  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-26 15:43:12.472  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 15:43:12.473  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 15:43:12.475  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-26 15:43:12.481  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 15:43:12.481  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 15:43:12.481  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 15:43:12.481  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 15:43:12.481  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 15:43:12.482  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 15:43:12.487  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 15:43:12.488  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 15:43:12.488  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 15:43:12.488  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 15:43:12.489  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 15:43:12.490  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 15:43:12.490  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 15:43:12.490  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 15:43:12.490  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-26 15:43:12.491  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 15:43:12.491  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 15:43:12.515  8144  8144 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 15:43:12.516  8144  8144 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 15:43:12.537  1032  1047 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8161 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 15:43:12.588  8144  8144 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 15:43:12.631  8144  8144 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 15:43:12.640  1032  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 15:43:12.642  1032  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 15:43:12.643  1032  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 15:43:12.645  1032  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 15:43:12.646  1032  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:43:12.647  1032  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:43:12.648  1032  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 15:43:12.648  1032  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-26 15:43:12.651  8144  8144 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 15:43:12.651  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 15:43:12.651  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 15:43:12.652  1032  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 15:43:12.652  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 15:43:12.652  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 15:43:12.652  1032  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 15:43:12.652  1032  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 15:43:12.652  1032  8182 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 15:43:12.652  1032  8182 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 15:43:12.674  1032  2015 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8185 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 15:43:12.677  1032  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 15:43:12.677  1032  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 15:43:12.677  1032  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 15:43:12.678  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:12.678  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:12.678  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:12.678  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:12.678  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-26 15:43:12.681  1032  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 15:43:12.682  8161  8183 W FormManager: Network not available. Please check & try again.
08-26 15:43:12.682  1032  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-26 15:43:12.682  1032  1539 D WifiConfigStore: Loading config and enabling all networks 
08-26 15:43:12.682  1032  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 15:43:12.683  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 15:43:12.683  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-26 15:43:12.683  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:12.684  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 15:43:12.685  1032  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 15:43:12.694  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:12.694  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:12.694  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:12.694  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:12.694  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:12.694  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:12.694  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:12.694  6697  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:12.698  6697  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:12.699  1032  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 15:43:12.700  8161  8184 V FormManager: Network unavailable.
08-26 15:43:12.709  1032  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 15:43:12.709  7860  7871 E UEI.SmartControl: file observer is disposed!
08-26 15:43:12.709  1032  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 15:43:12.710  1032  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-26 15:43:12.710  1032  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 15:43:12.711  1032  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 15:43:12.711  1032  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 15:43:12.712  1032  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 15:43:12.712  1032  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 15:43:12.712  8161  8184 V FormManager: Network unavailable.
08-26 15:43:12.712  1032  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 15:43:12.712  1032  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 15:43:12.713  1032  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 15:43:12.713  1032  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 15:43:12.713  1032  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 15:43:12.713  1032  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 15:43:12.714  1032  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 15:43:12.714  1032  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 15:43:12.714  1032  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 15:43:12.715  1032  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 15:43:12.715  1032  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 15:43:12.715  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-26 15:43:12.715  1943  2357 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 15:43:12.715  1943  2357 D WfdsService: Set the WFDS Monitor: true
08-26 15:43:12.715  1943  2357 D WfdsMonitor: WfdsMonitorThread create
08-26 15:43:12.715  1032  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 15:43:12.715  1032  1539 D WifiNative-HAL: Setting external_sim to 1
08-26 15:43:12.716  1032  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 15:43:12.716  1943  2357 D WfdsMonitor: WFDS Monitor is created and started
08-26 15:43:12.716  1943  2357 D WfdsService: WiFi: Supplicant connection re-established
08-26 15:43:12.716  7794  7794 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:12.716  1032  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 15:43:12.716  1032  1539 I WifiNative-HAL: startHal
08-26 15:43:12.716  1032  1539 D wifi    : setting scan oui 0xaf731320
08-26 15:43:12.717  1943  8202 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 15:43:12.717  1032  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 15:43:12.717  1032  1539 I WifiNative-HAL: startHal
08-26 15:43:12.717  1032  1539 D wifi    : setting scan oui 0xaf731320
08-26 15:43:12.717  1943  8202 E CtrlSupplicant: Succeed to open control connection
08-26 15:43:12.717  1032  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 15:43:12.717  1943  8202 E CtrlSupplicant: Succeed to open monitor connection
08-26 15:43:12.717  1943  8202 D WfdsMonitor: Supplicant connection established
08-26 15:43:12.717  1943  2357 D WfdsService: Connected to the supplicant for wfds
08-26 15:43:12.718  1032  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 15:43:12.718  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 15:43:12.718  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 15:43:12.719  1032  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 15:43:12.719  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 15:43:12.719  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 15:43:12.720  1032  1539 D WifiNative-wlan0: DRI,VER RXFILTER-STOP: returned true
08-26 15:43:12.720  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 15:43:12.720  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 15:43:12.720  1032  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 15:43:12.720  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 15:43:12.720  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 15:43:12.721  1032  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 15:43:12.721  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 15:43:12.721  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 15:43:12.721  1032  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 15:43:12.721  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 15:43:12.721  8144  8144 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 15:43:12.722  1032  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 15:43:12.722  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 15:43:12.722  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 15:43:12.722  1032  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 15:43:12.723  1032  1539 E WifiNative: : [142,061,526 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 15:43:12.723  1032  1539 D WifiNative-wlan0: doBoolean: RECONNECT
,08-26 15:43:12.724  1032  1539 D WifiNative-wlan0: RECONNECT: returned true
08-26 15:43:12.724  1032  1539 D WifiNative-wlan0: doString: [STATUS]
08-26 15:43:12.724  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 15:43:12.724  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 15:43:12.725  1032  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 15:43:12.725  1032  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 15:43:12.725  1032  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 15:43:12.726  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.727   313   907 D CommandListener: Setting iface cfg
08-26 15:43:12.727   313   907 D CommandListener: Trying to bring up p2p0
08-26 15:43:12.727  1032  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 15:43:12.727  1032  1537 D LGWifiP2pService: P2pEnablingState
08-26 15:43:12.727  1032  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.727  1032  1537 D LGWifiP2pService: P2p socket connection successful
08-26 15:43:12.727  1032  1537 D LGWifiP2pService: P2pEnabledState
08-26 15:43:12.729  1032  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 15:43:12.729  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 15:43:12.729  1032  1032 D RttService: SCAN_AVAILABLE : 3
08-26 15:43:12.729  1032  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.729  1032  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 15:43:12.729  1032  1556 I WifiNative-HAL: startHal
08-26 15:43:12.729  1032  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf731320
08-26 15:43:12.729  1032  1556 D wifi    : failed to get capabilities : -3
08-26 15:43:12.729  1032  1556 E WifiScanningService: could not get scan capabilities
08-26 15:43:12.730  1032  1557 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.730  1032  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 15:43:12.730  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 15:43:12.730  1943  1943 D WfdsService: WifiP2pState is changed : true
08-26 15:43:12.730  1032  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 15:43:12.730  1943  2357 D WfdsService: Receive the WFDS_ENABLE Method
08-26 15:43:12.730  1943  2357 D WfdsService: Set the WFDS Monitor: true
08-26 15:43:12.730  1943  2357 D WfdsService: Connected to the supplicant for wfds
08-26 15:43:12.730  1943  2357 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 15:43:12.730  1032  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 15:43:12.731  8144  8144 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 15:43:12.731  1943  2357 D WfdsService: selectPreferredScanChannel [36]
08-26 15:43:12.731  1943  2357 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 15:43:12.731  1032  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 15:43:12.731  1032  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 15:43:12.731  1032  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 15:43:12.731  1032  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-26 15:43:12.732  1032  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 15:43:12.732  1032  1537 D LGWifiP2pService: before postfix = G3
08-26 15:43:12.732  1032  1537 D WifiServerServic,eExt: postfix byte check : 2
08-26 15:43:12.732  1032  1537 D LGWifiP2pService: after postfix = G3
08-26 15:43:12.732  1032  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 15:43:12.732  1032  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 15:43:12.732  1032  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 15:43:12.732  1032  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 15:43:12.732  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=142071  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 15:43:12.732  1032  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 15:43:12.733  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 15:43:12.733  1032  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 15:43:12.733  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 15:43:12.733  1943  1943 D WfdsService: isConnected: false
08-26 15:43:12.733  1032  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 15:43:12.733  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-26 15:43:12.733  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=142072  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 15:43:12.734  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 15:43:12.734  1032  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 15:43:12.734  1032  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 15:43:12.734  1032  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 15:43:12.734  1032  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 15:43:12.735  8144  8144 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-26 15:43:12.735  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:12.735  1032  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 15:43:12.735  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:12.735  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 15:43:12.735  1032  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 15:43:12.736  1032  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 15:43:12.736  1032  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 15:43:12.736  8144  8144 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 15:43:12.736  1032  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 15:43:12.736  1032  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 15:43:12.736  1032  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 15:43:12.737  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:12.737  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:43:12.737  1032  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 15:43:12.737  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 15:43:12.737  1032  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 15:43:12.737  1032  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 15:43:12.737  1032  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 15:43:12.737  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:12.738  1032  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 15:43:12.738  1032  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 15:43:12.739  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 15:43:12.739  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 15:43:12.739  1943  1943 D WfdsService: Update P2p Interface State: 3
08-26 15:43:12.738  1032  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 15:43:12.739  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 15:43:12.741  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:12.741  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:12.741  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:12.741  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:12.741  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:12.741  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:12.741  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:12.741  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:43:12.742  1032  1924 I ActivityManager: Killing 7231:com.android.chrome/u0a57 (adj 15): empty #17
08-26 15:43:12.742  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:12.746  6697  6804 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 15:43:12.746  6697  6804 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 15:43:12.747  1032  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 15:43:12.748  1032  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 15:43:12.749  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 15:43:12.749  8144  8144 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:43:12.749  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 15:43:12.749  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:43:12.749  1032  8182 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:43:12.749  1032  8182 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:43:12.750  6697  6804 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@346497c9 Bundle[{}]
08-26 15:43:12.750  8144  8144 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 15:43:12.750  8144  8144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.750  1032  8182 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:43:12.750  1032  8182 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.750  1943  8202 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:43:12.750  1032  8182 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.750  6697  6804 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 15:43:12.750  1032  8182 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.750  1032  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 15:43:12.750  6697  6804 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 15:43:12.750  1032  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 15:43:12.751  8144  8144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.751  6697  6804 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 15:43:12.751  1032  8182 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:43:12.751  1032  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 15:43:12.751  1032  8182 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.751  1032  8182 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.751  1032  8182 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.751  1032  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 15:43:12.751  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 15:43:12.751  1943  8202 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:43:12.751  6697  6804 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 15:43:12.751  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 15:43:12.751  8144  8144 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 15:43:12.751  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 15:43:12.751  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 15:43:12.751  1032  8182 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 15:43:12.751  1032  8182 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 1,5:43:12.751  6697  6804 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 15:43:12.752  6697  6804 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 15:43:12.752  1032  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 15:43:12.752  1032  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 15:43:12.752  1032  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 15:43:12.752  1032  1539 D WifiNative-wlan0: doBoolean: SCAN
08-26 15:43:12.752  1032  1539 D WifiNative-wlan0: SCAN: returned false
08-26 15:43:12.753  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=142091  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 15:43:12.756  6697  6804 I System.out: Running OutgoingSocketThread
08-26 15:43:12.757  6697  8204 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 856)
08-26 15:43:12.758  6697  8204 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49299
08-26 15:43:12.758  6697  8204 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 15:43:12.770  8185  8185 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 15:43:12.789  1032  1537 D LGWifiP2pService: InactiveState
08-26 15:43:12.790  1032  1537 D LGWifiP2pService: InactiveState{ when=-52ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.790  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-52ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.790  1032  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-26 15:43:12.791  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-26 15:43:12.791  1032  1997 W libprocessgroup: failed to open /acct/uid_10057/pid_7231/cgroup.procs: No such file or directory
08-26 15:43:12.791  8144  8144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:43:12.791  1032  8182 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 15:43:12.791  1032  8182 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:43:12.791  1032  8182 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:43:12.791  1032  8182 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 15:43:12.792  8144  8144 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 15:43:12.792  8144  8144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.792  1943  8202 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 15:43:12.792  1943  8202 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:43:12.792  1032  8182 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:43:12.792  1032  8182 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.792  1032  8182 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.792  1032  8182 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.792  8144  8144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 15:43:12.792  1943  8202 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:43:12.793  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:12.793  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:43:12.796  1032  8182 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 15:43:12.796  1032  8182 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.796  1032  8182 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.796  1032  8182 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 15:43:12.797  1032  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
,08-26 15:43:12.797  1032  1537 D LGWifiP2pService: InactiveState{ when=-47ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.797  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-47ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.797  1032  1537 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.797  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:12.797  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:12.797  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 15:43:12.798  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=142136  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 15:43:12.798  1032  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 15:43:12.798  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:12.798  1032  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-26 15:43:12.797  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.799  1032  1537 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.799  1032  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 15:43:12.799  1032  1537 D LGWifiP2pService: InactiveState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.799  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.799  1032  1537 D LGWifiP2pService: DefaultState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.799  1032  1537 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.799  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.799  1032  1537 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.799  1032  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 15:43:12.799  1032  1537 D LGWifiP2pService: InactiveState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:43:12.799  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.799  1943  2357 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 15:43:12.799  1032  1537 D LGWifiP2pService: DefaultState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.799  1032  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 15:43:12.800  1032  1032 E WifiServerServiceExt: No p2p device connected
08-26 15:43:12.800  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 15:43:12.801  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:43:12.801  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 15:43:12.805  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:43:12.805  1032  1047 I ActivityManager: Killing 7255:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-26 15:43:12.843  1032  2052 W libprocessgroup: failed to open /acct/uid_10062/pid_7255/cgroup.procs: No such file or directory
,08-26 15:43:12.863  8185  8185 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 15:43:12.873  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:43:12.882  8161  8208 W FormManager: Network not available. Please check & try again.
,08-26 15:43:12.887  8161  8209 V FormManager: Network unavailable.
08-26 15:43:12.888  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 15:43:12.900  8161  8209 V FormManager: Network unavailable.
,08-26 15:43:12.912  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 15:43:12.912  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 15:43:12.917  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 15:43:12.921  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 15:43:12.926  4356  8210 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 15:43:12.933  4356  8211 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 15:43:12.933  4356  8211 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 15:43:12.991  1032  1996 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8212 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 15:43:13.124  8212  8212 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 15:43:13.125  8212  8212 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 15:43:13.139  8212  8212 V [BNRBootReceiver]: Boot Receiver Return
08-26 15:43:13.144  8212  8212 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-26 15:43:13.195  1032  1996 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8233 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 15:43:13.196  1032  1996 I ActivityManager: Killing 7276:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-26 15:43:13.240  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 15:43:13.240  1032  8182 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-26 15:43:13.240  8144  8144 E wpa_supplicant: USIM:  scard_init function
08-26 15:43:13.240  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 15:43:13.240  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-26 15:43:13.240  1032  8182 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 15:43:13.240  8144  8144 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 15:43:13.240  1032  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 15:43:13.242  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 15:43:13.242  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 15:43:13.242  1032  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 15:43:13.243  1032  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 15:43:13.243  1032  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 15:43:13.243  1032  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 15:43:13.270  1032  1048 W libprocessgroup: failed to open /acct/uid_10085/pid_7276/cgroup.procs: No such file or directory
,08-26 15:43:13.283  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=142621  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 15:43:13.285  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=142624  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 15:43:13.287  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:13.287  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 15:43:13.290  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.290  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.290  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 15:43:13.290  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:43:13.290  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 15:43:13.291  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.312  8233  8233 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 15:43:13.345  8233  8233 D PluginManager: init()
,08-26 15:43:13.511  8144  8144 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 15:43:13.511  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 15:43:13.512  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 15:43:13.512  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 15:43:13.512  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-26 15:43:13.513  1032  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 15:43:13.515  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=142854  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 15:43:13.517  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=142855  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-26 15:43:13.518  1032  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142857
08-26 15:43:13.523  1032  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142862
08-26 15:43:13.523  1032  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142862
08-26 15:43:13.524  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142863
08-26 15:43:13.524  1032  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142863
08-26 15:43:13.525  1032  1539 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:43:13.525  1032  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:43:13.526  1032  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:43:13.526  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:43:13.526  1032  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 15:43:13.527  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:43:13.527  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 15:43:13.527  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 15:43:13.527  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 15:43:13.528  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=142866  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 15:43:13.530  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:13.530  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:43:13.531  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.531  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.531  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 15:43:13.531  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.534  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.534  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.534  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-26 15:43:13.535  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=142873  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 15:43:13.535  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:43:13.535  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 15:43:13.551  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 15:43:13.551  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:43:13.552  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.606  8144  8144 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 15:43:13.606  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 15:43:13.606  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 15:43:13.606  8144  8144 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 15:43:13.607  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 15:43:13.607  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 15:43:13.607  1032  8182 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 15:43:13.607  1032  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=142946  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 15:43:13.607  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 15:43:13.607  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 15:43:13.607  1032  8182 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 15:43:13.607  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=142946  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 15:43:13.608  1032  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=142947
08-26 15:43:13.608  1032  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=142947
,08-26 15:43:13.609  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:43:13.609  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-26 15:43:13.610  1032  1539 D WifiNative-wlan0: doString: [STATUS]
08-26 15:43:13.610  1032  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 15:43:13.611  1032  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 15:43:13.612  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 15:43:13.615  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 15:43:13.617  1032  8182 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 15:43:13.617  1032  8182 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 15:43:13.621  1032  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 15:43:13.621  1032  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 15:43:13.626  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:13.626  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 15:43:13.630  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.632  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.632  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.632  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 15:43:13.635  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.635  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.635  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 15:43:13.636  1032  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 15:43:13.636  1032  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:43:13.636  1032  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 15:43:13.637  1032  1545 D ConnectivityService: Got NetworkAgent Messenger
08-26 15:43:13.637  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 15:43:13.637  1032  1545 D ConnectivityService: NetworkAgent connected
08-26 15:43:13.637  1032  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 15:43:13.637  1032  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 15:43:13.638  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:13.638  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:43:13.639  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 15:43:13.645  1032  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 15:43:13.645  1032  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:43:13.645  1032  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 15:43:13.645  1032  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 15:43:13.645  1032  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 15:43:13.650  1032  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 15:43:13.652   313   907 D CommandListener: Setting iface cfg
08-26 15:43:13.655  1032  1539 E WifiStateMachine: Start Dhcp Watchdog 3
08-26 15:43:13.655  1032  8251 D DhcpStateMachine: StoppedState
08-26 15:43:13.655  1032  8251 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:13.655  1032  8251 D DhcpStateMachine: WaitBeforeStartState
08-26 15:43:13.655  1032  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=142994  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 15:43:13.655  1032  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=142994  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 15:43:13.656  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=142994  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 15:43:13.656  1032  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=142995  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 15:43:13.656  1032  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=142995  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 15:43:13.657  1032  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=142995  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-26 15:43:13.657  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14494] from screen [on:0 period:-954788871] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 15:43:13.658  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-954788870] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 15:43:13.658  1032  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 15:43:13.661  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.661  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.661  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.662  1032  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.662  1032  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-26 15:43:13.662  1032  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.662  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.662  1032  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.663  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 15:43:13.663  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=133,0,0
08-26 15:43:13.663  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=133,0,0
08-26 15:43:13.663  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 15:43:13.663  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 15:43:13.663  1032  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 15:43:13.663  1032  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 15:43:13.664  1032  1539 D WifiNative-wlan0: SET ps 0: returned true
08-26 15:43:13.664  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 15:43:13.664  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 15:43:13.664  1032  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 15:43:13.664  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@66fa5be target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:13.664  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@66fa5be target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:13.664  1032  8251 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:13.664  1032  8251 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 15:43:13.665  1032  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 15:43:13.665  1032  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 15:43:13.665  1032  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 15:43:13.665   313   907 D CommandListener: Setting iface cfg
08-26 15:43:13.665   313   907 D CommandListener: Trying to bring up wlan0
08-26 15:43:13.666  1032  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 15:43:13.667  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 15:43:13.667  1032  1032 D WifiServ,erServiceExt: setSupplicantStateCOMPLETED
08-26 15:43:13.668  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.668  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.669  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-26 15:43:13.669  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 15:43:13.669  1032  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.670  1032  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.670  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.670  1032  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 15:43:13.672  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 15:43:13.672  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 15:43:13.673  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 15:43:13.673  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 15:43:13.673  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:13.673  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:13.673  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 15:43:13.673  1032  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 15:43:13.673  1032  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 15:43:13.674  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 15:43:13.674  1032  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 15:43:13.674  1032  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 15:43:13.690  1032  1539 D WifiNative-wlan0: SET ps 1: returned true
,08-26 15:43:13.690  1032  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 15:43:13.691  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 15:43:13.691  1032  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 15:43:13.692  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 15:43:13.692  1032  1545 D ConnectivityService: ignoring duplicate network state non-change
08-26 15:43:13.694  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:13.695  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 15:43:13.696  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.696  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.696  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.696  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 15:43:13.697  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 15:43:13.697  1032  1545 D ConnectivityService: Adding iface wlan0 to network 102
08-26 15:43:13.703  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.703  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.703  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 15:43:13.705  1032  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 15:43:13.708  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 15:43:13.711  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 15:43:13.712  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.712  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.712  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 15:43:13.714  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 15:43:13.717  1032  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 15:43:13.717  1032  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 15:43:13.718  1032  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 15:43:13.719   313   907 E Netd    : netlink response contains error (File exists)
08-26 15:43:13.720  1032  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 15:43:13.720  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.720  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:13.720  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 15:43:13.720  1032  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 15:43:13.720  1032  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-26 15:43:13.720  1032  1545 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 15:43:13.726  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 15:43:13.726  1032  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 15:43:13.726  1032  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 15:43:13.726  1032  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 15:43:13.726  1032  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:43:13.726  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:43:13.727  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 15:43:13.727  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:43:13.727  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 15:43:13.727  1032  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-26 15:43:13.727  1032  1545 D ConnectivityService:    accepting network in place of null
08-26 15:43:13.727  1032  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:43:13.727  1032  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:13.727  1032  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 15:43:13.727  1032  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]:, EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:13.727  1032  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 15:43:13.729  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:43:13.729  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 15:43:13.729  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:13.729  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 15:43:13.731   313  8255 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 15:43:13.733  1032  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:43:13.733  1032  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:43:13.734  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.735  1032  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 15:43:13.735  1032  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 15:43:13.735  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 15:43:13.735  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:13.735  1032  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 15:43:13.735  1032  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 15:43:13.735  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:13.736  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 15:43:13.736  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.738  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:13.738  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 15:43:13.739  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 15:43:13.739  1032  1545 D ConnectivityService: validation of new default Network = false
08-26 15:43:13.739  1032  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 15:43:13.739  1032  1545 D DSQN    : enableDataServiceNotify 
08-26 15:43:13.739  1032  1545 D DSQN    : start dsqn bin
08-26 15:43:13.740  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 15:43:13.740  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 av,ailable info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 15:43:13.740  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 15:43:13.740  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 15:43:13.746  1032  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 15:43:13.746  1032  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 15:43:13.746  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:43:13.746  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:43:13.746  1032  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:43:13.747  1603  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 15:43:13.729  8256  8256 W dsqn    : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:13.729  8256  8256 W dsqn    : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:13.759  6697  6804 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 857)
08-26 15:43:13.759  6697  6804 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 857)
08-26 15:43:13.760  8256  8256 E DSQN    : DSQN ssw
,08-26 15:43:13.765  6697  6804 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 862)
08-26 15:43:13.766  6697  6804 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 15:43:13.766  6697  6804 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 863)
08-26 15:43:13.769  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:13.769  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ca7892c added. We now have 2 listener(s)
08-26 15:43:13.769  1032  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:13.771  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 15:43:13.771  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:13.771  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:13.771  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:13.771  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1328fff5 added. We now have 9 listener(s)
08-26 15:43:13.771  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:13.772  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:13.776  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:13.776  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 15:43:13.777  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.777  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.778  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:13.778  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:13.778  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:13.778  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:13.778  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:13.778  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:13.778  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:43:13.778  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:43:13.780  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:43:13.780  6697  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:13.780  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:13.780  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cb073fb added. We now have 3 listener(s)
08-26 15:43:13.780  1032  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:13.782  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 15:43:13.782  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:13.782  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:13.782  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:13.782  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99a0c18 added. We now have 10 listener(s)
08-26 15:43:13.782  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:13.783  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:13.783  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:13.783  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:13.783  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:13.783  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.783  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:13.783  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:13.783  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ca7892c removed from the list
08-26 15:43:13.783  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.783  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1328fff5 removed from the list
08-26 15:43:13.783  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:13.783  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:13.783  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.784  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.784  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:13.788  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:13.789  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:13.789  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:13.790  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.790  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1328fff5 not in the list
08-26 15:43:13.790  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.790  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.791  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:13.791  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:13.791  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.791  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99a0c18 removed from the list
08-26 15:43:13.791  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:13.791  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:13.791  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.791  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:13.791  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cb073fb removed from the list
08-26 15:43:13.792  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:13.792  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38d6a671 added. We now have 2 listener(s)
08-26 15:43:13.792  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:13.794  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 15:43:13.794  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:13.794  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:13.795  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:13.795  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6817c56 added. We now have 9 listener(s)
08-26 15:43:13.795  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:13.795  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:43:13.797  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:13.801  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:13.801  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:13.801  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:13.801  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:13.801  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:13.801  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:13.801  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:43:13.801  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:43:13.803  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:13.803  6697  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:13.804  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:13.804  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e2fd1c4 added. We now have 3 listener(s)
08-26 15:43:13.804  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:13.806  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:13.807  6697  66,97 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:13.807  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 15:43:13.807  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:13.807  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:13.807  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:13.808  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dde38ad added. We now have 10 listener(s)
08-26 15:43:13.808  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:13.808  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:13.808  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:43:13.808  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:13.808  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:13.808  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:43:13.810  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 15:43:13.810  1032  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 15:43:13.816  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 15:43:13.816  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 15:43:13.817  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:43:13.818   313  8255 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-26 15:43:13.819  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:13.825  7860  7975 D UEI.SmartControl: Internal timer expired: 3
08-26 15:43:13.825  7860  7975 D UEI.SmartControl: unbind internal service
,08-26 15:43:13.827  7860  7860 D UEI.SmartControl: Service.onUnbind: IControl
08-26 15:43:13.827  7860  7860 D UEI.SmartControl: Service.onDestroy
08-26 15:43:13.827  7860  7860 D UEI.SmartControl: Lock is in USE false
08-26 15:43:13.828  6697  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 15:43:13.828  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:13.827  7860  7860 D UEI.SmartControl: unbind internal service
08-26 15:43:13.828  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:13.829  7860  7860 D serial_port: close(fd = 24)
08-26 15:43:13.830  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:13.830  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:13.830  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:13.830  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:13.830  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.830  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:13.830  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:13.830  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38d6a671 removed from the list
08-26 15:43:13.830  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.830  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6817c56 removed from the list
08-26 15:43:13.830  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:13.830  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.831  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.831  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.832  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:13.832  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:13.832  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.832  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6817c56 not in the list
08-26 15:43:13.832  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.832  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.832  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:13.833  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:43:13.833  6697  6804 D org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:13.833  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:13.833  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.833  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dde38ad removed from the list
08-26 15:43:13.833  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:13.833  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.833  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.833  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:13.833  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e2fd1c4 removed from the list
08-26 15:43:13.833  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:13.833  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133a4630 added. We now have 2 listener(s)
08-26 15:43:13.834  1032  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:13.834  7860  7860 I UEI.SmartControl: Serial port is closed.
08-26 15:43:13.834  7860  7860 I UEI.SmartControl: Serial port is closed.
08-26 15:43:13.834  7860  7860 D UEI.SmartControl: Blaster closed
08-26 15:43:13.834  7860  7860 D UEI.SmartControl: Shut down QS...
08-26 15:43:13.834  7860  7860 D UEI.SmartControl: Stopping QS lib
,08-26 15:43:13.834  7860  7860 D UEI.SmartControl: QS lib stop result = true
08-26 15:43:13.834  7860  7860 D UEI.SmartControl: Stopped QS lib
08-26 15:43:13.834  7860  7860 D UEI.SmartControl: QS shutdown complete
08-26 15:43:13.836  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 15:43:13.836  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:13.836  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:13.836  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 15:43:13.836  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a52b2a9 added. We now have 9 listener(s)
08-26 15:43:13.836  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:13.836  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:43:13.839  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:13.849  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:13.849  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:13.849  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:13.849  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:13.849  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:13.849  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:13.849  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:43:13.849  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:43:13.851  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:43:13.851  6697  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:13.851  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:13.851  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@103307cf added. We now have 3 listener(s)
08-26 15:43:13.856   313  8255 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-26 15:43:13.859  1032  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:13.863  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 15:43:13.863  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:13.863  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:13.863  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:13.863  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:13.863  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b35955c added. We now have 10 listener(s)
,08-26 15:43:13.863  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:13.863  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 15:43:13.865  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:13.866  1032  8251 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 15:43:13.866  1032  8251 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 15:43:13.866  1032  8251 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 15:43:13.867  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:13.868  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:43:13.868  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:13.868  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:13.868  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:43:13.859  8265  8265 W dhcpcd  : type=1400 audit(0.0:197): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:13.859  8265  8265 W dhcpcd  : type=1400 audit(0.0:198): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6502 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 15:43:13.872  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 15:43:13.872  1032  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:13.876  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:13.876  8265  8265 I dhcpcd  : version 5.5.6 starting
08-26 15:43:13.878  8265  8265 E dhcpcd  : get_duid: m
08-26 15:43:13.878  8265  8265 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 15:43:13.878  8265  8265 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 15:43:13.879  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 15:43:13.882  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:43:13.883  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:13.884  6697  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 15:43:13.884  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:13.884  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:13.884  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:13.884  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:13.884  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.884  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:13.885  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:13.885  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133a4630 removed from the list
08-26 15:43:13.885  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.885  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a52b2a9 removed from the list
08-26 15:43:13.885  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:13.885  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.885  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.885  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.886  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:13.886  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:13.886  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.886  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a52b2a9 not in the list
08-26 15:43:13.886  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.886  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.887  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:13.887  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:43:13.8,87  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:13.887  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:13.887  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.887  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b35955c removed from the list
08-26 15:43:13.887  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:13.887  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.887  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.887  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:13.888  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@103307cf removed from the list
08-26 15:43:13.888  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:13.889  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b8251eb added. We now have 2 listener(s)
,08-26 15:43:13.889  8233  8233 W ExternalStrings: load override strings
08-26 15:43:13.889  8233  8233 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 15:43:13.889  8233  8233 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 15:43:13.891  8233  8233 D StatusProvider: onCreate
08-26 15:43:13.892  1032  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:13.893   313   906 D LGDataListener: argv[0]=dsqncommand
08-26 15:43:13.893   313   906 D LGDataListener: argv[1]=wlan0
08-26 15:43:13.893   313   906 D LGDataListener: argv[2]=1
08-26 15:43:13.893   313   906 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 15:43:13.894  1032  1093 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 15:43:13.894  1032  1093 D DSQN    : start to monitor internet connection
08-26 15:43:13.899  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 15:43:13.900  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:13.900  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:13.900  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:13.900  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3234ab48 added. We now have 9 listener(s)
08-26 15:43:13.900  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:13.900  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:13.903  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:13.906  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:13.906  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:13.906  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:13.906  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:13.906  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:13.906  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:13.906  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:43:13.906  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:43:13.908  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:13.908  6697  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:13.909  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:13.909  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa706 added. We now have 3 listener(s)
08-26 15:43:13.909  1032  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:13.910  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:13.911  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 15:43:13.911  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:13.911  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:13.911  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:13.912  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:13.912  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@363221c7 added. We now have 10 listener(s)
08-26 15:43:13.912  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:13.912  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:13.912  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:43:13.912  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:13.912  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:13.912  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:43:13.915  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress:, Constructing...
,08-26 15:43:13.915  1032  1625 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:13.919  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 15:43:13.920  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 15:43:13.921  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:43:13.922  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:13.923  1032  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 13:43:13 GMT], X-Android-Received-Millis=[1472218993922], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472218993895]}
08-26 15:43:13.923  1032  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 15:43:13.923  1032  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 15:43:13.923  1032  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-26 15:43:13.923  1032  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 15:43:13.924  1032  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:43:13.924  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:43:13.924  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 15:43:13.924  1032  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-26 15:43:13.924  1032  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 15:43:13.924  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:43:13.924  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:43:13.924  1032  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:43:13.924  6697  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 15:43:13.924  1032  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:43:13.925  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 15:43:13.925  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:43:13.925  1603  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 15:43:13.925  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 15:43:13.925  1032  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:43:13.925  1032  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:43:13.92,7  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:13.927  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:13.927  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:13.928  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:13.928  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.928  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:13.928  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:13.928  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b8251eb removed from the list
08-26 15:43:13.928  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.928  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3234ab48 removed from the list
08-26 15:43:13.928  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:13.928  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.929  8265  8265 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 15:43:13.929  8265  8265 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 15:43:13.929  8265  8265 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 15:43:13.929  8265  8265 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 15:43:13.929  8265  8265 D dhcpcd  : wlan0: sending REQUEST (xid 0x6ed803d2), next in 3.73 seconds
,08-26 15:43:13.932  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.932  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.934  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:13.934  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:13.934  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.934  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3234ab48 not in the list
08-26 15:43:13.934  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.934  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.936  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:13.937  6697  6804 D BluetoothLeScanner: could not find callback wrapper
08-26 15:43:13.938  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:13.938  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:13.938  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.938  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@363221c7 removed from the list
08-26 15:43:13.938  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:13.938  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.938  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.938  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:13.938  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa706 removed from the list
08-26 15:43:13.940  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:13.940  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76f2d92 added. We now have 2 listener(s)
08-26 15:43:13.940  1032  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 15:43:13.945  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 15:43:13.946  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 15:43:13.946  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:13.946  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:13.946  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:13.946  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b251363 added. We now have 9 listener(s)
08-26 15:43:13.946  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:13.946  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.946  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:43:13.947  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 15:43:13.948  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:13.952  6697  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:13.952  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:13.952  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:43:13.952  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:13.952  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:13.952  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:13.952  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:43:13.952  6697  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:43:13.954  8233  8233 V Signer  : override build config not found
08-26 15:43:13.954  8233  8233 D Signer  : value of property debug is false
08-26 15:43:13.954  6697  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:13.954  6697  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:13.956  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:13.956  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e609819 added. We now have 3 listener(s)
08-26 15:43:13.956  1032  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 15:43:13.956  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:13.958  6697  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:13.959  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 15:43:13.959  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:13.959  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:13.959  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:13.959  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ce90de added. We now have 10 listener(s)
08-26 15:43:13.959  6697  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:13.959  6697  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:13.959  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:13.960  6697  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:13.960  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:13.960  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.960  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:13.960  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:13.960  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76f2d92 removed from the list
08-26 15:43:13.960  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.960  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b251363 removed from the list
08-26 15:43:13.960  6697  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:13.960  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.963  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.,bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.963  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:13.966  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:13.966  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:13.966  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.966  6697  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b251363 not in the list
08-26 15:43:13.966  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.966  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.966  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:13.966  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:13.966  6697  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:13.966  6697  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ce90de removed from the list
08-26 15:43:13.967  6697  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:13.967  6697  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:13.967  6697  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:13.967  6697  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:13.967  6697  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e609819 removed from the list
08-26 15:43:13.967  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 15:43:13.968  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 15:43:13.968  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 15:43:13.968  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:13.968  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 15:43:13.968  6697  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:13.970  8265  8265 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-26 15:43:13.976  6697  8275 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: My test thread name)
08-26 15:43:13.977  6697  8275 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: My test thread name)
08-26 15:43:13.977  6697  8275 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 15:43:13.979  6697  8276 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 872, name: My test thread name)
,08-26 15:43:13.979  6697  8276 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 872, thread name: My test thread name)
08-26 15:43:13.979  6697  8276 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 872, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 15:43:13.982  6697  6804 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 15:43:13.982  6697  6804 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 15:43:13.982  6697  6804 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 15:43:13.982  6697  6804 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 15:43:13.982  6697  6804 D com.test.thalitest.ThaliTestRunner: Total duration: 22951 ms
08-26 15:43:13.983  6697  6804 I jxcore-log: *Native tests were executed*
08-26 15:43:13.983  6697  6804 I jxcore-log: 
08-26 15:43:13.983  6697  6804 I jxcore-log: Total number of executed tests:  80
08-26 15:43:13.983  6697  6804 I jxcore-log: 
08-26 15:43:13.983  6697  6804 I jxcore-log: Number of passed tests:  80
08-26 15:43:13.983  6697  6804 I jxcore-log: 
08-26 15:43:13.984  6697  6804 I jxcore-log: Number of failed tests:  0
08-26 15:43:13.984  6697  6804 I jxcore-log: 
08-26 15:43:13.984  6697  6804 I jxcore-log: Number of ignored tests:  0
08-26 15:43:13.984  6697  6804 I jxcore-log: 
08-26 15:43:13.984  6697  6804 I jxcore-log: Total duration:  22951
08-26 15:43:13.984  6697  6804 I jxcore-log: 
08-26 15:43:13.984  6697  6804 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 15:43:13.984  6697  6804 I jxcore-log: 
08-26 15:43:13.986  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-26 15:43:13.986  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-26 15:43:13.987  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-26 15:43:13.987  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-26 15:43:13.987  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-26 15:43:13.987  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-26 15:43:13.987  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-26 15:43:13.988  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-26 15:43:13.988  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-26 15:43:13.988  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-26 15:43:13.988  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:13.988  6697  6804 I jxcore-log: 
08-26 15:43:13.988  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-26 15:43:13.988  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-26 15:43:13.989  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-26 15:43:13.996  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:13.996  6697  6804 I jxcore-log: 
,08-26 15:43:13.997  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:13.997  6697  6804 I jxcore-log: 
08-26 15:43:13.998  8233  8233 V LGMDMManager: Create singleton instance
08-26 15:43:13.999  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:13.999  6697  6804 I jxcore-log: 
08-26 15:43:14.001  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.001  6697  6804 I jxcore-log: 
08-26 15:43:14.003  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.003  6697  6804 I jxcore-log: 
08-26 15:43:14.005  6697  6697 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 15:43:14.005  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.005  6697  6804 I jxcore-log: 
08-26 15:43:14.007  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.007  6697  6804 I jxcore-log: 
08-26 15:43:14.008  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.008  6697  6804 I jxcore-log: 
08-26 15:43:14.008  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.008  6697  6804 I jxcore-log: 
,08-26 15:43:14.009  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.009  6697  6804 I jxcore-log: 
08-26 15:43:14.011  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:14.011  6697  6804 I jxcore-log: 
08-26 15:43:14.012  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.012  6697  6804 I jxcore-log: 
08-26 15:43:14.012  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.012  6697  6804 I jxcore-log: 
08-26 15:43:14.013  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.013  6697  6804 I jxcore-log: 
08-26 15:43:14.014  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.014  6697  6804 I jxcore-log: 
08-26 15:43:14.014  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.014  6697  6804 I jxcore-log: 
08-26 15:43:14.015  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.015  6697  6804 I jxcore-log: 
08-26 15:43:14.015  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.015  6697  6804 I jxcore-log: 
08-26 15:43:14.016  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.016  6697  6804 I jxcore-log: 
08-26 15:43:14.017  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.017  6697  6804 I jxcore-log: 
08-26 15:43:14.017  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.017  6697  6804 I jxcore-log: 
08-26 15:43:14.018  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.018  6697  6804 I jxcore-log: 
08-26 15:43:14.019  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.019  6697  6804 I jxcore-log: 
08-26 15:43:14.019  8265  8265 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 15:43:14.019  8265  8265 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 15:43:14.019  8265  8265 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 15:43:14.020  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.020  6697  6804 I jxcore-log: 
08-26 15:43:14.020  8265  8265 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 15:43:14.020  8265  8265 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 15:43:14.020  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15,:43:14.020  6697  6804 I jxcore-log: 
08-26 15:43:14.020  8265  8265 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 15:43:14.021  8265  8265 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 15:43:14.021  8265  8265 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 15:43:14.021  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.021  6697  6804 I jxcore-log: 
08-26 15:43:14.021  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.021  6697  6804 I jxcore-log: 
,08-26 15:43:14.022  6697  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.022  6697  6804 I jxcore-log: 
08-26 15:43:14.055  8233  8233 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-26 15:43:14.112  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 15:43:14.125  8233  8289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 15:43:14.130  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 15:43:14.134  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:43:14.178  1032  1960 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8299 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 15:43:14.180  1032  1960 I ActivityManager: Killing 7323:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-26 15:43:14.267  8284  8284 D AndroidRuntime: 
08-26 15:43:14.267  8284  8284 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 15:43:14.269  1032  8251 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 15:43:14.269  8284  8284 D AndroidRuntime: CheckJNI is OFF
08-26 15:43:14.269  1032  8251 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 15:43:14.269  1032  8251 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 15:43:14.270  1032  8251 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 15:43:14.270  1032  8251 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 15:43:14.270  1032  8251 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 15:43:14.270  1032  8251 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 15:43:14.270  1032  8251 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 15:43:14.270  1032  8251 D DhcpStateMachine: RunningState
,08-26 15:43:14.286  8233  8288 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 15:43:14.406  8284  8284 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 15:43:14.422  1032  1882 W libprocessgroup: failed to open /acct/uid_10093/pid_7323/cgroup.procs: No such file or directory
,08-26 15:43:14.431  1032  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-26 15:43:14.432  1032  1091 I ActivityManager: Killing 6697:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-26 15:43:14.472  1032  1575 I WindowState: WIN DEATH: Window{3fd0058b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 15:43:14.473  1032  1544 D WifiService: Client connection lost with reason: 4
08-26 15:43:14.482  1032  1575 D InputDispatcher: Window went away: Window{3fd0058b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 15:43:14.532  8299  8299 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 15:43:14.650  1032  1091 I ActivityManager:   Force finishing activity ActivityRecord{380e55ab u0 com.test.thalitest/.MainActivity t6}
,08-26 15:43:14.682   335   387 E GBMv2   : DFP En is all cleared set to be enabled
08-26 15:43:14.684  1032  1048 W ActivityManager: Spurious death for ProcessRecord{38eedca3 6697:com.test.thalitest/u0a118}, curProc for 6697: null
08-26 15:43:14.689  1032  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-26 15:43:14.702  8299  8299 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 15:43:14.711  1032  1101 I ActivityManager:   Force finishing activity ActivityRecord{380e55ab u0 com.test.thalitest/.MainActivity t6 f}
08-26 15:43:14.711  1032  1101 W ActivityManager: Duplicate finish request for ActivityRecord{380e55ab u0 com.test.thalitest/.MainActivity t6 f}
,08-26 15:43:14.730  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-26 15:43:14.731  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-26 15:43:14.731  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{fd033fa co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 15:43:14.732  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-26 15:43:14.741  1943  4008 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-26 15:43:14.741  1943  4008 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18d87dab co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-26 15:43:14.742  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-26 15:43:14.744  2035  2129 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-26 15:43:14.762  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-26 15:43:14.771  1998  1998 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-26 15:43:14.772  3844  3844 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-26 15:43:14.772  2501  2671 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 15:43:14.774  7759  7759 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-26 15:43:14.774  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-26 15:43:14.778  4547  4547 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-26 15:43:14.778  4547  4547 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 15:43:14.778  4547  4547 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 15:43:14.778  4547  4547 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-26 15:43:14.778  4547  4547 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:43:14.778  4547  4547 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:43:14.778  4547  4547 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:43:14.778  4547  4547 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 15:43:14.779  4547  4547 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:14.779  4547  4547 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:14.779  4547  4547 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 15:43:14.779  4547  4547 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 15:43:14.794  4649  4649 I art     : Explicit concurrent mark sweep GC freed 8209(470KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 668us total 74.133ms
,08-26 15:43:14.802  1032  1477 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 15:43:14.832  1032  1961 V SIM_STK : Menu title from STK is T-Mobile
,08-26 15:43:14.853  8299  8299 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-26 15:43:14.854  8299  8299 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 15:43:14.854  8299  8299 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 15:43:14.854  8299  8299 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 15:43:14.855  8299  8299 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 15:43:14.856  8299  8299 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 15:43:14.874  8233  8288 D LgDataFeature: LgDataFeature() Constructor: none
08-26 15:43:14.874  8233  8288 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 15:43:14.880  1032  1032 D administrator: Handling package changes for user 0
08-26 15:43:14.883  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-26 15:43:14.884  1907  1907 D ActionManagerService: notifyUserLog: 1000003
08-26 15:43:14.884  3844  4519 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-26 15:43:14.884  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-26 15:43:14.886  8299  8299 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 15:43:14.906  1603  1657 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 15:43:14.906  1603  1657 D KeyguardModel: createShortcutInfo...
08-26 15:43:14.906  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-26 15:43:14.906  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-26 15:43:14.907  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-26 15:43:14.910  1603  1657 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 15:43:14.910  1603  1657 D KeyguardModel: createShortcutInfo...
08-26 15:43:14.910  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-26 15:43:14.911  1907  1907 D ActionManagerService: notifyUserLog: 1000004
08-26 15:43:14.911  3844  4519 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-26 15:43:14.912  3844  3860 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , display: false
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , animation: false }
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , display: false
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , animation: false }
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , create_time: 1472216588858
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , display: false
08-26 15:43:14.916  2035  2035 I GBoardWebViewUtils: , animation: false }
08-26 15:43:14.921  2035  8349 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-26 15:43:14.922  1603  1657 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 15:43:14.922  1603  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:43:14.922  1603  1657 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 15:43:14.923  1603  1657 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 15:43:14.925  1603  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:43:14.925  1603  1657 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 15:43:14.929  1603  1657 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 15:43:14.929  1603  1657 D KeyguardModel: createShortcutInfo...
08-26 15:43:14.935  1870  1870 D SplitUIManager: split_name #11 / not available #0
,08-26 15:43:14.936  1870  1870 D SplitUIService: removed split : 
08-26 15:43:14.941  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 15:43:14.941  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-26 15:43:14.941  1603  1657 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 15:43:14.942  1603  1657 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 15:43:14.943  1603  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:43:14.943  1603  1657 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 15:43:14.957  1603  1657 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 15:43:14.957  1603  1657 D KeyguardModel: createShortcutInfo...
,08-26 15:43:14.960  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 15:43:14.960  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-26 15:43:14.969  1032  1937 V SIM_STK : Menu title from STK is T-Mobile
08-26 15:43:14.969  1032  1937 V SIM_STK : Menu title from STK is T-Mobile
08-26 15:43:14.970  1603  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:43:14.970  1603  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 15:43:14.970  1603  1657 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 15:43:14.971  1603  1657 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 15:43:15.009  1870  1870 D SplitUIManager: split_name #11 / not available #0
,08-26 15:43:15.009  1870  1870 I SplitUIService: split app #11
08-26 15:43:15.017  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:43:15.018  1603  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:43:15.018  1603  1657 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 15:43:15.023  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:43:15.037  1603  1657 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 15:43:15.037  1603  1657 D KeyguardModel: createShortcutInfo...
,08-26 15:43:15.038  1032  2015 V SIM_STK : Menu title from STK is T-Mobile
08-26 15:43:15.041  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-26 15:43:15.041  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 15:43:15.041  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-26 15:43:15.041  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 15:43:15.042  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 15:43:15.043  1032  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-26 15:43:15.047  1603  1657 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 15:43:15.047  1603  1657 D KeyguardModel: createShortcutInfo...
08-26 15:43:15.049  1603  1657 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 15:43:15.049  1603  1657 D KeyguardModel: createShortcutInfo...
08-26 15:43:15.049  1603  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:43:15.050  1603  1657 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 15:43:15.050  1603  1657 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 15:43:15.050  1603  1657 D KeyguardModel: createShortcutInfo...
08-26 15:43:15.051  1603  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:43:15.051  1603  1657 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 15:43:15.052  1603  1657 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 15:43:15.052  1603  1657 D KeyguardModel: createShortcutInfo...
,08-26 15:43:15.056  1032  1101 I art     : Explicit concurrent mark sweep GC freed 75718(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 4.214ms total 320.308ms
08-26 15:43:15.058  1603  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:43:15.058  1603  1657 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 15:43:15.063  1603  1657 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 15:43:15.063  1603  1657 D KeyguardModel: createShortcutInfo...
08-26 15:43:15.075  8284  8284 D AndroidRuntime: Shutting down VM
,08-26 15:43:15.125  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-26 15:43:15.128  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 15:43:15.130  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-26 15:43:15.131  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-26 15:43:15.132  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-26 15:43:15.133  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-26 15:43:15.134  1032  1101 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8354 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 15:43:15.136  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-26 15:43:15.136  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 15:43:15.137  1032  1960 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 15:43:15.137  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-26 15:43:15.137  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 15:43:15.137  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 15:43:15.137  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 15:43:15.137  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 15:43:15.137  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 15:43:15.137  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 15:43:15.137  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 15:43:15.137  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 15:43:15.138  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 15:43:15.138  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 15:43:15.140  8299  8299 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 15:43:15.143  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:43:15.145  8233  8289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 15:43:15.149  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-26 15:43:15.151  8299  8299 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-26 15:43:15.152  8299  8299 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 15:43:15.153  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 15:43:15.154  1032  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1345b926 u0 com.lge.launcher2/.Launcher t5} time:144505
08-26 15:43:15.155  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-26 15:43:15.156  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 15:43:15.166  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 15:43:15.172  2035  2173 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 15:43:15.172  2035  2173 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-26 15:43:15.180  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-26 15:43:15.181  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 15:43:15.181  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 15:43:15.184  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:43:15.185  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:43:15.189  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-26 15:43:15.190  2594  2594 D [Concierge]Service: onStartCommand(). Type : 8
08-26 15:43:15.191  2594  2594 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-26 15:43:15.191  2594  2594 D [Concierge]Service: Update widget ID : 11
08-26 15:43:15.192  8299  8299 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 15:43:15.194  2035  2035 D [Concierge]WidgetView: change position of spinner
,08-26 15:43:15.196  2594  2594 D [Concierge]Service: onStartCommand(). Type : 0
08-26 15:43:15.197  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1472218995196
08-26 15:43:15.199  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 15:43:15.203  6956  6956 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 15:43:15.205  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:43:15.205  8233  8289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 15:43:15.209  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:43:15.215  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:43:15.218  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:43:15.219  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:43:15.219  1032  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 15:43:15.219  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 15:43:15.220  1032  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 15:43:15.220  1032  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 15:43:15.220  1032  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 15:43:15.220  1032  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 15:43:15.221  1032  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 15:43:15.221  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-26 15:43:15.221  1032  1545 D ConnectivityService: identical MTU - not setting
08-26 15:43:15.221  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 15:43:15.221  1032  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 15:43:15.221  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:43:15.221  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:43:15.221  1032  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 15:43:15.223  1603  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 15:43:15.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 15:43:15.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 15:43:15.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 15:43:15.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 15:43:15.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 15:43:15.224  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 15:43:15.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 15:43:15.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 15:43:15.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 15:43:15.224  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 15:43:15.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 15:43:15.225  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 15:43:15.225  8233  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-26 15:43:15.227  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:43:15.228  8233  8289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 15:43:15.228  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 1615314
08-26 15:43:15.229  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-26 15:43:15.229  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 15:43:15.231  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@107a23b4
08-26 15:43:15.231  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-26 15:43:15.232  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 15:43:15.232  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 15:43:15.235  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLo,adBroadcast: android.net.wifi.STATE_CHANGE
08-26 15:43:15.237  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-26 15:43:15.238  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-26 15:43:15.238  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 15:43:15.238  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:43:15.238  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472218879192, New one : 1472218995196
08-26 15:43:15.238  2035  2035 D [Concierge]WidgetView: Unregister all receivers
08-26 15:43:15.238  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 15:43:15.239  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 15:43:15.240  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-26 15:43:15.241  1032  1891 I ActivityManager: Killing 7348:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-26 15:43:15.241  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-26 15:43:15.242  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-26 15:43:15.243  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-26 15:43:15.244  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-26 15:43:15.246  8233  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-26 15:43:15.250  8233  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-26 15:43:15.251  8233  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 15:43:15.251  8233  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 15:43:15.251  8233  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-26 15:43:15.251  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 15:43:15.252  8233  8288 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-26 15:43:15.252  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 15:43:15.255  8233  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-26 15:43:15.256  8233  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-26 15:43:15.280  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-26 15:43:15.294  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-26 15:43:15.294  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-26 15:43:15.295  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 15:43:15.305  1032  1625 W libprocessgroup: failed to open /acct/uid_10005/pid_7348/cgroup.procs: No such file or directory
08-26 15:43:15.305  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:43:15.305  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:43:15.306  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 15:43:15.309  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:43:15.309  8233  8289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 15:43:15.313  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 15:43:15.315  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8dff5af time:144666
08-26 15:43:15.318  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 15:43:15.323  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:43:15.323  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:43:15.324  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 15:43:15.325  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:43:15.325  8233  8289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 15:43:15.330  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:43:15.339  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:43:15.344  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 15:43:15.344  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:43:15.344  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 15:43:15.345  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:43:15.346  8233  8289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 15:43:15.351  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:43:15.356  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:43:15.361  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:43:15.362  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:43:15.362  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 15:43:15.367  8233  8289 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 15:43:15.369  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:43:15.376  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:43:15.380  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:43:15.385  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:43:15.385  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:43:15.388  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 15:43:15.396  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 15:43:15.397  8233  8233 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.ai(Unknown Source)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.mcafee.wsstorage.h.Y(Unknown Source)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.wavesecure.core.WSAndroidSystemIntentReceiver.a(Unknown Source)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.mcafee.app.u.onReceive(Unknown Source)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 15:43:15.397  8233  8233 E SQLiteDatabase: 	at com.an,droid.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 15:43:15.416  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 15:43:15.420  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:43:15.424  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:43:15.425  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 15:43:15.426  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 15:43:15.428  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:43:15.431  8185  8185 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 15:43:15.433  8185  8185 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:43:15.437  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 15:43:15.441  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 15:43:15.444  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 15:43:15.444  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 15:43:15.445  8299  8299 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 15:43:15.449  1032  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
08-26 15:43:15.465  8299  8299 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 15:43:15.465  8299  8299 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-26 15:43:15.467  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 15:43:15.471  8185  8185 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 15:43:15.471  8185  8185 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 15:43:15.473  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 15:43:15.474  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-26 15:43:15.477  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null

```
