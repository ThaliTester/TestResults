#### Test 82337235c6facd5_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-24 14:31:09.101  6627  6627 D DocsApplication: Installing DEX configuration.
08-24 14:31:09.120  6627  6627 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-24 14:31:09.123  6627  6627 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{11f4e7de com.google.android.apps.docs}
08-24 14:31:09.139  1817  1817 I art     : Explicit concurrent mark sweep GC freed 30054(1898KB) AllocSpace objects, 11(176KB) LOS objects, 51% free, 29MB/61MB, paused 2.237ms total 53.335ms
08-24 14:31:09.140   322   322 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
08-24 14:31:09.140   322   322 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
08-24 14:31:09.140   322   322 I rmt_storage: wakelock acquired: 1, error no: 42
08-24 14:31:09.140   322   908 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
08-24 14:31:09.165  6627  6627 D TAG     : onCreate()
08-24 14:31:09.178  5082  6626 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 303 ms] updated apps [took 303 ms] 
08-24 14:31:09.207   322   908 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
08-24 14:31:09.207   322   908 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
08-24 14:31:09.207   322   908 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
08-24 14:31:09.207   322   908 I rmt_storage: 
08-24 14:31:09.209   322   322 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
08-24 14:31:09.209   907   917 E Diag_Lib: [IMS_FATAL]| 3347 | 917 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-24 14:31:09.215  6627  6627 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-24 14:31:09.637   339   419 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-24 14:31:09.641  3277  6668 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-24 14:31:10.205  1817  5243 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-24 14:31:10.248  6669  6669 D AndroidRuntime: 
08-24 14:31:10.248  6669  6669 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 14:31:10.252  6669  6669 D AndroidRuntime: CheckJNI is OFF
08-24 14:31:10.323  1817  5243 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-24 14:31:10.357  1817  5243 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-24 14:31:10.408  6669  6669 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 14:31:10.414  1036  1051 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 14:31:10.436  1969  1984 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-24 14:31:10.439  1036  1051 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-24 14:31:10.441  1036  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{1b1ede5b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 14:31:10.441  1036  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{1b1ede5b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 14:31:10.442  1036  1051 D WindowStateEx: AppWindowTokenEx init.. 
08-24 14:31:10.444   357   373 E GBMv2   : DFP En is all cleared set to be enabled
08-24 14:31:10.493  1036  1051 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6702 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 14:31:10.495  6669  6669 D AndroidRuntime: Shutting down VM
08-24 14:31:10.592  1969  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-24 14:31:10.593  1969  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{230c65ba co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 14:31:10.594  1969  2579 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-24 14:31:10.595  1969  2579 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b222c6b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 14:31:10.678  6702  6702 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-24 14:31:10.754  6702  6702 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-24 14:31:10.762  6702  6702 I LibraryLoader: Loading: webviewchromium
08-24 14:31:10.764  6702  6702 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2856-2859)
08-24 14:31:10.764  6702  6702 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:31:10.780  6702  6702 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {30e91578}
,08-24 14:31:10.781  6702  6702 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:31:10.781  6702  6702 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 14:31:10.790  6702  6702 I BrowserStartupController: Initializing chromium process, renderers=0
08-24 14:31:10.791  6702  6702 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 14:31:10.807  6702  6702 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-24 14:31:10.807  6702  6702 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-24 14:31:10.808  6702  6702 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-24 14:31:10.821   329  1386 V AudioPolicyService: registerClient() client 0xb1427060, uid 10118
,08-24 14:31:10.827  1036  1097 D BluetoothManagerService: Message: 20
08-24 14:31:10.827  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37ea500d:true
08-24 14:31:10.830  6702  6702 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 14:31:10.830  6702  6702 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 14:31:10.830  6702  6702 I Adreno-EGL: Build Date: 12/12/14 금
08-24 14:31:10.830  6702  6702 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 14:31:10.830  6702  6702 I Adreno-EGL: Remote Branch: 
08-24 14:31:10.830  6702  6702 I Adreno-EGL: Local Patches: 
08-24 14:31:10.830  6702  6702 I Adreno-EGL: Reconstruct Branch: 
08-24 14:31:10.933  6702  6731 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-24 14:31:10.936  6702  6702 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-24 14:31:10.951  6702  6702 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:31:10.955  6702  6702 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 14:31:10.958  6702  6702 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-24 14:31:10.960  6702  6702 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-24 14:31:10.960  6702  6702 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-24 14:31:10.971  6702  6702 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-24 14:31:10.975  6627  6627 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:10.975  6627  6627 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 14:31:10.977  6702  6702 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 14:31:10.977  6702  6702 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:31:11.016  6702  6746 D OpenGLRenderer: Render dirty regions requested: true
08-24 14:31:11.017  6702  6746 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 14:31:11.021  6702  6746 D OpenGLRenderer: Enabling debug mode 0
,08-24 14:31:11.028  6702  6702 D Atlas   : Validating map...
08-24 14:31:11.031  1036  1915 D SplitWindow: check instance of lgWin Window{1e7fb71f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 14:31:11.089  6702  6744 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:11.090  6702  6744 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:31:11.135  6627  6627 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-24 14:31:11.177  1036  1596 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6766 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-24 14:31:11.205  1036  1098 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +614ms (total +761ms)
08-24 14:31:11.205  1036  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{94696f8 u0 com.test.thalitest/.MainActivity t6} time:103300
08-24 14:31:11.205  6702  6702 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@27103aa7 time:103300
08-24 14:31:11.236  6766  6766 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-24 14:31:11.248  6766  6766 I LockScreenSettings: New app installed broadcast received ..
,08-24 14:31:11.251  6766  6766 I LockScreenSettings: Number of installed packages  1
08-24 14:31:11.298  1036  2039 V SIM_STK : Menu title from STK is T-Mobile
,08-24 14:31:11.311  6702  6702 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-24 14:31:11.351  6702  6702 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-24 14:31:11.351  6702  6702 I chromium: 
,08-24 14:31:11.371  1036  1596 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6791 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 14:31:11.379  1036  1596 I ActivityManager: Killing 5671:com.lge.bnr/1000 (adj 15): empty #17
08-24 14:31:11.389   361   361 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 17.691ms
,08-24 14:31:11.400  6702  6744 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-24 14:31:11.400  6702  6744 I chromium: 
,08-24 14:31:11.404   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 14.944ms
08-24 14:31:11.418   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 13.310ms
,08-24 14:31:11.456  1036  2052 W libprocessgroup: failed to open /acct/uid_1000/pid_5671/cgroup.procs: No such file or directory
,08-24 14:31:11.501  6791  6791 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
,08-24 14:31:11.501  6791  6791 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-24 14:31:11.540  6702  6808 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435128832
,08-24 14:31:11.553  1036  2019 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6809 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-24 14:31:11.556  1036  2019 I ActivityManager: Killing 6236:com.google.android.gm/u0a64 (adj 15): empty #17
08-24 14:31:11.568  6702  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 14:31:11.568  6702  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 14:31:11.568  6702  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 14:31:11.568  6702  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 14:31:11.568  6702  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 14:31:11.569  6702  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@160c4ebb added. We now have 1 listener(s)
,08-24 14:31:11.663  1036  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 14:31:11.664  1036  2039 W libprocessgroup: failed to open /acct/uid_10064/pid_6236/cgroup.procs: No such file or directory
,08-24 14:31:11.671  6702  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-24 14:31:11.674  6702  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 14:31:11.679  6702  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:11.680  6702  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 14:31:11.697  6702  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d82616 added. We now have 1 listener(s)
,08-24 14:31:11.698  6702  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:11.705  1036  1545 D WifiService: New client listening to asynchronous messages
08-24 14:31:11.709  6702  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:31:11.710  6702  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 14:31:11.710  6702  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 14:31:11.710  6702  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 14:31:11.710  6702  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 14:31:11.716  6702  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:11.717  1036  1912 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:11.719  6702  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-24 14:31:11.731  6702  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-24 14:31:11.731  6702  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:11.731  6702  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:11.731  6702  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:11.731  6702  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:11.731  6702  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:11.731  6702  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:11.731  6702  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:11.731  6702  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:11.731  6702  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 14:31:11.731  6702  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:11.732  6702  6808 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 14:31:11.737  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:11.739  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:11.745   357   375 E GBMv2   : DFP En is all cleared set to be enabled
08-24 14:31:11.745   357   375 E GBMv2   : Set value is all cleared set the max
08-24 14:31:11.746   357   375 I GBMv2   : DFP Enabled. Ignore VFP set
,08-24 14:31:11.755  6809  6809 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-24 14:31:11.775  6702  6702 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 14:31:11.778  6809  6809 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 14:31:11.781  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-24 14:31:11.808  1036  2019 I ActivityManager: Killing 6032:com.google.android.talk/u0a72 (adj 15): empty #17
,08-24 14:31:11.887  1036  1967 W libprocessgroup: failed to open /acct/uid_10072/pid_6032/cgroup.procs: No such file or directory
,08-24 14:31:12.546  6702  6828 W jxcore-log: Initializing JXcore engine
,08-24 14:31:12.546  6702  6828 W jxcore-log: JXcore engine is ready
08-24 14:31:12.613  6828  6828 W Thread-782: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8377]" dev="sockfs" ino=8377 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-24 14:31:12.613  6828  6828 W Thread-782: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-24 14:31:12.613  6828  6828 W Thread-782: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10432]" dev="sockfs" ino=10432 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 14:31:12.613  6828  6828 W Thread-782: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-24 14:31:12.613  6828  6828 W Thread-782: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30655]" dev="sockfs" ino=30655 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-24 14:31:12.647  6702  6828 W jxcore-log: Starting JXcore engine
,08-24 14:31:12.800  6702  6828 W jxcore-log: Platform android
08-24 14:31:12.800  6702  6828 W jxcore-log: 
08-24 14:31:12.801  6702  6828 W jxcore-log: Process ARCH arm
08-24 14:31:12.801  6702  6828 W jxcore-log: 
,08-24 14:31:13.207  6702  6828 I jxcore-log: JXcore Cordova bridge is ready!
08-24 14:31:13.207  6702  6828 I jxcore-log: 
08-24 14:31:13.208  6702  6828 W jxcore-log: JXcore engine is started
,08-24 14:31:13.217  6702  6808 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-24 14:31:13.220  6702  6702 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-24 14:31:15.169  6627  6627 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-24 14:31:15.195  1036  1051 I ActivityManager: Killing 5810:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-24 14:31:15.219  5786  5786 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-24 14:31:15.219  5786  5786 W System.err: android.os.DeadObjectException
08-24 14:31:15.220  5786  5786 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 14:31:15.220  5786  5786 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 14:31:15.220  5786  5786 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-24 14:31:15.220  5786  5786 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-24 14:31:15.220  5786  5786 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-24 14:31:15.220  5786  5786 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-24 14:31:15.220  5786  5786 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:31:15.220  5786  5786 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:31:15.220  5786  5786 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:31:15.220  5786  5786 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 14:31:15.220  5786  5786 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:15.220  5786  5786 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:15.220  5786  5786 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 14:31:15.220  5786  5786 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 14:31:15.221  5786  5786 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-24 14:31:15.221  5786  5786 W System.err: android.os.DeadObjectException
08-24 14:31:15.221  5786  5786 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 14:31:15.221  5786  5786 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 14:31:15.221  5786  5786 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-24 14:31:15.221  5786  5786 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-24 14:31:15.221  5786  5786 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-24 14:31:15.221  5786  5786 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-24 14:31:15.221  5786  5786 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:31:15.221  5786  5786 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:31:15.221  5786  5786 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:31:15.221  5786  5786 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 14:31:15.221  5786  5786 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:15.221  5786  5786 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:15.222  5786  5786 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 14:31:15.222  5786  5786 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 14:31:15.222  5786  5786 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-24 14:31:15.222  5786  5786 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-24 14:31:15.409  1036  1051 E libprocessgroup: failed to kill 1 processes for processgroup 5810
,08-24 14:31:15.558  1036  1967 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-24 14:31:15.565  5786  5786 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-24 14:31:15.565  5786  5786 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-24 14:31:15.625  1036  1949 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6874 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 14:31:15.626  5786  5786 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-24 14:31:15.729  6874  6874 D UEI.SmartControl: Quickset Services start...
,08-24 14:31:15.732  6874  6874 I UEI.SmartControl: Manufacture = LGE
08-24 14:31:15.733  6874  6874 D UEI.SmartControl: Id = LGNevo
08-24 14:31:15.734  6874  6874 D UEI.SmartControl: File observer start...
08-24 14:31:15.736  6874  6874 E UEI.SmartControl: IR Port is disabled: false
08-24 14:31:15.737  6874  6874 D UEI.SmartControl: Starting file observer...
08-24 14:31:15.737  6874  6874 D UEI.SmartControl: Extracting JNI libs...
08-24 14:31:15.738  6874  6874 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-24 14:31:15.836  6874  6874 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-24 14:31:15.836  6874  6874 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-24 14:31:15.836  6874  6874 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-24 14:31:15.866  6874  6874 I UEI.SmartControl: --- Selecting new region: 6
,08-24 14:31:15.867  6874  6874 I UEI.SmartControl: Model = LG-D855
,08-24 14:31:15.869  6874  6874 D UEI.SmartControl: QS Service created
08-24 14:31:15.879  6874  6874 I UEI.SmartControl: Service initServices...
,08-24 14:31:15.882  6874  6874 D UEI.SmartControl: QS start get config
,08-24 14:31:15.916  6874  6874 D UEI.SmartControl: Loading JNI Libs...
,08-24 14:31:16.066  6627  6747 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-24 14:31:16.264  6874  6874 I UEI.SmartControl: Supports setup maps: true
,08-24 14:31:16.276  6874  6874 D UEI.SmartControl: QS start statue = true Error code = 0
,08-24 14:31:16.276  6874  6874 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-24 14:31:16.276  6874  6874 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-24 14:31:16.276  6874  6874 I UEI.SmartControl: ### init IR Blaster...
08-24 14:31:16.282  6874  6874 D serial_port: Configuring serial port
08-24 14:31:16.286  6874  6874 E UEI.SmartControl: UEIBLaster setting for 616
08-24 14:31:16.286  6874  6874 I UEI.SmartControl: Setting serial record hearder size = 2
08-24 14:31:16.287  6874  6874 I UEI.SmartControl: configuring settings for MAXQ616
,08-24 14:31:16.287  6874  6874 I UEI.SmartControl: Get version...
08-24 14:31:16.303  6874  6903 D UEI.SmartControl: serial port data available: 21
,08-24 14:31:16.330  6874  6874 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-24 14:31:16.330  6874  6874 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-24 14:31:16.330  6874  6874 I UEI.SmartControl: QS saving settings...
08-24 14:31:16.331  6874  6874 D UEI.SmartControl: IR Blaster version: 25672567
,08-24 14:31:16.349  6874  6903 D UEI.SmartControl: serial port data available: 4
,08-24 14:31:16.388  6874  6906 I UEI.SmartControl: Device manager: loading config....
,08-24 14:31:16.391  6874  6906 D UEI.SmartControl: ----------- loading internal config...
08-24 14:31:16.392  6874  6874 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-24 14:31:16.395  6874  6874 E UEI.SmartControl: Services init done
08-24 14:31:16.395  6874  6874 D UEI.SmartControl: QS Service init finished
08-24 14:31:16.397  6874  6874 D UEI.SmartControl: QS Service version name: 2.1.91
08-24 14:31:16.397  6874  6874 D UEI.SmartControl: QS Service version code: 201091
08-24 14:31:16.399  6874  6874 D UEI.SmartControl: Service requested: Control
08-24 14:31:16.404  6874  6906 E UEI.SmartControl: Loading SETTINGS...
,08-24 14:31:16.405  6874  6874 D UEI.SmartControl: Request IControl service: devices are loaded...
08-24 14:31:16.408  5786  5786 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-24 14:31:16.415  6874  6889 I UEI.SmartControl: ------ IControl API: 11
08-24 14:31:16.417  1036  2019 I ActivityManager: Killing 5786:com.lge.qremote/u0a112 (adj 15): empty #17
,08-24 14:31:16.419  6874  6889 I UEI.SmartControl: Registering callback...
08-24 14:31:16.422  6874  6906 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-24 14:31:16.426  6874  6905 I UEI.SmartControl: Notify AllClients services are ready: 0
08-24 14:31:16.427  6874  6905 D UEI.SmartControl: -----service ready thread exits
08-24 14:31:16.584  1036  1968 W libprocessgroup: failed to open /acct/uid_10112/pid_5786/cgroup.procs: No such file or directory
08-24 14:31:16.585  6874  6874 D UEI.SmartControl: Internal service binding...
,08-24 14:31:20.188  2800  2800 I MusicWidget: mDelayedStopHandler : unbind
,08-24 14:31:20.197  2222  2222 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
,08-24 14:31:20.197  2222  2222 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-24 14:31:20.198  2222  2222 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-24 14:31:20.202  2222  2222 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-24 14:31:20.203  2222  2222 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
,08-24 14:31:20.207  2222  2222 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-24 14:31:20.208  2222  2222 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-24 14:31:20.209  2222  2222 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-24 14:31:20.210  1036  2052 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1d8a83c1com.lge.music.MediaPlaybackService$5@30651766
08-24 14:31:20.211  2222  2222 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-24 14:31:20.211  2222  2222 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-24 14:31:20.212  2222  2222 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-24 14:31:20.213  2222  2222 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-24 14:31:20.213  2222  2222 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@8561124
08-24 14:31:20.214  2222  2222 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-24 14:31:20.215  2222  2222 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-24 14:31:20.215  2222  2222 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-24 14:31:20.216  2222  2222 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,08-24 14:31:20.218  2222  2222 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-24 14:31:20.219  2222  2222 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-24 14:31:20.219  2222  2222 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-24 14:31:20.220  2222  2222 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-24 14:31:20.221  2222  2222 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-24 14:31:20.221  2222  2222 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-24 14:31:20.222  2222  2222 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-24 14:31:20.224  2222  2222 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-24 14:31:20.224  2222  2222 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-24 14:31:20.224  2222  2222 V MediaPlayer[Native]: reset
08-24 14:31:20.232  2222  2222 V MediaPlayer[Native]: setListener
08-24 14:31:20.232  2222  2222 V MediaPlayer[Native]: disconnect
08-24 14:31:20.232  2222  2222 V MediaPlayer[Native]: destructor
,08-24 14:31:20.234   329   329 V AudioFlinger: releasing 18 from 2222 for -1
08-24 14:31:20.234   329   329 V AudioFlinger:  decremented refcount to 0
08-24 14:31:20.234   329   329 V AudioFlinger: purging stale effects
08-24 14:31:20.235  2222  2222 V MediaPlayer[Native]: disconnect
08-24 14:31:20.236  2222  2222 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-24 14:31:20.237  2222  2222 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-24 14:31:20.238  2222  2222 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-24 14:31:20.239  2222  2222 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-24 14:31:20.239  2222  2222 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-24 14:31:20.239  2222  2222 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-24 14:31:20.239  2222  2222 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 655375015
08-24 14:31:20.240  2222  2222 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 655375015
08-24 14:31:20.253  2222  2222 I SmartShareClient: [SmartShareManagerClient] terminate service: 2222/MediaPlaybackService/434349034
,08-24 14:31:20.259  2222  2222 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-24 14:31:20.259  2222  2222 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@17f20b54
08-24 14:31:20.261  2222  2222 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-24 14:31:20.262  2222  2222 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-24 14:31:20.263  2222  2222 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-24 14:31:20.263  2222  2222 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-24 14:31:20.265  1036  1949 I ActivityManager: Killing 5723:com.android.calendar/u0a13 (adj 15): empty #17
08-24 14:31:20.267  2222  2222 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29996
,08-24 14:31:20.348  1036  1596 W libprocessgroup: failed to open /acct/uid_10013/pid_5723/cgroup.procs: No such file or directory
,08-24 14:31:21.395  6874  6907 D UEI.SmartControl: Internal timer expired: 1
08-24 14:31:21.396  6874  6907 D UEI.SmartControl: unbind internal service
,08-24 14:31:21.454  6874  6874 D UEI.SmartControl: Service.onUnbind: IControl
,08-24 14:31:21.457  6874  6874 D UEI.SmartControl: Service.onDestroy
08-24 14:31:21.457  6874  6874 D UEI.SmartControl: Lock is in USE false
08-24 14:31:21.457  6874  6874 D UEI.SmartControl: unbind internal service
08-24 14:31:21.458  6874  6874 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@8561124
08-24 14:31:21.458  6874  6874 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-24 14:31:21.458  6874  6874 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-24 14:31:21.458  6874  6874 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-24 14:31:21.458  6874  6874 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-24 14:31:21.458  6874  6874 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-24 14:31:21.458  6874  6874 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-24 14:31:21.458  6874  6874 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-24 14:31:21.458  6874  6874 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-24 14:31:21.459  6874  6874 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:21.459  6874  6874 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:31:21.459  6874  6874 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 14:31:21.459  6874  6874 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:21.459  6874  6874 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:21.459  6874  6874 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 14:31:21.459  6874  6874 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 14:31:21.459  6874  6874 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@8561124
08-24 14:31:21.461  6874  6874 D serial_port: close(fd = 25)
08-24 14:31:21.464  6874  6874 I UEI.SmartControl: Serial port is closed.
08-24 14:31:21.464  6874  6874 I UEI.SmartControl: Serial port is closed.
08-24 14:31:21.464  6874  6874 D UEI.SmartControl: Blaster closed
08-24 14:31:21.465  6874  6874 D UEI.SmartControl: Shut down QS...
08-24 14:31:21.465  6874  6874 D UEI.SmartControl: Stopping QS lib
08-24 14:31:21.465  6874  6874 D UEI.SmartControl: QS lib stop result = true
08-24 14:31:21.465  6874  6874 D UEI.SmartControl: Stopped QS lib
08-24 14:31:21.466  6874  6874 D UEI.SmartControl: Stopped file observer...
08-24 14:31:21.466  6874  6874 D UEI.SmartControl: QS shutdown complete
08-24 14:31:23.284  1036  1093 I ActivityManager: Waited long enough for: ServiceRecord{dfbda03 u0 com.google.android.gms/.wearable.service.WearableService}
,08-24 14:31:25.738  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 14:31:25.738  6702  6828 I jxcore-log: 
,08-24 14:31:27.524  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 14:31:27.524  6702  6828 I jxcore-log: 
,08-24 14:31:27.556  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 14:31:27.556  6702  6828 I jxcore-log: 
,08-24 14:31:27.575  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 14:31:27.575  6702  6828 I jxcore-log: 
,08-24 14:31:27.599  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 14:31:27.599  6702  6828 I jxcore-log: 
,08-24 14:31:27.603  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 14:31:27.603  6702  6828 I jxcore-log: 
,08-24 14:31:30.277  2222  2222 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19986
,08-24 14:31:30.391  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 14:31:30.391  6702  6828 I jxcore-log: 
,08-24 14:31:30.394  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 14:31:30.394  6702  6828 I jxcore-log: 
,08-24 14:31:30.400  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:30.400  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:30.400  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:30.400  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:30.400  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:30.400  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:30.400  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:30.400  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:31:30.403  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:30.405  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 14:31:30.405  6702  6828 I jxcore-log: 
08-24 14:31:30.408  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 14:31:30.408  6702  6828 I jxcore-log: 
,08-24 14:31:32.161  1036  1388 V AlarmManager: RTC_WAKEUP set : Alarm{39565da3 type 0 when 1472041883841 com.android.vending} when 1472041883841
,08-24 14:31:32.217  4966  6929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-24 14:31:32.285  1036  2039 V SIM_STK : Menu title from STK is T-Mobile
,08-24 14:31:32.362  6142  6142 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-24 14:31:34.076  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 14:31:34.076  6702  6828 I jxcore-log: 
,08-24 14:31:34.088  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 14:31:34.088  6702  6828 I jxcore-log: 
08-24 14:31:34.096  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-24 14:31:34.096  6702  6828 I jxcore-log: 
,08-24 14:31:34.251  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 14:31:34.251  6702  6828 I jxcore-log: 
,08-24 14:31:35.044  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 14:31:35.044  6702  6828 I jxcore-log: 
,08-24 14:31:35.105  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 14:31:35.105  6702  6828 I jxcore-log: 
,08-24 14:31:35.112  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 14:31:35.112  6702  6828 I jxcore-log: 
08-24 14:31:35.307  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 14:31:35.307  6702  6828 I jxcore-log: 
,08-24 14:31:35.355  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 14:31:35.355  6702  6828 I jxcore-log: 
,08-24 14:31:35.365  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 14:31:35.365  6702  6828 I jxcore-log: 
08-24 14:31:35.376  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 14:31:35.376  6702  6828 I jxcore-log: 
,08-24 14:31:35.413  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 14:31:35.413  6702  6828 I jxcore-log: 
,08-24 14:31:35.452  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 14:31:35.452  6702  6828 I jxcore-log: 
,08-24 14:31:35.626  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-24 14:31:35.626  6702  6828 I jxcore-log: 
,08-24 14:31:35.637  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-24 14:31:35.637  6702  6828 I jxcore-log: 
08-24 14:31:35.649  6702  6828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-24 14:31:35.649  6702  6828 I jxcore-log: 
,08-24 14:31:35.677  6702  6828 D ExecuteNativeTests: Running unit tests
,08-24 14:31:35.818  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:35.818  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb added. We now have 2 listener(s)
,08-24 14:31:35.822  1036  1912 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:35.824  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 14:31:35.824  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:35.824  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:35.825  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:35.825  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 added. We now have 2 listener(s)
08-24 14:31:35.825  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:35.826  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:31:35.829  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:35.832  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:35.832  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:35.832  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:35.832  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:35.832  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:35.832  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:35.832  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:35.832  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:31:35.837  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:35.837  6702  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:35.839  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:35.841  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:35.846  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 14:31:35.850  6702  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:31:35.850  6702  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:31:35.853  6702  6828 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-24 14:31:35.854  6702  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 14:31:35.854  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 14:31:35.854  6702  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:31:35.854  6702  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:31:35.855  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:35.856  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:35.856  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:35.857  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:35.857  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:35.857  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:35.857  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:35.857  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb removed from the list
08-24 14:31:35.857  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:35.857  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 removed from the list
08-24 14:31:35.857  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:35.858  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:35.860  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:35.860  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:35.864  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:35.864  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:35.864  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:35.864  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:35.869  6702  6828 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-24 14:31:35.869  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:35.869  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:35.869  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:35.870  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:35.870  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:35.870  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:35.870  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:35.870  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:35.870  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:35.870  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:35.870  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:35.870  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:35.870  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:35.870  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:35.874  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:35.874  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:35.874  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:35.874  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 14:31:35.881  6702  6828 D io,.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 14:31:35.881  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 14:31:35.882  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110],
08-24 14:31:35.882  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 14:31:35.882  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 14:31:35.882  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 14:31:35.882  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 14:31:35.882  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610],
08-24 14:31:35.882  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 14:31:35.882  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 14:31:35.882  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 14:31:35.882  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:31:35.882  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:35.882  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:31:35.891  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:35.892  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:35.892  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:35.893  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:35.893  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:35.893  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:35.893  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:35.893  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:35.893  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:35.893  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:35.893  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:35.894  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:35.894  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:35.894  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:35.894  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:35.895  6702  6828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 14:31:35.898  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:35.903  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:35.903  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:35.903  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:35.903  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:35.903  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:35.903  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:35.903  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:35.903  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:35.906  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:35.906  6702  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:35.908  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:35.909  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:35.911  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:35.911  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:31:35.911  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:35.912  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:35.912  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:31:35.916  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 14:31:35.917  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:35.923  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:31:35.932  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 14:31:35.936  6702  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-24 14:31:35.939  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:31:35.939  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:35.941  6702  6828 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 14:31:35.941  6702  6828 I io.jxcore.node.ConnectionHelper: start: OK
08-24 14:31:35.945  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:35.945  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:35.945  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:35.947  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:35.947  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:35.947  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:35.947  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:35.947  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:35.947  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:35.947  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:35.947  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:35.950  6702  6828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 14:31:36.115  1036  1912 I art     : Explicit concurrent mark sweep GC freed 27377(1392KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.749ms total 143.986ms
,08-24 14:31:36.119  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:36.122  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:36.122  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:36.122  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:36.122  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:36.122  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:36.122  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:36.122  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:36.122  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:36.123  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:36.123  6702  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:36.125  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:36.127  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:36.129  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:36.129  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:31:36.129  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:36.129  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:36.129  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:31:36.134  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:31:36.134  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:36.137  6702  6828 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 14:31:36.137  6702  6828 I io.jxcore.node.ConnectionHelper: start: OK
08-24 14:31:36.139  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.139  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.139  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:31:36.141  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.142  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.142  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:36.142  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.142  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.142  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.142  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.142  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.143  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.143  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.144  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.144  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.146  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.146  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.146  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.146  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.147  6702  6828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 14:31:36.149  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:36.152  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:36.152  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:36.152  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:36.152  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:36.152  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:36.152  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:36.152  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:36.152  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:31:36.157  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:36.157  6702  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:36.159  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:36.161  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:36.161  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:36.161  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:31:36.161  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:36.161  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:36.161  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:31:36.166  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 14:31:36.169  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:36.170  6702  6828 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 14:31:36.171  6702  6828 I io.jxcore.node.ConnectionHelper: start: OK
08-24 14:31:36.171  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.171  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.171  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.172  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.172  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.172  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.172  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.172  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.172  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:36.173  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.173  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.173  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.173  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.173  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.173  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.173  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.174  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.174  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.175  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.175  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.175  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.175  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.176  6702  6828 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-24 14:31:36.176  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.176  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.176  6702  6828 V io.jxcore,.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.185  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.185  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.185  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.186  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.186  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.186  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.186  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.186  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.186  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.186  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.186  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.192  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.192  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.193  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.193  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.193  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.193  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.195  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 14:31:36.195  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.195  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.195  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.196  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.196  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.196  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.196  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.196  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.196  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.196  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.196  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.196  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.196  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.196  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.197  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.197  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.198  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.198  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.198  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.198  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.199  6702  6828 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-24 14:31:36.199  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.199  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.199  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.203  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.203  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.203  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.203  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.203  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.203  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.205  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.205  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.205  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.205  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.205  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.206  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.206  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.207  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.207  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.207  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.207  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.208  6702  6828 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 14:31:36.208  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.208  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.208  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.211  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.211  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.211  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.211  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.211  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.211  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.211  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.211  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.211  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.211  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.211  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:36.216  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.217  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.218  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.218  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.218  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.218  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.219  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 14:31:36.221  6702  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:31:36.221  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 14:31:36.221  6702  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:31:36.221  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 14:31:36.221  6702  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:31:36.221  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.221  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.221  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.225  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.225  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.225  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.225  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.225  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.225  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.225  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.225  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.225  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.225  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.225  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.230  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.230  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.232  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.232  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.232  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.232  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.234  6702  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:31:36.237  6702  6828 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 14:31:36.237  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-24 14:31:36.251  6702  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:31:36.252  6702  6828 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 14:31:36.252  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 14:31:36.252  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 14:31:36.252  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 14:31:36.252  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 14:31:36.253  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 14:31:36.253  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 14:31:36.253  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 14:31:36.253  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 14:31:36.253  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 14:31:36.253  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 14:31:36.253  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 14:31:36.253  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 14:31:36.253  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 14:31:36.253  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 14:31:36.254  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 14:31:36.254  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 14:31:36.254  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 14:31:36.254  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 14:31:36.254  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 14:31:36.254  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 14:31:36.254  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 14:31:36.254  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 14:31:36.254  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 14:31:36.255  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 14:31:36.255  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-24 14:31:36.258  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 14:31:36.258  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 14:31:36.258  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 14:31:36.258  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 14:31:36.258  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 14:31:36.258  6702  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 14:31:36.258  6702  6828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 14:31:36.259  6702  6828 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 14:31:36.259  6702  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:31:36.259  6702  6828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 14:31:36.259  6702  6828 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 14:31:36.259  6702  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:31:36.259  6702  6828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 14:31:36.259  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-24 14:31:36.263  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-24 14:31:36.264  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 14:31:36.265  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-24 14:31:36.267  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 14:31:36.267  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 14:31:36.269  6702  6828 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-24 14:31:36.269  6702  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:31:36.269  6702  6828 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-24 14:31:36.270  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.271  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.271  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.271  6702  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 846)
08-24 14:31:36.271  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.272  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.272  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.272  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-24 14:31:36.273  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.273  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.274  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.274  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.274  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.274  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.274  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.274  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:36.275  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.275  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.275  6702  6970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 846
08-24 14:31:36.276  6702  6970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 846)
08-24 14:31:36.276  6702  6970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 846)
08-24 14:31:36.276  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.276  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.276  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.276  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.277  6702  6828 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-24 14:31:36.278  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:31:36.279  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.279  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.279  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.279  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.279  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.279  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.279  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.279  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.279  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.279  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.279  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.280  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.280  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.282  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.282  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.283  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.283  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.283  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.283  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.284  6702  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-24 14:31:36.284  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.284  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.284  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.295  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.295  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.295  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.295  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.295  6702,  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.295  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.295  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.295  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.295  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.295  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.295  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:36.300  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.300  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.301  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.301  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.301  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.301  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.302  6702  6828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 14:31:36.302  6702  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 14:31:36.302  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 14:31:36.302  6702  6828 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 14:31:36.302  6702  6828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 14:31:36.302  6702  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-24 14:31:36.303  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:31:36.303  6702  6828 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 14:31:36.303  6702  6828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 14:31:36.303  6702  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 14:31:36.303  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:31:36.303  6702  6828 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 14:31:36.303  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.303  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.303  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.304  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.304  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.304  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.304  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.304  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.304  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
,08-24 14:31:36.304  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.304  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.304  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.304  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.304  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.306  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.306  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.306  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.307  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.307  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.307  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.307  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.307  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.307  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.307  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.307  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.307  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.308  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.308  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:31:36.308  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.308  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.308  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.308  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.308  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.308  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.308  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.308  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:31:36.308  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.308  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.308  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.308  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.308  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.309  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.309  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.309  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.309  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.309  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.309  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.309  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.309  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.310  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.310  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.310  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.310  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.310  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.310  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.313  6702  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 14:31:36.314  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:36.316  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-24 14:31:36.317  6702  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 14:31:36.317  6702  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 14:31:36.317  6702  6702 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 14:31:36.318  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 14:31:36.318  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:31:36.319  1036  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:36.319  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.319  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopLi,steningForIncomingConnections
08-24 14:31:36.319  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 14:31:36.319  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 14:31:36.319  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.319  6702  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 14:31:36.319  6702  6971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:36.320  6702  6702 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-24 14:31:36.320  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.320  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.320  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:31:36.320  6702  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:31:36.320  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:31:36.322  4328  4345 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-24 14:31:36.322  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:31:36.323  6702  6971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-24 14:31:36.323  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:36.323  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:36.323  6702  6971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 14:31:36.323  6702  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:31:36.323  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.323  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.323  6702  6971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 14:31:36.324  6702  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:31:36.325  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:36.325  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:36.325  6702  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-24 14:31:36.325  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:31:36.326  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.326  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.326  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.326  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.326  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.326  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.326  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.326  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib,.ConnectionManager@efd80cb not in the list
08-24 14:31:36.326  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.326  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.326  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.326  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.326  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.326  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.326  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.328  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.328  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.328  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.328  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.330  6702  6828 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 14:31:36.330  6702  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 14:31:36.330  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 14:31:36.331  6702  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:31:36.331  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.331  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.331  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:31:36.331  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.331  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.331  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.331  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.331  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.331  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.331  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 14:31:36.331  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.331  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.331  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.332  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:36.334  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.334  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.334  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:31:36.334  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.335  1036  1596 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:36.337  1036  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:36.338  1036  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:36.340  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:36.340  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.340  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:31:36.340  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.340  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.340  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.340  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.340  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.340  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.340  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.340  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:31:36.340  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.341  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.341  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.341  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.341  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.341  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.342  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
08-24 14:31:36.343  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:31:36.343  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:36.343  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:36.343  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:36.343  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.343  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.343  6702  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efd80cb not in the list
08-24 14:31:36.343  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.343  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
,08-24 14:31:36.343  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:36.343  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.343  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.343  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:36.343  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:36.345  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:36.345  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:36.345  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:36.345  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72fe0a8 not in the list
,08-24 14:31:36.346  6702  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-24 14:31:36.346  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-24 14:31:36.347  6702  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 14:31:36.347  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 14:31:36.347  6702  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 14:31:36.347  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:31:36.350  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 14:31:36.350  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-24 14:31:36.351  6702  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 14:31:36.351  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 14:31:36.351  6702  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 14:31:36.351  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 14:31:36.351  6702  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 14:31:36.351  6702  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-24 14:31:36.352  6702  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-24 14:31:36.352  6702  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 14:31:36.353  6702  6828 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 14:31:36.353  6702  6828 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 14:31:36.353  6702  6828 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 14:31:36.354  6702  6828 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-24 14:31:36.355  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:36.355  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1702edf9 added. We now have 2 listener(s)
08-24 14:31:36.355  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:36.356  6702  6828 D BluetoothAdapter: enable(): BT is already enabled..!
08-24 14:31:36.358  1036  1968 D WifiServiceImplEx: setWifiEnabled: true pid=6702, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 14:31:36.358  1036  1968 D WifiService: setWifiEnabled: true pid=6702, uid=10118
08-24 14:31:36.358  1036  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 14:31:36.360  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:36.360  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3857613e added. We now have 3 listener(s)
08-24 14:31:36.360  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:36.365  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:36.365  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10c97b9f added. We now have 4 listener(s)
08-24 14:31:36.365  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:36.367  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:36.367  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@56e44ec added. We now have 5 listener(s)
08-24 14:31:36.367  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:36.370  1036  1949 D WifiServiceImplEx: setWifiEnabled: false pid=6702, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 14:31:36.370  1036  1949 D WifiService: setWifiEnabled: false pid=6702, uid=10118
08-24 14:31:36.370  1036  1949 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 14:31:36.389  1036  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 14:31:36.389  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 14:31:36.390  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 14:31:36.390  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 14:31:36.390  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-24 14:31:36.390  1036  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-24 14:31:36.390  1036  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-24 14:31:36.391  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-24 14:31:36.391  1036  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 14:31:36.391  1036  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:31:36.391  1036  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 14:31:36.392  1036  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 14:31:36.392  1036  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 14:31:36.392  1036  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:36.393  1036  1915 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@8f7ed85 mBinding = false
08-24 14:31:36.400  6702  6969 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-24 14:31:36.401  6702  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 846)
08-24 14:31:36.404  1036  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 14:31:36.404  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 14:31:36.404  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.404  2680  2680 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 14:31:36.404  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.405  1036  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 14:31:36.405  1036  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 14:31:36.405  1036  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 14:31:36.405  1036  2822 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.406   325   895 D CommandListener: Clearing all IP addresses on wlan0
,08-24 14:31:36.413  1036  1097 D BluetoothManagerService: Message: 2
08-24 14:31:36.413  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 14:31:36.413  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 14:31:36.413  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-24 14:31:36.414  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:36.415  1036  1097 D BluetoothManagerService: Sending off request.
08-24 14:31:36.416  4328  4345 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-24 14:31:36.416  4328  4412 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-24 14:31:36.417  4328  4412 D BluetoothAdapterProperties: Setting state to 13
08-24 14:31:36.417  4328  4412 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 14:31:36.417  4328  4412 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 14:31:36.417  4328  4412 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-24 14:31:36.420  4328  4416 D BluetoothAdapterProperties: Scan Mode:20
,08-24 14:31:36.420  4328  4412 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 14:31:36.421  4328  4412 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 14:31:36.423  4328  4715 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:31:36.424  4328  4734 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:31:36.425  4328  4714 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-24 14:31:36.425  4328  4714 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:31:36.425  4328  4714 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-24 14:31:36.425  4328  4714 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-24 14:31:36.425  4328  4714 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-24 14:31:36.425  4328  4714 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-24 14:31:36.425  4328  4714 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-24 14:31:36.425  4328  4714 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-24 14:31:36.426  4328  4756 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:31:36.426  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-24 14:31:36.426  4328  4754 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:31:36.426  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.426  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:36.426  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:36.426  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:36.426  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:36.426  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:36.426  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:36.426  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:36.426  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:36.427  4328  4525 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-24 14:31:36.428  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 14:31:36.428  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 14:31:36.428  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 14:31:36.428  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 14:31:36.428  4328  4525 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:31:36.428  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 14:31:36.429  4328  4525 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:36.429  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 14:31:36.429  ,4328  4525 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 14:31:36.429  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-24 14:31:36.429  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-24 14:31:36.429  4328  4525 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 14:31:36.430  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.430  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:36.430  1036  1097 D BluetoothManagerService: Message: 60
08-24 14:31:36.431  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-24 14:31:36.431  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-24 14:31:36.431  6702  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:36.436  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.436  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:36.436  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:36.436  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:36.436  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:36.436  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:36.436  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:36.436  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:36.436  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:31:36.437  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.437  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:36.441  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:36.443  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.443  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:36.443  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:36.443  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:36.443  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:36.443  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:36.443  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:36.443  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:36.443  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:36.444  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.444  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:36.448  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:36.456  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 14:31:36.456  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-24 14:31:36.479  1036  1093 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6977 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-24 14:31:36.485  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:36.486  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 14:31:36.495  1036  1576 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-24 14:31:36.496  1036  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.496  1036  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.496  1036  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-24 14:31:36.496  1036  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.496  1036  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-24 14:31:36.496  4328  4328 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:36.496  4328  4328 D BluetoothMapService: STATE_TURNING_OFF
08-24 14:31:36.496  4328  4328 V BluetoothMapService: Handler(): got msg=4
08-24 14:31:36.496  4328  4328 D BluetoothMapService: MAP Service closeService in
08-24 14:31:36.496  4328  4328 D BluetoothMapMasInstance: MAP Service shutdown
08-24 14:31:36.497  4328  4328 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 14:31:36.497  4328  4328 V BluetoothMapService: MAP Service closeService out
08-24 14:31:36.500  4328  4328 V BtOppService: Receiver DISABLED_ACTION 
08-24 14:31:36.500  4328  4328 I BtOppRfcommListener: stopping Accept Thread
08-24 14:31:36.500  4328  4328 V BtOppRfcommListener: close mBtServerSocket
08-24 14:31:36.501  4328  4328 V BtOppRfcommListener: waiting for thread to terminate
08-24 14:31:36.501  4328  4734 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 14:31:36.502  4328  4328 V BtOppRfcommListener: done waiting for thread to terminate
,08-24 14:31:36.508  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.508  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:36.508  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:36.508  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:36.508  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:36.508  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:36.508  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:36.508  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:36.508  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:36.509  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.509  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:36.511  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.511  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:36.511  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:36.511  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:36.511  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:36.511  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:36.511  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:36.511  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:36.511  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:36.512  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.512  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:36.532  1036  1093 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7003 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 14:31:36.535  4328  4328 V BtOppService: onDestroy
08-24 14:31:36.536  4328  4328 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-24 14:31:36.537  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.537  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.537  1036  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3d5476d6
08-24 14:31:36.537  1036  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:36.538  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:36.538  1036  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:36.538  1036  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 14:31:36.538  1036  1538 D LGWifiP2pService: P2pDisablingState
08-24 14:31:36.538  1036  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:36.539  1036  1538 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.539  1036  1538 D LGWifiP2pService: p2p socket connection lost
08-24 14:31:36.539  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:36.539  1036  1538 D LGWifiP2pService: P2pDisabledState
08-24 14:31:36.539  1036  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:36.540  1036  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:36.540  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:36.540  1036  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:36.541  1036  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-24 14:31:36.541  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 14:31:36.541  2680  2680 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 14:31:36.541  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.541  1036  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.542  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-24 14:31:36.543  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-24 14:31:36.545  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:36.545  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:36.546  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 14:31:36.547  1036  1036 D WifiHS20: hidePasspointNotification off =false
,08-24 14:31:36.549  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:36.549  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:36.549  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 14:31:36.549  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 14:31:36.549  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.550  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-24 14:31:36.550  1036  1558 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.551  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 14:31:36.552  1036  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 14:31:36.552  1036  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 14:31:36.552   325  7017 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-24 14:31:36.553  1969  1969 D WfdsService: WifiP2pState is changed : false
08-24 14:31:36.553  1969  2299 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-24 14:31:36.553  1969  2299 D WfdsService: Set the WFDS Monitor: false
08-24 14:31:36.553  1036  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-24 14:31:36.553  1036  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 14:31:36.553   325   895 D CommandListener: Clearing all IP addresses on wlan0
08-24 14:31:36.554  1036  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-24 14:31:36.554  1036  1095 D DSQN    : Dns fail occured do internet check.
08-24 14:31:36.554  1036  1036 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-24 14:31:36.554  1036  1036 D DSQN    : try Internet connection check
08-24 14:31:36.555  1036  1546 D DSQN    : disableDataServiceNotify
08-24 14:31:36.555  1036  1546 D DSQN    : stop dsqn bin
08-24 14:31:36.559  1969  2299 D WfdsMonitor: WFDS Monitor is stopped
08-24 14:31:36.559  1969  2299 D WfdsService: STATE : WfdsDisabledState - enter
08-24 14:31:36.559  1969  2300 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-24 14:31:36.559  1036  1540 D WifiNative-p2p0: doBoolean: TERMINATE
08-24 14:31:36.559  1969  2756 D CtrlSupplicant: Received on exit socket, terminate
08-24 14:31:36.559  1969  2756 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
,08-24 14:31:36.559  1969  2756 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-24 14:31:36.559  1969  2756 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-24 14:31:36.560  1969  2299 W WfdsService: DefaultState - msg [9445378] is not handled
08-24 14:31:36.560  1036  1540 D WifiNative-p2p0: TERMINATE: returned true
08-24 14:31:36.560  1036  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 14:31:36.560  1036  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 14:31:36.560  1036  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 14:31:36.560   325  7022 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-24 14:31:36.561  1036  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-24 14:31:36.561  1036  7021 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-24 14:31:36.562  1036  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-24 14:31:36.562  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:36.562  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:36.562  1036  7019 D DSQN    : ThreadInternetCheck internet check NOK 
08-24 14:31:36.562  1036  7019 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-24 14:31:36.562  1036  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:36.563  1036  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-24 14:31:36.563  1036  7019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-24 14:31:36.563  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-24 14:31:36.563  1036  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-24 14:31:36.563  1036  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-24 14:31:36.563  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 14:31:36.564  1036  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.565  1036  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.565  1036  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-24 14:31:36.565  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-24 14:31:36.565  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only ,value.
08-24 14:31:36.565  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:36.565  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 14:31:36.567  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-24 14:31:36.571  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.571  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:36.571  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:36.571  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:36.571  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:36.571  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:36.571  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:36.571  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:36.571  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:36.573  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.573  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:36.573  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,08-24 14:31:36.575  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:36.575  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 14:31:36.576  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:36.576  1036  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:36.576  1036  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:36.576  1036  1546 D NetworkManagementService: Removing idletimer
08-24 14:31:36.576  1036  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:36.578  1036  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:36.578  1036  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 14:31:36.578  1036  1546 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-24 14:31:36.579  1036  1036 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-24 14:31:36.579  1036  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 14:31:36.580  1036  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 14:31:36.580  1875  1875 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:36.581  1875  1875 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 14:31:36.582  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.582  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:36.582  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:36.582  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:36.582  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:36.582  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:36.582  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:36.582  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:36.582  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:36.582  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.582  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:36.584  1969  1984 D WifiServiceExtension: isInternetCheckAvailable return false
08-24 14:31:36.584  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:36.584  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-24 14:31:36.584  1036  1036 ,D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 14:31:36.584  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 14:31:36.584  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 14:31:36.585  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 14:31:36.585  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 14:31:36.585  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 14:31:36.585  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 14:31:36.585  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 14:31:36.587  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:36.587  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-24 14:31:36.591  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:36.603  7003  7003 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:31:36.603  7003  7003 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-24 14:31:36.603  7003  7003 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 14:31:36.603  7003  7003 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-24 14:31:36.604  7003  7003 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 14:31:36.605  7003  7003 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-24 14:31:36.624  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:36.624  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-24 14:31:36.626  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:36.629  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 14:31:36.629  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:36.630  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:36.631  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:36.638  6977  6977 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-24 14:31:36.639  6977  6977 W LG Account v2.2: No ProfileInfo entries
08-24 14:31:36.639  6977  6977 I LG Account v2.2: isEnabled: false
08-24 14:31:36.639  6977  6977 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-24 14:31:36.639  6977  6977 I Feature : [Lifetracker]Country: EU
08-24 14:31:36.639  6977  6977 I Feature : [Lifetracker]Operator: OPEN
08-24 14:31:36.640  6977  6977 I Feature : [Lifetracker]Ranking support: false
08-24 14:31:36.640  6977  6977 I Feature : [Lifetracker]Comfort support: false
08-24 14:31:36.640  6977  6977 I Feature : [Lifetracker]Accessory: true
08-24 14:31:36.641  6977  6977 I Feature : [Lifetracker]Health device: true
08-24 14:31:36.641  6977  6977 I Feature : [Lifetracker]Extra Pedometer: false
08-24 14:31:36.641  6977  6977 I Feature : [Lifetracker]Blood glucose device: false
08-24 14:31:36.641  6977  6977 I Feature : [Lifetracker]Device Number: 3
08-24 14:31:36.646  2680  2680 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-24 14:31:36.646  2680  2680 I wpa_supplicant: monitor socket send errors count : 1
08-24 14:31:36.646  2680  2680 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-2\x00 that cannot receive messages
08-24 14:31:36.647  1036  2750 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-24 14:31:36.647  1036  2750 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 14:31:36.652  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 14:31:36.675  1036  2822 D DhcpStateMachine: StoppedState
08-24 14:31:36.675  1036  2822 D DhcpStateMachine: StoppedState{ when=-122ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:36.675  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 14:31:36.676  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:36.677  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:36.685  2680  2680 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 14:31:36.686  1036  1576 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7027 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 14:31:36.687  1036  1576 I ActivityManager: Killing 6302:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-24 14:31:36.687  2680  2680 W wpa_supplicant: USIM:  scard_deinit function
08-24 14:31:36.687  1036  2750 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-24 14:31:36.687  1036  2750 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 14:31:36.687  1036  2750 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 14:31:36.687  1036  2750 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-24 14:31:36.687  1036  2750 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 14:31:36.687  1036  2750 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 14:31:36.687  1036  1097 D Tethering: InitialState.processMessage what=4
08-24 14:31:36.687  1036  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=128769
08-24 14:31:36.688  1036  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=128769
,08-24 14:31:36.688  1036  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=128769  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 14:31:36.688  1036  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=128770  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 14:31:36.697  7003  7003 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 14:31:36.727  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-24 14:31:36.738  1036  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-24 14:31:36.738  1036  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-24 14:31:36.739  1036  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:36.739  1036  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:36.739  1036  1912 W libprocessgroup: failed to open /acct/uid_10014/pid_6302/cgroup.procs: No such file or directory
,08-24 14:31:36.749  4328  4328 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 14:31:36.749  4328  4328 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:36.749  4328  4328 V BluetoothPbapReceiver: ***********state = 13
08-24 14:31:36.751  4328  4328 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-24 14:31:36.752  4328  4328 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:36.752  4328  4328 V BluetoothPbapService: state: 13
08-24 14:31:36.752  4328  4328 V BluetoothPbapService: Pbap Service closeService in
08-24 14:31:36.753  1036  1097 D BluetoothManagerService: Message: 20
08-24 14:31:36.754  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1102594:true
08-24 14:31:36.754  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:31:36.755  4328  4328 V BluetoothPbapService: successfully stopped pbap service
08-24 14:31:36.755  4328  4328 V BluetoothPbapService: Pbap Service closeService out
08-24 14:31:36.756  4328  4328 V BluetoothPbapService: Pbap Service onDestroy
,08-24 14:31:36.756  4328  4328 V BluetoothPbapService: Pbap Service closeService in
08-24 14:31:36.756  4328  4328 V BluetoothPbapService: Pbap Service closeService out
08-24 14:31:36.756  4328  4328 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-24 14:31:36.768  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-24 14:31:36.770  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:36.770  2680  2680 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-24 14:31:36.770  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:36.772  1036  2750 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-24 14:31:36.772  1036  2750 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-24 14:31:36.773  1036  2750 D WifiMonitor: Disconnecting from the supplicant, no more events
08-24 14:31:36.773  1036  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-24 14:31:36.775  1036  1097 D BluetoothManagerService: Message: 30
08-24 14:31:36.778  1036  1097 D BluetoothManagerService: Message: 30
08-24 14:31:36.779  7003  7003 D LocalBluetoothProfileManager: Adding local MAP profile
08-24 14:31:36.780  7003  7003 D BluetoothMap: Create BluetoothMap proxy object
08-24 14:31:36.781  1036  1097 D BluetoothManagerService: Message: 30
08-24 14:31:36.783  1036  1097 D BluetoothManagerService: Message: 30
,08-24 14:31:36.784  7003  7003 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-24 14:31:36.785  7003  7003 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-24 14:31:36.788  7027  7027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 14:31:36.794  7003  7003 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-24 14:31:36.795  7027  7027 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 14:31:36.795  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 14:31:36.796  7003  7003 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-24 14:31:36.798  1036  1968 I ActivityManager: Killing 6395:com.android.defcontainer/u0a4 (adj 15): empty #17
08-24 14:31:36.826  6702  6702 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:31:36.830  1036  1596 W libprocessgroup: failed to open /acct/uid_10004/pid_6395/cgroup.procs: No such file or directory
08-24 14:31:36.840  7003  7003 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:31:36.853  7003  7003 D BluetoothInputDevice: Proxy object connected
,08-24 14:31:36.854  7003  7003 D HidProfile: Bluetooth service connected
,08-24 14:31:36.856  7003  7003 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:31:36.857  7003  7003 D PanProfile: Bluetooth service connected
08-24 14:31:36.858  7003  7003 D BluetoothMap: Proxy object connected
08-24 14:31:36.859  7003  7003 D MapProfile: Bluetooth service connected
08-24 14:31:36.859  7003  7003 D BluetoothMap: getConnectedDevices()
08-24 14:31:36.859  7003  7003 D BluetoothMap: Bluetooth is Not enabled
08-24 14:31:36.874  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 14:31:36.874  1036  1540 D WifiOffDelayIfNotUsed: stopMonitoring
08-24 14:31:36.874  1036  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 14:31:36.874  1036  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 14:31:36.874  1036  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 14:31:36.877  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 14:31:36.879  1969  1969 D WfdsService: Supplicant Connection state is changed : false
08-24 14:31:36.879  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 14:31:36.879  1969  2299 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-24 14:31:36.879  1969  2299 D WfdsService: Set the WFDS Monitor: false
08-24 14:31:36.879  1969  2299 D WfdsMonitor: WFDS Monitor is stopped
08-24 14:31:36.880  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-24 14:31:36.880  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-24 14:31:36.880  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-24 14:31:36.881  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:36.883  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.883  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:36.883  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:36.883  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:36.883  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:36.883  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:36.883  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:36.883  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:36.883  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:31:36.885  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:36.885  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:36.885  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:36.885  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:36.885  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:36.885  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:36.885  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:36.885  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:36.885  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:31:36.918  7003  7003 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:36.919  7003  7003 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:31:36.932  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:36.932  7003  7003 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-24 14:31:36.934  7003  7003 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-24 14:31:36.940  7003  7003 D BluetoothPermissionRequest: onReceive
08-24 14:31:36.944  7003  7003 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-24 14:31:36.951  1036  2052 I ActivityManager: Killing 6538:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-24 14:31:36.954  7003  7003 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 14:31:36.999  4328  4328 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-24 14:31:36.999  4328  4328 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-24 14:31:36.999  1036  1052 W libprocessgroup: failed to open /acct/uid_10008/pid_6538/cgroup.procs: No such file or directory
08-24 14:31:37.000  4328  4328 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-24 14:31:37.018  4328  4328 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:37.018  4328  4328 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-24 14:31:37.108  1036  1949 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7058 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-24 14:31:37.113  4328  4328 V BluetoothFtpService: Ftp Service onStartCommand
,08-24 14:31:37.114  4328  4328 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:37.114  4328  4328 V BluetoothFtpService: Ftp Service closeService
08-24 14:31:37.115  4328  4328 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-24 14:31:37.122  4328  4328 V BluetoothFtpService: successfully stopped ftp service
,08-24 14:31:37.122  4328  4328 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 14:31:37.123  4328  4328 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 14:31:37.123  4328  4328 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 14:31:37.123  4328  4328 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:37.123  4328  4328 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-24 14:31:37.123  4328  4328 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-24 14:31:37.125  4328  4328 V BluetoothFtpService: Ftp Service onDestroy
08-24 14:31:37.125  4328  4328 V BluetoothFtpService: Ftp Service closeService
08-24 14:31:37.165  1036  1052 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7075 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 14:31:37.167  4328  4328 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:37.167  4328  4328 V BluetoothSapService: state: 13
08-24 14:31:37.167  4328  4328 V BluetoothSapService: Stopping SAP server process
08-24 14:31:37.169  4328  4328 V BluetoothSapService: Sap Service closeSapService in
08-24 14:31:37.169  4328  4328 V BluetoothSapService: Close listen Socket : 
08-24 14:31:37.169  4328  4328 V BluetoothSapService: Close rfcomm Socket : 
08-24 14:31:37.169  4328  4328 V BluetoothSapService: Close sapd  Socket : 
08-24 14:31:37.172  4328  4328 V BluetoothSapService: Sap Service closeSapService out
08-24 14:31:37.172  4328  4328 V BluetoothSapService: Sap Service onDestroy
08-24 14:31:37.172  4328  4328 V BluetoothSapService: Sap Service closeSapService in
08-24 14:31:37.172  4328  4328 V BluetoothSapService: Close listen Socket : 
08-24 14:31:37.172  4328  4328 V BluetoothSapService: Close rfcomm Socket : 
08-24 14:31:37.172  4328  4328 V BluetoothSapService: Close sapd  Socket : 
08-24 14:31:37.173  4328  4328 V BluetoothSapService: Sap Service closeSapService out
,08-24 14:31:37.220  7058  7058 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 14:31:37.249  7058  7058 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-24 14:31:37.254  7075  7075 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 14:31:37.271  1036  1967 I ActivityManager: Killing 6076:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-24 14:31:37.288  7058  7058 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-24 14:31:37.289  7058  7058 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-24 14:31:37.289  7058  7058 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-24 14:31:37.290  7058  7058 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-24 14:31:37.290  7058  7058 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-24 14:31:37.292  7058  7058 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-24 14:31:37.300  7058  7058 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-24 14:31:37.309  1036  1576 W libprocessgroup: failed to open /acct/uid_10011/pid_6076/cgroup.procs: No such file or directory
,08-24 14:31:37.318  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 14:31:37.322  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:31:37.346  7058  7058 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-24 14:31:37.349  7058  7058 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-24 14:31:37.350  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:37.353  7027  7027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 14:31:37.353  7027  7027 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 14:31:37.353  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:37.358  7058  7058 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-24 14:31:37.358  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:37.370  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:37.380  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:31:37.380  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 14:31:37.382  7058  7058 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 14:31:37.386  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:37.390  7027  7027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 14:31:37.390  7027  7027 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 14:31:37.390  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:37.393  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:37.406  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:37.417  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:31:37.418  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 14:31:37.421  7058  7058 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 14:31:37.433  4328  4525 W bt-btif : ag scb idx 1 not allocated
08-24 14:31:37.433  4328  4416 D bt_hci_bdroid: cleanup
,08-24 14:31:37.433  4328  4525 E bt-btif : BTA AG is already disabled, ignoring ...
08-24 14:31:37.433  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 14:31:37.433  4328  4525 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 14:31:37.433  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 14:31:37.433  4328  4525 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:37.433  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 14:31:37.433  4328  4525 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:31:37.434  4328  4528 I bt_lpm  : LPM is already off!!!
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 14:31:37.434  4328  4694 I bt_userial_mct: exiting userial_read_thread
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 14:31:37.434  4328  4694 D bt_userial_mct: Leaving userial_evt_read_thread()
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 14:31:37.434  4328  4525 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 14:31:37.434  4328  4525 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 14:31:37.435  4328  4416 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-24 14:31:37.435  4328  4528 I bt_vendor: hw_epilog_process
08-24 14:31:37.436  4328  4416 D bt_hci_bdroid: cleanup Finalizing cleanup
08-24 14:31:37.436  4328  4416 D bt_userial_mct: userial_close
08-24 14:31:37.436  4328  4416 E bt_userial_mct: pthread_join() FAILED result:3
08-24 14:31:37.436  4328  4416 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-24 14:31:37.508  1036  2019 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7105 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-24 14:31:37.555  4328  4416 D bt_hci_bdroid: set_power 0
,08-24 14:31:37.555  4328  4416 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-24 14:31:37.555  4328  4416 I bt_vendor: bluetooth satus is on
08-24 14:31:37.555  4328  4416 I bt_vendor: bt-vendor : resetting BT status
08-24 14:31:37.555  4328  4416 I bt_vendor: Starting hciattach daemon
08-24 14:31:37.555  4328  4416 I bt_vendor: try to set false
08-24 14:31:37.557  4328  4416 I bt_vendor: Starting hciattach daemon
08-24 14:31:37.557  4328  4416 I bt_vendor: try to set false
08-24 14:31:37.559  4328  4416 I bt_vendor: cleanup
08-24 14:31:37.560  4328  4525 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-24 14:31:37.560  4328  4416 I GKI_LINUX: GKI_exit_task 0 done
08-24 14:31:37.560  4328  4416 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-24 14:31:37.562  4328  4412 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 14:31:37.571  4328  4328 D HeadsetService: Received stop request...Stopping profile...
,08-24 14:31:37.572  4328  4328 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 14:31:37.572  4328  4328 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 14:31:37.573  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a98e451
08-24 14:31:37.574  1036  1036 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
08-24 14:31:37.576  4328  4448 D HeadsetStateMachine: Exit Disconnected: -1
08-24 14:31:37.577  1875  1875 D BluetoothHeadset: Proxy object disconnected
08-24 14:31:37.577  1875  1875 D BluetoothHeadset: Proxy object disconnected
08-24 14:31:37.577  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-24 14:31:37.577  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-24 14:31:37.578  4328  4328 D A2dpService: Received stop request...Stopping profile...
08-24 14:31:37.578  1875  1875 D BluetoothHeadset: Proxy object disconnected
08-24 14:31:37.578  4328  4503 D A2dpStateMachine: Exit Disconnected: -1
,08-24 14:31:37.579  4328  4328 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-24 14:31:37.580  4328  4412 D BluetoothAdapterState: Stopping profile services that were post enabled
08-24 14:31:37.585  4328  4328 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-24 14:31:37.585  4328  4328 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 14:31:37.586  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a98e451
08-24 14:31:37.588  4328  4328 D HidService: Received stop request...Stopping profile...
08-24 14:31:37.588  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a98e451
,08-24 14:31:37.588  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-24 14:31:37.590  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-24 14:31:37.590  4328  4328 D HealthService: Received stop request...Stopping profile...
08-24 14:31:37.590  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a98e451
08-24 14:31:37.591  7003  7003 D BluetoothInputDevice: Proxy object disconnected
08-24 14:31:37.591  7003  7003 D HidProfile: Bluetooth service disconnected
08-24 14:31:37.593  4328  4328 D PanService: Received stop request...Stopping profile...
08-24 14:31:37.593  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a98e451
08-24 14:31:37.594  7003  7003 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 14:31:37.594  7003  7003 D PanProfile: Bluetooth service disconnected
08-24 14:31:37.595  4328  4328 D HeadsetStateMachine: Unbinding service...
08-24 14:31:37.595  4328  4328 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 14:31:37.595  4328  4328 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 14:31:37.595  4328  4328 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 14:31:37.595  4328  4328 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 14:31:37.596  4328  4328 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 14:31:37.596  4328  4328 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 14:31:37.596  4328  4328 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 14:31:37.596  4328  4328 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 14:31:37.597  4328  4328 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 14:31:37.597  4328  4328 D BtGatt.GattService: stop()
08-24 14:31:37.597  4328  4328 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 14:31:37.600  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a98e451
,08-24 14:31:37.601  4328  4328 D BluetoothMapService: Received stop request...Stopping profile...
08-24 14:31:37.601  4328  4328 D BluetoothMapService: stop()
08-24 14:31:37.602  4328  4328 D BluetoothMapEmailAppObserver: deinitObservers()
08-24 14:31:37.602  4328  4328 D BluetoothMapEmailAppObserver: removeReceiver()
08-24 14:31:37.602  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a98e451
08-24 14:31:37.603  7003  7003 D BluetoothMap: Proxy object disconnected
08-24 14:31:37.603  7003  7003 D MapProfile: Bluetooth service disconnected
08-24 14:31:37.604  4328  4328 I BluetoothA2dpServiceJni: cleanupNative
08-24 14:31:37.604  4328  4504 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-24 14:31:37.604  4328  4328 I GKI_LINUX: GKI_exit_task 2 done
08-24 14:31:37.604  4328  4328 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 14:31:37.605  4328  4328 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 14:31:37.605  4328  4328 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 14:31:37.605  4328  4328 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 14:31:37.605  4328  4328 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 14:31:37.605  4328  4328 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 14:31:37.605  4328  4328 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 14:31:37.605  4328  4328 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 14:31:37.607  4328  4328 V BluetoothMapService: Handler(): got msg=4
08-24 14:31:37.607  4328  4328 D BluetoothMapService: MAP Service closeService in
08-24 14:31:37.607  4328  4328 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 14:31:37.607  4328  4328 V BluetoothMapService: MAP Service closeService out
08-24 14:31:37.607  4328  4328 D BluetoothMapService: cleanup()
08-24 14:31:37.607  4328  4328 D BluetoothMapService: MAP Service closeService in
08-24 14:31:37.607  4328  4328 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 14:31:37.607  4328  4328 V BluetoothMapService: MAP Service closeService out
08-24 14:31:37.607  4328  4412 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-24 14:31:37.607  4328  4412 D BluetoothAdapterProperties: Setting state to 10
08-24 14:31:37.607  4328  4412 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 14:31:37.608  1036  1097 D BluetoothManagerService: Message: 60
08-24 14:31:37.608  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-24 14:31:37.608  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-24 14:31:37.608  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:31:37.608  4328  4412 I BluetoothAdapterState: Entering OffState
08-24 14:31:37.609  1875  2575 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:31:37.609  1875  1894 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:31:37.610  7003  7023 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 14:31:37.611  7003  7020 D BluetoothPan: onBluetoothStateChange on: false
08-24 14:31:37.611  7003  7023 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 14:31:37.612  7003  7020 D BluetoothMap: onBluetoothStateChange: up=false
08-24 14:31:37.613  1875  2614 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 14:31:37.614  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:31:37.615  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-24 14:31:37.615  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-24 14:31:37.618  1036  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-24 14:31:37.618  1036  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-24 14:31:37.618  1036  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@8f7ed85 mBinding = false
08-24 14:31:37.619  1036  1097 D BluetoothManagerService: Sending unbind request.
08-24 14:31:37.620  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-24 14:31:37.621  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:37.621  1969  2180 D LGBluetoothAPIService: Message: 2
08-24 14:31:37.622  1969  2180 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3cd7b3c8 mBinding = false
08-24 14:31:37.622  1969  2180 D LGBluetoothAPIService: Sending unbind request.
08-24 14:31:37.622  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 14:31:37.625  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:37.625  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:37.626  7003  7003 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 14:31:37.627  1605  1605 D BluetoothAdapter: 394673929: getState() :  mService = null. Returning STATE_OFF
08-24 14:31:37.627  1605  1605 D BluetoothAdapter: 394673929: getState() :  mService = null. Returning STATE_OFF
08-24 14:31:37.629  7003  7003 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-24 14:31:37.629  7003  7003 D LGBluetoothEventManager: [BTUI] clear device connection state
08-24 14:31:37.632  7003  7003 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 14:31:37.637  4328  4416 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-24 14:31:37.640  4328  4328 I GKI_LINUX: GKI_exit_task 1 done
,08-24 14:31:37.640  4328  4328 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-24 14:31:37.640  4328  4328 I BluetoothServiceJni: cleanupNative: return from cleanup
08-24 14:31:37.640  4328  4328 I art     : --- WEIRD: removing null entry 246
08-24 14:31:37.640  4328  4328 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-24 14:31:37.640  4328  4328 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-24 14:31:37.641  4328  4328 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-24 14:31:37.643  7003  7003 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:31:37.643  4328  4328 I art     : System.exit called, status: 0
08-24 14:31:37.644  4328  4328 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-24 14:31:37.665  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:37.669  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:37.672   329  1387 V AudioFlinger: 4328 died, releasing its sessions
08-24 14:31:37.672   329  1387 V AudioFlinger:  pid 1875 @ 0
08-24 14:31:37.672   329  1387 V AudioFlinger:  pid 3175 @ 1
08-24 14:31:37.672   329  1387 V AudioFlinger:  pid 3175 @ 2
08-24 14:31:37.677  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:37.678  7003  7003 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-24 14:31:37.715  1036  1051 I ActivityManager: Process com.android.bluetooth (pid 4328) has died
08-24 14:31:37.715  1036  1051 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-24 14:31:37.725  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:31:37.741  7105  7130 W FormManager: Network not available. Please check & try again.
,08-24 14:31:37.754  7003  7003 D BluetoothPermissionRequest: onReceive
08-24 14:31:37.754  7105  7132 V FormManager: Network unavailable.
,08-24 14:31:37.761  7003  7003 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 14:31:37.761  7003  7003 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-24 14:31:37.764  7105  7132 V FormManager: Network unavailable.
08-24 14:31:37.769  7003  7003 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-24 14:31:37.849  1036  2039 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7135 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-24 14:31:37.857  1036  2052 I ActivityManager: Killing 6098:com.android.contacts/u0a19 (adj 15): empty #17
,08-24 14:31:37.961  1036  1596 W libprocessgroup: failed to open /acct/uid_10019/pid_6098/cgroup.procs: No such file or directory
,08-24 14:31:38.000  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 14:31:38.000  7003  7003 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 14:31:38.000  7003  7003 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-24 14:31:38.001  7003  7003 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-24 14:31:38.002  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 14:31:38.017  7003  7003 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 14:31:38.018  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-24 14:31:38.018  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 14:31:38.018  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 14:31:38.019  7003  7003 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 14:31:38.020  7003  7003 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-24 14:31:38.021  7135  7135 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-24 14:31:38.022  7135  7135 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 14:31:38.023  7135  7135 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-24 14:31:38.024  7135  7135 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-24 14:31:38.026  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 14:31:38.027  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 14:31:38.032  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 14:31:38.038  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:38.051  7027  7027 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-24 14:31:38.051  7027  7027 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-24 14:31:38.051  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:38.051  7135  7135 D BluetoothAdapterApp: Loading JNI Library
08-24 14:31:38.051  4787  7153 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 14:31:38.053  4787  7155 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 14:31:38.054  4787  7155 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 14:31:38.058  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:38.067  7105  7157 W FormManager: Network not available. Please check & try again.
,08-24 14:31:38.068  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:38.083  7105  7158 V FormManager: Network unavailable.
,08-24 14:31:38.088  7105  7158 V FormManager: Network unavailable.
08-24 14:31:38.089  7058  7058 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-24 14:31:38.090  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-24 14:31:38.091  7058  7058 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-24 14:31:38.100  7135  7135 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@11f4e7de Instance Count = 1
,08-24 14:31:38.105  7135  7135 D BluetoothAdapterApp: onCreate
,08-24 14:31:38.130  7135  7135 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-24 14:31:38.130  7135  7135 D ProfileConfigQcom: Adding HeadsetService
08-24 14:31:38.130  7135  7135 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-24 14:31:38.130  7135  7135 D ProfileConfigQcom: Adding A2dpService
08-24 14:31:38.131  7135  7135 D ProfileConfigQcom: [BTUI] HidService is supported
08-24 14:31:38.131  7135  7135 D ProfileConfigQcom: Adding HidService
08-24 14:31:38.131  7135  7135 D ProfileConfigQcom: [BTUI] HealthService is supported
08-24 14:31:38.131  7135  7135 D ProfileConfigQcom: Adding HealthService
08-24 14:31:38.132  7135  7135 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-24 14:31:38.132  7058  7058 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:38.132  7058  7058 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 14:31:38.132  7135  7135 D ProfileConfigQcom: [BTUI] PanService is supported
08-24 14:31:38.133  7135  7135 D ProfileConfigQcom: Adding PanService
08-24 14:31:38.133  7135  7135 D ProfileConfigQcom: [BTUI] GattService is supported
08-24 14:31:38.133  7135  7135 D ProfileConfigQcom: Adding GattService
08-24 14:31:38.134  7135  7135 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-24 14:31:38.134  7135  7135 D ProfileConfigQcom: Adding BluetoothMapService
08-24 14:31:38.134  7135  7135 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-24 14:31:38.136  7135  7135 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-24 14:31:38.141  7003  7003 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-24 14:31:38.143  7135  7135 V LGMDMManagerInternal: Create singleton instance
,08-24 14:31:38.143  7058  7058 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-24 14:31:38.146  7058  7058 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-24 14:31:38.146  7058  7058 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-24 14:31:38.146  7058  7058 V SoundPool: doLoad: loading sample sampleID=1
08-24 14:31:38.147  7058  7058 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-24 14:31:38.151  7058  7162 V SoundPool: Start decode
08-24 14:31:38.151  7058  7162 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-24 14:31:38.153   329  1387 V MediaPlayerService: decode(22, 10857164, 17813)
08-24 14:31:38.153   329  1387 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-24 14:31:38.153   329  1387 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-24 14:31:38.153   329  1387 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-24 14:31:38.153   329  1387 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-24 14:31:38.153   329  1387 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-24 14:31:38.153   329  1387 V MediaPlayerService: player type = 3
08-24 14:31:38.153   329  1387 V AwesomePlayer: AwesomePlayer create()
08-24 14:31:38.154   329  1387 V AwesomePlayer: reset_l() 
08-24 14:31:38.154   329  1387 V AwesomePlayer: cancelPlayerEvents
08-24 14:31:38.154   329  1387 V AwesomePlayer: setAudioSink() 
08-24 14:31:38.154   329  1387 V AwesomePlayer: reset_l() 
08-24 14:31:38.154   329  1387 V AudioCache: notify(0xb04096c0, 8, 0, 0)
08-24 14:31:38.154   329  1387 V AudioCache: ignored
08-24 14:31:38.154   329  1387 V AwesomePlayer: cancelPlayerEvents
08-24 14:31:38.154   329  1387 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-24 14:31:38.155   329  1387 V AwesomePlayer: setDataSource_l dataSource
08-24 14:31:38.155   329  1387 V LGParserOSAL: SniffLGParser start
08-24 14:31:38.155   329  1387 V LGParserOSAL: MainType:5, SubType=0
08-24 14:31:38.155   329  1387 V LGParserOSAL: #### check Mime : application/ogg
08-24 14:31:38.155   329  1387 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-24 14:31:38.155   329  1387 E MediaExtractor: Use LGExtractor :application/ogg 
08-24 14:31:38.156  7058  7058 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-24 14:31:38.157  6874  6874 D UEI.SmartControl: QS Service created
08-24 14:31:38.157  7058  7058 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 14:31:38.158  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-24 14:31:38.170  7058  7058 V LGMDMManager: Create singleton instance
08-24 14:31:38.188  6874  6874 I UEI.SmartControl: Service initServices...
08-24 14:31:38.189  6874  6874 D UEI.SmartControl: QS start get config
08-24 14:31:38.203   329  1387 V LGParserOSAL: supported mime: application/ogg
08-24 14:31:38.203   329  1387 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-24 14:31:38.203   329  1387 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-24 14:31:38.203   329  1387 V AwesomePlayer: mBitrate = -1 bits/sec
08-24 14:31:38.203   329  1387 V AwesomePlayer: AudioTrack Setting
08-24 14:31:38.203   329  1387 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-24 14:31:38.203   329  1387 V AwesomePlayer: setAudioSource() 
08-24 14:31:38.203   329  1387 V MediaPlayerService: prepare
08-24 14:31:38.203   329  1387 V AwesomePlayer: prepareAsync_l() 
08-24 14:31:38.203   329  1387 V MediaPlayerService: wait for prepare
08-24 14:31:38.203   329  7163 V AwesomePlayer: onPrepareAsyncEvent() 
08-24 14:31:38.203   329  7163 V AwesomePlayer: initAudioDecoder() 
08-24 14:31:38.203   329  7163 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 14:31:38.203   329  7163 V AudioSystem: isOffloadSupported()
08-24 14:31:38.203   329  7163 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 14:31:38.204   329  7163 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 14:31:38.204   329  7163 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 14:31:38.204   329  7163 V AwesomePlayer: getUseOffload() = 0 
08-24 14:31:38.204   329  7163 V OMXCodec: OMXCodec::Create
08-24 14:31:38.204   329  7163 V OMXCodec: findMatchingCodecs()
08-24 14:31:38.204   329  7163 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-24 14:31:38.204   329  7163 V OMXCodec: matchingCodecs.size()=1
08-24 14:31:38.204   329  7163 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-24 14:31:38.205   329  7163 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-24 14:31:38.205   329  7163 V LGCodecAdapter: LG Codec Adapter start
08-24 14:31:38.205   329  7163 V OMXCodec: OMXCodec Createtor
08-24 14:31:38.205   329  7163 V OMXCodec: setComponentRole
08-24 14:31:38.206   329  7163 V OMXCodec: configureCodec protected=0
08-24 14:31:38.206   329  7163 V LGCodecAdapter: called getLGCodecSpecificData
08-24 14:31:38.206   329  7163 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-24 14:31:38.206   329  7163 V LGCodecOSAL: Called LGconfigureCodecMETA
08-24 14:31:38.206   329  7163 V LGCodecOSAL: Called LGconfigureCodecMSG
08-24 14:31:38.206   329  7163 V LGCodecOSAL: Not support LGCodec
08-24 14:31:38.206   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-24 14:31:38.206   329  7163 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-24 14:31:38.206   329  7163 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-24 14:31:38.207   329  7163 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-24 14:31:38.207   329  7163 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 14:31:38.207   329  7163 V AudioSystem: isOffloadSupported()
08-24 14:31:38.207   329  7163 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 14:31:38.207   329  7163 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-24 14:31:38.207   329  7163 V OMXCodec: init()
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-24 14:31:38.207   329  7163 V OMXCodec: allocateBuffers
08-24 14:31:38.207   329  7163 V OMXCodec: allocateBuffersOnPort portIndex=0
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
08-24 14:31:38.207   329  7163 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-24 14:31:38.207   329  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c01a0 on output port
08-24 14:31:38.207   329  7163 V OMXCodec: init() mAsyncCompletion wait!!! 
08-24 14:31:38.208   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-24 14:31:38.208   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 14:31:38.208   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-24 14:31:38.208   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-24 14:31:38.208   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-24 14:31:38.208   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-24 14:31:38.208   329  7163 V OMXCodec: init() mAsyncCompletion wait free! 
08-24 14:31:38.208   329  7163 V AwesomePlayer: finishAsyncPrepare_l() 
08-24 14:31:38.208   329  7163 V AudioCache: notify(0xb04096c0, 5, 0, 0)
08-24 14:31:38.208   329  7163 V AudioCache: ignored
08-24 14:31:38.208   329  7163 V AudioCache: notify(0xb04096c0, 1, 0, 0)
08-24 14:31:38.208   329  7163 V AudioCache: prepared
08-24 14:31:38.208   329  1387 V AudioCache: wait - success
08-24 14:31:38.208   329  1387 V MediaPlayerService: start
08-24 14:31:38.208   329  1387 V AwesomePlayer: play_l() 
08-24 14:31:38.208   329  1387 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-24 14:31:38.208   329  1387 V AwesomePlayer: createAudioPlayer_l
08-24 14:31:38.208   329  1387 V AwesomePlayer: seekAudioIfNecessary_l() 
08-24 14:31:38.208   329  1387 V AwesomePlayer: startAudioPlayer_l() 
08-24 14:31:38.208   329  1387 D AudioPlayer: start of Playback, useOffload 0
08-24 14:31:38.208   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-24 14:31:38.208   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-24 14:31:38.210   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-24 14:31:38.210   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-24 14:31:38.210   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-24 14:31:38.210   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-24 14:31:38.210   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-24 14:31:38.210   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044802976
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-24 14:31:38.211   329  7165 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on output port
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-24 14:31:38.211   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-24 14:31:3,8.212   329  1387 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-24 14:31:38.213   329  1387 V AudioCache: notify(0xb04096c0, 6, 0, 0)
08-24 14:31:38.213   329  1387 V AudioCache: ignored
08-24 14:31:38.213   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.213   329  7166 V AudioCache: memcpy(0xac300000, 0xb1782000, 4096)
08-24 14:31:38.214   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.214   329  7166 V AudioCache: memcpy(0xac301000, 0xb1782000, 4096)
08-24 14:31:38.215   329  1387 V MediaPlayerService: wait for playback complete
08-24 14:31:38.216   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.218   329  7166 V AudioCache: memcpy(0xac302000, 0xb1782000, 4096)
08-24 14:31:38.219   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.219   329  7166 V AudioCache: memcpy(0xac303000, 0xb1782000, 4096)
08-24 14:31:38.219   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.219   329  7166 V AudioCache: memcpy(0xac304000, 0xb1782000, 4096)
08-24 14:31:38.220   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.221   329  7166 V AudioCache: memcpy(0xac305000, 0xb1782000, 4096)
08-24 14:31:38.223   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.223   329  7166 V AudioCache: memcpy(0xac306000, 0xb1782000, 4096)
08-24 14:31:38.224   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.224   329  7166 V AudioCache: memcpy(0xac307000, 0xb1782000, 4096)
08-24 14:31:38.225   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.225   329  7166 V AudioCache: memcpy(0xac308000, 0xb1782000, 4096)
08-24 14:31:38.226   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.226   329  7166 V AudioCache: memcpy(0xac309000, 0xb1782000, 4096)
08-24 14:31:38.227   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.227   329  7166 V AudioCache: memcpy(0xac30a000, 0xb1782000, 4096)
08-24 14:31:38.227   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.227   329  7166 V AudioCache: memcpy(0xac30b000, 0xb1782000, 4096)
08-24 14:31:38.228   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.228   329  7166 V AudioCache: memcpy(0xac30c000, 0xb1782000, 4096)
08-24 14:31:38.228   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.228   329  7166 V AudioCache: memcpy(0xac30d000, 0xb1782000, 4096)
08-24 14:31:38.230   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.230   329  7166 V AudioCache: memcpy(0xac30e000, 0xb1782000, 4096)
08-24 14:31:38.230   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.230   329  7166 V AudioCache: memcpy(0xac30f000, 0xb1782000, 4096)
08-24 14:31:38.231   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.231   329  7166 V AudioCache: memcpy(0xac310000, 0xb1782000, 4096)
08-24 14:31:38.232   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.232   329  7166 V AudioCache: memcpy(0xac311000, 0xb1782000, 4096)
08-24 14:31:38.232   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.232   329  7166 V AudioCache: memcpy(0xac312000, 0xb1782000, 4096)
08-24 14:31:38.233   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.233   329  7166 V AudioCache: memcpy(0xac313000, 0xb1782000, 4096)
08-24 14:31:38.234   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.234   329  7166 V AudioCache: memcpy(0xac314000, 0xb1782000, 4096)
08-24 14:31:38.234   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.234   329  7166 V AudioCache: memcpy(0xac315000, 0xb1782000, 4096)
08-24 14:31:38.235   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.235   329  7166 V AudioCache: memcpy(0xac316000, 0xb1782000, 4096)
08-24 14:31:38.236   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.236   329  7166 V AudioCache: memcpy(0xac317000, 0xb1782000, 4096)
08-24 14:31:38.236   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.236   329  7166 V AudioCache: memcpy(0xac318000, 0xb1782000, 4096)
08-24 14:31:38.237   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.237   329  7166 V AudioCache: memcpy(0xac319000, 0xb1782000, 4096)
08-24 14:31:38.238   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.238   329  7166 V AudioCache: memcpy(0xac31a000, 0xb1782000, 4096)
08-24 14:31:38.238   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.238   329  7166 V AudioCache: memcpy(0xac31b000, 0xb1782000, 4096)
08-24 14:31:38.239   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.239   329  7166 V AudioCache: memcpy(0xac31c000, 0xb1782000, 4096)
,08-24 14:31:38.240   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.240   329  7166 V AudioCache: memcpy(0xac31d000, 0xb1782000, 4096)
08-24 14:31:38.240   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.240   329  7166 V AudioCache: memcpy(0xac31e000, 0xb1782000, 4096)
08-24 14:31:38.240   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.240   329  7166 V AudioCache: memcpy(0xac31f000, 0xb1782000, 4096)
08-24 14:31:38.241  7135  7135 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:38.241   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.241   329  7166 V AudioCache: memcpy(0xac320000, 0xb1782000, 4096)
08-24 14:31:38.242   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.242   329  7166 V AudioCache: memcpy(0xac321000, 0xb1782000, 4096)
08-24 14:31:38.242  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-24 14:31:38.242   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.243   329  7166 V AudioCache: memcpy(0xac322000, 0xb1782000, 4096)
08-24 14:31:38.243   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.243  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-24 14:31:38.243   329  7166 V AudioCache: memcpy(0xac323000, 0xb1782000, 4096)
08-24 14:31:38.244   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.244   329  7166 V AudioCache: memcpy(0xac324000, 0xb1782000, 4096)
08-24 14:31:38.245   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.245   329  7166 V AudioCache: memcpy(0xac325000, 0xb1782000, 4096)
08-24 14:31:38.246  7135  7135 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 14:31:38.246  7135  7135 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 14:31:38.246   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.246   329  7166 V AudioCache: memcpy(0xac326000, 0xb1782000, 4096)
08-24 14:31:38.246  7135  7135 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 14:31:38.247   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.247   329  7166 V AudioCache: memcpy(0xac327000, 0xb1782000, 4096)
08-24 14:31:38.247  7135  7135 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:38.247  7135  7135 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-24 14:31:38.247  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2455
08-24 14:31:38.247   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.247   329  7166 V AudioCache: memcpy(0xac328000, 0xb1782000, 4096)
08-24 14:31:38.248   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.248   329  7166 V AudioCache: memcpy(0xac329000, 0xb1782000, 4096)
08-24 14:31:38.249   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.249   329  7166 V AudioCache: memcpy(0xac32a000, 0xb1782000, 4096)
08-24 14:31:38.249   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.249   329  7166 V AudioCache: memcpy(0xac32b000, 0xb1782000, 4096)
08-24 14:31:38.250   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.250   329  7166 V AudioCache: memcpy(0xac32c000, 0xb1782000, 4096)
08-24 14:31:38.251   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.251   329  7166 V AudioCache: memcpy(0xac32d000, 0xb1782000, 4096)
08-24 14:31:38.251   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.251   329  7166 V AudioCache: memcpy(0xac32e000, 0xb1782000, 4096)
08-24 14:31:38.252   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.252   329  7166 V AudioCache: memcpy(0xac32f000, 0xb1782000, 4096)
08-24 14:31:38.253  7075  7075 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-24 14:31:38.253   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.253   329  7166 V AudioCache: memcpy(0xac330000, 0xb1782000, 4096)
08-24 14:31:38.254   329  7166 V AudioCache: write(0xb1782000, 4096)
08-24 14:31:38.254   329  7166 V AudioCache: memcpy(0xac331000, 0xb1782000, 4096)
08-24 14:31:38.255   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-24 14:31:38.255   329  7166 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-24 14:31:38.255   329  7166 V AwesomePlayer: postAudioEOS() 
08-24 14:31:38.255   329  7166 V AudioCache: write(0xb1782000, 280)
08-24 14:31:38.255   329  7166 V AudioCache: memcpy(0xac332000, 0xb1782000, 280)
08-24 14:31:38.256   329  7163 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-24 14:31:38.256   329  7163 V AwesomePlayer: onStreamDone
08-24 14:31:38.256   329  7163 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-24 14:31:38.256   329  7163 V AudioCache: notify(0xb04096c0, 2, 0, 0)
08-24 14:31:38.256   329  7163 V AudioCache: playback complete
08-24 14:31:38.256   329  7163 V AwesomePlayer: pause_l() 
08-24 14:31:38.256   329  7163 V AudioCache: notify(0xb04096c0, 7, 0, 0)
08-24 14:31:38.256   329  7163 V AudioCache: ignored
08-24 14:31:38.256   329  7163 V AwesomePlayer: cancelPlayerEvents
08-24 14:31:38.256   329  1387 V AudioCache: wait - success
08-24 14:31:38.256   329  1387 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-24 14:31:38.257   329  7163 D AudioPlayer: Pause Playback at 1068125
08-24 14:31:38.257   329  1387 V AwesomePlayer: reset_l() 
08-24 14:31:38.257   329  1387 V AudioCache: notify(0xb04096c0, 8, 0, 0)
08-24 14:31:38.257   329  1387 V AudioCache: ignored
08-24 14:31:38.257   329  1387 V AwesomePlayer: cancelPlayerEvents
08-24 14:31:38.257   329  1387 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-24 14:31:38.257   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-24 14:31:38.257   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-24 14:31:38.257   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-24 14:31:38.257   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 1
08-24 14:31:38.257   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-24 14:31:38.258   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-24 14:31:38.258   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-24 14:31:38.258   329  7165 V OMXCodec: [OMX.google.vorbis.decoder], freeing buffer 0xb54f7f10 on port 1
08-24 14:31:38.258   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-24 14:31:38.258   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f60 on port 1
08-24 14:31:38.258   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 14:31:38.258   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-24 14:31:38.258   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-24 14:31:38.258   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-24 14:31:38.258   329  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-24 14:31:38.258   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-24 14:31:38.258   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-24 14:31:38.258   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-24 14:31:38.259   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-24 14:31:38.259   329  1387 D AudioPlayer: AudioPlayer releasing audio source
08-24 14:31:38.259   329  1387 D AudioPlayer: AudioPlayer done releasing audio source
08-24 14:31:38.259   329  1387 V AwesomePlayer: reset_l() 
08-24 14:31:38.259   329  1387 V AwesomePlayer: cancelPlayerEvents
08-24 14:31:38.259   329  1387 V AwesomePlayer: ~AwesomePlayer call
08-24 14:31:38.259   329  1387 V AwesomePlayer: reset_l() 
08-24 14:31:38.259   329  1387 V AwesomePlayer: cancelPlayerEvents
08-24 14:31:38.260  7058  7162 V SoundPool: close(31)
08-24 14:31:38.260  7058  7162 V SoundPool: pointer = 0x9fe55000, size = 205080, sampleRate = 48000, numChannels = 2
08-24 14:31:38.478  6874  6874 I UEI.SmartControl: Supports setup maps: true
08-24 14:31:38.481  6874  6874 D UEI.SmartControl: QS start statue = true Error code = 0
08-24 14:31:38.481  6874  6874 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-24 14:31:38.481  6874  6874 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-24 14:31:38.481  6874  6874 I UEI.SmartControl: ### init IR Blaster...
,08-24 14:31:38.486  6874  6874 D serial_port: Configuring serial port
,08-24 14:31:38.487  6874  6874 E UEI.SmartControl: UEIBLaster setting for 616
08-24 14:31:38.487  6874  6874 I UEI.SmartControl: Setting serial record hearder size = 2
08-24 14:31:38.487  6874  6874 I UEI.SmartControl: configuring settings for MAXQ616
,08-24 14:31:38.487  6874  6874 I UEI.SmartControl: Get version...
08-24 14:31:38.505  6874  7168 D UEI.SmartControl: serial port data available: 21
,08-24 14:31:38.532  6874  6874 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-24 14:31:38.532  6874  6874 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-24 14:31:38.532  6874  6874 I UEI.SmartControl: QS saving settings...
08-24 14:31:38.533  6874  6874 D UEI.SmartControl: IR Blaster version: 25672567
,08-24 14:31:38.550  6874  7168 D UEI.SmartControl: serial port data available: 4
,08-24 14:31:38.583  6874  7174 I UEI.SmartControl: Device manager: loading config....
08-24 14:31:38.583  6874  7174 D UEI.SmartControl: ----------- loading internal config...
,08-24 14:31:38.589  6874  6874 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-24 14:31:38.593  6874  6874 E UEI.SmartControl: Services init done
08-24 14:31:38.593  6874  6874 D UEI.SmartControl: QS Service init finished
08-24 14:31:38.594  6874  6874 D UEI.SmartControl: QS Service version name: 2.1.91
08-24 14:31:38.594  6874  6874 D UEI.SmartControl: QS Service version code: 201091
08-24 14:31:38.596  6874  6874 D UEI.SmartControl: Service requested: Control
08-24 14:31:38.598  6874  7174 E UEI.SmartControl: Loading SETTINGS...
08-24 14:31:38.601  6874  6874 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-24 14:31:38.606  6874  6874 D UEI.SmartControl: Internal service binding...
08-24 14:31:38.607  7058  7058 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-24 14:31:38.608  6874  6889 I UEI.SmartControl: ------ IControl API: 11
08-24 14:31:38.609  6874  6889 D UEI.SmartControl: File observer start...
08-24 14:31:38.609  6874  7174 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-24 14:31:38.609  6874  6889 E UEI.SmartControl: IR Port is disabled: false
08-24 14:31:38.610  6874  6889 D UEI.SmartControl: Starting file observer...
08-24 14:31:38.610  6874  6889 I UEI.SmartControl: Registering callback...
08-24 14:31:38.611  6874  6908 I UEI.SmartControl: ------ IControl API: 19
08-24 14:31:38.613  6874  6908 I UEI.SmartControl: Registering Services Ready callback...
08-24 14:31:38.620  6874  7173 I UEI.SmartControl: Notify AllClients services are ready: 0
08-24 14:31:38.621  7058  7073 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-24 14:31:38.622  7058  7160 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-24 14:31:38.622  7058  7160 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-24 14:31:38.623  7058  7058 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-24 14:31:38.623  7058  7058 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-24 14:31:38.623  6874  6891 I UEI.SmartControl: ------ IControl API: 8
,08-24 14:31:38.625  6874  7173 D UEI.SmartControl: -----service ready thread exits
08-24 14:31:38.625  7058  7058 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-24 14:31:38.625  7058  7058 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-24 14:31:38.626  7058  7058 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-24 14:31:38.626  7058  7058 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-24 14:31:38.627  7058  7058 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-24 14:31:38.627  7058  7058 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-24 14:31:38.629  7058  7058 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-24 14:31:38.636  7058  7058 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-24 14:31:38.637  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-24 14:31:38.638  7058  7058 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 14:31:38.639  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-24 14:31:38.640  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-24 14:31:38.641  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-24 14:31:38.641  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-24 14:31:38.642  7058  7058 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472041898642]
08-24 14:31:38.655  7058  7058 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-24 14:31:38.657  1036  1967 I ActivityManager: Killing 6120:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-24 14:31:38.690  7058  7179 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-24 14:31:38.765  1036  1967 I ActivityManager: Killing 6589:com.lge.email/u0a23 (adj 15): empty #18
,08-24 14:31:38.823  1036  1052 W libprocessgroup: failed to open /acct/uid_10027/pid_6120/cgroup.procs: No such file or directory
,08-24 14:31:38.839  1036  1051 W libprocessgroup: failed to open /acct/uid_10023/pid_6589/cgroup.procs: No such file or directory
,08-24 14:31:38.842  7058  7058 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-24 14:31:38.852  7058  7058 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 14:31:38.854  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-24 14:31:38.858  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-24 14:31:38.859  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-24 14:31:38.859  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-24 14:31:38.861  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-24 14:31:38.874  7058  7058 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-24 14:31:39.439  1036  1915 D WifiServiceImplEx: setWifiEnabled: true pid=6702, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-24 14:31:39.440  1036  1915 D WifiService: setWifiEnabled: true pid=6702, uid=10118
08-24 14:31:39.440  1036  1915 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 14:31:39.463  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-24 14:31:39.463  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-24 14:31:39.463  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-24 14:31:39.465  1036  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-24 14:31:39.465  1036  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-24 14:31:39.468  1036  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-24 14:31:39.468  1036  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-24 14:31:39.468  1036  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin],
08-24 14:31:39.468  1036  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 14:31:39.468  1036  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,08-24 14:31:39.468  1036  1540 E WifiHW  : unknown target_country: EU , set to default
08-24 14:31:39.468  1036  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-24 14:31:39.468  1036  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-24 14:31:39.468  1036  1540 I WifiUtil: gEnableBmps=1
,08-24 14:31:39.585  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:39.605  1036  1097 D Tethering: MasterInitialState.processMessage what=3
,08-24 14:31:39.612  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:39.618  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:39.623  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:39.630  1036  1388 V AlarmManager: ELAPSED_WAKEUP set : Alarm{248f178c type 2 when 131692 com.google.android.gms} when 131692
,08-24 14:31:39.634  1036  1097 D Tethering: MasterInitialState.processMessage what=3
08-24 14:31:39.637  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 14:31:39.640  6492  6522 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 14:31:39.649  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:39.652  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:39.662  5872  5872 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-24 14:31:39.670  5872  5872 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-24 14:31:39.681  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:39.709  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:39.751  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:39.781  1036  1968 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7205 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-24 14:31:39.786  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:39.786  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 14:31:39.852  1036  1388 V AlarmManager: ELAPSED_WAKEUP set : Alarm{254ef6ea type 2 when 131933 com.google.android.gms} when 131933
,08-24 14:31:39.875  7205  7205 I AppUp4:AppBoxCP: onCreate
08-24 14:31:39.876  7205  7205 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-24 14:31:39.887  7205  7205 I AppUp4:DB:  setFingerPrint start
08-24 14:31:39.887  7205  7205 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-24 14:31:39.896  7205  7205 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-24 14:31:39.896  7205  7205 I AppUp4:DB:  SDK version = 21
08-24 14:31:39.896  7205  7205 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-24 14:31:39.898  7205  7205 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-24 14:31:39.900  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 14:31:39.900  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:39.902  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 14:31:39.903  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-24 14:31:39.912  7205  7205 I AppUp4:CustModeStarterReceiver: onReceive
08-24 14:31:39.957  7205  7205 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:39.957  7205  7205 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:31:39.973  7205  7205 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30e91578
,08-24 14:31:39.973  7205  7205 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 14:31:39.973  7205  7205 D AppUp4:CustFacade: isPhone : true
08-24 14:31:39.975  7205  7205 D AppUp4:CustModeStarterReceiver: begin check event
08-24 14:31:39.976  7205  7205 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-24 14:31:39.977  7205  7205 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-24 14:31:39.979  7205  7223 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-24 14:31:39.980  7205  7223 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-24 14:31:39.980  7205  7223 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-24 14:31:39.983  1036  2039 I ActivityManager: Killing 6627:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-24 14:31:40.019  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:40.020  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 14:31:40.021  1036  2052 W libprocessgroup: failed to open /acct/uid_10061/pid_6627/cgroup.procs: No such file or directory
08-24 14:31:40.022  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 14:31:40.029  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:40.032  4787  7234 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 14:31:40.037  4787  7235 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:40.037  4787  7235 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-24 14:31:40.098  1036  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7236 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-24 14:31:40.123   361   361 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 475us total 21.941ms
,08-24 14:31:40.145   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 21.326ms
,08-24 14:31:40.167  1036  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-24 14:31:40.168   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 20.589ms
08-24 14:31:40.173  1036  1097 D Tethering: InitialState.processMessage what=4
08-24 14:31:40.175  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 14:31:40.188   325   895 D SoftapController: Softap fwReload - Ok
,08-24 14:31:40.189  1036  1540 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (714ms)
08-24 14:31:40.193   325   895 D CommandListener: Setting iface cfg
08-24 14:31:40.193   325   895 D CommandListener: Trying to bring down wlan0
08-24 14:31:40.194   325   895 D CommandListener: Clearing all IP addresses on wlan0
08-24 14:31:40.199  1036  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-24 14:31:40.203  7254  7254 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 14:31:40.203  7254  7254 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:40.225  7236  7236 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 14:31:40.226  7236  7236 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 14:31:40.227  7236  7236 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 14:31:40.227  7236  7236 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 14:31:40.240  7254  7254 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-24 14:31:40.271  7254  7254 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 14:31:40.272  7254  7254 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-24 14:31:40.300  1036  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 14:31:40.300  1036  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 14:31:40.300  1036  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 14:31:40.300  1036  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-24 14:31:40.300  1036  1540 D WifiMonitor: connecting to supplicant
08-24 14:31:40.302  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:40.302  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-24 14:31:40.306  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:40.307  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-24 14:31:40.308  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:40.311  7236  7236 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-24 14:31:40.330  7236  7236 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-24 14:31:40.335  7254  7254 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 14:31:40.385  7236  7236 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 14:31:40.422  7236  7236 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:40.422  7236  7236 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:31:40.440  7254  7254 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-24 14:31:40.450  7254  7254 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-24 14:31:40.451  7254  7254 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-24 14:31:40.452  1036  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-24 14:31:40.452  1036  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,08-24 14:31:40.453  1036  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-24 14:31:40.453  1036  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-24 14:31:40.454  1036  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-24 14:31:40.454  1036  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:40.454  1036  7257 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=],
,08-24 14:31:40.455  1036  7257 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 14:31:40.455  1036  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0,
08-24 14:31:40.455  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,08-24 14:31:40.455  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-24 14:31:40.455  1036  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0,
08-24 14:31:40.455  1036  7257 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-24 14:31:40.455  1036  7257 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED ,
08-24 14:31:40.456  1036  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,08-24 14:31:40.456  1036  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR],
08-24 14:31:40.456  1036  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,08-24 14:31:40.456  1036  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
,08-24 14:31:40.456  1036  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-24 14:31:40.457  1036  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 14:31:40.457  1036  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 14:31:40.457  1036  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 14:31:40.457  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:40.458  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:31:40.458  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:40.458  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:40.458  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 14:31:40.459  1036  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
08-24 14:31:40.459  1036  1540 D WifiNative-wlan0: SET update_config 1: returned true
08-24 14:31:40.459  1036  1540 D WifiConfigStore: Loading config and enabling all networks 
08-24 14:31:40.459  1036  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,08-24 14:31:40.460  1036  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-24 14:31:40.463  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:40.467  1036  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-24 14:31:40.468  1969  1969 D WfdService: Waiting for WifiP2p enabling
08-24 14:31:40.475  1036  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-24 14:31:40.475  1036  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-24 14:31:40.477  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:40.477  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:40.477  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:40.477  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:40.477  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:40.477  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:40.477  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:40.477  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:40.477  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:31:40.478  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:40.478  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:40.478  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-24 14:31:40.479  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-24 14:31:40.479  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:40.479  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:40.479  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:40.479  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:40.479  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:40.479  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:40.479  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:40.479  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:40.479  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:31:40.480  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:40.480  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:40.481  1036  1540 D WifiStateMachine: enableVerboseLogging : level 2
08-24 14:31:40.481  1036  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-24 14:31:40.482  1036  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-24 14:31:40.482  1036  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-24 14:31:40.482  1036  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-24 14:31:40.482  1036  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-24 14:31:40.483  1036  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-24 14:31:40.483  1036  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-24 14:31:40.483  1036  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-24 14:31:40.483  1036  1540 D WifiNative-wlan0: doBoolean: SET s,erial_number LGD855a6933058
08-24 14:31:40.484  1036  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-24 14:31:40.484  1036  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-24 14:31:40.484  1036  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-24 14:31:40.484  1036  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-24 14:31:40.485  1036  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-24 14:31:40.486  1036  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 14:31:40.486  1036  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-24 14:31:40.486  1969  1969 D WfdsService: Supplicant Connection state is changed : true
08-24 14:31:40.486  1969  2299 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-24 14:31:40.486  1969  2299 D WfdsService: Set the WFDS Monitor: true
08-24 14:31:40.486  1969  2299 D WfdsMonitor: WfdsMonitorThread create
08-24 14:31:40.486  1036  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-24 14:31:40.486  1036  1540 D WifiNative-HAL: Setting external_sim to 1
08-24 14:31:40.486  1036  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-24 14:31:40.486  1969  2299 D WfdsMonitor: WFDS Monitor is created and started
08-24 14:31:40.486  1969  2299 D WfdsService: WiFi: Supplicant connection re-established
08-24 14:31:40.487  1036  1540 D WifiNative-wlan0: SET external_sim 1: returned true
08-24 14:31:40.487  1036  1540 I WifiNative-HAL: startHal
08-24 14:31:40.487  1036  1540 D wifi    : setting scan oui 0xaf724320
08-24 14:31:40.487  1969  7260 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-24 14:31:40.487  1036  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 14:31:40.487  1036  1540 I WifiNative-HAL: startHal
08-24 14:31:40.488  1036  1540 D wifi    : setting scan oui 0xaf724320
08-24 14:31:40.488  1969  7260 E CtrlSupplicant: Succeed to open control connection
08-24 14:31:40.488  1036  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-24 14:31:40.488  1969  7260 E CtrlSupplicant: Succeed to open monitor connection
08-24 14:31:40.488  1036  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-24 14:31:40.488  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-24 14:31:40.488  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-24 14:31:40.489  1036  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-24 14:31:40.489  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP,
,08-24 14:31:40.489  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 14:31:40.489  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 14:31:40.489  1969  7260 D WfdsMonitor: Supplicant connection established
,08-24 14:31:40.489  1969  2299 D WfdsService: Connected to the supplicant for wfds
08-24 14:31:40.489  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-24 14:31:40.490  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-24 14:31:40.490  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-24 14:31:40.490  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 14:31:40.490  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 14:31:40.490  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 14:31:40.490  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 14:31:40.490  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 14:31:40.491  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 14:31:40.491  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-24 14:31:40.491  7254  7254 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-24 14:31:40.491  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-24 14:31:40.491  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 14:31:40.491  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 14:31:40.492  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 14:31:40.492  1036  1540 E WifiNative: : [132,573,715 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-24 14:31:40.492  1036  1540 D WifiNative-wlan0: doBoolean: RECONNECT
08-24 14:31:40.493  1036  1540 D WifiNative-wlan0: RECONNECT: returned true
08-24 14:31:40.493  1036  1540 D WifiNative-wlan0: doString: [STATUS]
08-24 14:31:40.493  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-24 14:31:40.493  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-24 14:31:40.493  1036  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 14:31:40.493  1036  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 14:31:40.494  1036  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 14:31:40.494  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.495  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3,
08-24 14:31:40.495  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-24 14:31:40.495  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.495  1036  1557 I WifiNative-HAL: startHal
08-24 14:31:40.495  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf724320
08-24 14:31:40.496  1036  1557 D wifi    : failed to get capabilities : -3
08-24 14:31:40.496   325   895 D CommandListener: Setting iface cfg
08-24 14:31:40.496  1036  1557 E WifiScanningService: could not get scan capabilities
08-24 14:31:40.496   325   895 D CommandListener: Trying to bring up p2p0
08-24 14:31:40.496  1036  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.496  1036  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-24 14:31:40.496  1036  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-24 14:31:40.496  1036  1538 D LGWifiP2pService: P2pEnablingState
08-24 14:31:40.496  1036  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.496  1036  1538 D LGWifiP2pService: P2p socket connection successful
08-24 14:31:40.496  1036  1538 D LGWifiP2pService: P2pEnabledState
08-24 14:31:40.496  1036  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-24 14:31:40.496  1036  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-24 14:31:40.497  1036  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-24 14:31:40.497  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-24 14:31:40.497  1969  1969 D WfdsService: WifiP2pState is changed : true
08-24 14:31:40.497  1969  2299 D WfdsService: Receive the WFDS_ENABLE Method
08-24 14:31:40.497  1969  2299 D WfdsService: Set the WFDS Monitor: true
08-24 14:31:40.497  1036  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-24 14:31:40.497  1036  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-24 14:31:40.497  1969  2299 D WfdsService: Connected to the supplicant for wfds
08-24 14:31:40.497  1969  2299 D WfdsJNI : doCommand: WFDS_SET TRUE
08-24 14:31:40.497  7254  7254 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-24 14:31:40.498  1969  2299 D WfdsService: selectPreferredScanChannel [36]
08-24 14:31:40.498  1969  2299 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-24 14:31:40.498  1036  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-24 14:31:40.498  1036  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-24 14:31:40.499  1036  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-24 14:31:40.499  1036  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-24 14:31:40.499  7254  7254 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-24 14:31:40.499  1036  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-24 14:31:40.499  1969  1969 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-24 14:31:40.499  1036  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-24 14:31:40.500  1969  1969 D WfdsService: isConnected: false
08-24 14:31:40.500  1036  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-24 14:31:40.500  1036  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-24 14:31:40.500  7254  7254 E wpa_supplicant: disconnect_rssi_lvl: -100
08-24 14:31:40.500  1036  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-24 14:31:40.500  1036  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-24 14:31:40.500  1036  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-24 14:31:40.501  1036  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-24 14:31:40.501  1036  1538 D WifiNative-p2p0: SET device_name G3: returned true
,08-24 14:31:40.501  1036  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-24 14:31:40.501  1036  1538 D LGWifiP2pService: before postfix = G3
08-24 14:31:40.501  1036  1538 D WifiServerServiceExt: postfix byte check : 2
08-24 14:31:40.501  1036  1538 D LGWifiP2pService: after postfix = G3
08-24 14:31:40.501  1036  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-24 14:31:40.501  1036  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-24 14:31:40.501  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-24 14:31:40.501  1036  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-24 14:31:40.501  1036  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-24 14:31:40.502  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 14:31:40.503  7254  7254 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:40.503  7254  7254 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ,
08-24 14:31:40.503  7254  7254 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.504  7254  7254 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.505  1969  7260 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:40.505  1969  7260 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:40.505  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ],
08-24 14:31:40.505  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-24 14:31:40.506  1036  7257 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:40.506  1036  7257 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:40.506  1036  7257 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:40.506  1036  7257 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.506  1036  7257 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.506  1036  7257 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.506  1036  7257 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:40.506  1036  7257 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.506  1036  7257 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.506  1036  7257 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.507  1036  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-24 14:31:40.507  1036  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-24 14:31:40.507  1036  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-24 14:31:40.508  1036  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-24 14:31:40.508  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-24 14:31:40.508  1036  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-24 14:31:40.508  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-24 14:31:40.509  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-24 14:31:40.509  1036  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-24 14:31:40.509  1036  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-24 14:31:40.510  1969  1969 I WfdStateTracker: handleP2pThisDeviceChanged
08-24 14:31:40.510  1969  1969 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-24 14:31:40.510  1969  1969 D WfdsService: Update P2p Interface State: 3
08-24 14:31:40.511  1036  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-24 14:31:40.511  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-24 14:31:40.511  1036  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-24 14:31:40.511  1036  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-24 14:31:40.511  1036  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-24 14:31:40.512  1036  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-24 14:31:40.512  1036  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-24 14:31:40.512  1036  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-24 14:31:40.512  1036  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-24 14:31:40.512  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-24 14:31:40.519  1036  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-24 14:31:40.519  1036  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-24 14:31:40.519  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-24 14:31:40.519  1036  1538 D LGWifiP2pService: InactiveState
08-24 14:31:40.519  7254  7254 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 14:31:40.519  1036  1538 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.519  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.519  1036  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY C,Z
,08-24 14:31:40.520  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-24 14:31:40.520  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 14:31:40.520  1036  7257 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 14:31:40.520  1036  7257 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 14:31:40.520  1036  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-24 14:31:40.521  1036  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-24 14:31:40.522  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 14:31:40.522  7254  7254 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:40.522  1969  7260 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 14:31:40.523  1036  7257 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 14:31:40.523  1036  7257 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:40.523  1036  7257 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:40.523  1036  7257 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:40.523  7254  7254 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 14:31:40.523  7254  7254 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.523  1969  7260 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:40.523  1036  7257 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:40.523  1036  7257 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.523  1036  7257 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.523  1036  7257 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.524  7254  7254 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.524  1969  7260 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:40.524  1036  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-24 14:31:40.524  1036  7257 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:40.524  1036  7257 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.524  1036  7257 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.524  1036  1538 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.524  1036  7257 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:40.524  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.524  1036  1538 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.524  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.524  1036  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.524  1036  1538 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.524  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachi,ne$SmHandler }
08-24 14:31:40.524  1036  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-24 14:31:40.524  1036  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.525  1036  1540 D WifiNative-wlan0: doBoolean: SCAN
08-24 14:31:40.525  1036  1538 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.525  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.525  1036  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.525  1969  2299 W WfdsService: DefaultState - msg [9441285] is not handled
08-24 14:31:40.525  1036  1540 D WifiNative-wlan0: SCAN: returned false
08-24 14:31:40.525  1036  1538 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.525  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.525  1036  1538 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.525  1036  1036 E WifiServerServiceExt: No p2p device connected
08-24 14:31:40.525  1036  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=132607  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 14:31:40.528  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:40.528  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:40.528  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 14:31:40.528  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:40.528  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:40.528  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=132610  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 14:31:40.529  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:40.529  1036  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 14:31:40.529  1036  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 14:31:40.530  1036  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 14:31:40.530  1036  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 14:31:40.530  1036  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-24 14:31:40.531  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:40.531  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-24 14:31:40.542  7236  7236 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 14:31:40.563  7105  7262 W FormManager: Network not available. Please check & try again.
,08-24 14:31:40.564  3175  3175 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 14:31:40.564  3175  3175 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:40.565  3175  3175 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 14:31:40.570  7236  7236 I HubEmail: JNI_OnLoad()
08-24 14:31:40.570  7236  7236 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 14:31:40.570  7236  7236 I HubEmail: registerNatives()
08-24 14:31:40.571  7236  7236 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 14:31:40.571  7236  7236 I HubEmail: registerNativeMethods()
08-24 14:31:40.571  7236  7236 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 14:31:40.571  7236  7236 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-24 14:31:40.611  1036  1912 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7266 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-24 14:31:40.621  7105  7263 V FormManager: Network unavailable.
08-24 14:31:40.622  7236  7265 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:40.624  7105  7263 V FormManager: Network unavailable.
08-24 14:31:40.630  1036  1915 I ActivityManager: Killing 6766:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-24 14:31:40.686  1036  2019 W libprocessgroup: failed to open /acct/uid_10080/pid_6766/cgroup.procs: No such file or directory
,08-24 14:31:40.768  7266  7266 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:40.768  7266  7266 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:31:40.771  7266  7266 D PhoneMonitor: Register our PhoneStateListener
,08-24 14:31:40.787  7266  7266 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-24 14:31:40.789  7266  7266 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-24 14:31:40.813  7266  7266 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-24 14:31:40.815  7266  7266 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-24 14:31:40.817  7266  7266 D TelephonyAutoProfiling: [parse] Load xml
,08-24 14:31:40.824  7266  7266 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-24 14:31:40.824  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-24 14:31:40.824  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-24 14:31:40.825  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-24 14:31:40.825  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-24 14:31:40.825  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-24 14:31:40.825  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-24 14:31:40.825  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-24 14:31:40.825  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-24 14:31:40.825  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-24 14:31:40.825  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-24 14:31:40.826  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-24 14:31:40.826  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-24 14:31:40.826  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-24 14:31:40.826  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-24 14:31:40.826  7266  7266 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-24 14:31:40.826  7266  7266 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-24 14:31:40.841  7266  7266 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-24 14:31:40.857  1036  1968 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7285 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 14:31:40.858  1036  1968 I ActivityManager: Killing 6213:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-24 14:31:40.894  1036  2039 W libprocessgroup: failed to open /acct/uid_10097/pid_6213/cgroup.procs: No such file or directory
,08-24 14:31:41.051  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-24 14:31:41.051  1036  7257 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-24 14:31:41.052  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-24 14:31:41.052  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-24 14:31:41.052  7254  7254 E wpa_supplicant: USIM:  scard_init function
08-24 14:31:41.052  1036  7257 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-24 14:31:41.053  7254  7254 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-24 14:31:41.054  1036  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-24 14:31:41.055  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-24 14:31:41.055  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-24 14:31:41.057  1036  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-24 14:31:41.058  1036  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-24 14:31:41.059  1036  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-24 14:31:41.059  1036  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-24 14:31:41.139  1036  1949 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7303 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-24 14:31:41.142  1036  1949 I ActivityManager: Killing 6791:com.lge.eula/1000 (adj 15): empty #17
08-24 14:31:41.173  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-24 14:31:41.173  7254  7254 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-24 14:31:41.173  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-24 14:31:41.174  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-24 14:31:41.174  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-24 14:31:41.175  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 14:31:41.175  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-24 14:31:41.192  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 14:31:41.192  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-24 14:31:41.193  7254  7254 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 14:31:41.193  7254  7254 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 14:31:41.194  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-24 14:31:41.194  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 14:31:41.194  1036  7257 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 14:31:41.194  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-24 14:31:41.194  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 14:31:41.194  1036  7257 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 14:31:41.195  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 14:31:41.195  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 14:31:41.197  1036  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=133278  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 14:31:41.202  1036  1576 W libprocessgroup: failed to open /acct/uid_1000/pid_6791/cgroup.procs: No such file or directory
08-24 14:31:41.204  1036  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 14:31:41.205  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=133287  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 14:31:41.207  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:41.207  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:41.207  1036  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=133288  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 14:31:41.208  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=133289  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-24 14:31:41.209  1036  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=133290
08-24 14:31:41.209  1036  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=133291
08-24 14:31:41.210  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.211  1036  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=133293
08-24 14:31:41.212  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.212  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.212  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=133294
08-24 14:31:41.212  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 14:31:41.213  1036  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=133295
08-24 14:31:41.216  1036  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=133297  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 14:31:41.221  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.221  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.221  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-24 14:31:41.225  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=133307  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 14:31:41.226  1036  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=133307  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 14:31:41.227  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=133308  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 14:31:41.228  1036  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133309
08-24 14:31:41.228  1036  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133310
08-24 14:31:41.229  1036  1540 D WifiNative-wlan0: doString: [STATUS]
08-24 14:31:41.229  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 14:31:41.230  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 14:31:41.231  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:41.231  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:41.232  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.233  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.233  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.233  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 14:31:41.233  1036  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-24 14:31:41.234  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:41.234  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:41.235  1036  1540 I WifiServiceExtension: setVHTCapabilityType  : false
08-24 14:31:41.236  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.239  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.239  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.239  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-24 14:31:41.241  1036  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-24 14:31:41.241  1036  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-24 14:31:41.249  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.249  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.249  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 14:31:41.252  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:41.252  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:41.253  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.255  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:41.255  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:41.256  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.259  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.259  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.259  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 14:31:41.259  1036  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-24 14:31:41.260  1036  1546 D ConnectivityService: Got NetworkAgent Messenger
08-24 14:31:41.260  1036  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:31:41.260  1036  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 14:31:41.260  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-24 14:31:41.260  1036  1546 D ConnectivityService: NetworkAgent connected
08-24 14:31:41.260  1036  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 14:31:41.260  1036  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-24 14:31:41.267  1036  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 14:31:41.267  1036  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:31:41.267  1036  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 14:31:41.268  1036  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 14:31:41.268  1036  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 14:31:41.273  1036  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-24 14:31:41.274  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:41.274  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:41.275   325   895 D CommandListener: Setting iface cfg
08-24 14:31:41.276  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.326  1036  2003 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7322 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 14:31:41.327  1036  2003 I ActivityManager: Killing 6809:com.lge.bnr/1000 (adj 15): empty #17
,08-24 14:31:41.378  1036  1967 W libprocessgroup: failed to open /acct/uid_1000/pid_6809/cgroup.procs: No such file or directory
,08-24 14:31:41.393  1036  1540 E WifiStateMachine: Start Dhcp Watchdog 2
,08-24 14:31:41.393  1036  7321 D DhcpStateMachine: StoppedState
08-24 14:31:41.393  1036  7321 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:41.393  1036  7321 D DhcpStateMachine: WaitBeforeStartState
08-24 14:31:41.395  1036  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=133476  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 14:31:41.396  1036  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=133478  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 14:31:41.397  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=133478  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-24 14:31:41.398  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:41.398  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-24 14:31:41.399  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:41.399  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-24 14:31:41.400  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:41.401  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:41.401  1036  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:41.402  1036  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:41.402  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:41.402  1036  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:41.404  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:41.404  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-24 14:31:41.405  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:41.405  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-24 14:31:41.406  1036  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=133487  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 14:31:41.407  1036  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=133488  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 14:31:41.407  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=133489  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 14:31:41.409  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:86947] from screen [on:0 period:-1131881120] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 14:31:41.410  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1131881119] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 14:31:41.410  1036  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-24 14:31:41.414  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.417  1036  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-24 14:31:41.417  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.418  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.418  1036  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.418  1036  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.419  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.419  1036  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.420  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-24 14:31:41.420  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=94,0,0
08-24 14:31:41.421  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=94,0,0
08-24 14:31:41.421  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-24 14:31:41.421  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-24 14:31:41.422  1036  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-24 14:31:41.422  1036  1540 D WifiNative-wlan0: doBoolean: SET ps 0
08-24 14:31:41.422  1036  1540 D WifiNative-wlan0: SET ps 0: returned true
,08-24 14:31:41.422  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-24 14:31:41.423  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-24 14:31:41.423  1036  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-24 14:31:41.423  1036  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-24 14:31:41.423  1036  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 14:31:41.423  1036  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 14:31:41.423  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26cb1d9b target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:41.423  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26cb1d9b target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:41.424  1036  7321 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:41.424  1036  7321 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-24 14:31:41.424   325   895 D CommandListener: Setting iface cfg
08-24 14:31:41.424   325   895 D CommandListener: Trying to bring up wlan0
08-24 14:31:41.427  1036  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-24 14:31:41.428  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:41.428  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 14:31:41.429  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:41.429  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 14:31:41.429  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.430  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.430  7322  7322 I art     : Almond Protected OAT
08-24 14:31:41.430  1036  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.431  1036  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.431  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.431  1036  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:41.432  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-24 14:31:41.432  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 14:31:41.433  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 14:31:41.433  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 14:31:41.433  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:41.433  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 14:31:41.433  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:41.434  1036  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 14:31:41.434  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-24 14:31:41.434  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-24 14:31:41.435  1036  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-24 14:31:41.435  1036  1540 D WifiNative-wlan0: doBoolean: SET ps 1
,08-24 14:31:41.451  1036  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 14:31:41.452  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-24 14:31:41.452  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-24 14:31:41.453  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 14:31:41.453  1036  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-24 14:31:41.454  1036  1546 D ConnectivityService: ignoring duplicate network state non-change
08-24 14:31:41.456  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:41.456  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:41.459  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.459  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.459  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 14:31:41.461  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-24 14:31:41.462  1036  1546 D ConnectivityService: Adding iface wlan0 to network 101
08-24 14:31:41.463  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 14:31:41.470  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.470  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.470  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 14:31:41.473  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 14:31:41.478  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-24 14:31:41.481  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.481  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.481  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 14:31:41.483  1036  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-24 14:31:41.483  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 14:31:41.485  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.487  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:41.487  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 14:31:41.489  1036  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 14:31:41.489  1036  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-24 14:31:41.490  1036  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-24 14:31:41.490  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 14:31:41.490  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:41.490   325   895 E Netd    : netlink response contains error (File exists)
08-24 14:31:41.491  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.492  1036  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-24 14:31:41.493  1036  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-24 14:31:41.493  1036  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-24 14:31:41.493  1036  1546 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-24 14:31:41.494  1036  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 14:31:41.494  1036  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-24 14:31:41.496  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:41.496  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 14:31:41.496  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.497  1036  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-24 14:31:41.497  1036  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-24 14:31:41.497  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:41.497  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-24 14:31:41.497  1036  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 14:31:41.497  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:41.497  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:41.497  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 14:31:41.497  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-24 14:31:41.497  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:41.497  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
,08-24 14:31:41.497  1036  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-24 14:31:41.497  1036  1546 D ConnectivityService:    accepting network in place of null
08-24 14:31:41.497  1036  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:41.498  1036  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:41.498  1036  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 14:31:41.498  1875  1875 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:41.499  1875  1875 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 14:31:41.499  1036  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-24 14:31:41.499  1036  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-24 14:31:41.499  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 14:31:41.500  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-24 14:31:41.501  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:41.501   325  7342 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-24 14:31:41.501  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 14:31:41.501  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.502  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 14:31:41.502  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 14:31:41.502  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 14:31:41.504  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:41.504  1036  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-24 14:31:41.506  1036  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-24 14:31:41.508  1036  1546 D ConnectivityService: validation of new default Network = false
08-24 14:31:41.508  1036  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-24 14:31:41.508  1036  1546 D DSQN    : enableDataServiceNotify 
08-24 14:31:41.508  1036  1546 D DSQN    : start dsqn bin
08-24 14:31:41.513  7343  7343 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:41.513  7343  7343 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 14:31:41.517  1036  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-24 14:31:41.518  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:41.518  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:41.518  1036  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:41.519  1036  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-24 14:31:41.519  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 14:31:41.527  7343  7343 E DSQN    : DSQN ssw
,08-24 14:31:41.531  7322  7322 D WeatherApplication: removeAccount
08-24 14:31:41.532  7322  7322 D WeatherApplication: Account.length = 0
08-24 14:31:41.532  7322  7322 E WeatherApplication: OPERATOR:OPEN
08-24 14:31:41.533  1817  7344 I CheckinService: active receiver: enabled
08-24 14:31:41.537  7322  7322 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:41
08-24 14:31:41.538  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:41.538  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:41.538  1036  1538 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 14:31:41.542  1817  7344 I CheckinService: Preparing to send checkin request
08-24 14:31:41.542  1817  7344 I EventLogService: Accumulating logs since 1472041810893
08-24 14:31:41.543  7322  7322 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 14:31:41.543  7322  7322 D Weather.Utils: 2 : All the weather widget is gone.
08-24 14:31:41.545  7322  7322 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 14:31:41.547  7322  7322 D WeatherAncestor: connectivity changed - connection : true
08-24 14:31:41.548  7322  7322 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-24 14:31:41.548  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 14:31:41.549  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.549   325  7342 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-24 14:31:41.550  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.553  7322  7322 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 14:31:41.554  7322  7322 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 14:31:41.554  7322  7322 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-24 14:31:41.561  1036  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 14:31:41.561  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 14:31:41.562  1036  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 14:31:41.562  1036  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 14:31:41.562  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 14:31:41.562  1036  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 14:31:41.567  7322  7322 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 14:31:41.567  7322  7322 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:41
08-24 14:31:41.583   325  7342 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-24 14:31:41.605  1036  2039 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7350 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 14:31:41.606  1036  2039 I ActivityManager: Killing 2222:com.lge.music/u0a34 (adj 15): empty #17
,08-24 14:31:41.612   325   894 D LGDataListener: argv[0]=dsqncommand
08-24 14:31:41.612   325   894 D LGDataListener: argv[1]=wlan0
08-24 14:31:41.612   325   894 D LGDataListener: argv[2]=1
08-24 14:31:41.612   325   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-24 14:31:41.612  1036  1095 D DSQN    : DSQM DsqnNotification wlan0  1
08-24 14:31:41.612  1036  1095 D DSQN    : start to monitor internet connection
08-24 14:31:41.628  1036  7321 D DhcpStateMachine: DHCPV4 request on wlan0
,08-24 14:31:41.629   329  1386 V AudioFlinger: 2222 died, releasing its sessions
,08-24 14:31:41.629  1036  7321 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-24 14:31:41.629   329  1386 V AudioFlinger:  pid 1875 @ 0
08-24 14:31:41.629   329  1386 V AudioFlinger:  pid 3175 @ 1
08-24 14:31:41.629  1036  7321 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-24 14:31:41.629   329  1386 V AudioFlinger:  pid 3175 @ 2
08-24 14:31:41.623  7369  7369 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:41.623  7369  7369 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:41.641  7369  7369 I dhcpcd  : version 5.5.6 starting
08-24 14:31:41.642  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 12:31:41 GMT], X-Android-Received-Millis=[1472041901642], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472041901611]}
08-24 14:31:41.643  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-24 14:31:41.643  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-24 14:31:41.643  1036  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-24 14:31:41.643  1036  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-24 14:31:41.643  1036  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-24 14:31:41.643  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:41.643  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 14:31:41.643  7369  7369 E dhcpcd  : get_duid: m
08-24 14:31:41.643  7369  7369 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-24 14:31:41.643  1036  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-24 14:31:41.643  7369  7369 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-24 14:31:41.643  1036  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-24 14:31:41.643  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:41.643  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:41.644  1036  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:41.644  1036  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:41.644  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-24 14:31:41.644  1036  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:41.644  1036  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 14:31:41.645  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 14:31:41.645  1875  1875 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:41.646  1875  1875 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 14:31:41.659  1817  7344 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-24 14:31:41.660  1036  1968 W libprocessgroup: failed to open /acct/uid_10034/pid_2222/cgroup.procs: No such file or directory
,08-24 14:31:41.693  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-24 14:31:41.693  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.694  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:41.697  7369  7369 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-24 14:31:41.697  7369  7369 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 14:31:41.697  7369  7369 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 14:31:41.697  7369  7369 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-24 14:31:41.697  7369  7369 D dhcpcd  : wlan0: sending REQUEST (xid 0x9b85ebd), next in 3.92 seconds
08-24 14:31:41.733  7369  7369 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-24 14:31:41.736  7369  7369 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-24 14:31:41.736  7369  7369 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-24 14:31:41.736  7369  7369 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-24 14:31:41.737  7369  7369 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-24 14:31:41.737  7369  7369 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 14:31:41.737  7369  7369 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-24 14:31:41.737  7369  7369 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 14:31:41.737  7369  7369 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-24 14:31:41.772  1036  1968 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7380 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-24 14:31:41.810   281   356 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 14:31:41.811   281   356 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-24 14:31:41.811   281   356 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 14:31:41.811  7350  7401 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-24 14:31:41.813   281   356 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 14:31:41.813   281   356 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-24 14:31:41.813   281   356 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 14:31:41.813  7350  7401 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-24 14:31:41.822  7380  7380 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-24 14:31:41.822  7380  7380 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-24 14:31:41.844  7380  7380 I MultiDex: VM with version 2.1.0 has multidex support
,08-24 14:31:41.844  7380  7380 I MultiDex: install
,08-24 14:31:41.845  7380  7380 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-24 14:31:41.847   281   356 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 14:31:41.847   281   356 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-24 14:31:41.847   281   356 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 14:31:41.848  7350  7405 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-24 14:31:41.851   281   356 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 14:31:41.851   281   356 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-24 14:31:41.851   281   356 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 14:31:41.851  7350  7405 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-24 14:31:41.859  7380  7380 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-24 14:31:42.032  1036  7321 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-24 14:31:42.033  1036  7321 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-24 14:31:42.033  1036  7321 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 14:31:42.033  1036  7321 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-24 14:31:42.033  1036  7321 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-24 14:31:42.033  1036  7321 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 14:31:42.033  1036  7321 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-24 14:31:42.033  1036  7321 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-24 14:31:42.034  1036  7321 D DhcpStateMachine: RunningState
08-24 14:31:42.044  7350  7350 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-24 14:31:42.055  7350  7350 I LibraryLoader: Loading: webviewchromium
,08-24 14:31:42.059  7350  7350 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4149-4153)
08-24 14:31:42.059  7350  7350 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 14:31:42.067  7350  7350 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d7bda43}
08-24 14:31:42.069  7350  7350 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:31:42.069  7350  7350 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 14:31:42.080  7350  7350 I BrowserStartupController: Initializing chromium process, renderers=0
08-24 14:31:42.082  7350  7350 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:31:42.103  7380  7397 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:42.104  7380  7397 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:31:42.110  7350  7350 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-24 14:31:42.112   329   329 V AudioPolicyService: registerClient() client 0xb558a400, uid 10093
08-24 14:31:42.112  7350  7350 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-24 14:31:42.113  7350  7440 W AudioManagerAndroid: Requires BLUETOOTH permission
08-24 14:31:42.114  7350  7350 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-24 14:31:42.131  7350  7350 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 14:31:42.131  7350  7350 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 14:31:42.131  7350  7350 I Adreno-EGL: Build Date: 12/12/14 금
08-24 14:31:42.131  7350  7350 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 14:31:42.131  7350  7350 I Adreno-EGL: Remote Branch: 
08-24 14:31:42.131  7350  7350 I Adreno-EGL: Local Patches: 
08-24 14:31:42.131  7350  7350 I Adreno-EGL: Reconstruct Branch: 
,08-24 14:31:42.239  1036  1968 I art     : Explicit concurrent mark sweep GC freed 104765(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.205ms total 124.908ms
,08-24 14:31:42.265  7350  7350 I NSApplication: Starting up...
,08-24 14:31:42.327  1036  1967 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7455 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-24 14:31:42.329  1036  1967 I ActivityManager: Killing 6142:com.android.vending/u0a44 (adj 15): empty #17
08-24 14:31:42.374  7471  7471 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-24 14:31:42.403  1036  2070 W libprocessgroup: failed to open /acct/uid_10044/pid_6142/cgroup.procs: No such file or directory
08-24 14:31:42.436  7455  7455 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 14:31:42.457  7471  7471 I dex2oat : dex2oat took 82.685ms (threads: 4)
,08-24 14:31:42.467  1036  1052 D WifiServiceImplEx: setWifiEnabled: false pid=6702, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 14:31:42.467  1036  1052 D WifiService: setWifiEnabled: false pid=6702, uid=10118
08-24 14:31:42.467  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 14:31:42.477  7380  7397 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 14:31:42.477  7380  7397 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 14:31:42.477  7380  7397 I Adreno-EGL: Build Date: 12/12/14 금
08-24 14:31:42.477  7380  7397 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 14:31:42.477  7380  7397 I Adreno-EGL: Remote Branch: 
08-24 14:31:42.477  7380  7397 I Adreno-EGL: Local Patches: 
08-24 14:31:42.477  7380  7397 I Adreno-EGL: Reconstruct Branch: 
,08-24 14:31:42.489  1036  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 14:31:42.489  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 14:31:42.489  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 14:31:42.489  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 14:31:42.489  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-24 14:31:42.490  1036  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-24 14:31:42.490  1036  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-24 14:31:42.491  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-24 14:31:42.491  1036  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 14:31:42.491  1036  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:31:42.491  1036  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 14:31:42.491  1036  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 14:31:42.491  1036  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-24 14:31:42.509  1036  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-24 14:31:42.509  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 14:31:42.509  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.509  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.509  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 14:31:42.509  1036  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 14:31:42.510  1036  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 14:31:42.510  1036  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 14:31:42.511   325   895 D CommandListener: Clearing all IP addresses on wlan0
08-24 14:31:42.511  1036  7321 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.518  1036  1546 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-24 14:31:42.546  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 14:31:42.546  1036  1546 D ConnectivityService: ignoring duplicate network state non-change
08-24 14:31:42.546  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-24 14:31:42.548  1036  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.548  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.548  1036  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3d5476d6
08-24 14:31:42.548  1036  1538 D LGWifiP2pService: P2pDisablingState
,08-24 14:31:42.548  1036  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.548  1036  1538 D LGWifiP2pService: p2p socket connection lost
08-24 14:31:42.548  1036  1538 D LGWifiP2pService: P2pDisabledState
08-24 14:31:42.549  1036  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:42.549  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:42.549  1036  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:42.550  1036  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:42.550  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:42.550  1036  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:42.550  1036  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 14:31:42.551  1036  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-24 14:31:42.551  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.551  1036  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.551  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 14:31:42.551  7254  7254 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 14:31:42.551  1036  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 14:31:42.551  1036  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 14:31:42.552  1036  1540 D WifiNative-wlan0: SET ps 1: returned true
,08-24 14:31:42.571  1036  1036 D WifiHS20: hidePasspointNotification off =false
,08-24 14:31:42.575  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:42.575  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:42.576  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-24 14:31:42.577  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:42.579  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:42.579  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:42.579  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 14:31:42.579  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 14:31:42.579  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-24 14:31:42.579  1969  1969 D WfdsService: WifiP2pState is changed : false
08-24 14:31:42.579  1969  2299 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-24 14:31:42.579  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:42.579  1969  2299 D WfdsService: Set the WFDS Monitor: false
08-24 14:31:42.579  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:42.579  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 14:31:42.579  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 14:31:42.579  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-24 14:31:42.579  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.580  1036  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.580  1969  2299 D WfdsMonitor: WFDS Monitor is stopped
08-24 14:31:42.580  1969  2299 D WfdsService: STATE : WfdsDisabledState - enter
08-24 14:31:42.580  1969  7260 D CtrlSupplicant: Received on exit socket, terminate
08-24 14:31:42.580  1969  7260 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-24 14:31:42.580  1969  7260 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-24 14:31:42.580  1969  7260 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-24 14:31:42.580  1969  2300 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-24 14:31:42.581  1969  2299 W WfdsService: DefaultState - msg [9445378] is not handled
08-24 14:31:42.597  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:42.597  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-24 14:31:42.611  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 14:31:42.615   325   895 D CommandListener: Clearing all IP addresses on wlan0
08-24 14:31:42.616  1036  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-24 14:31:42.616  1036  1546 D DSQN    : disableDataServiceNotify
08-24 14:31:42.616  1036  1546 D DSQN    : stop dsqn bin
08-24 14:31:42.617  1036  1540 D WifiNative-p2p0: doBoolean: TERMINATE
08-24 14:31:42.617  1036  1540 D WifiNative-p2p0: TERMINATE: returned true
08-24 14:31:42.617  1036  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 14:31:42.617  1036  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 14:31:42.617  1036  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 14:31:42.618  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-24 14:31:42.618  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:42.618  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:42.619  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 14:31:42.620  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-24 14:31:42.620  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-24 14:31:42.620  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:42.620  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-24 14:31:42.621  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:42.621  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:42.621  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:42.621  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:42.621  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:42.621  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:42.621  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:42.621  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:42.621  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:42.621  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:42.621  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:42.622  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:42.622  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:42.622  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:42.622  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:42.622  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:42.622  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:42.622  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:42.622  6702  6702 V io.jxcore.node.ConnectivityMo,nitor:     - is connected/connecting to active network: false
08-24 14:31:42.622  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:42.622  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:42.622  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:42.631  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 14:31:42.631  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:42.632  1036  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-24 14:31:42.632  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:42.632  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:42.632  1036  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-24 14:31:42.632  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:42.632  1036  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-24 14:31:42.632  1036  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-24 14:31:42.632  1036  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-24 14:31:42.632  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 14:31:42.633  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:42.633  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 14:31:42.633  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-24 14:31:42.633  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:42.633  1036  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:42.633  1036  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:42.633  1036  1546 D NetworkManagementService: Removing idletimer
08-24 14:31:42.633  1036  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:42.634  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.634  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.634  1036  7320 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-24 14:31:42.634  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:42.635  1875  1875 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:42.635  1036  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:42.635  1036  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 14:31:42.635  1875  1875 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 14:31:42.635  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 14:31:42.636  1036  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=104857,6Kbps]
08-24 14:31:42.636  1036  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 14:31:42.637  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 14:31:42.637  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 14:31:42.637  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 14:31:42.637  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 14:31:42.637  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 14:31:42.637  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 14:31:42.637  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-24 14:31:42.664  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 14:31:42.665  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:42.665  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 14:31:42.678  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 14:31:42.679  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:42.679  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:42.690  7254  7254 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-24 14:31:42.690  7254  7254 I wpa_supplicant: monitor socket send errors count : 1
08-24 14:31:42.690  7254  7254 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-4\x00 that cannot receive messages
08-24 14:31:42.690  1036  7257 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-24 14:31:42.690  1036  7257 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-24 14:31:42.711  7254  7254 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 14:31:42.712  7254  7254 W wpa_supplicant: USIM:  scard_deinit function
08-24 14:31:42.713  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-24 14:31:42.713  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 14:31:42.713  1036  7257 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 14:31:42.713  1036  7257 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-24 14:31:42.713  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 14:31:42.713  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 14:31:42.713  1036  1097 D Tethering: InitialState.processMessage what=4
08-24 14:31:42.714  1036  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=134795
08-24 14:31:42.714  1036  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=134796
08-24 14:31:42.714  1036  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=134796  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 14:31:42.714  1036  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=134796  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 14:31:42.716  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 14:31:42.716  1036  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:42.716  1036  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:42.718  1036  7321 D DhcpStateMachine: StoppedState
08-24 14:31:42.719  1036  7321 D DhcpStateMachine: StoppedState{ when=-167ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:42.719  1036  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-24 14:31:42.719  1036  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-24 14:31:42.720  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 14:31:42.721  6492  6522 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 14:31:42.721   325  7492 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-24 14:31:42.722  1036  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-24 14:31:42.734  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:42.740  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 14:31:42.740  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:42.740  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 14:31:42.740  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-24 14:31:42.741  7205  7205 I AppUp4:CustModeStarterReceiver: onReceive
,08-24 14:31:42.745  7205  7205 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30e91578
08-24 14:31:42.745  7205  7205 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 14:31:42.745  7205  7205 D AppUp4:CustFacade: isPhone : true
08-24 14:31:42.746  7205  7205 D AppUp4:CustModeStarterReceiver: begin check event
08-24 14:31:42.746  7205  7205 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 14:31:42.748  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:42.748  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 14:31:42.749  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:42.751  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:42.755  7236  7236 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 14:31:42.755  4787  7495 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-24 14:31:42.763  7236  7498 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:42.767  4787  7496 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:42.767  4787  7496 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 14:31:42.774  7105  7501 W FormManager: Network not available. Please check & try again.
,08-24 14:31:42.778  3175  3175 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 14:31:42.778  3175  3175 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:42.778  3175  3175 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 14:31:42.781  7266  7266 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 14:31:42.781  7266  7266 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 14:31:42.787  7105  7502 V FormManager: Network unavailable.
,08-24 14:31:42.791  7322  7322 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:42
,08-24 14:31:42.792  7105  7502 V FormManager: Network unavailable.
08-24 14:31:42.793  7322  7322 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 14:31:42.793  7322  7322 D Weather.Utils: 2 : All the weather widget is gone.
08-24 14:31:42.794  7322  7322 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 14:31:42.794  7322  7322 D WeatherAncestor: connectivity changed - connection : true
08-24 14:31:42.794  7322  7322 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@205014b6
08-24 14:31:42.795  7322  7322 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 14:31:42.795  7322  7322 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 14:31:42.795  7322  7322 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 14:31:42.795  7322  7322 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 14:31:42.795  7322  7322 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:42
08-24 14:31:42.819  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 14:31:42.819  7003  7003 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 14:31:42.819  7003  7003 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 14:31:42.819  7003  7003 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 14:31:42.819  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 14:31:42.820  7380  7397 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 14:31:42.820  7380  7397 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 14:31:42.820  7380  7397 I Adreno-EGL: Build Date: 12/12/14 금
08-24 14:31:42.820  7380  7397 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 14:31:42.820  7380  7397 I Adreno-EGL: Remote Branch: 
08-24 14:31:42.820  7380  7397 I Adreno-EGL: Local Patches: 
08-24 14:31:42.820  7380  7397 I Adreno-EGL: Reconstruct Branch: 
08-24 14:31:42.820  7003  7003 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 14:31:42.820  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 14:31:42.820  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 14:31:42.820  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 14:31:42.820  7003  7003 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 14:31:42.820  7003  7003 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-24 14:31:42.829  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:42.834  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:42.836  7254  7254 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-24 14:31:42.836  1036  7257 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-24 14:31:42.836  1036  7257 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-24 14:31:42.836  1036  7257 D WifiMonitor: Disconnecting from the supplicant, no more events
08-24 14:31:42.836  7105  7507 W FormManager: Network not available. Please check & try again.
08-24 14:31:42.837  1036  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-24 14:31:42.838  7105  7508 V FormManager: Network unavailable.
08-24 14:31:42.840  7105  7508 V FormManager: Network unavailable.
08-24 14:31:42.840  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:42.853  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 14:31:42.856  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:42.860  7105  7510 W FormManager: Network not available. Please check & try again.
08-24 14:31:42.862  7380  7397 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 14:31:42.862  7380  7397 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 14:31:42.862  7380  7397 I Adreno-EGL: Build Date: 12/12/14 금
08-24 14:31:42.862  7380  7397 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 14:31:42.862  7380  7397 I Adreno-EGL: Remote Branch: 
08-24 14:31:42.862  7380  7397 I Adreno-EGL: Local Patches: 
08-24 14:31:42.862  7380  7397 I Adreno-EGL: Reconstruct Branch: 
08-24 14:31:42.863  7105  7511 V FormManager: Network unavailable.
08-24 14:31:42.865  7105  7511 V FormManager: Network unavailable.
,08-24 14:31:42.870  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:42.882  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 14:31:42.882  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 14:31:42.883  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 14:31:42.884  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:42.888  4787  7512 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 14:31:42.889  4787  7513 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 14:31:42.889  4787  7513 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 14:31:42.916  1036  1912 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7514 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-24 14:31:42.938  1036  1540 D WifiOffDelayIfNotUsed: stopMonitoring
08-24 14:31:42.939  1036  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 14:31:42.939  1036  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 14:31:42.939  1036  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 14:31:42.939  1969  1969 D WfdsService: Supplicant Connection state is changed : false
08-24 14:31:42.939  1969  2299 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-24 14:31:42.939  1969  2299 D WfdsService: Set the WFDS Monitor: false
08-24 14:31:42.939  1969  2299 D WfdsMonitor: WFDS Monitor is stopped
08-24 14:31:42.940   325  7532 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-24 14:31:42.941  1036  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-24 14:31:42.942  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:42.943  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 14:31:42.944  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-24 14:31:42.945  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:42.945  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:42.945  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:42.945  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:42.945  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:42.945  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:42.945  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:42.945  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:42.945  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:31:42.946  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-24 14:31:42.946  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-24 14:31:42.946  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:42.946  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:42.946  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:42.946  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:42.946  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:42.946  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:42.946  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:42.946  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:42.946  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:31:42.948  1817  7344 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-24 14:31:42.949  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:31:42.962  1817  7344 I CheckinService: active receiver: disabled
,08-24 14:31:43.033  7514  7514 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 14:31:43.033  7514  7514 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-24 14:31:43.041  7514  7514 V [BNRBootReceiver]: Boot Receiver Return
08-24 14:31:43.041  7514  7514 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 14:31:43.045  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:43.055  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.064  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 14:31:43.081  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:31:43.082  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 14:31:43.084  7058  7058 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-24 14:31:43.092  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-24 14:31:43.098  7003  7003 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-24 14:31:43.106  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:43.121  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.138  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:43.157  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 14:31:43.158  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:31:43.161  7058  7058 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 14:31:43.173  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:43.197  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.218  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:43.227  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:31:43.228  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 14:31:43.228  7058  7058 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:31:43.236  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:43.249  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.264  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 14:31:43.278  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:31:43.279  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 14:31:43.280  7058  7058 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:31:43.288  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 14:31:43.308  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.321  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 14:31:43.334  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:31:43.334  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 14:31:43.335  7058  7058 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 14:31:43.340  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:43.355  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.362  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 14:31:43.375  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 14:31:43.375  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:31:43.376  7058  7058 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:31:43.382  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:43.395  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.403  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 14:31:43.412  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:31:43.413  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 14:31:43.413  7058  7058 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:31:43.422  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:43.435  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.444  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:43.455  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 14:31:43.455  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:31:43.460  7058  7058 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:31:43.465  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:43.477  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.493  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 14:31:43.504  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 14:31:43.505  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 14:31:43.507  7058  7058 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:31:43.513  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:43.519  7027  7027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-24 14:31:43.535  1036  1545 D WifiService: New client listening to asynchronous messages
,08-24 14:31:43.536  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:43.541  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.554  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:43.568  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:31:43.569  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:31:43.571  7058  7058 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 14:31:43.573  7058  7058 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 14:31:43.574  7058  7058 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-24 14:31:43.585  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 14:31:43.588  6874  7178 D UEI.SmartControl: Internal timer expired: 2
08-24 14:31:43.588  6874  7178 D UEI.SmartControl: unbind internal service
08-24 14:31:43.597  7027  7027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-24 14:31:43.599  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 14:31:43.603  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.610  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:43.622  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:31:43.623  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:31:43.624  7058  7058 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 14:31:43.624  7058  7058 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 14:31:43.625  7058  7058 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-24 14:31:43.628  1036  1949 I ActivityManager: Killing 6977:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-24 14:31:43.664  6874  7172 D serial_port: close(fd = 24)
,08-24 14:31:43.670  6874  7172 I UEI.SmartControl: Serial port is closed.
08-24 14:31:43.684  1036  1596 W libprocessgroup: failed to open /acct/uid_10037/pid_6977/cgroup.procs: No such file or directory
,08-24 14:31:43.690  2206  2206 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-24 14:31:43.706  2206  2206 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-24 14:31:43.707  2206  2206 D c       : Getting all permits...
08-24 14:31:43.707  2206  2206 D a       : Opening database...
,08-24 14:31:43.712  2206  2206 D a       : Opening database auth.proximity.permit_store...
,08-24 14:31:43.713  2206  2206 D a       : Closing database...
08-24 14:31:43.730  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 14:31:43.737  7027  7027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 14:31:43.737  7027  7027 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 14:31:43.737  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:43.741  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.749  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:43.757  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:31:43.758  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:31:43.764  7058  7058 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-24 14:31:43.771  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:43.776  7027  7027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 14:31:43.777  7027  7027 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 14:31:43.777  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:43.783  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.793  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:43.802  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 14:31:43.802  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:31:43.805  7058  7058 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 14:31:43.811  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:43.816  7027  7027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-24 14:31:43.816  7027  7027 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 14:31:43.816  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:43.822  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:31:43.830  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:43.839  7058  7058 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:31:43.840  7058  7058 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:31:43.841  7058  7058 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-24 14:31:43.850  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:43.856  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:43.863  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:43.884  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 14:31:43.884  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-24 14:31:43.887  7105  7545 V FormManager: Network unavailable.
08-24 14:31:43.888  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:43.891  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:43.896  7105  7544 W FormManager: Network not available. Please check & try again.
08-24 14:31:43.900  7105  7545 V FormManager: Network unavailable.
08-24 14:31:43.901  4787  7550 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-24 14:31:43.904  7027  7027 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-24 14:31:43.904  7027  7027 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 14:31:43.904  7027  7027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:43.905  4787  7551 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 14:31:43.907  4787  7551 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 14:31:43.910  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:43.920  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:43.928  7105  7553 W FormManager: Network not available. Please check & try again.
,08-24 14:31:43.932  7105  7554 V FormManager: Network unavailable.
08-24 14:31:43.936  7105  7554 V FormManager: Network unavailable.
08-24 14:31:43.941  2206  2206 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-24 14:31:44.419  1036  1540 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1131878109] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 14:31:44.421  1036  1540 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1131878107] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 14:31:44.507  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:44.520  1036  1097 D Tethering: MasterInitialState.processMessage what=3
08-24 14:31:44.532  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:44.536  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:44.540  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:44.542  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 14:31:44.543  6492  6522 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 14:31:44.550  5872  5872 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-24 14:31:44.574  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:44.594  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 14:31:44.594  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:44.594  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 14:31:44.594  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-24 14:31:44.599  7205  7205 I AppUp4:CustModeStarterReceiver: onReceive
08-24 14:31:44.602  7205  7205 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30e91578
08-24 14:31:44.602  7205  7205 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 14:31:44.602  7205  7205 D AppUp4:CustFacade: isPhone : true
08-24 14:31:44.603  7205  7205 D AppUp4:CustModeStarterReceiver: begin check event
08-24 14:31:44.603  7205  7205 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 14:31:44.608  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:44.608  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 14:31:44.610  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 14:31:44.616  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:44.624  7236  7236 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-24 14:31:44.651  7236  7562 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:31:44.654  4787  7563 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-24 14:31:44.659  4787  7566 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:44.659  4787  7566 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 14:31:44.677  7105  7564 W FormManager: Network not available. Please check & try again.
,08-24 14:31:44.681  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:44.690  7105  7565 V FormManager: Network unavailable.
08-24 14:31:44.694  3175  3175 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-24 14:31:44.694  3175  3175 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:44.694  3175  3175 I LgeMiscReceiver: networkInfo.isConnected() = true
08-24 14:31:44.694  3175  3175 D PhoneState: setPdpRejectCasuse : false
,08-24 14:31:44.698  7266  7266 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 14:31:44.699  7266  7266 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 14:31:44.699  7105  7565 V FormManager: Network unavailable.
,08-24 14:31:44.708  7322  7322 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:44
08-24 14:31:44.710  7322  7322 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 14:31:44.710  7322  7322 D Weather.Utils: 2 : All the weather widget is gone.
08-24 14:31:44.710  7322  7322 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 14:31:44.710  7322  7322 D WeatherAncestor: connectivity changed - connection : true
,08-24 14:31:44.710  7322  7322 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@205014b6
,08-24 14:31:44.712  7322  7322 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-24 14:31:44.712  7322  7322 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-24 14:31:44.712  7322  7322 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-24 14:31:44.712  7322  7322 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 14:31:44.712  7322  7322 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:44
08-24 14:31:45.491  1036  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:45.491  1036  2019 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-24 14:31:45.532  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 14:31:45.532  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 14:31:45.532  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-24 14:31:45.533  1036  1097 D BluetoothManagerService: Message: 1
08-24 14:31:45.533  1036  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-24 14:31:45.560  1036  1097 D BluetoothManagerService: Message: 20
08-24 14:31:45.560  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1255d5b:true
,08-24 14:31:45.565  7135  7135 D BluetoothAdapterState: make
08-24 14:31:45.570  7135  7135 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-24 14:31:45.570  7135  7135 I bluedroid-qcom: init
08-24 14:31:45.571  7135  7594 I BluetoothAdapterState: Entering OffState
08-24 14:31:45.572  7135  7135 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-24 14:31:45.572  7135  7135 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-24 14:31:45.572  7135  7135 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 14:31:45.572  7135  7135 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 14:31:45.572  7135  7135 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-24 14:31:45.574  7135  7135 I bluedroid-qcom: get_profile_interface socket
08-24 14:31:45.574  7135  7135 I bluedroid-qcom: get_profile_interface map_client
,08-24 14:31:45.579  7135  7598 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-24 14:31:45.582  7135  7598 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-24 14:31:45.573  7597  7597 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:45.573  7597  7597 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:45.593  7597  7597 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-24 14:31:45.593  7597  7597 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-24 14:31:45.593  7597  7597 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-24 14:31:45.599  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 14:31:45.599  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 14:31:45.601  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-24 14:31:45.601  1036  1097 D BluetoothManagerService: Message: 40
08-24 14:31:45.601  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-24 14:31:45.602  7135  7150 I bluedroid-qcom: config_hci_snoop_log
08-24 14:31:45.603  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-24 14:31:45.603  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-24 14:31:45.604  7597  7597 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-24 14:31:45.610  7135  7594 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-24 14:31:45.613  7135  7598 D BluetoothAdapterProperties: Name is: G3
08-24 14:31:45.614  7135  7594 D BluetoothAdapterProperties: Setting state to 11
08-24 14:31:45.614  7135  7594 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 14:31:45.615  1036  1097 D BluetoothManagerService: Message: 60
08-24 14:31:45.615  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-24 14:31:45.615  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-24 14:31:45.617  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 14:31:45.619  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:45.622  7597  7597 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-24 14:31:45.622  7597  7597 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-24 14:31:45.628  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:45.631  7003  7003 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-24 14:31:45.634  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:45.642  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:45.655  1036  1097 D Tethering: MasterInitialState.processMessage what=3
,08-24 14:31:45.656  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:45.657  7135  7594 I LGBluetoothServiceJni: classInitNative: succeeds
08-24 14:31:45.658  7135  7135 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 14:31:45.664  7135  7135 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:45.664  7135  7135 V BluetoothPbapReceiver: ***********state = 11
08-24 14:31:45.667  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:45.673  1036  1097 D Tethering: MasterInitialState.processMessage what=3
,08-24 14:31:45.679  7135  7594 D BluetoothBondStateMachine: make
08-24 14:31:45.679  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 14:31:45.681  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:31:45.681  7135  7594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:45.682  7135  7594 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-24 14:31:45.682  7135  7594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:45.682  7135  7594 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-24 14:31:45.683  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:45.684  7135  7594 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-24 14:31:45.685  7135  7615 I BluetoothBondStateMachine: StableState(): Entering Off State
08-24 14:31:45.686  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:45.688  6492  6522 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-24 14:31:45.690  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:45.691  7135  7594 E BluetoothAdapterService: File transfer profiles supported!!
08-24 14:31:45.691  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:45.733  1036  1915 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7616 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-24 14:31:45.736  5872  5872 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-24 14:31:45.742  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:45.752  7135  7594 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 14:31:45.752  7135  7135 D HeadsetService: Received start request. Starting profile...
08-24 14:31:45.753  7135  7135 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 14:31:45.753  7135  7135 D LGBluetoothHfpAdapter: Version 1.6
08-24 14:31:45.756  7135  7135 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 14:31:45.757  7135  7135 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 14:31:45.758  7135  7135 D HeadsetStateMachine: make
08-24 14:31:45.759  5872  5872 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-24 14:31:45.762  7135  7594 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 14:31:45.772  7135  7594 E BluetoothAdapterService: File transfer profiles supported!!
08-24 14:31:45.781  7135  7594 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 14:31:45.787  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:45.790  7135  7594 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 14:31:45.794  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:45.794  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 14:31:45.801  7135  7594 E BluetoothAdapterService: File transfer profiles supported!!
08-24 14:31:45.801  7135  7135 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:45.802  7135  7135 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 14:31:45.804  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 14:31:45.804  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:45.804  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 14:31:45.805  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-24 14:31:45.807  7205  7205 I AppUp4:CustModeStarterReceiver: onReceive
08-24 14:31:45.809  7135  7135 D HeadsetStateMachine: max_hf_connections = 1
08-24 14:31:45.809  7135  7135 I bluedroid-qcom: get_profile_interface handsfree
08-24 14:31:45.811  7135  7135 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-24 14:31:45.813   329   329 V AudioPolicyService: registerClient() client 0xb558a220, uid 1002
08-24 14:31:45.814   329  1387 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-24 14:31:45.814   329  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 14:31:45.814   329  1387 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 14:31:45.814  7135  7135 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-24 14:31:45.814  7205  7205 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30e91578
08-24 14:31:45.814  7205  7205 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 14:31:45.815  7205  7205 D AppUp4:CustFacade: isPhone : true
08-24 14:31:45.815   329  1386 V AudioFlinger: registerClient() client 0xb1433148, pid 7135
08-24 14:31:45.815   329  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:45.815   329  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 14:31:45.815  1875  1894 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:45.815  7135  7135 V ToneGenerator: Create Track: 0xb4928a80
08-24 14:31:45.815  1875  1894 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 14:31:45.815  7135  7135 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-24 14:31:45.815  7135  7135 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-24 14:31:45.815  7135  7150 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:45.815  7135  7150 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-24 14:31:45.816   329  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:45.816   329  1387 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 14:31:45.816   329  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 14:31:45.816   329  1387 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-24 14:31:45.816   329  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 14:31:45.816   329  1387 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 14:31:45.816  7135  7150 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:45.816  7135  7150 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-24 14:31:45.816   329  1386 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 14:31:45.816   329   329 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 14:31:45.816   329   329 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-24 14:31:45.816   329   329 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 14:31:45.816   329   329 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 14:31:45.817  1036  1596 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:45.817  7135  7135 V AudioSystem: getLatency() output 2, latency 50
08-24 14:31:45.817  1036  1596 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 14:31:45.817  7135  7135 V AudioSystem: getFrameCount() output 2, frameCount 960
08-24 14:31:45.817  7135  7135 V AudioTrack: createTrack_l() output 2 afLatency 50
08-24 14:31:45.817  1036  1596 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:45.817  1036  1596 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 14:31:45.817   329  1387 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 14:31:45.817   329  1387 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 14:31:45.817   ,329  1387 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 14:31:45.817   329  1387 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 14:31:45.817   329  1387 V AudioFlinger: createTrack() lSessionId: 22
08-24 14:31:45.818  1605  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:45.818  1605  1621 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 14:31:45.818  3175  3191 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:45.818  3175  3191 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 14:31:45.818  3175  3191 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:45.818  3175  3191 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 14:31:45.818  1875  2614 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:45.818  1875  2614 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 14:31:45.818  1605  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:45.818  1605  1621 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 14:31:45.819  7205  7205 D AppUp4:CustModeStarterReceiver: begin check event
08-24 14:31:45.819  7135  7135 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-24 14:31:45.819  7205  7205 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 14:31:45.820   329   329 V AudioFlinger: acquiring 22 from 7135, for 7135
08-24 14:31:45.820   329   329 V AudioFlinger:  added new entry for 22
08-24 14:31:45.820  7135  7135 V ToneGenerator: ToneGenerator INIT OK, time: 137915
08-24 14:31:45.820  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:45.822  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:45.822  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 14:31:45.822  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:45.823  7135  7632 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-24 14:31:45.823  7135  7632 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 14:31:45.824  7135  7632 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 14:31:45.824  7135  7632 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-24 14:31:45.824  7135  7135 D A2dpService: Received start request. Starting profile...
08-24 14:31:45.824   329  1387 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7135
08-24 14:31:45.825  7135  7135 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 14:31:45.826   329  1387 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-24 14:31:45.826   329  1387 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-24 14:31:45.826   329  1387 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-24 14:31:45.826   329  1387 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-24 14:31:45.826   329  1387 V voice   : voice_set_parameters: exit with code(0)
08-24 14:31:45.826   329  1387 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-24 14:31:45.826   329  1387 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-24 14:31:45.826   329  1387 V msm8974_platform: platform_set_parameters: exit with code(0)
08-24 14:31:45.826   329  1387 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-24 14:31:45.826   329  1387 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-24 14:31:45.826   329  1387 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-24 14:31:45.826  7135  7135 V Avrcp   : make
08-24 14:31:45.827  7135  7632 V ToneGenerator: ToneGenerator destructor
08-24 14:31:45.827  7135  7632 V ToneGenerator: stopTone
08-24 14:31:45.827  7135  7632 V ToneGenerator: Delete Track: 0xb4928a80
08-24 14:31:45.827  7135  7135 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-24 14:31:45.827  7135  7135 I bluedroid-qcom: get_profile_interface avrcp
08-24 14:31:45.827  7135  7594 V LGMDMManager: Create singleton instance
08-24 14:31:45.828  7135  7632 V AudioTrack: ~AudioTrack, releasing session id from 7135 on behalf of 7135
08-24 14:31:45.828   329   329 V AudioFlinger: releasing 22 from 7135 for 7135
08-24 14:31:45.828   329   329 V AudioFlinger:  decremented refcount to 0
08-24 14:31:45.828   329   329 V AudioFlinger: purging stale effects
08-24 14:31:45.828   329   329 V AudioPolicyService: AudioCommandThread() adding release output 2
08-24 14:31:45.828   329   329 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-24 14:31:45.828   329   329 V AudioFlinger: PlaybackThread::Track destructor
08-24 14:31:45.828   329   329 V AudioFlinger: removeClient_l() pid 7135, calling pid 329
08-24 14:31:45.829   329  1260 V AudioPolicyService: AudioCommandThread() waking up
08-24 14:31:45.829   329  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-24 14:31:45.829   329  1260 V AudioPolicyManager: releaseOutput() 2
08-24 14:31:45.829   329  1260 V AudioPolicyService: AudioCommandThread() going to sleep
08-24 14:31:45.832  7135  7594 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-24 14:31:45.835  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:45.837  7135  7135 V AudioManager: registerRemoteController: size of Media player list: 0
08-24 14:31:45.837  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 14:31:45.841  7135  7135 E AudioManager: No RCC entry present to update
08-24 14:31:45.841  7135  7135 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-24 14:31:45.844  7135  7135 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-24 14:31:45.846  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-24 14:31:45.846  7135  7135 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-24 14:31:45.847  4787  7637 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 14:31:45.848  4787  7639 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:45.848  4787  7639 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-24 14:31:45.849  7236  7236 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 14:31:45.850  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-24 14:31:45.917  7616  7616 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-24 14:31:45.919  7616  7616 W LG Account v2.2: No ProfileInfo entries
08-24 14:31:45.919  7616  7616 I LG Account v2.2: isEnabled: false
08-24 14:31:45.919  7616  7616 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-24 14:31:45.919  7616  7616 I Feature : [Lifetracker]Country: EU
08-24 14:31:45.920  7616  7616 I Feature : [Lifetracker]Operator: OPEN
08-24 14:31:45.920  7616  7616 I Feature : [Lifetracker]Ranking support: false
08-24 14:31:45.920  7616  7616 I Feature : [Lifetracker]Comfort support: false
08-24 14:31:45.920  7616  7616 I Feature : [Lifetracker]Accessory: true
08-24 14:31:45.920  7616  7616 I Feature : [Lifetracker]Health device: true
08-24 14:31:45.920  7616  7616 I Feature : [Lifetracker]Extra Pedometer: false
08-24 14:31:45.921  7616  7616 I Feature : [Lifetracker]Blood glucose device: false
08-24 14:31:45.921  7616  7616 I Feature : [Lifetracker]Device Number: 3
08-24 14:31:45.938  7236  7643 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:31:45.953  7003  7003 D BluetoothPermissionRequest: onReceive
,08-24 14:31:45.960  7105  7645 W FormManager: Network not available. Please check & try again.
08-24 14:31:45.971  3175  3175 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 14:31:45.971  3175  3175 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:45.971  3175  3175 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 14:31:45.974  7003  7003 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 14:31:45.975  7105  7646 V FormManager: Network unavailable.
08-24 14:31:45.977  7266  7266 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 14:31:45.977  7266  7266 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 14:31:45.982  7105  7646 V FormManager: Network unavailable.
08-24 14:31:45.996  7322  7322 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:45
,08-24 14:31:45.999  7322  7322 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 14:31:45.999  7322  7322 D Weather.Utils: 2 : All the weather widget is gone.
08-24 14:31:45.999  7322  7322 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 14:31:45.999  7322  7322 D WeatherAncestor: connectivity changed - connection : true
08-24 14:31:46.000  7322  7322 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@205014b6
08-24 14:31:46.001  7322  7322 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 14:31:46.001  7322  7322 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 14:31:46.001  7322  7322 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 14:31:46.001  7322  7322 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 14:31:46.001  7322  7322 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:46
08-24 14:31:46.005  1036  1576 V SIM_STK : Menu title from STK is T-Mobile
08-24 14:31:46.005  1036  1576 V SIM_STK : Menu title from STK is T-Mobile
08-24 14:31:46.030  6492  6492 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 14:31:46.032  6492  6522 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-24 14:31:46.051  2206  2206 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:46.063  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 14:31:46.063  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:46.063  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-24 14:31:46.063  7205  7205 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-24 14:31:46.066  7205  7205 I AppUp4:CustModeStarterReceiver: onReceive
08-24 14:31:46.070  7205  7205 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30e91578
08-24 14:31:46.070  7205  7205 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 14:31:46.070  7205  7205 D AppUp4:CustFacade: isPhone : true
08-24 14:31:46.071  7205  7205 D AppUp4:CustModeStarterReceiver: begin check event
08-24 14:31:46.071  7205  7205 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 14:31:46.075  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:46.076  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 14:31:46.079  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:46.082  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:46.090  4787  7648 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 14:31:46.090  7236  7236 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 14:31:46.095  4787  7649 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:46.095  4787  7649 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-24 14:31:46.111  1036  1576 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-24 14:31:46.111  7236  7650 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:46.117  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-24 14:31:46.123  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 14:31:46.123  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 14:31:46.124  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 14:31:46.124  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 14:31:46.124  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 14:31:46.124  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 14:31:46.124  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 14:31:46.124  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 14:31:46.124  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 14:31:46.124  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-24 14:31:46.125  7135  7135 I BluetoothA2dpServiceJni: classInitNative
08-24 14:31:46.125  7135  7135 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 14:31:46.125  3175  3175 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 14:31:46.125  3175  3175 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:46.125  7135  7135 D A2dpStateMachine: make
08-24 14:31:46.125  3175  3175 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 14:31:46.128  7135  7135 I bluedroid-qcom: get_profile_interface a2dp
08-24 14:31:46.128  7135  7656 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-24 14:31:46.128  7105  7653 W FormManager: Network not available. Please check & try again.
08-24 14:31:46.130  7135  7135 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-24 14:31:46.130  7135  7135 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-24 14:31:46.130  7266  7266 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 14:31:46.131  7266  7266 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 14:31:46.131  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:46.131  7135  7655 D A2dpStateMachine: Enter Disconnected: -2
08-24 14:31:46.132  7135  7135 I BluetoothHidServiceJni: classInitNative: succeeds
08-24 14:31:46.134  7135  7135 D HidService: Received start request. Starting profile...
08-24 14:31:46.134  7135  7135 I bluedroid-qcom: get_profile_interface hidhost
08-24 14:31:46.134  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:46.135  7135  7135 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 14:31:46.136  7135  7135 D HealthService: Received start request. Starting profile...
,08-24 14:31:46.138  7135  7135 I bluedroid-qcom: get_profile_interface health
08-24 14:31:46.139  7135  7135 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-24 14:31:46.139  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:46.139  7105  7654 V FormManager: Network unavailable.
08-24 14:31:46.139  7135  7135 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 14:31:46.141  7135  7135 D PanService: Received start request. Starting profile...
08-24 14:31:46.141  7135  7135 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 14:31:46.141  7135  7135 I bluedroid-qcom: get_profile_interface pan
08-24 14:31:46.143  7322  7322 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:46
08-24 14:31:46.144  7322  7322 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 14:31:46.144  7322  7322 D Weather.Utils: 2 : All the weather widget is gone.
08-24 14:31:46.144  7322  7322 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 14:31:46.144  7322  7322 D WeatherAncestor: connectivity changed - connection : true
08-24 14:31:46.144  7322  7322 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@205014b6
08-24 14:31:46.145  7105  7654 V FormManager: Network unavailable.
08-24 14:31:46.145  7322  7322 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 14:31:46.145  7322  7322 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 14:31:46.145  7322  7322 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 14:31:46.145  7322  7322 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 14:31:46.146  7322  7322 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:31:46
08-24 14:31:46.150  7135  7135 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-24 14:31:46.150  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
,08-24 14:31:46.151  7135  7135 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-24 14:31:46.157  7135  7135 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 14:31:46.158  7135  7135 D BtGatt.GattService: Received start request. Starting profile...
08-24 14:31:46.158  7135  7135 D BtGatt.GattService: start()
08-24 14:31:46.158  7135  7135 I bluedroid-qcom: get_profile_interface gatt
08-24 14:31:46.158  7135  7135 D BtGatt.AdvertiseManager: advertise manager created
08-24 14:31:46.166  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
,08-24 14:31:46.167  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
,08-24 14:31:46.167  7135  7135 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-24 14:31:46.168  7135  7135 V BluetoothMapService: BluetoothMapBinder()
08-24 14:31:46.169  7135  7135 D BluetoothMapService: Received start request. Starting profile...
08-24 14:31:46.169  7135  7135 D BluetoothMapService: start()
08-24 14:31:46.173  7135  7135 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-24 14:31:46.173  7135  7135 D BluetoothMapEmailAppObserver: createReceiver()
08-24 14:31:46.174  7135  7135 D BluetoothMapEmailAppObserver: initObservers()
08-24 14:31:46.174  7135  7135 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-24 14:31:46.183  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:46.183  7135  7135 D HeadsetStateMachine: Proxy object connected
08-24 14:31:46.184  7135  7135 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-24 14:31:46.184  7135  7135 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-24 14:31:46.186  7135  7632 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 14:31:46.187  7135  7632 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 14:31:46.187  7135  7632 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-24 14:31:46.190  7135  7135 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 14:31:46.194  7135  7135 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 14:31:46.198  7135  7135 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-24 14:31:46.205  7135  7135 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 14:31:46.205  7135  7135 V PanService: [BTUI] SIM Extra State :ABSENT
08-24 14:31:46.211  7135  7135 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-24 14:31:46.217  7135  7135 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-24 14:31:46.218  7135  7135 V BluetoothMapService: Handler(): got msg=1
08-24 14:31:46.220  7135  7594 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-24 14:31:46.220  7135  7594 I bluedroid-qcom: enable
08-24 14:31:46.223  7135  7663 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-24 14:31:46.223  7135  7663 I bt-btu  : btu_task pending for preload complete event
08-24 14:31:46.224  7135  7594 I bt_hci_bdroid: init
08-24 14:31:46.225  7135  7135 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:46.228  7135  7594 I bt_vendor: bt-vendor : init
,08-24 14:31:46.228  7135  7594 I bt_vendor: bt-vendor : get_bt_soc_type
08-24 14:31:46.228  7135  7594 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-24 14:31:46.228  7135  7594 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-24 14:31:46.228  7135  7594 D bt_userial_mct: userial_init
08-24 14:31:46.229  7135  7135 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 14:31:46.229  7135  7135 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 14:31:46.229  7135  7135 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 14:31:46.229  7135  7135 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:46.229  7135  7135 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-24 14:31:46.230  7135  7594 D bt_hci_bdroid: set_power 1
08-24 14:31:46.230  7135  7594 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-24 14:31:46.230  7135  7594 I bt_vendor: Starting hciattach daemon
08-24 14:31:46.230  7135  7594 I bt_vendor: try to set true
08-24 14:31:46.223  7666  7666 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:46.223  7666  7666 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:46.266  7667  7667 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-24 14:31:46.411  7673  7673 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-24 14:31:46.436  7674  7674 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 14:31:46.458  7676  7676 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 14:31:46.471  7677  7677 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-24 14:31:46.484  7678  7678 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 14:31:46.496  7679  7679 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-24 14:31:46.526  7684  7684 I libmdmdetect: ESOC framework not supported
,08-24 14:31:46.527  7684  7684 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-24 14:31:46.535  7684  7684 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-24 14:31:46.535  7684  7684 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-24 14:31:46.535  7684  7684 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-24 14:31:46.535  7684  7684 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-24 14:31:46.535  7684  7684 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-24 14:31:46.535  7684  7684 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-24 14:31:46.535  7684  7684 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-24 14:31:46.577  7684  7685 E QC-QMI  : qmi_client [7684] 14: failed to locate client data
08-24 14:31:46.578   471   471 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-24 14:31:46.579   471   471 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-24 14:31:46.627  7689  7689 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-24 14:31:46.642  7693  7693 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 14:31:46.683  7135  7594 I bt_vendor: bluetooth satus is on
08-24 14:31:46.683  7135  7594 D bt_hci_bdroid: preload
,08-24 14:31:46.685  7135  7665 D bt_userial_mct: userial_open(port:0)
08-24 14:31:46.685  7135  7665 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-24 14:31:46.689  7135  7665 I bt_vendor: Done intiailizing UART
08-24 14:31:46.690  7135  7665 I bt_vendor: Done intiailizing UART
08-24 14:31:46.690  7135  7665 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-24 14:31:46.690  7135  7665 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-24 14:31:46.690  7135  7663 I bt-btu  : btu_task received preload complete event
08-24 14:31:46.691  7135  7663 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-24 14:31:46.691  7135  7663 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-24 14:31:46.693  7135  7663 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-24 14:31:46.698  7135  7695 D bt_userial_mct: Entering userial_read_thread()
,08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_HCI
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 14:31:46.703  7135  7663 I         : BTE_InitTraceLevels -- TRC_BTIF
08-24 14:31:46.752  7135  7663 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-24 14:31:46.752  7135  7663 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0161061 
08-24 14:31:46.752  7135  7663 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0161061 
,08-24 14:31:46.775  7135  7598 E bt-btif : Calling BTA_HhEnable
08-24 14:31:46.775  7135  7598 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-24 14:31:46.776  7135  7598 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-24 14:31:46.781  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 14:31:46.781  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 14:31:46.782  7135  7663 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-24 14:31:46.782  7135  7663 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-24 14:31:46.782  7135  7663 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-24 14:31:46.782  7135  7663 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-24 14:31:46.782  7135  7663 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-24 14:31:46.783  7135  7598 D BluetoothAdapterProperties: Name is: G3
08-24 14:31:46.785  7135  7598 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:31:46.785  7135  7598 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 14:31:46.785  7135  7598 D bt_hci_bdroid: postload
08-24 14:31:46.786  7135  7665 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 14:31:46.787  7135  7663 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-24 14:31:46.787  7135  7598 D bte_conf: Device ID record 1 : primary
08-24 14:31:46.787  7135  7598 D bte_conf:   vendorId            = 00c4
08-24 14:31:46.787  7135  7598 D bte_conf:   vendorIdSource      = 0001
08-24 14:31:46.787  7135  7598 D bte_conf:   product             = 13a1
08-24 14:31:46.787  7135  7598 D bte_conf:   version             = 1000
08-24 14:31:46.787  7135  7598 D bte_conf:   clientExecutableURL = 
08-24 14:31:46.787  7135  7598 D bte_conf:   serviceDescription  = 
08-24 14:31:46.788  7135  7598 D bte_conf:   documentationURL    = 
08-24 14:31:46.788  7135  7598 D bte_conf: bte_load_did_conf no section named DID2.
08-24 14:31:46.789  7135  7665 D bt_hci_bdroid: Used up Tx Cmd credits
,08-24 14:31:46.796  7135  7665 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 14:31:46.801  7135  7665 D bt_hci_bdroid: Used up Tx Cmd credits
,08-24 14:31:46.806  7135  7695 E bt_mct  : hci lib postload completed
08-24 14:31:46.803  7697  7697 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:46.803  7697  7697 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:46.813  7135  7663 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 14:31:46.814  7135  7663 W bt-smp  : Plain text(LSB ~ MSB) = 00 bb 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 14:31:46.814  7135  7663 W bt-smp  : Encrypted text(LSB ~ MSB) = 01 dd 8d 02 81 21 b9 b1 19 d9 ac 2c c2 9b 50 e6 
,08-24 14:31:46.816  7135  7663 W bt-btm  : Stopping oneshot timer
08-24 14:31:46.817  7135  7594 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-24 14:31:46.817  7135  7594 D BluetoothAdapterProperties: ScanMode =  20
08-24 14:31:46.817  7135  7594 D BluetoothAdapterProperties: State =  11
08-24 14:31:46.817  7135  7594 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-24 14:31:46.818  7135  7594 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-24 14:31:46.818  7135  7594 D BluetoothAdapterProperties: Setting state to 12
08-24 14:31:46.818  7135  7594 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 14:31:46.820  1036  1097 D BluetoothManagerService: Message: 60
08-24 14:31:46.820  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-24 14:31:46.820  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-24 14:31:46.820  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:31:46.822  7135  7598 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 14:31:46.822  7135  7598 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 14:31:46.838  7135  7594 I BluetoothAdapterState: Entering On State
,08-24 14:31:46.859  7135  7663 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 14:31:46.859  7135  7663 W bt-smp  : Plain text(LSB ~ MSB) = 5c ad 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 14:31:46.859  7135  7663 W bt-smp  : Encrypted text(LSB ~ MSB) = be 80 07 5a 62 13 e7 75 11 20 56 05 bc 93 f4 a2 
,08-24 14:31:46.862  7135  7663 W bt-btm  : Stopping oneshot timer
08-24 14:31:46.862  7135  7598 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 14:31:46.862  7135  7598 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-24 14:31:46.871  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:46.871  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:46.871  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:46.871  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:46.871  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:46.871  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:46.871  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:46.871  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:46.879  7135  7663 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 14:31:46.879  7135  7663 W bt-smp  : Plain text(LSB ~ MSB) = 53 64 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 14:31:46.879  7135  7663 W bt-smp  : Encrypted text(LSB ~ MSB) = 7a 7e c0 33 25 e7 03 c7 60 a8 33 6f d0 26 53 fd 
08-24 14:31:46.880  7135  7663 W bt-btm  : Stopping oneshot timer
08-24 14:31:46.881  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:46.885  1875  1893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:31:46.894  7135  7663 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 14:31:46.894  7135  7663 W bt-smp  : Plain text(LSB ~ MSB) = f7 41 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 14:31:46.894  7135  7663 W bt-smp  : Encrypted text(LSB ~ MSB) = ee 94 9b fb 14 af 7b 10 06 c4 e7 ec fd 12 45 af 
08-24 14:31:46.896  7135  7663 W bt-btm  : Stopping oneshot timer
08-24 14:31:46.897  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:46.897  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:46.897  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:46.897  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:46.897  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:46.897  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:46.897  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:46.897  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:46.906  7135  7594 D LGBluetoothServiceAdapter: [BTUI] OnState
08-24 14:31:46.907  7135  7594 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-24 14:31:46.907  7135  7594 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-24 14:31:46.908  7135  7594 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-24 14:31:46.909  7135  7594 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-24 14:31:46.911  1036  1036 D BluetoothHeadset: Proxy object connected
08-24 14:31:46.920  1875  1875 D BluetoothHeadset: Proxy object connected
,08-24 14:31:46.923  7135  7663 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 14:31:46.925  7135  7663 W bt-smp  : Plain text(LSB ~ MSB) = 32 a0 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 14:31:46.925  7135  7663 W bt-smp  : Encrypted text(LSB ~ MSB) = af ac 8b 1c 86 b4 5f 9a 19 b6 e4 aa 0d b6 a3 2c 
08-24 14:31:46.925  7135  7663 W bt-btm  : Stopping oneshot timer
08-24 14:31:46.930  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:46.930  1875  2614 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:31:46.952  7703  7703 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-24 14:31:46.965  1875  1875 D BluetoothHeadset: Proxy object connected
08-24 14:31:46.966  7003  7023 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 14:31:46.977  7003  7020 D BluetoothPan: onBluetoothStateChange on: true
08-24 14:31:46.977  7003  7020 D BluetoothPan: onBluetoothStateChange call bindService
08-24 14:31:46.981  7003  7023 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 14:31:46.981  7003  7003 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:31:46.981  7003  7003 D PanProfile: Bluetooth service connected
08-24 14:31:46.985  7003  7454 D BluetoothMap: onBluetoothStateChange: up=true
08-24 14:31:46.986  7003  7003 D BluetoothInputDevice: Proxy object connected
08-24 14:31:46.986  7003  7003 D HidProfile: Bluetooth service connected
08-24 14:31:46.988  1875  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:31:46.989  7003  7003 D BluetoothMap: Proxy object connected
08-24 14:31:46.989  7003  7003 D MapProfile: Bluetooth service connected
08-24 14:31:46.989  7003  7003 D BluetoothMap: getConnectedDevices()
08-24 14:31:46.990  7135  7150 V BluetoothMapService: getConnectedDevices()
08-24 14:31:46.991  1875  1875 D BluetoothHeadset: Proxy object connected
08-24 14:31:46.991  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:31:46.991  7350  7406 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-24 14:31:46.992  1036  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-24 14:31:46.992  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-24 14:31:46.994  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-24 14:31:46.999  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:46.999  1969  2180 D LGBluetoothAPIService: Message: 1
08-24 14:31:46.999  1969  2180 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-24 14:31:47.003  6702  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 14:31:47.005  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:47.008  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:47.008  1036  1036 D BluetoothA2dp: Proxy object connected
,08-24 14:31:47.010  1969  2180 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-24 14:31:47.012  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-24 14:31:47.012  1036  1097 D BluetoothManagerService: Message: 40
08-24 14:31:47.012  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-24 14:31:47.013  7003  7003 D LocalBluetoothProfileManager: Adding local A2DP profile
08-24 14:31:47.014  7135  7135 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:47.014  7135  7135 D BluetoothMapService: STATE_ON
08-24 14:31:47.016  7135  7135 D LGBluetoothAPIServer: [BTUI] onCreate()
08-24 14:31:47.016  7135  7135 D LGBluetoothAPIServer: [BTUI] onBind()
08-24 14:31:47.017  1036  1097 D BluetoothManagerService: Message: 30
08-24 14:31:47.017  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-24 14:31:47.017  1969  2180 D LGBluetoothAPIService: Message: 100
08-24 14:31:47.017  1969  2180 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-24 14:31:47.020  7003  7003 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-24 14:31:47.023  1036  1097 D BluetoothManagerService: Message: 30
08-24 14:31:47.029  7003  7003 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-24 14:31:47.030  7003  7003 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 14:31:47.033  7003  7003 D BluetoothA2dp: Proxy object connected
08-24 14:31:47.033  7003  7003 D A2dpProfile: Bluetooth service connected
08-24 14:31:47.034  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:47.034  7135  7135 V BluetoothPbapService: Pbap Service onCreate
08-24 14:31:47.034  7135  7135 V BluetoothPbapService: Starting PBAP service
,08-24 14:31:47.035  7135  7135 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-24 14:31:47.036  7135  7135 V BluetoothPbapService: Pbap Service onBind
08-24 14:31:47.037  7135  7135 V BluetoothMapService: Handler(): got msg=1
08-24 14:31:47.037  7003  7003 D BluetoothHeadset: Proxy object connected
08-24 14:31:47.038  7135  7135 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-24 14:31:47.038  7003  7003 D HeadsetProfile: Bluetooth service connected
08-24 14:31:47.038  7135  7135 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:47.038  7135  7135 V BluetoothPbapService: state: 12
,08-24 14:31:47.039  7135  7135 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 14:31:47.039  7135  7135 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:47.039  7135  7135 V BluetoothPbapReceiver: ***********state = 12
08-24 14:31:47.041  7135  7723 D BluetoothMapMasInstance: MAS initSocket()
08-24 14:31:47.041  7135  7135 V BluetoothPbapService: Handler(): got msg=1
08-24 14:31:47.043  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:31:47.043  2206  2206 D c       : Getting all permits...
08-24 14:31:47.043  2206  2206 D a       : Opening database...
08-24 14:31:47.044  7135  7135 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-24 14:31:47.044  7135  7723 D BluetoothMapMasInstance:   masId = 00
08-24 14:31:47.044  7135  7723 D BluetoothMapMasInstance:   msgTypes = 0e
08-24 14:31:47.044  7135  7723 D BluetoothMapMasInstance:   masName = SMS/MMS
08-24 14:31:47.044  7135  7723 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-24 14:31:47.046  7135  7725 V BluetoothPbapService: Pbap Service initSocket
08-24 14:31:47.046  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 14:31:47.047  1036  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:47.047  2206  2206 D a       : Opening database auth.proximity.permit_store...
08-24 14:31:47.048  7135  7723 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:47.048  2206  2206 D a       : Closing database...
08-24 14:31:47.051  7135  7723 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-24 14:31:47.051  7135  7723 V BluetoothMapMasInstance: Succeed to create listening socket 
08-24 14:31:47.052  7135  7723 D BluetoothMapMasInstance: Accepting socket connection...
08-24 14:31:47.054  7135  7598 D BluetoothAdapterProperties: Scan Mode:21
08-24 14:31:47.055  7135  7598 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-24 14:31:47.055  7003  7003 D DockEventReceiver: finishStartingService: stopping service
08-24 14:31:47.056  7135  7725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:47.057  7003  7003 D BluetoothPbap: Proxy object connected
08-24 14:31:47.057  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:47.058  7003  7003 D PbapServerProfile: Bluetooth service connected
08-24 14:31:47.058  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:47.061  7135  7725 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-24 14:31:47.061  7135  7725 V BluetoothPbapService: Succeed to create listening socket 
08-24 14:31:47.061  7135  7725 V BluetoothPbapService: Accepting socket connection...
08-24 14:31:47.064  7003  7003 D BluetoothPermissionRequest: onReceive
08-24 14:31:47.066  7003  7003 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 14:31:47.068  7003  7003 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 14:31:47.070  7135  7135 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-24 14:31:47.072  7135  7135 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-24 14:31:47.078  7135  7135 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-24 14:31:47.096  7135  7135 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-24 14:31:47.097  7135  7135 V BtOppService: onCreate
08-24 14:31:47.101  7135  7135 V BluetoothOppNotification: send message
08-24 14:31:47.103  7135  7135 V BtOppService: Starting RfcommListener
08-24 14:31:47.108  7135  7135 D BluetoothOppPreference: Dumping Names:  
08-24 14:31:47.109  7135  7135 D BluetoothOppPreference: {}
08-24 14:31:47.109  7135  7135 D BluetoothOppPreference: Dumping Channels:  
08-24 14:31:47.109  7135  7135 D BluetoothOppPreference: {}
,08-24 14:31:47.110  7135  7135 V BtOppService: onStartCommand
08-24 14:31:47.111  7135  7729 V BtOppService: Deleted complete outbound shares, number =  0
08-24 14:31:47.113  7135  7729 V BtOppService: Deleted complete inbound failed shares, number = 0
08-24 14:31:47.114  7135  7729 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-24 14:31:47.115  7135  7729 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5abb623 on behalf of 
08-24 14:31:47.116  7135  7732 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 14:31:47.116  7135  7732 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 14:31:47.117  7135  7135 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:47.117  7135  7135 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 14:31:47.118  7135  7732 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3dad6720 on behalf of 
08-24 14:31:47.119  7135  7732 V BluetoothOppNotification: update too frequent, put in queue
08-24 14:31:47.120  7135  7732 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 14:31:47.121  7135  7135 V BluetoothOppNotification: new notify threadi!
08-24 14:31:47.121  7135  7135 V BluetoothOppNotification: send delay message
08-24 14:31:47.122  7135  7733 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 14:31:47.123  7135  7135 V BtOppService: start RfcommListener
,08-24 14:31:47.124  7135  7733 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b00d8d9 on behalf of 
08-24 14:31:47.129  7135  7135 V BtOppService: RfcommListener started
08-24 14:31:47.129  7135  7135 V BtOppService: ContentObserver received notification
08-24 14:31:47.130  7135  7734 V BtOppRfcommListener: Starting RFCOMM listener....
08-24 14:31:47.130  7135  7135 V BtOppService: ContentObserver received notification
08-24 14:31:47.131  1036  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:47.132  7135  7735 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 14:31:47.132  7135  7735 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 14:31:47.132  7135  7734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:47.133  7135  7735 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3244a29e on behalf of 
08-24 14:31:47.134  7135  7734 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-24 14:31:47.134  7135  7734 V BtOppRfcommListener: Started RFCOMM listener....
08-24 14:31:47.134  7135  7734 I BtOppRfcommListener: Accept thread started.
08-24 14:31:47.134  7135  7734 V BtOppRfcommListener: Accepting connection...
08-24 14:31:47.135  7135  7735 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 14:31:47.135  7135  7733 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 14:31:47.137  7135  7733 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-24 14:31:47.140  7135  7733 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34f9917f on behalf of 
08-24 14:31:47.141  7135  7733 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 14:31:47.143  7135  7733 V BluetoothOppNotification: outbound notification was removed.
08-24 14:31:47.143  7135  7733 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 14:31:47.145  7135  7733 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fd1d54c on behalf of 
08-24 14:31:47.146  7135  7733 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 14:31:47.147  7135  7733 V BluetoothOppNotification: inbound notification was removed.
08-24 14:31:47.148  7135  7733 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 14:31:47.149  7135  7733 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d2995 on behalf of 
,08-24 14:31:47.156  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
,08-24 14:31:47.156  7135  7135 V BluetoothFtpService: Ftp Service onCreate
08-24 14:31:47.156  7135  7135 I BluetoothFtpService: Ftp Service onCreate
08-24 14:31:47.156  7135  7135 V BluetoothFtpService: Ftp Service onStartCommand
,08-24 14:31:47.156  7135  7135 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:47.156  7135  7135 V BluetoothFtpService: Starting Listening on sockets
08-24 14:31:47.157  7135  7135 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 14:31:47.157  7135  7135 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 14:31:47.157  7135  7135 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 14:31:47.157  7135  7135 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:47.157  7135  7135 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-24 14:31:47.157  7135  7135 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-24 14:31:47.159  7135  7135 V BluetoothFtpService: Handler(): got msg=1
08-24 14:31:47.160  7135  7135 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-24 14:31:47.160  7135  7135 V BluetoothFtpService: Ftp Service initSocket
08-24 14:31:47.166  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:47.167  7135  7135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:31:47.169  7135  7135 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-24 14:31:47.169  7135  7135 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-24 14:31:47.171  7135  7736 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-24 14:31:47.189  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:47.190  7135  7135 V BluetoothSapService: Sap Service onCreate
08-24 14:31:47.193  7135  7135 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:47.193  7135  7135 V BluetoothSapService: state: 12
08-24 14:31:47.193  7135  7135 V BluetoothSapService: Starting SAP server process
,08-24 14:31:47.196  7135  7135 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-24 14:31:47.197  7135  7738 V BluetoothSapService: Sap Service initRfcommSocket
08-24 14:31:47.193  7737  7737 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:47.193  7737  7737 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:47.204  1036  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:47.205  7135  7738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:47.206  7135  7738 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,08-24 14:31:47.206  7135  7738 V BluetoothSapService: Succeed to create listening socket 
08-24 14:31:47.206  7135  7738 V BluetoothSapService: Accepting socket connection...
08-24 14:31:47.226  7737  7737 V BT_SAP  : Event pipe created
08-24 14:31:47.226  7737  7737 V BT_SAP  : create_server_socket qcom.sap.server
08-24 14:31:47.226  7737  7737 V BT_SAP  : created socket fd 6
,08-24 14:31:47.553  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 14:31:47.553  1036  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 14:31:47.622  1036  1540 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-24 14:31:47.630  1036  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-24 14:31:47.692  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7706
08-24 14:31:47.692  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7707
08-24 14:31:47.692  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7717
08-24 14:31:47.693  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7722
08-24 14:31:47.693  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7745
,08-24 14:31:47.719  1036  1915 I ActivityManager: Killing 7514:com.lge.bnr/1000 (adj 15): empty #17
,08-24 14:31:47.751  1036  1576 W libprocessgroup: failed to open /acct/uid_1000/pid_7514/cgroup.procs: No such file or directory
,08-24 14:31:47.915  1036  2003 I ActivityManager: Killing 6874:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-24 14:31:47.938  7058  7058 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-24 14:31:47.941  7058  7058 W System.err: android.os.DeadObjectException
08-24 14:31:47.941  7058  7058 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 14:31:47.941  7058  7058 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 14:31:47.942  7058  7058 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-24 14:31:47.942  7058  7058 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-24 14:31:47.942  7058  7058 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-24 14:31:47.942  7058  7058 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-24 14:31:47.942  7058  7058 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:31:47.942  7058  7058 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:31:47.942  7058  7058 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:31:47.942  7058  7058 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 14:31:47.942  7058  7058 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:47.942  7058  7058 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:47.942  7058  7058 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 14:31:47.942  7058  7058 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 14:31:47.942  7058  7058 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-24 14:31:47.942  7058  7058 W System.err: android.os.DeadObjectException
08-24 14:31:47.943  7058  7058 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 14:31:47.943  7058  7058 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 14:31:47.943  7058  7058 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-24 14:31:47.943  7058  7058 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-24 14:31:47.943  7058  7058 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-24 14:31:47.943  7058  7058 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-24 14:31:47.943  7058  7058 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:31:47.943  7058  7058 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:31:47.943  7058  7058 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:31:47.943  7058  7058 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 14:31:47.943  7058  7058 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:47.943  7058  7058 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:47.943  7058  7058 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 14:31:47.943  7058  7058 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 14:31:47.943  7058  7058 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-24 14:31:47.944  7058  7058 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-24 14:31:47.948  1036  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_6874/cgroup.procs: No such file or directory
08-24 14:31:47.948  1036  1052 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-24 14:31:47.952  7058  7058 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-24 14:31:47.952  7,058  7058 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-24 14:31:48.003  1036  1915 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7753 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 14:31:48.014  7058  7058 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-24 14:31:48.122  7135  7135 V BluetoothOppNotification: new notify threadi!
,08-24 14:31:48.122  7135  7135 V BluetoothOppNotification: send delay message
08-24 14:31:48.126  7135  7776 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 14:31:48.245  1036  1051 I art     : Explicit concurrent mark sweep GC freed 93390(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.770ms total 175.469ms
08-24 14:31:48.246  7135  7776 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36046776 on behalf of 
08-24 14:31:48.248  7135  7776 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-24 14:31:48.253  7135  7776 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 14:31:48.255  7135  7776 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12aa3177 on behalf of 
08-24 14:31:48.255  7135  7776 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 14:31:48.257  7135  7776 V BluetoothOppNotification: outbound notification was removed.
08-24 14:31:48.257  7135  7776 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 14:31:48.259  7135  7776 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@69381e4 on behalf of 
08-24 14:31:48.260  7135  7776 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-24 14:31:48.267  7135  7776 V BluetoothOppNotification: inbound notification was removed.
08-24 14:31:48.267  7135  7776 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 14:31:48.268  7135  7776 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18b9f64d on behalf of 
08-24 14:31:48.287  7753  7753 D UEI.SmartControl: Quickset Services start...
,08-24 14:31:48.290  7753  7753 I UEI.SmartControl: Manufacture = LGE
08-24 14:31:48.290  7753  7753 D UEI.SmartControl: Id = LGNevo
08-24 14:31:48.292  7753  7753 D UEI.SmartControl: File observer start...
08-24 14:31:48.292  7753  7753 E UEI.SmartControl: IR Port is disabled: false
08-24 14:31:48.293  7753  7753 D UEI.SmartControl: Starting file observer...
08-24 14:31:48.293  7753  7753 D UEI.SmartControl: Extracting JNI libs...
08-24 14:31:48.293  7753  7753 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-24 14:31:48.387  7753  7753 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-24 14:31:48.388  7753  7753 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-24 14:31:48.388  7753  7753 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-24 14:31:48.429  7753  7753 I UEI.SmartControl: --- Selecting new region: 6
,08-24 14:31:48.431  7753  7753 I UEI.SmartControl: Model = LG-D855
,08-24 14:31:48.433  7753  7753 D UEI.SmartControl: QS Service created
,08-24 14:31:48.451  7753  7753 I UEI.SmartControl: Service initServices...
,08-24 14:31:48.457  7753  7753 D UEI.SmartControl: QS start get config
,08-24 14:31:48.543  7753  7753 D UEI.SmartControl: Loading JNI Libs...
,08-24 14:31:48.550  1036  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 14:31:48.550  1036  1915 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33df5ce2 mBinding = false
08-24 14:31:48.575  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-24 14:31:48.579  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 14:31:48.580  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-24 14:31:48.580  1036  1097 D BluetoothManagerService: Message: 2
08-24 14:31:48.581  1036  1097 D BluetoothManagerService: Sending off request.
08-24 14:31:48.582  7135  7151 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-24 14:31:48.582  7135  7594 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-24 14:31:48.582  7135  7594 D BluetoothAdapterProperties: Setting state to 13
08-24 14:31:48.582  7135  7594 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 14:31:48.583  7135  7594 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 14:31:48.583  7135  7594 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-24 14:31:48.585  7135  7598 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:31:48.586  7135  7594 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 14:31:48.587  7135  7594 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 14:31:48.588  7135  7723 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-24 14:31:48.588  7135  7723 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:31:48.588  7135  7723 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-24 14:31:48.588  7135  7723 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-24 14:31:48.588  7135  7723 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-24 14:31:48.588  7135  7723 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-24 14:31:48.588  7135  7723 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-24 14:31:48.588  7135  7723 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-24 14:31:48.590  7135  7725 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-24 14:31:48.592  7135  7734 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:31:48.593  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-24 14:31:48.593  7135  7663 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-24 14:31:48.594  7135  7736 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:31:48.594  7135  7738 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:31:48.600  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 14:31:48.600  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 14:31:48.600  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 14:31:48.600  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 14:31:48.600  7135  7663 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:31:48.600  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 14:31:48.600  7135  7663 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:48.600  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 14:31:48.600  7135  7663 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 14:31:48.601  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-24 14:31:48.601  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-24 14:31:48.601  7135  7663 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 14:31:48.605  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:48.605  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:48.605  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:48.605  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:48.605  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:48.605  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:48.605  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:48.605  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:48.605  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:48.610  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:48.610  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:48.612  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:48.612  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:48.612  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:48.612  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:48.612  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:48.612  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:48.612  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:48.612  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:48.612  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:31:48.615  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:48.616  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:48.616  1036  1097 D BluetoothManagerService: Message: 60
08-24 14:31:48.616  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,08-24 14:31:48.617  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-24 14:31:48.624  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:48.630  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-24 14:31:48.636  7135  7135 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:48.636  7135  7135 D BluetoothMapService: STATE_TURNING_OFF
08-24 14:31:48.636  7135  7135 V BluetoothMapService: Handler(): got msg=4
08-24 14:31:48.636  7135  7135 D BluetoothMapService: MAP Service closeService in
08-24 14:31:48.636  7135  7135 D BluetoothMapMasInstance: MAP Service shutdown
08-24 14:31:48.636  7135  7135 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 14:31:48.637  7135  7135 V BluetoothMapService: MAP Service closeService out
08-24 14:31:48.637  7135  7135 V BtOppService: Receiver DISABLED_ACTION 
08-24 14:31:48.638  7135  7135 I BtOppRfcommListener: stopping Accept Thread
08-24 14:31:48.638  7135  7135 V BtOppRfcommListener: close mBtServerSocket
08-24 14:31:48.639  7135  7734 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 14:31:48.640  7135  7135 V BtOppRfcommListener: waiting for thread to terminate
08-24 14:31:48.640  7135  7135 V BtOppRfcommListener: done waiting for thread to terminate
08-24 14:31:48.642  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:48.647  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:48.651  7003  7003 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-24 14:31:48.658  7003  7003 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 14:31:48.661  7135  7135 V BtOppService: onDestroy
08-24 14:31:48.662  7135  7135 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-24 14:31:48.668  7135  7135 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 14:31:48.668  7135  7135 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:48.668  7135  7135 V BluetoothPbapReceiver: ***********state = 13
,08-24 14:31:48.672  7135  7135 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-24 14:31:48.676  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:31:48.677  7135  7135 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:48.677  7135  7135 V BluetoothPbapService: state: 13
08-24 14:31:48.678  7135  7135 V BluetoothPbapService: Pbap Service closeService in
08-24 14:31:48.681  7135  7135 V BluetoothPbapService: successfully stopped pbap service
08-24 14:31:48.681  7135  7135 V BluetoothPbapService: Pbap Service closeService out
,08-24 14:31:48.685  7135  7135 V BluetoothPbapService: Pbap Service onDestroy
08-24 14:31:48.685  7135  7135 V BluetoothPbapService: Pbap Service closeService in
08-24 14:31:48.685  7135  7135 V BluetoothPbapService: Pbap Service closeService out
08-24 14:31:48.685  7135  7135 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-24 14:31:48.703  7003  7003 D DockEventReceiver: finishStartingService: stopping service
08-24 14:31:48.704  7003  7003 D BluetoothPbap: Proxy object disconnected
08-24 14:31:48.704  7003  7003 D PbapServerProfile: Bluetooth service disconnected
08-24 14:31:48.708  7003  7003 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-24 14:31:48.724  7003  7003 D BluetoothPermissionRequest: onReceive
08-24 14:31:48.725  7003  7003 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-24 14:31:48.744  7003  7003 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 14:31:48.749  7135  7135 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-24 14:31:48.749  7135  7135 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-24 14:31:48.758  7135  7135 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-24 14:31:48.762  7135  7135 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:48.762  7135  7135 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 14:31:48.765  7135  7135 V BluetoothFtpService: Ftp Service onStartCommand
,08-24 14:31:48.765  7135  7135 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:48.765  7135  7135 V BluetoothFtpService: Ftp Service closeService
08-24 14:31:48.767  7135  7135 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-24 14:31:48.768  7135  7135 V BluetoothFtpService: successfully stopped ftp service
08-24 14:31:48.769  7135  7135 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 14:31:48.769  7135  7135 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 14:31:48.769  7135  7135 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 14:31:48.769  7135  7135 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:48.769  7135  7135 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-24 14:31:48.769  7135  7135 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-24 14:31:48.771  7135  7135 V BluetoothFtpService: Ftp Service onDestroy
08-24 14:31:48.771  7135  7135 V BluetoothFtpService: Ftp Service closeService
08-24 14:31:48.771  7135  7135 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:48.771  7135  7135 V BluetoothSapService: state: 13
08-24 14:31:48.772  7135  7135 V BluetoothSapService: Stopping SAP server process
08-24 14:31:48.773  7135  7135 V BluetoothSapService: Sap Service closeSapService in
08-24 14:31:48.773  7135  7135 V BluetoothSapService: Close listen Socket : 
08-24 14:31:48.773  7135  7135 V BluetoothSapService: Close rfcomm Socket : 
08-24 14:31:48.773  7135  7135 V BluetoothSapService: Close sapd  Socket : 
08-24 14:31:48.776  7135  7135 V BluetoothSapService: Sap Service closeSapService out
08-24 14:31:48.776  7135  7135 V BluetoothSapService: Sap Service onDestroy
08-24 14:31:48.776  7135  7135 V BluetoothSapService: Sap Service closeSapService in
08-24 14:31:48.776  7135  7135 V BluetoothSapService: Close listen Socket : 
08-24 14:31:48.776  7135  7135 V BluetoothSapService: Close rfcomm Socket : 
08-24 14:31:48.776  7135  7135 V BluetoothSapService: Close sapd  Socket : 
08-24 14:31:48.777  7135  7135 V BluetoothSapService: Sap Service closeSapService out
,08-24 14:31:49.028  7753  7753 I UEI.SmartControl: Supports setup maps: true
,08-24 14:31:49.031  7753  7753 D UEI.SmartControl: QS start statue = true Error code = 0
,08-24 14:31:49.031  7753  7753 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-24 14:31:49.031  7753  7753 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-24 14:31:49.031  7753  7753 I UEI.SmartControl: ### init IR Blaster...
08-24 14:31:49.037  7753  7753 D serial_port: Configuring serial port
,08-24 14:31:49.045  7753  7753 E UEI.SmartControl: UEIBLaster setting for 616
,08-24 14:31:49.045  7753  7753 I UEI.SmartControl: Setting serial record hearder size = 2
,08-24 14:31:49.047  7753  7753 I UEI.SmartControl: configuring settings for MAXQ616
,08-24 14:31:49.047  7753  7753 I UEI.SmartControl: Get version...
,08-24 14:31:49.065  7753  7807 D UEI.SmartControl: serial port data available: 21
,08-24 14:31:49.094  7753  7753 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-24 14:31:49.094  7753  7753 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-24 14:31:49.096  7753  7753 I UEI.SmartControl: QS saving settings...
08-24 14:31:49.098  7753  7753 D UEI.SmartControl: IR Blaster version: 25672567
,08-24 14:31:49.115  7753  7807 D UEI.SmartControl: serial port data available: 4
,08-24 14:31:49.160  7753  7753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-24 14:31:49.168  7753  7816 I UEI.SmartControl: Device manager: loading config....
08-24 14:31:49.169  7753  7816 D UEI.SmartControl: ----------- loading internal config...
08-24 14:31:49.175  7753  7753 E UEI.SmartControl: Services init done
08-24 14:31:49.175  7753  7753 D UEI.SmartControl: QS Service init finished
08-24 14:31:49.177  7753  7753 D UEI.SmartControl: QS Service version name: 2.1.91
08-24 14:31:49.177  7753  7753 D UEI.SmartControl: QS Service version code: 201091
08-24 14:31:49.178  7753  7753 D UEI.SmartControl: Service requested: Control
,08-24 14:31:49.185  7753  7816 E UEI.SmartControl: Loading SETTINGS...
08-24 14:31:49.188  7753  7753 D UEI.SmartControl: Request IControl service: devices are loaded...
08-24 14:31:49.191  1036  1051 I ActivityManager: Killing 7058:com.lge.qremote/u0a112 (adj 15): empty #17
,08-24 14:31:49.208  7753  7816 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-24 14:31:49.216  7753  7815 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-24 14:31:49.217  7753  7815 D UEI.SmartControl: -----service ready thread exits
,08-24 14:31:49.253  1036  1967 W libprocessgroup: failed to open /acct/uid_10112/pid_7058/cgroup.procs: No such file or directory
,08-24 14:31:49.286  7753  7753 D UEI.SmartControl: Internal service binding...
,08-24 14:31:49.504  7135  7598 D bt_hci_bdroid: cleanup
,08-24 14:31:49.512  7135  7665 I bt_lpm  : LPM is already off!!!
08-24 14:31:49.512  7135  7695 I bt_userial_mct: exiting userial_read_thread
08-24 14:31:49.512  7135  7695 D bt_userial_mct: Leaving userial_evt_read_thread()
08-24 14:31:49.513  7135  7663 W bt-btif : ag scb idx 1 not allocated
08-24 14:31:49.513  7135  7663 E bt-btif : BTA AG is already disabled, ignoring ...
08-24 14:31:49.513  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 14:31:49.513  7135  7663 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 14:31:49.514  7135  7663 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 14:31:49.515  7135  7663 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 14:31:49.517  7135  7598 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-24 14:31:49.517  7135  7665 I bt_vendor: hw_epilog_process
08-24 14:31:49.517  7135  7598 D bt_hci_bdroid: cleanup Finalizing cleanup
08-24 14:31:49.517  7135  7598 D bt_userial_mct: userial_close
08-24 14:31:49.517  7135  7598 E bt_userial_mct: pthread_join() FAILED result:3
08-24 14:31:49.517  7135  7598 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-24 14:31:49.526  7135  7598 D bt_hci_bdroid: set_power 0
08-24 14:31:49.526  7135  7598 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-24 14:31:49.526  7135  7598 I bt_vendor: bluetooth satus is on
08-24 14:31:49.526  7135  7598 I bt_vendor: bt-vendor : resetting BT status
08-24 14:31:49.526  7135  7598 I bt_vendor: Starting hciattach daemon
08-24 14:31:49.526  7135  7598 I bt_vendor: try to set false
,08-24 14:31:49.533  7135  7598 I bt_vendor: Starting hciattach daemon
08-24 14:31:49.533  7135  7598 I bt_vendor: try to set false
08-24 14:31:49.534  7135  7598 I bt_vendor: cleanup
08-24 14:31:49.535  7135  7663 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-24 14:31:49.535  7135  7598 I GKI_LINUX: GKI_exit_task 0 done
08-24 14:31:49.535  7135  7598 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-24 14:31:49.537  7135  7594 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 14:31:49.542  7135  7135 D HeadsetService: Received stop request...Stopping profile...
,08-24 14:31:49.546  7135  7135 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 14:31:49.546  7135  7135 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 14:31:49.547  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:49.547  7135  7632 D HeadsetStateMachine: Exit Disconnected: -1
08-24 14:31:49.550  1875  1875 D BluetoothHeadset: Proxy object disconnected
08-24 14:31:49.550  1875  1875 D BluetoothHeadset: Proxy object disconnected
08-24 14:31:49.551  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-24 14:31:49.551  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-24 14:31:49.552  1875  1875 D BluetoothHeadset: Proxy object disconnected
08-24 14:31:49.556  7135  7135 D A2dpService: Received stop request...Stopping profile...
,08-24 14:31:49.559  7135  7655 D A2dpStateMachine: Exit Disconnected: -1
08-24 14:31:49.562  7135  7594 D BluetoothAdapterState: Stopping profile services that were post enabled
08-24 14:31:49.562  7135  7135 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-24 14:31:49.563  7135  7135 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-24 14:31:49.563  7135  7135 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 14:31:49.564  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:49.565  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-24 14:31:49.565  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-24 14:31:49.566  7135  7135 D HidService: Received stop request...Stopping profile...
08-24 14:31:49.566  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:49.568  7135  7135 D HeadsetStateMachine: Unbinding service...
,08-24 14:31:49.571  7135  7135 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 14:31:49.571  7135  7135 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 14:31:49.571  7135  7135 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 14:31:49.572  7135  7135 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 14:31:49.572  7135  7135 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 14:31:49.572  7135  7135 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 14:31:49.572  7135  7135 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 14:31:49.574  7135  7135 D HealthService: Received stop request...Stopping profile...
08-24 14:31:49.574  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:49.576  7135  7135 D PanService: Received stop request...Stopping profile...
08-24 14:31:49.577  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:49.578  7135  7135 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 14:31:49.579  7135  7135 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 14:31:49.579  7135  7135 D BtGatt.GattService: stop()
08-24 14:31:49.579  7135  7135 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 14:31:49.580  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
,08-24 14:31:49.584  7135  7135 D BluetoothMapService: Received stop request...Stopping profile...
08-24 14:31:49.584  7135  7135 D BluetoothMapService: stop()
08-24 14:31:49.586  7135  7135 D BluetoothMapEmailAppObserver: deinitObservers()
08-24 14:31:49.586  7135  7135 D BluetoothMapEmailAppObserver: removeReceiver()
08-24 14:31:49.587  7135  7135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@205014b6
08-24 14:31:49.588  7135  7135 V BluetoothMapService: Handler(): got msg=4
08-24 14:31:49.588  7135  7135 D BluetoothMapService: MAP Service closeService in
08-24 14:31:49.588  7135  7135 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 14:31:49.588  7135  7135 V BluetoothMapService: MAP Service closeService out
08-24 14:31:49.589  7135  7594 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-24 14:31:49.589  7135  7594 D BluetoothAdapterProperties: Setting state to 10
08-24 14:31:49.589  7135  7594 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 14:31:49.590  1036  1097 D BluetoothManagerService: Message: 60
08-24 14:31:49.590  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-24 14:31:49.590  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-24 14:31:49.590  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:31:49.591  7135  7594 I BluetoothAdapterState: Entering OffState
08-24 14:31:49.591  1875  2575 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:31:49.592  1875  2614 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 14:31:49.596  7003  7454 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 14:31:49.597  7003  7454 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:31:49.599  7003  7454 D BluetoothPan: onBluetoothStateChange on: false
08-24 14:31:49.599  7135  7135 I BluetoothA2dpServiceJni: cleanupNative
08-24 14:31:49.599  7135  7656 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-24 14:31:49.600  7135  7135 I GKI_LINUX: GKI_exit_task 2 done
08-24 14:31:49.600  7135  7135 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 14:31:49.603  7003  7454 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 14:31:49.604  7135  7135 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 14:31:49.604  7135  7135 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-24 14:31:49.607  7003  7454 D BluetoothMap: onBluetoothStateChange: up=false
08-24 14:31:49.609  7135  7135 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 14:31:49.609  7135  7135 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 14:31:49.609  7135  7135 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 14:31:49.610  1875  1893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:31:49.611  7135  7135 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 14:31:49.611  7135  7135 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 14:31:49.612  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:31:49.613  7003  7454 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:31:49.614  7135  7135 D BluetoothMapService: cleanup()
08-24 14:31:49.614  7135  7135 D BluetoothMapService: MAP Service closeService in
08-24 14:31:49.614  7135  7135 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 14:31:49.614  7135  7135 V BluetoothMapService: MAP Service closeService out
08-24 14:31:49.616  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-24 14:31:49.616  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-24 14:31:49.620  1036  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-24 14:31:49.620  1036  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-24 14:31:49.620  1036  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@33df5ce2 mBinding = false
08-24 14:31:49.621  1036  1097 D BluetoothManagerService: Sending unbind request.
08-24 14:31:49.626  7135  7598 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-24 14:31:49.627  7135  7135 I GKI_LINUX: GKI_exit_task 1 done
08-24 14:31:49.627  7135  7135 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-24 14:31:49.627  7135  7135 I BluetoothServiceJni: cleanupNative: return from cleanup
08-24 14:31:49.627  7135  7135 I art     : --- WEIRD: removing null entry 248
08-24 14:31:49.627  7135  7135 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-24 14:31:49.627  7135  7135 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-24 14:31:49.628  7135  7135 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-24 14:31:49.632  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-24 14:31:49.635  7135  7135 I art     : System.exit called, status: 0
08-24 14:31:49.635  7135  7135 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-24 14:31:49.654   329  1386 V AudioFlinger: 7135 died, releasing its sessions
08-24 14:31:49.654   329  1386 V AudioFlinger:  pid 1875 @ 0
08-24 14:31:49.654   329  1386 V AudioFlinger:  pid 3175 @ 1
08-24 14:31:49.654   329  1386 V AudioFlinger:  pid 3175 @ 2
,08-24 14:31:49.664  7003  7003 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-24 14:31:49.665  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-24 14:31:49.666  1969  2180 D LGBluetoothAPIService: Message: 101
08-24 14:31:49.666  1969  2180 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-24 14:31:49.666  1969  2180 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-24 14:31:49.666  1969  2180 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-24 14:31:49.766  1036  2052 I ActivityManager: Process com.android.bluetooth (pid 7135) has died
08-24 14:31:49.767  1036  2052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-24 14:31:49.767  1036  2052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-24 14:31:49.776  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:49.776  1969  2180 D LGBluetoothAPIService: Message: 2
08-24 14:31:49.776  1969  2180 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-24 14:31:49.778  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 14:31:49.779  7003  7003 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-24 14:31:49.780  7003  7003 D LGBluetoothEventManager: [BTUI] clear device connection state
08-24 14:31:49.780  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:49.782  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:49.784  7003  7003 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-24 14:31:49.794  1605  1605 D BluetoothAdapter: 394673929: getState() :  mService = null. Returning STATE_OFF
,08-24 14:31:49.795  1605  1605 D BluetoothAdapter: 394673929: getState() :  mService = null. Returning STATE_OFF
08-24 14:31:49.834  1036  1949 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7837 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-24 14:31:49.836  7003  7003 D DockEventReceiver: finishStartingService: stopping service
08-24 14:31:49.860   361   361 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 476us total 23.298ms
,08-24 14:31:49.881   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 20.379ms
,08-24 14:31:49.903   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 423us total 21.407ms
08-24 14:31:49.928  7837  7837 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-24 14:31:49.928  7837  7837 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 14:31:49.928  7837  7837 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-24 14:31:49.929  7837  7837 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-24 14:31:49.949  7837  7837 D BluetoothAdapterApp: Loading JNI Library
,08-24 14:31:49.985  7837  7837 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@11f4e7de Instance Count = 1
,08-24 14:31:49.992  7837  7837 D BluetoothAdapterApp: onCreate
,08-24 14:31:50.019  7837  7837 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-24 14:31:50.019  7837  7837 D ProfileConfigQcom: Adding HeadsetService
,08-24 14:31:50.019  7837  7837 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-24 14:31:50.019  7837  7837 D ProfileConfigQcom: Adding A2dpService
08-24 14:31:50.020  7837  7837 D ProfileConfigQcom: [BTUI] HidService is supported
,08-24 14:31:50.020  7837  7837 D ProfileConfigQcom: Adding HidService
08-24 14:31:50.020  7837  7837 D ProfileConfigQcom: [BTUI] HealthService is supported
08-24 14:31:50.020  7837  7837 D ProfileConfigQcom: Adding HealthService
,08-24 14:31:50.021  7837  7837 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-24 14:31:50.022  7837  7837 D ProfileConfigQcom: [BTUI] PanService is supported
,08-24 14:31:50.022  7837  7837 D ProfileConfigQcom: Adding PanService
08-24 14:31:50.022  7837  7837 D ProfileConfigQcom: [BTUI] GattService is supported
,08-24 14:31:50.022  7837  7837 D ProfileConfigQcom: Adding GattService
08-24 14:31:50.023  7837  7837 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-24 14:31:50.023  7837  7837 D ProfileConfigQcom: Adding BluetoothMapService
08-24 14:31:50.023  7837  7837 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-24 14:31:50.024  7837  7837 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-24 14:31:50.025  7837  7837 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:50.026  7837  7837 V BluetoothPbapReceiver: ***********state = 10
08-24 14:31:50.028  7837  7837 V LGMDMManagerInternal: Create singleton instance
,08-24 14:31:50.166  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:31:50.178  7837  7837 D LGBluetoothAPIServer: [BTUI] onCreate()
08-24 14:31:50.179  7003  7003 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-24 14:31:50.181  7837  7837 D LGBluetoothAPIServer: [BTUI] onBind()
,08-24 14:31:50.184  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-24 14:31:50.184  1969  2180 D LGBluetoothAPIService: Message: 100
08-24 14:31:50.185  1969  2180 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-24 14:31:50.189  7003  7003 D BluetoothPermissionRequest: onReceive
08-24 14:31:50.192  7003  7003 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 14:31:50.192  7003  7003 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-24 14:31:50.194  7003  7003 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-24 14:31:50.201  7837  7837 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-24 14:31:50.205  7837  7837 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:50.209  7837  7837 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 14:31:50.209  7837  7837 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 14:31:50.210  7837  7837 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 14:31:50.211  7837  7837 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:50.211  7837  7837 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-24 14:31:50.216  7075  7075 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-24 14:31:51.615  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-24 14:31:51.640  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 14:31:51.640  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:51.675  1036  1450 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 14:31:51.712  1036  1093 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7866 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-24 14:31:51.759  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-24 14:31:51.767  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-24 14:31:51.771  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-24 14:31:51.790  1036  1036 D administrator: Handling package changes for user 0
,08-24 14:31:51.804  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-24 14:31:51.832  7866  7866 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 14:31:51.920  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-24 14:31:51.920  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-24 14:31:51.922  7866  7866 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:51.922  7866  7866 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:31:51.963  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 14:31:51.971  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-24 14:31:51.979  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-24 14:31:51.981  2504  2504 V GmsNetworkLocationProvi: DISABLE
08-24 14:31:52.021  2504  2504 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-24 14:31:52.034  7866  7912 I Babel   : MmsConfig: mnc/mcc: 0/0
08-24 14:31:52.034  7866  7912 I Babel   : MmsConfig.loadMmsSettings
,08-24 14:31:52.037  7866  7912 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-24 14:31:52.037  7866  7912 I Babel   : MmsConfig.loadFromDatabase
,08-24 14:31:52.065  7866  7912 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-24 14:31:52.065  7866  7912 I Babel   : MmsConfig.loadFromResources
08-24 14:31:52.065  7866  7866 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:52.071  7866  7912 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-24 14:31:52.072  7866  7912 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-24 14:31:52.084  7866  7910 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 14:31:52.086  7866  7910 W AudioCapabilities: Unsupported mime audio/qcelp
08-24 14:31:52.088  7866  7910 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-24 14:31:52.115  1817  7914 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-24 14:31:52.115  1817  7914 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-24 14:31:52.120  7205  7205 I AppUp4:CustModeStarterReceiver: onReceive
08-24 14:31:52.125  7205  7205 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30e91578
08-24 14:31:52.125  7205  7205 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 14:31:52.125  7205  7205 D AppUp4:CustFacade: isPhone : true
08-24 14:31:52.125  7205  7205 D AppUp4:CustModeStarterReceiver: begin check event
08-24 14:31:52.125  7205  7205 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-24 14:31:52.126  7866  7910 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-24 14:31:52.131  7866  7910 W AudioCapabilities: Unsupported mime audio/qcelp
,08-24 14:31:52.135  7866  7910 W AudioCapabilities: Unsupported mime audio/evrc
08-24 14:31:52.135  1817  5243 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-24 14:31:52.154  7866  7910 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-24 14:31:52.156  7866  7910 W VideoCapabilities: Unsupported mime video/divx
08-24 14:31:52.159  7866  7910 W VideoCapabilities: Unsupported mime video/divx311
08-24 14:31:52.162  1036  2070 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7917 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-24 14:31:52.163  7866  7910 W VideoCapabilities: Unsupported mime video/divx4
,08-24 14:31:52.167  1036  2019 I ActivityManager: Killing 7027:com.lge.sync/1000 (adj 15): empty #17
08-24 14:31:52.181  1036  1545 D WifiService: Client connection lost with reason: 4
,08-24 14:31:52.184  7866  7910 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-24 14:31:52.194  7866  7910 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-24 14:31:52.197  7866  7910 W AudioCapabilities: Unsupported mime audio/eac3
,08-24 14:31:52.197  7866  7910 W AudioCapabilities: Unsupported mime audio/ac3
08-24 14:31:52.198  7866  7910 W AudioCapabilities: Unsupported mime audio/g726
08-24 14:31:52.198  7866  7910 W AudioCapabilities: Unsupported mime audio/wma-voice
08-24 14:31:52.199  7866  7910 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-24 14:31:52.199  7866  7910 W AudioCapabilities: Unsupported mime audio/adpcm
08-24 14:31:52.201  7866  7910 W VideoCapabilities: Unsupported mime video/theora
08-24 14:31:52.202  7866  7910 W VideoCapabilities: Unsupported mime video/mjpg
08-24 14:31:52.274  1036  1576 W libprocessgroup: failed to open /acct/uid_1000/pid_7027/cgroup.procs: No such file or directory
,08-24 14:31:52.308  7917  7917 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:31:52.309  7917  7917 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 14:31:52.309  7917  7917 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-24 14:31:52.310  7917  7917 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-24 14:31:52.311  7917  7917 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-24 14:31:52.377  7917  7917 I SystemConfig: BUILD Country: EU
08-24 14:31:52.377  7917  7917 I SystemConfig: BUILD Operator: OPEN
,08-24 14:31:52.412  1036  1052 I ActivityManager: Killing 7236:com.lge.email/u0a23 (adj 15): empty #17
,08-24 14:31:52.501  1036  2039 W libprocessgroup: failed to open /acct/uid_10023/pid_7236/cgroup.procs: No such file or directory
,08-24 14:31:52.541  1036  1052 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7937 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-24 14:31:52.546  7917  7935 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-24 14:31:52.546  7917  7935 I SystemConfig: existFile = false
08-24 14:31:52.546  7917  7935 I SystemConfig: canReadFile = false
08-24 14:31:52.546  7917  7935 I SystemConfig: systemFeature RCS result false
08-24 14:31:52.546  7917  7935 D SystemConfig: refreshRcsSupport() :false
,08-24 14:31:52.580  7937  7937 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:31:52.580  7937  7937 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 14:31:52.580  7937  7937 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-24 14:31:52.581  7937  7937 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 14:31:52.642  1036  1546 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-24 14:31:52.669  7937  7937 I AppConfig: Total System Memory = 2995761152
,08-24 14:31:52.678  7937  7937 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-24 14:31:52.784  1036  1949 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7956 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 14:31:52.786  1036  1949 I ActivityManager: Killing 7105:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-24 14:31:52.857  1036  2003 W libprocessgroup: failed to open /acct/uid_10026/pid_7105/cgroup.procs: No such file or directory
08-24 14:31:52.904  1036  1092 D LocationProviderProxy: applying state to connected service
,08-24 14:31:53.037  7956  7956 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-24 14:31:53.129  7956  7956 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:53.129  7956  7956 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:31:53.198  7956  7956 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-24 14:31:53.222  7956  7956 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 14:31:53.224  7956  7956 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 14:31:53.254  7956  7956 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:53.255  7956  7956 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-24 14:31:53.274  1036  2052 I ActivityManager: Killing 6492:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-24 14:31:53.421  1036  1596 W libprocessgroup: failed to open /acct/uid_1000/pid_6492/cgroup.procs: No such file or directory
,08-24 14:31:53.430  2849  4221 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-24 14:31:53.435  2849  4221 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1eeaed1c on behalf of 7956
08-24 14:31:53.437  5082  7999 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-24 14:31:53.479  1036  2070 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8000 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-24 14:31:53.502  7956  7956 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-24 14:31:53.530  7956  7956 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-24 14:31:53.575  8000  8000 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-24 14:31:53.597  8000  8000 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-24 14:31:53.597  8000  8000 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-24 14:31:53.597  8000  8000 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-24 14:31:53.597  8000  8000 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-24 14:31:53.597  8000  8000 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-24 14:31:53.597  8000  8000 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-24 14:31:53.615  1036  1912 I ActivityManager: Killing 7266:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-24 14:31:53.719  1036  2052 W libprocessgroup: failed to open /acct/uid_10046/pid_7266/cgroup.procs: No such file or directory
,08-24 14:31:53.949  1036  1912 V SIM_STK : Menu title from STK is T-Mobile
,08-24 14:31:53.974  5082  7999 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 537 ms] updated apps [took 537 ms] 
,08-24 14:31:54.159  7753  7817 D UEI.SmartControl: Internal timer expired: 1
,08-24 14:31:54.159  7753  7817 D UEI.SmartControl: unbind internal service
,08-24 14:31:54.176  7753  7753 D UEI.SmartControl: Service.onUnbind: IControl
08-24 14:31:54.178  7753  7753 D UEI.SmartControl: Service.onDestroy
08-24 14:31:54.178  7753  7753 D UEI.SmartControl: Lock is in USE false
08-24 14:31:54.178  7753  7753 D UEI.SmartControl: unbind internal service
08-24 14:31:54.179  7753  7753 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@8561124
08-24 14:31:54.179  7753  7753 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-24 14:31:54.179  7753  7753 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-24 14:31:54.179  7753  7753 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-24 14:31:54.179  7753  7753 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-24 14:31:54.179  7753  7753 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-24 14:31:54.179  7753  7753 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-24 14:31:54.179  7753  7753 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-24 14:31:54.179  7753  7753 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-24 14:31:54.179  7753  7753 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:54.180  7753  7753 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:31:54.180  7753  7753 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 14:31:54.180  7753  7753 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:54.180  7753  7753 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:54.180  7753  7753 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 14:31:54.180  7753  7753 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 14:31:54.180  7753  7753 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@8561124
,08-24 14:31:54.187  7753  7753 D serial_port: close(fd = 25)
08-24 14:31:54.191  7753  7753 I UEI.SmartControl: Serial port is closed.
08-24 14:31:54.191  7753  7753 I UEI.SmartControl: Serial port is closed.
08-24 14:31:54.191  7753  7753 D UEI.SmartControl: Blaster closed
08-24 14:31:54.191  7753  7753 D UEI.SmartControl: Shut down QS...
08-24 14:31:54.191  7753  7753 D UEI.SmartControl: Stopping QS lib
08-24 14:31:54.191  7753  7753 D UEI.SmartControl: QS lib stop result = true
08-24 14:31:54.191  7753  7753 D UEI.SmartControl: Stopped QS lib
08-24 14:31:54.192  7753  7753 D UEI.SmartControl: Stopped file observer...
08-24 14:31:54.192  7753  7753 D UEI.SmartControl: QS shutdown complete
,08-24 14:31:54.771  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:31:54.771  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18e4534a added. We now have 6 listener(s)
,08-24 14:31:54.771  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:54.787  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:54.787  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fd432bb added. We now have 7 listener(s)
08-24 14:31:54.787  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:54.788  6702  6828 I System.out: IsBluetoothEnabled
08-24 14:31:54.789  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:54.789  1036  1052 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-24 14:31:54.790  1036  1097 D BluetoothManagerService: Message: 2
08-24 14:31:54.794  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:54.796  1036  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:54.796  1036  2052 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-24 14:31:54.816  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 14:31:54.817  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 14:31:54.817  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-24 14:31:54.818  1036  1097 D BluetoothManagerService: Message: 1
08-24 14:31:54.818  1036  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-24 14:31:54.843  1036  1097 D BluetoothManagerService: Message: 20
08-24 14:31:54.844  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b2b07f3:true
,08-24 14:31:54.848  7837  7837 D BluetoothAdapterState: make
08-24 14:31:54.853  7837  7837 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-24 14:31:54.853  7837  7837 I bluedroid-qcom: init
08-24 14:31:54.854  7837  8044 I BluetoothAdapterState: Entering OffState
08-24 14:31:54.854  7837  7837 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-24 14:31:54.855  7837  7837 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-24 14:31:54.855  7837  7837 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 14:31:54.855  7837  7837 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 14:31:54.855  7837  7837 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-24 14:31:54.857  7837  7837 I bluedroid-qcom: get_profile_interface socket
08-24 14:31:54.857  7837  7837 I bluedroid-qcom: get_profile_interface map_client
,08-24 14:31:54.862  7837  8048 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-24 14:31:54.864  7837  8048 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-24 14:31:54.863  8047  8047 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:54.863  8047  8047 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:54.874  8047  8047 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-24 14:31:54.874  8047  8047 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-24 14:31:54.874  8047  8047 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-24 14:31:54.880  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 14:31:54.881  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 14:31:54.882  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-24 14:31:54.882  1036  1097 D BluetoothManagerService: Message: 40
08-24 14:31:54.882  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-24 14:31:54.883  7837  7854 I bluedroid-qcom: config_hci_snoop_log
08-24 14:31:54.884  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-24 14:31:54.884  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-24 14:31:54.885  8047  8047 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-24 14:31:54.888  7837  8048 D BluetoothAdapterProperties: Name is: G3
,08-24 14:31:54.896  8047  8047 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-24 14:31:54.896  8047  8047 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-24 14:31:54.898  7837  8044 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-24 14:31:54.899  7837  8044 D BluetoothAdapterProperties: Setting state to 11
08-24 14:31:54.899  7837  8044 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 14:31:54.902  7837  8044 I LGBluetoothServiceJni: classInitNative: succeeds
,08-24 14:31:54.907  1036  1097 D BluetoothManagerService: Message: 60
08-24 14:31:54.907  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-24 14:31:54.907  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-24 14:31:54.909  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:54.912  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 14:31:54.915  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:54.917  7003  7003 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-24 14:31:54.924  7837  7837 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 14:31:54.924  7837  7837 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:54.924  7837  7837 V BluetoothPbapReceiver: ***********state = 11
08-24 14:31:54.933  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:31:54.950  7837  8044 D BluetoothBondStateMachine: make
,08-24 14:31:54.953  7003  7003 D BluetoothPermissionRequest: onReceive
08-24 14:31:54.955  7837  8044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
08-24 14:31:54.955  7837  8044 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-24 14:31:54.955  7837  8044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
08-24 14:31:54.955  7837  8044 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-24 14:31:54.956  7837  8059 I BluetoothBondStateMachine: StableState(): Entering Off State
08-24 14:31:54.956  7837  8044 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-24 14:31:54.959  7003  7003 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 14:31:54.959  7837  8044 E BluetoothAdapterService: File transfer profiles supported!!
08-24 14:31:54.966  7837  8044 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 14:31:54.972  7837  7837 D HeadsetService: Received start request. Starting profile...
08-24 14:31:54.972  7837  7837 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 14:31:54.973  7837  7837 D LGBluetoothHfpAdapter: Version 1.6
08-24 14:31:54.974  7837  8044 E BluetoothAdapterService: File transfer profiles supported!!
08-24 14:31:54.979  7837  7837 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-24 14:31:54.980  7837  7837 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 14:31:54.981  7837  7837 D HeadsetStateMachine: make
08-24 14:31:54.982  7837  8044 E BluetoothAdapterService: File transfer profiles supported!!
08-24 14:31:54.987  7837  8044 E BluetoothAdapterService: File transfer profiles supported!!
08-24 14:31:54.993  7837  8044 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 14:31:54.999  7837  8044 E BluetoothAdapterService: File transfer profiles supported!!
08-24 14:31:55.021  7837  7837 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:31:55.021  7837  7837 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:31:55.023  7837  8044 V LGMDMManager: Create singleton instance
08-24 14:31:55.026  7837  8044 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-24 14:31:55.027  7837  7837 D HeadsetStateMachine: max_hf_connections = 1
08-24 14:31:55.027  7837  7837 I bluedroid-qcom: get_profile_interface handsfree
08-24 14:31:55.030  7837  7837 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-24 14:31:55.031   329   329 V AudioPolicyService: registerClient() client 0xb558af00, uid 1002
08-24 14:31:55.032   329  1386 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-24 14:31:55.032   329  1386 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 14:31:55.032   329  1386 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 14:31:55.032  7837  7837 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-24 14:31:55.032   329  1387 V AudioFlinger: registerClient() client 0xb55817f0, pid 7837
08-24 14:31:55.033   329  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:55.033   329  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 14:31:55.033  3175  3190 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:55.033  3175  3190 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 14:31:55.033   329  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:55.033   329  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 14:31:55.033  1875  1894 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:55.033  1875  1894 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 14:31:55.033  7837  7853 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:55.033  1875  1894 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:55.033  1875  1894 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 14:31:55.034  3175  3191 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:55.034  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:55.034  3175  3191 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 14:31:55.034  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 14:31:55.034  7837  7853 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-24 14:31:55.034  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:55.034  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 14:31:55.034  7837  7853 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:55.034  7837  7853 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-24 14:31:55.034  7837  7837 V ToneGenerator: Create Track: 0xb4928a80
08-24 14:31:55.034  1605  2096 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 14:31:55.034  7837  7837 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-24 14:31:55.034  1605  2096 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 14:31:55.034  7837  7837 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-24 14:31:55.034  1605  2096 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 14:31:55.034  1605  2096 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 14:31:55.034   329  1386 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 14:31:55.034   329  1386 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-24 14:31:55.034   329  1386 V AudioPolicyManagerEx: Aud,ioPolicyManagerEx: getOutputForDevice
08-24 14:31:55.034   329  1386 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 14:31:55.035   329  1387 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 14:31:55.035   329   329 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 14:31:55.035   329   329 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-24 14:31:55.035   329   329 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 14:31:55.035   329   329 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 14:31:55.035  7837  7837 V AudioSystem: getLatency() output 2, latency 50
08-24 14:31:55.035  7837  7837 V AudioSystem: getFrameCount() output 2, frameCount 960
,08-24 14:31:55.035  7837  7837 V AudioTrack: createTrack_l() output 2 afLatency 50
08-24 14:31:55.036   329  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 14:31:55.036   329  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 14:31:55.036   329  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 14:31:55.036   329  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 14:31:55.036   329  1386 V AudioFlinger: createTrack() lSessionId: 23
08-24 14:31:55.037  7837  7837 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-24 14:31:55.038   329   329 V AudioFlinger: acquiring 23 from 7837, for 7837
08-24 14:31:55.038   329   329 V AudioFlinger:  added new entry for 23
08-24 14:31:55.038  7837  7837 V ToneGenerator: ToneGenerator INIT OK, time: 147133
08-24 14:31:55.039  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
08-24 14:31:55.042  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
08-24 14:31:55.043  7837  8065 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-24 14:31:55.044  7837  8065 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 14:31:55.045  7837  8065 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 14:31:55.045  7837  8065 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-24 14:31:55.046  7837  7837 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:55.050  7837  7837 D A2dpService: Received start request. Starting profile...
,08-24 14:31:55.052  7837  7837 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 14:31:55.053   329  1386 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7837
08-24 14:31:55.054   329  1386 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-24 14:31:55.054   329  1386 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-24 14:31:55.054   329  1386 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-24 14:31:55.054   329  1386 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-24 14:31:55.054   329  1386 V voice   : voice_set_parameters: exit with code(0)
08-24 14:31:55.054   329  1386 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-24 14:31:55.054   329  1386 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-24 14:31:55.054   329  1386 V msm8974_platform: platform_set_parameters: exit with code(0)
08-24 14:31:55.054   329  1386 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-24 14:31:55.054   329  1386 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-24 14:31:55.054   329  1386 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-24 14:31:55.054  7837  8065 V ToneGenerator: ToneGenerator destructor
08-24 14:31:55.054  7837  8065 V ToneGenerator: stopTone
08-24 14:31:55.054  7837  8065 V ToneGenerator: Delete Track: 0xb4928a80
08-24 14:31:55.055  7837  7837 V Avrcp   : make
08-24 14:31:55.056  7837  8065 V AudioTrack: ~AudioTrack, releasing session id from 7837 on behalf of 7837
08-24 14:31:55.056   329   329 V AudioPolicyService: AudioCommandThread() adding release output 2
08-24 14:31:55.057   329   329 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-24 14:31:55.057  7837  7837 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-24 14:31:55.057   329  1387 V AudioFlinger: releasing 23 from 7837 for 7837
08-24 14:31:55.057  7837  7837 I bluedroid-qcom: get_profile_interface avrcp
08-24 14:31:55.057   329  1387 V AudioFlinger:  decremented refcount to 0
08-24 14:31:55.057   329  1387 V AudioFlinger: purging stale effects
08-24 14:31:55.057   329  1260 V AudioPolicyService: AudioCommandThread() waking up
08-24 14:31:55.057   329  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-24 14:31:55.057   329  1260 V AudioPolicyManager: releaseOutput() 2
08-24 14:31:55.057   329  1260 V AudioPolicyService: AudioCommandThread() going to sleep
08-24 14:31:55.057   329   329 V AudioFlinger: PlaybackThread::Track destructor
08-24 14:31:55.057   329   329 V AudioFlinger: removeClient_l() pid 7837, calling pid 329
08-24 14:31:55.067  7837  7837 V AudioManager: registerRemoteController: size of Media player list: 0
,08-24 14:31:55.070  7837  7837 E AudioManager: No RCC entry present to update
,08-24 14:31:55.070  7837  7837 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-24 14:31:55.076  7837  7837 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-24 14:31:55.078  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-24 14:31:55.078  7837  7837 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-24 14:31:55.083  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-24 14:31:55.211  1036  1968 V SIM_STK : Menu title from STK is T-Mobile
,08-24 14:31:55.211  1036  1968 V SIM_STK : Menu title from STK is T-Mobile
,08-24 14:31:55.296  1036  2019 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-24 14:31:55.313  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-24 14:31:55.319  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 14:31:55.320  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 14:31:55.320  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 14:31:55.320  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music,
08-24 14:31:55.320  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 14:31:55.321  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 14:31:55.321  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 14:31:55.321  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 14:31:55.321  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 14:31:55.321  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 14:31:55.321  7837  7837 I BluetoothA2dpServiceJni: classInitNative
08-24 14:31:55.322  7837  7837 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 14:31:55.322  7837  7837 D A2dpStateMachine: make
08-24 14:31:55.325  7837  7837 I bluedroid-qcom: get_profile_interface a2dp
08-24 14:31:55.326  7837  8076 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-24 14:31:55.329  7837  7837 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-24 14:31:55.330  7837  7837 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-24 14:31:55.331  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
08-24 14:31:55.332  7837  7837 I BluetoothHidServiceJni: classInitNative: succeeds
08-24 14:31:55.335  7837  8075 D A2dpStateMachine: Enter Disconnected: -2
,08-24 14:31:55.335  7837  7837 D HidService: Received start request. Starting profile...
,08-24 14:31:55.335  7837  7837 I bluedroid-qcom: get_profile_interface hidhost
08-24 14:31:55.336  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
08-24 14:31:55.336  7837  7837 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 14:31:55.339  7837  7837 D HealthService: Received start request. Starting profile...
,08-24 14:31:55.345  7837  7837 I bluedroid-qcom: get_profile_interface health
08-24 14:31:55.347  7837  7837 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-24 14:31:55.347  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7,
08-24 14:31:55.350  7837  7837 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-24 14:31:55.359  7837  7837 D PanService: Received start request. Starting profile...
08-24 14:31:55.359  7837  7837 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 14:31:55.359  7837  7837 I bluedroid-qcom: get_profile_interface pan
08-24 14:31:55.370  7837  7837 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-24 14:31:55.370  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
,08-24 14:31:55.374  7837  7837 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-24 14:31:55.381  7837  7837 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 14:31:55.382  7837  7837 D BtGatt.GattService: Received start request. Starting profile...
08-24 14:31:55.382  7837  7837 D BtGatt.GattService: start()
08-24 14:31:55.382  7837  7837 I bluedroid-qcom: get_profile_interface gatt
08-24 14:31:55.382  7837  7837 D BtGatt.AdvertiseManager: advertise manager created
,08-24 14:31:55.389  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
08-24 14:31:55.392  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
08-24 14:31:55.393  7837  7837 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-24 14:31:55.394  7837  7837 V BluetoothMapService: BluetoothMapBinder()
,08-24 14:31:55.395  7837  7837 D BluetoothMapService: Received start request. Starting profile...
08-24 14:31:55.395  7837  7837 D BluetoothMapService: start()
08-24 14:31:55.399  7837  7837 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-24 14:31:55.399  7837  7837 D BluetoothMapEmailAppObserver: createReceiver()
08-24 14:31:55.401  7837  7837 D BluetoothMapEmailAppObserver: initObservers()
08-24 14:31:55.401  7837  7837 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-24 14:31:55.410  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
,08-24 14:31:55.411  7837  7837 D HeadsetStateMachine: Proxy object connected
08-24 14:31:55.412  7837  7837 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-24 14:31:55.412  7837  7837 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-24 14:31:55.414  7837  8065 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 14:31:55.415  7837  8065 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 14:31:55.415  7837  8065 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-24 14:31:55.419  7837  7837 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 14:31:55.419  7837  7837 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 14:31:55.420  7837  7837 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 14:31:55.420  7837  7837 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 14:31:55.420  7837  7837 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:55.420  7837  7837 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-24 14:31:55.427  7837  7837 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-24 14:31:55.430  7837  7837 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 14:31:55.434  7837  7837 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 14:31:55.434  7837  7837 V PanService: [BTUI] SIM Extra State :ABSENT
08-24 14:31:55.438  7837  7837 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 14:31:55.441  7837  7837 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-24 14:31:55.441  7837  7837 V BluetoothMapService: Handler(): got msg=1
,08-24 14:31:55.445  7837  8044 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,08-24 14:31:55.445  7837  8044 I bluedroid-qcom: enable
08-24 14:31:55.447  7837  8044 I bt_hci_bdroid: init
08-24 14:31:55.448  7837  8086 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-24 14:31:55.448  7837  8086 I bt-btu  : btu_task pending for preload complete event
08-24 14:31:55.449  7837  8044 I bt_vendor: bt-vendor : init
08-24 14:31:55.449  7837  8044 I bt_vendor: bt-vendor : get_bt_soc_type
08-24 14:31:55.450  7837  8044 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-24 14:31:55.450  7837  8044 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-24 14:31:55.450  7837  8044 D bt_userial_mct: userial_init
08-24 14:31:55.450  7837  8044 D bt_hci_bdroid: set_power 1
08-24 14:31:55.450  7837  8044 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-24 14:31:55.450  7837  8044 I bt_vendor: Starting hciattach daemon
08-24 14:31:55.450  7837  8044 I bt_vendor: try to set true
08-24 14:31:55.443  8093  8093 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:55.443  8093  8093 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 14:31:55.479  8094  8094 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-24 14:31:55.581  8101  8101 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-24 14:31:55.599  8102  8102 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 14:31:55.628  8104  8104 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 14:31:55.641  8105  8105 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-24 14:31:55.654  8107  8107 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 14:31:55.668  8108  8108 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-24 14:31:55.691  8110  8110 I libmdmdetect: ESOC framework not supported
,08-24 14:31:55.693  8110  8110 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-24 14:31:55.703  8110  8110 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-24 14:31:55.703  8110  8110 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-24 14:31:55.703  8110  8110 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-24 14:31:55.703  8110  8110 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-24 14:31:55.703  8110  8110 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-24 14:31:55.703  8110  8110 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-24 14:31:55.703  8110  8110 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-24 14:31:55.757  8110  8111 E QC-QMI  : qmi_client [8110] 15: failed to locate client data
,08-24 14:31:55.760   471   471 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-24 14:31:55.760   471   471 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-24 14:31:55.804  8115  8115 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-24 14:31:55.822  8116  8116 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 14:31:55.856  7837  8044 I bt_vendor: bluetooth satus is on
,08-24 14:31:55.857  7837  8044 D bt_hci_bdroid: preload
08-24 14:31:55.860  7837  8092 D bt_userial_mct: userial_open(port:0)
,08-24 14:31:55.860  7837  8092 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-24 14:31:55.866  7837  8092 I bt_vendor: Done intiailizing UART
08-24 14:31:55.870  7837  8092 I bt_vendor: Done intiailizing UART
08-24 14:31:55.870  7837  8092 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-24 14:31:55.871  7837  8092 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-24 14:31:55.871  7837  8118 D bt_userial_mct: Entering userial_read_thread()
08-24 14:31:55.872  7837  8086 I bt-btu  : btu_task received preload complete event
08-24 14:31:55.872  7837  8086 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-24 14:31:55.873  7837  8086 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-24 14:31:55.878  7837  8086 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_HCI
,08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_SMP
,08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 14:31:55.883  7837  8086 I         : BTE_InitTraceLevels -- TRC_BTIF
08-24 14:31:55.991  7837  8086 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-24 14:31:55.991  7837  8086 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0161061 
08-24 14:31:56.016  7837  8086 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0161061 
,08-24 14:31:56.031  7837  8048 E bt-btif : Calling BTA_HhEnable
08-24 14:31:56.031  7837  8048 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-24 14:31:56.031  7837  8048 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-24 14:31:56.033  7837  8086 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-24 14:31:56.034  7837  8086 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-24 14:31:56.034  7837  8086 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-24 14:31:56.035  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 14:31:56.036  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 14:31:56.036  7837  8086 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-24 14:31:56.036  7837  8086 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-24 14:31:56.036  7837  8048 D BluetoothAdapterProperties: Name is: G3
08-24 14:31:56.037  7837  8048 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:31:56.038  7837  8048 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 14:31:56.038  7837  8048 D bt_hci_bdroid: postload
08-24 14:31:56.039  7837  8092 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 14:31:56.039  7837  8092 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 14:31:56.040  7837  8048 D bte_conf: Device ID record 1 : primary
08-24 14:31:56.040  7837  8048 D bte_conf:   vendorId            = 00c4
08-24 14:31:56.040  7837  8048 D bte_conf:   vendorIdSource      = 0001
08-24 14:31:56.040  7837  8086 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-24 14:31:56.041  7837  8092 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 14:31:56.040  7837  8048 D bte_conf:   product             = 13a1
08-24 14:31:56.041  7837  8048 D bte_conf:   version             = 1000
08-24 14:31:56.041  7837  8048 D bte_conf:   clientExecutableURL = 
08-24 14:31:56.041  7837  8048 D bte_conf:   serviceDescription  = 
08-24 14:31:56.041  7837  8048 D bte_conf:   documentationURL    = 
08-24 14:31:56.041  7837  8048 D bte_conf: bte_load_did_conf no section named DID2.
08-24 14:31:56.044  7837  8044 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-24 14:31:56.044  7837  8044 D BluetoothAdapterProperties: ScanMode =  20
08-24 14:31:56.044  7837  8044 D BluetoothAdapterProperties: State =  11
08-24 14:31:56.044  7837  8044 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-24 14:31:56.045  7837  8044 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
,08-24 14:31:56.051  7837  8044 D BluetoothAdapterProperties: Setting state to 12
08-24 14:31:56.051  7837  8044 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 14:31:56.052  7837  8048 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 14:31:56.052  7837  8048 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 14:31:56.053  8123  8123 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:56.053  8123  8123 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:56.062  1036  1097 D BluetoothManagerService: Message: 60
08-24 14:31:56.062  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-24 14:31:56.062  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-24 14:31:56.062  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:31:56.066  7837  8086 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 14:31:56.068  7837  8086 W bt-smp  : Plain text(LSB ~ MSB) = 16 46 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 14:31:56.068  7837  8086 W bt-smp  : Encrypted text(LSB ~ MSB) = 1e f7 ce b5 6e 36 25 a6 ab 30 e5 1c 85 fa b6 86 
08-24 14:31:56.068  7837  8092 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 14:31:56.068  7837  8086 W bt-btm  : Stopping oneshot timer
08-24 14:31:56.070  7837  8118 E bt_mct  : hci lib postload completed
08-24 14:31:56.080  7837  8044 I BluetoothAdapterState: Entering On State
,08-24 14:31:56.097  7837  8048 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 14:31:56.097  7837  8048 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-24 14:31:56.102  7837  8086 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 14:31:56.102  7837  8086 W bt-smp  : Plain text(LSB ~ MSB) = 3d 64 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 14:31:56.102  7837  8086 W bt-smp  : Encrypted text(LSB ~ MSB) = ca 19 fa a1 b1 b0 36 51 36 fc 56 2c 91 bb 4c e7 
08-24 14:31:56.102  7837  8086 W bt-btm  : Stopping oneshot timer
08-24 14:31:56.116  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:56.116  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:56.116  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:56.116  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:56.116  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:56.116  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:56.116  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:56.116  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:56.120  7837  8086 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 14:31:56.120  7837  8086 W bt-smp  : Plain text(LSB ~ MSB) = 73 84 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 14:31:56.120  7837  8086 W bt-smp  : Encrypted text(LSB ~ MSB) = ea c6 1d 1a 59 b3 2f da c1 93 e9 cf e7 b0 ee b4 
08-24 14:31:56.121  7837  8086 W bt-btm  : Stopping oneshot timer
08-24 14:31:56.127  1875  2614 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:31:56.135  7837  8086 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 14:31:56.136  7837  8086 W bt-smp  : Plain text(LSB ~ MSB) = e2 3e 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 14:31:56.136  7837  8086 W bt-smp  : Encrypted text(LSB ~ MSB) = 5e dc 78 7b 30 3c a9 45 f4 04 e4 d3 c6 b4 8b 49 
08-24 14:31:56.137  7837  8086 W bt-btm  : Stopping oneshot timer
08-24 14:31:56.143  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:56.151  7837  8044 D LGBluetoothServiceAdapter: [BTUI] OnState
08-24 14:31:56.151  7837  8044 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-24 14:31:56.151  7837  8044 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-24 14:31:56.154  7837  8044 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-24 14:31:56.154  7837  8044 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-24 14:31:56.156  1036  1036 D BluetoothHeadset: Proxy object connected
08-24 14:31:56.159  7837  8086 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 14:31:56.159  7837  8086 W bt-smp  : Plain text(LSB ~ MSB) = 16 81 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 14:31:56.159  7837  8086 W bt-smp  : Encrypted text(LSB ~ MSB) = dd 3b 41 e6 5a a4 7d 23 dc 74 45 e3 fa fe b7 fd 
08-24 14:31:56.159  7837  8086 W bt-btm  : Stopping oneshot timer
08-24 14:31:56.171  1875  1875 D BluetoothHeadset: Proxy object connected
,08-24 14:31:56.182  8128  8128 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-24 14:31:56.188  1875  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:31:56.191  1875  1875 D BluetoothHeadset: Proxy object connected
08-24 14:31:56.192  7003  7020 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 14:31:56.201  7003  7454 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 14:31:56.209  7003  7023 D BluetoothPan: onBluetoothStateChange on: true
08-24 14:31:56.210  7003  7023 D BluetoothPan: onBluetoothStateChange call bindService
,08-24 14:31:56.210  7003  7003 D BluetoothA2dp: Proxy object connected
08-24 14:31:56.210  7003  7003 D A2dpProfile: Bluetooth service connected
08-24 14:31:56.212  7003  7003 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:31:56.212  7003  7003 D PanProfile: Bluetooth service connected
08-24 14:31:56.212  7003  7454 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 14:31:56.215  7003  7020 D BluetoothMap: onBluetoothStateChange: up=true
08-24 14:31:56.216  7003  7003 D BluetoothInputDevice: Proxy object connected
08-24 14:31:56.216  7003  7003 D HidProfile: Bluetooth service connected
08-24 14:31:56.216  1875  1893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:31:56.220  7003  7003 D BluetoothMap: Proxy object connected
08-24 14:31:56.220  7003  7003 D MapProfile: Bluetooth service connected
08-24 14:31:56.220  7003  7003 D BluetoothMap: getConnectedDevices()
08-24 14:31:56.221  1875  1875 D BluetoothHeadset: Proxy object connected
08-24 14:31:56.221  7837  7854 V BluetoothMapService: getConnectedDevices()
08-24 14:31:56.222  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:31:56.223  1036  1036 D BluetoothA2dp: Proxy object connected
08-24 14:31:56.223  7003  7023 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:31:56.225  7003  7003 D BluetoothHeadset: Proxy object connected
08-24 14:31:56.226  7003  7003 D HeadsetProfile: Bluetooth service connected
08-24 14:31:56.226  1036  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-24 14:31:56.226  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-24 14:31:56.228  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 14:31:56.230  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:56.232  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:56.232  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-24 14:31:56.234  1036  1097 D BluetoothManagerService: Message: 40
08-24 14:31:56.234  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-24 14:31:56.235  1969  2180 D LGBluetoothAPIService: Message: 1
08-24 14:31:56.235  1969  2180 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-24 14:31:56.235  1969  2180 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-24 14:31:56.235  1969  2180 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-24 14:31:56.236  7837  7837 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:56.236  7837  7837 D BluetoothMapService: STATE_ON
08-24 14:31:56.241  7003  7003 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-24 14:31:56.242  7003  7003 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 14:31:56.245  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
08-24 14:31:56.245  7837  7837 V BluetoothPbapService: Pbap Service onCreate
08-24 14:31:56.245  7837  7837 V BluetoothPbapService: Starting PBAP service
,08-24 14:31:56.248  7837  7837 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-24 14:31:56.248  7837  7837 V BluetoothMapService: Handler(): got msg=1
08-24 14:31:56.249  7837  7837 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-24 14:31:56.249  7837  7837 V BluetoothPbapService: Pbap Service onBind
08-24 14:31:56.250  7837  8146 D BluetoothMapMasInstance: MAS initSocket()
08-24 14:31:56.251  7837  8146 D BluetoothMapMasInstance:   masId = 00
08-24 14:31:56.251  7837  8146 D BluetoothMapMasInstance:   msgTypes = 0e
08-24 14:31:56.251  7837  8146 D BluetoothMapMasInstance:   masName = SMS/MMS
08-24 14:31:56.251  7837  8146 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-24 14:31:56.253  7837  7837 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:56.253  7837  7837 V BluetoothPbapService: state: 12
08-24 14:31:56.253  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:56.253  7837  7837 V BluetoothPbapService: Handler(): got msg=1
08-24 14:31:56.254  7837  7837 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-24 14:31:56.254  7837  7837 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 14:31:56.254  7837  7837 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:56.254  7837  7837 V BluetoothPbapReceiver: ***********state = 12
08-24 14:31:56.255  7837  8146 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:56.257  7837  8147 V BluetoothPbapService: Pbap Service initSocket
08-24 14:31:56.257  2206  2206 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:31:56.257  7837  8146 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-24 14:31:56.257  7837  8146 V BluetoothMapMasInstance: Succeed to create listening socket 
08-24 14:31:56.258  7837  8146 D BluetoothMapMasInstance: Accepting socket connection...
,08-24 14:31:56.258  1036  2039 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:56.258  2206  2206 D c       : Getting all permits...
08-24 14:31:56.258  2206  2206 D a       : Opening database...
08-24 14:31:56.259  7837  8048 D BluetoothAdapterProperties: Scan Mode:21
08-24 14:31:56.259  7837  8048 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-24 14:31:56.260  2206  2206 D a       : Opening database auth.proximity.permit_store...
08-24 14:31:56.261  2206  2206 D a       : Closing database...
08-24 14:31:56.262  7837  8147 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:56.262  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:56.264  7003  7003 D DockEventReceiver: finishStartingService: stopping service
08-24 14:31:56.265  7003  7003 D BluetoothPbap: Proxy object connected
08-24 14:31:56.265  7003  7003 D PbapServerProfile: Bluetooth service connected
08-24 14:31:56.267  7837  8147 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-24 14:31:56.267  7837  8147 V BluetoothPbapService: Succeed to create listening socket 
08-24 14:31:56.267  7837  8147 V BluetoothPbapService: Accepting socket connection...
08-24 14:31:56.271  7003  7003 D BluetoothPermissionRequest: onReceive
,08-24 14:31:56.273  7003  7003 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 14:31:56.275  7003  7003 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 14:31:56.278  7837  7837 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-24 14:31:56.279  7837  7837 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-24 14:31:56.283  7837  7837 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-24 14:31:56.300  7837  7837 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 14:31:56.300  7837  7837 V BtOppService: onCreate
,08-24 14:31:56.304  7837  7837 V BluetoothOppNotification: send message
08-24 14:31:56.306  7837  7837 V BtOppService: Starting RfcommListener
08-24 14:31:56.312  7837  7837 D BluetoothOppPreference: Dumping Names:  
,08-24 14:31:56.312  7837  7837 D BluetoothOppPreference: {}
08-24 14:31:56.312  7837  7837 D BluetoothOppPreference: Dumping Channels:  
08-24 14:31:56.312  7837  7837 D BluetoothOppPreference: {}
08-24 14:31:56.312  7837  7837 V BtOppService: onStartCommand
08-24 14:31:56.313  7837  8155 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 14:31:56.314  7837  8155 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 14:31:56.314  7837  8152 V BtOppService: Deleted complete outbound shares, number =  0
08-24 14:31:56.315  7837  7837 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:56.316  7837  7837 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 14:31:56.316  7837  8155 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5abb623 on behalf of 
08-24 14:31:56.316  7837  8152 V BtOppService: Deleted complete inbound failed shares, number = 0
08-24 14:31:56.317  7837  8152 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-24 14:31:56.317  7837  8155 V BluetoothOppNotification: update too frequent, put in queue
08-24 14:31:56.318  7837  8155 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 14:31:56.318  7837  8155 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 14:31:56.325  7837  7837 V BluetoothOppNotification: new notify threadi!
,08-24 14:31:56.326  7837  7837 V BluetoothOppNotification: send delay message
08-24 14:31:56.326  7837  7837 V BtOppService: start RfcommListener
08-24 14:31:56.329  7837  8156 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 14:31:56.329  7837  7837 V BtOppService: RfcommListener started
08-24 14:31:56.329  7837  7837 V BtOppService: ContentObserver received notification
08-24 14:31:56.329  7837  7837 V BtOppService: ContentObserver received notification
08-24 14:31:56.330  7837  8157 V BtOppRfcommListener: Starting RFCOMM listener....
08-24 14:31:56.331  1036  1912 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:56.332  7837  8157 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:56.333  7837  8157 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-24 14:31:56.333  7837  8157 V BtOppRfcommListener: Started RFCOMM listener....
08-24 14:31:56.333  7837  8157 I BtOppRfcommListener: Accept thread started.
08-24 14:31:56.333  7837  8157 V BtOppRfcommListener: Accepting connection...
08-24 14:31:56.341  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
,08-24 14:31:56.342  7837  7837 V BluetoothFtpService: Ftp Service onCreate
08-24 14:31:56.342  7837  7837 I BluetoothFtpService: Ftp Service onCreate
08-24 14:31:56.342  7837  7837 V BluetoothFtpService: Ftp Service onStartCommand
08-24 14:31:56.342  7837  7837 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:56.342  7837  7837 V BluetoothFtpService: Starting Listening on sockets
08-24 14:31:56.342  7837  7837 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 14:31:56.342  7837  7837 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 14:31:56.342  7837  7837 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 14:31:56.342  7837  7837 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:56.342  7837  7837 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-24 14:31:56.342  7837  7837 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-24 14:31:56.344  7837  7837 V BluetoothFtpService: Handler(): got msg=1
08-24 14:31:56.345  7837  7837 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-24 14:31:56.345  7837  7837 V BluetoothFtpService: Ftp Service initSocket
08-24 14:31:56.347  1036  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:56.348  7837  7837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:56.352  7837  7837 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-24 14:31:56.352  7837  7837 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-24 14:31:56.353  7837  8158 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-24 14:31:56.377  7837  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@232c75b7
08-24 14:31:56.377  7837  7837 V BluetoothSapService: Sap Service onCreate
08-24 14:31:56.379  7837  7837 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:56.379  7837  7837 V BluetoothSapService: state: 12
08-24 14:31:56.379  7837  7837 V BluetoothSapService: Starting SAP server process
,08-24 14:31:56.382  7837  7837 V BluetoothSapService: SAP Service startRfcommListenerThread
08-24 14:31:56.383  7837  8160 V BluetoothSapService: Sap Service initRfcommSocket
08-24 14:31:56.384  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:56.373  8159  8159 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:56.373  8159  8159 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:56.385  7837  8160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:56.386  7837  8160 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-24 14:31:56.386  7837  8160 V BluetoothSapService: Succeed to create listening socket 
08-24 14:31:56.386  7837  8160 V BluetoothSapService: Accepting socket connection...
08-24 14:31:56.409  1036  2052 I art     : Explicit concurrent mark sweep GC freed 27377(1346KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.355ms total 90.791ms
08-24 14:31:56.410  7837  8152 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fd1d54c on behalf of 
08-24 14:31:56.410  7837  8155 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d2995 on behalf of 
,08-24 14:31:56.414  8159  8159 V BT_SAP  : Event pipe created
08-24 14:31:56.415  8159  8159 V BT_SAP  : create_server_socket qcom.sap.server
08-24 14:31:56.415  8159  8159 V BT_SAP  : created socket fd 6
08-24 14:31:56.415  7837  8156 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d544aaa on behalf of 
08-24 14:31:56.416  7837  8156 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 14:31:56.416  7837  8155 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 14:31:56.416  7837  8155 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 14:31:56.417  7837  8155 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@251fc69b on behalf of 
08-24 14:31:56.417  7837  8155 V BluetoothOppNotification: update too frequent, put in queue
08-24 14:31:56.418  7837  8156 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 14:31:56.419  7837  8155 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 14:31:56.419  7837  8156 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33ecfa38 on behalf of 
08-24 14:31:56.419  7837  8156 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 14:31:56.420  7837  8156 V BluetoothOppNotification: outbound notification was removed.
08-24 14:31:56.420  7837  8156 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 14:31:56.421  7837  8156 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f73ca11 on behalf of 
08-24 14:31:56.421  7837  8156 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 14:31:56.422  7837  8156 V BluetoothOppNotification: inbound notification was removed.
08-24 14:31:56.422  7837  8156 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 14:31:56.423  7837  8156 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36046776 on behalf of 
,08-24 14:31:56.841  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:56.841  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:56.841  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:56.841  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:56.841  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:56.841  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:56.841  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:56.841  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:56.844  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:56.846  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:56.846  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c70c3d8 added. We now have 8 listener(s)
08-24 14:31:56.846  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:56.849  1036  1968 D WifiServiceImplEx: setWifiEnabled: false pid=6702, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 14:31:56.849  1036  1968 D WifiService: setWifiEnabled: false pid=6702, uid=10118
08-24 14:31:56.849  1036  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 14:31:56.859  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:56.862  1036  1967 D WifiServiceImplEx: setWifiEnabled: true pid=6702, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 14:31:56.863  1036  1967 D WifiService: setWifiEnabled: true pid=6702, uid=10118
08-24 14:31:56.863  1036  1967 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 14:31:56.880  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 14:31:56.880  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 14:31:56.880  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-24 14:31:56.884  1036  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-24 14:31:56.884  1036  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-24 14:31:56.887  1036  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-24 14:31:56.887  1036  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 14:31:56.887  1036  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-24 14:31:56.887  1036  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 14:31:56.887  1036  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-24 14:31:56.887  1036  1540 E WifiHW  : unknown target_country: EU , set to default
08-24 14:31:56.887  1036  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-24 14:31:56.887  1036  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-24 14:31:56.887  1036  1540 I WifiUtil: gEnableBmps=1
08-24 14:31:57.337  7837  7837 V BluetoothOppNotification: new notify threadi!
08-24 14:31:57.337  7837  7837 V BluetoothOppNotification: send delay message
,08-24 14:31:57.377  7837  8179 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-24 14:31:57.395  7837  8179 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12aa3177 on behalf of 
08-24 14:31:57.396  7837  8179 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-24 14:31:57.405  7837  8179 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 14:31:57.406  7837  8179 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@69381e4 on behalf of 
08-24 14:31:57.406  7837  8179 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 14:31:57.408  7837  8179 V BluetoothOppNotification: outbound notification was removed.
08-24 14:31:57.408  7837  8179 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 14:31:57.409  7837  8179 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18b9f64d on behalf of 
,08-24 14:31:57.412  7837  8179 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-24 14:31:57.413  7837  8179 V BluetoothOppNotification: inbound notification was removed.
08-24 14:31:57.413  7837  8179 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 14:31:57.414  7837  8179 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3cc78502 on behalf of 
,08-24 14:31:57.524   325   895 D SoftapController: Softap fwReload - Ok
,08-24 14:31:57.530  1036  1540 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (639ms)
08-24 14:31:57.535   325   895 D CommandListener: Setting iface cfg
08-24 14:31:57.535   325   895 D CommandListener: Trying to bring down wlan0
08-24 14:31:57.545   325   895 D CommandListener: Clearing all IP addresses on wlan0
,08-24 14:31:57.550  1036  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-24 14:31:57.557  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 14:31:57.557  1036  1097 D Tethering: InitialState.processMessage what=4
,08-24 14:31:57.583  8182  8182 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 14:31:57.591  1036  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 14:31:57.591  1036  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 14:31:57.591  1036  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 14:31:57.592  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 14:31:57.593  8182  8182 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:57.598  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:57.606  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-24 14:31:57.640  1036  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-24 14:31:57.641  1036  1540 D WifiMonitor: connecting to supplicant
08-24 14:31:57.641  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-24 14:31:57.642  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 14:31:57.642  7003  7003 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 14:31:57.643  7003  7003 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 14:31:57.643  7003  7003 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 14:31:57.644  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 14:31:57.646  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:57.666  7003  7003 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 14:31:57.666  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 14:31:57.666  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 14:31:57.666  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 14:31:57.666  7003  7003 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 14:31:57.667  7003  7003 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-24 14:31:57.668  8182  8182 I wpa_supplicant: Successfully initialized wpa_supplicant
08-24 14:31:57.677  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 14:31:57.677  7003  7003 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 14:31:57.677  7003  7003 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 14:31:57.678  7003  7003 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 14:31:57.680  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-24 14:31:57.683  7003  7003 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 14:31:57.683  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 14:31:57.683  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 14:31:57.683  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 14:31:57.683  7003  7003 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 14:31:57.683  7003  7003 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 14:31:57.707  8182  8182 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 14:31:57.708  8182  8182 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-24 14:31:57.723  1036  1915 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8200 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-24 14:31:57.773  8182  8182 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 14:31:57.800  8182  8182 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-24 14:31:57.807  8182  8182 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-24 14:31:57.808  1036  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-24 14:31:57.808  1036  8220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-24 14:31:57.808  1036  8220 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 14:31:57.808  1036  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-24 14:31:57.809  1036  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-24 14:31:57.809  1036  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-24 14:31:57.810  1036  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:57.810  1036  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:57.811  1036  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:57.811  1036  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:57.812  1036  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-24 14:31:57.812  1036  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-24 14:31:57.813  1036  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-24 14:31:57.813  1036  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-24 14:31:57.813  1036  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-24 14:31:57.828  1036  1967 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8222 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 14:31:57.829  1036  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 14:31:57.829  1036  1540 E WifiStateMachine: useWiFiOffloading() : false
08-24 14:31:57.829  1036  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-24 14:31:57.831  1036  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
08-24 14:31:57.832  1036  1540 D WifiNative-wlan0: SET update_config 1: returned true
08-24 14:31:57.832  1036  1540 D WifiConfigStore: Loading config and enabling all networks 
08-24 14:31:57.832  1036  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-24 14:31:57.832  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:57.832  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:57.832  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:57.832  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:57.832  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 14:31:57.832  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:57.833  1036  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-24 14:31:57.834  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-24 14:31:57.834  1969  1969 D WfdService: Waiting for WifiP2p enabling
08-24 14:31:57.834  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-24 14:31:57.837  8182  8182 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-24 14:31:57.837  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-24 14:31:57.837  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-24 14:31:57.837  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-24 14:31:57.837  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-24 14:31:57.837  1036  8220 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-24 14:31:57.837  1036  8220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-24 14:31:57.838  8200  8219 W FormManager: Network not available. Please check & try again.
08-24 14:31:57.840  1036  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-24 14:31:57.843  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:57.843  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:57.843  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:57.843  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:57.843  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:57.843  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:57.843  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:57.843  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:31:57.843  8200  8221 V FormManager: Network unavailable.
,08-24 14:31:57.846  8200  8221 V FormManager: Network unavailable.
08-24 14:31:57.847  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:57.850  1036  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-24 14:31:57.850  1036  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-24 14:31:57.852  1036  1540 D WifiStateMachine: enableVerboseLogging : level 2
08-24 14:31:57.852  1036  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-24 14:31:57.852  1036  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-24 14:31:57.852  1036  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-24 14:31:57.852  1036  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-24 14:31:57.852  1036  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-24 14:31:57.853  1036  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-24 14:31:57.853  1036  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-24 14:31:57.853  1036  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-24 14:31:57.853  1036  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-24 14:31:57.854  1036  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-24 14:31:57.854  1036  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-24 14:31:57.855  1036  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-24 14:31:57.855  1036  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-24 14:31:57.855  1036  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-24 14:31:57.857  1969  1969 D WfdsService: Supplicant Connection state is changed : true
08-24 14:31:57.857  1969  2299 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-24 14:31:57.857  1969  2299 D WfdsService: Set the WFDS Monitor: true
08-24 14:31:57.857  1969  2299 D WfdsMonitor: WfdsMonitorThread create
08-24 14:31:57.857  1969  2299 D WfdsMonitor: WFDS Monitor is created and started
08-24 14:31:57.857  1969  2299 D WfdsService: WiFi: Supplicant connection re-established
08-24 14:31:57.857  1036  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 14:31:57.857  1036  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-24 14:31:57.858  1036  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-24 14:31:57.858  1036  1540 D WifiNative-HAL: Setting external_sim to 1
08-24 14:31:57.858  1036  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-24 14:31:57.858  1969  8240 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-24 14:31:57.858  1036  1540 D WifiNative-wlan0: SET external_sim 1: returned true
08-24 14:31:57.858  1036  1540 I WifiNative-HAL: startHal
08-24 14:31:57.858  1036  1540 D wifi    : setting scan oui 0xaf724320
,08-24 14:31:57.859  1969  8240 E CtrlSupplicant: Succeed to open control connection
08-24 14:31:57.859  1036  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 14:31:57.859  1036  1540 I WifiNative-HAL: startHal
08-24 14:31:57.859  1036  1540 D wifi    : setting scan oui 0xaf724320
08-24 14:31:57.859  1969  8240 E CtrlSupplicant: Succeed to open monitor connection
08-24 14:31:57.859  1969  8240 D WfdsMonitor: Supplicant connection established
,08-24 14:31:57.859  1036  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
,08-24 14:31:57.859  1969  2299 D WfdsService: Connected to the supplicant for wfds
08-24 14:31:57.859  1036  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-24 14:31:57.860  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-24 14:31:57.860  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-24 14:31:57.860  1036  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-24 14:31:57.860  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 14:31:57.860  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 14:31:57.860  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 14:31:57.860  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-24 14:31:57.861  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-24 14:31:57.861  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-24 14:31:57.861  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 14:31:57.861  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 14:31:57.861  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 14:31:57.861  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,08-24 14:31:57.861  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 14:31:57.861  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 14:31:57.862  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-24 14:31:57.862  8182  8182 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-24 14:31:57.862  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-24 14:31:57.862  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 14:31:57.862  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 14:31:57.862  1036  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 14:31:57.863  1036  1540 E WifiNative: : [149,944,549 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-24 14:31:57.863  1036  1540 D WifiNative-wlan0: doBoolean: RECONNECT
08-24 14:31:57.864  1036  1540 D WifiNative-wlan0: RECONNECT: returned true
08-24 14:31:57.864  1036  1540 D WifiNative-wlan0: doString: [STATUS]
08-24 14:31:57.864  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-24 14:31:57.864  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-24 14:31:57.864  1036  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 14:31:57.864  1036  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 14:31:57.865  7866  7866 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:57.865  1036  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 14:31:57.867  1036  1949 I ActivityManager: Killing 7285:com.android.chrome/u0a57 (adj 15): empty #17
08-24 14:31:57.867  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.869   325   895 D CommandListener: Setting iface cfg
08-24 14:31:57.869   325   895 D CommandListener: Trying to bring up p2p0
08-24 14:31:57.869  1036  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-24 14:31:57.869  1036  1538 D LGWifiP2pService: P2pEnablingState
08-24 14:31:57.869  1036  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.869  1036  1538 D LGWifiP2pService: P2p socket connection successful
08-24 14:31:57.869  1036  1538 D LGWifiP2pService: P2pEnabledState
08-24 14:31:57.893  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:57.893  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:57.893  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:57.893  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:57.893  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:57.893  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:57.893  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:57.893  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:31:57.894  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:57.898  6702  6828 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-24 14:31:57.898  6702  6828 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-24 14:31:57.900  6702  6828 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2d24db9a Bundle[{}]
08-24 14:31:57.901  6702  6828 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 14:31:57.901  6702  6828 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-24 14:31:57.901  6702  6828 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-24 14:31:57.902  6702  6828 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 14:31:57.902  6702  6828 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-24 14:31:57.903  6702  6828 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-24 14:31:57.907  6702  6828 I System.out: Running OutgoingSocketThread
,08-24 14:31:57.908  6702  8242 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 876)
08-24 14:31:57.910  6702  8242 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55011
08-24 14:31:57.910  6702  8242 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-24 14:31:57.918  1036  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-24 14:31:57.920  1036  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,08-24 14:31:57.920  1036  1915 W libprocessgroup: failed to open /acct/uid_10057/pid_7285/cgroup.procs: No such file or directory
08-24 14:31:57.923  1036  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-24 14:31:57.925  1036  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-24 14:31:57.927  1036  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-24 14:31:57.928  1036  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-24 14:31:57.928  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 14:31:57.928  1036  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.928  1036  1557 I WifiNative-HAL: startHal
08-24 14:31:57.928  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-24 14:31:57.928  1036  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.929  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-24 14:31:57.929  1969  1969 D WfdsService: WifiP2pState is changed : true
08-24 14:31:57.929  1969  2299 D WfdsService: Receive the WFDS_ENABLE Method
08-24 14:31:57.929  1969  2299 D WfdsService: Set the WFDS Monitor: true
08-24 14:31:57.930  1969  2299 D WfdsService: Connected to the supplicant for wfds
08-24 14:31:57.930  1969  2299 D WfdsJNI : doCommand: WFDS_SET TRUE
08-24 14:31:57.930  8182  8182 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-24 14:31:57.930  1969  1969 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-24 14:31:57.931  1036  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-24 14:31:57.931  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf724320
08-24 14:31:57.931  1036  1557 D wifi    : failed to get capabilities : -3
08-24 14:31:57.931  1036  1557 E WifiScanningService: could not get scan capabilities
08-24 14:31:57.931  1036  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-24 14:31:57.932  1969  2299 D WfdsService: selectPreferredScanChannel [36]
08-24 14:31:57.932  1969  2299 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,08-24 14:31:57.932  1036  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-24 14:31:57.932  1036  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-24 14:31:57.932  1036  1538 D LGWifiP2pService: before postfix = G3
08-24 14:31:57.932  1036  1538 D WifiServerServiceExt: postfix byte check : 2
08-24 14:31:57.932  1036  1538 D LGWifiP2pService: after postfix = G3
08-24 14:31:57.932  1036  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-24 14:31:57.933  1969  1969 D WfdsService: isConnected: false
08-24 14:31:57.933  1036  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-24 14:31:57.933  1036  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-24 14:31:57.934  1036  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-24 14:31:57.934  1036  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-24 14:31:57.935  1036  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-24 14:31:57.935  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-24 14:31:57.936  1036  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-24 14:31:57.936  1036  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-24 14:31:57.936  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-24 14:31:57.936  1036  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
,08-24 14:31:57.936  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-24 14:31:57.937  1036  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-24 14:31:57.937  1036  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-24 14:31:57.937  8182  8182 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-24 14:31:57.938  1036  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-24 14:31:57.938  1036  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,08-24 14:31:57.938  1036  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-24 14:31:57.938  1036  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-24 14:31:57.938  1969  1969 I WfdStateTracker: handleP2pThisDeviceChanged
08-24 14:31:57.938  1969  1969 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-24 14:31:57.939  1969  1969 D WfdsService: Update P2p Interface State: 3
08-24 14:31:57.939  8182  8182 E wpa_supplicant: disconnect_rssi_lvl: -100
08-24 14:31:57.939  1036  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-24 14:31:57.939  1036  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-24 14:31:57.939  1036  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=150021  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 14:31:57.939  1036  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-24 14:31:57.939  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-24 14:31:57.940  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=150022  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 14:31:57.941  1036  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 14:31:57.941  1036  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 14:31:57.942  1036  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-24 14:31:57.942  1036  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-24 14:31:57.942  1036  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-24 14:31:57.942  1036  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 14:31:57.942  1036  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-24 14:31:57.942  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-24 14:31:57.942  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:57.942  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:57.943  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:57.944  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:57.944  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:57.944  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 14:31:57.951  1036  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-24 14:31:57.951  1036  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-24 14:31:57.951  1036  1538 D LGWifiP2pService: InactiveState
08-24 14:31:57.952  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 14:31:57.952  8222  8222 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:31:57.952  1036  1538 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.952  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.952  8182  8182 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:57.953  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 14:31:57.953  8182  8182 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 14:31:57.953  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:57.,953  1036  8220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:57.953  8182  8182 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.953  1036  8220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:57.953  1036  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-24 14:31:57.953  1036  8220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:57.953  1036  8220 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.953  1036  8220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.953  1036  8220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.953  1036  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-24 14:31:57.953  8182  8182 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.953  1036  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-24 14:31:57.954  1036  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-24 14:31:57.954  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-24 14:31:57.954  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-24 14:31:57.954  8182  8182 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 14:31:57.954  1969  8240 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:57.954  1969  8240 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:57.955  1036  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-24 14:31:57.956  1036  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-24 14:31:57.956  1036  8220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:57.956  1036  8220 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.956  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:57.956  1036  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-24 14:31:57.956  1036  1540 D WifiNative-wlan0: doBoolean: SCAN
08-24 14:31:57.956  1036  8220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.956  1036  8220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.957  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-24 14:31:57.957  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 14:31:57.957  1036  8220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN,
,08-24 14:31:57.957  1036  8220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 14:31:57.957  1036  1540 D WifiNative-wlan0: SCAN: returned false
08-24 14:31:57.957  1036  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=150039  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 14:31:57.958  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=150040  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 14:31:57.959  1036  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 14:31:57.952  1036  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ,
08-24 14:31:57.959  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 14:31:57.960  1036  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 14:31:57.960  8182  8182 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-24 14:31:57.960  8182  8182 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 14:31:57.961  8182  8182 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.961  8182  8182 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.962  1969  8240 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 14:31:57.962  1969  8240 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:57.962  1969  8240 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-24 14:31:57.962  1036  8220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 14:31:57.962  1036  8220 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:57.962  1036  8220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:57.962  1036  8220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 14:31:57.962  1036  8220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:57.962  1036  8220 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.962  1036  8220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.962  1036  8220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.962  1036  8220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 14:31:57.962  1036  8220 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.963  1036  8220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.963  1036  8220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 14:31:57.963  1036  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-24 14:31:57.963  1036  1538 D LGWifiP2pService: InactiveState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.963  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.963  1036  1538 D LGWifiP2pService: DefaultState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.963  1036  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 14:31:57.964  1036  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 14:31:57.964  1036  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 14:31:57.968  1036  1538 D LGWifiP2pService: InactiveState{ when=-17ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.968  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.968  1036  1538 D LGWifiP2pService: DefaultState{ when=-17ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.969  1036  1538 D LGWifiP2pService: InactiveState{ when=-17ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.969  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.969  1036  1538 D LGWifiP2pService: DefaultState{ when=-17ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.969  1036  1538 D LGWifiP2pService: InactiveState{ when=-17ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.969  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.969  1036  1538 D LGWifiP2pService: DefaultState{ when=-18ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.969  1036  1538 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:57.969  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=CZ target=com.android.internal.util.StateMachine,$SmHandler }
08-24 14:31:57.969  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:57.969  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:57.970  1969  2299 W WfdsService: DefaultState - msg [9441285] is not handled
08-24 14:31:57.970  1036  1036 E WifiServerServiceExt: No p2p device connected
08-24 14:31:57.970  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:57.970  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:57.970  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 14:31:57.970  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:57.970  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-24 14:31:57.970  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 14:31:57.977  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 14:31:57.978  1036  2052 I ActivityManager: Killing 7303:com.lge.drmservice/u0a62 (adj 15): empty #17
08-24 14:31:58.007  1036  2039 W libprocessgroup: failed to open /acct/uid_10062/pid_7303/cgroup.procs: No such file or directory
,08-24 14:31:58.020  8222  8222 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 14:31:58.022  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:58.025  8200  8246 W FormManager: Network not available. Please check & try again.
08-24 14:31:58.026  8200  8247 V FormManager: Network unavailable.
08-24 14:31:58.028  8200  8247 V FormManager: Network unavailable.
08-24 14:31:58.028  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:58.042  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-24 14:31:58.044  4787  4787 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-24 14:31:58.047  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:58.049  4787  4787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 14:31:58.054  4787  8248 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-24 14:31:58.056  4787  8249 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 14:31:58.057  4787  8249 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 14:31:58.116  1036  1915 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8250 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-24 14:31:58.237  8250  8250 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 14:31:58.237  8250  8250 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-24 14:31:58.257  8250  8250 V [BNRBootReceiver]: Boot Receiver Return
,08-24 14:31:58.262  8250  8250 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 14:31:58.341  1036  2070 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8275 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 14:31:58.346  1036  2070 I ActivityManager: Killing 7322:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-24 14:31:58.398  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-24 14:31:58.398  8182  8182 E wpa_supplicant: USIM:  scard_init function
08-24 14:31:58.398  1036  8220 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-24 14:31:58.398  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-24 14:31:58.398  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-24 14:31:58.398  1036  8220 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-24 14:31:58.398  8182  8182 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-24 14:31:58.402  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-24 14:31:58.402  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-24 14:31:58.403  1036  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 14:31:58.403  1036  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 14:31:58.404  1036  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 14:31:58.404  1036  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-24 14:31:58.404  1036  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-24 14:31:58.410  1036  1968 W libprocessgroup: failed to open /acct/uid_10085/pid_7322/cgroup.procs: No such file or directory
,08-24 14:31:58.420  1036  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=150501  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 14:31:58.423  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:58.423  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-24 14:31:58.424  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=150506  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-24 14:31:58.427  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.427  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.427  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 14:31:58.428  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.430  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:58.430  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-24 14:31:58.449  8275  8275 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 14:31:58.468  8275  8275 D PluginManager: init()
,08-24 14:31:58.513  1036  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-24 14:31:58.514  8182  8182 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-24 14:31:58.516  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-24 14:31:58.516  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-24 14:31:58.516  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-24 14:31:58.516  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-24 14:31:58.517  1036  1540 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:58.518  1036  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:58.519  1036  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:58.519  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:58.519  1036  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 14:31:58.520  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 14:31:58.520  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 14:31:58.523  1036  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=150601  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 14:31:58.523  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=150604  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 14:31:58.523  1036  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=150605
08-24 14:31:58.524  1036  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=150605
08-24 14:31:58.524  1036  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=150605
08-24 14:31:58.524  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=150606
08-24 14:31:58.524  1036  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=150606
,08-24 14:31:58.529  1036  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=150606  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 14:31:58.531  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.531  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.531  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 14:31:58.532  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:58.532  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:58.534  8182  8182 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 14:31:58.534  8182  8182 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 14:31:58.536  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 14:31:58.536  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 14:31:58.536  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-24 14:31:58.536  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 14:31:58.536  1036  8220 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 14:31:58.536  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-24 14:31:58.536  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 14:31:58.537  1036  8220 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 14:31:58.537  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 14:31:58.537  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 14:31:58.538  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.539  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.539  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-24 14:31:58.542  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=150624  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 14:31:58.543  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:58.543  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-24 14:31:58.544  1036  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=150626  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 14:31:58.544  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=150626  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 14:31:58.545  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.545  1036  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=150626
08-24 14:31:58.545  1036  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=150627
08-24 14:31:58.545  1036  1540 D WifiNative-wlan0: doString: [STATUS]
08-24 14:31:58.546  1036  8220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 14:31:58.546  1036  8220 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 14:31:58.546  1036  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 14:31:58.547  1036  1540 I WifiServiceExtension: setVHTCapabilityType  : false
08-24 14:31:58.548  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:58.548  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:58.549  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.554  1036  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-24 14:31:58.554  1036  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-24 14:31:58.563  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.563  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.563  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 14:31:58.565  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.566  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:58.566  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:58.567  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.567  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 14:31:58.568  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.567  1036  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-24 14:31:58.569  1036  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:31:58.569  1036  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 14:31:58.570  1036  1546 D ConnectivityService: Got NetworkAgent Messenger
08-24 14:31:58.570  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-24 14:31:58.570  1036  1546 D ConnectivityService: NetworkAgent connected
08-24 14:31:58.570  1036  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 14:31:58.570  1036  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 14:31:58.572  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:58.572  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-24 14:31:58.573  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 14:31:58.577  1036  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 14:31:58.577  1036  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:31:58.577  1036  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 14:31:58.577  1036  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 14:31:58.577  1036  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 14:31:58.582  1036  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 14:31:58.583   325   895 D CommandListener: Setting iface cfg
08-24 14:31:58.587  1036  1540 E WifiStateMachine: Start Dhcp Watchdog 3
08-24 14:31:58.587  1036  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=150669  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 14:31:58.587  1036  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=150669  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 14:31:58.588  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=150669  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 14:31:58.588  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:58.588  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-24 14:31:58.590  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:58.590  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-24 14:31:58.590  1036  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=150672  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 14:31:58.591  1036  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=150672  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 14:31:58.591  1036  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=150673  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 14:31:58.592  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14170] from screen [on:0 period:-1131863936] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 14:31:58.592  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1131863936] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 14:31:58.592  1036  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 14:31:58.593  1036  8293 D DhcpStateMachine: StoppedState
08-24 14:31:58.593  1036  8293 D DhcpStateMachine: StoppedState{ when=-6ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:58.593  1036  8293 D DhcpStateMachine: WaitBeforeStartState
08-24 14:31:58.596  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.597  1036  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-24 14:31:58.597  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:58.598  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:58.598  1036  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:58.598  1036  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:58.599  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:58.599  1036  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:58.600  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-24 14:31:58.600  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:58.601  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 14:31:58.602  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=103,0,0
08-24 14:31:58.602  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=103,0,0
08-24 14:31:58.602  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-24 14:31:58.602  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-24 14:31:58.603  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 14:31:58.603  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 14:31:58.603  1036  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-24 14:31:58.603  1036  1540 D WifiNative-wlan0: doBoolean: SET ps 0
08-24 14:31:58.604  1036  1540 D WifiNative-wlan0: SET ps 0: returned true
08-24 14:31:58.604  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-24 14:31:58.604  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-24 14:31:58.604  1036  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-24 14:31:58.605  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@304dc18 target=com.android.internal.uti,l.StateMachine$SmHandler }
08-24 14:31:58.605  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@304dc18 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:58.605  1036  8293 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:58.605  1036  8293 D DhcpStateMachine: DHCP Start wake lock is acquired.
,08-24 14:31:58.606  1036  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-24 14:31:58.606  1036  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 14:31:58.607  1036  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 14:31:58.608   325   895 D CommandListener: Setting iface cfg
08-24 14:31:58.608   325   895 D CommandListener: Trying to bring up wlan0
08-24 14:31:58.609  1036  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-24 14:31:58.610  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:58.610  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:58.610  1036  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:58.611  1036  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-24 14:31:58.611  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:58.611  1036  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 14:31:58.615  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-24 14:31:58.616  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 14:31:58.616  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 14:31:58.616  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 14:31:58.616  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 14:31:58.617  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:58.617  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:58.617  1036  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 14:31:58.617  1036  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-24 14:31:58.617  8182  8182 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-24 14:31:58.618  1036  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-24 14:31:58.618  1036  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 14:31:58.619  1036  1540 D WifiNative-wlan0: SET ps 1: returned true
08-24 14:31:58.619  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-24 14:31:58.620  1036  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 14:31:58.620  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 14:31:58.620  1036  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-24 14:31:58.621  1036  1546 D ConnectivityService: ignoring duplicate network state non-change
08-24 14:31:58.626  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.626  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.626  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 14:31:58.628  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.628  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.628  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-24 14:31:58.630  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:58.630  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:58.630  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.631  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-24 14:31:58.631  1036  1546 D ConnectivityService: Adding iface wlan0 to network 102
08-24 14:31:58.633  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:58.633  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 14:31:58.633  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 14:31:58.634  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.636  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-24 14:31:58.640  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.640  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.640  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-24 14:31:58.643  1036  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-24 14:31:58.645  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 14:31:58.650  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.650  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:58.650  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 14:31:58.655  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:58.655  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 14:31:58.655  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 14:31:58.659  1036  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 14:31:58.659  1036  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-24 14:31:58.660  1036  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-24 14:31:58.660   325   895 E Netd    : netlink response contains error (File exists)
08-24 14:31:58.660  1036  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-24 14:31:58.661  1036  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-24 14:31:58.661  1036  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-24 14:31:58.661  1036  1546 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-24 14:31:58.661  1036  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 14:31:58.661  1036  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 14:31:58.661  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:58.661  1036  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-24 14:31:58.662  1036  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-24 14:31:58.662  1036  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 14:31:58.662  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:58.662  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 14:31:58.662  1036  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:58.662  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:58.662  1036  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-24 14:31:58.662  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-24 14:31:58.662  1036  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-24 14:31:58.662  1036  1546 D ConnectivityService:    accepting network in place of null
08-24 14:31:58.662  1036  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:58.662  1036  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:58.662  1036  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-24 14:31:58.663  1875  1875 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:58.663  1875  1875 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 14:31:58.664  1036  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{,102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-24 14:31:58.664  1036  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-24 14:31:58.664  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 14:31:58.664  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 14:31:58.664  1036  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-24 14:31:58.664  1036  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-24 14:31:58.664  1036  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:58.665  1036  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 14:31:58.666  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 14:31:58.666  1036  1546 D ConnectivityService: validation of new default Network = false
08-24 14:31:58.666  1036  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-24 14:31:58.666  1036  1546 D DSQN    : enableDataServiceNotify 
08-24 14:31:58.666  1036  1546 D DSQN    : start dsqn bin
08-24 14:31:58.666  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-24 14:31:58.667  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 14:31:58.667  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 14:31:58.667  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 14:31:58.667  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.669   325  8308 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-24 14:31:58.669   325  8308 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-24 14:31:58.673  1036  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-24 14:31:58.673  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:58.673  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:58.673  1036  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:58.663  8309  8309 W dsqn    : type=1400 audit(0.0:193): av,c: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:58.663  8309  8309 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:58.673  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 14:31:58.679  1036  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-24 14:31:58.688  8309  8309 E DSQN    : DSQN ssw
08-24 14:31:58.699  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 14:31:58.701  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.702  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.712   325  8308 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-24 14:31:58.739   325   894 D LGDataListener: argv[0]=dsqncommand
08-24 14:31:58.739   325   894 D LGDataListener: argv[1]=wlan0
08-24 14:31:58.739   325   894 D LGDataListener: argv[2]=1
08-24 14:31:58.739   325   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-24 14:31:58.740  1036  1095 D DSQN    : DSQM DsqnNotification wlan0  1
08-24 14:31:58.740  1036  1095 D DSQN    : start to monitor internet connection
08-24 14:31:58.772  1036  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 12:31:58 GMT], X-Android-Received-Millis=[1472041918772], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472041918739]}
08-24 14:31:58.772  1036  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-24 14:31:58.772  1036  8292 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-24 14:31:58.773  1036  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-24 14:31:58.773  1036  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-24 14:31:58.773  1036  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 14:31:58.773  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:58.773  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 14:31:58.773  1036  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-24 14:31:58.773  1036  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-24 14:31:58.774  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:58.774  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:58.774  1036  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:31:58.775  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 14:31:58.775  1036  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:58.775  1036  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:58.775  1036  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 14:31:58.775  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-24 14:31:58.776  1875  1875 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:58.776  1875  1875 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-24 14:31:58.800  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 14:31:58.801  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.802  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 14:31:58.807  1036  8293 D DhcpStateMachine: DHCPV4 request on wlan0
08-24 14:31:58.808  1036  8293 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-24 14:31:58.808  1036  8293 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-24 14:31:58.803  8316  8316 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 14:31:58.803  8316  8316 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 14:31:58.819  8316  8316 I dhcpcd  : version 5.5.6 starting
08-24 14:31:58.821  8316  8316 E dhcpcd  : get_duid: m
08-24 14:31:58.821  8316  8316 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-24 14:31:58.821  8316  8316 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-24 14:31:58.890  8316  8316 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-24 14:31:58.890  8316  8316 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 14:31:58.890  8316  8316 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 14:31:58.890  8316  8316 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-24 14:31:58.890  8316  8316 D dhcpcd  : wlan0: sending REQUEST (xid 0x8dabc6fa), next in 4.81 seconds
,08-24 14:31:58.902  8275  8275 W ExternalStrings: load override strings
08-24 14:31:58.902  8275  8275 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 14:31:58.902  8275  8275 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-24 14:31:58.903  8275  8275 D StatusProvider: onCreate
08-24 14:31:58.910  6702  6828 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 877)
08-24 14:31:58.910  6702  6828 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 877)
,08-24 14:31:58.919  8316  8316 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-24 14:31:58.921  6702  6828 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 882)
08-24 14:31:58.924  6702  6828 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-24 14:31:58.924  6702  6828 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 883),
,08-24 14:31:58.929  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 14:31:58.929  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18bf6331 added. We now have 2 listener(s)
08-24 14:31:58.929  1036  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:58.932  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-24 14:31:58.932  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:58.932  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:58.932  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:31:58.932  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c5a16 added. We now have 9 listener(s)
08-24 14:31:58.932  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:58.932  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:31:58.935  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:58.938  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:58.938  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:58.938  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:58.938  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:58.938  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:58.938  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-24 14:31:58.938  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:58.938  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:58.938  8275  8275 V Signer  : override build config not found
08-24 14:31:58.939  8275  8275 D Signer  : value of property debug is false
,08-24 14:31:58.942  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:58.942  6702  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:58.942  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 14:31:58.943  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@221a4584 added. We now have 3 listener(s)
08-24 14:31:58.943  1036  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 14:31:58.944  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:58.946  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:58.947  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 14:31:58.948  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:58.948  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:58.948  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:58.948  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e76016d added. We now have 10 listener(s)
08-24 14:31:58.948  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:58.948  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:58.948  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:58.948  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:58.949  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:58.949  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:58.949  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:58.949  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:58.949  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18bf6331 removed from the list
08-24 14:31:58.949  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:58.949  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c5a16 removed from the list
08-24 14:31:58.950  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:58.950  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:58.950  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:31:58.950  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:58.952  8316  8316 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-24 14:31:58.952  8316  8316 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-24 14:31:58.953  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:31:58.953  8316  8316 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-24 14:31:58.953  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:58.953  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:31:58.953  8316  8316 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-24 14:31:58.953  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c5a16 not in the list
08-24 14:31:58.953  8316  8316 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-24 14:31:58.953  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:58.953  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:58.953  8316  8316 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-24 14:31:58.953  8316  8316 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 14:31:58.953  8316  8316 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-24 14:31:58.955  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:58.955  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:31:58.955  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:58.955  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e76016d removed from the list
08-24 14:31:58.955  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:58.955  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:58.955  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:58.955  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:58.955  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@221a4584 removed from the list
08-24 14:31:58.956  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:58.956  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc01a2 added. We now have 2 listener(s)
,08-24 14:31:58.958  1036  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 14:31:58.961  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 14:31:58.961  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-24 14:31:58.961  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:58.961  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:58.961  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@183e33 added. We now have 9 listener(s)
08-24 14:31:58.961  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:58.962  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:31:58.966  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:58.971  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:58.971  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:58.971  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:58.971  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-24 14:31:58.971  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:58.971  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:58.971  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:58.971  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:31:58.973  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:58.973  6702  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:58.973  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:58.974  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357e4769 added. We now have 3 listener(s)
08-24 14:31:58.974  1036  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:58.976  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:58.978  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 14:31:58.978  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:58.979  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:58.979  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:58.979  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:58.979  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24bc95ee added. We now have 10 listener(s)
08-24 14:31:58.979  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:58.979  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:58.979  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:31:58.979  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:58.979  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:58.979  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:31:58.980  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-24 14:31:58.982  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 14:31:58.982  1036  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:58.982  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-24 14:31:58.983  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-24 14:31:58.983  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-24 14:31:58.983  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-24 14:31:58.983  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-24 14:31:58.983  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-24 14:31:58.983  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-24 14:31:58.984  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-24 14:31:58.984  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-24 14:31:58.984  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-24 14:31:58.984  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-24 14:31:58.984  8275  8275 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-24 14:31:58.986  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:31:58.987  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 14:31:58.990  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:31:58.990  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:58.992  6702  6828 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 14:31:58.992  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:58.992  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:58.993  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:58.993  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:58.993  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:58.993  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:58.993  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:58.993  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:58.993  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:58.993  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc01a2 removed from the list
08-24 14:31:58.993  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:58.994  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@183e33 removed from the list
08-24 14:31:58.994  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:58.994  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:58.994  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:58.994  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:58.995  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:58.995  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:58.995  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:58.995  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@183e33 not in the list
08-24 14:31:58.995  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:58.995  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:58.996  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:58.996,  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:58.996  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:58.996  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:58.996  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:58.996  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24bc95ee removed from the list
08-24 14:31:58.996  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:58.996  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:58.996  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:58.996  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:58.996  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357e4769 removed from the list
08-24 14:31:58.997  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:58.997  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13aaf125 added. We now have 2 listener(s)
08-24 14:31:58.997  1036  1596 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:58.998  8275  8275 V LGMDMManager: Create singleton instance
08-24 14:31:58.999  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 14:31:58.999  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:59.000  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:59.000  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:59.000  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ce022fa added. We now have 9 listener(s)
08-24 14:31:59.000  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:59.000  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:31:59.002  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:59.008  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:59.008  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:59.008  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:59.008  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:59.008  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:59.008  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:59.008  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:59.008  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:59.009  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:59.010  6702  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:59.011  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:59.011  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1708d308 added. We now have 3 listener(s)
08-24 14:31:59.011  1036  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:59.012  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:59.014  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:59.015  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 14:31:59.015  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:59.015  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:59.015  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:59.015  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f3e7aa1 added. We now have 10 listener(s)
08-24 14:31:59.015  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:59.015  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:59.015  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:59.015  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:31:59.015  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:59.015  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:59.015  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:31:59.017  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 14:31:59.018  1036  1912 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:59.020  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 14:31:59.021  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 14:31:59.022  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:31:59.023  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:59.024  6702  6828 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 14:31:59.024  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:59.024  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:59.024  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:59.024  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:59.024  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.024  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:59.024  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:59.024  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13aaf125 removed from the list
08-24 14:31:59.024  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:59.024  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ce022fa removed from the list
08-24 14:31:59.024  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:59.024  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.025  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.025  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.025  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:59.025  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:59.025  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:59.025  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ce022fa not in the list
08-24 14:31:59.025  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.025  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.026  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:59.026  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:59.026  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:59.026  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:59.026  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:59.027  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f3e7aa1 removed from the list
08-24 14:31:59.027  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:59.027  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.027  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.027  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:59.027  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1708d308 removed from the list
08-24 14:31:59.028  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:59.028  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20dc17b4 added. We now have 2 listener(s)
08-24 14:31:59.028  1036  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:59.031  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 14:31:59.031  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:59.031  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:59.031  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:59.031  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16271fdd added. We now have 9 listener(s)
08-24 14:31:59.031  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:59.032  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:31:59.033  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:59.038  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:59.038  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:59.038  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:59.038  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:59.038  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:59.038  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:59.038  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:59.038  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:59.039  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:59.039  6702  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:59.041  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:59.041  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ed1a23 added. We now have 3 listener(s)
08-24 14:31:59.042  1036  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:59.042  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:59.044  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 14:31:59.044  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:59.044  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:59.044  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:59.044  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1afcfb20 added. We now have 10 listener(s)
08-24 14:31:59.044  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:59.044  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:59.044  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:31:59.044  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:59.044  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:59.044  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:31:59.046  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:59.047  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 14:31:59.047  1036  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:59.051  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 14:31:59.051  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 14:31:59.056  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:31:59.056  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:59.060  6702  6828 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 14:31:59.061  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:59.062  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:59.062  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:59.062  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:59.062  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.062  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:59.062  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:59.062  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20dc17b4 removed from the list
08-24 14:31:59.062  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:59.062  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16271fdd removed from the list
08-24 14:31:59.062  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:59.062  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.062  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.062  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.063  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:59.063  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:59.063  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:59.063  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16271fdd not in the list
08-24 14:31:59.063  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.063  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.065  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:59.066  6702  6828 D BluetoothLeScanner: could not find callback wrapper
08-24 14:31:59.066  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:59.066  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:59.066  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:59.066  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1afcfb20 removed from the list
08-24 14:31:59.066  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:59.066  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.066  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.066  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:59.066  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ed1a23 removed from the list
08-24 14:31:59.067  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:59.067  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22ed357f added. We now have 2 listener(s)
08-24 14:31:59.067  1036  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:59.067  8275  8275 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-24 14:31:59.070  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 14:31:59.070  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:59.070  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:59.070  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:59.070  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@486a94c added. We now have 9 listener(s)
08-24 14:31:59.070  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:59.070  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:31:59.072  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:59.076  6702  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:59.076  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:59.076  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:31:59.076  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:59.076  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:59.076  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:59.076  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:59.076  6702  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:59.077  6702  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:59.078  6702  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:59.078  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:59.078  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b073eaa added. We now have 3 listener(s)
08-24 14:31:59.078  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:31:59.079  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:59.081  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:59.082  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 14:31:59.083  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:59.083  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:59.083  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:59.083  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a9aa9b added. We now have 10 listener(s)
08-24 14:31:59.083  6702  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:59.083  6702  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:59.083  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:59.083  6702  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:59.084  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:59.084  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.084  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:59.084  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:59.084  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22ed357f removed from the list
08-24 14:31:59.084  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:59.084  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@486a94c removed from the list
08-24 14:31:59.084  6702  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:59.084  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.084  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.084  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.085  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:59.085  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:59.085  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:59.085  6702  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@486a94c not in the list
08-24 14:31:59.085  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.085  6702  6828 D org.thaliproject.p2p.btconnect,orlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.086  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:59.086  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:59.086  6702  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:59.086  6702  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a9aa9b removed from the list
08-24 14:31:59.086  6702  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:59.086  6702  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:59.087  6702  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:59.087  6702  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:59.087  6702  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b073eaa removed from the list
08-24 14:31:59.088  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-24 14:31:59.088  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 14:31:59.088  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 14:31:59.088  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:59.088  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-24 14:31:59.089  6702  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:59.099  6702  8342 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 890, name: My test thread name)
08-24 14:31:59.099  6702  8342 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 890, thread name: My test thread name)
08-24 14:31:59.099  6702  8342 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 890, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-24 14:31:59.102  6702  8343 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 892, name: My test thread name)
08-24 14:31:59.103  6702  8343 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 892, thread name: My test thread name)
,08-24 14:31:59.103  6702  8343 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 892, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-24 14:31:59.106  6702  6828 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-24 14:31:59.106  6702  6828 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-24 14:31:59.106  6702  6828 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-24 14:31:59.106  6702  6828 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-24 14:31:59.106  6702  6828 D com.test.thalitest.ThaliTestRunner: Total duration: 23291 ms
08-24 14:31:59.108  6702  6828 I jxcore-log: Total number of executed tests:  80
08-24 14:31:59.108  6702  6828 I jxcore-log: 
08-24 14:31:59.108  6702  6828 I jxcore-log: Number of passed tests:  80
08-24 14:31:59.108  6702  6828 I jxcore-log: 
08-24 14:31:59.108  6702  6828 I jxcore-log: Number of failed tests:  0
08-24 14:31:59.108  6702  6828 I jxcore-log: 
08-24 14:31:59.108  6702  6828 I jxcore-log: Number of ignored tests:  0
08-24 14:31:59.108  6702  6828 I jxcore-log: 
08-24 14:31:59.108  6702  6828 I jxcore-log: Total duration:  23291
08-24 14:31:59.108  6702  6828 I jxcore-log: 
08-24 14:31:59.108  6702  6828 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 14:31:59.108  6702  6828 I jxcore-log: 
08-24 14:31:59.111  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.111  6702  6828 I jxcore-log: 
08-24 14:31:59.114  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.114  6702  6828 I jxcore-log: 
,08-24 14:31:59.115  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.115  6702  6828 I jxcore-log: 
08-24 14:31:59.116  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.116  6702  6828 I jxcore-log: 
08-24 14:31:59.118  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.118  6702  6828 I jxcore-log: 
08-24 14:31:59.120  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.120  6702  6828 I jxcore-log: 
08-24 14:31:59.123  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.123  6702  6828 I jxcore-log: 
08-24 14:31:59.123  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:59.126  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.126  6702  6828 I jxcore-log: 
08-24 14:31:59.127  6702  6702 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 14:31:59.127  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:31:59.127  6702  6828 I jxcore-log: 
08-24 14:31:59.128  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:31:59.128  6702  6828 I jxcore-log: 
,08-24 14:31:59.129  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:59.129  6702  6828 I jxcore-log: 
08-24 14:31:59.130  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:59.130  6702  6828 I jxcore-log: 
08-24 14:31:59.131  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 14:31:59.131  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:31:59.131  6702  6828 I jxcore-log: 
08-24 14:31:59.133  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:31:59.133  6702  6828 I jxcore-log: 
08-24 14:31:59.133  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:31:59.133  6702  6828 I jxcore-log: 
08-24 14:31:59.134  8275  8347 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 14:31:59.134  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:31:59.135  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:59.135  6702  6828 I jxcore-log: 
08-24 14:31:59.136  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:59.136  6702  6828 I jxcore-log: 
08-24 14:31:59.136  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:31:59.136  6702  6828 I jxcore-log: 
08-24 14:31:59.137  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:31:59.137  6702  6828 I jxcore-log: 
08-24 14:31:59.138  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:59.138  6702  6828 I jxcore-log: 
08-24 14:31:59.138  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:59.138  6702  6828 I jxcore-log: 
08-24 14:31:59.140  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:31:59.140  6702  6828 I jxcore-log: 
,08-24 14:31:59.140  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:31:59.140  6702  6828 I jxcore-log: 
08-24 14:31:59.141  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:31:59.141  6702  6828 I jxcore-log: 
08-24 14:31:59.142  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:31:59.142  6702  6828 I jxcore-log: 
08-24 14:31:59.142  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.142  6702  6828 I jxcore-log: 
08-24 14:31:59.143  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.143  6702  6828 I jxcore-log: 
08-24 14:31:59.143  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.143  6702  6828 I jxcore-log: 
08-24 14:31:59.143  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.143  6702  6828 I jxcore-log: 
08-24 14:31:59.144  6702  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:59.144  6702  6828 I jxcore-log: 
08-24 14:31:59.172  1036  2070 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8350 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-24 14:31:59.173  1036  2070 I ActivityManager: Killing 7350:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-24 14:31:59.211  1036  8293 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-24 14:31:59.212  1036  8293 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-24 14:31:59.212  1036  8293 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 14:31:59.212  1036  8293 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-24 14:31:59.212  1036  8293 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-24 14:31:59.213  1036  8293 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 14:31:59.213  1036  8293 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-24 14:31:59.213  1036  8293 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-24 14:31:59.213  1036  8293 D DhcpStateMachine: RunningState
,08-24 14:31:59.266  8275  8346 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-24 14:31:59.361  8367  8367 D AndroidRuntime: 
08-24 14:31:59.361  8367  8367 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-24 14:31:59.363  8367  8367 D AndroidRuntime: CheckJNI is OFF
08-24 14:31:59.380  1036  2070 E libprocessgroup: failed to kill 1 processes for processgroup 7350
,08-24 14:31:59.410  8350  8350 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 14:31:59.446  8350  8350 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-24 14:31:59.497  8350  8350 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-24 14:31:59.497  8350  8350 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-24 14:31:59.498  8350  8350 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-24 14:31:59.498  8350  8350 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-24 14:31:59.498  8350  8350 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-24 14:31:59.500  8350  8350 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-24 14:31:59.505  8350  8350 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-24 14:31:59.508  8367  8367 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-24 14:31:59.514  8350  8350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 14:31:59.516  1036  1093 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-24 14:31:59.517  8350  8350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:31:59.517  1036  1093 I ActivityManager: Killing 6702:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-24 14:31:59.531  8275  8346 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 14:31:59.532  8275  8346 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:31:59.582  1036  2003 I WindowState: WIN DEATH: Window{1e7fb71f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 14:31:59.583  1036  1545 D WifiService: Client connection lost with reason: 4
,08-24 14:31:59.589  1036  2003 D InputDispatcher: Window went away: Window{1e7fb71f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 14:31:59.662  8275  8346 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-24 14:31:59.734  1036  1093 I ActivityManager:   Force finishing activity ActivityRecord{94696f8 u0 com.test.thalitest/.MainActivity t6}
,08-24 14:31:59.781   357   373 E GBMv2   : DFP En is all cleared set to be enabled
,08-24 14:31:59.788  1036  1118 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-24 14:31:59.789  8350  8350 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 14:31:59.795  1036  1118 I ActivityManager:   Force finishing activity ActivityRecord{94696f8 u0 com.test.thalitest/.MainActivity t6 f}
08-24 14:31:59.796  1036  1118 W ActivityManager: Duplicate finish request for ActivityRecord{94696f8 u0 com.test.thalitest/.MainActivity t6 f}
,08-24 14:31:59.796  8350  8350 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-24 14:31:59.805  8350  8350 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-24 14:31:59.833  1036  1596 W ActivityManager: Spurious death for ProcessRecord{214f5224 6702:com.test.thalitest/u0a118}, curProc for 6702: null
,08-24 14:31:59.838  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-24 14:31:59.856  1036  1450 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 14:31:59.862  2022  2022 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-24 14:31:59.865  2504  2632 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 14:31:59.866  7837  7837 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-24 14:31:59.866  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-24 14:31:59.867  3776  3776 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-24 14:31:59.869  4966  4966 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-24 14:31:59.869  4966  4966 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-24 14:31:59.869  4966  4966 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-24 14:31:59.869  4966  4966 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-24 14:31:59.869  4966  4966 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:31:59.869  4966  4966 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:31:59.869  4966  4966 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:31:59.869  4966  4966 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 14:31:59.869  4966  4966 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:59.870  4966  4966 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:59.870  4966  4966 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 14:31:59.870  4966  4966 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 14:31:59.870  2078  2078 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-24 14:31:59.872  2078  2078 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-24 14:31:59.874  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-24 14:31:59.875  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:31:59.875  2078  2178 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-24 14:31:59.876  8275  8347 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 14:31:59.894  5082  5082 I art     : Explicit concurrent mark sweep GC freed 8208(470KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 508us total 85.580ms
,08-24 14:31:59.899  1036  1092 W InputMethodInfo: Duplicated subtype definition found: , voice
08-24 14:31:59.911  1036  2003 V SIM_STK : Menu title from STK is T-Mobile
08-24 14:31:59.930  1036  1036 D administrator: Handling package changes for user 0
,08-24 14:31:59.934  8275  8346 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-24 14:31:59.938  1969  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-24 14:31:59.938  1969  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1c352447 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-24 14:31:59.940  1969  2579 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-24 14:31:59.940  1969  2579 D SplitWindowPolicy: topRunningActivity=ActivityInfo{9984474 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-24 14:31:59.951  1931  1931 D ActionManagerService: notifyUserLog: 1000003
,08-24 14:31:59.952  2078  2078 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-24 14:31:59.952  3776  4992 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-24 14:31:59.956  8275  8346 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-24 14:31:59.957  1605  1659 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 14:31:59.957  1605  1659 D KeyguardModel: createShortcutInfo...
08-24 14:31:59.958  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-24 14:31:59.959  2078  2078 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-24 14:31:59.961  2078  2078 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-24 14:31:59.963  2078  2078 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-24 14:31:59.965  1605  1659 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 14:31:59.965  1605  1659 D KeyguardModel: createShortcutInfo...
08-24 14:31:59.969  8275  8346 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-24 14:31:59.973  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 14:31:59.974  1605  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:31:59.974  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-24 14:31:59.976  1931  1931 D ActionManagerService: notifyUserLog: 1000004
08-24 14:31:59.976  2078  2078 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-24 14:31:59.976  3776  4992 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-24 14:31:59.979  3776  3792 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , create_time: 1430832262123
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , expire_time: 0
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , display: false
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , animation: false }
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , create_time: 1430832262287
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , expire_time: 0
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , display: false
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , animation: false }
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , create_time: 1471602816196
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , expire_time: 0
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , display: false
08-24 14:31:59.986  2078  2078 I GBoardWebViewUtils: , animation: false }
08-24 14:31:59.994  1895  1895 D SplitUIManager: split_name #11 / not available #0
08-24 14:31:59.994  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 14:31:59.994  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-24 14:31:59.994  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-24 14:31:59.994  1895  1895 D SplitUIService: removed split : 
08-24 14:31:59.994  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 14:31:59.996  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:31:59.997  1605  1659 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-24 14:32:00.002  1036  1388 D PowerManagerServiceEx: acquireWakeLockInternal: lock=403707383, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
08-24 14:32:00.004  1036  1968 V SIM_STK : Menu title from STK is T-Mobile
08-24 14:32:00.004  1036  1968 V SIM_STK : Menu title from STK is T-Mobile
08-24 14:32:00.007  8275  8346 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-24 14:32:00.007  8275  8346 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-24 14:32:00.008  8275  8346 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-24 14:32:00.014  8275  8346 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-24 14:32:00.017  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:32:00.036  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 14:32:00.036  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 14:32:00.036  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 14:32:00.036  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 14:32:00.039  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 14:32:00.039  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 14:32:00.040  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 14:32:00.040  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 14:32:00.041  2078  8393 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-24 14:32:00.042  8275  8346 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-24 14:32:00.042  1605  1659 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 14:32:00.042  1605  1659 D KeyguardModel: createShortcutInfo...
08-24 14:32:00.054  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
,08-24 14:32:00.056  1036  2070 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-24 14:32:00.056  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-24 14:32:00.056  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 14:32:00.056  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 14:32:00.057  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 14:32:00.057  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 14:32:00.057  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 14:32:00.057  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 14:32:00.057  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 14:32:00.057  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 14:32:00.057  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 14:32:00.057  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 14:32:00.057  7837  7837 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 14:32:00.057  2078  2078 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-24 14:32:00.057  8350  8350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:32:00.058  8350  8350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 14:32:00.079  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 14:32:00.080  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 14:32:00.081  8350  8350 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 14:32:00.084  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-24 14:32:00.085  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:32:00.085  1605  1659 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-24 14:32:00.088  7003  7003 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-24 14:32:00.091  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:32:00.092  8275  8347 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 14:32:00.095  1605  1659 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 14:32:00.095  1605  1659 D KeyguardModel: createShortcutInfo...
08-24 14:32:00.099  1605  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:32:00.099  1605  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 14:32:00.099  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-24 14:32:00.099  1895  1895 D SplitUIManager: split_name #11 / not available #0
08-24 14:32:00.099  1605  1659 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 14:32:00.099  1895  1895 I SplitUIService: split app #11
08-24 14:32:00.103  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-24 14:32:00.103  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 14:32:00.103  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 14:32:00.105  1036  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-24 14:32:00.107  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:32:00.108  1605  1659 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 14:32:00.109  1605  1659 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 14:32:00.109  1605  1659 D KeyguardModel: createShortcutInfo...
08-24 14:32:00.119  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:32:00.121  2078  2078 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-24 14:32:00.123  1605  1659 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 14:32:00.123  1605  1659 D KeyguardModel: createShortcutInfo...
08-24 14:32:00.125  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:32:00.128  1605  1659 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 14:32:00.128  1605  1659 D KeyguardModel: createShortcutInfo...
08-24 14:32:00.130  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:32:00.130  1605  1659 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 14:32:00.131  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-24 14:32:00.131  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-24 14:32:00.136  1605  1659 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 14:32:00.136  1605  1659 D KeyguardModel: createShortcutInfo...
08-24 14:32:00.138  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 14:32:00.138  1605  1659 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-24 14:32:00.139  1605  1659 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 14:32:00.139  1605  1659 D KeyguardModel: createShortcutInfo...
08-24 14:32:00.140  1605  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:32:00.140  1605  1659 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 14:32:00.142  1605  1659 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 14:32:00.142  1605  1659 D KeyguardModel: createShortcutInfo...
08-24 14:32:00.146  8350  8350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:32:00.146  8350  8350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:32:00.147  8350  8350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:32:00.149  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 14:32:00.149  7003  7003 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 14:32:00.149  7003  7003 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 14:32:00.149  7003  7003 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 14:32:00.151  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 14:32:00.151  7003  7003 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 14:32:00.151  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-24 14:32:00.151  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 14:32:00.151  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 14:32:00.151  7003  7003 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 14:32:00.151  7003  7003 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-24 14:32:00.151  7003  7003 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 14:32:00.155  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:32:00.157  8275  8347 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-24 14:32:00.161  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 14:32:00.165  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:32:00.166  1036  1540 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 14:32:00.166  1036  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 14:32:00.166  1036  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 14:32:00.166  1036  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 14:32:00.167  1036  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 14:32:00.167  1036  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 14:32:00.167  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-24 14:32:00.167  1036  1546 D ConnectivityService: identical MTU - not setting
08-24 14:32:00.167  1036  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 14:32:00.167  1036  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 14:32:00.167  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:32:00.167  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:32:00.168  1036  1546 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 14:32:00.168  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-24 14:32:00.174  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-24 14:32:00.174  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-24 14:32:00.191  8350  8350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:32:00.203  8350  8350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 14:32:00.203  8350  8350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:32:00.205  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:32:00.206  8275  8347 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 14:32:00.210  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:32:00.218  1036  1118 I art     : Explicit concurrent mark sweep GC freed 83483(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.861ms total 207.796ms
08-24 14:32:00.222  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-24 14:32:00.223  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:32:00.225  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:32:00.227  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-24 14:32:00.228  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,08-24 14:32:00.229  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-24 14:32:00.230  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-24 14:32:00.233  8350  8350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:32:00.233  8350  8350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:32:00.234  8350  8350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:32:00.235  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:32:00.236  8275  8347 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 14:32:00.246  2078  2078 E [Concierge]WebView: View is detached but the BroadcastReceiver got Time-tick!!!
,08-24 14:32:00.247  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-24 14:32:00.247  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:32:00.247  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 14:32:00.248  2078  2267 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-24 14:32:00.248  2078  2267 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-24 14:32:00.255  1036  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5651596 u0 com.lge.launcher2/.Launcher t5} time:152349
,08-24 14:32:00.265  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:32:00.268  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-24 14:32:00.269  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 14:32:00.269  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:32:00.270  8350  8350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:32:00.270  8350  8350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:32:00.271  8350  8350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:32:00.272  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:32:00.276  2078  2078 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-24 14:32:00.277  2617  2617 D [Concierge]Service: onStartCommand(). Type : 8
08-24 14:32:00.277  2617  2617 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-24 14:32:00.278  2617  2617 D [Concierge]Service: Update widget ID : 11
08-24 14:32:00.280  2078  2078 D [Concierge]WidgetView: change position of spinner
08-24 14:32:00.280  2078  2078 I [Concierge]WidgetView: initWebView(). Time : 1472041920280
08-24 14:32:00.281  2617  2617 D [Concierge]Service: onStartCommand(). Type : 0
08-24 14:32:00.295  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 14:32:00.299  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:32:00.302  8350  8350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:32:00.302  8350  8350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:32:00.303  8350  8350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:32:00.303  8367  8367 D AndroidRuntime: Shutting down VM
08-24 14:32:00.306  2078  2078 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 993991871
,08-24 14:32:00.307  2078  2078 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-24 14:32:00.307  2078  2078 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-24 14:32:00.309  2078  2078 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3181e6e0
08-24 14:32:00.310  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-24 14:32:00.310  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:32:00.311  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 14:32:00.311  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:32:00.316  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-24 14:32:00.317  2078  2078 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-24 14:32:00.317  2078  2078 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-24 14:32:00.345  1036  1118 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8403 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-24 14:32:00.353  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:32:00.357  2078  2078 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472041796421, New one : 1472041920280
08-24 14:32:00.357  2078  2078 D [Concierge]WidgetView: Unregister all receivers
08-24 14:32:00.357  2078  2078 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-24 14:32:00.358  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:32:00.359  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-24 14:32:00.360  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-24 14:32:00.361  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-24 14:32:00.362  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-24 14:32:00.363  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 14:32:00.363  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-24 14:32:00.365  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-24 14:32:00.368  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:32:00.370  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:32:00.370  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:32:00.372   361   361 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 456us total 27.360ms
,08-24 14:32:00.375  8350  8350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:32:00.376  8350  8350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:32:00.380  8350  8350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 14:32:00.385  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:32:00.392   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 403us total 18.665ms
08-24 14:32:00.410   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 16.123ms
,08-24 14:32:00.414  2078  2078 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-24 14:32:00.415  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 14:32:00.419  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:32:00.424  2078  2078 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-24 14:32:00.424  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-24 14:32:00.425  8350  8350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:32:00.425  8350  8350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:32:00.426  8350  8350 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 14:32:00.426  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-24 14:32:00.428  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:32:00.431  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:32:00.436  8222  8222 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-24 14:32:00.439  8222  8222 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 14:32:00.441  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 14:32:00.445  2078  2078 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@14af6168 time:152539
08-24 14:32:00.447  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:32:00.450  1036  1052 I ActivityManager: Killing 7380:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-24 14:32:00.589  1036  1949 W libprocessgroup: failed to open /acct/uid_10005/pid_7380/cgroup.procs: No such file or directory
08-24 14:32:00.590  8350  8350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 14:32:00.591  8350  8350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 14:32:00.595  8350  8350 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 14:32:00.597  8350  8350 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 14:32:00.598  8350  8350 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 14:32:00.606  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 14:32:00.614  8222  8222 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-24 14:32:00.614  8222  8222 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-24 14:32:00.619  2078  2078 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-24 14:32:00.621  7003  7003 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 14:32:00.628  7003  7003 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 14:32:00.637  8350  8350 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 14:32:00.638  8350  8350 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 14:32:00.640  8350  8350 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.,
08-24 14:32:00.641  8350  8350 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 14:32:00.642  8350  8350 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 14:32:00.646  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 14:32:00.653  8350  8350 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-24 14:32:00.654  8350  8350 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-24 14:32:00.655  8350  8350 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-24 14:32:00.683  8350  8350 D LgDataFeature: LgDataFeature() Constructor: none
08-24 14:32:00.683  8350  8350 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:32:00.686  2078  2906 I GBoardtInterface: onReloaded()
08-24 14:32:00.689  8350  8350 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-24 14:32:00.690  8350  8350 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-24 14:32:00.690  8350  8350 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-24 14:32:00.690  8350  8350 V SoundPool: doLoad: loading sample sampleID=1
08-24 14:32:00.691  8350  8350 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-24 14:32:00.693  7753  7753 D UEI.SmartControl: QS Service created
08-24 14:32:00.693  8350  8350 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-24 14:32:00.694  8350  8425 V SoundPool: Start decode
08-24 14:32:00.694  8350  8425 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-24 14:32:00.694   329  1386 V MediaPlayerService: decode(22, 10857164, 17813)
08-24 14:32:00.695   329  1386 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-24 14:32:00.695   329  1386 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-24 14:32:00.695   329  1386 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-24 14:32:00.695   329  1386 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-24 14:32:00.695   329  1386 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-24 14:32:00.695   329  1386 V MediaPlayerService: player type = 3
08-24 14:32:00.695   329  1386 V AwesomePlayer: AwesomePlayer create()
08-24 14:32:00.695   329  1386 V AwesomePlayer: reset_l() 
08-24 14:32:00.695   329  1386 V AwesomePlayer: cancelPlayerEvents
08-24 14:32:00.695   329  1386 V AwesomePlayer: setAudioSink() 
08-24 14:32:00.695   329  1386 V AwesomePlayer: reset_l() 
08-24 14:32:00.695   329  1386 V AudioCache: notify(0xb5474c00, 8, 0, 0)
08-24 14:32:00.695   329  1386 V AudioCache: ignored
08-24 14:32:00.695   329  1386 V AwesomePlayer: cancelPlayerEvents
08-24 14:32:00.695   329  1386 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
,08-24 14:32:00.695  8350  8350 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 14:32:00.695   329  1386 V AwesomePlayer: setDataSource_l dataSource
08-24 14:32:00.695   329  1386 V LGParserOSAL: SniffLGParser start
08-24 14:32:00.695   329  1386 V LGParserOSAL: MainType:5, SubType=0
08-24 14:32:00.695   329  1386 V LGParserOSAL: #### check Mime : application/ogg
08-24 14:32:00.695   329  1386 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-24 14:32:00.695   329  1386 E MediaExtractor: Use LGExtractor :application/ogg 
08-24 14:32:00.696  8350  8350 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-24 14:32:00.697  2078  2078 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-24 14:32:00.699  3776  3792 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 14:32:00.704  8350  8350 V LGMDMManager: Create singleton instance
08-24 14:32:00.719  7753  7753 I UEI.SmartControl: Service initServices...
,08-24 14:32:00.726   329  1386 V LGParserOSAL: supported mime: application/ogg
08-24 14:32:00.726   329  1386 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-24 14:32:00.726   329  1386 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-24 14:32:00.726   329  1386 V AwesomePlayer: mBitrate = -1 bits/sec
08-24 14:32:00.726   329  1386 V AwesomePlayer: AudioTrack Setting
08-24 14:32:00.726   329  1386 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-24 14:32:00.726   329  1386 V AwesomePlayer: setAudioSource() 
08-24 14:32:00.726   329  1386 V MediaPlayerService: prepare
08-24 14:32:00.726   329  1386 V AwesomePlayer: prepareAsync_l() 
,08-24 14:32:00.726   329  1386 V MediaPlayerService: wait for prepare
08-24 14:32:00.726   329  8426 V AwesomePlayer: onPrepareAsyncEvent() 
08-24 14:32:00.726   329  8426 V AwesomePlayer: initAudioDecoder() 
08-24 14:32:00.726   329  8426 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 14:32:00.726   329  8426 V AudioSystem: isOffloadSupported()
08-24 14:32:00.726   329  8426 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 14:32:00.726   329  8426 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 14:32:00.726   329  8426 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 14:32:00.726   329  8426 V AwesomePlayer: getUseOffload() = 0 
08-24 14:32:00.726   329  8426 V OMXCodec: OMXCodec::Create
08-24 14:32:00.726   329  8426 V OMXCodec: findMatchingCodecs()
08-24 14:32:00.726   329  8426 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-24 14:32:00.726   329  8426 V OMXCodec: matchingCodecs.size()=1
08-24 14:32:00.726   329  8426 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-24 14:32:00.728   329  8426 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-24 14:32:00.728   329  8426 V LGCodecAdapter: LG Codec Adapter start
08-24 14:32:00.728   329  8426 V OMXCodec: OMXCodec Createtor
08-24 14:32:00.728   329  8426 V OMXCodec: setComponentRole
08-24 14:32:00.728   329  8426 V OMXCodec: configureCodec protected=0
08-24 14:32:00.728   329  8426 V LGCodecAdapter: called getLGCodecSpecificData
08-24 14:32:00.728   329  8426 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-24 14:32:00.728   329  8426 V LGCodecOSAL: Called LGconfigureCodecMETA
08-24 14:32:00.728   329  8426 V LGCodecOSAL: Called LGconfigureCodecMSG
08-24 14:32:00.728   329  8426 V LGCodecOSAL: Not support LGCodec
08-24 14:32:00.728   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-24 14:32:00.728   329  8426 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-24 14:32:00.728   329  8426 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-24 14:32:00.729   329  8426 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-24 14:32:00.729   329  8426 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 14:32:00.729   329  8426 V AudioSystem: isOffloadSupported()
08-24 14:32:00.729   329  8426 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 14:32:00.729   329  8426 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-24 14:32:00.729   329  8426 V OMXCodec: init()
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-24 14:32:00.729   329  8426 V OMXCodec: allocateBuffers
08-24 14:32:00.729   329  8426 V OMXCodec: allocateBuffersOnPort portIndex=0
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.deco,der] allocated buffer 0xb54f7ab0 on input port
08-24 14:32:00.729   329  8426 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-24 14:32:00.729   329  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-24 14:32:00.730   329  8426 V OMXCodec: init() mAsyncCompletion wait!!! 
08-24 14:32:00.730   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-24 14:32:00.730   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 14:32:00.730   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
,08-24 14:32:00.730   329  8426 V OMXCodec: init() mAsyncCompletion wait!!! 
08-24 14:32:00.730   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-24 14:32:00.730   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-24 14:32:00.730   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-24 14:32:00.730   329  8426 V OMXCodec: init() mAsyncCompletion wait free! 
08-24 14:32:00.732   329  8426 V AwesomePlayer: finishAsyncPrepare_l() 
08-24 14:32:00.732   329  8426 V AudioCache: notify(0xb5474c00, 5, 0, 0)
08-24 14:32:00.732   329  8426 V AudioCache: ignored
08-24 14:32:00.732   329  8426 V AudioCache: notify(0xb5474c00, 1, 0, 0)
08-24 14:32:00.732   329  8426 V AudioCache: prepared
,08-24 14:32:00.732   329  1386 V AudioCache: wait - success
08-24 14:32:00.732   329  1386 V MediaPlayerService: start
08-24 14:32:00.732   329  1386 V AwesomePlayer: play_l() 
08-24 14:32:00.732   329  1386 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-24 14:32:00.732   329  1386 V AwesomePlayer: createAudioPlayer_l
08-24 14:32:00.732   329  1386 V AwesomePlayer: seekAudioIfNecessary_l() 
08-24 14:32:00.732   329  1386 V AwesomePlayer: startAudioPlayer_l() 
08-24 14:32:00.732   329  1386 D AudioPlayer: start of Playback, useOffload 0
08-24 14:32:00.732   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-24 14:32:00.732   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-24 14:32:00.734   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-24 14:32:00.735   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-24 14:32:00.735   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-24 14:32:00.735   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-24 14:32:00.735   329  8428 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 14:32:00.735   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 14:32:00.735   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
,08-24 14:32:00.735   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-24 14:32:00.735   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-24 14:32:00.735   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on output port
08-24 14:32:00.735   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-24 14:32:00.735   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-24 14:32:00.735   329  1386 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-24 14:32:00.736   329  1386 V AudioCache: notify(0xb5474c00, 6, 0, 0)
08-24 14:32:00.736   329  1386 V AudioCache: ignored
08-24 14:32:00.736   329  1386 V MediaPlayerService: wait for playback complete
,08-24 14:32:00.745   329  8429 V AudioCache: write(0xb16e5000, 4096),
08-24 14:32:00.745   329  8429 V AudioCache: memcpy(0xac100000, 0xb16e5000, 4096)
08-24 14:32:00.745   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.745   329  8429 V AudioCache: memcpy(0xac101000, 0xb16e5000, 4096)
08-24 14:32:00.746   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.746   329  8429 V AudioCache: memcpy(0xac102000, 0xb16e5000, 4096)
08-24 14:32:00.746   329  8429 V AudioCache: write(0xb16e5000, 4096),
08-24 14:32:00.746   329  8429 V AudioCache: memcpy(0xac103000, 0xb16e5000, 4096)
08-24 14:32:00.747   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.747   329  8429 V AudioCache: memcpy(0xac104000, 0xb16e5000, 4096)
08-24 14:32:00.747   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.747   329  8429 V AudioCache: memcpy(0xac105000, 0xb16e5000, 4096)
08-24 14:32:00.747   329  8429 V AudioCache: write(0xb16e5000, 4096),
08-24 14:32:00.747   329  8429 V AudioCache: memcpy(0xac106000, 0xb16e5000, 4096)
08-24 14:32:00.748   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.748   329  8429 V AudioCache: memcpy(0xac107000, 0xb16e5000, 4096)
08-24 14:32:00.748   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.748   329  8429 V AudioCache: memcpy(0xac108000, 0xb16e5000, 4096)
08-24 14:32:00.748   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.748   329  8429 V AudioCache: memcpy(0xac109000, 0xb16e5000, 4096)
08-24 14:32:00.749   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.749   329  8429 V AudioCache: memcpy(0xac10a000, 0xb16e5000, 4096)
08-24 14:32:00.749   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.749   329  8429 V AudioCache: memcpy(0xac10b000, 0xb16e5000, 4096)
08-24 14:32:00.749   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.749   329  8429 V AudioCache: memcpy(0xac10c000, 0xb16e5000, 4096)
08-24 14:32:00.749   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.749   329  8429 V AudioCache: memcpy(0xac10d000, 0xb16e5000, 4096)
08-24 14:32:00.749   329  8429 V AudioCache: write(0xb16e5000, 4096)
,08-24 14:32:00.749   329  8429 V AudioCache: memcpy(0xac10e000, 0xb16e5000, 4096)
08-24 14:32:00.749   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.749   329  8429 V AudioCache: memcpy(0xac10f000, 0xb16e5000, 4096)
08-24 14:32:00.750   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.750   329  8429 V AudioCache: memcpy(0xac110000, 0xb16e5000, 4096)
08-24 14:32:00.750   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.750   329  8429 V AudioCache: memcpy(0xac111000, 0xb16e5000, 4096)
08-24 14:32:00.750   329  8429 V AudioCache: write(0xb16e5000, 4096)
,08-24 14:32:00.750   329  8429 V AudioCache: memcpy(0xac112000, 0xb16e5000, 4096)
08-24 14:32:00.751   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.751   329  8429 V AudioCache: memcpy(0xac113000, 0xb16e5000, 4096)
08-24 14:32:00.751   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.751   329  8429 V AudioCache: memcpy(0xac114000, 0xb16e5000, 4096)
08-24 14:32:00.751   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.751   329  8429 V AudioCache: memcpy(0xac115000, 0xb16e5000, 4096)
08-24 14:32:00.752   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.752   329  8429 V AudioCache: memcpy(0xac116000, 0xb16e5000, 4096),
08-24 14:32:00.752   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.752   329  8429 V AudioCache: memcpy(0xac117000, 0xb16e5000, 4096)
08-24 14:32:00.753   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.753   329  8429 V AudioCache: memcpy(0xac118000, 0xb16e5000, 4096)
08-24 14:32:00.753   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.753   329  8429 V AudioCache: memcpy(0xac119000, 0xb16e5000, 4096)
08-24 14:32:00.753   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.753   329  8429 V AudioCache: memcpy(0xac11a000, 0xb16e5000, 4096)
08-24 14:32:00.754   329  8429 V AudioCache: write(0xb16e5000, 4096)
,08-24 14:32:00.754   329  8429 V AudioCache: memcpy(0xac11b000, 0xb16e5000, 4096)
08-24 14:32:00.754   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.754   329  8429 V AudioCache: memcpy(0xac11c000, 0xb16e5000, 4096)
08-24 14:32:00.754   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.754   329  8429 V AudioCache: memcpy(0xac11d000, 0xb16e5000, 4096)
08-24 14:32:00.755   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.755   329  8429 V AudioCache: memcpy(0xac11e000, 0xb16e5000, 4096)
08-24 14:32:00.755   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.755   329  8429 V AudioCache: memcpy(0xac11f000, 0xb16e5000, 4096)
08-24 14:32:00.756   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.756   329  8429 V AudioCache: memcpy(0xac120000, 0xb16e5000, 4096)
08-24 14:32:00.756   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.756   329  8429 V AudioCache: memcpy(0xac121000, 0xb16e5000, 4096)
08-24 14:32:00.756   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.756   329  8429 V AudioCache: memcpy(0xac122000, 0xb16e5000, 4096)
08-24 14:32:00.757  8350  8350 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-24 14:32:00.757   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.757   329  8429 V AudioCache: memcpy(0xac123000, 0xb16e5000, 4096)
08-24 14:32:00.757   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.757   329  8429 V AudioCache: memcpy(0xac124000, 0xb16e5000, 4096)
08-24 14:32:00.757   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.757   329  8429 V AudioCache: memcpy(0xac125000, 0xb16e5000, 4096)
08-24 14:32:00.758  8350  8350 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-24 14:32:00.758   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.758   329  8429 V AudioCache: memcpy(0xac126000, 0xb16e5000, 4096)
08-24 14:32:00.758   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.758   329  8429 V AudioCache: memcpy(0xac127000, 0xb16e5000, 4096)
08-24 14:32:00.759   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.759   329  8429 V AudioCache: memcpy(0xac128000, 0xb16e5000, 4096)
08-24 14:32:00.759   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.759   329  8429 V AudioCache: memcpy(0xac129000, 0xb16e5000, 4096)
08-24 14:32:00.759   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.759   329  8429 V AudioCache: memcpy(0xac12a000, 0xb16e5000, 4096)
08-24 14:32:00.759  8350  8350 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3480
08-24 14:32:00.760   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.760   329  8429 V AudioCache: memcpy(0xac12b000, 0xb16e5000, 4096)
08-24 14:32:00.760   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.760   329  8429 V AudioCache: memcpy(0xac12c000, 0xb16e5000, 4096)
08-24 14:32:00.760   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.760   329  8429 V AudioCache: memcpy(0xac12d000, 0xb16e5000, 4096)
08-24 14:32:00.761   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.761   329  8429 V AudioCache: memcpy(0xac12e000, 0xb16e5000, 4096)
08-24 14:32:00.761   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.761   329  8429 V AudioCache: memcpy(0xac12f000, 0xb16e5000, 4096)
08-24 14:32:00.761   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.761   329  8429 V AudioCache: memcpy(0xac130000, 0xb16e5000, 4096)
08-24 14:32:00.762   329  8429 V AudioCache: write(0xb16e5000, 4096)
08-24 14:32:00.762   329  8429 V AudioCache: memcpy(0xac131000, 0xb16e5000, 4096)
08-24 14:32:00.762   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-24 14:32:00.762   329  8429 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08,-24 14:32:00.762   329  8429 V AwesomePlayer: postAudioEOS() 
08-24 14:32:00.762   329  8429 V AudioCache: write(0xb16e5000, 280)
08-24 14:32:00.762   329  8429 V AudioCache: memcpy(0xac132000, 0xb16e5000, 280)
08-24 14:32:00.763   329  8426 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-24 14:32:00.763   329  8426 V AwesomePlayer: onStreamDone
08-24 14:32:00.763   329  8426 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-24 14:32:00.763   329  8426 V AudioCache: notify(0xb5474c00, 2, 0, 0)
08-24 14:32:00.763   329  8426 V AudioCache: playback complete
08-24 14:32:00.763   329  8426 V AwesomePlayer: pause_l() 
08-24 14:32:00.763   329  8426 V AudioCache: notify(0xb5474c00, 7, 0, 0)
08-24 14:32:00.763   329  8426 V AudioCache: ignored
08-24 14:32:00.763   329  8426 V AwesomePlayer: cancelPlayerEvents
08-24 14:32:00.763   329  1386 V AudioCache: wait - success
08-24 14:32:00.763   329  1386 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-24 14:32:00.764   329  8426 D AudioPlayer: Pause Playback at 1068125
08-24 14:32:00.764   329  1386 V AwesomePlayer: reset_l() 
08-24 14:32:00.764   329  1386 V AudioCache: notify(0xb5474c00, 8, 0, 0)
08-24 14:32:00.764   329  1386 V AudioCache: ignored
08-24 14:32:00.764   329  1386 V AwesomePlayer: cancelPlayerEvents
08-24 14:32:00.764   329  1386 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-24 14:32:00.764   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-24 14:32:00.764   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-24 14:32:00.764   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-24 14:32:00.764   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8240 on port 1
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 14:32:00.764   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-24 14:32:00.764   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncComp,letion wait free!!
08-24 14:32:00.764   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-24 14:32:00.765   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-24 14:32:00.765   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-24 14:32:00.765   329  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-24 14:32:00.765   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-24 14:32:00.765   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-24 14:32:00.765   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-24 14:32:00.765   329  1386 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-24 14:32:00.765   329  1386 D AudioPlayer: AudioPlayer releasing audio source
08-24 14:32:00.765   329  1386 D AudioPlayer: AudioPlayer done releasing audio source
08-24 14:32:00.765   329  1386 V AwesomePlayer: reset_l() 
08-24 14:32:00.765   329  1386 V AwesomePlayer: cancelPlayerEvents
08-24 14:32:00.765   329  1386 V AwesomePlayer: ~AwesomePlayer call
08-24 14:32:00.766   329  1386 V AwesomePlayer: reset_l() 
08-24 14:32:00.766   329  1386 V AwesomePlayer: cancelPlayerEvents
08-24 14:32:00.766  8350  8425 V SoundPool: close(31)
08-24 14:32:00.766  8350  8425 V SoundPool: pointer = 0x9fe4b000, size = 205080, sampleRate = 48000, numChannels = 2
08-24 14:32:00.767  8275  8275 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-24 14:32:00.771  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-24 14:32:00.773  7753  7753 D UEI.SmartControl: QS start get config
08-24 14:32:00.777  3776  3791 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 14:32:00.781  2206  2206 I ConfigService: onCreate
08-24 14:32:00.781  2206  2206 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/config.db'.
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at com.google.android.gms.config.h.run(SourceFile:121)
08-24 14:32:00.785  2206  8430 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-24 14:32:00.785  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at com.google.android.gms.config.h.run(SourceFile:121)
08-24 14:32:00.786  2206  8430 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-24 14:32:00.786  1817  4024 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
08-24 14:32:00.790  2206  8430 W SQLiteOpenHelper: Opened config.db in read-only mode
08-24 14:32:00.791  2206  2206 I ConfigService: onBind returning update interface
08-24 14:32:00.793  2206  2206 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-24 14:32:00.793  2206  2206 I ConfigService: onBind returning config service
08-24 14:32:00.793  1931  1931 D ActionManagerService: notifyUserLog: 1000001
08-24 14:32:00.795  3776  4992 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-24 14:32:00.795  3776  4992 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-24 14:32:00.798  2206  2206 I ConfigService: onDestroy
08-24 14:32:00.799  1931  1931 D ActionManagerService: notifyUserLog: 1000001
08-24 14:32:00.799  3776  4992 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-24 14:32:00.799  3776  4992 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-24 14:32:00.799  3776  4992 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-24 14:32:00.800  3776  4992 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-24 14:32:00.800  3776  3792 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 14:32:00.801  1817  8431 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-24 14:32:00.803  2078  2078 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-24 14:32:00.803  2078  2078 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-24 14:32:00.805  2078  2078 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-24 14:32:00.806  2078  2078 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,08-24 14:32:00.808  2078  2078 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-24 14:32:00.808  2078  2078 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-24 14:32:00.808  7205  7205 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: Error inserting package=com.test.thalitest
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 14:32:00.813  7205  7205 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 14:32:00.830  2268  2391 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-24 14:32:00.830  2268  8437 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:32:00.831  2268  2391 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:32:00.836  1817  8435 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:32:00.836  1817  8435 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:32:00.837  1817  8435 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-24 14:32:00.838  1817  8435 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
--------- beginning of crash
08-24 14:32:00.839  1817  8435 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-24 14:32:00.839  1817  8435 E AndroidRuntime: Process: com.google.android.gms, PID: 1817
08-24 14:32:00.839  1817  8435 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-24 14:32:00.839  1817  8435 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 14:32:00.839  1817  8435 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-24 14:32:00.839  1817  8435 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-24 14:32:00.839  1817  8435 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 14:32:00.839  1817  8435 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-24 14:32:00.839  1817  8435 E AndroidRuntime: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:215)
08-24 14:32:00.839  1817  8435 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-24 14:32:00.839  1817  8435 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-24 14:32:00.839  1817  8435 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:00.839  1817  8435 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:32:00.839  1817  8435 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:32:00.841  5910  8436 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-24 14:32:00.848  2268  8437 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-24 14:32:00.848  1036  1968 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8438 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-24 14:32:00.849  2268  8437 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-24 14:32:00.849  2268  8437 E AndroidRuntime: Process: android.process.acore, PID: 2268
08-24 14:32:00.849  2268  8437 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:32:00.849  2268  8437 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:32:00.853  7753  7753 E UEI.SmartControl: unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac1a: open failed: EROFS (Read-only file system)
08-24 14:32:00.853  7753  7753 I UEI.SmartControl: Specific region DB is not found, use default...

```
