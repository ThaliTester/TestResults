#### Test 84265062bba4ad4_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-11 11:55:52.444  6569  6569 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
--------- beginning of system
09-11 11:55:52.480  1031  1049 I ActivityManager: Killing 5507:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-11 11:55:52.510  1982  1982 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
09-11 11:55:52.510  1982  1982 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-11 11:55:52.512  1031  1918 W libprocessgroup: failed to open /acct/uid_10085/pid_5507/cgroup.procs: No such file or directory
09-11 11:55:52.518  1982  1982 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-11 11:55:52.550  6408  6408 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-11 11:55:52.555  6408  6408 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
09-11 11:55:52.577  5071  6594 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-11 11:55:52.621  1031  1964 V SIM_STK : Menu title from STK is T-Mobile
09-11 11:55:52.634  1031  1562 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6595 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-11 11:55:52.732  5071  6594 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 154 ms] updated apps [took 154 ms] 
09-11 11:55:52.885  6595  6595 D DocsApplication: Installing DEX configuration.
09-11 11:55:52.904  6595  6595 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-11 11:55:52.909  6595  6595 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{247836bd com.google.android.apps.docs}
09-11 11:55:52.926  6595  6595 D TAG     : onCreate()
09-11 11:55:52.945  6595  6595 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-11 11:55:53.085   321   434 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,09-11 11:55:53.088  3241  6613 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-11 11:55:53.313   302   302 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
09-11 11:55:53.313   302   302 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
09-11 11:55:53.313   302   302 I rmt_storage: wakelock acquired: 1, error no: 42
09-11 11:55:53.313   302   909 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
09-11 11:55:53.414   302   909 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
09-11 11:55:53.414   302   909 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
09-11 11:55:53.414   302   909 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
09-11 11:55:53.414   302   909 I rmt_storage: 
09-11 11:55:53.416   302   302 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
09-11 11:55:53.417   904   916 E Diag_Lib: [IMS_FATAL]| 3347 | 916 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
09-11 11:55:53.576  6614  6614 D AndroidRuntime: 
09-11 11:55:53.576  6614  6614 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-11 11:55:53.579  6614  6614 D AndroidRuntime: CheckJNI is OFF
09-11 11:55:53.704  6614  6614 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-11 11:55:53.709  1031  1641 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-11 11:55:53.723  1928  1944 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-11 11:55:53.726  1031  1641 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-11 11:55:53.729  1031  1641 D ActivityManager: setTaskToReturnTo : TaskRecord{1f00b794 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-11 11:55:53.729  1031  1641 D ActivityManager: setTaskToReturnTo : TaskRecord{1f00b794 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-11 11:55:53.730  1031  1641 D WindowStateEx: AppWindowTokenEx init.. 
09-11 11:55:53.731   328   350 E GBMv2   : DFP En is all cleared set to be enabled
09-11 11:55:53.735  1804  5141 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-11 11:55:53.774  1031  1641 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6629 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-11 11:55:53.776  6614  6614 D AndroidRuntime: Shutting down VM
09-11 11:55:53.826  1928  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-11 11:55:53.826  1928  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2007efc9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-11 11:55:53.829  1928  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-11 11:55:53.830  1928  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{ce686ce co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-11 11:55:53.864  6629  6629 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-11 11:55:53.923  6629  6629 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-11 11:55:53.930  6629  6629 I LibraryLoader: Loading: webviewchromium
09-11 11:55:53.932  6629  6629 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1401-1403)
09-11 11:55:53.932  6629  6629 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-11 11:55:53.949  6629  6629 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2712955f}
09-11 11:55:53.951  6629  6629 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-11 11:55:53.952  6629  6629 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-11 11:55:53.954  1804  5141 I art     : Explicit concurrent mark sweep GC freed 35381(2MB) AllocSpace objects, 13(208KB) LOS objects, 51% free, 29MB/61MB, paused 1.376ms total 132.773ms
09-11 11:55:53.958  6629  6629 I BrowserStartupController: Initializing chromium process, renderers=0
09-11 11:55:53.959  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-11 11:55:53.973  6629  6629 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-11 11:55:53.974  6629  6629 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-11 11:55:53.974   311   311 V AudioPolicyService: registerClient() client 0xb558a280, uid 10118
09-11 11:55:53.974  6629  6629 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-11 11:55:53.975  1804  5141 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-11 11:55:53.984  6629  6629 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-11 11:55:53.984  6629  6629 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-11 11:55:53.984  6629  6629 I Adreno-EGL: Build Date: 12/12/14 금
09-11 11:55:53.984  6629  6629 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-11 11:55:53.984  6629  6629 I Adreno-EGL: Remote Branch: 
09-11 11:55:53.984  6629  6629 I Adreno-EGL: Local Patches: 
09-11 11:55:53.984  6629  6629 I Adreno-EGL: Reconstruct Branch: 
,09-11 11:55:53.990  1031  1102 D BluetoothManagerService: Message: 20
09-11 11:55:53.990  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2764f77e:true
09-11 11:55:54.013  1804  5141 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,09-11 11:55:54.063  6629  6668 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-11 11:55:54.065  6629  6629 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-11 11:55:54.078  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-11 11:55:54.081  6629  6629 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-11 11:55:54.084  6629  6629 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-11 11:55:54.086  6629  6629 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-11 11:55:54.086  6629  6629 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-11 11:55:54.103  6629  6629 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-11 11:55:54.112  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-11 11:55:54.112  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-11 11:55:54.169  6629  6685 D OpenGLRenderer: Render dirty regions requested: true
09-11 11:55:54.169  6629  6685 I OpenGLRenderer: Initialized EGL, version 1.4
,09-11 11:55:54.175  6629  6685 D OpenGLRenderer: Enabling debug mode 0
09-11 11:55:54.197  6629  6629 D Atlas   : Validating map...
,09-11 11:55:54.205  1031  1049 D SplitWindow: check instance of lgWin Window{16f14748 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-11 11:55:54.230  6629  6679 D LgDataFeature: LgDataFeature() Constructor: none
,09-11 11:55:54.230  6629  6679 D LgDataFeature: LgDataFeature() Constructor Done, null
09-11 11:55:54.354  1031  1103 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +529ms (total +622ms)
09-11 11:55:54.355  1031  1103 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3bb5723d u0 com.test.thalitest/.MainActivity t6} time:101826
,09-11 11:55:54.358  6629  6629 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@280f07ba time:101829
09-11 11:55:54.467  6629  6629 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-11 11:55:54.467  6629  6629 I chromium: 
,09-11 11:55:54.485  6629  6629 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-11 11:55:54.533  6595  6595 D LgDataFeature: LgDataFeature() Constructor: none
09-11 11:55:54.533  6595  6595 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-11 11:55:54.630  6629  6696 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,09-11 11:55:54.644  6629  6696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-11 11:55:54.644  6629  6696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-11 11:55:54.644  6629  6696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-11 11:55:54.644  6629  6696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-11 11:55:54.644  6629  6696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-11 11:55:54.644  6629  6696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1f5e added. We now have 1 listener(s)
,09-11 11:55:54.649  1031  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:55:54.652  6629  6696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-11 11:55:54.653  6629  6696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:55:54.654  6629  6696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:55:54.654  6629  6696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-11 11:55:54.661  6629  6696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20ef5d55 added. We now have 1 listener(s)
09-11 11:55:54.661  6629  6696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:55:54.664  1031  1530 D WifiService: New client listening to asynchronous messages
09-11 11:55:54.667  6629  6696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:55:54.667  6629  6696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-11 11:55:54.667  6629  6696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-11 11:55:54.667  6629  6696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-11 11:55:54.668  6629  6696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-11 11:55:54.671  6629  6696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:55:54.671  1031  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:55:54.672  6629  6696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-11 11:55:54.678  6629  6696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-11 11:55:54.678  6629  6696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:55:54.678  6629  6696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:55:54.678  6629  6696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:55:54.678  6629  6696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:55:54.678  6629  6696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:55:54.678  6629  6696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:55:54.678  6629  6696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:55:54.678  6629  6696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:55:54.678  6629  6696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-11 11:55:54.679  6629  6696 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:55:54.680  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:55:54.682  6629  6696 I io.jxcore.node.LifeCycleMonitor: start: OK
09-11 11:55:54.682  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:55:54.717  6629  6679 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-11 11:55:54.717  6629  6679 I chromium: 
,09-11 11:55:54.767  1031  1562 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6705 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-11 11:55:54.768  1031  1562 I ActivityManager: Killing 6169:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-11 11:55:54.782  6629  6629 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-11 11:55:54.880  1031  1945 W libprocessgroup: failed to open /acct/uid_10097/pid_6169/cgroup.procs: No such file or directory
,09-11 11:55:54.889  6595  6595 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
09-11 11:55:54.917  6705  6705 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-11 11:55:54.931  6705  6705 I LockScreenSettings: New app installed broadcast received ..
,09-11 11:55:54.934  6705  6705 I LockScreenSettings: Number of installed packages  1
09-11 11:55:54.973  1031  1983 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6731 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-11 11:55:54.998   340   340 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 27.822ms
,09-11 11:55:55.018   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 18.204ms
09-11 11:55:55.035   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 352us total 16.284ms
,09-11 11:55:55.035  6731  6731 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-11 11:55:55.254  1031  1946 V SIM_STK : Menu title from STK is T-Mobile
09-11 11:55:55.308  1031  1760 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6757 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-11 11:55:55.349   328   352 E GBMv2   : DFP En is all cleared set to be enabled
09-11 11:55:55.349   328   352 E GBMv2   : Set value is all cleared set the max
09-11 11:55:55.349   328   352 I GBMv2   : DFP Enabled. Ignore VFP set
,09-11 11:55:55.364  6757  6757 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-11 11:55:55.364  6757  6757 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,09-11 11:55:55.367  5653  5653 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
09-11 11:55:55.376  1031  1918 I art     : Explicit concurrent mark sweep GC freed 18251(891KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2ms total 135.677ms
09-11 11:55:55.386  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,09-11 11:55:55.408  1031  1873 I ActivityManager: Killing 6194:com.google.android.gm/u0a64 (adj 15): empty #17
,09-11 11:55:55.480  1031  1945 W libprocessgroup: failed to open /acct/uid_10064/pid_6194/cgroup.procs: No such file or directory
,09-11 11:55:55.649  6629  6700 W jxcore-log: Initializing JXcore engine
09-11 11:55:55.649  6629  6700 W jxcore-log: JXcore engine is ready
,09-11 11:55:55.679  6700  6700 W Thread-782: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8409]" dev="sockfs" ino=8409 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-11 11:55:55.679  6700  6700 W Thread-782: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-11 11:55:55.679  6700  6700 W Thread-782: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10387]" dev="sockfs" ino=10387 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-11 11:55:55.679  6700  6700 W Thread-782: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-11 11:55:55.679  6700  6700 W Thread-782: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30281]" dev="sockfs" ino=30281 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-11 11:55:55.701  6629  6700 W jxcore-log: Starting JXcore engine
09-11 11:55:55.781  6629  6700 W jxcore-log: Platform android
09-11 11:55:55.781  6629  6700 W jxcore-log: 
09-11 11:55:55.781  6629  6700 W jxcore-log: Process ARCH arm
09-11 11:55:55.781  6629  6700 W jxcore-log: 
,09-11 11:55:56.055  6629  6700 I jxcore-log: JXcore Cordova bridge is ready!
09-11 11:55:56.055  6629  6700 I jxcore-log: 
09-11 11:55:56.056  6629  6700 W jxcore-log: JXcore engine is started
,09-11 11:55:56.065  6629  6696 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-11 11:55:56.067  6629  6629 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-11 11:55:58.661  6595  6595 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
09-11 11:55:58.666  1031  1946 I ActivityManager: Killing 5984:com.google.android.talk/u0a72 (adj 15): empty #17
,09-11 11:55:58.790  1031  1048 W libprocessgroup: failed to open /acct/uid_10072/pid_5984/cgroup.procs: No such file or directory
,09-11 11:55:59.625  6595  6695 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-11 11:56:00.039  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-11 11:56:00.039  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
09-11 11:56:00.039  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-11 11:56:00.039  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,09-11 11:56:00.046  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
09-11 11:56:00.046  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
09-11 11:56:00.047  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
09-11 11:56:00.049  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
09-11 11:56:00.236  1031  1946 I ActivityManager: Killing 5773:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-11 11:56:00.269  5749  5749 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-11 11:56:00.269  5749  5749 W System.err: android.os.DeadObjectException
09-11 11:56:00.269  5749  5749 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-11 11:56:00.269  5749  5749 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-11 11:56:00.269  5749  5749 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-11 11:56:00.269  5749  5749 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-11 11:56:00.269  5749  5749 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-11 11:56:00.269  5749  5749 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-11 11:56:00.269  5749  5749 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-11 11:56:00.269  5749  5749 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-11 11:56:00.270  5749  5749 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:00.270  5749  5749 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:00.270  5749  5749 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:00.270  5749  5749 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:00.270  5749  5749 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:00.270  5749  5749 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:00.270  5749  5749 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-11 11:56:00.270  5749  5749 W System.err: android.os.DeadObjectException
09-11 11:56:00.270  5749  5749 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-11 11:56:00.270  5749  5749 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-11 11:56:00.270  5749  5749 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-11 11:56:00.270  5749  5749 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-11 11:56:00.270  5749  5749 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-11 11:56:00.271  5749  5749 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-11 11:56:00.271  5749  5749 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-11 11:56:00.271  5749  5749 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-11 11:56:00.271  5749  5749 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:00.271  5749  5749 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:00.271  5749  5749 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:00.271  5749  5749 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:00.271  5749  5749 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:00.271  5749  5749 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:00.271  5749  5749 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-11 11:56:00.271  5749  5749 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-11 11:56:00.449  1031  1946 E libprocessgroup: failed to kill 1 processes for processgroup 5773
,09-11 11:56:00.564  1031  1048 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-11 11:56:00.575  5749  5749 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-11 11:56:00.575  5749  5749 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-11 11:56:00.616  1031  1760 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6806 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-11 11:56:00.617  5749  5749 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-11 11:56:00.685  6806  6806 D UEI.SmartControl: Quickset Services start...
09-11 11:56:00.687  6806  6806 I UEI.SmartControl: Manufacture = LGE
09-11 11:56:00.687  6806  6806 D UEI.SmartControl: Id = LGNevo
09-11 11:56:00.688  6806  6806 D UEI.SmartControl: File observer start...
,09-11 11:56:00.690  6806  6806 E UEI.SmartControl: IR Port is disabled: false
09-11 11:56:00.690  6806  6806 D UEI.SmartControl: Starting file observer...
09-11 11:56:00.691  6806  6806 D UEI.SmartControl: Extracting JNI libs...
,09-11 11:56:00.691  6806  6806 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-11 11:56:00.781  6806  6806 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-11 11:56:00.782  6806  6806 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-11 11:56:00.782  6806  6806 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-11 11:56:00.818  6806  6806 I UEI.SmartControl: --- Selecting new region: 6
,09-11 11:56:00.821  6806  6806 I UEI.SmartControl: Model = LG-D855
09-11 11:56:00.823  6806  6806 D UEI.SmartControl: QS Service created
09-11 11:56:00.840  6806  6806 I UEI.SmartControl: Service initServices...
09-11 11:56:00.845  6806  6806 D UEI.SmartControl: QS start get config
,09-11 11:56:00.888  6806  6806 D UEI.SmartControl: Loading JNI Libs...
,09-11 11:56:01.187  6806  6806 I UEI.SmartControl: Supports setup maps: true
,09-11 11:56:01.195  6806  6806 D UEI.SmartControl: QS start statue = true Error code = 0
09-11 11:56:01.195  6806  6806 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-11 11:56:01.196  6806  6806 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-11 11:56:01.196  6806  6806 I UEI.SmartControl: ### init IR Blaster...
09-11 11:56:01.201  6806  6806 D serial_port: Configuring serial port
09-11 11:56:01.206  6806  6806 E UEI.SmartControl: UEIBLaster setting for 616
,09-11 11:56:01.206  6806  6806 I UEI.SmartControl: Setting serial record hearder size = 2
,09-11 11:56:01.206  6806  6806 I UEI.SmartControl: configuring settings for MAXQ616
09-11 11:56:01.207  6806  6806 I UEI.SmartControl: Get version...
,09-11 11:56:01.223  6806  6832 D UEI.SmartControl: serial port data available: 21
,09-11 11:56:01.250  6806  6806 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-11 11:56:01.250  6806  6806 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-11 11:56:01.250  6806  6806 I UEI.SmartControl: QS saving settings...
09-11 11:56:01.251  6806  6806 D UEI.SmartControl: IR Blaster version: 25672567
,09-11 11:56:01.264  6806  6832 D UEI.SmartControl: serial port data available: 4
,09-11 11:56:01.296  6806  6806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-11 11:56:01.301  6806  6835 I UEI.SmartControl: Device manager: loading config....
09-11 11:56:01.301  6806  6835 D UEI.SmartControl: ----------- loading internal config...
09-11 11:56:01.307  6806  6806 E UEI.SmartControl: Services init done
09-11 11:56:01.307  6806  6806 D UEI.SmartControl: QS Service init finished
09-11 11:56:01.308  6806  6806 D UEI.SmartControl: QS Service version name: 2.1.91
09-11 11:56:01.308  6806  6806 D UEI.SmartControl: QS Service version code: 201091
,09-11 11:56:01.311  6806  6806 D UEI.SmartControl: Service requested: Control
09-11 11:56:01.314  6806  6835 E UEI.SmartControl: Loading SETTINGS...
09-11 11:56:01.317  6806  6806 D UEI.SmartControl: Request IControl service: devices are loaded...
09-11 11:56:01.318  1031  2000 I ActivityManager: Killing 5749:com.lge.qremote/u0a112 (adj 15): empty #17
09-11 11:56:01.325  6806  6835 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-11 11:56:01.349  6806  6834 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-11 11:56:01.349  6806  6834 D UEI.SmartControl: -----service ready thread exits
09-11 11:56:01.420  1031  1049 W libprocessgroup: failed to open /acct/uid_10112/pid_5749/cgroup.procs: No such file or directory
,09-11 11:56:01.429  6806  6806 D UEI.SmartControl: Internal service binding...
,09-11 11:56:05.245  2773  2773 I MusicWidget: mDelayedStopHandler : unbind
,09-11 11:56:05.250  2145  2145 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-11 11:56:05.250  2145  2145 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-11 11:56:05.250  2145  2145 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-11 11:56:05.252  2145  2145 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-11 11:56:05.252  2145  2145 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-11 11:56:05.253  2145  2145 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-11 11:56:05.254  2145  2145 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-11 11:56:05.254  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-11 11:56:05.256  1031  1983 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@17e770e5com.lge.music.MediaPlaybackService$5@280f07ba
09-11 11:56:05.257  2145  2145 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-11 11:56:05.257  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-11 11:56:05.258  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-11 11:56:05.261  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-11 11:56:05.261  2145  2145 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@38f5287b
09-11 11:56:05.262  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-11 11:56:05.262  2145  2145 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-11 11:56:05.263  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-11 11:56:05.263  2145  2145 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-11 11:56:05.263  2145  2145 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-11 11:56:05.263  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-11 11:56:05.264  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-11 11:56:05.265  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-11 11:56:05.265  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-11 11:56:05.266  2145  2145 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-11 11:56:05.267  2145  2145 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-11 11:56:05.268  2145  2145 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-11 11:56:05.268  2145  2145 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-11 11:56:05.268  2145  2145 V MediaPlayer[Native]: reset
09-11 11:56:05.274  2145  2145 V MediaPlayer[Native]: setListener
09-11 11:56:05.274  2145  2145 V MediaPlayer[Native]: disconnect
09-11 11:56:05.274  2145  2145 V MediaPlayer[Native]: destructor
09-11 11:56:05.274   311   311 V AudioFlinger: releasing 18 from 2145 for -1
09-11 11:56:05.274   311   311 V AudioFlinger:  decremented refcount to 0
09-11 11:56:05.274   311   311 V AudioFlinger: purging stale effects
09-11 11:56:05.274  2145  2145 V MediaPlayer[Native]: disconnect
09-11 11:56:05.275  2145  2145 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-11 11:56:05.276  2145  2145 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-11 11:56:05.277  2145  2145 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-11 11:56:05.277  2145  2145 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-11 11:56:05.278  2145  2145 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-11 11:56:05.278  2145  2145 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-11 11:56:05.278  2145  2145 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 379397739
09-11 11:56:05.278  2145  2145 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 379397739
,09-11 11:56:05.283  2145  2145 I SmartShareClient: [SmartShareManagerClient] terminate service: 2145/MediaPlaybackService/603357625
09-11 11:56:05.286  2145  2145 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-11 11:56:05.286  2145  2145 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@246025c8
09-11 11:56:05.288  2145  2145 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-11 11:56:05.289  2145  2145 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-11 11:56:05.290  2145  2145 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-11 11:56:05.290  2145  2145 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-11 11:56:05.292  1031  2000 I ActivityManager: Killing 5696:com.android.calendar/u0a13 (adj 15): empty #17
,09-11 11:56:05.299  2145  2145 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
,09-11 11:56:05.381  1031  1049 W libprocessgroup: failed to open /acct/uid_10013/pid_5696/cgroup.procs: No such file or directory
,09-11 11:56:05.920  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-11 11:56:05.920  6629  6700 I jxcore-log: 
,09-11 11:56:05.922  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-11 11:56:05.922  6629  6700 I jxcore-log: 
09-11 11:56:05.927  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:05.927  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:05.927  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:05.927  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:05.927  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:05.927  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:05.927  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:05.927  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:05.930  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:05.933  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-11 11:56:05.933  6629  6700 I jxcore-log: 
,09-11 11:56:05.934  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-11 11:56:05.934  6629  6700 I jxcore-log: 
,09-11 11:56:06.295  6806  6836 D UEI.SmartControl: Internal timer expired: 1
09-11 11:56:06.296  6806  6836 D UEI.SmartControl: unbind internal service
,09-11 11:56:06.310  6806  6806 D UEI.SmartControl: Service.onUnbind: IControl
,09-11 11:56:06.312  6806  6806 D UEI.SmartControl: Service.onDestroy
,09-11 11:56:06.313  6806  6806 D UEI.SmartControl: Lock is in USE false
,09-11 11:56:06.313  6806  6806 D UEI.SmartControl: unbind internal service
09-11 11:56:06.313  6806  6806 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@38f5287b
09-11 11:56:06.314  6806  6806 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-11 11:56:06.314  6806  6806 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-11 11:56:06.314  6806  6806 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-11 11:56:06.314  6806  6806 W System.err: 	at com.uei.control.Service.c(Unknown Source)
,09-11 11:56:06.314  6806  6806 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-11 11:56:06.314  6806  6806 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-11 11:56:06.314  6806  6806 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-11 11:56:06.314  6806  6806 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-11 11:56:06.314  6806  6806 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:06.314  6806  6806 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:06.314  6806  6806 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:06.314  6806  6806 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:06.314  6806  6806 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:06.314  6806  6806 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:06.314  6806  6806 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:06.314  6806  6806 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@38f5287b
,09-11 11:56:06.316  6806  6833 D serial_port: close(fd = 25)
09-11 11:56:06.320  6806  6833 I UEI.SmartControl: Serial port is closed.
09-11 11:56:06.321  6806  6806 I UEI.SmartControl: Serial port is closed.
,09-11 11:56:06.321  6806  6806 I UEI.SmartControl: Serial port is closed.
09-11 11:56:06.321  6806  6806 D UEI.SmartControl: Blaster closed
09-11 11:56:06.321  6806  6806 D UEI.SmartControl: Shut down QS...
,09-11 11:56:06.321  6806  6806 D UEI.SmartControl: Stopping QS lib
09-11 11:56:06.322  6806  6806 D UEI.SmartControl: QS lib stop result = true
09-11 11:56:06.322  6806  6806 D UEI.SmartControl: Stopped QS lib
09-11 11:56:06.322  6806  6806 D UEI.SmartControl: Stopped file observer...
09-11 11:56:06.322  6806  6806 D UEI.SmartControl: QS shutdown complete
09-11 11:56:06.441  6629  6700 D executeNativeTests: Running unit tests
,09-11 11:56:06.518  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-11 11:56:06.518  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae added. We now have 2 listener(s),
,09-11 11:56:06.518  1031  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:06.520  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:56:06.520  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:06.520  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:06.520  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:06.520  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f added. We now have 2 listener(s)
09-11 11:56:06.520  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:06.520  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:56:06.523  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:06.525  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:06.525  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.525  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:06.525  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.525  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:06.525  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.525  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:06.525  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:06.527  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.528  6629  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:06.529  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:06.530  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:06.535  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-11 11:56:06.535  6629  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-11 11:56:06.535  6629  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-11 11:56:06.545  6629  6700 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-11 11:56:06.546  6629  6700 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-11 11:56:06.546  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-11 11:56:06.546  6629  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-11 11:56:06.546  6629  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-11 11:56:06.548  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:06.551  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.551  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.552  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.552  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.552  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:06.552  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-11 11:56:06.552  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae removed from the list
09-11 11:56:06.553  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.553  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f removed from the list
09-11 11:56:06.553  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.553  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.553  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.553  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.554  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.554  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.554  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.554  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.555  6629  6700 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-11 11:56:06.555  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.556  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.556  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.556  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.556  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.556  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.556  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.556  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.556  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.556  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.556  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.556  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.556  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.556  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.556  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.556  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.556  6629  670,0 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.556  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.560  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-11 11:56:06.560  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-11 11:56:06.560  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-11 11:56:06.560  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-11 11:56:06.560  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-11 11:56:06.560  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-11 11:56:06.560  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-11 11:56:06.560  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-11 11:56:06.560  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-11 11:56:06.560  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-11 11:56:06.560  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-11 11:56:06.561  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-11 11:56:06.561  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.561  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.561  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.562  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.563  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.563  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.563  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.563  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.563  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.563  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.563  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.563  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.563  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.563  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.565  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.565  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.565  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.565  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.567  6629  6700 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-11 11:56:06.568  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:06.570  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:06.570  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.570  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:06.570  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.570  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:06.570  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.570  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:06.570  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:06.571  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.571  6629  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:06.571  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:06.571  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:06.572  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:06.572  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:06.572  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-11 11:56:06.572  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:06.574  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:06.577  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-11 11:56:06.577  1031  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:06.581  1031  1098 I ActivityManager: Waited long enough for: ServiceRecord{3cb14046 u0 com.google.android.gms/.wearable.service.WearableService}
09-11 11:56:06.581  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-11 11:56:06.585  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-11 11:56:06.586  6629  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-11 11:56:06.589  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-11 11:56:06.589  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:06.590  6629  6700 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-11 11:56:06.590  6629  6700 I io.jxcore.node.ConnectionHelper: start: OK
09-11 11:56:06.593  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.593  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.593  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.593  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.593  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.593  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:06.593  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.593  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.593  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.593  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.593  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.593  6629  6700 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-11 11:56:06.595  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:06.597  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:06.597  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.597  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:06.597  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.597  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:06.597  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.597  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:06.597  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:06.598  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.598  6629  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:56:06.600  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:06.601  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:06.602  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:06.602  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:06.602  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:06.602  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:06.602  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-11 11:56:06.604  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-11 11:56:06.605  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:06.605  6629  6700 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-11 11:56:06.606  6629  6700 I io.jxcore.node.ConnectionHelper: start: OK
09-11 11:56:06.607  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.607  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.607  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.607  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.607  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.607  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:06.607  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.607  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.607  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.607  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.607  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.607  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.607  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.608  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.608  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.609  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.609  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.609  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.609  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.609  6629  6700 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-11 11:56:06.612  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:06.614  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:06.614  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.614  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:06.614  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.614  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:06.614  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.614  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:06.614  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:06.615  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.615  6629  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:06.616  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:06.617  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:06.617  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:06.617  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:06.617  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:06.617  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:06.617  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-11 11:56:06.620  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-11 11:56:06.621  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:06.622  6629  6700 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-11 11:56:06.623  6629  6700 I io.jxcore.node.ConnectionHelper: start: OK
09-11 11:56:06.623  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.623  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.623  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.623  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.624  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.624  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.624  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.624  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.624  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:06.624  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.624  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.624  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.624  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.624  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.624  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.624  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.625  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.625  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.625  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.625  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.625  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.625  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.626  6629  6700 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-11 11:56:06.626  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.626  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.626  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.626  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.626  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.626  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.626  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.626  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.627  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.627  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.627  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.627  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.627  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.627  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.627  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.627  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.628  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.628  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.628  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.628  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.629  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-11 11:56:06.629  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.629  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.629  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.629  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.629  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.629  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.629  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.629  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.629  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.629  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.629  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.629  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.629  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.629  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.630  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.630  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.630  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.630  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.630  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.630  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.631  6629  6700 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-11 11:56:06.631  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.631  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.631  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.631  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.631  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.631  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.631  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.631  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.631  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.631  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.631  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.631  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.631  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.631  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.632  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.632  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-11 11:56:06.635  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.635  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.635  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.635  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.638  6629  6700 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-11 11:56:06.638  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.638  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.638  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.638  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.638  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.638  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.638  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.638  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.638  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.638  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.638  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.639  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.639  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.639  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.640  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.640  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.641  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.641  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.641  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.641  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.642  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-11 11:56:06.642  6629  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-11 11:56:06.642  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-11 11:56:06.642  6629  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-11 11:56:06.642  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-11 11:56:06.642  6629  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-11 11:56:06.642  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.643  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.643  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.643  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.643  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.643  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.643  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.643  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.643  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.643  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.643  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.643  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.643  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.643  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.646  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.646  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.646  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.646  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.646  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.647  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.647  6629  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:06.647  6629  6700 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-11 11:56:06.647  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-11 11:56:06.649  6629  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:06.649  6629  6700 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-11 11:56:06.649  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-11 11:56:06.649  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-11 11:56:06.650  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-11 11:56:06.650  6629  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-11 11:56:06.650  6629  6700 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-11 11:56:06.650  6629  6700 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-11 11:56:06.650  6629  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:06.650  6629  6700 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-11 11:56:06.651  6629  6700 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-11 11:56:06.651  6629  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:06.651  6629  6700 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-11 11:56:06.651  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-11 11:56:06.653  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-11 11:56:06.654  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-11 11:56:06.655  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-11 11:56:06.656  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-11 11:56:06.656  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-11 11:56:06.656  6629  6700 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-11 11:56:06.656  6629  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:06.656  6629  6700 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-11 11:56:06.656  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.656  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.656  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.656  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.656  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.656  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.657  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-11 11:56:06.659  6629  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 846)
09-11 11:56:06.660  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.660  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.660  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.660  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.660  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.660  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.660  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.660  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.663  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.663  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.664  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.664  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.664  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.664  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.664  6629  6700 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-11 11:56:06.664  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.664  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.665  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.665  6629  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 846
09-11 11:56:06.665  6629  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 846)
09-11 11:56:06.665  6629  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 846)
09-11 11:56:06.665  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.665  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.665  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.665  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.665  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.665  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.665  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.665  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.665  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.665  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.665  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.666  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.666  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.666  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.666  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.666  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.666  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.669  6629  6700 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-11 11:56:06.669  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.669  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.669  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-11 11:56:06.672  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.672  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.672  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.672  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.672  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.672  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.672  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.672  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.672  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.672  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.672  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.673  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.673  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.673  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.673  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.673  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.673  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.674  6629  6700 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-11 11:56:06.674  6629  6700 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-11 11:56:06.674  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-11 11:56:06.674  6629  6700 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-11 11:56:06.674  6629  6700 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-11 11:56:06.674  6629  6700 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-11 11:56:06.675  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-11 11:56:06.675  6629  6700 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-11 11:56:06.675  6629  6700 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-11 11:56:06.675  6629  6700 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-11 11:56:06.675  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-11 11:56:06.675  6629  6700 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-11 11:56:06.675  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.675  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.675  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.675  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.675  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.676  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.676  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.676  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.676  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.676  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.676  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.676  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.676  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.676  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.676  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.676  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.677  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.677  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.677  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.677  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.677  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.677  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.677  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.677  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.677  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.677  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.677  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.677  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.678  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.679  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.679  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.679  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.679  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.679  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.679  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.679  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.679  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.679  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.679  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.679  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.679  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.679  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.679  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.679  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.679  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.679  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.679  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.679  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.679  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.680  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.680  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.681  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.681  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.681  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.681  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.682  6629  6700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-11 11:56:06.682  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:06.685  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-11 11:56:06.686  6629  6700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-11 11:56:06.686  6629  6700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-11 11:56:06.687  6629  6629 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-11 11:56:06.687  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-11 11:56:06.687  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-11 11:56:06.688  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.688  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-11 11:56:06.688  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-11 11:56:06.688  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-11 11:56:06.688  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.688  6629  6700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-11 11:56:06.688  6629  6629 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-11 11:56:06.688  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.688  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.688  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:06.688  6629  6700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:06.688  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-11 11:56:06.689  6629  6840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-11 11:56:06.689  6629  6840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-11 11:56:06.690  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-11 11:56:06.694  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:06.694  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:06.694  6629  6700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:06.694  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.694  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.696  6629  6700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:06.696  6629  6629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:06.696  6629  6629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:06.696  6629  6629 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-11 11:56:06.696  6629  6629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:06.696  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.697  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.697  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.697  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.697  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.697  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.697  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.697  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.697  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.697  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.697  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.697  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.697  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.697  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.697  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.698  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.698  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.698  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.698  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.698  6629  6700 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-11 11:56:06.699  6629  6700 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-11 11:56:06.699  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-11 11:56:06.700  6629  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-11 11:56:06.700  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.700  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.700  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.700  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.700  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.700  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.700  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.700  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.700  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.700  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.700  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.700  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.700  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.700  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.701  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.701  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.701  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.701  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.702  1031  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:06.702  1031  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:06.703  1031  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:06.703  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.703  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.703  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.703  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.704  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.704  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.704  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.704  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.704  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.704  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.704  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.704  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.704  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.704  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.705  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.705  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.705  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.705  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.705  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.705  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.705  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.705  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.705  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.706  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.706  6629  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180d62ae not in the list
09-11 11:56:06.706  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.706  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.706  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.706  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.706  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.706  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.706  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.706  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.706  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.706  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.706  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1258384f not in the list
09-11 11:56:06.707  6629  6700 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-11 11:56:06.707  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-11 11:56:06.707  6629  6700 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-11 11:56:06.707  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-11 11:56:06.707  6629  6700 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-11 11:56:06.707  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-11 11:56:06.709  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-11 11:56:06.709  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-11 11:56:06.709  6629  6700 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-11 11:56:06.709  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-11 11:56:06.709  6629  6700 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-11 11:56:06.709  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-11 11:56:06.709  6629  6700 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-11 11:56:06.709  6629  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-11 11:56:06.710  6629  6700 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-11 11:56:06.710  6629  6700 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-11 11:56:06.710  6629  6700 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-11 11:56:06.710  6629  6700 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-11 11:56:06.711  6629  6700 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-11 11:56:06.711  6629  6700 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-11 11:56:06.711  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:06.711  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27482a74 added. We now have 2 listener(s)
09-11 11:56:06.711  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:06.715  6629  6700 D BluetoothAdapter: enable(): BT is already enabled..!
09-11 11:56:06.717  1031  1873 D WifiServiceImplEx: setWifiEnabled: true pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-11 11:56:06.717  1031  1873 D WifiService: setWifiEnabled: true pid=6629, uid=10118
09-11 11:56:06.717  1031  1873 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-11 11:56:06.718  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:06.718  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@619b9d added. We now have 3 listener(s)
09-11 11:56:06.718  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:06.721  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:06.721  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f674812 added. We now have 4 listener(s)
09-11 11:56:06.721  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:06.722  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:06.722  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26db5be3 added. We now have 5 listener(s)
09-11 11:56:06.722  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:06.724  1031  1983 D WifiServiceImplEx: setWifiEnabled: false pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-11 11:56:06.724  1031  1983 D WifiService: setWifiEnabled: false pid=6629, uid=10118
09-11 11:56:06.724  1031  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-11 11:56:06.733  1031  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:06.733  1031  1964 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3cc69fbb mBinding = false
09-11 11:56:06.734  1031  1525 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-11 11:56:06.734  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-11 11:56:06.734  1031  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-11 11:56:06.735  1031  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-11 11:56:06.735  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-11 11:56:06.735  1031  1525 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-11 11:56:06.735  1031  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-11 11:56:06.735  1031  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-11 11:56:06.736  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-11 11:56:06.737  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-11 11:56:06.737  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-11 11:56:06.738  1031  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-11 11:56:06.738  1031  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-11 11:56:06.744  1031  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-11 11:56:06.744  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-11 11:56:06.744  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-11 11:56:06.744  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-11 11:56:06.744  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-11 11:56:06.744  2692  2692 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-11 11:56:06.744  1031  1102 D BluetoothManagerService: Message: 2
09-11 11:56:06.744  1031  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.744  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.744  1031  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-11 11:56:06.744  1031  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-11 11:56:06.745  1031  1525 D WifiNative-wlan0: SET ps 1: returned true
09-11 11:56:06.745  1031  1102 D BluetoothManagerService: Sending off request.
09-11 11:56:06.746  1031  2849 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.746  4301  4328 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-11 11:56:06.746  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:06.748   306   890 D CommandListener: Clearing all IP addresses on wlan0
09-11 11:56:06.753  1031  1371 D PowerManagerServiceEx: acquireWakeLockInternal: lock=20282519, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
09-11 11:56:06.759  4301  4403 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-11 11:56:06.759  4301  4403 D BluetoothAdapterProperties: Setting state to 13
09-11 11:56:06.759  4301  4403 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-11 11:56:06.759  4301  4403 D BluetoothAdapterProperties: onBluetoothDisable()
09-11 11:56:06.759  4301  4403 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-11 11:56:06.760  4301  4411 D BluetoothAdapterProperties: Scan Mode:20
09-11 11:56:06.760  4301  4403 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-11 11:56:06.761  4301  4725 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:06.761  4301  4403 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-11 11:56:06.762  4301  4796 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:06.762  4301  4799 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:06.762  4301  4795 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:06.763  4301  4722 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-11 11:56:06.763  4301  4722 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:06.763  4301  4722 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-11 11:56:06.763  4301  4722 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-11 11:56:06.763  4301  4722 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-11 11:56:06.763  4301  4722 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-11 11:56:06.763  4301  4722 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-11 11:56:06.763  4301  4722 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-11 11:56:06.764  1031  1102 D BluetoothManagerService: Message: 60
09-11 11:56:06.764  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-11 11:56:06.764  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-11 11:56:06.765  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.765  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:06.765  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.765  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:06.765  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.765  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.765  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.765  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:06.765  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:06.765  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.765  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular,: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.765  6629  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:06.766  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:06.768  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-11 11:56:06.768  4301  4535 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-11 11:56:06.769  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-11 11:56:06.769  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-11 11:56:06.769  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-11 11:56:06.769  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-11 11:56:06.769  4301  4535 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:06.769  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-11 11:56:06.769  4301  4535 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:06.769  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-11 11:56:06.769  4301  4535 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:06.769  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-11 11:56:06.769  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-11 11:56:06.769  4301  4535 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-11 11:56:06.770  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:06.784  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.784  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:06.784  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.784  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:06.784  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.784  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.784  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.784  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:06.784  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:06.784  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.784  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.785  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:06.793  1031  1098 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6849 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-11 11:56:06.798  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:06.799  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-11 11:56:06.799  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-11 11:56:06.803  1031  1641 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-11 11:56:06.803  1031  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.803  1031  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.803  1031  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-11 11:56:06.803  1031  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.803  1031  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,09-11 11:56:06.806  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.806  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:06.806  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.806  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:06.806  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.806  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.806  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:06.806  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:06.806  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:06.806  4301  4301 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:06.806  4301  4301 D BluetoothMapService: STATE_TURNING_OFF
09-11 11:56:06.806  4301  4301 V BluetoothMapService: Handler(): got msg=4
09-11 11:56:06.806  4301  4301 D BluetoothMapService: MAP Service closeService in
09-11 11:56:06.806  4301  4301 D BluetoothMapMasInstance: MAP Service shutdown
09-11 11:56:06.807  4301  4301 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-11 11:56:06.807  4301  4301 V BluetoothMapService: MAP Service closeService out
09-11 11:56:06.807  4301  4301 V BtOppService: Receiver DISABLED_ACTION 
09-11 11:56:06.807  4301  4301 I BtOppRfcommListener: stopping Accept Thread
09-11 11:56:06.807  4301  4301 V BtOppRfcommListener: close mBtServerSocket
09-11 11:56:06.808  4301  4795 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-11 11:56:06.808  4301  4301 V BtOppRfcommListener: waiting for thread to terminate
09-11 11:56:06.808  4301  4301 V BtOppRfcommListener: done waiting for thread to terminate
09-11 11:56:06.809  6629  6838 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-11 11:56:06.809  6629  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 846)
09-11 11:56:06.809  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.809  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:06.812  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.812  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:06.812  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.812  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:06.812  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.812  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.812  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:06.812  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:06.812  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:06.813  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Ch,ecking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.813  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:06.823  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-11 11:56:06.829  1031  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-11 11:56:06.829  1031  1531 D DSQN    : disableDataServiceNotify
09-11 11:56:06.829  1031  1531 D DSQN    : stop dsqn bin
09-11 11:56:06.830   306  6879 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-11 11:56:06.831  1031  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-11 11:56:06.831  4301  4301 V BtOppService: onDestroy
09-11 11:56:06.831  1031  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-11 11:56:06.833  4301  4301 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-11 11:56:06.833  2570  2570 D [Concierge]Service: onStartCommand(). Type : 9
09-11 11:56:06.835  1031  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:06.835  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-11 11:56:06.835  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:06.835  1031  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:06.835  1031  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:06.836  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:06.836  1031  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:06.836  1031  1525 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-11 11:56:06.836  1031  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:06.836  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:06.836  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:06.837  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-11 11:56:06.837  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:06.837  1031  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:06.837  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-11 11:56:06.838  1031  1524 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.838  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.838  1031  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1817dd15
09-11 11:56:06.839  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:06.839  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:06.839  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-11 11:56:06.839  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
09-11 11:56:06.839  1031  1031 D RttService: SCAN_AVAILABLE : 1
09-11 11:56:06.839  1031  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.840  1031  1524 D LGWifiP2pService: P2pDisablingState
09-11 11:56:06.840  1031  1544 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.840  1031  1524 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.840  4962  6847 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
09-11 11:56:06.840  1031  1524 D LGWifiP2pService: p2p socket connection lost
09-11 11:56:06.840  1031  1524 D LGWifiP2pService: P2pDisabledState
09-11 11:56:06.840  1031  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-11 11:56:06.840  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-11 11:56:06.840  1031  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.840  1031  1524 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.840  2692  2692 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-11 11:56:06.841  1031  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-11 11:56:06.841  1031  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-11 11:56:06.841  1031  1525 D WifiNative-wlan0: SET ps 1: returned true
09-11 11:56:06.841   306   890 D CommandListener: Clearing all IP addresses on wlan0
09-11 11:56:06.842  1031  1525 D WifiNative-p2p0: doBoolean: TERMINATE
09-11 11:56:06.842  1031  1525 D WifiNative-p2p0: TERMINATE: returned true
09-11 11:56:06.842  1031  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-11 11:56:06.842  1031  1525 E WifiStateMachine: useWiFiOffloading() : false
09-11 11:56:06.842  1031  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-11 11:56:06.844  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-11 11:56:06.844  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-11 11:56:06.844  1928  1928 D WfdsService: Wif,iP2pState is changed : false
09-11 11:56:06.845  1928  2275 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-11 11:56:06.845  1928  2275 D WfdsService: Set the WFDS Monitor: false
09-11 11:56:06.845  1928  2275 D WfdsMonitor: WFDS Monitor is stopped
09-11 11:56:06.845  1928  2275 D WfdsService: STATE : WfdsDisabledState - enter
09-11 11:56:06.845  1928  2747 D CtrlSupplicant: Received on exit socket, terminate
09-11 11:56:06.845  1928  2747 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-11 11:56:06.846  1928  2747 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-11 11:56:06.846  1928  2747 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-11 11:56:06.846  1928  2280 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-11 11:56:06.846  1928  2275 W WfdsService: DefaultState - msg [9445378] is not handled
,09-11 11:56:06.850  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-11 11:56:06.853  1031  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-11 11:56:06.853  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:06.853  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:06.853  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:06.853  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:06.853  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-11 11:56:06.854  1031  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:06.854  1031  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-11 11:56:06.854  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-11 11:56:06.854  1031  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-11 11:56:06.854  1031  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-11 11:56:06.854  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-11 11:56:06.855  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:06.855  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:06.855  1031  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.855  1031  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.855  1031  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-11 11:56:06.855  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-11 11:56:06.855  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:06.857  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:06.857  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-11 11:56:06.858  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:06.858  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-11 11:56:06.858  1031  1531 D ConnectivityService: Checking for replacement net,work to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:06.858  1031  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:06.858  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:06.858  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-11 11:56:06.858  1031  1525 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:06.858  1031  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:06.867  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:06.867  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:06.868  1031  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,09-11 11:56:06.868  1031  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-11 11:56:06.869  1031  1531 D NetworkManagementService: Removing idletimer
09-11 11:56:06.870  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:06.870  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-11 11:56:06.870  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.870  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:06.870  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.870  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:06.870  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:06.870  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.870  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:06.870  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:06.870  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:06.870  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-11 11:56:06.870  1031  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:06.871  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-11 11:56:06.871  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-11 11:56:06.871  1031  1531 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-11 11:56:06.871  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-11 11:56:06.871  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-11 11:56:06.871  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.871  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-11 11:56:06.871  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:06.871  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-11 11:56:06.871  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-11 11:56:06.871  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:06.875  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.875  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:06.875  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Dire,ct supported: true
09-11 11:56:06.875  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:06.875  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:06.875  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.875  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:06.875  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:06.875  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:06.875  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.875  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:06.881  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-11 11:56:06.881  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-11 11:56:06.883  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:06.884  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-11 11:56:06.896  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-11 11:56:06.897  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:06.897  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-11 11:56:06.908  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-11 11:56:06.909  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:06.909  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:06.920  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=20282519 [*alarm*], flags=0x0
09-11 11:56:06.920  2692  2692 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-11 11:56:06.920  2692  2692 I wpa_supplicant: monitor socket send errors count : 1
09-11 11:56:06.920  2692  2692 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-2\x00 that cannot receive messages
,09-11 11:56:06.921  1031  2709 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-11 11:56:06.921  1031  2709 D WifiMonitor: Dropping event because (p2p0) is stopped
09-11 11:56:06.954  1031  1891 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6888 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-11 11:56:06.958  1031  2849 D DhcpStateMachine: StoppedState
09-11 11:56:06.958  1031  2849 D DhcpStateMachine: StoppedState{ when=-117ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.958  1031  1525 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-11 11:56:06.959  1031  1525 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-11 11:56:06.959  6849  6849 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-11 11:56:06.959  6849  6849 W LG Account v2.2: No ProfileInfo entries
09-11 11:56:06.959  6849  6849 I LG Account v2.2: isEnabled: false
09-11 11:56:06.960  6849  6849 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-11 11:56:06.960  6849  6849 I Feature : [Lifetracker]Country: EU
09-11 11:56:06.960  6849  6849 I Feature : [Lifetracker]Operator: OPEN
09-11 11:56:06.960  6849  6849 I Feature : [Lifetracker]Ranking support: false
09-11 11:56:06.960  6849  6849 I Feature : [Lifetracker]Comfort support: false
09-11 11:56:06.960  6849  6849 I Feature : [Lifetracker]Accessory: true
09-11 11:56:06.960  6849  6849 I Feature : [Lifetracker]Health device: true
09-11 11:56:06.960  6849  6849 I Feature : [Lifetracker]Extra Pedometer: false
09-11 11:56:06.960  6849  6849 I Feature : [Lifetracker]Blood glucose device: false
09-11 11:56:06.960  6849  6849 I Feature : [Lifetracker]Device Number: 3
09-11 11:56:06.969  2692  2692 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-11 11:56:06.970  2692  2692 W wpa_supplicant: USIM:  scard_deinit function
09-11 11:56:06.970  1031  2709 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-11 11:56:06.970  1031  2709 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-11 11:56:06.970  1031  2709 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-11 11:56:06.971  1031  2709 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-11 11:56:06.971  1031  2709 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-11 11:56:06.971  1031  2709 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-11 11:56:06.972  1031  1525 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=114430
09-11 11:56:06.972  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:06.972  1031  1102 D Tethering: InitialState.processMessage what=4
09-11 11:56:06.972  1031  1525 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=114430
09-11 11:56:06.972  1031  1525 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=114430  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-11 11:56:06.973  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-11 11:56:06.973  1031  1525 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=114431  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-11 11:56:06.973  1031  1525 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:06.973  1031  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-11 11:56:07.013  1031  1946 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6906 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-11 11:56:07.017  1031  1946 I ActivityManager: Killing 6260:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-11 11:56:07.045  2692  2692 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-11 11:56:07.045  1031  2709 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-11 11:56:07.045  1031  2709 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-11 11:56:07.045  1031  2709 D WifiMonitor: Disconnecting from the supplicant, no more events
09-11 11:56:07.046  1031  1525 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-11 11:56:07.048  1031  1562 W libprocessgroup: failed to open /acct/uid_10014/pid_6260/cgroup.procs: No such file or directory
09-11 11:56:07.066  6888  6888 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-11 11:56:07.066  6888  6888 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-11 11:56:07.066  6888  6888 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-11 11:56:07.067  6888  6888 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,09-11 11:56:07.068  6888  6888 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-11 11:56:07.069  6888  6888 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-11 11:56:07.092  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-11 11:56:07.100  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-11 11:56:07.101  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:07.102  1031  1641 I ActivityManager: Killing 6343:com.android.defcontainer/u0a4 (adj 15): empty #17
09-11 11:56:07.131  1031  1946 W libprocessgroup: failed to open /acct/uid_10004/pid_6343/cgroup.procs: No such file or directory
,09-11 11:56:07.147  1031  1525 D WifiOffDelayIfNotUsed: stopMonitoring
09-11 11:56:07.147  1031  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-11 11:56:07.147  1031  1525 E WifiStateMachine: useWiFiOffloading() : false
09-11 11:56:07.147  1031  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-11 11:56:07.147  1928  1928 D WfdsService: Supplicant Connection state is changed : false
09-11 11:56:07.148  1928  2275 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,09-11 11:56:07.148  1928  2275 D WfdsService: Set the WFDS Monitor: false
09-11 11:56:07.148  1928  2275 D WfdsMonitor: WFDS Monitor is stopped
09-11 11:56:07.149  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:07.149  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-11 11:56:07.151  2489  2489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:07.152  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-11 11:56:07.152  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-11 11:56:07.153  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-11 11:56:07.154  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:07.154  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:07.154  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:07.154  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:07.154  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:07.154  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:07.154  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:07.154  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:07.154  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:07.154  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:07.180  6888  6888 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-11 11:56:07.185  4301  4301 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-11 11:56:07.185  4301  4301 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:07.185  4301  4301 V BluetoothPbapReceiver: ***********state = 13
,09-11 11:56:07.187  4301  4301 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-11 11:56:07.188  4301  4301 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:07.188  4301  4301 V BluetoothPbapService: state: 13
09-11 11:56:07.188  4301  4301 V BluetoothPbapService: Pbap Service closeService in
09-11 11:56:07.189  4301  4301 V BluetoothPbapService: successfully stopped pbap service
09-11 11:56:07.189  4301  4301 V BluetoothPbapService: Pbap Service closeService out
09-11 11:56:07.189  2167  2167 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-11 11:56:07.189  4301  4301 V BluetoothPbapService: Pbap Service onDestroy
09-11 11:56:07.189  4301  4301 V BluetoothPbapService: Pbap Service closeService in
09-11 11:56:07.189  4301  4301 V BluetoothPbapService: Pbap Service closeService out
09-11 11:56:07.189  4301  4301 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-11 11:56:07.197  6629  6629 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-11 11:56:07.200  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-11 11:56:07.234  6888  6888 D LgDataFeature: LgDataFeature() Constructor: none
09-11 11:56:07.234  6888  6888 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-11 11:56:07.246  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:07.257  1031  1102 D BluetoothManagerService: Message: 20
09-11 11:56:07.257  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14b4b33:true
,09-11 11:56:07.269  1031  1102 D BluetoothManagerService: Message: 30,
,09-11 11:56:07.277  1031  1102 D BluetoothManagerService: Message: 30
09-11 11:56:07.281  6888  6888 D LocalBluetoothProfileManager: Adding local MAP profile
09-11 11:56:07.282  6888  6888 D BluetoothMap: Create BluetoothMap proxy object
09-11 11:56:07.283  1031  1102 D BluetoothManagerService: Message: 30
,09-11 11:56:07.288  1031  1102 D BluetoothManagerService: Message: 30
,09-11 11:56:07.291  6888  6888 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-11 11:56:07.292  6888  6888 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-11 11:56:07.308  6888  6888 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-11 11:56:07.312  6888  6888 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,09-11 11:56:07.332  6888  6888 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:07.344  6888  6888 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-11 11:56:07.349  6888  6888 D BluetoothInputDevice: Proxy object connected
09-11 11:56:07.350  6888  6888 D HidProfile: Bluetooth service connected
09-11 11:56:07.351  6888  6888 D BluetoothPan: BluetoothPAN Proxy object connected
09-11 11:56:07.352  6888  6888 D PanProfile: Bluetooth service connected
09-11 11:56:07.352  6888  6888 D BluetoothMap: Proxy object connected
09-11 11:56:07.353  6888  6888 D MapProfile: Bluetooth service connected
09-11 11:56:07.353  6888  6888 D BluetoothMap: getConnectedDevices()
09-11 11:56:07.354  6888  6888 D BluetoothMap: Bluetooth is Not enabled
09-11 11:56:07.354  6888  6888 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-11 11:56:07.356  6888  6888 D BluetoothPermissionRequest: onReceive
09-11 11:56:07.360  6888  6888 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-11 11:56:07.370  1031  1760 I ActivityManager: Killing 6468:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-11 11:56:07.370  6888  6888 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-11 11:56:07.444  4301  4301 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-11 11:56:07.444  4301  4301 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-11 11:56:07.445  1031  1945 W libprocessgroup: failed to open /acct/uid_10008/pid_6468/cgroup.procs: No such file or directory
09-11 11:56:07.446  4301  4301 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-11 11:56:07.520  1031  1641 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6940 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-11 11:56:07.521  4301  4301 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:07.521  4301  4301 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-11 11:56:07.527  4301  4301 V BluetoothFtpService: Ftp Service onStartCommand
09-11 11:56:07.527  4301  4301 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:07.528  4301  4301 V BluetoothFtpService: Ftp Service closeService
09-11 11:56:07.528  4301  4301 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-11 11:56:07.532  4301  4301 V BluetoothFtpService: successfully stopped ftp service
09-11 11:56:07.532  4301  4301 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-11 11:56:07.532  4301  4301 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-11 11:56:07.532  4301  4301 V BluetoothSapReceiver: SapReceiver onReceive 
09-11 11:56:07.532  4301  4301 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:07.533  4301  4301 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-11 11:56:07.533  4301  4301 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-11 11:56:07.537  4301  4301 V BluetoothFtpService: Ftp Service onDestroy
09-11 11:56:07.537  4301  4301 V BluetoothFtpService: Ftp Service closeService
09-11 11:56:07.587  1031  1945 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6957 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-11 11:56:07.589  4301  4301 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:07.589  4301  4301 V BluetoothSapService: state: 13
09-11 11:56:07.589  4301  4301 V BluetoothSapService: Stopping SAP server process
09-11 11:56:07.590  4301  4301 V BluetoothSapService: Sap Service closeSapService in
09-11 11:56:07.590  4301  4301 V BluetoothSapService: Close listen Socket : 
09-11 11:56:07.590  4301  4301 V BluetoothSapService: Close rfcomm Socket : 
09-11 11:56:07.591  4301  4301 V BluetoothSapService: Close sapd  Socket : 
09-11 11:56:07.592  4301  4301 V BluetoothSapService: Sap Service closeSapService out
09-11 11:56:07.592  4301  4301 V BluetoothSapService: Sap Service onDestroy
09-11 11:56:07.592  4301  4301 V BluetoothSapService: Sap Service closeSapService in
09-11 11:56:07.592  4301  4301 V BluetoothSapService: Close listen Socket : 
09-11 11:56:07.592  4301  4301 V BluetoothSapService: Close rfcomm Socket : 
09-11 11:56:07.592  4301  4301 V BluetoothSapService: Close sapd  Socket : 
09-11 11:56:07.594  4301  4301 V BluetoothSapService: Sap Service closeSapService out
,09-11 11:56:07.643  6940  6940 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-11 11:56:07.655  6957  6957 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-11 11:56:07.668  6940  6940 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-11 11:56:07.671  1031  1048 I ActivityManager: Killing 6513:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-11 11:56:07.778  4301  4411 D bt_hci_bdroid: cleanup
09-11 11:56:07.779  4301  4537 I bt_lpm  : LPM is already off!!!
09-11 11:56:07.779  4301  4711 I bt_userial_mct: exiting userial_read_thread
09-11 11:56:07.779  4301  4711 D bt_userial_mct: Leaving userial_evt_read_thread()
09-11 11:56:07.780  4301  4535 W bt-btif : ag scb idx 1 not allocated
09-11 11:56:07.780  4301  4535 E bt-btif : BTA AG is already disabled, ignoring ...
09-11 11:56:07.780  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-11 11:56:07.780  4301  4535 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:07.780  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-11 11:56:07.780  4301  4535 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:07.780  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-11 11:56:07.780  4301  4535 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-11 11:56:07.781  4301  4535 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:07.781  4301  4535 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-11 11:56:07.785  4301  4411 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-11 11:56:07.785  4301  4537 I bt_vendor: hw_epilog_process
09-11 11:56:07.786  4301  4411 D bt_hci_bdroid: cleanup Finalizing cleanup
09-11 11:56:07.786  4301  4411 D bt_userial_mct: userial_close
09-11 11:56:07.786  4301  4411 E bt_userial_mct: pthread_join() FAILED result:3
09-11 11:56:07.786  4301  4411 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-11 11:56:07.793  1031  1641 W libprocessgroup: failed to open /acct/uid_10011/pid_6513/cgroup.procs: No such file or directory
09-11 11:56:07.832  6940  6940 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-11 11:56:07.832  6940  6940 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-11 11:56:07.833  6940  6940 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-11 11:56:07.833  6940  6940 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-11 11:56:07.833  6940  6940 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-11 11:56:07.835  6940  6940 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-11 11:56:07.842  6940  6940 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-11 11:56:07.850  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:07.854  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:07.869  4301  4411 D bt_hci_bdroid: set_power 0
09-11 11:56:07.869  4301  4411 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-11 11:56:07.869  4301  4411 I bt_vendor: bluetooth satus is on
09-11 11:56:07.869  4301  4411 I bt_vendor: bt-vendor : resetting BT status
09-11 11:56:07.869  4301  4411 I bt_vendor: Starting hciattach daemon
09-11 11:56:07.869  4301  4411 I bt_vendor: try to set false
,09-11 11:56:07.871  4301  4411 I bt_vendor: Starting hciattach daemon
09-11 11:56:07.871  4301  4411 I bt_vendor: try to set false
09-11 11:56:07.873  4301  4411 I bt_vendor: cleanup
09-11 11:56:07.879  4301  4535 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-11 11:56:07.886  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-11 11:56:07.891  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:07.894  4301  4411 I GKI_LINUX: GKI_exit_task 0 done
09-11 11:56:07.894  4301  4411 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-11 11:56:07.896  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-11 11:56:07.896  4301  4403 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-11 11:56:07.896  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-11 11:56:07.897  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:07.898  6940  6940 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-11 11:56:07.901  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:07.903  4301  4301 D HeadsetService: Received stop request...Stopping profile...
09-11 11:56:07.906  6940  6940 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-11 11:56:07.906  4301  4301 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-11 11:56:07.907  4301  4301 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-11 11:56:07.907  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32e6bbac
09-11 11:56:07.907  4301  4466 D HeadsetStateMachine: Exit Disconnected: -1
09-11 11:56:07.909  4301  4301 D A2dpService: Received stop request...Stopping profile...
09-11 11:56:07.909  4301  4513 D A2dpStateMachine: Exit Disconnected: -1
09-11 11:56:07.909  1031  1031 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:07.909  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-11 11:56:07.910  4301  4301 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-11 11:56:07.910  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:07.910  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:07.910  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:07.911  4301  4301 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-11 11:56:07.911  4301  4301 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-11 11:56:07.911  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32e6bbac
09-11 11:56:07.913  1031  1031 D BluetoothA2dp: Proxy object disconnected
09-11 11:56:07.913  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-11 11:56:07.913  4301  4301 D HidService: Received stop request...Stopping profile...
09-11 11:56:07.913  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32e6bbac
,09-11 11:56:07.919  4301  4403 D BluetoothAdapterState: Stopping profile services that were post enabled
09-11 11:56:07.921  4301  4301 D HealthService: Received stop request...Stopping profile...
09-11 11:56:07.922  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32e6bbac
09-11 11:56:07.923  4301  4301 D HeadsetStateMachine: Unbinding service...
09-11 11:56:07.924  4301  4301 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-11 11:56:07.924  4301  4301 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-11 11:56:07.924  4301  4301 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-11 11:56:07.924  4301  4301 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-11 11:56:07.924  4301  4301 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-11 11:56:07.924  4301  4301 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-11 11:56:07.924  4301  4301 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-11 11:56:07.925  4301  4301 D PanService: Received stop request...Stopping profile...
09-11 11:56:07.926  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32e6bbac
,09-11 11:56:07.926  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:07.927  6888  6888 D BluetoothInputDevice: Proxy object disconnected
09-11 11:56:07.927  6888  6888 D HidProfile: Bluetooth service disconnected
09-11 11:56:07.928  4301  4301 D BtGatt.DebugUtils: handleDebugAction() action=null
09-11 11:56:07.928  4301  4301 D BtGatt.GattService: Received stop request...Stopping profile...
09-11 11:56:07.929  4301  4301 D BtGatt.GattService: stop()
09-11 11:56:07.929  4301  4301 D BtGatt.AdvertiseManager: advertise clients cleared
09-11 11:56:07.930  6888  6888 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-11 11:56:07.930  6888  6888 D PanProfile: Bluetooth service disconnected
09-11 11:56:07.930  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32e6bbac
09-11 11:56:07.931  4301  4301 I BluetoothA2dpServiceJni: cleanupNative
,09-11 11:56:07.931  4301  4514 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-11 11:56:07.932  4301  4301 I GKI_LINUX: GKI_exit_task 2 done
09-11 11:56:07.932  4301  4301 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-11 11:56:07.933  4301  4301 D BluetoothMapService: Received stop request...Stopping profile...
09-11 11:56:07.933  4301  4301 D BluetoothMapService: stop()
09-11 11:56:07.933  4301  4301 D BluetoothMapEmailAppObserver: deinitObservers()
09-11 11:56:07.934  4301  4301 D BluetoothMapEmailAppObserver: removeReceiver()
09-11 11:56:07.934  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32e6bbac
09-11 11:56:07.935  4301  4301 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-11 11:56:07.935  4301  4301 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-11 11:56:07.935  4301  4301 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-11 11:56:07.935  4301  4301 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-11 11:56:07.935  4301  4301 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-11 11:56:07.936  4301  4301 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-11 11:56:07.936  4301  4301 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-11 11:56:07.937  6888  6888 D BluetoothMap: Proxy object disconnected
09-11 11:56:07.937  6888  6888 D MapProfile: Bluetooth service disconnected
09-11 11:56:07.937  4301  4301 V BluetoothMapService: Handler(): got msg=4
09-11 11:56:07.937  4301  4301 D BluetoothMapService: MAP Service closeService in
09-11 11:56:07.937  4301  4301 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-11 11:56:07.937  4301  4301 V BluetoothMapService: MAP Service closeService out
09-11 11:56:07.938  4301  4301 D BluetoothMapService: cleanup()
,09-11 11:56:07.938  4301  4301 D BluetoothMapService: MAP Service closeService in
09-11 11:56:07.938  4301  4301 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-11 11:56:07.939  4301  4403 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-11 11:56:07.939  4301  4403 D BluetoothAdapterProperties: Setting state to 10
09-11 11:56:07.939  4301  4403 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-11 11:56:07.939  1031  1102 D BluetoothManagerService: Message: 60
09-11 11:56:07.939  4301  4403 I BluetoothAdapterState: Entering OffState
09-11 11:56:07.939  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-11 11:56:07.940  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-11 11:56:07.940  4301  4301 V BluetoothMapService: MAP Service closeService out
09-11 11:56:07.941  1839  3424 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:07.942  1839  3425 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:07.942  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:07.943  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:07.944  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-11 11:56:07.944  6888  6905 D BluetoothMap: onBluetoothStateChange: up=false
09-11 11:56:07.945  6888  6904 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-11 11:56:07.946  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:07.949  6888  6993 D BluetoothPan: onBluetoothStateChange on: false
09-11 11:56:07.949  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:07.951  6888  6905 D BluetoothPbap: onBluetoothStateChange: up=false
09-11 11:56:07.955  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-11 11:56:07.955  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-11 11:56:07.955  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:07.955  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-11 11:56:07.955  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:07.961  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:07.964  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-11 11:56:07.964  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-11 11:56:07.968  1031  1102 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-11 11:56:07.968  1031  1102 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-11 11:56:07.969  1031  1102 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3cc69fbb mBinding = false
09-11 11:56:07.970  1031  1102 D BluetoothManagerService: Sending unbind request.
09-11 11:56:07.970  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:07.972  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-11 11:56:07.978  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:07.980  1928  2115 D LGBluetoothAPIService: Message: 2
09-11 11:56:07.980  1928  2115 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@c8e59ef mBinding = false
09-11 11:56:07.980  1928  2115 D LGBluetoothAPIService: Sending unbind request.
09-11 11:56:07.981  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:07.982  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:07.983  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-11 11:56:07.985  4301  4411 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-11 11:56:07.986  4301  4301 I GKI_LINUX: GKI_exit_task 1 done
09-11 11:56:07.986  4301  4301 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-11 11:56:07.986  4301  4301 I BluetoothServiceJni: cleanupNative: return from cleanup
09-11 11:56:07.987  4301  4301 I art     : --- WEIRD: removing null entry 246
09-11 11:56:07.987  4301  4301 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-11 11:56:07.988  4301  4301 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-11 11:56:07.988  4301  4301 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-11 11:56:07.989  6888  6888 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-11 11:56:07.991  4301  4301 I art     : System.exit called, status: 0
09-11 11:56:07.991  6888  6888 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-11 11:56:07.991  4301  4301 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-11 11:56:07.991  6888  6888 D LGBluetoothEventManager: [BTUI] clear device connection state
09-11 11:56:07.997  1588  1588 D BluetoothAdapter: 738293956: getState() :  mService = null. Returning STATE_OFF
09-11 11:56:07.997  1588  1588 D BluetoothAdapter: 738293956: getState() :  mService = null. Returning STATE_OFF
09-11 11:56:07.999  6888  6888 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-11 11:56:08.016  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:08.016  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:08.017  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-11 11:56:08.020   311  1369 V AudioFlinger: 4301 died, releasing its sessions
,09-11 11:56:08.020   311  1369 V AudioFlinger:  pid 1839 @ 0
09-11 11:56:08.020   311  1369 V AudioFlinger:  pid 3288 @ 1
09-11 11:56:08.020   311  1369 V AudioFlinger:  pid 3288 @ 2
09-11 11:56:08.082  1031  1927 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7000 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-11 11:56:08.084  6888  6888 D DockEventReceiver: finishStartingService: stopping service
09-11 11:56:08.085  6888  6888 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-11 11:56:08.119  1031  2000 I ActivityManager: Process com.android.bluetooth (pid 4301) has died
09-11 11:56:08.120  1031  2000 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-11 11:56:08.130  2167  2167 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:08.160  6888  6888 D BluetoothPermissionRequest: onReceive
09-11 11:56:08.164  6888  6888 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-11 11:56:08.165  6888  6888 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-11 11:56:08.172  6888  6888 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-11 11:56:08.245  1031  1760 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7017 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-11 11:56:08.267  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-11 11:56:08.279  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:08.287  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-11 11:56:08.320  7017  7017 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-11 11:56:08.321  7017  7017 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-11 11:56:08.321  7017  7017 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-11 11:56:08.322  7017  7017 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-11 11:56:08.322  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:08.322  6888  6888 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-11 11:56:08.322  6888  6888 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-11 11:56:08.323  6888  6888 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-11 11:56:08.328  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-11 11:56:08.332  7000  7039 W FormManager: Network not available. Please check & try again.
09-11 11:56:08.338  6888  6888 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,09-11 11:56:08.340  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-11 11:56:08.341  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-11 11:56:08.341  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-11 11:56:08.341  6888  6888 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-11 11:56:08.341  6888  6888 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-11 11:56:08.345  7017  7017 D BluetoothAdapterApp: Loading JNI Library
09-11 11:56:08.348  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-11 11:56:08.348  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-11 11:56:08.350  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-11 11:56:08.360  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-11 11:56:08.370  7000  7041 V FormManager: Network unavailable.
,09-11 11:56:08.373  7000  7041 V FormManager: Network unavailable.
09-11 11:56:08.379  4807  7050 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-11 11:56:08.380  4807  7048 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-11 11:56:08.383  6906  6906 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-11 11:56:08.384  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-11 11:56:08.384  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:08.384  7017  7017 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@247836bd Instance Count = 1
09-11 11:56:08.385  4807  7050 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-11 11:56:08.386  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:08.391  7017  7017 D BluetoothAdapterApp: onCreate
09-11 11:56:08.395  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:08.400  7000  7052 W FormManager: Network not available. Please check & try again.
,09-11 11:56:08.407  7000  7053 V FormManager: Network unavailable.
09-11 11:56:08.410  7000  7053 V FormManager: Network unavailable.
09-11 11:56:08.414  7017  7017 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-11 11:56:08.414  7017  7017 D ProfileConfigQcom: Adding HeadsetService
,09-11 11:56:08.414  7017  7017 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-11 11:56:08.415  7017  7017 D ProfileConfigQcom: Adding A2dpService
09-11 11:56:08.415  7017  7017 D ProfileConfigQcom: [BTUI] HidService is supported
09-11 11:56:08.415  7017  7017 D ProfileConfigQcom: Adding HidService
09-11 11:56:08.416  7017  7017 D ProfileConfigQcom: [BTUI] HealthService is supported
09-11 11:56:08.416  7017  7017 D ProfileConfigQcom: Adding HealthService
09-11 11:56:08.416  7017  7017 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-11 11:56:08.417  7017  7017 D ProfileConfigQcom: [BTUI] PanService is supported
09-11 11:56:08.417  7017  7017 D ProfileConfigQcom: Adding PanService
09-11 11:56:08.417  6940  6940 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-11 11:56:08.417  1031  1873 I ActivityManager: Killing 6045:com.android.contacts/u0a19 (adj 15): empty #17
09-11 11:56:08.418  7017  7017 D ProfileConfigQcom: [BTUI] GattService is supported
09-11 11:56:08.418  7017  7017 D ProfileConfigQcom: Adding GattService
09-11 11:56:08.418  7017  7017 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-11 11:56:08.418  7017  7017 D ProfileConfigQcom: Adding BluetoothMapService
09-11 11:56:08.419  7017  7017 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-11 11:56:08.419  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-11 11:56:08.420  6940  6940 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-11 11:56:08.420  7017  7017 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-11 11:56:08.457  6940  6940 D LgDataFeature: LgDataFeature() Constructor: none
09-11 11:56:08.457  6940  6940 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-11 11:56:08.466  6940  6940 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,09-11 11:56:08.467  6940  6940 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
,09-11 11:56:08.467  6940  6940 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
,09-11 11:56:08.467  6940  6940 V SoundPool: doLoad: loading sample sampleID=1
,09-11 11:56:08.468  6940  6940 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-11 11:56:08.470  6940  7057 V SoundPool: Start decode
09-11 11:56:08.471  6940  7057 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,09-11 11:56:08.472   311  1369 V MediaPlayerService: decode(22, 10857164, 17813)
09-11 11:56:08.472   311  1369 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-11 11:56:08.473   311  1369 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-11 11:56:08.473   311  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-11 11:56:08.473   311  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-11 11:56:08.473   311  1369 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-11 11:56:08.473   311  1369 V MediaPlayerService: player type = 3
09-11 11:56:08.473   311  1369 V AwesomePlayer: AwesomePlayer create()
09-11 11:56:08.474   311  1369 V AwesomePlayer: reset_l() 
09-11 11:56:08.474   311  1369 V AwesomePlayer: cancelPlayerEvents
,09-11 11:56:08.474   311  1369 V AwesomePlayer: setAudioSink() 
09-11 11:56:08.474   311  1369 V AwesomePlayer: reset_l() 
09-11 11:56:08.474   311  1369 V AudioCache: notify(0xb5474980, 8, 0, 0)
,09-11 11:56:08.474   311  1369 V AudioCache: ignored
09-11 11:56:08.474   311  1369 V AwesomePlayer: cancelPlayerEvents
09-11 11:56:08.475   311  1369 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-11 11:56:08.475   311  1369 V AwesomePlayer: setDataSource_l dataSource
,09-11 11:56:08.475   311  1369 V LGParserOSAL: SniffLGParser start
,09-11 11:56:08.475   311  1369 V LGParserOSAL: MainType:5, SubType=0
09-11 11:56:08.475   311  1369 V LGParserOSAL: #### check Mime : application/ogg
09-11 11:56:08.475   311  1369 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-11 11:56:08.475   311  1369 E MediaExtractor: Use LGExtractor :application/ogg 
09-11 11:56:08.504  6806  6806 D UEI.SmartControl: QS Service created
,09-11 11:56:08.505  1031  1049 W libprocessgroup: failed to open /acct/uid_10019/pid_6045/cgroup.procs: No such file or directory
09-11 11:56:08.515  7017  7017 V LGMDMManagerInternal: Create singleton instance
09-11 11:56:08.518  6940  6940 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-11 11:56:08.519  6806  6806 I UEI.SmartControl: Service initServices...
09-11 11:56:08.520  6806  6806 D UEI.SmartControl: QS start get config
09-11 11:56:08.522  6940  6940 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-11 11:56:08.523  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-11 11:56:08.529  6888  6888 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-11 11:56:08.530   311  1369 V LGParserOSAL: supported mime: application/ogg
09-11 11:56:08.530   311  1369 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-11 11:56:08.530   311  1369 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-11 11:56:08.530   311  1369 V AwesomePlayer: mBitrate = -1 bits/sec
09-11 11:56:08.530   311  1369 V AwesomePlayer: AudioTrack Setting
09-11 11:56:08.530   311  1369 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-11 11:56:08.530   311  1369 V AwesomePlayer: setAudioSource() 
09-11 11:56:08.530   311  1369 V MediaPlayerService: prepare
09-11 11:56:08.530   311  1369 V AwesomePlayer: prepareAsync_l() 
09-11 11:56:08.530   311  1369 V MediaPlayerService: wait for prepare
09-11 11:56:08.530   311  7058 V AwesomePlayer: onPrepareAsyncEvent() 
09-11 11:56:08.530   311  7058 V AwesomePlayer: initAudioDecoder() 
09-11 11:56:08.530   311  7058 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-11 11:56:08.530   311  7058 V AudioSystem: isOffloadSupported()
09-11 11:56:08.530   311  7058 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-11 11:56:08.530   311  7058 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-11 11:56:08.530   311  7058 I AudioFlinger: isAudioPlaybackHookOn() false
09-11 11:56:08.530   311  7058 V AwesomePlayer: getUseOffload() = 0 
09-11 11:56:08.530   311  7058 V OMXCodec: OMXCodec::Create
09-11 11:56:08.530   311  7058 V OMXCodec: findMatchingCodecs()
09-11 11:56:08.530   311  7058 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-11 11:56:08.531   311  7058 V OMXCodec: matchingCodecs.size()=1
09-11 11:56:08.531   311  7058 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,09-11 11:56:08.532   311  7058 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-11 11:56:08.532   311  7058 V LGCodecAdapter: LG Codec Adapter start
09-11 11:56:08.532   311  7058 V OMXCodec: OMXCodec Createtor
09-11 11:56:08.532   311  7058 V OMXCodec: setComponentRole
09-11 11:56:08.533   311  7058 V OMXCodec: configureCodec protected=0
09-11 11:56:08.533   311  7058 V LGCodecAdapter: called getLGCodecSpecificData
09-11 11:56:08.533   311  7058 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-11 11:56:08.533   311  7058 V LGCodecOSAL: Called LGconfigureCodecMETA
09-11 11:56:08.533   311  7058 V LGCodecOSAL: Called LGconfigureCodecMSG
09-11 11:56:08.533   311  7058 V LGCodecOSAL: Not support LGCodec
09-11 11:56:08.533   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-11 11:56:08.533   311  7058 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-11 11:56:08.533   311  7058 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-11 11:56:08.533   311  7058 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-11 11:56:08.533   311  7058 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-11 11:56:08.533   311  7058 V AudioSystem: isOffloadSupported()
09-11 11:56:08.533   311  7058 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-11 11:56:08.533   311  7058 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-11 11:56:08.533   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-11 11:56:08.533   311  7058 V OMXCodec: init()
09-11 11:56:08.533   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-11 11:56:08.533   311  7058 V OMXCodec: allocateBuffers
09-11 11:56:08.533   311  7058 V OMXCodec: allocateBuffersOnPort portIndex=0
09-11 11:56:08.533   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-11 11:56:08.535   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
09-11 11:56:08.535   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c01f0 on input port
09-11 11:56:08.535   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0240 on input port
09-11 11:56:08.535   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c08d0 on input port
09-11 11:56:08.535   311  7058 V OMXCodec: allocateBuffersOnPort portIndex=1
09-11 11:56:08.535   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-11 11:56:08.535   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0920 on output port
09-11 11:56:08.535   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0d80 on output port
09-11 11:56:08.536   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb16a0470 on output port
09-11 11:56:08.536   311  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb16a04c0 on output port
09-11 11:56:08.536   311  7058 V OMXCodec: init() mAsyncCompletion wait!!! 
09-11 11:56:08.536   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-11 11:56:08.536   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-11 11:56:08.536   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-11 11:56:08.536   311  7058 V OMXCodec: init() mAsyncCompletion wait!!! 
09-11 11:56:08.536   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-11 11:56:08.536   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-11 11:56:08.536   31,1  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-11 11:56:08.537   311  7058 V OMXCodec: init() mAsyncCompletion wait free! 
09-11 11:56:08.537   311  7058 V AwesomePlayer: finishAsyncPrepare_l() 
09-11 11:56:08.537   311  7058 V AudioCache: notify(0xb5474980, 5, 0, 0)
09-11 11:56:08.537   311  7058 V AudioCache: ignored
09-11 11:56:08.537   311  7058 V AudioCache: notify(0xb5474980, 1, 0, 0)
09-11 11:56:08.537   311  7058 V AudioCache: prepared
09-11 11:56:08.537   311  1369 V AudioCache: wait - success
09-11 11:56:08.537   311  1369 V MediaPlayerService: start
09-11 11:56:08.537   311  1369 V AwesomePlayer: play_l() 
09-11 11:56:08.537   311  1369 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-11 11:56:08.537   311  1369 V AwesomePlayer: createAudioPlayer_l
09-11 11:56:08.537   311  1369 V AwesomePlayer: seekAudioIfNecessary_l() 
09-11 11:56:08.537   311  1369 V AwesomePlayer: startAudioPlayer_l() 
09-11 11:56:08.537   311  1369 D AudioPlayer: start of Playback, useOffload 0
09-11 11:56:08.537   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-11 11:56:08.537   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-11 11:56:08.539   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-11 11:56:08.539   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-11 11:56:08.539   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-11 11:56:08.539   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-11 11:56:08.539   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-11 11:56:08.539   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-11 11:56:08.539   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974550304
09-11 11:56:08.539   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-11 11:56:08.540   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974551424
09-11 11:56:08.540   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-11 11:56:08.540   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2976515184
,09-11 11:56:08.540   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-11 11:56:08.540   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2976515264
09-11 11:56:08.540   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-11 11:56:08.540   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-11 11:56:08.540   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-11 11:56:08.540   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-11 11:56:08.540   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-11 11:56:08.540   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-11 11:56:08.542   311  7060 V OMXCodec: allocateBuffersOnPort portIndex=1
09-11 11:56:08.542   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-11 11:56:08.542   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb16a0470 on output port
09-11 11:56:08.542   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0d80 on output port
,09-11 11:56:08.543   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0920 on output port
09-11 11:56:08.543   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
09-11 11:56:08.543   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-11 11:56:08.543   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-11 11:56:08.544   311  1369 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-11 11:56:08.545   311  1369 V AudioCache: notify(0xb5474980, 6, 0, 0)
09-11 11:56:08.545   311  1369 V AudioCache: ignored
,09-11 11:56:08.545   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.545   311  7061 V AudioCache: memcpy(0xaf104000, 0xb57ff000, 4096)
09-11 11:56:08.546   311  1369 V MediaPlayerService: wait for playback complete
09-11 11:56:08.547   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.547   311  7061 V AudioCache: memcpy(0xaf105000, 0xb57ff000, 4096)
09-11 11:56:08.547   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.547   311  7061 V AudioCache: memcpy(0xaf106000, 0xb57ff000, 4096)
09-11 11:56:08.549   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.549   311  7061 V AudioCache: memcpy(0xaf107000, 0xb57ff000, 4096)
09-11 11:56:08.549   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.549   311  7061 V AudioCache: memcpy(0xaf108000, 0xb57ff000, 4096)
09-11 11:56:08.550   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.550   311  7061 V AudioCache: memcpy(0xaf109000, 0xb57ff000, 4096)
09-11 11:56:08.550   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.550   311  7061 V AudioCache: memcpy(0xaf10a000, 0xb57ff000, 4096)
09-11 11:56:08.551   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.551   311  7061 V AudioCache: memcpy(0xaf10b000, 0xb57ff000, 4096)
09-11 11:56:08.552   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.552   311  7061 V AudioCache: memcpy(0xaf10c000, 0xb57ff000, 4096)
09-11 11:56:08.552   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.552   311  7061 V AudioCache: memcpy(0xaf10d000, 0xb57ff000, 4096)
09-11 11:56:08.553   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.553   311  7061 V AudioCache: memcpy(0xaf10e000, 0xb57ff000, 4096)
09-11 11:56:08.554   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.554   311  7061 V AudioCache: memcpy(0xaf10f000, 0xb57ff000, 4096)
09-11 11:56:08.554  6940  6940 V LGMDMManager: Create singleton instance
09-11 11:56:08.557   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.557   311  7061 V AudioCache: memcpy(0xaf110000, 0xb57ff000, 4096)
09-11 11:56:08.557   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.557   311  7061 V AudioCache: memcpy(0xaf111000, 0xb57ff000, 4096)
09-11 11:56:08.558   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.558   311  7061 V AudioCache: memcpy(0xaf112000, 0xb57ff000, 4096)
09-11 11:56:08.558   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.558   311  7061 V AudioCache: memcpy(0xaf113000, 0xb57ff000, 4096)
,09-11 11:56:08.560   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.560   311  7061 V AudioCache: memcpy(0xaf114000, 0xb57ff000, 4096)
09-11 11:56:08.561   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.561   311  7061 V AudioCache: memcpy(0xaf115000, 0xb57ff000, 4096)
09-11 11:56:08.562   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.562   311  7061 V AudioCache: memcpy(0xaf116000, 0xb57ff000, 4096)
09-11 11:56:08.563   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.563   311  7061 V AudioCache: memcpy(0xaf117000, 0xb57ff000, 4096)
09-11 11:56:08.564   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.564   311  7061 V AudioCache: memcpy(0xaf118000, 0xb57ff000, 4096)
09-11 11:56:08.565   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.565   311  7061 V AudioCache: memcpy(0xaf119000, 0xb57ff000, 4096)
09-11 11:56:08.566   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.566   311  7061 V AudioCache: memcpy(0xaf11a000, 0xb57ff000, 4096)
09-11 11:56:08.567   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.567   311  7061 V AudioCache: memcpy(0xaf11b000, 0xb57ff000, 4096)
09-11 11:56:08.567   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.567   311  7061 V AudioCache: memcpy(0xaf11c000, 0xb57ff000, 4096)
09-11 11:56:08.568   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.568   311  7061 V AudioCache: memcpy(0xaf11d000, 0xb57ff000, 4096)
09-11 11:56:08.569   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.569   311  7061 V AudioCache: memcpy(0xaf11e000, 0xb57ff000, 4096)
09-11 11:56:08.570   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.570   311  7061 V AudioCache: memcpy(0xaf11f000, 0xb57ff000, 4096)
09-11 11:56:08.570   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.570   311  7061 V AudioCache: memcpy(0xaf120000, 0xb57ff000, 4096)
09-11 11:56:08.571   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.571   311  7061 V AudioCache: memcpy(0xaf121000, 0xb57ff000, 4096)
09-11 11:56:08.572   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.572   311  7061 V AudioCache: memcpy(0xaf122000, 0xb57ff000, 4096)
09-11 11:56:08.572   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.572   311  7061 V AudioCache: memcpy(0xaf123000, 0xb57ff000, 4096)
09-11 11:56:08.573   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.573   311  7061 V AudioCache: memcpy(0xaf124000, 0xb57ff000, 4096)
09-11 11:56:08.574   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.574   311  7061 V AudioCache: memcpy(0xaf125000, 0xb57ff000, 4096)
09-11 11:56:08.574   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.574   311  7061 V AudioCache: memcpy(0xaf126000, 0xb57ff000, 4096)
09-11 11:56:08.575   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.575   311  7061 V AudioCache: memcpy(0xaf127000, 0xb57ff000, 4096)
09-11 11:56:08.575   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.575   311  7061 V AudioCache: memcpy(0xaf128000, 0xb57ff000, 4096)
09-11 11:56:08.576   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.576   311  7061 V AudioCache: memcpy(0xaf129000, 0xb57ff000, 4096)
09-11 11:56:08.576   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.576   311  7061 V AudioCache: memcpy(0xaf12a000, 0xb57ff000, 4096)
09-11 11:56:08.577   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.577   311  7061 V AudioCache: memcpy(0xaf12b000, 0xb57ff000, 4096)
09-11 11:56:08.577   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.577   311  7061 V AudioCache: memcpy(0xaf12c000, 0xb57ff000, 4096)
09-11 11:56:08.578   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.578   311  7061 V AudioCache: memcpy(0xaf12d000, 0xb57ff000, 4096)
09-11 11:56:08.581   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.581   311  7061 V AudioCache: mem,cpy(0xaf12e000, 0xb57ff000, 4096)
09-11 11:56:08.581   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.581   311  7061 V AudioCache: memcpy(0xaf12f000, 0xb57ff000, 4096)
09-11 11:56:08.582   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.582   311  7061 V AudioCache: memcpy(0xaf130000, 0xb57ff000, 4096)
09-11 11:56:08.582   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.582   311  7061 V AudioCache: memcpy(0xaf131000, 0xb57ff000, 4096)
09-11 11:56:08.583   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.583   311  7061 V AudioCache: memcpy(0xaf132000, 0xb57ff000, 4096)
09-11 11:56:08.583   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.583   311  7061 V AudioCache: memcpy(0xaf133000, 0xb57ff000, 4096)
09-11 11:56:08.584   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.584   311  7061 V AudioCache: memcpy(0xaf134000, 0xb57ff000, 4096)
09-11 11:56:08.584   311  7061 V AudioCache: write(0xb57ff000, 4096)
09-11 11:56:08.584   311  7061 V AudioCache: memcpy(0xaf135000, 0xb57ff000, 4096)
09-11 11:56:08.585   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-11 11:56:08.585   311  7061 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-11 11:56:08.585   311  7061 V AwesomePlayer: postAudioEOS() 
09-11 11:56:08.585   311  7061 V AudioCache: write(0xb57ff000, 280)
09-11 11:56:08.585   311  7061 V AudioCache: memcpy(0xaf136000, 0xb57ff000, 280)
09-11 11:56:08.589   311  7058 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-11 11:56:08.589   311  7058 V AwesomePlayer: onStreamDone
09-11 11:56:08.589   311  7058 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-11 11:56:08.589   311  7058 V AudioCache: notify(0xb5474980, 2, 0, 0)
09-11 11:56:08.589   311  7058 V AudioCache: playback complete
09-11 11:56:08.589   311  7058 V AwesomePlayer: pause_l() 
09-11 11:56:08.589   311  7058 V AudioCache: notify(0xb5474980, 7, 0, 0)
09-11 11:56:08.589   311  7058 V AudioCache: ignored
09-11 11:56:08.589   311  7058 V AwesomePlayer: cancelPlayerEvents
09-11 11:56:08.589   311  1369 V AudioCache: wait - success
09-11 11:56:08.589   311  1369 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-11 11:56:08.589   311  7058 D AudioPlayer: Pause Playback at 1068125
09-11 11:56:08.589   311  1369 V AwesomePlayer: reset_l() 
09-11 11:56:08.589   311  1369 V AudioCache: notify(0xb5474980, 8, 0, 0)
09-11 11:56:08.589   311  1369 V AudioCache: ignored
09-11 11:56:08.589   311  1369 V AwesomePlayer: cancelPlayerEvents
09-11 11:56:08.589   311  1369 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-11 11:56:08.589   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-11 11:56:08.589   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
,09-11 11:56:08.589   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-11 11:56:08.589   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c08d0 on port 0
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0240 on port 0
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c01f0 on port 0
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0920 on port 1
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0d80 on port 1
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb16a0470 on port 1
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-11 11:56:08.590   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-11 11:56:08.590   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-11 11:56:08.590   311  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-11 11:56:08.590   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-11 11:56:08.590   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-11 11:56:08.590   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-11 11:56:08.600   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-11 11:56:08.600   311  1369 D AudioPlayer: AudioPlayer releasing audio source
09-11 11:56:08.600   311  1369 D AudioPlayer: AudioPlayer done releasing audio source
09-11 11:56:08.600   311  1369 V AwesomePlayer: reset_l() 
09-11 11:56:08.600   311  1369 V AwesomePlayer: cancelPlayerEvents
09-11 11:56:08.600   311  1369 V AwesomePlayer: ~AwesomePlayer call
09-11 11:56:08.600   311  1369 V AwesomePlayer: reset_l() 
09-11 11:56:08.600   311  1369 V AwesomePlayer: cancelPlayerEvents
09-11 11:56:08.601  6940  7057 V SoundPool: close(31)
09-11 11:56:08.601  6940  7057 V SoundPool: pointer = 0xa0004000, size = 205080, sampleRate = 48000, numChannels = 2
09-11 11:56:08.608  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:08.611  7017  7017 V Blue,toothSapReceiver: [BTUI] checkServiceStart
,09-11 11:56:08.611  7017  7017 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-11 11:56:08.612  7017  7017 V BluetoothSapReceiver: SapReceiver onReceive 
09-11 11:56:08.613  7017  7017 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:08.613  7017  7017 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-11 11:56:08.615  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-11 11:56:08.616  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-11 11:56:08.621  6957  6957 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-11 11:56:08.621  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7344
09-11 11:56:08.791  6806  6806 I UEI.SmartControl: Supports setup maps: true
,09-11 11:56:08.794  6806  6806 D UEI.SmartControl: QS start statue = true Error code = 0
09-11 11:56:08.794  6806  6806 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-11 11:56:08.794  6806  6806 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-11 11:56:08.794  6806  6806 I UEI.SmartControl: ### init IR Blaster...
09-11 11:56:08.798  6806  6806 D serial_port: Configuring serial port
09-11 11:56:08.798  6806  6806 E UEI.SmartControl: UEIBLaster setting for 616
09-11 11:56:08.798  6806  6806 I UEI.SmartControl: Setting serial record hearder size = 2
09-11 11:56:08.798  6806  6806 I UEI.SmartControl: configuring settings for MAXQ616
09-11 11:56:08.798  6806  6806 I UEI.SmartControl: Get version...
09-11 11:56:08.817  6806  7063 D UEI.SmartControl: serial port data available: 21
,09-11 11:56:08.844  6806  6806 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-11 11:56:08.844  6806  6806 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-11 11:56:08.844  6806  6806 I UEI.SmartControl: QS saving settings...
09-11 11:56:08.846  6806  6806 D UEI.SmartControl: IR Blaster version: 25672567
09-11 11:56:08.870  6806  7063 D UEI.SmartControl: serial port data available: 4
,09-11 11:56:08.903  6806  7069 I UEI.SmartControl: Device manager: loading config....
,09-11 11:56:08.905  6806  6806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-11 11:56:08.906  6806  7069 D UEI.SmartControl: ----------- loading internal config...
09-11 11:56:08.908  6806  6806 E UEI.SmartControl: Services init done
09-11 11:56:08.908  6806  6806 D UEI.SmartControl: QS Service init finished
09-11 11:56:08.909  6806  6806 D UEI.SmartControl: QS Service version name: 2.1.91
09-11 11:56:08.909  6806  6806 D UEI.SmartControl: QS Service version code: 201091
09-11 11:56:08.910  6806  6806 D UEI.SmartControl: Service requested: Control
09-11 11:56:08.911  6806  7069 E UEI.SmartControl: Loading SETTINGS...
09-11 11:56:08.915  6806  6806 D UEI.SmartControl: Request IControl service: devices are loaded...
09-11 11:56:08.916  6806  7069 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-11 11:56:08.917  6806  6806 D UEI.SmartControl: Internal service binding...
,09-11 11:56:08.918  6940  6940 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-11 11:56:08.920  6806  6821 I UEI.SmartControl: ------ IControl API: 11
09-11 11:56:08.920  6806  6821 D UEI.SmartControl: File observer start...
09-11 11:56:08.920  6806  6821 E UEI.SmartControl: IR Port is disabled: false
09-11 11:56:08.921  6806  6821 D UEI.SmartControl: Starting file observer...
09-11 11:56:08.922  6806  6821 I UEI.SmartControl: Registering callback...
09-11 11:56:08.923  6806  6837 I UEI.SmartControl: ------ IControl API: 19
09-11 11:56:08.924  6806  6837 I UEI.SmartControl: Registering Services Ready callback...
09-11 11:56:08.943  6806  7068 I UEI.SmartControl: Notify AllClients services are ready: 0
09-11 11:56:08.943  6806  7068 D UEI.SmartControl: -----service ready thread exits
09-11 11:56:08.944  6940  6956 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-11 11:56:08.945  6940  7055 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-11 11:56:08.945  6940  7055 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-11 11:56:08.947  6940  6940 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-11 11:56:08.948  6940  6940 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,09-11 11:56:08.952  6806  6822 I UEI.SmartControl: ------ IControl API: 8
09-11 11:56:08.955  6940  6940 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,09-11 11:56:08.955  6940  6940 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-11 11:56:08.956  6940  6940 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-11 11:56:08.956  6940  6940 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-11 11:56:08.958  6940  6940 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-11 11:56:08.958  6940  6940 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,09-11 11:56:08.962  6940  6940 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-11 11:56:08.966  6940  6940 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-11 11:56:08.967  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-11 11:56:08.969  6940  6940 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-11 11:56:08.970  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-11 11:56:08.971  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-11 11:56:08.974  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-11 11:56:08.975  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-11 11:56:08.978  6940  6940 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473587768977]
,09-11 11:56:08.983  6940  6940 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-11 11:56:08.991  1031  1945 I ActivityManager: Killing 6569:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-11 11:56:09.015  6940  7071 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-11 11:56:09.080  1031  1945 I ActivityManager: Killing 6538:com.lge.email/u0a23 (adj 15): empty #18
,09-11 11:56:09.141  1031  1946 W libprocessgroup: failed to open /acct/uid_10027/pid_6569/cgroup.procs: No such file or directory
,09-11 11:56:09.153  1031  1964 W libprocessgroup: failed to open /acct/uid_10023/pid_6538/cgroup.procs: No such file or directory
09-11 11:56:09.154  6940  6940 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-11 11:56:09.155  6940  6940 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-11 11:56:09.155  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-11 11:56:09.156  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-11 11:56:09.156  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-11 11:56:09.156  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-11 11:56:09.158  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-11 11:56:09.168  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-11 11:56:09.771  1031  1927 D WifiServiceImplEx: setWifiEnabled: true pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-11 11:56:09.772  1031  1927 D WifiService: setWifiEnabled: true pid=6629, uid=10118
,09-11 11:56:09.772  1031  1927 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-11 11:56:09.798  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-11 11:56:09.800  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-11 11:56:09.800  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-11 11:56:09.801  1031  1525 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-11 11:56:09.801  1031  1525 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-11 11:56:09.804  1031  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,09-11 11:56:09.804  1031  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-11 11:56:09.804  1031  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-11 11:56:09.804  1031  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-11 11:56:09.804  1031  1525 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-11 11:56:09.804  1031  1525 E WifiHW  : unknown target_country: EU , set to default
09-11 11:56:09.804  1031  1525 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-11 11:56:09.804  1031  1525 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-11 11:56:09.804  1031  1525 I WifiUtil: gEnableBmps=1
09-11 11:56:09.860  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:09.875  1031  1102 D Tethering: MasterInitialState.processMessage what=3
09-11 11:56:09.880  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:09.886  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:09.890  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:09.893  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:09.896  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-11 11:56:09.898  6408  6446 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-11 11:56:09.903  1031  1102 D Tethering: MasterInitialState.processMessage what=3
09-11 11:56:09.910  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:09.924  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:09.926  5803  5803 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-11 11:56:09.931  5803  5803 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-11 11:56:09.969  2167  2167 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:10.016  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:10.032  1031  1891 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7091 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-11 11:56:10.038  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:10.038  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-11 11:56:10.118  7091  7091 I AppUp4:AppBoxCP: onCreate
09-11 11:56:10.119  7091  7091 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-11 11:56:10.129  7091  7091 I AppUp4:DB:  setFingerPrint start
,09-11 11:56:10.129  7091  7091 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-11 11:56:10.138  7091  7091 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-11 11:56:10.138  7091  7091 I AppUp4:DB:  SDK version = 21
09-11 11:56:10.138  7091  7091 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-11 11:56:10.140  7091  7091 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-11 11:56:10.142  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-11 11:56:10.143  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:10.145  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-11 11:56:10.145  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-11 11:56:10.152  7091  7091 I AppUp4:CustModeStarterReceiver: onReceive
,09-11 11:56:10.194  7091  7091 D LgDataFeature: LgDataFeature() Constructor: none
,09-11 11:56:10.194  7091  7091 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-11 11:56:10.203  7091  7091 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2712955f
09-11 11:56:10.203  7091  7091 D AppUp4:CustFacade: isCustomizationCompleted : false
09-11 11:56:10.203  7091  7091 D AppUp4:CustFacade: isPhone : true
,09-11 11:56:10.204  7091  7091 D AppUp4:CustModeStarterReceiver: begin check event
09-11 11:56:10.205  7091  7091 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-11 11:56:10.206  7091  7091 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,09-11 11:56:10.208  7091  7112 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,09-11 11:56:10.209  7091  7112 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-11 11:56:10.209  7091  7112 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-11 11:56:10.213  1031  1760 I ActivityManager: Killing 6092:com.android.vending/u0a44 (adj 15): empty #17
,09-11 11:56:10.284  1031  1049 W libprocessgroup: failed to open /acct/uid_10044/pid_6092/cgroup.procs: No such file or directory
,09-11 11:56:10.284  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:10.285  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-11 11:56:10.292  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:10.298  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:10.312  4807  7122 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-11 11:56:10.320  4807  7123 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:10.321  4807  7123 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-11 11:56:10.383  1031  1964 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7124 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-11 11:56:10.404   340   340 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 484us total 22.415ms
,09-11 11:56:10.443   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 36.986ms
,09-11 11:56:10.466   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 21.547ms
,09-11 11:56:10.468   306   890 D SoftapController: Softap fwReload - Ok
09-11 11:56:10.470  1031  1525 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (660ms)
09-11 11:56:10.473   306   890 D CommandListener: Setting iface cfg
09-11 11:56:10.473   306   890 D CommandListener: Trying to bring down wlan0
09-11 11:56:10.473   306   890 D CommandListener: Clearing all IP addresses on wlan0
09-11 11:56:10.475  1031  1525 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-11 11:56:10.477  1031  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-11 11:56:10.477  1031  1525 E WifiStateMachine: useWiFiOffloading() : false
09-11 11:56:10.477  1031  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-11 11:56:10.469  7142  7142 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:10.469  7142  7142 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-11 11:56:10.512  1031  1371 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7143 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-11 11:56:10.512  1031  1371 V AlarmManager: RTC_WAKEUP set : Alarm{2db53303 type 0 when 1473587767565 com.android.vending} when 1473587767565
09-11 11:56:10.513  1031  1371 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2303d280 type 2 when 117875 com.google.android.gms} when 117875
,09-11 11:56:10.515  7142  7142 I wpa_supplicant: Successfully initialized wpa_supplicant
09-11 11:56:10.515  1031  1525 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-11 11:56:10.515  1031  1525 D WifiMonitor: connecting to supplicant
09-11 11:56:10.528  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-11 11:56:10.531  1031  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-11 11:56:10.531  1031  1102 D Tethering: InitialState.processMessage what=4
09-11 11:56:10.532  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-11 11:56:10.532  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-11 11:56:10.533  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:10.536  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:10.536  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:10.552  7142  7142 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-11 11:56:10.552  7142  7142 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-11 11:56:10.561  7124  7124 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-11 11:56:10.561  7124  7124 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-11 11:56:10.562  7124  7124 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-11 11:56:10.562  7124  7124 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-11 11:56:10.610  7124  7124 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-11 11:56:10.618  7124  7124 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-11 11:56:10.626  7142  7142 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-11 11:56:10.640  7124  7124 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-11 11:56:10.659  7124  7124 D LgDataFeature: LgDataFeature() Constructor: none
09-11 11:56:10.659  7124  7124 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-11 11:56:10.694  7142  7142 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-11 11:56:10.699  7142  7142 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-11 11:56:10.699  7142  7142 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-11 11:56:10.700  1031  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-11 11:56:10.701  1031  7169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-11 11:56:10.701  1031  7169 D WifiMonitor: Dropping event because (p2p0) is stopped
09-11 11:56:10.701  1031  1525 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-11 11:56:10.701  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-11 11:56:10.701  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-11 11:56:10.701  1031  7169 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-11 11:56:10.701  1031  7169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-11 11:56:10.701  1031  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-11 11:56:10.701  1031  1525 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-11 11:56:10.702  1031  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:10.702  1031  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:10.703  1031  1525 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-11 11:56:10.703  1031  1525 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-11 11:56:10.703  1031  1525 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-11 11:56:10.703  1031  1525 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-11 11:56:10.703  1031  1525 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-11 11:56:10.704  1031  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-11 11:56:10.704  1031  1525 E WifiStateMachine: useWiFiOffloading() : false
09-11 11:56:10.704  1031  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-11 11:56:10.704  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:10.704  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:10.705  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:10.705  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:10.705  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-11 11:56:10.705  1928  1928 D WfdService: Waiting for WifiP2p enabling
09-11 11:56:10.706  7143  7143 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-11 11:56:10.706  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,09-11 11:56:10.706  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-11 11:56:10.709  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:10.710  1031  1525 D WifiNative-wlan0: doBoolean: SET update_config 1
09-11 11:56:10.710  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:10.711  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.711  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:10.711  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:10.711  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:10.711  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.711  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:10.711  1031  1525 D WifiNative-wlan0: SET update_config 1: returned true
09-11 11:56:10.711  1031  1525 D WifiConfigStore: Loading config and enabling all networks 
09-11 11:56:10.712  1031  1525 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-11 11:56:10.712  1031  1525 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-11 11:56:10.717  1031  1525 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-11 11:56:10.724  1031  1525 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-11 11:56:10.724  1031  1525 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-11 11:56:10.726  1031  1525 D WifiStateMachine: enableVerboseLogging : level 2
09-11 11:56:10.726  1031  1525 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-11 11:56:10.729  1031  1525 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-11 11:56:10.729  1031  1525 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-11 11:56:10.731  1031  1525 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-11 11:56:10.731  1031  1525 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-11 11:56:10.731  1031  1525 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-11 11:56:10.731  1031  1525 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-11 11:56:10.731  1031  1525 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-11 11:56:10.731  1031  1525 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-11 11:56:10.732  1031  1525 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-11 11:56:10.732  1031  1525 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-11 11:56:10.732  1031  1525 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-11 11:56:10.732  1031  1525 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-11 11:56:10.733  1031  1525 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-11 11:56:10.734  1928  1928 D WfdsService: Supplicant Connection state is changed : true
09-11 11:56:10.734  1031  1525 D WifiStateMachine: Setting OUI to DA-A1-19
09-11 11:56:10.734  1031  1525 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-11 11:56:10.734  1928  2275 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-11 11:56:10.734  1928  2275 D WfdsService: Set the WFDS Monitor: true
09-11 11:56:10.734  1928  2275 D WfdsMonitor: WfdsMonitorThread create
09-11 11:56:10.734  1928  2275 D WfdsMonitor: WFDS Monitor is created and started
09-11 11:56:10.734  1928  2275 D WfdsService: WiFi: Supplicant connection re-established
09-11 11:56:10.735  1031  1525 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-11 11:56:10.735  1031  1525 D WifiNative-HAL: Setting external_sim to 1
09-11 11:56:10.735  1031  1525 D WifiNative-wlan0: doBoolean: SET external_sim 1
,09-11 11:56:10.736  1031  1525 D WifiNative-wlan0: SET external_sim 1: returned true
09-11 11:56:10.736  1031  1525 I WifiNative-HAL: startHal
09-11 11:56:10.736  1031  1525 D wifi    : setting scan oui 0xaf742040
09-11 11:56:10.737  1031  1525 D WifiStateMachine: Setting OUI to DA-A1-19
09-11 11:56:10.737  1031  1525 I WifiNative-HAL: startHal
09-11 11:56:10.737  1031  1525 D wifi    : setting scan oui 0xaf742040
09-11 11:56:10.738  1031  1525 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-11 11:56:10.739  1928  7181 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-11 11:56:10.739  1928  7181 E CtrlSupplicant: Succeed to open control connection
09-11 11:56:10.739  1031  1525 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-11 11:56:10.739  1928  7181 E CtrlSupplicant: Succeed to open monitor connection
09-11 11:56:10.739  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-11 11:56:10.739  1928  7181 D WfdsMonitor: Supplicant connection established
09-11 11:56:10.740  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-11 11:56:10.740  1928  2275 D WfdsService: Connected to the supplicant for wfds
09-11 11:56:10.740  1031  1525 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-11 11:56:10.740  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-11 11:56:10.740  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-11 11:56:10.741  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-11 11:56:10.741  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-11 11:56:10.741  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-11 11:56:10.741  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-11 11:56:10.741  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-11 11:56:10.741  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-11 11:56:10.741  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-11 11:56:10.741  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-11 11:56:10.742  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-11 11:56:10.742  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-11 11:56:10.742  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-11 11:56:10.742  7142  7142 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-11 11:56:10.742  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-11 11:56:10.742  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-11 11:56:10.742  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-11 11:56:10.743  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-11 11:56:10.743  1031  1525 E WifiNative: : [118,201,025 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-11 11:56:10.743  1031  1525 D WifiNative-wlan0: doBoolean: RECONNECT
09-11 11:56:10.744  1031  1525 D WifiNative-wlan0: RECONNECT: returned true
09-11 11:56:10.744  1031  1525 D WifiNative-wlan0: doString: [STATUS]
09-11 11:56:10.744  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-11 11:56:10.744  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-11 11:56:10.745  1031  1525 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-11 11:56:10.745  1031  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-11 11:56:10.745  1031  1525 D WifiNative-wlan0: SET ps 1: returned true
09-11 11:56:10.745  1031  1524 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:,56:10.746  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
09-11 11:56:10.746  1031  1031 D RttService: SCAN_AVAILABLE : 3
09-11 11:56:10.746  1031  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.746  1031  1543 I WifiNative-HAL: startHal
09-11 11:56:10.746  1031  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf742040
09-11 11:56:10.746  1031  1543 D wifi    : failed to get capabilities : -3
09-11 11:56:10.746  1031  1543 E WifiScanningService: could not get scan capabilities
09-11 11:56:10.746  1031  1525 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-11 11:56:10.747   306   890 D CommandListener: Setting iface cfg
09-11 11:56:10.747  1031  1544 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.747   306   890 D CommandListener: Trying to bring up p2p0
09-11 11:56:10.747  1031  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-11 11:56:10.747  1031  1524 D LGWifiP2pService: P2pEnablingState
09-11 11:56:10.747  1031  1524 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.747  1031  1524 D LGWifiP2pService: P2p socket connection successful
09-11 11:56:10.747  1031  1524 D LGWifiP2pService: P2pEnabledState
09-11 11:56:10.747  1031  1525 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-11 11:56:10.747  1031  1524 D LGWifiP2pService: sending p2p connection changed broadcast
09-11 11:56:10.747  1031  1525 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-11 11:56:10.748  1031  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-11 11:56:10.748  1031  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-11 11:56:10.748  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-11 11:56:10.748  1031  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
09-11 11:56:10.748  1928  1928 D WfdsService: WifiP2pState is changed : true
09-11 11:56:10.748  1031  1524 D WifiNative-p2p0: SET device_name G3: returned true
09-11 11:56:10.748  1031  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-11 11:56:10.749  1031  1524 D LGWifiP2pService: before postfix = G3
09-11 11:56:10.749  1031  1524 D WifiServerServiceExt: postfix byte check : 2
09-11 11:56:10.749  1928  2275 D WfdsService: Receive the WFDS_ENABLE Method
09-11 11:56:10.749  1031  1524 D LGWifiP2pService: after postfix = G3
09-11 11:56:10.749  1928  2275 D WfdsService: Set the WFDS Monitor: true
09-11 11:56:10.749  1031  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-11 11:56:10.749  1928  2275 D WfdsService: Connected to the supplicant for wfds
09-11 11:56:10.749  1928  2275 D WfdsJNI : doCommand: WFDS_SET TRUE
,09-11 11:56:10.749  7142  7142 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-11 11:56:10.749  1031  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-11 11:56:10.749  1031  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-11 11:56:10.749  1031  1525 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-11 11:56:10.749  1031  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-11 11:56:10.749  1031  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,09-11 11:56:10.750  1031  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-11 11:56:10.750  1031  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-11 11:56:10.750  1031  1524 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-11 11:56:10.750  1031  1524 D WifiNative-HAL: p2pGetDeviceAddress
09-11 11:56:10.750  1031  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-11 11:56:10.750  1031  1525 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-11 11:56:10.751  1031  1525 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-11 11:56:10.752  1031  1525 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-11 11:56:10.752  1031  1525 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-11 11:56:10.753  7142  7142 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-11 11:56:10.754  1928  2275 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
09-11 11:56:10.754  7142  7142 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
09-11 11:56:10.754  1031  1525 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-11 11:56:10.754  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-11 11:56:10.755  1031  1524 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-11 11:56:10.755  1031  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-11 11:56:10.755  1928  2275 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
09-11 11:56:10.755  1031  1524 D WifiNative-p2p0: P2P_FLUSH: returned true
09-11 11:56:10.755  1031  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-11 11:56:10.755  1928  2275 D WfdsService: selectPreferredScanChannel [36]
09-11 11:56:10.755  1928  2275 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-11 11:56:10.755  1031  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-11 11:56:10.755  1031  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-11 11:56:10.756  1928  1928 D WfdsService: isConnected: false
09-11 11:56:10.756  1031  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-11 11:56:10.756  1031  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-11 11:56:10.756  1031  1525 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-11 11:56:10.756  1031  1525 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-11 11:56:10.756  1031  1525 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-11 11:56:10.758  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
09-11 11:56:10.758  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-11 11:56:10.759  1928  1928 D WfdsService: Update P2p Interface State: 3
09-11 11:56:10.760  7143  7143 D LgDataFeature: LgDataFeature() Constructor: none
,09-11 11:56:10.760  7143  7143 D LgDataFeature: LgDataFeature() Constructor Done, null
09-11 11:56:10.769  7124  7124 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-11 11:56:10.776  7142  7142 E wpa_supplicant: disconnect_rssi_lvl: -100
,09-11 11:56:10.777  1031  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true,
09-11 11:56:10.777  1031  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-11 11:56:10.777  1031  1524 D LGWifiP2pService: InactiveState
09-11 11:56:10.777  1031  1524 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,09-11 11:56:10.777  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.777  1031  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-11 11:56:10.777  1031  1525 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-11 11:56:10.777  1031  1525 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-11 11:56:10.777  1031  1525 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-11 11:56:10.777  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-11 11:56:10.778  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-11 11:56:10.778  7142  7142 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:10.778  7142  7142 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-11 11:56:10.779  7142  7142 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.779  7142  7142 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.779  1031  7169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-11 11:56:10.779  1031  7169 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:10.779  1031  7169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:10.779  1031  7169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:10.779  1031  7169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:10.779  1031  7169 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.779  1928  7181 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-11 11:56:10.779  1031  7169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.779  1928  7181 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:10.779  1031  7169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.779  1928  7181 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:10.779  1031  7169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:10.779  1031  7169 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.779  1031  7169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.779  1031  7169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.779  1031  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780,  1031  1031 E WifiServerServiceExt: No p2p device connected
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780  1031  1524 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.780  1928  2275 W WfdsService: DefaultState - msg [9441285] is not handled
09-11 11:56:10.780  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-11 11:56:10.781  7142  7142 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:10.781  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-11 11:56:10.781  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:10.781  7142  7142 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,09-11 11:56:10.781  1031  7169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:10.781  1031  7169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:10.781  7142  7142 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.781  1031  7169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:10.781  1031  7169 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.781  1031  7169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.781  7142  7142 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-11 11:56:10.781  1031  7169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.782  1031  7169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:10.782  1031  7169 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.782  1031  7169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.782  1031  7169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:10.782  1928  7181 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-11 11:56:10.782  1928  7181 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:10.782  1031  1525 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-11 11:56:10.782  1031  1524 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.782  1031  1525 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-11 11:56:10.782  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.782  1031  1525 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,09-11 11:56:10.783  1031  1525 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-11 11:56:10.783  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-11 11:56:10.783  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-11 11:56:10.783  7142  7142 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-11 11:56:10.783  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-11 11:56:10.783  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-11 11:56:10.783  1031  7169 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-11 11:56:10.783  1031  7169 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-11 11:56:10.783  1031  1525 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-11 11:56:10.783  1031  1525 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-11 11:56:10.784  1031  1525 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-11 11:56:10.784  1031  1525 D WifiNative-wlan0: doBoolean: SCAN
,09-11 11:56:10.784  1031  1525 D WifiNative-wlan0: SCAN: returned false
09-11 11:56:10.784  1031  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=118242  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-11 11:56:10.787  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=118245  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-11 11:56:10.787  1031  1525 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-11 11:56:10.787  1031  1525 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-11 11:56:10.788  1031  1525 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-11 11:56:10.788  1031  1525 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-11 11:56:10.788  1031  1525 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-11 11:56:10.789  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:10.789  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:10.790  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:10.790  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:10.791  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-11 11:56:10.791  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:10.793  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:10.793  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
09-11 11:56:10.796  7000  7184 W FormManager: Network not available. Please check & try again.
09-11 11:56:10.799  3288  3288 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-11 11:56:10.799  3288  3288 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:10.799  3288  3288 I LgeMiscReceiver: networkInfo.isConnected() = false
09-11 11:56:10.807  7143  7143 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-11 11:56:10.820  1031  1918 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7189 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-11 11:56:10.821  7143  7143 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-11 11:56:10.823  7000  7185 V FormManager: Network unavailable.
09-11 11:56:10.823  7143  7143 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-11 11:56:10.824  7000  7185 V FormManager: Network unavailable.
09-11 11:56:10.833  7143  7143 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-11 11:56:10.833  7143  7143 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-11 11:56:10.833  7124  7124 I HubEmail: JNI_OnLoad()
09-11 11:56:10.834  7124  7124 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-11 11:56:10.834  7124  7124 I HubEmail: registerNatives()
09-11 11:56:10.834  7124  7124 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-11 11:56:10.834  7124  7124 I HubEmail: registerNativeMethods()
09-11 11:56:10.834  7124  7124 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-11 11:56:10.834  7124  7124 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-11 11:56:10.837  1031  1562 I ActivityManager: Killing 6595:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-11 11:56:10.871  1031  2019 W libprocessgroup: failed to open /acct/uid_10061/pid_6595/cgroup.procs: No such file or directory
,09-11 11:56:10.881  7124  7204 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:10.883  3398  6001 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-11 11:56:10.885  3398  6001 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@35849fd3 on behalf of 7143
,09-11 11:56:10.895  7143  7143 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-11 11:56:10.910  7143  7143 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-11 11:56:10.939  1031  1760 V SIM_STK : Menu title from STK is T-Mobile
,09-11 11:56:10.972  7189  7189 D LgDataFeature: LgDataFeature() Constructor: none
,09-11 11:56:10.972  7189  7189 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-11 11:56:10.975  7189  7189 D PhoneMonitor: Register our PhoneStateListener
09-11 11:56:11.000  7189  7189 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-11 11:56:11.004  7189  7189 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-11 11:56:11.034  7189  7189 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-11 11:56:11.035  7189  7189 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,09-11 11:56:11.037  7189  7189 D TelephonyAutoProfiling: [parse] Load xml
,09-11 11:56:11.042  7189  7189 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-11 11:56:11.043  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-11 11:56:11.044  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-11 11:56:11.044  7189  7189 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-11 11:56:11.044  7189  7189 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-11 11:56:11.058  7189  7189 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-11 11:56:11.073  1031  1049 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7212 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-11 11:56:11.078  1031  1049 I ActivityManager: Killing 6705:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-11 11:56:11.140  1031  1945 W libprocessgroup: failed to open /acct/uid_10080/pid_6705/cgroup.procs: No such file or directory
,09-11 11:56:11.156  7143  7143 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-11 11:56:11.160  1031  1873 I ActivityManager: Killing 6757:com.lge.eula/1000 (adj 15): empty #17
09-11 11:56:11.230  1031  1760 W libprocessgroup: failed to open /acct/uid_1000/pid_6757/cgroup.procs: No such file or directory
,09-11 11:56:11.393  7142  7142 E wpa_supplicant: USIM:  scard_init function
09-11 11:56:11.394  7142  7142 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-11 11:56:11.396  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-11 11:56:11.396  1031  7169 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-11 11:56:11.396  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-11 11:56:11.396  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-11 11:56:11.396  1031  7169 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-11 11:56:11.396  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-11 11:56:11.396  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-11 11:56:11.397  1031  1525 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-11 11:56:11.399  1031  1525 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-11 11:56:11.399  1031  1525 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-11 11:56:11.400  1031  1525 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-11 11:56:11.400  1031  1525 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-11 11:56:11.404  1031  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=118862  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-11 11:56:11.407  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:11.408  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-11 11:56:11.410  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:11.410  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.410  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-11 11:56:11.412  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:11.414  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=118872  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-11 11:56:11.417  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.418  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.418  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-11 11:56:11.420  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:11.420  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-11 11:56:11.432  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:11.432  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-11 11:56:11.433  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:11.477  1031  1945 I art     : Explicit concurrent mark sweep GC freed 78976(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.683ms total 175.108ms
,09-11 11:56:11.514  1031  1964 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7236 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-11 11:56:11.515  1031  1964 I ActivityManager: Killing 5653:com.lge.bnr/1000 (adj 15): empty #17
,09-11 11:56:11.537  7142  7142 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-11 11:56:11.537  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-11 11:56:11.537  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-11 11:56:11.537  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-11 11:56:11.538  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-11 11:56:11.538  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-11 11:56:11.538  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-11 11:56:11.538  1031  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=118996  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-11 11:56:11.540  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=118997  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-11 11:56:11.540  1031  1525 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=118998
09-11 11:56:11.540  1031  1525 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=118998
09-11 11:56:11.541  1031  1525 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=118998
09-11 11:56:11.541  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=118999
09-11 11:56:11.542  1031  1525 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119000
09-11 11:56:11.542  1031  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=119000  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-11 11:56:11.551  1031  1983 W libprocessgroup: failed to open /acct/uid_1000/pid_5653/cgroup.procs: No such file or directory
,09-11 11:56:11.555  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=119012  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-11 11:56:11.555  1031  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-11 11:56:11.556  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:11.556  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:11.557  7142  7142 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-11 11:56:11.557  7142  7142 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-11 11:56:11.558  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-11 11:56:11.558  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-11 11:56:11.558  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-11 11:56:11.558  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-11 11:56:11.558  1031  7169 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-11 11:56:11.558  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-11 11:56:11.558  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-11 11:56:11.558  1031  7169 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-11 11:56:11.559  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-11 11:56:11.559  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-11 11:56:11.559  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:11.560  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.560  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.560  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-11 11:56:11.569  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.569  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.569  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-11 11:56:11.569  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:11.569  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,09-11 11:56:11.571  1031  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=119028  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-11 11:56:11.571  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=119029  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-11 11:56:11.572  1031  1525 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=119030
09-11 11:56:11.573  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:11.573  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-11 11:56:11.575  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:11.575  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:11.576  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:11.580  1031  1525 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=119038
09-11 11:56:11.581  1031  1525 D WifiNative-wlan0: doString: [STATUS]
09-11 11:56:11.581  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-11 11:56:11.581  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-11 11:56:11.582  1031  1525 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-11 11:56:11.584  1031  1525 I WifiServiceExtension: setVHTCapabilityType  : false
,09-11 11:56:11.591  1031  1525 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-11 11:56:11.591  1031  1525 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-11 11:56:11.598  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.598  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.598  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-11 11:56:11.604  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.604  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.604  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-11 11:56:11.608  1031  1525 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-11 11:56:11.608  1031  1531 D ConnectivityService: Got NetworkAgent Messenger
09-11 11:56:11.608  1031  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-11 11:56:11.608  1031  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-11 11:56:11.608  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-11 11:56:11.608  1031  1531 D ConnectivityService: NetworkAgent connected
09-11 11:56:11.609  1031  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-11 11:56:11.609  1031  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-11 11:56:11.615  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:11.615  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:11.617  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-11 11:56:11.619  1031  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-11 11:56:11.619  1031  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-11 11:56:11.619  1031  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-11 11:56:11.619  1031  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-11 11:56:11.619  1031  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-11 11:56:11.620  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:11.620  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:11.621  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:11.625  1031  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-11 11:56:11.626   306   890 D CommandListener: Setting iface cfg
09-11 11:56:11.629  1031  1525 E WifiStateMachine: Start Dhcp Watchdog 2
09-11 11:56:11.629  1031  7254 D DhcpStateMachine: StoppedState
09-11 11:56:11.629  1031  7254 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:11.629  1031  7254 D DhcpStateMachine: WaitBeforeStartState
,09-11 11:56:11.630  1031  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=119087  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-11 11:56:11.630  1031  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=119088  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-11 11:56:11.631  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=119088  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-11 11:56:11.631  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:11.632  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
,09-11 11:56:11.632  1031  1525 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,09-11 11:56:11.632  1031  1525 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:11.633  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:11.633  1031  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:11.634  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:11.634  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-11 11:56:11.634  1031  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119092  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-11 11:56:11.635  1031  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119092  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-11 11:56:11.635  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119093  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-11 11:56:11.636  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:72557] from screen [on:0 period:413989108] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-11 11:56:11.637  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:413989109] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-11 11:56:11.637  1031  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-11 11:56:11.686  1031  1873 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7259 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-11 11:56:11.688  1031  1873 I ActivityManager: Killing 6731:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-11 11:56:11.774  1031  1945 W libprocessgroup: failed to open /acct/uid_10097/pid_6731/cgroup.procs: No such file or directory
,09-11 11:56:11.781  1031  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-11 11:56:11.782  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:11.784  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:11.785  1031  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:11.786  1031  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:11.787  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:11.788  1031  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-11 11:56:11.791  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-11 11:56:11.793  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=182,0,0
09-11 11:56:11.794  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=182,0,0
09-11 11:56:11.795  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-11 11:56:11.796  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-11 11:56:11.797  1031  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-11 11:56:11.797  1031  1525 D WifiNative-wlan0: doBoolean: SET ps 0
09-11 11:56:11.799  1031  1525 D WifiNative-wlan0: SET ps 0: returned true
09-11 11:56:11.799  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-11 11:56:11.800  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-11 11:56:11.801  1031  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-11 11:56:11.801  1031  1525 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-11 11:56:11.801  1031  1525 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-11 11:56:11.801  1031  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ad71ac3 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:11.801  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ad71ac3 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:11.802  1031  7254 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:11.802  1031  7254 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-11 11:56:11.802  1031  1525 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-11 11:56:11.803   306   890 D CommandListener: Setting iface cfg
,09-11 11:56:11.803   306   890 D CommandListener: Trying to bring up wlan0
09-11 11:56:11.805  1031  1525 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-11 11:56:11.806  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:11.806  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:11.807  1031  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:11.807  1031  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:11.807  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:11.808  1031  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:11.809  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-11 11:56:11.809  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-11 11:56:11.810  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-11 11:56:11.810  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-11 11:56:11.810  1031  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:11.810  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:11.810  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-11 11:56:11.811  1031  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-11 11:56:11.811  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-11 11:56:11.811  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-11 11:56:11.811  1031  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-11 11:56:11.811  1031  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-11 11:56:11.818  7259  7259 I art     : Almond Protected OAT
,09-11 11:56:11.828  1031  1525 D WifiNative-wlan0: SET ps 1: returned true
09-11 11:56:11.828  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-11 11:56:11.829  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-11 11:56:11.829  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,09-11 11:56:11.830  1031  1525 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-11 11:56:11.830  1031  1531 D ConnectivityService: ignoring duplicate network state non-change
09-11 11:56:11.832  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-11 11:56:11.832  1031  1531 D ConnectivityService: Adding iface wlan0 to network 101
09-11 11:56:11.834  1031  1525 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-11 11:56:11.840  1031  1524 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:11.840  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:11.840  1031  1524 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:11.843  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:11.844  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:11.844  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-11 11:56:11.849  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:11.849  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:11.850  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:11.859  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.859  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.859  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-11 11:56:11.861  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.861  1031  1525 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-11 11:56:11.861  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.861  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-11 11:56:11.862  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-11 11:56:11.862  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-11 11:56:11.862  1031  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-11 11:56:11.862  1031  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-11 11:56:11.863  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-11 11:56:11.863  1031  1525 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-11 11:56:11.864  1031  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-11 11:56:11.864  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-11 11:56:11.864  1031  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-11 11:56:11.865  1031  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-11 11:56:11.866   306   890 E Netd    : netlink response contains error (File exists)
09-11 11:56:11.866  1031  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-11 11:56:11.867  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.867  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.867  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-11 11:56:11.868  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-11 11:56:11.868  1031  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-11 11:56:11.868  1031  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-11 11:56:11.868  1031  1531 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-11 11:56:11.873  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:11.873  1031  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-11 11:56:11.873  1031  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-11 11:56:11.873  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:11.873  1031  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-11 11:56:11.873  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-11 11:56:11.874  1031  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-11 11:56:11.874  1031  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:11.874  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:11.874  1031  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-11 11:56:11.874  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:11.874  1031  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-11 11:56:11.875  1031  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:11.875  1031  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-11 11:56:11.875  1031  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:11.875  1031  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-11 11:56:11.875  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:11.875  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:11.876  1031  1531 D ConnectivityService: currentScore = 0, newScore = 20
09-11 11:56:11.876  1031  1531 D ConnectivityService:    accepting network in place of null
09-11 11:56:11.876  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:11.877  1031  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:11.877  1031  1525 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:11.877  1031  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:11.878  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:11.878  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-11 11:56:11.878  1031  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDn,Bandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-11 11:56:11.878  1031  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-11 11:56:11.879  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-11 11:56:11.879   306  7281 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-11 11:56:11.879  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:11.879  1031  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-11 11:56:11.880  1031  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-11 11:56:11.881  1031  1531 D ConnectivityService: validation of new default Network = false
09-11 11:56:11.881  1031  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-11 11:56:11.881  1031  1531 D DSQN    : enableDataServiceNotify 
09-11 11:56:11.881  1031  1531 D DSQN    : start dsqn bin
09-11 11:56:11.885  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-11 11:56:11.885  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-11 11:56:11.885  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-11 11:56:11.885  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-11 11:56:11.890  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:11.890  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-11 11:56:11.891  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:11.897  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:11.897  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-11 11:56:11.897  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-11 11:56:11.908  7259  7259 D WeatherApplication: removeAccount
09-11 11:56:11.909  7259  7259 D WeatherApplication: Account.length = 0
,09-11 11:56:11.911  7259  7259 E WeatherApplication: OPERATOR:OPEN
09-11 11:56:11.912  1031  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-11 11:56:11.917  7259  7259 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:56:11
09-11 11:56:11.918  1804  7282 I CheckinService: active receiver: enabled
09-11 11:56:11.924   306  7281 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-11 11:56:11.938  1031  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-11 11:56:11.938  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:11.938  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:11.939  1031  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:11.939  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-11 11:56:11.929  7283  7283 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:11.929  7283  7283 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:11.942  7259  7259 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-11 11:56:11.942  7259  7259 D Weather.Utils: 2 : All the weather widget is gone.
09-11 11:56:11.945  7259  7259 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-11 11:56:11.946  1804  7282 I CheckinService: Preparing to send checkin request
,09-11 11:56:11.946  1804  7282 I EventLogService: Accumulating logs since 1473587695348
09-11 11:56:11.947  7259  7259 D WeatherAncestor: connectivity changed - connection : true
09-11 11:56:11.948  7259  7259 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-11 11:56:11.955  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-11 11:56:11.955  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:11.956  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-11 11:56:11.961   306  7281 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-11 11:56:11.961  7283  7283 E DSQN    : DSQN ssw
09-11 11:56:11.964  7259  7259 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-11 11:56:11.964  7259  7259 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-11 11:56:11.964  7259  7259 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-11 11:56:11.977  7259  7259 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-11 11:56:11.977  7259  7259 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:56:11
09-11 11:56:11.986   306   889 D LGDataListener: argv[0]=dsqncommand
09-11 11:56:11.986   306   889 D LGDataListener: argv[1]=wlan0
09-11 11:56:11.986   306   889 D LGDataListener: argv[2]=1
,09-11 11:56:11.986   306   889 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-11 11:56:11.986  1031  1100 D DSQN    : DSQM DsqnNotification wlan0  1
09-11 11:56:11.986  1031  1100 D DSQN    : start to monitor internet connection
09-11 11:56:12.003  1031  7254 D DhcpStateMachine: DHCPV4 request on wlan0
,09-11 11:56:11.989  7291  7291 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:11.989  7291  7291 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:12.003  1031  7254 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-11 11:56:12.003  1031  7254 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-11 11:56:12.012  1031  1964 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7292 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-11 11:56:12.013  1031  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 11 Sep 2016 09:56:12 GMT], X-Android-Received-Millis=[1473587772012], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473587771986]}
09-11 11:56:12.013  1031  1964 I ActivityManager: Killing 2145:com.lge.music/u0a34 (adj 15): empty #17
09-11 11:56:12.013  1031  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-11 11:56:12.013  1031  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-11 11:56:12.013  1031  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-11 11:56:12.013  1031  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-11 11:56:12.013  1031  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:12.013  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:12.013  1031  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-11 11:56:12.013  1031  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-11 11:56:12.013  1031  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-11 11:56:12.013  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:12.013  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:12.013  1031  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:12.014  1031  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:12.014  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-11 11:56:12.014  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-11 11:56:12.014  1031  1525 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:12.014  1031  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:12.014  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:12.015  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIM,S&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-11 11:56:12.016  7291  7291 I dhcpcd  : version 5.5.6 starting
09-11 11:56:12.020  7291  7291 E dhcpcd  : get_duid: m
09-11 11:56:12.020  7291  7291 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-11 11:56:12.020  7291  7291 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-11 11:56:12.030   311  1773 V AudioFlinger: 2145 died, releasing its sessions
09-11 11:56:12.030   311  1773 V AudioFlinger:  pid 1839 @ 0
09-11 11:56:12.030   311  1773 V AudioFlinger:  pid 3288 @ 1
09-11 11:56:12.031   311  1773 V AudioFlinger:  pid 3288 @ 2
,09-11 11:56:12.067  7291  7291 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-11 11:56:12.068  7291  7291 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-11 11:56:12.068  7291  7291 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-11 11:56:12.068  7291  7291 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-11 11:56:12.069  7291  7291 D dhcpcd  : wlan0: sending REQUEST (xid 0xa07ac1dc), next in 3.06 seconds
09-11 11:56:12.070  1804  7282 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-11 11:56:12.073  1031  1927 W libprocessgroup: failed to open /acct/uid_10034/pid_2145/cgroup.procs: No such file or directory
,09-11 11:56:12.087  7291  7291 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-11 11:56:12.088  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-11 11:56:12.089  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:12.090  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:12.099  7291  7291 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-11 11:56:12.099  7291  7291 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-11 11:56:12.099  7291  7291 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-11 11:56:12.099  7291  7291 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-11 11:56:12.099  7291  7291 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-11 11:56:12.099  7291  7291 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-11 11:56:12.100  7291  7291 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-11 11:56:12.100  7291  7291 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-11 11:56:12.140  1031  2000 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7319 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-11 11:56:12.156   278   437 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-11 11:56:12.156   278   437 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-11 11:56:12.156   278   437 W Vold    : Returning OperationFailed - no handler for errno 0
09-11 11:56:12.157  7292  7327 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-11 11:56:12.158   278   437 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-11 11:56:12.158   278   437 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-11 11:56:12.158   278   437 W Vold    : Returning OperationFailed - no handler for errno 0
09-11 11:56:12.159  7292  7327 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-11 11:56:12.163   278   437 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-11 11:56:12.163   278   437 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-11 11:56:12.163   278   437 W Vold    : Returning OperationFailed - no handler for errno 0
09-11 11:56:12.163  7292  7345 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-11 11:56:12.165   278   437 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-11 11:56:12.165   278   437 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-11 11:56:12.165   278   437 W Vold    : Returning OperationFailed - no handler for errno 0
09-11 11:56:12.165  7292  7345 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-11 11:56:12.182  7319  7319 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-11 11:56:12.182  7319  7319 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-11 11:56:12.198  7319  7319 I MultiDex: VM with version 2.1.0 has multidex support
,09-11 11:56:12.198  7319  7319 I MultiDex: install
09-11 11:56:12.198  7319  7319 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-11 11:56:12.204  7319  7319 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-11 11:56:12.307  7292  7292 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-11 11:56:12.312  7292  7292 I LibraryLoader: Loading: webviewchromium
,09-11 11:56:12.314  7292  7292 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9783-9785)
09-11 11:56:12.315  7292  7292 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-11 11:56:12.320  7292  7292 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e95e586}
,09-11 11:56:12.325  7292  7292 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-11 11:56:12.325  7292  7292 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-11 11:56:12.345  7292  7292 I BrowserStartupController: Initializing chromium process, renderers=0
,09-11 11:56:12.347  7292  7292 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-11 11:56:12.369   311   311 V AudioPolicyService: registerClient() client 0xb14bf9a0, uid 10093
,09-11 11:56:12.371  7292  7292 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-11 11:56:12.372  7292  7292 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-11 11:56:12.372  7292  7292 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-11 11:56:12.373  7292  7378 W AudioManagerAndroid: Requires BLUETOOTH permission
09-11 11:56:12.390  7292  7292 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-11 11:56:12.390  7292  7292 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-11 11:56:12.390  7292  7292 I Adreno-EGL: Build Date: 12/12/14 금
09-11 11:56:12.390  7292  7292 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-11 11:56:12.390  7292  7292 I Adreno-EGL: Remote Branch: 
09-11 11:56:12.390  7292  7292 I Adreno-EGL: Local Patches: 
09-11 11:56:12.390  7292  7292 I Adreno-EGL: Reconstruct Branch: 
,09-11 11:56:12.405  1031  7254 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-11 11:56:12.406  1031  7254 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,09-11 11:56:12.406  1031  7254 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-11 11:56:12.406  1031  7254 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-11 11:56:12.406  1031  7254 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-11 11:56:12.406  1031  7254 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-11 11:56:12.406  1031  7254 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-11 11:56:12.406  1031  7254 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-11 11:56:12.407  1031  7254 D DhcpStateMachine: RunningState
09-11 11:56:12.464  7292  7292 I NSApplication: Starting up...
,09-11 11:56:12.516  7391  7391 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-11 11:56:12.537  1031  1946 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7394 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-11 11:56:12.540  1031  1946 I ActivityManager: Killing 6849:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-11 11:56:12.569  7391  7391 I dex2oat : dex2oat took 52.698ms (threads: 4)
,09-11 11:56:12.584  7319  7344 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-11 11:56:12.584  7319  7344 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-11 11:56:12.584  7319  7344 I Adreno-EGL: Build Date: 12/12/14 금
09-11 11:56:12.584  7319  7344 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-11 11:56:12.584  7319  7344 I Adreno-EGL: Remote Branch: 
09-11 11:56:12.584  7319  7344 I Adreno-EGL: Local Patches: 
09-11 11:56:12.584  7319  7344 I Adreno-EGL: Reconstruct Branch: 
,09-11 11:56:12.592  1031  1760 W libprocessgroup: failed to open /acct/uid_10037/pid_6849/cgroup.procs: No such file or directory
09-11 11:56:12.640  7394  7394 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-11 11:56:12.729  7319  7344 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-11 11:56:12.729  7319  7344 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-11 11:56:12.729  7319  7344 I Adreno-EGL: Build Date: 12/12/14 금
09-11 11:56:12.729  7319  7344 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-11 11:56:12.729  7319  7344 I Adreno-EGL: Remote Branch: 
09-11 11:56:12.729  7319  7344 I Adreno-EGL: Local Patches: 
09-11 11:56:12.729  7319  7344 I Adreno-EGL: Reconstruct Branch: 
,09-11 11:56:12.770  1031  1525 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-11 11:56:12.771  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-11 11:56:12.771  1031  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-11 11:56:12.771  1031  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-11 11:56:12.772  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-11 11:56:12.772  1031  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-11 11:56:12.773  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-11 11:56:12.773  1031  1531 D ConnectivityService: identical MTU - not setting
09-11 11:56:12.773  1031  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-11 11:56:12.773  1031  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-11 11:56:12.773  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:12.774  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:12.775  1031  1531 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:12.776  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-11 11:56:12.799  7319  7344 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-11 11:56:12.799  7319  7344 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-11 11:56:12.799  7319  7344 I Adreno-EGL: Build Date: 12/12/14 금
09-11 11:56:12.799  7319  7344 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-11 11:56:12.799  7319  7344 I Adreno-EGL: Remote Branch: 
09-11 11:56:12.799  7319  7344 I Adreno-EGL: Local Patches: 
09-11 11:56:12.799  7319  7344 I Adreno-EGL: Reconstruct Branch: 
,09-11 11:56:12.806  1031  1641 D WifiServiceImplEx: setWifiEnabled: false pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-11 11:56:12.806  1031  1641 D WifiService: setWifiEnabled: false pid=6629, uid=10118
09-11 11:56:12.806  1031  1641 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-11 11:56:12.816  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-11 11:56:12.816  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-11 11:56:12.816  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-11 11:56:12.819  1031  1525 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-11 11:56:12.819  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-11 11:56:12.820  1031  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-11 11:56:12.820  1031  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-11 11:56:12.820  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-11 11:56:12.820  1031  1525 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-11 11:56:12.821  1031  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-11 11:56:12.821  1031  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-11 11:56:12.821  1031  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-11 11:56:12.821  1031  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-11 11:56:12.828  1031  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-11 11:56:12.828  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-11 11:56:12.828  1031  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.828  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.828  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-11 11:56:12.828  1031  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-11 11:56:12.829  1031  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-11 11:56:12.829  1031  1525 D WifiNative-wlan0: SET ps 1: returned true
09-11 11:56:12.829   306   890 D CommandListener: Clearing all IP addresses on wlan0
,09-11 11:56:12.832  1031  7254 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.864  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-11 11:56:12.864  1031  1531 D ConnectivityService: ignoring duplicate network state non-change
09-11 11:56:12.864  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-11 11:56:12.864  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-11 11:56:12.866  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:12.866  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:12.866  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-11 11:56:12.868  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:12.868  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:12.868  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
,09-11 11:56:12.871  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:12.874  1031  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:12.874  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:12.875  1031  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:12.875  1031  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:12.875  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:12.876  1031  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:12.876  1031  1525 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-11 11:56:12.876  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-11 11:56:12.877  1031  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.877  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.877  1031  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1817dd15
09-11 11:56:12.878  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:12.878  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:12.878  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-11 11:56:12.878  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
09-11 11:56:12.878  1031  1031 D RttService: SCAN_AVAILABLE : 1
09-11 11:56:12.879  1031  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.880  1031  1544 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.880  1031  1524 D LGWifiP2pService: P2pDisablingState
09-11 11:56:12.880  1031  1524 D LGWifiP2pService: P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.880  1031  1524 D LGWifiP2pService: p2p socket connection lost
09-11 11:56:12.880  1031  1524 D LGWifiP2pService: P2pDisabledState
09-11 11:56:12.881  1031  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-11 11:56:12.881  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,09-11 11:56:12.881  7142  7142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-11 11:56:12.882  1031  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-11 11:56:12.882  1031  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-11 11:56:12.882  1031  1525 D WifiNative-wlan0: SET ps 1: returned true
09-11 11:56:12.884  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-11 11:56:12.884  1928  1928 D WfdsService: WifiP2pState is changed : false
09-11 11:56:12.885  1031  1524 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.885  1031  1524 D LGWifiP2pService: DefaultState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.886  1928  2275 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-11 11:56:12.886  1928  2275 D WfdsService: Set the WFDS Monitor: false
09-11 11:56:12.887  1928  2275 D WfdsMonitor: WFDS Monitor is stopped
09-11 11:56:12.887  1928  2275 D WfdsService: STATE : WfdsDisabledState - enter
09-11 11:56:12.887  1928  7181 D CtrlSupplicant: Received on exit socket, terminate
09-11 11:56:12.887  1928  7181 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-11 11:56:12.887  1928  7181 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-11 11:56:12.888  1928  7181 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-11 11:56:12.888  1928  2280 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-11 11:56:12.888  1928  2275 W WfdsService: DefaultState - msg [9445378] is not handled
09-11 11:56:12.893  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:12.893  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-11 11:56:12.898  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:12.906   306   890 D CommandListener: Clearing all IP addresses on wlan0
09-11 11:56:12.906  1031  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-11 11:56:12.906  1031  1531 D DSQN    : disableDataServiceNotify
09-11 11:56:12.906  1031  1531 D DSQN    : stop dsqn bin
,09-11 11:56:12.907  1031  1525 D WifiNative-p2p0: doBoolean: TERMINATE
09-11 11:56:12.909  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-11 11:56:12.909  1031  1525 D WifiNative-p2p0: TERMINATE: returned true
09-11 11:56:12.909  1031  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-11 11:56:12.909  1031  1525 E WifiStateMachine: useWiFiOffloading() : false
09-11 11:56:12.909  1031  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-11 11:56:12.910  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:12.910  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:12.910  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-11 11:56:12.911  1031  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-11 11:56:12.911  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:12.911  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:12.911  1031  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:12.911  1031  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-11 11:56:12.911  1031  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.911  1031  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.912  1031  7253 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-11 11:56:12.912  1031  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-11 11:56:12.912  1031  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-11 11:56:12.912  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-11 11:56:12.912  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:12.912  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-11 11:56:12.912  1031  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-11 11:56:12.912  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-11 11:56:12.913  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-11 11:56:12.913  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-11 11:56:12.913  1031  1031 D LocSvc_java: ignore wifi update if we, are not in OPENING or CLOSING
09-11 11:56:12.914  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:12.914  1031  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:12.914  1031  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:12.915  1031  1531 D NetworkManagementService: Removing idletimer
09-11 11:56:12.915  1031  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:12.915  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:12.915  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-11 11:56:12.916  1031  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-11 11:56:12.916  1031  1525 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:12.916  1031  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:12.917  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:12.917  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:12.917  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:12.917  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:12.917  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:12.917  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:12.917  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:12.917  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:12.917  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:12.917  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:12.917  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:12.918  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-11 11:56:12.921  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,09-11 11:56:12.921  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:12.921  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-11 11:56:12.923  6408  6446 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-11 11:56:12.924  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-11 11:56:12.924  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:12.924  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-11 11:56:12.924  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-11 11:56:12.924  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:12.924  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:12.924  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:12.924  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:12.924  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:12.924  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:12.924  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:12.924  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:12.924  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:12.924  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:12.924  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:12.924  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-11 11:56:12.926  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-11 11:56:12.926  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-11 11:56:12.926  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-11 11:56:12.928  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-11 11:56:12.937  2167  2167 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:12.939  1031  1531 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-11 11:56:12.954  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-11 11:56:12.954  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:12.954  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-11 11:56:12.954  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-11 11:56:12.956  7091  7091 I AppUp4:CustModeStarterReceiver: onReceive
09-11 11:56:12.958  7091  7091 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2712955f
09-11 11:56:12.958  7091  7091 D AppUp4:CustFacade: isCustomizationCompleted : false
09-11 11:56:12.958  7091  7091 D AppUp4:CustFacade: isPhone : true
09-11 11:56:12.959  7091  7091 D AppUp4:CustModeStarterReceiver: begin check event
09-11 11:56:12.959  7091  7091 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-11 11:56:12.961  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:12.961  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-11 11:56:12.961  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:12.962  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-11 11:56:12.963  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:12.963  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:12.963  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:12.964  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-11 11:56:12.968  4807  7428 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-11 11:56:12.970  7124  7124 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-11 11:56:12.972  4807  7429 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:12.972  4807  7429 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-11 11:56:12.982  7319  7344 D LgDataFeature: LgDataFeature() Constructor: none
09-11 11:56:12.983  7319  7344 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-11 11:56:12.985  7124  7431 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:12.988  3288  3288 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-11 11:56:12.988  3288  3288 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:12.988  3288  3288 I LgeMiscReceiver: networkInfo.isConnected() = false
09-11 11:56:12.990  7142  7142 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-11 11:56:12.990  7142  7142 I wpa_supplicant: monitor socket send errors count : 1
09-11 11:56:12.990  7142  7142 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-4\x00 that cannot receive messages
09-11 11:56:12.991  1031  7169 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-11 11:56:12.991  1031  7169 D WifiMonitor: Dropping event because (p2p0) is stopped
09-11 11:56:12.992  7000  7432 W FormManager: Network not available. Please check & try again.
09-11 11:56:12.993  7189  7189 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-11 11:56:12.993  7189  7189 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-11 11:56:12.994  7000  7433 V FormManager: Network unavailable.
09-11 11:56:12.995  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-11 11:56:12.996  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:12.997  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:13.002  7259  7259 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:56:13
09-11 11:56:13.003  7000  7433 V FormManager: Network unavailable.
09-11 11:56:13.003  7259  7259 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-11 11:56:13.003  7259  7259 D Weather.Utils: 2 : All the weather widget is gone.
,09-11 11:56:13.005  7259  7259 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-11 11:56:13.005  7259  7259 D WeatherAncestor: connectivity changed - connection : true
09-11 11:56:13.005  7259  7259 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@c748075
09-11 11:56:13.005  7259  7259 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-11 11:56:13.006  7259  7259 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-11 11:56:13.006  7259  7259 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-11 11:56:13.006  7259  7259 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-11 11:56:13.006  7259  7259 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:56:13
09-11 11:56:13.012  7142  7142 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-11 11:56:13.012  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,09-11 11:56:13.012  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-11 11:56:13.012  1031  7169 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-11 11:56:13.012  1031  7169 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-11 11:56:13.013  7142  7142 W wpa_supplicant: USIM:  scard_deinit function
09-11 11:56:13.013  1031  1525 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=120471
09-11 11:56:13.013  1031  1525 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=120471
09-11 11:56:13.014  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-11 11:56:13.014  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-11 11:56:13.014  1031  1525 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=120472  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-11 11:56:13.014  1031  1525 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=120472  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-11 11:56:13.017  1031  1102 D Tethering: InitialState.processMessage what=4
09-11 11:56:13.018  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-11 11:56:13.019  1031  1525 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:13.019  1031  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:13.021   306  7441 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-11 11:56:13.022  1031  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-11 11:56:13.027  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-11 11:56:13.031  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:13.033  7000  7444 V FormManager: Network unavailable.
09-11 11:56:13.034  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.035  7000  7444 V FormManager: Network unavailable.
09-11 11:56:13.040  7000  7443 W FormManager: Network not available. Please check & try again.
,09-11 11:56:13.045  1031  7254 D DhcpStateMachine: StoppedState
09-11 11:56:13.045  1031  7254 D DhcpStateMachine: StoppedState{ when=-163ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:13.046  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:13.046  6888  6888 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-11 11:56:13.046  6888  6888 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-11 11:56:13.046  6888  6888 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-11 11:56:13.046  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-11 11:56:13.047  1031  1525 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-11 11:56:13.047  1031  1525 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-11 11:56:13.048  6888  6888 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-11 11:56:13.048  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-11 11:56:13.048  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-11 11:56:13.048  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-11 11:56:13.048  6888  6888 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-11 11:56:13.048  6888  6888 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-11 11:56:13.059  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-11 11:56:13.062  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:13.067  7000  7447 W FormManager: Network not available. Please check & try again.
09-11 11:56:13.068  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.070  7000  7448 V FormManager: Network unavailable.
09-11 11:56:13.076  7000  7448 V FormManager: Network unavailable.
,09-11 11:56:13.078  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-11 11:56:13.078  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-11 11:56:13.080  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:13.081  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-11 11:56:13.084  4807  7449 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-11 11:56:13.087  4807  7450 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-11 11:56:13.087  4807  7450 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-11 11:56:13.118  1031  1918 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7451 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-11 11:56:13.135  7142  7142 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-11 11:56:13.135  1031  7169 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-11 11:56:13.136  1031  7169 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-11 11:56:13.136  1031  7169 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-11 11:56:13.136  1031  1525 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-11 11:56:13.151   306  7467 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-11 11:56:13.151  1031  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-11 11:56:13.154  1804  7282 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,09-11 11:56:13.173  1804  7282 I CheckinService: active receiver: disabled
,09-11 11:56:13.212  7451  7451 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-11 11:56:13.212  7451  7451 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-11 11:56:13.218  7451  7451 V [BNRBootReceiver]: Boot Receiver Return
09-11 11:56:13.218  7451  7451 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-11 11:56:13.221  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:13.227  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.233  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.237  1031  1525 D WifiOffDelayIfNotUsed: stopMonitoring
09-11 11:56:13.237  1031  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-11 11:56:13.237  1031  1525 E WifiStateMachine: useWiFiOffloading() : false
09-11 11:56:13.237  1031  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-11 11:56:13.239  1928  1928 D WfdsService: Supplicant Connection state is changed : false
09-11 11:56:13.239  1928  2275 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,09-11 11:56:13.239  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-11 11:56:13.240  1928  2275 D WfdsService: Set the WFDS Monitor: false
09-11 11:56:13.240  1928  2275 D WfdsMonitor: WFDS Monitor is stopped
09-11 11:56:13.240  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:13.241  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-11 11:56:13.241  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-11 11:56:13.241  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-11 11:56:13.242  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:13.243  2489  2489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:13.243  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:13.248  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:13.249  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:13.250  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-11 11:56:13.254  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-11 11:56:13.258  6888  6888 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-11 11:56:13.261  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:13.268  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.275  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.281  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:13.282  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:13.283  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-11 11:56:13.287  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:13.294  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.302  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.311  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-11 11:56:13.312  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:13.312  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-11 11:56:13.316  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:13.324  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.334  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-11 11:56:13.346  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-11 11:56:13.347  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:13.348  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-11 11:56:13.353  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:13.364  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.375  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.384  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:13.385  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:13.386  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-11 11:56:13.391  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:13.402  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.413  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.426  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:13.427  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:13.427  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-11 11:56:13.435  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:13.446  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.459  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.468  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:13.468  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:13.469  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-11 11:56:13.479  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:13.498  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.512  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.529  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:13.530  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:13.537  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-11 11:56:13.547  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:13.577  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.587  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.596  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:13.597  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:13.598  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-11 11:56:13.604  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:13.613  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-11 11:56:13.624  1031  1530 D WifiService: New client listening to asynchronous messages
09-11 11:56:13.625  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:13.629  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.636  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-11 11:56:13.648  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:13.648  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:13.651  6940  6940 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-11 11:56:13.653  6940  6940 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-11 11:56:13.654  6940  6940 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-11 11:56:13.661  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:13.671  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-11 11:56:13.673  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:13.678  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.688  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.702  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:13.703  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:13.705  6940  6940 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-11 11:56:13.707  6940  6940 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-11 11:56:13.709  6940  6940 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-11 11:56:13.717  1031  1760 I ActivityManager: Killing 6957:com.lge.settings.easy/1000 (adj 15): empty #17
,09-11 11:56:13.780  1031  1562 W libprocessgroup: failed to open /acct/uid_1000/pid_6957/cgroup.procs: No such file or directory
,09-11 11:56:13.785  2167  2167 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-11 11:56:13.803  2167  2167 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-11 11:56:13.804  2167  2167 D c       : Getting all permits...
09-11 11:56:13.804  2167  2167 D a       : Opening database...
09-11 11:56:13.811  2167  2167 D a       : Opening database auth.proximity.permit_store...
09-11 11:56:13.812  2167  2167 D a       : Closing database...
09-11 11:56:13.831  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:13.834  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-11 11:56:13.834  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-11 11:56:13.835  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:13.838  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.846  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.857  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:13.857  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:13.860  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-11 11:56:13.868  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:13.874  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-11 11:56:13.874  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-11 11:56:13.874  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:13.880  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.891  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.904  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-11 11:56:13.904  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:13.905  6806  7070 D UEI.SmartControl: Internal timer expired: 2
09-11 11:56:13.905  6806  7070 D UEI.SmartControl: unbind internal service,
09-11 11:56:13.907  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-11 11:56:13.914  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:13.920  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-11 11:56:13.920  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-11 11:56:13.921  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:13.928  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:13.940  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.950  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:13.951  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:13.953  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-11 11:56:13.957  6806  7064 D serial_port: close(fd = 24)
09-11 11:56:13.963  6806  7064 I UEI.SmartControl: Serial port is closed.
09-11 11:56:13.967  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-11 11:56:13.972  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:13.988  7000  7479 V FormManager: Network unavailable.
09-11 11:56:13.990  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:13.993  7000  7478 W FormManager: Network not available. Please check & try again.
,09-11 11:56:14.003  7000  7479 V FormManager: Network unavailable.
09-11 11:56:14.029  2167  2167 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-11 11:56:14.053  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-11 11:56:14.054  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-11 11:56:14.057  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:14.061  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:14.070  6906  6906 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-11 11:56:14.070  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-11 11:56:14.070  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-11 11:56:14.072  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:14.073  4807  7480 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-11 11:56:14.079  4807  7482 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-11 11:56:14.079  4807  7482 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-11 11:56:14.084  7000  7483 W FormManager: Network not available. Please check & try again.
,09-11 11:56:14.085  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:14.101  7000  7484 V FormManager: Network unavailable.
,09-11 11:56:14.104  7000  7484 V FormManager: Network unavailable.
,09-11 11:56:14.109  7000  7481 W art     : No such thread id for suspend: 15
,09-11 11:56:14.781  1031  1525 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:413992253] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-11 11:56:14.783  1031  1525 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:413992255] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-11 11:56:14.882  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:14.895  1031  1102 D Tethering: MasterInitialState.processMessage what=3
09-11 11:56:14.906  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:14.910  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:14.915  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-11 11:56:14.916  6408  6446 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-11 11:56:14.922  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:14.930  5803  5803 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-11 11:56:14.957  2167  2167 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:14.983  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-11 11:56:14.983  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:14.983  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-11 11:56:14.983  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-11 11:56:14.989  7091  7091 I AppUp4:CustModeStarterReceiver: onReceive
09-11 11:56:14.996  7091  7091 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2712955f
09-11 11:56:14.996  7091  7091 D AppUp4:CustFacade: isCustomizationCompleted : false
09-11 11:56:14.996  7091  7091 D AppUp4:CustFacade: isPhone : true
,09-11 11:56:14.999  7091  7091 D AppUp4:CustModeStarterReceiver: begin check event
09-11 11:56:14.999  7091  7091 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-11 11:56:15.005  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:15.005  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-11 11:56:15.006  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:15.010  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-11 11:56:15.024  7124  7124 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-11 11:56:15.063  3288  3288 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-11 11:56:15.063  3288  3288 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:15.064  3288  3288 I LgeMiscReceiver: networkInfo.isConnected() = true
09-11 11:56:15.064  3288  3288 D PhoneState: setPdpRejectCasuse : false
,09-11 11:56:15.066  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:15.067  7189  7189 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-11 11:56:15.067  7189  7189 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-11 11:56:15.072  4807  7504 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-11 11:56:15.073  4807  7512 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:15.073  4807  7512 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-11 11:56:15.090  7124  7505 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:15.090  7000  7508 W FormManager: Network not available. Please check & try again.
,09-11 11:56:15.091  7259  7259 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:56:15
,09-11 11:56:15.094  7259  7259 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-11 11:56:15.094  7259  7259 D Weather.Utils: 2 : All the weather widget is gone.
,09-11 11:56:15.094  7000  7509 V FormManager: Network unavailable.
09-11 11:56:15.095  7259  7259 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-11 11:56:15.095  7259  7259 D WeatherAncestor: connectivity changed - connection : true
,09-11 11:56:15.095  7259  7259 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@c748075
,09-11 11:56:15.097  7259  7259 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-11 11:56:15.097  7259  7259 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-11 11:56:15.097  7259  7259 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-11 11:56:15.097  7259  7259 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-11 11:56:15.098  7259  7259 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:56:15
09-11 11:56:15.098  7000  7509 V FormManager: Network unavailable.
,09-11 11:56:15.823  1031  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:15.823  1031  1946 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-11 11:56:15.854  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-11 11:56:15.854  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-11 11:56:15.854  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-11 11:56:15.855  1031  1102 D BluetoothManagerService: Message: 1
09-11 11:56:15.855  1031  1102 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-11 11:56:15.882  1031  1102 D BluetoothManagerService: Message: 20
09-11 11:56:15.882  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a6903df:true
,09-11 11:56:15.886  7017  7017 D BluetoothAdapterState: make
09-11 11:56:15.891  7017  7017 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-11 11:56:15.891  7017  7017 I bluedroid-qcom: init
09-11 11:56:15.893  7017  7524 I BluetoothAdapterState: Entering OffState
09-11 11:56:15.893  7017  7017 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-11 11:56:15.893  7017  7017 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-11 11:56:15.893  7017  7017 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-11 11:56:15.893  7017  7017 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-11 11:56:15.893  7017  7017 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-11 11:56:15.895  7017  7017 I bluedroid-qcom: get_profile_interface socket
09-11 11:56:15.895  7017  7017 I bluedroid-qcom: get_profile_interface map_client
,09-11 11:56:15.900  7017  7528 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-11 11:56:15.889  7527  7527 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:15.889  7527  7527 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:15.910  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-11 11:56:15.913  1031  1102 D BluetoothManagerService: Message: 40
09-11 11:56:15.913  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-11 11:56:15.913  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:15.920  7527  7527 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-11 11:56:15.920  7527  7527 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-11 11:56:15.920  7527  7527 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-11 11:56:15.923  7527  7527 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-11 11:56:15.930  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:15.931  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:15.932  7527  7527 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-11 11:56:15.932  7527  7527 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-11 11:56:15.935  7017  7036 I bluedroid-qcom: config_hci_snoop_log
,09-11 11:56:15.939  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-11 11:56:15.939  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-11 11:56:15.941  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:15.951  7017  7528 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-11 11:56:15.953  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:15.956  7017  7524 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-11 11:56:15.956  1031  1102 D Tethering: MasterInitialState.processMessage what=3
09-11 11:56:15.956  1031  1102 D Tethering: MasterInitialState.processMessage what=3
09-11 11:56:15.963  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:15.967  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:15.972  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-11 11:56:15.973  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
09-11 11:56:15.975  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:15.977  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:15.977  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:15.984  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-11 11:56:15.989  7017  7528 D BluetoothAdapterProperties: Name is: G3
09-11 11:56:15.991  5803  5803 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-11 11:56:15.991  7017  7524 D BluetoothAdapterProperties: Setting state to 11
09-11 11:56:15.991  7017  7524 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-11 11:56:15.992  6408  6446 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-11 11:56:15.993  1031  1102 D BluetoothManagerService: Message: 60
09-11 11:56:15.993  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-11 11:56:15.993  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-11 11:56:15.995  7017  7524 I LGBluetoothServiceJni: classInitNative: succeeds
09-11 11:56:15.999  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:16.000  6888  6888 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-11 11:56:16.005  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-11 11:56:16.009  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:16.011  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:16.011  7017  7524 D BluetoothBondStateMachine: make
09-11 11:56:16.014  7017  7524 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
,09-11 11:56:16.014  7017  7524 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-11 11:56:16.014  7017  7524 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:16.014  7017  7524 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-11 11:56:16.015  7017  7524 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-11 11:56:16.016  7017  7544 I BluetoothBondStateMachine: StableState(): Entering Off State
09-11 11:56:16.020  7017  7524 E BluetoothAdapterService: File transfer profiles supported!!
09-11 11:56:16.023  7017  7017 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-11 11:56:16.025  7017  7017 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:16.025  7017  7017 V BluetoothPbapReceiver: ***********state = 11
09-11 11:56:16.026  5803  5803 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-11 11:56:16.027  7017  7524 E BluetoothAdapterService: File transfer profiles supported!!
09-11 11:56:16.031  2167  2167 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-11 11:56:16.032  7017  7017 D HeadsetService: Received start request. Starting profile...
09-11 11:56:16.032  7017  7017 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-11 11:56:16.032  7017  7017 D LGBluetoothHfpAdapter: Version 1.6
09-11 11:56:16.035  7017  7017 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-11 11:56:16.036  7017  7524 E BluetoothAdapterService: File transfer profiles supported!!
09-11 11:56:16.036  7017  7017 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-11 11:56:16.037  7017  7017 D HeadsetStateMachine: make
09-11 11:56:16.066  7017  7017 D LgDataFeature: LgDataFeature() Constructor: none
,09-11 11:56:16.067  7017  7017 D LgDataFeature: LgDataFeature() Constructor Done, null
09-11 11:56:16.075  1031  1983 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7550 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-11 11:56:16.077  7017  7017 D HeadsetStateMachine: max_hf_connections = 1
,09-11 11:56:16.077  7017  7017 I bluedroid-qcom: get_profile_interface handsfree
09-11 11:56:16.079  7017  7017 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-11 11:56:16.081   311  1773 V AudioPolicyService: registerClient() client 0xb14bfde0, uid 1002
09-11 11:56:16.081   311   311 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-11 11:56:16.081   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-11 11:56:16.081   311   311 V AudioPolicyManagerEx: getOutput() returns output 2
09-11 11:56:16.081  7017  7017 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-11 11:56:16.082   311  1370 V AudioFlinger: registerClient() client 0xb14330a0, pid 7017
09-11 11:56:16.082   311  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:16.082   311  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-11 11:56:16.083  3288  3310 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:16.083  3288  3310 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-11 11:56:16.083  1031  1945 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:16.083  1031  1945 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-11 11:56:16.083  1588  3178 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:16.083  1588  3178 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-11 11:56:16.083  7017  7037 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:16.083  7017  7037 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-11 11:56:16.083  1839  3424 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:16.083  1839  3424 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-11 11:56:16.083   311  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:16.083   311  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-11 11:56:16.083  1588  2086 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:16.083  1588  2086 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-11 11:56:16.084  1839  2389 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:16.084  1839  2389 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-11 11:56:16.084  1031  1048 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:16.084  1031  1048 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-11 11:56:16.084  3288  3306 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:16.084  7017  7036 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:16.084  3288  3306 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-11 11:56:16.084  7017  7036 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
,09-11 11:56:16.084  7017  7017 V ToneGenerator: Create Track: 0xb4928080
09-11 11:56:16.084  7017  7017 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-11 11:56:16.084  7017  7017 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-11 11:56:16.085   311  1773 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-11 11:56:16.085   311  1773 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-11 11:56:16.085   311  1773 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-11 11:56:16.085   311  1773 V AudioPolicyManagerEx: getOutput() returns output 2
09-11 11:56:16.085   311  1369 I AudioFlinger: isAudioPlaybackHookOn() false
09-11 11:56:16.086  7017  7524 E BluetoothAdapterService: File transfer profiles supported!!
09-11 11:56:16.086   311  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-11 11:56:16.086   311  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-11 11:56:16.086   311  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-11 11:56:16.086   311  1369 V AudioPolicyManagerEx: getOutput() returns output 2
09-11 11:56:16.087  7017  7017 V AudioSystem: getLatency() output 2, latency 50
09-11 11:56:16.087  7017  7017 V AudioSystem: getFrameCount() output 2, frameCount 960
09-11 11:56:16.087  7017  7017 V AudioTrack: createTrack_l() output 2 afLatency 50
09-11 11:56:16.087   311  1773 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-11 11:56:16.087   311  1773 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-11 11:56:16.087   311  1773 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-11 11:56:16.087   311  1773 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-11 11:56:16.087   311  1773 V AudioFlinger: createTrack() lSessionId: 22
09-11 11:56:16.088  7017  7017 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-11 11:56:16.089   311  1773 V AudioFlinger: acquiring 22 from 7017, for 7017
09-11 11:56:16.089   311  1773 V AudioFlinger:  added new entry for 22
09-11 11:56:16.090  7017  7017 V ToneGenerator: ToneGenerator INIT OK, time: 123561
09-11 11:56:16.090  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:16.090  7017  7548 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-11 11:56:16.090  7017  7548 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,09-11 11:56:16.090  7017  7548 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-11 11:56:16.091  7017  7548 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-11 11:56:16.091  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:16.093  7017  7017 D A2dpService: Received start request. Starting profile...
09-11 11:56:16.094  7017  7017 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-11 11:56:16.095  7017  7017 V Avrcp   : make
09-11 11:56:16.095  7017  7017 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-11 11:56:16.095  7017  7017 I bluedroid-qcom: get_profile_interface avrcp
09-11 11:56:16.095   311  1370 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7017
09-11 11:56:16.096   311  1370 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-11 11:56:16.096   311  1370 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-11 11:56:16.096   311  1370 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-11 11:56:16.096   311  1370 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-11 11:56:16.096   311  1370 V voice   : voice_set_parameters: exit with code(0)
09-11 11:56:16.096   311  1370 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-11 11:56:16.096   311  1370 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-11 11:56:16.096   311  1370 V msm8974_platform: platform_set_parameters: exit with code(0)
09-11 11:56:16.096   311  1370 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-11 11:56:16.096   311  1370 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-11 11:56:16.096   311  1370 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-11 11:56:16.097  7017  7548 V ToneGenerator: ToneGenerator destructor
09-11 11:56:16.097  7017  7548 V ToneGenerator: stopTone
09-11 11:56:16.097  7017  7548 V ToneGenerator: Delete Track: 0xb4928080
09-11 11:56:16.097  2167  2167 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:16.098  7017  7548 V AudioTrack: ~AudioTrack, releasing session id from 7017 on behalf of 7017
09-11 11:56:16.099   311   311 V AudioFlinger: releasing 22 from 7017 for 7017
09-11 11:56:16.099   311   311 V AudioFlinger:  decremented refcount to 0
09-11 11:56:16.099   311   311 V AudioFlinger: purging stale effects
09-11 11:56:16.099   311   311 V AudioPolicyService: AudioCommandThread() adding release output 2
09-11 11:56:16.099   311   311 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-11 11:56:16.099   311  1259 V AudioPolicyService: AudioCommandThread() waking up
09-11 11:56:16.099   311  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
09-11 11:56:16.099   311  1259 V AudioPolicyManager: releaseOutput() 2
09-11 11:56:16.099   311  1259 V AudioPolicyService: AudioCommandThread() going to sleep
09-11 11:56:16.099   311   311 V AudioFlinger: PlaybackThread::Track destructor
09-11 11:56:16.099   311   311 V AudioFlinger: removeClient_l() pid 7017, calling pid 311
09-11 11:56:16.100  7017  7524 E BluetoothAdapterService: File transfer profiles supported!!
09-11 11:56:16.104  7017  7017 V AudioManager: registerRemoteController: size of Media player list: 0
,09-11 11:56:16.106  7017  7017 E AudioManager: No RCC entry present to update
09-11 11:56:16.106  7017  7017 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-11 11:56:16.109  7017  7017 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-11 11:56:16.110  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-11 11:56:16.110  7017  7017 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-11 11:56:16.110  7017  7524 E BluetoothAdapterService: File transfer profiles supported!!
09-11 11:56:16.112  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-11 11:56:16.112  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:16.112  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-11 11:56:16.112  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-11 11:56:16.114  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-11 11:56:16.115  7091  7091 I AppUp4:CustModeStarterReceiver: onReceive
09-11 11:56:16.118  7017  7524 E BluetoothAdapterService: File transfer profiles supported!!
,09-11 11:56:16.125  7091  7091 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2712955f
09-11 11:56:16.125  7091  7091 D AppUp4:CustFacade: isCustomizationCompleted : false
09-11 11:56:16.125  7091  7091 D AppUp4:CustFacade: isPhone : true
09-11 11:56:16.150  7091  7091 D AppUp4:CustModeStarterReceiver: begin check event
,09-11 11:56:16.151  7091  7091 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-11 11:56:16.175  7017  7524 V LGMDMManager: Create singleton instance
09-11 11:56:16.176  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:16.176  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-11 11:56:16.178  7017  7524 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-11 11:56:16.178  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:16.181  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:16.187  7124  7124 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-11 11:56:16.189  4807  7570 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-11 11:56:16.198  7124  7572 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:16.202  1031  1927 V SIM_STK : Menu title from STK is T-Mobile
09-11 11:56:16.202  1031  1927 V SIM_STK : Menu title from STK is T-Mobile
,09-11 11:56:16.205  4807  7571 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:16.205  4807  7571 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-11 11:56:16.216  3288  3288 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-11 11:56:16.216  3288  3288 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:16.216  3288  3288 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-11 11:56:16.218  7189  7189 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-11 11:56:16.219  7189  7189 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-11 11:56:16.232  7000  7575 W FormManager: Network not available. Please check & try again.
09-11 11:56:16.232  7550  7550 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-11 11:56:16.232  7550  7550 W LG Account v2.2: No ProfileInfo entries
09-11 11:56:16.232  7550  7550 I LG Account v2.2: isEnabled: false
09-11 11:56:16.232  7550  7550 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-11 11:56:16.233  7550  7550 I Feature : [Lifetracker]Country: EU
09-11 11:56:16.233  7550  7550 I Feature : [Lifetracker]Operator: OPEN
09-11 11:56:16.233  7550  7550 I Feature : [Lifetracker]Ranking support: false
09-11 11:56:16.233  7550  7550 I Feature : [Lifetracker]Comfort support: false
09-11 11:56:16.233  7550  7550 I Feature : [Lifetracker]Accessory: true
09-11 11:56:16.233  7259  7259 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:56:16
09-11 11:56:16.233  7550  7550 I Feature : [Lifetracker]Health device: true
09-11 11:56:16.233  7550  7550 I Feature : [Lifetracker]Extra Pedometer: false
09-11 11:56:16.233  7550  7550 I Feature : [Lifetracker]Blood glucose device: false
09-11 11:56:16.233  7550  7550 I Feature : [Lifetracker]Device Number: 3
,09-11 11:56:16.236  7000  7576 V FormManager: Network unavailable.
09-11 11:56:16.237  7259  7259 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-11 11:56:16.237  7259  7259 D Weather.Utils: 2 : All the weather widget is gone.
09-11 11:56:16.237  7259  7259 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-11 11:56:16.237  7259  7259 D WeatherAncestor: connectivity changed - connection : true
09-11 11:56:16.238  7259  7259 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@c748075
09-11 11:56:16.238  7259  7259 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-11 11:56:16.238  7259  7259 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-11 11:56:16.238  7259  7259 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-11 11:56:16.238  7259  7259 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-11 11:56:16.239  7259  7259 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:56:16
09-11 11:56:16.245  6888  6888 D BluetoothPermissionRequest: onReceive
,09-11 11:56:16.246  7000  7576 V FormManager: Network unavailable.
09-11 11:56:16.255  1031  1945 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-11 11:56:16.255  6888  6888 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-11 11:56:16.260  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-11 11:56:16.262  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-11 11:56:16.263  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-11 11:56:16.263  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-11 11:56:16.263  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-11 11:56:16.263  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-11 11:56:16.263  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-11 11:56:16.263  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-11 11:56:16.263  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-11 11:56:16.263  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-11 11:56:16.263  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-11 11:56:16.263  7017  7017 I BluetoothA2dpServiceJni: classInitNative
09-11 11:56:16.264  7017  7017 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-11 11:56:16.264  7017  7017 D A2dpStateMachine: make
09-11 11:56:16.265  7017  7017 I bluedroid-qcom: get_profile_interface a2dp
09-11 11:56:16.265  7017  7580 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-11 11:56:16.266  7017  7017 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-11 11:56:16.267  7017  7017 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-11 11:56:16.267  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-11 11:56:16.267  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:16.267  7017  7017 D HeadsetStateMachine: Proxy object connected
09-11 11:56:16.268  7017  7017 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-11 11:56:16.268  7017  7017 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-11 11:56:16.269  7017  7579 D A2dpStateMachine: Enter Disconnected: -2
09-11 11:56:16.269  6408  6446 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-11 11:56:16.270  7017  7017 I BluetoothHidServiceJni: classInitNative: succeeds
09-11 11:56:16.271  7017  7017 D HidService: Received start request. Starting profile...
09-11 11:56:16.271  7017  7017 I bluedroid-qcom: get_profile_interface hidhost
09-11 11:56:16.271  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
,09-11 11:56:16.275  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-11 11:56:16.276  7017  7548 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-11 11:56:16.276  7017  7548 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-11 11:56:16.276  7017  7017 I BluetoothHealthServiceJni: classInitNative: succeeds
09-11 11:56:16.276  7017  7548 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-11 11:56:16.277  7017  7017 D HealthService: Received start request. Starting profile...
09-11 11:56:16.278  7017  7017 I bluedroid-qcom: get_profile_interface health
09-11 11:56:16.279  7017  7017 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-11 11:56:16.279  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:16.279  7017  7017 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-11 11:56:16.280  7017  7017 D PanService: Received start request. Starting profile...
09-11 11:56:16.280  7017  7017 D BluetoothPanServiceJni: initializeNative(L110): pan
09-11 11:56:16.280  7017  7017 I bluedroid-qcom: get_profile_interface pan
09-11 11:56:16.283  2167  2167 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:16.285  7017  7017 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-11 11:56:16.285  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:16.286  7017  7017 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-11 11:56:16.291  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-11 11:56:16.291  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:16.292  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-11 11:56:16.292  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-11 11:56:16.292  7017  7017 D BtGatt.DebugUtils: handleDebugAction() action=null
09-11 11:56:16.293  7017  7017 D BtGatt.GattService: Received start request. Starting profile...
09-11 11:56:16.293  7017  7017 D BtGatt.GattService: start()
09-11 11:56:16.293  7017  7017 I bluedroid-qcom: get_profile_interface gatt
09-11 11:56:16.293  7091  7091 I AppUp4:CustModeStarterReceiver: onReceive
09-11 11:56:16.293  7017  7017 D BtGatt.AdvertiseManager: advertise manager created
09-11 11:56:16.296  7091  7091 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2712955f
09-11 11:56:16.296  7091  7091 D AppUp4:CustFacade: isCustomizationCompleted : false
09-11 11:56:16.296  7091  7091 D AppUp4:CustFacade: isPhone : true
09-11 11:56:16.296  7091  7091 D AppUp4:CustModeStarterReceiver: begin check event
09-11 11:56:16.296  7091  7091 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-11 11:56:16.304  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:16.305  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-11 11:56:16.307  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:16.400  1031  1918 I art     : Explicit concurrent mark sweep GC freed 121065(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.430ms total 103.493ms
,09-11 11:56:16.403  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:16.407  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:16.408  7017  7017 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-11 11:56:16.410  7017  7017 V BluetoothMapService: BluetoothMapBinder()
09-11 11:56:16.412  7017  7017 D BluetoothMapService: Received start request. Starting profile...
09-11 11:56:16.412  7017  7017 D BluetoothMapService: start()
,09-11 11:56:16.414  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 ,
09-11 11:56:16.425  7017  7017 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-11 11:56:16.425  7017  7017 D BluetoothMapEmailAppObserver: createReceiver()
,09-11 11:56:16.428  7017  7017 D BluetoothMapEmailAppObserver: initObservers()
09-11 11:56:16.428  7017  7017 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-11 11:56:16.434  7124  7124 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-11 11:56:16.437  4807  7587 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-11 11:56:16.444  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:16.445  4807  7588 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:16.445  4807  7588 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-11 11:56:16.448  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-11 11:56:16.451  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-11 11:56:16.454  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-11 11:56:16.459  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-11 11:56:16.459  7017  7017 V PanService: [BTUI] SIM Extra State :ABSENT
,09-11 11:56:16.463  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-11 11:56:16.463  7017  7017 V BluetoothMapService: Handler(): got msg=1
09-11 11:56:16.464  7017  7524 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-11 11:56:16.465  7017  7524 I bluedroid-qcom: enable
09-11 11:56:16.465  7017  7593 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-11 11:56:16.465  7017  7593 I bt-btu  : btu_task pending for preload complete event
09-11 11:56:16.465  7017  7524 I bt_hci_bdroid: init
09-11 11:56:16.466  7017  7524 I bt_vendor: bt-vendor : init
09-11 11:56:16.466  7017  7524 I bt_vendor: bt-vendor : get_bt_soc_type
09-11 11:56:16.466  7017  7524 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-11 11:56:16.466  7017  7524 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-11 11:56:16.466  7017  7524 D bt_userial_mct: userial_init
09-11 11:56:16.467  7017  7524 D bt_hci_bdroid: set_power 1
09-11 11:56:16.467  7017  7524 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-11 11:56:16.467  7017  7524 I bt_vendor: Starting hciattach daemon
09-11 11:56:16.467  7017  7524 I bt_vendor: try to set true
09-11 11:56:16.468  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:16.469  7124  7590 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:16.459  7596  7596 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:16.459  7596  7596 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:16.471  7017  7017 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-11 11:56:16.471  7017  7017 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-11 11:56:16.471  7017  7017 V BluetoothSapReceiver: SapReceiver onReceive 
09-11 11:56:16.471  7017  7017 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:16.471  7017  7017 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-11 11:56:16.476  7000  7591 W FormManager: Network not available. Please check & try again.
,09-11 11:56:16.481  3288  3288 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-11 11:56:16.481  3288  3288 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:16.481  3288  3288 I LgeMiscReceiver: networkInfo.isConnected() = false
09-11 11:56:16.484  7598  7598 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
09-11 11:56:16.516  1031  1964 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7602 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-11 11:56:16.519  7189  7189 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-11 11:56:16.520  7189  7189 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-11 11:56:16.532  7259  7259 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:56:16
09-11 11:56:16.533  7259  7259 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-11 11:56:16.533  7259  7259 D Weather.Utils: 2 : All the weather widget is gone.
,09-11 11:56:16.535   340   340 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 377us total 20.191ms
09-11 11:56:16.538  7259  7259 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-11 11:56:16.538  7259  7259 D WeatherAncestor: connectivity changed - connection : true
09-11 11:56:16.538  7259  7259 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@c748075
09-11 11:56:16.546  7259  7259 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-11 11:56:16.546  7259  7259 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-11 11:56:16.546  7259  7259 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-11 11:56:16.549  7259  7259 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-11 11:56:16.549  7259  7259 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:56:16
09-11 11:56:16.550  7000  7592 V FormManager: Network unavailable.
09-11 11:56:16.552   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 397us total 16.415ms
09-11 11:56:16.561  7000  7592 V FormManager: Network unavailable.
09-11 11:56:16.564  7621  7621 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-11 11:56:16.566   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 14.337ms
09-11 11:56:16.567  7602  7602 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-11 11:56:16.574  7622  7622 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-11 11:56:16.584  1031  1760 I ActivityManager: Killing 7143:com.android.vending/u0a44 (adj 15): empty #17
,09-11 11:56:16.593  7624  7624 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-11 11:56:16.599  7625  7625 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-11 11:56:16.609  7626  7626 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-11 11:56:16.618  7627  7627 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-11 11:56:16.630  1031  2000 W libprocessgroup: failed to open /acct/uid_10044/pid_7143/cgroup.procs: No such file or directory
09-11 11:56:16.637  7629  7629 I libmdmdetect: ESOC framework not supported
,09-11 11:56:16.637  7629  7629 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-11 11:56:16.645  7629  7629 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-11 11:56:16.645  7629  7629 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-11 11:56:16.645  7629  7629 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-11 11:56:16.645  7629  7629 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-11 11:56:16.645  7629  7629 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-11 11:56:16.645  7629  7629 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-11 11:56:16.645  7629  7629 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-11 11:56:16.680  7629  7630 E QC-QMI  : qmi_client [7629] 14: failed to locate client data
09-11 11:56:16.681   461   461 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-11 11:56:16.681   461   461 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-11 11:56:16.720  7631  7631 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-11 11:56:16.742  7632  7632 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-11 11:56:16.768  7017  7524 I bt_vendor: bluetooth satus is on
,09-11 11:56:16.769  7017  7524 D bt_hci_bdroid: preload
09-11 11:56:16.769  7017  7595 D bt_userial_mct: userial_open(port:0)
09-11 11:56:16.769  7017  7595 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-11 11:56:16.773  7017  7595 I bt_vendor: Done intiailizing UART
,09-11 11:56:16.775  7017  7595 I bt_vendor: Done intiailizing UART
09-11 11:56:16.776  7017  7595 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-11 11:56:16.776  7017  7595 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-11 11:56:16.776  7017  7634 D bt_userial_mct: Entering userial_read_thread()
,09-11 11:56:16.776  7017  7593 I bt-btu  : btu_task received preload complete event
09-11 11:56:16.777  7017  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-11 11:56:16.777  7017  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-11 11:56:16.779  7017  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_HCI
,09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_AVDT
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_A2D
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_BNEP
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_BTM
,09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_GAP
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_PAN
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_SDP
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_GATT,
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_SMP
,09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-11 11:56:16.782  7017  7593 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-11 11:56:16.848  7017  7593 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-11 11:56:16.848  7017  7593 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0212061 
,09-11 11:56:16.848  7017  7593 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0212061 
09-11 11:56:16.853  1031  1098 W ProcessCpuTracker: Skipping unknown process pid 7537
09-11 11:56:16.855  1031  1098 W ProcessCpuTracker: Skipping unknown process pid 7540
,09-11 11:56:16.860  7017  7528 E bt-btif : Calling BTA_HhEnable
09-11 11:56:16.860  7017  7528 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-11 11:56:16.861  7017  7528 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-11 11:56:16.861  7017  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-11 11:56:16.862  7017  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-11 11:56:16.862  7017  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-11 11:56:16.862  7017  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-11 11:56:16.862  7017  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-11 11:56:16.862  7017  7528 D BluetoothAdapterProperties: Name is: G3
,09-11 11:56:16.863  7017  7528 D BluetoothAdapterProperties: Scan Mode:20
09-11 11:56:16.863  7017  7528 D BluetoothAdapterProperties: Discoverable Timeout:120
09-11 11:56:16.864  7017  7528 D bt_hci_bdroid: postload
09-11 11:56:16.864  7017  7595 D bt_hci_bdroid: Used up Tx Cmd credits
09-11 11:56:16.864  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-11 11:56:16.865  7017  7528 D bte_conf: Device ID record 1 : primary
09-11 11:56:16.865  7017  7528 D bte_conf:   vendorId            = 00c4
09-11 11:56:16.865  7017  7528 D bte_conf:   vendorIdSource      = 0001
09-11 11:56:16.865  7017  7528 D bte_conf:   product             = 13a1
09-11 11:56:16.865  7017  7528 D bte_conf:   version             = 1000
09-11 11:56:16.865  7017  7528 D bte_conf:   clientExecutableURL = 
09-11 11:56:16.865  7017  7528 D bte_conf:   serviceDescription  = 
09-11 11:56:16.865  7017  7528 D bte_conf:   documentationURL    = 
09-11 11:56:16.865  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
09-11 11:56:16.865  7017  7528 D bte_conf: bte_load_did_conf no section named DID2.
09-11 11:56:16.849  7639  7639 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:16.868  7017  7524 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-11 11:56:16.868  7017  7593 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-11 11:56:16.868  7017  7524 D BluetoothAdapterProperties: ScanMode =  20
09-11 11:56:16.868  7017  7595 D bt_hci_bdroid: Used up Tx Cmd credits
09-11 11:56:16.849  7639  7639 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:16.868  7017  7524 D BluetoothAdapterProperties: State =  11
09-11 11:56:16.868  7017  7528 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-11 11:56:16.868  7017  7524 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-11 11:56:16.869  7017  7524 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-11 11:56:16.869  7017  7524 D BluetoothAdapterProperties: Setting state to 12
09-11 11:56:16.869  7017  7524 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-11 11:56:16.870  1031  1102 D BluetoothManagerService: Message: 60
09-11 11:56:16.870  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-11 11:56:16.870  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-11 11:56:16.870  7017  7634 E bt_mct  : hci lib postload completed
09-11 11:56:16.870  7017  7528 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-11 11:56:16.870  7017  7524 I BluetoothAdapterState: Entering On State
09-11 11:56:16.872  1839  2389 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:16.874  7017  7524 D LGBluetoothServiceAdapter: [BTUI] OnState
09-11 11:56:16.874  7017  7524 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-11 11:56:16.874  7017  7524 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-11 11:56:16.877  1839  3425 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-11 11:56:16.881  1839  1839 D BluetoothHeadset: Proxy object connected
09-11 11:56:16.881  7017  7524 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-11 11:56:16.885  7017  7528 D BluetoothAdapterProperties: Discoverable Timeout:120
09-11 11:56:16.885  7017  7528 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-11 11:56:16.886  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:16.886  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:16.886  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:16.886  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:16.886  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:16.886  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:16.886  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:16.886  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:16.886  7017  7593 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-11 11:56:16.887  7017  7593 W bt-smp  : Plain text(LSB ~ MSB) = 7e ea 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-11 11:56:16.887  7017  7593 W bt-smp  : Encrypted text(LSB ~ MSB) = 0c a4 1f 9a c2 99 ab 16 36 91 b2 d5 ba bc 3f 45 
09-11 11:56:16.887  7017  7593 W bt-btm  : Stopping oneshot timer
09-11 11:56:16.887  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:16.889  1839  1839 D BluetoothHeadset: Proxy object connected
,09-11 11:56:16.891  6888  6993 D BluetoothMap: onBluetoothStateChange: up=true
09-11 11:56:16.892  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:16.892  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:16.892  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:16.892  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:16.892  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:16.892  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:16.892  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:16.892  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:16.895  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:16.897  6888  6904 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-11 11:56:16.897  6888  6888 D BluetoothMap: Proxy object connected
09-11 11:56:16.898  6888  6888 D MapProfile: Bluetooth service connected
09-11 11:56:16.898  6888  6888 D BluetoothMap: getConnectedDevices()
,09-11 11:56:16.899  7017  7037 V BluetoothMapService: getConnectedDevices()
09-11 11:56:16.900  1839  2389 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:16.901  6888  6888 D BluetoothInputDevice: Proxy object connected
09-11 11:56:16.901  6888  6888 D HidProfile: Bluetooth service connected
09-11 11:56:16.902  1839  1839 D BluetoothHeadset: Proxy object connected
09-11 11:56:16.903  6888  6905 D BluetoothPan: onBluetoothStateChange on: true
09-11 11:56:16.903  6888  6905 D BluetoothPan: onBluetoothStateChange call bindService
,09-11 11:56:16.904  7017  7593 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-11 11:56:16.904  7017  7593 W bt-smp  : Plain text(LSB ~ MSB) = 9b 4e 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-11 11:56:16.904  7017  7593 W bt-smp  : Encrypted text(LSB ~ MSB) = 87 51 4b 67 1f cc 61 5a b3 33 45 5e 97 94 4a fc 
09-11 11:56:16.904  7017  7593 W bt-btm  : Stopping oneshot timer
09-11 11:56:16.907  6888  6904 D BluetoothPbap: onBluetoothStateChange: up=true
09-11 11:56:16.911  6888  6888 D BluetoothPan: BluetoothPAN Proxy object connected
09-11 11:56:16.911  6888  6888 D PanProfile: Bluetooth service connected
09-11 11:56:16.911  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:16.911  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=true
09-11 11:56:16.912  1031  1031 D BluetoothHeadset: Proxy object connected
09-11 11:56:16.913  1031  1102 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-11 11:56:16.913  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-11 11:56:16.916  1031  1031 D BluetoothA2dp: Proxy object connected
,09-11 11:56:16.919  7017  7593 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-11 11:56:16.919  7017  7593 W bt-smp  : Plain text(LSB ~ MSB) = 5d 6b 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-11 11:56:16.919  7017  7593 W bt-smp  : Encrypted text(LSB ~ MSB) = 63 04 a5 c8 d3 b1 bb c6 c1 f4 85 45 88 4e 70 a5 
09-11 11:56:16.919  7017  7593 W bt-btm  : Stopping oneshot timer
09-11 11:56:16.920  7017  7524 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-11 11:56:16.921  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-11 11:56:16.923  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:16.923  1928  2115 D LGBluetoothAPIService: Message: 1
09-11 11:56:16.923  1928  2115 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-11 11:56:16.929  7645  7645 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-11 11:56:16.932  7017  7593 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-11 11:56:16.933  7017  7593 W bt-smp  : Plain text(LSB ~ MSB) = 6d 41 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-11 11:56:16.933  7017  7593 W bt-smp  : Encrypted text(LSB ~ MSB) = 93 bb a6 1b 6a 92 a4 ce 21 61 68 d2 63 6f 10 36 
09-11 11:56:16.933  7017  7593 W bt-btm  : Stopping oneshot timer
09-11 11:56:16.934  7017  7017 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:16.934  7017  7017 D BluetoothMapService: STATE_ON
09-11 11:56:16.935  6888  6888 D LocalBluetoothProfileManager: Adding local A2DP profile
09-11 11:56:16.936  7017  7017 D LGBluetoothAPIServer: [BTUI] onCreate()
09-11 11:56:16.936  7017  7017 D LGBluetoothAPIServer: [BTUI] onBind()
09-11 11:56:16.937  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-11 11:56:16.937  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-11 11:56:16.938  1031  1102 D BluetoothManagerService: Message: 40
09-11 11:56:16.938  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-11 11:56:16.938  1031  1102 D BluetoothManagerService: Message: 30
09-11 11:56:16.939  1928  2115 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-11 11:56:16.939  1928  2115 D LGBluetoothAPIService: Message: 100
09-11 11:56:16.939  1928  2115 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-11 11:56:16.941  6629  6629 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-11 11:56:16.942  6888  6888 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-11 11:56:16.943  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:16.944  7017  7593 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-11 11:56:16.944  7017  7593 W bt-smp  : Plain text(LSB ~ MSB) = 58 44 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-11 11:56:16.944  7017  7593 W bt-smp  : Encrypted text(LSB ~ MSB) = 27 ee 92 9a 2f 86 4e 8f fb 02 ed 45 ca 80 fc 07 
09-11 11:56:16.944  7017  7593 W bt-btm  : Stopping oneshot timer
09-11 11:56:16.944  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:16.947  1031  1102 D BluetoothManagerService: Message: 30
09-11 11:56:16.953  6888  6888 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-11 11:56:16.954  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:16.954  7017  7017 V BluetoothPbapService: Pbap Service onCreate
09-11 11:56:16.954  7017  7017 V BluetoothPbapService: Starting PBAP service
09-11 11:56:16.955  6888  6888 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-11 11:56:16.956  7017  7017 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,09-11 11:56:16.956  7017  7017 V BluetoothPbapService: Pbap Service onBind
09-11 11:56:16.959  6888  6888 D BluetoothA2dp: Proxy object connected
09-11 11:56:16.959  7017  7017 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:16.960  6888  6888 D A2dpProfile: Bluetooth service connected
09-11 11:56:16.960  7017  7017 V BluetoothPbapService: state: 12
09-11 11:56:16.960  7017  7017 V BluetoothMapService: Handler(): got msg=1
09-11 11:56:16.961  7017  7017 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-11 11:56:16.961  7017  7017 V BluetoothPbapService: Handler(): got msg=1
09-11 11:56:16.962  7017  7017 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-11 11:56:16.962  6888  6888 D BluetoothHeadset: Proxy object connected
09-11 11:56:16.962  7017  7017 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-11 11:56:16.962  7017  7017 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:16.962  7017  7017 V BluetoothPbapReceiver: ***********state = 12
09-11 11:56:16.963  6888  6888 D HeadsetProfile: Bluetooth service connected
09-11 11:56:16.963  7017  7652 V BluetoothPbapService: Pbap Service initSocket
09-11 11:56:16.965  7017  7651 D BluetoothMapMasInstance: MAS initSocket()
09-11 11:56:16.965  1031  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:16.965  2167  2167 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-11 11:56:16.965  7017  7651 D BluetoothMapMasInstance:   masId = 00
09-11 11:56:16.965  7017  7651 D BluetoothMapMasInstance:   msgTypes = 0e
09-11 11:56:16.965  7017  7651 D BluetoothMapMasInstance:   masName = SMS/MMS
09-11 11:56:16.965  7017  7651 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-11 11:56:16.966  1031  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:16.966  2167  2167 D c       : Getting all permits...
09-11 11:56:16.966  2167  2167 D a       : Opening database...
,09-11 11:56:16.969  7017  7651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:16.970  7017  7652 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:16.971  7017  7528 D BluetoothAdapterProperties: Scan Mode:21
09-11 11:56:16.971  7017  7651 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-11 11:56:16.971  7017  7528 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,09-11 11:56:16.971  7017  7651 V BluetoothMapMasInstance: Succeed to create listening socket 
09-11 11:56:16.972  7017  7651 D BluetoothMapMasInstance: Accepting socket connection...
09-11 11:56:16.972  2167  2167 D a       : Opening database auth.proximity.permit_store...
09-11 11:56:16.972  2167  2167 D a       : Closing database...
09-11 11:56:16.974  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:16.975  7017  7652 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-11 11:56:16.975  7017  7652 V BluetoothPbapService: Succeed to create listening socket 
09-11 11:56:16.975  7017  7652 V BluetoothPbapService: Accepting socket connection...
09-11 11:56:16.976  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:16.976  6888  6888 D DockEventReceiver: finishStartingService: stopping service
09-11 11:56:16.977  6888  6888 D BluetoothPbap: Proxy object connected
09-11 11:56:16.977  6888  6888 D PbapServerProfile: Bluetooth service connected
,09-11 11:56:16.984  6888  6888 D BluetoothPermissionRequest: onReceive
09-11 11:56:16.987  6888  6888 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-11 11:56:16.988  6888  6888 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-11 11:56:16.991  7017  7017 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-11 11:56:16.992  7017  7017 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-11 11:56:16.997  7017  7017 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-11 11:56:17.016  7017  7017 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-11 11:56:17.016  7017  7017 V BtOppService: onCreate
09-11 11:56:17.020  7017  7017 V BluetoothOppNotification: send message
09-11 11:56:17.023  7017  7017 V BtOppService: Starting RfcommListener
09-11 11:56:17.033  7017  7017 D BluetoothOppPreference: Dumping Names:  
09-11 11:56:17.033  7017  7017 D BluetoothOppPreference: {}
,09-11 11:56:17.033  7017  7017 D BluetoothOppPreference: Dumping Channels:  
09-11 11:56:17.033  7017  7017 D BluetoothOppPreference: {}
,09-11 11:56:17.035  7017  7017 V BtOppService: onStartCommand
09-11 11:56:17.036  7017  7660 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-11 11:56:17.037  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:17.037  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-11 11:56:17.040  7017  7017 V BluetoothOppNotification: new notify threadi!
09-11 11:56:17.041  7017  7017 V BluetoothOppNotification: send delay message
09-11 11:56:17.042  7017  7017 V BtOppService: start RfcommListener
09-11 11:56:17.045  7017  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-11 11:56:17.046  7017  7661 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-11 11:56:17.046  7017  7657 V BtOppService: Deleted complete outbound shares, number =  0
,09-11 11:56:17.049  7017  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33b69ee6 on behalf of 
09-11 11:56:17.049  7017  7661 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@350fec27 on behalf of 
09-11 11:56:17.049  7017  7657 V BtOppService: Deleted complete inbound failed shares, number = 0
09-11 11:56:17.050  7017  7657 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-11 11:56:17.050  7017  7661 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-11 11:56:17.050  7017  7017 V BtOppService: RfcommListener started
09-11 11:56:17.050  7017  7660 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-11 11:56:17.050  7017  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-11 11:56:17.051  7017  7662 V BtOppRfcommListener: Starting RFCOMM listener....
09-11 11:56:17.052  1031  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:17.053  7017  7657 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ee59ed4 on behalf of 
09-11 11:56:17.053  7017  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a21687d on behalf of 
09-11 11:56:17.054  7017  7661 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-11 11:56:17.054  7017  7662 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:17.055  7017  7660 V BluetoothOppNotification: update too frequent, put in queue
09-11 11:56:17.056  7017  7662 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-11 11:56:17.056  7017  7662 V BtOppRfcommListener: Started RFCOMM listener....
09-11 11:56:17.056  7017  7662 I BtOppRfcommListener: Accept thread started.
09-11 11:56:17.056  7017  7662 V BtOppRfcommListener: Accepting connection...
09-11 11:56:17.056  7017  7660 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-11 11:56:17.058  7017  7661 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bbdc372 on behalf of 
,09-11 11:56:17.059  7017  7661 V BluetoothOppNotification: outbound: succ-0  fail-0
09-11 11:56:17.061  7017  7661 V BluetoothOppNotification: outbound notification was removed.
09-11 11:56:17.061  7017  7661 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-11 11:56:17.062  7017  7661 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d8523c3 on behalf of 
09-11 11:56:17.063  7017  7661 V BluetoothOppNotification: inbound: succ-0  fail-0
09-11 11:56:17.064  7017  7661 V BluetoothOppNotification: inbound notification was removed.
09-11 11:56:17.064  7017  7661 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-11 11:56:17.065  7017  7661 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e67d440 on behalf of 
09-11 11:56:17.071  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
,09-11 11:56:17.071  7017  7017 V BluetoothFtpService: Ftp Service onCreate
09-11 11:56:17.071  7017  7017 I BluetoothFtpService: Ftp Service onCreate
09-11 11:56:17.071  7017  7017 V BluetoothFtpService: Ftp Service onStartCommand
09-11 11:56:17.071  7017  7017 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:17.071  7017  7017 V BluetoothFtpService: Starting Listening on sockets
09-11 11:56:17.072  7017  7017 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-11 11:56:17.072  7017  7017 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-11 11:56:17.072  7017  7017 V BluetoothSapReceiver: SapReceiver onReceive 
09-11 11:56:17.072  7017  7017 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:17.072  7017  7017 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
,09-11 11:56:17.072  7017  7017 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-11 11:56:17.074  7017  7017 V BtOppService: ContentObserver received notification
09-11 11:56:17.074  7017  7017 V BtOppService: ContentObserver received notification
09-11 11:56:17.074  7017  7017 V BluetoothFtpService: Handler(): got msg=1
09-11 11:56:17.075  7017  7017 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-11 11:56:17.075  7017  7017 V BluetoothFtpService: Ftp Service initSocket
09-11 11:56:17.079  7017  7663 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-11 11:56:17.079  7017  7663 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-11 11:56:17.080  7017  7663 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32a0a4be on behalf of 
09-11 11:56:17.080  1031  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:17.081  7017  7017 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:17.081  7017  7663 V BluetoothOppNotification: update too frequent, put in queue
09-11 11:56:17.082  7017  7663 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-11 11:56:17.082  7017  7017 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-11 11:56:17.083  7017  7017 V BluetoothFtpService: Succeed to create listening socket on channel 20
,09-11 11:56:17.085  7017  7664 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-11 11:56:17.108  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:17.109  7017  7017 V BluetoothSapService: Sap Service onCreate
,09-11 11:56:17.111  7017  7017 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:17.111  7017  7017 V BluetoothSapService: state: 12
09-11 11:56:17.111  7017  7017 V BluetoothSapService: Starting SAP server process
09-11 11:56:17.113  7017  7017 V BluetoothSapService: SAP Service startRfcommListenerThread
09-11 11:56:17.099  7665  7665 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-11 11:56:17.099  7665  7665 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:17.118  7017  7666 V BluetoothSapService: Sap Service initRfcommSocket
09-11 11:56:17.119  1031  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:17.120  7017  7666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:17.121  7017  7666 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-11 11:56:17.121  7017  7666 V BluetoothSapService: Succeed to create listening socket 
09-11 11:56:17.121  7017  7666 V BluetoothSapService: Accepting socket connection...
09-11 11:56:17.131  7665  7665 V BT_SAP  : Event pipe created
09-11 11:56:17.132  7665  7665 V BT_SAP  : create_server_socket qcom.sap.server
09-11 11:56:17.132  7665  7665 V BT_SAP  : created socket fd 6
,09-11 11:56:17.181  7292  7342 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-11 11:56:17.884  1031  1524 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-11 11:56:17.884  1031  1524 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-11 11:56:17.915  1031  1525 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-11 11:56:17.916  1031  1525 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-11 11:56:17.942  1031  2000 I ActivityManager: Killing 7451:com.lge.bnr/1000 (adj 15): empty #17
,09-11 11:56:17.974  1031  1964 W libprocessgroup: failed to open /acct/uid_1000/pid_7451/cgroup.procs: No such file or directory
,09-11 11:56:18.043  7017  7017 V BluetoothOppNotification: new notify threadi!
,09-11 11:56:18.044  7017  7017 V BluetoothOppNotification: send delay message
,09-11 11:56:18.055  7017  7678 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-11 11:56:18.060  7017  7678 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@253e4eca on behalf of 
09-11 11:56:18.061  7017  7678 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-11 11:56:18.065  7017  7678 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-11 11:56:18.067  7017  7678 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11c5483b on behalf of 
09-11 11:56:18.068  7017  7678 V BluetoothOppNotification: outbound: succ-0  fail-0
09-11 11:56:18.069  7017  7678 V BluetoothOppNotification: outbound notification was removed.
09-11 11:56:18.069  7017  7678 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-11 11:56:18.071  7017  7678 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5a3eb58 on behalf of 
09-11 11:56:18.071  7017  7678 V BluetoothOppNotification: inbound: succ-0  fail-0
09-11 11:56:18.074  7017  7678 V BluetoothOppNotification: inbound notification was removed.
09-11 11:56:18.074  7017  7678 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-11 11:56:18.077  7017  7678 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@369034b1 on behalf of 
,09-11 11:56:18.145  1031  2000 I ActivityManager: Killing 6806:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-11 11:56:18.180  6940  6940 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,09-11 11:56:18.180  6940  6940 W System.err: android.os.DeadObjectException
09-11 11:56:18.181  6940  6940 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-11 11:56:18.181  6940  6940 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,09-11 11:56:18.181  6940  6940 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,09-11 11:56:18.181  6940  6940 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-11 11:56:18.181  6940  6940 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-11 11:56:18.181  6940  6940 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,09-11 11:56:18.181  6940  6940 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-11 11:56:18.181  6940  6940 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-11 11:56:18.181  6940  6940 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:18.181  6940  6940 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:18.181  6940  6940 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:18.181  6940  6940 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:18.181  6940  6940 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:18.181  6940  6940 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:18.182  6940  6940 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-11 11:56:18.182  6940  6940 W System.err: android.os.DeadObjectException
09-11 11:56:18.182  6940  6940 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-11 11:56:18.182  6940  6940 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-11 11:56:18.182  6940  6940 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-11 11:56:18.182  6940  6940 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-11 11:56:18.182  6940  6940 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-11 11:56:18.182  6940  6940 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-11 11:56:18.182  6940  6940 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-11 11:56:18.182  6940  6940 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-11 11:56:18.182  6940  6940 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:18.182  6940  6940 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:18.183  6940  6940 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:18.183  6940  6940 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:18.183  6940  6940 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:18.183  6940  6940 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:18.183  6940  6940 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-11 11:56:18.183  6940  6940 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-11 11:56:18.203  1031  1964 W libprocessgroup: failed to open /acct/uid_1000/pid_6806/cgroup.procs: No such file or directory
09-11 11:56:18.203  1031  1964 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-11 11:56:18.210  6940  6940 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-11 11:56:18.211  6940  6940 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-11 11:56:18.252  1031  1641 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7679 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-11 11:56:18.292  6940  6940 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-11 11:56:18.348  7679  7679 D UEI.SmartControl: Quickset Services start...
,09-11 11:56:18.350  7679  7679 I UEI.SmartControl: Manufacture = LGE
,09-11 11:56:18.351  7679  7679 D UEI.SmartControl: Id = LGNevo
09-11 11:56:18.352  7679  7679 D UEI.SmartControl: File observer start...
09-11 11:56:18.353  7679  7679 E UEI.SmartControl: IR Port is disabled: false
09-11 11:56:18.353  7679  7679 D UEI.SmartControl: Starting file observer...
09-11 11:56:18.353  7679  7679 D UEI.SmartControl: Extracting JNI libs...
09-11 11:56:18.353  7679  7679 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-11 11:56:18.456  7679  7679 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-11 11:56:18.457  7679  7679 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-11 11:56:18.457  7679  7679 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-11 11:56:18.498  7679  7679 I UEI.SmartControl: --- Selecting new region: 6
,09-11 11:56:18.501  7679  7679 I UEI.SmartControl: Model = LG-D855
,09-11 11:56:18.504  7679  7679 D UEI.SmartControl: QS Service created
,09-11 11:56:18.520  7679  7679 I UEI.SmartControl: Service initServices...
,09-11 11:56:18.526  7679  7679 D UEI.SmartControl: QS start get config
,09-11 11:56:18.573  7679  7679 D UEI.SmartControl: Loading JNI Libs...
,09-11 11:56:18.830  7679  7679 I UEI.SmartControl: Supports setup maps: true
,09-11 11:56:18.834  7679  7679 D UEI.SmartControl: QS start statue = true Error code = 0
09-11 11:56:18.834  7679  7679 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-11 11:56:18.834  7679  7679 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-11 11:56:18.834  7679  7679 I UEI.SmartControl: ### init IR Blaster...
09-11 11:56:18.840  7679  7679 D serial_port: Configuring serial port
09-11 11:56:18.843  7679  7679 E UEI.SmartControl: UEIBLaster setting for 616
09-11 11:56:18.843  7679  7679 I UEI.SmartControl: Setting serial record hearder size = 2
09-11 11:56:18.844  7679  7679 I UEI.SmartControl: configuring settings for MAXQ616
09-11 11:56:18.844  7679  7679 I UEI.SmartControl: Get version...
09-11 11:56:18.860  7679  7711 D UEI.SmartControl: serial port data available: 21
,09-11 11:56:18.870  1031  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-11 11:56:18.871  1031  1873 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@62ef776 mBinding = false
09-11 11:56:18.887  7679  7679 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-11 11:56:18.887  7679  7679 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-11 11:56:18.887  7679  7679 I UEI.SmartControl: QS saving settings...
09-11 11:56:18.888  7679  7679 D UEI.SmartControl: IR Blaster version: 25672567
,09-11 11:56:18.895  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-11 11:56:18.895  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-11 11:56:18.895  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-11 11:56:18.896  1031  1102 D BluetoothManagerService: Message: 2
09-11 11:56:18.896  1031  1102 D BluetoothManagerService: Sending off request.
09-11 11:56:18.897  7017  7037 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-11 11:56:18.897  7017  7524 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-11 11:56:18.898  7017  7524 D BluetoothAdapterProperties: Setting state to 13
09-11 11:56:18.898  7017  7524 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-11 11:56:18.899  7017  7524 D BluetoothAdapterProperties: onBluetoothDisable()
09-11 11:56:18.899  7017  7524 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-11 11:56:18.901  7017  7528 D BluetoothAdapterProperties: Scan Mode:20
09-11 11:56:18.901  7017  7524 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-11 11:56:18.903  7017  7652 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:18.903  7017  7664 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:18.903  7017  7524 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-11 11:56:18.905  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:18.905  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:18.905  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:18.905  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:18.905  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:18.905  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:18.905  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:18.905  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:18.905  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:18.910  7017  7666 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:18.911  7017  7662 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:18.912  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:18.912  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:18.914  7017  7651 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-11 11:56:18.914  7017  7651 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:18.914  7017  7651 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-11 11:56:18.914  7017  7651 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-11 11:56:18.914  7017  7651 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-11 11:56:18.914  7017  7651 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-11 11:56:18.914  7017  7651 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-11 11:56:18.914  7017  7651 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-11 11:56:18.914  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:18.914  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:18.914  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:18.914  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:18.914  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:18.914  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:18.914  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:18.914  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:18.914  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:18.915  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:18.915  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:18.915  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-11 11:56:18.916  7017  7593 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-11 11:56:18.919  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-11 11:56:18.920  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-11 11:56:18.920  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-11 11:56:18.920  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-11 11:56:18.920  7017  7593 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:18.920  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-11 11:56:18.920  ,7017  7593 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:18.920  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-11 11:56:18.920  7017  7593 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:18.920  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-11 11:56:18.920  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-11 11:56:18.920  7017  7593 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-11 11:56:18.924  7679  7711 D UEI.SmartControl: serial port data available: 4
,09-11 11:56:18.954  7679  7715 I UEI.SmartControl: Device manager: loading config....
,09-11 11:56:18.954  7679  7715 D UEI.SmartControl: ----------- loading internal config...
09-11 11:56:18.954  7679  7679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-11 11:56:18.956  7679  7679 E UEI.SmartControl: Services init done
09-11 11:56:18.956  7679  7679 D UEI.SmartControl: QS Service init finished
09-11 11:56:18.957  7679  7679 D UEI.SmartControl: QS Service version name: 2.1.91
09-11 11:56:18.957  7679  7679 D UEI.SmartControl: QS Service version code: 201091
09-11 11:56:18.958  7679  7679 D UEI.SmartControl: Service requested: Control
,09-11 11:56:18.961  7679  7715 E UEI.SmartControl: Loading SETTINGS...
09-11 11:56:18.963  7679  7679 D UEI.SmartControl: Request IControl service: devices are loaded...
09-11 11:56:18.965  6940  6940 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-11 11:56:18.965  7679  7694 I UEI.SmartControl: ------ IControl API: 11
09-11 11:56:18.965  1031  1562 I ActivityManager: Killing 6940:com.lge.qremote/u0a112 (adj 15): empty #17
09-11 11:56:18.966  1031  1102 D BluetoothManagerService: Message: 60
09-11 11:56:18.966  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-11 11:56:18.966  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-11 11:56:18.966  7679  7694 I UEI.SmartControl: Registering callback...
09-11 11:56:18.969  7679  7715 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-11 11:56:18.973  7679  7714 I UEI.SmartControl: Notify AllClients services are ready: 0
09-11 11:56:18.973  7679  7714 D UEI.SmartControl: -----service ready thread exits
,09-11 11:56:19.005  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:19.007  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:19.007  6888  6888 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-11 11:56:19.008  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:19.008  1031  1918 W libprocessgroup: failed to open /acct/uid_10112/pid_6940/cgroup.procs: No such file or directory
,09-11 11:56:19.009  7017  7017 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:19.009  7017  7017 D BluetoothMapService: STATE_TURNING_OFF
09-11 11:56:19.009  7017  7017 V BluetoothMapService: Handler(): got msg=4
09-11 11:56:19.009  7017  7017 D BluetoothMapService: MAP Service closeService in
09-11 11:56:19.009  7017  7017 D BluetoothMapMasInstance: MAP Service shutdown
09-11 11:56:19.009  7017  7017 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-11 11:56:19.009  7017  7017 V BluetoothMapService: MAP Service closeService out
09-11 11:56:19.010  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-11 11:56:19.011  7017  7017 V BtOppService: Receiver DISABLED_ACTION 
09-11 11:56:19.011  7017  7017 I BtOppRfcommListener: stopping Accept Thread
09-11 11:56:19.011  7017  7017 V BtOppRfcommListener: close mBtServerSocket
09-11 11:56:19.011  7017  7017 V BtOppRfcommListener: waiting for thread to terminate
09-11 11:56:19.011  7017  7662 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-11 11:56:19.012  7017  7017 V BtOppRfcommListener: done waiting for thread to terminate
09-11 11:56:19.013  7017  7017 V BtOppService: onDestroy
09-11 11:56:19.013  7679  7679 D UEI.SmartControl: Internal service binding...
09-11 11:56:19.013  6888  6888 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-11 11:56:19.015  7017  7017 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-11 11:56:19.017  7017  7017 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-11 11:56:19.017  7017  7017 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:19.017  7017  7017 V BluetoothPbapReceiver: ***********state = 13
09-11 11:56:19.019  7017  7017 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-11 11:56:19.020  7017  7017 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:19.020  7017  7017 V BluetoothPbapService: state: 13
09-11 11:56:19.021  7017  7017 V BluetoothPbapService: Pbap Service closeService in
09-11 11:56:19.023  2167  2167 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:19.025  7017  7017 V BluetoothPbapService: successfully stopped pbap service
09-11 11:56:19.025  7017  7017 V BluetoothPbapService: Pbap Service closeService out
09-11 11:56:19.026  7017  7017 V BluetoothPbapService: Pbap Service onDestroy
09-11 11:56:19.026  7017  7017 V BluetoothPbapService: Pbap Service closeService in
09-11 11:56:19.026  7017  7017 V BluetoothPbapService: Pbap Service closeService out
09-11 11:56:19.026  7017  7017 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-11 11:56:19.026  6888  6888 D DockEventReceiver: finishStartingService: stopping service
09-11 11:56:19.027  6888  6888 D BluetoothPbap: Proxy object disconnected
09-11 11:56:19.027  6888  6888 D PbapServerProfile: Bluetooth service disconnected
09-11 11:56:19.033  6888  6888 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-11 11:56:19.036  6888  6888 D BluetoothPermissionRequest: onReceive
09-11 11:56:19.036  6888  6888 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-11 11:56:19.040  6888  6888 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-11 11:56:19.043  7017  7017 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-11 11:56:19.043  7017  7017 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-11 11:56:19.044  7017  7017 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-11 11:56:19.047  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:19.047  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-11 11:56:19.048  7017  7017 V BluetoothFtpService: Ftp Service onStartCommand
09-11 11:56:19.048  7017  7017 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:19.048  7017  7017 V BluetoothFtpService: Ftp Service closeService
09-11 11:56:19.048  7017  7017 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-11 11:56:19.049  7017  7017 V BluetoothFtpService: successfully stopped ftp service
09-11 11:56:19.049  7017  7017 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-11 11:56:19.049  7017  7017 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-11 11:56:19.049  7017  7017 V BluetoothSapReceiver: SapReceiver onReceive 
09-11 11:56:19.049  7017  7017 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:19.049  7017  7017 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-11 11:56:19.049  7017  7017 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-11 11:56:19.050  7017  7017 V BluetoothFtpService: Ftp Service onDestroy
09-11 11:56:19.050  7017  7017 V BluetoothFtpService: Ftp Service closeService
09-11 11:56:19.052  7017  7017 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:19.052  7017  7017 V BluetoothSapService: state: 13
09-11 11:56:19.052  7017  7017 V BluetoothSapService: Stopping SAP server process
09-11 11:56:19.052  7017  7017 V BluetoothSapService: Sap Service closeSapService in
09-11 11:56:19.053  7017  7017 V BluetoothSapService: Close listen Socket : 
09-11 11:56:19.053  7017  7017 V BluetoothSapService: Close rfcomm Socket : 
09-11 11:56:19.053  7017  7017 V BluetoothSapService: Close sapd  Socket : 
09-11 11:56:19.056  7017  7017 V BluetoothSapService: Sap Service closeSapService out
09-11 11:56:19.056  7017  7017 V BluetoothSapService: Sap Service onDestroy
09-11 11:56:19.056  7017  7017 V BluetoothSapService: Sap Service closeSapService in
09-11 11:56:19.058  7017  7017 V BluetoothSapService: Close listen Socket : 
09-11 11:56:19.058  7017  7017 V BluetoothSapService: Close rfcomm Socket : 
09-11 11:56:19.058  7017  7017 V BluetoothSapService: Close sapd  Socket : 
,09-11 11:56:19.061  7017  7017 V BluetoothSapService: Sap Service closeSapService out
,09-11 11:56:19.824  7017  7528 D bt_hci_bdroid: cleanup
,09-11 11:56:19.832  7017  7595 I bt_lpm  : LPM is already off!!!
09-11 11:56:19.833  7017  7634 I bt_userial_mct: exiting userial_read_thread
09-11 11:56:19.833  7017  7634 D bt_userial_mct: Leaving userial_evt_read_thread()
09-11 11:56:19.834  7017  7593 W bt-btif : ag scb idx 1 not allocated
09-11 11:56:19.834  7017  7593 E bt-btif : BTA AG is already disabled, ignoring ...
09-11 11:56:19.834  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-11 11:56:19.834  7017  7593 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:19.834  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-11 11:56:19.834  7017  7593 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:19.834  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-11 11:56:19.834  7017  7593 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:19.834  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-11 11:56:19.834  7017  7593 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:19.835  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-11 11:56:19.835  7017  7593 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:19.835  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-11 11:56:19.835  7017  7593 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:19.835  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-11 11:56:19.835  7017  7593 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:19.835  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-11 11:56:19.835  7017  7593 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:19.835  7017  7593 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-11 11:56:19.835  7017  7593 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:19.835  7017  7593 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-11 11:56:19.838  7017  7528 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-11 11:56:19.838  7017  7595 I bt_vendor: hw_epilog_process
09-11 11:56:19.841  7017  7528 D bt_hci_bdroid: cleanup Finalizing cleanup
09-11 11:56:19.841  7017  7528 D bt_userial_mct: userial_close
09-11 11:56:19.841  7017  7528 E bt_userial_mct: pthread_join() FAILED result:3
09-11 11:56:19.841  7017  7528 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-11 11:56:19.849  7017  7528 D bt_hci_bdroid: set_power 0
09-11 11:56:19.849  7017  7528 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-11 11:56:19.849  7017  7528 I bt_vendor: bluetooth satus is on
09-11 11:56:19.849  7017  7528 I bt_vendor: bt-vendor : resetting BT status
09-11 11:56:19.849  7017  7528 I bt_vendor: Starting hciattach daemon
09-11 11:56:19.849  7017  7528 I bt_vendor: try to set false
,09-11 11:56:19.855  7017  7528 I bt_vendor: Starting hciattach daemon
09-11 11:56:19.855  7017  7528 I bt_vendor: try to set false
09-11 11:56:19.856  7017  7528 I bt_vendor: cleanup
09-11 11:56:19.857  7017  7593 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-11 11:56:19.857  7017  7528 I GKI_LINUX: GKI_exit_task 0 done
09-11 11:56:19.857  7017  7528 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-11 11:56:19.859  7017  7524 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-11 11:56:19.863  7017  7017 D HeadsetService: Received stop request...Stopping profile...
,09-11 11:56:19.866  7017  7017 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-11 11:56:19.866  7017  7017 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-11 11:56:19.866  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:19.868  7017  7548 D HeadsetStateMachine: Exit Disconnected: -1
09-11 11:56:19.872  7017  7524 D BluetoothAdapterState: Stopping profile services that were post enabled
09-11 11:56:19.874  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:19.874  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:19.874  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:19.874  1031  1031 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:19.874  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-11 11:56:19.877  7017  7017 D A2dpService: Received stop request...Stopping profile...
,09-11 11:56:19.880  7017  7579 D A2dpStateMachine: Exit Disconnected: -1
09-11 11:56:19.882  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-11 11:56:19.883  7017  7017 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-11 11:56:19.883  7017  7017 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-11 11:56:19.883  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:19.886  7017  7017 D HidService: Received stop request...Stopping profile...
09-11 11:56:19.886  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:19.886  1031  1031 D BluetoothA2dp: Proxy object disconnected
09-11 11:56:19.886  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-11 11:56:19.888  7017  7017 D HealthService: Received stop request...Stopping profile...
09-11 11:56:19.889  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
,09-11 11:56:19.893  7017  7017 D PanService: Received stop request...Stopping profile...
09-11 11:56:19.894  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:19.895  7017  7017 D BtGatt.DebugUtils: handleDebugAction() action=null
09-11 11:56:19.896  7017  7017 D BtGatt.GattService: Received stop request...Stopping profile...
09-11 11:56:19.897  7017  7017 D BtGatt.GattService: stop()
09-11 11:56:19.897  7017  7017 D BtGatt.AdvertiseManager: advertise clients cleared
09-11 11:56:19.898  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:19.900  7017  7017 D BluetoothMapService: Received stop request...Stopping profile...
09-11 11:56:19.900  7017  7017 D BluetoothMapService: stop()
09-11 11:56:19.900  7017  7017 D BluetoothMapEmailAppObserver: deinitObservers()
09-11 11:56:19.901  7017  7017 D BluetoothMapEmailAppObserver: removeReceiver()
,09-11 11:56:19.903  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c748075
09-11 11:56:19.906  7017  7017 D HeadsetStateMachine: Unbinding service...
09-11 11:56:19.907  7017  7017 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-11 11:56:19.907  7017  7017 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-11 11:56:19.907  7017  7017 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-11 11:56:19.907  7017  7017 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-11 11:56:19.907  7017  7017 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-11 11:56:19.907  7017  7017 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-11 11:56:19.907  7017  7017 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-11 11:56:19.908  7017  7017 I BluetoothA2dpServiceJni: cleanupNative
09-11 11:56:19.908  7017  7580 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-11 11:56:19.910  7017  7017 I GKI_LINUX: GKI_exit_task 2 done
09-11 11:56:19.910  7017  7017 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-11 11:56:19.910  7017  7017 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-11 11:56:19.910  7017  7017 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-11 11:56:19.910  7017  7017 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-11 11:56:19.911  7017  7017 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-11 11:56:19.911  7017  7017 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-11 11:56:19.911  7017  7017 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-11 11:56:19.911  7017  7017 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-11 11:56:19.914  7017  7017 V BluetoothMapService: Handler(): got msg=4
09-11 11:56:19.914  7017  7017 D BluetoothMapService: MAP Service closeService in
09-11 11:56:19.914  7017  7017 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-11 11:56:19.914  7017  7017 V BluetoothMapService: MAP Service closeService out
,09-11 11:56:19.917  7017  7524 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-11 11:56:19.917  7017  7524 D BluetoothAdapterProperties: Setting state to 10
09-11 11:56:19.917  7017  7524 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-11 11:56:19.919  7017  7017 D BluetoothMapService: cleanup()
09-11 11:56:19.920  7017  7017 D BluetoothMapService: MAP Service closeService in
09-11 11:56:19.920  7017  7017 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-11 11:56:19.920  7017  7017 V BluetoothMapService: MAP Service closeService out
09-11 11:56:19.922  1031  1102 D BluetoothManagerService: Message: 60
09-11 11:56:19.922  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-11 11:56:19.922  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-11 11:56:19.924  1839  3425 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:19.924  7017  7524 I BluetoothAdapterState: Entering OffState
09-11 11:56:19.925  6888  6993 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:19.926  1839  2389 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-11 11:56:19.929  6888  6993 D BluetoothMap: onBluetoothStateChange: up=false
09-11 11:56:19.931  6888  6993 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:19.931  6888  6993 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-11 11:56:19.932  1839  3424 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:19.932  6888  6993 D BluetoothPan: onBluetoothStateChange on: false
09-11 11:56:19.933  6888  6993 D BluetoothPbap: onBluetoothStateChange: up=false
09-11 11:56:19.933  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:19.933  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:19.934  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-11 11:56:19.934  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-11 11:56:19.936  1031  1102 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-11 11:56:19.936  1031  1102 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-11 11:56:19.936  1031  1102 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@62ef776 mBinding = false
09-11 11:56:19.937  1031  1102 D BluetoothManagerService: Sending unbind request.
09-11 11:56:19.942  7017  7528 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-11 11:56:19.945  7017  7017 I GKI_LINUX: GKI_exit_task 1 done
09-11 11:56:19.945  7017  7017 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-11 11:56:19.946  7017  7017 I BluetoothServiceJni: cleanupNative: return from cleanup
09-11 11:56:19.946  7017  7017 I art     : --- WEIRD: removing null entry 248
09-11 11:56:19.946  7017  7017 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-11 11:56:19.946  7017  7017 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-11 11:56:19.947  7017  7017 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-11 11:56:19.948  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-11 11:56:19.950  7017  7017 I art     : System.exit called, status: 0
09-11 11:56:19.950  7017  7017 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-11 11:56:19.970   311  1773 V AudioFlinger: 7017 died, releasing its sessions
09-11 11:56:19.970   311  1773 V AudioFlinger:  pid 1839 @ 0
09-11 11:56:19.970   311  1773 V AudioFlinger:  pid 3288 @ 1
09-11 11:56:19.970   311  1773 V AudioFlinger:  pid 3288 @ 2
,09-11 11:56:19.974  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,09-11 11:56:19.974  1928  2115 D LGBluetoothAPIService: Message: 101
,09-11 11:56:19.974  1928  2115 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-11 11:56:19.974  1928  2115 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-11 11:56:19.975  1928  2115 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-11 11:56:19.977  6888  6888 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-11 11:56:20.009  1031  1760 I ActivityManager: Process com.android.bluetooth (pid 7017) has died
09-11 11:56:20.009  1031  1760 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-11 11:56:20.009  1031  1760 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,09-11 11:56:20.017  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-11 11:56:20.019  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:20.020  1928  2115 D LGBluetoothAPIService: Message: 2
09-11 11:56:20.020  1928  2115 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-11 11:56:20.021  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:20.021  6888  6888 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-11 11:56:20.021  6888  6888 D LGBluetoothEventManager: [BTUI] clear device connection state
09-11 11:56:20.024  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:20.030  6888  6888 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-11 11:56:20.032  1588  1588 D BluetoothAdapter: 738293956: getState() :  mService = null. Returning STATE_OFF
09-11 11:56:20.032  1588  1588 D BluetoothAdapter: 738293956: getState() :  mService = null. Returning STATE_OFF
09-11 11:56:20.079  1031  1641 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7750 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-11 11:56:20.082  6888  6888 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:20.132  7750  7750 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-11 11:56:20.133  7750  7750 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-11 11:56:20.133  7750  7750 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,09-11 11:56:20.134  7750  7750 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-11 11:56:20.156  7750  7750 D BluetoothAdapterApp: Loading JNI Library
,09-11 11:56:20.192  7750  7750 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@247836bd Instance Count = 1
,09-11 11:56:20.198  7750  7750 D BluetoothAdapterApp: onCreate
,09-11 11:56:20.225  7750  7750 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-11 11:56:20.225  7750  7750 D ProfileConfigQcom: Adding HeadsetService
,09-11 11:56:20.225  7750  7750 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-11 11:56:20.225  7750  7750 D ProfileConfigQcom: Adding A2dpService
09-11 11:56:20.225  7750  7750 D ProfileConfigQcom: [BTUI] HidService is supported
09-11 11:56:20.226  7750  7750 D ProfileConfigQcom: Adding HidService
,09-11 11:56:20.226  7750  7750 D ProfileConfigQcom: [BTUI] HealthService is supported
09-11 11:56:20.226  7750  7750 D ProfileConfigQcom: Adding HealthService
09-11 11:56:20.227  7750  7750 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-11 11:56:20.229  7750  7750 D ProfileConfigQcom: [BTUI] PanService is supported
09-11 11:56:20.229  7750  7750 D ProfileConfigQcom: Adding PanService
09-11 11:56:20.229  7750  7750 D ProfileConfigQcom: [BTUI] GattService is supported
,09-11 11:56:20.229  7750  7750 D ProfileConfigQcom: Adding GattService
09-11 11:56:20.230  7750  7750 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-11 11:56:20.230  7750  7750 D ProfileConfigQcom: Adding BluetoothMapService
09-11 11:56:20.230  7750  7750 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-11 11:56:20.231  7750  7750 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-11 11:56:20.232  7750  7750 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:20.233  7750  7750 V BluetoothPbapReceiver: ***********state = 10
09-11 11:56:20.235  7750  7750 V LGMDMManagerInternal: Create singleton instance
09-11 11:56:20.359  2167  2167 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:20.360  7750  7750 D LGBluetoothAPIServer: [BTUI] onCreate()
,09-11 11:56:20.360  7750  7750 D LGBluetoothAPIServer: [BTUI] onBind()
,09-11 11:56:20.364  6888  6888 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-11 11:56:20.372  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-11 11:56:20.372  1928  2115 D LGBluetoothAPIService: Message: 100
09-11 11:56:20.373  1928  2115 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,09-11 11:56:20.383  6888  6888 D BluetoothPermissionRequest: onReceive
09-11 11:56:20.386  6888  6888 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-11 11:56:20.386  6888  6888 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-11 11:56:20.389  6888  6888 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-11 11:56:20.396  7750  7750 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-11 11:56:20.403  7750  7750 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:20.407  7750  7750 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-11 11:56:20.408  7750  7750 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-11 11:56:20.408  7750  7750 V BluetoothSapReceiver: SapReceiver onReceive 
09-11 11:56:20.409  7750  7750 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:20.409  7750  7750 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-11 11:56:20.418  7602  7602 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-11 11:56:21.916  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
,09-11 11:56:21.916  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:22.031  1031  1439 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-11 11:56:22.051  1588  1588 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-11 11:56:22.118  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-11 11:56:22.133  1031  1098 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7780 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-11 11:56:22.147  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-11 11:56:22.148  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-11 11:56:22.163  1031  1031 D administrator: Handling package changes for user 0
,09-11 11:56:22.171  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-11 11:56:22.209  7780  7780 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-11 11:56:22.276  7780  7780 D LgDataFeature: LgDataFeature() Constructor: none
09-11 11:56:22.276  7780  7780 D LgDataFeature: LgDataFeature() Constructor Done, null
09-11 11:56:22.276  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-11 11:56:22.277  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-11 11:56:22.348  1031  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-11 11:56:22.355  1031  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-11 11:56:22.364  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-11 11:56:22.364  7780  7825 I Babel   : MmsConfig: mnc/mcc: 0/0
09-11 11:56:22.364  7780  7825 I Babel   : MmsConfig.loadMmsSettings
09-11 11:56:22.365  2489  2489 V GmsNetworkLocationProvi: DISABLE
09-11 11:56:22.367  7780  7825 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-11 11:56:22.367  7780  7825 I Babel   : MmsConfig.loadFromDatabase
,09-11 11:56:22.395  1031  1097 D LocationProviderProxy: applying state to connected service
09-11 11:56:22.395  2489  2489 E GCoreFlp: Bound FusedProviderService with LocationManager
09-11 11:56:22.394  7780  7825 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-11 11:56:22.396  7780  7825 I Babel   : MmsConfig.loadFromResources
09-11 11:56:22.397  7780  7825 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-11 11:56:22.398  7780  7825 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-11 11:56:22.413  7780  7780 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:22.429  7780  7823 W AudioCapabilities: Unsupported mime audio/evrc
09-11 11:56:22.430  7780  7823 W AudioCapabilities: Unsupported mime audio/qcelp
09-11 11:56:22.433  7780  7823 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-11 11:56:22.437  1804  7828 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-11 11:56:22.438  1804  7828 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-11 11:56:22.443  7091  7091 I AppUp4:CustModeStarterReceiver: onReceive
09-11 11:56:22.447  7091  7091 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2712955f
09-11 11:56:22.447  7091  7091 D AppUp4:CustFacade: isCustomizationCompleted : false
09-11 11:56:22.447  7091  7091 D AppUp4:CustFacade: isPhone : true
09-11 11:56:22.447  7091  7091 D AppUp4:CustModeStarterReceiver: begin check event
09-11 11:56:22.448  7091  7091 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-11 11:56:22.448  1804  5141 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-11 11:56:22.455  7780  7823 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-11 11:56:22.457  7780  7823 W AudioCapabilities: Unsupported mime audio/qcelp
09-11 11:56:22.458  7780  7823 W AudioCapabilities: Unsupported mime audio/evrc
09-11 11:56:22.480  7780  7823 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-11 11:56:22.482  7780  7823 W VideoCapabilities: Unsupported mime video/divx
,09-11 11:56:22.483  7780  7823 W VideoCapabilities: Unsupported mime video/divx311
09-11 11:56:22.485  7780  7823 W VideoCapabilities: Unsupported mime video/divx4
09-11 11:56:22.489  7780  7823 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-11 11:56:22.501  1031  1964 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7831 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-11 11:56:22.505  1031  1946 I ActivityManager: Killing 6906:com.lge.sync/1000 (adj 15): empty #17
09-11 11:56:22.505  7780  7823 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-11 11:56:22.508  7780  7823 W AudioCapabilities: Unsupported mime audio/eac3
09-11 11:56:22.509  7780  7823 W AudioCapabilities: Unsupported mime audio/ac3
09-11 11:56:22.510  7780  7823 W AudioCapabilities: Unsupported mime audio/g726
09-11 11:56:22.511  7780  7823 W AudioCapabilities: Unsupported mime audio/wma-voice
09-11 11:56:22.511  7780  7823 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-11 11:56:22.512  7780  7823 W AudioCapabilities: Unsupported mime audio/adpcm
09-11 11:56:22.513  7780  7823 W VideoCapabilities: Unsupported mime video/theora
09-11 11:56:22.515  1031  1530 D WifiService: Client connection lost with reason: 4
,09-11 11:56:22.516  7780  7823 W VideoCapabilities: Unsupported mime video/mjpg
09-11 11:56:22.580  1031  1048 W libprocessgroup: failed to open /acct/uid_1000/pid_6906/cgroup.procs: No such file or directory
,09-11 11:56:22.623  7831  7831 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-11 11:56:22.624  7831  7831 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-11 11:56:22.624  7831  7831 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-11 11:56:22.626  7831  7831 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,09-11 11:56:22.627  7831  7831 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-11 11:56:22.697  7831  7831 I SystemConfig: BUILD Country: EU
09-11 11:56:22.697  7831  7831 I SystemConfig: BUILD Operator: OPEN
,09-11 11:56:22.748  1031  1927 I ActivityManager: Killing 7124:com.lge.email/u0a23 (adj 15): empty #17
,09-11 11:56:22.875  1031  1562 W libprocessgroup: failed to open /acct/uid_10023/pid_7124/cgroup.procs: No such file or directory
,09-11 11:56:22.946  1031  2019 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7854 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-11 11:56:22.953  7831  7849 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-11 11:56:22.953  7831  7849 I SystemConfig: existFile = false
09-11 11:56:22.953  7831  7849 I SystemConfig: canReadFile = false
09-11 11:56:22.953  7831  7849 I SystemConfig: systemFeature RCS result false
09-11 11:56:22.954  7831  7849 D SystemConfig: refreshRcsSupport() :false
,09-11 11:56:23.028  7854  7854 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-11 11:56:23.029  7854  7854 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-11 11:56:23.029  7854  7854 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-11 11:56:23.030  7854  7854 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-11 11:56:23.169  7854  7854 I AppConfig: Total System Memory = 2995761152
,09-11 11:56:23.182  7854  7854 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,09-11 11:56:23.276  1031  1049 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7873 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-11 11:56:23.277  1031  1049 I ActivityManager: Killing 7000:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-11 11:56:23.340  1031  1873 W libprocessgroup: failed to open /acct/uid_10026/pid_7000/cgroup.procs: No such file or directory
,09-11 11:56:23.568  7873  7873 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-11 11:56:23.655  7873  7873 D LgDataFeature: LgDataFeature() Constructor: none
,09-11 11:56:23.655  7873  7873 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-11 11:56:23.711  7873  7873 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-11 11:56:23.731  7873  7873 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-11 11:56:23.732  7873  7873 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-11 11:56:23.749  7873  7873 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-11 11:56:23.749  7873  7873 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-11 11:56:23.767  1031  1946 I ActivityManager: Killing 6408:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-11 11:56:23.801  1031  1562 W libprocessgroup: failed to open /acct/uid_1000/pid_6408/cgroup.procs: No such file or directory
,09-11 11:56:23.803  3398  3413 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-11 11:56:23.808  3398  3413 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@225c8710 on behalf of 7873
09-11 11:56:23.810  5071  7913 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-11 11:56:23.866  1031  1918 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7914 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-11 11:56:23.912  7873  7873 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-11 11:56:23.951  7873  7873 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-11 11:56:23.955  7679  7716 D UEI.SmartControl: Internal timer expired: 1
09-11 11:56:23.955  7679  7716 D UEI.SmartControl: unbind internal service
09-11 11:56:23.958  7679  7679 D UEI.SmartControl: Service.onUnbind: IControl
09-11 11:56:23.959  7679  7679 D UEI.SmartControl: Service.onDestroy
09-11 11:56:23.959  7679  7679 D UEI.SmartControl: Lock is in USE false
09-11 11:56:23.959  7679  7679 D UEI.SmartControl: unbind internal service
09-11 11:56:23.959  7679  7679 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@38f5287b
09-11 11:56:23.960  7679  7679 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-11 11:56:23.960  7679  7679 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-11 11:56:23.960  7679  7679 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-11 11:56:23.960  7679  7679 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-11 11:56:23.960  7679  7679 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-11 11:56:23.960  7679  7679 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-11 11:56:23.960  7679  7679 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-11 11:56:23.960  7679  7679 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-11 11:56:23.960  7679  7679 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:23.960  7679  7679 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:23.960  7679  7679 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:23.960  7679  7679 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:23.960  7679  7679 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:23.960  7679  7679 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:23.960  7679  7679 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:23.960  7679  7679 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@38f5287b
09-11 11:56:23.962  7679  7679 D serial_port: close(fd = 25)
09-11 11:56:23.964  7679  7679 I UEI.SmartControl: Serial port is closed.
09-11 11:56:23.964  7679  7679 I UEI.SmartControl: Serial port is closed.
,09-11 11:56:23.966  7679  7679 D UEI.SmartControl: Blaster closed
09-11 11:56:23.966  7679  7679 D UEI.SmartControl: Shut down QS...
09-11 11:56:23.966  7679  7679 D UEI.SmartControl: Stopping QS lib
09-11 11:56:23.966  7679  7679 D UEI.SmartControl: QS lib stop result = true
09-11 11:56:23.966  7679  7679 D UEI.SmartControl: Stopped QS lib
09-11 11:56:23.967  7679  7679 D UEI.SmartControl: Stopped file observer...
09-11 11:56:23.967  7679  7679 D UEI.SmartControl: QS shutdown complete
09-11 11:56:23.980  7914  7914 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-11 11:56:24.002  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-11 11:56:24.002  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-11 11:56:24.002  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,09-11 11:56:24.002  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-11 11:56:24.002  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-11 11:56:24.002  7914  7914 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-11 11:56:24.017  1031  1873 I ActivityManager: Killing 7189:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-11 11:56:24.103  1031  2000 W libprocessgroup: failed to open /acct/uid_10046/pid_7189/cgroup.procs: No such file or directory
,09-11 11:56:24.398  1031  1873 I art     : Explicit concurrent mark sweep GC freed 33244(1574KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.798ms total 143.377ms
,09-11 11:56:24.445  1031  2019 V SIM_STK : Menu title from STK is T-Mobile
,09-11 11:56:24.466  5071  7913 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 656 ms] updated apps [took 656 ms] 
,09-11 11:56:24.934  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-11 11:56:24.934  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24c15499 added. We now have 6 listener(s)
,09-11 11:56:24.934  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:24.943  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:24.943  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@156dd35e added. We now have 7 listener(s)
09-11 11:56:24.943  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:24.944  6629  6700 I System.out: IsBluetoothEnabled
09-11 11:56:24.945  1031  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:24.945  1031  1983 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-11 11:56:24.945  1031  1102 D BluetoothManagerService: Message: 2
09-11 11:56:24.949  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:24.949  1031  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:24.949  1031  2000 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-11 11:56:24.963  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-11 11:56:24.964  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-11 11:56:24.964  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-11 11:56:24.965  1031  1102 D BluetoothManagerService: Message: 1
09-11 11:56:24.965  1031  1102 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-11 11:56:24.988  1031  1102 D BluetoothManagerService: Message: 20
09-11 11:56:24.989  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@143113b8:true
,09-11 11:56:24.993  7750  7750 D BluetoothAdapterState: make
09-11 11:56:24.997  7750  7750 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-11 11:56:24.998  7750  7750 I bluedroid-qcom: init
09-11 11:56:24.999  7750  7959 I BluetoothAdapterState: Entering OffState
09-11 11:56:24.999  7750  7750 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-11 11:56:25.000  7750  7750 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-11 11:56:25.000  7750  7750 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-11 11:56:25.000  7750  7750 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-11 11:56:25.000  7750  7750 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-11 11:56:25.002  7750  7750 I bluedroid-qcom: get_profile_interface socket
09-11 11:56:25.002  7750  7750 I bluedroid-qcom: get_profile_interface map_client
,09-11 11:56:25.006  7750  7963 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-11 11:56:24.989  7962  7962 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:25.011  7750  7963 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-11 11:56:24.999  7962  7962 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:25.018  7962  7962 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-11 11:56:25.018  7962  7962 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-11 11:56:25.018  7962  7962 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-11 11:56:25.024  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-11 11:56:25.024  1031  1102 D BluetoothManagerService: Message: 40
09-11 11:56:25.025  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-11 11:56:25.025  7750  7766 I bluedroid-qcom: config_hci_snoop_log
09-11 11:56:25.027  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-11 11:56:25.027  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-11 11:56:25.031  7962  7962 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-11 11:56:25.038  7750  7959 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-11 11:56:25.039  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-11 11:56:25.039  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
09-11 11:56:25.040  7750  7963 D BluetoothAdapterProperties: Name is: G3
09-11 11:56:25.041  7962  7962 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-11 11:56:25.041  7962  7962 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-11 11:56:25.043  7750  7959 D BluetoothAdapterProperties: Setting state to 11
09-11 11:56:25.043  7750  7959 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-11 11:56:25.044  1031  1102 D BluetoothManagerService: Message: 60
09-11 11:56:25.044  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-11 11:56:25.044  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-11 11:56:25.045  7750  7959 I LGBluetoothServiceJni: classInitNative: succeeds
,09-11 11:56:25.055  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:25.055  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-11 11:56:25.059  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:25.062  6888  6888 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-11 11:56:25.071  7750  7750 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-11 11:56:25.071  7750  7750 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:25.071  7750  7750 V BluetoothPbapReceiver: ***********state = 11
09-11 11:56:25.078  7750  7959 D BluetoothBondStateMachine: make
,09-11 11:56:25.090  2167  2167 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:25.094  7750  7959 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:25.095  7750  7959 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-11 11:56:25.095  7750  7959 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:25.095  7750  7959 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-11 11:56:25.097  7750  7959 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-11 11:56:25.098  7750  7977 I BluetoothBondStateMachine: StableState(): Entering Off State
09-11 11:56:25.104  7750  7959 E BluetoothAdapterService: File transfer profiles supported!!
,09-11 11:56:25.112  6888  6888 D BluetoothPermissionRequest: onReceive
09-11 11:56:25.114  7750  7750 D HeadsetService: Received start request. Starting profile...
09-11 11:56:25.114  7750  7750 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-11 11:56:25.115  7750  7750 D LGBluetoothHfpAdapter: Version 1.6
,09-11 11:56:25.115  7750  7959 E BluetoothAdapterService: File transfer profiles supported!!
09-11 11:56:25.116  6888  6888 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-11 11:56:25.117  7750  7750 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-11 11:56:25.118  7750  7750 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-11 11:56:25.118  7750  7750 D HeadsetStateMachine: make
09-11 11:56:25.123  7750  7959 E BluetoothAdapterService: File transfer profiles supported!!
09-11 11:56:25.128  7750  7959 E BluetoothAdapterService: File transfer profiles supported!!
09-11 11:56:25.132  7750  7959 E BluetoothAdapterService: File transfer profiles supported!!
,09-11 11:56:25.139  7750  7959 E BluetoothAdapterService: File transfer profiles supported!!
09-11 11:56:25.144  7750  7959 E BluetoothAdapterService: File transfer profiles supported!!
09-11 11:56:25.148  7750  7750 D LgDataFeature: LgDataFeature() Constructor: none
09-11 11:56:25.148  7750  7750 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-11 11:56:25.152  7750  7750 D HeadsetStateMachine: max_hf_connections = 1
09-11 11:56:25.152  7750  7750 I bluedroid-qcom: get_profile_interface handsfree
09-11 11:56:25.153  7750  7750 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-11 11:56:25.154   311  1369 V AudioPolicyService: registerClient() client 0xb1427180, uid 1002
09-11 11:56:25.154   311  1370 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-11 11:56:25.154   311  1370 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-11 11:56:25.154   311  1370 V AudioPolicyManagerEx: getOutput() returns output 2
09-11 11:56:25.154  7750  7750 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-11 11:56:25.154   311   311 V AudioFlinger: registerClient() client 0xb54eacd0, pid 7750
09-11 11:56:25.155   311  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:25.155   311  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-11 11:56:25.155  1031  1946 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:25.155  1031  1946 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-11 11:56:25.155  1839  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:25.155  1839  1855 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-11 11:56:25.155  3288  3310 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:25.155  3288  3310 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-11 11:56:25.155   311  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:25.155   311  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-11 11:56:25.155  1031  1760 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:25.155  1031  1760 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-11 11:56:25.155  1839  3425 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:25.155  1839  3425 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-11 11:56:25.155  3288  3306 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:25.155  3288  3306 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-11 11:56:25.155  1588  2086 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:25.155  1588  2086 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-11 11:56:25.156  1588  2086 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:25.156  1588  2086 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-11 11:56:25.156  7750  7766 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-11 11:56:25.156  7750  7766 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-11 11:56:25.156  7750  7766 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-11 11:56:25.156  7750  7766 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-11 11:56:25.156  7750  7750 V ToneGenerator: Create Track: 0xb4928a80
09-11 11:56:25.156  7750  7750 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-11 11:56:25.156  7750  7750 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-11 11:56:25.156   311  1370 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-11 11:56:25.156   311  1370 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-11 11:56:25.156   311  1370 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-11 11:56:25.156   311  1370 V AudioPolicyManagerEx: getOutput() returns output 2
09-11 11:56:25.156   311   311 I AudioFlinger: isAudioPlaybackHookOn() false
09-11 ,11:56:25.156   311  1773 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-11 11:56:25.156   311  1773 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-11 11:56:25.156   311  1773 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-11 11:56:25.156   311  1773 V AudioPolicyManagerEx: getOutput() returns output 2
09-11 11:56:25.156  7750  7750 V AudioSystem: getLatency() output 2, latency 50
09-11 11:56:25.156  7750  7750 V AudioSystem: getFrameCount() output 2, frameCount 960
09-11 11:56:25.156  7750  7750 V AudioTrack: createTrack_l() output 2 afLatency 50
09-11 11:56:25.157   311  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-11 11:56:25.157   311  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-11 11:56:25.157   311  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-11 11:56:25.157   311  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-11 11:56:25.157   311  1369 V AudioFlinger: createTrack() lSessionId: 23
09-11 11:56:25.157  7750  7750 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-11 11:56:25.158   311  1370 V AudioFlinger: acquiring 23 from 7750, for 7750
09-11 11:56:25.158   311  1370 V AudioFlinger:  added new entry for 23
09-11 11:56:25.158  7750  7750 V ToneGenerator: ToneGenerator INIT OK, time: 132629
09-11 11:56:25.158  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:25.158  7750  7981 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-11 11:56:25.159  7750  7981 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-11 11:56:25.159  7750  7981 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-11 11:56:25.159  7750  7981 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-11 11:56:25.159   311   311 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7750
09-11 11:56:25.159   311   311 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-11 11:56:25.159   311   311 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-11 11:56:25.159  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:25.159   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-11 11:56:25.159   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-11 11:56:25.159   311   311 V voice   : voice_set_parameters: exit with code(0)
09-11 11:56:25.160   311   311 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-11 11:56:25.160   311   311 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
,09-11 11:56:25.160   311   311 V msm8974_platform: platform_set_parameters: exit with code(0)
09-11 11:56:25.160   311   311 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-11 11:56:25.160   311   311 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-11 11:56:25.160   311   311 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,09-11 11:56:25.165  7750  7750 D A2dpService: Received start request. Starting profile...
09-11 11:56:25.166  7750  7750 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-11 11:56:25.166  7750  7981 V ToneGenerator: ToneGenerator destructor
09-11 11:56:25.166  7750  7981 V ToneGenerator: stopTone
09-11 11:56:25.166  7750  7981 V ToneGenerator: Delete Track: 0xb4928a80
09-11 11:56:25.167  7750  7750 V Avrcp   : make
09-11 11:56:25.168  7750  7750 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-11 11:56:25.168  7750  7750 I bluedroid-qcom: get_profile_interface avrcp
09-11 11:56:25.168  7750  7959 V LGMDMManager: Create singleton instance
09-11 11:56:25.169  7750  7981 V AudioTrack: ~AudioTrack, releasing session id from 7750 on behalf of 7750
09-11 11:56:25.169   311  1773 V AudioFlinger: releasing 23 from 7750 for 7750
09-11 11:56:25.169   311  1773 V AudioFlinger:  decremented refcount to 0
09-11 11:56:25.169   311  1773 V AudioFlinger: purging stale effects
09-11 11:56:25.169   311  1773 V AudioPolicyService: AudioCommandThread() adding release output 2
09-11 11:56:25.169   311  1773 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-11 11:56:25.170   311  1259 V AudioPolicyService: AudioCommandThread() waking up
09-11 11:56:25.170   311  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
09-11 11:56:25.170   311  1259 V AudioPolicyManager: releaseOutput() 2
09-11 11:56:25.170   311  1259 V AudioPolicyService: AudioCommandThread() going to sleep
09-11 11:56:25.170   311  1773 V AudioFlinger: PlaybackThread::Track destructor
09-11 11:56:25.170   311  1773 V AudioFlinger: removeClient_l() pid 7750, calling pid 311
09-11 11:56:25.172  7750  7959 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-11 11:56:25.175  7750  7750 V AudioManager: registerRemoteController: size of Media player list: 0
,09-11 11:56:25.176  7750  7750 E AudioManager: No RCC entry present to update
,09-11 11:56:25.176  7750  7750 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-11 11:56:25.179  7750  7750 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-11 11:56:25.180  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,09-11 11:56:25.180  7750  7750 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-11 11:56:25.183  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-11 11:56:25.267  1031  1873 V SIM_STK : Menu title from STK is T-Mobile
09-11 11:56:25.267  1031  1873 V SIM_STK : Menu title from STK is T-Mobile
,09-11 11:56:25.363  1031  1927 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-11 11:56:25.372  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-11 11:56:25.376  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-11 11:56:25.376  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-11 11:56:25.376  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-11 11:56:25.377  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-11 11:56:25.377  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-11 11:56:25.377  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-11 11:56:25.377  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-11 11:56:25.377  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-11 11:56:25.377  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-11 11:56:25.377  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,09-11 11:56:25.377  7750  7750 I BluetoothA2dpServiceJni: classInitNative
09-11 11:56:25.378  7750  7750 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-11 11:56:25.378  7750  7750 D A2dpStateMachine: make
,09-11 11:56:25.382  7750  7750 I bluedroid-qcom: get_profile_interface a2dp
09-11 11:56:25.382  7750  7989 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-11 11:56:25.387  7750  7750 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-11 11:56:25.388  7750  7750 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-11 11:56:25.390  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:25.392  7750  7987 D A2dpStateMachine: Enter Disconnected: -2
,09-11 11:56:25.393  7750  7750 I BluetoothHidServiceJni: classInitNative: succeeds
,09-11 11:56:25.398  7750  7750 D HidService: Received start request. Starting profile...
09-11 11:56:25.398  7750  7750 I bluedroid-qcom: get_profile_interface hidhost
09-11 11:56:25.398  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:25.399  7750  7750 I BluetoothHealthServiceJni: classInitNative: succeeds
09-11 11:56:25.400  7750  7750 D HealthService: Received start request. Starting profile...
09-11 11:56:25.403  7750  7750 I bluedroid-qcom: get_profile_interface health
09-11 11:56:25.403  7750  7750 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-11 11:56:25.403  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:25.404  7750  7750 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-11 11:56:25.408  7750  7750 D PanService: Received start request. Starting profile...
09-11 11:56:25.408  7750  7750 D BluetoothPanServiceJni: initializeNative(L110): pan
09-11 11:56:25.408  7750  7750 I bluedroid-qcom: get_profile_interface pan
09-11 11:56:25.415  7750  7750 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-11 11:56:25.415  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:25.416  7750  7750 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-11 11:56:25.420  7750  7750 D BtGatt.DebugUtils: handleDebugAction() action=null
09-11 11:56:25.421  7750  7750 D BtGatt.GattService: Received start request. Starting profile...
09-11 11:56:25.421  7750  7750 D BtGatt.GattService: start()
09-11 11:56:25.421  7750  7750 I bluedroid-qcom: get_profile_interface gatt
09-11 11:56:25.422  7750  7750 D BtGatt.AdvertiseManager: advertise manager created
,09-11 11:56:25.435  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
,09-11 11:56:25.442  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:25.443  7750  7750 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-11 11:56:25.447  7750  7750 V BluetoothMapService: BluetoothMapBinder()
09-11 11:56:25.448  7750  7750 D BluetoothMapService: Received start request. Starting profile...
09-11 11:56:25.448  7750  7750 D BluetoothMapService: start()
09-11 11:56:25.457  7750  7750 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-11 11:56:25.458  7750  7750 D BluetoothMapEmailAppObserver: createReceiver()
,09-11 11:56:25.465  7750  7750 D BluetoothMapEmailAppObserver: initObservers()
,09-11 11:56:25.466  7750  7750 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-11 11:56:25.491  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:25.493  7750  7750 D HeadsetStateMachine: Proxy object connected
09-11 11:56:25.496  7750  7750 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-11 11:56:25.497  7750  7750 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-11 11:56:25.512  7750  7750 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-11 11:56:25.512  7750  7981 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-11 11:56:25.514  7750  7981 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-11 11:56:25.514  7750  7981 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-11 11:56:25.515  7750  7750 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:25.519  7750  7750 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-11 11:56:25.522  7750  7750 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-11 11:56:25.525  7750  7750 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-11 11:56:25.529  7750  7750 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-11 11:56:25.529  7750  7750 V PanService: [BTUI] SIM Extra State :ABSENT
09-11 11:56:25.533  7750  7750 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-11 11:56:25.533  7750  7750 V BluetoothMapService: Handler(): got msg=1
09-11 11:56:25.534  7750  7750 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-11 11:56:25.534  7750  7959 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-11 11:56:25.534  7750  7750 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-11 11:56:25.534  7750  7959 I bluedroid-qcom: enable
09-11 11:56:25.534  7750  7750 V BluetoothSapReceiver: SapReceiver onReceive 
09-11 11:56:25.534  7750  7750 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:25.534  7750  7750 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-11 11:56:25.534  7750  7959 I bt_hci_bdroid: init
09-11 11:56:25.536  7750  7959 I bt_vendor: bt-vendor : init
09-11 11:56:25.536  7750  7959 I bt_vendor: bt-vendor : get_bt_soc_type
09-11 11:56:25.536  7750  7959 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-11 11:56:25.536  7750  7959 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-11 11:56:25.536  7750  7959 D bt_userial_mct: userial_init
09-11 11:56:25.536  7750  7959 D bt_hci_bdroid: set_power 1
09-11 11:56:25.536  7750  7959 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-11 11:56:25.536  7750  7959 I bt_vendor: Starting hciattach daemon
09-11 11:56:25.536  7750  7959 I bt_vendor: try to set true
09-11 11:56:25.541  7750  8002 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-11 11:56:25.542  7750  8002 I bt-btu  : btu_task pending for preload complete event
,09-11 11:56:25.529  8005  8005 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:25.529  8005  8005 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:25.564  8006  8006 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-11 11:56:25.633  8012  8012 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-11 11:56:25.646  8013  8013 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-11 11:56:25.685  8015  8015 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-11 11:56:25.698  8016  8016 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-11 11:56:25.710  8017  8017 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-11 11:56:25.722  8018  8018 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-11 11:56:25.743  8020  8020 I libmdmdetect: ESOC framework not supported
09-11 11:56:25.743  8020  8020 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-11 11:56:25.755  8020  8020 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-11 11:56:25.755  8020  8020 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,09-11 11:56:25.755  8020  8020 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,09-11 11:56:25.755  8020  8020 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-11 11:56:25.755  8020  8020 D bthci_qcomm_common: [BTUI]     LE: Class 2
,09-11 11:56:25.755  8020  8020 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-11 11:56:25.755  8020  8020 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-11 11:56:25.802  8020  8021 E QC-QMI  : qmi_client [8020] 15: failed to locate client data
09-11 11:56:25.803   461   461 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-11 11:56:25.803   461   461 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-11 11:56:25.855  8022  8022 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-11 11:56:25.881  8023  8023 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-11 11:56:25.942  7750  7959 I bt_vendor: bluetooth satus is on
,09-11 11:56:25.942  7750  7959 D bt_hci_bdroid: preload
09-11 11:56:25.942  7750  8004 D bt_userial_mct: userial_open(port:0)
,09-11 11:56:25.942  7750  8004 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-11 11:56:25.947  7750  8004 I bt_vendor: Done intiailizing UART
,09-11 11:56:25.950  7750  8004 I bt_vendor: Done intiailizing UART
,09-11 11:56:25.950  7750  8004 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-11 11:56:25.951  7750  8004 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-11 11:56:25.951  7750  8028 D bt_userial_mct: Entering userial_read_thread(),
09-11 11:56:25.959  7750  8002 I bt-btu  : btu_task received preload complete event
,09-11 11:56:25.971  7750  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,09-11 11:56:25.971  7750  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,09-11 11:56:25.973  7750  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_HCI
,09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_AVDT
09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_AVRC
09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_A2D
,09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_BNEP,
,09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_BTM
,09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_HID_HOST,
09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_GAP
09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_PAN
09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_SDP
09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_GATT
,09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_SMP
09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-11 11:56:25.978  7750  8002 I         : BTE_InitTraceLevels -- TRC_BTIF
09-11 11:56:26.086  7750  8002 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
09-11 11:56:26.086  7750  8002 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0212061 
,09-11 11:56:26.086  7750  8002 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0212061 
,09-11 11:56:26.125  7750  7963 E bt-btif : Calling BTA_HhEnable
09-11 11:56:26.125  7750  7963 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-11 11:56:26.125  7750  7963 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-11 11:56:26.129  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-11 11:56:26.129  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
09-11 11:56:26.130  7750  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-11 11:56:26.130  7750  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-11 11:56:26.130  7750  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-11 11:56:26.130  7750  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-11 11:56:26.130  7750  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-11 11:56:26.131  7750  7963 D BluetoothAdapterProperties: Name is: G3
09-11 11:56:26.132  7750  7963 D BluetoothAdapterProperties: Scan Mode:20
09-11 11:56:26.132  7750  7963 D BluetoothAdapterProperties: Discoverable Timeout:120
09-11 11:56:26.132  7750  7963 D bt_hci_bdroid: postload
09-11 11:56:26.133  7750  8004 D bt_hci_bdroid: Used up Tx Cmd credits
09-11 11:56:26.133  7750  7963 D bte_conf: Device ID record 1 : primary
09-11 11:56:26.133  7750  7963 D bte_conf:   vendorId            = 00c4
09-11 11:56:26.133  7750  7963 D bte_conf:   vendorIdSource      = 0001
09-11 11:56:26.133  7750  7963 D bte_conf:   product             = 13a1
09-11 11:56:26.133  7750  7963 D bte_conf:   version             = 1000
09-11 11:56:26.133  7750  7963 D bte_conf:   clientExecutableURL = 
09-11 11:56:26.134  7750  7963 D bte_conf:   serviceDescription  = 
09-11 11:56:26.134  7750  7963 D bte_conf:   documentationURL    = 
09-11 11:56:26.134  7750  7963 D bte_conf: bte_load_did_conf no section named DID2.
09-11 11:56:26.134  7750  8002 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-11 11:56:26.135  7750  8004 D bt_hci_bdroid: Used up Tx Cmd credits
09-11 11:56:26.136  7750  8004 D bt_hci_bdroid: Used up Tx Cmd credits
09-11 11:56:26.139  7750  8004 D bt_hci_bdroid: Used up Tx Cmd credits
,09-11 11:56:26.143  7750  8028 E bt_mct  : hci lib postload completed
09-11 11:56:26.129  8030  8030 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:26.129  8030  8030 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:26.150  7750  7959 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-11 11:56:26.150  7750  7959 D BluetoothAdapterProperties: ScanMode =  20
09-11 11:56:26.150  7750  7959 D BluetoothAdapterProperties: State =  11
09-11 11:56:26.150  7750  7959 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-11 11:56:26.150  7750  7959 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-11 11:56:26.151  7750  7959 D BluetoothAdapterProperties: Setting state to 12
09-11 11:56:26.151  7750  7959 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-11 11:56:26.151  7750  7963 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-11 11:56:26.155  1031  1102 D BluetoothManagerService: Message: 60
09-11 11:56:26.155  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-11 11:56:26.155  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-11 11:56:26.156  7750  8002 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-11 11:56:26.156  7750  8002 W bt-smp  : Plain text(LSB ~ MSB) = 10 2d 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-11 11:56:26.156  7750  8002 W bt-smp  : Encrypted text(LSB ~ MSB) = 86 92 5f 02 19 25 57 ae e6 6e 6e 0d 0c 02 b2 59 
09-11 11:56:26.156  7750  8002 W bt-btm  : Stopping oneshot timer
09-11 11:56:26.156  7750  7963 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-11 11:56:26.200  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:26.200  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:26.200  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:26.200  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:26.200  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:26.200  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:26.200  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:26.200  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:26.204  7750  7963 D BluetoothAdapterProperties: Discoverable Timeout:120
09-11 11:56:26.205  7750  7963 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-11 11:56:26.208  7750  7959 I BluetoothAdapterState: Entering On State
09-11 11:56:26.210  1839  3424 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:26.212  7750  8002 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-11 11:56:26.212  7750  8002 W bt-smp  : Plain text(LSB ~ MSB) = 1a e6 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-11 11:56:26.212  7750  8002 W bt-smp  : Encrypted text(LSB ~ MSB) = 7d 3e 78 77 bd 14 1d 60 85 90 f1 74 78 a5 cb 3e 
,09-11 11:56:26.215  7750  8002 W bt-btm  : Stopping oneshot timer
09-11 11:56:26.219  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:26.236  7750  8002 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-11 11:56:26.236  7750  8002 W bt-smp  : Plain text(LSB ~ MSB) = 94 14 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-11 11:56:26.236  7750  8002 W bt-smp  : Encrypted text(LSB ~ MSB) = cd 38 f7 0d 16 40 24 15 e1 c1 17 c5 20 b7 0f 11 
,09-11 11:56:26.239  7750  8002 W bt-btm  : Stopping oneshot timer
,09-11 11:56:26.246  7750  7959 D LGBluetoothServiceAdapter: [BTUI] OnState
09-11 11:56:26.246  7750  7959 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-11 11:56:26.246  7750  7959 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-11 11:56:26.253  7750  7959 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-11 11:56:26.260  7750  7959 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-11 11:56:26.262  1839  1839 D BluetoothHeadset: Proxy object connected
09-11 11:56:26.262  7750  8002 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-11 11:56:26.262  7750  8002 W bt-smp  : Plain text(LSB ~ MSB) = 61 09 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-11 11:56:26.262  7750  8002 W bt-smp  : Encrypted text(LSB ~ MSB) = 91 c0 cc 27 31 f8 b5 87 97 bb fd 43 2c 9d 66 b4 
09-11 11:56:26.263  6888  6904 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:26.264  7750  8002 W bt-btm  : Stopping oneshot timer
09-11 11:56:26.267  8035  8035 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-11 11:56:26.273  6888  6888 D BluetoothHeadset: Proxy object connected
09-11 11:56:26.273  6888  6888 D HeadsetProfile: Bluetooth service connected
09-11 11:56:26.273  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-11 11:56:26.275  1839  1839 D BluetoothHeadset: Proxy object connected
09-11 11:56:26.276  6888  6905 D BluetoothMap: onBluetoothStateChange: up=true
09-11 11:56:26.278  6888  6993 D BluetoothA2dp: onBluetoothStateChange: up=true
09-11 11:56:26.279  6888  6888 D BluetoothMap: Proxy object connected
09-11 11:56:26.279  6888  6888 D MapProfile: Bluetooth service connected
09-11 11:56:26.279  6888  6888 D BluetoothMap: getConnectedDevices()
09-11 11:56:26.280  6888  6905 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-11 11:56:26.280  7750  7964 V BluetoothMapService: getConnectedDevices()
09-11 11:56:26.281  6888  6888 D BluetoothA2dp: Proxy object connected
09-11 11:56:26.281  6888  6888 D A2dpProfile: Bluetooth service connected
09-11 11:56:26.282  7750  8002 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-11 11:56:26.282  7750  8002 W bt-smp  : Plain text(LSB ~ MSB) = 63 da 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-11 11:56:26.282  7750  8002 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f 83 9f 95 14 f7 54 d2 4c 8f a8 b4 58 2e b5 09 
09-11 11:56:26.282  7750  8002 W bt-btm  : Stopping oneshot timer
09-11 11:56:26.283  1839  2389 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:26.284  6888  6888 D BluetoothInputDevice: Proxy object connected
,09-11 11:56:26.284  6888  6888 D HidProfile: Bluetooth service connected
09-11 11:56:26.285  1839  1839 D BluetoothHeadset: Proxy object connected
09-11 11:56:26.285  6888  6904 D BluetoothPan: onBluetoothStateChange on: true
09-11 11:56:26.285  6888  6904 D BluetoothPan: onBluetoothStateChange call bindService
,09-11 11:56:26.287  6888  6905 D BluetoothPbap: onBluetoothStateChange: up=true
09-11 11:56:26.288  6888  6888 D BluetoothPan: BluetoothPAN Proxy object connected
09-11 11:56:26.288  6888  6888 D PanProfile: Bluetooth service connected
09-11 11:56:26.290  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:26.291  1031  1031 D BluetoothHeadset: Proxy object connected
09-11 11:56:26.292  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=true
09-11 11:56:26.293  1031  1102 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-11 11:56:26.293  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-11 11:56:26.295  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:26.295  1031  1031 D BluetoothA2dp: Proxy object connected
09-11 11:56:26.296  1928  2115 D LGBluetoothAPIService: Message: 1
09-11 11:56:26.296  1928  2115 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-11 11:56:26.296  1928  2115 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-11 11:56:26.296  1928  2115 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-11 11:56:26.297  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-11 11:56:26.302  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-11 11:56:26.303  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:26.303  7750  7750 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:26.304  7750  7750 D BluetoothMapService: STATE_ON
09-11 11:56:26.304  1031  1102 D BluetoothManagerService: Message: 40
09-11 11:56:26.304  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-11 11:56:26.306  6888  6888 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-11 11:56:26.307  6888  6888 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-11 11:56:26.312  6888  6888 D DockEventReceiver: finishStartingService: stopping service
09-11 11:56:26.320  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:26.320  7750  7750 V BluetoothPbapService: Pbap Service onCreate
09-11 11:56:26.320  7750  7750 V BluetoothPbapService: Starting PBAP service
,09-11 11:56:26.321  7750  7750 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-11 11:56:26.321  7750  7750 V BluetoothPbapService: Pbap Service onBind
,09-11 11:56:26.322  7750  7750 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:26.322  6888  6888 D BluetoothPbap: Proxy object connected
09-11 11:56:26.322  7750  7750 V BluetoothPbapService: state: 12
09-11 11:56:26.322  6888  6888 D PbapServerProfile: Bluetooth service connected
09-11 11:56:26.323  7750  7750 V BluetoothMapService: Handler(): got msg=1
09-11 11:56:26.323  7750  7750 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,09-11 11:56:26.323  7750  7750 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-11 11:56:26.324  7750  7750 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:26.324  7750  7750 V BluetoothPbapReceiver: ***********state = 12
09-11 11:56:26.324  7750  8055 D BluetoothMapMasInstance: MAS initSocket()
09-11 11:56:26.325  7750  7750 V BluetoothPbapService: Handler(): got msg=1
09-11 11:56:26.325  7750  8055 D BluetoothMapMasInstance:   masId = 00
09-11 11:56:26.325  7750  8055 D BluetoothMapMasInstance:   msgTypes = 0e
09-11 11:56:26.325  7750  8055 D BluetoothMapMasInstance:   masName = SMS/MMS
09-11 11:56:26.325  7750  8055 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-11 11:56:26.325  7750  7750 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-11 11:56:26.326  2167  2167 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-11 11:56:26.326  1031  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:26.326  2167  2167 D c       : Getting all permits...
09-11 11:56:26.326  2167  2167 D a       : Opening database...
09-11 11:56:26.328  7750  8055 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:26.329  7750  8055 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=74 mFd=0
09-11 11:56:26.329  7750  8055 V BluetoothMapMasInstance: Succeed to create listening socket 
09-11 11:56:26.329  7750  7963 D BluetoothAdapterProperties: Scan Mode:21
09-11 11:56:26.329  7750  8055 D BluetoothMapMasInstance: Accepting socket connection...
09-11 11:56:26.329  7750  7963 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-11 11:56:26.330  7750  8056 V BluetoothPbapService: Pbap Service initSocket
09-11 11:56:26.330  2167  2167 D a       : Opening database auth.proximity.permit_store...
09-11 11:56:26.330  2167  2167 D a       : Closing database...
09-11 11:56:26.331  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:26.332  1031  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:26.332  7750  8056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-11 11:56:26.338  7750  8056 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=74
,09-11 11:56:26.338  7750  8056 V BluetoothPbapService: Succeed to create listening socket 
09-11 11:56:26.338  7750  8056 V BluetoothPbapService: Accepting socket connection...
09-11 11:56:26.343  6888  6888 D BluetoothPermissionRequest: onReceive
09-11 11:56:26.344  6888  6888 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-11 11:56:26.346  6888  6888 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-11 11:56:26.349  7750  7750 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-11 11:56:26.350  7750  7750 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-11 11:56:26.355  7750  7750 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-11 11:56:26.395  7750  7750 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-11 11:56:26.395  7750  7750 V BtOppService: onCreate
,09-11 11:56:26.399  7750  7750 V BluetoothOppNotification: send message
09-11 11:56:26.402  7750  7750 V BtOppService: Starting RfcommListener
09-11 11:56:26.409  7750  7750 D BluetoothOppPreference: Dumping Names:  
09-11 11:56:26.409  7750  7750 D BluetoothOppPreference: {}
,09-11 11:56:26.409  7750  7750 D BluetoothOppPreference: Dumping Channels:  
09-11 11:56:26.409  7750  7750 D BluetoothOppPreference: {}
09-11 11:56:26.411  7750  7750 V BtOppService: onStartCommand
09-11 11:56:26.414  7750  8060 V BtOppService: Deleted complete outbound shares, number =  0
09-11 11:56:26.416  7750  8060 V BtOppService: Deleted complete inbound failed shares, number = 0
09-11 11:56:26.417  7750  8060 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-11 11:56:26.418  7750  7750 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:26.418  7750  8063 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-11 11:56:26.419  7750  8063 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-11 11:56:26.419  7750  7750 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-11 11:56:26.419  7750  8060 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33b69ee6 on behalf of 
09-11 11:56:26.423  7750  8063 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@350fec27 on behalf of 
09-11 11:56:26.423  7750  7750 V BluetoothOppNotification: new notify threadi!
,09-11 11:56:26.425  7750  7750 V BluetoothOppNotification: send delay message
09-11 11:56:26.426  7750  8063 V BluetoothOppNotification: update too frequent, put in queue
09-11 11:56:26.426  7750  8064 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-11 11:56:26.427  7750  7750 V BtOppService: start RfcommListener
09-11 11:56:26.428  7750  8063 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-11 11:56:26.429  7750  8064 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ee59ed4 on behalf of 
09-11 11:56:26.430  7750  8064 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-11 11:56:26.431  7750  8064 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-11 11:56:26.433  7750  8064 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a21687d on behalf of 
09-11 11:56:26.435  7750  7750 V BtOppService: RfcommListener started
09-11 11:56:26.435  7750  7750 V BtOppService: ContentObserver received notification
09-11 11:56:26.435  7750  8064 V BluetoothOppNotification: outbound: succ-0  fail-0
09-11 11:56:26.436  7750  7750 V BtOppService: ContentObserver received notification
,09-11 11:56:26.440  7750  8066 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-11 11:56:26.440  7750  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-11 11:56:26.441  7750  8065 V BtOppRfcommListener: Starting RFCOMM listener....
09-11 11:56:26.441  7750  8064 V BluetoothOppNotification: outbound notification was removed.
09-11 11:56:26.442  1031  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:26.442  7750  8064 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-11 11:56:26.442  7750  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bbdc372 on behalf of 
09-11 11:56:26.443  7750  8065 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:26.444  7750  8065 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-11 11:56:26.444  7750  8065 V BtOppRfcommListener: Started RFCOMM listener....
09-11 11:56:26.444  7750  8065 I BtOppRfcommListener: Accept thread started.
09-11 11:56:26.445  7750  8065 V BtOppRfcommListener: Accepting connection...
09-11 11:56:26.446  7750  8064 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d8523c3 on behalf of 
09-11 11:56:26.447  7750  8064 V BluetoothOppNotification: inbound: succ-0  fail-0
09-11 11:56:26.449  7750  8066 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-11 11:56:26.452  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
,09-11 11:56:26.452  7750  7750 V BluetoothFtpService: Ftp Service onCreate
09-11 11:56:26.452  7750  7750 I BluetoothFtpService: Ftp Service onCreate
09-11 11:56:26.452  7750  7750 V BluetoothFtpService: Ftp Service onStartCommand
09-11 11:56:26.452  7750  7750 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:26.453  7750  7750 V BluetoothFtpService: Starting Listening on sockets
09-11 11:56:26.453  7750  7750 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-11 11:56:26.453  7750  7750 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-11 11:56:26.453  7750  7750 V BluetoothSapReceiver: SapReceiver onReceive 
09-11 11:56:26.453  7750  7750 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:26.453  7750  7750 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-11 11:56:26.453  7750  7750 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-11 11:56:26.454  7750  8064 V BluetoothOppNotification: inbound notification was removed.
09-11 11:56:26.455  7750  8064 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-11 11:56:26.456  7750  7750 V BluetoothFtpService: Handler(): got msg=1
09-11 11:56:26.457  7750  7750 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-11 11:56:26.457  7750  7750 V BluetoothFtpService: Ftp Service initSocket
09-11 11:56:26.459  7750  8064 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e610f79 on behalf of 
09-11 11:56:26.465  1031  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:26.466  7750  7750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:26.467  7750  7750 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,09-11 11:56:26.468  7750  7750 V BluetoothFtpService: Succeed to create listening socket on channel 20
,09-11 11:56:26.471  7750  8067 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-11 11:56:26.492  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c3c880a
09-11 11:56:26.492  7750  7750 V BluetoothSapService: Sap Service onCreate
,09-11 11:56:26.495  7750  7750 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:26.495  7750  7750 V BluetoothSapService: state: 12
09-11 11:56:26.495  7750  7750 V BluetoothSapService: Starting SAP server process
09-11 11:56:26.498  7750  7750 V BluetoothSapService: SAP Service startRfcommListenerThread
09-11 11:56:26.479  8068  8068 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:26.479  8068  8068 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:26.501  7750  8069 V BluetoothSapService: Sap Service initRfcommSocket
09-11 11:56:26.502  1031  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:26.504  7750  8069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:26.506  7750  8069 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-11 11:56:26.506  7750  8069 V BluetoothSapService: Succeed to create listening socket 
09-11 11:56:26.506  7750  8069 V BluetoothSapService: Accepting socket connection...
,09-11 11:56:26.514  8068  8068 V BT_SAP  : Event pipe created
,09-11 11:56:26.514  8068  8068 V BT_SAP  : create_server_socket qcom.sap.server
,09-11 11:56:26.514  8068  8068 V BT_SAP  : created socket fd 6
09-11 11:56:26.996  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:26.996  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:26.996  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:26.996  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:26.996  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:26.996  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:26.996  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:26.996  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:27.005  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:27.009  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:27.009  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2eddd33f added. We now have 8 listener(s)
,09-11 11:56:27.009  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:27.012  1031  1641 D WifiServiceImplEx: setWifiEnabled: false pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-11 11:56:27.012  1031  1641 D WifiService: setWifiEnabled: false pid=6629, uid=10118
09-11 11:56:27.012  1031  1641 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-11 11:56:27.019  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:27.024  1031  1891 D WifiServiceImplEx: setWifiEnabled: true pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-11 11:56:27.025  1031  1891 D WifiService: setWifiEnabled: true pid=6629, uid=10118
09-11 11:56:27.025  1031  1891 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-11 11:56:27.043  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-11 11:56:27.043  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-11 11:56:27.043  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,09-11 11:56:27.045  1031  1525 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-11 11:56:27.045  1031  1525 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-11 11:56:27.048  1031  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-11 11:56:27.048  1031  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-11 11:56:27.048  1031  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-11 11:56:27.048  1031  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-11 11:56:27.048  1031  1525 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-11 11:56:27.048  1031  1525 E WifiHW  : unknown target_country: EU , set to default
09-11 11:56:27.048  1031  1525 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,09-11 11:56:27.048  1031  1525 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-11 11:56:27.048  1031  1525 I WifiUtil: gEnableBmps=1
09-11 11:56:27.426  7750  7750 V BluetoothOppNotification: new notify threadi!
09-11 11:56:27.427  7750  7750 V BluetoothOppNotification: send delay message
,09-11 11:56:27.442  7750  8082 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-11 11:56:27.491  7750  8082 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c5a2a35 on behalf of 
,09-11 11:56:27.492  7750  8082 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-11 11:56:27.496  7750  8082 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-11 11:56:27.497  7750  8082 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@253e4eca on behalf of 
09-11 11:56:27.498  7750  8082 V BluetoothOppNotification: outbound: succ-0  fail-0
09-11 11:56:27.500  7750  8082 V BluetoothOppNotification: outbound notification was removed.
09-11 11:56:27.500  7750  8082 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-11 11:56:27.501  7750  8082 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11c5483b on behalf of 
09-11 11:56:27.502  7750  8082 V BluetoothOppNotification: inbound: succ-0  fail-0
09-11 11:56:27.503  7750  8082 V BluetoothOppNotification: inbound notification was removed.
09-11 11:56:27.503  7750  8082 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-11 11:56:27.504  7750  8082 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5a3eb58 on behalf of 
,09-11 11:56:27.654   306   890 D SoftapController: Softap fwReload - Ok
,09-11 11:56:27.757  1031  1525 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (705ms)
,09-11 11:56:27.761   306   890 D CommandListener: Setting iface cfg
09-11 11:56:27.761   306   890 D CommandListener: Trying to bring down wlan0
09-11 11:56:27.762   306   890 D CommandListener: Clearing all IP addresses on wlan0
09-11 11:56:27.763  1031  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-11 11:56:27.768  1031  1102 D Tethering: InitialState.processMessage what=4
09-11 11:56:27.772  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-11 11:56:27.779  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:27.779  1031  1525 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-11 11:56:27.779  6888  6888 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-11 11:56:27.779  6888  6888 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-11 11:56:27.779  6888  6888 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-11 11:56:27.780  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-11 11:56:27.782  6888  6888 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-11 11:56:27.782  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-11 11:56:27.782  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-11 11:56:27.782  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-11 11:56:27.782  6888  6888 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-11 11:56:27.782  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-11 11:56:27.782  6888  6888 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-11 11:56:27.769  8104  8104 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:27.769  8104  8104 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-11 11:56:27.791  1031  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-11 11:56:27.791  1031  1525 E WifiStateMachine: useWiFiOffloading() : false
09-11 11:56:27.791  1031  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-11 11:56:27.792  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:27.792  6888  6888 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-11 11:56:27.792  6888  6888 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-11 11:56:27.792  6888  6888 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-11 11:56:27.793  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-11 11:56:27.793  1031  1525 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-11 11:56:27.793  1031  1525 D WifiMonitor: connecting to supplicant
09-11 11:56:27.798  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-11 11:56:27.798  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-11 11:56:27.801  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:27.802  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-11 11:56:27.804  6888  6888 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-11 11:56:27.804  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-11 11:56:27.804  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-11 11:56:27.804  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-11 11:56:27.804  6888  6888 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-11 11:56:27.804  6888  6888 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-11 11:56:27.805  8104  8104 I wpa_supplicant: Successfully initialized wpa_supplicant
09-11 11:56:27.827  8104  8104 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-11 11:56:27.827  8104  8104 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-11 11:56:27.840  1031  1760 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8108 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-11 11:56:27.886  8104  8104 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-11 11:56:27.920  8104  8104 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-11 11:56:27.927  1031  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-11 11:56:27.928  1031  1525 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-11 11:56:27.929  1031  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-11 11:56:27.931  1031  1525 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-11 11:56:27.932  1031  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:27.933  1031  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:27.934  1031  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-11 11:56:27.935  1031  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:27.937  1031  1525 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-11 11:56:27.937  1031  1525 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-11 11:56:27.938  1031  1525 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-11 11:56:27.939  1031  1525 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-11 11:56:27.939  1031  1525 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-11 11:56:27.970  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-11 11:56:27.970  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-11 11:56:27.971  8104  8104 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-11 11:56:27.971  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-11 11:56:27.971  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-11 11:56:27.971  1031  8129 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-11 11:56:27.971  1031  8129 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,09-11 11:56:27.979  1031  1873 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8131 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-11 11:56:27.985  1031  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-11 11:56:27.985  1031  1525 E WifiStateMachine: useWiFiOffloading() : false
09-11 11:56:27.985  1031  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-11 11:56:27.986  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:27.986  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:27.986  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:27.987  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:27.987  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-11 11:56:27.988  1031  1525 D WifiNative-wlan0: doBoolean: SET update_config 1
09-11 11:56:27.988  8108  8128 W FormManager: Network not available. Please check & try again.
09-11 11:56:27.989  1031  1525 D WifiNative-wlan0: SET update_config 1: returned true
09-11 11:56:27.989  1031  1525 D WifiConfigStore: Loading config and enabling all networks 
09-11 11:56:27.989  1031  1525 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-11 11:56:27.991  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-11 11:56:27.991  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:27.992  1031  1525 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-11 11:56:27.992  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-11 11:56:27.993  1928  1928 D WfdService: Waiting for WifiP2p enabling
09-11 11:56:27.995  8108  8130 V FormManager: Network unavailable.
09-11 11:56:27.996  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:27.996  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:27.996  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:27.996  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:27.996  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:27.996  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:27.996  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:27.996  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:27.998  8108  8130 V FormManager: Network unavailable.
,09-11 11:56:28.000  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:28.006  1031  1525 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-11 11:56:28.017  1031  1525 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-11 11:56:28.018  1031  1525 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-11 11:56:28.019  1031  1525 D WifiStateMachine: enableVerboseLogging : level 2
09-11 11:56:28.019  1031  1525 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-11 11:56:28.020  1031  1525 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-11 11:56:28.020  1031  1525 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-11 11:56:28.020  1031  1525 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-11 11:56:28.020  1031  1525 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-11 11:56:28.021  1031  1525 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-11 11:56:28.021  1031  1525 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-11 11:56:28.021  1031  1525 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-11 11:56:28.021  1031  1525 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-11 11:56:28.022  1031  1525 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-11 11:56:28.022  1031  1525 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-11 11:56:28.022  1031  1525 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-11 11:56:28.022  1031  1525 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-11 11:56:28.023  1031  1525 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-11 11:56:28.024  1031  1641 I ActivityManager: Killing 7212:com.android.chrome/u0a57 (adj 15): empty #17
09-11 11:56:28.056  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:28.056  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:28.056  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:28.056  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:28.056  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:28.056  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:28.056  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:28.056  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:28.058  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:28.066  6629  6700 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-11 11:56:28.067  6629  6700 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-11 11:56:28.070  1031  1525 D WifiStateMachine: Setting OUI to DA-A1-19
09-11 11:56:28.070  1031  1525 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-11 11:56:28.072  1031  1525 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-11 11:56:28.072  1031  1525 D WifiNative-HAL: Setting external_sim to 1
09-11 11:56:28.072  1031  1525 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-11 11:56:28.073  1031  1918 W libprocessgroup: failed to open /acct/uid_10057/pid_7212/cgroup.procs: No such file or directory
09-11 11:56:28.073  1031  1525 D WifiNative-wlan0: SET external_sim 1: returned true
09-11 11:56:28.073  1031  1525 I WifiNative-HAL: startHal
09-11 11:56:28.073  1031  1525 D wifi    : setting scan oui 0xaf742040
09-11 11:56:28.073  1031  1525 D WifiStateMachine: Setting OUI to DA-A1-19
09-11 11:56:28.073  1031  1525 I WifiNative-HAL: startHal
09-11 11:56:28.073  6629  6700 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@235e4b29 Bundle[{}]
09-11 11:56:28.073  1031  1525 D wifi    : setting scan oui 0xaf742040
09-11 11:56:28.074  1031  1525 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-11 11:56:28.074  1031  1525 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-11 11:56:28.075  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-11 11:56:28.075  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-11 11:56:28.075  1031  1525 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-11 11:56:28.075  6629  6700 I io.jxcore.node.LifeCycleMonitor: start: OK
09-11 11:56:28.075  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-11 11:56:28.075  6629  6700 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-11 11:56:28.075  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-11 11:56:28.076  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-11 11:56:28.076  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-11 11:56:28.076  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-11 11:56:28.076  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-11 11:56:28.076  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-11 11:56:28.077  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-11 11:56:28.077  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-11 11:56:28.077  6629  6700 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-11 11:56:28.077  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-11 11:56:28.077  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-11 11:56:28.077  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-11 11:56:28.077  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-11 11:56:28.078  8104  8104 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-11 11:56:28.078  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-11 11:56:28.078  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-11 11:56:28.078  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-11 11:56:28.078  6629  6700 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-11 11:56:28.079  1031  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-11 11:56:28.079  1031  1525 E WifiNative: : [135,536,986 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-11 11:56:28.079  1031  1525 D WifiNative-wlan0: doBoolean: RECONNECT
09-11 11:56:28.079  6629  6700 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-11 11:56:28.080  1031  1525 D WifiNative-wlan0: RECONNECT: returned true
09-11 11:56:28.080  1031  1525 D WifiNative-wlan0: doString: [STATUS]
09-11 11:56:28.080  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-11 11:56:28.080  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:0,0:00:00:00:00 SSID=
09-11 11:56:28.081  1031  1525 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-11 11:56:28.081  1031  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-11 11:56:28.081  6629  6700 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-11 11:56:28.081  1031  1525 D WifiNative-wlan0: SET ps 1: returned true
09-11 11:56:28.081  1031  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.084   306   890 D CommandListener: Setting iface cfg
09-11 11:56:28.084   306   890 D CommandListener: Trying to bring up p2p0
09-11 11:56:28.084  1031  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-11 11:56:28.085  1031  1524 D LGWifiP2pService: P2pEnablingState
09-11 11:56:28.085  1031  1524 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.085  1031  1524 D LGWifiP2pService: P2p socket connection successful
09-11 11:56:28.085  1031  1524 D LGWifiP2pService: P2pEnabledState
09-11 11:56:28.085  1031  1524 D LGWifiP2pService: sending p2p connection changed broadcast
09-11 11:56:28.086  1031  1525 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-11 11:56:28.086  1031  1525 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-11 11:56:28.086  1031  1525 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-11 11:56:28.087  1031  1525 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-11 11:56:28.087  1031  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=135545  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-11 11:56:28.088  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=135545  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-11 11:56:28.088  1031  1525 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-11 11:56:28.088  1031  1525 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-11 11:56:28.089  6629  6700 I System.out: Running OutgoingSocketThread
,09-11 11:56:28.090  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
09-11 11:56:28.090  1031  1031 D RttService: SCAN_AVAILABLE : 3
09-11 11:56:28.090  1031  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.090  1031  1543 I WifiNative-HAL: startHal
09-11 11:56:28.090  1031  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf742040
09-11 11:56:28.090  1031  1543 D wifi    : failed to get capabilities : -3
09-11 11:56:28.090  1031  1543 E WifiScanningService: could not get scan capabilities
09-11 11:56:28.091  1031  1544 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.091  6629  8149 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 877)
09-11 11:56:28.091  1031  1525 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-11 11:56:28.091  1031  1525 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-11 11:56:28.091  8104  8104 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-11 11:56:28.092  1031  1525 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-11 11:56:28.092  6629  8149 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 36447
09-11 11:56:28.092  7780  7780 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.092  6629  8149 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-11 11:56:28.093  1928  1928 D WfdsService: Supplicant Connection state is changed : true
09-11 11:56:28.093  1928  2275 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-11 11:56:28.093  1928  2275 D WfdsService: Set the WFDS Monitor: true
09-11 11:56:28.093  1928  2275 D WfdsMonitor: WfdsMonitorThread create
09-11 11:56:28.094  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-11 11:56:28.094  1928  2275 D WfdsMonitor: WFDS Monitor is created and started
09-11 11:56:28.094  1928  2275 D WfdsService: WiFi: Supplicant connection re-established
09-11 11:56:28.094  1928  1928 D WfdsService: WifiP2pState is changed : true
09-11 11:56:28.094  1928  2275 D WfdsService: Receive the WFDS_ENABLE Method
09-11 11:56:28.094  1928  2275 D WfdsService: Set the WFDS Monitor: true
09-11 11:56:28.094  1928  2275 D WfdsService: Connected to the supplicant for wfds
09-11 11:56:28.094  1031  1525 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-11 11:56:28.095  1928  2275 D WfdsJNI : doCommand: WFDS_SET TRUE
09-11 11:56:28.095  1031  1525 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-11 11:56:28.095  1928  2275 E CtrlSupplicant: Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
09-11 11:56:28.095  1031  1525 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-11 11:56:28.095  1928  2275 D WfdsJNI : wfds_send_command: [WFDS_SET TRUE] failed
09-11 11:56:28.095  8104  8104 E wpa_supplicant: disconnect_rssi_lvl: -100
09-11 11:56:28.095  1928  2275 D WfdsService: selectPreferredScanChannel [36]
09-11 11:56:28.095  1928  2275 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-11 11:56:28.095  1928  8150 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-11 11:56:28.095  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:28.095  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:28.096  1928  8150 E CtrlSupplicant: Succeed to open control connection
09-11 11:56:28.096  1031  1525 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-11 11:56:28.096  1928  8150 E CtrlSupplicant: Succeed to open monitor connection
09-11 11:56:28.096  1588  1588 D StatusBar.NetworkController: refreshView,s: Data not connected!! Set no data type icon / Roaming
09-11 11:56:28.096  1031  1525 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-11 11:56:28.097  1928  8150 D WfdsMonitor: Supplicant connection established
09-11 11:56:28.097  1031  1525 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-11 11:56:28.098  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-11 11:56:28.098  1928  2275 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
09-11 11:56:28.098  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-11 11:56:28.099  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.099  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.099  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-11 11:56:28.100  8104  8104 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:28.100  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-11 11:56:28.100  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:28.100  1031  8129 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:28.100  1031  8129 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:28.101  8104  8104 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-11 11:56:28.101  8104  8104 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.101  1031  8129 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:28.101  1031  8129 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.101  1031  8129 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.101  1031  8129 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.101  8104  8104 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.101  1031  8129 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:28.101  1031  8129 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.102  1031  8129 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.102  1031  8129 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.102  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-11 11:56:28.102  1928  1928 D WfdsService: isConnected: false
09-11 11:56:28.103  1928  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:28.103  1928  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:28.103  1031  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-11 11:56:28.103  1031  1525 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-11 11:56:28.104  1031  1525 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-11 11:56:28.104  1031  1525 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,09-11 11:56:28.104  1031  1525 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-11 11:56:28.104  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-11 11:56:28.104  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-11 11:56:28.104  8104  8104 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-11 11:56:28.105  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-11 11:56:28.105  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-11 11:56:28.105  1031  1525 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-11 11:56:28.105  1031  8129 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-11 11:56:28.105  1031  8129 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-11 11:56:28.105  1031  1525 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-11 11:56:28.106  1031  1525 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-11 11:56:28.106  1031  1525 D WifiNative-wlan0: doBoolean: SCAN
09-11 11:56:28.106  1031  1525 D WifiNative-wlan0: SCAN: returned false
09-11 11:56:28.107  1031  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=135564  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-11 11:56:28.107  1031  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-11 11:56:28.107  1031  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
,09-11 11:56:28.108  1031  1524 D WifiNative-p2p0: SET device_name G3: returned true
,09-11 11:56:28.108  1031  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-11 11:56:28.108  1031  1524 D LGWifiP2pService: before postfix = G3
09-11 11:56:28.108  1031  1524 D WifiServerServiceExt: postfix byte check : 2
09-11 11:56:28.108  1031  1524 D LGWifiP2pService: after postfix = G3
09-11 11:56:28.108  1031  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-11 11:56:28.109  1031  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-11 11:56:28.109  1031  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-11 11:56:28.109  1031  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-11 11:56:28.109  1031  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-11 11:56:28.110  1031  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-11 11:56:28.112  1031  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-11 11:56:28.112  1031  1524 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-11 11:56:28.112  1031  1524 D WifiNative-HAL: p2pGetDeviceAddress
09-11 11:56:28.113  1031  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-11 11:56:28.115  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=135573  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-11 11:56:28.116  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.116  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.116  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-11 11:56:28.118  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:28.118  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
09-11 11:56:28.118  1031  1524 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-11 11:56:28.118  1031  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-11 11:56:28.117  1031  1525 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-11 11:56:28.119  1031  1524 D WifiNative-p2p0: P2P_FLUSH: returned true
09-11 11:56:28.119  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
09-11 11:56:28.119  1031  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-11 11:56:28.119  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-11 11:56:28.119  1928  1928 D WfdsService: Update P2p Interface State: 3
09-11 11:56:28.119  1031  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-11 11:56:28.119  1031  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-11 11:56:28.119  1031  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-11 11:56:28.119  1031  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-11 11:56:28.120  1031  1525 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-11 11:56:28.120  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:28.120  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:28.121  1031  1525 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-11 11:56:28.121  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:28.122  1031  1525 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-11 11:56:28.123  1031  1525 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-11 11:56:28.124  1031  ,1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:28.124  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
09-11 11:56:28.127  1031  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-11 11:56:28.127  1031  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-11 11:56:28.127  1031  1524 D LGWifiP2pService: InactiveState
09-11 11:56:28.127  1031  1524 D LGWifiP2pService: InactiveState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.127  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.127  1031  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-11 11:56:28.127  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-11 11:56:28.128  8104  8104 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-11 11:56:28.128  1928  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-11 11:56:28.128  8104  8104 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-11 11:56:28.128  8104  8104 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.129  1928  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:28.129  1031  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
,09-11 11:56:28.129  1031  1524 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.129  1031  8129 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-11 11:56:28.129  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.129  1031  8129 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:28.129  1031  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.129  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.129  1031  8129 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:28.129  1031  1524 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.129  1031  8129 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-11 11:56:28.129  1031  8129 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:28.129  1031  8129 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.129  1031  8129 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.129  1031  8129 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-11 11:56:28.129  8104  8104 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.130  1031  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.130  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.130  1031  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.130  1928  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:28.130  1031  8129 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-11 11:56:28.130  1031  8129 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.130  1031  8129 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.130  1031  8129 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-11 11:56:28.130  1031  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.130  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.130  1031  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.130  1031  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.130  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,09-11 11:56:28.130  1031  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.131  1031  1031 E WifiServerServiceExt: No p2p device connected
09-11 11:56:28.131  1928  2275 W WfdsService: DefaultState - msg [9441285] is not handled
09-11 11:56:28.143  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:28.145  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:28.150  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-11 11:56:28.151  1031  1760 I ActivityManager: Killing 7236:com.lge.drmservice/u0a62 (adj 15): empty #17
09-11 11:56:28.181  1031  1891 W libprocessgroup: failed to open /acct/uid_10062/pid_7236/cgroup.procs: No such file or directory
,09-11 11:56:28.194  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-11 11:56:28.196  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:28.201  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:28.208  8108  8154 W FormManager: Network not available. Please check & try again.
,09-11 11:56:28.221  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-11 11:56:28.222  4807  4807 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-11 11:56:28.222  8108  8155 V FormManager: Network unavailable.
,09-11 11:56:28.225  8108  8155 V FormManager: Network unavailable.
09-11 11:56:28.226  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:28.228  4807  4807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-11 11:56:28.237  4807  8156 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-11 11:56:28.241  4807  8157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-11 11:56:28.242  4807  8157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-11 11:56:28.290  1031  1918 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8158 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-11 11:56:28.391  8158  8158 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-11 11:56:28.431  8158  8158 D PluginManager: init()
,09-11 11:56:28.729  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-11 11:56:28.730  1031  8129 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-11 11:56:28.731  1031  1525 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-11 11:56:28.732  1031  1525 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-11 11:56:28.733  1031  1525 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-11 11:56:28.734  1031  1525 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-11 11:56:28.734  1031  1525 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-11 11:56:28.739  8104  8104 E wpa_supplicant: USIM:  scard_init function
09-11 11:56:28.740  8104  8104 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-11 11:56:28.740  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-11 11:56:28.741  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
09-11 11:56:28.741  1031  8129 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-11 11:56:28.741  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-11 11:56:28.741  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-11 11:56:28.750  1031  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=136208  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-11 11:56:28.754  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=136212  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-11 11:56:28.761  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.761  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.761  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-11 11:56:28.762  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:28.762  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:28.763  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:28.766  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:28.766  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-11 11:56:28.873  1031  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-11 11:56:28.875  8104  8104 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-11 11:56:28.877  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-11 11:56:28.877  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-11 11:56:28.877  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-11 11:56:28.877  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-11 11:56:28.878  1031  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=136336  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-11 11:56:28.878  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=136336  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-11 11:56:28.882  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-11 11:56:28.882  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-11 11:56:28.883  1031  1525 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136340
09-11 11:56:28.883  1031  1525 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136341
09-11 11:56:28.883  1031  1525 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136341
09-11 11:56:28.883  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136341
09-11 11:56:28.883  1031  1525 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136341
09-11 11:56:28.884  1031  1525 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:28.884  1031  1525 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:28.884  1031  1525 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:28.884  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-11 11:56:28.885  1031  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-11 11:56:28.892  1031  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=136349  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-11 11:56:28.894  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:28.894  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-11 11:56:28.894  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.894  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.894  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-11 11:56:28.897  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:28.897  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:28.898  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.898  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.898  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-11 11:56:28.899  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=136357  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-11 11:56:28.900  8104  8104 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-11 11:56:28.900  8104  8104 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-11 11:56:28.901  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:28.901  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-11 11:56:28.902  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-11 11:56:28.902  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-11 11:56:28.902  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-11 11:56:28.902  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-11 11:56:28.902  1031  8129 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-11 11:56:28.902  1031  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=136360  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-11 11:56:28.902  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=136360  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-11 11:56:28.903  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:28.903  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-11 11:56:28.904  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-11 11:56:28.904  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-11 11:56:28.904  1031  8129 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-11 11:56:28.904  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-11 11:56:28.904  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-11 11:56:28.905  1031  1525 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=136363
09-11 11:56:28.905  1031  1525 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=136363
09-11 11:56:28.906  1031  1525 D WifiNative-wlan0: doString: [STATUS]
09-11 11:56:28.906  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:28.906  1031  8129 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-11 11:56:28.906  1031  8129 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-11 11:56:28.908  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:28.908  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:28.909  1031  1525 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-11 11:56:28.911  1031  1525 I WifiServiceExtension: setVHTCapabilityType  : false
09-11 11:56:28.912  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming,
,09-11 11:56:28.912  8158  8158 W ExternalStrings: load override strings
09-11 11:56:28.912  8158  8158 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:28.912  8158  8158 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:28.916  8158  8158 D StatusProvider: onCreate
09-11 11:56:28.919  1031  1525 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,09-11 11:56:28.919  1031  1525 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-11 11:56:28.921  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.921  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.921  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-11 11:56:28.927  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.927  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:28.927  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-11 11:56:28.929  1031  1525 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-11 11:56:28.929  1031  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-11 11:56:28.929  1031  1531 D ConnectivityService: Got NetworkAgent Messenger
09-11 11:56:28.929  1031  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-11 11:56:28.929  1031  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-11 11:56:28.929  1031  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-11 11:56:28.929  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-11 11:56:28.930  1031  1531 D ConnectivityService: NetworkAgent connected
09-11 11:56:28.935  1031  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-11 11:56:28.935  1031  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-11 11:56:28.935  1031  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-11 11:56:28.935  1031  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-11 11:56:28.935  1031  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-11 11:56:28.936  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:28.936  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:28.938  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-11 11:56:28.941  1031  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-11 11:56:28.943   306   890 D CommandListener: Setting iface cfg
09-11 11:56:28.944  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:28.944  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:28.945  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:28.948  1031  1525 E WifiStateMachine: Start Dhcp Watchdog 3
09-11 11:56:28.949  1031  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=136406  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-11 11:56:28.949  1031  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=136407  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-11 11:56:28.954  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=136412  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-11 11:56:28.955  1031  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=136413  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-11 11:56:28.956  1031  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=136413  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-11 11:56:28.956  1031  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=136414  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-11 11:56:28.957  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14173] from screen [on:0 period:414006429] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-11 11:56:28.958  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:414006430] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-11 11:56:28.958  1031  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-11 11:56:28.958  1031  8182 D DhcpStateMachine: StoppedState
09-11 11:56:28.958  1031  8182 D DhcpStateMachine: StoppedState{ when=-10ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.958  1031  8182 D DhcpStateMachine: WaitBeforeStartState
09-11 11:56:28.963  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:28.964  1031  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-11 11:56:28.965  8158  8158 V Signer  : override build config not found
09-11 11:56:28.965  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.965  8158  8158 D Signer  : value of property debug is false
09-11 11:56:28.965  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.966  1031  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.966  1031  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.967  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.967  1031  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.968  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-11 11:56:28.968  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:28.968  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-11 11:56:28.969  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-11 11:56:28.969  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-11 11:56:28.970  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=191,0,0
09-11 11:56:28.970  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=191,0,0
09-11 11:56:28.970  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,09-11 11:56:28.971  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-11 11:56:28.971  1031  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-11 11:56:28.971  1031  1525 D WifiNative-wlan0: doBoolean: SET ps 0
09-11 11:56:28.972  1031  1525 D WifiNative-wlan0: SET ps 0: returned true
09-11 11:56:28.972  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-11 11:56:28.972  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-11 11:56:28.972  1031  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-11 11:56:28.975  1031  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29c8ee52 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.975  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29c8ee52 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.976  1031  8182 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:28.976  1031  8182 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-11 11:56:28.983  1031  1525 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-11 11:56:28.983  1031  1525 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-11 11:56:28.983  1031  1525 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-11 11:56:28.991   306   890 D CommandListener: Setting iface cfg
09-11 11:56:28.991   306   890 D CommandListener: Trying to bring up wlan0
,09-11 11:56:28.992  1031  1525 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-11 11:56:28.994  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.995  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.996  1031  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.997  1031  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.997  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-11 11:56:28.997  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-11 11:56:28.997  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-11 11:56:28.997  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-11 11:56:28.998  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-11 11:56:28.998  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-11 11:56:28.998  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-11 11:56:28.998  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-11 11:56:28.998  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.998  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-11 11:56:28.998  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-11 11:56:28.998  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-11 11:56:28.999  1031  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-11 11:56:28.999  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-11 11:56:28.999  8158  8158 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-11 11:56:29.006  8158  8158 V LGMDMManager: Create singleton instance
09-11 11:56:29.009  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-11 11:56:29.009  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,09-11 11:56:29.010  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-11 11:56:29.010  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-11 11:56:29.010  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-11 11:56:29.011  1031  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-11 11:56:29.011  1031  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-11 11:56:29.011  8104  8104 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-11 11:56:29.011  1031  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-11 11:56:29.011  1031  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-11 11:56:29.012  1031  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:29.012  1031  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:29.027  1031  1525 D WifiNative-wlan0: SET ps 1: returned true
09-11 11:56:29.027  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-11 11:56:29.028  1031  1525 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-11 11:56:29.028  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,09-11 11:56:29.028  1031  1525 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-11 11:56:29.030  1031  1531 D ConnectivityService: ignoring duplicate network state non-change
09-11 11:56:29.032  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:29.032  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:29.033  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:29.033  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:29.033  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-11 11:56:29.033  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:29.034  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-11 11:56:29.035  1031  1531 D ConnectivityService: Adding iface wlan0 to network 102
,09-11 11:56:29.035  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:29.035  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:29.036  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-11 11:56:29.036  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-11 11:56:29.037  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-11 11:56:29.038  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:29.038  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:29.038  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-11 11:56:29.039  1031  1525 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-11 11:56:29.040  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-11 11:56:29.043  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:29.043  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:29.043  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-11 11:56:29.054  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:29.054  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-11 11:56:29.055  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-11 11:56:29.058  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:29.058  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-11 11:56:29.058  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-11 11:56:29.061  1031  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-11 11:56:29.061  1031  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-11 11:56:29.061  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:29.062  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-11 11:56:29.062  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:29.062  1031  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-11 11:56:29.063   306   890 E Netd    : netlink response contains error (File exists)
09-11 11:56:29.063  1031  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-11 11:56:29.064  1031  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-11 11:56:29.064  1031  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-11 11:56:29.064  1031  1531 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-11 11:56:29.065  1031  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-11 11:56:29.065  1031  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-11 11:56:29.065  1031  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-11 11:56:29.065  1031  8181 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:29.065  1031  8181 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-11 11:56:29.065  1031  8181 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:29.065  1031  8181 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-11 11:56:29.068  1031  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-11 11:56:29.068  1031  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:29.068  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:29.068   306  8197 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-11 11:56:29.068  1031  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-11 11:56:29.068  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:29.068  1031  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-11 11:56:29.068  1031  1531 D ConnectivityService: currentScore = 0, newScore = 20
09-11 11:56:29.068  1031  1531 D ConnectivityService:    accepting network in place of null
09-11 11:56:29.068  1031  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:29.068  1031  1525 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:29.068  1031  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:,29.069  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:29.069  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-11 11:56:29.070  1031  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-11 11:56:29.070  1031  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-11 11:56:29.070  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-11 11:56:29.070  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:29.070  1031  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-11 11:56:29.071  1031  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-11 11:56:29.071  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-11 11:56:29.071  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-11 11:56:29.071  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-11 11:56:29.071  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-11 11:56:29.072  1031  1531 D ConnectivityService: validation of new default Network = false
09-11 11:56:29.072  1031  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-11 11:56:29.072  1031  1531 D DSQN    : enableDataServiceNotify 
09-11 11:56:29.072  1031  1531 D DSQN    : start dsqn bin
,09-11 11:56:29.079  1031  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-11 11:56:29.079  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:29.080  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:29.069  8199  8199 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:29.080  1031  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:29.080  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-11 11:56:29.069  8199  8199 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:29.088  1031  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-11 11:56:29.091  6629  6700 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 878)
09-11 11:56:29.091  6629  6700 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 878)
09-11 11:56:29.093  8158  8158 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
09-11 11:56:29.094  8199  8199 E DSQN    : DSQN ssw
09-11 11:56:29.095  6629  6700 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 883)
09-11 11:56:29.096  6629  6700 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-11 11:56:29.096  6629  6700 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 884)
09-11 11:56:29.100  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:29.100  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8a540c added. We now have 2 listener(s)
09-11 11:56:29.100  1031  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-11 11:56:29.102  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:56:29.102  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:29.102  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:29.102  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:29.102  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c9a155 added. We now have 9 listener(s)
09-11 11:56:29.102  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:29.103  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:56:29.104  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:29.107  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:29.107  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:29.107  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:29.107  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:29.107  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:29.107  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:29.107  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:29.107  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:29.109  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:29.109  6629  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:29.109  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:29.109  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@466645b added. We now have 3 listener(s)
09-11 11:56:29.109  1031  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:29.110  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-11 11:56:29.111  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:29.112  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:29.112  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:29.113  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:29.114  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:56:29.114  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:5,6:29.114  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:29.114  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:29.114  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8ea4f8 added. We now have 10 listener(s)
09-11 11:56:29.114  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:29.114  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:29.114  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:29.114  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:29.114  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:29.114  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.114  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:29.114  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:29.114  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8a540c removed from the list
09-11 11:56:29.114  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.114  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c9a155 removed from the list
09-11 11:56:29.114  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:29.114  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.115  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.115  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.116  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:29.116  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:29.116  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.116  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c9a155 not in the list
09-11 11:56:29.116  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.116  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.116  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:29.116  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:29.116  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.117  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8ea4f8 removed from the list
09-11 11:56:29.117  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:29.117  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.117  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.117  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:29.117  6629  6700 V org.thaliproject.p2p.btconnectorlib.Connec,tionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@466645b removed from the list
09-11 11:56:29.117  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:29.117  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31cffdd1 added. We now have 2 listener(s)
09-11 11:56:29.117  1031  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:29.119  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:56:29.119  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:29.119  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:29.119  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:29.119  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@358af036 added. We now have 9 listener(s)
09-11 11:56:29.120  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:29.120  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:56:29.121  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:29.124  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:29.124  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:29.124  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:29.124  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:29.124  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:29.124  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:29.124  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:29.124  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:29.125  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:29.125  6629  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:29.125  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:29.125  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8518a4 added. We now have 3 listener(s)
09-11 11:56:29.125  1031  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-11 11:56:29.126  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:29.128  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:29.128  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:56:29.128  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:29.128  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:29.128  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:29.128  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1505a60d added. We now have 10 listener(s)
09-11 11:56:29.128  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:29.128  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:29.128  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:29.128  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:29.128  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:29.128  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-11 11:56:29.130  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-11 11:56:29.130  1031  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:29.131   306  8197 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-11 11:56:29.134  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-11 11:56:29.135  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-11 11:56:29.136  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-11 11:56:29.136  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:29.138  6629  6700 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-11 11:56:29.138  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:29.138  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:29.140  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:29.140  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:29.140  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:29.140  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:29.140  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.140  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:29.140  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:29.140  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31cffdd1 removed from the list
09-11 11:56:29.140  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.140  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@358af036 removed from the list
09-11 11:56:29.140  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:29.140  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.140  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.140  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.141  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:29.141  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:29.141  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.141  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@358af036 not in the list
09-11 11:56:29.141  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.141  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.142  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:29.142  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:29.142  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:29.142  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:29.142  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.142  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryMa,nagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1505a60d removed from the list
09-11 11:56:29.142  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:29.142  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.142  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.142  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:29.142  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8518a4 removed from the list
09-11 11:56:29.143  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:29.143  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e4d1b10 added. We now have 2 listener(s)
09-11 11:56:29.143  1031  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:29.146  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:56:29.146  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:29.146  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:29.146  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:29.146  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3739609 added. We now have 9 listener(s)
09-11 11:56:29.146  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:29.146  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:56:29.148  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:29.151  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:29.151  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:29.151  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:29.151  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:29.151  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:29.151  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:29.151  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:29.151  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:29.153  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:29.153  6629  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:29.153  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:29.153  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a380a2f added. We now have 3 listener(s)
09-11 11:56:29.153  1031  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:29.155  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:29.156  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:29.156  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:29.157  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:56:29.157  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:29.157  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:29.157  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:29.157  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c50d83c added. We now have 10 listener(s)
09-11 11:56:29.157  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:29.157  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:29.158  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:29.158  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:29.158  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:29.158  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:29.158  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-11 11:56:29.162  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-11 11:56:29.162  1031  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:29.162  8158  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-11 11:56:29.164   306  8197 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-11 11:56:29.167  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-11 11:56:29.168  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-11 11:56:29.168  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-11 11:56:29.170  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-11 11:56:29.170  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:29.172  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:29.172  6629  6700 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-11 11:56:29.172  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:29.172  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:29.172  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:29.172  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:29.172  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.172  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:29.172  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:29.172  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e4d1b10 removed from the list
09-11 11:56:29.172  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.172  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3739609 removed from the list
09-11 11:56:29.172  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:29.172  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.173  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.173  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.173  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:29.173  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:29.173  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.173  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3739609 not in the list
09-11 11:56:29.173  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.173  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.174  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:29.175  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:29.175  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:29.175  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:29.175  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.175  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c50d83c removed from the list
09-11 11:56:29.175  6629  6700 I org.thaliproject.p2p.btconnectorlib.Con,nectionManager: dispose
09-11 11:56:29.175  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.175  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.175  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:29.175  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a380a2f removed from the list
09-11 11:56:29.175  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:29.176  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@451a4b added. We now have 2 listener(s)
09-11 11:56:29.182  1031  8182 D DhcpStateMachine: DHCPV4 request on wlan0
09-11 11:56:29.183  1031  8182 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-11 11:56:29.183  1031  8182 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-11 11:56:29.169  8208  8208 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:29.169  8208  8208 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-11 11:56:29.188   306   889 D LGDataListener: argv[0]=dsqncommand
09-11 11:56:29.188   306   889 D LGDataListener: argv[1]=wlan0
09-11 11:56:29.188   306   889 D LGDataListener: argv[2]=1
09-11 11:56:29.189   306   889 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-11 11:56:29.189  1031  1100 D DSQN    : DSQM DsqnNotification wlan0  1
09-11 11:56:29.189  1031  1100 D DSQN    : start to monitor internet connection
09-11 11:56:29.195  8208  8208 I dhcpcd  : version 5.5.6 starting
,09-11 11:56:29.197  8208  8208 E dhcpcd  : get_duid: m
09-11 11:56:29.197  8208  8208 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-11 11:56:29.197  8208  8208 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-11 11:56:29.202  1031  1049 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8211 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-11 11:56:29.203  1031  1049 I ActivityManager: Killing 7259:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-11 11:56:29.214  1031  8181 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 11 Sep 2016 09:56:29 GMT], X-Android-Received-Millis=[1473587789214], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473587789188]}
09-11 11:56:29.214  1031  8181 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-11 11:56:29.214  1031  8181 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,09-11 11:56:29.215   340   340 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 246us total 14.658ms
09-11 11:56:29.215  1031  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-11 11:56:29.215  1031  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-11 11:56:29.215  1031  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:29.215  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:29.215  1031  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-11 11:56:29.215  1031  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-11 11:56:29.215  1031  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-11 11:56:29.215  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:29.215  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:29.216  1031  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:29.216  1031  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:29.216  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-11 11:56:29.216  1031  1525 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:29.216  1031  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:29.217  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-11 11:56:29.217  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:29.217  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-11 11:56:29.226   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 10.660ms
,09-11 11:56:29.236   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 200us total 9.674ms
09-11 11:56:29.253  8208  8208 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-11 11:56:29.253  8208  8208 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-11 11:56:29.253  8208  8208 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-11 11:56:29.254  8208  8208 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-11 11:56:29.254  8208  8208 D dhcpcd  : wlan0: sending REQUEST (xid 0x2c421719), next in 4.15 seconds
09-11 11:56:29.316  8158  8204 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-11 11:56:29.330  1031  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-11 11:56:29.332  1031  2019 W libprocessgroup: failed to open /acct/uid_10085/pid_7259/cgroup.procs: No such file or directory
,09-11 11:56:29.336  8208  8208 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-11 11:56:29.338  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:56:29.338  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:29.338  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:29.338  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:29.338  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c713c28 added. We now have 9 listener(s)
09-11 11:56:29.338  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:29.338  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:56:29.340  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:29.345  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:29.345  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:29.345  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:29.345  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:29.345  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:29.345  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:29.345  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:29.345  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:29.346  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:29.346  6629  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:29.346  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:29.346  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dcdd2e6 added. We now have 3 listener(s)
09-11 11:56:29.347  1031  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:29.348  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:56:29.348  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:29.348  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:29.348  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:29.348  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac91027 added. We now have 10 listener(s)
09-11 11:56:29.348  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:29.348  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:29.348  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:29.348  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:29.348  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:29.348  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-11 11:56:29.353  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:29.354  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-11 11:56:29.354  1031  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:29.355  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:29.357  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-11 11:56:29.359  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-11 11:56:29.360  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-11 11:56:29.360  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:29.362  6629  6700 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-11 11:56:29.363  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:29.364  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:29.364  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:29.364  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:29.364  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.364  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:29.364  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:29.364  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@451a4b removed from the list
09-11 11:56:29.364  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.364  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c713c28 removed from the list
09-11 11:56:29.364  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:29.364  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.364  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.364  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.365  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:29.365  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:29.365  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.365  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c713c28 not in the list
09-11 11:56:29.365  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.365  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.366  8208  8208 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-11 11:56:29.366  8208  8208 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-11 11:56:29.366  8208  8208 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-11 11:56:29.366  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:29.366  8208  8208 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-11 11:56:29.367  8208  8208 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-11 11:56:29.367  6629  6700 D BluetoothLeScanner: could not find callback wrapper
09-11 11:56:29.367  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:29.367  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:29.367  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.367  8208  8208 D dhcpcd  : getUs,ingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-11 11:56:29.367  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac91027 removed from the list
09-11 11:56:29.367  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:29.367  8208  8208 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-11 11:56:29.367  8208  8208 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-11 11:56:29.367  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.367  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.367  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:29.367  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dcdd2e6 removed from the list
09-11 11:56:29.368  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:29.368  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2143772 added. We now have 2 listener(s)
09-11 11:56:29.369  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-11 11:56:29.369  1031  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:29.370  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:29.370  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-11 11:56:29.371  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:56:29.371  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:29.371  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:29.371  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:29.371  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac87c3 added. We now have 9 listener(s)
09-11 11:56:29.371  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:29.371  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:56:29.373  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:29.375  6629  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:29.375  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:29.375  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-11 11:56:29.375  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:29.375  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:29.375  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:29.375  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:29.375  6629  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:29.376  8211  8211 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-11 11:56:29.376  6629  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:29.376  6629  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:29.376  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:29.377  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab11379 added. We now have 3 listener(s)
09-11 11:56:29.377  1031  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-11 11:56:29.379  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-11 11:56:29.379  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:29.379  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:29.380  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:29.380  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ea58be added. We now have 10 listener(s)
09-11 11:56:29.380  6629  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:29.380  6629  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:29.380  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:29.380  6629  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:29.380  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:29.380  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.380  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:29.380  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:29.380  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2143772 removed from the list
09-11 11:56:29.380  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.380  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac87c3 removed from the list
,09-11 11:56:29.389  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:29.389  6629  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:29.389  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.390  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.390  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.392  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:29.392  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:29.392  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.392  6629  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac87c3 not in the list
09-11 11:56:29.392  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.392  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.393  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:29.393  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:29.393  6629  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:29.393  6629  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ea58be removed from the list
09-11 11:56:29.393  6629  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:29.393  6629  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:29.393  6629  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:29.393  6629  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:29.394  6629  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab11379 removed from the list
09-11 11:56:29.394  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:29.395  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-11 11:56:29.395  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-11 11:56:29.395  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-11 11:56:29.395  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:29.395  6629  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-11 11:56:29.396  6629  6700 V io.jxcore.node.StartStopOperation: is,TargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:29.410  6629  8239 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 891, name: My test thread name)
09-11 11:56:29.410  6629  8239 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 891, thread name: My test thread name)
09-11 11:56:29.410  6629  8239 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 891, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-11 11:56:29.413  6629  8241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 893, name: My test thread name)
09-11 11:56:29.413  6629  8241 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 893, thread name: My test thread name)
09-11 11:56:29.413  6629  8241 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 893, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-11 11:56:29.415  6629  6700 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-11 11:56:29.415  6629  6700 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-11 11:56:29.415  6629  6700 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-11 11:56:29.416  6629  6700 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-11 11:56:29.416  6629  6700 D com.test.thalitest.ThaliTestRunner: Total duration: 22900 ms
09-11 11:56:29.417  6629  6700 I jxcore-log: *Native tests were executed*
09-11 11:56:29.417  6629  6700 I jxcore-log: 
09-11 11:56:29.417  6629  6700 I jxcore-log: Total number of executed tests:  80
09-11 11:56:29.417  6629  6700 I jxcore-log: 
09-11 11:56:29.417  6629  6700 I jxcore-log: Number of passed tests:  80
09-11 11:56:29.417  6629  6700 I jxcore-log: 
09-11 11:56:29.418  6629  6700 I jxcore-log: Number of failed tests:  0
09-11 11:56:29.418  6629  6700 I jxcore-log: 
09-11 11:56:29.418  6629  6700 I jxcore-log: Number of ignored tests:  0
09-11 11:56:29.418  6629  6700 I jxcore-log: 
09-11 11:56:29.419  6629  6700 I jxcore-log: Total duration:  22900
09-11 11:56:29.419  6629  6700 I jxcore-log: 
09-11 11:56:29.419  6629  6700 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-11 11:56:29.419  6629  6700 I jxcore-log: 
09-11 11:56:29.425  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.425  6629  6700 I jxcore-log: 
,09-11 11:56:29.428  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.428  6629  6700 I jxcore-log: 
09-11 11:56:29.430  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.430  6629  6700 I jxcore-log: 
09-11 11:56:29.431  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.431  6629  6700 I jxcore-log: 
09-11 11:56:29.432  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.432  6629  6700 I jxcore-log: 
09-11 11:56:29.434  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.434  6629  6700 I jxcore-log: 
09-11 11:56:29.434  8211  8211 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-11 11:56:29.437  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.437  6629  6700 I jxcore-log: 
09-11 11:56:29.440  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-11 11:56:29.440  6629  6700 I jxcore-log: 
,09-11 11:56:29.441  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-11 11:56:29.441  6629  6700 I jxcore-log: 
09-11 11:56:29.442  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:29.442  6629  6700 I jxcore-log: 
09-11 11:56:29.443  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:29.443  6629  6700 I jxcore-log: 
09-11 11:56:29.443  6629  6629 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-11 11:56:29.444  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-11 11:56:29.444  6629  6700 I jxcore-log: 
09-11 11:56:29.445  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-11 11:56:29.445  6629  6700 I jxcore-log: 
09-11 11:56:29.446  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-11 11:56:29.446  6629  6700 I jxcore-log: 
09-11 11:56:29.446  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:29.446  6629  6700 I jxcore-log: 
09-11 11:56:29.447  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:29.447  6629  6700 I jxcore-log: 
09-11 11:56:29.448  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:29.448  6629  6700 I jxcore-log: 
09-11 11:56:29.448  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:29.448  6629  6700 I jxcore-log: 
09-11 11:56:29.449  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:29.449  6629  6700 I jxcore-log: 
09-11 11:56:29.450  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:29.450  6629  6700 I jxcore-log: 
09-11 11:56:29.451  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:29.451  6629  6700 I jxcore-log: 
09-11 11:56:29.451  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:29.451  6629  6700 I jxcore-log: 
09-11 11:56:29.452  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-11 11:56:29.452  6629  6700 I jxcore-log: 
09-11 11:56:29.452  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-11 11:56:29.452  6629  6700 I jxcore-log: 
09-11 11:56:29.453  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.453  6629  6700 I jxcore-log: 
09-11 11:56:29.454  6629  6700 I jxcore-log: DEBUG thaliMobileN,ativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.454  6629  6700 I jxcore-log: 
09-11 11:56:29.454  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.454  6629  6700 I jxcore-log: 
09-11 11:56:29.455  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.455  6629  6700 I jxcore-log: 
09-11 11:56:29.455  6629  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:29.455  6629  6700 I jxcore-log: 
,09-11 11:56:29.471  8211  8211 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-11 11:56:29.471  8211  8211 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,09-11 11:56:29.477  8211  8211 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-11 11:56:29.477  8211  8211 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-11 11:56:29.478  8211  8211 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-11 11:56:29.480  8211  8211 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-11 11:56:29.485  8211  8211 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-11 11:56:29.490  8211  8211 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:29.495  8211  8211 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:29.516  8211  8211 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-11 11:56:29.520  8211  8211 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-11 11:56:29.522  8211  8211 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-11 11:56:29.552  1031  1873 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8268 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-11 11:56:29.568  8158  8204 D LgDataFeature: LgDataFeature() Constructor: none
,09-11 11:56:29.568  8158  8204 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-11 11:56:29.589  1031  8182 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-11 11:56:29.590  1031  8182 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-11 11:56:29.590  1031  8182 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-11 11:56:29.590  1031  8182 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-11 11:56:29.590  1031  8182 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-11 11:56:29.590  1031  8182 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-11 11:56:29.590  1031  8182 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-11 11:56:29.590  1031  8182 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-11 11:56:29.590  1031  8182 D DhcpStateMachine: RunningState
,09-11 11:56:29.632  8257  8257 D AndroidRuntime: 
09-11 11:56:29.632  8257  8257 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-11 11:56:29.634  8268  8268 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-11 11:56:29.634  8257  8257 D AndroidRuntime: CheckJNI is OFF
09-11 11:56:29.634  8268  8268 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-11 11:56:29.637  8268  8268 V [BNRBootReceiver]: Boot Receiver Return
09-11 11:56:29.638  8268  8268 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-11 11:56:29.639  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:29.639  8158  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-11 11:56:29.644  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:29.650  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:29.652  1031  1048 I ActivityManager: Killing 7292:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-11 11:56:29.655  8158  8204 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-11 11:56:29.737  8257  8257 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-11 11:56:29.859  1031  1983 W libprocessgroup: failed to open /acct/uid_10093/pid_7292/cgroup.procs: No such file or directory
09-11 11:56:29.860  8211  8211 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:29.860  8211  8211 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:29.869  8211  8211 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-11 11:56:29.870  1031  1098 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-11 11:56:29.870  1031  1098 I ActivityManager: Killing 6629:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-11 11:56:29.888  8158  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,09-11 11:56:29.904  8158  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,09-11 11:56:29.906  8158  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-11 11:56:29.907  8158  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-11 11:56:29.907  8158  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-11 11:56:29.908  8158  8204 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-11 11:56:29.914  8158  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-11 11:56:29.917  8158  8204 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,09-11 11:56:29.939  1031  1945 I WindowState: WIN DEATH: Window{16f14748 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-11 11:56:29.940  1031  1530 D WifiService: Client connection lost with reason: 4
09-11 11:56:29.951  1031  1945 D InputDispatcher: Window went away: Window{16f14748 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-11 11:56:30.153  1031  1098 I ActivityManager:   Force finishing activity ActivityRecord{3bb5723d u0 com.test.thalitest/.MainActivity t6}
,09-11 11:56:30.202   328   350 E GBMv2   : DFP En is all cleared set to be enabled
,09-11 11:56:30.222  1031  1873 W ActivityManager: Spurious death for ProcessRecord{30a60d75 6629:com.test.thalitest/u0a118}, curProc for 6629: null
,09-11 11:56:30.229  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-11 11:56:30.230  1031  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-11 11:56:30.232  1031  1123 I ActivityManager:   Force finishing activity ActivityRecord{3bb5723d u0 com.test.thalitest/.MainActivity t6 f}
09-11 11:56:30.232  1031  1123 W ActivityManager: Duplicate finish request for ActivityRecord{3bb5723d u0 com.test.thalitest/.MainActivity t6 f}
09-11 11:56:30.238  6888  6888 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-11 11:56:30.250  2020  2020 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-11 11:56:30.252  2020  2020 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-11 11:56:30.255  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-11 11:56:30.265  1031  1439 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-11 11:56:30.271  3801  3801 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-11 11:56:30.275  7750  7750 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-11 11:56:30.275  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-11 11:56:30.278  1982  1982 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-11 11:56:30.311  1031  1562 V SIM_STK : Menu title from STK is T-Mobile
,09-11 11:56:30.329  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:30.331  8158  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-11 11:56:30.338  2489  2690 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-11 11:56:30.351  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-11 11:56:30.351  2020  2089 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,09-11 11:56:30.353  1928  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-11 11:56:30.353  1928  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3b6841da co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-11 11:56:30.355  1928  4071 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-11 11:56:30.356  1928  4071 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1810a60b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-11 11:56:30.360  1892  1892 D ActionManagerService: notifyUserLog: 1000003
09-11 11:56:30.360  4962  4962 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-11 11:56:30.360  3801  4952 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-11 11:56:30.361  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-11 11:56:30.373  2020  2020 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-11 11:56:30.374  1588  1644 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-11 11:56:30.374  1588  1644 D KeyguardModel: createShortcutInfo...
09-11 11:56:30.379  2020  2020 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-11 11:56:30.379  4962  4962 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-11 11:56:30.379  4962  4962 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-11 11:56:30.379  4962  4962 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-11 11:56:30.379  4962  4962 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-11 11:56:30.379  4962  4962 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-11 11:56:30.379  4962  4962 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:30.379  4962  4962 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:30.380  4962  4962 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:30.380  4962  4962 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:30.380  4962  4962 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:30.380  4962  4962 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-11 11:56:30.380  2020  2020 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-11 11:56:30.384  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-11 11:56:30.384  1588  1644 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-11 11:56:30.384  1588  1644 D KeyguardModel: createShortcutInfo...
09-11 11:56:30.385  5071  5071 I art     : Explicit concurrent mark sweep GC freed 8240(472KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 625us total 141.795ms
,09-11 11:56:30.390  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-11 11:56:30.391  3801  3817 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-11 11:56:30.395  1588  1644 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-11 11:56:30.395  1588  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-11 11:56:30.396  1588  1644 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-11 11:56:30.397  1588  1644 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-11 11:56:30.399  1588  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-11 11:56:30.400  1892  1892 D ActionManagerService: notifyUserLog: 1000004
09-11 11:56:30.401  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262123
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , expire_time: 0
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , display: false
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , animation: false }
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262287
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , expire_time: 0
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , display: false
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , animation: false }
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , create_time: 1473420113195
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , expire_time: 0
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , display: false
09-11 11:56:30.402  2020  2020 I GBoardWebViewUtils: , animation: false }
,09-11 11:56:30.403  3801  4952 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-11 11:56:30.403  1588  1644 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-11 11:56:30.407  1031  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
09-11 11:56:30.413  2020  8318 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,09-11 11:56:30.415  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-11 11:56:30.415  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-11 11:56:30.416  1588  1644 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-11 11:56:30.416  1588  1644 D KeyguardModel: createShortcutInfo...
09-11 11:56:30.417  1856  1856 D SplitUIManager: split_name #11 / not available #0
09-11 11:56:30.418  1856  1856 D SplitUIService: removed split : 
09-11 11:56:30.424  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:30.429  1588  1644 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-11 11:56:30.430  1588  1644 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-11 11:56:30.434  1588  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-11 11:56:30.434  1588  1644 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-11 11:56:30.436  1588  1644 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-11 11:56:30.436  1588  1644 D KeyguardModel: createShortcutInfo...
09-11 11:56:30.445  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-11 11:56:30.446  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-11 11:56:30.450  1588  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-11 11:56:30.450  1588  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-11 11:56:30.450  1588  1644 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-11 11:56:30.450  1588  1644 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-11 11:56:30.451  1588  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-11 11:56:30.451  1588  1644 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-11 11:56:30.458  1588  1644 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-11 11:56:30.458  1588  1644 D KeyguardModel: createShortcutInfo...
,09-11 11:56:30.461  1856  1856 D SplitUIManager: split_name #11 / not available #0
09-11 11:56:30.461  1856  1856 I SplitUIService: split app #11
09-11 11:56:30.465  8211  8211 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:30.466  8211  8211 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:30.466  8211  8211 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-11 11:56:30.467  1031  1031 I art     : Explicit concurrent mark sweep GC freed 79738(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.626ms total 219.720ms
09-11 11:56:30.467  1031  1123 I art     : WaitForGcToComplete blocked for 117.699ms for cause Explicit
,09-11 11:56:30.476  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:30.476  6888  6888 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-11 11:56:30.477  6888  6888 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-11 11:56:30.477  6888  6888 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-11 11:56:30.477  1588  1588 D KeyguardModel: handleShortcutListChanged...
09-11 11:56:30.477  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-11 11:56:30.478  1031  1927 V SIM_STK : Menu title from STK is T-Mobile
09-11 11:56:30.478  1031  1927 V SIM_STK : Menu title from STK is T-Mobile
09-11 11:56:30.489  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-11 11:56:30.499  1588  1644 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-11 11:56:30.499  1588  1644 D KeyguardModel: createShortcutInfo...
09-11 11:56:30.505  6888  6888 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-11 11:56:30.505  1588  1644 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-11 11:56:30.505  1588  1644 D KeyguardModel: createShortcutInfo...
,09-11 11:56:30.506  1588  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-11 11:56:30.506  1588  1644 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-11 11:56:30.507  1588  1644 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-11 11:56:30.507  1588  1644 D KeyguardModel: createShortcutInfo...
09-11 11:56:30.509  1588  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-11 11:56:30.509  1588  1644 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-11 11:56:30.510  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-11 11:56:30.510  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-11 11:56:30.510  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-11 11:56:30.510  6888  6888 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-11 11:56:30.510  6888  6888 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-11 11:56:30.510  6888  6888 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-11 11:56:30.514  1031  1760 V SIM_STK : Menu title from STK is T-Mobile
09-11 11:56:30.517  1588  1644 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-11 11:56:30.517  1588  1644 D KeyguardModel: createShortcutInfo...
09-11 11:56:30.518  1588  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-11 11:56:30.518  1588  1644 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-11 11:56:30.522  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:30.522  8158  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-11 11:56:30.523  1588  1644 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-11 11:56:30.523  1588  1644 D KeyguardModel: createShortcutInfo...
09-11 11:56:30.528  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:30.541  1031  1031 D administrator: Handling package changes for user 0
09-11 11:56:30.549  1588  1588 D KeyguardModel: handleShortcutListChanged...
09-11 11:56:30.549  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-11 11:56:30.550  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:30.557  1031  1983 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-11 11:56:30.557  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-11 11:56:30.557  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-11 11:56:30.557  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-11 11:56:30.557  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-11 11:56:30.557  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-11 11:56:30.557  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-11 11:56:30.558  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-11 11:56:30.558  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-11 11:56:30.558  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-11 11:56:30.558  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-11 11:56:30.558  7750  7750 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,09-11 11:56:30.558  8211  8211 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:30.558  8211  8211 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:30.559  8211  8211 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-11 11:56:30.562  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:30.569   321   434 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-11 11:56:30.569  3241  8324 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,09-11 11:56:30.585  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:30.591  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:30.598  8211  8211 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:30.598  8211  8211 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:30.599  8211  8211 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-11 11:56:30.601  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:30.606  2020  2020 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-11 11:56:30.607  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-11 11:56:30.607  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-11 11:56:30.609  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-11 11:56:30.610  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-11 11:56:30.611  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-11 11:56:30.612  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-11 11:56:30.614  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-11 11:56:30.618  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-11 11:56:30.626  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-11 11:56:30.626  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-11 11:56:30.626  1031  1031 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-11 11:56:30.626  8211  8211 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:30.627  8211  8211 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:30.627  8211  8211 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-11 11:56:30.630  1031  1103 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bc61ead u0 com.lge.launcher2/.Launcher t5} time:138101
09-11 11:56:30.630  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-11 11:56:30.630  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-11 11:56:30.630  1031  1564 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-11 11:56:30.633  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:30.639  2020  2136 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-11 11:56:30.639  2020  2136 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-11 11:56:30.643  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-11 11:56:30.644  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-11 11:56:30.645  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-11 11:56:30.645  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-11 11:56:30.647  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:30.650  8211  8211 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:30.650  8211  8211 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:30.650  8211  8211 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-11 11:56:30.654  2020  2020 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-11 11:56:30.655  2570  2570 D [Concierge]Service: onStartCommand(). Type : 8
09-11 11:56:30.655  2570  2570 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,09-11 11:56:30.655  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:30.655  2570  2570 D [Concierge]Service: Update widget ID : 11
09-11 11:56:30.658  2020  2020 D [Concierge]WidgetView: change position of spinner
09-11 11:56:30.659  2570  2570 D [Concierge]Service: onStartCommand(). Type : 0
,09-11 11:56:30.660  2020  2020 I [Concierge]WidgetView: initWebView(). Time : 1473587790660
09-11 11:56:30.665  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-11 11:56:30.669  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:30.673  8211  8211 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-11 11:56:30.674  8211  8211 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:30.677  8211  8211 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-11 11:56:30.678  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:30.686  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-11 11:56:30.688  2020  2020 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 585256882
09-11 11:56:30.689  2020  2020 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-11 11:56:30.689  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-11 11:56:30.690  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:30.691  2020  2020 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2a83a601
09-11 11:56:30.692  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,09-11 11:56:30.693  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-11 11:56:30.693  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-11 11:56:30.694  8211  8211 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:30.694  8211  8211 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:30.695  8211  8211 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-11 11:56:30.697  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:30.698  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-11 11:56:30.698  2020  2020 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-11 11:56:30.698  2020  2020 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-11 11:56:30.699  8131  8131 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-11 11:56:30.699  2020  2020 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473587679598, New one : 1473587790660
09-11 11:56:30.699  2020  2020 D [Concierge]WidgetView: Unregister all receivers
09-11 11:56:30.699  2020  2020 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-11 11:56:30.700  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-11 11:56:30.701  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:30.702  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-11 11:56:30.703  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-11 11:56:30.704  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-11 11:56:30.704  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-11 11:56:30.705  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-11 11:56:30.706  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,09-11 11:56:30.708  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:30.710  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-11 11:56:30.710  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-11 11:56:30.713  8211  8211 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:30.713  8211  8211 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:30.713  8211  8211 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-11 11:56:30.714  8211  8211 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-11 11:56:30.714  8211  8211 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-11 11:56:30.732  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-11 11:56:30.740  8131  8131 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-11 11:56:30.741  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-11 11:56:30.743  6888  6888 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-11 11:56:30.747  6888  6888 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-11 11:56:30.750  1031  1525 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-11 11:56:30.750  1031  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-11 11:56:30.750  1031  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-11 11:56:30.750  1031  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-11 11:56:30.751  1031  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-11 11:56:30.751  1031  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-11 11:56:30.751  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-11 11:56:30.751  1031  1531 D ConnectivityService: identical MTU - not setting
09-11 11:56:30.751  1031  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-11 11:56:30.751  1031  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-11 11:56:30.751  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:30.751  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:30.752  1031  1531 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-11 11:56:30.752  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-11 11:56:30.752  8211  8211 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-11 11:56:30.753  8211  8211 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-11 11:56:30.753  8211  8211 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-11 11:56:30.753  8211  8211 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-11 11:56:30.754  8211  8211 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-11 11:56:30.754  1031  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-11 11:56:30.758  1031  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-11 11:56:30.759  1031  1123 I art     : Explicit concurrent mark sweep GC freed 10699(592KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 11.950ms total 287.197ms
09-11 11:56:30.759  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-11 11:56:30.768  2020  2020 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-11 11:56:30.768  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,09-11 11:56:30.770  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-11 11:56:30.770  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:30.774  8211  8211 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-11 11:56:30.774  8211  8211 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-11 11:56:30.774  8211  8211 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-11 11:56:30.795  8211  8211 D LgDataFeature: LgDataFeature() Constructor: none
,09-11 11:56:30.795  8211  8211 D LgDataFeature: LgDataFeature() Constructor Done, null
09-11 11:56:30.797  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-11 11:56:30.799  2020  2020 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9bba80f time:138270
09-11 11:56:30.799  8211  8211 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-11 11:56:30.800  8211  8211 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-11 11:56:30.800  8211  8211 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
09-11 11:56:30.800  8211  8211 V SoundPool: doLoad: loading sample sampleID=1
09-11 11:56:30.801  8211  8211 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-11 11:56:30.803  8211  8330 V SoundPool: Start decode
09-11 11:56:30.803  8211  8330 V MediaPlayer[Native]: decode(32, 10857164, 17813)
09-11 11:56:30.803  8211  8211 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-11 11:56:30.803   311  1773 V MediaPlayerService: decode(22, 10857164, 17813)
09-11 11:56:30.803   311  1773 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-11 11:56:30.803   311  1773 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-11 11:56:30.803   311  1773 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-11 11:56:30.803   311  1773 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-11 11:56:30.803   311  1773 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-11 11:56:30.803   311  1773 V MediaPlayerService: player type = 3
09-11 11:56:30.803   311  1773 V AwesomePlayer: AwesomePlayer create()
09-11 11:56:30.803   311  1773 V AwesomePlayer: reset_l() 
09-11 11:56:30.803   311  1773 V AwesomePlayer: cancelPlayerEvents
09-11 11:56:30.803   311  1773 V AwesomePlayer: setAudioSink() 
09-11 11:56:30.803   311  1773 V AwesomePlayer: reset_l() 
09-11 11:56:30.803   311  1773 V AudioCache: notify(0xb5474980, 8, 0, 0)
09-11 11:56:30.803   311  1773 V AudioCache: ignored
09-11 11:56:30.803   311  1773 V AwesomePlayer: cancelPlayerEvents
09-11 11:56:30.803   311  1773 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-11 11:56:30.803   311  1773 V AwesomePlayer: setDataSource_l dataSource
09-11 11:56:30.804   311  1773 V LGParserOSAL: SniffLGParser start
09-11 11:56:30.804   311  1773 V LGParserOSAL: MainType:5, SubType=0
09-11 11:56:30.804   311  1773 V LGParserOSAL: #### check Mime : application/ogg
09-11 11:56:30.804   311  1773 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-11 11:56:30.804   311  1773 E MediaExtractor: Use LGExtractor :application/ogg 
09-11 11:56:30.808  7679  7679 D UEI.SmartControl: QS Service created
09-11 11:56:30.815  7679  7679 I UEI.SmartControl: Service initServices...
09-11 11:56:30.815  7679  7679 D UEI.SmartControl: QS start get config
,09-11 11:56:30.822  8211  8211 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-11 11:56:30.822  8211  8211 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-11 11:56:30.825   311  1773 V LGParserOSAL: supported mime: application/ogg
09-11 11:56:30.825   311  1773 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-11 11:56:30.825   311  1773 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-11 11:56:30.825   311  1773 V AwesomePlayer: mBitrate = -1 bits/sec
09-11 11:56:30.825   311  1773 V AwesomePlayer: AudioTrack Setting
09-11 11:56:30.825   311  1773 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-11 11:56:30.825   311  1773 V AwesomePlayer: setAudioSource() 
09-11 11:56:30.825   311  1773 V MediaPlayerService: prepare
09-11 11:56:30.825   311  1773 V AwesomePlayer: prepareAsync_l() 
09-11 11:56:30.825   311  1773 V MediaPlayerService: wait for prepare
09-11 11:56:30.825   311  8331 V AwesomePlayer: onPrepareAsyncEvent() 
09-11 11:56:30.825   311  8331 V AwesomePlayer: initAudioDecoder() 
09-11 11:56:30.825   311  8331 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-11 11:56:30.825   311  8331 V AudioSystem: isOffloadSupported()
09-11 11:56:30.825   311  8331 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-11 11:56:30.825   311  8331 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-11 11:56:30.825   311  8331 I AudioFlinger: isAudioPlaybackHookOn() false
09-11 11:56:30.825   311  8331 V AwesomePlayer: getUseOffload() = 0 
09-11 11:56:30.825   311  8331 V OMXCodec: OMXCodec::Create
09-11 11:56:30.826   311  8331 V OMXCodec: findMatchingCodecs()
09-11 11:56:30.826   311  8331 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-11 11:56:30.826   311  8331 V OMXCodec: matchingCodecs.size()=1
09-11 11:56:30.826   311  8331 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-11 11:56:30.826   311  8331 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-11 11:56:30.826   311  8331 V LGCodecAdapter: LG Codec Adapter start
09-11 11:56:30.827   311  8331 V OMXCodec: OMXCodec Createtor
09-11 11:56:30.827   311  8331 V OMXCodec: setComponentRole
09-11 11:56:30.827   311  8331 V OMXCodec: configureCodec protected=0
09-11 11:56:30.827   311  8331 V LGCodecAdapter: called getLGCodecSpecificData
09-11 11:56:30.827   311  8331 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-11 11:56:30.827   311  8331 V LGCodecOSAL: Called LGconfigureCodecMETA
09-11 11:56:30.827   311  8331 V LGCodecOSAL: Called LGconfigureCodecMSG
09-11 11:56:30.827   311  8331 V LGCodecOSAL: Not support LGCodec
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-11 11:56:30.827   311  8331 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-11 11:56:30.827   311  8331 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-11 11:56:30.827   311  8331 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-11 11:56:30.827   311  8331 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-11 11:56:30.827   311  8331 V AudioSystem: isOffloadSupported()
09-11 11:56:30.827   311  8331 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-11 11:56:30.827   311  8331 D AudioPolicyManager: isOffloadSupported: stream_typ,e != MUSIC, returning false
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-11 11:56:30.827   311  8331 V OMXCodec: init()
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-11 11:56:30.827   311  8331 V OMXCodec: allocateBuffers
09-11 11:56:30.827   311  8331 V OMXCodec: allocateBuffersOnPort portIndex=0
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on input port
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on input port
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
09-11 11:56:30.827   311  8331 V OMXCodec: allocateBuffersOnPort portIndex=1
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on output port
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0240 on output port
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c08d0 on output port
09-11 11:56:30.827   311  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0920 on output port
09-11 11:56:30.827   311  8331 V OMXCodec: init() mAsyncCompletion wait!!! 
09-11 11:56:30.827   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-11 11:56:30.827   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-11 11:56:30.827   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-11 11:56:30.827   311  8331 V OMXCodec: init() mAsyncCompletion wait!!! 
09-11 11:56:30.827   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-11 11:56:30.827   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-11 11:56:30.827   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-11 11:56:30.827   311  8331 V OMXCodec: init() mAsyncCompletion wait free! 
09-11 11:56:30.827   311  8331 V AwesomePlayer: finishAsyncPrepare_l() 
09-11 11:56:30.827   311  8331 V AudioCache: notify(0xb5474980, 5, 0, 0)
09-11 11:56:30.827   311  8331 V AudioCache: ignored
09-11 11:56:30.827   311  8331 V AudioCache: notify(0xb5474980, 1, 0, 0)
09-11 11:56:30.827   311  8331 V AudioCache: prepared
09-11 11:56:30.827   311  1773 V AudioCache: wait - success
09-11 11:56:30.827   311  1773 V MediaPlayerService: start
09-11 11:56:30.827   311  1773 V AwesomePlayer: play_l() 
09-11 11:56:30.828   311  1773 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-11 11:56:30.828   311  1773 V AwesomePlayer: createAudioPlayer_l
09-11 11:56:30.828   311  1773 V AwesomePlayer: seekAudioIfNecessary_l() 
09-11 11:56:30.828   311  1773 V AwesomePlayer: startAudioPlayer_l() 
09-11 11:56:30.828   311  1773 D AudioPlayer: start of Playback, useOffload 0
09-11 11:56:30.828   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-11 11:56:30.828   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-11 11:56:30.828  8211  8211 V LGMDMManager: Create singleton instance
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-11 11:56:30.829   311  8333 V OMXCode,c: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975584
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974548544
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974550224
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974550304
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-11 11:56:30.829   311  8333 V OMXCodec: allocateBuffersOnPort portIndex=1
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c08d0 on output port
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0240 on output port
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on output port
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-11 11:56:30.829   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-11 11:56:30.830   311  1773 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-11 11:56:30.830   311  1773 V AudioCache: notify(0xb5474980, 6, 0, 0)
09-11 11:56:30.830   311  1773 V AudioCache: ignored
09-11 11:56:30.830   311  1773 V MediaPlayerService: wait for playback complete
09-11 11:56:30.830   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.830   311  8334 V AudioCache: memcpy(0xac004000, 0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: memcpy(0xac005000, 0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: memcpy(0xac006000, 0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: memcpy(0xac007000, 0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: memcpy(0xac008000, 0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: memcpy(0xac009000, 0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: memcpy(0xac00a000, 0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.831   311  8334 V AudioCache: memcpy(0xac00b000, 0xb54f5000, 4096)
09-11 11:56:30.832   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.832   311  8334 V AudioCache: memcpy(0xac00c000, 0xb54f5000, 4096)
09-11 11:56:30.832   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.832   311  8334 V AudioCache: memcpy(0xac00d000, 0xb54f5000, 4096)
09-11 11:56:30.832   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.832   311  8334 V AudioCache: memcpy(0xac00e000, 0xb54f5000, 4096)
09-11 11:56:30.832   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.832   311  8334 V AudioCache: memcpy(0xac00f000, 0xb54f5000, 4096)
09-11 11:56:30.833   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.833   311  8334 V AudioCache: memcpy(0xac010000, 0xb54f5000, 4096)
09-11 11:56:30.834   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.834   311  8334 V AudioCache: memcpy(0xac011000, 0xb54f5000, 4096)
09-11 11:56:30.835   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.835   311  8334 V AudioCache: memcpy(0xac012000, 0xb54f5000, 4096)
09-11 11:56:30.836   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.836   311  8334 V AudioCache: memcpy(0xac013000, 0xb54f5000, 4096)
09-11 11:56:30.836   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.836   311  8334 V AudioCache: memcpy(0xac014000, 0xb54f5000, 4096)
09-11 11:56:30.836   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.837   311  8334 V AudioCache: memcpy(0xac015000, 0xb54f5000, 4096)
09-11 11:56:30.837   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.837   311  8334 V AudioCache: memcpy(0xac016000, 0xb54f5000, 4096)
09-11 11:56:30.837   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.837   311  8334 V AudioCache: memcpy(0xac017000, 0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: memcpy(0xac018000, 0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: memcpy(0xac019000, 0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: memcpy(0xac01a000, 0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: memcpy(0xac01b000, 0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: memcpy(0xac01c000, 0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.838   311  8334 V AudioCache: memcpy(0xac01d000, 0xb54f5000, 4096)
09-11 11:56:30.839   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.839   311  8334 V AudioCache: memcpy(0xac01e000, 0xb54f5000, 4096)
09-11 11:56:30.839   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.839   311  8334 V AudioCache: memcpy(0xac01f000, 0xb54f5000, 4096)
09-11 11:56:30.839   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.839   311  8334 V AudioCache: memcpy(0xac020000, 0xb54f5000, 4096)
09-11 11:56:30.840   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.840   311  8334 V AudioCache: memcpy(0xac021000, 0xb54f5000, 4096)
09-11 11:56:30.840   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.840   311  8334 V AudioCache: memcpy(0xac022000, 0xb54f5000, 4096)
09-11 11:56:30.840   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.840   311  8334 V AudioCache: memcpy(0xac023000, 0xb54f5000, 4096)
09-11 11:56:30.841   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.841   311  8334 V AudioCache: memcpy(0xac024000, 0xb54f5000, 4096)
09-11 11:56:30.841   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.841   311  8334 V AudioCache: memcpy(0xac025000, 0xb54f5000, 4096)
09-11 11:56:30.841   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.841   311  8334 V AudioCache: memcpy(0xac026000, 0xb54f5000, 4096)
09-11 11:56:30.841   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.841   311  8334 V AudioCache: memcpy(0xac027000, 0xb54f5000, 4096)
09-11 11:56:30.842   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.842   311  8334 V AudioCache: memcpy(0xac028000, 0xb54f5000, 4096)
09-11 11:56:30.842   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.842   311  8334 V AudioCache: memcpy(0xac029000, 0xb54f5000, 4096)
09-11 11:56:30.842   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.842   311  8334 V AudioCache: memcpy(0xac02a000, 0xb54f5000, 4096)
09-11 11:56:30.843   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.843   311  8334 V AudioCache: memcpy(0xac02b000, 0xb54f5000, 4096)
09-11 11:56:30.843   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.843   311  8334 V AudioCache: memcpy(0xac02c000, 0xb54f5000, 4096)
09-11 11:56:30.843   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.843   311  8334 V AudioCache: memcpy(0xac02d000, 0xb54f5000, 4096)
09-11 11:56:30.844   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.844   311  8334 V AudioCache: memcpy(0xac02e000, 0xb54f5000, 4096)
09-11 11:56:30.844   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.844   311  8334 V AudioCache: memcpy(0xac02f000, 0xb54f5000, 4096)
09-11 11:56:30.844   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.844   311  8334 V AudioCache: memcpy(0xac030000, 0xb54f5000, 4096)
09-11 11:56:30.845   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.845   311  8334 V AudioCache: memcpy(0xac031000, 0xb54f5000, 4096)
,09-11 11:56:30.845   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.845   311  8334 V AudioCache: memcpy(0xac032000, 0xb54f5000, 4096)
09-11 11:56:30.847   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.847   311  8334 V AudioCache: memcpy(0xac033000, 0xb54f5000, 4096)
09-11 11:56:30.847   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.847   311  8334 V AudioCache: memcpy(0xac034000, 0xb54f5000, 4096)
09-11 11:56:30.847   311  8334 V AudioCache: write(0xb54f5000, 4096)
09-11 11:56:30.847   311  8334 V AudioCache: memcpy(0xac035000, 0xb54f5000, 4096)
09-11 11:56:30.848   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-11 11:56:30.848   311  8334 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-11 11:56:30.848   311  8334 V AwesomePlayer: postAudioEOS() 
09-11 11:56:30.848   311  8334 V AudioCache: write(0xb54f5000, 280)
09-11 11:56:30.848   311  8334 V AudioCache: memcpy(0xac036000, 0xb54f5000, 280)
09-11 11:56:30.851   311  8331 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-11 11:56:30.851   311  8331 V AwesomePlayer: onStreamDone
09-11 11:56:30.851   311  8331 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-11 11:56:30.851   311  8331 V AudioCache: notify(0xb5474980, 2, 0, 0)
09-11 11:56:30.851   311  8331 V AudioCache: playback complete
09-11 11:56:30.851   311  8331 V AwesomePlayer: pause_l() 
09-11 11:56:30.851   311  8331 V AudioCache: notify(0xb5474980, 7, 0, 0)
09-11 11:56:30.851   311  8331 V AudioCache: ignored
09-11 11:56:30.851   311  8331 V AwesomePlayer: cancelPlayerEvents
09-11 11:56:30.851   311  8331 D AudioPlayer: Pause Playback at 1068125
09-11 11:56:30.851   311  1773 V AudioCache: wait - success
09-11 11:56:30.851   311  1773 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-11 11:56:30.853   311  1773 V AwesomePlayer: reset_l() 
09-11 11:56:30.853   311  1773 V AudioCache: notify(0xb5474980, 8, 0, 0)
09-11 11:56:30.853   311  1773 V AudioCache: ignored
09-11 11:56:30.853   311  1773 V AwesomePlayer: cancelPlayerEvents
09-11 11:56:30.853   311  1773 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-11 11:56:30.853   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-11 11:56:30.853   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-11 11:56:30.853   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-11 11:56:30.853   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-11 11:56:30.853  8257  8257 D AndroidRuntime: Shutting down VM
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 0
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 0
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-11 11:56:30.853   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 1
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0240 on port 1
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c08d0 on port 1
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-11 11:56:30.854   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-11 11:56:30.854   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-11 11:56:30.854   311  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-11 11:56:30.854   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-11 11:56:30.854   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-11 11:56:30.854   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-11 11:56:30.855   311  1773 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-11 11:56:30.855   311  1773 D AudioPlayer: AudioPlayer releasing audio source
09-11 11:56:30.855   311  1773 D AudioPlayer: AudioPlayer done releasing audio source
09-11 11:56:30.855   311  1773 V AwesomePlayer: reset_l() 
09-11 11:56:30.855   311  1773 V AwesomePlayer: cancelPlayerEvents
09-11 11:56:30.855   311  1773 V AwesomePlayer: ~AwesomePlayer call
09-11 11:56:30.855   311  1773 V AwesomePlayer: reset_l() 
09-11 11:56:30.855   311  1773 V AwesomePlayer: cancelPlayerEvents
09-11 11:56:30.855  8211  8330 V SoundPool: close(32)
09-11 11:56:30.855  8211  8330 V SoundPool: pointer = 0xa0004000, size = 205080, sampleRate = 48000, numChannels = 2
09-11 11:56:30.884  8211  8211 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-11 11:56:30.887  8211  8211 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-11 11:56:30.887  1031  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8335 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-11 11:56:30.889  8211  8211 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5521
09-11 11:56:30.901  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-11 11:56:30.902  8158  8158 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-11 11:56:30.905  1804  1804 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,09-11 11:56:30.909  2167  2167 I ConfigService: onCreate
09-11 11:56:30.910  2167  2167 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-11 11:56:30.912  1804  1804 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-11 11:56:30.913  2167  2167 I ConfigService: onBind returning update interface
09-11 11:56:30.914  2167  2167 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-11 11:56:30.914  2167  2167 I ConfigService: onBind returning config service
09-11 11:56:30.915  2020  2020 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-11 11:56:30.936  2167  2167 I ConfigService: onDestroy
,09-11 11:56:30.939  1804  8354 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-11 11:56:30.962  5843  8360 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-11 11:56:30.963  2020  2878 I GBoardtInterface: onReloaded()
09-11 11:56:30.966  1804  5141 I Icing   : doRemovePackageData com.test.thalitest
09-11 11:56:30.967  1804  8361 I PeopleContactsSync: CP2 sync disabled
09-11 11:56:30.967  2020  2020 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-11 11:56:30.968  3801  4945 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-11 11:56:30.971  3801  3817 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-11 11:56:30.975  7091  7091 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-11 11:56:30.981  1892  1892 D ActionManagerService: notifyUserLog: 1000001
09-11 11:56:30.982  3801  4952 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-11 11:56:30.982  3801  4952 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-11 11:56:30.986  1892  1892 D ActionManagerService: notifyUserLog: 1000001
,09-11 11:56:30.988  3801  3817 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-11 11:56:30.990  2337  8362 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-11 11:56:31.015  1031  1760 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8365 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-11 11:56:31.017  3801  4952 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-11 11:56:31.017  3801  4952 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-11 11:56:31.017  3801  4952 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-11 11:56:31.017  3801  4952 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-11 11:56:31.019  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-11 11:56:31.019  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-11 11:56:31.021  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-11 11:56:31.021  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-11 11:56:31.023  1804  8359 W GmsApplication: Using Auth Proxy for data requests.
09-11 11:56:31.024  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-11 11:56:31.024  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-11 11:56:31.030  1804  8359 W GmsApplication: Using Auth Proxy for data requests.
,09-11 11:56:31.043  2167  4686 I art     : Explicit concurrent mark sweep GC freed 6594(376KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 671us total 16.724ms
,09-11 11:56:31.086  8365  8365 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-11 11:56:31.086  8365  8365 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-11 11:56:31.087  8365  8365 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-11 11:56:31.087  8365  8365 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-11 11:56:31.176  8365  8365 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-11 11:56:31.184  8365  8365 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-11 11:56:31.184  7679  7679 E UEI.SmartControl: unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac2: open failed: EROFS (Read-only file system)
09-11 11:56:31.185  7679  7679 I UEI.SmartControl: Specific region DB is not found, use default...
09-11 11:56:31.203  7679  7679 E UEI.SmartControl: unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac1a: open failed: EROFS (Read-only file system)
,09-11 11:56:31.203  7679  7679 I UEI.SmartControl: Supports setup maps: true
09-11 11:56:31.204  7679  7679 W System.err: java.lang.NullPointerException: Attempt to get length of null array
09-11 11:56:31.204  7679  7679 W System.err: 	at com.uei.control.core.ab.b(Unknown Source)
09-11 11:56:31.204  7679  7679 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
09-11 11:56:31.204  7679  7679 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
09-11 11:56:31.204  7679  7679 W System.err: 	at com.uei.control.Service.a(Unknown Source)
09-11 11:56:31.204  7679  7679 W System.err: 	at com.uei.control.Service.onCreate(Unknown Source)
09-11 11:56:31.204  7679  7679 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-11 11:56:31.204  7679  7679 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-11 11:56:31.204  7679  7679 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-11 11:56:31.204  7679  7679 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:31.204  7679  7679 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:31.204  7679  7679 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:31.204  7679  7679 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:31.204  7679  7679 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:31.204  7679  7679 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:31.204  7679  7679 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
09-11 1,1:56:31.204  7679  7679 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:31.204  7679  7679 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:31.205  7679  7679 I UEI.SmartControl: ### init IR Blaster...
09-11 11:56:31.208  7679  7679 D serial_port: Configuring serial port
09-11 11:56:31.208  7679  7679 E UEI.SmartControl: UEIBLaster setting for 616
09-11 11:56:31.208  7679  7679 I UEI.SmartControl: Setting serial record hearder size = 2
09-11 11:56:31.208  7679  7679 I UEI.SmartControl: configuring settings for MAXQ616
09-11 11:56:31.208  7679  7679 I UEI.SmartControl: Get version...
09-11 11:56:31.211  8365  8365 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-11 11:56:31.224  7679  8386 D UEI.SmartControl: serial port data available: 21
,09-11 11:56:31.229  8365  8365 D LgDataFeature: LgDataFeature() Constructor: none
09-11 11:56:31.229  8365  8365 D LgDataFeature: LgDataFeature() Constructor Done, null
09-11 11:56:31.250  7679  7679 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-11 11:56:31.250  7679  7679 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-11 11:56:31.250  7679  7679 I UEI.SmartControl: QS saving settings...
,09-11 11:56:31.253  7679  7679 W FileUtils: Failed to chmod(/data/data/com.uei.lg.quicksetsdk.maxq616/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-11 11:56:31.253  7679  7679 W System.err: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
09-11 11:56:31.253  7679  7679 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-11 11:56:31.253  7679  7679 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-11 11:56:31.253  7679  7679 W System.err: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
09-11 11:56:31.253  7679  7679 W System.err: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
09-11 11:56:31.253  7679  7679 W System.err: 	at com.uei.control.core.QSApp.m(Unknown Source)
09-11 11:56:31.253  7679  7679 W System.err: 	at com.uei.control.core.QSApp.b(Unknown Source)
09-11 11:56:31.253  7679  7679 W System.err: 	at com.uei.control.core.a.a(Unknown Source)
09-11 11:56:31.253  7679  7679 W System.err: 	at com.uei.control.core.a.<init>(Unknown Source)
09-11 11:56:31.253  7679  7679 W System.err: 	at com.uei.control.Service.a(Unknown Source)
09-11 11:56:31.254  7679  7679 W System.err: 	at com.uei.control.Service.onCreate(Unknown Source)
09-11 11:56:31.254  7679  7679 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-11 11:56:31.254  7679  7679 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-11 11:56:31.254  7679  7679 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-11 11:56:31.254  7679  7679 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:31.254  7679  7679 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:31.254  7679  7679 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:31.254  7679  7679 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:31.254  7679  7679 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:31.254  7679  7679 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:31.254  7679  7679 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:31.254  7679  7679 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-11 11:56:31.254  7679  7679 W System.err: 	at libcore.io.Posix.open(Native Method)
09-11 11:56:31.254  7679  7679 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-11 11:56:31.254  7679  7679 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-11 11:56:31.254  7679  7679 W System.err: 	... 19 more
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.QSApp.m(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.QSApp.b(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.a.a(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.a.<init>(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService,(ActivityThread.java:2738)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	... 19 more
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.QSApp.m(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.QSApp.b(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.a.a(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.core.a.<init>(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: Caused by: android.system.ErrnoExce,ption: open failed: EROFS (Read-only file system)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-11 11:56:31.255  7679  7679 E UEI.SmartControl: 	... 19 more
09-11 11:56:31.255  7679  7679 D UEI.SmartControl: IR Blaster version: 25672567

```
