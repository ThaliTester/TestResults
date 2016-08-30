#### Test 82642184cbac892_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 02:46:03.598  6487  6487 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
--------- beginning of system
08-30 02:46:03.648  1036  2042 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6518 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-30 02:46:03.650  1036  2042 I ActivityManager: Killing 6071:com.android.vending/u0a44 (adj 15): empty #17
08-30 02:46:03.719  1036  1052 W libprocessgroup: failed to open /acct/uid_10044/pid_6071/cgroup.procs: No such file or directory
08-30 02:46:03.744  6518  6518 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 02:46:03.744  6518  6518 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 02:46:03.744  6518  6518 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 02:46:03.745  6518  6518 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 02:46:03.869  6518  6518 I AppConfig: Total System Memory = 2995761152
08-30 02:46:03.881  6518  6518 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 02:46:03.922  1036  2107 I ActivityManager: Killing 6109:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 02:46:03.961  1036  1977 W libprocessgroup: failed to open /acct/uid_10080/pid_6109/cgroup.procs: No such file or directory
08-30 02:46:03.962  2053  2053 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-30 02:46:03.962  2053  2053 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-30 02:46:03.966  2053  2053 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-30 02:46:03.994  6373  6373 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-30 02:46:04.002  6373  6373 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-30 02:46:04.048  1036  1652 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6550 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 02:46:04.245   337   435 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 02:46:04.251  3248  6571 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 02:46:04.300  6550  6550 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-30 02:46:04.407  6550  6550 D LgDataFeature: LgDataFeature() Constructor: none
08-30 02:46:04.407  6550  6550 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 02:46:04.461  6550  6550 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-30 02:46:04.491  6550  6550 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 02:46:04.495  6550  6550 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 02:46:04.522  6550  6550 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 02:46:04.522  6550  6550 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-30 02:46:04.541  1036  1574 I ActivityManager: Killing 5477:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-30 02:46:04.573  1036  2042 W libprocessgroup: failed to open /acct/uid_10085/pid_5477/cgroup.procs: No such file or directory
08-30 02:46:04.588  5026  6588 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-30 02:46:04.594  3418  3596 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 02:46:04.595  3418  3596 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2f26d373 on behalf of 6550
08-30 02:46:04.639  1036  2042 V SIM_STK : Menu title from STK is T-Mobile
08-30 02:46:04.643  1036  1970 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6591 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 02:46:04.704  6550  6550 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-30 02:46:04.732  6550  6550 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-30 02:46:04.783  5026  6588 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 195 ms] updated apps [took 195 ms] 
08-30 02:46:04.811  6591  6591 D DocsApplication: Installing DEX configuration.
08-30 02:46:04.828  6591  6591 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-30 02:46:04.831  6591  6591 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3914615d com.google.android.apps.docs}
08-30 02:46:04.846  6591  6591 D TAG     : onCreate()
08-30 02:46:04.853  6589  6589 D AndroidRuntime: 
08-30 02:46:04.853  6589  6589 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 02:46:04.856  6589  6589 D AndroidRuntime: CheckJNI is OFF
08-30 02:46:04.864  6591  6591 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-30 02:46:04.973  6589  6589 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 02:46:04.978  1036  1051 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 02:46:04.999  1979  2004 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 02:46:05.003  1036  1051 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 02:46:05.005  1036  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{3bf99f23 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 02:46:05.005  1036  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{3bf99f23 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 02:46:05.006  1036  1051 D WindowStateEx: AppWindowTokenEx init.. 
08-30 02:46:05.007   344   353 E GBMv2   : DFP En is all cleared set to be enabled
08-30 02:46:05.043  1036  1051 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6639 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 02:46:05.046  6589  6589 D AndroidRuntime: Shutting down VM
08-30 02:46:05.102  1979  4391 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 02:46:05.102  1979  4391 D SplitWindowPolicy: topRunningActivity=ActivityInfo{b6afc69 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 02:46:05.104  1979  2003 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 02:46:05.104  1979  2003 D SplitWindowPolicy: topRunningActivity=ActivityInfo{17aba6ee co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 02:46:05.152  6639  6639 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 02:46:05.258  6639  6639 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 02:46:05.266  6639  6639 I LibraryLoader: Loading: webviewchromium
08-30 02:46:05.269  6639  6639 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5517-5520)
08-30 02:46:05.269  6639  6639 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 02:46:05.285  6639  6639 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6f46aff}
,08-30 02:46:05.286  6639  6639 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 02:46:05.287  6639  6639 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 02:46:05.295  6639  6639 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 02:46:05.296  6639  6639 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 02:46:05.306   323  1384 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
,08-30 02:46:05.309  6639  6639 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 02:46:05.309  6639  6639 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 02:46:05.310  6639  6639 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-30 02:46:05.310  1036  1116 D BluetoothManagerService: Message: 20
08-30 02:46:05.310  1036  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@813ca95:true
08-30 02:46:05.322  6639  6639 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 02:46:05.322  6639  6639 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 02:46:05.322  6639  6639 I Adreno-EGL: Build Date: 12/12/14 금
08-30 02:46:05.322  6639  6639 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 02:46:05.322  6639  6639 I Adreno-EGL: Remote Branch: 
08-30 02:46:05.322  6639  6639 I Adreno-EGL: Local Patches: 
08-30 02:46:05.322  6639  6639 I Adreno-EGL: Reconstruct Branch: 
,08-30 02:46:05.384  6639  6668 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 02:46:05.390  6639  6639 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 02:46:05.406  6639  6639 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 02:46:05.410  6639  6639 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 02:46:05.413  6639  6639 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 02:46:05.415  6639  6639 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 02:46:05.415  6639  6639 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-30 02:46:05.428  6639  6639 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-30 02:46:05.434  6639  6639 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 02:46:05.434  6639  6639 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 02:46:05.468  6639  6680 D OpenGLRenderer: Render dirty regions requested: true
08-30 02:46:05.469  6639  6680 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 02:46:05.485  6639  6680 D OpenGLRenderer: Enabling debug mode 0
,08-30 02:46:05.496  6639  6639 D Atlas   : Validating map...
,08-30 02:46:05.502  1036  2094 D SplitWindow: check instance of lgWin Window{8063f67 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 02:46:05.573  6639  6678 D LgDataFeature: LgDataFeature() Constructor: none
08-30 02:46:05.573  6639  6678 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 02:46:05.613  1036  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +511ms (total +605ms)
08-30 02:46:05.613  1036  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{fd79c20 u0 com.test.thalitest/.MainActivity t6} time:105865
,08-30 02:46:05.620  6639  6639 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1cc359da time:105872
08-30 02:46:05.728  6639  6639 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 02:46:05.728  6639  6639 I chromium: 
,08-30 02:46:05.764  6639  6639 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 02:46:05.789  1843  5114 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-30 02:46:05.843  1843  5114 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-30 02:46:05.877  6639  6691 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435064832
,08-30 02:46:05.886  6639  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 02:46:05.886  6639  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 02:46:05.886  6639  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 02:46:05.886  6639  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 02:46:05.886  6639  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 02:46:05.886  6639  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@257d77e added. We now have 1 listener(s)
08-30 02:46:05.890  1036  1652 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 02:46:05.893  6639  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 02:46:05.895  6639  6691 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 02:46:05.896  6639  6691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 02:46:05.896  6639  6691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 02:46:05.902  6639  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e60bf5 added. We now have 1 listener(s)
08-30 02:46:05.903  6639  6691 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 02:46:05.906  1036  1543 D WifiService: New client listening to asynchronous messages
08-30 02:46:05.908  1843  5114 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-30 02:46:05.911  6639  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 02:46:05.911  6639  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 02:46:05.912  6639  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 02:46:05.912  6639  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 02:46:05.912  6639  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 02:46:05.915  6639  6691 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 02:46:05.915  1036  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 02:46:05.915  6639  6691 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-30 02:46:05.924  6639  6691 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 02:46:05.924  6639  6691 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:46:05.924  6639  6691 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:46:05.924  6639  6691 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 02:46:05.924  6639  6691 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:46:05.924  6639  6691 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:46:05.924  6639  6691 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:46:05.924  6639  6691 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:46:05.924  6639  6691 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 02:46:05.924  6639  6691 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 02:46:05.924  6639  6691 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 02:46:05.927  6639  6639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 02:46:05.928  6639  6639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 02:46:05.929  6639  6691 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 02:46:05.952  6639  6678 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 02:46:05.952  6639  6678 I chromium: 
,08-30 02:46:05.987  6639  6639 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 02:46:06.343  6591  6591 D LgDataFeature: LgDataFeature() Constructor: none
08-30 02:46:06.343  6591  6591 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 02:46:06.588  1036  2107 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6709 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-30 02:46:06.589  1036  2107 I ActivityManager: Killing 6129:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-30 02:46:06.600   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 21.634ms
08-30 02:46:06.621   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 515us total 20.021ms
,08-30 02:46:06.643   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 21.150ms
,08-30 02:46:06.654   344   355 E GBMv2   : DFP En is all cleared set to be enabled
08-30 02:46:06.654   344   355 E GBMv2   : Set value is all cleared set the max
08-30 02:46:06.654   344   355 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 02:46:06.755  1036  2095 W libprocessgroup: failed to open /acct/uid_10097/pid_6129/cgroup.procs: No such file or directory
,08-30 02:46:06.768  6591  6591 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-30 02:46:06.799  6709  6709 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 02:46:06.977  1036  1052 I art     : Explicit concurrent mark sweep GC freed 30302(1449KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 3.363ms total 159.209ms
,08-30 02:46:06.980  6709  6709 I LockScreenSettings: New app installed broadcast received ..
08-30 02:46:06.992  6709  6709 I LockScreenSettings: Number of installed packages  1
,08-30 02:46:07.026  1036  2022 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6730 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 02:46:07.078  6730  6730 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 02:46:07.092  6639  6698 W jxcore-log: Initializing JXcore engine
08-30 02:46:07.092  6639  6698 W jxcore-log: JXcore engine is ready
,08-30 02:46:07.122  6698  6698 W Thread-787: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10295]" dev="sockfs" ino=10295 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 02:46:07.122  6698  6698 W Thread-787: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 02:46:07.122  6698  6698 W Thread-787: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7680]" dev="sockfs" ino=7680 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 02:46:07.122  6698  6698 W Thread-787: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 02:46:07.122  6698  6698 W Thread-787: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[29499]" dev="sockfs" ino=29499 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-30 02:46:07.139  6639  6698 W jxcore-log: Starting JXcore engine
08-30 02:46:07.214  6639  6698 W jxcore-log: Platform android
08-30 02:46:07.214  6639  6698 W jxcore-log: 
08-30 02:46:07.214  6639  6698 W jxcore-log: Process ARCH arm
08-30 02:46:07.214  6639  6698 W jxcore-log: 
,08-30 02:46:07.304  1036  2042 V SIM_STK : Menu title from STK is T-Mobile
,08-30 02:46:07.349  1036  1977 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6763 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 02:46:07.406  6639  6698 I jxcore-log: JXcore Cordova bridge is ready!
08-30 02:46:07.406  6639  6698 I jxcore-log: 
08-30 02:46:07.406  6639  6698 W jxcore-log: JXcore engine is started
08-30 02:46:07.415  6639  6691 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 02:46:07.418  6763  6763 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-30 02:46:07.418  6763  6763 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-30 02:46:07.418  6639  6639 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-30 02:46:07.421  5614  5614 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-30 02:46:07.441  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-30 02:46:07.465  1036  1051 I ActivityManager: Killing 5969:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 02:46:07.632  1036  1652 W libprocessgroup: failed to open /acct/uid_10072/pid_5969/cgroup.procs: No such file or directory
,08-30 02:46:10.424  6591  6591 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-30 02:46:10.427  1036  1767 I ActivityManager: Killing 6163:com.google.android.gm/u0a64 (adj 15): empty #17
08-30 02:46:10.530  1036  1977 W libprocessgroup: failed to open /acct/uid_10064/pid_6163/cgroup.procs: No such file or directory
,08-30 02:46:10.681  2801  2801 I MusicWidget: mDelayedStopHandler : unbind
,08-30 02:46:10.688  2225  2225 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
,08-30 02:46:10.689  2225  2225 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
,08-30 02:46:10.690  2225  2225 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-30 02:46:10.693  2225  2225 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-30 02:46:10.694  2225  2225 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-30 02:46:10.695  2225  2225 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-30 02:46:10.700  2225  2225 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
,08-30 02:46:10.700  2225  2225 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-30 02:46:10.702  1036  1652 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@210ca4fccom.lge.music.MediaPlaybackService$5@38f3785
,08-30 02:46:10.709  2225  2225 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-30 02:46:10.710  2225  2225 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 02:46:10.719  2225  2225 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 02:46:10.722  2225  2225 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 02:46:10.724  2225  2225 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@21aeb81b
08-30 02:46:10.725  2225  2225 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 02:46:10.726  2225  2225 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-30 02:46:10.727  2225  2225 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 02:46:10.728  2225  2225 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-30 02:46:10.729  2225  2225 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-30 02:46:10.730  2225  2225 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 02:46:10.732  2225  2225 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 02:46:10.736  2225  2225 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 02:46:10.738  2225  2225 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 02:46:10.739  2225  2225 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 02:46:10.749  2225  2225 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,08-30 02:46:10.752  2225  2225 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-30 02:46:10.753  2225  2225 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-30 02:46:10.753  2225  2225 V MediaPlayer[Native]: reset
08-30 02:46:10.759  2225  2225 V MediaPlayer[Native]: setListener
08-30 02:46:10.759  2225  2225 V MediaPlayer[Native]: disconnect
,08-30 02:46:10.759  2225  2225 V MediaPlayer[Native]: destructor
08-30 02:46:10.759   323  1384 V AudioFlinger: releasing 18 from 2225 for -1
08-30 02:46:10.759   323  1384 V AudioFlinger:  decremented refcount to 0
08-30 02:46:10.759   323  1384 V AudioFlinger: purging stale effects
08-30 02:46:10.759  2225  2225 V MediaPlayer[Native]: disconnect
08-30 02:46:10.761  2225  2225 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-30 02:46:10.762  2225  2225 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-30 02:46:10.762  2225  2225 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-30 02:46:10.763  2225  2225 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018,
08-30 02:46:10.763  2225  2225 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-30 02:46:10.764  2225  2225 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-30 02:46:10.764  2225  2225 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 482564570
08-30 02:46:10.764  2225  2225 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 482564570
,08-30 02:46:10.779  2225  2225 I SmartShareClient: [SmartShareManagerClient] terminate service: 2225/MediaPlaybackService/993703513
,08-30 02:46:10.784  2225  2225 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-30 02:46:10.784  2225  2225 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@1d29de0b
08-30 02:46:10.787  2225  2225 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-30 02:46:10.787  2225  2225 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-30 02:46:10.789  2225  2225 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-30 02:46:10.789  2225  2225 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-30 02:46:10.791  1036  1051 I ActivityManager: Killing 5748:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 02:46:10.800  2225  2225 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
08-30 02:46:10.806  5724  5724 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-30 02:46:10.806  5724  5724 W System.err: android.os.DeadObjectException
,08-30 02:46:10.806  5724  5724 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-30 02:46:10.806  5724  5724 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 02:46:10.806  5724  5724 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 02:46:10.806  5724  5724 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 02:46:10.806  5724  5724 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 02:46:10.806  5724  5724 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 02:46:10.806  5724  5724 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 02:46:10.806  5724  5724 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 02:46:10.806  5724  5724 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 02:46:10.806  5724  5724 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 02:46:10.806  5724  5724 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:46:10.806  5724  5724 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:46:10.806  5724  5724 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 02:46:10.807  5724  5724 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 02:46:10.807  5724  5724 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 02:46:10.807  5724  5724 W System.err: android.os.DeadObjectException
08-30 02:46:10.807  5724  5724 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 02:46:10.807  5724  5724 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-30 02:46:10.807  5724  5724 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 02:46:10.807  5724  5724 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-30 02:46:10.807  5724  5724 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 02:46:10.807  5724  5724 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317),
08-30 02:46:10.807  5724  5724 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 02:46:10.807  5724  5724 W System.err: 	,at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 02:46:10.807  5724  5724 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-30 02:46:10.807  5724  5724 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 02:46:10.807  5724  5724 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-30 02:46:10.807  5724  5724 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:46:10.807  5724  5724 W System.err: 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 02:46:10.807  5724  5724 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 02:46:10.807  5724  5724 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 02:46:10.809  5724  5724 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 02:46:11.089  1036  2022 W libprocessgroup: failed to open /acct/uid_1000/pid_5748/cgroup.procs: No such file or directory,
,08-30 02:46:11.090  1036  2022 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms,
,08-30 02:46:11.108  1036  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=194537284, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-30 02:46:11.110  5724  5724 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 02:46:11.110  5724  5724 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 02:46:11.142  1036  1945 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6801 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 02:46:11.145  5724  5724 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 02:46:11.174  2664  2664 D [Concierge]Service: onStartCommand(). Type : 9
08-30 02:46:11.180  4923  6798 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-30 02:46:11.184  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=194537284 [*alarm*], flags=0x0
08-30 02:46:11.236  6801  6801 D UEI.SmartControl: Quickset Services start...
08-30 02:46:11.237  6801  6801 I UEI.SmartControl: Manufacture = LGE
08-30 02:46:11.237  6801  6801 D UEI.SmartControl: Id = LGNevo
,08-30 02:46:11.239  6801  6801 D UEI.SmartControl: File observer start...
,08-30 02:46:11.241  6801  6801 E UEI.SmartControl: IR Port is disabled: false
08-30 02:46:11.241  6801  6801 D UEI.SmartControl: Starting file observer...
08-30 02:46:11.242  6801  6801 D UEI.SmartControl: Extracting JNI libs...
08-30 02:46:11.242  6801  6801 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 02:46:11.287  6801  6801 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 02:46:11.287  6801  6801 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-30 02:46:11.287  6801  6801 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-30 02:46:11.306  6801  6801 I UEI.SmartControl: --- Selecting new region: 6
,08-30 02:46:11.307  6801  6801 I UEI.SmartControl: Model = LG-D855
08-30 02:46:11.309  6801  6801 D UEI.SmartControl: QS Service created
08-30 02:46:11.320  6801  6801 I UEI.SmartControl: Service initServices...
08-30 02:46:11.323  6801  6801 D UEI.SmartControl: QS start get config
,08-30 02:46:11.372  6801  6801 D UEI.SmartControl: Loading JNI Libs...
,08-30 02:46:11.407  6591  6703 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 02:46:11.619  6801  6801 I UEI.SmartControl: Supports setup maps: true
,08-30 02:46:11.622  6801  6801 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 02:46:11.622  6801  6801 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-30 02:46:11.622  6801  6801 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 02:46:11.622  6801  6801 I UEI.SmartControl: ### init IR Blaster...
08-30 02:46:11.627  6801  6801 D serial_port: Configuring serial port
,08-30 02:46:11.630  6801  6801 E UEI.SmartControl: UEIBLaster setting for 616
08-30 02:46:11.631  6801  6801 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 02:46:11.631  6801  6801 I UEI.SmartControl: configuring settings for MAXQ616
08-30 02:46:11.631  6801  6801 I UEI.SmartControl: Get version...
,08-30 02:46:11.648  6801  6841 D UEI.SmartControl: serial port data available: 21
,08-30 02:46:11.677  6801  6801 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 02:46:11.677  6801  6801 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 02:46:11.677  6801  6801 I UEI.SmartControl: QS saving settings...
,08-30 02:46:11.681  6801  6801 D UEI.SmartControl: IR Blaster version: 25672567
08-30 02:46:11.698  6801  6841 D UEI.SmartControl: serial port data available: 4
,08-30 02:46:11.735  6801  6844 I UEI.SmartControl: Device manager: loading config....
08-30 02:46:11.736  6801  6844 D UEI.SmartControl: ----------- loading internal config...
,08-30 02:46:11.739  6801  6801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 02:46:11.742  6801  6801 E UEI.SmartControl: Services init done
08-30 02:46:11.742  6801  6801 D UEI.SmartControl: QS Service init finished
08-30 02:46:11.743  6801  6801 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 02:46:11.743  6801  6801 D UEI.SmartControl: QS Service version code: 201091
08-30 02:46:11.744  6801  6801 D UEI.SmartControl: Service requested: Control
08-30 02:46:11.756  6801  6844 E UEI.SmartControl: Loading SETTINGS...
,08-30 02:46:11.760  6801  6801 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 02:46:11.765  5724  5724 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 02:46:11.765  1036  1652 I ActivityManager: Killing 5724:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 02:46:11.766  6801  6816 I UEI.SmartControl: ------ IControl API: 11
08-30 02:46:11.767  6801  6816 I UEI.SmartControl: Registering callback...
08-30 02:46:11.775  6801  6844 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 02:46:11.791  6801  6843 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 02:46:11.791  6801  6843 D UEI.SmartControl: -----service ready thread exits
,08-30 02:46:11.880  1036  1767 W libprocessgroup: failed to open /acct/uid_10112/pid_5724/cgroup.procs: No such file or directory
08-30 02:46:11.880  6801  6801 D UEI.SmartControl: Internal service binding...
,08-30 02:46:12.287  1036  2094 I ActivityManager: Killing 5658:com.android.calendar/u0a13 (adj 15): empty #17
,08-30 02:46:12.399  1036  1976 W libprocessgroup: failed to open /acct/uid_10013/pid_5658/cgroup.procs: No such file or directory
,08-30 02:46:16.734  6801  6845 D UEI.SmartControl: Internal timer expired: 1
,08-30 02:46:16.735  6801  6845 D UEI.SmartControl: unbind internal service
,08-30 02:46:16.749  6801  6801 D UEI.SmartControl: Service.onUnbind: IControl
08-30 02:46:16.750  6801  6801 D UEI.SmartControl: Service.onDestroy
08-30 02:46:16.750  6801  6801 D UEI.SmartControl: Lock is in USE false
08-30 02:46:16.750  6801  6801 D UEI.SmartControl: unbind internal service
,08-30 02:46:16.755  6801  6801 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@21aeb81b
08-30 02:46:16.756  6801  6801 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-30 02:46:16.756  6801  6801 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 02:46:16.756  6801  6801 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 02:46:16.756  6801  6801 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 02:46:16.757  6801  6801 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-30 02:46:16.757  6801  6801 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-30 02:46:16.757  6801  6801 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-30 02:46:16.757  6801  6801 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-30 02:46:16.757  6801  6801 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:16.757  6801  6801 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 02:46:16.757  6801  6801 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 02:46:16.757  6801  6801 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:46:16.757  6801  6801 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:46:16.757  6801  6801 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 02:46:16.758  6801  6801 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 02:46:16.758  6801  6801 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@21aeb81b
08-30 02:46:16.758  6801  6842 D serial_port: close(fd = 25)
08-30 02:46:16.823  6801  6842 I UEI.SmartControl: Serial port is closed.
,08-30 02:46:16.838  6801  6801 I UEI.SmartControl: Serial port is closed.
,08-30 02:46:16.839  6801  6801 I UEI.SmartControl: Serial port is closed.
08-30 02:46:16.839  6801  6801 D UEI.SmartControl: Blaster closed
08-30 02:46:16.840  6801  6801 D UEI.SmartControl: Shut down QS...
08-30 02:46:16.840  6801  6801 D UEI.SmartControl: Stopping QS lib
08-30 02:46:16.842  6801  6801 D UEI.SmartControl: QS lib stop result = true
08-30 02:46:16.842  6801  6801 D UEI.SmartControl: Stopped QS lib
08-30 02:46:16.842  6801  6801 D UEI.SmartControl: Stopped file observer...
08-30 02:46:16.842  6801  6801 D UEI.SmartControl: QS shutdown complete
08-30 02:46:17.818  1036  1092 I ActivityManager: Waited long enough for: ServiceRecord{136f018e u0 com.google.android.gms/.wearable.service.WearableService}
,08-30 02:46:20.828  2225  2225 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19980
,08-30 02:46:25.906  1036  1377 V AlarmManager: RTC_WAKEUP set : Alarm{2210f56b type 0 when 1472517979527 com.android.vending} when 1472517979527
,08-30 02:46:26.048  1036  1977 V SIM_STK : Menu title from STK is T-Mobile
,08-30 02:46:26.202  6550  6550 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 02:46:26.776  6639  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 02:46:26.776  6639  6698 I jxcore-log: 
,08-30 02:46:26.778  6639  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 02:46:26.778  6639  6698 I jxcore-log: 
08-30 02:46:26.781  6639  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:46:26.781  6639  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:46:26.781  6639  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 02:46:26.781  6639  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:46:26.781  6639  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:46:26.781  6639  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:46:26.781  6639  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:46:26.781  6639  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 02:46:26.782  6639  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 02:46:26.784  6639  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 02:46:26.784  6639  6698 I jxcore-log: 
08-30 02:46:26.786  6639  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 02:46:26.786  6639  6698 I jxcore-log: 
08-30 02:46:27.128  6639  6698 I jxcore-log: Running unit tests
08-30 02:46:27.128  6639  6698 I jxcore-log: 
08-30 02:46:27.129  6639  6698 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 02:46:27.129  6639  6698 I jxcore-log: Failed to execute UT.
08-30 02:46:27.129  6639  6698 I jxcore-log: 
08-30 02:46:27.130  6639  6698 I jxcore-log: Unit Test app is loaded
08-30 02:46:27.130  6639  6698 I jxcore-log: 
08-30 02:46:27.135  6639  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 02:46:27.135  6639  6698 I jxcore-log: 
,08-30 02:46:27.142  6639  6698 I jxcore-log: My device name is: LGE-LG-D855
08-30 02:46:27.142  6639  6698 I jxcore-log: 
08-30 02:46:27.144  6639  6698 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 02:46:27.144  6639  6698 I jxcore-log: 
08-30 02:46:27.151  6639  6639 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 02:46:29.603  6639  6698 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 02:46:29.603  6639  6698 I jxcore-log: 
,08-30 02:46:30.044  6639  6698 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 02:46:30.044  6639  6698 I jxcore-log: 
,08-30 02:46:30.069  6639  6698 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 02:46:30.069  6639  6698 I jxcore-log: 
,08-30 02:46:31.426  6639  6698 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 02:46:31.426  6639  6698 I jxcore-log: 
,08-30 02:46:31.659  6639  6698 I jxcore-log: ERROR runTests: 
08-30 02:46:31.659  6639  6698 I jxcore-log: 
,08-30 02:46:31.663  6639  6698 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:46:31.663  6639  6698 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 02:46:31.665  6639  6698 I jxcore-log: WARN testUtils: logCallback not set!
08-30 02:46:31.665  6639  6698 I jxcore-log: 
08-30 02:46:31.674  6639  6698 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _functionName: 'loadFile',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _lineNumber: '26',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _columnNumber: '11',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 02:46:31.674  6639  6698 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _functionName: '',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _lineNumber: '38',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _columnNumber: '7',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 02:46:31.674  6639  6698 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _functionName: '',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _lineNumber: '35',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _columnNumber: '3',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 02:46:31.674  6639  6698 I jxcore-log:   { _fileName: 'module.js',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _lineNumber: '621',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _columnNumber: '8',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 02:46:31.674  6639  6698 I jxcore-log:   { _fileName: 'module.js',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _lineNumber: '651',
08-30 02:46:31.674  6639  6698 I jxcore-log:     _columnNumber: '1',
,08-30 02:46:31.674  6639  6698 I jxcore-log:    
08-30 02:46:31.674  6639  6698 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 02:46:31.674  6639  6698 I jxcore-log: 
,08-30 02:46:31.675  6639  6698 E jxcore-log: Error: 
08-30 02:46:31.675  6639  6698 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:46:31.675  6639  6698 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 02:46:31.675  6639  6698 E jxcore-log: 
,08-30 02:46:32.017  6884  6884 D AndroidRuntime: 
08-30 02:46:32.017  6884  6884 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 02:46:32.022  6884  6884 D AndroidRuntime: CheckJNI is OFF
08-30 02:46:32.189  6884  6884 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 02:46:32.209  1036  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-30 02:46:32.210  1036  1092 I ActivityManager: Killing 6639:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-30 02:46:32.255  1036  2022 I WindowState: WIN DEATH: Window{8063f67 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 02:46:32.256  1036  1543 D WifiService: Client connection lost with reason: 4
08-30 02:46:32.260  1036  2022 D InputDispatcher: Window went away: Window{8063f67 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 02:46:32.430  1036  1092 I ActivityManager:   Force finishing activity ActivityRecord{fd79c20 u0 com.test.thalitest/.MainActivity t6}
,08-30 02:46:32.487   344   353 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 02:46:32.497  1036  1991 W ActivityManager: Spurious death for ProcessRecord{27c148c8 6639:com.test.thalitest/u0a118}, curProc for 6639: null
08-30 02:46:32.499  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 02:46:32.502  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{fd79c20 u0 com.test.thalitest/.MainActivity t6 f}
08-30 02:46:32.502  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{fd79c20 u0 com.test.thalitest/.MainActivity t6 f}
,08-30 02:46:32.548  5026  5026 I art     : Explicit concurrent mark sweep GC freed 476(32KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 584us total 36.988ms
,08-30 02:46:32.552  2096  2096 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 02:46:32.552  1979  2003 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 02:46:32.553  1979  2003 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b06c78f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 02:46:32.553  2096  2096 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-30 02:46:32.555  1979  4391 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 02:46:32.556  1979  4391 D SplitWindowPolicy: topRunningActivity=ActivityInfo{a4aba1c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 02:46:32.558  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 02:46:32.559  2096  2162 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-30 02:46:32.566  1939  1939 D ActionManagerService: notifyUserLog: 1000003
08-30 02:46:32.566  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 02:46:32.567  3809  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 02:46:32.567  2096  2096 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 02:46:32.569  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 02:46:32.575  1036  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 02:46:32.589  2454  2597 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 02:46:32.600  3809  3809 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 02:46:32.603  2096  2096 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-30 02:46:32.604  2096  2096 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 02:46:32.605  4291  4291 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 02:46:32.605  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 02:46:32.605  2053  2053 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-30 02:46:32.609  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 02:46:32.638  1036  2042 V SIM_STK : Menu title from STK is T-Mobile
,08-30 02:46:32.654  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 02:46:32.659  4923  4923 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 02:46:32.659  4923  4923 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 02:46:32.659  4923  4923 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 02:46:32.659  4923  4923 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 02:46:32.659  4923  4923 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 02:46:32.659  4923  4923 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 02:46:32.659  4923  4923 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 02:46:32.659  4923  4923 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 02:46:32.659  4923  4923 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:46:32.659  4923  4923 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:46:32.659  4923  4923 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 02:46:32.659  4923  4923 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 02:46:32.671  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-30 02:46:32.672  1843  1843 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-30 02:46:32.673  1939  1939 D ActionManagerService: notifyUserLog: 1000004
08-30 02:46:32.673  3809  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 02:46:32.675  3809  4917 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 02:46:32.677  1603  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 02:46:32.677  1603  1650 D KeyguardModel: createShortcutInfo...
08-30 02:46:32.687  1603  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 02:46:32.687  1603  1650 D KeyguardModel: createShortcutInfo...
,08-30 02:46:32.691  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 02:46:32.691  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 02:46:32.695  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 02:46:32.695  1603  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 02:46:32.695  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 02:46:32.696  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 02:46:32.697  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:32.697  1603  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 02:46:32.702  1603  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 02:46:32.702  1603  1650 D KeyguardModel: createShortcutInfo...
,08-30 02:46:32.708  1036  1036 I art     : Explicit concurrent mark sweep GC freed 17455(1176KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.839ms total 183.052ms
08-30 02:46:32.709  1036  1124 I art     : WaitForGcToComplete blocked for 10.550ms for cause Explicit
08-30 02:46:32.712  1905  1905 D SplitUIManager: split_name #11 / not available #0
08-30 02:46:32.712  1905  1905 D SplitUIService: removed split : 
08-30 02:46:32.715  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-30 02:46:32.715  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 02:46:32.716  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:32.716  1603  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 02:46:32.719  1603  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 02:46:32.719  1603  1650 D KeyguardModel: createShortcutInfo...
08-30 02:46:32.724  2266  2266 I ConfigService: onCreate
08-30 02:46:32.724  2266  2266 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 02:46:32.727  2266  2266 I ConfigService: onBind returning update interface
,08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , expire_time: 0
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , display: false
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , animation: false }
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , expire_time: 0
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , display: false
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , animation: false }
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , expire_time: 0
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , display: false
08-30 02:46:32.729  2096  2096 I GBoardWebViewUtils: , animation: false }
08-30 02:46:32.742  2266  2266 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 02:46:32.742  2266  2266 I ConfigService: onBind returning config service
08-30 02:46:32.742  1843  1843 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-30 02:46:32.753  1905  1905 D SplitUIManager: split_name #11 / not available #0
08-30 02:46:32.753  1905  1905 I SplitUIService: split app #11
08-30 02:46:32.755  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 02:46:32.757  1603  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 02:46:32.757  1603  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 02:46:32.757  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 02:46:32.757  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 02:46:32.757  2096  6913 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-30 02:46:32.758  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:32.759  1603  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 02:46:32.759  1036  2115 V SIM_STK : Menu title from STK is T-Mobile
08-30 02:46:32.759  1036  2115 V SIM_STK : Menu title from STK is T-Mobile
08-30 02:46:32.760  1603  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 02:46:32.760  1603  1650 D KeyguardModel: createShortcutInfo...
08-30 02:46:32.768  1843  1843 I ConfigFetchService: service connected
,08-30 02:46:32.769  1843  1843 I ConfigClient: service connected
08-30 02:46:32.770  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-30 02:46:32.770  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 02:46:32.773  2266  2266 I ConfigService: onDestroy
08-30 02:46:32.779  1603  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 02:46:32.779  1603  1650 D KeyguardModel: createShortcutInfo...
08-30 02:46:32.789  1603  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 02:46:32.789  1603  1650 D KeyguardModel: createShortcutInfo...
,08-30 02:46:32.791  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:32.791  1603  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 02:46:32.792  1603  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 02:46:32.792  1603  1650 D KeyguardModel: createShortcutInfo...
08-30 02:46:32.793  1036  1036 D administrator: Handling package changes for user 0
08-30 02:46:32.796  1843  6915 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 02:46:32.797  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:32.797  1603  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 02:46:32.798  1603  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 02:46:32.798  1603  1650 D KeyguardModel: createShortcutInfo...
08-30 02:46:32.800  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:32.800  1603  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-30 02:46:32.810  1603  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 02:46:32.811  1603  1650 D KeyguardModel: createShortcutInfo...
,08-30 02:46:32.823  1036  2107 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 02:46:32.824  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 02:46:32.824  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 02:46:32.824  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 02:46:32.824  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 02:46:32.824  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 02:46:32.824  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 02:46:32.824  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 02:46:32.824  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 02:46:32.824  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 02:46:32.824  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 02:46:32.824  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 02:46:32.831  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-30 02:46:32.831  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 02:46:32.848  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 02:46:32.851  1036  1945 V SIM_STK : Menu title from STK is T-Mobile
08-30 02:46:32.858  5892  6920 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-30 02:46:32.869  1843  6922 I PeopleContactsSync: CP2 sync disabled
,08-30 02:46:32.870  2096  2096 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-30 02:46:32.872  6458  6458 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-30 02:46:32.884  1843  5114 I Icing   : doRemovePackageData com.test.thalitest
,08-30 02:46:32.890  6487  6487 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-30 02:46:32.892  2185  6924 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 02:46:32.895  1843  6921 W GmsApplication: Using Auth Proxy for data requests.
,08-30 02:46:32.900  1843  6921 W GmsApplication: Using Auth Proxy for data requests.
08-30 02:46:32.910  1036  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-30 02:46:32.933  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 02:46:32.933  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 02:46:32.934  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 02:46:32.937  1036  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 02:46:32.940   337   435 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 02:46:32.941  3248  6926 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 02:46:32.989  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-30 02:46:32.991  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 02:46:32.992  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 02:46:32.994  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 02:46:32.995  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 02:46:32.996  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-30 02:46:33.009  1036  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5d9650a u0 com.lge.launcher2/.Launcher t5} time:133261
,08-30 02:46:33.012  2053  2053 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 02:46:33.012  2053  2053 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-30 02:46:33.012  2053  2053 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-30 02:46:33.017  6373  6373 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 02:46:33.018  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 02:46:33.018  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 02:46:33.020  2096  2294 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 02:46:33.021  2096  2294 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-30 02:46:33.032  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 02:46:33.033  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 02:46:33.033  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 02:46:33.040  2096  2096 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-30 02:46:33.041  1036  1124 I art     : Explicit concurrent mark sweep GC freed 9598(736KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.348ms total 322.448ms
08-30 02:46:33.049  1036  1977 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6931 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 02:46:33.052  2664  2664 D [Concierge]Service: onStartCommand(). Type : 8
08-30 02:46:33.052  2664  2664 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 02:46:33.053  2664  2664 D [Concierge]Service: Update widget ID : 11
08-30 02:46:33.054  2096  2096 D [Concierge]WidgetView: change position of spinner
08-30 02:46:33.056  2096  2096 I [Concierge]WidgetView: initWebView(). Time : 1472517993056
08-30 02:46:33.056  2664  2664 D [Concierge]Service: onStartCommand(). Type : 0
,08-30 02:46:33.072  2096  2096 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 678016466
08-30 02:46:33.072  2096  2096 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 02:46:33.072  2096  2096 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 02:46:33.075  2096  2096 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@5658bdd
08-30 02:46:33.075  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 02:46:33.076  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 02:46:33.076  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 02:46:33.081  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-30 02:46:33.081  2096  2096 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 02:46:33.082  2096  2096 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 02:46:33.082  2096  2096 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472517887900, New one : 1472517993056
08-30 02:46:33.082  2096  2096 D [Concierge]WidgetView: Unregister all receivers
08-30 02:46:33.082  2096  2096 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 02:46:33.083  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 02:46:33.084  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 02:46:33.085  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 02:46:33.086  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 02:46:33.087  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 02:46:33.088  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 02:46:33.094  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 02:46:33.094  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 02:46:33.123  6884  6884 D AndroidRuntime: Shutting down VM
,08-30 02:46:33.133  2096  2096 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 02:46:33.141  2096  2096 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 02:46:33.141  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-30 02:46:33.142  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 02:46:33.144  6931  6931 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 02:46:33.145  6931  6931 W LG Account v2.2: No ProfileInfo entries
08-30 02:46:33.145  6931  6931 I LG Account v2.2: isEnabled: false
08-30 02:46:33.145  6931  6931 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 02:46:33.145  6931  6931 I Feature : [Lifetracker]Country: EU
08-30 02:46:33.145  6931  6931 I Feature : [Lifetracker]Operator: OPEN
08-30 02:46:33.145  6931  6931 I Feature : [Lifetracker]Ranking support: false
08-30 02:46:33.145  6931  6931 I Feature : [Lifetracker]Comfort support: false
08-30 02:46:33.145  6931  6931 I Feature : [Lifetracker]Accessory: true
08-30 02:46:33.145  6931  6931 I Feature : [Lifetracker]Health device: true
08-30 02:46:33.145  6931  6931 I Feature : [Lifetracker]Extra Pedometer: false
08-30 02:46:33.145  6931  6931 I Feature : [Lifetracker]Blood glucose device: false
08-30 02:46:33.146  6931  6931 I Feature : [Lifetracker]Device Number: 3
08-30 02:46:33.146  6931  6931 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-30 02:46:33.161  2096  2096 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1294c5af time:133413
,08-30 02:46:33.180  1036  1945 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6951 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 02:46:33.180  1036  1945 I ActivityManager: Killing 6217:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-30 02:46:33.191  1036  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 02:46:33.202  1036  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 02:46:33.274  2096  2096 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 02:46:33.278  1036  1976 W libprocessgroup: failed to open /acct/uid_10014/pid_6217/cgroup.procs: No such file or directory
08-30 02:46:33.283  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 02:46:33.293  6951  6951 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 02:46:33.293  6951  6951 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 02:46:33.293  6951  6951 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 02:46:33.294  6951  6951 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 02:46:33.294  6951  6951 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 02:46:33.295  6951  6951 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 02:46:33.314  2096  2904 I GBoardtInterface: onReloaded()
,08-30 02:46:33.316  2096  2096 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 02:46:33.317  3809  4917 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 02:46:33.319  3809  3825 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 02:46:33.324  1939  1939 D ActionManagerService: notifyUserLog: 1000001
,08-30 02:46:33.329  3809  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 02:46:33.329  3809  4922 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 02:46:33.332  1939  1939 D ActionManagerService: notifyUserLog: 1000001
08-30 02:46:33.333  3809  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 02:46:33.333  3809  4922 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 02:46:33.333  3809  4922 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 02:46:33.333  3809  4922 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 02:46:33.334  3809  4917 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 02:46:33.336  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 02:46:33.336  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 02:46:33.338  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 02:46:33.338  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 02:46:33.340  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 02:46:33.340  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-30 02:46:33.383  6951  6951 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-30 02:46:33.394  6951  6951 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-30 02:46:33.394  6951  6951 D HideNavigationAppsReceiver: replacing : false
,08-30 02:46:33.396  6951  6951 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-30 02:46:33.398  6951  6951 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
,08-30 02:46:33.398  6951  6951 D ButtonCombinationReceiver: replacing : false
08-30 02:46:33.404  1036  1970 I ActivityManager: Killing 6415:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-30 02:46:33.469  1036  1574 W libprocessgroup: failed to open /acct/uid_10008/pid_6415/cgroup.procs: No such file or directory
,08-30 02:46:33.473  5026  6970 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-30 02:46:33.500  1036  1051 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6971 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a

```
