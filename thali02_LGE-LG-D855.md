#### Test 830701771a7aee8_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-08 18:23:33.662  6568  6568 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-08 18:23:33.666  6568  6568 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{34a77e90 com.google.android.apps.docs}
09-08 18:23:33.684  6568  6568 D TAG     : onCreate()
09-08 18:23:33.705  6568  6568 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,09-08 18:23:34.045  6594  6594 D AndroidRuntime: 
09-08 18:23:34.045  6594  6594 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-08 18:23:34.049  6594  6594 D AndroidRuntime: CheckJNI is OFF
09-08 18:23:34.246  6594  6594 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 18:23:34.252  1036  1941 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 18:23:34.260  1942  3901 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-08 18:23:34.262  1036  1941 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-08 18:23:34.263  1036  1941 D ActivityManager: setTaskToReturnTo : TaskRecord{1d64e4e3 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-08 18:23:34.263  1036  1941 D ActivityManager: setTaskToReturnTo : TaskRecord{1d64e4e3 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-08 18:23:34.264  1036  1941 D WindowStateEx: AppWindowTokenEx init.. 
09-08 18:23:34.265   331   341 E GBMv2   : DFP En is all cleared set to be enabled
09-08 18:23:34.299  1036  1941 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6609 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-08 18:23:34.302  6594  6594 D AndroidRuntime: Shutting down VM
09-08 18:23:34.354  1942  3901 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-08 18:23:34.354  1942  3901 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3734810c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-08 18:23:34.355  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-08 18:23:34.355  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1bf4ca55 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-08 18:23:34.419  6609  6609 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-08 18:23:34.483  1818  4775 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-08 18:23:34.511  6609  6609 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-08 18:23:34.519  6609  6609 I LibraryLoader: Loading: webviewchromium
09-08 18:23:34.521  6609  6609 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 306-309)
09-08 18:23:34.522  6609  6609 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 18:23:34.536  6609  6609 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {18cc269a}
09-08 18:23:34.537  6609  6609 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 18:23:34.537  6609  6609 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 18:23:34.545  6609  6609 I BrowserStartupController: Initializing chromium process, renderers=0
,09-08 18:23:34.546  6609  6609 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 18:23:34.561  6609  6609 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-08 18:23:34.562   315   315 V AudioPolicyService: registerClient() client 0xb04105e0, uid 10118
09-08 18:23:34.562  6609  6609 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-08 18:23:34.562  6609  6609 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-08 18:23:34.565  1036  1118 D BluetoothManagerService: Message: 20
09-08 18:23:34.565  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f1ee255:true
09-08 18:23:34.572  1818  4775 I art     : Explicit concurrent mark sweep GC freed 24624(1606KB) AllocSpace objects, 16(256KB) LOS objects, 51% free, 29MB/61MB, paused 1.342ms total 70.772ms
09-08 18:23:34.577  6609  6609 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 18:23:34.577  6609  6609 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 18:23:34.577  6609  6609 I Adreno-EGL: Build Date: 12/12/14 금
09-08 18:23:34.577  6609  6609 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 18:23:34.577  6609  6609 I Adreno-EGL: Remote Branch: 
09-08 18:23:34.577  6609  6609 I Adreno-EGL: Local Patches: 
09-08 18:23:34.577  6609  6609 I Adreno-EGL: Reconstruct Branch: 
,09-08 18:23:34.578  1818  4775 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-08 18:23:34.610  1818  4775 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,09-08 18:23:34.672  6609  6649 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-08 18:23:34.679  6609  6609 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-08 18:23:34.704  6609  6609 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 18:23:34.709  6609  6609 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-08 18:23:34.713  6609  6609 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,09-08 18:23:34.716  6609  6609 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-08 18:23:34.716  6609  6609 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-08 18:23:34.732  6609  6609 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-08 18:23:34.739  6609  6609 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 18:23:34.739  6609  6609 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 18:23:34.747   306   306 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
09-08 18:23:34.747   306   306 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
09-08 18:23:34.747   306   306 I rmt_storage: wakelock acquired: 1, error no: 42
09-08 18:23:34.747   306   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,09-08 18:23:34.778  6609  6662 D OpenGLRenderer: Render dirty regions requested: true
09-08 18:23:34.778  6609  6662 I OpenGLRenderer: Initialized EGL, version 1.4
09-08 18:23:34.784  6609  6662 D OpenGLRenderer: Enabling debug mode 0
09-08 18:23:34.794  6609  6609 D Atlas   : Validating map...
,09-08 18:23:34.799  1036  2052 D SplitWindow: check instance of lgWin Window{33ca77d4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 18:23:34.809   306   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
09-08 18:23:34.809   306   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,09-08 18:23:34.809   306   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
09-08 18:23:34.809   306   914 I rmt_storage: 
09-08 18:23:34.811   306   306 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
09-08 18:23:34.811   901   912 E Diag_Lib: [IMS_FATAL]| 3347 | 912 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
09-08 18:23:34.850  6609  6660 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:23:34.850  6609  6660 D LgDataFeature: LgDataFeature() Constructor Done, null
09-08 18:23:34.851  6568  6568 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 18:23:34.851  6568  6568 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:23:34.958  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +605ms (total +692ms)
,09-08 18:23:34.958  6609  6609 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2486a631 time:100746
,09-08 18:23:34.962  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c44cee0 u0 com.test.thalitest/.MainActivity t6} time:100750,
09-08 18:23:34.981  6114  6114 I LockScreenSettings: New app installed broadcast received ..
,09-08 18:23:34.985  6114  6114 I LockScreenSettings: Number of installed packages  1
09-08 18:23:34.996  6568  6568 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-08 18:23:35.032  1036  1905 V SIM_STK : Menu title from STK is T-Mobile
,09-08 18:23:35.059  1036  1699 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6684 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-08 18:23:35.073  6609  6609 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-08 18:23:35.073  6609  6609 I chromium: 
,09-08 18:23:35.103  6609  6609 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 18:23:35.105  6684  6684 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-08 18:23:35.105  6684  6684 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
09-08 18:23:35.143  1036  1905 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6701 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-08 18:23:35.144  1036  1905 I ActivityManager: Killing 5803:com.google.android.gm/u0a64 (adj 15): empty #17
,09-08 18:23:35.212  6609  6718 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,09-08 18:23:35.222  1036  1986 W libprocessgroup: failed to open /acct/uid_10064/pid_5803/cgroup.procs: No such file or directory
,09-08 18:23:35.227  6609  6718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 18:23:35.227  6609  6718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 18:23:35.227  6609  6718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 18:23:35.227  6609  6718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 18:23:35.227  6609  6718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-08 18:23:35.227  6609  6718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5ec425 added. We now have 1 listener(s)
09-08 18:23:35.232  1036  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:23:35.235  6609  6718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-08 18:23:35.237  6609  6718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 18:23:35.238  6609  6718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:23:35.238  6609  6718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 18:23:35.245  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 18:23:35.246  6609  6718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a210208 added. We now have 1 listener(s)
09-08 18:23:35.246  6609  6718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:23:35.253  1036  1474 D WifiService: New client listening to asynchronous messages
,09-08 18:23:35.260  6609  6718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:23:35.260  6609  6718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 18:23:35.260  6609  6718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 18:23:35.261  6609  6718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 18:23:35.261  6609  6718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-08 18:23:35.265  6609  6718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:35.265  1036  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:23:35.267  6609  6718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-08 18:23:35.275  6609  6718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-08 18:23:35.275  6609  6718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:35.275  6609  6718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:35.275  6609  6718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:35.275  6609  6718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:35.275  6609  6718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:35.275  6609  6718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:35.275  6609  6718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:35.275  6609  6718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:35.275  6609  6718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 18:23:35.275  6609  6718 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:35.278  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:35.278  6609  6718 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 18:23:35.280  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:35.329  6609  6660 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-08 18:23:35.329  6609  6660 I chromium: 
09-08 18:23:35.329  6701  6701 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,09-08 18:23:35.351  6701  6701 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-08 18:23:35.356  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-08 18:23:35.379  6609  6609 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 18:23:35.389  1036  1052 I ActivityManager: Killing 5647:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-08 18:23:35.407  5612  5612 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,09-08 18:23:35.408  5612  5612 W System.err: android.os.DeadObjectException
09-08 18:23:35.409  5612  5612 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 18:23:35.409  5612  5612 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 18:23:35.409  5612  5612 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-08 18:23:35.409  5612  5612 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-08 18:23:35.409  5612  5612 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 18:23:35.410  5612  5612 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 18:23:35.410  5612  5612 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 18:23:35.410  5612  5612 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 18:23:35.410  5612  5612 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 18:23:35.410  5612  5612 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 18:23:35.410  5612  5612 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:35.410  5612  5612 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:35.410  5612  5612 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 18:23:35.411  5612  5612 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 18:23:35.411  5612  5612 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-08 18:23:35.412  5612  5612 W System.err: android.os.DeadObjectException
09-08 18:23:35.412  5612  5612 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 18:23:35.412  5612  5612 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 18:23:35.412  5612  5612 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-08 18:23:35.413  5612  5612 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-08 18:23:35.413  5612  5612 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 18:23:35.413  5612  5612 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 18:23:35.413  5612  5612 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 18:23:35.413  5612  5612 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 18:23:35.414  5612  5612 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 18:23:35.414  5612  5612 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 18:23:35.414  5612  5612 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:35.414  5612  5612 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:35.414  5612  5612 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 18:23:35.414  5612  5612 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 18:23:35.414  5612  5612 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-08 18:23:35.415  5612  5612 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-08 18:23:35.624  1036  2052 W libprocessgroup: failed to open /acct/uid_1000/pid_5647/cgroup.procs: No such file or directory
09-08 18:23:35.625  1036  2052 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-08 18:23:35.633  5612  5612 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-08 18:23:35.634  5612  5612 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-08 18:23:35.710  1036  1887 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6733 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 18:23:35.711  5612  5612 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-08 18:23:35.841  6733  6733 D UEI.SmartControl: Quickset Services start...
,09-08 18:23:35.844  6733  6733 I UEI.SmartControl: Manufacture = LGE
09-08 18:23:35.844  6733  6733 D UEI.SmartControl: Id = LGNevo
09-08 18:23:35.846  6733  6733 D UEI.SmartControl: File observer start...
09-08 18:23:35.847  6733  6733 E UEI.SmartControl: IR Port is disabled: false
09-08 18:23:35.847  6733  6733 D UEI.SmartControl: Starting file observer...
09-08 18:23:35.849  6733  6733 D UEI.SmartControl: Extracting JNI libs...
09-08 18:23:35.849  6733  6733 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-08 18:23:35.952  6733  6733 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-08 18:23:35.953  6733  6733 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-08 18:23:35.953  6733  6733 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-08 18:23:35.959   331   345 E GBMv2   : DFP En is all cleared set to be enabled
09-08 18:23:35.959   331   345 E GBMv2   : Set value is all cleared set the max
09-08 18:23:35.959   331   345 I GBMv2   : DFP Enabled. Ignore VFP set
09-08 18:23:35.982  6733  6733 I UEI.SmartControl: --- Selecting new region: 6
,09-08 18:23:35.984  6733  6733 I UEI.SmartControl: Model = LG-D855
09-08 18:23:35.985  6733  6733 D UEI.SmartControl: QS Service created
09-08 18:23:36.012  6733  6733 I UEI.SmartControl: Service initServices...
,09-08 18:23:36.016  6733  6733 D UEI.SmartControl: QS start get config
09-08 18:23:36.042  6733  6733 D UEI.SmartControl: Loading JNI Libs...
,09-08 18:23:36.368  6609  6721 W jxcore-log: Initializing JXcore engine
09-08 18:23:36.368  6609  6721 W jxcore-log: JXcore engine is ready
09-08 18:23:36.382  6733  6733 I UEI.SmartControl: Supports setup maps: true
09-08 18:23:36.386  6733  6733 D UEI.SmartControl: QS start statue = true Error code = 0
09-08 18:23:36.386  6733  6733 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-08 18:23:36.386  6733  6733 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-08 18:23:36.386  6733  6733 I UEI.SmartControl: ### init IR Blaster...
09-08 18:23:36.391  6733  6733 D serial_port: Configuring serial port
09-08 18:23:36.395  6733  6733 E UEI.SmartControl: UEIBLaster setting for 616
09-08 18:23:36.395  6733  6733 I UEI.SmartControl: Setting serial record hearder size = 2
09-08 18:23:36.395  6733  6733 I UEI.SmartControl: configuring settings for MAXQ616
09-08 18:23:36.395  6733  6733 I UEI.SmartControl: Get version...
09-08 18:23:36.412  6733  6755 D UEI.SmartControl: serial port data available: 21
09-08 18:23:36.440  6733  6733 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-08 18:23:36.441  6733  6733 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-08 18:23:36.441  6733  6733 I UEI.SmartControl: QS saving settings...
09-08 18:23:36.444  6733  6733 D UEI.SmartControl: IR Blaster version: 25672567
09-08 18:23:36.432  6721  6721 W Thread-761: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8276]" dev="sockfs" ino=8276 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-08 18:23:36.432  6721  6721 W Thread-761: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-08 18:23:36.432  6721  6721 W Thread-761: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10458]" dev="sockfs" ino=10458 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-08 18:23:36.432  6721  6721 W Thread-761: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-08 18:23:36.432  6721  6721 W Thread-761: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30571]" dev="sockfs" ino=30571 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-08 18:23:36.464  6733  6755 D UEI.SmartControl: serial port data available: 4
09-08 18:23:36.471  6609  6721 W jxcore-log: Starting JXcore engine
09-08 18:23:36.505  6733  6758 I UEI.SmartControl: Device manager: loading config....
09-08 18:23:36.507  6733  6758 D UEI.SmartControl: ----------- loading internal config...
09-08 18:23:36.509  6733  6733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-08 18:23:36.513  6733  6733 E UEI.SmartControl: Services init done
09-08 18:23:36.513  6733  6733 D UEI.SmartControl: QS Service init finished
09-08 18:23:36.517  6733  6733 D UEI.SmartControl: QS Service version name: 2.1.91
09-08 18:23:36.518  6733  6733 D UEI.SmartControl: QS Service version code: 201091
09-08 18:23:36.519  6733  6733 D UEI.SmartControl: Service requested: Control
09-08 18:23:36.529  6733  6758 E UEI.SmartControl: Loading SETTINGS...
09-08 18:23:36.531  6733  6733 D UEI.SmartControl: Request IControl service: devices are loaded...
09-08 18:23:36.536  5612  5612 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-08 18:23:36.537  6733  6748 I UEI.SmartControl: ------ IControl API: 11
09-08 18:23:36.537  1036  1941 I ActivityManager: Killing 5612:com.lge.qremote/u0a112 (adj 15): empty #17
09-08 18:23:36.539  6733  6748 I UEI.SmartControl: Registering callback...
09-08 18:23:36.556  6733  6758 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-08 18:23:36.563  6733  6757 I UEI.SmartControl: Notify AllClients services are ready: 0
09-08 18:23:36.564  6733  6757 D UEI.SmartControl: -----service ready thread exits
09-08 18:23:36.640  6609  6721 W jxcore-log: Platform android
09-08 18:23:36.640  6609  6721 W jxcore-log: 
09-08 18:23:36.641  6609  6721 W jxcore-log: Process ARCH arm
09-08 18:23:36.641  6609  6721 W jxcore-log: 
09-08 18:23:36.713  6733  6733 D UEI.SmartControl: Internal service binding...
09-08 18:23:36.713  1036  1986 W libprocessgroup: failed to open /acct/uid_10112/pid_5612/cgroup.procs: No such file or directory
09-08 18:23:36.995  6609  6721 I jxcore-log: JXcore Cordova bridge is ready!
09-08 18:23:36.995  6609  6721 I jxcore-log: 
09-08 18:23:36.997  6609  6721 W jxcore-log: JXcore engine is started
,09-08 18:23:37.004  6609  6718 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-08 18:23:37.007  6609  6609 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-08 18:23:39.054  6568  6568 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-08 18:23:39.098  1036  1940 I ActivityManager: Killing 5845:com.google.android.talk/u0a72 (adj 15): empty #17
,09-08 18:23:39.177  1036  1986 W libprocessgroup: failed to open /acct/uid_10072/pid_5845/cgroup.procs: No such file or directory
,09-08 18:23:39.912  6568  6667 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-08 18:23:41.460  2801  2801 I MusicWidget: mDelayedStopHandler : unbind
,09-08 18:23:41.464  2213  2213 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-08 18:23:41.465  2213  2213 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-08 18:23:41.465  2213  2213 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-08 18:23:41.469  2213  2213 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-08 18:23:41.469  2213  2213 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-08 18:23:41.470  2213  2213 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-08 18:23:41.473  2213  2213 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-08 18:23:41.474  2213  2213 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,09-08 18:23:41.479  1036  1699 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@19bafdbbcom.lge.music.MediaPlaybackService$5@278f32d8
09-08 18:23:41.480  2213  2213 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-08 18:23:41.481  2213  2213 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 18:23:41.482  2213  2213 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 18:23:41.483  2213  2213 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 18:23:41.484  2213  2213 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@16b61266
09-08 18:23:41.484  2213  2213 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 18:23:41.484  2213  2213 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-08 18:23:41.485  2213  2213 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 18:23:41.485  2213  2213 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-08 18:23:41.485  2213  2213 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-08 18:23:41.486  2213  2213 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 18:23:41.486  2213  2213 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 18:23:41.487  2213  2213 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 18:23:41.487  2213  2213 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 18:23:41.488  2213  2213 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 18:23:41.489  2213  2213 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-08 18:23:41.491  2213  2213 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-08 18:23:41.491  2213  2213 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-08 18:23:41.491  2213  2213 V MediaPlayer[Native]: reset
,09-08 18:23:41.499  2213  2213 V MediaPlayer[Native]: setListener
09-08 18:23:41.499  2213  2213 V MediaPlayer[Native]: disconnect
09-08 18:23:41.499  2213  2213 V MediaPlayer[Native]: destructor
09-08 18:23:41.499   315   315 V AudioFlinger: releasing 16 from 2213 for -1
09-08 18:23:41.499   315   315 V AudioFlinger:  decremented refcount to 0
09-08 18:23:41.499   315   315 V AudioFlinger: purging stale effects
09-08 18:23:41.499  2213  2213 V MediaPlayer[Native]: disconnect
09-08 18:23:41.500  2213  2213 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-08 18:23:41.502  2213  2213 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-08 18:23:41.502  2213  2213 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-08 18:23:41.503  2213  2213 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-08 18:23:41.503  2213  2213 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-08 18:23:41.503  2213  2213 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-08 18:23:41.503  2213  2213 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 612804145
09-08 18:23:41.504  2213  2213 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 612804145
,09-08 18:23:41.506  6733  6759 D UEI.SmartControl: Internal timer expired: 1
09-08 18:23:41.506  6733  6759 D UEI.SmartControl: unbind internal service
09-08 18:23:41.510  6733  6733 D UEI.SmartControl: Service.onUnbind: IControl
09-08 18:23:41.510  6733  6733 D UEI.SmartControl: Service.onDestroy
09-08 18:23:41.510  6733  6733 D UEI.SmartControl: Lock is in USE false
09-08 18:23:41.510  6733  6733 D UEI.SmartControl: unbind internal service
09-08 18:23:41.510  6733  6733 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@16b61266
09-08 18:23:41.511  6733  6733 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-08 18:23:41.511  6733  6733 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-08 18:23:41.511  6733  6733 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-08 18:23:41.511  6733  6733 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-08 18:23:41.511  6733  6733 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-08 18:23:41.511  6733  6733 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-08 18:23:41.511  6733  6733 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-08 18:23:41.511  6733  6733 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-08 18:23:41.511  6733  6733 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:41.511  6733  6733 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 18:23:41.511  6733  6733 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 18:23:41.511  6733  6733 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:41.511  6733  6733 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:41.511  6733  6733 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 18:23:41.511  6733  6733 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 18:23:41.511  6733  6733 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@16b61266
09-08 18:23:41.514  6733  6733 D serial_port: close(fd = 25)
09-08 18:23:41.515  2213  2213 I SmartShareClient: [SmartShareManagerClient] terminate service: 2213/MediaPlaybackService/78508988
,09-08 18:23:41.519  6733  6733 I UEI.SmartControl: Serial port is closed.
09-08 18:23:41.519  6733  6733 I UEI.SmartControl: Serial port is closed.
09-08 18:23:41.519  6733  6733 D UEI.SmartControl: Blaster closed
09-08 18:23:41.519  6733  6733 D UEI.SmartControl: Shut down QS...
09-08 18:23:41.519  6733  6733 D UEI.SmartControl: Stopping QS lib
09-08 18:23:41.520  6733  6733 D UEI.SmartControl: QS lib stop result = true
09-08 18:23:41.520  6733  6733 D UEI.SmartControl: Stopped QS lib
09-08 18:23:41.520  6733  6733 D UEI.SmartControl: Stopped file observer...
09-08 18:23:41.520  6733  6733 D UEI.SmartControl: QS shutdown complete
09-08 18:23:41.526  2213  2213 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-08 18:23:41.526  2213  2213 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@edde116
09-08 18:23:41.529  2213  2213 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-08 18:23:41.529  2213  2213 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-08 18:23:41.530  2213  2213 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-08 18:23:41.531  2213  2213 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,09-08 18:23:41.534  1036  1628 I ActivityManager: Killing 6342:com.android.calendar/u0a13 (adj 15): empty #17
09-08 18:23:41.542  2213  2213 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
,09-08 18:23:41.634  1036  1905 W libprocessgroup: failed to open /acct/uid_10013/pid_6342/cgroup.procs: No such file or directory
,09-08 18:23:42.693  1818  6476 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-08 18:23:42.699   309  6807 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-08 18:23:42.699   309  6807 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-08 18:23:42.699   309  6807 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-08 18:23:42.963  1818  1818 I ConfigFetchService: fetch service done; releasing wakelock
,09-08 18:23:42.969  1818  1818 I ConfigFetchService: stopping self
09-08 18:23:42.980  2082  2082 I ConfigService: onDestroy
,09-08 18:23:47.786  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 18:23:47.786  6609  6721 I jxcore-log: 
,09-08 18:23:47.788  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 18:23:47.788  6609  6721 I jxcore-log: 
09-08 18:23:47.793  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:47.793  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:47.793  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:47.793  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:47.793  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:47.793  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:47.793  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:47.793  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:47.796  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:47.799  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 18:23:47.799  6609  6721 I jxcore-log: 
,09-08 18:23:47.800  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 18:23:47.800  6609  6721 I jxcore-log: 
,09-08 18:23:47.832  1036  1114 I ActivityManager: Waited long enough for: ServiceRecord{3f9d9714 u0 com.google.android.gms/.wearable.service.WearableService}
,09-08 18:23:48.436  6609  6721 D executeNativeTests: Running unit tests
,09-08 18:23:48.519  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:23:48.519  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 added. We now have 2 listener(s)
,09-08 18:23:48.520  1036  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:23:48.521  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-08 18:23:48.521  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:23:48.521  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:23:48.522  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:48.522  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a added. We now have 2 listener(s)
09-08 18:23:48.522  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:23:48.522  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:23:48.524  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:48.529  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:48.529  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:48.529  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:48.529  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:48.529  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:48.529  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:48.529  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:48.529  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:48.530  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:48.530  6609  6721 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:48.531  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.532  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.539  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:23:48.542  6609  6721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:48.542  6609  6721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:48.543  6609  6721 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-08 18:23:48.547  6609  6721 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 18:23:48.547  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:23:48.547  6609  6721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:48.548  6609  6721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:48.549  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.552  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.552  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.552  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.553  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.553  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:48.554  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:23:48.555  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 removed from the list
09-08 18:23:48.555  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.555  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a removed from the list
09-08 18:23:48.555  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.555  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.555  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.555  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:48.556  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.556  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.556  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.557  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.559  6609  6721 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-08 18:23:48.559  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.559  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.559  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.560  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.560  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.560  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.560  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.560  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.560  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.560  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.560  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.560  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.560  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.560  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.561  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.561  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.561  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.561  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 18:23:48.565  6609  6721 D, io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 18:23:48.565  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 18:23:48.565  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 1,8:23:48.565  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.565  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.566  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.566  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.566  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.566  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.566  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.566  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.566  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.566  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.566  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.566  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.566  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.566  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.566  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.566  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.566  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.567  6609  6721 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 18:23:48.573  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:48.575  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:48.575  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:48.575  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:48.575  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:48.575  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:48.575  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:48.575  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:48.575  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:48.576  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:48.576  6609  6721 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:48.576  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:23:48.577  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.578  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.578  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:48.578  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:48.578  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:48.578  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:23:48.581  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:23:48.582  1036  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:23:48.586  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 18:23:48.590  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 18:23:48.592  6609  6721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-08 18:23:48.593  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:23:48.594  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:48.595  6609  6721 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 18:23:48.595  6609  6721 I io.jxcore.node.ConnectionHelper: start: OK
09-08 18:23:48.598  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.598  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.598  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.598  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.598  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.598  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:48.598  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.598  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.598  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.598  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.598  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.598  6609  6721 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 18:23:48.600  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:48.602  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:48.602  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:48.602  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:48.602  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:48.602  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:48.602  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:48.602  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:48.602  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:48.602  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:48.602  6609  6721 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:48.603  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:48.605  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:23:48.605  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:48.605  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:48.605  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:48.605  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:23:48.606  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.608  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:23:48.608  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:48.609  6609  6721 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 18:23:48.609  6609  6721 I io.jxcore.node.ConnectionHelper: start: OK
09-08 18:23:48.611  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.611  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.611  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.611  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.611  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.611  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:48.611  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.611  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.611  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.611  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.611  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.612  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.612  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.613  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.613  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.615  6609  6721 D BluetoothLeScanner: could not find callback wrapper
,09-08 18:23:48.615  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.615  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.615  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.616  6609  6721 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 18:23:48.618  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:48.621  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:48.621  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:48.621  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:48.621  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:48.621  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:48.621  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:48.621  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:48.621  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:48.622  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:48.622  6609  6721 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:48.623  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:23:48.623  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:48.623  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:48.623  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:48.624  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:23:48.624  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.626  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:48.628  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:23:48.629  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:48.630  6609  6721 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 18:23:48.630  6609  6721 I io.jxcore.node.ConnectionHelper: start: OK
09-08 18:23:48.630  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.630  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.630  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.631  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.631  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.631  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.631  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.631  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.631  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:48.632  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.632  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.632  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.632  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.632  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.632  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.632  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.633  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.633  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.633  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.633  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.633  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.633  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.634  6609  6721 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 18:23:48.634  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.634  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discove,ry: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.634  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.635  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.635  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.635  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.635  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.635  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.635  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.635  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.635  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.635  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.635  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.635  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.636  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.636  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.636  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.636  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.636  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.636  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.637  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 18:23:48.637  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.637  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.637  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.638  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.638  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.638  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.638  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.638  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.638  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.638  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.638  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.638  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.638  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.638  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.639  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.639  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.640  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.640  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.640  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.640  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.641  6609  6721 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 18:23:48.641  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.641  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.641  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.641  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.641  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.641  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.641  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.641  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.641  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.641  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.641  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.641  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.641  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.641  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.643  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.643  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.643  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.643  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.644  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.644  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.644  6609  6721 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 18:23:48.645  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.645  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.645  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.645  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.645  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.645  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.645  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.645  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.645  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.645  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.645  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.645  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.645  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.645  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.646  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.646  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.647  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.647  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.647  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.647  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.648  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:23:48.648  6609  6721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:48.648  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:23:48.648  6609  6721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:48.648  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:23:48.648  6609  6721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:48.648  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.648  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.648  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.648  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.648  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.648  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.648  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.649  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.649  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.649  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.649  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.649  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.649  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.649  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.652  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.652  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.653  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.653  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.653  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.653  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.654  6609  6721 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:48.654  6609  6721 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 18:23:48.655  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 18:23:48.661  6609  6721 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:48.661  6609  6721 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 18:23:48.662  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 18:23:48.663  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 18:23:48.663  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 18:23:48.663  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 18:23:48.663  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 18:23:48.663  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-08 18:23:48.663  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 18:23:48.663  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 18:23:48.663  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 18:23:48.663  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 18:23:48.663  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 18:23:48.663  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 18:23:48.663  6609  6721 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 18:23:48.663  6609  6721 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:48.663  6609  6721 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 18:23:48.664  6609  6721 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:48.664  6609  6721 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:48.664  6609  6721 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 18:23:48.664  6609  6721 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:48.664  6609  6721 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:48.664  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 18:23:48.666  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 18:23:48.667  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 18:23:48.667  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 18:23:48.668  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 18:23:48.668  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 18:23:48.668  6609  6721 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 18:23:48.668  6609  6721 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:48.668  6609  6721 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 18:23:48.669  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.669  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.669  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.670  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.670  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.670  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.670  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 18:23:48.671  6609  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 825)
09-08 18:23:48.673  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.673  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.673  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.673  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.673  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.673  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.673  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.673  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.674  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.674  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.674  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.674  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.674  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.674  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.675  6609  6721 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 18:23:48.676  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.676  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.676  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.676  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.676  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.676  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.676  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.676  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.676  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.676  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.676  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.676  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.676  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.676  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.677  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.677  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.678  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.678  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.678  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.678  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.681  6609  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 18:23:48.682  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.682  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.682  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.682  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.682  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.682  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.683  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.683  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.683  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.683  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.683  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.683  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.683  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.683  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.683  6609  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 825
09-08 18:23:48.683  6609  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 825)
09-08 18:23:48.683  6609  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 825)
09-08 18:23:48.684  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.684  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.685  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.685  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.685  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.685  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.686  6609  6721 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 18:23:48.686  6609  6721 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 18:23:48.686  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:48.686  6609  6721 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 18:23:48.686  6609  6721 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 18:23:48.686  6609  6721 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 18:23:48.686  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:23:48.686  6609  6721 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 18:23:48.686  6609  6721 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 18:23:48.686  6609  6721 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 18:23:48.686  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:23:48.687  6609  6721 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 18:23:48.687  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.687  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.687  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.688  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.688  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.688  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.688  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.688  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.688  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.688  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.688  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.688  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.688  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.688  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.689  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.689  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.690  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.690  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.690  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.690  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.690  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.691  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.691  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.691  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.691  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.691  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.691  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.691  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.691  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.691  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.691  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.691  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.691  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.691  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.691  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.691  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.691  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.691  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.692  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.693  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.693  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.693  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.693  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.693  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.693  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.693  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.693  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.693  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.693  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.694  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.694  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-08 18:23:48.695  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.695  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.695  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.695  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.696  6609  6721 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 18:23:48.697  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:48.698  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 18:23:48.698  6609  6721 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 18:23:48.698  6609  6721 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 18:23:48.699  6609  6609 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 18:23:48.699  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 18:23:48.699  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:23:48.700  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.700  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 18:23:48.700  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 18:23:48.700  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 18:23:48.701  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.701  6609  6721 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 18:23:48.702  6609  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 18:23:48.702  6609  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 18:23:48.703  6609  6609 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 18:23:48.703  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.703  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.703  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:23:48.703  6609  6721 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:23:48.703  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:23:48.705  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:23:48.706  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:23:48.706  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:48.706  6609  6721 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:23:48.706  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.706  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.707  6609  6721 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:48.707  6609  6609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:48.707  6609  6609 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 18:23:48.707  6609  6609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:48.708  6609  6609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:48.708  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.708  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.708  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.708  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.708  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.708  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.709  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.709  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.709  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.709  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.709  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.709  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.709  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.709  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.709  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.710  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.710  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.710  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.710  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.711  6609  6721 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 18:23:48.722  6609  6721 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 18:23:48.722  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:23:48.723  6609  6721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:48.724  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.724  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.724  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.724  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.724  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.724  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.724  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.724  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.724  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.724  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.724  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.724  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.724  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.724  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.732  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.732  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.732  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.732  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.734  1036  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:23:48.734  1036  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:23:48.735  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:23:48.736  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.736  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.736  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:23:48.739  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.739  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.739  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.739  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.739  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.739  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.739  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.739  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.739  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.739  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.739  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.740  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.740  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.740  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.740  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.742  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:48.742  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:48.742  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:48.742  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:48.742  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.742  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.742  6609  6721 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8c7b5 not in the list
09-08 18:23:48.742  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.742  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.742  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:48.742  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:48.742  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.742  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: r,elease: The given listener does not exist in the list - probably already removed
09-08 18:23:48.742  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:48.743  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:48.743  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:48.743  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:48.743  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc45e4a not in the list
09-08 18:23:48.745  6609  6721 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 18:23:48.745  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:48.745  6609  6721 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 18:23:48.745  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:48.745  6609  6721 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 18:23:48.745  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:23:48.748  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 18:23:48.748  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 18:23:48.749  6609  6721 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 18:23:48.749  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 18:23:48.749  6609  6721 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 18:23:48.749  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-08 18:23:48.749  6609  6721 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 18:23:48.749  6609  6721 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 18:23:48.750  6609  6721 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 18:23:48.750  6609  6721 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 18:23:48.751  6609  6721 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 18:23:48.751  6609  6721 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 18:23:48.751  6609  6721 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 18:23:48.751  6609  6721 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-08 18:23:48.758  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:48.758  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@81dcd33 added. We now have 2 listener(s)
09-08 18:23:48.758  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:23:48.762  6609  6721 D BluetoothAdapter: enable(): BT is already enabled..!
09-08 18:23:48.768  1036  1628 D WifiServiceImplEx: setWifiEnabled: true pid=6609, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 18:23:48.769  1036  1628 D WifiService: setWifiEnabled: true pid=6609, uid=10118
09-08 18:23:48.769  1036  1628 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:23:48.773  6609  6808 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-08 18:23:48.773  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:48.773  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31a818f0 added. We now have 3 listener(s)
09-08 18:23:48.773  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:23:48.773  6609  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 825)
09-08 18:23:48.776  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:48.776  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15cbee69 added. We now have 4 listener(s)
09-08 18:23:48.776  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:23:48.778  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:48.778  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38aeb0ee added. We now have 5 listener(s)
09-08 18:23:48.778  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:23:48.780  1036  1052 D WifiServiceImplEx: setWifiEnabled: false pid=6609, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 18:23:48.780  1036  1052 D WifiService: setWifiEnabled: false pid=6609, uid=10118
09-08 18:23:48.780  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:23:48.788  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 18:23:48.788  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 18:23:48.788  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-08 18:23:48.789  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:23:48.789  1036  1051 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@370d64c9 mBinding = false
09-08 18:23:48.789  1036  1436 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-08 18:23:48.790  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-08 18:23:48.790  1036  1436 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-08 18:23:48.790  1036  1436 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-08 18:23:48.791  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-08 18:23:48.791  1036  1436 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 18:23:48.791  1036  1436 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 18:23:48.791  1036  1436 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 18:23:48.792  1036  1436 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 18:23:48.792  1036  1436 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 18:23:48.798  1036  1436 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 18:23:48.798  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.798  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:23:48.799  1036  1118 D BluetoothManagerService: Message: 2
09-08 18:23:48.799  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 18:23:48.800  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 18:23:48.800  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-08 18:23:48.800  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 18:23:48.800  2749  2749 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 18:23:48.800  1036  1118 D BluetoothManagerService: Sending off request.
09-08 18:23:48.800  3844  3862 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-08 18:23:48.801  1036  1436 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 18:23:48.801  1036  1436 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 18:23:48.801  3844  3933 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-08 18:23:48.801  3844  3933 D BluetoothAdapterProperties: Setting state to 13
09-08 18:23:48.801  1036  1436 D WifiNative-wlan0: SET ps 1: returned true
,09-08 18:23:48.801  3844  3933 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 18:23:48.801  1036  1118 D BluetoothManagerService: Message: 60
09-08 18:23:48.801  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-08 18:23:48.801  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-08 18:23:48.801  3844  3933 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 18:23:48.801  3844  3933 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-08 18:23:48.803  3844  3844 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:48.803  3844  3844 D BluetoothMapService: STATE_TURNING_OFF
09-08 18:23:48.803  3844  3844 V BtOppService: Receiver DISABLED_ACTION 
09-08 18:23:48.803  3844  3844 V BluetoothMapService: Handler(): got msg=4
09-08 18:23:48.803  3844  3844 D BluetoothMapService: MAP Service closeService in
09-08 18:23:48.803  3844  3844 D BluetoothMapMasInstance: MAP Service shutdown
09-08 18:23:48.804  3844  4279 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-08 18:23:48.804  3844  4279 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:23:48.804  3844  4279 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-08 18:23:48.804  3844  4279 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-08 18:23:48.804  3844  4279 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-08 18:23:48.804  3844  4279 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-08 18:23:48.804  3844  4279 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-08 18:23:48.804  3844  4279 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-08 18:23:48.804   309   893 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:23:48.804  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:48.805  3844  3844 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 18:23:48.805  3844  3844 V BluetoothMapService: MAP Service closeService out
09-08 18:23:48.805  3844  3844 I BtOppRfcommListener: stopping Accept Thread
09-08 18:23:48.805  3844  3844 V BtOppRfcommListener: close mBtServerSocket
09-08 18:23:48.805  3844  3844 V BtOppRfcommListener: waiting for thread to terminate
09-08 18:23:48.805  3844  4356 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:23:48.805  3844  4356 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 18:23:48.806  3844  3844 V BtOppRfcommListener: done waiting for thread to terminate
09-08 18:23:48.806  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 18:23:48.806  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:48.806  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:48.806  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:48.806  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:48.806  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:48.806  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:48.806  ,6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:48.806  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:48.806  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:48.807  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:48.807  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:48.810  1036  2868 D DhcpStateMachine: RunningState{ when=-9ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:23:48.842  1036  1114 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6818 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-08 18:23:48.843  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 18:23:48.843  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-08 18:23:48.846  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-08 18:23:48.847  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-08 18:23:48.848  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:48.848  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:48.848  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 18:23:48.848  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-08 18:23:48.848  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:48.848  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:48.848  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 18:23:48.848  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
09-08 18:23:48.848  1036  1036 D RttService: SCAN_AVAILABLE : 1
09-08 18:23:48.849  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.849  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.849  1036  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2ec664c8
09-08 18:23:48.849  1036  1390 D LGWifiP2pService: P2pDisablingState
09-08 18:23:48.849  1036  1390 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.849  1036  1390 D LGWifiP2pService: p2p socket connection lost
09-08 18:23:48.849  1036  1390 D LGWifiP2pService: P2pDisabledState
09-08 18:23:48.850  1036  1436 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:48.850  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:48.851  1036  1436 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:48.851  1036  1436 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:48.851  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:48.851  1036  1436 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:48.852  1036  1436 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 18:23:48.852  1036  1436 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,09-08 18:23:48.852  1036  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.852  1036  1390 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.856  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-08 18:23:48.856  1942  1942 D WfdsService: WifiP2pState is changed : false
09-08 18:23:48.856  1942  2243 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-08 18:23:48.856  1942  2243 D WfdsService: Set the WFDS Monitor: false
09-08 18:23:48.857  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 18:23:48.857  2749  2749 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 18:23:48.857  1036  1436 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 18:23:48.857  1036  1436 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 18:23:48.857  1036  1436 D WifiNative-wlan0: SET ps 1: returned true
09-08 18:23:48.865  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:48.870  1942  2243 D WfdsMonitor: WFDS Monitor is stopped
09-08 18:23:48.870  1942  2243 D WfdsService: STATE : WfdsDisabledState - enter
,09-08 18:23:48.871  1942  2793 D CtrlSupplicant: Received on exit socket, terminate
09-08 18:23:48.871  1942  2793 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-08 18:23:48.871  1942  2793 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-08 18:23:48.871  1942  2793 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-08 18:23:48.871  1942  2245 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-08 18:23:48.871  1036  1558 D WifiScanningService: DefaultState got{ when=-21ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.872  1036  1559 D RttService: EnabledState got{ when=-21ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.872  1942  2243 W WfdsService: DefaultState - msg [9445378] is not handled
09-08 18:23:48.878  1036  1052 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-08 18:23:48.878  1036  2867 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.878  1036  2867 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.878  1036  2867 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-08 18:23:48.879  1036  2867 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.879  1036  2867 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-08 18:23:48.887   309   893 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:23:48.888  1036  1484 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-08 18:23:48.888  1036  1484 D DSQN    : disableDataServiceNotify
09-08 18:23:48.888  1036  1484 D DSQN    : stop dsqn bin
,09-08 18:23:48.889   309  6843 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-08 18:23:48.890  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-08 18:23:48.890  1036  2867 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-08 18:23:48.892  3844  3844 V BtOppService: onDestroy
09-08 18:23:48.894  1036  1484 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 18:23:48.894  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:48.894  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:23:48.895  1036  1484 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:23:48.895  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-08 18:23:48.895  1036  2867 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.895  1036  2867 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:48.895  1036  2867 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-08 18:23:48.896  1605  2099 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 18:23:48.896  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:48.896  3844  3937 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:23:48.897  3844  3933 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-08 18:23:48.897  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-08 18:23:48.897  3844  4362 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:23:48.897  3844  4106 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-08 18:23:48.897  3844  3933 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-08 18:23:48.897  3844  4358 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:23:48.898  3844  4285 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:23:48.899  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 18:23:48.899  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 18:23:48.899  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 18:23:48.899  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 18:23:48.899  3844  4106 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:48.899  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 18:23:48.899  3844  4106 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:48.899  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 18:23:48.899  3844  4106 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:48.899  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-08 18:23:48.899  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-08 18:23:48.899  3844  4106 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-08 18:23:48.899  3844  3844 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-08 1,8:23:48.899  1036  1436 D WifiNative-p2p0: doBoolean: TERMINATE
09-08 18:23:48.900  1036  1436 D WifiNative-p2p0: TERMINATE: returned true
09-08 18:23:48.900  1036  1436 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 18:23:48.900  1036  1436 E WifiStateMachine: useWiFiOffloading() : false
09-08 18:23:48.900  1036  1436 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-08 18:23:48.903  1036  1484 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-08 18:23:48.904  1036  1484 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 18:23:48.904  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 18:23:48.906  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-08 18:23:48.909  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:48.909  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:23:48.910  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:48.910  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:48.910  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:48.910  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:48.910  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:48.910  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:48.910  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:48.910  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:48.910  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:48.910  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:48.910  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:48.910  6609  6721 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:48.911  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:48.934  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:48.934  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 18:23:48.937  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:48.942  1036  1959 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6847 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-08 18:23:48.944  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:48.944  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 18:23:48.944  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:23:48.944  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 18:23:48.945  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:48.945  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:48.945  1036  1484 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:48.945  1036  1484 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:48.945  1036  1484 D NetworkManagementService: Removing idletimer
09-08 18:23:48.945  1036  1436 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:48.946  1036  1436 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:48.946  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:48.946  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 18:23:48.946  1036  1484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:48.946  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 18:23:48.947  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 18:23:48.947  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 18:23:48.949  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.952  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.956  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:48.956  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:48.956  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:48.956  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:48.956  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:48.956  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:48.956  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:48.956  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:48.956  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:48.957  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:48.957  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:48.958  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.959  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.960  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.961  1036  1577 V SIM_STK : Menu title from STK is T-Mobile
,09-08 18:23:48.965  6818  6818 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:48.965  6818  6818 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-08 18:23:48.965  6818  6818 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 18:23:48.966  6818  6818 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-08 18:23:48.966  6818  6818 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 18:23:48.967  6818  6818 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-08 18:23:48.979  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 18:23:48.979  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:48.980  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 18:23:48.991  1036  1999 I art     : Explicit concurrent mark sweep GC freed 35017(1772KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.795ms total 155.915ms
09-08 18:23:48.996  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 18:23:48.996  1036  1379 V AlarmManager: RTC_WAKEUP set : Alarm{159d22da type 0 when 1473351828317 com.android.vending} when 1473351828317
09-08 18:23:48.996  1036  1484 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-08 18:23:48.997  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:48.997  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-08 18:23:48.997  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:48.997  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:48.997  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:48.997  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 18:23:48.997  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-08 18:23:48.997  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:23:48.997  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-08 18:23:48.997  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 18:23:48.998  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 18:23:48.998  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 18:23:48.998  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 18:23:48.998  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 18:23:48.998  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 18:23:48.998  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 18:23:48.998  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-08 18:23:49.022  1036  2868 D DhcpStateMachine: StoppedState
09-08 18:23:49.022  1036  2868 D DhcpStateMachine: StoppedState{ when=-165ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:23:49.022  2749  2749 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-08 18:23:49.023  2749  2749 I wpa_supplicant: monitor socket send errors count : 1
09-08 18:23:49.023  2749  2749 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-2\x00 that cannot receive messages
09-08 18:23:49.023  1036  2784 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-08 18:23:49.023  1036  2784 D WifiMonitor: Dropping event because (p2p0) is stopped
09-08 18:23:49.024  1036  1436 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-08 18:23:49.024  1036  1436 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-08 18:23:49.044  6847  6847 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-08 18:23:49.048  6847  6847 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 18:23:49.049  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:23:49.054  6818  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-08 18:23:49.056  3844  3844 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-08 18:23:49.056  3844  3844 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:49.057  3844  3844 V BluetoothPbapReceiver: ***********state = 13
09-08 18:23:49.057  3844  3844 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-08 18:23:49.058  3844  3844 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:49.058  3844  3844 V BluetoothPbapService: state: 13
09-08 18:23:49.058  3844  3844 V BluetoothPbapService: Pbap Service closeService in
09-08 18:23:49.059  2082  2082 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:23:49.059  3844  3844 V BluetoothPbapService: successfully stopped pbap service
09-08 18:23:49.059  3844  3844 V BluetoothPbapService: Pbap Service closeService out
09-08 18:23:49.059  3844  3844 V BluetoothPbapService: Pbap Service onDestroy
09-08 18:23:49.059  3844  3844 V BluetoothPbapService: Pbap Service closeService in
09-08 18:23:49.059  3844  3844 V BluetoothPbapService: Pbap Service closeService out
09-08 18:23:49.059  3844  3844 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-08 18:23:49.060  2749  2749 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 18:23:49.060  1036  2784 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-08 18:23:49.060  1036  2784 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 18:23:49.060  1036  2784 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 18:23:49.060  1036  2784 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-08 18:23:49.061  2749  2749 W wpa_supplicant: USIM:  scard_deinit function
09-08 18:23:49.061  1036  2784 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 18:23:49.061  1036  2784 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 18:23:49.061  1036  1436 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=114836
09-08 18:23:49.061  1036  1436 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=114837
09-08 18:23:49.062  1036  1436 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=114837  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-08 18:23:49.062  1036  1118 D Tethering: InitialState.processMessage what=4
09-08 18:23:49.062  1036  1436 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=114837  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-08 18:23:49.067  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:49.087  1036  1940 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6868 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-08 18:23:49.088  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:23:49.089  1036  1436 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:49.089  1036  1436 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:49.098   335   335 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 197us total 9.215ms
09-08 18:23:49.107   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.708ms
,09-08 18:23:49.116   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 303us total 9.063ms
09-08 18:23:49.124  6818  6818 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:23:49.124  6818  6818 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:23:49.136  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 18:23:49.144  1036  1118 D BluetoothManagerService: Message: 20
09-08 18:23:49.144  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1927e401:true
09-08 18:23:49.157  1036  1118 D BluetoothManagerService: Message: 30
,09-08 18:23:49.158  6868  6868 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-08 18:23:49.158  6868  6868 W LG Account v2.2: No ProfileInfo entries
09-08 18:23:49.158  6868  6868 I LG Account v2.2: isEnabled: false
09-08 18:23:49.158  6868  6868 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-08 18:23:49.158  6868  6868 I Feature : [Lifetracker]Country: EU
09-08 18:23:49.158  6868  6868 I Feature : [Lifetracker]Operator: OPEN
09-08 18:23:49.158  6868  6868 I Feature : [Lifetracker]Ranking support: false
09-08 18:23:49.158  6868  6868 I Feature : [Lifetracker]Comfort support: false
09-08 18:23:49.158  6868  6868 I Feature : [Lifetracker]Accessory: true
09-08 18:23:49.158  6868  6868 I Feature : [Lifetracker]Health device: true
09-08 18:23:49.158  6868  6868 I Feature : [Lifetracker]Extra Pedometer: false
09-08 18:23:49.158  6868  6868 I Feature : [Lifetracker]Blood glucose device: false
09-08 18:23:49.158  6868  6868 I Feature : [Lifetracker]Device Number: 3
09-08 18:23:49.162  1036  1986 I ActivityManager: Killing 6305:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-08 18:23:49.163  1036  1118 D BluetoothManagerService: Message: 30
09-08 18:23:49.173  2749  2749 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-08 18:23:49.173  1036  2784 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-08 18:23:49.173  1036  2784 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-08 18:23:49.173  1036  2784 D WifiMonitor: Disconnecting from the supplicant, no more events
09-08 18:23:49.173  1036  1436 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,09-08 18:23:49.190  6076  6076 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-08 18:23:49.205  1036  2052 W libprocessgroup: failed to open /acct/uid_10014/pid_6305/cgroup.procs: No such file or directory
,09-08 18:23:49.206  6818  6818 D LocalBluetoothProfileManager: Adding local MAP profile
09-08 18:23:49.209  6609  6609 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-08 18:23:49.210  1036  1959 I ActivityManager: Killing 6275:com.android.defcontainer/u0a4 (adj 15): empty #17
09-08 18:23:49.210  6818  6818 D BluetoothMap: Create BluetoothMap proxy object
09-08 18:23:49.211  1036  1118 D BluetoothManagerService: Message: 30
09-08 18:23:49.240  1036  1887 W libprocessgroup: failed to open /acct/uid_10004/pid_6275/cgroup.procs: No such file or directory
,09-08 18:23:49.242  1036  1118 D BluetoothManagerService: Message: 30
09-08 18:23:49.246  6818  6818 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 18:23:49.248  6818  6818 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-08 18:23:49.274  6818  6818 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-08 18:23:49.274  1036  1436 D WifiOffDelayIfNotUsed: stopMonitoring
09-08 18:23:49.274  1036  1436 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 18:23:49.274  1036  1436 E WifiStateMachine: useWiFiOffloading() : false
09-08 18:23:49.274  1036  1436 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-08 18:23:49.277  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:49.277  1942  1942 D WfdsService: Supplicant Connection state is changed : false
09-08 18:23:49.277  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-08 18:23:49.277  1942  2243 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-08 18:23:49.278  1942  2243 D WfdsService: Set the WFDS Monitor: false
09-08 18:23:49.278  1942  2243 D WfdsMonitor: WFDS Monitor is stopped
09-08 18:23:49.278  1036  1450 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-08 18:23:49.278  1036  1450 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-08 18:23:49.279  2454  2454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:49.281  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-08 18:23:49.282  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:49.282  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:49.282  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:49.282  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:49.282  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:49.282  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:49.282  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:49.282  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:49.282  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:49.285  6818  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,09-08 18:23:49.290  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:49.290  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:49.290  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:49.290  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:49.290  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:49.290  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:49.290  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:49.290  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:49.290  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:49.303  6818  6818 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:49.321  6818  6818 D BluetoothInputDevice: Proxy object connected
,09-08 18:23:49.324  6818  6818 D HidProfile: Bluetooth service connected
09-08 18:23:49.330  6818  6818 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:23:49.332  6818  6818 D PanProfile: Bluetooth service connected
09-08 18:23:49.333  6818  6818 D BluetoothMap: Proxy object connected
,09-08 18:23:49.335  6818  6818 D MapProfile: Bluetooth service connected
09-08 18:23:49.335  6818  6818 D BluetoothMap: getConnectedDevices()
09-08 18:23:49.336  6818  6818 D BluetoothMap: Bluetooth is Not enabled
09-08 18:23:49.337  6818  6818 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-08 18:23:49.343  6818  6818 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-08 18:23:49.352  6818  6818 D BluetoothPermissionRequest: onReceive
09-08 18:23:49.356  6818  6818 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-08 18:23:49.368  1036  1959 I ActivityManager: Killing 6478:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-08 18:23:49.371  6818  6818 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 18:23:49.406  3844  3844 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-08 18:23:49.406  3844  3844 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-08 18:23:49.407  3844  3844 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-08 18:23:49.409  1036  1940 W libprocessgroup: failed to open /acct/uid_10008/pid_6478/cgroup.procs: No such file or directory
09-08 18:23:49.483  1036  1959 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6898 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-08 18:23:49.490  3844  3844 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:49.490  3844  3844 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-08 18:23:49.491  3844  3844 V BluetoothFtpService: Ftp Service onStartCommand
09-08 18:23:49.492  3844  3844 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:49.494  3844  3844 V BluetoothFtpService: Ftp Service closeService
09-08 18:23:49.495  3844  3844 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-08 18:23:49.497  3844  3844 V BluetoothFtpService: successfully stopped ftp service
09-08 18:23:49.497  3844  3844 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 18:23:49.497  3844  3844 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 18:23:49.497  3844  3844 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 18:23:49.497  3844  3844 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:49.497  3844  3844 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-08 18:23:49.497  3844  3844 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-08 18:23:49.501  3844  3844 V BluetoothFtpService: Ftp Service onDestroy
09-08 18:23:49.501  3844  3844 V BluetoothFtpService: Ftp Service closeService
,09-08 18:23:49.554  1036  1887 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6915 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 18:23:49.562  3844  3844 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:49.562  3844  3844 V BluetoothSapService: state: 13
09-08 18:23:49.563  3844  3844 V BluetoothSapService: Stopping SAP server process
09-08 18:23:49.564  3844  3844 V BluetoothSapService: Sap Service closeSapService in
09-08 18:23:49.564  3844  3844 V BluetoothSapService: Close listen Socket : 
09-08 18:23:49.565  3844  3844 V BluetoothSapService: Close rfcomm Socket : 
09-08 18:23:49.565  3844  3844 V BluetoothSapService: Close sapd  Socket : 
09-08 18:23:49.566  3844  3844 V BluetoothSapService: Sap Service closeSapService out
09-08 18:23:49.566  3844  3844 V BluetoothSapService: Sap Service onDestroy
09-08 18:23:49.566  3844  3844 V BluetoothSapService: Sap Service closeSapService in
09-08 18:23:49.566  3844  3844 V BluetoothSapService: Close listen Socket : 
,09-08 18:23:49.567  3844  3844 V BluetoothSapService: Close rfcomm Socket : 
09-08 18:23:49.567  3844  3844 V BluetoothSapService: Close sapd  Socket : 
09-08 18:23:49.568  3844  3844 V BluetoothSapService: Sap Service closeSapService out
09-08 18:23:49.586  6898  6898 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 18:23:49.615  6915  6915 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 18:23:49.619  6898  6898 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-08 18:23:49.631  1036  1988 I ActivityManager: Killing 6006:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-08 18:23:49.656  6898  6898 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-08 18:23:49.657  6898  6898 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-08 18:23:49.657  6898  6898 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-08 18:23:49.657  6898  6898 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-08 18:23:49.658  6898  6898 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-08 18:23:49.660  6898  6898 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-08 18:23:49.665  6898  6898 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-08 18:23:49.674  1036  1577 W libprocessgroup: failed to open /acct/uid_10011/pid_6006/cgroup.procs: No such file or directory
,09-08 18:23:49.682  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:49.684  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:49.699  6898  6898 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 18:23:49.704  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:49.710  6847  6847 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 18:23:49.710  6847  6847 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 18:23:49.711  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:23:49.713  6898  6898 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-08 18:23:49.716  6898  6898 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-08 18:23:49.716  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:49.725  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:49.735  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:49.735  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:49.736  6898  6898 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 18:23:49.746  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 18:23:49.750  6847  6847 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 18:23:49.750  6847  6847 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 18:23:49.750  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 18:23:49.755  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 18:23:49.760  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:49.767  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:49.768  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 18:23:49.769  6898  6898 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 18:23:49.833  1036  2052 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6935 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-08 18:23:49.901  3844  3937 D bt_hci_bdroid: cleanup
09-08 18:23:49.901  3844  4106 W bt-btif : ag scb idx 1 not allocated
09-08 18:23:49.902  3844  4242 I bt_userial_mct: exiting userial_read_thread
09-08 18:23:49.902  3844  4242 D bt_userial_mct: Leaving userial_evt_read_thread()
09-08 18:23:49.902  3844  4108 I bt_lpm  : LPM is already off!!!
,09-08 18:23:49.902  3844  4106 E bt-btif : BTA AG is already disabled, ignoring ...
09-08 18:23:49.902  3844  3937 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 18:23:49.902  3844  4106 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:49.902  3844  4106 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-08 18:23:49.902  3844  4108 I bt_vendor: hw_epilog_process
09-08 18:23:49.903  3844  3937 D bt_hci_bdroid: cleanup Finalizing cleanup
09-08 18:23:49.903  3844  3937 D bt_userial_mct: userial_close
09-08 18:23:49.903  3844  3937 E bt_userial_mct: pthread_join() FAILED result:3
09-08 18:23:49.903  3844  3937 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-08 18:23:49.948  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 18:23:49.951  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:49.959  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:49.962  3844  3937 D bt_hci_bdroid: set_power 0
,09-08 18:23:49.962  3844  3937 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-08 18:23:49.962  3844  3937 I bt_vendor: bluetooth satus is on
09-08 18:23:49.962  3844  3937 I bt_vendor: bt-vendor : resetting BT status
09-08 18:23:49.962  3844  3937 I bt_vendor: Starting hciattach daemon
09-08 18:23:49.962  3844  3937 I bt_vendor: try to set false
09-08 18:23:49.963  3844  3937 I bt_vendor: Starting hciattach daemon
09-08 18:23:49.963  3844  3937 I bt_vendor: try to set false
09-08 18:23:49.965  3844  3937 I bt_vendor: cleanup
09-08 18:23:49.966  3844  4106 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-08 18:23:49.967  3844  3937 I GKI_LINUX: GKI_exit_task 0 done
09-08 18:23:49.967  3844  3937 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-08 18:23:49.970  3844  3933 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-08 18:23:49.974  3844  3844 D HeadsetService: Received stop request...Stopping profile...
09-08 18:23:49.977  3844  3844 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-08 18:23:49.977  3844  3844 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 18:23:49.977  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37cb8bcb
,09-08 18:23:49.982  3844  3978 D HeadsetStateMachine: Exit Disconnected: -1
09-08 18:23:49.986  1036  1036 D BluetoothHeadset: Proxy object disconnected
09-08 18:23:49.986  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-08 18:23:49.986  1853  1853 D BluetoothHeadset: Proxy object disconnected,
09-08 18:23:49.986  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-08 18:23:49.987  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-08 18:23:49.988  3844  3844 D A2dpService: Received stop request...Stopping profile...
09-08 18:23:49.988  3844  4059 D A2dpStateMachine: Exit Disconnected: -1
09-08 18:23:49.989  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-08 18:23:49.992  3844  3933 D BluetoothAdapterState: Stopping profile services that were post enabled
09-08 18:23:49.993  3844  3844 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-08 18:23:49.993  3844  3844 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 18:23:49.993  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37cb8bcb
,09-08 18:23:49.998  1036  1036 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:49.998  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-08 18:23:49.999  3844  3844 D HidService: Received stop request...Stopping profile...
09-08 18:23:49.999  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37cb8bcb
09-08 18:23:50.000  3844  3844 D HealthService: Received stop request...Stopping profile...
09-08 18:23:50.000  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37cb8bcb
09-08 18:23:50.002  6818  6818 D BluetoothInputDevice: Proxy object disconnected
09-08 18:23:50.002  6818  6818 D HidProfile: Bluetooth service disconnected
09-08 18:23:50.003  3844  3844 D PanService: Received stop request...Stopping profile...
09-08 18:23:50.004  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37cb8bcb
09-08 18:23:50.005  6818  6818 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:23:50.005  6818  6818 D PanProfile: Bluetooth service disconnected
09-08 18:23:50.005  3844  3844 D HeadsetStateMachine: Unbinding service...
09-08 18:23:50.006  3844  3844 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 18:23:50.006  3844  3844 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 18:23:50.006  3844  3844 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 18:23:50.006  3844  3844 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 18:23:50.006  3844  3844 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 18:23:50.006  3844  3844 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 18:23:50.006  3844  3844 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-08 18:23:50.006  3844  3844 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 18:23:50.006  6935  6955 W FormManager: Network not available. Please check & try again.
09-08 18:23:50.007  3844  3844 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 18:23:50.007  3844  3844 D BtGatt.GattService: stop()
09-08 18:23:50.007  3844  3844 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 18:23:50.008  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37cb8bcb
09-08 18:23:50.010  3844  3844 D BluetoothMapService: Received stop request...Stopping profile...
09-08 18:23:50.010  3844  3844 D BluetoothMapService: stop()
09-08 18:23:50.011  3844  3844 D BluetoothMapEmailAppObserver: deinitObservers()
09-08 18:23:50.011  3844  3844 D BluetoothMapEmailAppObserver: removeReceiver()
09-08 18:23:50.015  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37cb8bcb
09-08 18:23:50.017  3844  3844 I BluetoothA2dpServiceJni: cleanupNative
09-08 18:23:50.017  3844  4061 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-08 18:23:50.017  3844  3844 I GKI_LINUX: GKI_exit_task 2 done
09-08 18:23:50.017  3844  3844 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-08 18:23:50.017  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 18:23:50.018  6818  6818 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 18:23:50.018  3844  3844 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 18:23:50.018  3844  3844 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 18:23:50.018  6818  6818 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 18:23:50.018  6818  6818 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 18:23:50.019  3844  3844 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 18:23:50.019  3844  3844 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 18:23:50.019  3844  3844 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 18:23:50.019  3844  3844 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 18:23:50.019  3844  3844 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-08 18:23:50.020  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 18:23:50.021  3844  3844 V BluetoothMapService: Handler(): got msg=4
09-08 18:23:50.021  3844  3844 D BluetoothMapService: MAP Service closeService in
09-08 18:23:50.021  3844  3844 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
,09-08 18:23:50.021  3844  3844 V BluetoothMapService: MAP Service closeService out
09-08 18:23:50.022  3844  3933 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-08 18:23:50.022  3844  3933 D BluetoothAdapterProperties: Setting state to 10
09-08 18:23:50.022  3844  3933 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-08 18:23:50.022  3844  3933 I BluetoothAdapterState: Entering OffState
09-08 18:23:50.023  1036  1118 D BluetoothManagerService: Message: 60
09-08 18:23:50.023  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-08 18:23:50.023  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-08 18:23:50.023  3844  3844 D BluetoothMapService: cleanup()
09-08 18:23:50.023  3844  3844 D BluetoothMapService: MAP Service closeService in
09-08 18:23:50.023  3844  3844 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 18:23:50.023  3844  3844 V BluetoothMapService: MAP Service closeService out
09-08 18:23:50.024  6818  6841 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 18:23:50.025  1853  3988 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:23:50.025  6818  6844 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 18:23:50.026  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:23:50.026  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:23:50.026  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:23:50.027  6818  6841 D BluetoothPan: onBluetoothStateChange on: false
09-08 18:23:50.027  6818  6844 D BluetoothMap: onBluetoothStateChange: up=false
09-08 18:23:50.028  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:23:50.030  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-08 18:23:50.030  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-08 18:23:50.032  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-08 18:23:50.032  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-08 18:23:50.032  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@370d64c9 mBinding = false
,09-08 18:23:50.033  1036  1118 D BluetoothManagerService: Sending unbind request.
09-08 18:23:50.034  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-08 18:23:50.036  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 18:23:50.039  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:50.040  1942  2102 D LGBluetoothAPIService: Message: 2
09-08 18:23:50.040  1942  2102 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@f9e3c6a mBinding = false
09-08 18:23:50.040  1942  2102 D LGBluetoothAPIService: Sending unbind request.
09-08 18:23:50.041  3844  3937 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-08 18:23:50.041  3844  3844 I GKI_LINUX: GKI_exit_task 1 done
09-08 18:23:50.041  3844  3844 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-08 18:23:50.042  3844  3844 I BluetoothServiceJni: cleanupNative: return from cleanup
09-08 18:23:50.042  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:50.042  3844  3844 I art     : --- WEIRD: removing null entry 246
09-08 18:23:50.042  3844  3844 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-08 18:23:50.042  3844  3844 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-08 18:23:50.044  6935  6958 V FormManager: Network unavailable.
09-08 18:23:50.044  3844  3844 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,09-08 18:23:50.047  6935  6958 V FormManager: Network unavailable.
09-08 18:23:50.049  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:50.050  4497  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
09-08 18:23:50.051  3844  3844 I art     : System.exit called, status: 0
09-08 18:23:50.051  3844  3844 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-08 18:23:50.053  1605  1605 D BluetoothAdapter: 465229763: getState() :  mService = null. Returning STATE_OFF
09-08 18:23:50.053  1605  1605 D BluetoothAdapter: 465229763: getState() :  mService = null. Returning STATE_OFF
09-08 18:23:50.058  6818  6818 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 18:23:50.058  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-08 18:23:50.058  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 18:23:50.058  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 18:23:50.058  6818  6818 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 18:23:50.058  6818  6818 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 18:23:50.059  6818  6818 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-08 18:23:50.060  6818  6818 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-08 18:23:50.060  6818  6818 D LGBluetoothEventManager: [BTUI] clear device connection state
09-08 18:23:50.062  6818  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-08 18:23:50.080  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-08 18:23:50.081  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 18:23:50.084   315  2211 V AudioFlinger: 3844 died, releasing its sessions
09-08 18:23:50.084   315  2211 V AudioFlinger:  pid 1853 @ 0
09-08 18:23:50.084   315  2211 V AudioFlinger:  pid 3466 @ 1
09-08 18:23:50.084   315  2211 V AudioFlinger:  pid 3466 @ 2
09-08 18:23:50.085  6818  6818 D DockEventReceiver: finishStartingService: stopping service
09-08 18:23:50.085  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:50.092  6818  6818 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,09-08 18:23:50.152  1036  1986 I ActivityManager: Process com.android.bluetooth (pid 3844) has died
09-08 18:23:50.152  1036  1986 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-08 18:23:50.163  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 18:23:50.168  2082  2082 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:50.178  1036  1941 I ActivityManager: Killing 6028:com.android.contacts/u0a19 (adj 15): empty #17
09-08 18:23:50.183  4291  6973 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 18:23:50.192  4291  6974 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 18:23:50.192  4291  6974 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 18:23:50.231  1036  1905 W libprocessgroup: failed to open /acct/uid_10019/pid_6028/cgroup.procs: No such file or directory
,09-08 18:23:50.255  6935  6976 W FormManager: Network not available. Please check & try again.
,09-08 18:23:50.257  6935  6977 V FormManager: Network unavailable.
09-08 18:23:50.260  6847  6847 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-08 18:23:50.260  6847  6847 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 18:23:50.260  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:23:50.266  6935  6977 V FormManager: Network unavailable.
,09-08 18:23:50.269  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:50.275  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:50.275  6818  6818 D BluetoothPermissionRequest: onReceive
09-08 18:23:50.278  6818  6818 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-08 18:23:50.278  6818  6818 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-08 18:23:50.279  6818  6818 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-08 18:23:50.340  1036  2033 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6979 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-08 18:23:50.369  6898  6898 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-08 18:23:50.371  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-08 18:23:50.372  6898  6898 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,09-08 18:23:50.414  6979  6979 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-08 18:23:50.414  6979  6979 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 18:23:50.414  6979  6979 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-08 18:23:50.415  6979  6979 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 18:23:50.419  6898  6898 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:23:50.419  6898  6898 D LgDataFeature: LgDataFeature() Constructor Done, null
09-08 18:23:50.426  6898  6898 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-08 18:23:50.428  6898  6898 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-08 18:23:50.428  6898  6898 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
09-08 18:23:50.428  6898  6898 V SoundPool: doLoad: loading sample sampleID=1
,09-08 18:23:50.428  6898  6898 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-08 18:23:50.431  6898  6998 V SoundPool: Start decode
09-08 18:23:50.431  6898  6998 V MediaPlayer[Native]: decode(32, 10857164, 17813)
09-08 18:23:50.432   315  2211 V MediaPlayerService: decode(23, 10857164, 17813)
09-08 18:23:50.432   315  2211 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-08 18:23:50.432   315  2211 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-08 18:23:50.432   315  2211 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-08 18:23:50.432   315  2211 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-08 18:23:50.432   315  2211 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-08 18:23:50.432   315  2211 V MediaPlayerService: player type = 3
09-08 18:23:50.432   315  2211 V AwesomePlayer: AwesomePlayer create()
09-08 18:23:50.433   315  2211 V AwesomePlayer: reset_l() 
09-08 18:23:50.433   315  2211 V AwesomePlayer: cancelPlayerEvents
09-08 18:23:50.433   315  2211 V AwesomePlayer: setAudioSink() 
09-08 18:23:50.433   315  2211 V AwesomePlayer: reset_l() 
09-08 18:23:50.433   315  2211 V AudioCache: notify(0xb5474a80, 8, 0, 0)
09-08 18:23:50.433   315  2211 V AudioCache: ignored
09-08 18:23:50.433   315  2211 V AwesomePlayer: cancelPlayerEvents
09-08 18:23:50.433   315  2211 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-08 18:23:50.433   315  2211 V AwesomePlayer: setDataSource_l dataSource
09-08 18:23:50.433   315  2211 V LGParserOSAL: SniffLGParser start
09-08 18:23:50.433   315  2211 V LGParserOSAL: MainType:5, SubType=0
09-08 18:23:50.433   315  2211 V LGParserOSAL: #### check Mime : application/ogg
09-08 18:23:50.433   315  2211 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-08 18:23:50.433   315  2211 E MediaExtractor: Use LGExtractor :application/ogg 
09-08 18:23:50.435  6733  6733 D UEI.SmartControl: QS Service created
09-08 18:23:50.442  6898  6898 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-08 18:23:50.445  6898  6898 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,09-08 18:23:50.446  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-08 18:23:50.449  6733  6733 I UEI.SmartControl: Service initServices...
,09-08 18:23:50.449  6733  6733 D UEI.SmartControl: QS start get config
09-08 18:23:50.453  6979  6979 D BluetoothAdapterApp: Loading JNI Library
,09-08 18:23:50.470  6898  6898 V LGMDMManager: Create singleton instance
,09-08 18:23:50.477   315  2211 V LGParserOSAL: supported mime: application/ogg
09-08 18:23:50.477   315  2211 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-08 18:23:50.477   315  2211 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-08 18:23:50.477   315  2211 V AwesomePlayer: mBitrate = -1 bits/sec
09-08 18:23:50.477   315  2211 V AwesomePlayer: AudioTrack Setting
09-08 18:23:50.477   315  2211 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-08 18:23:50.477   315  2211 V AwesomePlayer: setAudioSource() 
09-08 18:23:50.477   315  2211 V MediaPlayerService: prepare
09-08 18:23:50.477   315  2211 V AwesomePlayer: prepareAsync_l() 
09-08 18:23:50.477   315  2211 V MediaPlayerService: wait for prepare
09-08 18:23:50.477   315  6999 V AwesomePlayer: onPrepareAsyncEvent() 
09-08 18:23:50.477   315  6999 V AwesomePlayer: initAudioDecoder() 
09-08 18:23:50.478   315  6999 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-08 18:23:50.478   315  6999 V AudioSystem: isOffloadSupported()
09-08 18:23:50.478   315  6999 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-08 18:23:50.478   315  6999 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-08 18:23:50.478   315  6999 I AudioFlinger: isAudioPlaybackHookOn() false
09-08 18:23:50.478   315  6999 V AwesomePlayer: getUseOffload() = 0 
09-08 18:23:50.478   315  6999 V OMXCodec: OMXCodec::Create
09-08 18:23:50.478   315  6999 V OMXCodec: findMatchingCodecs()
09-08 18:23:50.478   315  6999 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-08 18:23:50.478   315  6999 V OMXCodec: matchingCodecs.size()=1
09-08 18:23:50.478   315  6999 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-08 18:23:50.479  6979  6979 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@34a77e90 Instance Count = 1
09-08 18:23:50.482   315  6999 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-08 18:23:50.482   315  6999 V LGCodecAdapter: LG Codec Adapter start
09-08 18:23:50.482   315  6999 V OMXCodec: OMXCodec Createtor
09-08 18:23:50.483  6979  6979 D BluetoothAdapterApp: onCreate
,09-08 18:23:50.483   315  6999 V OMXCodec: setComponentRole
09-08 18:23:50.483   315  6999 V OMXCodec: configureCodec protected=0
09-08 18:23:50.483   315  6999 V LGCodecAdapter: called getLGCodecSpecificData
09-08 18:23:50.483   315  6999 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-08 18:23:50.483   315  6999 V LGCodecOSAL: Called LGconfigureCodecMETA
09-08 18:23:50.483   315  6999 V LGCodecOSAL: Called LGconfigureCodecMSG
09-08 18:23:50.483   315  6999 V LGCodecOSAL: Not support LGCodec
09-08 18:23:50.483   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-08 18:23:50.483   315  6999 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
,09-08 18:23:50.484   315  6999 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-08 18:23:50.484   315  6999 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-08 18:23:50.484   315  6999 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-08 18:23:50.484   315  6999 V AudioSystem: isOffloadSupported()
09-08 18:23:50.484   315  6999 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-08 18:23:50.484   315  6999 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-08 18:23:50.484   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-08 18:23:50.484   315  6999 V OMXCodec: init()
,09-08 18:23:50.484   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-08 18:23:50.484   315  6999 V OMXCodec: allocateBuffers
09-08 18:23:50.484   315  6999 V OMXCodec: allocateBuffersOnPort portIndex=0
09-08 18:23:50.485   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-08 18:23:50.485   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
09-08 18:23:50.485   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
09-08 18:23:50.485   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
09-08 18:23:50.485   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
,09-08 18:23:50.486   315  6999 V OMXCodec: allocateBuffersOnPort portIndex=1
09-08 18:23:50.486   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-08 18:23:50.486   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-08 18:23:50.486   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
09-08 18:23:50.486   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
09-08 18:23:50.486   315  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on output port
09-08 18:23:50.486   315  6999 V OMXCodec: init() mAsyncCompletion wait!!! 
09-08 18:23:50.492   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,09-08 18:23:50.492   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-08 18:23:50.492   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-08 18:23:50.492   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-08 18:23:50.492   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-08 18:23:50.492   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-08 18:23:50.492   315  6999 V OMXCodec: init() mAsyncCompletion wait free! 
09-08 18:23:50.492   315  6999 V AwesomePlayer: finishAsyncPrepare_l() 
09-08 18:23:50.492   315  6999 V AudioCache: notify(0xb5474a80, 5, 0, 0)
09-08 18:23:50.492   315  6999 V AudioCache: ignored
,09-08 18:23:50.492   315  6999 V AudioCache: notify(0xb5474a80, 1, 0, 0)
09-08 18:23:50.492   315  6999 V AudioCache: prepared
09-08 18:23:50.492   315  2211 V AudioCache: wait - success
09-08 18:23:50.492   315  2211 V MediaPlayerService: start
09-08 18:23:50.492   315  2211 V AwesomePlayer: play_l() 
09-08 18:23:50.492   315  2211 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-08 18:23:50.493   315  2211 V AwesomePlayer: createAudioPlayer_l
09-08 18:23:50.493   315  2211 V AwesomePlayer: seekAudioIfNecessary_l() 
09-08 18:23:50.493   315  2211 V AwesomePlayer: startAudioPlayer_l() 
09-08 18:23:50.493   315  2211 D AudioPlayer: start of Playback, useOffload 0
,09-08 18:23:50.493   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-08 18:23:50.493   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-08 18:23:50.494   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-08 18:23:50.494   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-08 18:23:50.494   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-08 18:23:50.494   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-08 18:23:50.494   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-08 18:23:50.495   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,09-08 18:23:50.496   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
09-08 18:23:50.496   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 18:23:50.496   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048736
09-08 18:23:50.496   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 18:23:50.496   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048896
09-08 18:23:50.496   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975344
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0,
,09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-08 18:23:50.497   315  7001 V OMXCodec: allocateBuffersOnPort portIndex=1
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb16dd2e0 on output port
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-08 18:23:50.497   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-08 18:23:50.498   315  2211 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-08 18:23:50.498  6979  6979 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-08 18:23:50.498  6979  6979 D ProfileConfigQcom: Adding HeadsetService
09-08 18:23:50.499  6979  6979 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-08 18:23:50.499  6979  6979 D ProfileConfigQcom: Adding A2dpService
09-08 18:23:50.499  6979  6979 D ProfileConfigQcom: [BTUI] HidService is supported
09-08 18:23:50.499  6979  6979 D ProfileConfigQcom: Adding HidService
09-08 18:23:50.499  6979  6979 D ProfileConfigQcom: [BTUI] HealthService is supported
09-08 18:23:50.499  6979  6979 D ProfileConfigQcom: Adding HealthService
,09-08 18:23:50.499  6979  6979 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-08 18:23:50.500  6979  6979 D ProfileConfigQcom: [BTUI] PanService is supported
09-08 18:23:50.500  6979  6979 D ProfileConfigQcom: Adding PanService
09-08 18:23:50.500  6979  6979 D ProfileConfigQcom: [BTUI] GattService is supported
09-08 18:23:50.501  6979  6979 D ProfileConfigQcom: Adding GattService
09-08 18:23:50.501  6979  6979 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-08 18:23:50.501  6979  6979 D ProfileConfigQcom: Adding BluetoothMapService
09-08 18:23:50.501  6979  6979 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,09-08 18:23:50.502   315  2211 V AudioCache: notify(0xb5474a80, 6, 0, 0)
09-08 18:23:50.502   315  2211 V AudioCache: ignored
09-08 18:23:50.502   315  2211 V MediaPlayerService: wait for playback complete
09-08 18:23:50.502  6979  6979 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-08 18:23:50.503   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.503   315  7003 V AudioCache: memcpy(0xaf006000, 0xb1009000, 4096)
09-08 18:23:50.505   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.505   315  7003 V AudioCache: memcpy(0xaf007000, 0xb1009000, 4096)
09-08 18:23:50.506   315  7003 V AudioCache: write(0xb1009000, 4096)
,09-08 18:23:50.506   315  7003 V AudioCache: memcpy(0xaf008000, 0xb1009000, 4096)
09-08 18:23:50.506   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.506   315  7003 V AudioCache: memcpy(0xaf009000, 0xb1009000, 4096)
09-08 18:23:50.507   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.507   315  7003 V AudioCache: memcpy(0xaf00a000, 0xb1009000, 4096)
09-08 18:23:50.507   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.507   315  7003 V AudioCache: memcpy(0xaf00b000, 0xb1009000, 4096)
09-08 18:23:50.508   315  7003 V AudioCache: write(0xb1009000, 4096)
,09-08 18:23:50.508   315  7003 V AudioCache: memcpy(0xaf00c000, 0xb1009000, 4096)
09-08 18:23:50.508   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.508   315  7003 V AudioCache: memcpy(0xaf00d000, 0xb1009000, 4096)
09-08 18:23:50.509   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.509   315  7003 V AudioCache: memcpy(0xaf00e000, 0xb1009000, 4096)
09-08 18:23:50.509   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.509   315  7003 V AudioCache: memcpy(0xaf00f000, 0xb1009000, 4096)
09-08 18:23:50.510  6979  6979 V LGMDMManagerInternal: Create singleton instance
,09-08 18:23:50.510   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.510   315  7003 V AudioCache: memcpy(0xaf010000, 0xb1009000, 4096)
,09-08 18:23:50.510   315  7003 V AudioCache: write(0xb1009000, 4096)
,09-08 18:23:50.510   315  7003 V AudioCache: memcpy(0xaf011000, 0xb1009000, 4096)
09-08 18:23:50.510   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.510   315  7003 V AudioCache: memcpy(0xaf012000, 0xb1009000, 4096)
09-08 18:23:50.511   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.511   315  7003 V AudioCache: memcpy(0xaf013000, 0xb1009000, 4096)
09-08 18:23:50.511   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.511   315  7003 V AudioCache: memcpy(0xaf014000, 0xb1009000, 4096)
09-08 18:23:50.512   315  7003 V AudioCache: write(0xb1009000, 4096),
09-08 18:23:50.512   315  7003 V AudioCache: memcpy(0xaf015000, 0xb1009000, 4096)
09-08 18:23:50.512   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.512   315  7003 V AudioCache: memcpy(0xaf016000, 0xb1009000, 4096)
09-08 18:23:50.513   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.513   315  7003 V AudioCache: memcpy(0xaf017000, 0xb1009000, 4096)
09-08 18:23:50.513   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.513   315  7003 V AudioCache: memcpy(0xaf018000, 0xb1009000, 4096)
,09-08 18:23:50.514   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.514   315  7003 V AudioCache: memcpy(0xaf019000, 0xb1009000, 4096)
09-08 18:23:50.514   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.514   315  7003 V AudioCache: memcpy(0xaf01a000, 0xb1009000, 4096)
09-08 18:23:50.514   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.514   315  7003 V AudioCache: memcpy(0xaf01b000, 0xb1009000, 4096)
09-08 18:23:50.515   315  7003 V AudioCache: write(0xb1009000, 4096)
,09-08 18:23:50.515   315  7003 V AudioCache: memcpy(0xaf01c000, 0xb1009000, 4096)
09-08 18:23:50.515   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.515   315  7003 V AudioCache: memcpy(0xaf01d000, 0xb1009000, 4096)
09-08 18:23:50.516   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.516   315  7003 V AudioCache: memcpy(0xaf01e000, 0xb1009000, 4096)
09-08 18:23:50.516   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.516   315  7003 V AudioCache: memcpy(0xaf01f000, 0xb1009000, 4096)
09-08 18:23:50.517   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.517   315  7003 V AudioCache: memcpy(0xaf020000, 0xb1009000, 4096)
,09-08 18:23:50.517   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.517   315  7003 V AudioCache: memcpy(0xaf021000, 0xb1009000, 4096)
09-08 18:23:50.518   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.518   315  7003 V AudioCache: memcpy(0xaf022000, 0xb1009000, 4096)
09-08 18:23:50.518   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.518   315  7003 V AudioCache: memcpy(0xaf023000, 0xb1009000, 4096)
09-08 18:23:50.519   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.519   315  7003 V AudioCache: memcpy(0xaf024000, 0xb1009000, 4096)
,09-08 18:23:50.519   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.519   315  7003 V AudioCache: memcpy(0xaf025000, 0xb1009000, 4096)
09-08 18:23:50.519   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.519   315  7003 V AudioCache: memcpy(0xaf026000, 0xb1009000, 4096)
09-08 18:23:50.520   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.520   315  7003 V AudioCache: memcpy(0xaf027000, 0xb1009000, 4096)
09-08 18:23:50.520   315  7003 V AudioCache: write(0xb1009000, 4096)
,09-08 18:23:50.520   315  7003 V AudioCache: memcpy(0xaf028000, 0xb1009000, 4096)
09-08 18:23:50.521   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.521   315  7003 V AudioCache: memcpy(0xaf029000, 0xb1009000, 4096)
,09-08 18:23:50.521   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.521   315  7003 V AudioCache: memcpy(0xaf02a000, 0xb1009000, 4096)
09-08 18:23:50.522   315  7003 V AudioCache: write(0xb1009000, 4096)
,09-08 18:23:50.522   315  7003 V AudioCache: memcpy(0xaf02b000, 0xb1009000, 4096)
09-08 18:23:50.522   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.522   315  7003 V AudioCache: memcpy(0xaf02c000, 0xb1009000, 4096)
09-08 18:23:50.523   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.523   315  7003 V AudioCache: memcpy(0xaf02d000, 0xb1009000, 4096)
09-08 18:23:50.523  6818  6818 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-08 18:23:50.523   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.523   315  7003 V AudioCache: memcpy(0xaf02e000, 0xb1009000, 4096)
09-08 18:23:50.524   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.524   315  7003 V AudioCache: memcpy(0xaf02f000, 0xb1009000, 4096)
09-08 18:23:50.524   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.524   315  7003 V AudioCache: memcpy(0xaf030000, 0xb1009000, 4096)
09-08 18:23:50.525   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.525   315  7003 V AudioCache: memcpy(0xaf031000, 0xb1009000, 4096)
09-08 18:23:50.525   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.525   315  7003 V AudioCache: memcpy(0xaf032000, 0xb1009000, 4096)
09-08 18:23:50.525   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.525   315  7003 V AudioCache: memcpy(0xaf033000, 0xb1009000, 4096)
09-08 18:23:50.526   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.526   315  7003 V AudioCache: memcpy(0xaf034000, 0xb1009000, 4096)
09-08 18:23:50.526   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-08 18:23:50.526   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.526   315  7003 V AudioCache: memcpy(0xaf035000, 0xb1009000, 4096)
09-08 18:23:50.526   315  7003 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-08 18:23:50.526   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.526   315  7003 V AudioCache: memcpy(0xaf036000, 0xb1009000, 4096)
09-08 18:23:50.526   315  7003 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-08 18:23:50.526   315  7003 V AudioCache: write(0xb1009000, 4096)
09-08 18:23:50.526   315  7003 V AudioCache: memcpy(0xaf037000, 0xb1009000, 4096)
09-08 18:23:50.526   315  7003 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-08 18:23:50.526   315  7003 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-08 18:23:50.526   315  7003 V AwesomePlayer: postAudioEOS() 
09-08 18:23:50.526   315  7003 V AudioCache: write(0xb1009000, 280)
09-08 18:23:50.526   315  7003 V AudioCache: memcpy(0xaf038000, 0xb1009000, 280)
09-08 18:23:50.528   315  6999 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-08 18:23:50.528   315  6999 V AwesomePlayer: onStreamDone
09-08 18:23:50.528   315  6999 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-08 18:23:50.528   315  6999 V AudioCache: notify(0xb5474a80, 2, 0, 0)
09-08 18:23:50.528   315  6999 V AudioCache: playback complete
09-08 18:23:50.528   315  6999 V AwesomePlayer: pause_l() 
09-08 18:23:50.528   315  6999 V AudioCache: notify(0xb5474a80, 7, 0, 0)
09-08 18:23:50.528   315  6999 V AudioCache: ignored
09-08 18:23:50.528   315  6999 V AwesomePlayer: cancelPlayerEvents
09-08 18:23:50.528   315  6999 D AudioPlayer: Pause Playback at 1068125
09-08 18:23:50.528   315  2211 V AudioCache: wait - success
09-08 18:23:50.528   315  2211 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-08 18:23:50.528   315  2211 V AwesomePlayer: reset_l() 
09-08 18:23:50.528   315  2211 V AudioCache: notify(0xb5474a80, 8, 0, 0)
09-08 18:23:50.528   315  2211 V AudioCache: ignored
09-08 18:23:50.528   315  2211 V AwesomePlayer: cancelPlayerEvents
09-08 18:23:50.529   315  2211 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffloa,d=0
09-08 18:23:50.529   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-08 18:23:50.529   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-08 18:23:50.529   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-08 18:23:50.529   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb16dd2e0 on port 1
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fba0 on port 1
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fc40 on port 1
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 18:23:50.529   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-08 18:23:50.530   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-08 18:23:50.530   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-08 18:23:50.530   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-08 18:23:50.530   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-08 18:23:50.530   315  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-08 18:23:50.530   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-08 18:23:50.530   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-08 18:23:50.530   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-08 18:23:50.532   315  2211 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-08 18:23:50.532   315  2211 D AudioPlayer: AudioPlayer releasing audio source
,09-08 18:23:50.532   315  2211 D AudioPlayer: AudioPlayer done releasing audio source
09-08 18:23:50.532   315  2211 V AwesomePlayer: reset_l() 
09-08 18:23:50.532   315  2211 V AwesomePlayer: cancelPlayerEvents
09-08 18:23:50.532   315  2211 V AwesomePlayer: ~AwesomePlayer call
09-08 18:23:50.532   315  2211 V AwesomePlayer: reset_l() 
09-08 18:23:50.532   315  2211 V AwesomePlayer: cancelPlayerEvents
09-08 18:23:50.532  6898  6998 V SoundPool: close(32)
09-08 18:23:50.532  6898  6998 V SoundPool: pointer = 0x9fff1000, size = 205080, sampleRate = 48000, numChannels = 2
,09-08 18:23:50.550  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-08 18:23:50.552  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-08 18:23:50.555  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8302
,09-08 18:23:50.564  6979  6979 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:50.567  6979  6979 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-08 18:23:50.567  6979  6979 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 18:23:50.568  6979  6979 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 18:23:50.568  6979  6979 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:50.569  6979  6979 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-08 18:23:50.575  6915  6915 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-08 18:23:50.803  6733  6733 I UEI.SmartControl: Supports setup maps: true
09-08 18:23:50.806  6733  6733 D UEI.SmartControl: QS start statue = true Error code = 0
,09-08 18:23:50.806  6733  6733 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-08 18:23:50.806  6733  6733 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-08 18:23:50.806  6733  6733 I UEI.SmartControl: ### init IR Blaster...
09-08 18:23:50.809  6733  6733 D serial_port: Configuring serial port
09-08 18:23:50.810  6733  6733 E UEI.SmartControl: UEIBLaster setting for 616
09-08 18:23:50.810  6733  6733 I UEI.SmartControl: Setting serial record hearder size = 2
09-08 18:23:50.810  6733  6733 I UEI.SmartControl: configuring settings for MAXQ616
09-08 18:23:50.810  6733  6733 I UEI.SmartControl: Get version...
09-08 18:23:50.829  6733  7005 D UEI.SmartControl: serial port data available: 21
,09-08 18:23:50.855  6733  6733 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-08 18:23:50.856  6733  6733 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-08 18:23:50.856  6733  6733 I UEI.SmartControl: QS saving settings...
09-08 18:23:50.858  6733  6733 D UEI.SmartControl: IR Blaster version: 25672567
,09-08 18:23:50.875  6733  7005 D UEI.SmartControl: serial port data available: 4
,09-08 18:23:50.908  6733  7014 I UEI.SmartControl: Device manager: loading config....
09-08 18:23:50.909  6733  7014 D UEI.SmartControl: ----------- loading internal config...
09-08 18:23:50.910  6733  6733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-08 18:23:50.914  6733  6733 E UEI.SmartControl: Services init done
09-08 18:23:50.914  6733  6733 D UEI.SmartControl: QS Service init finished
09-08 18:23:50.919  6733  6733 D UEI.SmartControl: QS Service version name: 2.1.91
09-08 18:23:50.919  6733  6733 D UEI.SmartControl: QS Service version code: 201091
09-08 18:23:50.920  6733  6733 D UEI.SmartControl: Service requested: Control
09-08 18:23:50.927  6733  7014 E UEI.SmartControl: Loading SETTINGS...
,09-08 18:23:50.931  6733  6733 D UEI.SmartControl: Request IControl service: devices are loaded...
09-08 18:23:50.934  6898  6898 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-08 18:23:50.936  6733  6748 I UEI.SmartControl: ------ IControl API: 11
09-08 18:23:50.936  6733  6748 D UEI.SmartControl: File observer start...
09-08 18:23:50.936  6733  6748 E UEI.SmartControl: IR Port is disabled: false
09-08 18:23:50.936  6733  6748 D UEI.SmartControl: Starting file observer...
09-08 18:23:50.936  6733  6748 I UEI.SmartControl: Registering callback...
09-08 18:23:50.937  6733  6749 I UEI.SmartControl: ------ IControl API: 19
09-08 18:23:50.938  6733  6749 I UEI.SmartControl: Registering Services Ready callback...
09-08 18:23:50.938  6733  6733 D UEI.SmartControl: Internal service binding...
09-08 18:23:50.939  6733  7014 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-08 18:23:50.946  6733  7013 I UEI.SmartControl: Notify AllClients services are ready: 0
09-08 18:23:50.948  6733  7013 D UEI.SmartControl: -----service ready thread exits
,09-08 18:23:50.950  6898  6914 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-08 18:23:50.951  6898  6996 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-08 18:23:50.951  6898  6996 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-08 18:23:50.952  6898  6898 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-08 18:23:50.952  6898  6898 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-08 18:23:50.952  6733  6748 I UEI.SmartControl: ------ IControl API: 8
09-08 18:23:50.954  6898  6898 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-08 18:23:50.954  6898  6898 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-08 18:23:50.955  6898  6898 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-08 18:23:50.955  6898  6898 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-08 18:23:50.956  6898  6898 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-08 18:23:50.956  6898  6898 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-08 18:23:50.957  6898  6898 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-08 18:23:50.961  6898  6898 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-08 18:23:50.964  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-08 18:23:50.965  6898  6898 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 18:23:50.965  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-08 18:23:50.966  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-08 18:23:50.967  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-08 18:23:50.968  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-08 18:23:50.969  6898  6898 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473351830968]
09-08 18:23:50.970  6898  6898 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-08 18:23:50.972  1036  1986 I ActivityManager: Killing 6052:com.android.gallery3d/u0a27 (adj 15): empty #17
09-08 18:23:50.994  6898  7016 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-08 18:23:51.002  1036  1986 I ActivityManager: Killing 6530:com.lge.email/u0a23 (adj 15): empty #18
09-08 18:23:51.033  1036  1051 W libprocessgroup: failed to open /acct/uid_10027/pid_6052/cgroup.procs: No such file or directory
,09-08 18:23:51.041  1036  2033 W libprocessgroup: failed to open /acct/uid_10023/pid_6530/cgroup.procs: No such file or directory
,09-08 18:23:51.042  6898  6898 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-08 18:23:51.044  6898  6898 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 18:23:51.045  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-08 18:23:51.045  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-08 18:23:51.046  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-08 18:23:51.047  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-08 18:23:51.047  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-08 18:23:51.064  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-08 18:23:51.553  2213  2213 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19978
,09-08 18:23:51.916  1036  1941 D WifiServiceImplEx: setWifiEnabled: true pid=6609, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 18:23:51.917  1036  1941 D WifiService: setWifiEnabled: true pid=6609, uid=10118
09-08 18:23:51.917  1036  1941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:23:51.940  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 18:23:51.940  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 18:23:51.940  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,09-08 18:23:51.944  1036  1436 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-08 18:23:51.944  1036  1436 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-08 18:23:51.947  1036  1436 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-08 18:23:51.947  1036  1436 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 18:23:51.947  1036  1436 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-08 18:23:51.947  1036  1436 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 18:23:51.947  1036  1436 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-08 18:23:51.947  1036  1436 E WifiHW  : unknown target_country: EU , set to default
09-08 18:23:51.947  1036  1436 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-08 18:23:51.947  1036  1436 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-08 18:23:51.947  1036  1436 I WifiUtil: gEnableBmps=1
09-08 18:23:51.948  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:51.953  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,09-08 18:23:51.964  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.966  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:51.971  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:51.977  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-08 18:23:51.987  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:51.991  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.991  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:51.993  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-08 18:23:51.996  6435  6469 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 18:23:52.007  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-08 18:23:52.017  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-08 18:23:52.038  2082  2082 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:52.077  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:52.108  1036  2028 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7035 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-08 18:23:52.116  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:52.116  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 18:23:52.183  7035  7035 I AppUp4:AppBoxCP: onCreate
09-08 18:23:52.184  7035  7035 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-08 18:23:52.194  7035  7035 I AppUp4:DB:  setFingerPrint start
,09-08 18:23:52.194  7035  7035 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-08 18:23:52.203  7035  7035 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-08 18:23:52.203  7035  7035 I AppUp4:DB:  SDK version = 21
,09-08 18:23:52.204  7035  7035 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-08 18:23:52.206  7035  7035 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-08 18:23:52.208  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-08 18:23:52.208  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:52.211  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,09-08 18:23:52.211  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 18:23:52.219  7035  7035 I AppUp4:CustModeStarterReceiver: onReceive
,09-08 18:23:52.265  7035  7035 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 18:23:52.265  7035  7035 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:23:52.275  7035  7035 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18cc269a
09-08 18:23:52.275  7035  7035 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 18:23:52.276  7035  7035 D AppUp4:CustFacade: isPhone : true
09-08 18:23:52.277  7035  7035 D AppUp4:CustModeStarterReceiver: begin check event
09-08 18:23:52.278  7035  7035 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-08 18:23:52.278  7035  7035 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-08 18:23:52.280  7035  7055 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-08 18:23:52.281  7035  7055 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-08 18:23:52.281  7035  7055 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-08 18:23:52.285  1036  2028 I ActivityManager: Killing 6568:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-08 18:23:52.345  1036  1905 W libprocessgroup: failed to open /acct/uid_10061/pid_6568/cgroup.procs: No such file or directory
09-08 18:23:52.347  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:52.348  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-08 18:23:52.353  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:52.359  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:52.379  4291  7060 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 18:23:52.386  4291  7061 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:52.386  4291  7061 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 18:23:52.450  1036  2033 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7065 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-08 18:23:52.525  7065  7065 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:52.526  7065  7065 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 18:23:52.528  7065  7065 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 18:23:52.528  7065  7065 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-08 18:23:52.627  7065  7065 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-08 18:23:52.643  7065  7065 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-08 18:23:52.716   309   893 D SoftapController: Softap fwReload - Ok
,09-08 18:23:52.717  1036  1436 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (748ms)
,09-08 18:23:52.725  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:23:52.726   309   893 D CommandListener: Setting iface cfg
09-08 18:23:52.727   309   893 D CommandListener: Trying to bring down wlan0
09-08 18:23:52.727  1036  1118 D Tethering: InitialState.processMessage what=4
09-08 18:23:52.729  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:23:52.731   309   893 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:23:52.733  1036  1436 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-08 18:23:52.738  1036  1436 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 18:23:52.738  1036  1436 E WifiStateMachine: useWiFiOffloading() : false
09-08 18:23:52.738  1036  1436 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 18:23:52.740  7065  7065 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 18:23:52.732  7090  7090 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-08 18:23:52.745  1036  1436 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-08 18:23:52.745  1036  1436 D WifiMonitor: connecting to supplicant
09-08 18:23:52.732  7090  7090 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:52.757  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 18:23:52.759  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-08 18:23:52.760  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-08 18:23:52.761  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:52.762  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:52.782  7090  7090 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 18:23:52.809  7090  7090 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 18:23:52.810  7090  7090 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-08 18:23:52.810  7065  7065 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:23:52.811  7065  7065 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:23:52.880  7090  7090 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 18:23:52.923  7090  7090 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-08 18:23:52.926  7065  7065 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-08 18:23:52.927  7090  7090 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-08 18:23:52.928  1036  1436 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-08 18:23:52.932  1036  1436 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-08 18:23:52.932  1036  1436 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-08 18:23:52.932  1036  1436 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-08 18:23:52.933  1036  1436 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:52.933  1036  1436 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:52.933  1036  1436 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:52.934  1036  1436 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:52.935  1036  1436 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-08 18:23:52.935  1036  1436 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-08 18:23:52.935  1036  7104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-08 18:23:52.935  1036  7104 D WifiMonitor: Dropping event because (p2p0) is stopped
09-08 18:23:52.936  1036  1436 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-08 18:23:52.936  1036  1436 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-08 18:23:52.936  1036  1436 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-08 18:23:52.936  1036  1436 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 18:23:52.936  1036  1436 E WifiStateMachine: useWiFiOffloading() : false
09-08 18:23:52.936  1036  1436 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 18:23:52.936  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:52.936  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:52.936  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:52.937  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:52.937  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 18:23:52.937  1036  1436 D WifiNative-wlan0: doBoolean: SET update_config 1
09-08 18:23:52.937  1036  1436 D WifiNative-wlan0: SET update_config 1: returned true
09-08 18:23:52.937  1036  1436 D WifiConfigStore: Loading config and enabling all networks 
09-08 18:23:52.937  1036  1436 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-08 18:23:52.937  1036  1436 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-08 18:23:52.938  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:52.938  1942  1942 D WfdService: Waiting for WifiP2p enabling
09-08 18:23:52.941  1036  1436 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-08 18:23:52.943  7090  7090 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-08 18:23:52.943  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-08 18:23:52.943  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 18:23:52.943  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-08 18:23:52.943  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-08 18:23:52.943 , 1036  7104 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-08 18:23:52.943  1036  7104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,09-08 18:23:52.945  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:52.945  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:52.945  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:52.945  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:52.945  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:52.945  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:52.945  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:52.945  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:52.945  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:52.945  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:52.945  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:52.949  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-08 18:23:52.950  1036  1450 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-08 18:23:52.951  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:52.951  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:52.951  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:52.951  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:52.951  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:52.951  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:52.951  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:52.951  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:52.951  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:52.951  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:52.951  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:52.951  1036  1436 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-08 18:23:52.951  1036  1436 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-08 18:23:52.952  1036  1436 D WifiStateMachine: enableVerboseLogging : level 2
09-08 18:23:52.952  1036  1436 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-08 18:23:52.953  1036  1436 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-08 18:23:52.953  1036  1436 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-08 18:23:52.953  1036  1436 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-08 18:23:52.953  1036  1436 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-08 18:23:52.953  1036  1436 D Wif,iNative-wlan0: SET model_name LG-D855: returned true
09-08 18:23:52.954  1036  1436 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-08 18:23:52.954  1036  1436 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-08 18:23:52.954  1036  1436 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-08 18:23:52.954  1036  1436 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-08 18:23:52.954  1036  1436 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-08 18:23:52.955  1036  1436 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-08 18:23:52.955  1036  1436 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-08 18:23:52.955  1036  1436 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-08 18:23:52.957  7065  7065 I HubEmail: JNI_OnLoad()
09-08 18:23:52.957  7065  7065 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 18:23:52.958  7065  7065 I HubEmail: registerNatives()
09-08 18:23:52.958  7065  7065 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 18:23:52.958  7065  7065 I HubEmail: registerNativeMethods()
09-08 18:23:52.958  7065  7065 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 18:23:52.958  7065  7065 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-08 18:23:52.963  1036  1436 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 18:23:52.963  1036  1436 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-08 18:23:52.964  1942  1942 D WfdsService: Supplicant Connection state is changed : true
09-08 18:23:52.964  1036  1436 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-08 18:23:52.964  1036  1436 D WifiNative-HAL: Setting external_sim to 1
09-08 18:23:52.964  1036  1436 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-08 18:23:52.964  1942  2243 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-08 18:23:52.964  1942  2243 D WfdsService: Set the WFDS Monitor: true
09-08 18:23:52.964  1942  2243 D WfdsMonitor: WfdsMonitorThread create
09-08 18:23:52.964  1036  1436 D WifiNative-wlan0: SET external_sim 1: returned true
09-08 18:23:52.964  1036  1436 I WifiNative-HAL: startHal
09-08 18:23:52.964  1942  2243 D WfdsMonitor: WFDS Monitor is created and started
09-08 18:23:52.964  1942  2243 D WfdsService: WiFi: Supplicant connection re-established
09-08 18:23:52.964  1036  1436 D wifi    : setting scan oui 0xaf66c540
09-08 18:23:52.964  1036  1436 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 18:23:52.964  1036  1436 I WifiNative-HAL: startHal
09-08 18:23:52.964  1036  1436 D wifi    : setting scan oui 0xaf66c540
09-08 18:23:52.964  1036  1436 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-08 18:23:52.965  1036  1436 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-08 18:23:52.965  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-08 18:23:52.965  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
,09-08 18:23:52.966  1036  1436 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-08 18:23:52.966  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 18:23:52.966  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 18:23:52.966  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 18:23:52.966  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-08 18:23:52.966  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-08 18:23:52.967  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-08 18:23:52.967  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 18:23:52.967  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 18:23:52.967  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 18:23:52.967  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 18:23:52.967  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 18:23:52.967  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 18:23:52.967  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-08 18:23:52.968  7090  7090 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-08 18:23:52.968  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-08 18:23:52.968  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 18:23:52.968  1942  7109 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-08 18:23:52.968  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 18:23:52.968  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 18:23:52.968  3466  3466 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 18:23:52.968  3466  3466 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:52.968  1942  7109 E CtrlSupplicant: Succeed to open control connection
09-08 18:23:52.968  6935  7107 W FormManager: Network not available. Please check & try again.
09-08 18:23:52.969  3466  3466 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 18:23:52.969  1942  7109 E CtrlSupplicant: Succeed to open monitor connection
09-08 18:23:52.969  1942  7109 D WfdsMonitor: Supplicant connection established
09-08 18:23:52.969  1036  1436 E WifiNative: : [118,744,454 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-08 18:23:52.969  1036  1436 D WifiNative-wlan0: doBoolean: RECONNECT
09-08 18:23:52.969  1036  1436 D WifiNative-wlan0: RECONNECT: returned true
09-08 18:23:52.969  1036  1436 D WifiNative-wlan0: doString: [STATUS]
09-08 18:23:52.970  1942  2243 D WfdsService: Connected to the supplicant for wfds
09-08 18:23:52.970  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-08 18:23:52.970  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 18:23:52.970  1036  1436 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-08 18:23:52.970  1036  1436 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 18:23:52.971  1036  1436 D WifiNative-wlan0: SET ps 1: returned true
09-08 18:23:52.971  1036  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:23:52.974   309   893 D CommandListener: Setting iface cfg
09-08 18:23:52.974   309   893 D CommandListener: Trying to bring up p2p0
09-08 18:23:52.975  1036  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 18:23:52.975  1036  1390 D LGWifiP2pService: P2pEnablingState
,09-08 18:23:52.975  1036  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:52.975  1036  1390 D LGWifiP2pService: P2p socket connection successful
09-08 18:23:52.975  1036  1390 D LGWifiP2pService: P2pEnabledState
09-08 18:23:52.989  1036  2028 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7113 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-08 18:23:52.991  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 18:23:52.991  1036  1036 D RttService: SCAN_AVAILABLE : 3
09-08 18:23:52.991  1036  1559 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:52.992  1036  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:52.992  1036  1558 I WifiNative-HAL: startHal
09-08 18:23:52.992  1036  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf66c540
09-08 18:23:52.992  1036  1558 D wifi    : failed to get capabilities : -3
09-08 18:23:52.992  1036  1558 E WifiScanningService: could not get scan capabilities
09-08 18:23:52.992  1036  1390 D LGWifiP2pService: sending p2p connection changed broadcast
09-08 18:23:52.993  1036  1436 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-08 18:23:52.993  1036  1436 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-08 18:23:52.993  1036  1436 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-08 18:23:52.993  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-08 18:23:52.993  1942  1942 D WfdsService: WifiP2pState is changed : true
09-08 18:23:52.993  1942  2243 D WfdsService: Receive the WFDS_ENABLE Method
09-08 18:23:52.993  1036  1436 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-08 18:23:52.993  1942  2243 D WfdsService: Set the WFDS Monitor: true
09-08 18:23:52.993  1942  2243 D WfdsService: Connected to the supplicant for wfds
09-08 18:23:52.993  1942  2243 D WfdsJNI : doCommand: WFDS_SET TRUE
09-08 18:23:52.994  7090  7090 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-08 18:23:52.994  1036  1436 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=118769  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 18:23:52.994  1942  2243 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
09-08 18:23:52.994  7090  7090 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
09-08 18:23:52.994  1942  2243 D WfdsService: selectPreferredScanChannel [36]
09-08 18:23:52.994  1942  2243 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-08 18:23:52.995  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=118771  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 18:23:52.995  1036  1436 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-08 18:23:52.996  1036  1436 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-08 18:23:52.996  1036  1436 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-08 18:23:52.996  1036  1436 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-08 18:23:52.996  7090  7090 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-08 18:23:52.996  1036  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-08 18:23:52.996  1036  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-08 18:23:52.996  1036  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
09-08 18:23:52.997  1036  1390 D WifiNative-p2p0: SET device_name G3: returned true
09-08 18:23:52.997  1036  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-08 18:23:52.997  1036  1390 D LGWifiP2pService: before postfix = G3
09-08 18:23:52.997  1036  1390 D WifiServerServiceExt: postfix byte check : 2
09-08 18:23:52.997  1036  1390 D LGWifiP2pService: after postfix = G3
09-08 18:23:52.997  1036  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-08 18:23:52.997  1036  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-08 18:23:52.997  1036  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-08 18:23:52.997  1036  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-08 18:23:52.997  1036  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physi,cal_display keypad
09-08 18:23:52.998  1036  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-08 18:23:52.998  1036  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-08 18:23:52.998  6935  7108 V FormManager: Network unavailable.
09-08 18:23:52.998  1036  1436 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-08 18:23:52.998  1036  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-08 18:23:52.998  1036  1390 D WifiNative-HAL: p2pGetDeviceAddress
09-08 18:23:52.998  1036  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-08 18:23:52.999  7065  7110 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:52.999  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:52.999  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:23:53.000  1036  1436 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-08 18:23:53.000  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:53.001  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.001  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.001  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 18:23:53.001  1036  1436 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-08 18:23:53.001  1036  1436 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-08 18:23:53.002  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-08 18:23:53.002  1942  1942 D WfdsService: isConnected: false
09-08 18:23:53.002  7090  7090 E wpa_supplicant: disconnect_rssi_lvl: -100
09-08 18:23:53.002  1036  1436 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-08 18:23:53.003  1036  1436 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-08 18:23:53.003  1036  1436 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-08 18:23:53.003  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-08 18:23:53.003  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-08 18:23:53.004  7090  7090 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:23:53.004  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 18:23:53.004  7090  7090 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 18:23:53.004  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:23:53.004  7090  7090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.005  1036  7104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:23:53.005  1036  7104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:23:53.005  1036  7104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:23:53.005  1036  7104 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.005  1036  7104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.005  1036  7104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.005  1036  1436 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-08 18:23:53.005  7090  7090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.005  1036  1436 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-08 18:23:53.005  1036  1436 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-08 18:23:53.005  1036  7104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:23:53.006  1036  7104 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.006  1036  1436 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-08 18:23:53.006  1036  7104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.006  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-08 18:23:53.006  1036  7104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.006  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-08 18:23:53.006  7090  7090 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 18:23:53.006  1942  7109 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:23:53.006  1942  7109 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:23:53.006  1036  1436 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-08 18:23:53.006  1036  1436 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-08 18:23:53.006  1036  1436 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-08 18:23:53.007  1036  1436 D WifiNative-wlan0: doBoolean: SCAN
09-08 18:23:53.007  1036  1436 D WifiNative-wlan0: SCAN: returned false
09-08 18:23:53.007  1036  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-08 18:23:53.007  1036  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-08 18:23:53.007  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-08 18:23:53.007  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 18:23:53.007  1036  7104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 18:23:53.007  1036  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
09-08 18:23:53.007  1036  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-08 18:23:53.007  1036  7104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 18:23:53.007  1036  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-08 18:23:53.007  1036  1390 D WifiNative-p2p0: doString: ,[LIST_NETWORKS]
09-08 18:23:53.008  1036  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-08 18:23:53.008  1036  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-08 18:23:53.008  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
09-08 18:23:53.008  1036  1436 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=118784  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 18:23:53.009  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-08 18:23:53.009  1942  1942 D WfdsService: Update P2p Interface State: 3
09-08 18:23:53.010  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=118785  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 18:23:53.011  1036  1436 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 18:23:53.012  1036  1436 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 18:23:53.012  1036  1436 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 18:23:53.013  1036  1436 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 18:23:53.013  1036  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-08 18:23:53.013  1036  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-08 18:23:53.013  1036  1436 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 18:23:53.014  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.014  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.014  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 18:23:53.014  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:23:53.014  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 18:23:53.015  1036  1390 D LGWifiP2pService: InactiveState
09-08 18:23:53.015  1036  1390 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.015  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.015  1036  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,09-08 18:23:53.015  6935  7108 V FormManager: Network unavailable.
,09-08 18:23:53.015  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:23:53.015  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 18:23:53.016  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 18:23:53.016  7090  7090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:23:53.016  1036  7104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 18:23:53.016  1036  7104 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:23:53.016  1036  7104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:23:53.016  1036  7104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:23:53.017  7090  7090 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 18:23:53.017  7090  7090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.017  1036  7104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:23:53.017  1036  7104 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.017  1036  7104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.017  1036  7104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.018  7090  7090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.018  1942  7109 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 18:23:53.018  1942  7109 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:23:53.018  1036  7104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:23:53.018  1036  7104 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.018  1942  7109 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:23:53.018  1036  7104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.018  1036  7104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:23:53.019  1036  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-08 18:23:53.019  1036  1390 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.019  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.019  1036  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.019  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.019  1036  1390 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.019  1036  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.019  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.019  1036  1390 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.020  1036  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.020  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHa,ndler }
09-08 18:23:53.020  1036  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.020  1036  1699 I ActivityManager: Killing 6114:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-08 18:23:53.020  1036  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.020  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.020  1036  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.020  1942  2243 W WfdsService: DefaultState - msg [9441285] is not handled
09-08 18:23:53.020  1036  1036 E WifiServerServiceExt: No p2p device connected
09-08 18:23:53.023  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:53.023  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:23:53.024  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:53.052  1036  1887 W libprocessgroup: failed to open /acct/uid_10080/pid_6114/cgroup.procs: No such file or directory
,09-08 18:23:53.112  7113  7113 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:23:53.112  7113  7113 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:23:53.115  7113  7113 D PhoneMonitor: Register our PhoneStateListener
09-08 18:23:53.129  7113  7113 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-08 18:23:53.130  7113  7113 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-08 18:23:53.154  7113  7113 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-08 18:23:53.156  7113  7113 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,09-08 18:23:53.157  7113  7113 D TelephonyAutoProfiling: [parse] Load xml
09-08 18:23:53.166  7113  7113 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-08 18:23:53.166  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-08 18:23:53.166  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-08 18:23:53.167  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-08 18:23:53.167  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-08 18:23:53.167  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-08 18:23:53.167  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-08 18:23:53.167  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-08 18:23:53.167  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-08 18:23:53.167  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-08 18:23:53.167  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-08 18:23:53.167  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-08 18:23:53.167  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-08 18:23:53.168  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-08 18:23:53.168  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-08 18:23:53.168  7113  7113 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-08 18:23:53.168  7113  7113 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-08 18:23:53.189  1036  1986 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7133 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 18:23:53.191  1036  1986 I ActivityManager: Killing 6143:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-08 18:23:53.192  7113  7113 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-08 18:23:53.245  1036  1941 W libprocessgroup: failed to open /acct/uid_10097/pid_6143/cgroup.procs: No such file or directory
,09-08 18:23:53.436  1036  1986 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7151 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-08 18:23:53.437  1036  1986 I ActivityManager: Killing 6684:com.lge.eula/1000 (adj 15): empty #17
09-08 18:23:53.504  1036  1988 W libprocessgroup: failed to open /acct/uid_1000/pid_6684/cgroup.procs: No such file or directory
,09-08 18:23:53.546  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-08 18:23:53.546  1036  7104 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-08 18:23:53.546  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-08 18:23:53.546  7090  7090 E wpa_supplicant: USIM:  scard_init function
09-08 18:23:53.546  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
09-08 18:23:53.546  1036  7104 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,09-08 18:23:53.547  7090  7090 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-08 18:23:53.547  1036  1436 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-08 18:23:53.548  1036  1436 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-08 18:23:53.548  1036  1436 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-08 18:23:53.548  1036  1436 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-08 18:23:53.549  1036  1436 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-08 18:23:53.549  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-08 18:23:53.549  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-08 18:23:53.564  1036  1436 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=119340  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-08 18:23:53.569  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:53.569  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:23:53.569  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.570  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.570  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 18:23:53.570  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=119346  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-08 18:23:53.570  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:53.572  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:23:53.572  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-08 18:23:53.640  1036  1699 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7171 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 18:23:53.642  1036  1699 I ActivityManager: Killing 6701:com.lge.bnr/1000 (adj 15): empty #17
,09-08 18:23:53.663  7090  7090 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 18:23:53.667  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-08 18:23:53.667  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-08 18:23:53.667  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-08 18:23:53.667  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-08 18:23:53.667  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 18:23:53.667  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 18:23:53.669  1036  1436 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=119445  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 18:23:53.670  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=119446  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 18:23:53.672  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 18:23:53.672  7090  7090 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 18:23:53.672  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 18:23:53.672  7090  7090 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 18:23:53.672  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-08 18:23:53.672  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 18:23:53.672  1036  7104 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 18:23:53.672  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-08 18:23:53.672  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 18:23:53.672  1036  7104 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 18:23:53.673  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 18:23:53.673  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 18:23:53.673  1036  1436 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119449
09-08 18:23:53.675  1036  1436 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119451
09-08 18:23:53.676  1036  1436 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119451
09-08 18:23:53.677  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119452
09-08 18:23:53.677  1036  1436 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119453
09-08 18:23:53.679  1036  1436 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=119454  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-08 18:23:53.713  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 18:23:53.713  1036  2028 W libprocessgroup: failed to open /acct/uid_1000/pid_6701/cgroup.procs: No such file or directory
,09-08 18:23:53.728  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.728  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.728  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 18:23:53.730  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:53.730  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 18:23:53.732  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:53.737  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.737  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.737  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-08 18:23:53.738  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=119514  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-08 18:23:53.739  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:23:53.739  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-08 18:23:53.741  1036  1436 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=119517  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 18:23:53.742  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=119518  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 18:23:53.743  1036  1436 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=119518
09-08 18:23:53.743  1036  1436 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=119519
09-08 18:23:53.744  1036  1436 D WifiNative-wlan0: doString: [STATUS]
09-08 18:23:53.744  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 18:23:53.744  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-08 18:23:53.746  1036  1436 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-08 18:23:53.748  1036  1436 I WifiServiceExtension: setVHTCapabilityType  : false
09-08 18:23:53.753  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:53.753  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:23:53.756  1036  1436 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-08 18:23:53.756  1036  1436 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-08 18:23:53.761  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.761  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.762  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 18:23:53.763  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:53.767  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.767  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.767  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 18:23:53.769  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:53.769  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:23:53.771  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:53.772  7171  7171 I art     : Almond Protected OAT
,09-08 18:23:53.775  1036  1436 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-08 18:23:53.775  1036  1436 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 18:23:53.775  1036  1436 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 18:23:53.775  1036  1484 D ConnectivityService: Got NetworkAgent Messenger
09-08 18:23:53.775  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 18:23:53.775  1036  1484 D ConnectivityService: NetworkAgent connected
09-08 18:23:53.776  1036  1436 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 18:23:53.776  1036  1436 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 18:23:53.783  1036  1436 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 18:23:53.783  1036  1436 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 18:23:53.783  1036  1436 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 18:23:53.783  1036  1436 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 18:23:53.783  1036  1436 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 18:23:53.784  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:53.784  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:23:53.786  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 18:23:53.787  1036  1436 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 18:23:53.789   309   893 D CommandListener: Setting iface cfg
09-08 18:23:53.792  1036  1436 E WifiStateMachine: Start Dhcp Watchdog 2
09-08 18:23:53.792  1036  7195 D DhcpStateMachine: StoppedState
09-08 18:23:53.793  1036  7195 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.793  1036  7195 D DhcpStateMachine: WaitBeforeStartState
09-08 18:23:53.793  1036  1436 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119569  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 18:23:53.794  1036  1436 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119570  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 18:23:53.795  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119570  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 18:23:53.795  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,09-08 18:23:53.796  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:53.796  1036  1436 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:53.796  1036  1436 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:53.797  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:53.797  1036  1436 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:53.798  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:23:53.798  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-08 18:23:53.799  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:23:53.799  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-08 18:23:53.800  1036  1436 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=119576  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 18:23:53.801  1036  1436 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=119576  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 18:23:53.801  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=119577  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 18:23:53.804  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:73073] from screen [on:0 period:178051275] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 18:23:53.805  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:178051277] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 18:23:53.805  1036  1436 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-08 18:23:53.809  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:53.809  1036  1484 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-08 18:23:53.810  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:53.810  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:53.811  1036  1436 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:53.811  1036  1436 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:53.812  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:53.813  1036  1436 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:53.813  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-08 18:23:53.813  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=119,0,0
09-08 18:23:53.814  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=119,0,0
09-08 18:23:53.814  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-08 18:23:53.814  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-08 18:23:53.815  1036  1436 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-08 18:23:53.815  1036  1436 D WifiNative-wlan0: doBoolean: SET ps 0
09-08 18:23:53.815  1036  1436 D WifiNative-wlan0: SET ps 0: returned true
09-08 18:23:53.815  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-08 18:23:53.816  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-08 18:23:53.816  1036  1436 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-08 18:23:53.816  1036  1436 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-08 18:23:53.816  1036  1436 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 18:23:53.817  1036  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3af6a09e target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.817  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3af6a09e target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.817  1036  1436 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 18:23:53.817  1036  7195 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.817  1036  7195 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-08 18:23:53.818   309   893 D CommandListener: Setting iface cfg
09-08 18:23:53.818   309   893 D CommandListener: Trying to bring up wlan0
09-08 18:23:53.820  1036  1436 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-08 18:23:53.822  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-08 18:23:53.822  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:53.823  1036  1436 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:53.823  1036  1436 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:53.824  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:53.824  1036  1436 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:53.825  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-08 18:23:53.826  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 18:23:53.826  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 18:23:53.827  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 18:23:53.827  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.827  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.827  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 18:23:53.827  1036  1436 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 18:23:53.827  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-08 18:23:53.827  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-08 18:23:53.828  1036  1436 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-08 18:23:53.828  1036  1436 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 18:23:53.828  7171  7171 D WeatherApplication: removeAccount
09-08 18:23:53.829  7171  7171 D WeatherApplication: Account.length = 0
09-08 18:23:53.830  7171  7171 E WeatherApplication: OPERATOR:OPEN
09-08 18:23:53.835  7171  7171 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:23:53
,09-08 18:23:53.837  7171  7171 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 18:23:53.837  7171  7171 D Weather.Utils: 2 : All the weather widget is gone.
09-08 18:23:53.839  7171  7171 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 18:23:53.842  7171  7171 D WeatherAncestor: connectivity changed - connection : true
09-08 18:23:53.843  7171  7171 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-08 18:23:53.844  1036  1436 D WifiNative-wlan0: SET ps 1: returned true
09-08 18:23:53.844  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-08 18:23:53.845  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 18:23:53.846  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,09-08 18:23:53.846  1036  1436 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 18:23:53.847  1036  1484 D ConnectivityService: ignoring duplicate network state non-change
09-08 18:23:53.849  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.849  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.849  1036  1390 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:53.849  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 18:23:53.850  1036  1484 D ConnectivityService: Adding iface wlan0 to network 101
09-08 18:23:53.851  7171  7171 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 18:23:53.851  7171  7171 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 18:23:53.851  7171  7171 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-08 18:23:53.853  1036  1436 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-08 18:23:53.859  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:23:53.859  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 18:23:53.862  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:53.862  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 18:23:53.863  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:53.867  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.867  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.867  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 18:23:53.871  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.871  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.871  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 18:23:53.871  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 18:23:53.873  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-08 18:23:53.874  7171  7171 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 18:23:53.874  7171  7171 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:23:53
09-08 18:23:53.875  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.875  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.875  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 18:23:53.876  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-08 18:23:53.879  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.880  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:53.880  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 18:23:53.884  1036  1484 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 18:23:53.884  1036  1484 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-08 18:23:53.885  1036  1484 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-08 18:23:53.885  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:53.885  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:23:53.886   309   893 E Netd    : netlink response contains error (File exists)
09-08 18:23:53.886  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:53.886  1036  1484 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-08 18:23:53.887  1036  1484 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-08 18:23:53.887  1036  1484 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-08 18:23:53.888  1036  1484 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-08 18:23:53.888  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 18:23:53.888  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,09-08 18:23:53.888  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:53.891  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:53.891  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 18:23:53.892  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:53.900  1036  1436 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 18:23:53.901  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 18:23:53.901  1036  1436 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 18:23:53.902  1036  1436 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 18:23:53.902  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-08 18:23:53.903  1036  1436 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-08 18:23:53.926  1036  1959 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7199 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:53.927  1036  1959 I ActivityManager: Killing 2213:com.lge.music/u0a34 (adj 15): empty #17
09-08 18:23:53.951   315  1397 V AudioFlinger: 2213 died, releasing its sessions
09-08 18:23:53.952   315  1397 V AudioFlinger:  pid 1853 @ 0
09-08 18:23:53.952   315  1397 V AudioFlinger:  pid 3466 @ 1
09-08 18:23:53.952   315  1397 V AudioFlinger:  pid 3466 @ 2
,09-08 18:23:53.959   335   335 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 354us total 30.286ms
09-08 18:23:53.973   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 275us total 14.040ms
,09-08 18:23:53.987   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 267us total 12.852ms
,09-08 18:23:54.013  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 18:23:54.013  1036  1484 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 18:23:54.013  1036  1484 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-08 18:23:54.014  1036  1484 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-08 18:23:54.014  1036  1484 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:54.014  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:23:54.014  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 18:23:54.014  1036  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:54.014  1036  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-08 18:23:54.014  1036  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:54.014  1036  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-08 18:23:54.014  1036  1114 W ActivityManager: Failed to clear dns cache for: com.lge.music
,09-08 18:23:54.016  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:54.016  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-08 18:23:54.016  1036  1484 D ConnectivityService: currentScore = 0, newScore = 20
09-08 18:23:54.016  1036  1484 D ConnectivityService:    accepting network in place of null
09-08 18:23:54.016  1036  1484 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:54.017  1036  1436 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:54.017  1036  1436 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:54.017  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:54.018  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 18:23:54.018  1036  1484 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-08 18:23:54.018  1036  1484 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 18:23:54.019  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 18:23:54.019  1036  7195 D DhcpStateMachine: DHCPV4 request on wlan0
09-08 18:23:54.019  1036  7195 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-08 18:23:54.019  1036  7195 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-08 18:23:54.019   309  7217 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-08 18:23:54.002  7218  7218 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:54.012  7218  7218 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:54.028  7218  7218 I dhcpcd  : version 5.5.6 starting
09-08 18:23:54.029  7218  7218 E dhcpcd  : get_duid: m
09-08 18:23:54.029  7218  7218 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-08 18:23:54.029  7218  7218 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-08 18:23:54.031  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:54.031  1036  1051 W libprocessgroup: failed to open /acct/uid_10034/pid_2213/cgroup.procs: No such file or directory
09-08 18:23:54.031  1036  1484 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-08 18:23:54.032  1036  1484 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-08 18:23:54.033  1036  1484 D ConnectivityService: validation of new default Network = false
09-08 18:23:54.033  1036  1484 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-08 18:23:54.033  1036  1484 D DSQN    : enableDataServiceNotify 
09-08 18:23:54.033  1036  1484 D DSQN    : start dsqn bin
09-08 18:23:54.033  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-08 18:23:54.034  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 18:23:54.034  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 18:23:54.034  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 18:23:54.039  1036  1484 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-08 18:23:54.040  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:54.040  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:23:54.040  1036  1484 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-08 18:23:54.041  1605  2099 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 18:23:54.032  7220  7220 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:54.032  7220  7220 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:54.055  7220  7220 E DSQN    : DSQN ssw
,09-08 18:23:54.065  1036  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-08 18:23:54.070  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 18:23:54.071  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 18:23:54.072  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:54.077   309  7217 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-08 18:23:54.088  7218  7218 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 18:23:54.088  7218  7218 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 18:23:54.088  7218  7218 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 18:23:54.088  7218  7218 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-08 18:23:54.088  7218  7218 D dhcpcd  : wlan0: sending REQUEST (xid 0x34e73fae), next in 4.67 seconds
09-08 18:23:54.089  1818  7229 I CheckinService: active receiver: enabled
09-08 18:23:54.099  1818  7229 I CheckinService: Preparing to send checkin request
09-08 18:23:54.100  1818  7229 I EventLogService: Accumulating logs since 1473351772758
,09-08 18:23:54.107   309  7217 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-08 18:23:54.122  7218  7218 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-08 18:23:54.135   309   892 D LGDataListener: argv[0]=dsqncommand
09-08 18:23:54.135   309   892 D LGDataListener: argv[1]=wlan0
09-08 18:23:54.135   309   892 D LGDataListener: argv[2]=1
09-08 18:23:54.135   309   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,09-08 18:23:54.135  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
09-08 18:23:54.135  1036  1116 D DSQN    : start to monitor internet connection
09-08 18:23:54.142  7218  7218 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-08 18:23:54.142  1818  7229 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-08 18:23:54.142  7218  7218 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-08 18:23:54.142  7218  7218 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-08 18:23:54.142  7218  7218 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-08 18:23:54.143  7218  7218 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 18:23:54.143  7218  7218 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 18:23:54.143  7218  7218 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 18:23:54.143  7218  7218 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-08 18:23:54.157  1036  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 16:23:54 GMT], X-Android-Received-Millis=[1473351834157], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473351834134]}
09-08 18:23:54.158  1036  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 18:23:54.158  1036  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 18:23:54.158  1036  1484 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-08 18:23:54.158  1036  1484 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-08 18:23:54.158  1036  1484 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:54.158  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:23:54.158  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 18:23:54.158  1036  1484 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-08 18:23:54.158  1036  1484 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-08 18:23:54.158  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:54.158  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:23:54.159  1036  1484 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:23:54.160  1036  1484 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:54.160  1605  2099 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 18:23:54.160  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 18:23:54.160   278   449 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 18:23:54.160   278   449 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 18:23:54.160   278   449 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 18:23:54.161  1036  1436 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:54.161  1036  1436 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:54.161  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:54.161  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 18:23:54.161  7199  7235 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 18:23:54.167   278   449 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 18:23:54.167   278   449 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 18:23:54.167   278   449 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:54.170  7199  7235 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-08 18:23:54.177  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 18:23:54.179  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:54.179  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:54.181   278   449 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 18:23:54.181   278   449 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 18:23:54.181   278   449 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 18:23:54.181  7199  7242 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 18:23:54.183   278   449 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 18:23:54.183   278   449 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 18:23:54.183   278   449 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 18:23:54.184  7199  7242 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 18:23:54.264  1036  1628 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7252 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-08 18:23:54.310  7252  7252 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-08 18:23:54.310  7252  7252 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 18:23:54.332  7252  7252 I MultiDex: VM with version 2.1.0 has multidex support
09-08 18:23:54.332  7252  7252 I MultiDex: install
09-08 18:23:54.332  7252  7252 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-08 18:23:54.347  7252  7252 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-08 18:23:54.401  7199  7199 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-08 18:23:54.411  7199  7199 I LibraryLoader: Loading: webviewchromium
09-08 18:23:54.414  7199  7199 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 198-202)
09-08 18:23:54.414  7199  7199 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 18:23:54.422  1036  7195 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-08 18:23:54.423  1036  7195 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-08 18:23:54.423  1036  7195 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 18:23:54.423  1036  7195 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-08 18:23:54.423  1036  7195 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-08 18:23:54.423  1036  7195 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 18:23:54.423  1036  7195 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-08 18:23:54.423  1036  7195 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-08 18:23:54.424  1036  7195 D DhcpStateMachine: RunningState
09-08 18:23:54.424  7199  7199 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ee746d}
09-08 18:23:54.427  7199  7199 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 18:23:54.429  7199  7199 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 18:23:54.443  7199  7199 I BrowserStartupController: Initializing chromium process, renderers=0
,09-08 18:23:54.444  7199  7199 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 18:23:54.467  7199  7199 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-08 18:23:54.469  7199  7199 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-08 18:23:54.469  7199  7199 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-08 18:23:54.471   315   315 V AudioPolicyService: registerClient() client 0xb0410420, uid 10093
09-08 18:23:54.473  7199  7296 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 18:23:54.499  7199  7199 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 18:23:54.499  7199  7199 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 18:23:54.499  7199  7199 I Adreno-EGL: Build Date: 12/12/14 금
09-08 18:23:54.499  7199  7199 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 18:23:54.499  7199  7199 I Adreno-EGL: Remote Branch: 
09-08 18:23:54.499  7199  7199 I Adreno-EGL: Local Patches: 
09-08 18:23:54.499  7199  7199 I Adreno-EGL: Reconstruct Branch: 
,09-08 18:23:54.591  7199  7199 I NSApplication: Starting up...
,09-08 18:23:54.652  1036  2033 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7311 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-08 18:23:54.652  1036  2033 I ActivityManager: Killing 6076:com.android.vending/u0a44 (adj 15): empty #17
,09-08 18:23:54.658  7309  7309 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
09-08 18:23:54.703  1036  2028 W libprocessgroup: failed to open /acct/uid_10044/pid_6076/cgroup.procs: No such file or directory
,09-08 18:23:54.709  7309  7309 I dex2oat : dex2oat took 50.869ms (threads: 4)
09-08 18:23:54.725  7252  7270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 18:23:54.725  7252  7270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 18:23:54.725  7252  7270 I Adreno-EGL: Build Date: 12/12/14 금
09-08 18:23:54.725  7252  7270 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 18:23:54.725  7252  7270 I Adreno-EGL: Remote Branch: 
09-08 18:23:54.725  7252  7270 I Adreno-EGL: Local Patches: 
09-08 18:23:54.725  7252  7270 I Adreno-EGL: Reconstruct Branch: 
,09-08 18:23:54.733  7311  7311 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 18:23:54.833  1036  1436 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-08 18:23:54.833  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 18:23:54.833  1036  1436 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 18:23:54.834  1036  1436 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 18:23:54.834  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 18:23:54.834  1036  1436 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 18:23:54.835  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-08 18:23:54.835  1036  1484 D ConnectivityService: identical MTU - not setting
09-08 18:23:54.835  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 18:23:54.835  1036  1484 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 18:23:54.835  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:54.835  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:23:54.835  1036  1484 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:23:54.836  1605  2099 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 18:23:54.883  7252  7270 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:23:54.883  7252  7270 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:23:54.916  7252  7270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 18:23:54.916  7252  7270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 18:23:54.916  7252  7270 I Adreno-EGL: Build Date: 12/12/14 금
09-08 18:23:54.916  7252  7270 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 18:23:54.916  7252  7270 I Adreno-EGL: Remote Branch: 
09-08 18:23:54.916  7252  7270 I Adreno-EGL: Local Patches: 
09-08 18:23:54.916  7252  7270 I Adreno-EGL: Reconstruct Branch: 
,09-08 18:23:54.946  1036  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6609, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 18:23:54.946  1036  1051 D WifiService: setWifiEnabled: false pid=6609, uid=10118
09-08 18:23:54.946  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:23:54.962  1036  1436 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-08 18:23:54.963  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 18:23:54.963  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-08 18:23:54.963  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 18:23:54.963  1036  1436 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-08 18:23:54.963  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,09-08 18:23:54.966  1036  1436 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-08 18:23:54.966  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-08 18:23:54.966  1036  1436 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 18:23:54.966  1036  1436 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 18:23:54.966  1036  1436 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 18:23:54.967  1036  1436 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 18:23:54.967  1036  1436 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 18:23:54.973  1036  1436 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 18:23:54.973  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:54.973  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:54.974  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 18:23:54.974  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 18:23:54.974  1036  1436 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 18:23:54.974  1036  1436 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 18:23:54.975  1036  1436 D WifiNative-wlan0: SET ps 1: returned true
09-08 18:23:54.975  1036  7195 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:54.975   309   893 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:23:54.986  1036  1941 I art     : Explicit concurrent mark sweep GC freed 96306(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 5.159ms total 182.792ms
,09-08 18:23:55.013  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 18:23:55.013  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-08 18:23:55.020  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-08 18:23:55.020  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:55.020  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:55.020  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 18:23:55.022  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:55.022  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:23:55.023  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-08 18:23:55.023  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:55.029  1036  1036 D WifiHS20: hidePasspointNotification off =false
,09-08 18:23:55.036  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:55.036  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:55.036  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 18:23:55.037  1036  1436 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:55.037  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:55.037  1036  1436 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:55.037  1036  1436 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 18:23:55.038  1036  1436 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:55.038  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:55.038  1036  1436 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:23:55.039  1036  1390 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:55.039  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:55.039  1036  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2ec664c8
09-08 18:23:55.039  1036  1390 D LGWifiP2pService: P2pDisablingState
09-08 18:23:55.039  1036  1390 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:55.039  1036  1390 D LGWifiP2pService: p2p socket connection lost
09-08 18:23:55.040  1036  1390 D LGWifiP2pService: P2pDisabledState
09-08 18:23:55.041  7252  7270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 18:23:55.041  7252  7270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 18:23:55.041  7252  7270 I Adreno-EGL: Build Date: 12/12/14 금
09-08 18:23:55.041  7252  7270 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 18:23:55.041  7252  7270 I Adreno-EGL: Remote Branch: 
09-08 18:23:55.041  7252  7270 I Adreno-EGL: Local Patches: 
09-08 18:23:55.041  7252  7270 I Adreno-EGL: Reconstruct Branch: 
09-08 18:23:55.044  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
09-08 18:23:55.044  1036  1036 D RttService: SCAN_AVAILABLE : 1
09-08 18:23:55.044  1036  1558 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:55.044  1036  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:55.044  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-08 18:23:55.044  1942  1942 D WfdsService: WifiP2pState is changed : false
09-08 18:23:55.046  1942  2243 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-08 18:23:55.046  1942  2243 D WfdsService: Set the WFDS Monitor: false
,09-08 18:23:55.047  1942  2243 D WfdsMonitor: WFDS Monitor is stopped
09-08 18:23:55.047  1942  2243 D WfdsService: STATE : WfdsDisabledState - enter
09-08 18:23:55.047  1942  7109 D CtrlSupplicant: Received on exit socket, terminate
09-08 18:23:55.047  1942  7109 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-08 18:23:55.047  1942  7109 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-08 18:23:55.047  1942  7109 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-08 18:23:55.048  1942  2245 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-08 18:23:55.048  1942  2243 W WfdsService: DefaultState - msg [9445378] is not handled
09-08 18:23:55.050  1036  1436 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-08 18:23:55.050  1036  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:55.050  1036  1390 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:55.050  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 18:23:55.051  7090  7090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 18:23:55.051  1036  1436 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 18:23:55.051  1036  1436 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 18:23:55.051  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:55.051  1036  1436 D WifiNative-wlan0: SET ps 1: returned true
09-08 18:23:55.051  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:23:55.053  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:55.072   309   893 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:23:55.072  1036  1484 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-08 18:23:55.073  1036  1484 D DSQN    : disableDataServiceNotify
09-08 18:23:55.073  1036  1484 D DSQN    : stop dsqn bin
09-08 18:23:55.076  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 18:23:55.076  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 18:23:55.077  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-08 18:23:55.077  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:55.077  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:55.077  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 18:23:55.078  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:55.079  1036  1484 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-08 18:23:55.079  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:55.079  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:23:55.074  1036  1436 D WifiNative-p2p0: doBoolean: TERMINATE
09-08 18:23:55.079  1036  1484 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:23:55.080  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-08 18:23:55.080  1036  1436 D WifiNative-p2p0: TERMINATE: returned true
09-08 18:23:55.080  1036  1436 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 18:23:55.080  1036  1436 E WifiStateMachine: useWiFiOffloading() : false
09-08 18:23:55.080  1036  1436 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 18:23:55.080  1036  1484 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-08 18:23:55.080  1036  1484 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 18:23:55.080  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 18:23:55.080  1605  2099 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 18:23:55.081  1036  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:55.081  1036  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:55.081  1036  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-08 18:23:55.083  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:55.083  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 18:23:55.083  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:55.083  1036  1484 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:55.083  1036  1484 D, ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:55.083  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-08 18:23:55.083  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:23:55.083  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-08 18:23:55.085  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 18:23:55.088  1036  1484 D NetworkManagementService: Removing idletimer
09-08 18:23:55.088  1036  1484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:55.088  1036  1484 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-08 18:23:55.088  1036  1484 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-08 18:23:55.089  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:55.089  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 18:23:55.089  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,09-08 18:23:55.091  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 18:23:55.092  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 18:23:55.092  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 18:23:55.092  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 18:23:55.092  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 18:23:55.092  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 18:23:55.092  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 18:23:55.092  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 18:23:55.092  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 18:23:55.099  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:55.099  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:55.099  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:55.099  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:55.099  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:55.099  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:55.099  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:55.099  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:55.099  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:55.099  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:55.099  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:55.100  1036  1436 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:55.100  1036  1436 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:55.100  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:55.100  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:55.100  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:55.100  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:55.100  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:55.100  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:55.100  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:55.100  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to act,ive network: false
09-08 18:23:55.100  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:55.100  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:55.100  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:55.101  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 18:23:55.120  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 18:23:55.120  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:55.121  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 18:23:55.137  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 18:23:55.138  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:55.139  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:55.191  1036  7195 D DhcpStateMachine: StoppedState
,09-08 18:23:55.191  1036  7195 D DhcpStateMachine: StoppedState{ when=-141ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:55.192  1036  1436 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-08 18:23:55.193  1036  1436 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-08 18:23:55.214  7090  7090 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-08 18:23:55.214  7090  7090 I wpa_supplicant: monitor socket send errors count : 1
09-08 18:23:55.214  7090  7090 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-4\x00 that cannot receive messages
,09-08 18:23:55.217  1036  7104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-08 18:23:55.217  1036  7104 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-08 18:23:55.257  7090  7090 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 18:23:55.258  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-08 18:23:55.258  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 18:23:55.258  1036  7104 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 18:23:55.258  1036  7104 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-08 18:23:55.259  7090  7090 W wpa_supplicant: USIM:  scard_deinit function
09-08 18:23:55.259  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 18:23:55.259  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 18:23:55.259  1036  1118 D Tethering: InitialState.processMessage what=4
09-08 18:23:55.259  1036  1436 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121035
09-08 18:23:55.259  1036  1436 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121035
09-08 18:23:55.260  1036  1436 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=121035  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-08 18:23:55.260  1036  1436 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=121036  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,09-08 18:23:55.266  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-08 18:23:55.266  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:23:55.266  1036  1436 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:55.267  1036  1436 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:23:55.273  6435  6469 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-08 18:23:55.288  2082  2082 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:55.296  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-08 18:23:55.296  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:55.296  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 18:23:55.296  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 18:23:55.299  7035  7035 I AppUp4:CustModeStarterReceiver: onReceive
09-08 18:23:55.302  7035  7035 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18cc269a
09-08 18:23:55.302  7035  7035 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 18:23:55.302  7035  7035 D AppUp4:CustFacade: isPhone : true
09-08 18:23:55.302  7035  7035 D AppUp4:CustModeStarterReceiver: begin check event
09-08 18:23:55.302  7035  7035 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 18:23:55.306  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:55.306  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 18:23:55.307  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:55.310  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 18:23:55.316  4291  7359 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 18:23:55.317  7065  7065 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-08 18:23:55.319  4291  7360 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:55.319  4291  7360 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 18:23:55.334  7065  7362 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:55.342  3466  3466 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 18:23:55.342  6935  7364 W FormManager: Network not available. Please check & try again.
09-08 18:23:55.343  3466  3466 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:55.343  3466  3466 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 18:23:55.345  7113  7113 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 18:23:55.345  7113  7113 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-08 18:23:55.354  7171  7171 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:23:55
09-08 18:23:55.355  6935  7365 V FormManager: Network unavailable.
,09-08 18:23:55.357  7171  7171 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 18:23:55.357  7171  7171 D Weather.Utils: 2 : All the weather widget is gone.
09-08 18:23:55.357  7171  7171 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 18:23:55.357  7171  7171 D WeatherAncestor: connectivity changed - connection : true
09-08 18:23:55.357  7171  7171 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30448fa8
09-08 18:23:55.358  6935  7365 V FormManager: Network unavailable.
09-08 18:23:55.359  7171  7171 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 18:23:55.359  7171  7171 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 18:23:55.359  7171  7171 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 18:23:55.359  7171  7171 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 18:23:55.359  7171  7171 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:23:55
09-08 18:23:55.363  7090  7090 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-08 18:23:55.363  1036  7104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-08 18:23:55.363  1036  7104 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
09-08 18:23:55.363  1036  7104 D WifiMonitor: Disconnecting from the supplicant, no more events
09-08 18:23:55.364  1036  1436 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
09-08 18:23:55.380  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 18:23:55.380  6818  6818 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 18:23:55.380  6818  6818 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 18:23:55.380  6818  6818 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 18:23:55.381  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 18:23:55.381  6818  6818 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 18:23:55.381  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-08 18:23:55.381  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 18:23:55.381  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 18:23:55.381  6818  6818 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 18:23:55.381  6818  6818 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-08 18:23:55.388  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:23:55.391  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:55.396  6935  7368 W FormManager: Network not available. Please check & try again.
09-08 18:23:55.397  6935  7369 V FormManager: Network unavailable.
,09-08 18:23:55.398  6935  7369 V FormManager: Network unavailable.
09-08 18:23:55.400  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:55.410   309  7371 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-08 18:23:55.410  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-08 18:23:55.412  1818  7229 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-08 18:23:55.416  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:23:55.419  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:55.423  6935  7373 W FormManager: Network not available. Please check & try again.
,09-08 18:23:55.430  6935  7374 V FormManager: Network unavailable.
09-08 18:23:55.430  1818  7229 I CheckinService: active receiver: disabled
,09-08 18:23:55.433  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 18:23:55.441  6935  7374 V FormManager: Network unavailable.
09-08 18:23:55.451  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-08 18:23:55.451  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 18:23:55.453  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:55.455  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:55.457  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:55.458  4291  7375 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 18:23:55.458  4291  7376 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 18:23:55.458  4291  7376 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 18:23:55.461  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:55.465  1036  1436 D WifiOffDelayIfNotUsed: stopMonitoring
09-08 18:23:55.465  1036  1436 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 18:23:55.465  1036  1436 E WifiStateMachine: useWiFiOffloading() : false
09-08 18:23:55.465  1036  1436 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 18:23:55.465  1942  1942 D WfdsService: Supplicant Connection state is changed : false
09-08 18:23:55.465  1942  2243 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-08 18:23:55.465  1942  2243 D WfdsService: Set the WFDS Monitor: false
09-08 18:23:55.465  1942  2243 D WfdsMonitor: WFDS Monitor is stopped
09-08 18:23:55.466  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:23:55.467  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-08 18:23:55.469  2454  2454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:55.469  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-08 18:23:55.469  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:55.469  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:55.469  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:55.469  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:55.469  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:55.469  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:55.469  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:55.469  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:55.469  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:55.470  1036  1450 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-08 18:23:55.470  1036  1450 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-08 18:23:55.470  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:55.471  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:55.481  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:55.481  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:55.482  6898  6898 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 18:23:55.543  1036  1577 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7377 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-08 18:23:55.676  7377  7377 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-08 18:23:55.677  7377  7377 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-08 18:23:55.688  7377  7377 V [BNRBootReceiver]: Boot Receiver Return
09-08 18:23:55.689  7377  7377 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-08 18:23:55.695  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 18:23:55.707  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:55.718  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:55.726  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:55.727  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:55.732  6898  6898 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 18:23:55.741  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-08 18:23:55.745  6818  6818 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-08 18:23:55.754  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:55.766  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:55.779  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 18:23:55.794  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:55.794  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:55.795  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 18:23:55.802  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:55.817  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:55.831  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:55.845  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:55.846  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 18:23:55.846  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 18:23:55.857  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:55.871  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:55.877  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 18:23:55.887  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:55.888  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:55.888  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 18:23:55.897  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:55.908  6733  7015 D UEI.SmartControl: Internal timer expired: 2
09-08 18:23:55.909  6733  7015 D UEI.SmartControl: unbind internal service
,09-08 18:23:55.913  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 18:23:55.920  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:55.934  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:55.934  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:55.935  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 18:23:55.945  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:55.964  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:55.971  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:55.980  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:55.981  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:55.981  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 18:23:55.992  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:56.012  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:56.015  6733  7009 D serial_port: close(fd = 24)
09-08 18:23:56.020  6733  7009 I UEI.SmartControl: Serial port is closed.
,09-08 18:23:56.024  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:56.038  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:56.039  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 18:23:56.054  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 18:23:56.063  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 18:23:56.075  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:56.084  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:56.092  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 18:23:56.093  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:56.094  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 18:23:56.098  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:56.106  6847  6847 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-08 18:23:56.119  1036  1474 D WifiService: New client listening to asynchronous messages
09-08 18:23:56.120  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 18:23:56.126  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:56.137  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:56.151  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 18:23:56.152  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:56.154  6898  6898 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 18:23:56.157  6898  6898 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 18:23:56.158  6898  6898 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-08 18:23:56.168  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 18:23:56.180  6847  6847 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-08 18:23:56.184  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:23:56.192  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:56.205  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 18:23:56.220  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 18:23:56.220  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 18:23:56.223  6898  6898 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 18:23:56.224  6898  6898 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 18:23:56.225  6898  6898 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-08 18:23:56.230  1036  1905 I ActivityManager: Killing 6868:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-08 18:23:56.368  1036  1052 W libprocessgroup: failed to open /acct/uid_10037/pid_6868/cgroup.procs: No such file or directory
,09-08 18:23:56.375  2082  2082 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-08 18:23:56.386  2082  2082 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-08 18:23:56.387  2082  2082 D c       : Getting all permits...
09-08 18:23:56.387  2082  2082 D a       : Opening database...
,09-08 18:23:56.394  2082  2082 D a       : Opening database auth.proximity.permit_store...
09-08 18:23:56.395  2082  2082 D a       : Closing database...
09-08 18:23:56.407  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 18:23:56.414  6847  6847 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 18:23:56.414  6847  6847 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 18:23:56.414  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:23:56.417  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:56.425  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:56.434  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 18:23:56.435  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:56.437  6898  6898 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 18:23:56.441  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:56.446  6847  6847 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 18:23:56.446  6847  6847 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 18:23:56.446  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:23:56.451  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:56.461  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:56.471  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:56.471  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:56.474  6898  6898 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 18:23:56.479  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:23:56.483  6847  6847 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 18:23:56.484  6847  6847 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 18:23:56.484  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 18:23:56.493  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:23:56.500  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:56.507  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:23:56.508  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:23:56.511  6898  6898 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 18:23:56.521  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:23:56.525  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:56.534  6935  7405 W FormManager: Network not available. Please check & try again.
09-08 18:23:56.536  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:56.544  6935  7406 V FormManager: Network unavailable.
,09-08 18:23:56.551  6935  7406 V FormManager: Network unavailable.
09-08 18:23:56.555  2082  2082 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-08 18:23:56.574  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-08 18:23:56.574  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 18:23:56.575  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:56.578  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:56.587  6847  6847 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-08 18:23:56.587  6847  6847 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 18:23:56.587  6847  6847 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:23:56.588  4291  7407 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 18:23:56.592  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:56.597  4291  7408 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 18:23:56.597  4291  7408 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 18:23:56.598  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:23:56.608  6935  7410 W FormManager: Network not available. Please check & try again.
,09-08 18:23:56.616  6935  7411 V FormManager: Network unavailable.
09-08 18:23:56.618  6935  7411 V FormManager: Network unavailable.
,09-08 18:23:56.816  1036  1436 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:178054288] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 18:23:56.818  1036  1436 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:178054290] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 18:23:57.034  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:57.048  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-08 18:23:57.058  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:57.062  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:57.065  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:57.067  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-08 18:23:57.069  6435  6469 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 18:23:57.079  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-08 18:23:57.096  2082  2082 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:57.116  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 18:23:57.116  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:57.117  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 18:23:57.117  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-08 18:23:57.121  7035  7035 I AppUp4:CustModeStarterReceiver: onReceive
09-08 18:23:57.125  7035  7035 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18cc269a
09-08 18:23:57.125  7035  7035 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 18:23:57.125  7035  7035 D AppUp4:CustFacade: isPhone : true
09-08 18:23:57.126  7035  7035 D AppUp4:CustModeStarterReceiver: begin check event
09-08 18:23:57.126  7035  7035 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 18:23:57.131  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:57.131  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-08 18:23:57.136  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:57.139  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:57.146  7065  7065 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-08 18:23:57.193  4291  7433 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 18:23:57.194  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 18:23:57.200  7065  7432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:57.202  6935  7446 W FormManager: Network not available. Please check & try again.
09-08 18:23:57.206  4291  7448 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:57.206  4291  7448 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 18:23:57.211  3466  3466 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 18:23:57.211  3466  3466 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:57.211  3466  3466 I LgeMiscReceiver: networkInfo.isConnected() = true
09-08 18:23:57.211  3466  3466 D PhoneState: setPdpRejectCasuse : false
,09-08 18:23:57.216  7113  7113 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 18:23:57.216  7113  7113 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 18:23:57.217  6935  7447 V FormManager: Network unavailable.
09-08 18:23:57.230  7171  7171 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:23:57
,09-08 18:23:57.231  6935  7447 V FormManager: Network unavailable.
,09-08 18:23:57.233  7171  7171 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-08 18:23:57.233  7171  7171 D Weather.Utils: 2 : All the weather widget is gone.
,09-08 18:23:57.233  7171  7171 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-08 18:23:57.233  7171  7171 D WeatherAncestor: connectivity changed - connection : true
09-08 18:23:57.233  7171  7171 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30448fa8
09-08 18:23:57.234  7171  7171 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 18:23:57.234  7171  7171 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-08 18:23:57.234  7171  7171 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 18:23:57.234  7171  7171 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 18:23:57.234  7171  7171 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:23:57
09-08 18:23:57.959  1036  1628 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
09-08 18:23:57.960  1036  1628 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-08 18:23:57.991  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-08 18:23:57.994  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 18:23:57.994  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-08 18:23:57.995  1036  1118 D BluetoothManagerService: Message: 1
09-08 18:23:57.995  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-08 18:23:58.025  1036  1118 D BluetoothManagerService: Message: 20
09-08 18:23:58.025  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c9f7b3f:true
09-08 18:23:58.026  6979  6979 D BluetoothAdapterState: make
,09-08 18:23:58.033  6979  6979 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-08 18:23:58.033  6979  6979 I bluedroid-qcom: init
09-08 18:23:58.035  6979  7463 I BluetoothAdapterState: Entering OffState
09-08 18:23:58.035  6979  6979 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-08 18:23:58.035  6979  6979 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-08 18:23:58.036  6979  6979 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 18:23:58.036  6979  6979 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 18:23:58.036  6979  6979 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-08 18:23:58.037  6979  6979 I bluedroid-qcom: get_profile_interface socket
09-08 18:23:58.037  6979  6979 I bluedroid-qcom: get_profile_interface map_client
09-08 18:23:58.039  6979  7467 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-08 18:23:58.041  6979  7467 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-08 18:23:58.032  7466  7466 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:58.032  7466  7466 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:58.055  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-08 18:23:58.057  1036  1118 D BluetoothManagerService: Message: 40
09-08 18:23:58.057  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-08 18:23:58.059  6979  6994 I bluedroid-qcom: config_hci_snoop_log
09-08 18:23:58.060  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-08 18:23:58.060  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-08 18:23:58.063  7466  7466 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-08 18:23:58.063  7466  7466 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-08 18:23:58.063  7466  7466 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-08 18:23:58.068  7466  7466 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-08 18:23:58.076  7466  7466 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-08 18:23:58.076  7466  7466 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-08 18:23:58.078  6979  7463 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-08 18:23:58.080  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-08 18:23:58.080  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,09-08 18:23:58.083  6979  7467 D BluetoothAdapterProperties: Name is: G3
09-08 18:23:58.083  6979  7463 D BluetoothAdapterProperties: Setting state to 11
09-08 18:23:58.083  6979  7463 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-08 18:23:58.084  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.095  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:58.098  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.107  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:58.109  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-08 18:23:58.109  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-08 18:23:58.109  1036  1118 D BluetoothManagerService: Message: 60
09-08 18:23:58.109  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-08 18:23:58.109  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-08 18:23:58.110  6979  7463 I LGBluetoothServiceJni: classInitNative: succeeds
09-08 18:23:58.114  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-08 18:23:58.118  6435  6469 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 18:23:58.127  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.130  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:58.133  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:58.141  6979  7463 D BluetoothBondStateMachine: make
09-08 18:23:58.143  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-08 18:23:58.144  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:58.144  6979  7463 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:58.144  6979  7482 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 18:23:58.144  6979  7463 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-08 18:23:58.144  6979  7463 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:58.144  6979  7463 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,09-08 18:23:58.145  6979  7463 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-08 18:23:58.149  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 18:23:58.150  6818  6818 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-08 18:23:58.151  6979  7463 E BluetoothAdapterService: File transfer profiles supported!!
09-08 18:23:58.152  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:58.153  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:58.159  6979  6979 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-08 18:23:58.163  6979  6979 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:58.163  6979  6979 V BluetoothPbapReceiver: ***********state = 11
09-08 18:23:58.165  6979  7463 E BluetoothAdapterService: File transfer profiles supported!!
09-08 18:23:58.168  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-08 18:23:58.170  6979  6979 D HeadsetService: Received start request. Starting profile...
09-08 18:23:58.171  6979  6979 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 18:23:58.171  6979  6979 D LGBluetoothHfpAdapter: Version 1.6
09-08 18:23:58.173  6979  7463 E BluetoothAdapterService: File transfer profiles supported!!
09-08 18:23:58.174  6979  6979 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-08 18:23:58.175  6979  6979 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 18:23:58.176  6979  6979 D HeadsetStateMachine: make
,09-08 18:23:58.180  2082  2082 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:23:58.181  6979  7463 E BluetoothAdapterService: File transfer profiles supported!!
09-08 18:23:58.202  6979  7463 E BluetoothAdapterService: File transfer profiles supported!!
09-08 18:23:58.204  6979  6979 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:23:58.204  6979  6979 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:23:58.207  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.208  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:58.208  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:58.209  6979  6979 D HeadsetStateMachine: max_hf_connections = 1
09-08 18:23:58.209  6979  6979 I bluedroid-qcom: get_profile_interface handsfree
,09-08 18:23:58.210  6979  7463 E BluetoothAdapterService: File transfer profiles supported!!
09-08 18:23:58.212  6979  6979 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-08 18:23:58.213   315  1397 V AudioPolicyService: registerClient() client 0xb558a880, uid 1002
09-08 18:23:58.213   315   315 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-08 18:23:58.213   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 18:23:58.213   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 18:23:58.213  6979  6979 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-08 18:23:58.213   315  1398 V AudioFlinger: registerClient() client 0xb5581808, pid 6979
09-08 18:23:58.214   315  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:23:58.214   315  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 18:23:58.214  1036  1887 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:23:58.214  1036  1887 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 18:23:58.214   315  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:23:58.214   315  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 18:23:58.214  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:23:58.214  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 18:23:58.214  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:23:58.214  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 18:23:58.214  3466  3482 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:23:58.214  3466  3482 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 18:23:58.214  3466  3482 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:23:58.215  3466  3482 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 18:23:58.215  6979  6994 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:23:58.215  6979  6994 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-08 18:23:58.215  6979  6994 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:23:58.215  6979  6994 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-08 18:23:58.215  1605  2135 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:23:58.215  1605  2135 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 18:23:58.215  1605  2135 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:23:58.215  1605  2135 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 18:23:58.215  1036  2033 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:23:58.215  1036  2033 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 18:23:58.215  6979  6979 V ToneGenerator: Create Track: 0xb4928a80
09-08 18:23:58.215  6979  6979 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-08 18:23:58.215  6979  6979 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-08 18:23:58.215   315  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-08 18:23:58.215   315  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-08 18:23:58.215   315  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 18:23:58.215   315  1397 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 18:23:58.216   315  2211 I AudioFlinger: isAudioPlaybackHookOn() false
09-08 18:23:58.216   315  1398 V AudioPolicyManager: getOutputForAttr() ,usage=3, content=4, tag= flags=00000000
09-08 18:23:58.216   315  1398 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-08 18:23:58.216   315  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 18:23:58.216   315  1398 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 18:23:58.216  6979  6979 V AudioSystem: getLatency() output 2, latency 50
09-08 18:23:58.216  6979  6979 V AudioSystem: getFrameCount() output 2, frameCount 960
09-08 18:23:58.216  6979  6979 V AudioTrack: createTrack_l() output 2 afLatency 50
09-08 18:23:58.217   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-08 18:23:58.217   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-08 18:23:58.217   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-08 18:23:58.217   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-08 18:23:58.217   315   315 V AudioFlinger: createTrack() lSessionId: 20
09-08 18:23:58.217  6979  6979 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-08 18:23:58.218   315   315 V AudioFlinger: acquiring 20 from 6979, for 6979
09-08 18:23:58.218   315   315 V AudioFlinger:  added new entry for 20
09-08 18:23:58.218  6979  6979 V ToneGenerator: ToneGenerator INIT OK, time: 124006
09-08 18:23:58.218  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:58.219  6979  7485 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-08 18:23:58.219  6979  7485 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 18:23:58.219  6979  7485 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 18:23:58.219  6979  7485 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-08 18:23:58.220   315  1398 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6979
,09-08 18:23:58.220   315  1398 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-08 18:23:58.220   315  1398 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-08 18:23:58.220   315  1398 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-08 18:23:58.220   315  1398 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-08 18:23:58.220   315  1398 V voice   : voice_set_parameters: exit with code(0)
09-08 18:23:58.220   315  1398 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-08 18:23:58.220   315  1398 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-08 18:23:58.220   315  1398 V msm8974_platform: platform_set_parameters: exit with code(0)
09-08 18:23:58.220   315  1398 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-08 18:23:58.220   315  1398 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-08 18:23:58.220   315  1398 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-08 18:23:58.221  6979  7485 V ToneGenerator: ToneGenerator destructor
09-08 18:23:58.221  6979  7485 V ToneGenerator: stopTone
09-08 18:23:58.221  6979  7485 V ToneGenerator: Delete Track: 0xb4928a80
09-08 18:23:58.221  6979  7485 V AudioTrack: ~AudioTrack, releasing session id from 6979 on behalf of 6979
09-08 18:23:58.221   315  2211 V AudioPolicyService: AudioCommandThread() adding release output 2
09-08 18:23:58.221   315  2211 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-08 18:23:58.221   315  2211 V AudioFlinger: PlaybackThread::Track destructor
09-08 18:23:58.221   315  1273 V AudioPolicyService: AudioCommandThread() waking up
09-08 18:23:58.221   315  1398 V AudioFlinger: releasing 20 from 6979 for 6979
09-08 18:23:58.221   315  1398 V AudioFlinger:  decremented refcount to 0
09-08 18:23:58.221   315  2211 V AudioFlinger: removeClient_l() pid 6979, calling pid 315
09-08 18:23:58.221   315  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
09-08 18:23:58.221   315  1398 V AudioFlinger: purging stale effects
09-08 18:23:58.221   315  1273 V AudioPolicyManager: releaseOutput() 2
09-08 18:23:58.221   315  1273 V AudioPolicyService: AudioCommandThread() going to sleep
09-08 18:23:58.225  1036  1941 W Process : Unable to open /proc/7487/status
09-08 18:23:58.241  1036  1988 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7488 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:58.243  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:58.245  6979  6979 D A2dpService: Received start request. Starting profile...
09-08 18:23:58.245  6979  6979 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 18:23:58.246  6979  6979 V Avrcp   : make
09-08 18:23:58.246  6979  6979 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-08 18:23:58.246  6979  6979 I bluedroid-qcom: get_profile_interface avrcp
09-08 18:23:58.249  6979  7463 E BluetoothAdapterService: File transfer profiles supported!!
09-08 18:23:58.261  6979  6979 V AudioManager: registerRemoteController: size of Media player list: 0
,09-08 18:23:58.265  6979  6979 E AudioManager: No RCC entry present to update
09-08 18:23:58.265  6979  6979 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-08 18:23:58.266  6979  7463 V LGMDMManager: Create singleton instance
09-08 18:23:58.267  6979  7463 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-08 18:23:58.268  2082  2082 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.269  6979  6979 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-08 18:23:58.270  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-08 18:23:58.270  6979  6979 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-08 18:23:58.274  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 18:23:58.274  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.275  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 18:23:58.275  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 18:23:58.277  7035  7035 I AppUp4:CustModeStarterReceiver: onReceive
,09-08 18:23:58.278  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-08 18:23:58.282  7035  7035 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18cc269a
09-08 18:23:58.282  7035  7035 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 18:23:58.282  7035  7035 D AppUp4:CustFacade: isPhone : true
,09-08 18:23:58.314  7035  7035 D AppUp4:CustModeStarterReceiver: begin check event
,09-08 18:23:58.314  7035  7035 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-08 18:23:58.320  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.320  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 18:23:58.322  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:58.324  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:58.329  4291  7507 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 18:23:58.333  7065  7065 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-08 18:23:58.338  4291  7508 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.338  4291  7508 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 18:23:58.353  7065  7509 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:58.353  3466  3466 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 18:23:58.353  3466  3466 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.353  3466  3466 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 18:23:58.356  7113  7113 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 18:23:58.357  7113  7113 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 18:23:58.365  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
,09-08 18:23:58.365  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
09-08 18:23:58.368  6935  7511 W FormManager: Network not available. Please check & try again.
09-08 18:23:58.372  7171  7171 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:23:58
09-08 18:23:58.373  7171  7171 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 18:23:58.373  7171  7171 D Weather.Utils: 2 : All the weather widget is gone.
09-08 18:23:58.373  7171  7171 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 18:23:58.373  7171  7171 D WeatherAncestor: connectivity changed - connection : true
09-08 18:23:58.373  7171  7171 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30448fa8
09-08 18:23:58.374  7171  7171 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 18:23:58.374  7171  7171 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 18:23:58.374  7171  7171 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 18:23:58.374  7171  7171 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 18:23:58.374  7171  7171 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:23:58
09-08 18:23:58.377  6935  7512 V FormManager: Network unavailable.
,09-08 18:23:58.383  6935  7512 V FormManager: Network unavailable.
09-08 18:23:58.383  7488  7488 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-08 18:23:58.384  7488  7488 W LG Account v2.2: No ProfileInfo entries
09-08 18:23:58.384  7488  7488 I LG Account v2.2: isEnabled: false
09-08 18:23:58.384  7488  7488 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-08 18:23:58.384  7488  7488 I Feature : [Lifetracker]Country: EU
09-08 18:23:58.384  7488  7488 I Feature : [Lifetracker]Operator: OPEN
09-08 18:23:58.384  7488  7488 I Feature : [Lifetracker]Ranking support: false
09-08 18:23:58.384  7488  7488 I Feature : [Lifetracker]Comfort support: false
09-08 18:23:58.384  7488  7488 I Feature : [Lifetracker]Accessory: true
09-08 18:23:58.384  7488  7488 I Feature : [Lifetracker]Health device: true
09-08 18:23:58.384  7488  7488 I Feature : [Lifetracker]Extra Pedometer: false
09-08 18:23:58.384  7488  7488 I Feature : [Lifetracker]Blood glucose device: false
09-08 18:23:58.384  7488  7488 I Feature : [Lifetracker]Device Number: 3
09-08 18:23:58.395  6818  6818 D BluetoothPermissionRequest: onReceive
,09-08 18:23:58.400  6818  6818 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 18:23:58.407  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-08 18:23:58.409  6435  6469 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 18:23:58.425  2082  2082 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:58.433  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 18:23:58.433  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.433  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 18:23:58.433  7035  7035 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 18:23:58.434  7035  7035 I AppUp4:CustModeStarterReceiver: onReceive
09-08 18:23:58.437  7035  7035 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18cc269a
09-08 18:23:58.437  7035  7035 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 18:23:58.437  7035  7035 D AppUp4:CustFacade: isPhone : true
09-08 18:23:58.438  7035  7035 D AppUp4:CustModeStarterReceiver: begin check event
09-08 18:23:58.438  7035  7035 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 18:23:58.440  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.440  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-08 18:23:58.442  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:58.444  1036  2052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-08 18:23:58.445  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:23:58.450  7065  7065 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-08 18:23:58.453  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-08 18:23:58.453  4291  7518 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.453  4291  7518 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 18:23:58.457  4291  7517 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 18:23:58.458  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-08 18:23:58.459  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-08 18:23:58.459  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-08 18:23:58.459  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-08 18:23:58.459  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 18:23:58.459  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-08 18:23:58.459  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-08 18:23:58.459  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-08 18:23:58.459  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 18:23:58.459  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-08 18:23:58.460  6979  6979 I BluetoothA2dpServiceJni: classInitNative
09-08 18:23:58.460  6979  6979 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 18:23:58.460  6979  6979 D A2dpStateMachine: make
09-08 18:23:58.461  6979  6979 I bluedroid-qcom: get_profile_interface a2dp
09-08 18:23:58.461  6979  7521 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-08 18:23:58.465  6979  6979 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-08 18:23:58.465  6979  6979 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-08 18:23:58.466  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:58.467  6979  7520 D A2dpStateMachine: Enter Disconnected: -2
09-08 18:23:58.467  6979  6979 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 18:23:58.468  7065  7519 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:58.469  6979  6979 D HidService: Received start request. Starting profile...
09-08 18:23:58.469  6979  6979 I bluedroid-qcom: get_profile_interface hidhost
09-08 18:23:58.469  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:58.470  6979  6979 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 18:23:58.472  6979  6979 D HealthService: Received start request. Starting profile...
09-08 18:23:58.474  6979  6979 I bluedroid-qcom: get_profile_interface health
09-08 18:23:58.474  3466  3466 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 18:23:58.474  6979  6979 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-08 18:23:58.474  3466  3466 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:58.474  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:58.474  3466  3466 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 18:23:58.475  6979  6979 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 18:23:58.476  6935  7524 W FormManager: Network not available. Please check & try again.
09-08 18:23:58.476  6935  7525 V FormManager: Network unavailable.
09-08 18:23:58.477  6979  6979 D PanService: Received start request. Starting profile...
09-08 18:23:58.477  6979  6979 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 18:23:58.477  6979  6979 I bluedroid-qcom: get_profile_interface pan
09-08 18:23:58.480  7113  7113 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-08 18:23:58.482  7113  7113 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 18:23:58.482  6935  7525 V FormManager: Network unavailable.
09-08 18:23:58.483  6979  6979 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-08 18:23:58.483  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:58.483  6979  6979 D HeadsetStateMachine: Proxy object connected
09-08 18:23:58.484  6979  6979 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-08 18:23:58.484  6979  6979 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-08 18:23:58.488  6979  6979 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 18:23:58.488  6979  7485 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-08 18:23:58.489  6979  7485 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 18:23:58.489  6979  7485 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-08 18:23:58.489  6979  6979 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-08 18:23:58.494  6979  6979 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 18:23:58.495  6979  6979 D BtGatt.GattService: Received start request. Starting profile...
09-08 18:23:58.495  6979  6979 D BtGatt.GattService: start()
09-08 18:23:58.495  6979  6979 I bluedroid-qcom: get_profile_interface gatt
09-08 18:23:58.495  6979  6979 D BtGatt.AdvertiseManager: advertise manager created
09-08 18:23:58.500  7171  7171 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:23:58
09-08 18:23:58.502  7171  7171 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 18:23:58.502  7171  7171 D Weather.Utils: 2 : All the weather widget is gone.
09-08 18:23:58.503  7171  7171 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 18:23:58.503  7171  7171 D WeatherAncestor: connectivity changed - connection : true
09-08 18:23:58.503  7171  7171 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30448fa8
09-08 18:23:58.504  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:58.504  7171  7171 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 18:23:58.504  7171  7171 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 18:23:58.504  7171  7171 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 18:23:58.504  7171  7171 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 18:23:58.504  7171  7171 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:23:58
09-08 18:23:58.505  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
,09-08 18:23:58.506  6979  6979 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-08 18:23:58.507  6979  6979 V BluetoothMapService: BluetoothMapBinder()
09-08 18:23:58.507  6979  6979 D BluetoothMapService: Received start request. Starting profile...
09-08 18:23:58.507  6979  6979 D BluetoothMapService: start()
09-08 18:23:58.515  6979  6979 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-08 18:23:58.515  6979  6979 D BluetoothMapEmailAppObserver: createReceiver()
,09-08 18:23:58.518  6979  6979 D BluetoothMapEmailAppObserver: initObservers()
09-08 18:23:58.519  6979  6979 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-08 18:23:58.530  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
,09-08 18:23:58.534  6979  6979 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 18:23:58.539  6979  6979 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-08 18:23:58.543  6979  6979 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 18:23:58.543  6979  6979 V PanService: [BTUI] SIM Extra State :ABSENT
,09-08 18:23:58.548  6979  6979 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 18:23:58.552  6979  6979 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-08 18:23:58.552  6979  6979 V BluetoothMapService: Handler(): got msg=1
09-08 18:23:58.553  6979  7463 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-08 18:23:58.553  6979  7463 I bluedroid-qcom: enable
09-08 18:23:58.554  6979  7532 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-08 18:23:58.554  6979  7532 I bt-btu  : btu_task pending for preload complete event
09-08 18:23:58.554  6979  7463 I bt_hci_bdroid: init
09-08 18:23:58.556  6979  7463 I bt_vendor: bt-vendor : init
09-08 18:23:58.556  6979  7463 I bt_vendor: bt-vendor : get_bt_soc_type
,09-08 18:23:58.556  6979  7463 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-08 18:23:58.556  6979  7463 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-08 18:23:58.556  6979  7463 D bt_userial_mct: userial_init
,09-08 18:23:58.557  6979  6979 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:58.557  6979  7463 D bt_hci_bdroid: set_power 1
09-08 18:23:58.557  6979  7463 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-08 18:23:58.557  6979  7463 I bt_vendor: Starting hciattach daemon
09-08 18:23:58.557  6979  7463 I bt_vendor: try to set true
09-08 18:23:58.560  6979  6979 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 18:23:58.560  6979  6979 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 18:23:58.560  6979  6979 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 18:23:58.560  6979  6979 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:58.560  6979  6979 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-08 18:23:58.542  7535  7535 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:58.542  7535  7535 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:58.593  7536  7536 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-08 18:23:58.705  7542  7542 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-08 18:23:58.720  7543  7543 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-08 18:23:58.760  7545  7545 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-08 18:23:58.778  7546  7546 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-08 18:23:58.791  7550  7550 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-08 18:23:58.803  7551  7551 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-08 18:23:58.823  7553  7553 I libmdmdetect: ESOC framework not supported
09-08 18:23:58.824  7553  7553 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-08 18:23:58.831  7553  7553 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-08 18:23:58.831  7553  7553 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-08 18:23:58.831  7553  7553 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-08 18:23:58.831  7553  7553 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-08 18:23:58.831  7553  7553 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-08 18:23:58.831  7553  7553 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-08 18:23:58.831  7553  7553 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-08 18:23:58.863  1036  1114 W ProcessCpuTracker: Skipping unknown process pid 7547
,09-08 18:23:58.867  7553  7554 E QC-QMI  : qmi_client [7553] 14: failed to locate client data
09-08 18:23:58.868   434   434 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-08 18:23:58.868   434   434 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-08 18:23:58.915  7555  7555 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-08 18:23:58.943  7556  7556 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-08 18:23:58.961  6979  7463 I bt_vendor: bluetooth satus is on
09-08 18:23:58.961  6979  7463 D bt_hci_bdroid: preload
09-08 18:23:58.961  6979  7534 D bt_userial_mct: userial_open(port:0)
09-08 18:23:58.961  6979  7534 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-08 18:23:58.967  6979  7534 I bt_vendor: Done intiailizing UART
09-08 18:23:58.971  6979  7534 I bt_vendor: Done intiailizing UART
,09-08 18:23:58.971  6979  7534 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-08 18:23:58.972  6979  7534 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-08 18:23:58.972  6979  7532 I bt-btu  : btu_task received preload complete event
09-08 18:23:58.972  6979  7558 D bt_userial_mct: Entering userial_read_thread()
09-08 18:23:58.973  6979  7532 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-08 18:23:58.973  6979  7532 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,09-08 18:23:58.975  6979  7532 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-08 18:23:58.979  6979  7532 I         : BTE_InitTraceLevels -- TRC_HCI
09-08 18:23:58.979  6979  7532 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-08 18:23:58.979  6979  7532 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 18:23:58.979  6979  7532 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 18:23:58.979  6979  7532 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 18:23:58.979  6979  7532 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 18:23:58.980  6979  7532 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 18:23:58.980  6979  7532 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 18:23:58.980  6979  7532 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-08 18:23:58.980  6979  7532 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 18:23:58.980  6979  7532 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 18:23:58.980  6979  7532 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 18:23:58.980  6979  7532 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 18:23:58.980  6979  7532 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 18:23:58.980  6979  7532 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 18:23:58.980  6979  7532 I         : BTE_InitTraceLevels -- TRC_BTIF
09-08 18:23:59.066  6979  7532 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-08 18:23:59.066  6979  7532 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ff061 
09-08 18:23:59.066  6979  7532 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ff061 
,09-08 18:23:59.085  6979  7467 E bt-btif : Calling BTA_HhEnable
,09-08 18:23:59.085  6979  7532 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-08 18:23:59.085  6979  7532 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-08 18:23:59.085  6979  7532 W bt-l2cap: btif_storagA_Register() called for PSM: 0x001b
,09-08 18:23:59.085  6979  7467 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-08 18:23:59.085  6979  7532 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-08 18:23:59.085  6979  7532 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-08 18:23:59.086  6979  7467 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-08 18:23:59.088  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-08 18:23:59.088  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,09-08 18:23:59.089  6979  7467 D BluetoothAdapterProperties: Name is: G3
09-08 18:23:59.092  6979  7467 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:23:59.093  6979  7467 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:23:59.093  6979  7467 D bt_hci_bdroid: postload
09-08 18:23:59.093  6979  7534 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 18:23:59.094  6979  7532 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-08 18:23:59.095  6979  7467 D bte_conf: Device ID record 1 : primary
09-08 18:23:59.095  6979  7467 D bte_conf:   vendorId            = 00c4
09-08 18:23:59.095  6979  7467 D bte_conf:   vendorIdSource      = 0001
09-08 18:23:59.095  6979  7467 D bte_conf:   product             = 13a1
09-08 18:23:59.095  6979  7467 D bte_conf:   version             = 1000
09-08 18:23:59.095  6979  7467 D bte_conf:   clientExecutableURL = 
09-08 18:23:59.095  6979  7467 D bte_conf:   serviceDescription  = 
09-08 18:23:59.095  6979  7467 D bte_conf:   documentationURL    = 
09-08 18:23:59.095  6979  7467 D bte_conf: bte_load_did_conf no section named DID2.
09-08 18:23:59.096  6979  7534 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 18:23:59.096  6979  7534 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 18:23:59.097  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:59.097  6979  7467 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 18:23:59.098  6979  7463 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-08 18:23:59.082  7560  7560 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:59.098  6979  7463 D BluetoothAdapterProperties: ScanMode =  20
09-08 18:23:59.098  6979  7463 D BluetoothAdapterProperties: State =  11
09-08 18:23:59.098  6979  7534 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 18:23:59.098  6979  7534 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 18:23:59.098  6979  7463 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-08 18:23:59.098  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:59.099  6979  7463 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-08 18:23:59.099  6979  7463 D BluetoothAdapterProperties: Setting state to 12
,09-08 18:23:59.099  6979  7463 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 18:23:59.101  6979  7467 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-08 18:23:59.092  7560  7560 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:59.105  6979  7463 I BluetoothAdapterState: Entering On State
09-08 18:23:59.105  1036  1118 D BluetoothManagerService: Message: 60
09-08 18:23:59.105  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-08 18:23:59.108  6979  7532 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 18:23:59.108  6979  7532 W bt-smp  : Plain text(LSB ~ MSB) = c4 d3 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 18:23:59.108  6979  7532 W bt-smp  : Encrypted text(LSB ~ MSB) = 9a e3 76 04 f4 87 de 88 0d 44 84 40 f5 97 22 37 
09-08 18:23:59.108  6979  7532 W bt-btm  : Stopping oneshot timer
09-08 18:23:59.108  6979  7534 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 18:23:59.108  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-08 18:23:59.109  6818  6841 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 18:23:59.111  6979  7463 D LGBluetoothServiceAdapter: [BTUI] OnState
09-08 18:23:59.111  6979  7463 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-08 18:23:59.111  6979  7463 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-08 18:23:59.112  6979  7558 E bt_mct  : hci lib postload completed
09-08 18:23:59.114  1853  3988 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:23:59.116  6979  7463 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-08 18:23:59.119  1853  1853 D BluetoothHeadset: Proxy object connected
09-08 18:23:59.119  6818  6844 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 18:23:59.122  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:23:59.124  1036  1036 D BluetoothHeadset: Proxy object connected
09-08 18:23:59.124  6979  7467 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:23:59.125  6979  7467 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-08 18:23:59.125  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 18:23:59.126  6818  6818 D BluetoothInputDevice: Proxy object connected
09-08 18:23:59.127  6818  6818 D HidProfile: Bluetooth service connected
09-08 18:23:59.128  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:23:59.129  1853  1853 D BluetoothHeadset: Proxy object connected
09-08 18:23:59.129  6818  6844 D BluetoothPan: onBluetoothStateChange on: true
09-08 18:23:59.130  6818  6844 D BluetoothPan: onBluetoothStateChange call bindService
09-08 18:23:59.130  6979  7532 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 18:23:59.130  6979  7532 W bt-smp  : Plain text(LSB ~ MSB) = 7a 77 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 18:23:59.130  6979  7532 W bt-smp  : Encrypted text(LSB ~ MSB) = ad 7f 58 ed 9e 29 6b b6 a0 ee 71 70 74 ac 37 5a 
09-08 18:23:59.130  6979  7532 W bt-btm  : Stopping oneshot timer
09-08 18:23:59.131  1036  1036 D BluetoothA2dp: Proxy object connected
,09-08 18:23:59.139  6818  6844 D BluetoothMap: onBluetoothStateChange: up=true
09-08 18:23:59.141  6818  6818 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:23:59.141  6818  6818 D PanProfile: Bluetooth service connected
09-08 18:23:59.143  6979  7532 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 18:23:59.143  6979  7532 W bt-smp  : Plain text(LSB ~ MSB) = 9c 9f 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 18:23:59.143  6979  7532 W bt-smp  : Encrypted text(LSB ~ MSB) = 65 65 d0 db 7c 09 af 54 43 85 a9 5d e2 1c 20 af 
,09-08 18:23:59.143  6979  7532 W bt-btm  : Stopping oneshot timer
09-08 18:23:59.145  1853  3996 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:23:59.145  6818  6818 D BluetoothMap: Proxy object connected
09-08 18:23:59.145  6818  6818 D MapProfile: Bluetooth service connected
09-08 18:23:59.146  6818  6818 D BluetoothMap: getConnectedDevices()
09-08 18:23:59.147  6979  6995 V BluetoothMapService: getConnectedDevices()
09-08 18:23:59.148  1853  1853 D BluetoothHeadset: Proxy object connected
09-08 18:23:59.149  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-08 18:23:59.149  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-08 18:23:59.150  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-08 18:23:59.152  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-08 18:23:59.155  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:59.155  6979  7532 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 18:23:59.155  6979  7532 W bt-smp  : Plain text(LSB ~ MSB) = 04 79 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 18:23:59.155  6979  7532 W bt-smp  : Encrypted text(LSB ~ MSB) = 21 78 50 05 a7 bd 68 fc 6b 37 e9 18 66 51 05 f4 
09-08 18:23:59.155  6979  7532 W bt-btm  : Stopping oneshot timer
09-08 18:23:59.155  1942  2102 D LGBluetoothAPIService: Message: 1
09-08 18:23:59.156  1942  2102 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-08 18:23:59.161  6609  6609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-08 18:23:59.162  6979  7463 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-08 18:23:59.164  1036  1118 D BluetoothManagerService: Message: 40
09-08 18:23:59.164  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-08 18:23:59.167  6979  7532 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 18:23:59.167  6979  7532 W bt-smp  : Plain text(LSB ~ MSB) = 3b 51 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 18:23:59.167  6979  7532 W bt-smp  : Encrypted text(LSB ~ MSB) = 6e 71 e8 aa 07 f3 f1 32 7b 93 39 63 e8 23 35 20 
09-08 18:23:59.167  6979  7532 W bt-btm  : Stopping oneshot timer
,09-08 18:23:59.169  6979  6979 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:59.169  6979  6979 D BluetoothMapService: STATE_ON
09-08 18:23:59.169  6979  6979 V BluetoothMapService: Handler(): got msg=1
09-08 18:23:59.172  6979  6979 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-08 18:23:59.174  6979  7567 D BluetoothMapMasInstance: MAS initSocket()
09-08 18:23:59.175  6979  7567 D BluetoothMapMasInstance:   masId = 00
09-08 18:23:59.175  6979  7567 D BluetoothMapMasInstance:   msgTypes = 0e
09-08 18:23:59.175  6979  7567 D BluetoothMapMasInstance:   masName = SMS/MMS
09-08 18:23:59.175  6979  7567 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-08 18:23:59.175  7566  7566 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-08 18:23:59.180  1036  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-08 18:23:59.180  1942  2102 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-08 18:23:59.182  6818  6818 D LocalBluetoothProfileManager: Adding local A2DP profile
09-08 18:23:59.187  6979  7567 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:23:59.190  6979  7567 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-08 18:23:59.190  6979  7567 V BluetoothMapMasInstance: Succeed to create listening socket 
09-08 18:23:59.191  6979  7567 D BluetoothMapMasInstance: Accepting socket connection...
09-08 18:23:59.192  6979  7467 D BluetoothAdapterProperties: Scan Mode:21
09-08 18:23:59.192  6979  7467 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,09-08 18:23:59.197  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:59.197  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:59.197  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:59.197  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:59.197  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:59.197  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:59.197  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:59.197  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:59.198  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:59.199  6979  6979 V BluetoothPbapService: Pbap Service onCreate
09-08 18:23:59.199  6979  6979 V BluetoothPbapService: Starting PBAP service
09-08 18:23:59.199  1036  1118 D BluetoothManagerService: Message: 30
09-08 18:23:59.200  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:59.200  6979  6979 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-08 18:23:59.201  6979  6979 V BluetoothPbapService: Pbap Service onBind
09-08 18:23:59.201  7199  7239 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-08 18:23:59.204  6979  6979 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:59.204  6818  6818 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-08 18:23:59.204  6979  6979 V BluetoothPbapService: state: 12
09-08 18:23:59.205  6979  6979 D LGBluetoothAPIServer: [BTUI] onCreate()
09-08 18:23:59.205  6979  6979 D LGBluetoothAPIServer: [BTUI] onBind()
09-08 18:23:59.206  6979  6979 V BluetoothPbapService: Handler(): got msg=1
,09-08 18:23:59.208  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-08 18:23:59.208  1942  2102 D LGBluetoothAPIService: Message: 100
09-08 18:23:59.208  1942  2102 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-08 18:23:59.208  1036  1118 D BluetoothManagerService: Message: 30
09-08 18:23:59.209  6979  6979 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-08 18:23:59.209  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:59.209  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:59.209  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:23:59.209  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:59.209  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:59.209  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:59.209  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:59.209  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:59.210  6979  7577 V BluetoothPbapService: Pbap Service initSocket
09-08 18:23:59.210  1036  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:23:59.212  6979  7577 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:23:59.213  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:59.213  6979  7577 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-08 18:23:59.213  6979  7577 V BluetoothPbapService: Succeed to create listening socket 
09-08 18:23:59.213  6979  7577 V BluetoothPbapService: Accepting socket connection...
09-08 18:23:59.214  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:59.215  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:59.215  6818  6818 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-08 18:23:59.217  6818  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-08 18:23:59.220  6818  6818 D BluetoothPbap: Proxy object connected
09-08 18:23:59.220  6818  6818 D PbapServerProfile: Bluetooth service connected
09-08 18:23:59.220  6818  6818 D BluetoothA2dp: Proxy object connected
09-08 18:23:59.221  6818  6818 D A2dpProfile: Bluetooth service connected
09-08 18:23:59.221  6979  6979 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 18:23:59.221  6979  6979 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:59.221  6979  6979 V BluetoothPbapReceiver: ***********state = 12
09-08 18:23:59.222  6818  6818 D BluetoothHeadset: Proxy object connected
09-08 18:23:59.223  6818  6818 D HeadsetProfile: Bluetooth service connected
09-08 18:23:59.224  2082  2082 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:23:59.225  2082  2082 D c       : Getting all permits...
09-08 18:23:59.225  2082  2082 D a       : Opening database...
09-08 18:23:59.228  6818  6818 D DockEventReceiver: finishStartingService: stopping service
09-08 18:23:59.230  2082  2082 D a       : Opening database auth.proximity.permit_store...
09-08 18:23:59.231  2082  2082 D a       : Closing database...
,09-08 18:23:59.241  6818  6818 D BluetoothPermissionRequest: onReceive
09-08 18:23:59.243  6818  6818 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-08 18:23:59.244  6818  6818 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 18:23:59.248  6979  6979 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-08 18:23:59.249  6979  6979 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-08 18:23:59.255  6979  6979 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-08 18:23:59.277  6979  6979 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-08 18:23:59.277  6979  6979 V BtOppService: onCreate
,09-08 18:23:59.282  6979  6979 V BluetoothOppNotification: send message
09-08 18:23:59.286  6979  6979 V BtOppService: Starting RfcommListener
09-08 18:23:59.295  6979  6979 D BluetoothOppPreference: Dumping Names:  
09-08 18:23:59.295  6979  6979 D BluetoothOppPreference: {}
09-08 18:23:59.296  6979  6979 D BluetoothOppPreference: Dumping Channels:  
09-08 18:23:59.296  6979  6979 D BluetoothOppPreference: {}
09-08 18:23:59.297  6979  6979 V BtOppService: onStartCommand
,09-08 18:23:59.301  6979  6979 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:59.301  6979  6979 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-08 18:23:59.301  6979  7584 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-08 18:23:59.304  6979  6979 V BluetoothOppNotification: new notify threadi!
09-08 18:23:59.305  6979  6979 V BluetoothOppNotification: send delay message
09-08 18:23:59.306  6979  6979 V BtOppService: start RfcommListener
,09-08 18:23:59.311  6979  6979 V BtOppService: RfcommListener started
,09-08 18:23:59.314  6979  7584 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-08 18:23:59.315  6979  7585 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-08 18:23:59.315  6979  7581 V BtOppService: Deleted complete outbound shares, number =  0
09-08 18:23:59.324  6979  7586 V BtOppRfcommListener: Starting RFCOMM listener....
09-08 18:23:59.324  6979  7581 V BtOppService: Deleted complete inbound failed shares, number = 0
09-08 18:23:59.324  1036  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-08 18:23:59.324  6979  7585 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a02ad4d on behalf of 
09-08 18:23:59.325  6979  7581 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-08 18:23:59.325  6979  7586 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:23:59.327  6979  7581 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fef7d13 on behalf of 
09-08 18:23:59.328  6979  7586 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-08 18:23:59.329  6979  7586 V BtOppRfcommListener: Started RFCOMM listener....
09-08 18:23:59.329  6979  7586 I BtOppRfcommListener: Accept thread started.
09-08 18:23:59.329  6979  7586 V BtOppRfcommListener: Accepting connection...
09-08 18:23:59.330  6979  7585 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-08 18:23:59.330  6979  7584 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a7f7002 on behalf of 
09-08 18:23:59.332  6979  7585 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-08 18:23:59.333  6979  7584 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-08 18:23:59.335  6979  7585 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20c63b50 on behalf of 
09-08 18:23:59.336  6979  7585 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-08 18:23:59.338  6979  7585 V BluetoothOppNotification: outbound notification was removed.
09-08 18:23:59.338  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:59.338  6979  7585 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-08 18:23:59.338  6979  6979 V BluetoothFtpService: Ftp Service onCreate
09-08 18:23:59.338  6979  6979 I BluetoothFtpService: Ftp Service onCreate
09-08 18:23:59.339  6979  6979 V BluetoothFtpService: Ftp Service onStartCommand
09-08 18:23:59.339  6979  6979 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:59.339  6979  6979 V BluetoothFtpService: Starting Listening on sockets
09-08 18:23:59.340  6979  7585 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d788a4e on behalf of 
09-08 18:23:59.340  6979  6979 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 18:23:59.340  6979  6979 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 18:23:59.340  6979  6979 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 18:23:59.341  6979  6979 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:59.341  6979  6979 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-08 18:23:59.341  6979  7585 V BluetoothOppNotification: inbound: succ-0  fail-0
09-08 18:23:59.341  6979  6979 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-08 18:23:59.344  6979  7585 V BluetoothOppNotification: inbound notification was removed.
09-08 18:23:59.344  6979  7585 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-08 18:23:59.346  6979  7585 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ccad76f on behalf of 
09-08 18:23:59.347  6979  6979 V BtOppService: ContentObserver received notification
09-08 18:23:59.348  6979  6979 V BtOppService: ContentObserver received notification
09-08 18:23:59.348  6979  6979 V BluetoothFtpService: Handler(): got msg=1
09-08 18:23:59.349  6979  7587 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-08 18:23:59.349  6979  7587 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-08 18:23:59.349  6979  6979 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-08 18:23:59.350  6979  6979 V BluetoothFtpService: Ftp Service initSocket
,09-08 18:23:59.351  6979  7587 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1edbbc7c on behalf of 
,09-08 18:23:59.354  6979  7587 V BluetoothOppNotification: update too frequent, put in queue
09-08 18:23:59.355  6979  7587 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-08 18:23:59.357  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:23:59.358  6979  6979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:23:59.359  6979  6979 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-08 18:23:59.359  6979  6979 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-08 18:23:59.361  6979  7588 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-08 18:23:59.375  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:23:59.375  6979  6979 V BluetoothSapService: Sap Service onCreate
09-08 18:23:59.377  6979  6979 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:59.377  6979  6979 V BluetoothSapService: state: 12
09-08 18:23:59.377  6979  6979 V BluetoothSapService: Starting SAP server process
,09-08 18:23:59.380  6979  6979 V BluetoothSapService: SAP Service startRfcommListenerThread
,09-08 18:23:59.362  7589  7589 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:59.362  7589  7589 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:23:59.381  6979  7590 V BluetoothSapService: Sap Service initRfcommSocket
09-08 18:23:59.382  1036  1628 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:23:59.383  6979  7590 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:23:59.385  6979  7590 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-08 18:23:59.385  6979  7590 V BluetoothSapService: Succeed to create listening socket 
09-08 18:23:59.385  6979  7590 V BluetoothSapService: Accepting socket connection...
09-08 18:23:59.397  7589  7589 V BT_SAP  : Event pipe created
09-08 18:23:59.397  7589  7589 V BT_SAP  : create_server_socket qcom.sap.server
09-08 18:23:59.397  7589  7589 V BT_SAP  : created socket fd 6
,09-08 18:24:00.004  1036  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=413417037, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,09-08 18:24:00.029  6898  6898 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,09-08 18:24:00.030  6898  6898 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8302
,09-08 18:24:00.044  1036  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:00.044  1036  1390 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:24:00.059  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-08 18:24:00.074  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-08 18:24:00.074  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
09-08 18:24:00.074  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-08 18:24:00.076  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
09-08 18:24:00.078  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
09-08 18:24:00.078  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
09-08 18:24:00.078  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
09-08 18:24:00.083  1036  1436 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 18:24:00.083  1036  1436 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 18:24:00.088  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,09-08 18:24:00.119  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=413417037 [*alarm*], flags=0x0
,09-08 18:24:00.267  1036  2052 I ActivityManager: Killing 7377:com.lge.bnr/1000 (adj 15): empty #17
,09-08 18:24:00.299  1036  1905 W libprocessgroup: failed to open /acct/uid_1000/pid_7377/cgroup.procs: No such file or directory
,09-08 18:24:00.306  6979  6979 V BluetoothOppNotification: new notify threadi!
09-08 18:24:00.307  6979  6979 V BluetoothOppNotification: send delay message
09-08 18:24:00.308  6979  7600 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-08 18:24:00.309  6979  7600 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18662468 on behalf of 
09-08 18:24:00.310  6979  7600 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-08 18:24:00.311  6979  7600 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-08 18:24:00.315  6979  7600 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13056081 on behalf of 
,09-08 18:24:00.316  6979  7600 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-08 18:24:00.317  6979  7600 V BluetoothOppNotification: outbound notification was removed.
,09-08 18:24:00.317  6979  7600 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-08 18:24:00.318  6979  7600 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21779526 on behalf of 
,09-08 18:24:00.319  6979  7600 V BluetoothOppNotification: inbound: succ-0  fail-0,
09-08 18:24:00.320  6979  7600 V BluetoothOppNotification: inbound notification was removed.,
09-08 18:24:00.320  6979  7600 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-08 18:24:00.322  6979  7600 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30c04567 on behalf of 
09-08 18:24:00.408  1036  2033 I ActivityManager: Killing 6847:com.lge.sync/1000 (adj 15): empty #17
,09-08 18:24:00.443  1036  1474 D WifiService: Client connection lost with reason: 4
,09-08 18:24:00.453  1036  1905 W libprocessgroup: failed to open /acct/uid_1000/pid_6847/cgroup.procs: No such file or directory
,09-08 18:24:01.017  1036  1699 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-08 18:24:01.017  1036  1699 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@91f33fb mBinding = false
,09-08 18:24:01.051  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-08 18:24:01.051  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 18:24:01.051  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-08 18:24:01.052  1036  1118 D BluetoothManagerService: Message: 2
09-08 18:24:01.053  1036  1118 D BluetoothManagerService: Sending off request.
09-08 18:24:01.053  6979  6995 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-08 18:24:01.054  6979  7463 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-08 18:24:01.054  6979  7463 D BluetoothAdapterProperties: Setting state to 13
09-08 18:24:01.054  6979  7463 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 18:24:01.055  6979  7463 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 18:24:01.055  6979  7463 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-08 18:24:01.057  6979  7467 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:24:01.059  6979  7463 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-08 18:24:01.063  6979  7463 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-08 18:24:01.066  6979  7577 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:24:01.067  6979  7586 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:24:01.068  6979  7588 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:24:01.068  6979  7590 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:24:01.069  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-08 18:24:01.069  6979  7532 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-08 18:24:01.070  6979  7567 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-08 18:24:01.070  6979  7567 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:24:01.070  6979  7567 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-08 18:24:01.070  6979  7567 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-08 18:24:01.070  6979  7567 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-08 18:24:01.070  6979  7567 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-08 18:24:01.070  6979  7567 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-08 18:24:01.070  6979  7567 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-08 18:24:01.076  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 18:24:01.076  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 18:24:01.076  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-08 18:24:01.078  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 18:24:01.078  6979  7532 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:24:01.078  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 18:24:01.078  6979  7532 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:24:01.078  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 18:24:01.078  6979  7532 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:24:01.078  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-08 18:24:01.079  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-08 18:24:01.081  6979  7532 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-08 18:24:01.087  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:24:01.087  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:01.087  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:01.087  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:24:01.087  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:01.087  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:24:01.087  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:01.087  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:01.087  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:24:01.090  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:24:01.090  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:01.096  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:24:01.096  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:01.096  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:01.096  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:24:01.096  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:01.096  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:24:01.096  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:01.096  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:01.096  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:24:01.098  6609  6609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:24:01.098  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:24:01.099  1036  1118 D BluetoothManagerService: Message: 60
09-08 18:24:01.099  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-08 18:24:01.099  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-08 18:24:01.105  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:01.106  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 18:24:01.110  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:01.112  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:01.114  6979  6979 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:01.114  6979  6979 D BluetoothMapService: STATE_TURNING_OFF
09-08 18:24:01.114  6979  6979 V BluetoothMapService: Handler(): got msg=4
,09-08 18:24:01.117  6979  6979 D BluetoothMapService: MAP Service closeService in
09-08 18:24:01.117  6979  6979 D BluetoothMapMasInstance: MAP Service shutdown
09-08 18:24:01.118  6979  6979 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 18:24:01.118  6979  6979 V BluetoothMapService: MAP Service closeService out
09-08 18:24:01.119  6979  6979 V BtOppService: Receiver DISABLED_ACTION 
09-08 18:24:01.119  6979  6979 I BtOppRfcommListener: stopping Accept Thread
09-08 18:24:01.119  6979  6979 V BtOppRfcommListener: close mBtServerSocket
09-08 18:24:01.120  6979  7586 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 18:24:01.121  6979  6979 V BtOppRfcommListener: waiting for thread to terminate
09-08 18:24:01.121  6979  6979 V BtOppRfcommListener: done waiting for thread to terminate
09-08 18:24:01.124  6818  6818 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-08 18:24:01.141  6818  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-08 18:24:01.153  6979  6979 V BtOppService: onDestroy
,09-08 18:24:01.163  6979  6979 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-08 18:24:01.172  6979  6979 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 18:24:01.173  6979  6979 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:01.173  6979  6979 V BluetoothPbapReceiver: ***********state = 13
,09-08 18:24:01.189  6818  6818 D DockEventReceiver: finishStartingService: stopping service
09-08 18:24:01.201  6979  6979 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-08 18:24:01.209  6979  6979 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:01.209  6979  6979 V BluetoothPbapService: state: 13
09-08 18:24:01.210  6979  6979 V BluetoothPbapService: Pbap Service closeService in
09-08 18:24:01.212  6979  6979 V BluetoothPbapService: successfully stopped pbap service
,09-08 18:24:01.212  6979  6979 V BluetoothPbapService: Pbap Service closeService out
09-08 18:24:01.213  6818  6818 D BluetoothPbap: Proxy object disconnected
09-08 18:24:01.213  6979  6979 V BluetoothPbapService: Pbap Service onDestroy
09-08 18:24:01.213  6979  6979 V BluetoothPbapService: Pbap Service closeService in
,09-08 18:24:01.213  6979  6979 V BluetoothPbapService: Pbap Service closeService out
09-08 18:24:01.213  6979  6979 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-08 18:24:01.214  6818  6818 D PbapServerProfile: Bluetooth service disconnected
,09-08 18:24:01.218  2082  2082 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:24:01.226  6818  6818 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-08 18:24:01.231  6818  6818 D BluetoothPermissionRequest: onReceive
09-08 18:24:01.231  6818  6818 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-08 18:24:01.236  6818  6818 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 18:24:01.239  6979  6979 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-08 18:24:01.239  6979  6979 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-08 18:24:01.240  6979  6979 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-08 18:24:01.244  6979  6979 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:01.244  6979  6979 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-08 18:24:01.245  6979  6979 V BluetoothFtpService: Ftp Service onStartCommand
09-08 18:24:01.245  6979  6979 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:01.245  6979  6979 V BluetoothFtpService: Ftp Service closeService
09-08 18:24:01.245  6979  6979 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-08 18:24:01.248  6979  6979 V BluetoothFtpService: successfully stopped ftp service
09-08 18:24:01.248  6979  6979 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 18:24:01.248  6979  6979 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 18:24:01.248  6979  6979 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 18:24:01.248  6979  6979 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:01.249  6979  6979 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-08 18:24:01.249  6979  6979 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-08 18:24:01.249  6979  6979 V BluetoothFtpService: Ftp Service onDestroy
09-08 18:24:01.249  6979  6979 V BluetoothFtpService: Ftp Service closeService
09-08 18:24:01.253  6979  6979 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:01.253  6979  6979 V BluetoothSapService: state: 13
09-08 18:24:01.253  6979  6979 V BluetoothSapService: Stopping SAP server process
,09-08 18:24:01.255  6979  6979 V BluetoothSapService: Sap Service closeSapService in
,09-08 18:24:01.256  6979  6979 V BluetoothSapService: Close listen Socket : 
,09-08 18:24:01.256  6979  6979 V BluetoothSapService: Close rfcomm Socket : 
09-08 18:24:01.256  6979  6979 V BluetoothSapService: Close sapd  Socket : 
09-08 18:24:01.257  6979  6979 V BluetoothSapService: Sap Service closeSapService out
,09-08 18:24:01.257  6979  6979 V BluetoothSapService: Sap Service onDestroy
09-08 18:24:01.257  6979  6979 V BluetoothSapService: Sap Service closeSapService in
09-08 18:24:01.257  6979  6979 V BluetoothSapService: Close listen Socket : 
09-08 18:24:01.257  6979  6979 V BluetoothSapService: Close rfcomm Socket : 
,09-08 18:24:01.257  6979  6979 V BluetoothSapService: Close sapd  Socket : 
09-08 18:24:01.257  6979  6979 V BluetoothSapService: Sap Service closeSapService out
09-08 18:24:01.985  6979  7467 D bt_hci_bdroid: cleanup
,09-08 18:24:01.996  6979  7534 I bt_lpm  : LPM is already off!!!
09-08 18:24:01.997  6979  7558 I bt_userial_mct: exiting userial_read_thread
09-08 18:24:01.997  6979  7558 D bt_userial_mct: Leaving userial_evt_read_thread()
09-08 18:24:01.997  6979  7532 W bt-btif : ag scb idx 1 not allocated
09-08 18:24:01.997  6979  7532 E bt-btif : BTA AG is already disabled, ignoring ...
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 18:24:01.997  6979  7532 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:24:01.998  6979  7532 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-08 18:24:01.998  6979  7467 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-08 18:24:01.999  6979  7534 I bt_vendor: hw_epilog_process
09-08 18:24:01.999  6979  7467 D bt_hci_bdroid: cleanup Finalizing cleanup
09-08 18:24:01.999  6979  7467 D bt_userial_mct: userial_close
09-08 18:24:01.999  6979  7467 E bt_userial_mct: pthread_join() FAILED result:3
09-08 18:24:01.999  6979  7467 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-08 18:24:02.002  6979  7467 D bt_hci_bdroid: set_power 0
09-08 18:24:02.002  6979  7467 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-08 18:24:02.004  6979  7467 I bt_vendor: bluetooth satus is on
09-08 18:24:02.004  6979  7467 I bt_vendor: bt-vendor : resetting BT status
09-08 18:24:02.004  6979  7467 I bt_vendor: Starting hciattach daemon
09-08 18:24:02.004  6979  7467 I bt_vendor: try to set false
09-08 18:24:02.006  6979  7467 I bt_vendor: Starting hciattach daemon
09-08 18:24:02.006  6979  7467 I bt_vendor: try to set false
,09-08 18:24:02.011  6979  7467 I bt_vendor: cleanup
09-08 18:24:02.012  6979  7532 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-08 18:24:02.012  6979  7467 I GKI_LINUX: GKI_exit_task 0 done
09-08 18:24:02.012  6979  7467 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-08 18:24:02.014  6979  7463 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-08 18:24:02.022  6979  6979 D HeadsetService: Received stop request...Stopping profile...
,09-08 18:24:02.026  6979  7463 D BluetoothAdapterState: Stopping profile services that were post enabled
09-08 18:24:02.028  6979  6979 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-08 18:24:02.028  6979  6979 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 18:24:02.028  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:24:02.028  6979  7485 D HeadsetStateMachine: Exit Disconnected: -1
09-08 18:24:02.031  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-08 18:24:02.031  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-08 18:24:02.031  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-08 18:24:02.033  1036  1036 D BluetoothHeadset: Proxy object disconnected
09-08 18:24:02.033  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-08 18:24:02.033  6979  6979 D A2dpService: Received stop request...Stopping profile...
,09-08 18:24:02.036  6979  7520 D A2dpStateMachine: Exit Disconnected: -1
09-08 18:24:02.038  6979  6979 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-08 18:24:02.040  6979  6979 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-08 18:24:02.040  6979  6979 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 18:24:02.040  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:24:02.043  6979  6979 D HidService: Received stop request...Stopping profile...
09-08 18:24:02.043  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:24:02.043  1036  1036 D BluetoothA2dp: Proxy object disconnected
09-08 18:24:02.043  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-08 18:24:02.044  6979  6979 D HealthService: Received stop request...Stopping profile...
09-08 18:24:02.045  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:24:02.046  6979  6979 D PanService: Received stop request...Stopping profile...
,09-08 18:24:02.049  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:24:02.051  6979  6979 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 18:24:02.052  6979  6979 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 18:24:02.052  6979  6979 D BtGatt.GattService: stop()
09-08 18:24:02.052  6979  6979 D BtGatt.AdvertiseManager: advertise clients cleared
09-08 18:24:02.054  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
09-08 18:24:02.056  6979  6979 D BluetoothMapService: Received stop request...Stopping profile...
09-08 18:24:02.056  6979  6979 D BluetoothMapService: stop()
09-08 18:24:02.057  6979  6979 D BluetoothMapEmailAppObserver: deinitObservers()
09-08 18:24:02.057  6979  6979 D BluetoothMapEmailAppObserver: removeReceiver()
09-08 18:24:02.058  6979  6979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30448fa8
,09-08 18:24:02.062  6979  6979 D HeadsetStateMachine: Unbinding service...
09-08 18:24:02.064  6979  6979 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 18:24:02.064  6979  6979 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 18:24:02.064  6979  6979 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 18:24:02.064  6979  6979 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 18:24:02.064  6979  6979 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 18:24:02.064  6979  6979 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 18:24:02.064  6979  6979 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-08 18:24:02.064  6979  6979 I BluetoothA2dpServiceJni: cleanupNative
09-08 18:24:02.065  6979  7521 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-08 18:24:02.065  6979  6979 I GKI_LINUX: GKI_exit_task 2 done
09-08 18:24:02.065  6979  6979 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-08 18:24:02.065  6979  6979 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 18:24:02.065  6979  6979 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 18:24:02.066  6979  6979 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 18:24:02.066  6979  6979 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 18:24:02.066  6979  6979 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 18:24:02.066  6979  6979 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 18:24:02.066  6979  6979 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 18:24:02.069  6979  6979 V BluetoothMapService: Handler(): got msg=4
09-08 18:24:02.069  6979  6979 D BluetoothMapService: MAP Service closeService in
09-08 18:24:02.069  6979  6979 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 18:24:02.069  6979  6979 V BluetoothMapService: MAP Service closeService out
09-08 18:24:02.069  6979  7463 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-08 18:24:02.069  6979  7463 D BluetoothAdapterProperties: Setting state to 10
09-08 18:24:02.069  6979  7463 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-08 18:24:02.073  6979  6979 D BluetoothMapService: cleanup()
09-08 18:24:02.073  6979  6979 D BluetoothMapService: MAP Service closeService in
09-08 18:24:02.073  6979  6979 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 18:24:02.073  6979  6979 V BluetoothMapService: MAP Service closeService out
09-08 18:24:02.075  1036  1118 D BluetoothManagerService: Message: 60
09-08 18:24:02.075  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-08 18:24:02.075  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-08 18:24:02.076  6979  7463 I BluetoothAdapterState: Entering OffState
09-08 18:24:02.076  6818  6841 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:24:02.077  6818  6841 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 18:24:02.077  1853  2478 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:24:02.078  6818  6841 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 18:24:02.078  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:24:02.079  1853  3996 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:24:02.079  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:24:02.079  6818  6841 D BluetoothPan: onBluetoothStateChange on: false
09-08 18:24:02.080  6818  6841 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:24:02.081  6818  6841 D BluetoothMap: onBluetoothStateChange: up=false
09-08 18:24:02.081  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 18:24:02.087  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-08 18:24:02.087  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-08 18:24:02.090  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-08 18:24:02.090  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-08 18:24:02.090  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@91f33fb mBinding = false
09-08 18:24:02.092  1036  1118 D BluetoothManagerService: Sending unbind request.
09-08 18:24:02.097  6979  7467 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-08 18:24:02.099  6979  6979 I GKI_LINUX: GKI_exit_task 1 done
09-08 18:24:02.099  6979  6979 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-08 18:24:02.100  6979  6979 I BluetoothServiceJni: cleanupNative: return from cleanup
09-08 18:24:02.100  6979  6979 I art     : --- WEIRD: removing null entry 248
09-08 18:24:02.100  6979  6979 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-08 18:24:02.100  6979  6979 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-08 18:24:02.101  6979  6979 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-08 18:24:02.102  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-08 18:24:02.104  6979  6979 I art     : System.exit called, status: 0
09-08 18:24:02.104  6979  6979 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-08 18:24:02.123   315  1398 V AudioFlinger: 6979 died, releasing its sessions
09-08 18:24:02.123   315  1398 V AudioFlinger:  pid 1853 @ 0
09-08 18:24:02.123   315  1398 V AudioFlinger:  pid 3466 @ 1
09-08 18:24:02.123   315  1398 V AudioFlinger:  pid 3466 @ 2
,09-08 18:24:02.127  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-08 18:24:02.127  1942  2102 D LGBluetoothAPIService: Message: 101
,09-08 18:24:02.127  1942  2102 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-08 18:24:02.127  1942  2102 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
,09-08 18:24:02.127  1942  2102 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-08 18:24:02.129  6818  6818 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,09-08 18:24:02.134  1036  1986 I ActivityManager: Process com.android.bluetooth (pid 6979) has died
09-08 18:24:02.134  1036  1986 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,09-08 18:24:02.135  1036  1986 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 13999ms
,09-08 18:24:02.148  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:02.148  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 18:24:02.148  1942  2102 D LGBluetoothAPIService: Message: 2
09-08 18:24:02.149  1942  2102 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-08 18:24:02.151  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:02.152  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:02.154  1605  1605 D BluetoothAdapter: 465229763: getState() :  mService = null. Returning STATE_OFF
09-08 18:24:02.154  1605  1605 D BluetoothAdapter: 465229763: getState() :  mService = null. Returning STATE_OFF
09-08 18:24:02.157  6818  6818 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-08 18:24:02.157  6818  6818 D LGBluetoothEventManager: [BTUI] clear device connection state
09-08 18:24:02.160  6818  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-08 18:24:02.209  1036  2028 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7647 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-08 18:24:02.210  6818  6818 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:24:02.468  1036  1699 I art     : Explicit concurrent mark sweep GC freed 94400(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.822ms total 173.871ms
,09-08 18:24:02.484  7647  7647 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-08 18:24:02.485  7647  7647 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 18:24:02.487  7647  7647 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,09-08 18:24:02.488  7647  7647 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-08 18:24:02.516  7647  7647 D BluetoothAdapterApp: Loading JNI Library
,09-08 18:24:02.574  7647  7647 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@34a77e90 Instance Count = 1
,09-08 18:24:02.584  7647  7647 D BluetoothAdapterApp: onCreate
09-08 18:24:02.613  7647  7647 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-08 18:24:02.614  7647  7647 D ProfileConfigQcom: Adding HeadsetService
09-08 18:24:02.615  7647  7647 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-08 18:24:02.615  7647  7647 D ProfileConfigQcom: Adding A2dpService
09-08 18:24:02.616  7647  7647 D ProfileConfigQcom: [BTUI] HidService is supported
09-08 18:24:02.616  7647  7647 D ProfileConfigQcom: Adding HidService
09-08 18:24:02.617  7647  7647 D ProfileConfigQcom: [BTUI] HealthService is supported
09-08 18:24:02.617  7647  7647 D ProfileConfigQcom: Adding HealthService
09-08 18:24:02.618  7647  7647 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-08 18:24:02.624  7647  7647 D ProfileConfigQcom: [BTUI] PanService is supported,
,09-08 18:24:02.624  7647  7647 D ProfileConfigQcom: Adding PanService
09-08 18:24:02.624  7647  7647 D ProfileConfigQcom: [BTUI] GattService is supported
09-08 18:24:02.625  7647  7647 D ProfileConfigQcom: Adding GattService
,09-08 18:24:02.625  7647  7647 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,09-08 18:24:02.625  7647  7647 D ProfileConfigQcom: Adding BluetoothMapService
09-08 18:24:02.626  7647  7647 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported,
09-08 18:24:02.627  7647  7647 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 18:24:02.628  7647  7647 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:02.628  7647  7647 V BluetoothPbapReceiver: ***********state = 10
09-08 18:24:02.630  7647  7647 V LGMDMManagerInternal: Create singleton instance
,09-08 18:24:02.728  2082  2082 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
09-08 18:24:02.730  6818  6818 D LGBluetoothUserBindClient: [BTUI] onServiceConnected,
09-08 18:24:02.735  7647  7647 D LGBluetoothAPIServer: [BTUI] onCreate()
,09-08 18:24:02.736  7647  7647 D LGBluetoothAPIServer: [BTUI] onBind()
,09-08 18:24:02.737  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter,
,09-08 18:24:02.737  1942  2102 D LGBluetoothAPIService: Message: 100
,09-08 18:24:02.737  1942  2102 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,09-08 18:24:02.746  6818  6818 D BluetoothPermissionRequest: onReceive,
09-08 18:24:02.749  6818  6818 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-08 18:24:02.750  6818  6818 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-08 18:24:02.752  6818  6818 D LGBluetoothResetSettingReceiver: return without doing reset settings.,
,09-08 18:24:02.757  7647  7647 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-08 18:24:02.760  7647  7647 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:02.763  7647  7647 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-08 18:24:02.764  7647  7647 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-08 18:24:02.764  7647  7647 V BluetoothSapReceiver: SapReceiver onReceive 
,09-08 18:24:02.765  7647  7647 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:02.765  7647  7647 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-08 18:24:02.769  6915  6915 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-08 18:24:03.076  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{25cf3c56 type 2 when 128845 com.google.android.gms} when 128845
,09-08 18:24:03.093   309  7678 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-08 18:24:03.099  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-08 18:24:04.139  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:24:04.139  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:04.182  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-08 18:24:04.204  1036  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 18:24:04.263  1036  1036 D administrator: Handling package changes for user 0
,09-08 18:24:04.294  1036  1114 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7679 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-08 18:24:04.321  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-08 18:24:04.327  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-08 18:24:04.335  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-08 18:24:04.373  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-08 18:24:04.376  7679  7679 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 18:24:04.439  7679  7679 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:24:04.439  7679  7679 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:24:04.442  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-08 18:24:04.442  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-08 18:24:04.488  1036  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 18:24:04.493  1036  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-08 18:24:04.498  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-08 18:24:04.498  2454  2454 V GmsNetworkLocationProvi: DISABLE
,09-08 18:24:04.519  2454  2454 E GCoreFlp: Bound FusedProviderService with LocationManager
09-08 18:24:04.544  7679  7724 I Babel   : MmsConfig: mnc/mcc: 0/0
09-08 18:24:04.544  7679  7724 I Babel   : MmsConfig.loadMmsSettings
,09-08 18:24:04.547  7679  7724 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-08 18:24:04.547  7679  7724 I Babel   : MmsConfig.loadFromDatabase
09-08 18:24:04.558  7679  7679 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:04.564  7679  7722 W AudioCapabilities: Unsupported mime audio/evrc
09-08 18:24:04.564  7679  7724 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-08 18:24:04.564  7679  7724 I Babel   : MmsConfig.loadFromResources
09-08 18:24:04.565  7679  7722 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 18:24:04.565  7679  7724 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-08 18:24:04.565  7679  7724 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-08 18:24:04.566  7679  7722 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 18:24:04.578  1818  7726 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-08 18:24:04.578  1818  7726 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-08 18:24:04.582  7035  7035 I AppUp4:CustModeStarterReceiver: onReceive
,09-08 18:24:04.587  7679  7722 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-08 18:24:04.588  7679  7722 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 18:24:04.588  7035  7035 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18cc269a
09-08 18:24:04.588  7035  7035 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 18:24:04.588  7035  7035 D AppUp4:CustFacade: isPhone : true
09-08 18:24:04.588  7035  7035 D AppUp4:CustModeStarterReceiver: begin check event
09-08 18:24:04.588  7035  7035 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-08 18:24:04.589  7679  7722 W AudioCapabilities: Unsupported mime audio/evrc
09-08 18:24:04.592  1818  4775 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-08 18:24:04.599  7679  7722 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-08 18:24:04.614  7679  7722 W VideoCapabilities: Unsupported mime video/divx
09-08 18:24:04.616  7679  7722 W VideoCapabilities: Unsupported mime video/divx311
09-08 18:24:04.617  7679  7722 W VideoCapabilities: Unsupported mime video/divx4
,09-08 18:24:04.624  7679  7722 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-08 18:24:04.625  1036  1905 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7730 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-08 18:24:04.627  1036  1940 I ActivityManager: Killing 7065:com.lge.email/u0a23 (adj 15): empty #17
09-08 18:24:04.652  7679  7722 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 18:24:04.655  7679  7722 W AudioCapabilities: Unsupported mime audio/eac3
09-08 18:24:04.656  7679  7722 W AudioCapabilities: Unsupported mime audio/ac3
09-08 18:24:04.657  7679  7722 W AudioCapabilities: Unsupported mime audio/g726
09-08 18:24:04.658  7679  7722 W AudioCapabilities: Unsupported mime audio/wma-voice
09-08 18:24:04.659  7679  7722 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-08 18:24:04.660  7679  7722 W AudioCapabilities: Unsupported mime audio/adpcm
09-08 18:24:04.661  7679  7722 W VideoCapabilities: Unsupported mime video/theora
09-08 18:24:04.663  7679  7722 W VideoCapabilities: Unsupported mime video/mjpg
,09-08 18:24:04.715  1036  2028 W libprocessgroup: failed to open /acct/uid_10023/pid_7065/cgroup.procs: No such file or directory
09-08 18:24:04.722  1036  1113 D LocationProviderProxy: applying state to connected service
09-08 18:24:04.730  7730  7730 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:24:04.731  7730  7730 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 18:24:04.731  7730  7730 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-08 18:24:04.732  7730  7730 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-08 18:24:04.732  7730  7730 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 18:24:04.779  7730  7730 I SystemConfig: BUILD Country: EU
09-08 18:24:04.779  7730  7730 I SystemConfig: BUILD Operator: OPEN
,09-08 18:24:04.831  1036  1577 I ActivityManager: Killing 6935:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-08 18:24:04.932  1036  1940 W libprocessgroup: failed to open /acct/uid_10026/pid_6935/cgroup.procs: No such file or directory
,09-08 18:24:04.946  7730  7748 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-08 18:24:04.946  7730  7748 I SystemConfig: existFile = false
09-08 18:24:04.946  7730  7748 I SystemConfig: canReadFile = false
09-08 18:24:04.947  7730  7748 I SystemConfig: systemFeature RCS result false
09-08 18:24:04.947  7730  7748 D SystemConfig: refreshRcsSupport() :false
09-08 18:24:04.993  1036  1577 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7753 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-08 18:24:05.052  7753  7753 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:24:05.052  7753  7753 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 18:24:05.053  7753  7753 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-08 18:24:05.053  7753  7753 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-08 18:24:05.120  7753  7753 I AppConfig: Total System Memory = 2995761152
,09-08 18:24:05.127  7753  7753 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-08 18:24:05.205  1036  1699 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7772 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 18:24:05.207  1036  1699 I ActivityManager: Killing 6435:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-08 18:24:05.315  1036  1959 W libprocessgroup: failed to open /acct/uid_1000/pid_6435/cgroup.procs: No such file or directory
,09-08 18:24:05.538  7772  7772 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-08 18:24:05.604  7772  7772 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:24:05.604  7772  7772 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:24:05.655  7772  7772 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-08 18:24:05.676  7772  7772 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-08 18:24:05.678  7772  7772 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-08 18:24:05.707  7772  7772 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:24:05.708  7772  7772 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-08 18:24:05.724  1036  2033 I ActivityManager: Killing 7113:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-08 18:24:05.795  1036  2052 W libprocessgroup: failed to open /acct/uid_10046/pid_7113/cgroup.procs: No such file or directory
,09-08 18:24:05.798  3512  5820 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-08 18:24:05.800  3512  5820 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2c237d9e on behalf of 7772
,09-08 18:24:05.807  4604  7812 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-08 18:24:05.860  1036  1905 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7814 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-08 18:24:05.867  7772  7772 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-08 18:24:05.899  7772  7772 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-08 18:24:05.938  7814  7814 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-08 18:24:05.966  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,09-08 18:24:05.966  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,09-08 18:24:05.966  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-08 18:24:05.966  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-08 18:24:05.966  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-08 18:24:05.966  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-08 18:24:05.981  1036  2028 I ActivityManager: Killing 7133:com.android.chrome/u0a57 (adj 15): empty #17
,09-08 18:24:06.010  1036  1577 W libprocessgroup: failed to open /acct/uid_10057/pid_7133/cgroup.procs: No such file or directory
,09-08 18:24:06.187  1036  1699 V SIM_STK : Menu title from STK is T-Mobile
,09-08 18:24:06.213  4604  7812 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 406 ms] updated apps [took 406 ms] 
,09-08 18:24:07.156  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:07.156  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c8dd41c added. We now have 6 listener(s)
,09-08 18:24:07.156  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:07.171  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:07.171  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28ac0825 added. We now have 7 listener(s)
09-08 18:24:07.171  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:07.174  6609  6721 I System.out: IsBluetoothEnabled
09-08 18:24:07.177  1036  1988 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:07.177  1036  1988 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,09-08 18:24:07.180  1036  1118 D BluetoothManagerService: Message: 2
09-08 18:24:07.183  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:07.183  1036  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:07.183  1036  2052 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-08 18:24:07.195  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 18:24:07.195  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 18:24:07.195  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-08 18:24:07.206  1036  1118 D BluetoothManagerService: Message: 1
09-08 18:24:07.206  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-08 18:24:07.232  1036  1118 D BluetoothManagerService: Message: 20
09-08 18:24:07.232  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18b4337b:true
,09-08 18:24:07.235  7647  7647 D BluetoothAdapterState: make
09-08 18:24:07.240  7647  7647 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-08 18:24:07.240  7647  7647 I bluedroid-qcom: init
09-08 18:24:07.241  7647  7858 I BluetoothAdapterState: Entering OffState
09-08 18:24:07.242  7647  7647 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-08 18:24:07.242  7647  7647 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-08 18:24:07.242  7647  7647 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 18:24:07.242  7647  7647 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 18:24:07.242  7647  7647 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-08 18:24:07.244  7647  7647 I bluedroid-qcom: get_profile_interface socket
09-08 18:24:07.244  7647  7647 I bluedroid-qcom: get_profile_interface map_client
,09-08 18:24:07.248  7647  7862 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-08 18:24:07.250  7647  7862 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-08 18:24:07.242  7861  7861 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:07.242  7861  7861 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:07.260  7861  7861 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-08 18:24:07.260  7861  7861 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-08 18:24:07.260  7861  7861 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-08 18:24:07.266  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-08 18:24:07.266  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
09-08 18:24:07.268  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-08 18:24:07.268  1036  1118 D BluetoothManagerService: Message: 40
09-08 18:24:07.268  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-08 18:24:07.269  7647  7663 I bluedroid-qcom: config_hci_snoop_log
09-08 18:24:07.270  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-08 18:24:07.270  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-08 18:24:07.272  7861  7861 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-08 18:24:07.275  7647  7862 D BluetoothAdapterProperties: Name is: G3
,09-08 18:24:07.281  7861  7861 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-08 18:24:07.281  7861  7861 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-08 18:24:07.284  7647  7858 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-08 18:24:07.284  7647  7858 D BluetoothAdapterProperties: Setting state to 11
09-08 18:24:07.284  7647  7858 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-08 18:24:07.286  1036  1118 D BluetoothManagerService: Message: 60
09-08 18:24:07.286  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-08 18:24:07.286  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-08 18:24:07.290  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:24:07.292  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-08 18:24:07.294  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:07.296  6818  6818 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-08 18:24:07.304  7647  7647 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 18:24:07.304  7647  7647 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:07.304  7647  7647 V BluetoothPbapReceiver: ***********state = 11
,09-08 18:24:07.314  7647  7858 I LGBluetoothServiceJni: classInitNative: succeeds
09-08 18:24:07.315  2082  2082 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:24:07.326  7647  7858 D BluetoothBondStateMachine: make
,09-08 18:24:07.329  6818  6818 D BluetoothPermissionRequest: onReceive
09-08 18:24:07.330  7647  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
09-08 18:24:07.330  7647  7858 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-08 18:24:07.330  7647  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
09-08 18:24:07.330  7647  7858 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-08 18:24:07.331  7647  7858 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-08 18:24:07.332  7647  7879 I BluetoothBondStateMachine: StableState(): Entering Off State
09-08 18:24:07.333  6818  6818 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 18:24:07.335  7647  7858 E BluetoothAdapterService: File transfer profiles supported!!
09-08 18:24:07.342  7647  7858 E BluetoothAdapterService: File transfer profiles supported!!
,09-08 18:24:07.344  7647  7647 D HeadsetService: Received start request. Starting profile...
09-08 18:24:07.344  7647  7647 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 18:24:07.345  7647  7647 D LGBluetoothHfpAdapter: Version 1.6
09-08 18:24:07.347  7647  7647 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-08 18:24:07.348  7647  7647 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 18:24:07.349  7647  7647 D HeadsetStateMachine: make
09-08 18:24:07.350  7647  7858 E BluetoothAdapterService: File transfer profiles supported!!
09-08 18:24:07.355  7647  7858 E BluetoothAdapterService: File transfer profiles supported!!
,09-08 18:24:07.360  7647  7858 E BluetoothAdapterService: File transfer profiles supported!!
09-08 18:24:07.365  7647  7858 E BluetoothAdapterService: File transfer profiles supported!!
09-08 18:24:07.368  7647  7858 E BluetoothAdapterService: File transfer profiles supported!!
,09-08 18:24:07.382  7647  7858 V LGMDMManager: Create singleton instance
09-08 18:24:07.384  7647  7647 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:24:07.384  7647  7647 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:24:07.387  7647  7858 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-08 18:24:07.389  7647  7647 D HeadsetStateMachine: max_hf_connections = 1
09-08 18:24:07.389  7647  7647 I bluedroid-qcom: get_profile_interface handsfree
09-08 18:24:07.391  7647  7647 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-08 18:24:07.392   315  1398 V AudioPolicyService: registerClient() client 0xb0410620, uid 1002
09-08 18:24:07.392   315  2211 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-08 18:24:07.392   315  2211 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 18:24:07.392   315  2211 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 18:24:07.392  7647  7647 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-08 18:24:07.393   315  1397 V AudioFlinger: registerClient() client 0xb5581790, pid 7647
09-08 18:24:07.394   315  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:24:07.394   315  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 18:24:07.394  1036  1940 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:24:07.394  1036  1940 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 18:24:07.394  1605  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:24:07.394  1605  1623 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 18:24:07.394  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:24:07.395  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 18:24:07.395  7647  7663 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:24:07.395  3466  3481 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 18:24:07.395  3466  3481 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 18:24:07.395  7647  7663 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-08 18:24:07.395  7647  7647 V ToneGenerator: Create Track: 0xb4928a80
09-08 18:24:07.395   315  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:24:07.395  7647  7647 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-08 18:24:07.395  7647  7647 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-08 18:24:07.395   315  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 18:24:07.395   315  1398 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-08 18:24:07.395   315  1398 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-08 18:24:07.395   315  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 18:24:07.395   315  1398 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 18:24:07.395  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:24:07.395  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 18:24:07.396  3466  3482 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:24:07.396  1605  2693 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:24:07.396  3466  3482 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 18:24:07.396  1605  2693 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 18:24:07.396  1853  3988 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:24:07.396  7647  7664 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 18:24:07.396  1853  3988 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 18:24:07.396  7647  7664 V AudioSystem: ioConfigChanged() new output samplingRate 48000, forma,t 0x1 channel mask 0x3 frameCount 960 latency 80
09-08 18:24:07.396   315  2211 I AudioFlinger: isAudioPlaybackHookOn() false
09-08 18:24:07.396   315   315 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-08 18:24:07.396   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-08 18:24:07.396   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 18:24:07.396   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 18:24:07.396  7647  7647 V AudioSystem: getLatency() output 2, latency 50
09-08 18:24:07.396  7647  7647 V AudioSystem: getFrameCount() output 2, frameCount 960
09-08 18:24:07.396  7647  7647 V AudioTrack: createTrack_l() output 2 afLatency 50
09-08 18:24:07.397   315  2211 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-08 18:24:07.397   315  2211 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-08 18:24:07.397   315  2211 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-08 18:24:07.397   315  2211 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-08 18:24:07.397   315  2211 V AudioFlinger: createTrack() lSessionId: 21
09-08 18:24:07.398  7647  7647 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-08 18:24:07.398   315  1398 V AudioFlinger: acquiring 21 from 7647, for 7647
09-08 18:24:07.398   315  1398 V AudioFlinger:  added new entry for 21
09-08 18:24:07.398  7647  7647 V ToneGenerator: ToneGenerator INIT OK, time: 133186
09-08 18:24:07.398  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
09-08 18:24:07.399  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
,09-08 18:24:07.401  7647  7647 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:07.402  7647  7880 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-08 18:24:07.402  7647  7880 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 18:24:07.403  7647  7880 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 18:24:07.403  7647  7880 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-08 18:24:07.404   315  1397 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7647
09-08 18:24:07.404   315  1397 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-08 18:24:07.404   315  1397 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-08 18:24:07.404   315  1397 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-08 18:24:07.404   315  1397 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-08 18:24:07.404   315  1397 V voice   : voice_set_parameters: exit with code(0)
09-08 18:24:07.404   315  1397 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-08 18:24:07.404   315  1397 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-08 18:24:07.404   315  1397 V msm8974_platform: platform_set_parameters: exit with code(0)
09-08 18:24:07.404   315  1397 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-08 18:24:07.404   315  1397 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-08 18:24:07.405   315  1397 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-08 18:24:07.405  7647  7647 D A2dpService: Received start request. Starting profile...
09-08 18:24:07.405  7647  7880 V ToneGenerator: ToneGenerator destructor
09-08 18:24:07.405  7647  7880 V ToneGenerator: stopTone
09-08 18:24:07.405  7647  7880 V ToneGenerator: Delete Track: 0xb4928a80
09-08 18:24:07.405  7647  7647 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 18:24:07.405   315  2211 V AudioPolicyService: AudioCommandThread() adding release output 2
09-08 18:24:07.405   315  2211 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-08 18:24:07.405   315  2211 V AudioFlinger: PlaybackThread::Track destructor
09-08 18:24:07.405   315  1273 V AudioPolicyService: AudioCommandThread() waking up
09-08 18:24:07.405   315  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
09-08 18:24:07.405   315  2211 V AudioFlinger: removeClient_l() pid 7647, calling pid 315
09-08 18:24:07.405   315  1273 V AudioPolicyManager: releaseOutput() 2
09-08 18:24:07.405   315  1273 V AudioPolicyService: AudioCommandThread() going to sleep
09-08 18:24:07.406  7647  7880 V AudioTrack: ~AudioTrack, releasing session id from 7647 on behalf of 7647
09-08 18:24:07.406   315  1397 V AudioFlinger: releasing 21 from 7647 for 7647
09-08 18:24:07.406   315  1397 V AudioFlinger:  decremented refcount to 0
09-08 18:24:07.406   315  1397 V AudioFlinger: purging stale effects
09-08 18:24:07.406  7647  7647 V Avrcp   : make
09-08 18:24:07.407  7647  7647 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-08 18:24:07.407  7647  7647 I bluedroid-qcom: get_profile_interface avrcp
09-08 18:24:07.416  7647  7647 V AudioManager: registerRemoteController: size of Media player list: 0
,09-08 18:24:07.417  7647  7647 E AudioManager: No RCC entry present to update
09-08 18:24:07.417  7647  7647 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-08 18:24:07.422  7647  7647 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-08 18:24:07.423  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-08 18:24:07.423  7647  7647 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-08 18:24:07.429  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-08 18:24:07.527  1036  1999 V SIM_STK : Menu title from STK is T-Mobile
09-08 18:24:07.527  1036  1999 V SIM_STK : Menu title from STK is T-Mobile
,09-08 18:24:07.598  1036  1577 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-08 18:24:07.616  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-08 18:24:07.627  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-08 18:24:07.628  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-08 18:24:07.628  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-08 18:24:07.628  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-08 18:24:07.629  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 18:24:07.629  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-08 18:24:07.629  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-08 18:24:07.629  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-08 18:24:07.629  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 18:24:07.629  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-08 18:24:07.630  7647  7647 I BluetoothA2dpServiceJni: classInitNative
09-08 18:24:07.630  7647  7647 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 18:24:07.630  7647  7647 D A2dpStateMachine: make
09-08 18:24:07.632  7647  7647 I bluedroid-qcom: get_profile_interface a2dp
09-08 18:24:07.632  7647  7890 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-08 18:24:07.635  7647  7647 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-08 18:24:07.635  7647  7647 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-08 18:24:07.637  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
09-08 18:24:07.637  7647  7889 D A2dpStateMachine: Enter Disconnected: -2
09-08 18:24:07.638  7647  7647 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 18:24:07.641  7647  7647 D HidService: Received start request. Starting profile...
09-08 18:24:07.641  7647  7647 I bluedroid-qcom: get_profile_interface hidhost
09-08 18:24:07.641  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
09-08 18:24:07.642  7647  7647 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 18:24:07.644  7647  7647 D HealthService: Received start request. Starting profile...
,09-08 18:24:07.647  7647  7647 I bluedroid-qcom: get_profile_interface health
,09-08 18:24:07.648  7647  7647 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-08 18:24:07.648  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
09-08 18:24:07.651  7647  7647 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 18:24:07.656  7647  7647 D PanService: Received start request. Starting profile...
09-08 18:24:07.656  7647  7647 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 18:24:07.656  7647  7647 I bluedroid-qcom: get_profile_interface pan
09-08 18:24:07.668  7647  7647 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-08 18:24:07.669  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
09-08 18:24:07.670  7647  7647 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-08 18:24:07.678  7647  7647 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 18:24:07.678  7647  7647 D BtGatt.GattService: Received start request. Starting profile...
09-08 18:24:07.678  7647  7647 D BtGatt.GattService: start()
09-08 18:24:07.679  7647  7647 I bluedroid-qcom: get_profile_interface gatt
09-08 18:24:07.679  7647  7647 D BtGatt.AdvertiseManager: advertise manager created
09-08 18:24:07.689  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
,09-08 18:24:07.694  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
09-08 18:24:07.695  7647  7647 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-08 18:24:07.697  7647  7647 V BluetoothMapService: BluetoothMapBinder()
09-08 18:24:07.698  7647  7647 D BluetoothMapService: Received start request. Starting profile...
09-08 18:24:07.698  7647  7647 D BluetoothMapService: start()
09-08 18:24:07.703  7647  7647 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-08 18:24:07.703  7647  7647 D BluetoothMapEmailAppObserver: createReceiver()
,09-08 18:24:07.707  7647  7647 D BluetoothMapEmailAppObserver: initObservers()
09-08 18:24:07.707  7647  7647 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-08 18:24:07.716  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
09-08 18:24:07.717  7647  7647 D HeadsetStateMachine: Proxy object connected
09-08 18:24:07.718  7647  7647 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-08 18:24:07.718  7647  7647 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-08 18:24:07.721  7647  7880 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-08 18:24:07.722  7647  7880 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 18:24:07.722  7647  7880 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-08 18:24:07.725  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 18:24:07.726  7647  7647 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 18:24:07.726  7647  7647 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 18:24:07.726  7647  7647 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 18:24:07.726  7647  7647 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:07.726  7647  7647 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-08 18:24:07.733  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-08 18:24:07.738  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 18:24:07.741  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 18:24:07.742  7647  7647 V PanService: [BTUI] SIM Extra State :ABSENT
09-08 18:24:07.747  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-08 18:24:07.752  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-08 18:24:07.752  7647  7647 V BluetoothMapService: Handler(): got msg=1
09-08 18:24:07.753  7647  7858 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-08 18:24:07.753  7647  7858 I bluedroid-qcom: enable
09-08 18:24:07.754  7647  7900 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-08 18:24:07.754  7647  7900 I bt-btu  : btu_task pending for preload complete event
09-08 18:24:07.754  7647  7858 I bt_hci_bdroid: init
09-08 18:24:07.755  7647  7858 I bt_vendor: bt-vendor : init
09-08 18:24:07.755  7647  7858 I bt_vendor: bt-vendor : get_bt_soc_type
09-08 18:24:07.755  7647  7858 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-08 18:24:07.755  7647  7858 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-08 18:24:07.755  7647  7858 D bt_userial_mct: userial_init
09-08 18:24:07.756  7647  7858 D bt_hci_bdroid: set_power 1
09-08 18:24:07.756  7647  7858 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-08 18:24:07.756  7647  7858 I bt_vendor: Starting hciattach daemon
09-08 18:24:07.756  7647  7858 I bt_vendor: try to set true
09-08 18:24:07.742  7903  7903 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:07.742  7903  7903 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-08 18:24:07.788  7904  7904 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-08 18:24:07.866  7910  7910 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-08 18:24:07.879  7911  7911 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-08 18:24:07.903  7913  7913 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-08 18:24:07.916  7914  7914 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-08 18:24:07.931  7915  7915 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-08 18:24:07.943  7916  7916 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-08 18:24:07.964  7918  7918 I libmdmdetect: ESOC framework not supported
,09-08 18:24:07.965  7918  7918 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-08 18:24:07.974  7918  7918 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-08 18:24:07.974  7918  7918 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-08 18:24:07.974  7918  7918 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-08 18:24:07.974  7918  7918 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,09-08 18:24:07.974  7918  7918 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-08 18:24:07.974  7918  7918 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-08 18:24:07.974  7918  7918 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-08 18:24:08.014  7918  7919 E QC-QMI  : qmi_client [7918] 15: failed to locate client data
09-08 18:24:08.015   434   434 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-08 18:24:08.015   434   434 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove,
,09-08 18:24:08.043  7920  7920 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-08 18:24:08.058  7921  7921 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-08 18:24:08.111  7647  7858 I bt_vendor: bluetooth satus is on
09-08 18:24:08.111  7647  7858 D bt_hci_bdroid: preload
,09-08 18:24:08.111  7647  7902 D bt_userial_mct: userial_open(port:0)
09-08 18:24:08.111  7647  7902 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-08 18:24:08.116  7647  7902 I bt_vendor: Done intiailizing UART
,09-08 18:24:08.119  7647  7902 I bt_vendor: Done intiailizing UART
09-08 18:24:08.119  7647  7902 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-08 18:24:08.119  7647  7902 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-08 18:24:08.120  7647  7923 D bt_userial_mct: Entering userial_read_thread()
09-08 18:24:08.120  7647  7900 I bt-btu  : btu_task received preload complete event
09-08 18:24:08.120  7647  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-08 18:24:08.120  7647  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-08 18:24:08.124  7647  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_HCI
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_A2D
,09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 18:24:08.129  7647  7900 I         : BTE_InitTraceLevels -- TRC_BTIF
09-08 18:24:08.199  7647  7900 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-08 18:24:08.199  7647  7900 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ff061 
09-08 18:24:08.199  7647  7900 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ff061 
,09-08 18:24:08.251  7647  7862 E bt-btif : Calling BTA_HhEnable
,09-08 18:24:08.251  7647  7862 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-08 18:24:08.251  7647  7862 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-08 18:24:08.256  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-08 18:24:08.257  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
09-08 18:24:08.257  7647  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-08 18:24:08.257  7647  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-08 18:24:08.257  7647  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-08 18:24:08.257  7647  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-08 18:24:08.257  7647  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-08 18:24:08.258  7647  7862 D BluetoothAdapterProperties: Name is: G3
09-08 18:24:08.260  7647  7862 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:24:08.260  7647  7862 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:24:08.260  7647  7862 D bt_hci_bdroid: postload
09-08 18:24:08.261  7647  7862 D bte_conf: Device ID record 1 : primary
09-08 18:24:08.261  7647  7862 D bte_conf:   vendorId            = 00c4
09-08 18:24:08.261  7647  7862 D bte_conf:   vendorIdSource      = 0001
09-08 18:24:08.261  7647  7862 D bte_conf:   product             = 13a1
09-08 18:24:08.261  7647  7862 D bte_conf:   version             = 1000
09-08 18:24:08.261  7647  7862 D bte_conf:   clientExecutableURL = 
09-08 18:24:08.261  7647  7862 D bte_conf:   serviceDescription  = 
09-08 18:24:08.261  7647  7862 D bte_conf:   documentationURL    = 
09-08 18:24:08.261  7647  7862 D bte_conf: bte_load_did_conf no section named DID2.
09-08 18:24:08.262  7647  7902 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 18:24:08.262  7647  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-08 18:24:08.265  7647  7858 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-08 18:24:08.265  7647  7858 D BluetoothAdapterProperties: ScanMode =  20
09-08 18:24:08.265  7647  7858 D BluetoothAdapterProperties: State =  11
09-08 18:24:08.265  7647  7858 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-08 18:24:08.266  7647  7858 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-08 18:24:08.266  7647  7858 D BluetoothAdapterProperties: Setting state to 12
09-08 18:24:08.266  7647  7858 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 18:24:08.271  7647  7862 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 18:24:08.262  7928  7928 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:08.274  1036  1118 D BluetoothManagerService: Message: 60
09-08 18:24:08.274  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-08 18:24:08.274  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-08 18:24:08.275  7647  7902 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 18:24:08.271  7647  7862 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-08 18:24:08.262  7928  7928 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:08.279  7647  7902 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 18:24:08.281  7647  7902 D bt_hci_bdroid: Used up Tx Cmd credits
,09-08 18:24:08.285  7647  7923 E bt_mct  : hci lib postload completed
09-08 18:24:08.297  7647  7900 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 18:24:08.297  7647  7900 W bt-smp  : Plain text(LSB ~ MSB) = e1 0a 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 18:24:08.297  7647  7900 W bt-smp  : Encrypted text(LSB ~ MSB) = 03 cc 41 b8 1b b1 5a 7b 98 13 08 a8 9a a2 d3 33 
,09-08 18:24:08.300  7647  7900 W bt-btm  : Stopping oneshot timer
09-08 18:24:08.310  7647  7858 I BluetoothAdapterState: Entering On State
,09-08 18:24:08.319  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:08.319  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:08.319  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:24:08.319  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:08.319  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:08.319  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:08.319  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:08.319  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:24:08.321  7647  7862 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:24:08.325  7647  7862 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-08 18:24:08.336  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:24:08.343  7647  7858 D LGBluetoothServiceAdapter: [BTUI] OnState
09-08 18:24:08.343  7647  7858 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-08 18:24:08.343  7647  7858 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-08 18:24:08.346  7647  7900 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-08 18:24:08.346  7647  7900 W bt-smp  : Plain text(LSB ~ MSB) = d2 10 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
,09-08 18:24:08.346  7647  7900 W bt-smp  : Encrypted text(LSB ~ MSB) = 21 5a 48 85 e4 2b 43 e6 f5 1b f3 65 16 f3 ba db 
09-08 18:24:08.346  7647  7900 W bt-btm  : Stopping oneshot timer
09-08 18:24:08.347  7647  7858 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-08 18:24:08.374  7647  7858 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-08 18:24:08.383  6818  6841 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 18:24:08.390  7942  7942 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-08 18:24:08.395  6818  6844 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 18:24:08.398  6818  6818 D BluetoothHeadset: Proxy object connected
09-08 18:24:08.398  6818  6818 D HeadsetProfile: Bluetooth service connected
,09-08 18:24:08.399  1853  3996 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:08.401  1853  1853 D BluetoothHeadset: Proxy object connected
09-08 18:24:08.401  6818  6841 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 18:24:08.404  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:08.404  1036  1036 D BluetoothHeadset: Proxy object connected
09-08 18:24:08.405  7647  7900 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 18:24:08.405  7647  7900 W bt-smp  : Plain text(LSB ~ MSB) = 3d b3 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 18:24:08.405  7647  7900 W bt-smp  : Encrypted text(LSB ~ MSB) = de 8d d3 8c 02 26 db df dc c8 4c 39 48 08 09 14 
09-08 18:24:08.405  7647  7900 W bt-btm  : Stopping oneshot timer
,09-08 18:24:08.409  6818  6818 D BluetoothInputDevice: Proxy object connected
09-08 18:24:08.409  6818  6818 D HidProfile: Bluetooth service connected
09-08 18:24:08.409  1853  2465 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:08.411  1853  1853 D BluetoothHeadset: Proxy object connected
09-08 18:24:08.411  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:24:08.413  6818  6844 D BluetoothPan: onBluetoothStateChange on: true
09-08 18:24:08.413  6818  6844 D BluetoothPan: onBluetoothStateChange call bindService
09-08 18:24:08.414  1036  1036 D BluetoothA2dp: Proxy object connected
09-08 18:24:08.414  7647  7900 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 18:24:08.414  7647  7900 W bt-smp  : Plain text(LSB ~ MSB) = ff f2 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 18:24:08.414  7647  7900 W bt-smp  : Encrypted text(LSB ~ MSB) = 03 5b 33 f3 38 db ae 76 de ae 41 40 9d 10 7a 5c 
09-08 18:24:08.414  7647  7900 W bt-btm  : Stopping oneshot timer
09-08 18:24:08.417  6818  6841 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 18:24:08.418  6818  6818 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:24:08.418  6818  6818 D PanProfile: Bluetooth service connected
09-08 18:24:08.423  6818  7944 D BluetoothMap: onBluetoothStateChange: up=true
09-08 18:24:08.424  6818  6818 D BluetoothA2dp: Proxy object connected
09-08 18:24:08.424  6818  6818 D A2dpProfile: Bluetooth service connected
09-08 18:24:08.425  1853  3988 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:08.426  7647  7900 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 18:24:08.427  7647  7900 W bt-smp  : Plain text(LSB ~ MSB) = ca 14 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 18:24:08.427  7647  7900 W bt-smp  : Encrypted text(LSB ~ MSB) = c7 d5 19 5f 6a 39 0b 89 3c ae bd 24 4e a4 96 bc 
09-08 18:24:08.427  7647  7900 W bt-btm  : Stopping oneshot timer
09-08 18:24:08.427  6818  6818 D BluetoothMap: Proxy object connected
09-08 18:24:08.427  6818  6818 D MapProfile: Bluetooth service connected
09-08 18:24:08.427  6818  6818 D BluetoothMap: getConnectedDevices()
09-08 18:24:08.428  7647  7664 V BluetoothMapService: getConnectedDevices()
09-08 18:24:08.428  1853  1853 D BluetoothHeadset: Proxy object connected
09-08 18:24:08.429  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-08 18:24:08.429  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-08 18:24:08.432  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:08.433  1942  2102 D LGBluetoothAPIService: Message: 1
09-08 18:24:08.433  1942  2102 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-08 18:24:08.433  1942  2102 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-08 18:24:08.433  1942  2102 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-08 18:24:08.435  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 18:24:08.439  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-08 18:24:08.439  1036  1118 D BluetoothManagerService: Message: 40
09-08 18:24:08.439  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-08 18:24:08.444  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:08.448  7647  7647 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:08.448  7647  7647 D BluetoothMapService: STATE_ON
09-08 18:24:08.448  7647  7647 V BluetoothMapService: Handler(): got msg=1
09-08 18:24:08.449  7647  7647 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-08 18:24:08.451  6818  6818 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-08 18:24:08.453  6818  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-08 18:24:08.462  7647  7950 D BluetoothMapMasInstance: MAS initSocket()
09-08 18:24:08.462  7647  7950 D BluetoothMapMasInstance:   masId = 00
09-08 18:24:08.462  7647  7950 D BluetoothMapMasInstance:   msgTypes = 0e
09-08 18:24:08.462  7647  7950 D BluetoothMapMasInstance:   masName = SMS/MMS
09-08 18:24:08.462  7647  7950 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,09-08 18:24:08.463  6818  6818 D DockEventReceiver: finishStartingService: stopping service
09-08 18:24:08.463  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:08.465  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
09-08 18:24:08.465  7647  7647 V BluetoothPbapService: Pbap Service onCreate
09-08 18:24:08.465  7647  7647 V BluetoothPbapService: Starting PBAP service
09-08 18:24:08.467  7647  7647 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-08 18:24:08.467  7647  7647 V BluetoothPbapService: Pbap Service onBind
09-08 18:24:08.468  7647  7950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:24:08.469  6818  6818 D BluetoothPbap: Proxy object connected
09-08 18:24:08.469  6818  6818 D PbapServerProfile: Bluetooth service connected
09-08 18:24:08.469  7647  7647 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:08.469  7647  7647 V BluetoothPbapService: state: 12
09-08 18:24:08.470  7647  7647 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 18:24:08.470  7647  7647 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:08.470  7647  7950 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-08 18:24:08.470  7647  7647 V BluetoothPbapReceiver: ***********state = 12
09-08 18:24:08.470  7647  7950 V BluetoothMapMasInstance: Succeed to create listening socket 
09-08 18:24:08.470  7647  7950 D BluetoothMapMasInstance: Accepting socket connection...
09-08 18:24:08.471  7647  7862 D BluetoothAdapterProperties: Scan Mode:21
09-08 18:24:08.471  7647  7862 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-08 18:24:08.472  7647  7647 V BluetoothPbapService: Handler(): got msg=1
09-08 18:24:08.473  7647  7647 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-08 18:24:08.473  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:08.474  7647  7953 V BluetoothPbapService: Pbap Service initSocket
09-08 18:24:08.474  1036  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:08.475  2082  2082 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:24:08.475  7647  7953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:08.476  2082  2082 D c       : Getting all permits...
09-08 18:24:08.476  2082  2082 D a       : Opening database...
,09-08 18:24:08.476  7647  7953 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-08 18:24:08.476  7647  7953 V BluetoothPbapService: Succeed to create listening socket 
09-08 18:24:08.476  7647  7953 V BluetoothPbapService: Accepting socket connection...
09-08 18:24:08.480  2082  2082 D a       : Opening database auth.proximity.permit_store...
09-08 18:24:08.481  2082  2082 D a       : Closing database...
09-08 18:24:08.491  6818  6818 D BluetoothPermissionRequest: onReceive
,09-08 18:24:08.493  6818  6818 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-08 18:24:08.495  6818  6818 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 18:24:08.499  7647  7647 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-08 18:24:08.500  7647  7647 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-08 18:24:08.507  7647  7647 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-08 18:24:08.526  7647  7647 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-08 18:24:08.526  7647  7647 V BtOppService: onCreate
,09-08 18:24:08.531  7647  7647 V BluetoothOppNotification: send message
09-08 18:24:08.534  7647  7647 V BtOppService: Starting RfcommListener
09-08 18:24:08.543  7647  7647 D BluetoothOppPreference: Dumping Names:  
09-08 18:24:08.543  7647  7647 D BluetoothOppPreference: {}
,09-08 18:24:08.544  7647  7647 D BluetoothOppPreference: Dumping Channels:  
09-08 18:24:08.544  7647  7647 D BluetoothOppPreference: {}
,09-08 18:24:08.548  7647  7647 V BtOppService: onStartCommand
09-08 18:24:08.552  7647  7960 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-08 18:24:08.555  7647  7647 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:08.555  7647  7647 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-08 18:24:08.559  7647  7647 V BluetoothOppNotification: new notify threadi!
09-08 18:24:08.561  7647  7647 V BluetoothOppNotification: send delay message
,09-08 18:24:08.563  7647  7957 V BtOppService: Deleted complete outbound shares, number =  0
09-08 18:24:08.563  7647  7647 V BtOppService: start RfcommListener
09-08 18:24:08.566  7647  7957 V BtOppService: Deleted complete inbound failed shares, number = 0
09-08 18:24:08.567  7647  7957 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-08 18:24:08.568  7647  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-08 18:24:08.570  7647  7957 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a02ad4d on behalf of 
09-08 18:24:08.570  7647  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a7f7002 on behalf of 
09-08 18:24:08.571  7647  7647 V BtOppService: RfcommListener started
09-08 18:24:08.573  7647  7961 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-08 18:24:08.574  7647  7960 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-08 18:24:08.578  7647  7962 V BtOppRfcommListener: Starting RFCOMM listener....
09-08 18:24:08.578  7647  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-08 18:24:08.578  1036  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:08.580  7647  7962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:24:08.583  7647  7962 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-08 18:24:08.583  7647  7960 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fef7d13 on behalf of 
09-08 18:24:08.583  7647  7962 V BtOppRfcommListener: Started RFCOMM listener....
09-08 18:24:08.583  7647  7962 I BtOppRfcommListener: Accept thread started.
09-08 18:24:08.583  7647  7962 V BtOppRfcommListener: Accepting connection...
09-08 18:24:08.585  7647  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20c63b50 on behalf of 
09-08 18:24:08.586  7647  7960 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-08 18:24:08.587  7647  7961 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-08 18:24:08.590  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
09-08 18:24:08.590  7647  7647 V BluetoothFtpService: Ftp Service onCreate
09-08 18:24:08.590  7647  7647 I BluetoothFtpService: Ftp Service onCreate
09-08 18:24:08.590  7647  7647 V BluetoothFtpService: Ftp Service onStartCommand
09-08 18:24:08.590  7647  7647 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:08.590  7647  7647 V BluetoothFtpService: Starting Listening on sockets
09-08 18:24:08.591  7647  7647 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 18:24:08.591  7647  7647 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 18:24:08.591  7647  7647 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 18:24:08.591  7647  7647 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:08.591  7647  7647 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-08 18:24:08.591  7647  7647 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-08 18:24:08.593  7647  7961 V BluetoothOppNotification: outbound notification was removed.
09-08 18:24:08.593  7647  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-08 18:24:08.595  7647  7647 V BtOppService: ContentObserver received notification
09-08 18:24:08.595  7647  7647 V BtOppService: ContentObserver received notification
09-08 18:24:08.595  7647  7647 V BluetoothFtpService: Handler(): got msg=1
09-08 18:24:08.597  7647  7647 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-08 18:24:08.597  7647  7647 V BluetoothFtpService: Ftp Service initSocket
09-08 18:24:08.600  7647  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d788a4e on behalf of 
,09-08 18:24:08.602  7647  7963 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-08 18:24:08.602  7647  7963 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-08 18:24:08.602  7647  7961 V BluetoothOppNotification: inbound: succ-0  fail-0
09-08 18:24:08.604  7647  7963 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ccad76f on behalf of 
09-08 18:24:08.605  1036  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:08.605  7647  7963 V BluetoothOppNotification: update too frequent, put in queue
09-08 18:24:08.607  7647  7647 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:24:08.608  7647  7963 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-08 18:24:08.608  7647  7961 V BluetoothOppNotification: inbound notification was removed.
09-08 18:24:08.608  7647  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-08 18:24:08.610  7647  7647 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-08 18:24:08.611  7647  7647 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-08 18:24:08.614  7647  7964 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-08 18:24:08.633  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e68ac1
,09-08 18:24:08.634  7647  7647 V BluetoothSapService: Sap Service onCreate
09-08 18:24:08.636  7647  7647 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:24:08.636  7647  7647 V BluetoothSapService: state: 12
09-08 18:24:08.636  7647  7647 V BluetoothSapService: Starting SAP server process
,09-08 18:24:08.639  7647  7647 V BluetoothSapService: SAP Service startRfcommListenerThread
,09-08 18:24:08.622  7965  7965 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:08.640  7647  7966 V BluetoothSapService: Sap Service initRfcommSocket
09-08 18:24:08.622  7965  7965 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:08.641  1036  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:08.642  7647  7966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:24:08.643  7647  7966 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-08 18:24:08.643  7647  7966 V BluetoothSapService: Succeed to create listening socket 
09-08 18:24:08.643  7647  7966 V BluetoothSapService: Accepting socket connection...
09-08 18:24:08.650  7965  7965 V BT_SAP  : Event pipe created
09-08 18:24:08.650  7965  7965 V BT_SAP  : create_server_socket qcom.sap.server
09-08 18:24:08.650  7965  7965 V BT_SAP  : created socket fd 6
,09-08 18:24:08.760  1036  1699 I art     : Explicit concurrent mark sweep GC freed 24480(1208KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.904ms total 147.767ms
,09-08 18:24:08.761  7647  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f577b8b on behalf of 
,09-08 18:24:09.251  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:09.251  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:09.251  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:24:09.251  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:09.251  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:09.251  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:09.251  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:09.251  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:09.259  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:24:09.260  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:09.260  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d58edfa added. We now have 8 listener(s)
09-08 18:24:09.260  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:09.263  1036  1988 D WifiServiceImplEx: setWifiEnabled: false pid=6609, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 18:24:09.264  1036  1988 D WifiService: setWifiEnabled: false pid=6609, uid=10118
09-08 18:24:09.264  1036  1988 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-08 18:24:09.268  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:09.273  1036  1052 D WifiServiceImplEx: setWifiEnabled: true pid=6609, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 18:24:09.273  1036  1052 D WifiService: setWifiEnabled: true pid=6609, uid=10118
09-08 18:24:09.273  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:24:09.294  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 18:24:09.294  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 18:24:09.294  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-08 18:24:09.296  1036  1436 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-08 18:24:09.296  1036  1436 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-08 18:24:09.298  1036  1436 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-08 18:24:09.298  1036  1436 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 18:24:09.298  1036  1436 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-08 18:24:09.299  1036  1436 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 18:24:09.299  1036  1436 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-08 18:24:09.299  1036  1436 E WifiHW  : unknown target_country: EU , set to default
09-08 18:24:09.299  1036  1436 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-08 18:24:09.299  1036  1436 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-08 18:24:09.299  1036  1436 I WifiUtil: gEnableBmps=1
09-08 18:24:09.562  7647  7647 V BluetoothOppNotification: new notify threadi!
09-08 18:24:09.562  7647  7647 V BluetoothOppNotification: send delay message
,09-08 18:24:09.566  7647  7980 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-08 18:24:09.567  7647  7980 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18662468 on behalf of 
,09-08 18:24:09.568  7647  7980 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-08 18:24:09.568  7647  7980 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-08 18:24:09.569  7647  7980 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13056081 on behalf of 
,09-08 18:24:09.569  7647  7980 V BluetoothOppNotification: outbound: succ-0  fail-0
09-08 18:24:09.571  7647  7980 V BluetoothOppNotification: outbound notification was removed.
09-08 18:24:09.571  7647  7980 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-08 18:24:09.571  7647  7980 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21779526 on behalf of 
09-08 18:24:09.572  7647  7980 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-08 18:24:09.573  7647  7980 V BluetoothOppNotification: inbound notification was removed.
09-08 18:24:09.573  7647  7980 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-08 18:24:09.573  7647  7980 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30c04567 on behalf of 
09-08 18:24:09.973   309   893 D SoftapController: Softap fwReload - Ok
,09-08 18:24:10.102  1036  1436 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (798ms)
,09-08 18:24:10.107   309   893 D CommandListener: Setting iface cfg
09-08 18:24:10.107   309   893 D CommandListener: Trying to bring down wlan0
09-08 18:24:10.108  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:24:10.108  1036  1118 D Tethering: InitialState.processMessage what=4
09-08 18:24:10.108   309   893 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:24:10.109  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:24:10.113  1036  1436 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-08 18:24:10.114  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 18:24:10.114  6818  6818 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 18:24:10.114  6818  6818 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 18:24:10.114  6818  6818 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 18:24:10.115  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 18:24:10.115  1036  1436 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 18:24:10.115  1036  1436 E WifiStateMachine: useWiFiOffloading() : false
09-08 18:24:10.115  1036  1436 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-08 18:24:10.102  8003  8003 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:10.102  8003  8003 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:10.122  1036  1436 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-08 18:24:10.122  1036  1436 D WifiMonitor: connecting to supplicant
09-08 18:24:10.124  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-08 18:24:10.125  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:10.127  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-08 18:24:10.131  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:10.135  6818  6818 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 18:24:10.135  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,09-08 18:24:10.135  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 18:24:10.135  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 18:24:10.136  6818  6818 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 18:24:10.136  6818  6818 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 18:24:10.138  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 18:24:10.138  6818  6818 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 18:24:10.138  6818  6818 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 18:24:10.138  6818  6818 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 18:24:10.138  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 18:24:10.139  6818  6818 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 18:24:10.139  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-08 18:24:10.139  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 18:24:10.139  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 18:24:10.139  6818  6818 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 18:24:10.139  6818  6818 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-08 18:24:10.142  8003  8003 I wpa_supplicant: Successfully initialized wpa_supplicant
09-08 18:24:10.175  1036  2028 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8005 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-08 18:24:10.176  8003  8003 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 18:24:10.177  8003  8003 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-08 18:24:10.193   335   335 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 296us total 14.721ms
,09-08 18:24:10.207   335   335 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 264us total 13.104ms
,09-08 18:24:10.219   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 11.669ms
,09-08 18:24:10.249  8003  8003 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 18:24:10.252  1036  2028 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8027 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-08 18:24:10.259  8005  8024 W FormManager: Network not available. Please check & try again.
09-08 18:24:10.266  8005  8025 V FormManager: Network unavailable.
,09-08 18:24:10.268  8005  8025 V FormManager: Network unavailable.
09-08 18:24:10.287  1036  1577 I ActivityManager: Killing 7151:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-08 18:24:10.305  8003  8003 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-08 18:24:10.310  8003  8003 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-08 18:24:10.312  1036  1436 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-08 18:24:10.313  1036  1436 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-08 18:24:10.313  1036  1436 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-08 18:24:10.314  1036  1436 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-08 18:24:10.314  1036  1436 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:24:10.315  1036  1436 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:24:10.315  1036  1436 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-08 18:24:10.315  1036  1436 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-08 18:24:10.315  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-08 18:24:10.315  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-08 18:24:10.315  1036  8045 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-08 18:24:10.315  1036  8045 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-08 18:24:10.316  1036  1436 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-08 18:24:10.316  1036  1436 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-08 18:24:10.316  1036  1436 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-08 18:24:10.328  1036  2028 W libprocessgroup: failed to open /acct/uid_10062/pid_7151/cgroup.procs: No such file or directory
09-08 18:24:10.331  1036  1436 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 18:24:10.331  1036  1436 E WifiStateMachine: useWiFiOffloading() : false
09-08 18:24:10.331  1036  1436 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 18:24:10.332  1036  1436 D WifiNative-wlan0: doBoolean: SET update_config 1
09-08 18:24:10.332  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:10.333  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:10.333  1036  1436 D WifiNative-wlan0: SET update_config 1: returned true
09-08 18:24:10.333  1036  1436 D WifiConfigStore: Loading config and enabling all networks 
09-08 18:24:10.333  1036  1436 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-08 18:24:10.333  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:10.333  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:10.333  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 18:24:10.334  1036  1436 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-08 18:24:10.335  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:10.336  1942  1942 D WfdService: Waiting for WifiP2p enabling
09-08 18:24:10.338  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-08 18:24:10.338  1036  1450 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-08 18:24:10.339  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:10.339  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:10.339  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:24:10.339  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:10.339  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:10.339  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:10.339  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:10.339  6609  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:24:10.342  6609  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:24:10.344  1036  1436 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-08 18:24:10.356  1036  1436 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-08 18:24:10.356  1036  1436 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-08 18:24:10.357  1036  1436 D WifiStateMachine: enableVerboseLogging : level 2
09-08 18:24:10.357  1036  1436 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-08 18:24:10.358  1036  1436 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-08 18:24:10.358  1036  1436 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-08 18:24:10.358  1036  1436 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-08 18:24:10.358  1036  1436 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-08 18:24:10.359  1036  1436 D WifiN,ative-wlan0: SET model_name LG-D855: returned true
09-08 18:24:10.359  1036  1436 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-08 18:24:10.359  1036  1436 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-08 18:24:10.359  1036  1436 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-08 18:24:10.359  1036  1436 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-08 18:24:10.360  1036  1436 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-08 18:24:10.360  1036  1436 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-08 18:24:10.360  1036  1436 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-08 18:24:10.360  1036  1436 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,09-08 18:24:10.361  1036  1436 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 18:24:10.361  1036  1436 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-08 18:24:10.361  1942  1942 D WfdsService: Supplicant Connection state is changed : true
09-08 18:24:10.361  1036  1436 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-08 18:24:10.362  1036  1436 D WifiNative-HAL: Setting external_sim to 1
09-08 18:24:10.362  1036  1436 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-08 18:24:10.362  1942  2243 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-08 18:24:10.362  1942  2243 D WfdsService: Set the WFDS Monitor: true
09-08 18:24:10.362  1942  2243 D WfdsMonitor: WfdsMonitorThread create
09-08 18:24:10.362  1036  1436 D WifiNative-wlan0: SET external_sim 1: returned true
,09-08 18:24:10.362  1036  1436 I WifiNative-HAL: startHal
09-08 18:24:10.362  1036  1436 D wifi    : setting scan oui 0xaf66c540
09-08 18:24:10.363  1036  1436 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 18:24:10.363  1942  2243 D WfdsMonitor: WFDS Monitor is created and started
09-08 18:24:10.363  1036  1436 I WifiNative-HAL: startHal
09-08 18:24:10.363  1942  2243 D WfdsService: WiFi: Supplicant connection re-established
09-08 18:24:10.363  1036  1436 D wifi    : setting scan oui 0xaf66c540
09-08 18:24:10.363  1036  1436 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-08 18:24:10.363  7679  7679 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:10.364  1942  8047 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-08 18:24:10.364  1942  8047 E CtrlSupplicant: Succeed to open control connection
09-08 18:24:10.364  1036  1436 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-08 18:24:10.364  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-08 18:24:10.364  1942  8047 E CtrlSupplicant: Succeed to open monitor connection
09-08 18:24:10.365  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-08 18:24:10.365  1036  1436 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-08 18:24:10.365  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 18:24:10.366  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 18:24:10.366  1942  8047 D WfdsMonitor: Supplicant connection established
09-08 18:24:10.366  1942  2243 D WfdsService: Connected to the supplicant for wfds
09-08 18:24:10.366  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 18:24:10.366  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-08 18:24:10.366  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-08 18:24:10.367  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-08 18:24:10.367  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 18:24:10.367  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 18:24:10.367  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 18:24:10.367  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 18:24:10.367  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 18:24:10.368  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 18:24:10.368  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-08 18:24:10.368  8003  8003 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-08 18:24:10.369  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-08 18:24:10.369  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 18:24:10.369  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 18:24:10.369  1036  1436 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 18:24:10.370  1036  1436 E WifiNative: : [136,145,353 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-08 18:24:10.370  1036  1436 D WifiNative-wlan0: doBoolean: RECONNECT
09-08 18:24:10.371  1036  1436 D WifiNative-wlan0: RECONNECT: returned true
09-08 18:24:10.371  1036  1436 D WifiNative-wlan0: doString: [STATUS]
09-08 18:24:10.371  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-08 18:24:10.372  1036  1436 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-08 18:24:10.372  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 18:24:10.372  1036  1436 D WifiNa,tive-wlan0: doBoolean: SET ps 1
09-08 18:24:10.373  1036  1436 D WifiNative-wlan0: SET ps 1: returned true
09-08 18:24:10.373  1036  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.374  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 18:24:10.374  1036  1436 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-08 18:24:10.374  1036  1036 D RttService: SCAN_AVAILABLE : 3
09-08 18:24:10.374  1036  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.374  1036  1558 I WifiNative-HAL: startHal
09-08 18:24:10.374  1036  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf66c540
09-08 18:24:10.374  1036  1558 D wifi    : failed to get capabilities : -3
09-08 18:24:10.374  1036  1558 E WifiScanningService: could not get scan capabilities
09-08 18:24:10.374  1036  1436 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-08 18:24:10.374  1036  1559 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.374   309   893 D CommandListener: Setting iface cfg
09-08 18:24:10.375   309   893 D CommandListener: Trying to bring up p2p0
09-08 18:24:10.375  1036  1436 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-08 18:24:10.375  1036  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 18:24:10.375  1036  1390 D LGWifiP2pService: P2pEnablingState
09-08 18:24:10.375  1036  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.375  1036  1390 D LGWifiP2pService: P2p socket connection successful
09-08 18:24:10.375  1036  1390 D LGWifiP2pService: P2pEnabledState
09-08 18:24:10.375  1036  1436 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-08 18:24:10.375  1036  1390 D LGWifiP2pService: sending p2p connection changed broadcast
09-08 18:24:10.375  1036  1436 E WifiStateMachine:  DisconnectedState what:132106 1 0,
09-08 18:24:10.376  1036  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-08 18:24:10.376  1036  1436 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-08 18:24:10.376  1036  1436 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-08 18:24:10.376  1036  1436 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-08 18:24:10.377  8003  8003 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-08 18:24:10.377  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-08 18:24:10.377  1942  1942 D WfdsService: WifiP2pState is changed : true
09-08 18:24:10.377  1942  2243 D WfdsService: Receive the WFDS_ENABLE Method
,09-08 18:24:10.377  1942  2243 D WfdsService: Set the WFDS Monitor: true
09-08 18:24:10.377  1036  1436 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-08 18:24:10.377  1942  2243 D WfdsService: Connected to the supplicant for wfds
09-08 18:24:10.377  1942  2243 D WfdsJNI : doCommand: WFDS_SET TRUE
09-08 18:24:10.377  8003  8003 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-08 18:24:10.377  1942  2243 D WfdsService: selectPreferredScanChannel [36]
09-08 18:24:10.377  1942  2243 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-08 18:24:10.377  1036  1436 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,09-08 18:24:10.378  1036  1436 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-08 18:24:10.378  1036  1436 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-08 18:24:10.378  8003  8003 E wpa_supplicant: disconnect_rssi_lvl: -100
09-08 18:24:10.378  1036  1436 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-08 18:24:10.379  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-08 18:24:10.379  1036  1436 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-08 18:24:10.379  1942  1942 D WfdsService: isConnected: false
09-08 18:24:10.379  1036  1436 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-08 18:24:10.379  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,09-08 18:24:10.380  1036  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-08 18:24:10.381  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 18:24:10.381  8003  8003 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:24:10.382  8003  8003 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 18:24:10.383  8003  8003 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.383  8003  8003 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.384  1942  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-08 18:24:10.384  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 18:24:10.385  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:24:10.385  1036  8045 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:24:10.385  8027  8027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:24:10.385  1942  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:24:10.385  1036  8045 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:24:10.385  1036  8045 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:24:10.386  1036  8045 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.386  1036  8045 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.386  1036  8045 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-08 18:24:10.386  1036  8045 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:24:10.386  1036  8045 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.386  1036  8045 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.386  1036  8045 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.386  1036  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
09-08 18:24:10.387  1036  1436 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-08 18:24:10.387  1036  1390 D WifiNative-p2p0: SET device_name G3: returned true
09-08 18:24:10.387  1036  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
,09-08 18:24:10.387  1036  1390 D LGWifiP2pService: before postfix = G3
09-08 18:24:10.387  1036  1390 D WifiServerServiceExt: postfix byte check : 2
09-08 18:24:10.388  1036  1390 D LGWifiP2pService: after postfix = G3
09-08 18:24:10.388  1036  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-08 18:24:10.388  1036  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-08 18:24:10.388  1036  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-08 18:24:10.388  1036  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
,09-08 18:24:10.388  1036  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-08 18:24:10.389  1036  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-08 18:24:10.389  1036  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-08 18:24:10.389  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 18:24:10.389  1036  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-08 18:24:10.389  1036  1390 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 18:24:10.390  1036  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,09-08 18:24:10.390  1036  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-08 18:24:10.390  1036  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-08 18:24:10.391  1036  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
09-08 18:24:10.391  1036  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-08 18:24:10.392  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
09-08 18:24:10.392  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-08 18:24:10.392  1942  1942 D WfdsService: Update P2p Interface State: 3
09-08 18:24:10.392  1036  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-08 18:24:10.392  1036  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-08 18:24:10.393  1036  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-08 18:24:10.393  1036  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,09-08 18:24:10.394  1036  1436 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-08 18:24:10.395  1036  1436 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-08 18:24:10.395  1036  1436 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-08 18:24:10.395  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-08 18:24:10.397  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:10.398  1036  1940 I ActivityManager: Killing 7171:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-08 18:24:10.402  1036  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-08 18:24:10.402  1036  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-08 18:24:10.402  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-08 18:24:10.402  8003  8003 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 18:24:10.403  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-08 18:24:10.403  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 18:24:10.403  1036  8045 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 18:24:10.403  1036  8045 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 18:24:10.404  1036  1436 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-08 18:24:10.404  1036  1436 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-08 18:24:10.404  1036  1436 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-08 18:24:10.404  1036  1436 D WifiNative-wlan0: doBoolean: SCAN
09-08 18:24:10.404  1036  1436 D WifiNative-wlan0: SCAN: returned false
09-08 18:24:10.404  1036  1436 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=136180  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-08 18:24:10.428  1036  1390 D LGWifiP2pService: InactiveState
,09-08 18:24:10.428  1036  1390 D LGWifiP2pService: InactiveState{ when=-36ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:24:10.428  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-36ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.428  1036  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-08 18:24:10.429  1036  1959 W libprocessgroup: failed to open /acct/uid_10085/pid_7171/cgroup.procs: No such file or directory
09-08 18:24:10.429  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 18:24:10.429  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=136205  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 18:24:10.429  8003  8003 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:24:10.429  1036  1436 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 18:24:10.430  8003  8003 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 18:24:10.430  8003  8003 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.430  1036  1436 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 18:24:10.430  8003  8003 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.431  1942  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 18:24:10.431  1942  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:24:10.431  1942  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:24:10.431  1036  8045 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 18:24:10.431  1036  8045 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:24:10.431  1036  8045 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:24:10.431  1036  8045 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 18:24:10.431  1036  8045 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:24:10.431  1036  8045 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.431  1036  8045 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.431  1036  8045 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.431  1036  8045 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 18:24:10.431  1036  8045 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.431  1036  8045 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.431  1036  8045 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 18:24:10.432  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:24:10.432  1036  1436 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 18:24:10.432  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:24:10.432  1036  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-08 18:24:10.432  1036  1390 D LGWifiP2pService: InactiveState{ when=-38ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.432  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-38ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.432  1036  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.,StateMachine$SmHandler }
09-08 18:24:10.432  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.432  1036  1436 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 18:24:10.432  1036  1390 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.433  1036  1390 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.433  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.433  1036  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.433  1036  1390 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.433  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.433  1036  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.433  1036  1390 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.433  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.433  1036  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:10.433  1036  1036 E WifiServerServiceExt: No p2p device connected
09-08 18:24:10.434  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:10.434  1942  2243 W WfdsService: DefaultState - msg [9441285] is not handled
09-08 18:24:10.434  1036  1436 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 18:24:10.434  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:10.435  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:10.435  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 18:24:10.436  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:24:10.436  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 18:24:10.447  8027  8027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 18:24:10.450  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 18:24:10.456  8005  8051 W FormManager: Network not available. Please check & try again.
09-08 18:24:10.458  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:10.459  8005  8052 V FormManager: Network unavailable.
09-08 18:24:10.465  8005  8052 V FormManager: Network unavailable.
,09-08 18:24:10.472  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-08 18:24:10.473  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 18:24:10.474  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:24:10.477  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 18:24:10.482  4291  8053 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 18:24:10.493  4291  8054 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 18:24:10.493  4291  8054 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 18:24:10.525  1036  1699 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8055 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-08 18:24:10.649  8055  8055 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-08 18:24:10.649  8055  8055 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-08 18:24:10.658  8055  8055 V [BNRBootReceiver]: Boot Receiver Return
09-08 18:24:10.659  8055  8055 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-08 18:24:10.736  1036  2033 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8076 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 18:24:10.737  1036  2033 I ActivityManager: Killing 7199:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-08 18:24:10.949  1036  1887 W libprocessgroup: failed to open /acct/uid_10093/pid_7199/cgroup.procs: No such file or directory
,09-08 18:24:10.989  8076  8076 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 18:24:11.005  8003  8003 E wpa_supplicant: USIM:  scard_init function
09-08 18:24:11.005  8003  8003 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-08 18:24:11.011  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-08 18:24:11.011  1036  8045 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-08 18:24:11.011  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-08 18:24:11.011  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
09-08 18:24:11.011  1036  8045 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-08 18:24:11.011  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-08 18:24:11.013  1036  1436 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-08 18:24:11.013  1036  1436 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-08 18:24:11.014  1036  1436 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-08 18:24:11.014  1036  1436 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-08 18:24:11.014  1036  1436 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-08 18:24:11.016  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-08 18:24:11.028  1036  1436 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=136803  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-08 18:24:11.034  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.034  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.035  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 18:24:11.036  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:24:11.036  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:24:11.039  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 18:24:11.048  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.048  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.048  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 18:24:11.049  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=136824  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-08 18:24:11.050  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:24:11.050  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-08 18:24:11.060  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:24:11.060  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 18:24:11.065  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.079  8076  8076 D PluginManager: init()
,09-08 18:24:11.123  8003  8003 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 18:24:11.129  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-08 18:24:11.129  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-08 18:24:11.129  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-08 18:24:11.129  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-08 18:24:11.129  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 18:24:11.129  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 18:24:11.131  1036  1436 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=136907  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 18:24:11.132  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=136908  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 18:24:11.133  1036  1436 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136909
09-08 18:24:11.134  8003  8003 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 18:24:11.134  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 18:24:11.134  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 18:24:11.135  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-08 18:24:11.135  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 18:24:11.135  8003  8003 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 18:24:11.135  1036  8045 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 18:24:11.135  1036  1436 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136909
09-08 18:24:11.135  1036  1436 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136911
09-08 18:24:11.135  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136911
09-08 18:24:11.136  1036  1436 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136912
09-08 18:24:11.137  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 18:24:11.137  1036  1436 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=136912  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-08 18:24:11.138  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=136914  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-08 18:24:11.139  1036  1436 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=136914  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 18:24:11.139  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=136915  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 18:24:11.139  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-08 18:24:11.139  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 18:24,:11.140  1036  1436 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:24:11.140  1036  8045 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 18:24:11.140  1036  1436 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:24:11.140  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 18:24:11.140  1036  1436 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:24:11.140  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 18:24:11.140  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:24:11.141  1036  1436 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 18:24:11.144  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 18:24:11.144  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:24:11.144  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.144  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.144  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 18:24:11.145  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.145  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:24:11.145  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-08 18:24:11.145  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:24:11.145  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-08 18:24:11.146  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.148  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:24:11.148  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:24:11.149  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.149  1036  1436 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=136925
09-08 18:24:11.150  1036  1436 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=136925
09-08 18:24:11.150  1036  1436 D WifiNative-wlan0: doString: [STATUS]
09-08 18:24:11.150  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:24:11.150  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-08 18:24:11.151  1036  1436 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-08 18:24:11.152  1036  8045 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 18:24:11.152  1036  8045 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 18:24:11.153  1036  1436 I WifiServiceExtension: setVHTCapabilityType  : false
09-08 18:24:11.158  1036  1436 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-08 18:24:11.158  1036  1436 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-08 18:24:11.161  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.161  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.161  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 18:24:11.164  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.164  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.164  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 18:24:11.165  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:24:11.165  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:24:11.167  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.168  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:24:11.168  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:24:11.169  1036  1436 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-08 18:24:11.169  1036  1436 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 18:24:11.169  1036  1436 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 18:24:11.169  1036  1484 D ConnectivityService: Got NetworkAgent Messenger
09-08 18:24:11.169  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 18:24:11.169  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.169  1036  1484 D ConnectivityService: NetworkAgent connected
09-08 18:24:11.170  1036  1436 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 18:24:11.170  1036  1436 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 18:24:11.175  1036  1436 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 18:24:11.175  1036  1436 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 18:24:11.175  1036  1436 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-08 18:24:11.178  1036  1436 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 18:24:11.178  1036  1436 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 18:24:11.183  1036  1436 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 18:24:11.185   309   893 D CommandListener: Setting iface cfg
09-08 18:24:11.187  1036  1436 E WifiStateMachine: Start Dhcp Watchdog 3
09-08 18:24:11.187  1036  8116 D DhcpStateMachine: StoppedState
09-08 18:24:11.187  1036  8116 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:11.187  1036  8116 D DhcpStateMachine: WaitBeforeStartState
09-08 18:24:11.187  1036  1436 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=136962  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-08 18:24:11.187  1036  1436 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=136963  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 18:24:11.188  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=136963  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 18:24:11.188  1036  1436 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=136964  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 18:24:11.189  1036  1436 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=136964  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 18:24:11.189  1036  1436 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=136965  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 18:24:11.190  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14371] from screen [on:0 period:178068662] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 18:24:11.191  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:178068663] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 18:24:11.191  1036  1436 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-08 18:24:11.193  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.194  1036  1484 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-08 18:24:11.195  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.195  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.195  1036  1436 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.195  1036  1436 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.196  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.196  1036  1436 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.196  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-08 18:24:11.196  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=128,0,0
09-08 18:24:11.197  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=128,0,0
09-08 18:24:11.197  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-08 18:24:11.197  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-08 18:24:11.197  1036  1436 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-08 18:24:11.197  1036  1436 D WifiNative-wlan0: doBoolean: SET ps 0
09-08 18:24:11.197  1036  1436 D WifiNative-wlan0: SET ps 0: returned true
09-08 18:24:11.197  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-08 18:24:11.198  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-08 18:24:11.198  1036  1436 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-08 18:24:11.198  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2c009000 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:11.198  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2c009000 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:11.198  1036  1436 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-08 18:24:11.198  1036  1436 V DhcpStateMachine: Current State is mWaitBeforeStartState,.
09-08 18:24:11.198  1036  8116 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:11.198  1036  8116 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-08 18:24:11.198  1036  1436 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 18:24:11.199   309   893 D CommandListener: Setting iface cfg
09-08 18:24:11.199   309   893 D CommandListener: Trying to bring up wlan0
09-08 18:24:11.199  1036  1436 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-08 18:24:11.200  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:24:11.200  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-08 18:24:11.201  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 18:24:11.201  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 18:24:11.202  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.202  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.203  1036  1436 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.203  1036  1436 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.203  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.203  1036  1436 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 18:24:11.204  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-08 18:24:11.204  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 18:24:11.204  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 18:24:11.204  1036  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:11.204  1036  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:11.204  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 18:24:11.205  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 18:24:11.205  1036  1436 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 18:24:11.205  1036  1436 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-08 18:24:11.205  8003  8003 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-08 18:24:11.206  1036  1436 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-08 18:24:11.206  1036  1436 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 18:24:11.223  1036  1436 D WifiNative-wlan0: SET ps 1: returned true
09-08 18:24:11.224  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-08 18:24:11.224  1036  1436 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 18:24:11.224  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 18:24:11.224  1036  1436 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 18:24:11.225  1036  1484 D ConnectivityService: ignoring duplicate network state non-change
09-08 18:24:11.228  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.228  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.229  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:24:11.229  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 18:24:11.229  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:24:11.230  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.231  1036  1484 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 18:24:11.232  1036  1484 D ConnectivityService: Adding iface wlan0 to network 102
09-08 18:24:11.234  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.234  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.234  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 18:24:11.235  1036  1436 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-08 18:24:11.237  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 18:24:11.239  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-08 18:24:11.241  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.241  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.241  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-08 18:24:11.243  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 18:24:11.254  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:24:11.254  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 18:24:11.254  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.254  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:24:11.254  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-08 18:24:11.255  1036  1484 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 18:24:11.255  1036  1484 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-08 18:24:11.255  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.256  1036  1484 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-08 18:24:11.256   309   893 E Netd    : netlink response contains error (File exists)
09-08 18:24:11.256  1036  1484 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-08 18:24:11.257  1036  1484 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-08 18:24:11.257  1036  1484 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-08 18:24:11.257  1036  1484 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-08 18:24:11.257  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:24:11.257  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 18:24:11.258  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.258  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 18:24:11.258  1036  1484 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 18:24:11.258  1036  1484 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-08 18:24:11.259  1036  8115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:11.259  1036  8115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-08 18:24:11.259  1036  8115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:11.259  1036  8115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-08 18:24:11.260  1036  1484 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-08 18:24:11.260  1036  1484 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:24:11.261   309  8122 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-08 18:24:11.261  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:24:11.261  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 18:24:11.261  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:24:11.261  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:24:11.261  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-08 18:24:11.261  1036  1484 D ConnectivityService: currentScore = 0, newScore = 20
09-08 18:24:11.261  1036  1484 D ConnectivityService:    accepting network in place of null
09-08 18:24:11.261  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 18:24:11.261  1036  1484 D ConnectivityService: sending new Min Network Score(20): Net,workRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:24:11.261  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.263  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:24:11.263  1036  1436 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:24:11.263  1036  1436 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:24:11.263  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 18:24:11.263  1036  1484 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-08 18:24:11.264  1036  1484 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-08 18:24:11.264  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 18:24:11.264  1036  1484 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 18:24:11.264  1036  1484 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-08 18:24:11.264  1036  1484 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-08 18:24:11.265  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-08 18:24:11.265  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 18:24:11.265  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 18:24:11.265  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 18:24:11.266  1036  1484 D ConnectivityService: validation of new default Network = false
09-08 18:24:11.266  1036  1484 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-08 18:24:11.266  1036  1484 D DSQN    : enableDataServiceNotify 
09-08 18:24:11.266  1036  1484 D DSQN    : start dsqn bin
,09-08 18:24:11.272  1036  1484 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-08 18:24:11.272  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:24:11.272  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:24:11.272  1036  1484 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:24:11.272  1605  2099 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 18:24:11.275  1036  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-08 18:24:11.262  8123  8123 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:11.262  8123  8123 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:11.289  8123  8123 E DSQN    : DSQN ssw
,09-08 18:24:11.292  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 18:24:11.293  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.294  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.306  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:11.306  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:11.306  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:24:11.306  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:11.306  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:11.306  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:11.306  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:11.306  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:24:11.307  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:11.311  6609  6721 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-08 18:24:11.312  6609  6721 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-08 18:24:11.313  6609  6721 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2033c3ec Bundle[{}]
09-08 18:24:11.314  6609  6721 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 18:24:11.314  6609  6721 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-08 18:24:11.314  6609  6721 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 18:24:11.315  6609  6721 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 18:24:11.315  6609  6721 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 18:24:11.316  6609  6721 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 18:24:11.321  6609  6721 I System.out: Running OutgoingSocketThread
09-08 18:24:11.322  6609  8127 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 855)
09-08 18:24:11.323  6609  8127 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58195
09-08 18:24:11.323  6609  8127 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-08 18:24:11.325   309  8122 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-08 18:24:11.360   309  8122 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-08 18:24:11.389   309   892 D LGDataListener: argv[0]=dsqncommand
09-08 18:24:11.389   309   892 D LGDataListener: argv[1]=wlan0
09-08 18:24:11.389   309   892 D LGDataListener: argv[2]=1
09-08 18:24:11.389   309   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-08 18:24:11.389  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
09-08 18:24:11.389  1036  1116 D DSQN    : start to monitor internet connection
,09-08 18:24:11.404  1036  8116 D DhcpStateMachine: DHCPV4 request on wlan0
,09-08 18:24:11.405  1036  8116 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,09-08 18:24:11.406  1036  8116 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-08 18:24:11.402  8130  8130 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:11.402  8130  8130 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 18:24:11.414  1036  8115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 16:24:11 GMT], X-Android-Received-Millis=[1473351851413], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473351851388]}
09-08 18:24:11.414  1036  8115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 18:24:11.415  1036  8115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 18:24:11.415  1036  1484 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-08 18:24:11.415  1036  1484 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-08 18:24:11.416  1036  1484 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:24:11.416  1036  1484 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:24:11.416  1036  1484 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 18:24:11.416  1036  1484 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-08 18:24:11.416  1036  1484 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-08 18:24:11.417  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:24:11.417  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:24:11.418  1036  1484 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:24:11.418  1605  2099 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 18:24:11.418  1036  1484 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:24:11.419  1036  1436 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:24:11.419  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 18:24:11.419  1036  1436 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:24:11.420  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:24:11.420  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-08 18:24:11.434  8130  8130 I dhcpcd  : version 5.5.6 starting
,09-08 18:24:11.436  8130  8130 E dhcpcd  : get_duid: m
09-08 18:24:11.436  8130  8130 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-08 18:24:11.436  8130  8130 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-08 18:24:11.455  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-08 18:24:11.458  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.460  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:11.486  8130  8130 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 18:24:11.486  8130  8130 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 18:24:11.486  8130  8130 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 18:24:11.486  8130  8130 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-08 18:24:11.486  8130  8130 D dhcpcd  : wlan0: sending REQUEST (xid 0x35fc0bd2), next in 4.59 seconds
,09-08 18:24:11.542  8130  8130 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-08 18:24:11.542  8076  8076 W ExternalStrings: load override strings
09-08 18:24:11.542  8076  8076 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 18:24:11.542  8076  8076 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-08 18:24:11.545  8076  8076 D StatusProvider: onCreate
,09-08 18:24:11.572  8130  8130 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,09-08 18:24:11.572  8130  8130 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-08 18:24:11.573  8130  8130 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-08 18:24:11.573  8130  8130 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-08 18:24:11.574  8130  8130 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-08 18:24:11.574  8130  8130 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 18:24:11.575  8130  8130 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 18:24:11.575  8130  8130 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-08 18:24:11.588  8076  8076 V Signer  : override build config not found
,09-08 18:24:11.589  8076  8076 D Signer  : value of property debug is false
,09-08 18:24:11.614  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-08 18:24:11.614  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-08 18:24:11.615  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,09-08 18:24:11.615  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-08 18:24:11.615  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-08 18:24:11.615  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-08 18:24:11.615  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-08 18:24:11.615  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-08 18:24:11.615  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-08 18:24:11.616  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-08 18:24:11.616  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-08 18:24:11.616  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-08 18:24:11.616  8076  8076 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-08 18:24:11.624  8076  8076 V LGMDMManager: Create singleton instance
09-08 18:24:11.660  8076  8076 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-08 18:24:11.701  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 18:24:11.706  8076  8148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-08 18:24:11.712  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:24:11.716  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:11.721  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:24:11.721  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:24:11.722  6898  6898 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 18:24:11.724  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-08 18:24:11.727  6818  6818 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-08 18:24:11.729  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 18:24:11.733  8076  8148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-08 18:24:11.742  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:24:11.747  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:11.752  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:24:11.752  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:24:11.753  6898  6898 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 18:24:11.756  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:24:11.757  8076  8148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-08 18:24:11.767  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:24:11.773  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:11.777  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:24:11.777  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:24:11.777  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 18:24:11.780  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 18:24:11.780  6818  6818 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 18:24:11.780  6818  6818 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 18:24:11.780  6818  6818 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 18:24:11.780  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 18:24:11.781  6818  6818 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 18:24:11.781  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 18:24:11.781  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 18:24:11.781  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 18:24:11.781  6818  6818 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 18:24:11.781  6818  6818 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 18:24:11.781  6818  6818 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 18:24:11.784  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 18:24:11.786  8076  8148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-08 18:24:11.789  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 18:24:11.791  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:11.796  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 18:24:11.796  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:24:11.796  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 18:24:11.799  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:24:11.800  8076  8148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-08 18:24:11.806  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:24:11.810  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:11.818  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:24:11.818  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:24:11.819  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 18:24:11.905  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 18:24:11.907  8076  8148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-08 18:24:11.910  8076  8147 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-08 18:24:11.924  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:24:11.930  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:11.936  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:24:11.936  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:24:11.936  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 18:24:11.940  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 18:24:11.940  8076  8148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-08 18:24:11.947  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:24:11.952  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:11.957  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:24:11.958  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:24:11.958  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 18:24:11.968  8076  8148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-08 18:24:11.969  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:24:11.982  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:24:11.989  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 18:24:12.000  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:24:12.001  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 18:24:12.003  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 18:24:12.010  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:24:12.011  8076  8148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-08 18:24:12.011  1036  8116 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-08 18:24:12.012  1036  8116 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-08 18:24:12.012  1036  8116 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 18:24:12.012  1036  8116 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-08 18:24:12.012  1036  8116 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-08 18:24:12.012  1036  8116 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 18:24:12.012  1036  8116 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-08 18:24:12.013  1036  8116 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-08 18:24:12.013  1036  8116 D DhcpStateMachine: RunningState
,09-08 18:24:12.031  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:24:12.044  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:12.056  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:24:12.057  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 18:24:12.058  6898  6898 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 18:24:12.064  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:24:12.066  8076  8148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-08 18:24:12.069  8027  8027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-08 18:24:12.078  8027  8027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:24:12.085  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:24:12.092  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:12.099  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 18:24:12.099  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:24:12.101  6898  6898 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 18:24:12.103  6898  6898 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 18:24:12.105  6898  6898 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-08 18:24:12.111  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 18:24:12.112  8076  8148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-08 18:24:12.116  8027  8027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 18:24:12.117  8027  8027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-08 18:24:12.121  6818  6818 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 18:24:12.127  6818  6818 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 18:24:12.132  6898  6898 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 18:24:12.132  6898  6898 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 18:24:12.133  6898  6898 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 18:24:12.134  6898  6898 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 18:24:12.134  6898  6898 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-08 18:24:12.138  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,09-08 18:24:12.140  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-08 18:24:12.143  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-08 18:24:12.144  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-08 18:24:12.146  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-08 18:24:12.147  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-08 18:24:12.149  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-08 18:24:12.150  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,09-08 18:24:12.152  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-08 18:24:12.154  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-08 18:24:12.155  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-08 18:24:12.156  1036  1052 I ActivityManager: Killing 7252:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-08 18:24:12.169  8076  8147 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 18:24:12.169  8076  8147 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:24:12.236  1036  1988 W libprocessgroup: failed to open /acct/uid_10005/pid_7252/cgroup.procs: No such file or directory
,09-08 18:24:12.276  8076  8147 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-08 18:24:12.298  8076  8147 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,09-08 18:24:12.307  8076  8147 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,09-08 18:24:12.308  8076  8147 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-08 18:24:12.308  8076  8147 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-08 18:24:12.309  8076  8147 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-08 18:24:12.309  8076  8147 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-08 18:24:12.315  8076  8147 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,09-08 18:24:12.317  8076  8147 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,09-08 18:24:12.323  6609  6721 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 856)
,09-08 18:24:12.323  6609  6721 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 856)
,09-08 18:24:12.327  6609  6721 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 861)
,09-08 18:24:12.328  6609  6721 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-08 18:24:12.328  6609  6721 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 862)
09-08 18:24:12.331  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:12.331  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30bbafab added. We now have 2 listener(s)
09-08 18:24:12.332  1036  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:12.334  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 18:24:12.334  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:12.334  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:24:12.334  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:12.334  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b21608 added. We now have 9 listener(s)
09-08 18:24:12.334  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:12.335  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:24:12.338  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:12.342  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:12.342  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:12.342  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:24:12.342  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:12.342  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:12.342  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:12.342  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:12.342  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:24:12.344  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:12.344  6609  6721 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:12.345  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:12.345  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3737efc6 added. We now have 3 listener(s)
09-08 18:24:12.346  1036  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:12.347  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:12.348  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 18:24:12.349  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:12.350  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:12.350  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:12.350  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:12.350  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7039b87 added. We now have 10 listener(s)
09-08 18:24:12.350  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:12.350  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:12.350  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:12.350  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:24:12.351  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:12.351  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.351  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:12.351  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:12.351  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30bbafab removed from the list
09-08 18:24:12.351  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.351  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b21608 removed from the list
09-08 18:24:12.351  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:12.351  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.352  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.352  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.354  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:12.354  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:12.354  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.354  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b21608 not in the list
09-08 18:24:12.354  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.354  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.355  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:12.355  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:12.355  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.355  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7039b87 removed from the list
09-08 18:24:12.355  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:12.355  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.355  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.355  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:12.355  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3737efc6 removed from the list
09-08 18:24:12.356  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:12.356  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27568ab4 added. We now have 2 listener(s)
09-08 18:24:12.357  1036  1905 D BluetoothManagerService: checkIfCall,erIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:12.359  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 18:24:12.359  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:12.359  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:12.359  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:12.359  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@195416dd added. We now have 9 listener(s)
09-08 18:24:12.359  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:12.360  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:24:12.363  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:12.366  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:12.366  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:12.366  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:24:12.366  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:12.366  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:12.366  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:12.366  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:12.366  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:24:12.367  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:12.367  6609  6721 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:12.368  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:12.369  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef46923 added. We now have 3 listener(s)
09-08 18:24:12.369  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:12.369  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:12.370  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:12.371  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 18:24:12.371  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:12.371  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:12.372  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:12.372  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2b9e20 added. We now have 10 listener(s)
09-08 18:24:12.372  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:12.372  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:12.372  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:24:12.372  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:24:12.372  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:12.372  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:24:12.374  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 18:24:12.375  1036  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 for,egroundUser=0
09-08 18:24:12.375  1036  1379 V AlarmManager: RTC_WAKEUP set : Alarm{3081e9a9 type 0 when 1473351845412 com.google.android.gms} when 1473351845412
09-08 18:24:12.375  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1e382b2e type 2 when 138150 com.google.android.gms} when 138150
,09-08 18:24:12.384  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 18:24:12.386  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:24:12.388   309  8187 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 18:24:12.388   309  8187 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-08 18:24:12.388  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:24:12.389  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:12.390  6609  6721 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 18:24:12.390  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:12.390  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:12.393  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:12.393  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:12.393  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:12.393  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:12.393  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.393  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:12.393  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:12.393  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27568ab4 removed from the list
09-08 18:24:12.393  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.393  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@195416dd removed from the list
09-08 18:24:12.393  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:12.393  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.393  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.393  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.394  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:12.394  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:12.394  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.394  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@195416dd not in the list
09-08 18:24:12.394  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.394  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.395  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:,24:12.396  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:24:12.396  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:24:12.396  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:12.396  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.396  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2b9e20 removed from the list
09-08 18:24:12.396  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:12.396  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.396  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.396  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:12.396  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef46923 removed from the list
09-08 18:24:12.397  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:12.397  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59a747f added. We now have 2 listener(s)
09-08 18:24:12.398  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-08 18:24:12.401  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 18:24:12.401  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:12.401  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:12.402  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:12.402  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7c7c4c added. We now have 9 listener(s)
09-08 18:24:12.402  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:12.402  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:24:12.404  1818  8186 I CheckinService: active receiver: enabled
09-08 18:24:12.405  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:12.416  1818  8186 I CheckinService: Preparing to send checkin request
09-08 18:24:12.416  1818  8186 I EventLogService: Accumulating logs since 1473351834100
09-08 18:24:12.418  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:12.418  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:12.418  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:24:12.418  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:12.418  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:12.418  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:12.418  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:12.418  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:24:12.419  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:12.419  6609  6721 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:12.419  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:12.419  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc8c9aa added. We now have 3 listener(s)
09-08 18:24:12.420  1036  1699 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:12.423  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:12.424  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 18:24:12.424  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:12.424  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:12.425  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:12.425  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:12.425  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@226bd99b added. We now have 10 listener(s)
09-08 18:24:12.425  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:12.425  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:12.426  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:12.426  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:24:12.426  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:24:12.426  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new l,istener
09-08 18:24:12.426  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:24:12.426   309  8187 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-08 18:24:12.430  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 18:24:12.430  1036  1628 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:12.434  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 18:24:12.435  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 18:24:12.436  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:24:12.436  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:12.438  6609  6721 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 18:24:12.438  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:12.438  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:12.438  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:12.439  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:12.439  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.439  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:12.439  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:12.439  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59a747f removed from the list
09-08 18:24:12.439  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.439  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7c7c4c removed from the list
09-08 18:24:12.439  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:12.439  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.439  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.439  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.440  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:12.440  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:12.440  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.440  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7c7c4c not in the list
09-08 18:24:12.440  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.440  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.441  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:12.441  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:24:12.441  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:24:12.441  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:12.441  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.442  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@226bd99b removed from the list
09-08 18:24:12.442  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:12.442  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08, 18:24:12.442  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.442  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:12.442  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc8c9aa removed from the list
09-08 18:24:12.442  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:12.443  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c1d676 added. We now have 2 listener(s)
09-08 18:24:12.443  1036  1699 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:12.445  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 18:24:12.445  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:12.445  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:12.446  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:12.446  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14247477 added. We now have 9 listener(s)
09-08 18:24:12.446  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:12.446  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:24:12.449  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:12.454  1818  8186 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-08 18:24:12.456  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:12.456  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:12.456  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:24:12.456  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:12.456  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:12.456  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:12.456  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:12.456  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:24:12.460  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:24:12.460  6609  6721 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:12.460  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:12.460  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@262d714d added. We now have 3 listener(s)
09-08 18:24:12.461  1036  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:12.462  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:12.463  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 18:24:12.463  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:12.463  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:12.463  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:12.463  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86ce402 added. We now have 10 listener(s)
09-08 18:24:12.463  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:12.463  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:12.464  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:24:12.464  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:24:12.464  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:12.464  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:24:12.466  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 18:24:12.467  1036  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:12.467  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:12.470  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 18:24:12.470  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 18:24:12.471  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:24:12.472  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:12.474  6609  6721 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 18:24:12.482  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:12.482  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:24:12.482  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:12.482  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:12.482  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.482  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:12.482  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:12.482  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c1d676 removed from the list
09-08 18:24:12.482  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.482  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14247477 removed from the list
09-08 18:24:12.483  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:12.483  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.483  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.483  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:12.485  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:12.485  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:12.485  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.485  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14247477 not in the list
09-08 18:24:12.485  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.485  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.486  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:12.486  6609  6721 D BluetoothLeScanner: could not find callback wrapper
09-08 18:24:12.486  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:24:12.486  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:12.486  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.486  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86ce402 removed from the list
09-08 18:24:12.486  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:12.487  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.487  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.487  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:12.487  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@262d714d removed from the list
09-08 18:24:12.487  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:12.487  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286cd549 added. We now have 2 listener(s)
09-08 18:24:12.487  1036  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:12.490  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 18:24:12.490  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:12.490  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:12.490  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:12.490  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec93e4e added. We now have 9 listener(s)
09-08 18:24:12.490  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:12.490  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:24:12.492  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoo,thManager: bind: Binding a new listener
09-08 18:24:12.495  6609  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:12.495  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:12.495  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 18:24:12.495  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:12.495  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:12.495  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:12.495  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:12.495  6609  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:24:12.497  6609  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:12.497  6609  6721 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:12.497  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:12.497  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3d907c added. We now have 3 listener(s)
09-08 18:24:12.498  1036  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 18:24:12.499  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:12.500  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:12.501  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 18:24:12.501  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:12.501  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:12.501  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:12.501  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21247d05 added. We now have 10 listener(s)
09-08 18:24:12.501  6609  6721 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:12.501  6609  6721 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:12.502  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:12.502  6609  6721 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:12.502  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:12.502  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.502  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:12.502  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:12.502  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286cd549 removed from the list
09-08 18:24:12.502  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.502  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec93e4e removed from the list
09-08 18:24:12.502  6609  6721 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:12.502  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.503  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.503  6609  6721 D org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.504  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:12.504  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:12.504  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.504  6609  6721 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec93e4e not in the list
09-08 18:24:12.504  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.504  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.504  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:12.504  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:12.505  6609  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:12.505  6609  6721 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21247d05 removed from the list
09-08 18:24:12.505  6609  6721 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:12.505  6609  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:12.505  6609  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:12.505  6609  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:12.505  6609  6721 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3d907c removed from the list
09-08 18:24:12.506  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 18:24:12.506  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 18:24:12.506  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 18:24:12.506  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:12.506  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 18:24:12.506  6609  6721 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:24:12.515  6609  8197 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 869, name: My test thread name)
09-08 18:24:12.515  6609  8197 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 869, thread name: My test thread name)
09-08 18:24:12.516  6609  8197 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 869, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-08 18:24:12.518  6609  8198 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 871, name: My test thread name)
09-08 18:24:12.518  6609  8198 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 871, thread name: My test thread name)
09-08 18:24:12.518  6609  8198 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 871, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-08 18:24:12.519  6609  6721 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-08 18:24:12.519  6609  6721 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-08 18:24:12.519  6609  6721 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-08 18:24:12.520  6609  6721 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-08 18:24:12.520  6609  6721 D com.test.thalitest.ThaliTestRunner: Total duration: 24003 ms
09-08 18:24:12.521  6609  6721 I jxcore-log: *Native tests were executed*
09-08 18:24:12.521  6609  6721 I jxcore-log: 
09-08 18:24:12.521  6609  6721 I jxcore-log: Total number of executed tests:  80
09-08 18:24:12.521  6609  6721 I jxcore-log: 
09-08 18:24:12.521  6609  6721 I jxcore-log: Number of passed tests:  80
09-08 18:24:12.521  6609  6721 I jxcore-log: 
09-08 18:24:12.521  6609  6721 I jxcore-log: Number of failed tests:  0
09-08 18:24:12.521  6609  6721 I jxcore-log: 
09-08 18:24:12.521  6609  6721 I jxcore-log: Number of ignored tests:  0
09-08 18:24:12.521  6609  6721 I jxcore-log: 
09-08 18:24:12.522  6609  6721 I jxcore-log: Total duration:  24003
09-08 18:24:12.522  6609  6721 I jxcore-log: 
09-08 18:24:12.522  6609  6721 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-08 18:24:12.522  6609  6721 I jxcore-log: 
09-08 18:24:12.525  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.525  6609  6721 I jxcore-log: 
09-08 18:24:12.527  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.527  6609  6721 I jxcore-log: 
09-08 18:24:12.528  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.528  6609  6721 I jxcore-log: 
09-08 18:24:12.529  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.529  6609  6721 I jxcore-log: 
09-08 18:24:12.530  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.530  6609  6721 I jxcore-log: 
09-08 18:24:12.531  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.531  6609  6721 I jxcore-log: 
,09-08 18:24:12.534  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:12.534  6609  6721 I jxcore-log: 
09-08 18:24:12.536  6609  6609 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-08 18:24:12.536  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:12.536  6609  6721 I jxcore-log: 
09-08 18:24:12.537  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:12.537  6609  6721 I jxcore-log: 
09-08 18:24:12.538  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:24:12.538  6609  6721 I jxcore-log: 
09-08 18:24:12.539  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:24:12.539  6609  6721 I jxcore-log: 
09-08 18:24:12.539  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:12.539  6609  6721 I jxcore-log: 
09-08 18:24:12.540  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:12.540  6609  6721 I jxcore-log: 
09-08 18:24:12.541  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:12.541  6609  6721 I jxcore-log: 
09-08 18:24:12.542  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:12.542  6609  6721 I jxcore-log: 
09-08 18:24:12.543  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:12.543  6609  6721 I jxcore-log: 
09-08 18:24:12.543  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:12.543  6609  6721 I jxcore-log: 
09-08 18:24:12.544  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:12.544  6609  6721 I jxcore-log: 
09-08 18:24:12.545  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:12.545  6609  6721 I jxcore-log: 
09-08 18:24:12.545  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:12.545  6609  6721 I jxcore-log: 
,09-08 18:24:12.546  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.546  6609  6721 I jxcore-log: 
09-08 18:24:12.547  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.547  6609  6721 I jxcore-log: 
09-08 18:24:12.548  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.548  6609  6721 I jxcore-log: 
09-08 18:24:12.548  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.548  6609  6721 I jxcore-log: 
09-08 18:24:12.549  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.549  6609  6721 I jxcore-log: 
09-08 18:24:12.550  6609  6721 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:12.550  6609  6721 I jxcore-log: 
09-08 18:24:12.560  1036  1986 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8200 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-08 18:24:12.615  8200  8200 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-08 18:24:12.616  8200  8200 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 18:24:12.647  8200  8200 I MultiDex: VM with version 2.1.0 has multidex support
09-08 18:24:12.647  8200  8200 I MultiDex: install
09-08 18:24:12.647  8200  8200 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-08 18:24:12.660  8200  8200 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-08 18:24:12.668  2082  2082 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-08 18:24:12.679  2082  2082 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-08 18:24:12.680  2082  2082 D c       : Getting all permits...
09-08 18:24:12.680  2082  2082 D a       : Opening database...
09-08 18:24:12.685  2082  2082 D a       : Opening database auth.proximity.permit_store...
09-08 18:24:12.686  2082  2082 D a       : Closing database...
09-08 18:24:12.691  2082  8207 D GCM     : Connected
,09-08 18:24:12.707  2082  8207 D GCM     : Message class com.google.e.a.a.q
,09-08 18:24:12.833  8218  8218 D AndroidRuntime: 
09-08 18:24:12.833  8218  8218 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-08 18:24:12.836  8218  8218 D AndroidRuntime: CheckJNI is OFF
09-08 18:24:13.005  1036  1436 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 18:24:13.005  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 18:24:13.005  1036  1436 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 18:24:13.006  1036  1436 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 18:24:13.006  1036  1436 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 18:24:13.007  1036  1436 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 18:24:13.008  1036  1484 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
,09-08 18:24:13.008  1036  1484 D ConnectivityService: identical MTU - not setting
09-08 18:24:13.008  1036  1484 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 18:24:13.008  8218  8218 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-08 18:24:13.008  1036  1484 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 18:24:13.008  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:24:13.008  1036  1484 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:24:13.008  1036  1484 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 18:24:13.010  1605  2099 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 18:24:13.015  1036  1114 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-08 18:24:13.015  1036  1114 I ActivityManager: Killing 6609:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-08 18:24:13.053  8236  8236 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-08 18:24:13.072  1036  1988 I WindowState: WIN DEATH: Window{33ca77d4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-08 18:24:13.073  1036  1474 D WifiService: Client connection lost with reason: 4
09-08 18:24:13.082  1036  1988 D InputDispatcher: Window went away: Window{33ca77d4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 18:24:13.118  8236  8236 I dex2oat : dex2oat took 65.570ms (threads: 4)
,09-08 18:24:13.132  8200  8217 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 18:24:13.132  8200  8217 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 18:24:13.132  8200  8217 I Adreno-EGL: Build Date: 12/12/14 금
09-08 18:24:13.132  8200  8217 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 18:24:13.132  8200  8217 I Adreno-EGL: Remote Branch: 
09-08 18:24:13.132  8200  8217 I Adreno-EGL: Local Patches: 
09-08 18:24:13.132  8200  8217 I Adreno-EGL: Reconstruct Branch: 
,09-08 18:24:13.286  1036  1114 I ActivityManager:   Force finishing activity ActivityRecord{2c44cee0 u0 com.test.thalitest/.MainActivity t6}
,09-08 18:24:13.295  8200  8217 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:24:13.295  8200  8217 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:24:13.306  8200  8217 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 18:24:13.306  8200  8217 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 18:24:13.306  8200  8217 I Adreno-EGL: Build Date: 12/12/14 금
09-08 18:24:13.306  8200  8217 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 18:24:13.306  8200  8217 I Adreno-EGL: Remote Branch: 
09-08 18:24:13.306  8200  8217 I Adreno-EGL: Local Patches: 
09-08 18:24:13.306  8200  8217 I Adreno-EGL: Reconstruct Branch: 
,09-08 18:24:13.338   331   341 E GBMv2   : DFP En is all cleared set to be enabled
,09-08 18:24:13.349  1036  1577 W ActivityManager: Spurious death for ProcessRecord{12f5ba53 6609:com.test.thalitest/u0a118}, curProc for 6609: null
09-08 18:24:13.350  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-08 18:24:13.351  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-08 18:24:13.351  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-08 18:24:13.352  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2604b6d1 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-08 18:24:13.352  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-08 18:24:13.354  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{2c44cee0 u0 com.test.thalitest/.MainActivity t6 f}
09-08 18:24:13.354  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{2c44cee0 u0 com.test.thalitest/.MainActivity t6 f}
09-08 18:24:13.354  8200  8217 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 18:24:13.354  8200  8217 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 18:24:13.354  8200  8217 I Adreno-EGL: Build Date: 12/12/14 금
09-08 18:24:13.354  8200  8217 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 18:24:13.354  8200  8217 I Adreno-EGL: Remote Branch: 
09-08 18:24:13.354  8200  8217 I Adreno-EGL: Local Patches: 
09-08 18:24:13.354  8200  8217 I Adreno-EGL: Reconstruct Branch: 
09-08 18:24:13.358  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-08 18:24:13.358  1942  3901 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-08 18:24:13.359  1942  3901 D SplitWindowPolicy: topRunningActivity=ActivityInfo{165bb536 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-08 18:24:13.359  2034  2076 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,09-08 18:24:13.382  1906  1906 D ActionManagerService: notifyUserLog: 1000003
09-08 18:24:13.382  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-08 18:24:13.382  3726  4492 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-08 18:24:13.383  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-08 18:24:13.384  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-08 18:24:13.385  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-08 18:24:13.390  1906  1906 D ActionManagerService: notifyUserLog: 1000004
09-08 18:24:13.390  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-08 18:24:13.390  3726  4492 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,09-08 18:24:13.393  3726  3742 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-08 18:24:13.402  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-08 18:24:13.406  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,09-08 18:24:13.408  7647  7647 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-08 18:24:13.408  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-08 18:24:13.412  3726  3726 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-08 18:24:13.419  2454  2649 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 18:24:13.425  4604  4604 I art     : Explicit concurrent mark sweep GC freed 8194(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 515us total 57.251ms
,09-08 18:24:13.448  1036  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 18:24:13.477  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
,09-08 18:24:13.482  4497  4497 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-08 18:24:13.482  4497  4497 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-08 18:24:13.482  4497  4497 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-08 18:24:13.483  4497  4497 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-08 18:24:13.483  4497  4497 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 18:24:13.483  4497  4497 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 18:24:13.483  4497  4497 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 18:24:13.483  4497  4497 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 18:24:13.483  4497  4497 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:24:13.483  4497  4497 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:24:13.483  4497  4497 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 18:24:13.483  4497  4497 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , expire_time: 0
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , display: false
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , animation: false }
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , expire_time: 0
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , display: false
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , animation: false }
09-08 18:24:13.485  1036  1036 D administrator: Handling package changes for user 0
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , create_time: 1472828323917
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , expire_time: 0
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , display: false
09-08 18:24:13.485  2034  2034 I GBoardWebViewUtils: , animation: false }
09-08 18:24:13.490  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-08 18:24:13.492  1605  1663 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-08 18:24:13.492  1605  1663 D KeyguardModel: createShortcutInfo...
09-08 18:24:13.498  1605  1663 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-08 18:24:13.498  1605  1663 D KeyguardModel: createShortcutInfo...
09-08 18:24:13.500  2034  8258 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-08 18:24:13.501  8076  8076 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-08 18:24:13.503  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,09-08 18:24:13.524  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-08 18:24:13.525  1605  1663 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-08 18:24:13.525  1605  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:24:13.525  1605  1663 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-08 18:24:13.526  1605  1663 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-08 18:24:13.527  1605  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 18:24:13.527  1605  1663 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-08 18:24:13.538  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,09-08 18:24:13.542  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-08 18:24:13.545  1605  1663 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-08 18:24:13.546  1605  1663 D KeyguardModel: createShortcutInfo...
09-08 18:24:13.550  1605  1663 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-08 18:24:13.550  1605  1663 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 18:24:13.559  1605  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 18:24:13.559  1605  1663 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-08 18:24:13.563  2082  2082 I ConfigService: onCreate
09-08 18:24:13.564  2082  2082 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-08 18:24:13.564  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-08 18:24:13.568  1605  1663 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,09-08 18:24:13.568  1605  1663 D KeyguardModel: createShortcutInfo...
09-08 18:24:13.571  2082  2082 I ConfigService: onBind returning update interface
09-08 18:24:13.578  1605  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:24:13.579  1605  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 18:24:13.579  1605  1663 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-08 18:24:13.579  1605  1663 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-08 18:24:13.582  1605  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 18:24:13.582  1605  1663 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-08 18:24:13.588  1036  2028 V SIM_STK : Menu title from STK is T-Mobile
09-08 18:24:13.588  1036  2028 V SIM_STK : Menu title from STK is T-Mobile
09-08 18:24:13.594  1605  1663 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-08 18:24:13.594  1605  1663 D KeyguardModel: createShortcutInfo...
,09-08 18:24:13.598  1870  1870 D SplitUIManager: split_name #11 / not available #0
09-08 18:24:13.598  1870  1870 D SplitUIService: removed split : 
09-08 18:24:13.600  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-08 18:24:13.602  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,09-08 18:24:13.619  1870  1870 D SplitUIManager: split_name #11 / not available #0
09-08 18:24:13.619  1870  1870 I SplitUIService: split app #11
09-08 18:24:13.633  2082  2082 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-08 18:24:13.633  2082  2082 I ConfigService: onBind returning config service
,09-08 18:24:13.640  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
09-08 18:24:13.643  1036  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-08 18:24:13.643  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-08 18:24:13.644  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-08 18:24:13.644  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-08 18:24:13.644  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-08 18:24:13.644  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-08 18:24:13.644  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 18:24:13.644  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-08 18:24:13.644  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-08 18:24:13.644  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-08 18:24:13.644  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 18:24:13.644  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-08 18:24:13.644  1605  1605 D KeyguardModel: handleShortcutListChanged...
09-08 18:24:13.644  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-08 18:24:13.647  1818  8263 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-08 18:24:13.653  2082  2082 I ConfigService: onDestroy
09-08 18:24:13.655  1605  1663 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-08 18:24:13.655  1605  1663 D KeyguardModel: createShortcutInfo...
09-08 18:24:13.658  1605  1663 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-08 18:24:13.658  1605  1663 D KeyguardModel: createShortcutInfo...
,09-08 18:24:13.659  1605  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 18:24:13.659  1605  1663 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-08 18:24:13.661  1605  1663 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-08 18:24:13.661  1605  1663 D KeyguardModel: createShortcutInfo...
09-08 18:24:13.663  1605  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 18:24:13.663  1605  1663 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-08 18:24:13.664  1605  1663 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-08 18:24:13.664  1605  1663 D KeyguardModel: createShortcutInfo...
09-08 18:24:13.665  1605  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 18:24:13.665  1605  1663 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-08 18:24:13.671  1605  1663 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
,09-08 18:24:13.671  1605  1663 D KeyguardModel: createShortcutInfo...
09-08 18:24:13.675  5926  8266 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-08 18:24:13.681  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-08 18:24:13.684  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 18:24:13.685  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-08 18:24:13.686  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-08 18:24:13.687  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-08 18:24:13.688  1818  8270 I PeopleContactsSync: CP2 sync disabled
09-08 18:24:13.688  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-08 18:24:13.692  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-08 18:24:13.692  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-08 18:24:13.692  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-08 18:24:13.693  1818  4775 I Icing   : doRemovePackageData com.test.thalitest
09-08 18:24:13.696  1036  1580 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,09-08 18:24:13.698   325   426 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-08 18:24:13.698  3205  8271 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-08 18:24:13.699  1036  1113 W InputMethodInfo: Duplicated subtype definition found: , voice
09-08 18:24:13.706  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b8658c2 u0 com.lge.launcher2/.Launcher t5} time:139494
09-08 18:24:13.712  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-08 18:24:13.712  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-08 18:24:13.727  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-08 18:24:13.727  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-08 18:24:13.727  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 18:24:13.729  2034  2146 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-08 18:24:13.729  2034  2146 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-08 18:24:13.743  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-08 18:24:13.744  2581  2581 D [Concierge]Service: onStartCommand(). Type : 8
09-08 18:24:13.744  2581  2581 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-08 18:24:13.745  2581  2581 D [Concierge]Service: Update widget ID : 11
09-08 18:24:13.749  2034  2034 D [Concierge]WidgetView: change position of spinner
09-08 18:24:13.750  2581  2581 D [Concierge]Service: onStartCommand(). Type : 0
09-08 18:24:13.750  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1473351853750
,09-08 18:24:13.764  1605  1605 D KeyguardModel: handleShortcutListChanged...
09-08 18:24:13.764  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-08 18:24:13.771  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 207284873
09-08 18:24:13.772  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-08 18:24:13.772  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-08 18:24:13.775  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@391e6609
09-08 18:24:13.775  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-08 18:24:13.776  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,09-08 18:24:13.776  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 18:24:13.783  2082  2249 I art     : Explicit concurrent mark sweep GC freed 9320(532KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 958us total 54.394ms
09-08 18:24:13.784  7035  7035 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-08 18:24:13.786  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-08 18:24:13.788  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-08 18:24:13.788  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-08 18:24:13.789  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473351742269, New one : 1473351853750
09-08 18:24:13.789  2034  2034 D [Concierge]WidgetView: Unregister all receivers
09-08 18:24:13.789  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-08 18:24:13.789  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 18:24:13.791  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-08 18:24:13.792  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-08 18:24:13.793  1818  8269 W GmsApplication: Using Auth Proxy for data requests.
09-08 18:24:13.793  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-08 18:24:13.794  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-08 18:24:13.795  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-08 18:24:13.796  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 18:24:13.796  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-08 18:24:13.799  1818  8269 W GmsApplication: Using Auth Proxy for data requests.
09-08 18:24:13.827  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-08 18:24:13.837  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-08 18:24:13.838  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-08 18:24:13.842  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-08 18:24:13.852  2350  8277 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-08 18:24:13.862  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2419710a time:139650
,09-08 18:24:13.876  1036  1052 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8278 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-08 18:24:13.907  8278  8278 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:24:13.908  8278  8278 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 18:24:13.909  8278  8278 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 18:24:13.909  8278  8278 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-08 18:24:13.910  1036  1124 I art     : Explicit concurrent mark sweep GC freed 85936(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 2.841ms total 359.980ms
09-08 18:24:13.922   309  8297 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-08 18:24:13.923   309  8297 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-08 18:24:13.965  8218  8218 D AndroidRuntime: Shutting down VM
,09-08 18:24:13.995  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8298 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-08 18:24:13.998  8278  8278 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-08 18:24:14.006  8278  8278 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-08 18:24:14.028  1036  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:24:14.030  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-08 18:24:14.032  1036  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-08 18:24:14.035  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-08 18:24:14.036  8278  8278 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-08 18:24:14.040  1036  2052 I ActivityManager: Killing 7679:com.google.android.talk/u0a72 (adj 15): empty #17
09-08 18:24:14.061  8278  8278 D LgDataFeature: LgDataFeature() Constructor: none
09-08 18:24:14.062  8278  8278 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 18:24:14.067  2034  2872 I GBoardtInterface: onReloaded()
09-08 18:24:14.069  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,09-08 18:24:14.142  1036  1699 W libprocessgroup: failed to open /acct/uid_10072/pid_7679/cgroup.procs: No such file or directory
,09-08 18:24:14.144  3726  4490 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-08 18:24:14.146  3726  3742 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-08 18:24:14.151  1906  1906 D ActionManagerService: notifyUserLog: 1000001
09-08 18:24:14.153  3726  4492 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-08 18:24:14.153  3726  4492 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-08 18:24:14.156  1906  1906 D ActionManagerService: notifyUserLog: 1000001
,09-08 18:24:14.158  3726  4492 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-08 18:24:14.158  3726  4492 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-08 18:24:14.158  3726  4492 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-08 18:24:14.159  3726  4492 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-08 18:24:14.159  3726  4490 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-08 18:24:14.161  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-08 18:24:14.161  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-08 18:24:14.163  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-08 18:24:14.163  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-08 18:24:14.165  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-08 18:24:14.165  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-08 18:24:14.172  8278  8278 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-08 18:24:14.186   309  8297 D libc-netbsd: res_queryN name = android.clients.google.com succeed
09-08 18:24:14.186  1036  1905 I ActivityManager: Killing 7772:com.android.vending/u0a44 (adj 15): empty #17
,09-08 18:24:14.196  1036  1436 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=64.0, 0.0, 0.0  rx=55.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:178071668] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 18:24:14.197  1036  1436 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=64.0, 0.0, 0.0  rx=55.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:178071669] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 18:24:14.197  1036  1436 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-08 18:24:14.240  1036  1441 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-08 18:24:14.252  1996  1996 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-08 18:24:14.252  1996  1996 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,09-08 18:24:14.253  1996  1996 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-08 18:24:14.255  1036  1988 W libprocessgroup: failed to open /acct/uid_10044/pid_7772/cgroup.procs: No such file or directory
09-08 18:24:14.255  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:24:14.259  8076  8076 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 18:24,:14.259  8076  8076 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 18:24:14.264  8076  8076 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-08 18:24:14.266  1036  1484 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:24:14.267  7488  7488 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
09-08 18:24:14.269  6818  6818 D PackageIntentReceiver: Not supported Hotkey customization function 
09-08 18:24:14.270  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 18:24:14.270  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-08 18:24:14.273  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-08 18:24:14.274  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:24:14.275  2454  2543 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.backuptransport/shared_prefs/BackupTransport.backupScheduler.xml to backup file /data/data/com.google.android.backuptransport/shared_prefs/BackupTransport.backupScheduler.xml.bak
09-08 18:24:14.277  6818  6818 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-08 18:24:14.277  6818  6818 D HideNavigationAppsReceiver: replacing : false
,09-08 18:24:14.280  6818  6818 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
,09-08 18:24:14.282  6818  6818 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-08 18:24:14.282  6818  6818 D ButtonCombinationReceiver: replacing : false
09-08 18:24:14.310  1036  1959 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8323 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a

```
