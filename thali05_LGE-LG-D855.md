#### Test 75789268eab05ed_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-05 11:08:01.424  6476  6476 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-05 11:08:01.439  6476  6476 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-05 11:08:01.501  6476  6476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 11:08:01.537  6476  6476 D LgDataFeature: LgDataFeature() Constructor: none
07-05 11:08:01.537  6476  6476 D LgDataFeature: LgDataFeature() Constructor Done, null
07-05 11:08:01.673  6476  6476 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
--------- beginning of system
07-05 11:08:01.719  1037  1560 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6507 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
07-05 11:08:01.720  1037  1560 I ActivityManager: Killing 6003:com.android.vending/u0a44 (adj 15): empty #17
07-05 11:08:01.841  6503  6503 D AndroidRuntime: 
07-05 11:08:01.841  6503  6503 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 11:08:01.846  6503  6503 D AndroidRuntime: CheckJNI is OFF
07-05 11:08:01.846  1037  1052 W libprocessgroup: failed to open /acct/uid_10044/pid_6003/cgroup.procs: No such file or directory
07-05 11:08:01.894  6507  6507 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 11:08:01.895  6507  6507 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-05 11:08:01.895  6507  6507 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-05 11:08:01.895  6507  6507 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-05 11:08:02.002  6503  6503 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 11:08:02.009  1037  1872 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 11:08:02.045  1927  1942 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-05 11:08:02.051  1037  1872 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-05 11:08:02.052  1037  1872 D ActivityManager: setTaskToReturnTo : TaskRecord{37bdf7d #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 11:08:02.053  1037  1872 D ActivityManager: setTaskToReturnTo : TaskRecord{37bdf7d #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 11:08:02.055  1037  1872 D WindowStateEx: AppWindowTokenEx init.. 
07-05 11:08:02.056   335   343 E GBMv2   : DFP En is all cleared set to be enabled
07-05 11:08:02.125  1037  1872 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6554 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 11:08:02.127  6503  6503 D AndroidRuntime: Shutting down VM
07-05 11:08:02.133  6507  6507 I AppConfig: Total System Memory = 2995761152
07-05 11:08:02.140  6507  6507 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
07-05 11:08:02.179  1037  1584 I ActivityManager: Killing 5429:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
07-05 11:08:02.260  1982  1982 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
07-05 11:08:02.260  1982  1982 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
07-05 11:08:02.260  1037  2036 W libprocessgroup: failed to open /acct/uid_10085/pid_5429/cgroup.procs: No such file or directory
07-05 11:08:02.263  1982  1982 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
07-05 11:08:02.263  1927  4386 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-05 11:08:02.263  1927  4386 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a6e1c6e co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-05 11:08:02.264  1927  4005 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-05 11:08:02.265  1927  4005 D SplitWindowPolicy: topRunningActivity=ActivityInfo{189fcf0f co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-05 11:08:02.267  6554  6554 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-05 11:08:02.295  6336  6336 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
,07-05 11:08:02.299  6336  6336 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
07-05 11:08:02.347  1037  1053 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6573 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 11:08:02.389  6554  6554 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-05 11:08:02.406  6554  6554 I LibraryLoader: Loading: webviewchromium
07-05 11:08:02.409  6554  6554 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3481-3486)
07-05 11:08:02.410  6554  6554 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 11:08:02.428  6554  6554 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10eb024c}
,07-05 11:08:02.429  6554  6554 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 11:08:02.429  6554  6554 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 11:08:02.440  6554  6554 I BrowserStartupController: Initializing chromium process, renderers=0
,07-05 11:08:02.442  6554  6554 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:08:02.465  6554  6554 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-05 11:08:02.466  6554  6554 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-05 11:08:02.467  6554  6554 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,07-05 11:08:02.475   313  1371 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
07-05 11:08:02.481  6554  6554 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 11:08:02.481  6554  6554 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 11:08:02.481  6554  6554 I Adreno-EGL: Build Date: 12/12/14 금
07-05 11:08:02.481  6554  6554 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-05 11:08:02.481  6554  6554 I Adreno-EGL: Remote Branch: 
07-05 11:08:02.481  6554  6554 I Adreno-EGL: Local Patches: 
07-05 11:08:02.481  6554  6554 I Adreno-EGL: Reconstruct Branch: 
,07-05 11:08:02.495  1037  1110 D BluetoothManagerService: Message: 20
07-05 11:08:02.495  1037  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d6f476c:true
,07-05 11:08:02.529  6573  6573 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-05 11:08:02.571  6554  6606 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,07-05 11:08:02.573  6554  6554 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-05 11:08:02.593  6554  6554 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 11:08:02.594  6573  6573 D LgDataFeature: LgDataFeature() Constructor: none
,07-05 11:08:02.594  6573  6573 D LgDataFeature: LgDataFeature() Constructor Done, null
07-05 11:08:02.598  6554  6554 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 11:08:02.601  6554  6554 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-05 11:08:02.604  6554  6554 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-05 11:08:02.604  6554  6554 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,07-05 11:08:02.619  6554  6554 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-05 11:08:02.625  6554  6554 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:08:02.625  6554  6554 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:08:02.640  6573  6573 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-05 11:08:02.660  6554  6633 D OpenGLRenderer: Render dirty regions requested: true
07-05 11:08:02.660  6554  6633 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 11:08:02.661  6573  6573 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-05 11:08:02.662  6573  6573 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-05 11:08:02.678  1037  1100 W ActivityManager: Activity pause timeout for ActivityRecord{11846e72 u0 com.test.thalitest/.MainActivity t12}
07-05 11:08:02.680  6573  6573 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-05 11:08:02.680  6573  6573 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
07-05 11:08:02.682  6554  6633 D OpenGLRenderer: Enabling debug mode 0
,07-05 11:08:02.689  6554  6554 D Atlas   : Validating map...
07-05 11:08:02.693  1037  1584 D SplitWindow: check instance of lgWin Window{f040dd2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-05 11:08:02.708  1037  1926 I ActivityManager: Killing 6072:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,07-05 11:08:02.737  6554  6630 D LgDataFeature: LgDataFeature() Constructor: none
07-05 11:08:02.737  6554  6630 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-05 11:08:02.755  1037  1910 W libprocessgroup: failed to open /acct/uid_10097/pid_6072/cgroup.procs: No such file or directory
,07-05 11:08:02.765  5032  6638 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-05 11:08:02.811  1037  2018 V SIM_STK : Menu title from STK is T-Mobile
,07-05 11:08:02.819  1037  1871 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6641 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 11:08:02.826  2831  2850 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
07-05 11:08:02.827  2831  2850 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@232adbb0 on behalf of 6573
,07-05 11:08:02.835  6573  6573 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
07-05 11:08:02.842  1037  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +664ms (total +785ms)
,07-05 11:08:02.843  6554  6554 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@296a9d8b time:133920
07-05 11:08:02.843  1037  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{11846e72 u0 com.test.thalitest/.MainActivity t12} time:133920
07-05 11:08:02.849  6573  6573 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-05 11:08:02.938  1802  1802 I art     : Explicit concurrent mark sweep GC freed 31294(1977KB) AllocSpace objects, 12(192KB) LOS objects, 51% free, 29MB/61MB, paused 977us total 29.210ms
,07-05 11:08:02.955  5032  6638 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 189 ms] updated apps [took 189 ms] 
,07-05 11:08:02.959  6554  6554 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-05 11:08:02.959  6554  6554 I chromium: 
07-05 11:08:02.997  6554  6554 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 11:08:03.054  6554  6554 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-05 11:08:03.102  6641  6641 D DocsApplication: Installing DEX configuration.
,07-05 11:08:03.115  6641  6641 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,07-05 11:08:03.117  6641  6641 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{d937852 com.google.android.apps.docs}
07-05 11:08:03.126  6554  6671 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435030528
07-05 11:08:03.129  6641  6641 D TAG     : onCreate()
07-05 11:08:03.138  6554  6671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 11:08:03.138  6554  6671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 11:08:03.138  6554  6671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 11:08:03.138  6554  6671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 11:08:03.138  6554  6671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 11:08:03.138  6554  6671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4ffc5f added. We now have 1 listener(s)
07-05 11:08:03.140  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 11:08:03.143  6554  6671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-05 11:08:03.144  6554  6671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-05 11:08:03.145  6554  6671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 11:08:03.145  6554  6671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 11:08:03.151  6554  6671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@324a5b0a added. We now have 1 listener(s)
07-05 11:08:03.151  6554  6671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 11:08:03.152  6641  6641 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-05 11:08:03.156  1037  1528 D WifiService: New client listening to asynchronous messages
07-05 11:08:03.159  6554  6671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-05 11:08:03.161  6554  6671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-05 11:08:03.161  6554  6671 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-05 11:08:03.164  6554  6671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-05 11:08:03.165  1037  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 11:08:03.166  6554  6671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-05 11:08:03.176  6554  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 11:08:03.176  6554  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 11:08:03.176  6554  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 11:08:03.176  6554  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 11:08:03.176  6554  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 11:08:03.176  6554  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 11:08:03.176  6554  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 11:08:03.176  6554  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 11:08:03.176  6554  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 11:08:03.176  6554  6671 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 11:08:03.177  6554  6671 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 11:08:03.179  6554  6554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 11:08:03.181  6554  6554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 11:08:03.208  6554  6630 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-05 11:08:03.208  6554  6630 I chromium: 
07-05 11:08:03.256  6554  6554 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-05 11:08:03.715   335   364 E GBMv2   : DFP En is all cleared set to be enabled
07-05 11:08:03.715   335   364 E GBMv2   : Set value is all cleared set the max
07-05 11:08:03.715   335   364 I GBMv2   : DFP Enabled. Ignore VFP set
07-05 11:08:03.833  6554  6674 W jxcore-log: Initializing JXcore engine
07-05 11:08:03.833  6554  6674 W jxcore-log: JXcore engine is ready
07-05 11:08:03.854  6674  6674 W Thread-776: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8424]" dev="sockfs" ino=8424 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-05 11:08:03.854  6674  6674 W Thread-776: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-05 11:08:03.854  6674  6674 W Thread-776: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10414]" dev="sockfs" ino=10414 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-05 11:08:03.854  6674  6674 W Thread-776: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-05 11:08:03.854  6674  6674 W Thread-776: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30620]" dev="sockfs" ino=30620 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-05 11:08:03.880  6554  6674 W jxcore-log: Starting JXcore engine
07-05 11:08:03.953  6554  6674 W jxcore-log: Platform android
07-05 11:08:03.953  6554  6674 W jxcore-log: 
07-05 11:08:03.954  6554  6674 W jxcore-log: Process ARCH arm
07-05 11:08:03.954  6554  6674 W jxcore-log: 
07-05 11:08:03.956  1802  5162 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,07-05 11:08:04.056  1802  5162 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,07-05 11:08:04.100  1802  5162 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,07-05 11:08:04.154  6554  6674 I jxcore-log: JXcore Cordova bridge is ready!
07-05 11:08:04.154  6554  6674 I jxcore-log: 
07-05 11:08:04.154  6554  6674 W jxcore-log: JXcore engine is started
,07-05 11:08:04.212   329   408 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,07-05 11:08:04.218  3250  6686 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,07-05 11:08:04.309  6641  6641 D LgDataFeature: LgDataFeature() Constructor: none
07-05 11:08:04.309  6641  6641 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-05 11:08:04.508  6641  6641 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 11:08:04.543  1037  2018 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6699 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-05 11:08:04.565   348   348 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 26.588ms
,07-05 11:08:04.593   348   348 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 26.418ms
07-05 11:08:04.613   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 434us total 19.698ms
,07-05 11:08:04.694  1037  1944 I art     : Explicit concurrent mark sweep GC freed 27788(1335KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.656ms total 101.875ms
,07-05 11:08:04.737  6699  6699 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-05 11:08:04.746  6699  6699 I LockScreenSettings: New app installed broadcast received ..
07-05 11:08:04.748  6699  6699 I LockScreenSettings: Number of installed packages  1
07-05 11:08:04.823  1037  1910 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6728 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-05 11:08:04.824  1037  1910 I ActivityManager: Killing 5547:com.lge.bnr/1000 (adj 15): empty #17
,07-05 11:08:04.905  1037  1053 W libprocessgroup: failed to open /acct/uid_1000/pid_5547/cgroup.procs: No such file or directory
,07-05 11:08:04.941  6728  6728 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 11:08:05.296  1037  1944 V SIM_STK : Menu title from STK is T-Mobile
,07-05 11:08:05.369  1037  1910 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6761 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-05 11:08:05.466  6761  6761 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-05 11:08:05.466  6761  6761 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,07-05 11:08:05.522  1037  1944 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6779 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
07-05 11:08:05.524  1037  1944 I ActivityManager: Killing 5677:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,07-05 11:08:05.551  5645  5645 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,07-05 11:08:05.551  5645  5645 W System.err: android.os.DeadObjectException
07-05 11:08:05.552  5645  5645 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-05 11:08:05.552  5645  5645 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-05 11:08:05.552  5645  5645 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-05 11:08:05.552  5645  5645 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-05 11:08:05.552  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-05 11:08:05.552  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-05 11:08:05.552  5645  5645 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 11:08:05.552  5645  5645 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 11:08:05.552  5645  5645 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 11:08:05.552  5645  5645 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-05 11:08:05.552  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 11:08:05.552  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 11:08:05.552  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-05 11:08:05.552  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-05 11:08:05.553  5645  5645 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-05 11:08:05.553  5645  5645 W System.err: android.os.DeadObjectException
07-05 11:08:05.555  5645  5645 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-05 11:08:05.555  5645  5645 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-05 11:08:05.555  5645  5645 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-05 11:08:05.555  5645  5645 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-05 11:08:05.555  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-05 11:08:05.555  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-05 11:08:05.555  5645  5645 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 11:08:05.555  5645  5645 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 11:08:05.555  5645  5645 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 11:08:05.555  5645  5645 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-05 11:08:05.555  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 11:08:05.555  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 11:08:05.555  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-05 11:08:05.556  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-05 11:08:05.556  5645  5645 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-05 11:08:05.556  5645  5645 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-05 11:08:05.655  1037  1560 W libprocessgroup: failed to open /acct/uid_1000/pid_5677/cgroup.procs: No such file or directory
07-05 11:08:05.655  1037  1560 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-05 11:08:05.662  5645  5645 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-05 11:08:05.662  5645  5645 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-05 11:08:05.736  1037  1981 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6796 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-05 11:08:05.738  5645  5645 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-05 11:08:05.776  6779  6779 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-05 11:08:05.801  6796  6796 D UEI.SmartControl: Quickset Services start...
,07-05 11:08:05.803  1037  1981 I ActivityManager: Killing 6102:com.google.android.gm/u0a64 (adj 15): empty #17
07-05 11:08:05.804  6779  6779 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:08:05.805  6796  6796 I UEI.SmartControl: Manufacture = LGE
07-05 11:08:05.805  6796  6796 D UEI.SmartControl: Id = LGNevo
07-05 11:08:05.807  6796  6796 D UEI.SmartControl: File observer start...
07-05 11:08:05.808  6796  6796 E UEI.SmartControl: IR Port is disabled: false
07-05 11:08:05.808  6796  6796 D UEI.SmartControl: Starting file observer...
07-05 11:08:05.808  6796  6796 D UEI.SmartControl: Extracting JNI libs...
07-05 11:08:05.808  6796  6796 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-05 11:08:05.842  4907  6813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,07-05 11:08:05.895  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1021375534 [*alarm*], flags=0x0
,07-05 11:08:05.898  6336  6336 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-05 11:08:05.899  1037  1560 W libprocessgroup: failed to open /acct/uid_10064/pid_6102/cgroup.procs: No such file or directory
07-05 11:08:05.912  6796  6796 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-05 11:08:05.912  6796  6796 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-05 11:08:05.912  6796  6796 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-05 11:08:05.961  6796  6796 I UEI.SmartControl: --- Selecting new region: 6
,07-05 11:08:05.963  6796  6796 I UEI.SmartControl: Model = LG-D855
07-05 11:08:05.965  6796  6796 D UEI.SmartControl: QS Service created
07-05 11:08:05.980  6796  6796 I UEI.SmartControl: Service initServices...
,07-05 11:08:05.985  6796  6796 D UEI.SmartControl: QS start get config
07-05 11:08:06.035  6796  6796 D UEI.SmartControl: Loading JNI Libs...
,07-05 11:08:06.296  1588  1588 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,07-05 11:08:06.297  1588  1588 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:08:06.302  1588  1588 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
07-05 11:08:06.302  1588  1588 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:08:06.302  1037  1528 D WifiController: battery changed pluggedType: 2
07-05 11:08:06.303  4255  4423 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 11:08:06.304  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 11:08:06.304  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 11:08:06.304  1927  2107 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:08:06.304  1927  2107 D LEDHandler: Battery Level Remaining: 100%
07-05 11:08:06.304  1927  2107 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
07-05 11:08:06.305  6779  6779 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:08:06.306  1588  1588 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:08:06.308  6796  6796 I UEI.SmartControl: Supports setup maps: true
07-05 11:08:06.311  6796  6796 D UEI.SmartControl: QS start statue = true Error code = 0
07-05 11:08:06.311  6796  6796 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-05 11:08:06.311  6796  6796 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-05 11:08:06.311  6796  6796 I UEI.SmartControl: ### init IR Blaster...
,07-05 11:08:06.320  6796  6796 D serial_port: Configuring serial port
,07-05 11:08:06.327  6796  6796 E UEI.SmartControl: UEIBLaster setting for 616
07-05 11:08:06.327  6796  6796 I UEI.SmartControl: Setting serial record hearder size = 2
07-05 11:08:06.328  6796  6796 I UEI.SmartControl: configuring settings for MAXQ616
07-05 11:08:06.328  6796  6796 I UEI.SmartControl: Get version...
,07-05 11:08:06.344  6796  6825 D UEI.SmartControl: serial port data available: 21
,07-05 11:08:06.372  6796  6796 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-05 11:08:06.372  6796  6796 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-05 11:08:06.372  6796  6796 I UEI.SmartControl: QS saving settings...
,07-05 11:08:06.377  6796  6796 D UEI.SmartControl: IR Blaster version: 25672567
,07-05 11:08:06.395  6796  6825 D UEI.SmartControl: serial port data available: 4
,07-05 11:08:06.435  6796  6828 I UEI.SmartControl: Device manager: loading config....
07-05 11:08:06.437  6796  6828 D UEI.SmartControl: ----------- loading internal config...
,07-05 11:08:06.442  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-05 11:08:06.445  6796  6796 E UEI.SmartControl: Services init done
07-05 11:08:06.445  6796  6796 D UEI.SmartControl: QS Service init finished
07-05 11:08:06.448  6796  6796 D UEI.SmartControl: QS Service version name: 2.1.91
07-05 11:08:06.448  6796  6796 D UEI.SmartControl: QS Service version code: 201091
07-05 11:08:06.449  6796  6796 D UEI.SmartControl: Service requested: Control
07-05 11:08:06.455  6796  6828 E UEI.SmartControl: Loading SETTINGS...
,07-05 11:08:06.460  6796  6796 D UEI.SmartControl: Request IControl service: devices are loaded...
07-05 11:08:06.462  6796  6828 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-05 11:08:06.463  5645  5645 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-05 11:08:06.464  6796  6812 I UEI.SmartControl: ------ IControl API: 11
07-05 11:08:06.465  6796  6812 I UEI.SmartControl: Registering callback...
07-05 11:08:06.465  6796  6811 I UEI.SmartControl: ------ IControl API: 19
07-05 11:08:06.466  6796  6811 I UEI.SmartControl: Registering Services Ready callback...
07-05 11:08:06.467  1037  1981 I ActivityManager: Killing 5645:com.lge.qremote/u0a112 (adj 15): empty #17
07-05 11:08:06.491  6796  6827 I UEI.SmartControl: Notify AllClients services are ready: 0
07-05 11:08:06.491  6796  6827 D UEI.SmartControl: -----service ready thread exits
,07-05 11:08:06.523  1037  1560 W libprocessgroup: failed to open /acct/uid_10112/pid_5645/cgroup.procs: No such file or directory
07-05 11:08:06.523  6796  6796 D UEI.SmartControl: Internal service binding...
,07-05 11:08:08.435  6641  6641 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-05 11:08:08.439  1037  1762 I ActivityManager: Killing 5892:com.google.android.talk/u0a72 (adj 15): empty #17
07-05 11:08:08.474  1037  1052 W libprocessgroup: failed to open /acct/uid_10072/pid_5892/cgroup.procs: No such file or directory
,07-05 11:08:09.380  6641  6687 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 11:08:10.299  1037  1890 I ActivityManager: Killing 5590:com.android.calendar/u0a13 (adj 15): empty #17
,07-05 11:08:10.335  1037  1584 W libprocessgroup: failed to open /acct/uid_10013/pid_5590/cgroup.procs: No such file or directory
,07-05 11:08:10.836  2122  2122 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,07-05 11:08:10.840  2122  2122 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
07-05 11:08:11.434  6796  6829 D UEI.SmartControl: Internal timer expired: 1
07-05 11:08:11.434  6796  6829 D UEI.SmartControl: unbind internal service
,07-05 11:08:11.454  6796  6796 D UEI.SmartControl: Service.onUnbind: IControl
,07-05 11:08:11.457  6796  6796 D UEI.SmartControl: Service.onDestroy
07-05 11:08:11.458  6796  6796 D UEI.SmartControl: Lock is in USE false
07-05 11:08:11.458  6796  6796 D UEI.SmartControl: unbind internal service
07-05 11:08:11.458  6796  6796 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1ebf738
07-05 11:08:11.458  6796  6796 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-05 11:08:11.458  6796  6796 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-05 11:08:11.459  6796  6796 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-05 11:08:11.459  6796  6796 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-05 11:08:11.459  6796  6796 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-05 11:08:11.459  6796  6796 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-05 11:08:11.459  6796  6796 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-05 11:08:11.459  6796  6796 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-05 11:08:11.459  6796  6796 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:08:11.459  6796  6796 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 11:08:11.459  6796  6796 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-05 11:08:11.459  6796  6796 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 11:08:11.459  6796  6796 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 11:08:11.459  6796  6796 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-05 11:08:11.459  6796  6796 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-05 11:08:11.459  6796  6796 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1ebf738
07-05 11:08:11.461  6796  6796 D serial_port: close(fd = 25)
07-05 11:08:11.466  6796  6796 I UEI.SmartControl: Serial port is closed.
07-05 11:08:11.466  6796  6796 I UEI.SmartControl: Serial port is closed.
07-05 11:08:11.466  6796  6796 D UEI.SmartControl: Blaster closed
,07-05 11:08:11.472  6796  6796 D UEI.SmartControl: Shut down QS...
,07-05 11:08:11.472  6796  6796 D UEI.SmartControl: Stopping QS lib
07-05 11:08:11.472  6796  6796 D UEI.SmartControl: QS lib stop result = true
07-05 11:08:11.472  6796  6796 D UEI.SmartControl: Stopped QS lib
07-05 11:08:11.473  6796  6796 D UEI.SmartControl: Stopped file observer...
,07-05 11:08:11.473  6796  6796 D UEI.SmartControl: QS shutdown complete
,07-05 11:08:15.577  1037  1100 I ActivityManager: Waited long enough for: ServiceRecord{21ee4974 u0 com.google.android.gms/.wearable.service.WearableService}
,07-05 11:08:22.017  1037  1362 V AlarmManager: RTC_WAKEUP set : Alarm{32d8e08a type 0 when 1467709697689 com.android.vending} when 1467709697689
,07-05 11:08:22.111  1037  1871 V SIM_STK : Menu title from STK is T-Mobile
,07-05 11:08:22.291  6573  6573 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-05 11:08:57.283  1588  1588 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:08:57.284  1588  1588 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 11:08:57.294  1037  1528 D WifiController: battery changed pluggedType: 2
07-05 11:08:57.296  1927  2107 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:08:57.296  1927  2107 D LEDHandler: Battery Level Remaining: 100%
07-05 11:08:57.297  1927  2107 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
,07-05 11:08:57.300  1588  1588 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
07-05 11:08:57.300  1588  1588 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:08:57.302  1588  1588 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:08:57.304  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 11:08:57.304  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 11:08:57.306  4255  4423 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 11:08:57.311  6779  6779 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 11:09:00.037  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 11:09:00.037  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:09:00.037  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:09:00.038  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:09:00.050  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:09:00.051  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
,07-05 11:09:00.054  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:09:00.056  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:10:00.054  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:10:00.054  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:10:00.055  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-05 11:10:00.055  1588  1588 I [SystemUI]Clock: called onTimeUpdated(),
,07-05 11:10:00.072  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:10:00.072  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:10:00.076  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
,07-05 11:10:00.079  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:10:39.552  1037  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1021375534, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,07-05 11:10:39.563  1037  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2f7dd6fb type 2 when 253431 android} when 253431
07-05 11:10:39.565  1037  1362 V AlarmManager: RTC_WAKEUP set : Alarm{11373318 type 0 when 1467709822175 com.google.android.gms} when 1467709822175
07-05 11:10:39.608  2588  2588 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 11:10:39.637  1802  6853 I EventLogService: Aggregate from 1467709591594 (log), 1467708022069 (data)
,07-05 11:10:39.660  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1021375534 [*alarm*], flags=0x0
,07-05 11:11:00.057  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 11:11:00.058  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 11:11:00.058  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:11:00.058  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:11:00.072  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:11:00.072  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:11:00.074  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
,07-05 11:11:00.076  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:11:23.249  1037  3483 I LocationManagerService: remove 1bbb3b4d
07-05 11:11:23.250  1037  3483 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-05 11:11:23.250  1037  3483 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-05 11:11:23.262  1037  3483 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-05 11:11:23.264  1037  3483 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-05 11:11:23.265  1037  3483 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-05 11:11:41.348  1037  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1021375534, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,07-05 11:11:41.397  2588  2588 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 11:11:41.424  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1021375534 [*alarm*], flags=0x0
,07-05 11:12:00.053  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 11:12:00.053  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:12:00.053  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:12:00.054  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:12:00.067  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:12:00.067  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:12:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:12:00.071  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:12:57.928  1588  1588 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:12:57.928  1588  1588 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 11:12:57.950  1037  1528 D WifiController: battery changed pluggedType: 2
,07-05 11:12:57.956  1588  1588 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
07-05 11:12:57.956  1588  1588 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:12:57.958  1927  2107 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:12:57.958  1927  2107 D LEDHandler: Battery Level Remaining: 100%
07-05 11:12:57.958  1927  2107 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
07-05 11:12:57.958  1588  1588 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:12:57.961  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 11:12:57.961  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 11:12:57.962  4255  4423 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 11:12:57.966  6779  6779 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 11:13:00.054  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 11:13:00.054  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:13:00.054  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:13:00.055  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:13:00.067  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:13:00.067  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
,07-05 11:13:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:13:00.071  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:14:00.052  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:14:00.052  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:14:00.052  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-05 11:14:00.062  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
07-05 11:14:00.069  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:14:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:14:00.071  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:14:00.076  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:15:00.057  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 11:15:00.057  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 11:15:00.057  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:15:00.058  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:15:00.071  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:15:00.072  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:15:00.075  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:15:00.080  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:15:01.225  1037  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1021375534, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,07-05 11:15:01.294  1037  1100 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6881 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-05 11:15:01.333  2588  2588 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 11:15:01.461  6881  6881 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-05 11:15:01.465  6881  6881 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@cae71d9
07-05 11:15:01.466  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1021375534 [*alarm*], flags=0x0
07-05 11:15:01.466  1037  1999 I ActivityManager: Killing 6161:com.android.providers.calendar/u0a14 (adj 15): empty #17
07-05 11:15:01.549  1037  1584 W libprocessgroup: failed to open /acct/uid_10014/pid_6161/cgroup.procs: No such file or directory
,07-05 11:16:00.056  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 11:16:00.056  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 11:16:00.056  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:16:00.057  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:16:00.071  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:16:00.071  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:16:00.075  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:16:00.075  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:16:41.355  1037  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1021375534, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,07-05 11:16:41.406  2588  2588 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 11:16:41.431  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1021375534 [*alarm*], flags=0x0
,07-05 11:17:00.052  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 11:17:00.053  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 11:17:00.058  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:17:00.060  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
07-05 11:17:00.067  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:17:00.067  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:17:00.072  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
,07-05 11:17:00.076  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:18:00.110  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:18:00.110  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:18:00.110  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:18:00.111  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:18:00.124  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:18:00.124  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:18:00.127  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:18:00.129  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:18:09.387  1037  1584 I ActivityManager: Killing 2122:com.lge.music/u0a34 (adj 15): empty #17
,07-05 11:18:09.412   313  2121 V AudioFlinger: 2122 died, releasing its sessions
07-05 11:18:09.412   313  2121 V AudioFlinger:  pid 1837 @ 0
07-05 11:18:09.412   313  2121 V AudioFlinger:  pid 3309 @ 1
07-05 11:18:09.412   313  2121 V AudioFlinger:  pid 3309 @ 2
,07-05 11:18:09.449  1037  2018 W libprocessgroup: failed to open /acct/uid_10034/pid_2122/cgroup.procs: No such file or directory
,07-05 11:19:00.053  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 11:19:00.053  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:19:00.054  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:19:00.054  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:19:00.067  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:19:00.067  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:19:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:19:00.071  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:20:00.054  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:20:00.054  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:20:00.054  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:20:00.055  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:20:00.068  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:20:00.068  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:20:00.071  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:20:00.073  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:21:00.052  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:21:00.053  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 11:21:00.060  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:21:00.062  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
07-05 11:21:00.068  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:21:00.068  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:21:00.071  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:21:00.075  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:21:33.836  1037  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1021375534, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,07-05 11:21:33.848  1037  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1d6c7b56 type 2 when 929144 com.google.android.gms} when 929144
,07-05 11:21:33.886  2588  2588 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 11:21:33.917  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1021375534 [*alarm*], flags=0x0
,07-05 11:21:34.019  2206  2930 D GCM     : Message class com.google.e.a.a.h
,07-05 11:21:37.535  1037  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{f48e7d7 type 2 when 948580 com.android.bluetooth} when 948580
,07-05 11:21:37.554  4255  4489 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-05 11:21:37.555  4255  4489 W bt-smp  : Plain text(LSB ~ MSB) = 4e 82 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-05 11:21:37.555  4255  4489 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 ba 0b 75 fd ea 23 bb 57 85 2f 23 d5 fb 37 98 
07-05 11:21:37.555  4255  4489 W bt-btm  : Stopping oneshot timer
,07-05 11:22:00.058  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 11:22:00.059  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:22:00.059  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:22:00.059  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:22:00.072  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:22:00.072  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:22:00.076  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
,07-05 11:22:00.083  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:23:00.057  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:23:00.058  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:23:00.058  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:23:00.058  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:23:00.071  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:23:00.071  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:23:00.074  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:23:00.076  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:24:00.089  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:24:00.089  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:24:00.089  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:24:00.089  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:24:00.095  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:24:00.095  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:24:00.096  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:24:00.097  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:25:00.093  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:25:00.094  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:25:00.094  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:25:00.094  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:25:00.107  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:25:00.108  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:25:00.110  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:25:00.112  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:26:00.051  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:26:00.052  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:26:00.052  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:26:00.052  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:26:00.066  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:26:00.066  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
,07-05 11:26:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:26:00.071  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:26:08.876  1037  1099 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 11:27:00.053  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 11:27:00.053  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:27:00.054  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:27:00.054  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:27:00.067  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:27:00.067  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:27:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:27:00.071  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:28:00.052  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:28:00.053  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:28:00.053  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:28:00.053  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:28:00.067  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:28:00.067  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:28:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:28:00.071  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:29:00.053  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:29:00.053  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:29:00.054  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:29:00.054  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:29:00.068  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:29:00.068  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:29:00.070  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:29:00.072  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:30:00.054  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:30:00.054  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:30:00.054  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:30:00.055  1588  1588 I [SystemUI]Clock: called onTimeUpdated(),
,07-05 11:30:00.068  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,07-05 11:30:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:30:00.071  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:30:00.073  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:30:01.465  1037  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1021375534, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,07-05 11:30:01.491  6881  6881 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-05 11:30:01.496  6881  6881 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@cae71d9
07-05 11:30:01.519  2588  2588 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 11:30:01.546  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1021375534 [*alarm*], flags=0x0
,07-05 11:31:00.054  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 11:31:00.054  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:31:00.054  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 11:31:00.055  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
