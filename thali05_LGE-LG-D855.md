#### Test 6810213040493cb_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-28 12:30:38.772  5743  5743 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
07-28 12:30:38.839  5743  5743 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:30:38.839  5743  5743 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:30:38.881  5743  5743 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
07-28 12:30:38.897  5743  5743 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-28 12:30:38.898  5743  5743 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-28 12:30:38.914  5743  5743 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-28 12:30:38.915  5743  5743 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
07-28 12:30:38.924  1036  1936 I ActivityManager: Killing 5259:com.lge.clock/u0a10 (adj 15): empty #17
07-28 12:30:38.956  1036  1560 W libprocessgroup: failed to open /acct/uid_10010/pid_5259/cgroup.procs: No such file or directory
07-28 12:30:38.975  3288  3304 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
07-28 12:30:38.979  3288  3304 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2f50d3d2 on behalf of 5743
07-28 12:30:38.981  4509  5786 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-28 12:30:39.016  1036  2021 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5787 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 12:30:39.051  5743  5743 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
07-28 12:30:39.075  5743  5743 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
07-28 12:30:39.267  5787  5787 D DocsApplication: Installing DEX configuration.
07-28 12:30:39.294  5787  5787 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-28 12:30:39.297  5787  5787 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{15d7be41 com.google.android.apps.docs}
07-28 12:30:39.311  5787  5787 D TAG     : onCreate()
07-28 12:30:39.328  5787  5787 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-28 12:30:39.435  1036  1993 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:30:39.508  4509  5786 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 525 ms] updated apps [took 525 ms] 
,07-28 12:30:40.064  5825  5825 D AndroidRuntime: 
07-28 12:30:40.064  5825  5825 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 12:30:40.069  5825  5825 D AndroidRuntime: CheckJNI is OFF
07-28 12:30:40.200  5825  5825 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-28 12:30:40.209  1036  2021 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-28 12:30:40.217  1927  1943 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-28 12:30:40.219  1036  2021 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-28 12:30:40.221  1036  2021 D ActivityManager: setTaskToReturnTo : TaskRecord{2ff7eac1 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-28 12:30:40.221  1036  2021 D ActivityManager: setTaskToReturnTo : TaskRecord{2ff7eac1 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-28 12:30:40.222  1036  2021 D WindowStateEx: AppWindowTokenEx init.. 
07-28 12:30:40.223   335   349 E GBMv2   : DFP En is all cleared set to be enabled
07-28 12:30:40.254  1036  2021 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5840 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-28 12:30:40.256  5825  5825 D AndroidRuntime: Shutting down VM
07-28 12:30:40.292  1927  3882 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-28 12:30:40.292  1927  3882 D SplitWindowPolicy: topRunningActivity=ActivityInfo{25b80bb7 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-28 12:30:40.293  1927  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-28 12:30:40.293  1927  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2978ef24 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-28 12:30:40.326  5840  5840 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-28 12:30:40.440  5840  5840 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-28 12:30:40.449  5840  5840 I LibraryLoader: Loading: webviewchromium
07-28 12:30:40.452  5840  5840 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1840-1844)
07-28 12:30:40.452  5840  5840 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:30:40.481  5840  5840 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {257b40c3}
07-28 12:30:40.483  5840  5840 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:30:40.483  5840  5840 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-28 12:30:40.495  5840  5840 I BrowserStartupController: Initializing chromium process, renderers=0
07-28 12:30:40.496  5840  5840 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:30:40.502  5840  5870 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
07-28 12:30:40.506  5840  5840 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-28 12:30:40.507  5840  5840 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-28 12:30:40.508  5840  5840 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-28 12:30:40.508  1803  4629 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
07-28 12:30:40.512   314  1370 V AudioPolicyService: registerClient() client 0xb0410980, uid 10118
07-28 12:30:40.516  1036  1108 D BluetoothManagerService: Message: 20
07-28 12:30:40.516  1036  1108 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3be60943:true
07-28 12:30:40.527  5840  5840 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:30:40.527  5840  5840 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:30:40.527  5840  5840 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:30:40.527  5840  5840 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:30:40.527  5840  5840 I Adreno-EGL: Remote Branch: 
07-28 12:30:40.527  5840  5840 I Adreno-EGL: Local Patches: 
07-28 12:30:40.527  5840  5840 I Adreno-EGL: Reconstruct Branch: 
07-28 12:30:40.546  1803  4629 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-28 12:30:40.574  5840  5880 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-28 12:30:40.576  5840  5840 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-28 12:30:40.586  5840  5840 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:30:40.589  5840  5840 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-28 12:30:40.591  5840  5840 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-28 12:30:40.593  5840  5840 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-28 12:30:40.593  5840  5840 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-28 12:30:40.596  1803  4629 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
07-28 12:30:40.603  5840  5840 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-28 12:30:40.608  5840  5840 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:30:40.608  5840  5840 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:30:40.654  5840  5893 D OpenGLRenderer: Render dirty regions requested: true
07-28 12:30:40.655  5840  5893 I OpenGLRenderer: Initialized EGL, version 1.4
07-28 12:30:40.674  5840  5893 D OpenGLRenderer: Enabling debug mode 0
07-28 12:30:40.685  5840  5840 D Atlas   : Validating map...
07-28 12:30:40.689  1036  1891 D SplitWindow: check instance of lgWin Window{264a2425 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-28 12:30:40.732  5840  5891 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:30:40.732  5840  5891 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:30:40.751  5787  5787 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:30:40.752  5787  5787 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:30:40.852  1036  1109 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +562ms (total +629ms)
07-28 12:30:40.853  5840  5840 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@380e7a6e time:122245
07-28 12:30:40.854  1036  1109 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{85bf266 u0 com.test.thalitest/.MainActivity t40} time:122247
07-28 12:30:40.905  5787  5787 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-28 12:30:40.939  1036  1890 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5915 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
07-28 12:30:40.956   339   339 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 352us total 17.424ms
07-28 12:30:40.971  5840  5840 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-28 12:30:40.971  5840  5840 I chromium: 
07-28 12:30:40.971   339   339 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 328us total 15.015ms
07-28 12:30:40.985   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 278us total 13.633ms
07-28 12:30:41.001  5915  5915 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
07-28 12:30:41.004  5840  5840 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-28 12:30:41.009  5915  5915 I LockScreenSettings: New app installed broadcast received ..
07-28 12:30:41.011  5915  5915 I LockScreenSettings: Number of installed packages  1
07-28 12:30:41.044  5840  5891 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-28 12:30:41.044  5840  5891 I chromium: 
07-28 12:30:41.048  1036  1051 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5937 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-28 12:30:41.049  1036  1051 I ActivityManager: Killing 5006:com.lge.bnr/1000 (adj 15): empty #17
07-28 12:30:41.118  1036  2021 W libprocessgroup: failed to open /acct/uid_1000/pid_5006/cgroup.procs: No such file or directory
07-28 12:30:41.123  5840  5955 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435030528
07-28 12:30:41.137  5840  5955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-28 12:30:41.137  5840  5955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-28 12:30:41.137  5840  5955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-28 12:30:41.137  5840  5955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-28 12:30:41.137  5840  5955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-28 12:30:41.137  5840  5955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f50d3d2 added. We now have 1 listener(s)
07-28 12:30:41.143  1036  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:30:41.146  5840  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-28 12:30:41.147  5840  5955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:30:41.149  5840  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:30:41.149  5840  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:30:41.155  5937  5937 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-28 12:30:41.158  5840  5955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24422359 added. We now have 1 listener(s)
07-28 12:30:41.159  5840  5955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:30:41.168  1036  1528 D WifiService: New client listening to asynchronous messages
07-28 12:30:41.173  5840  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:30:41.173  5840  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
07-28 12:30:41.174  5840  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
07-28 12:30:41.174  5840  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
07-28 12:30:41.175  5840  5955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
07-28 12:30:41.178  5840  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:41.180  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:30:41.182  5840  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-28 12:30:41.192  5840  5955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 12:30:41.192  5840  5955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:41.192  5840  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:41.192  5840  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:41.192  5840  5955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:41.192  5840  5955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:41.192  5840  5955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:41.192  5840  5955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:41.192  5840  5955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:41.192  5840  5955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-28 12:30:41.192  5840  5955 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:30:41.194  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:41.195  5840  5955 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 12:30:41.222  5840  5840 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-28 12:30:41.522   335   351 E GBMv2   : DFP En is all cleared set to be enabled
07-28 12:30:41.522   335   351 E GBMv2   : Set value is all cleared set the max
07-28 12:30:41.522   335   351 I GBMv2   : DFP Enabled. Ignore VFP set
,07-28 12:30:41.700  1036  1578 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:30:41.746  1036  1936 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5983 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:30:41.884  1036  2015 I art     : Explicit concurrent mark sweep GC freed 23851(1160KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.301ms total 84.526ms
,07-28 12:30:41.900  5983  5983 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
,07-28 12:30:41.900  5983  5983 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
07-28 12:30:41.903  5840  5958 W jxcore-log: Initializing JXcore engine
07-28 12:30:41.903  5840  5958 W jxcore-log: JXcore engine is ready
,07-28 12:30:41.928  1036  1936 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6006 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-28 12:30:41.929  1036  1936 I ActivityManager: Killing 5330:com.google.android.gm/u0a64 (adj 15): empty #17
07-28 12:30:41.962  5958  5958 W Thread-677: type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[8318]" dev="sockfs" ino=8318 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-28 12:30:41.962  5958  5958 W Thread-677: type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-28 12:30:41.962  5958  5958 W Thread-677: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[8494]" dev="sockfs" ino=8494 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-28 12:30:41.962  5958  5958 W Thread-677: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-28 12:30:41.962  5958  5958 W Thread-677: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[27258]" dev="sockfs" ino=27258 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-28 12:30:41.996  5840  5958 W jxcore-log: Starting JXcore engine
,07-28 12:30:42.032  1036  2015 W libprocessgroup: failed to open /acct/uid_10064/pid_5330/cgroup.procs: No such file or directory
07-28 12:30:42.097  6006  6006 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,07-28 12:30:42.124  6006  6006 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-28 12:30:42.125  1036  1890 I ActivityManager: Killing 5374:com.google.android.talk/u0a72 (adj 15): empty #17
07-28 12:30:42.147  5840  5958 W jxcore-log: Platform android
07-28 12:30:42.147  5840  5958 W jxcore-log: 
07-28 12:30:42.147  5840  5958 W jxcore-log: Process ARCH arm
07-28 12:30:42.147  5840  5958 W jxcore-log: 
,07-28 12:30:42.261  1036  2015 W libprocessgroup: failed to open /acct/uid_10072/pid_5374/cgroup.procs: No such file or directory
,07-28 12:30:42.351  5840  5958 I jxcore-log: JXcore Cordova bridge is ready!
07-28 12:30:42.351  5840  5958 I jxcore-log: 
07-28 12:30:42.351  5840  5958 W jxcore-log: JXcore engine is started
,07-28 12:30:42.361  5840  5955 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-28 12:30:42.364  5840  5840 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-28 12:30:44.854  5787  5787 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-28 12:30:44.862  1036  2021 I ActivityManager: Killing 5133:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-28 12:30:44.882  5104  5104 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-28 12:30:44.882  5104  5104 W System.err: android.os.DeadObjectException
07-28 12:30:44.882  5104  5104 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:30:44.882  5104  5104 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:30:44.882  5104  5104 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-28 12:30:44.882  5104  5104 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-28 12:30:44.882  5104  5104 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:30:44.882  5104  5104 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:30:44.882  5104  5104 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:30:44.882  5104  5104 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:30:44.883  5104  5104 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:30:44.883  5104  5104 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:30:44.883  5104  5104 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:30:44.883  5104  5104 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:30:44.883  5104  5104 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:30:44.883  5104  5104 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:30:44.883  5104  5104 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,07-28 12:30:44.883  5104  5104 W System.err: android.os.DeadObjectException
,07-28 12:30:44.883  5104  5104 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,07-28 12:30:44.883  5104  5104 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,07-28 12:30:44.883  5104  5104 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-28 12:30:44.883  5104  5104 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-28 12:30:44.884  5104  5104 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:30:44.884  5104  5104 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:30:44.884  5104  5104 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,07-28 12:30:44.884  5104  5104 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:30:44.884  5104  5104 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:30:44.884  5104  5104 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:30:44.884  5104  5104 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:30:44.884  5104  5104 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:30:44.884  5104  5104 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:30:44.884  5104  5104 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:30:44.884  5104  5104 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-28 12:30:44.884  5104  5104 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,07-28 12:30:45.089  1036  1960 W libprocessgroup: failed to open /acct/uid_1000/pid_5133/cgroup.procs: No such file or directory
07-28 12:30:45.090  1036  1960 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-28 12:30:45.103  5104  5104 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-28 12:30:45.104  5104  5104 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:30:45.134  1036  1891 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6032 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:30:45.135  5104  5104 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-28 12:30:45.200  6032  6032 D UEI.SmartControl: Quickset Services start...
07-28 12:30:45.202  6032  6032 I UEI.SmartControl: Manufacture = LGE
07-28 12:30:45.202  6032  6032 D UEI.SmartControl: Id = LGNevo
07-28 12:30:45.203  6032  6032 D UEI.SmartControl: File observer start...
07-28 12:30:45.204  6032  6032 E UEI.SmartControl: IR Port is disabled: false
07-28 12:30:45.204  6032  6032 D UEI.SmartControl: Starting file observer...
07-28 12:30:45.204  6032  6032 D UEI.SmartControl: Extracting JNI libs...
07-28 12:30:45.205  6032  6032 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,07-28 12:30:45.276  6032  6032 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-28 12:30:45.276  6032  6032 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-28 12:30:45.276  6032  6032 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-28 12:30:45.324  6032  6032 I UEI.SmartControl: --- Selecting new region: 6
07-28 12:30:45.326  6032  6032 I UEI.SmartControl: Model = LG-D855
07-28 12:30:45.327  6032  6032 D UEI.SmartControl: QS Service created
,07-28 12:30:45.359  6032  6032 I UEI.SmartControl: Service initServices...
07-28 12:30:45.362  6032  6032 D UEI.SmartControl: QS start get config
,07-28 12:30:45.426  6032  6032 D UEI.SmartControl: Loading JNI Libs...
,07-28 12:30:45.714  6032  6032 I UEI.SmartControl: Supports setup maps: true
,07-28 12:30:45.717  6032  6032 D UEI.SmartControl: QS start statue = true Error code = 0
,07-28 12:30:45.718  6032  6032 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:30:45.718  6032  6032 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:30:45.718  6032  6032 I UEI.SmartControl: ### init IR Blaster...
07-28 12:30:45.722  6032  6032 D serial_port: Configuring serial port
07-28 12:30:45.725  6032  6032 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:30:45.725  6032  6032 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:30:45.725  6032  6032 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:30:45.725  6032  6032 I UEI.SmartControl: Get version...
,07-28 12:30:45.741  6032  6065 D UEI.SmartControl: serial port data available: 21
,07-28 12:30:45.770  6032  6032 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:30:45.770  6032  6032 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:30:45.771  6032  6032 I UEI.SmartControl: QS saving settings...
07-28 12:30:45.772  6032  6032 D UEI.SmartControl: IR Blaster version: 25672567
,07-28 12:30:45.789  6032  6065 D UEI.SmartControl: serial port data available: 4
,07-28 12:30:45.823  6032  6032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-28 12:30:45.826  5787  5899 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
07-28 12:30:45.828  6032  6070 I UEI.SmartControl: Device manager: loading config....
07-28 12:30:45.831  6032  6032 E UEI.SmartControl: Services init done
07-28 12:30:45.831  6032  6032 D UEI.SmartControl: QS Service init finished
07-28 12:30:45.833  6032  6032 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:30:45.833  6032  6032 D UEI.SmartControl: QS Service version code: 201091
07-28 12:30:45.834  6032  6070 D UEI.SmartControl: ----------- loading internal config...
07-28 12:30:45.834  6032  6032 D UEI.SmartControl: Service requested: Control
07-28 12:30:45.844  6032  6070 E UEI.SmartControl: Loading SETTINGS...
,07-28 12:30:45.847  6032  6032 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 12:30:45.849  5104  5104 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-28 12:30:45.849  6032  6047 I UEI.SmartControl: ------ IControl API: 11
07-28 12:30:45.850  1036  2033 I ActivityManager: Killing 5104:com.lge.qremote/u0a112 (adj 15): empty #17
07-28 12:30:45.850  6032  6047 I UEI.SmartControl: Registering callback...
07-28 12:30:45.856  6032  6070 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-28 12:30:45.874  6032  6069 I UEI.SmartControl: Notify AllClients services are ready: 0
07-28 12:30:45.875  6032  6069 D UEI.SmartControl: -----service ready thread exits
,07-28 12:30:46.014  1036  1924 W libprocessgroup: failed to open /acct/uid_10112/pid_5104/cgroup.procs: No such file or directory
07-28 12:30:46.015  6032  6032 D UEI.SmartControl: Internal service binding...
,07-28 12:30:46.687  1036  1763 I ActivityManager: Killing 5046:com.android.calendar/u0a13 (adj 15): empty #17
,07-28 12:30:46.775  1036  1560 W libprocessgroup: failed to open /acct/uid_10013/pid_5046/cgroup.procs: No such file or directory
,07-28 12:30:50.814  6032  6066 D serial_port: close(fd = 25)
,07-28 12:30:50.822  6032  6071 D UEI.SmartControl: Internal timer expired: 1
07-28 12:30:50.822  6032  6071 D UEI.SmartControl: unbind internal service
07-28 12:30:50.838  6032  6032 D UEI.SmartControl: Service.onUnbind: IControl
,07-28 12:30:50.842  6032  6032 D UEI.SmartControl: Service.onDestroy
,07-28 12:30:50.842  6032  6032 D UEI.SmartControl: Lock is in USE false
,07-28 12:30:50.842  6032  6032 D UEI.SmartControl: unbind internal service
,07-28 12:30:50.842  6032  6032 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@747261f
07-28 12:30:50.843  6032  6032 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-28 12:30:50.843  6032  6032 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-28 12:30:50.843  6032  6032 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
,07-28 12:30:50.843  6032  6032 W System.err: ,	at com.uei.control.Service.c(Unknown Source)
,07-28 12:30:50.843  6032  6032 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-28 12:30:50.844  6032  6032 W System.err: ,	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-28 12:30:50.844  6032  6032 W System.err: ,	,at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-28 12:30:50.844  6032  6032 W System.err: 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
,07-28 12:30:50.844  6032  6032 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-28 12:30:50.844  6032  6032 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,07-28 12:30:50.844  6032  6032 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,07-28 12:30:50.844  6032  6032 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,07-28 12:30:50.844  6032  6032 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:30:50.844  6032  6032 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:30:50.844  6032  6032 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:30:50.844  6032  6032 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@747261f
07-28 12:30:50.847  6032  6066 I UEI.SmartControl: Serial port is closed.
07-28 12:30:50.848  6032  6032 I UEI.SmartControl: Serial port is closed.
07-28 12:30:50.848  6032  6032 I UEI.SmartControl: Serial port is closed.
07-28 12:30:50.848  6032  6032 D UEI.SmartControl: Blaster closed
07-28 12:30:50.848  6032  6032 D UEI.SmartControl: Shut down QS...
07-28 12:30:50.849  6032  6032 D UEI.SmartControl: Stopping QS lib
07-28 12:30:50.849  6032  6032 D UEI.SmartControl: QS lib stop result = true
07-28 12:30:50.849  6032  6032 D UEI.SmartControl: Stopped QS lib
07-28 12:30:50.849  6032  6032 D UEI.SmartControl: Stopped file observer...
07-28 12:30:50.849  6032  6032 D UEI.SmartControl: QS shutdown complete
07-28 12:30:51.919  1036  1099 I ActivityManager: Waited long enough for: ServiceRecord{2ae8a81e u0 com.google.android.gms/.wearable.service.WearableService}
,07-28 12:30:53.253  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-28 12:30:53.253  5840  5958 I jxcore-log: 
,07-28 12:30:53.256  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-28 12:30:53.256  5840  5958 I jxcore-log: 
,07-28 12:30:53.261  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:53.261  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.261  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.261  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.261  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:53.261  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.261  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.261  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:30:53.263  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:53.266  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-28 12:30:53.266  5840  5958 I jxcore-log: 
,07-28 12:30:53.268  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-28 12:30:53.268  5840  5958 I jxcore-log: 
07-28 12:30:53.617  5840  5958 D ExecuteNativeTests: Running unit tests
,07-28 12:30:53.701  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
07-28 12:30:53.701  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e added. We now have 2 listener(s)
,07-28 12:30:53.701  1036  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:30:53.703  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,07-28 12:30:53.703  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:30:53.703  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:30:53.704  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:30:53.704  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff added. We now have 2 listener(s)
07-28 12:30:53.704  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:30:53.704  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:30:53.706  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:30:53.708  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:53.708  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.708  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
,07-28 12:30:53.708  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.708  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:53.708  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.708  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.708  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:30:53.709  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:30:53.709  5840  5958 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:30:53.710  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:53.712  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
07-28 12:30:53.713  5840  5958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:30:53.713  5840  5958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
07-28 12:30:53.714  5840  5958 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-28 12:30:53.715  5840  5958 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:30:53.715  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:30:53.715  5840  5958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-28 12:30:53.715  5840  5958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:30:53.716  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.716  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.716  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
07-28 12:30:53.717  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:30:53.717  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.717  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:30:53.717  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
07-28 12:30:53.718  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e removed from the list
07-28 12:30:53.718  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.718  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff removed from the list
07-28 12:30:53.718  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:30:53.718  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.719  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:30:53.719  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.719  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:30:53.719  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.719  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:30:53.720  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.721  5840  5958 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-28 12:30:53.722  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.722  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.722  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
07-28 12:30:53.722  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.722  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.722  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.722  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.722  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.722  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
,07-28 12:30:53.722  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.722  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.722  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.722  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.722  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.724  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:30:53.724  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.724  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.724  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
,07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410],
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:30:53.730  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:30:53.731  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:30:53.731  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:30:53.731  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.731  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.732  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.732  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.732  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:30:53.732  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.732  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.732  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.732  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.732  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.732  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
07-28 12:30:53.732  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.732  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.733  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.733  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.733  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:30:53.733  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.733  5840  5958 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:30:53.734  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.736  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:53.736  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.736  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,07-28 12:30:53.736  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.736  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:53.736  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.736  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.736  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:53.736  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:53.736  5840  5958 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:30:53.737  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:53.738  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
07-28 12:30:53.738  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:30:53.738  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:30:53.738  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.738  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:30:53.740  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:30:53.741  1036  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:30:53.744  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:30:53.747  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:30:53.749  5840  5958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,07-28 12:30:53.750  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
07-28 12:30:53.750  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.751  5840  5958 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:30:53.751  5840  5958 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:30:53.753  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.753  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.753  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.754  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
07-28 12:30:53.754  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.754  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.754  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.754  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.754  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.754  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.754  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.754  5840  5958 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,07-28 12:30:53.755  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.757  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:53.757  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.757  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.757  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.757  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:53.757  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.757  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.757  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:53.758  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:53.758  5840  5958 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:30:53.758  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:53.759  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:30:53.759  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:30:53.759  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:30:53.759  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.759  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:30:53.761  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:30:53.761  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:30:53.762  5840  5958 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:30:53.762  5840  5958 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:30:53.763  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.763  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.763  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.763  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.764  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.764  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.764  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.764  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.764  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.764  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.764  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.764  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.764  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.764  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.765  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.765  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.766  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.766  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.766  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.766  5840  5958 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:30:53.767  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.769  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:53.769  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.769  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.769  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.769  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:53.769  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.769  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.769  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:53.770  5840  5958 D io.jxc,ore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:53.770  5840  5958 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:30:53.770  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:30:53.770  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:30:53.770  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:30:53.770  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.770  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:30:53.770  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:53.772  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:30:53.773  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.773  5840  5958 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:30:53.774  5840  5958 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:30:53.774  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.774  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.774  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.774  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.774  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.774  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.775  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.775  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.775  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.775  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.775  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.775  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.775  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.775  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.775  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.775  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.776  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.776  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.776  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.776  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.776  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.776  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.777  5840  5958 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-28 12:30:53.777  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.777  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.777  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.777  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.777  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.777  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.777  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.777  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.777  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.777  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.777  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.777  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.777  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.777  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.778  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.778  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.778  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.779  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.779  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.779  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.779  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:30:53.779  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.779  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.779  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.780  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.780  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.780  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.780  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.780  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.780  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.780  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.780  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.780  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.780  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.780  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.781  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.781  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.781  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.781  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.781  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.781  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.781  5840  5958 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-28 12:30:53.782  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.782  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.782  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.782  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.782  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.782  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.782  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.782  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.782  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.782  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.782  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.782  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.782  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.782  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.783  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.783  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.783  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.783  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.783  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.783  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.784  5840  5958 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-28 12:30:53.784  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.784  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.784  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.784  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.784  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.784  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.784  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.784  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.784  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.784  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.784  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.784  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.784  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.784  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.785  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.785  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.785  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.785  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.785  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.786  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.786  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:30:53.787  5840  5958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:30:53.787  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:30:53.788  5840  5958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:30:53.788  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:30:53.788  5840  5958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:30:53.788  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.788  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.788  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.788  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.788  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.788  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.788  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.788  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.788  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.788  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.788  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.788  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.788  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.788  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.789  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.789  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.789  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.789  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.789  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.790  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.790  5840  5958 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:30:53.791  5840  5958 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:30:53.791  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:30:53.794  5840  5958 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:30:53.794  5840  5958 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-28 12:30:53.794  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:30:53.794  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,07-28 12:30:53.794  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:30:53.795  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:30:53.795  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:30:53.795  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:30:53.795  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:30:53.795  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:30:53.795  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:30:53.795  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:30:53.795  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:30:53.795  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:30:53.795  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:30:53.795  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:30:53.796  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:30:53.796  5840  5958 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-28 12:30:53.797  5840  5958 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:30:53.797  5840  5958 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-28 12:30:53.797  5840  5958 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:30:53.797  5840  5958 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:30:53.797  5840  5958 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-28 12:30:53.797  5840  5958 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:30:53.797  5840  5958 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:30:53.797  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-28 12:30:53.799  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-28 12:30:53.799  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-28 12:30:53.799  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-28 12:30:53.800  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-28 12:30:53.800  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-28 12:30:53.800  5840  5958 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-28 12:30:53.800  5840  5958 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:30:53.800  5840  5958 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-28 12:30:53.800  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.800  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.800  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.802  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.802  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.802  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.802  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-28 12:30:53.807  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.807  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.807  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.807  5840  6081 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 741)
07-28 12:30:53.807  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.807  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.807  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.807  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.807  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.812  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.812  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.814  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.814  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.814  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.814  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.817  5840  6082 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 741
07-28 12:30:53.817  5840  6082 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 741)
07-28 12:30:53.817  5840  6082 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 741)
07-28 12:30:53.818  5840  5958 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-28 12:30:53.818  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.818  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.818  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.818  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.819  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.819  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.819  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.819  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.819  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.819  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.819  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.819  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.819  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.819  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.819  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.819  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.820  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.820  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.820  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.820  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.820  5840  5958 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-28 12:30:53.821  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.821  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.821  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.821  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.821  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.821  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.821  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.821  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.821  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.821  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.821  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.821  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.821  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.821  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.822  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.822  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.822  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.822  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.822  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.822  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.823  5840  5958 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-28 12:30:53.823  5840  5958 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-28 12:30:53.823  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:30:53.823  5840  5958 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-28 12:30:53.823  5840  5958 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:30:53.823  5840  5958 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-28 12:30:53.823  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:30:53.823  5840  5958 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-28 12:30:53.824  5840  5958 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:30:53.824  5840  5958 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:30:53.824  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:30:53.824  5840  5958 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-28 12:30:53.824  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.824  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.824  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.824  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.824  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.824  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.824  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.824  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.824  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.824  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.824  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.824  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.824  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.824  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.825  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.825  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.825  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.825  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.825  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.825  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.826  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.826  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.826  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.826  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.826  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.826  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.826  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.826  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.826  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.826  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.826  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.826  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.826  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.826  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.826  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.826  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.826  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.826  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.827  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.827  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.827  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.827  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.827  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.827  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.827  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.827  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.827  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.827  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.827  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.828  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.828  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.829  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.829  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.829  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.829  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.832  5840  5958 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-28 12:30:53.833  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.834  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-28 12:30:53.835  5840  5958 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-28 12:30:53.836  5840  5958 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-28 12:30:53.836  5840  5840 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-28 12:30:53.836  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-28 12:30:53.836  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:30:53.837  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:30:53.838  5840  6083 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:30:53.839  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.839  3773  3789 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
07-28 12:30:53.839  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-28 12:30:53.839  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-28 12:30:53.839  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-28 12:30:53.839  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.839  5840  5958 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-28 12:30:53.839  5840  5840 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-28 12:30:53.839  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.839  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.839  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:30:53.839  5840  5958 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:30:53.839  5840  6083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-28 12:30:53.839  5840  6083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-28 12:30:53.839  5840  6083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,07-28 12:30:53.840  5840  5840 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-28 12:30:53.841  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:30:53.841  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:30:53.842  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.842  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.842  5840  5958 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:30:53.842  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.842  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.843  5840  5958 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:30:53.843  5840  5840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:30:53.843  5840  5840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:30:53.844  5840  5840 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:30:53.844  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.844  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.844  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.844  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.844  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.844  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.844  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.844  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.844  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.844  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.844  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.844  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.844  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.844  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.844  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.845  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.845  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.845  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.845  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.846  5840  5958 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-28 12:30:53.846  5840  5958 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:30:53.847  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:30:53.848  5840  5958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:30:53.848  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.848  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.848  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.849  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.849  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.849  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.849  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.849  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.849  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.849  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.849  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.849  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.849  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.849  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.852  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.852  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.852  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.852  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.853  1036  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:30:53.857  1036  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:30:53.858  1036  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:30:53.858  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.858  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.858  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.858  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.858  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.858  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.858  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.858  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.858  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.858  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.858  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.858  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.858  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.858  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.859  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.859  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.859  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.859  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.860  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.860  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.860  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.860  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.860  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.860  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.860  5840  5958 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706ce1e not in the list
07-28 12:30:53.860  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.860  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.860  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.860  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.860  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.860  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.860  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.860  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.860  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.860  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.860  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e716ff not in the list
07-28 12:30:53.861  5840  5958 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-28 12:30:53.861  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:30:53.862  5840  5958 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-28 12:30:53.862  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:30:53.862  5840  5958 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-28 12:30:53.862  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:30:53.863  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:30:53.863  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-28 12:30:53.864  5840  5958 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-28 12:30:53.864  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:30:53.864  5840  5958 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-28 12:30:53.864  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:30:53.864  5840  5958 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-28 12:30:53.864  5840  5958 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-28 12:30:53.864  5840  5958 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-28 12:30:53.864  5840  5958 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-28 12:30:53.865  5840  5958 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-28 12:30:53.865  5840  5958 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-28 12:30:53.865  5840  5958 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-28 12:30:53.865  5840  5958 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-28 12:30:53.866  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:30:53.866  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3075c964 added. We now have 2 listener(s)
07-28 12:30:53.866  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:30:53.867  5840  5958 D BluetoothAdapter: enable(): BT is already enabled..!
07-28 12:30:53.868  1036  1936 D WifiServiceImplEx: setWifiEnabled: true pid=5840, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:30:53.869  1036  1936 D WifiService: setWifiEnabled: true pid=5840, uid=10118
07-28 12:30:53.869  1036  1936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:30:53.870  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:30:53.870  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cdb67cd added. We now have 3 listener(s)
07-28 12:30:53.870  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:30:53.873  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:30:53.873  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@899d882 added. We now have 4 listener(s)
07-28 12:30:53.873  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:30:53.874  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:30:53.874  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4fb93 added. We now have 5 listener(s)
07-28 12:30:53.874  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:30:53.876  1036  1936 D WifiServiceImplEx: setWifiEnabled: false pid=5840, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:30:53.876  1036  1936 D WifiService: setWifiEnabled: false pid=5840, uid=10118
07-28 12:30:53.876  1036  1936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:30:53.885  1036  1522 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:30:53.885  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:30:53.885  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:30:53.885  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-28 12:30:53.885  1036  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-28 12:30:53.886  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:30:53.886  1036  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:30:53.886  1036  1960 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3a54bd7b mBinding = false
07-28 12:30:53.886  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:30:53.887  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:30:53.887  1036  1036 D RttService: SCAN_AVAILABL,E : 1
07-28 12:30:53.887  1036  1521 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:53.887  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:53.887  1036  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@178ce719
07-28 12:30:53.887  1036  1542 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:30:53.887  1036  1521 D LGWifiP2pService: P2pDisablingState
07-28 12:30:53.887  1036  1521 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:53.888  1036  1521 D LGWifiP2pService: p2p socket connection lost
07-28 12:30:53.888  1036  1521 D LGWifiP2pService: P2pDisabledState
07-28 12:30:53.888  1036  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:53.889  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:30:53.889  1927  1927 D WfdsService: WifiP2pState is changed : false
07-28 12:30:53.889  1036  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-28 12:30:53.889  1927  2296 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-28 12:30:53.889  1927  2296 D WfdsService: Set the WFDS Monitor: false
07-28 12:30:53.890   310   894 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:30:53.894  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:30:53.895  1927  2296 D WfdsService: STATE : WfdsDisabledState - enter
07-28 12:30:53.895  1927  2297 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-28 12:30:53.896  1927  2770 D CtrlSupplicant: Received on exit socket, terminate
07-28 12:30:53.896  1927  2770 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-28 12:30:53.896  1927  2770 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-28 12:30:53.896  1927  2770 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-28 12:30:53.896  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-28 12:30:53.897  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:53.897  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:53.897  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:30:53.898  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.898  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:30:53.898  1927  2296 W WfdsService: DefaultState - msg [9445378] is not handled
,07-28 12:30:53.899  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-28 12:30:53.899  2149  2149 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
07-28 12:30:53.900  1036  1522 D WifiNative-p2p0: doBoolean: TERMINATE
07-28 12:30:53.902  2149  2149 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
07-28 12:30:53.903  1036  1108 D BluetoothManagerService: Message: 2
07-28 12:30:53.904  1036  1108 D BluetoothManagerService: Sending off request.
07-28 12:30:53.904  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:53.905  1036  1522 D WifiNative-p2p0: TERMINATE: returned true
07-28 12:30:53.905  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:30:53.905  1036  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:30:53.905  1036  1522 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:30:53.905  1036  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:30:53.906  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:30:53.906  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:30:53.906  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-28 12:30:53.909  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:53.909  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:53.909  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:30:53.909  3773  3900 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-28 12:30:53.910  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:30:53.912  3773  3856 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-28 12:30:53.912  3773  3856 D BluetoothAdapterProperties: Setting state to 13
07-28 12:30:53.912  3773  3856 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:30:53.913  3773  3856 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 12:30:53.913  3773  3856 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 12:30:53.913  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-28 12:30:53.914  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:53.914  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.914  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.914  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:30:53.914  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:53.914  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.914  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.914  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:53.914  1036  1108 D BluetoothManagerService: Message: 60
07-28 12:30:53.915  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-28 12:30:53.915  1036  1108 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-28 12:30:53.918  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.918  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:53.918  5840  5958 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:30:53.918  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.918  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:30:53.918  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.918  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.918  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:30:53.918  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:53.918  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.918  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.918  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:53.919  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.919  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:53.921  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.921  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnecti,vityInfo: State changed:
07-28 12:30:53.921  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.921  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.921  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:30:53.921  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:53.921  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.921  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.921  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:53.921  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.922  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:30:53.934  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.934  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:30:53.935  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:30:53.937  1036  1757 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6091 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:30:53.938  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:53.941  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-28 12:30:53.941  3773  3860 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:30:53.941  3773  3856 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 12:30:53.941  3773  4140 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:30:53.942  3773  3856 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:30:53.942  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-28 12:30:53.942  3773  3968 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-28 12:30:53.943  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:30:53.943  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-28 12:30:53.943  3773  4100 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:30:53.943  3773  4138 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:30:53.943  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:30:53.943  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:30:53.943  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:30:53.943  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:30:53.944  3773  3968 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:30:53.944  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:30:53.944  3773  3968 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:30:53.944  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:30:53.944  3773  3968 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:30:53.944  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-28 12:30:53.944  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-28 12:30:53.944  3773  3968 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:30:53.944  3773  4115 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:30:53.944  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:53.946  3773  4096 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-28 12:30:53.946  3773  4096 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:30:53.946  3773  4096 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-28 12:30:53.946  3773  4096 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-28 12:30:53.946  3773  4096 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-28 12:30:53.946  3773  4096 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-28 12:30:53.946  3773  4096 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-28 12:30:53.946  3773  4096 V ,BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-28 12:30:53.946  3773  3773 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:53.947  3773  3773 D BluetoothMapService: STATE_TURNING_OFF
07-28 12:30:53.947  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:53.947  3773  3773 V BluetoothMapService: Handler(): got msg=4
07-28 12:30:53.947  3773  3773 D BluetoothMapService: MAP Service closeService in
07-28 12:30:53.947  3773  3773 D BluetoothMapMasInstance: MAP Service shutdown
07-28 12:30:53.947  3773  3773 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:30:53.947  3773  3773 V BluetoothMapService: MAP Service closeService out
07-28 12:30:53.948  3773  3773 V BtOppService: Receiver DISABLED_ACTION 
07-28 12:30:53.948  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:53.948  3773  3773 I BtOppRfcommListener: stopping Accept Thread
07-28 12:30:53.948  3773  3773 V BtOppRfcommListener: close mBtServerSocket
07-28 12:30:53.949  3773  3773 V BtOppRfcommListener: waiting for thread to terminate
07-28 12:30:53.949  3773  4115 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-28 12:30:53.950  3773  3773 V BtOppRfcommListener: done waiting for thread to terminate
07-28 12:30:53.950  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:53.953  5840  6081 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
07-28 12:30:53.953  5840  6081 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 741)
07-28 12:30:53.953  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:53.955  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:30:53.976  1036  1099 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6108 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:30:53.977  3773  3773 V BtOppService: onDestroy
07-28 12:30:53.978  3773  3773 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-28 12:30:53.988  2585  2585 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 12:30:53.988  2585  2585 I wpa_supplicant: monitor socket send errors count : 1
07-28 12:30:53.988  2585  2585 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-2\x00 that cannot receive messages
,07-28 12:30:53.989  1036  2767 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-28 12:30:53.989  1036  2767 D WifiMonitor: Dropping event because (p2p0) is stopped
,07-28 12:30:54.022  6108  6108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:30:54.022  6108  6108 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-28 12:30:54.022  6108  6108 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:30:54.022  6108  6108 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
07-28 12:30:54.024  6108  6108 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,07-28 12:30:54.024  6108  6108 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-28 12:30:54.026  2585  2585 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:30:54.026  2585  2585 W wpa_supplicant: USIM:  scard_deinit function
07-28 12:30:54.027  1036  1108 D Tethering: InitialState.processMessage what=4
07-28 12:30:54.027  1036  2767 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-28 12:30:54.027  1036  2767 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:30:54.027  1036  2767 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:30:54.027  1036  2767 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-28 12:30:54.027  1036  1108 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:30:54.028  1036  2767 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:30:54.028  1036  2767 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:30:54.028  1036  1522 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=135408
07-28 12:30:54.028  1036  1522 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=135408
07-28 12:30:54.029  1036  1522 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:30:54.029  1036  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:30:54.029   310  6128 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-28 12:30:54.029  1036  1522 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=135409  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:30:54.030  1036  1522 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=135409  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:30:54.031  1036  1106 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-28 12:30:54.031  6091  6091 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:30:54.038  6091  6091 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:30:54.038  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:30:54.040  1036  1051 I ActivityManager: Killing 4790:com.android.providers.calendar/u0a14 (adj 15): empty #17
07-28 12:30:54.134  1036  1757 W libprocessgroup: failed to open /acct/uid_10014/pid_4790/cgroup.procs: No such file or directory
,07-28 12:30:54.150  2585  2585 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-28 12:30:54.151  1036  2767 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,07-28 12:30:54.151  1036  2767 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING ,
07-28 12:30:54.152  1036  2767 D WifiMonitor: Disconnecting from the supplicant, no more events
07-28 12:30:54.154  1036  1522 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
07-28 12:30:54.242  6108  6108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-28 12:30:54.248  3773  3773 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:30:54.248  3773  3773 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:54.248  3773  3773 V BluetoothPbapReceiver: ***********state = 13
07-28 12:30:54.250  3773  3773 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-28 12:30:54.252  3773  3773 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:54.252  3773  3773 V BluetoothPbapService: state: 13
07-28 12:30:54.252  3773  3773 V BluetoothPbapService: Pbap Service closeService in
07-28 12:30:54.256  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:30:54.256  3773  3773 V BluetoothPbapService: successfully stopped pbap service
07-28 12:30:54.256  3773  3773 V BluetoothPbapService: Pbap Service closeService out
07-28 12:30:54.256  3773  3773 V BluetoothPbapService: Pbap Service onDestroy
07-28 12:30:54.256  3773  3773 V BluetoothPbapService: Pbap Service closeService in
07-28 12:30:54.256  3773  3773 V BluetoothPbapService: Pbap Service closeService out
07-28 12:30:54.256  3773  3773 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-28 12:30:54.278  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:30:54.316  6108  6108 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:30:54.316  6108  6108 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:30:54.329  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:54.330  1036  1052 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6131 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
07-28 12:30:54.330  1036  1522 D WifiOffDelayIfNotUsed: stopMonitoring
07-28 12:30:54.331  1036  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:30:54.331  1036  1522 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:30:54.331  1036  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:30:54.332  1927  1927 D WfdsService: Supplicant Connection state is changed : false
07-28 12:30:54.332  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-28 12:30:54.332  1927  2296 D WfdsService: Set the WFDS Monitor: false
07-28 12:30:54.332  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:30:54.336  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:30:54.338  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:54.338  1036  1108 D BluetoothManagerService: Message: 20
07-28 12:30:54.338  1036  1108 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a4362d:true
07-28 12:30:54.343  2494  2494 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:54.344  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-28 12:30:54.344  1036  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-28 12:30:54.344  1036  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-28 12:30:54.345  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:54.347  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:54.347  5840  5840 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-28 12:30:54.354  1036  1108 D BluetoothManagerService: Message: 30
07-28 12:30:54.359  1036  1108 D BluetoothManagerService: Message: 30
,07-28 12:30:54.363  6108  6108 D LocalBluetoothProfileManager: Adding local MAP profile
07-28 12:30:54.365  6108  6108 D BluetoothMap: Create BluetoothMap proxy object
07-28 12:30:54.365  1036  1108 D BluetoothManagerService: Message: 30
07-28 12:30:54.369  1036  1108 D BluetoothManagerService: Message: 30
07-28 12:30:54.370  6108  6108 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-28 12:30:54.371  6108  6108 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-28 12:30:54.382  6108  6108 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,07-28 12:30:54.385  6108  6108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-28 12:30:54.396  6108  6108 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:30:54.404  6108  6108 D BluetoothInputDevice: Proxy object connected
07-28 12:30:54.406  6108  6108 D HidProfile: Bluetooth service connected
07-28 12:30:54.407  6108  6108 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:30:54.407  6108  6108 D PanProfile: Bluetooth service connected
,07-28 12:30:54.408  6108  6108 D BluetoothMap: Proxy object connected
07-28 12:30:54.409  6108  6108 D MapProfile: Bluetooth service connected
07-28 12:30:54.409  6108  6108 D BluetoothMap: getConnectedDevices()
07-28 12:30:54.409  6108  6108 D BluetoothMap: Bluetooth is Not enabled
07-28 12:30:54.409  6108  6108 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 12:30:54.449  1036  2015 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6153 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
07-28 12:30:54.451  1036  2015 I ActivityManager: Killing 2149:com.lge.music/u0a34 (adj 15): empty #17
,07-28 12:30:54.469   314  1370 V AudioFlinger: 2149 died, releasing its sessions
07-28 12:30:54.469   314  1370 V AudioFlinger:  pid 1839 @ 0
07-28 12:30:54.469   314  1370 V AudioFlinger:  pid 3146 @ 1
07-28 12:30:54.469   314  1370 V AudioFlinger:  pid 3146 @ 2
,07-28 12:30:54.498  1036  1051 W libprocessgroup: failed to open /acct/uid_10034/pid_2149/cgroup.procs: No such file or directory
,07-28 12:30:54.503  6131  6131 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-28 12:30:54.504  6131  6131 W LG Account v2.2: No ProfileInfo entries
07-28 12:30:54.504  6131  6131 I LG Account v2.2: isEnabled: false
07-28 12:30:54.504  6131  6131 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-28 12:30:54.504  6131  6131 I Feature : [Lifetracker]Country: EU
07-28 12:30:54.504  6131  6131 I Feature : [Lifetracker]Operator: OPEN
07-28 12:30:54.504  6131  6131 I Feature : [Lifetracker]Ranking support: false
07-28 12:30:54.504  6131  6131 I Feature : [Lifetracker]Comfort support: false
07-28 12:30:54.504  6131  6131 I Feature : [Lifetracker]Accessory: true
07-28 12:30:54.504  6131  6131 I Feature : [Lifetracker]Health device: true
07-28 12:30:54.505  6131  6131 I Feature : [Lifetracker]Extra Pedometer: false
07-28 12:30:54.505  6131  6131 I Feature : [Lifetracker]Blood glucose device: false
07-28 12:30:54.505  6131  6131 I Feature : [Lifetracker]Device Number: 3
07-28 12:30:54.511  6108  6108 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-28 12:30:54.515  6108  6108 D BluetoothPermissionRequest: onReceive
07-28 12:30:54.517  6108  6108 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-28 12:30:54.521  6153  6153 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:30:54.528  6108  6108 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-28 12:30:54.530  1036  1891 I ActivityManager: Killing 5607:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-28 12:30:54.569  3773  3773 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-28 12:30:54.569  3773  3773 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,07-28 12:30:54.570  3773  3773 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-28 12:30:54.574  6153  6153 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-28 12:30:54.575  1036  1052 W libprocessgroup: failed to open /acct/uid_10008/pid_5607/cgroup.procs: No such file or directory
07-28 12:30:54.577  3773  3773 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:54.577  3773  3773 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:30:54.579  3773  3773 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:30:54.579  3773  3773 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:54.580  3773  3773 V BluetoothFtpService: Ftp Service closeService
07-28 12:30:54.580  3773  3773 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-28 12:30:54.582  3773  3773 V BluetoothFtpService: successfully stopped ftp service
07-28 12:30:54.583  3773  3773 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:30:54.583  3773  3773 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:30:54.583  3773  3773 V BluetoothSapReceiver: SapReceiver onReceive 
,07-28 12:30:54.584  3773  3773 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:54.584  3773  3773 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-28 12:30:54.584  3773  3773 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:30:54.587  3773  3773 V BluetoothFtpService: Ftp Service onDestroy
07-28 12:30:54.587  3773  3773 V BluetoothFtpService: Ftp Service closeService
07-28 12:30:54.627  6153  6153 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,07-28 12:30:54.628  6153  6153 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-28 12:30:54.628  6153  6153 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-28 12:30:54.628  6153  6153 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-28 12:30:54.629  6153  6153 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-28 12:30:54.631  6153  6153 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-28 12:30:54.637  6153  6153 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-28 12:30:54.662  1036  1960 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6177 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:30:54.668  3773  3773 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:54.668  3773  3773 V BluetoothSapService: state: 13
07-28 12:30:54.668  3773  3773 V BluetoothSapService: Stopping SAP server process
07-28 12:30:54.672  3773  3773 V BluetoothSapService: Sap Service closeSapService in
07-28 12:30:54.672  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:30:54.672  3773  3773 V BluetoothSapService: Close listen Socket : 
07-28 12:30:54.672  3773  3773 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:30:54.673  3773  3773 V BluetoothSapService: Close sapd  Socket : 
07-28 12:30:54.674  3773  3773 V BluetoothSapService: Sap Service closeSapService out
07-28 12:30:54.674  3773  3773 V BluetoothSapService: Sap Service onDestroy
07-28 12:30:54.674  3773  3773 V BluetoothSapService: Sap Service closeSapService in
07-28 12:30:54.674  3773  3773 V BluetoothSapService: Close listen Socket : 
07-28 12:30:54.674  3773  3773 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:30:54.674  3773  3773 V BluetoothSapService: Close sapd  Socket : 
07-28 12:30:54.674  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:30:54.675  3773  3773 V BluetoothSapService: Sap Service closeSapService out
07-28 12:30:54.705  6153  6153 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-28 12:30:54.713  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:30:54.714  6153  6153 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-28 12:30:54.718  6091  6091 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,07-28 12:30:54.719  6091  6091 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:30:54.721  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:30:54.723  6153  6153 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-28 12:30:54.726  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:30:54.728  6177  6177 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 12:30:54.736  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:54.745  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:30:54.745  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:30:54.748  6153  6153 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:30:54.751  1036  1757 I ActivityManager: Killing 5642:com.lge.appbox.client/u0a11 (adj 15): empty #17
07-28 12:30:54.781  1036  1051 W libprocessgroup: failed to open /acct/uid_10011/pid_5642/cgroup.procs: No such file or directory
,07-28 12:30:54.855  1036  1757 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6197 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-28 12:30:54.943  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:30:54.947  3773  3860 D bt_hci_bdroid: cleanup
07-28 12:30:54.947  3773  3968 W bt-btif : ag scb idx 1 not allocated
07-28 12:30:54.947  3773  3968 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:30:54.947  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:30:54.948  3773  3968 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:30:54.948  3773  3968 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:30:54.948  3773  3973 I bt_lpm  : LPM is already off!!!
07-28 12:30:54.948  3773  4087 I bt_userial_mct: exiting userial_read_thread
07-28 12:30:54.949  3773  4087 D bt_userial_mct: Leaving userial_evt_read_thread()
07-28 12:30:54.949  3773  3860 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-28 12:30:54.949  3773  3973 I bt_vendor: hw_epilog_process
07-28 12:30:54.950  3773  3860 D bt_hci_bdroid: cleanup Finalizing cleanup
07-28 12:30:54.950  3773  3860 D bt_userial_mct: userial_close
07-28 12:30:54.950  3773  3860 E bt_userial_mct: pthread_join() FAILED result:3
07-28 12:30:54.950  3773  3860 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-28 12:30:54.950  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:54.960  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:54.980  6197  6217 W FormManager: Network not available. Please check & try again.
,07-28 12:30:54.993  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:30:54.993  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:30:54.993  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:30:54.993  6108  6108 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:30:54.994  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-28 12:30:55.002  6197  6218 V FormManager: Network unavailable.
07-28 12:30:55.004  6197  6218 V FormManager: Network unavailable.
07-28 12:30:55.005  6108  6108 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:30:55.006  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:30:55.006  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:30:55.006  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:30:55.006  6108  6108 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:30:55.006  6108  6108 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:30:55.010  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:30:55.010  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:30:55.012  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:30:55.016  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:30:55.022  6091  6091 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-28 12:30:55.022  6091  6091 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:30:55.022  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:30:55.026  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:55.031  6197  6222 W FormManager: Network not available. Please check & try again.
07-28 12:30:55.033  4240  6223 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:30:55.035  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:55.035  4240  6223 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:30:55.035  4240  6221 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:30:55.037  3773  3860 D bt_hci_bdroid: set_power 0
,07-28 12:30:55.037  3773  3860 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-28 12:30:55.037  3773  3860 I bt_vendor: bluetooth satus is on
07-28 12:30:55.037  3773  3860 I bt_vendor: bt-vendor : resetting BT status
07-28 12:30:55.037  3773  3860 I bt_vendor: Starting hciattach daemon
07-28 12:30:55.037  3773  3860 I bt_vendor: try to set false
07-28 12:30:55.038  3773  3860 I bt_vendor: Starting hciattach daemon
07-28 12:30:55.038  3773  3860 I bt_vendor: try to set false
07-28 12:30:55.038  3773  3860 I bt_vendor: cleanup
07-28 12:30:55.039  3773  3968 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:30:55.039  3773  3860 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:30:55.039  3773  3860 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,07-28 12:30:55.041  3773  3856 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:30:55.045  3773  3773 D HeadsetService: Received stop request...Stopping profile...
07-28 12:30:55.048  3773  3773 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:30:55.048  3773  3773 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:30:55.048  3773  3773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d082d40
07-28 12:30:55.048  3773  3887 D HeadsetStateMachine: Exit Disconnected: -1
07-28 12:30:55.050  1036  1036 D BluetoothHeadset: Proxy object disconnected
07-28 12:30:55.050  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-28 12:30:55.051  1839  1839 D BluetoothHeadset: Proxy object disconnected
07-28 12:30:55.051  1839  1839 D BluetoothHeadset: Proxy object disconnected
,07-28 12:30:55.052  1839  1839 D BluetoothHeadset: Proxy object disconnected
07-28 12:30:55.052  3773  3773 D A2dpService: Received stop request...Stopping profile...
07-28 12:30:55.054  3773  3773 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-28 12:30:55.054  3773  3950 D A2dpStateMachine: Exit Disconnected: -1
07-28 12:30:55.056  3773  3773 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-28 12:30:55.056  3773  3773 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:30:55.057  3773  3773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d082d40
07-28 12:30:55.058  1036  1036 D BluetoothA2dp: Proxy object disconnected
07-28 12:30:55.058  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-28 12:30:55.059  3773  3773 D HidService: Received stop request...Stopping profile...
07-28 12:30:55.060  3773  3773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d082d40
07-28 12:30:55.060  3773  3856 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:30:55.061  3773  3773 D HeadsetStateMachine: Unbinding service...
07-28 12:30:55.062  3773  3773 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:30:55.063  3773  3773 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:30:55.063  3773  3773 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:30:55.063  3773  3773 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:30:55.063  3773  3773 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:30:55.063  3773  3773 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:30:55.063  3773  3773 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,07-28 12:30:55.066  3773  3773 D HealthService: Received stop request...Stopping profile...
07-28 12:30:55.066  6108  6108 D BluetoothInputDevice: Proxy object disconnected
07-28 12:30:55.067  3773  3773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d082d40
07-28 12:30:55.067  6108  6108 D HidProfile: Bluetooth service disconnected
07-28 12:30:55.068  3773  3773 D PanService: Received stop request...Stopping profile...
07-28 12:30:55.069  3773  3773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d082d40
07-28 12:30:55.069  6197  6225 V FormManager: Network unavailable.
07-28 12:30:55.071  6108  6108 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:30:55.072  6108  6108 D PanProfile: Bluetooth service disconnected
07-28 12:30:55.072  3773  3773 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:30:55.072  6153  6153 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 12:30:55.073  3773  3773 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:30:55.073  3773  3773 D BtGatt.GattService: stop()
07-28 12:30:55.073  3773  3773 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 12:30:55.074  3773  3773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d082d40
07-28 12:30:55.075  3773  3773 I BluetoothA2dpServiceJni: cleanupNative
,07-28 12:30:55.075  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 12:30:55.076  6153  6153 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-28 12:30:55.077  3773  3954 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:30:55.077  3773  3773 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:30:55.077  3773  3773 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:30:55.078  3773  3773 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:30:55.078  3773  3773 D BluetoothMapService: stop()
07-28 12:30:55.079  3773  3773 D BluetoothMapEmailAppObserver: deinitObservers()
07-28 12:30:55.079  3773  3773 D BluetoothMapEmailAppObserver: removeReceiver()
07-28 12:30:55.079  3773  3773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d082d40
07-28 12:30:55.079  6197  6225 V FormManager: Network unavailable.
07-28 12:30:55.080  3773  3773 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:30:55.080  3773  3773 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:30:55.081  3773  3773 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:30:55.081  3773  3773 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:30:55.081  3773  3773 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:30:55.081  6108  6108 D BluetoothMap: Proxy object disconnected
07-28 12:30:55.081  6108  6108 D MapProfile: Bluetooth service disconnected
07-28 12:30:55.081  3773  3773 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:30:55.081  3773  3773 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 12:30:55.082  3773  3773 V BluetoothMapService: Handler(): got msg=4
07-28 12:30:55.082  3773  3773 D BluetoothMapService: MAP Service closeService in
07-28 12:30:55.082  3773  3773 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:30:55.082  3773  3773 V BluetoothMapService: MAP Service closeService out
07-28 12:30:55.082  3773  3773 D BluetoothMapService: cleanup()
07-28 12:30:55.082  3773  3773 D BluetoothMapService: MAP Service closeService in
07-28 12:30:55.082  3773  3773 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:30:55.082  3773  3773 V BluetoothMapService: MAP Service closeService out
07-28 12:30:55.082  3773  3856 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:30:55.082  3773  3856 D BluetoothAdapterProperties: Setting state to 10
07-28 12:30:55.082  3773  3856 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:30:55.083  1036  1108 D BluetoothManagerService: Message: 60
07-28 12:30:55.083  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-28 12:30:55.083  1036  1108 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-28 12:30:55.084  3773  3856 I BluetoothAdapterState: Entering OffState
07-28 12:30:55.084  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:30:55.084  1036  1108 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:30:55.085  6108  6124 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:30:55.088  1036  1936 I ActivityManager: Killing 5661:com.android.contacts/u0a19 (adj 15): empty #17
,07-28 12:30:55.116  6153  6153 D LgDataFeature: LgDataFeature() Constructor: none
,07-28 12:30:55.116  6153  6153 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:30:55.123  6153  6153 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-28 12:30:55.124  6153  6153 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-28 12:30:55.124  6153  6153 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-28 12:30:55.124  6153  6153 V SoundPool: doLoad: loading sample sampleID=1
07-28 12:30:55.125  6153  6153 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:30:55.126  6153  6234 V SoundPool: Start decode
07-28 12:30:55.126  6153  6234 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-28 12:30:55.127   314  1371 V MediaPlayerService: decode(22, 10857164, 17813)
07-28 12:30:55.127   314  1371 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-28 12:30:55.127   314  1371 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-28 12:30:55.127   314  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-28 12:30:55.127   314  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-28 12:30:55.127   314  1371 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-28 12:30:55.127   314  1371 V MediaPlayerService: player type = 3
07-28 12:30:55.127   314  1371 V AwesomePlayer: AwesomePlayer create()
,07-28 12:30:55.128   314  1371 V AwesomePlayer: reset_l() 
07-28 12:30:55.129   314  1371 V AwesomePlayer: cancelPlayerEvents
07-28 12:30:55.129   314  1371 V AwesomePlayer: setAudioSink() 
07-28 12:30:55.129   314  1371 V AwesomePlayer: reset_l() 
07-28 12:30:55.129   314  1371 V AudioCache: notify(0xb1005040, 8, 0, 0)
07-28 12:30:55.129   314  1371 V AudioCache: ignored
07-28 12:30:55.129   314  1371 V AwesomePlayer: cancelPlayerEvents
07-28 12:30:55.129   314  1371 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
07-28 12:30:55.129   314  1371 V AwesomePlayer: setDataSource_l dataSource
07-28 12:30:55.129   314  1371 V LGParserOSAL: SniffLGParser start
07-28 12:30:55.129   314  1371 V LGParserOSAL: MainType:5, SubType=0
07-28 12:30:55.129   314  1371 V LGParserOSAL: #### check Mime : application/ogg
07-28 12:30:55.129   314  1371 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-28 12:30:55.130   314  1371 E MediaExtractor: Use LGExtractor :application/ogg 
07-28 12:30:55.178   314  1371 V LGParserOSAL: supported mime: application/ogg
07-28 12:30:55.179   314  1371 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-28 12:30:55.179   314  1371 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-28 12:30:55.179   314  1371 V AwesomePlayer: mBitrate = -1 bits/sec
07-28 12:30:55.179   314  1371 V AwesomePlayer: AudioTrack Setting
07-28 12:30:55.179   314  1371 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-28 12:30:55.179   314  1371 V AwesomePlayer: setAudioSource() 
07-28 12:30:55.179   314  1371 V MediaPlayerService: prepare
07-28 12:30:55.179   314  1371 V AwesomePlayer: prepareAsync_l() 
07-28 12:30:55.179   314  1371 V MediaPlayerService: wait for prepare
07-28 12:30:55.179   314  6235 V AwesomePlayer: onPrepareAsyncEvent() 
07-28 12:30:55.179   314  6235 V AwesomePlayer: initAudioDecoder() 
07-28 12:30:55.179   314  6235 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:30:55.179   314  6235 V AudioSystem: isOffloadSupported()
07-28 12:30:55.179   314  6235 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:30:55.179   314  6235 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:30:55.179   314  6235 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:30:55.179   314  6235 V AwesomePlayer: getUseOffload() = 0 
07-28 12:30:55.179   314  6235 V OMXCodec: OMXCodec::Create
07-28 12:30:55.180   314  6235 V OMXCodec: findMatchingCodecs()
07-28 12:30:55.180   314  6235 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-28 12:30:55.180   314  6235 V OMXCodec: matchingCodecs.size()=1
07-28 12:30:55.180   314  6235 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,07-28 12:30:55.187   314  6235 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-28 12:30:55.187   314  6235 V LGCodecAdapter: LG Codec Adapter start
07-28 12:30:55.187   314  6235 V OMXCodec: OMXCodec Createtor
07-28 12:30:55.187   314  6235 V OMXCodec: setComponentRole
07-28 12:30:55.187   314  6235 V OMXCodec: configureCodec protected=0
07-28 12:30:55.187   314  6235 V LGCodecAdapter: called getLGCodecSpecificData
07-28 12:30:55.188   314  6235 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-28 12:30:55.188   314  6235 V LGCodecOSAL: Called LGconfigureCodecMETA
07-28 12:30:55.188   314  6235 V LGCodecOSAL: Called LGconfigureCodecMSG
07-28 12:30:55.188   314  6235 V LGCodecOSAL: Not support LGCodec
07-28 12:30:55.188   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:30:55.188   314  6235 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-28 12:30:55.188   314  6235 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-28 12:30:55.189   314  6235 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-28 12:30:55.189   314  6235 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:30:55.189   314  6235 V AudioSystem: isOffloadSupported()
07-28 12:30:55.189   314  6235 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:30:55.189   314  6235 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:30:55.189   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-28 12:30:55.189   314  6235 V OMXCodec: init()
07-28 12:30:55.189   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-28 12:30:55.190   314  6235 V OMXCodec: allocateBuffers
07-28 12:30:55.190   314  6235 V OMXCodec: allocateBuffersOnPort portIndex=0
07-28 12:30:55.190   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-28 12:30:55.190   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
07-28 12:30:55.190   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
07-28 12:30:55.191   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
07-28 12:30:55.191   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
07-28 12:30:55.191   314  6235 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:30:55.191   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:30:55.191   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
07-28 12:30:55.191   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
07-28 12:30:55.191   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
07-28 12:30:55.191   314  6235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb178f1f0 on output port
07-28 12:30:55.192   314  6235 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 12:30:55.192   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:30:55.192   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:30:55.192   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-28 12:30:55.192   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3,
07-28 12:30:55.192   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-28 12:30:55.192   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-28 12:30:55.192   314  6235 V OMXCodec: init() mAsyncCompletion wait free! 
,07-28 12:30:55.192   314  6235 V AwesomePlayer: finishAsyncPrepare_l() 
07-28 12:30:55.193   314  6235 V AudioCache: notify(0xb1005040, 5, 0, 0)
07-28 12:30:55.193   314  6235 V AudioCache: ignored
07-28 12:30:55.193   314  6235 V AudioCache: notify(0xb1005040, 1, 0, 0),
07-28 12:30:55.193   314  6235 V AudioCache: prepared
07-28 12:30:55.193   314  1371 V AudioCache: wait - success
07-28 12:30:55.193   314  1371 V MediaPlayerService: start
,07-28 12:30:55.193   314  1371 V AwesomePlayer: play_l() 
07-28 12:30:55.193   314  1371 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-28 12:30:55.193   314  1371 V AwesomePlayer: createAudioPlayer_l
,07-28 12:30:55.193   314  1371 V AwesomePlayer: seekAudioIfNecessary_l() 
07-28 12:30:55.193   314  1371 V AwesomePlayer: startAudioPlayer_l() 
07-28 12:30:55.193   314  1371 D AudioPlayer: start of Playback, useOffload 0
,07-28 12:30:55.193   314  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:30:55.193   314  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:30:55.199  1036  1891 W libprocessgroup: failed to open /acct/uid_10019/pid_5661/cgroup.procs: No such file or directory
07-28 12:30:55.200  1839  4330 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-28 12:30:55.202   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
,07-28 12:30:55.202   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-28 12:30:55.202   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-28 12:30:55.202   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,07-28 12:30:55.202   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-28 12:30:55.202   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:30:55.203   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
,07-28 12:30:55.203   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:30:55.203   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
07-28 12:30:55.203   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,07-28 12:30:55.203   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
07-28 12:30:55.203   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:30:55.204   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977493488
,07-28 12:30:55.204   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:30:55.204   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-28 12:30:55.204   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,07-28 12:30:55.204   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-28 12:30:55.204   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-28 12:30:55.204   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
,07-28 12:30:55.204   314  6237 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:30:55.204   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:30:55.205   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
,07-28 12:30:55.205   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
07-28 12:30:55.205   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
07-28 12:30:55.205   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
07-28 12:30:55.207   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,07-28 12:30:55.207   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-28 12:30:55.212   314  1371 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-28 12:30:55.212  6032  6032 D UEI.SmartControl: QS Service created
,07-28 12:30:55.214   314  1371 V AudioCache: notify(0xb1005040, 6, 0, 0)
07-28 12:30:55.214   314  1371 V AudioCache: ignored
07-28 12:30:55.214   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.214   314  6238 V AudioCache: memcpy(0xaf104000, 0xb57c3000, 4096)
07-28 12:30:55.215  1839  2455 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:30:55.216  1036  1108 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:30:55.217  6108  6123 D BluetoothPan: onBluetoothStateChange on: false
07-28 12:30:55.218  6108  6124 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:30:55.219  6153  6153 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 12:30:55.220  6108  6123 D BluetoothPbap: onBluetoothStateChange: up=false
,07-28 12:30:55.221   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.221   314  6238 V AudioCache: memcpy(0xaf105000, 0xb57c3000, 4096)
07-28 12:30:55.221  1036  1108 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-28 12:30:55.221   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.221   314  6238 V AudioCache: memcpy(0xaf106000, 0xb57c3000, 4096)
07-28 12:30:55.221  1036  1108 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-28 12:30:55.222   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.222   314  6238 V AudioCache: memcpy(0xaf107000, 0xb57c3000, 4096)
07-28 12:30:55.223   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.223   314  6238 V AudioCache: memcpy(0xaf108000, 0xb57c3000, 4096)
07-28 12:30:55.224  1036  1108 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-28 12:30:55.224  1036  1108 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-28 12:30:55.224  1036  1108 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3a54bd7b mBinding = false
07-28 12:30:55.224  6153  6153 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:30:55.225  1036  1108 D BluetoothManagerService: Sending unbind request.
07-28 12:30:55.226  1036  1108 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-28 12:30:55.226   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.226   314  6238 V AudioCache: memcpy(0xaf109000, 0xb57c3000, 4096)
07-28 12:30:55.227   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.227   314  6238 V AudioCache: memcpy(0xaf10a000, 0xb57c3000, 4096)
07-28 12:30:55.227   314  1371 V MediaPlayerService: wait for playback complete
07-28 12:30:55.228   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.228   314  6238 V AudioCache: memcpy(0xaf10b000, 0xb57c3000, 4096)
07-28 12:30:55.229  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:30:55.229   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.229   314  6238 V AudioCache: memcpy(0xaf10c000, 0xb57c3000, 4096)
07-28 12:30:55.230   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.230   314  6238 V AudioCache: memcpy(0xaf10d000, 0xb57c3000, 4096)
07-28 12:30:55.231   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.231   314  6238 V AudioCache: memcpy(0xaf10e000, 0xb57c3000, 4096)
07-28 12:30:55.232   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.232   314  6238 V AudioCache: memcpy(0xaf10f000, 0xb57c3000, 4096)
07-28 12:30:55.232   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.233   314  6238 V AudioCache: memcpy(0xaf110000, 0xb57c3000, 4096)
07-28 12:30:55.233  6032  6032 I UEI.SmartControl: Service initServices...
07-28 12:30:55.233  6032  6032 D UEI.SmartControl: QS start get config
07-28 12:30:55.234   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.234   314  6238 V AudioCache: memcpy(0xaf111000, 0xb57c3000, 4096)
07-28 12:30:55.237  3773  3860 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-28 12:30:55.238  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:55.238  1927  2107 D LGBluetoothAPIService: Message: 2
07-28 12:30:55.238  1927  2107 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1b32fa8d mBinding = false
07-28 12:30:55.238  1927  2107 D LGBluetoothAPIService: Sending unbind request.
07-28 12:30:55.239  3773  3773 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:30:55.239  3773  3773 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 12:30:55.239  3773  3773 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:30:55.239  3773  3773 I art     : --- WEIRD: removing null entry 246
07-28 12:30:55.239  3773  3773 W art     : JNI W,ARNING: DeleteGlobalRef(0x2003da) failed to find entry
07-28 12:30:55.239  3773  3773 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-28 12:30:55.243   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.244   314  6238 V AudioCache: memcpy(0xaf112000, 0xb57c3000, 4096)
07-28 12:30:55.246  6108  6108 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:30:55.247  6108  6108 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-28 12:30:55.247  6108  6108 D LGBluetoothEventManager: [BTUI] clear device connection state
07-28 12:30:55.249  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:30:55.247   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.249   314  6238 V AudioCache: memcpy(0xaf113000, 0xb57c3000, 4096)
07-28 12:30:55.250   314  6238 V AudioCache: write(0xb57c3000, 4096)
,07-28 12:30:55.250   314  6238 V AudioCache: memcpy(0xaf114000, 0xb57c3000, 4096)
07-28 12:30:55.254  6153  6153 V LGMDMManager: Create singleton instance
07-28 12:30:55.258   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.258   314  6238 V AudioCache: memcpy(0xaf115000, 0xb57c3000, 4096)
07-28 12:30:55.258  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:55.258   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.258   314  6238 V AudioCache: memcpy(0xaf116000, 0xb57c3000, 4096)
07-28 12:30:55.258  6108  6108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:30:55.259  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:55.259   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.259   314  6238 V AudioCache: memcpy(0xaf117000, 0xb57c3000, 4096)
,07-28 12:30:55.260   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.260   314  6238 V AudioCache: memcpy(0xaf118000, 0xb57c3000, 4096)
07-28 12:30:55.261   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.261   314  6238 V AudioCache: memcpy(0xaf119000, 0xb57c3000, 4096)
07-28 12:30:55.262  1588  1588 D BluetoothAdapter: 309953467: getState() :  mService = null. Returning STATE_OFF
07-28 12:30:55.262  1588  1588 D BluetoothAdapter: 309953467: getState() :  mService = null. Returning STATE_OFF
07-28 12:30:55.262   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.262   314  6238 V AudioCache: memcpy(0xaf11a000, 0xb57c3000, 4096)
07-28 12:30:55.263   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.263   314  6238 V AudioCache: memcpy(0xaf11b000, 0xb57c3000, 4096)
,07-28 12:30:55.264   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.264   314  6238 V AudioCache: memcpy(0xaf11c000, 0xb57c3000, 4096)
07-28 12:30:55.265   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.265   314  6238 V AudioCache: memcpy(0xaf11d000, 0xb57c3000, 4096)
07-28 12:30:55.265  3773  3773 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-28 12:30:55.265   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.265   314  6238 V AudioCache: memcpy(0xaf11e000, 0xb57c3000, 4096)
07-28 12:30:55.266   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.266   314  6238 V AudioCache: memcpy(0xaf11f000, 0xb57c3000, 4096)
07-28 12:30:55.266  1036  1366 V AlarmManager: RTC_WAKEUP set : Alarm{180e9810 type 0 when 1469701853919 com.android.vending} when 1469701853919
07-28 12:30:55.267   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.267   314  6238 V AudioCache: memcpy(0xaf120000, 0xb57c3000, 4096)
07-28 12:30:55.268   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.268   314  6238 V AudioCache: memcpy(0xaf121000, 0xb57c3000, 4096)
07-28 12:30:55.268  3773  3773 I art     : System.exit called, status: 0
07-28 12:30:55.268  3773  3773 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-28 12:30:55.269   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.269   314  6238 V AudioCache: memcpy(0xaf122000, 0xb57c3000, 4096)
07-28 12:30:55.269   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.269   314  6238 V AudioCache: memcpy(0xaf123000, 0xb57c3000, 4096)
07-28 12:30:55.270   314  6238 V AudioCache: write(0xb57c3000, 4096)
,07-28 12:30:55.270   314  6238 V AudioCache: memcpy(0xaf124000, 0xb57c3000, 4096)
07-28 12:30:55.271   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.271   314  6238 V AudioCache: memcpy(0xaf125000, 0xb57c3000, 4096)
07-28 12:30:55.271   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.271   314  6238 V AudioCache: memcpy(0xaf126000, 0xb57c3000, 4096)
,07-28 12:30:55.272   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.272   314  6238 V AudioCache: memcpy(0xaf127000, 0xb57c3000, 4096)
07-28 12:30:55.273   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.273   314  6238 V AudioCache: memcpy(0xaf128000, 0xb57c3000, 4096)
07-28 12:30:55.273   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.273   314  6238 V AudioCache: memcpy(0xaf129000, 0xb57c3000, 4096)
07-28 12:30:55.274   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.274   314  6238 V AudioCache: memcpy(0xaf12a000, 0xb57c3000, 4096)
07-28 12:30:55.275   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.275   314  6238 V AudioCache: memcpy(0xaf12b000, 0xb57c3000, 4096)
07-28 12:30:55.275   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.275   314  6238 V AudioCache: memcpy(0xaf12c000, 0xb57c3000, 4096)
07-28 12:30:55.276   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.276   314  6238 V AudioCache: memcpy(0xaf12d000, 0xb57c3000, 4096)
07-28 12:30:55.277   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.277   314  6238 V AudioCache: memcpy(0xaf12e000, 0xb57c3000, 4096)
07-28 12:30:55.280   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.280   314  6238 V AudioCache: memcpy(0xaf12f000, 0xb57c3000, 4096)
07-28 12:30:55.281   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.281   314  6238 V AudioCache: memcpy(0xaf130000, 0xb57c3000, 4096)
07-28 12:30:55.282   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.282   314  6238 V AudioCache: memcpy(0xaf131000, 0xb57c3000, 4096)
07-28 12:30:55.282   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.282   314  6238 V AudioCache: memcpy(0xaf132000, 0xb57c3000, 4096)
07-28 12:30:55.283   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.283   314  6238 V AudioCache: memcpy(0xaf133000, 0xb57c3000, 4096)
07-28 12:30:55.284  6108  6108 D DockEventReceiver: finishStartingService: stopping service
07-28 12:30:55.284   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.284   314  6238 V AudioCache: memcpy(0xaf134000, 0xb57c3000, 4096)
07-28 12:30:55.284   314  6238 V AudioCache: write(0xb57c3000, 4096)
07-28 12:30:55.284   314  6238 V AudioCache: memcpy(0xaf135000, 0xb57c3000, 4096)
07-28 12:30:55.285   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-28 12:30:55.285   314  6238 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 12:30:55.285   314  6238 V AwesomePlayer: postAudioEOS() 
07-28 12:30:55.285   314  6238 V AudioCache: write(0xb57c3000, 280)
07-28 12:30:55.285   314  6238 V AudioCache: memcpy(0xaf136000, 0xb57c3000, 280)
07-28 12:30:55.286   314  6235 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-28 12:30:55.286   314  6235 V AwesomePlayer: onStreamDone
07-28 12:30:55.286   314  6235 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-28 12:30:55.286   314  6235 V AudioCache: notify(0xb1005040, 2, 0, 0)
07-28 12:30:55.286   314  6235 V AudioCache: playback complete
07-28 12:30:55.286   314  6235 V AwesomePlayer: pause_l() 
07-28 12:30:55.286   314  1371 V AudioCache: wait - success
07-28 12:30:55.286   314  6235 V AudioCache: notify(0xb1005040, 7, 0, 0)
07-28 12:30:55.286   314  6235 V AudioCache: ignored
07-28 12:30:55.286   314  1371 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-28 12:30:55.286   314  6235 V AwesomePlayer: cancelPlayerEvents
07-28 12:30:55.286   314  6235 D AudioPlayer: Pause Playback at 1068125
07-28 12:30:55.287   314  1371 V AwesomePlayer: reset_l() 
07-28 12:30:55.287   314  1371 V AudioCache: notify(0xb1005040, 8, 0, 0)
07-28 12:30:55.287   314  1371 V AudioCache: ignored
07-28 12:30:55.287   314  1371 V AwesomePlayer: cancelPlayerEvents
07-28 12:30:55.287   314  1371 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-28 12:30:55.287   314  1371 V OMX,Codec: [OMX.google.vorbis.decoder] stop mState=4
07-28 12:30:55.287   314  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-28 12:30:55.287   314  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-28 12:30:55.287   314  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:30:55.287   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:30:55.287   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:30:55.287   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-28 12:30:55.287   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
07-28 12:30:55.287   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-28 12:30:55.287   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
07-28 12:30:55.287   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-28 12:30:55.288   314  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:30:55.288   314  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-28 12:30:55.288   314  6237 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-28 12:30:55.288   314  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:30:55.288   314  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-28 12:30:55.288   314  1371 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-28 12:30:55.289   314  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-28 12:30:55.289   314  1371 D AudioPlayer: AudioPlayer releasing audio source
07-28 12:30:55.289   314  1371 D AudioPlayer: AudioPlayer done releasing audio source
07-28 12:30:55.289   314  1371 V AwesomePlayer: reset_l() 
07-28 12:30:55.289   314  1371 V AwesomePlayer: cancelPlayerEvents
,07-28 12:30:55.289   314  1371 V AwesomePlayer: ~AwesomePlayer call
07-28 12:30:55.289   314  1371 V AwesomePlayer: reset_l() 
07-28 12:30:55.289   314  1371 V AwesomePlayer: cancelPlayerEvents
07-28 12:30:55.290  6153  6234 V SoundPool: close(31)
07-28 12:30:55.290  6153  6234 V SoundPool: pointer = 0x9ffca000, size = 205080, sampleRate = 48000, numChannels = 2
07-28 12:30:55.291   314  2161 V AudioFlinger: 3773 died, releasing its sessions
07-28 12:30:55.291   314  2161 V AudioFlinger:  pid 1839 @ 0
07-28 12:30:55.291   314  2161 V AudioFlinger:  pid 3146 @ 1
07-28 12:30:55.291   314  2161 V AudioFlinger:  pid 3146 @ 2
07-28 12:30:55.292  6108  6108 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,07-28 12:30:55.326  1036  1560 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:30:55.345  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,07-28 12:30:55.346  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-28 12:30:55.357  1036  1890 I ActivityManager: Process com.android.bluetooth (pid 3773) has died
,07-28 12:30:55.357  1036  1890 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
07-28 12:30:55.360  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:30:55.362  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5416
07-28 12:30:55.367  6108  6108 D BluetoothPermissionRequest: onReceive
07-28 12:30:55.370  6108  6108 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,07-28 12:30:55.370  6108  6108 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-28 12:30:55.372  6108  6108 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:30:55.391  4376  6241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,07-28 12:30:55.417  1036  1757 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6245 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-28 12:30:55.420   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 201us total 10.838ms
07-28 12:30:55.430   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 201us total 9.563ms
07-28 12:30:55.439   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 9.500ms
,07-28 12:30:55.463  6245  6245 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-28 12:30:55.463  6245  6245 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:30:55.463  6245  6245 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-28 12:30:55.463  6245  6245 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:30:55.478  6245  6245 D BluetoothAdapterApp: Loading JNI Library
,07-28 12:30:55.499  5743  5743 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-28 12:30:55.506  6245  6245 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@15d7be41 Instance Count = 1
07-28 12:30:55.510  6245  6245 D BluetoothAdapterApp: onCreate
,07-28 12:30:55.524  6245  6245 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,07-28 12:30:55.524  6245  6245 D ProfileConfigQcom: Adding HeadsetService
07-28 12:30:55.524  6245  6245 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-28 12:30:55.524  6245  6245 D ProfileConfigQcom: Adding A2dpService
07-28 12:30:55.524  6245  6245 D ProfileConfigQcom: [BTUI] HidService is supported
07-28 12:30:55.525  6245  6245 D ProfileConfigQcom: Adding HidService
07-28 12:30:55.525  6245  6245 D ProfileConfigQcom: [BTUI] HealthService is supported
07-28 12:30:55.525  6245  6245 D ProfileConfigQcom: Adding HealthService
07-28 12:30:55.525  6245  6245 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-28 12:30:55.526  6245  6245 D ProfileConfigQcom: [BTUI] PanService is supported
07-28 12:30:55.526  6245  6245 D ProfileConfigQcom: Adding PanService
07-28 12:30:55.526  6245  6245 D ProfileConfigQcom: [BTUI] GattService is supported
07-28 12:30:55.526  6245  6245 D ProfileConfigQcom: Adding GattService
07-28 12:30:55.526  6245  6245 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-28 12:30:55.526  6245  6245 D ProfileConfigQcom: Adding BluetoothMapService
07-28 12:30:55.526  6245  6245 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-28 12:30:55.528  6245  6245 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-28 12:30:55.530  6108  6108 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 12:30:55.531  6245  6245 V LGMDMManagerInternal: Create singleton instance
07-28 12:30:55.553  6032  6032 I UEI.SmartControl: Supports setup maps: true
,07-28 12:30:55.556  6032  6032 D UEI.SmartControl: QS start statue = true Error code = 0
,07-28 12:30:55.556  6032  6032 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:30:55.556  6032  6032 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:30:55.556  6032  6032 I UEI.SmartControl: ### init IR Blaster...
07-28 12:30:55.559  6032  6032 D serial_port: Configuring serial port
07-28 12:30:55.559  6032  6032 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:30:55.559  6032  6032 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:30:55.559  6032  6032 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:30:55.560  6032  6032 I UEI.SmartControl: Get version...
07-28 12:30:55.576  6032  6267 D UEI.SmartControl: serial port data available: 21
07-28 12:30:55.577  6245  6245 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:30:55.580  6245  6245 V BluetoothSapReceiver: [BTUI] checkServiceStart
,07-28 12:30:55.580  6245  6245 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:30:55.580  6245  6245 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:30:55.581  6245  6245 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:55.581  6245  6245 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-28 12:30:55.594  6177  6177 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,07-28 12:30:55.602  6032  6032 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-28 12:30:55.602  6032  6032 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:30:55.602  6032  6032 I UEI.SmartControl: QS saving settings...
07-28 12:30:55.603  6032  6032 D UEI.SmartControl: IR Blaster version: 25672567
07-28 12:30:55.619  6032  6267 D UEI.SmartControl: serial port data available: 4
,07-28 12:30:55.651  6032  6271 I UEI.SmartControl: Device manager: loading config....
,07-28 12:30:55.653  6032  6271 D UEI.SmartControl: ----------- loading internal config...
07-28 12:30:55.654  6032  6032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 12:30:55.661  6032  6032 E UEI.SmartControl: Services init done
07-28 12:30:55.661  6032  6032 D UEI.SmartControl: QS Service init finished
07-28 12:30:55.663  6032  6032 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:30:55.663  6032  6032 D UEI.SmartControl: QS Service version code: 201091
07-28 12:30:55.665  6032  6032 D UEI.SmartControl: Service requested: Control
,07-28 12:30:55.669  6032  6271 E UEI.SmartControl: Loading SETTINGS...
07-28 12:30:55.670  6032  6032 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 12:30:55.674  6032  6032 D UEI.SmartControl: Internal service binding...
07-28 12:30:55.675  6153  6153 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-28 12:30:55.677  6032  6047 I UEI.SmartControl: ------ IControl API: 11
07-28 12:30:55.677  6032  6047 D UEI.SmartControl: File observer start...
,07-28 12:30:55.679  6032  6047 E UEI.SmartControl: IR Port is disabled: false
07-28 12:30:55.679  6032  6047 D UEI.SmartControl: Starting file observer...
07-28 12:30:55.679  6032  6047 I UEI.SmartControl: Registering callback...
07-28 12:30:55.681  6032  6048 I UEI.SmartControl: ------ IControl API: 19
07-28 12:30:55.684  6032  6048 I UEI.SmartControl: Registering Services Ready callback...
07-28 12:30:55.685  6032  6271 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-28 12:30:55.709  6032  6270 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-28 12:30:55.709  6032  6270 D UEI.SmartControl: -----service ready thread exits
07-28 12:30:55.712  6153  6168 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-28 12:30:55.714  6153  6232 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-28 12:30:55.714  6153  6232 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,07-28 12:30:55.715  6153  6153 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-28 12:30:55.716  6153  6153 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-28 12:30:55.716  6032  6047 I UEI.SmartControl: ------ IControl API: 8
07-28 12:30:55.720  6153  6153 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-28 12:30:55.720  6153  6153 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-28 12:30:55.721  6153  6153 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-28 12:30:55.722  6153  6153 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-28 12:30:55.723  6153  6153 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,07-28 12:30:55.724  6153  6153 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,07-28 12:30:55.725  6153  6153 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-28 12:30:55.730  6153  6153 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 12:30:55.731  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 12:30:55.732  6153  6153 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:30:55.733  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:30:55.734  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,07-28 12:30:55.735  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-28 12:30:55.736  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-28 12:30:55.737  6153  6153 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1469701855736]
07-28 12:30:55.740  6153  6153 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-28 12:30:55.742  1036  1936 I ActivityManager: Killing 5720:com.android.gallery3d/u0a27 (adj 15): empty #17
07-28 12:30:55.777  6153  6273 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-28 12:30:55.787  1036  1936 I ActivityManager: Killing 5687:com.lge.email/u0a23 (adj 15): empty #18
07-28 12:30:55.844  1036  1924 W libprocessgroup: failed to open /acct/uid_10027/pid_5720/cgroup.procs: No such file or directory
,07-28 12:30:55.851  1036  1051 W libprocessgroup: failed to open /acct/uid_10023/pid_5687/cgroup.procs: No such file or directory
,07-28 12:30:55.860  6153  6153 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,07-28 12:30:55.861  6153  6153 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,07-28 12:30:55.861  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-28 12:30:55.862  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-28 12:30:55.862  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-28 12:30:55.863  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-28 12:30:55.863  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-28 12:30:55.874  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,07-28 12:30:56.923  1036  2015 D WifiServiceImplEx: setWifiEnabled: true pid=5840, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,07-28 12:30:56.924  1036  2015 D WifiService: setWifiEnabled: true pid=5840, uid=10118
,07-28 12:30:56.924  1036  2015 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:30:56.954  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:30:56.955  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:30:56.955  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-28 12:30:56.956  1036  1522 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-28 12:30:56.956  1036  1522 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-28 12:30:56.959  1036  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-28 12:30:56.959  1036  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:30:56.959  1036  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-28 12:30:56.959  1036  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:30:56.959  1036  1522 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-28 12:30:56.959  1036  1522 E WifiHW  : unknown target_country: EU , set to default
07-28 12:30:56.959  1036  1522 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-28 12:30:56.959  1036  1522 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-28 12:30:56.959  1036  1522 I WifiUtil: gEnableBmps=1
07-28 12:30:57.556   310   894 D SoftapController: Softap fwReload - Ok
,07-28 12:30:57.560  1036  1108 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:30:57.563  1036  1522 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (600ms)
07-28 12:30:57.578   310   894 D CommandListener: Setting iface cfg
07-28 12:30:57.578   310   894 D CommandListener: Trying to bring down wlan0
,07-28 12:30:57.560  1036  1108 D Tethering: InitialState.processMessage what=4
07-28 12:30:57.583  1036  1108 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:30:57.584   310  6291 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-28 12:30:57.587   310   894 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:30:57.589  1036  1106 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-28 12:30:57.598  1036  1522 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-28 12:30:57.602  6292  6292 W wpa_supplicant: type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:30:57.612  1036  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:30:57.612  1036  1522 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:30:57.612  1036  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:30:57.615  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-28 12:30:57.616  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:57.612  6292  6292 W wpa_supplicant: type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:30:57.638  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:57.641  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-28 12:30:57.648  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:57.648  1036  1522 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 12:30:57.648  1036  1522 D WifiMonitor: connecting to supplicant
,07-28 12:30:57.669  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:30:57.670  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:30:57.670  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:30:57.670  6108  6108 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-28 12:30:57.674  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:30:57.676  6292  6292 I wpa_supplicant: Successfully initialized wpa_supplicant
07-28 12:30:57.677  6108  6108 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:30:57.677  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:30:57.677  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:30:57.678  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:30:57.678  6108  6108 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:30:57.678  6108  6108 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:30:57.682  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:30:57.682  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:30:57.682  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:30:57.682  6108  6108 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:30:57.683  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-28 12:30:57.684  6108  6108 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:30:57.684  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:30:57.684  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:30:57.684  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:30:57.684  6108  6108 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:30:57.684  6108  6108 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:30:57.700  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:30:57.704  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:57.709  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:57.711  6292  6292 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 12:30:57.711  6292  6292 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-28 12:30:57.719  6197  6310 W FormManager: Network not available. Please check & try again.
,07-28 12:30:57.728  6197  6311 V FormManager: Network unavailable.
07-28 12:30:57.730  6197  6311 V FormManager: Network unavailable.
07-28 12:30:57.820  6292  6292 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:30:57.831  6292  6292 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-28 12:30:57.837  6292  6292 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-28 12:30:57.840  1036  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,07-28 12:30:57.840  1036  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-28 12:30:57.840  6292  6292 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-28 12:30:57.841  1036  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:30:57.841  1036  1522 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:30:57.841  1036  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:30:57.842  1036  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:30:57.843  1036  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:30:57.844  1036  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:30:57.846  1036  1522 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-28 12:30:57.846  1036  1522 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-28 12:30:57.846  1036  6312 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-28 12:30:57.847  1036  6312 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 12:30:57.847  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:30:57.847  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 12:30:57.847  1036  1522 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-28 12:30:57.847  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-28 12:30:57.848  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-28 12:30:57.848  1036  1522 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-28 12:30:57.848  1036  6312 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:30:57.848  1036  1522 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-28 12:30:57.848  1036  6312 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:30:57.848  1036  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:30:57.848  1036  1522 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:30:57.848  1036  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:30:57.849  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:57.849  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:57.849  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:57.850  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:57.850  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:30:57.853  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:57.853  1927  1927 D WfdService: Waiting for WifiP2p enabling
,07-28 12:30:57.856  1036  1522 D WifiNative-wlan0: doBoolean: SET update_config 1
,07-28 12:30:57.857  1036  1522 D WifiNative-wlan0: SET update_config 1: returned true
07-28 12:30:57.857  1036  1522 D WifiConfigStore: Loading config and enabling all networks 
07-28 12:30:57.857  1036  1522 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-28 12:30:57.857  1036  1522 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-28 12:30:57.860  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-28 12:30:57.860  1036  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-28 12:30:57.862  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:57.862  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:30:57.862  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:57.862  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:57.862  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:57.862  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:57.862  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:57.862  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:57.862  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:57.862  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:57.862  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:57.865  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:57.865  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:30:57.865  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:57.865  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:57.865  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:57.865  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:57.865  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:57.865  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:57.865  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:57.865  1036  1522 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-28 12:30:57.865  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:57.865  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:57.875  1036  1522 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-28 12:30:57.875  1036  1522 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 12:30:57.877  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:30:57.880  1036  1522 D WifiStateMachine: enableVerboseLogging : level 2
07-28 12:30:57.880  1036  1522 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-28 12:30:57.880  1036  1522 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-28 12:30:57.881  1036  1522 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-28 12:30:57.881  1036  1522 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-28 12:30:57.881  1036  1522 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-28 12:30:57.882  1036  1522 D WifiNative-wlan0: SET model_name LG-D855: returned true
,07-28 12:30:57.882  1036  1522 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-28 12:30:57.882  1036  1522 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-28 12:30:57.882  1036  1522 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-28 12:30:57.883  1036  1522 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-28 12:30:57.883  1036  1522 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-28 12:30:57.883  1036  1522 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-28 12:30:57.883  1036  1522 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-28 12:30:57.884  1036  1522 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-28 12:30:57.884  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:30:57.886  1036  1522 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:30:57.886  1036  1522 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-28 12:30:57.886  1036  1522 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-28 12:30:57.886  1036  1522 D WifiNative-HAL: Setting external_sim to 1
07-28 12:30:57.887  1036  1522 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-28 12:30:57.887  1036  1522 D WifiNative-wlan0: SET external_sim 1: returned true
07-28 12:30:57.887  1036  1522 I WifiNative-HAL: startHal
07-28 12:30:57.887  1036  1522 D wifi    : setting scan oui 0xaf7c7a20
07-28 12:30:57.888  1036  1522 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:30:57.888  1036  1522 I WifiNative-HAL: startHal
07-28 12:30:57.888  1036  1522 D wifi    : setting scan oui 0xaf7c7a20
07-28 12:30:57.888  1036  1522 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-28 12:30:57.888  1927  1927 D WfdsService: Supplicant Connection state is changed : true
07-28 12:30:57.888  1036  1522 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-28 12:30:57.889  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-28 12:30:57.889  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-28 12:30:57.889  1927  2296 D WfdsService: Set the WFDS Monitor: true
07-28 12:30:57.889  1927  2296 D WfdsMonitor: WfdsMonitorThread create
07-28 12:30:57.889  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-28 12:30:57.889  1927  2296 D WfdsMonitor: WFDS Monitor is created and started
07-28 12:30:57.889  1927  2296 D WfdsService: WiFi: Supplicant connection re-established
07-28 12:30:57.889  1036  1522 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-28 12:30:57.889  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:30:57.889  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:30:57.890  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:30:57.890  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-28 12:30:57.890  1927  6317 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-28 12:30:57.890  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-28 12:30:57.890  1927  6317 E CtrlSupplicant: Succeed to open control connection
,07-28 12:30:57.891  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-28 12:30:57.891  1927  6317 E CtrlSupplicant: Succeed to open monitor connection
07-28 12:30:57.891  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:30:57.891  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:30:57.892  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:30:57.892  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:30:57.892  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:30:57.892  1927  6317 D WfdsMonitor: Supplicant connection established
07-28 12:30:57.892  1927  2296 D WfdsService: Connected to the supplicant for wfds
07-28 12:30:57.893  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:30:57.893  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-28 12:30:57.893  6292  6292 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-28 12:30:57.893  6197  6315 W FormManager: Network not available. Please check & try again.
07-28 12:30:57.894  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-28 12:30:57.894  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:30:57.894  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:30:57.894  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:30:57.895  1036  1522 E WifiNative: : [139,274,425 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-28 12:30:57.895  1036  1522 D WifiNative-wlan0: doBoolean: RECONNECT
07-28 12:30:57.896  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:57.896  1036  1522 D WifiNative-wlan0: RECONNECT: returned true
07-28 12:30:57.896  1036  1522 D WifiNative-wlan0: doString: [STATUS]
07-28 12:30:57.896  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:30:57.897  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 12:30:57.897  1036  1522 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:30:57.897  1036  1522 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:30:57.898  1036  1522 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:30:57.898  1036  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.900   310   894 D CommandListener: Setting iface cfg
07-28 12:30:57.900   310   894 D CommandListener: Trying to bring up p2p0
07-28 12:30:57.901  1036  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 12:30:57.901  1036  1521 D LGWifiP2pService: P2pEnablingState
07-28 12:30:57.901  1036  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.901  1036  1521 D LGWifiP2pService: P2p socket connection successful
07-28 12:30:57.901  1036  1521 D LGWifiP2pService: P2pEnabledState
07-28 12:30:57.902  1036  1521 D LGWifiP2pService: sending p2p connection changed broadcast
,07-28 12:30:57.904  1036  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-28 12:30:57.905  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-28 12:30:57.905  1927  1927 D WfdsService: WifiP2pState is changed : true
,07-28 12:30:57.905  1036  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-28 12:30:57.905  1927  2296 D WfdsService: Receive the WFDS_ENABLE Method
07-28 12:30:57.905  1036  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
07-28 12:30:57.905  1927  2296 D WfdsService: Set the WFDS Monitor: true
07-28 12:30:57.905  1927  2296 D WfdsService: Connected to the supplicant for wfds
07-28 12:30:57.905  1927  2296 D WfdsJNI : doCommand: WFDS_SET TRUE
07-28 12:30:57.905  6292  6292 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-28 12:30:57.906  1927  2296 D WfdsService: selectPreferredScanChannel [36]
07-28 12:30:57.906  1927  2296 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-28 12:30:57.906  1036  1521 D WifiNative-p2p0: SET device_name G3: returned true
07-28 12:30:57.906  1036  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-28 12:30:57.906  1036  1521 D LGWifiP2pService: before postfix = G3
07-28 12:30:57.906  1036  1521 D WifiServerServiceExt: postfix byte check : 2
07-28 12:30:57.906  1036  1521 D LGWifiP2pService: after postfix = G3
07-28 12:30:57.906  1036  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-28 12:30:57.906  1036  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-28 12:30:57.907  1036  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-28 12:30:57.907  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-28 12:30:57.907  1036  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-28 12:30:57.907  1036  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-28 12:30:57.907  1927  1927 D WfdsService: isConnected: false
07-28 12:30:57.907  1036  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-28 12:30:57.908  1036  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-28 12:30:57.908  1036  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-28 12:30:57.908  1036  1521 D WifiNative-HAL: p2pGetDeviceAddress
07-28 12:30:57.908  1036  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-28 12:30:57.909  1036  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-28 12:30:57.909  1036  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-28 12:30:57.909  1036  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
07-28 12:30:57.910  1036  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-28 12:30:57.910  1036  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-28 12:30:57.910  1036  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-28 12:30:57.910  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
07-28 12:30:57.910  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-28 12:30:57.911  1927  1927 D WfdsService: Update P2p Interface State: 3
07-28 12:30:57.911  1036  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-28 12:30:57.911  1036  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-28 12:30:57.911  6197  6316 V FormManager: Network unavailable.
07-28 12:30:57.912  1036  1522 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:30:57.912  1036  1522 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-28 12:30:57.913  1036  1522 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-28 12:30:57.913  1036  1522 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-28 12:30:57.914  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=139293  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:30:57.914  6197  6316 V FormManager: Network unavailable.
,07-28 12:30:57.918  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:30:57.918  1036  1036 D RttService: SCAN_AVAILABLE : 3
07-28 12:30:57.919  1036  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.919  1036  1541 I WifiNative-HAL: startHal
,07-28 12:30:57.919  1036  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.919  1036  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-28 12:30:57.920  1036  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-28 12:30:57.920  1036  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf7c7a20
07-28 12:30:57.920  1036  1541 D wifi    : failed to get capabilities : -3
07-28 12:30:57.920  1036  1541 E WifiScanningService: could not get scan capabilities
07-28 12:30:57.920  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:57.920  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:30:57.920  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:57.920  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:57.920  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:30:57.920  1036  1521 D LGWifiP2pService: InactiveState
07-28 12:30:57.921  1036  1521 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.921  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.921  1036  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-28 12:30:57.921  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:57.921  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:30:57.922  6292  6292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:30:57.922  1036  6312 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:30:57.922  1036  6312 E WifiMonitor: WifiMonitor:p2p0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:30:57.922  1036  6312 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:30:57.922  1036  6312 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,07-28 12:30:57.923  6292  6292 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:30:57.923  6292  6292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.923  1036  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-28 12:30:57.923  1036  1521 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.923  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.923  1036  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.923  1036  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.923  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.923  1036  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.923  6292  6292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.923  1036  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.924  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.924  1036  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.924  1036  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.924  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.924  1036  1521 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.924  1927  6317 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:30:57.924  1036  1036 E WifiServerServiceExt: No p2p device connected
07-28 12:30:57.924  1927  6317 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:30:57.924  1927  6317 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:30:57.925  1036  6312 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:30:57.925  1927  2296 W WfdsService: DefaultState - msg [9441285] is not handled
07-28 12:30:57.925  1036  6312 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.925  1036  6312 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.925  1036  6312 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.925  1036  6312 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:30:57.925  1036  6312 E WifiMonitor: WifiMonitor:p2p0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.925  1036  6312 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.925  1036  6312 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.927  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=139307  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:30:57.928  1036  1522 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-28 12:30:57.929  1036  1522 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-28 12:30:57.929  1036  1522 E WifiStateMachine:  DriverStartedState ,what:132106 1 0
07-28 12:30:57.930  1036  1522 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-28 12:30:57.930  6292  6292 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-28 12:30:57.930  1036  1522 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-28 12:30:57.931  1036  1522 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,07-28 12:30:57.931  1036  1522 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-28 12:30:57.931  1036  1522 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-28 12:30:57.931  6292  6292 E wpa_supplicant: disconnect_rssi_lvl: -100
07-28 12:30:57.932  1036  1522 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:30:57.932  1036  1522 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:30:57.933  1036  1522 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:30:57.933  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-28 12:30:57.933  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:30:57.934  6292  6292 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:30:57.934  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:30:57.934  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:30:57.934  1036  6312 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:30:57.934  1036  6312 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:30:57.935  6292  6292 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:30:57.935  6292  6292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.935  1036  6312 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:30:57.935  1036  6312 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.935  1036  6312 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.935  1036  6312 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.935  1927  6317 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:30:57.935  6292  6292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.936  1036  6312 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:30:57.936  1036  6312 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.936  1036  6312 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.936  1036  6312 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:30:57.936  1927  6317 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:30:57.936  1036  1522 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-28 12:30:57.937  1036  1521 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.937  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:57.937  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:30:57.937  1036  1522 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:30:57.937  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:30:57.937  1036  1522 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:30:57.938  1036  1522 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:30:57.938  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-28 12:30:57.938  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-28 12:30:57.938  6292  6292 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UN,KNOWN
07-28 12:30:57.938  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-28 12:30:57.938  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:30:57.938  1036  6312 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:30:57.938  1036  6312 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:30:57.939  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:30:57.939  1036  1522 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-28 12:30:57.939  1036  1522 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-28 12:30:57.939  1036  1522 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-28 12:30:57.939  1036  1522 D WifiNative-wlan0: doBoolean: SCAN
07-28 12:30:57.940  1036  1522 D WifiNative-wlan0: SCAN: returned false
07-28 12:30:57.940  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=139320  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:30:57.941  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:30:57.941  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=139321  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:30:57.942  1036  1522 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:30:57.942  1036  1522 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:30:57.943  1036  1522 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:30:57.943  1036  1522 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:30:57.943  1036  1522 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,07-28 12:30:57.944  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:57.944  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:30:57.945  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:30:57.945  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:57.946  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:30:57.947  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:57.948  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:30:57.948  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
07-28 12:30:57.948  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:30:57.948  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
07-28 12:30:57.952  6006  6006 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:30:57.952  6006  6006 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
07-28 12:30:57.952  4240  6319 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:30:57.957  6006  6006 V [BNRBootReceiver]: Boot Receiver Return
,07-28 12:30:57.958  4240  6320 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:30:57.959  4240  6320 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:30:57.961  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:30:57.967  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:30:57.972  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:57.979  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:30:57.979  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:30:57.980  6153  6153 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:30:57.984  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:30:57.990  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:30:57.997  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:58.003  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:30:58.003  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:30:58.004  6153  6153 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-28 12:30:58.524  6292  6292 E wpa_supplicant: USIM:  scard_init function
,07-28 12:30:58.534  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-28 12:30:58.534  1036  6312 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-28 12:30:58.534  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-28 12:30:58.535  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
07-28 12:30:58.535  1036  6312 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-28 12:30:58.537  6292  6292 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-28 12:30:58.540  1036  1522 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-28 12:30:58.541  1036  1522 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-28 12:30:58.541  1036  1522 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-28 12:30:58.541  1036  1522 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-28 12:30:58.541  1036  1522 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-28 12:30:58.547  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:30:58.547  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,07-28 12:30:58.568  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=139947  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-28 12:30:58.576  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:58.576  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:30:58.578  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:58.582  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:58.582  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:58.582  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,07-28 12:30:58.585  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=139965  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-28 12:30:58.587  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:30:58.587  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-28 12:30:58.595  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-28 12:30:58.609  6108  6108 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-28 12:30:58.614  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:30:58.624  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:30:58.632  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:58.640  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:30:58.640  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:30:58.641  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:30:58.656  6292  6292 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-28 12:30:58.663  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-28 12:30:58.663  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-28 12:30:58.663  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-28 12:30:58.663  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-28 12:30:58.664  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:30:58.664  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:30:58.668  6292  6292 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:30:58.668  6292  6292 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:30:58.671  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=140050  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,07-28 12:30:58.675  1036  1108 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-28 12:30:58.680  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:30:58.680  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:30:58.680  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-28 12:30:58.680  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:30:58.680  1036  6312 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:30:58.680  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-28 12:30:58.680  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:30:58.680  1036  6312 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:30:58.680  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:30:58.680  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:30:58.681  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=140061  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 12:30:58.684  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:30:58.684  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:30:58.684  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:30:58.684  6108  6108 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-28 12:30:58.688  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:30:58.688  6108  6108 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:30:58.689  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-28 12:30:58.689  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:30:58.689  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:30:58.689  6108  6108 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:30:58.689  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-28 12:30:58.689  6108  6108 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:30:58.691  1036  1522 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140071
07-28 12:30:58.694  1036  1522 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140073
07-28 12:30:58.694  1036  1522 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140073
07-28 12:30:58.694  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140074
07-28 12:30:58.695  1036  1522 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140074
07-28 12:30:58.695  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=140074  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,07-28 12:30:58.708  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:58.708  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:30:58.710  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:58.711  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:58.712  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:58.712  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,07-28 12:30:58.720  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=140100  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 12:30:58.721  1036  1522 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:30:58.721  1036  1522 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:30:58.721  1036  1522 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:30:58.721  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:30:58.722  1036  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:30:58.722  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=140101  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:30:58.722  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=140102  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:30:58.723  1036  1522 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140102
07-28 12:30:58.723  1036  1522 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140103
07-28 12:30:58.724  1036  1522 D WifiNative-wlan0: doString: [STATUS]
07-28 12:30:58.725  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:30:58.725  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,07-28 12:30:58.727  1036  1522 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:30:58.729  1036  1522 I WifiServiceExtension: setVHTCapabilityType  : false
07-28 12:30:58.733  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:30:58.739  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:58.739  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:58.739  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,07-28 12:30:58.741  1036  1522 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-28 12:30:58.742  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:58.742  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:30:58.743  1036  1522 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-28 12:30:58.749  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:58.749  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:58.749  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:30:58.752  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:58.752  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:58.752  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,07-28 12:30:58.768  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:30:58.778  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:58.778  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:30:58.779  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:58.782  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:58.782  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:30:58.784  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:58.792  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:30:58.794  1036  1522 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-28 12:30:58.795  1036  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:30:58.795  1036  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:30:58.796  1036  1529 D ConnectivityService: Got NetworkAgent Messenger
,07-28 12:30:58.796  1036  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-28 12:30:58.797  1036  1529 D ConnectivityService: NetworkAgent connected
07-28 12:30:58.797  1036  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:30:58.797  1036  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:30:58.800  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:58.804  1036  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:30:58.804  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:30:58.804  1036  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:30:58.804  1036  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:30:58.804  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:30:58.804  1036  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:30:58.804  1036  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:30:58.806  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:30:58.807  1036  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
,07-28 12:30:58.814   310   894 D CommandListener: Setting iface cfg
07-28 12:30:58.815  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:30:58.821  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:30:58.824  1036  1522 E WifiStateMachine: Start Dhcp Watchdog 1
,07-28 12:30:58.824  1036  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=140203  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:30:58.825  1036  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=140204  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:30:58.825  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=140204  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:30:58.825  1036  6347 D DhcpStateMachine: StoppedState
07-28 12:30:58.826  1036  6347 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:58.826  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:30:58.826  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-28 12:30:58.827  1036  6347 D DhcpStateMachine: WaitBeforeStartState
07-28 12:30:58.827  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:30:58.827  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-28 12:30:58.827  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,07-28 12:30:58.827  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-28 12:30:58.828  1036  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=140207  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:30:58.828  1036  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=140207  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:30:58.829  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=140208  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:30:58.829  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:58.835  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:30:58.835  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:30:58.835  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:30:58.835  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:823043603] from screen [on:0 period:823043603]
07-28 12:30:58.837  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:30:58.840  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:823043607]
07-28 12:30:58.840  1036  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-28 12:30:58.843  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:30:58.845  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:58.849  1036  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
07-28 12:30:58.849  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:58.852  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:30:58.852  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:30:58.853  1036  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:30:58.853  1036  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:30:58.853  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:30:58.854  1036  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:30:58.854  1036  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,07-28 12:30:58.859  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:30:58.859  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
07-28 12:30:58.859  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:30:58.859  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
07-28 12:30:58.859  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-28 12:30:58.859  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:30:58.860  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-28 12:30:58.860  1036  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-28 12:30:58.860  1036  1522 D WifiNative-wlan0: doBoolean: SET ps 0
07-28 12:30:58.861  1036  1522 D WifiNative-wlan0: SET ps 0: returned true
07-28 12:30:58.861  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-28 12:30:58.861  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:30:58.861  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-28 12:30:58.861  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:30:58.861  1036  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-28 12:30:58.861  1036  1522 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-28 12:30:58.861  1036  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e6934a3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:58.861  1036  1522 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:30:58.861  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e6934a3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:58.862  1036  1522 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:30:58.862  1036  1522 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
07-28 12:30:58.862  1036  6347 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:58.862  1036  6347 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-28 12:30:58.868  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:30:58.873  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,07-28 12:30:58.873  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:30:58.875  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:30:58.879  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:58.883  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:30:58.883  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:30:58.884  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:30:58.888  1036  1521 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:58.888  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:58.888  1036  1521 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:58.905  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:30:58.905  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:30:58.906  1036  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:30:58.906  1036  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:30:58.906  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,07-28 12:30:58.906  1036  1522 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:30:59.067  1036  6347 D DhcpStateMachine: DHCPV4 request on wlan0
,07-28 12:30:59.068  1036  6347 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-28 12:30:59.068  1036  6347 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-28 12:30:59.072  6351  6351 W dhcpcd  : type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:30:59.072  6351  6351 W dhcpcd  : type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:30:59.103  6351  6351 I dhcpcd  : version 5.5.6 starting
07-28 12:30:59.105  6351  6351 E dhcpcd  : get_duid: m
07-28 12:30:59.105  6351  6351 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-28 12:30:59.105  6351  6351 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,07-28 12:30:59.210  6351  6351 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:30:59.211  6351  6351 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:30:59.211  6351  6351 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,07-28 12:30:59.215  6351  6351 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-28 12:30:59.215  6351  6351 D dhcpcd  : wlan0: sending REQUEST (xid 0x3a518592), next in 4.44 seconds
07-28 12:30:59.228  6351  6351 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-28 12:30:59.237  6351  6351 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-28 12:30:59.237  6351  6351 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-28 12:30:59.240  6351  6351 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-28 12:30:59.240  6351  6351 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-28 12:30:59.241  6351  6351 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:30:59.241  6351  6351 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:30:59.241  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:30:59.242  6351  6351 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:30:59.242  6351  6351 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-28 12:30:59.243  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:30:59.244  1036  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:30:59.245  1036  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:30:59.247  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:30:59.248  1036  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 12:30:59.251  1036  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,07-28 12:30:59.676  1036  6347 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-28 12:30:59.686  1036  6347 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-28 12:30:59.686  1036  6347 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:30:59.687  1036  6347 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-28 12:30:59.688  1036  6347 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-28 12:30:59.688  1036  6347 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:30:59.688  1036  6347 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
07-28 12:30:59.691  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:30:59.693  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:30:59.696  1036  6347 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,07-28 12:30:59.701  1036  1521 D LGWifiP2pService: InactiveState{ when=-9ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:59.702  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:59.702  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:30:59.704  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:30:59.706  1036  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:30:59.707  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-28 12:30:59.711  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,07-28 12:30:59.714  1036  6347 D DhcpStateMachine: RunningState
07-28 12:30:59.714  1036  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-28 12:30:59.715  1036  1522 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:30:59.729  1036  1522 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:30:59.730  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:30:59.731  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:30:59.731  1036  1522 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,07-28 12:30:59.736  1036  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-28 12:30:59.736  1036  1529 D ConnectivityService: ignoring duplicate network state non-change
07-28 12:30:59.752  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:59.752  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-28 12:30:59.764  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:59.764  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:59.764  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,07-28 12:30:59.770  1036  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-28 12:30:59.771  1036  1529 D ConnectivityService: Adding iface wlan0 to network 100
07-28 12:30:59.776  1036  1522 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-28 12:30:59.794  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:59.794  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:59.794  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,07-28 12:30:59.808  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:30:59.827  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,07-28 12:30:59.837  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:30:59.850  1036  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 12:30:59.850  1036  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,07-28 12:30:59.854  1036  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
07-28 12:30:59.855  1036  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
07-28 12:30:59.856  1036  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-28 12:30:59.856  1036  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
07-28 12:30:59.856  1036  1529 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
07-28 12:30:59.866  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
,07-28 12:30:59.867  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:59.867  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:59.867  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:30:59.871  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:59.871  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:30:59.872  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:30:59.873  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:59.876  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:59.876  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:59.877  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:30:59.878  1036  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:30:59.878  1036  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-28 12:30:59.878  1036  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-28 12:30:59.879  1036  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-28 12:30:59.879  1036  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:30:59.879  1036  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:30:59.879  1036  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:30:59.879  1036  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:30:59.879  1036  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-28 12:30:59.880  1036  1529 D ConnectivityService: currentScore = 0, newScore = 20
07-28 12:30:59.880  1036  1529 D ConnectivityService:    accepting network in place of null
07-28 12:30:59.880  1036  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:30:59.880  1036  1522 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:30:59.880  1036  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:30:59.880  1036  1529 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
07-28 12:30:59.881  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:30:59.881  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETH,ERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:30:59.881  1036  6341 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:59.881  1036  6341 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-28 12:30:59.882  1036  6341 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:59.882  1036  6341 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,07-28 12:30:59.892   310  6407 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-28 12:30:59.895  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:59.895  1036  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 12:30:59.895  1036  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-28 12:30:59.895  1036  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:30:59.895  1036  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:30:59.896  1036  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-28 12:30:59.896  1036  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-28 12:30:59.897  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:30:59.898  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:59.899   310  6408 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-28 12:30:59.899   310  6408 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,07-28 12:30:59.901  1036  1529 D ConnectivityService: validation of new default Network = false
07-28 12:30:59.901  1036  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-28 12:30:59.901  1036  1529 D DSQN    : enableDataServiceNotify 
07-28 12:30:59.901  1036  1529 D DSQN    : start dsqn bin
07-28 12:30:59.904  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-28 12:30:59.905  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:30:59.905  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:30:59.905  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:30:59.905  1036  1036 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
07-28 12:30:59.910  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:59.910  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:30:59.910  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:59.914   310  6410 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-28 12:30:59.914   310  6410 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,07-28 12:30:59.919  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:30:59.928  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:59.938  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:30:59.938  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:30:59.941  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:30:59.942  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:59.943  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:30:59.945  1036  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-28 12:30:59.945  1036  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:30:59.945  1036  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:30:59.945  1036  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:30:59.945  1588  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:30:59.932  6411  6411 W dsqn    : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:30:59.932  6411  6411 W dsqn    : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:30:59.950  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:30:59.953  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:30:59.958  1036  1966 D WifiServiceImplEx: setWifiEnabled: false pid=5840, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:30:59.958  1036  1966 D WifiService: setWifiEnabled: false pid=5840, uid=10118
07-28 12:30:59.958  1036  1966 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:30:59.958   310  6408 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
07-28 12:30:59.959  6411  6411 E DSQN    : DSQN ssw
07-28 12:30:59.960   310  6407 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-28 12:30:59.962  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:30:59.965   310  6410 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
07-28 12:30:59.966  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:30:59.971  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:30:59.971  1036  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:30:59.971  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:30:59.971  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:30:59.972  1036  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-28 12:30:59.972  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:30:59.972  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:30:59.972  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-28 12:30:59.972  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:30:59.973  1036  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:30:59.973  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:30:59.973  1036  1522 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 12:30:59.973  1036  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:30:59.973  1036  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:30:59.974  1036  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:30:59.974  1036  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,07-28 12:30:59.976  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:30:59.979  6091  6091 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:30:59.980  1036  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:30:59.980  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:30:59.981  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:30:59.981  1036  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:59.981  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:59.981  1036  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:30:59.981  1036  1522 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:30:59.981  1036  1522 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:30:59.982  1036  6347 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:59.984   310   894 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:30:59.985  1036  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,07-28 12:30:59.989  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:30:59.992  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:30:59.996  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:00.000  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:31:00.001  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:00.002  6153  6153 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:31:00.002  6153  6153 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:31:00.003  6153  6153 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:31:00.006  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:00.010  6091  6091 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:31:00.010  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:31:00.013  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:31:00.013  1036  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-28 12:31:00.013  1036  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,07-28 12:31:00.016  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-28 12:31:00.016  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:00.016  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
,07-28 12:31:00.016  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:00.016  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:31:00.017  1036  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:00.017  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:00.017  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:31:00.017  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:00.017  1036  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:00.017  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:00.017  1036  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@178ce719
07-28 12:31:00.018  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:00.020  1036  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:00.021  1036  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:00.021  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:00.021  1036  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:00.022  1036  1521 D LGWifiP2pService: P2pDisablingState
07-28 12:31:00.022  1036  1521 D LGWifiP2pService: P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:00.022  1036  1521 D LGWifiP2pService: p2p socket connection lost
07-28 12:31:00.022  1036  1521 D LGWifiP2pService: P2pDisabledState
07-28 12:31:00.022  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-28 12:31:00.022  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:00.022  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:00.022  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:31:00.022  1036  1522 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 12:31:00.022  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:31:00.023  1036  1036 D RttService: SCAN_AVAILABLE : 1
07-28 12:31:00.023  1036  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:00.023  1036  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-28 12:31:00.023  1036  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:00.023  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:31:00.023  1036  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:00.023  1036  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:00.023  6292  6292 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:31:00.023  1036  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:31:00.023  1036  1522 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:31:00.024  1036  1522 D WifiNative-wlan0: SET ps 1: returned true
0,7-28 12:31:00.024  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:31:00.025  1927  1927 D WfdsService: WifiP2pState is changed : false
07-28 12:31:00.025  1927  2296 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-28 12:31:00.025  1927  2296 D WfdsService: Set the WFDS Monitor: false
,07-28 12:31:00.026  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:31:00.026  1927  2296 D WfdsService: STATE : WfdsDisabledState - enter
07-28 12:31:00.026  1927  6317 D CtrlSupplicant: Received on exit socket, terminate
07-28 12:31:00.026  1927  6317 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-28 12:31:00.026  1927  6317 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-28 12:31:00.026  1927  6317 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-28 12:31:00.027  1927  2296 W WfdsService: DefaultState - msg [9445378] is not handled
07-28 12:31:00.028  1927  2297 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-28 12:31:00.032  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:00.038  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:31:00.038  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:00.038  6153  6153 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:31:00.039  6153  6153 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:31:00.039  6153  6153 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:31:00.039  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:00.039  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:31:00.040  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:00.043  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:00.046  6091  6091 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:31:00.046  6091  6091 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:31:00.046  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:31:00.049  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:31:00.050   310   894 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:31:00.050  1036  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-28 12:31:00.050  1036  1529 D DSQN    : disableDataServiceNotify
07-28 12:31:00.050  1036  1529 D DSQN    : stop dsqn bin
07-28 12:31:00.051  1036  1522 D WifiNative-p2p0: doBoolean: TERMINATE
07-28 12:31:00.052  1036  1522 D WifiNative-p2p0: TERMINATE: returned true
07-28 12:31:00.052  1036  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:31:00.052  1036  1522 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:31:00.052  1036  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:31:00.053  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-28 12:31:00.053  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:00.053  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:00.053  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:31:00.054  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-28 12:31:00.054  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-28 12:31:00.054  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:31:00.054  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-28 12:31:00.056  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:31:00.056  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:31:00.056  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:31:00.056  1036  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-28 12:31:00.056  1036  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:00.056  1036  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:00.056  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth L,E multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:00.056  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:31:00.057  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:31:00.057  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:31:00.057  1036  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:00.057  1036  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-28 12:31:00.057  1588  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 12:31:00.058  1036  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-28 12:31:00.058  1036  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-28 12:31:00.058  1036  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:31:00.058  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:00.059  1036  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:31:00.060  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:31:00.060  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:31:00.060  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:31:00.060  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:31:00.060  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-28 12:31:00.060  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
07-28 12:31:00.060  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-28 12:31:00.060  1036  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:00.060  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
07-28 12:31:00.060  1036  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:31:00.060  1036  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:00.060  1036  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Ca,pabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:00.061  1036  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:00.061  1036  1529 D NetworkManagementService: Removing idletimer
07-28 12:31:00.061  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:00.061  1036  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:00.061  1036  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-28 12:31:00.061  1036  1522 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:00.061  1036  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:31:00.061  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
07-28 12:31:00.061  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-28 12:31:00.062  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:31:00.062  1036  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:31:00.062  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
07-28 12:31:00.062  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:31:00.062  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:31:00.062  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:31:00.062  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:31:00.063  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:31:00.063  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:31:00.066  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:00.068  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:00.071  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:00.071  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:00.077  6153  6153 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:31:00.079  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:00.081  6091  6091 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:31:00.081  6091  6091 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:31:00.081  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:31:00.084  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:31:00.088  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:00.092  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:00.092  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:00.094  6153  6153 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:31:00.097  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:00.098  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:31:00.099  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:00.099  6091  6091 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:31:00.099  6091  6091 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:31:00.099  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:31:00.099  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:00.100  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,07-28 12:31:00.102  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:31:00.105  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:00.108  6292  6292 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 12:31:00.108  6292  6292 I wpa_supplicant: monitor socket send errors count : 1
07-28 12:31:00.108  6292  6292 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-4\x00 that cannot receive messages
07-28 12:31:00.109  1036  6312 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-28 12:31:00.109  1036  6312 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 12:31:00.111  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:00.111  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:31:00.112  6153  6153 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:31:00.118  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:31:00.122  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:31:00.124  6197  6424 W FormManager: Network not available. Please check & try again.
07-28 12:31:00.128  6197  6425 V FormManager: Network unavailable.
07-28 12:31:00.131  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:00.131  6197  6425 V FormManager: Network unavailable.
07-28 12:31:00.133  6292  6292 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:31:00.134  6292  6292 W wpa_supplicant: USIM:  scard_deinit function
07-28 12:31:00.134  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-28 12:31:00.134  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:31:00.135  1036  6312 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:31:00.135  1036  6312 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-28 12:31:00.135  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,07-28 12:31:00.135  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:31:00.136  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:31:00.136  1036  1522 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=141516
07-28 12:31:00.137  1036  1108 D Tethering: InitialState.processMessage what=4
07-28 12:31:00.137  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:00.137  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:00.138  1036  1522 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=141518
,07-28 12:31:00.139  1036  1522 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=141518  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:31:00.139  1036  1522 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=141519  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:31:00.140  1036  1108 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:31:00.141  1036  1522 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:31:00.141  1036  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:31:00.152  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:31:00.152  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:31:00.152  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:31:00.152  6108  6108 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-28 12:31:00.154  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:31:00.154  6108  6108 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:31:00.154  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:31:00.154  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:31:00.155  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:31:00.155  6108  6108 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:31:00.155  6108  6108 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:31:00.178  6292  6292 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 12:31:00.179  1036  6312 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-28 12:31:00.179  1036  6312 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-TERMINATING 
07-28 12:31:00.179  1036  6312 D WifiMonitor: Disconnecting from the supplicant, no more events
,07-28 12:31:00.181  1036  1522 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 37 0
07-28 12:31:00.189  1036  6347 D DhcpStateMachine: StoppedState
07-28 12:31:00.189  1036  6347 D DhcpStateMachine: StoppedState{ when=-166ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:00.287  1927  1927 D WfdsService: Supplicant Connection state is changed : false
,07-28 12:31:00.288  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-28 12:31:00.288  1927  2296 D WfdsService: Set the WFDS Monitor: false
07-28 12:31:00.288  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:31:00.294  1036  1522 D WifiOffDelayIfNotUsed: stopMonitoring
07-28 12:31:00.294  1036  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:31:00.294  1036  1522 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:31:00.294  1036  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:31:00.296  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:31:00.297  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:31:00.299  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:00.301  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,07-28 12:31:00.302  2494  2494 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:00.303  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-28 12:31:00.306  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:31:00.306  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
07-28 12:31:00.306  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:00.306  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:00.306  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:00.306  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:31:00.306  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:00.306  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:00.306  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:31:00.307  1036  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-28 12:31:00.307  1036  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-28 12:31:00.310  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:31:00.310  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:00.310  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:00.310  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:00.310  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:00.310  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:31:00.310  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:00.310  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:00.310  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:31:00.314  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:31:00.319  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:31:00.326  4240  6426 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:31:00.328  4240  6427 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,07-28 12:31:00.328  4240  6427 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:31:00.339  6091  6091 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-28 12:31:00.339  6091  6091 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:31:00.339  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:31:00.343  6197  6429 W FormManager: Network not available. Please check & try again.
,07-28 12:31:00.349  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:31:00.352  6197  6430 V FormManager: Network unavailable.
,07-28 12:31:00.355  6197  6430 V FormManager: Network unavailable.
07-28 12:31:00.356  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:00.364  1036  1366 D PowerManagerServiceEx: acquireWakeLockInternal: lock=461972835, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
07-28 12:31:00.382  6153  6153 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
07-28 12:31:00.383  6153  6153 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5416
,07-28 12:31:00.406  2608  2608 D [Concierge]Service: onStartCommand(). Type : 9
,07-28 12:31:00.434  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=461972835 [*alarm*], flags=0x0
,07-28 12:31:00.500  1036  1522 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
,07-28 12:31:00.500  1036  1522 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,07-28 12:31:00.652  6032  6272 D UEI.SmartControl: Internal timer expired: 2
,07-28 12:31:00.653  6032  6272 D UEI.SmartControl: unbind internal service
,07-28 12:31:00.899  6032  6269 D serial_port: close(fd = 24)
,07-28 12:31:00.910  6032  6269 I UEI.SmartControl: Serial port is closed.
,07-28 12:31:01.851  1036  1522 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:823046618] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-28 12:31:01.853  1036  1522 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:823046621] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-28 12:31:02.899  1036  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:31:02.913  1036  1108 D Tethering: MasterInitialState.processMessage what=3
07-28 12:31:02.928  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:02.931  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:02.934  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:02.939  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-28 12:31:02.943  3627  3648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:31:02.956  5281  5281 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 12:31:02.972  1036  1966 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:02.973  1036  1966 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-28 12:31:03.004  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:31:03.004  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:31:03.004  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,07-28 12:31:03.006  1036  1108 D BluetoothManagerService: Message: 1
07-28 12:31:03.006  1036  1108 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-28 12:31:03.037  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:31:03.062  1036  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:31:03.072  1036  1108 D BluetoothManagerService: Message: 20
07-28 12:31:03.072  1036  1108 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a2767f7:true
07-28 12:31:03.073  6245  6245 D BluetoothAdapterState: make
07-28 12:31:03.080  6245  6245 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-28 12:31:03.080  6245  6245 I bluedroid-qcom: init
07-28 12:31:03.080  6245  6455 I BluetoothAdapterState: Entering OffState
07-28 12:31:03.081  6245  6245 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:31:03.082  6245  6245 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:31:03.082  6245  6245 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:31:03.082  6245  6245 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 12:31:03.082  6245  6245 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
,07-28 12:31:03.084  6245  6245 I bluedroid-qcom: get_profile_interface socket
07-28 12:31:03.084  6245  6245 I bluedroid-qcom: get_profile_interface map_client
07-28 12:31:03.072  6460  6460 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:03.087  6245  6461 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-28 12:31:03.082  6460  6460 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:03.093  6245  6461 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-28 12:31:03.094  6460  6460 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-28 12:31:03.094  6460  6460 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-28 12:31:03.094  6460  6460 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,07-28 12:31:03.101  6460  6460 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-28 12:31:03.108  6460  6460 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-28 12:31:03.108  6460  6460 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-28 12:31:03.110   339   339 I art     : Background concurrent mark sweep GC freed 89(3KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 10.488ms total 31.378ms
,07-28 12:31:03.124  1036  1763 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6464 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
07-28 12:31:03.126  1036  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:03.127  1036  1108 D Tethering: MasterInitialState.processMessage what=3
07-28 12:31:03.129  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:03.129  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:03.131  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-28 12:31:03.131  1036  1108 D Tethering: MasterInitialState.processMessage what=3
07-28 12:31:03.131  1036  1108 D BluetoothManagerService: Message: 40
07-28 12:31:03.131  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-28 12:31:03.131  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:03.132  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:03.134  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:31:03.134  6245  6461 D BluetoothAdapterProperties: Name is: G3
07-28 12:31:03.134  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:31:03.134  6245  6263 I bluedroid-qcom: config_hci_snoop_log
07-28 12:31:03.135  1036  1108 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-28 12:31:03.135  1036  1108 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-28 12:31:03.141  6245  6455 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-28 12:31:03.142  6245  6455 D BluetoothAdapterProperties: Setting state to 11
07-28 12:31:03.142  6245  6455 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 12:31:03.142  5281  5281 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-28 12:31:03.143  1036  1108 D BluetoothManagerService: Message: 60
07-28 12:31:03.143  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-28 12:31:03.143  1036  1108 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-28 12:31:03.143  6245  6455 I LGBluetoothServiceJni: classInitNative: succeeds
07-28 12:31:03.146  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:03.146  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:31:03.147  6245  6455 D BluetoothBondStateMachine: make
07-28 12:31:03.148  6108  6108 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,07-28 12:31:03.150  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:03.153  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:03.153  6245  6455 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:03.153  6245  6455 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-28 12:31:03.153  6245  6455 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:03.153  6245  6455 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-28 12:31:03.154  6245  6479 I BluetoothBondStateMachine: StableState(): Entering Off State
07-28 12:31:03.154  6245  6455 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-28 12:31:03.155  6245  6245 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:31:03.156  6245  6245 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:03.156  6245  6245 V BluetoothPbapReceiver: ***********state = 11
07-28 12:31:03.158  6245  6455 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:31:03.159  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:31:03.161  5281  5281 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-28 12:31:03.164  6245  6455 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:31:03.165  6245  6245 D HeadsetService: Received start request. Starting profile...
07-28 12:31:03.165  6245  6245 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:31:03.165  6245  6245 D LGBluetoothHfpAdapter: Version 1.6
07-28 12:31:03.168  6245  6245 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:31:03.168  6245  6245 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:31:03.169  6245  6245 D HeadsetStateMachine: make
07-28 12:31:03.176  6245  6455 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:31:03.181  6245  6455 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:31:03.185  6245  6455 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:31:03.190  6108  6108 D BluetoothPermissionRequest: onReceive
07-28 12:31:03.190  6245  6455 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:31:03.196  6245  6245 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:31:03.196  6245  6245 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:31:03.199  6108  6108 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:31:03.200  6245  6245 D HeadsetStateMachine: max_hf_connections = 1
07-28 12:31:03.200  6245  6245 I bluedroid-qcom: get_profile_interface handsfree
,07-28 12:31:03.201  6245  6245 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-28 12:31:03.201  6245  6455 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:31:03.202   314  2161 V AudioPolicyService: registerClient() client 0xb04103c0, uid 1002
07-28 12:31:03.202   314   314 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:31:03.202   314   314 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:31:03.202   314   314 V AudioPolicyManagerEx: getOutput() returns output 2
,07-28 12:31:03.202  6245  6245 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 12:31:03.203   314  1371 V AudioFlinger: registerClient() client 0xb16ded48, pid 6245
07-28 12:31:03.203   314  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:03.203   314  1364 V AudioSystem: ioConfigChanged() opening already existing output! 2
,07-28 12:31:03.203  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:03.203  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:31:03.203  6245  6245 V ToneGenerator: Create Track: 0xb4928a80
07-28 12:31:03.203  6245  6245 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-28 12:31:03.203  6245  6245 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-28 12:31:03.203   314   314 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:31:03.203   314   314 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:31:03.203   314   314 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:31:03.203   314   314 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:31:03.203  6245  6245 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 12:31:03.204  1588  2088 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:03.204  1588  2088 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:31:03.204   314  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:03.204   314  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:31:03.204  1839  1854 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:03.204  1839  1854 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:31:03.204  1839  1854 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:03.204  1839  1854 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:31:03.204  3146  3167 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:03.204  3146  3167 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:31:03.204  3146  3167 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:03.204  3146  3167 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:31:03.204  6245  6262 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:03.204  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:03.204  6245  6262 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-28 12:31:03.204  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:31:03.204  6245  6262 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:03.204  6245  6262 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-28 12:31:03.204  1588  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:03.204  1588  1606 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:31:03.205   314  2161 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:31:03.205   314   314 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:31:03.205   314   314 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-28 12:31:03.205   314   314 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:31:03.205   314   314 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:31:03.205  6245  6245 V AudioSystem: getLatency() output 2, latency 50
07-28 12:31:03.205  6245  6245 V AudioSystem: getFrameCount() output 2, frameCount 960
07-28 12:31:03.205  6245  6245 V AudioTrack: createTrack_l() output 2 afLatency 50
07-28 12:31:03.206   314  1370 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:31:03.206   314  1370 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:31:03.206   314  1370 V AudioFlinger: [MABL_A,udioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:31:03.206   314  1370 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:31:03.206   314  1370 V AudioFlinger: createTrack() lSessionId: 22
07-28 12:31:03.206  6245  6245 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-28 12:31:03.207   314  1371 V AudioFlinger: acquiring 22 from 6245, for 6245
07-28 12:31:03.207   314  1371 V AudioFlinger:  added new entry for 22
07-28 12:31:03.207  6245  6245 V ToneGenerator: ToneGenerator INIT OK, time: 144599
07-28 12:31:03.207  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:03.207  6245  6484 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-28 12:31:03.207  6245  6484 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:31:03.207  6245  6484 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:31:03.207  6245  6484 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-28 12:31:03.208   314  2161 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6245
07-28 12:31:03.208   314  2161 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-28 12:31:03.208   314  2161 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-28 12:31:03.208  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:03.208   314  2161 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-28 12:31:03.208   314  2161 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-28 12:31:03.208   314  2161 V voice   : voice_set_parameters: exit with code(0)
07-28 12:31:03.208   314  2161 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-28 12:31:03.208   314  2161 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-28 12:31:03.208   314  2161 V msm8974_platform: platform_set_parameters: exit with code(0)
07-28 12:31:03.208   314  2161 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-28 12:31:03.208   314  2161 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-28 12:31:03.208   314  2161 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-28 12:31:03.209  6245  6484 V ToneGenerator: ToneGenerator destructor
07-28 12:31:03.209  6245  6484 V ToneGenerator: stopTone
07-28 12:31:03.209  6245  6484 V ToneGenerator: Delete Track: 0xb4928a80
07-28 12:31:03.209  6245  6484 V AudioTrack: ~AudioTrack, releasing session id from 6245 on behalf of 6245
07-28 12:31:03.209   314  1371 V AudioPolicyService: AudioCommandThread() adding release output 2
07-28 12:31:03.209   314  1371 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-28 12:31:03.209   314  1371 V AudioFlinger: PlaybackThread::Track destructor
07-28 12:31:03.209   314  1126 V AudioPolicyService: AudioCommandThread() waking up
07-28 12:31:03.209   314  1371 V AudioFlinger: removeClient_l() pid 6245, calling pid 314
07-28 12:31:03.209  6245  6245 D A2dpService: Received start request. Starting profile...
07-28 12:31:03.209   314  1126 V AudioPolicyService: AudioCommandThread() processing release output 2
07-28 12:31:03.210   314  1126 V AudioPolicyManager: releaseOutput() 2
07-28 12:31:03.210   314  1126 V AudioPolicyService: AudioCommandThread() going to sleep
07-28 12:31:03.210   314  1371 V AudioFlinger: releasing 22 from 6245 for 6245
07-28 12:31:03.210   314  1371 V AudioFlinger:  decremented refcount to 0
07-28 12:31:03.210   314  1371 V AudioFlinger: purging stale effects
07-28 12:31:03.210  6245  6245 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 12:31:03.211  6245  6245 V Avrcp   : make
07-28 12:31:03.211  6245  6245 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-28 12:31:03.211  6245  6245 I bluedroid-qcom: get_profile_interface avrcp
07-28 12:31:03.217  1036  1966 W Process : Unable to open /proc/6485/status
07-28 12:31:03.218  6245  6245 V AudioManager: registerRemoteController: size of Media player list: 0
07-28 12:31:03.219  6245  6245 E AudioManager: No RCC entry present to update
07-28 12:31:03.219  6245  6245 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-28 12:31:03.221  6245  6245 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-28 12:31:03.222  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-28 12:31:03.222  6245  6245 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-28 12:31:03.225  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 12:31:03.226  6464  6464 I AppUp4:AppBoxCP: onCreate
07-28 12:31:03.227  6464  6464 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-28 12:31:03.228  6245  6455 V LGMDMManager: Create singleton instance
07-28 12:31:03.230  6245  6455 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-28 12:31:03.235  6464  6464 I AppUp4:DB:  setFingerPrint start
07-28 12:31:03.235  6464  6464 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-28 12:31:03.240  6464  6464 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-28 12:31:03.240  6464  6464 I AppUp4:DB:  SDK version = 21
07-28 12:31:03.240  6464  6464 I AppUp4:DB:  beforefinger == newfinger no write in DB
,07-28 12:31:03.241  6464  6464 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-28 12:31:03.242  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:31:03.242  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:03.243  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:31:03.243  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:31:03.272  6464  6464 I AppUp4:CustModeStarterReceiver: onReceive
,07-28 12:31:03.304  6464  6464 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:31:03.304  6464  6464 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:31:03.311  6464  6464 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@257b40c3
07-28 12:31:03.311  6464  6464 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:31:03.311  6464  6464 D AppUp4:CustFacade: isPhone : true
07-28 12:31:03.311  6464  6464 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:31:03.312  6464  6464 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-28 12:31:03.312  6464  6464 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-28 12:31:03.331  1036  2033 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:31:03.331  1036  2033 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:31:03.331  6464  6488 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-28 12:31:03.331  6464  6488 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-28 12:31:03.331  6464  6488 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-28 12:31:03.335  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:03.335  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:31:03.336  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:31:03.339  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:31:03.343  4240  6490 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:31:03.348  4240  6491 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:03.348  4240  6491 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-28 12:31:03.375  1036  2021 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6492 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-28 12:31:03.422  1036  1891 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-28 12:31:03.428  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-28 12:31:03.433  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:31:03.433  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,07-28 12:31:03.433  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:31:03.433  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:31:03.433  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:31:03.433  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:31:03.434  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 12:31:03.434  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:31:03.434  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:31:03.434  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 12:31:03.434  6245  6245 I BluetoothA2dpServiceJni: classInitNative
07-28 12:31:03.434  6245  6245 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:31:03.434  6245  6245 D A2dpStateMachine: make
07-28 12:31:03.436  6245  6245 I bluedroid-qcom: get_profile_interface a2dp
07-28 12:31:03.436  6245  6510 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 12:31:03.438  6245  6245 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:31:03.438  6245  6245 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-28 12:31:03.439  6245  6509 D A2dpStateMachine: Enter Disconnected: -2
07-28 12:31:03.439  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:03.440  6245  6245 I BluetoothHidServiceJni: classInitNative: succeeds
07-28 12:31:03.440  6492  6492 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:31:03.441  6492  6492 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:31:03.442  6492  6492 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 12:31:03.442  6492  6492 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-28 12:31:03.446  6245  6245 D HidService: Received start request. Starting profile...
07-28 12:31:03.446  6245  6245 I bluedroid-qcom: get_profile_interface hidhost
07-28 12:31:03.447  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:03.447  6245  6245 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:31:03.448  6245  6245 D HealthService: Received start request. Starting profile...
07-28 12:31:03.450  6245  6245 I bluedroid-qcom: get_profile_interface health
07-28 12:31:03.451  6245  6245 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:31:03.451  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:03.451  6245  6245 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-28 12:31:03.453  6245  6245 D PanService: Received start request. Starting profile...
07-28 12:31:03.453  6245  6245 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:31:03.453  6245  6245 I bluedroid-qcom: get_profile_interface pan
,07-28 12:31:03.459  6245  6245 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-28 12:31:03.459  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:03.460  6245  6245 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-28 12:31:03.465  6245  6245 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:31:03.466  6245  6245 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:31:03.466  6245  6245 D BtGatt.GattService: start()
07-28 12:31:03.466  6245  6245 I bluedroid-qcom: get_profile_interface gatt
07-28 12:31:03.466  6245  6245 D BtGatt.AdvertiseManager: advertise manager created
07-28 12:31:03.471  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:03.471  6245  6245 D HeadsetStateMachine: Proxy object connected
07-28 12:31:03.472  6245  6245 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-28 12:31:03.472  6245  6245 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,07-28 12:31:03.475  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:03.475  6245  6245 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-28 12:31:03.477  6245  6245 V BluetoothMapService: BluetoothMapBinder()
07-28 12:31:03.477  6245  6245 D BluetoothMapService: Received start request. Starting profile...
07-28 12:31:03.478  6245  6245 D BluetoothMapService: start()
07-28 12:31:03.481  6245  6245 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-28 12:31:03.481  6245  6245 D BluetoothMapEmailAppObserver: createReceiver()
07-28 12:31:03.482  6245  6245 D BluetoothMapEmailAppObserver: initObservers()
07-28 12:31:03.482  6245  6245 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,07-28 12:31:03.492  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:03.495  6245  6245 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:31:03.496  6245  6484 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 12:31:03.496  6245  6484 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:31:03.497  6245  6484 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-28 12:31:03.499  6245  6245 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:31:03.501  6245  6245 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:31:03.504  6245  6245 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:31:03.504  6245  6245 V PanService: [BTUI] SIM Extra State :ABSENT
,07-28 12:31:03.507  6245  6245 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:31:03.510  6245  6245 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-28 12:31:03.513  6245  6245 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:03.513  6245  6245 V BluetoothMapService: Handler(): got msg=1
07-28 12:31:03.514  6245  6245 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:31:03.514  6245  6455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-28 12:31:03.514  6245  6245 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:31:03.514  6245  6455 I bluedroid-qcom: enable
07-28 12:31:03.514  6245  6245 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:31:03.515  6245  6245 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:03.515  6245  6245 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-28 12:31:03.515  6245  6517 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 12:31:03.515  6245  6517 I bt-btu  : btu_task pending for preload complete event
07-28 12:31:03.515  6245  6455 I bt_hci_bdroid: init
07-28 12:31:03.516  6492  6492 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-28 12:31:03.517  6245  6455 I bt_vendor: bt-vendor : init
07-28 12:31:03.517  6245  6455 I bt_vendor: bt-vendor : get_bt_soc_type
07-28 12:31:03.517  6245  6455 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-28 12:31:03.517  6245  6455 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-28 12:31:03.517  6245  6455 D bt_userial_mct: userial_init
07-28 12:31:03.517  6245  6455 D bt_hci_bdroid: set_power 1
07-28 12:31:03.517  6245  6455 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-28 12:31:03.517  6245  6455 I bt_vendor: Starting hciattach daemon
07-28 12:31:03.517  6245  6455 I bt_vendor: try to set true
,07-28 12:31:03.512  6520  6520 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:31:03.512  6520  6520 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:03.526  6492  6492 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
07-28 12:31:03.538  6522  6522 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-28 12:31:03.559  6492  6492 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-28 12:31:03.590  6492  6492 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:31:03.590  6492  6492 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:31:03.599  6528  6528 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
07-28 12:31:03.609  6530  6530 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:31:03.639  6532  6532 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:31:03.649  6535  6535 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-28 12:31:03.660  6536  6536 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
07-28 12:31:03.667  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:03.669  6537  6537 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
07-28 12:31:03.685  6540  6540 I libmdmdetect: ESOC framework not supported
07-28 12:31:03.685  6540  6540 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-28 12:31:03.687  1036  1098 E GpsLocationProvider: No APN found to select.
07-28 12:31:03.690  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:03.690  6492  6492 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-28 12:31:03.691  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:03.692  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:03.692  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:03.692  6540  6540 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-28 12:31:03.692  6540  6540 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-28 12:31:03.692  6540  6540 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-28 12:31:03.692  6540  6540 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-28 12:31:03.692  6540  6540 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-28 12:31:03.692  6540  6540 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-28 12:31:03.692  6540  6540 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-28 12:31:03.726  6540  6541 E QC-QMI  : qmi_client [6540] 14: failed to locate client data
,07-28 12:31:03.727   451   451 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-28 12:31:03.727   451   451 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
07-28 12:31:03.743  3146  3146 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:31:03.743  3146  3146 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:03.744  3146  3146 I LgeMiscReceiver: networkInfo.isConnected() = true
07-28 12:31:03.745  3146  3146 D PhoneState: setPdpRejectCasuse : false
,07-28 12:31:03.758  6492  6492 I HubEmail: JNI_OnLoad()
07-28 12:31:03.758  6492  6492 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:31:03.758  6492  6492 I HubEmail: registerNatives()
,07-28 12:31:03.758  6492  6492 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:31:03.758  6492  6492 I HubEmail: registerNativeMethods()
07-28 12:31:03.758  6492  6492 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:31:03.758  6492  6492 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,07-28 12:31:03.794  6547  6547 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-28 12:31:03.804  1036  1993 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6548 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
07-28 12:31:03.806  6197  6543 W FormManager: Network not available. Please check & try again.
,07-28 12:31:03.809  6551  6551 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-28 12:31:03.814  6197  6544 V FormManager: Network unavailable.
07-28 12:31:03.817  6492  6546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:03.820  6197  6544 V FormManager: Network unavailable.
,07-28 12:31:03.826  1036  1993 I ActivityManager: Killing 5536:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-28 12:31:03.858  1036  1578 W libprocessgroup: failed to open /acct/uid_10004/pid_5536/cgroup.procs: No such file or directory
,07-28 12:31:03.869  6245  6455 I bt_vendor: bluetooth satus is on
,07-28 12:31:03.869  6245  6455 D bt_hci_bdroid: preload
,07-28 12:31:03.869  6245  6519 D bt_userial_mct: userial_open(port:0)
,07-28 12:31:03.869  6245  6519 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
07-28 12:31:03.872  6245  6519 I bt_vendor: Done intiailizing UART
07-28 12:31:03.873  6245  6519 I bt_vendor: Done intiailizing UART
07-28 12:31:03.873  6245  6519 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-28 12:31:03.873  6245  6519 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-28 12:31:03.874  6245  6567 D bt_userial_mct: Entering userial_read_thread()
07-28 12:31:03.874  6245  6517 I bt-btu  : btu_task received preload complete event
07-28 12:31:03.874  6245  6517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-28 12:31:03.874  6245  6517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,07-28 12:31:03.876  6245  6517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003,
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_HCI
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:31:03.879  6245  6517 I         : BTE_InitTraceLevels -- TRC_BTIF
07-28 12:31:03.925  6548  6548 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:31:03.925  6548  6548 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:31:03.928  6548  6548 D PhoneMonitor: Register our PhoneStateListener
,07-28 12:31:03.960  6245  6517 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,07-28 12:31:03.960  6245  6517 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d8061 
,07-28 12:31:03.960  6245  6517 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d8061 
,07-28 12:31:04.001  6245  6461 E bt-btif : Calling BTA_HhEnable
07-28 12:31:04.002  6245  6461 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,07-28 12:31:04.002  6245  6517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-28 12:31:04.002  6245  6517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-28 12:31:04.002  6245  6461 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-28 12:31:04.002  6245  6517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-28 12:31:04.003  6245  6517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-28 12:31:04.003  6245  6517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-28 12:31:04.018  6245  6517 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:31:04.018  6245  6517 W bt-smp  : Plain text(LSB ~ MSB) = 6f 5e 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:31:04.018  6245  6517 W bt-smp  : Encrypted text(LSB ~ MSB) = 07 57 d9 24 71 d8 d2 7e 5e fd e9 fa c3 52 d5 37 
07-28 12:31:04.019  6245  6517 W bt-btm  : Stopping oneshot timer
,07-28 12:31:04.054  1036  1763 I art     : Explicit concurrent mark sweep GC freed 127542(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.936ms total 109.225ms
07-28 12:31:04.055  6245  6461 D BluetoothAdapterProperties: Name is: G3
,07-28 12:31:04.055  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:31:04.056  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:31:04.056  6245  6461 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:31:04.056  6245  6461 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:31:04.056  6245  6461 D bt_hci_bdroid: postload
07-28 12:31:04.056  6245  6461 D bte_conf: Device ID record 1 : primary
07-28 12:31:04.056  6245  6461 D bte_conf:   vendorId            = 00c4
07-28 12:31:04.056  6245  6461 D bte_conf:   vendorIdSource      = 0001
07-28 12:31:04.056  6245  6461 D bte_conf:   product             = 13a1
07-28 12:31:04.056  6245  6461 D bte_conf:   version             = 1000
07-28 12:31:04.056  6245  6461 D bte_conf:   clientExecutableURL = 
07-28 12:31:04.057  6245  6461 D bte_conf:   serviceDescription  = 
07-28 12:31:04.057  6245  6461 D bte_conf:   documentationURL    = 
07-28 12:31:04.057  6245  6461 D bte_conf: bte_load_did_conf no section named DID2.
07-28 12:31:04.058  6245  6519 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:31:04.060  6245  6519 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:31:04.060  6245  6519 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:31:04.052  6569  6569 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:04.052  6569  6569 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:04.064  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:04.064  6245  6567 E bt_mct  : hci lib postload completed
07-28 12:31:04.066  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:04.068  6548  6548 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:31:04.068  6245  6517 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,07-28 12:31:04.069  6245  6455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 12:31:04.069  6245  6455 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:31:04.069  6245  6455 D BluetoothAdapterProperties: State =  11
07-28 12:31:04.069  6245  6455 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-28 12:31:04.070  6245  6455 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-28 12:31:04.070  6245  6455 D BluetoothAdapterProperties: Setting state to 12
07-28 12:31:04.070  6245  6455 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-28 12:31:04.072  1036  1108 D BluetoothManagerService: Message: 60
07-28 12:31:04.073  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-28 12:31:04.073  1036  1108 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
07-28 12:31:04.073  6245  6455 I BluetoothAdapterState: Entering On State
07-28 12:31:04.074  6548  6548 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:31:04.076  6245  6461 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-28 12:31:04.077  6245  6461 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:31:04.079  6245  6455 D LGBluetoothServiceAdapter: [BTUI] OnState
07-28 12:31:04.079  6245  6455 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-28 12:31:04.079  6245  6455 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-28 12:31:04.079  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:31:04.080  6245  6455 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,07-28 12:31:04.093  6548  6548 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-28 12:31:04.094  6548  6548 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,07-28 12:31:04.094  6548  6548 D TelephonyAutoProfiling: [parse] Load xml
07-28 12:31:04.097  6548  6548 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-28 12:31:04.097  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
07-28 12:31:04.097  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-28 12:31:04.097  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-28 12:31:04.097  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-28 12:31:04.097  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-28 12:31:04.097  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-28 12:31:04.098  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-28 12:31:04.098  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-28 12:31:04.098  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-28 12:31:04.098  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-28 12:31:04.098  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-28 12:31:04.098  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-28 12:31:04.098  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
07-28 12:31:04.098  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-28 12:31:04.098  6548  6548 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
,07-28 12:31:04.098  6548  6548 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
07-28 12:31:04.100  6577  6577 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-28 12:31:04.108  6548  6548 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-28 12:31:04.109  6245  6461 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:31:04.109  6245  6461 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,07-28 12:31:04.118  1036  1890 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6578 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:31:04.119  1036  1890 I ActivityManager: Killing 5787:com.google.android.apps.docs/u0a61 (adj 15): empty #17
07-28 12:31:04.123  6245  6455 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-28 12:31:04.159  1036  2033 W libprocessgroup: failed to open /acct/uid_10061/pid_5787/cgroup.procs: No such file or directory
,07-28 12:31:04.173  1036  1108 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:31:04.174  1036  1036 D BluetoothHeadset: Proxy object connected
07-28 12:31:04.174  1839  1839 D BluetoothHeadset: Proxy object connected
07-28 12:31:04.174  6108  6124 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 12:31:04.181  1839  2455 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:31:04.182  6108  6108 D BluetoothInputDevice: Proxy object connected
07-28 12:31:04.183  6108  6108 D HidProfile: Bluetooth service connected
07-28 12:31:04.186  1839  1839 D BluetoothHeadset: Proxy object connected
,07-28 12:31:04.188  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:31:04.193  1839  1839 D BluetoothHeadset: Proxy object connected
07-28 12:31:04.193  1036  1108 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:31:04.195  6108  6576 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:31:04.195  6108  6576 D BluetoothPan: onBluetoothStateChange call bindService
07-28 12:31:04.197  1036  1036 D BluetoothA2dp: Proxy object connected
07-28 12:31:04.203  6108  6123 D BluetoothMap: onBluetoothStateChange: up=true
07-28 12:31:04.203  6108  6108 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:31:04.203  6108  6108 D PanProfile: Bluetooth service connected
,07-28 12:31:04.208  6108  6576 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:31:04.209  6108  6108 D BluetoothMap: Proxy object connected
07-28 12:31:04.209  6108  6108 D MapProfile: Bluetooth service connected
07-28 12:31:04.209  6108  6108 D BluetoothMap: getConnectedDevices()
07-28 12:31:04.211  1036  1108 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-28 12:31:04.211  1036  1108 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-28 12:31:04.211  6245  6262 V BluetoothMapService: getConnectedDevices()
07-28 12:31:04.212  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-28 12:31:04.215  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:04.215  1927  2107 D LGBluetoothAPIService: Message: 1
07-28 12:31:04.215  1927  2107 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-28 12:31:04.216  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:31:04.217  1036  1108 D BluetoothManagerService: Message: 40
07-28 12:31:04.217  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-28 12:31:04.224  1927  2107 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-28 12:31:04.225  5840  5840 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,07-28 12:31:04.227  6245  6245 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:04.227  6245  6245 D BluetoothMapService: STATE_ON
07-28 12:31:04.229  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:04.229  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:04.229  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:04.229  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:04.229  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:04.229  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:04.229  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:04.229  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:31:04.230  6108  6108 D LocalBluetoothProfileManager: Adding local A2DP profile
07-28 12:31:04.230  6245  6245 D LGBluetoothAPIServer: [BTUI] onCreate()
07-28 12:31:04.232  6245  6245 D LGBluetoothAPIServer: [BTUI] onBind()
07-28 12:31:04.233  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-28 12:31:04.234  1036  1108 D BluetoothManagerService: Message: 30
07-28 12:31:04.234  1927  2107 D LGBluetoothAPIService: Message: 100
07-28 12:31:04.234  1927  2107 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-28 12:31:04.238  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:04.242  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:04.242  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:04.242  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:04.242  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:04.242  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:04.242  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:04.242  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:04.242  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:31:04.244  6108  6108 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-28 12:31:04.244  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:31:04.247  1036  1108 D BluetoothManagerService: Message: 30
07-28 12:31:04.251  6108  6108 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,07-28 12:31:04.253  6108  6108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:31:04.253  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:04.254  6245  6245 V BluetoothPbapService: Pbap Service onCreate
07-28 12:31:04.254  6245  6245 V BluetoothPbapService: Starting PBAP service
07-28 12:31:04.255  6245  6245 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-28 12:31:04.255  6245  6245 V BluetoothMapService: Handler(): got msg=1
07-28 12:31:04.256  6245  6245 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-28 12:31:04.256  6245  6245 V BluetoothPbapService: Pbap Service onBind
07-28 12:31:04.257  6245  6596 D BluetoothMapMasInstance: MAS initSocket()
07-28 12:31:04.258  6245  6596 D BluetoothMapMasInstance:   masId = 00
07-28 12:31:04.258  6245  6596 D BluetoothMapMasInstance:   msgTypes = 0e
07-28 12:31:04.258  6245  6596 D BluetoothMapMasInstance:   masName = SMS/MMS
07-28 12:31:04.258  6245  6596 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-28 12:31:04.260  1036  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:04.260  6108  6108 D BluetoothA2dp: Proxy object connected
07-28 12:31:04.260  6245  6245 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:04.260  6245  6245 V BluetoothPbapService: state: 12
07-28 12:31:04.261  6245  6245 V BluetoothPbapService: Handler(): got msg=1
07-28 12:31:04.261  6245  6245 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-28 12:31:04.261  6108  6108 D A2dpProfile: Bluetooth service connected
07-28 12:31:04.262  6245  6245 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:31:04.263  6245  6245 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:04.263  6245  6245 V BluetoothPbapReceiver: ***********state = 12
07-28 12:31:04.263  6108  6108 D BluetoothHeadset: Proxy object connected
,07-28 12:31:04.265  6245  6597 V BluetoothPbapService: Pbap Service initSocket
07-28 12:31:04.265  6108  6108 D HeadsetProfile: Bluetooth service connected
07-28 12:31:04.265  6245  6596 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:31:04.266  1036  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:04.267  6245  6596 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-28 12:31:04.267  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:31:04.267  6245  6596 V BluetoothMapMasInstance: Succeed to create listening socket 
07-28 12:31:04.267  6245  6596 D BluetoothMapMasInstance: Accepting socket connection...
07-28 12:31:04.268  2193  2193 D c       : Getting all permits...
07-28 12:31:04.268  2193  2193 D a       : Opening database...
07-28 12:31:04.268  6245  6461 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:31:04.268  6245  6461 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-28 12:31:04.269  6245  6597 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:31:04.270  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:04.271  6245  6597 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-28 12:31:04.271  6245  6597 V BluetoothPbapService: Succeed to create listening socket 
07-28 12:31:04.271  6245  6597 V BluetoothPbapService: Accepting socket connection...
07-28 12:31:04.271  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:04.273  2193  2193 D a       : Opening database auth.proximity.permit_store...
07-28 12:31:04.274  2193  2193 D a       : Closing database...
07-28 12:31:04.275  6108  6108 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:31:04.276  6108  6108 D BluetoothPbap: Proxy object connected
07-28 12:31:04.276  6108  6108 D PbapServerProfile: Bluetooth service connected
07-28 12:31:04.285  6108  6108 D BluetoothPermissionRequest: onReceive
07-28 12:31:04.287  6108  6108 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,07-28 12:31:04.289  6108  6108 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:31:04.292  6245  6245 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-28 12:31:04.293  6245  6245 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-28 12:31:04.298  6245  6245 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-28 12:31:04.321  6245  6245 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,07-28 12:31:04.321  6245  6245 V BtOppService: onCreate
07-28 12:31:04.325  6245  6245 V BluetoothOppNotification: send message
07-28 12:31:04.329  6245  6245 V BtOppService: Starting RfcommListener
07-28 12:31:04.332  6245  6245 D BluetoothOppPreference: Dumping Names:  
07-28 12:31:04.332  6245  6245 D BluetoothOppPreference: {}
07-28 12:31:04.332  6245  6245 D BluetoothOppPreference: Dumping Channels:  
07-28 12:31:04.332  6245  6245 D BluetoothOppPreference: {}
,07-28 12:31:04.336  6245  6245 V BtOppService: onStartCommand
07-28 12:31:04.337  6245  6601 V BtOppService: Deleted complete outbound shares, number =  0
07-28 12:31:04.338  6245  6604 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:31:04.339  6245  6601 V BtOppService: Deleted complete inbound failed shares, number = 0
07-28 12:31:04.339  6245  6245 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:04.339  6245  6245 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:31:04.339  6245  6604 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:31:04.341  6245  6601 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,07-28 12:31:04.341  6245  6245 V BluetoothOppNotification: new notify threadi!
07-28 12:31:04.342  6245  6604 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ce092da on behalf of 
07-28 12:31:04.342  6245  6245 V BluetoothOppNotification: send delay message
07-28 12:31:04.343  6245  6245 V BtOppService: start RfcommListener
07-28 12:31:04.343  6245  6605 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:31:04.343  6245  6601 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16f9230b on behalf of 
07-28 12:31:04.345  6245  6245 V BtOppService: RfcommListener started
07-28 12:31:04.345  6245  6605 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@164375e8 on behalf of 
07-28 12:31:04.345  6245  6245 V BtOppService: ContentObserver received notification
07-28 12:31:04.345  6245  6245 V BtOppService: ContentObserver received notification
07-28 12:31:04.345  6245  6605 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-28 12:31:04.346  6245  6604 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,07-28 12:31:04.346  6245  6604 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:31:04.347  6245  6605 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 12:31:04.347  6245  6604 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22161401 on behalf of 
07-28 12:31:04.348  6245  6605 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@374502a6 on behalf of 
07-28 12:31:04.348  6245  6606 V BtOppRfcommListener: Starting RFCOMM listener....
07-28 12:31:04.349  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:04.349  6245  6604 V BluetoothOppNotification: update too frequent, put in queue
07-28 12:31:04.349  6245  6606 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:31:04.350  6245  6606 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
07-28 12:31:04.350  6245  6606 V BtOppRfcommListener: Started RFCOMM listener....
07-28 12:31:04.350  6245  6606 I BtOppRfcommListener: Accept thread started.
07-28 12:31:04.350  6245  6606 V BtOppRfcommListener: Accepting connection...
07-28 12:31:04.350  6245  6605 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:31:04.351  6245  6604 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 12:31:04.351  6245  6605 V BluetoothOppNotification: outbound notification was removed.
07-28 12:31:04.351  6245  6605 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:31:04.352  6245  6605 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@194e4e7 on behalf of 
07-28 12:31:04.353  6245  6605 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:31:04.354  6245  6605 V BluetoothOppNotification: inbound notification was removed.
07-28 12:31:04.354  6245  6605 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:31:04.355  6245  6605 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bce0894 on behalf of 
07-28 12:31:04.364  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
,07-28 12:31:04.364  6245  6245 V BluetoothFtpService: Ftp Service onCreate
07-28 12:31:04.364  6245  6245 I BluetoothFtpService: Ftp Service onCreate
07-28 12:31:04.364  6245  6245 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:31:04.364  6245  6245 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:04.364  6245  6245 V BluetoothFtpService: Starting Listening on sockets
07-28 12:31:04.364  6245  6245 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:31:04.364  6245  6245 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:31:04.364  6245  6245 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:31:04.365  6245  6245 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:04.365  6245  6245 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-28 12:31:04.365  6245  6245 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:31:04.367  6245  6245 V BluetoothFtpService: Handler(): got msg=1
07-28 12:31:04.367  6245  6245 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-28 12:31:04.367  6245  6245 V BluetoothFtpService: Ftp Service initSocket
07-28 12:31:04.370  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:04.371  6245  6245 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:31:04.372  6245  6245 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-28 12:31:04.373  6245  6607 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-28 12:31:04.393  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
,07-28 12:31:04.393  6245  6245 V BluetoothSapService: Sap Service onCreate
,07-28 12:31:04.395  6245  6245 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:04.395  6245  6245 V BluetoothSapService: state: 12
07-28 12:31:04.395  6245  6245 V BluetoothSapService: Starting SAP server process
07-28 12:31:04.396  6245  6245 V BluetoothSapService: SAP Service startRfcommListenerThread
07-28 12:31:04.392  6608  6608 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:04.397  6245  6609 V BluetoothSapService: Sap Service initRfcommSocket
07-28 12:31:04.392  6608  6608 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:04.398  1036  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:04.398  6245  6609 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:31:04.399  6245  6609 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-28 12:31:04.399  6245  6609 V BluetoothSapService: Succeed to create listening socket 
07-28 12:31:04.399  6245  6609 V BluetoothSapService: Accepting socket connection...
07-28 12:31:04.404  6608  6608 V BT_SAP  : Event pipe created
07-28 12:31:04.404  6608  6608 V BT_SAP  : create_server_socket qcom.sap.server
07-28 12:31:04.404  6608  6608 V BT_SAP  : created socket fd 6
07-28 12:31:04.531  1036  1560 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6611 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-28 12:31:04.532  1036  1560 I ActivityManager: Killing 5915:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,07-28 12:31:04.590  1036  1891 W libprocessgroup: failed to open /acct/uid_10080/pid_5915/cgroup.procs: No such file or directory
07-28 12:31:04.652  6611  6611 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
07-28 12:31:04.655  6611  6611 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,07-28 12:31:04.663  6611  6611 V DrmService: Service onCreate
07-28 12:31:04.663  6611  6611 D DrmService: Received new request = 2
07-28 12:31:04.672  6611  6631 I DrmSntpClient: Start Sync process
,07-28 12:31:04.673  6611  6631 D DrmSntpClient: Server : 0
07-28 12:31:04.728  1036  1560 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6632 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:31:04.739  6611  6631 D DrmSntpClient: Automatic sync but WiFi isn't enabled
07-28 12:31:04.740  6611  6611 D DrmService: Completed !! request = 2
07-28 12:31:04.740  6611  6611 D DrmService: Request count = 0
07-28 12:31:04.742  6611  6611 V DrmService: Service onDestroy
07-28 12:31:04.744  1036  1966 I ActivityManager: Killing 5937:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,07-28 12:31:04.756  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 6451
07-28 12:31:04.757  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 6452
07-28 12:31:04.758  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 6462
07-28 12:31:04.759  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 6463
,07-28 12:31:04.762  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 6628
07-28 12:31:04.799  1036  1890 W libprocessgroup: failed to open /acct/uid_10097/pid_5937/cgroup.procs: No such file or directory
,07-28 12:31:04.848  6632  6632 I art     : Almond Protected OAT
,07-28 12:31:04.907  6632  6632 D WeatherApplication: removeAccount
,07-28 12:31:04.910  6632  6632 D WeatherApplication: Account.length = 0
07-28 12:31:04.911  6632  6632 E WeatherApplication: OPERATOR:OPEN
07-28 12:31:04.917  6632  6632 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:31:4
07-28 12:31:04.921  6632  6632 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,07-28 12:31:04.921  6632  6632 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:31:04.924  6632  6632 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:31:04.927  6632  6632 D WeatherAncestor: connectivity changed - connection : true
07-28 12:31:04.928  6632  6632 D WeatherService: 2 : isServiceAlived():false forecastCache:null
07-28 12:31:04.941  6632  6632 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:31:04.941  6632  6632 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:31:04.941  6632  6632 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,07-28 12:31:04.962  6632  6632 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:31:04.963  6632  6632 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:31:4
,07-28 12:31:04.966   310  6407 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-28 12:31:04.971  1036  6341 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.SocketException: Binding socket to network 100 failed: errno 64 (Machine is not on the network)
07-28 12:31:04.971  1036  6341 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s915ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:31:04.971  1036  6341 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s915ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:04.972  1036  6341 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-28 12:31:05.006  1036  2021 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6650 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 12:31:05.009  1036  2021 I ActivityManager: Killing 5983:com.lge.eula/1000 (adj 15): empty #17
,07-28 12:31:05.024  1036  1521 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:31:05.025  1036  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:05.056  1036  1522 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
07-28 12:31:05.058  1036  1522 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-28 12:31:05.069  1036  1763 W libprocessgroup: failed to open /acct/uid_1000/pid_5983/cgroup.procs: No such file or directory
07-28 12:31:05.191   278   419 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:31:05.192   278   419 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-28 12:31:05.192   278   419 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:31:05.193  6650  6668 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-28 12:31:05.197   278   419 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:31:05.197   278   419 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-28 12:31:05.197   278   419 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:31:05.199  6650  6668 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-28 12:31:05.232   278   419 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:31:05.232   278   419 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-28 12:31:05.233   278   419 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:31:05.234  6650  6672 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-28 12:31:05.240   278   419 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:31:05.240   278   419 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-28 12:31:05.240   278   419 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:31:05.242  6650  6672 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-28 12:31:05.345  6245  6245 V BluetoothOppNotification: new notify threadi!
07-28 12:31:05.345  6245  6245 V BluetoothOppNotification: send delay message
,07-28 12:31:05.347  6245  6685 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:31:05.349  6245  6685 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1404239 on behalf of 
07-28 12:31:05.350  6245  6685 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 12:31:05.351  6245  6685 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 12:31:05.353  6245  6685 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d9fc07e on behalf of 
07-28 12:31:05.354  6245  6685 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:31:05.357  6245  6685 V BluetoothOppNotification: outbound notification was removed.
07-28 12:31:05.358  6245  6685 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,07-28 12:31:05.360  6245  6685 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@191f89df on behalf of 
07-28 12:31:05.361  6245  6685 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:31:05.365  6245  6685 V BluetoothOppNotification: inbound notification was removed.
07-28 12:31:05.365  6245  6685 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:31:05.368  6245  6685 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fe9d62c on behalf of 
07-28 12:31:05.474  6650  6650 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-28 12:31:05.487  6650  6650 I LibraryLoader: Loading: webviewchromium
07-28 12:31:05.492  6650  6650 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6879-6884)
07-28 12:31:05.492  6650  6650 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:31:05.503  6650  6650 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d0e799c}
,07-28 12:31:05.506  6650  6650 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:31:05.506  6650  6650 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,07-28 12:31:05.525  6650  6650 I BrowserStartupController: Initializing chromium process, renderers=0
07-28 12:31:05.527  6650  6650 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:31:05.557  6650  6650 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,07-28 12:31:05.558  6650  6650 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-28 12:31:05.558  6650  6650 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
07-28 12:31:05.559   314  1371 V AudioPolicyService: registerClient() client 0xb04109a0, uid 10093
07-28 12:31:05.562  6650  6694 W AudioManagerAndroid: Requires BLUETOOTH permission
07-28 12:31:05.592  6650  6650 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:31:05.592  6650  6650 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:31:05.592  6650  6650 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:31:05.592  6650  6650 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:31:05.592  6650  6650 I Adreno-EGL: Remote Branch: 
07-28 12:31:05.592  6650  6650 I Adreno-EGL: Local Patches: 
07-28 12:31:05.592  6650  6650 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:31:05.690  6650  6650 I NSApplication: Starting up...
,07-28 12:31:05.802  1036  2033 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6707 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-28 12:31:05.808  1036  1891 I ActivityManager: Killing 5743:com.android.vending/u0a44 (adj 15): empty #17
07-28 12:31:05.870  1036  2015 W libprocessgroup: failed to open /acct/uid_10044/pid_5743/cgroup.procs: No such file or directory
,07-28 12:31:05.911  6707  6707 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:31:06.009  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:31:06.009  1036  1960 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3d15954e mBinding = false
,07-28 12:31:06.027  1036  1108 D BluetoothManagerService: Message: 2
07-28 12:31:06.032  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:31:06.033  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:31:06.034  1036  1108 D BluetoothManagerService: Sending off request.
07-28 12:31:06.035  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-28 12:31:06.036  6245  6595 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-28 12:31:06.038  6245  6455 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-28 12:31:06.038  6245  6455 D BluetoothAdapterProperties: Setting state to 13
07-28 12:31:06.038  6245  6455 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:31:06.039  1036  1108 D BluetoothManagerService: Message: 60
07-28 12:31:06.039  6245  6455 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 12:31:06.039  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-28 12:31:06.039  6245  6455 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 12:31:06.039  1036  1108 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,07-28 12:31:06.040  6245  6461 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:31:06.040  6245  6455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 12:31:06.045  6245  6455 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:31:06.047  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-28 12:31:06.047  6245  6517 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-28 12:31:06.048  6245  6596 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-28 12:31:06.048  6245  6596 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:31:06.048  6245  6596 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-28 12:31:06.048  6245  6596 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-28 12:31:06.048  6245  6596 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-28 12:31:06.048  6245  6596 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-28 12:31:06.048  6245  6596 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-28 12:31:06.048  6245  6596 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-28 12:31:06.049  6245  6597 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:31:06.051  6245  6606 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:31:06.051  6245  6607 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-28 12:31:06.053  6245  6609 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:31:06.057  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:31:06.057  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:31:06.057  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:31:06.057  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:31:06.057  6245  6517 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:31:06.057  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:31:06.057  6245  6517 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:31:06.057  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:31:06.057  6245  6517 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:31:06.057  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-28 12:31:06.057  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-28 12:31:06.057  6245  6517 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:31:06.059  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:06.060  6245  6245 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:06.060  6245  6245 D BluetoothMapService: STATE_TURNING_OFF
07-28 12:31:06.060  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:31:06.060  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:06.060  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:06.060  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:06.060  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:06.060  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:31:06.060  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:06.060  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:06.060  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:31:06.060  6245  6245 V BtOppService: Receiver DISABLED_ACTION 
07-28 12:31:06.060  6245  6245 V BluetoothMapService: Handler(): got msg=4
07-28 12:31:06.060  6245  6245 D BluetoothMapService: MAP Service closeService in
07-28 12:31:06.060  6245  6245 D BluetoothMapMasInstance: MAP Service shutdown
07-28 12:31:06.061  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:31:06.061  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:31:06.061  6245  6245 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:31:06.061  6245  6245 V BluetoothMapService: MAP Service closeService out
07-28 12:31:06.061  6245  6245 I BtOppRfcommListener: stopping Accept Thread
07-28 12:31:06.061  6245  6245 V BtOppRfcommListener: close mBtServerSocket
07-28 12:31:06.061  6245  6245 V BtOppRfcommListener: waiting for thread to terminate
07-28 12:31:06.061  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:31:06.062  6245  6606 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-28 12:31:06.064  6108  6108 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
07-28 12:31:06.066  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:31:06.066  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:06.066  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:06.066  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:06.066  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:06.066  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:31:06.066  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:06.066  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:06.066  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:31:06.066  6245  6245 V BtOppRfcommListener: done waiting for thread to terminate
07-28 12:31:06.067  6245  6245 V BtOppService: onDestroy
07-28 12:31:06.067  5840  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:31:06.067  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:31:06.069  6108  6108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:31:06.071  6245  6245 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-28 12:31:06.072  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:06.075  6245  6245 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:31:06.076  6245  6245 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:06.076  6245  6245 V BluetoothPbapReceiver: ***********state = 13
07-28 12:31:06.077  6245  6245 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,07-28 12:31:06.080  6108  6108 D DockEventReceiver: finishStartingService: stopping service
07-28 12:31:06.081  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:31:06.082  6245  6245 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:06.082  6245  6245 V BluetoothPbapService: state: 13
07-28 12:31:06.082  6245  6245 V BluetoothPbapService: Pbap Service closeService in
07-28 12:31:06.083  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:06.090  6245  6245 V BluetoothPbapService: successfully stopped pbap service
07-28 12:31:06.090  6245  6245 V BluetoothPbapService: Pbap Service closeService out
,07-28 12:31:06.091  6245  6245 V BluetoothPbapService: Pbap Service onDestroy
07-28 12:31:06.091  6245  6245 V BluetoothPbapService: Pbap Service closeService in
07-28 12:31:06.091  6245  6245 V BluetoothPbapService: Pbap Service closeService out
07-28 12:31:06.091  6245  6245 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-28 12:31:06.097  6108  6108 D BluetoothPbap: Proxy object disconnected
,07-28 12:31:06.097  6108  6108 D PbapServerProfile: Bluetooth service disconnected
07-28 12:31:06.107  6108  6108 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-28 12:31:06.112  6108  6108 D BluetoothPermissionRequest: onReceive
07-28 12:31:06.112  6108  6108 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-28 12:31:06.118  6108  6108 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:31:06.121  6245  6245 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-28 12:31:06.121  6245  6245 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-28 12:31:06.122  6245  6245 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,07-28 12:31:06.125  6245  6245 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:06.125  6245  6245 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:31:06.126  6245  6245 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:31:06.126  6245  6245 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:06.126  6245  6245 V BluetoothFtpService: Ftp Service closeService
07-28 12:31:06.126  6245  6245 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-28 12:31:06.128  6245  6245 V BluetoothFtpService: successfully stopped ftp service
07-28 12:31:06.128  6245  6245 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:31:06.128  6245  6245 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:31:06.128  6245  6245 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:31:06.128  6245  6245 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:06.128  6245  6245 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-28 12:31:06.128  6245  6245 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:31:06.129  6245  6245 V BluetoothFtpService: Ftp Service onDestroy
07-28 12:31:06.129  6245  6245 V BluetoothFtpService: Ftp Service closeService
07-28 12:31:06.132  6245  6245 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:06.132  6245  6245 V BluetoothSapService: state: 13
07-28 12:31:06.132  6245  6245 V BluetoothSapService: Stopping SAP server process
07-28 12:31:06.133  6245  6245 V BluetoothSapService: Sap Service closeSapService in
07-28 12:31:06.133  6245  6245 V BluetoothSapService: Close listen Socket : 
07-28 12:31:06.133  6245  6245 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:31:06.133  6245  6245 V BluetoothSapService: Close sapd  Socket : 
,07-28 12:31:06.138  6245  6245 V BluetoothSapService: Sap Service closeSapService out
07-28 12:31:06.138  6245  6245 V BluetoothSapService: Sap Service onDestroy
07-28 12:31:06.138  6245  6245 V BluetoothSapService: Sap Service closeSapService in
07-28 12:31:06.138  6245  6245 V BluetoothSapService: Close listen Socket : 
07-28 12:31:06.138  6245  6245 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:31:06.138  6245  6245 V BluetoothSapService: Close sapd  Socket : 
07-28 12:31:06.139  6245  6245 V BluetoothSapService: Sap Service closeSapService out
07-28 12:31:06.229  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-28 12:31:06.233  3627  3648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:31:06.244  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:31:06.254  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:31:06.254  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:06.254  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:31:06.254  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:31:06.257  6464  6464 I AppUp4:CustModeStarterReceiver: onReceive
,07-28 12:31:06.261  6464  6464 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@257b40c3
07-28 12:31:06.261  6464  6464 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:31:06.261  6464  6464 D AppUp4:CustFacade: isPhone : true
07-28 12:31:06.261  6464  6464 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:31:06.262  6464  6464 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:31:06.265  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:06.265  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:31:06.267  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:31:06.270  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:31:06.275  6492  6492 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-28 12:31:06.277  4240  6749 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:31:06.281  4240  6750 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:06.281  4240  6750 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:31:06.288  6492  6751 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:31:06.298  6197  6754 W FormManager: Network not available. Please check & try again.
,07-28 12:31:06.303  3146  3146 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:31:06.303  3146  3146 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:06.303  3146  3146 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-28 12:31:06.311  6548  6548 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:31:06.311  6548  6548 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:31:06.314  6197  6755 V FormManager: Network unavailable.
,07-28 12:31:06.324  6632  6632 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:31:6
,07-28 12:31:06.326  6197  6755 V FormManager: Network unavailable.
07-28 12:31:06.326  6632  6632 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:31:06.326  6632  6632 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:31:06.326  6632  6632 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:31:06.327  6632  6632 D WeatherAncestor: connectivity changed - connection : true
07-28 12:31:06.327  6632  6632 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@19c4f479
,07-28 12:31:06.328  6632  6632 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,07-28 12:31:06.328  6632  6632 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:31:06.328  6632  6632 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:31:06.328  6632  6632 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:31:06.328  6632  6632 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:31:6
07-28 12:31:06.348  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-28 12:31:06.349  3627  3648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:31:06.366  2193  2193 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:31:06.373  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:31:06.373  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:06.373  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:31:06.373  6464  6464 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:31:06.375  6464  6464 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:31:06.378  6464  6464 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@257b40c3
07-28 12:31:06.378  6464  6464 D AppUp4:CustFacade: isCustomizationCompleted : false
,07-28 12:31:06.378  6464  6464 D AppUp4:CustFacade: isPhone : true
07-28 12:31:06.380  6464  6464 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:31:06.380  6464  6464 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:31:06.386  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:06.386  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:31:06.388  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:31:06.391  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:31:06.396  4240  6760 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:31:06.398  6492  6492 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-28 12:31:06.401  4240  6761 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:06.401  4240  6761 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:31:06.419  6492  6762 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:31:06.422  6197  6764 W FormManager: Network not available. Please check & try again.
07-28 12:31:06.428  3146  3146 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:31:06.428  3146  3146 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:06.428  3146  3146 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 12:31:06.431  6548  6548 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:31:06.432  6548  6548 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:31:06.433  6197  6765 V FormManager: Network unavailable.
,07-28 12:31:06.446  6197  6765 V FormManager: Network unavailable.
,07-28 12:31:06.451  6632  6632 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:31:6
,07-28 12:31:06.455  6632  6632 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,07-28 12:31:06.455  6632  6632 D Weather.Utils: 2 : All the weather widget is gone.
,07-28 12:31:06.455  6632  6632 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,07-28 12:31:06.456  6632  6632 D WeatherAncestor: connectivity changed - connection : true,
07-28 12:31:06.456  6632  6632 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@19c4f479
07-28 12:31:06.457  6632  6632 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:31:06.457  6632  6632 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,07-28 12:31:06.457  6632  6632 D ForecastDataCache: 2 : Cache is up-to-date, count: 0,
,07-28 12:31:06.457  6632  6632 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,07-28 12:31:06.458  6632  6632 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:31:6
07-28 12:31:06.963  6245  6461 D bt_hci_bdroid: cleanup
,07-28 12:31:06.982  6245  6519 I bt_lpm  : LPM is already off!!!
07-28 12:31:06.984  6245  6567 I bt_userial_mct: exiting userial_read_thread
07-28 12:31:06.984  6245  6567 D bt_userial_mct: Leaving userial_evt_read_thread()
07-28 12:31:06.985  6245  6517 W bt-btif : ag scb idx 1 not allocated
07-28 12:31:06.985  6245  6517 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:31:06.985  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:31:06.985  6245  6517 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:31:06.986  6245  6517 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:31:06.987  6245  6517 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:31:06.989  6245  6461 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,07-28 12:31:06.992  6245  6519 I bt_vendor: hw_epilog_process
07-28 12:31:06.992  6245  6461 D bt_hci_bdroid: cleanup Finalizing cleanup
07-28 12:31:06.992  6245  6461 D bt_userial_mct: userial_close
07-28 12:31:06.992  6245  6461 E bt_userial_mct: pthread_join() FAILED result:3
07-28 12:31:06.992  6245  6461 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-28 12:31:07.007  6245  6461 D bt_hci_bdroid: set_power 0
07-28 12:31:07.007  6245  6461 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-28 12:31:07.007  6245  6461 I bt_vendor: bluetooth satus is on
07-28 12:31:07.007  6245  6461 I bt_vendor: bt-vendor : resetting BT status
07-28 12:31:07.007  6245  6461 I bt_vendor: Starting hciattach daemon
07-28 12:31:07.007  6245  6461 I bt_vendor: try to set false
,07-28 12:31:07.011  6245  6461 I bt_vendor: Starting hciattach daemon
07-28 12:31:07.011  6245  6461 I bt_vendor: try to set false
07-28 12:31:07.012  6245  6461 I bt_vendor: cleanup
07-28 12:31:07.013  6245  6517 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:31:07.013  6245  6461 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:31:07.013  6245  6461 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-28 12:31:07.015  6245  6455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:31:07.019  6245  6245 D HeadsetService: Received stop request...Stopping profile...
,07-28 12:31:07.024  6245  6245 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:31:07.024  6245  6245 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:31:07.024  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:07.026  6245  6484 D HeadsetStateMachine: Exit Disconnected: -1
07-28 12:31:07.027  1036  1036 D BluetoothHeadset: Proxy object disconnected
07-28 12:31:07.027  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-28 12:31:07.028  1839  1839 D BluetoothHeadset: Proxy object disconnected
07-28 12:31:07.028  1839  1839 D BluetoothHeadset: Proxy object disconnected
07-28 12:31:07.031  1839  1839 D BluetoothHeadset: Proxy object disconnected
,07-28 12:31:07.034  6245  6245 D A2dpService: Received stop request...Stopping profile...
07-28 12:31:07.035  6245  6509 D A2dpStateMachine: Exit Disconnected: -1
07-28 12:31:07.036  6245  6245 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-28 12:31:07.042  6245  6455 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:31:07.042  6245  6245 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-28 12:31:07.042  6245  6245 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:31:07.043  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:07.044  1036  1036 D BluetoothA2dp: Proxy object disconnected
07-28 12:31:07.044  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,07-28 12:31:07.048  6245  6245 D HidService: Received stop request...Stopping profile...
07-28 12:31:07.048  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:07.051  6245  6245 D HeadsetStateMachine: Unbinding service...
07-28 12:31:07.052  6245  6245 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:31:07.052  6245  6245 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:31:07.052  6245  6245 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:31:07.052  6245  6245 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:31:07.052  6245  6245 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:31:07.052  6245  6245 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:31:07.052  6245  6245 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:31:07.053  6245  6245 D HealthService: Received stop request...Stopping profile...
07-28 12:31:07.054  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:07.056  6245  6245 D PanService: Received stop request...Stopping profile...
,07-28 12:31:07.059  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:07.060  6245  6245 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:31:07.063  6245  6245 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:31:07.063  6245  6245 D BtGatt.GattService: stop()
07-28 12:31:07.063  6245  6245 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 12:31:07.064  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:07.066  6245  6245 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:31:07.066  6245  6245 D BluetoothMapService: stop()
07-28 12:31:07.067  6245  6245 D BluetoothMapEmailAppObserver: deinitObservers()
07-28 12:31:07.068  6245  6245 D BluetoothMapEmailAppObserver: removeReceiver()
,07-28 12:31:07.070  6245  6245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19c4f479
07-28 12:31:07.071  6245  6245 I BluetoothA2dpServiceJni: cleanupNative
07-28 12:31:07.072  6245  6510 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:31:07.073  6245  6245 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:31:07.073  6245  6245 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:31:07.073  6245  6245 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:31:07.073  6245  6245 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:31:07.073  6245  6245 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:31:07.074  6245  6245 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:31:07.074  6245  6245 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:31:07.074  6245  6245 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:31:07.074  6245  6245 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 12:31:07.077  6245  6245 V BluetoothMapService: Handler(): got msg=4
07-28 12:31:07.077  6245  6245 D BluetoothMapService: MAP Service closeService in
07-28 12:31:07.077  6245  6245 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:31:07.077  6245  6245 V BluetoothMapService: MAP Service closeService out
07-28 12:31:07.078  6245  6455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:31:07.078  6245  6455 D BluetoothAdapterProperties: Setting state to 10
07-28 12:31:07.078  6245  6455 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:31:07.078  6245  6245 D BluetoothMapService: cleanup()
07-28 12:31:07.078  6245  6245 D BluetoothMapService: MAP Service closeService in
07-28 12:31:07.078  6245  6245 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:31:07.078  6245  6245 V BluetoothMapService: MAP Service closeService out
07-28 12:31:07.079  1036  1108 D BluetoothManagerService: Message: 60
07-28 12:31:07.079  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-28 12:31:07.079  1036  1108 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,07-28 12:31:07.083  6245  6455 I BluetoothAdapterState: Entering OffState
07-28 12:31:07.084  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:31:07.084  1036  1108 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:31:07.085  6108  6124 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:31:07.085  6108  6124 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:31:07.086  6108  6124 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:31:07.087  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:31:07.087  1839  2455 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:31:07.088  1036  1108 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:31:07.088  6108  6124 D BluetoothPan: onBluetoothStateChange on: false
07-28 12:31:07.089  6108  6124 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:31:07.089  6108  6124 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:31:07.090  1036  1108 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-28 12:31:07.090  1036  1108 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-28 12:31:07.092  1036  1108 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-28 12:31:07.092  1036  1108 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-28 12:31:07.092  1036  1108 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3d15954e mBinding = false
,07-28 12:31:07.095  1036  1108 D BluetoothManagerService: Sending unbind request.
07-28 12:31:07.100  6245  6461 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-28 12:31:07.101  6245  6245 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:31:07.101  6245  6245 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 12:31:07.101  6245  6245 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:31:07.101  6245  6245 I art     : --- WEIRD: removing null entry 248
07-28 12:31:07.101  6245  6245 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
07-28 12:31:07.101  6245  6245 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-28 12:31:07.102  6245  6245 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-28 12:31:07.103  1036  1108 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,07-28 12:31:07.108  6245  6245 I art     : System.exit called, status: 0
07-28 12:31:07.108  6245  6245 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-28 12:31:07.127   314  2161 V AudioFlinger: 6245 died, releasing its sessions
07-28 12:31:07.127   314  2161 V AudioFlinger:  pid 1839 @ 0
07-28 12:31:07.127   314  2161 V AudioFlinger:  pid 3146 @ 1
07-28 12:31:07.127   314  2161 V AudioFlinger:  pid 3146 @ 2
,07-28 12:31:07.130  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
07-28 12:31:07.131  1927  2107 D LGBluetoothAPIService: Message: 101
07-28 12:31:07.131  1927  2107 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
07-28 12:31:07.131  1927  2107 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
07-28 12:31:07.131  1927  2107 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
07-28 12:31:07.132  6108  6108 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-28 12:31:07.135  1036  2033 I ActivityManager: Process com.android.bluetooth (pid 6245) has died
07-28 12:31:07.136  1036  2033 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
07-28 12:31:07.136  1036  2033 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
07-28 12:31:07.141  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:07.144  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:31:07.145  1927  2107 D LGBluetoothAPIService: Message: 2
07-28 12:31:07.145  1927  2107 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
07-28 12:31:07.146  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:07.146  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:07.149  6108  6108 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-28 12:31:07.149  6108  6108 D LGBluetoothEventManager: [BTUI] clear device connection state
07-28 12:31:07.153  6108  6108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-28 12:31:07.177  1588  1588 D BluetoothAdapter: 309953467: getState() :  mService = null. Returning STATE_OFF
07-28 12:31:07.177  1588  1588 D BluetoothAdapter: 309953467: getState() :  mService = null. Returning STATE_OFF
,07-28 12:31:07.210  1036  1890 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6795 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-28 12:31:07.212  6108  6108 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:31:07.252  6795  6795 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-28 12:31:07.253  6795  6795 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 12:31:07.253  6795  6795 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-28 12:31:07.254  6795  6795 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-28 12:31:07.271  6795  6795 D BluetoothAdapterApp: Loading JNI Library
,07-28 12:31:07.306  6795  6795 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@15d7be41 Instance Count = 1
,07-28 12:31:07.311  6795  6795 D BluetoothAdapterApp: onCreate
07-28 12:31:07.334  6795  6795 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-28 12:31:07.335  6795  6795 D ProfileConfigQcom: Adding HeadsetService
07-28 12:31:07.335  6795  6795 D ProfileConfigQcom: [BTUI] A2dpService is supported
,07-28 12:31:07.335  6795  6795 D ProfileConfigQcom: Adding A2dpService
,07-28 12:31:07.335  6795  6795 D ProfileConfigQcom: [BTUI] HidService is supported
,07-28 12:31:07.335  6795  6795 D ProfileConfigQcom: Adding HidService
07-28 12:31:07.336  6795  6795 D ProfileConfigQcom: [BTUI] HealthService is supported
07-28 12:31:07.336  6795  6795 D ProfileConfigQcom: Adding HealthService
07-28 12:31:07.336  6795  6795 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,07-28 12:31:07.337  6795  6795 D ProfileConfigQcom: [BTUI] PanService is supported
07-28 12:31:07.337  6795  6795 D ProfileConfigQcom: Adding PanService
07-28 12:31:07.337  6795  6795 D ProfileConfigQcom: [BTUI] GattService is supported
07-28 12:31:07.337  6795  6795 D ProfileConfigQcom: Adding GattService
07-28 12:31:07.337  6795  6795 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-28 12:31:07.337  6795  6795 D ProfileConfigQcom: Adding BluetoothMapService
07-28 12:31:07.338  6795  6795 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,07-28 12:31:07.339  6795  6795 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:31:07.340  6795  6795 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:07.340  6795  6795 V BluetoothPbapReceiver: ***********state = 10
07-28 12:31:07.342  6795  6795 V LGMDMManagerInternal: Create singleton instance
,07-28 12:31:07.408  6795  6795 D LGBluetoothAPIServer: [BTUI] onCreate()
07-28 12:31:07.409  6795  6795 D LGBluetoothAPIServer: [BTUI] onBind()
07-28 12:31:07.411  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:31:07.415  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-28 12:31:07.416  1927  2107 D LGBluetoothAPIService: Message: 100
07-28 12:31:07.416  1927  2107 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-28 12:31:07.417  6108  6108 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 12:31:07.434  6108  6108 D BluetoothPermissionRequest: onReceive
,07-28 12:31:07.437  6108  6108 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 12:31:07.437  6108  6108 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-28 12:31:07.440  6108  6108 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:31:07.445  6795  6795 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-28 12:31:07.447  6795  6795 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:07.450  6795  6795 V BluetoothSapReceiver: [BTUI] checkServiceStart
,07-28 12:31:07.450  6795  6795 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,07-28 12:31:07.451  6795  6795 V BluetoothSapReceiver: SapReceiver onReceive 
,07-28 12:31:07.451  6795  6795 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:07.452  6795  6795 V BluetoothSapReceiver:  Bluetooth Adapter state = 10,
07-28 12:31:07.455  6177  6177 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings,
07-28 12:31:09.028  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop,
07-28 12:31:09.028  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,07-28 12:31:09.960  1036  6409 D LocSvc_java: requestTime failed
,07-28 12:31:09.961  1036  6409 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
,07-28 12:31:10.070  1036  1529 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,07-28 12:31:10.223  6650  6670 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-28 12:31:11.242  1036  1578 I ActivityManager: Killing 6006:com.lge.bnr/1000 (adj 15): empty #17
,07-28 12:31:11.274  1036  1993 W libprocessgroup: failed to open /acct/uid_1000/pid_6006/cgroup.procs: No such file or directory
,07-28 12:31:12.051  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:31:12.052  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ef9bdef added. We now have 6 listener(s)
,07-28 12:31:12.052  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:31:12.062  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:12.062  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e0ee0fc added. We now have 7 listener(s)
07-28 12:31:12.062  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:12.062  5840  5958 I System.out: IsBluetoothEnabled
07-28 12:31:12.063  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:12.063  1036  1052 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
07-28 12:31:12.064  1036  1108 D BluetoothManagerService: Message: 2
07-28 12:31:12.067  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:12.068  1036  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:12.068  1036  1891 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
07-28 12:31:12.083  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:31:12.083  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:31:12.083  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,07-28 12:31:12.086  1036  1108 D BluetoothManagerService: Message: 1
07-28 12:31:12.087  1036  1108 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-28 12:31:12.111  1036  1108 D BluetoothManagerService: Message: 20
07-28 12:31:12.111  1036  1108 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@56b3d2d:true
,07-28 12:31:12.114  6795  6795 D BluetoothAdapterState: make
07-28 12:31:12.119  6795  6795 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-28 12:31:12.120  6795  6795 I bluedroid-qcom: init
07-28 12:31:12.121  6795  6828 I BluetoothAdapterState: Entering OffState
07-28 12:31:12.121  6795  6795 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:31:12.121  6795  6795 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:31:12.122  6795  6795 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:31:12.122  6795  6795 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 12:31:12.122  6795  6795 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-28 12:31:12.124  6795  6795 I bluedroid-qcom: get_profile_interface socket
07-28 12:31:12.124  6795  6795 I bluedroid-qcom: get_profile_interface map_client
,07-28 12:31:12.129  6795  6832 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-28 12:31:12.131  6795  6832 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-28 12:31:12.122  6831  6831 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:12.122  6831  6831 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:12.140  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,07-28 12:31:12.146  6831  6831 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-28 12:31:12.146  6831  6831 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-28 12:31:12.146  6831  6831 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-28 12:31:12.147  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:31:12.149  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-28 12:31:12.149  1036  1108 D BluetoothManagerService: Message: 40
07-28 12:31:12.149  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-28 12:31:12.150  6795  6810 I bluedroid-qcom: config_hci_snoop_log
07-28 12:31:12.151  1036  1108 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-28 12:31:12.151  1036  1108 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-28 12:31:12.154  6831  6831 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-28 12:31:12.157  6795  6832 D BluetoothAdapterProperties: Name is: G3
07-28 12:31:12.161  6831  6831 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-28 12:31:12.161  6831  6831 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-28 12:31:12.165  6795  6828 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-28 12:31:12.165  6795  6828 D BluetoothAdapterProperties: Setting state to 11
07-28 12:31:12.165  6795  6828 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,07-28 12:31:12.168  1036  1108 D BluetoothManagerService: Message: 60
07-28 12:31:12.168  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-28 12:31:12.168  1036  1108 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-28 12:31:12.170  6795  6828 I LGBluetoothServiceJni: classInitNative: succeeds
07-28 12:31:12.177  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:12.179  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:31:12.181  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:12.190  6795  6828 D BluetoothBondStateMachine: make
,07-28 12:31:12.193  6108  6108 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-28 12:31:12.203  6795  6795 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:31:12.203  6795  6795 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:12.203  6795  6795 V BluetoothPbapReceiver: ***********state = 11
,07-28 12:31:12.207  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:31:12.210  6795  6828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
07-28 12:31:12.210  6795  6828 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-28 12:31:12.210  6795  6828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
07-28 12:31:12.210  6795  6828 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-28 12:31:12.211  6795  6828 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-28 12:31:12.211  6795  6833 I BluetoothBondStateMachine: StableState(): Entering Off State
07-28 12:31:12.215  6795  6828 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:31:12.229  6108  6108 D BluetoothPermissionRequest: onReceive
,07-28 12:31:12.230  6795  6828 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:31:12.232  6795  6795 D HeadsetService: Received start request. Starting profile...
07-28 12:31:12.232  6795  6795 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:31:12.233  6795  6795 D LGBluetoothHfpAdapter: Version 1.6
07-28 12:31:12.235  6108  6108 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:31:12.235  6795  6795 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:31:12.237  6795  6795 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:31:12.237  6795  6795 D HeadsetStateMachine: make
07-28 12:31:12.239  6795  6828 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:31:12.247  6795  6828 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:31:12.252  6795  6828 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:31:12.257  6795  6828 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:31:12.262  6795  6828 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:31:12.275  6795  6795 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:31:12.275  6795  6795 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:31:12.277  6795  6828 V LGMDMManager: Create singleton instance
,07-28 12:31:12.280  6795  6828 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-28 12:31:12.281  6795  6795 D HeadsetStateMachine: max_hf_connections = 1
07-28 12:31:12.281  6795  6795 I bluedroid-qcom: get_profile_interface handsfree
07-28 12:31:12.283  6795  6795 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-28 12:31:12.284   314  2161 V AudioPolicyService: registerClient() client 0xb0410140, uid 1002
07-28 12:31:12.284   314  1371 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:31:12.284   314  1371 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:31:12.284   314  1371 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:31:12.284  6795  6795 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 12:31:12.285   314   314 V AudioFlinger: registerClient() client 0xb55814d8, pid 6795
07-28 12:31:12.285   314  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:12.285   314  1364 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:31:12.285   314  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:12.286   314  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:31:12.286  1588  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:12.286  1588  1610 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:31:12.286  1588  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:12.286  1588  1610 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:31:12.286  1839  4330 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:12.286  1839  4330 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:31:12.286  1839  4330 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:12.286  1839  4330 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:31:12.286  6795  6795 V ToneGenerator: Create Track: 0xb4928080
07-28 12:31:12.286  6795  6795 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-28 12:31:12.286  6795  6795 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-28 12:31:12.286  3146  3167 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:12.286  6795  6811 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:12.286  3146  3167 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:31:12.286  3146  3167 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:12.286  3146  3167 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:31:12.286  6795  6811 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-28 12:31:12.287  6795  6811 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:12.287  6795  6811 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-28 12:31:12.287   314   314 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:31:12.287   314   314 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:31:12.287   314   314 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:31:12.287   314   314 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:31:12.287  1036  1924 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:31:12.287  1036  1924 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:31:12.287  1036  1924 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:31:12.287  1036  1924 V AudioSystem: ioCo,nfigChanged() opening already existing output! 4
07-28 12:31:12.287   314  1371 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:31:12.288   314  1371 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:31:12.288   314  1371 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-28 12:31:12.288   314  1371 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:31:12.288   314  1371 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:31:12.289  6795  6795 V AudioSystem: getLatency() output 2, latency 50
07-28 12:31:12.289  6795  6795 V AudioSystem: getFrameCount() output 2, frameCount 960
07-28 12:31:12.289  6795  6795 V AudioTrack: createTrack_l() output 2 afLatency 50
07-28 12:31:12.289   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:31:12.289   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:31:12.289   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:31:12.289   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:31:12.289   314   314 V AudioFlinger: createTrack() lSessionId: 23
07-28 12:31:12.290  6795  6795 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-28 12:31:12.290   314  1370 V AudioFlinger: acquiring 23 from 6795, for 6795
07-28 12:31:12.290   314  1370 V AudioFlinger:  added new entry for 23
07-28 12:31:12.290  6795  6795 V ToneGenerator: ToneGenerator INIT OK, time: 153683
07-28 12:31:12.291  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
07-28 12:31:12.292  6795  6850 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-28 12:31:12.292  6795  6850 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:31:12.292  6795  6850 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:31:12.292  6795  6850 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-28 12:31:12.293   314  1371 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6795
07-28 12:31:12.293   314  1371 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-28 12:31:12.293   314  1371 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-28 12:31:12.293   314  1371 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-28 12:31:12.293   314  1371 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-28 12:31:12.293   314  1371 V voice   : voice_set_parameters: exit with code(0)
07-28 12:31:12.293   314  1371 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-28 12:31:12.293   314  1371 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-28 12:31:12.293   314  1371 V msm8974_platform: platform_set_parameters: exit with code(0)
,07-28 12:31:12.293   314  1371 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-28 12:31:12.294   314  1371 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-28 12:31:12.294   314  1371 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-28 12:31:12.294  6795  6850 V ToneGenerator: ToneGenerator destructor
07-28 12:31:12.294  6795  6850 V ToneGenerator: stopTone
07-28 12:31:12.294  6795  6850 V ToneGenerator: Delete Track: 0xb4928080
07-28 12:31:12.298  6795  6850 V AudioTrack: ~AudioTrack, releasing session id from 6795 on behalf of 6795
07-28 12:31:12.298  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
07-28 12:31:12.298   314   314 V AudioFlinger: releasing 23 from 6795 for 6795
07-28 12:31:12.298   314   314 V AudioFlinger:  decremented refcount to 0
07-28 12:31:12.298   314   314 V AudioFlinger: purging stale effects
07-28 12:31:12.298   314   314 V AudioPolicyService: AudioCommandThread() adding release output 2
07-28 12:31:12.298   314   314 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-28 12:31:12.298   314   314 V AudioFlinger: PlaybackThread::Track destructor
07-28 12:31:12.298   314   314 V AudioFlinger: removeClient_l() pid 6795, calling pid 314
07-28 12:31:12.298   314  1126 V AudioPolicyService: AudioCommandThread() waking up
07-28 12:31:12.298   314  1126 V AudioPolicyService: AudioCommandThread() processing release output 2
07-28 12:31:12.298   314  1126 V AudioPolicyManager: releaseOutput() 2
07-28 12:31:12.298   314  1126 V AudioPolicyService: AudioCommandThread() going to sleep
07-28 12:31:12.300  6795  6795 D A2dpService: Received start request. Starting profile...
07-28 12:31:12.300  6795  6795 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 12:31:12.301  6795  6795 V Avrcp   : make
07-28 12:31:12.302  6795  6795 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-28 12:31:12.302  6795  6795 I bluedroid-qcom: get_profile_interface avrcp
07-28 12:31:12.312  6795  6795 V AudioManager: registerRemoteController: size of Media player list: 0
07-28 12:31:12.314  6795  6795 E AudioManager: No RCC entry present to update
07-28 12:31:12.314  6795  6795 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 12:31:12.318  6795  6795 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-28 12:31:12.319  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-28 12:31:12.319  6795  6795 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-28 12:31:12.324  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 12:31:12.421  1036  1936 I art     : Explicit concurrent mark sweep GC freed 33596(1634KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.591ms total 133.945ms
,07-28 12:31:12.423  1036  1924 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:31:12.423  1036  1924 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:31:12.494  1036  1891 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-28 12:31:12.501  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-28 12:31:12.504  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:31:12.505  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 12:31:12.505  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:31:12.505  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:31:12.505  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:31:12.505  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:31:12.505  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 12:31:12.505  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:31:12.505  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:31:12.505  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 12:31:12.506  6795  6795 I BluetoothA2dpServiceJni: classInitNative
07-28 12:31:12.506  6795  6795 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:31:12.506  6795  6795 D A2dpStateMachine: make
07-28 12:31:12.509  6795  6795 I bluedroid-qcom: get_profile_interface a2dp
07-28 12:31:12.509  6795  6857 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,07-28 12:31:12.512  6795  6795 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,07-28 12:31:12.512  6795  6795 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-28 12:31:12.512  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
07-28 12:31:12.513  6795  6795 I BluetoothHidServiceJni: classInitNative: succeeds
07-28 12:31:12.515  6795  6795 D HidService: Received start request. Starting profile...
07-28 12:31:12.515  6795  6795 I bluedroid-qcom: get_profile_interface hidhost
07-28 12:31:12.515  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
07-28 12:31:12.515  6795  6856 D A2dpStateMachine: Enter Disconnected: -2
07-28 12:31:12.515  6795  6795 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:31:12.516  6795  6795 D HealthService: Received start request. Starting profile...
07-28 12:31:12.520  6795  6795 I bluedroid-qcom: get_profile_interface health
07-28 12:31:12.520  6795  6795 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:31:12.520  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
07-28 12:31:12.521  6795  6795 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-28 12:31:12.522  6795  6795 D PanService: Received start request. Starting profile...
07-28 12:31:12.522  6795  6795 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:31:12.522  6795  6795 I bluedroid-qcom: get_profile_interface pan
,07-28 12:31:12.529  6795  6795 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,07-28 12:31:12.530  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
,07-28 12:31:12.533  6795  6795 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-28 12:31:12.547  6795  6795 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:31:12.548  6795  6795 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:31:12.548  6795  6795 D BtGatt.GattService: start()
07-28 12:31:12.548  6795  6795 I bluedroid-qcom: get_profile_interface gatt
07-28 12:31:12.549  6795  6795 D BtGatt.AdvertiseManager: advertise manager created
,07-28 12:31:12.562  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
,07-28 12:31:12.564  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
,07-28 12:31:12.564  6795  6795 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-28 12:31:12.565  6795  6795 V BluetoothMapService: BluetoothMapBinder()
07-28 12:31:12.566  6795  6795 D BluetoothMapService: Received start request. Starting profile...
07-28 12:31:12.566  6795  6795 D BluetoothMapService: start()
07-28 12:31:12.570  6795  6795 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-28 12:31:12.570  6795  6795 D BluetoothMapEmailAppObserver: createReceiver()
07-28 12:31:12.571  6795  6795 D BluetoothMapEmailAppObserver: initObservers()
07-28 12:31:12.572  6795  6795 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,07-28 12:31:12.583  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
07-28 12:31:12.584  6795  6795 D HeadsetStateMachine: Proxy object connected
07-28 12:31:12.585  6795  6795 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-28 12:31:12.585  6795  6795 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-28 12:31:12.591  6795  6795 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:31:12.592  6795  6850 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 12:31:12.593  6795  6850 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:31:12.594  6795  6850 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,07-28 12:31:12.595  6795  6795 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:31:12.598  6795  6795 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:31:12.601  6795  6795 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:12.606  6795  6795 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:31:12.607  6795  6795 V PanService: [BTUI] SIM Extra State :ABSENT
,07-28 12:31:12.610  6795  6795 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:31:12.614  6795  6795 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-28 12:31:12.614  6795  6795 V BluetoothMapService: Handler(): got msg=1
07-28 12:31:12.616  6795  6828 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-28 12:31:12.616  6795  6828 I bluedroid-qcom: enable
07-28 12:31:12.616  6795  6828 I bt_hci_bdroid: init
07-28 12:31:12.617  6795  6867 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 12:31:12.617  6795  6795 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:31:12.617  6795  6795 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:31:12.617  6795  6795 V BluetoothSapReceiver: SapReceiver onReceive 
,07-28 12:31:12.617  6795  6795 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:12.617  6795  6795 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-28 12:31:12.621  6795  6867 I bt-btu  : btu_task pending for preload complete event
07-28 12:31:12.622  6795  6828 I bt_vendor: bt-vendor : init
07-28 12:31:12.622  6795  6828 I bt_vendor: bt-vendor : get_bt_soc_type
07-28 12:31:12.622  6795  6828 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-28 12:31:12.624  6795  6828 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-28 12:31:12.624  6795  6828 D bt_userial_mct: userial_init
07-28 12:31:12.625  6795  6828 D bt_hci_bdroid: set_power 1
07-28 12:31:12.625  6795  6828 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-28 12:31:12.625  6795  6828 I bt_vendor: Starting hciattach daemon
07-28 12:31:12.625  6795  6828 I bt_vendor: try to set true
07-28 12:31:12.622  6870  6870 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:12.622  6870  6870 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:12.667  6871  6871 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-28 12:31:12.770  6877  6877 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-28 12:31:12.786  6878  6878 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:31:12.827  6880  6880 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:31:12.840  6881  6881 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-28 12:31:12.865  6882  6882 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:31:12.885  6883  6883 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-28 12:31:12.909  6885  6885 I libmdmdetect: ESOC framework not supported
,07-28 12:31:12.917  6885  6885 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
07-28 12:31:12.928  6885  6885 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-28 12:31:12.928  6885  6885 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-28 12:31:12.928  6885  6885 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-28 12:31:12.928  6885  6885 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-28 12:31:12.928  6885  6885 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-28 12:31:12.929  6885  6885 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-28 12:31:12.929  6885  6885 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,07-28 12:31:12.982  6885  6889 E QC-QMI  : qmi_client [6885] 15: failed to locate client data
,07-28 12:31:12.989   451   451 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-28 12:31:12.989   451   451 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
07-28 12:31:13.026  6893  6893 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-28 12:31:13.041  6894  6894 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:31:13.082  6795  6828 I bt_vendor: bluetooth satus is on
,07-28 12:31:13.082  6795  6828 D bt_hci_bdroid: preload
,07-28 12:31:13.083  6795  6869 D bt_userial_mct: userial_open(port:0)
,07-28 12:31:13.083  6795  6869 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-28 12:31:13.093  6795  6869 I bt_vendor: Done intiailizing UART
07-28 12:31:13.101  6795  6869 I bt_vendor: Done intiailizing UART
07-28 12:31:13.102  6795  6869 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-28 12:31:13.102  6795  6869 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-28 12:31:13.103  6795  6867 I bt-btu  : btu_task received preload complete event
07-28 12:31:13.104  6795  6867 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-28 12:31:13.104  6795  6867 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,07-28 12:31:13.109  6795  6867 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,07-28 12:31:13.119  6795  6896 D bt_userial_mct: Entering userial_read_thread()
,07-28 12:31:13.124  6795  6867 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 12:31:13.124  6795  6867 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-28 12:31:13.124  6795  6867 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-28 12:31:13.124  6795  6867 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-28 12:31:13.124  6795  6867 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-28 12:31:13.124  6795  6867 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:31:13.124  6795  6867 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:31:13.124  6795  6867 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:31:13.124  6795  6867 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-28 12:31:13.125  6795  6867 I         : BTE_InitTraceLevels -- TRC_GAP
,07-28 12:31:13.125  6795  6867 I         : BTE_InitTraceLevels -- TRC_PAN,
07-28 12:31:13.125  6795  6867 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:31:13.125  6795  6867 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:31:13.125  6795  6867 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:31:13.125  6795  6867 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-28 12:31:13.125  6795  6867 I         : BTE_InitTraceLevels -- TRC_BTIF
07-28 12:31:13.221  6795  6867 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-28 12:31:13.221  6795  6867 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d8061 
07-28 12:31:13.221  6795  6867 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d8061 ,
,07-28 12:31:13.253  6795  6832 E bt-btif : Calling BTA_HhEnable
07-28 12:31:13.253  6795  6832 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-28 12:31:13.253  6795  6832 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-28 12:31:13.256  6795  6867 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-28 12:31:13.256  6795  6867 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-28 12:31:13.256  6795  6867 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-28 12:31:13.258  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:31:13.258  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:31:13.258  6795  6867 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-28 12:31:13.258  6795  6867 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-28 12:31:13.259  6795  6832 D BluetoothAdapterProperties: Name is: G3
07-28 12:31:13.260  6795  6832 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:31:13.260  6795  6832 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:31:13.260  6795  6832 D bt_hci_bdroid: postload
07-28 12:31:13.261  6795  6869 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:31:13.262  6795  6869 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:31:13.262  6795  6867 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-28 12:31:13.262  6795  6832 D bte_conf: Device ID record 1 : primary
07-28 12:31:13.262  6795  6832 D bte_conf:   vendorId            = 00c4
07-28 12:31:13.262  6795  6832 D bte_conf:   vendorIdSource      = 0001
07-28 12:31:13.262  6795  6832 D bte_conf:   product             = 13a1
07-28 12:31:13.262  6795  6832 D bte_conf:   version             = 1000
07-28 12:31:13.262  6795  6832 D bte_conf:   clientExecutableURL = 
07-28 12:31:13.262  6795  6832 D bte_conf:   serviceDescription  = 
07-28 12:31:13.262  6795  6832 D bte_conf:   documentationURL    = 
,07-28 12:31:13.262  6795  6832 D bte_conf: bte_load_did_conf no section named DID2.
07-28 12:31:13.266  6795  6869 D bt_hci_bdroid: Used up Tx Cmd credits
,07-28 12:31:13.272  6795  6869 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:31:13.272  6795  6828 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 12:31:13.272  6795  6828 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:31:13.273  6795  6828 D BluetoothAdapterProperties: State =  11
07-28 12:31:13.273  6795  6828 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-28 12:31:13.273  6795  6828 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-28 12:31:13.273  6795  6828 D BluetoothAdapterProperties: Setting state to 12
07-28 12:31:13.273  6795  6828 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-28 12:31:13.274  6795  6832 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-28 12:31:13.274  6795  6832 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:31:13.262  6898  6898 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:13.277  6795  6896 E bt_mct  : hci lib postload completed
07-28 12:31:13.272  6898  6898 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:13.285  6795  6867 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:31:13.285  6795  6867 W bt-smp  : Plain text(LSB ~ MSB) = 25 68 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:31:13.285  6795  6867 W bt-smp  : Encrypted text(LSB ~ MSB) = 44 52 16 0a 14 73 ac 85 29 64 70 ff 3b 22 03 d0 
,07-28 12:31:13.289  6795  6867 W bt-btm  : Stopping oneshot timer
07-28 12:31:13.301  1036  1108 D BluetoothManagerService: Message: 60
07-28 12:31:13.301  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-28 12:31:13.301  1036  1108 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,07-28 12:31:13.304  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:31:13.305  6795  6828 I BluetoothAdapterState: Entering On State
07-28 12:31:13.315  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:13.315  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:13.315  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:13.315  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:13.315  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:13.315  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:13.315  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:13.315  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:13.318  6795  6867 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:31:13.318  6795  6867 W bt-smp  : Plain text(LSB ~ MSB) = 10 7d 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:31:13.318  6795  6867 W bt-smp  : Encrypted text(LSB ~ MSB) = fb f2 4b 28 0c b1 a5 01 b1 1e 93 c5 da 2d a7 2c 
07-28 12:31:13.318  6795  6867 W bt-btm  : Stopping oneshot timer
07-28 12:31:13.322  6795  6832 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:31:13.322  6795  6832 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-28 12:31:13.329  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:13.332  6795  6867 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:31:13.332  6795  6867 W bt-smp  : Plain text(LSB ~ MSB) = f0 90 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:31:13.332  6795  6867 W bt-smp  : Encrypted text(LSB ~ MSB) = db 01 2e 47 0a c0 ce 08 d9 03 b5 b0 11 06 7f 02 
07-28 12:31:13.333  6795  6867 W bt-btm  : Stopping oneshot timer
07-28 12:31:13.346  6795  6867 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:31:13.346  6795  6867 W bt-smp  : Plain text(LSB ~ MSB) = 5a 5c 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:31:13.346  6795  6867 W bt-smp  : Encrypted text(LSB ~ MSB) = 08 69 08 c3 e5 f2 1a 1e 60 e8 58 4f c7 f8 77 04 
,07-28 12:31:13.349  6795  6867 W bt-btm  : Stopping oneshot timer
07-28 12:31:13.350  6795  6828 D LGBluetoothServiceAdapter: [BTUI] OnState
07-28 12:31:13.350  6795  6828 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-28 12:31:13.350  6795  6828 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-28 12:31:13.351  6795  6828 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-28 12:31:13.353  1839  1839 D BluetoothHeadset: Proxy object connected
07-28 12:31:13.354  1036  1108 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:31:13.354  6795  6828 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-28 12:31:13.358  1036  1036 D BluetoothHeadset: Proxy object connected
,07-28 12:31:13.366  6108  6123 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:31:13.373  6795  6867 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:31:13.373  6795  6867 W bt-smp  : Plain text(LSB ~ MSB) = 56 a5 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:31:13.373  6795  6867 W bt-smp  : Encrypted text(LSB ~ MSB) = b6 e4 d4 39 35 d9 bf 67 4b 49 df 74 66 48 88 ef 
07-28 12:31:13.373  6795  6867 W bt-btm  : Stopping oneshot timer
,07-28 12:31:13.387  6108  6576 D BluetoothA2dp: onBluetoothStateChange: up=true,
,07-28 12:31:13.391  6108  6108 D BluetoothInputDevice: Proxy object connected
07-28 12:31:13.391  6108  6108 D HidProfile: Bluetooth service connected
07-28 12:31:13.401  6108  6123 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:31:13.409  1839  2455 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 12:31:13.413  1839  1839 D BluetoothHeadset: Proxy object connected
07-28 12:31:13.413  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:31:13.415  6108  6108 D BluetoothA2dp: Proxy object connected
07-28 12:31:13.415  6108  6108 D A2dpProfile: Bluetooth service connected
07-28 12:31:13.416  1839  1839 D BluetoothHeadset: Proxy object connected
07-28 12:31:13.417  1036  1108 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:31:13.419  1036  1036 D BluetoothA2dp: Proxy object connected
07-28 12:31:13.419  6108  6124 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:31:13.419  6108  6124 D BluetoothPan: onBluetoothStateChange call bindService
07-28 12:31:13.420  6108  6108 D BluetoothHeadset: Proxy object connected
07-28 12:31:13.420  6108  6108 D HeadsetProfile: Bluetooth service connected
,07-28 12:31:13.425  6108  6123 D BluetoothMap: onBluetoothStateChange: up=true
07-28 12:31:13.427  6108  6576 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:31:13.428  6918  6918 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-28 12:31:13.430  1036  1108 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-28 12:31:13.431  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-28 12:31:13.431  1036  1108 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-28 12:31:13.432  1036  1108 D BluetoothManagerService: Message: 40
07-28 12:31:13.432  1036  1108 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,07-28 12:31:13.432  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:13.433  1927  2107 D LGBluetoothAPIService: Message: 1
07-28 12:31:13.433  1927  2107 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-28 12:31:13.433  1927  2107 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
07-28 12:31:13.433  1927  2107 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-28 12:31:13.437  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:31:13.438  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:13.440  6795  6795 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:13.440  6795  6795 D BluetoothMapService: STATE_ON
07-28 12:31:13.445  6108  6108 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:31:13.445  6108  6108 D PanProfile: Bluetooth service connected
,07-28 12:31:13.448  6108  6108 D BluetoothMap: Proxy object connected
07-28 12:31:13.448  6108  6108 D MapProfile: Bluetooth service connected
07-28 12:31:13.448  6108  6108 D BluetoothMap: getConnectedDevices()
07-28 12:31:13.449  6795  6811 V BluetoothMapService: getConnectedDevices()
07-28 12:31:13.453  6108  6108 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-28 12:31:13.454  6108  6108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:31:13.458  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
07-28 12:31:13.458  6795  6795 V BluetoothPbapService: Pbap Service onCreate
07-28 12:31:13.458  6795  6795 V BluetoothPbapService: Starting PBAP service
,07-28 12:31:13.459  6795  6795 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-28 12:31:13.459  6795  6795 V BluetoothPbapService: Pbap Service onBind
07-28 12:31:13.461  6795  6795 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:13.461  6795  6795 V BluetoothPbapService: state: 12
07-28 12:31:13.461  6795  6795 V BluetoothMapService: Handler(): got msg=1
07-28 12:31:13.462  6795  6795 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-28 12:31:13.462  6795  6795 V BluetoothPbapService: Handler(): got msg=1
07-28 12:31:13.463  6795  6795 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-28 12:31:13.463  6795  6923 D BluetoothMapMasInstance: MAS initSocket()
07-28 12:31:13.464  6795  6795 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:31:13.464  6795  6795 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:13.464  6795  6795 V BluetoothPbapReceiver: ***********state = 12
07-28 12:31:13.464  6795  6923 D BluetoothMapMasInstance:   masId = 00
07-28 12:31:13.464  6795  6923 D BluetoothMapMasInstance:   msgTypes = 0e
07-28 12:31:13.464  6795  6923 D BluetoothMapMasInstance:   masName = SMS/MMS
07-28 12:31:13.464  6795  6923 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-28 12:31:13.465  6108  6108 D DockEventReceiver: finishStartingService: stopping service
07-28 12:31:13.465  1036  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:13.466  6108  6108 D BluetoothPbap: Proxy object connected
07-28 12:31:13.466  6108  6108 D PbapServerProfile: Bluetooth service connected
07-28 12:31:13.468  6795  6923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:31:13.469  6795  6924 V BluetoothPbapService: Pbap Service initSocket
07-28 12:31:13.471  6795  6923 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-28 12:31:13.471  6795  6923 V BluetoothMapMasInstance: Succeed to create listening socket 
07-28 12:31:13.471  6795  6923 D BluetoothMapMasInstance: Accepting socket connection...
07-28 12:31:13.471  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:13.471  2193  2193 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:31:13.472  2193  2193 D c       : Getting all permits...
,07-28 12:31:13.472  2193  2193 D a       : Opening database...
,07-28 12:31:13.475  2193  2193 D a       : Opening database auth.proximity.permit_store...
,07-28 12:31:13.476  2193  2193 D a       : Closing database...
07-28 12:31:13.477  6795  6832 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:31:13.477  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:13.477  6795  6832 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-28 12:31:13.478  6795  6924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:31:13.479  6795  6924 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-28 12:31:13.479  6795  6924 V BluetoothPbapService: Succeed to create listening socket 
07-28 12:31:13.479  6795  6924 V BluetoothPbapService: Accepting socket connection...
07-28 12:31:13.489  6108  6108 D BluetoothPermissionRequest: onReceive
,07-28 12:31:13.491  6108  6108 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 12:31:13.492  6108  6108 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:31:13.495  6795  6795 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-28 12:31:13.496  6795  6795 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-28 12:31:13.503  6795  6795 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-28 12:31:13.530  6795  6795 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,07-28 12:31:13.530  6795  6795 V BtOppService: onCreate
,07-28 12:31:13.536  6795  6795 V BluetoothOppNotification: send message
07-28 12:31:13.542  6795  6795 V BtOppService: Starting RfcommListener
07-28 12:31:13.550  6795  6795 D BluetoothOppPreference: Dumping Names:  
07-28 12:31:13.550  6795  6795 D BluetoothOppPreference: {}
07-28 12:31:13.551  6795  6795 D BluetoothOppPreference: Dumping Channels:  
07-28 12:31:13.551  6795  6795 D BluetoothOppPreference: {}
07-28 12:31:13.553  6795  6795 V BtOppService: onStartCommand
,07-28 12:31:13.557  6795  6795 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:13.558  6795  6795 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:31:13.562  6795  6795 V BluetoothOppNotification: new notify threadi!
07-28 12:31:13.563  6795  6795 V BluetoothOppNotification: send delay message
07-28 12:31:13.563  6795  6931 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:31:13.563  6795  6795 V BtOppService: start RfcommListener
07-28 12:31:13.567  6795  6795 V BtOppService: RfcommListener started
07-28 12:31:13.568  6795  6934 V BtOppRfcommListener: Starting RFCOMM listener....
07-28 12:31:13.568  1036  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:31:13.570  6795  6934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:31:13.571  6795  6934 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
07-28 12:31:13.571  6795  6934 V BtOppRfcommListener: Started RFCOMM listener....
07-28 12:31:13.571  6795  6934 I BtOppRfcommListener: Accept thread started.
07-28 12:31:13.572  6795  6934 V BtOppRfcommListener: Accepting connection...
07-28 12:31:13.579  6795  6931 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,07-28 12:31:13.581  6795  6933 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:31:13.583  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
,07-28 12:31:13.583  6795  6795 V BluetoothFtpService: Ftp Service onCreate
07-28 12:31:13.583  6795  6795 I BluetoothFtpService: Ftp Service onCreate
07-28 12:31:13.584  6795  6795 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:31:13.584  6795  6795 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:13.584  6795  6795 V BluetoothFtpService: Starting Listening on sockets
07-28 12:31:13.584  6795  6795 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:31:13.584  6795  6795 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:31:13.584  6795  6795 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:31:13.585  6795  6795 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:13.585  6795  6795 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-28 12:31:13.585  6795  6795 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:31:13.587  6795  6931 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16f9230b on behalf of 
07-28 12:31:13.587  6795  6928 V BtOppService: Deleted complete outbound shares, number =  0
07-28 12:31:13.588  6795  6795 V BluetoothFtpService: Handler(): got msg=1
07-28 12:31:13.589  6795  6795 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-28 12:31:13.589  6795  6795 V BluetoothFtpService: Ftp Service initSocket
07-28 12:31:13.591  6795  6933 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@164375e8 on behalf of 
07-28 12:31:13.592  6795  6928 V BtOppService: Deleted complete inbound failed shares, number = 0
,07-28 12:31:13.592  6795  6933 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 12:31:13.592  6795  6928 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-28 12:31:13.593  6795  6928 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22161401 on behalf of 
07-28 12:31:13.594  6795  6931 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 12:31:13.596  6795  6933 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 12:31:13.598  1036  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:13.598  6795  6933 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@374502a6 on behalf of 
07-28 12:31:13.599  6795  6795 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:31:13.599  6795  6795 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
07-28 12:31:13.600  6795  6933 V BluetoothOppNotification: outbound: succ-0  fail-0
,07-28 12:31:13.600  6795  6795 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-28 12:31:13.600  6795  6795 V BtOppService: ContentObserver received notification
07-28 12:31:13.601  6795  6933 V BluetoothOppNotification: outbound notification was removed.
07-28 12:31:13.601  6795  6933 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:31:13.601  6795  6935 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-28 12:31:13.602  6795  6933 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@194e4e7 on behalf of 
07-28 12:31:13.603  6795  6936 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:31:13.603  6795  6936 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:31:13.604  6795  6933 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:31:13.604  6795  6936 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bce0894 on behalf of 
07-28 12:31:13.605  6795  6936 V BluetoothOppNotification: update too frequent, put in queue
,07-28 12:31:13.610  6795  6936 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,07-28 12:31:13.611  6795  6933 V BluetoothOppNotification: inbound notification was removed.
07-28 12:31:13.611  6795  6933 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:31:13.612  6795  6933 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33ceef3d on behalf of 
07-28 12:31:13.618  6795  6795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ef25be
07-28 12:31:13.618  6795  6795 V BluetoothSapService: Sap Service onCreate
,07-28 12:31:13.620  6795  6795 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:13.620  6795  6795 V BluetoothSapService: state: 12
07-28 12:31:13.620  6795  6795 V BluetoothSapService: Starting SAP server process
,07-28 12:31:13.621  6795  6795 V BtOppService: ContentObserver received notification
07-28 12:31:13.622  6795  6795 V BluetoothSapService: SAP Service startRfcommListenerThread
07-28 12:31:13.623  6795  6937 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:31:13.623  6795  6937 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:31:13.624  6795  6939 V BluetoothSapService: Sap Service initRfcommSocket
07-28 12:31:13.624  1036  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:13.612  6938  6938 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:13.612  6938  6938 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:13.625  6795  6937 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1404239 on behalf of 
07-28 12:31:13.625  6795  6939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:31:13.625  6795  6937 V BluetoothOppNotification: update too frequent, put in queue
07-28 12:31:13.627  6795  6937 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 12:31:13.627  6795  6939 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
07-28 12:31:13.628  6795  6939 V BluetoothSapService: Succeed to create listening socket 
07-28 12:31:13.628  6795  6939 V BluetoothSapService: Accepting socket connection...
07-28 12:31:13.635  6938  6938 V BT_SAP  : Event pipe created
07-28 12:31:13.635  6938  6938 V BT_SAP  : create_server_socket qcom.sap.server
07-28 12:31:13.635  6938  6938 V BT_SAP  : created socket fd 6
,07-28 12:31:14.122  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:14.122  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:14.122  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:14.122  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:14.122  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:14.122  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:14.122  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:14.122  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:14.133  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:31:14.135  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:14.135  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13cac385 added. We now have 8 listener(s)
07-28 12:31:14.135  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:14.138  1036  2021 D WifiServiceImplEx: setWifiEnabled: false pid=5840, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:31:14.138  1036  2021 D WifiService: setWifiEnabled: false pid=5840, uid=10118
07-28 12:31:14.138  1036  2021 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:31:14.144  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:14.148  1036  1960 D WifiServiceImplEx: setWifiEnabled: true pid=5840, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:31:14.148  1036  1960 D WifiService: setWifiEnabled: true pid=5840, uid=10118
07-28 12:31:14.148  1036  1960 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:31:14.166  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:31:14.166  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:31:14.166  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-28 12:31:14.168  1036  1522 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-28 12:31:14.168  1036  1522 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-28 12:31:14.171  1036  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-28 12:31:14.171  1036  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:31:14.171  1036  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-28 12:31:14.171  1036  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:31:14.171  1036  1522 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-28 12:31:14.171  1036  1522 E WifiHW  : unknown target_country: EU , set to default
07-28 12:31:14.171  1036  1522 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-28 12:31:14.171  1036  1522 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-28 12:31:14.171  1036  1522 I WifiUtil: gEnableBmps=1
07-28 12:31:14.568  6795  6795 V BluetoothOppNotification: new notify threadi!
07-28 12:31:14.569  6795  6795 V BluetoothOppNotification: send delay message
,07-28 12:31:14.578  6795  6952 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,07-28 12:31:14.585  6795  6952 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d9fc07e on behalf of 
07-28 12:31:14.586  6795  6952 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-28 12:31:14.604  6795  6952 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,07-28 12:31:14.608  6795  6952 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@191f89df on behalf of 
07-28 12:31:14.609  6795  6952 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:31:14.611  6795  6952 V BluetoothOppNotification: outbound notification was removed.
07-28 12:31:14.612  6795  6952 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:31:14.613  6795  6952 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fe9d62c on behalf of 
07-28 12:31:14.614  6795  6952 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:31:14.615  6795  6952 V BluetoothOppNotification: inbound notification was removed.
07-28 12:31:14.616  6795  6952 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:31:14.617  6795  6952 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17d9c8f5 on behalf of 
,07-28 12:31:14.784   310   894 D SoftapController: Softap fwReload - Ok
,07-28 12:31:14.790  1036  1522 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (615ms)
07-28 12:31:14.798   310   894 D CommandListener: Setting iface cfg
07-28 12:31:14.798   310   894 D CommandListener: Trying to bring down wlan0
07-28 12:31:14.809  1036  1108 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:31:14.809  1036  1108 D Tethering: InitialState.processMessage what=4
07-28 12:31:14.809  1036  1108 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-28 12:31:14.825   310   894 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:31:14.868  1036  1522 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,07-28 12:31:14.862  6960  6960 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:14.878  1036  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:31:14.878  1036  1522 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:31:14.878  1036  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-28 12:31:14.872  6960  6960 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:14.893  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,07-28 12:31:14.899  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-28 12:31:14.901  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:14.902  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:14.903  1036  1522 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 12:31:14.903  1036  1522 D WifiMonitor: connecting to supplicant
07-28 12:31:14.908  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:31:14.908  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:31:14.908  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:31:14.908  6108  6108 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:31:14.909  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:31:14.910  6108  6108 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:31:14.910  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:31:14.910  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:31:14.910  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:31:14.910  6108  6108 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:31:14.910  6108  6108 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:31:14.913  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:31:14.913  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:31:14.913  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:31:14.913  6108  6108 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:31:14.914  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:31:14.914  6108  6108 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:31:14.914  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:31:14.914  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:31:14.914  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:31:14.914  6108  6108 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:31:14.915  6108  6108 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-28 12:31:14.920  6960  6960 I wpa_supplicant: Successfully initialized wpa_supplicant
07-28 12:31:14.922  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:31:14.925  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:31:14.930  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:31:14.945  6197  6979 W FormManager: Network not available. Please check & try again.
,07-28 12:31:14.948  6197  6980 V FormManager: Network unavailable.
,07-28 12:31:14.950  6197  6980 V FormManager: Network unavailable.
,07-28 12:31:14.953  6960  6960 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 12:31:14.953  6960  6960 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,07-28 12:31:14.995  6960  6960 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:31:15.011  6960  6960 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-28 12:31:15.017  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,07-28 12:31:15.018  1036  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:31:15.018  1036  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,07-28 12:31:15.019  1036  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:31:15.019  1036  1522 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:31:15.019  1036  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:31:15.019  1036  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:31:15.020  1036  1522 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-28 12:31:15.020  1036  1522 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-28 12:31:15.020  1036  1522 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-28 12:31:15.020  1036  1522 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-28 12:31:15.021  1036  1522 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-28 12:31:15.021  1036  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:31:15.021  1036  1522 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:31:15.021  1036  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:31:15.022  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.022  1036  1522 D WifiNative-wlan0: doBoolean: SET update_config 1
07-28 12:31:15.022  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.022  1036  1522 D WifiNative-wlan0: SET update_config 1: returned true
07-28 12:31:15.022  1036  1522 D WifiConfigStore: Loading config and enabling all networks 
07-28 12:31:15.022  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.022  1036  1522 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-28 12:31:15.022  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.023  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:31:15.023  1036  1522 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-28 12:31:15.024  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:15.024  1036  6981 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-28 12:31:15.024  1036  6981 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 12:31:15.025  1927  1927 D WfdService: Waiting for WifiP2p enabling
,07-28 12:31:15.030  1036  1522 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-28 12:31:15.039  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-28 12:31:15.039  1036  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-28 12:31:15.039  1036  1522 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-28 12:31:15.040  1036  1522 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:31:15.041  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:15.041  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:15.041  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:15.041  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:15.041  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:15.041  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:15.041  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:15.041  5840  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:31:15.041  1036  1522 D WifiStateMachine: enableVerboseLogging : level 2
07-28 12:31:15.041  1036  1522 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-28 12:31:15.041  1036  1522 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-28 12:31:15.042  1036  1522 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-28 12:31:15.042  1036  1522 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-28 12:31:15.042  1036  1522 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-28 12:31:15.042  1036  1522 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-28 12:31:15.042  1036  1522 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-28 12:31:15.043  1036  1522 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-28 12:31:15.043  1036  1522 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,07-28 12:31:15.043  1036  1522 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-28 12:31:15.043  1036  1522 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-28 12:31:15.044  1036  1522 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-28 12:31:15.044  1036  1522 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-28 12:31:15.044  1036  1522 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-28 12:31:15.046  1036  1522 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:31:15.046  1036  1522 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,07-28 12:31:15.046  1036  1522 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-28 12:31:15.046  1036  1522 D WifiNative-HAL: Setting external_sim to 1
07-28 12:31:15.046  1036  1522 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-28 12:31:15.047  1927  1927 D WfdsService: Supplicant Connection state is changed : true
07-28 12:31:15.047  1036  1522 D WifiNative-wlan0: SET external_sim 1: returned true
07-28 12:31:15.047  1036  1522 I WifiNative-HAL: startHal
07-28 12:31:15.047  1036  1522 D wifi    : setting scan oui 0xaf7c7a20
07-28 12:31:15.047  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-28 12:31:15.047  1927  2296 D WfdsService: Set the WFDS Monitor: true
07-28 12:31:15.048  1927  2296 D WfdsMonitor: WfdsMonitorThread create
07-28 12:31:15.048  1036  1522 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:31:15.048  1036  1522 I WifiNative-HAL: startHal
07-28 12:31:15.048  1036  1522 D wifi    : setting scan oui 0xaf7c7a20
07-28 12:31:15.048  1927  2296 D WfdsMonitor: WFDS Monitor is created and started
07-28 12:31:15.048  1927  2296 D WfdsService: WiFi: Supplicant connection re-established
07-28 12:31:15.048  1036  1522 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-28 12:31:15.049  1036  1522 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-28 12:31:15.049  1927  6982 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-28 12:31:15.049  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-28 12:31:15.049  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-28 12:31:15.050  1927  6982 E CtrlSupplicant: Succeed to open control connection
07-28 12:31:15.050  1036  1522 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-28 12:31:15.050  1927  6982 E CtrlSupplicant: Succeed to open monitor connection
07-28 12:31:15.050  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:31:15.050  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:31:15.051  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:31:15.051  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:31:15.051  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-28 12:31:15.051  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-28 12:31:15.052  1927  6982 D WfdsMonitor: Supplicant connection established
07-28 12:31:15.052  1927  2296 D WfdsService: Connected to the supplicant for wfds
07-28 12:31:15.052  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-28 12:31:15.052  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:31:15.052  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:31:15.053  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:31:15.053  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:31:15.053  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:31:15.053  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:31:15.053  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-28 12:31:15.053  6960  6960 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-28 12:31:15.054  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-28 12:31:15.054  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:31:15.054  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:31:15.054  1036  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:31:15.055  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:31:15.055  1036  1522 E WifiNative: : [156,434,082 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-28 12:31:15.,055  1036  1522 D WifiNative-wlan0: doBoolean: RECONNECT
07-28 12:31:15.056  5840  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:15.059  6960  6960 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-28 12:31:15.061  1036  1522 D WifiNative-wlan0: RECONNECT: returned true
07-28 12:31:15.061  1036  1522 D WifiNative-wlan0: doString: [STATUS]
07-28 12:31:15.062  1036  1522 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:31:15.062  1036  1522 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:31:15.062  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:31:15.062  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 12:31:15.062  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-28 12:31:15.063  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-28 12:31:15.063  1036  6981 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:31:15.063  1036  6981 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:31:15.063  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:31:15.063  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 12:31:15.064  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:15.065  1036  1522 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:31:15.065  1036  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.067   310   894 D CommandListener: Setting iface cfg
07-28 12:31:15.067   310   894 D CommandListener: Trying to bring up p2p0
07-28 12:31:15.067  1036  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 12:31:15.067  1036  1521 D LGWifiP2pService: P2pEnablingState
07-28 12:31:15.067  1036  1521 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.067  1036  1521 D LGWifiP2pService: P2p socket connection successful
07-28 12:31:15.067  1036  1521 D LGWifiP2pService: P2pEnabledState
,07-28 12:31:15.071  1036  1521 D LGWifiP2pService: sending p2p connection changed broadcast
07-28 12:31:15.074  1036  1522 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:31:15.074  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:31:15.074  1036  1522 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-28 12:31:15.074  1036  1036 D RttService: SCAN_AVAILABLE : 3
07-28 12:31:15.075  1036  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.075  1036  1541 I WifiNative-HAL: startHal
07-28 12:31:15.075  1036  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf7c7a20
07-28 12:31:15.075  1036  1541 D wifi    : failed to get capabilities : -3
07-28 12:31:15.075  1036  1541 E WifiScanningService: could not get scan capabilities
07-28 12:31:15.075  1036  1522 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-28 12:31:15.075  1036  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-28 12:31:15.075  6197  6984 W FormManager: Network not available. Please check & try again.
07-28 12:31:15.076  1036  1542 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.076  1036  1522 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-28 12:31:15.076  1036  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-28 12:31:15.076  1036  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
07-28 12:31:15.077  1036  1522 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-28 12:31:15.077  1036  1521 D WifiNative-p2p0: SET device_name G3: returned true
07-28 12:31:15.077  1036  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-28 12:31:15.077  1036  1521 D LGWifiP2pService: before postfix = G3
07-28 12:31:15.077  1036  1521 D WifiServerServiceExt: postfix byte check : 2
07-28 12:31:15.077  1036  1521 D LGWifiP2pService: after postfix = G3
07-28 12:31:15.077  1036  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-28 12:31:15.077  1036  1522 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-28 12:31:15.077  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,07-28 12:31:15.077  1927  1927 D WfdsService: WifiP2pState is changed : true
07-28 12:31:15.078  1036  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-28 12:31:15.078  1036  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-28 12:31:15.078  1036  1522 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-28 12:31:15.078  1036  1522 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-28 12:31:15.078  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-28 12:31:15.078  6960  6960 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-28 12:31:15.078  1036  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-28 12:31:15.078  1036  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-28 12:31:15.078  1036  1522 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-28 12:31:15.078  1927  1927 D WfdsService: isConnected: false
07-28 12:31:15.078  1927  2296 D WfdsService: Receive the WFDS_ENABLE Method
07-28 12:31:15.078  1927  2296 D WfdsService: Set the WFDS Monitor: true
07-28 12:31:15.078  1927  2296 D WfdsService: Connected to the supplicant for wfds
07-28 12:31:15.078  1927  2296 D WfdsJNI : doCommand: WFDS_SET TRUE
07-28 12:31:15.078  1036  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-28 12:31:15.079  6960  6960 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-28 12:31:15.079  1036  1522 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-28 12:31:15.079  1927  2296 D WfdsService: selectPreferredScanChannel [36]
07-28 12:31:15.079  1927  2296 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-28 12:31:15.079  1036  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-28 12:31:15.079  1036  1522 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-28 12:31:15.079  1036  1522 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-28 12:31:15.079  6960  6960 E wpa_supplicant: disconnect_rssi_lvl: -100
07-28 12:31:15.080  1036  1522 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:31:15.080  1036  1522 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:31:15.081  1036  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-28 12:31:15.081  1036  1521 D WifiNative-HAL: p2pGetDeviceAddress
07-28 12:31:15.081  1036  1522 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:31:15.081  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-28 12:31:15.081  1036  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-28 12:31:15.081  1036  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-28 12:31:15.082  1036  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-28 12:31:15.082  1036  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
07-28 12:31:15.082  1036  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-28 12:31:15.082  1036  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-28 12:31:15.083  1036  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-28 12:31:15.083  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:31:15.083  6960  6960 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:31:15.084  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:31:15.084  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:31:15.084  1036  6981 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:31:15.084  1036  6981 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:31:15.084  6960  6960 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:31:15.084  6960  6960 I w,pa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.085  1036  6981 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:31:15.085  1036  1522 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-28 12:31:15.085  1036  6981 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.085  1036  6981 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.085  1036  6981 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.085  1036  1522 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:31:15.085  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.086  1036  6981 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:31:15.086  1036  6981 E WifiMonitor: WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.086  1036  6981 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.086  1036  6981 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.086  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
07-28 12:31:15.086  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-28 12:31:15.086  1927  1927 D WfdsService: Update P2p Interface State: 3
07-28 12:31:15.087  1036  1522 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:31:15.087  1927  6982 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:31:15.087  1036  1522 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:31:15.087  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-28 12:31:15.087  1927  6982 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:31:15.088  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-28 12:31:15.088  6960  6960 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:31:15.088  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-28 12:31:15.088  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:31:15.088  1036  6981 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:31:15.088  1036  6981 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:31:15.089  1036  1522 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-28 12:31:15.089  1036  1522 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-28 12:31:15.089  1036  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-28 12:31:15.089  6197  6985 V FormManager: Network unavailable.
07-28 12:31:15.089  1036  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-28 12:31:15.089  1036  1522 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-28 12:31:15.090  1036  1522 D WifiNative-wlan0: doBoolean: SCAN
07-28 12:31:15.093  6197  6985 V FormManager: Network unavailable.
07-28 12:31:15.095  1036  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-28 12:31:15.095  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:31:15.095  1036  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-28 12:31:15.096  1036  1521 D LGWifiP2pService: InactiveState
07-28 12:31:15.096  4240  4240 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:31:15.096  1036  1521 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.096  1036  1521 D LGWifiP2pService: P2,pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.096  1036  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-28 12:31:15.097  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:31:15.097  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:31:15.098  6960  6960 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:31:15.098  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.099  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.099  1927  6982 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:31:15.100  1927  6982 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:31:15.100  1927  6982 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:31:15.100  1036  6981 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:31:15.100  1036  6981 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:31:15.100  1036  6981 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:31:15.100  1036  6981 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:31:15.100  1036  6981 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:31:15.100  1036  6981 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.100  1036  6981 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.100  1036  6981 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.100  1036  6981 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:31:15.100  1036  6981 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.100  1036  6981 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.100  1036  6981 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:31:15.101  1036  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-28 12:31:15.101  1036  1521 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.101  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.101  1036  1521 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.101  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.101  1036  1521 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.102  1036  1522 D WifiNative-wlan0: SCAN: returned false
07-28 12:31:15.103  1036  1521 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.103  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=156482  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:31:15.103  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.103  1036  1521 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.103  1036  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.103  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.103  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:31:15.103  1036  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.103  1036  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.104  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.104  1036  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.104  1036  1036 E WifiServerServiceExt: No p2p device connected
07-28 12:31:15.104  1927  2296 W WfdsService: DefaultState - msg [9441285] is not handled
07-28 12:31:15.105  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=156484  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:31:15.106  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=156485  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:31:15.107  4240  4240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:31:15.108  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.108  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:31:15.110  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.110  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.110  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:15.110  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:31:15.117  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=156497  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:31:15.118  1036  1522 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:31:15.119  1036  1522 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:31:15.119  1036  1522 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:31:15.119  1036  1522 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:31:15.120  1036  1522 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:31:15.121  4240  6987 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:31:15.122  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.122  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.122  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:31:15.126  4240  6988 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,07-28 12:31:15.127  4240  6988 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:31:15.131  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.131  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:31:15.133  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:15.163  1036  1560 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6989 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-28 12:31:15.165  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:31:15.165  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
07-28 12:31:15.182  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:15.182  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:15.182  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:15.182  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:15.182  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:15.182  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:15.182  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:15.182  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:15.184  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:15.190  5840  5958 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-28 12:31:15.191  5840  5958 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-28 12:31:15.193  5840  5958 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2513fed Bundle[{}]
07-28 12:31:15.194  5840  5958 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 12:31:15.194  5840  5958 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-28 12:31:15.195  5840  5958 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-28 12:31:15.195  5840  5958 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-28 12:31:15.196  5840  5958 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-28 12:31:15.197  5840  5958 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-28 12:31:15.205  5840  5958 I System.out: Running OutgoingSocketThread
07-28 12:31:15.209  5840  7006 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 771)
07-28 12:31:15.211  5840  7006 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47494
,07-28 12:31:15.211  5840  7006 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
07-28 12:31:15.292  6989  6989 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:31:15.293  6989  6989 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-28 12:31:15.307  6989  6989 V [BNRBootReceiver]: Boot Receiver Return
07-28 12:31:15.311  6989  6989 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-28 12:31:15.316  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:15.337  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:31:15.344  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:31:15.355  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:15.355  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:31:15.360  6153  6153 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:31:15.367  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:15.383  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:31:15.400  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:15.407  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:15.408  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:15.411  6153  6153 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:31:15.416  1036  1966 I ActivityManager: Killing 6464:com.lge.appbox.client/u0a11 (adj 15): empty #17
,07-28 12:31:15.459  1036  1936 W libprocessgroup: failed to open /acct/uid_10011/pid_6464/cgroup.procs: No such file or directory
,07-28 12:31:15.664  6960  6960 E wpa_supplicant: USIM:  scard_init function
,07-28 12:31:15.672  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-28 12:31:15.672  1036  6981 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-28 12:31:15.672  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-28 12:31:15.672  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: WPS-AP-AVAILABLE 
07-28 12:31:15.672  1036  6981 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-28 12:31:15.673  1036  1522 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 12:31:15.673  1036  1522 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 12:31:15.674  1036  1522 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 12:31:15.674  1036  1522 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 12:31:15.674  1036  1522 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-28 12:31:15.674  6960  6960 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-28 12:31:15.678  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:31:15.678  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-28 12:31:15.693  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=157072  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-28 12:31:15.702  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.702  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:31:15.705  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:15.707  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.708  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.708  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,07-28 12:31:15.712  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=157091  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-28 12:31:15.713  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:31:15.713  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-28 12:31:15.718  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-28 12:31:15.730  6108  6108 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-28 12:31:15.735  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:31:15.748  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:31:15.758  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:15.766  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:15.766  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:15.767  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:31:15.786  6960  6960 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-28 12:31:15.793  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-28 12:31:15.793  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-28 12:31:15.793  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-28 12:31:15.793  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-28 12:31:15.793  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:31:15.793  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:31:15.798  6960  6960 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:31:15.798  6960  6960 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:31:15.800  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=157179  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,07-28 12:31:15.804  1036  1108 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-28 12:31:15.809  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=157188  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 12:31:15.810  1036  1522 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157189
07-28 12:31:15.810  1036  1522 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157189
07-28 12:31:15.810  1036  1522 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157190
07-28 12:31:15.811  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157190
07-28 12:31:15.811  1036  1522 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=157190
07-28 12:31:15.812  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=157191  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 12:31:15.813  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:31:15.813  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:31:15.814  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-28 12:31:15.814  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:31:15.814  1036  6981 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:31:15.814  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-28 12:31:15.814  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:31:15.814  1036  6981 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:31:15.814  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:31:15.814  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,07-28 12:31:15.825  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.825  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.825  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 12:31:15.825  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.825  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.825  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-28 12:31:15.828  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.828  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-28 12:31:15.833  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:15.835  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.835  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:31:15.837  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:15.838  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=157218  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 12:31:15.839  1036  1522 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:31:15.839  1036  1522 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:31:15.839  1036  1522 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:31:15.840  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:31:15.840  1036  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:31:15.842  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:31:15.842  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,07-28 12:31:15.846  1036  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=157225  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:31:15.847  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=157226  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:31:15.848  1036  1522 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=157227
07-28 12:31:15.848  1036  1522 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=157227
07-28 12:31:15.848  1036  1522 D WifiNative-wlan0: doString: [STATUS]
07-28 12:31:15.849  1036  6981 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:31:15.849  1036  6981 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:31:15.852  1036  1522 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:31:15.853  1036  1522 I WifiServiceExtension: setVHTCapabilityType  : false
07-28 12:31:15.855  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:31:15.855  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:31:15.855  6108  6108 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:31:15.855  6108  6108 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-28 12:31:15.858  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:31:15.860  1036  1522 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-28 12:31:15.860  1036  1522 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-28 12:31:15.868  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.868  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.868  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,07-28 12:31:15.870  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.870  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:31:15.875  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.875  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.875  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:31:15.879  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:31:15.882  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.882  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:31:15.884  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:15.885  1036  1522 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-28 12:31:15.886  1036  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:31:15.886  1036  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:31:15.886  1036  1529 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:31:15.886  1036  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-28 12:31:15.886  1036  1529 D ConnectivityService: NetworkAgent connected
07-28 12:31:15.886  1036  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:31:15.886  1036  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:31:15.891  6108  6108 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:31:15.891  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-28 12:31:15.891  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:31:15.893  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:31:15.893  6108  6108 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:31:15.893  6108  6108 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-28 12:31:15.894  6108  6108 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:31:15.898  1036  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:31:15.898  1036  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:31:15.898  1036  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,07-28 12:31:15.902  1036  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:31:15.902  1036  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:31:15.908  1036  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:31:15.909  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:15.909   310   894 D CommandListener: Setting iface cfg
07-28 12:31:15.914  1036  1522 E WifiStateMachine: Start Dhcp Watchdog 2
07-28 12:31:15.915  1036  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=157294  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:31:15.915  1036  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=157294  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:31:15.916  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=157295  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:31:15.917  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,07-28 12:31:15.917  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-28 12:31:15.917  1036  7030 D DhcpStateMachine: StoppedState
07-28 12:31:15.917  1036  7030 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.917  1036  7030 D DhcpStateMachine: WaitBeforeStartState
07-28 12:31:15.919  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:31:15.920  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-28 12:31:15.920  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:31:15.922  1036  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=157301  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:31:15.922  1036  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=157301  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:31:15.922  1036  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=157302  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:31:15.923  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14069] from screen [on:0 period:823060691] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-28 12:31:15.924  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:823060692] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-28 12:31:15.924  1036  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-28 12:31:15.925  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:15.930  1036  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-28 12:31:15.930  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:31:15.931  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:15.931  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:15.932  1036  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:15.932  1036  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:15.933  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:15.933  1036  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:31:15.934  1036  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:31:15.935  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:31:15.935  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:31:15.935  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=9,0,0
07-28 12:31:15.935  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=9,0,0
07-28 12:31:15.936  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-28 12:31:15.936  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:15.936  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-28 12:31:15.936  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:15.936  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:31:15.936  1036  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-28 12:31:15.936  1036  1522 D WifiNative-wlan0: doBoolean: SET ps 0
07-28 12:31:15.939  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:15.943  1036  1522 D WifiNative-wlan0: SET ps 0: returned true
07-28 12:31:15.943  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
,07-28 12:31:15.943  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-28 12:31:15.943  1036  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-28 12:31:15.943  1036  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3a31398a target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.943  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3a31398a target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.944  1036  7030 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.944  1036  7030 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-28 12:31:15.945  1036  1522 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-28 12:31:15.945  1036  1522 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:31:15.945  1036  1522 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:31:15.946   310   894 D CommandListener: Setting iface cfg
07-28 12:31:15.946   310   894 D CommandListener: Trying to bring up wlan0
07-28 12:31:15.946  1036  1522 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-28 12:31:15.947  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:31:15.947  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:31:15.948  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
07-28 12:31:15.948  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
07-28 12:31:15.948  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:31:15.948  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:31:15.948  1036  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.948  1036  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:31:15.948  1036  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.948  1036  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-28 12:31:15.948  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-28 12:31:15.949  1036  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-28 12:31:15.949  1036  1522 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:31:15.951  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:31:15.956  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:15.961  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:15.961  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:15.961  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:31:15.964  1036  1522 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:31:15.965  1036  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:31:15.965  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:31:15.965  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:31:15.965  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:15.965  1036  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:31:15.965  1036  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:31:15.966  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,07-28 12:31:15.966  1036  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:31:15.966  1036  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:31:15.966  1036  1522 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:31:15.966  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:31:15.966  1036  1522 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-28 12:31:15.967  1036  1529 D ConnectivityService: ignoring duplicate network state non-change
07-28 12:31:15.971  1036  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-28 12:31:15.971  1036  1529 D ConnectivityService: Adding iface wlan0 to network 101
07-28 12:31:15.972  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.972  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:31:15.973  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:15.974  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.974  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.974  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:31:15.979  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.979  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-28 12:31:15.982  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:15.984  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-28 12:31:15.985  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.985  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.985  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:31:15.985  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:31:15.985  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.985  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.985  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:31:15.988  1036  1522 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-28 12:31:15.990  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:31:15.990  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.991  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.991  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:31:15.992  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:31:15.997  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.997  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:31:15.997  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:15.999  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:15.999  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.999  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:31:15.999  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:16.004  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:16.004  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:16.004  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:31:16.007  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:16.008  1036  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 12:31:16.008  1036  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-28 12:31:16.009  1036  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-28 12:31:16.010   310   894 E Netd    : netlink response contains error (File exists)
07-28 12:31:16.010  1036  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-28 12:31:16.011  1036  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-28 12:31:16.011  1036  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
07-28 12:31:16.011  1036  1529 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
07-28 12:31:16.013  1036  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:31:16.013  1036  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-28 12:31:16.013  1036  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-28 12:31:16.013  1036  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-28 12:31:16.013  1036  7017 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:16.013  1036  7017 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-28 12:31:16.013  1036  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:31:16.014  1036  7017 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:16.014  1036  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:16.014  1036  7017 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 12:31:16.014  1036  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:31:16.014  1036  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:16.014  1036  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-28 12:31:16.014  1036  1529 D ConnectivityService: currentScore = 0, newScore = 20
07-28 12:31:16.014  1036  1529 D ConnectivityService:    accepting network in place of null
07-28 12:31:16.014  1036  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:16.016  1036  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 12:31:16.016  1036  1529 ,D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 12:31:16.016  1036  1522 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:16.016  1036  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:31:16.016  1036  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:31:16.017   310  7040 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-28 12:31:16.018  1036  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:31:16.018  1036  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-28 12:31:16.018  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:16.018  1036  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-28 12:31:16.019  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:31:16.019  1036  1529 D ConnectivityService: validation of new default Network = false
07-28 12:31:16.019  1036  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-28 12:31:16.019  1036  1529 D DSQN    : enableDataServiceNotify 
07-28 12:31:16.019  1036  1529 D DSQN    : start dsqn bin
07-28 12:31:16.021  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-28 12:31:16.021  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:31:16.021  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:31:16.021  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:31:16.022  1036  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-28 12:31:16.022  1036  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:16.023  1036  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:16.023  1036  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:16.023  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:31:16.024  1588  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:31:16.012  7041  7041 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:16.012  7041  7041 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:31:16.037  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:16.038  7041  7041 E DSQN    : DSQN ssw
07-28 12:31:16.043  1036  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-28 12:31:16.049  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:16.049  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:16.049  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:31:16.054  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:16.054  1803  7045 I CheckinService: active receiver: enabled
,07-28 12:31:16.065  1803  7045 I CheckinService: Preparing to send checkin request
07-28 12:31:16.065  1803  7045 I EventLogService: Accumulating logs since 1469701163828
07-28 12:31:16.070  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:31:16.076  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:31:16.078   310  7040 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-28 12:31:16.082  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:16.082  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:16.084  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:31:16.084  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:31:16.085  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:16.086  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:16.086  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:31:16.092  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:31:16.096  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:16.101  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:16.102  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:16.103  6153  6153 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:31:16.108  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:16.110   310  7040 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-28 12:31:16.112  6091  6091 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:31:16.113  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:31:16.116  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:31:16.121  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:16.128  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:16.128  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:16.128  6153  6153 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:31:16.129  6153  6153 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:31:16.129  6153  6153 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,07-28 12:31:16.133  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:31:16.135  1803  7045 W EventLogAggregator: Unknown tag: snet_gcore
07-28 12:31:16.135  1803  7045 W EventLogAggregator: Unknown tag: snet_launch_service
07-28 12:31:16.137  6091  6091 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:31:16.138  6091  6091 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:31:16.141  6108  6108 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:31:16.143   310   893 D LGDataListener: argv[0]=dsqncommand
07-28 12:31:16.143   310   893 D LGDataListener: argv[1]=wlan0
07-28 12:31:16.143   310   893 D LGDataListener: argv[2]=1
07-28 12:31:16.143   310   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-28 12:31:16.144  1036  1106 D DSQN    : DSQM DsqnNotification wlan0  1
07-28 12:31:16.145  1036  1106 D DSQN    : start to monitor internet connection
07-28 12:31:16.146  6108  6108 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:31:16.148  1036  7030 D DhcpStateMachine: DHCPV4 request on wlan0
07-28 12:31:16.149  1036  7030 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-28 12:31:16.149  1036  7030 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-28 12:31:16.142  7049  7049 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:31:16.142  7049  7049 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:31:16.161  6153  6153 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:31:16.161  6153  6153 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:31:16.162  6153  6153 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:31:16.163  7049  7049 I dhcpcd  : version 5.5.6 starting
07-28 12:31:16.163  6153  6153 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,07-28 12:31:16.163  6153  6153 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:31:16.165  7049  7049 E dhcpcd  : get_duid: m
07-28 12:31:16.165  7049  7049 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-28 12:31:16.165  7049  7049 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,07-28 12:31:16.178  1036  7017 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:31:16 GMT], X-Android-Received-Millis=[1469701876178], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469701876143]}
07-28 12:31:16.179  1036  7017 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,07-28 12:31:16.179  1036  7017 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-28 12:31:16.179  1036  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-28 12:31:16.179  1036  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-28 12:31:16.179  1036  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:31:16.180  1036  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:16.180  1036  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:31:16.180  1036  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
07-28 12:31:16.180  1036  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-28 12:31:16.180  1036  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:16.180  1036  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:16.180  1036  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:16.181  1036  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:16.181  1588  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:31:16.181  1036  1522 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:16.181  1036  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-28 12:31:16.181  1036  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:31:16.181  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:16.183  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:31:16.188  1803  7045 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-28 12:31:16.193  1036  1528 D WifiService: New client listening to asynchronous messages
07-28 12:31:16.198  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:31:16.199  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:31:16.200  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:31:16.207  5840  5958 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 772)
,07-28 12:31:16.207  5840  5958 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 772)
07-28 12:31:16.211  5840  5958 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 777)
07-28 12:31:16.213  5840  5958 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
07-28 12:31:16.213  5840  5958 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 778)
,07-28 12:31:16.216  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:16.217  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c5f5da added. We now have 2 listener(s)
07-28 12:31:16.217  1036  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:16.221  7049  7049 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:31:16.221  7049  7049 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:31:16.221  7049  7049 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:31:16.221  7049  7049 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
,07-28 12:31:16.221  7049  7049 D dhcpcd  : wlan0: sending REQUEST (xid 0xc7728644), next in 4.80 seconds
07-28 12:31:16.222  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:31:16.222  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:16.222  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:16.222  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:16.222  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fce4a0b added. We now have 9 listener(s)
07-28 12:31:16.223  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:16.223  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:31:16.226  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:31:16.231  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:31:16.231  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:16.231  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:16.231  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:16.231  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:16.231  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:31:16.231  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:31:16.231  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:31:16.233  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:31:16.233  5840  5958 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:31:16.233  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:16.233  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f91301 added. We now have 3 listener(s)
07-28 12:31:16.234  1036  1966 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:16.234  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:16.236  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:16.236  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:31:16.236  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
07-28 12:31:16.236  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:16.236  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:16.236  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@199d95a6 added. We now have 10 listener(s)
07-28 12:31:16.236  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:16.236  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:31:16.237  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:16.237  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:31:16.237  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:16.237  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.237  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:16.237  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:16.237  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c5f5da removed from the list
07-28 12:31:16.237  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.237  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fce4a0b removed from the list
07-28 12:31:16.237  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:31:16.237  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.238  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.238  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:16.239  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:16.239  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:16.239  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.239  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fce4a0b not in the list
07-28 12:31:16.239  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.239  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.240  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:16.240  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:16.240  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.241  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@199d95a6 removed from the list
07-28 12:31:16.241  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:16.241  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.241  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.241  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:16.241  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f91301 removed from the list
07-28 12:31:16.241  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:16.241  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10157be7 added. We now have 2 listener(s)
07-28 12:31:16.242  1036  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:16.245  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:31:16.245  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:16.245  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:16.245  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:16.245  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20905394 added. We now have 9 listener(s)
07-28 12:31:16.245  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:16.245  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:31:16.246  7049  7049 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
07-28 12:31:16.248  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:31:16.251  5840  5958 V io.jxcore.node.ConnectivityMonitor,: updateConnectivityInfo: FORCED notification:
07-28 12:31:16.251  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:16.251  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:16.251  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:16.251  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:16.251  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:31:16.251  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:31:16.251  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:31:16.253  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:31:16.253  5840  5958 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:31:16.253  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:16.253  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfd6632 added. We now have 3 listener(s)
07-28 12:31:16.253  1036  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:16.255  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:16.256  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:31:16.256  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:16.256  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:16.257  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:16.257  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39b3ef83 added. We now have 10 listener(s)
07-28 12:31:16.257  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:16.257  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:31:16.257  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:31:16.257  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:16.257  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:31:16.257  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:31:16.257  7049  7049 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-28 12:31:16.257  7049  7049 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-28 12:31:16.258  7049  7049 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-28 12:31:16.258  7049  7049 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-28 12:31:16.258  7049  7049 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:31:16.258  7049  7049 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:31:16.258  7049  7049 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:31:16.258  7049  7049 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-28 12:31:16.257  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:31:16.261  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:31:16.262  1036  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:16.266  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseS,ettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:31:16.267  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:31:16.269  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:31:16.269  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:16.271  5840  5958 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:31:16.272  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:16.272  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:31:16.273  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:31:16.273  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:16.273  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:31:16.273  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:16.273  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.273  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:16.274  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:16.274  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10157be7 removed from the list
07-28 12:31:16.274  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.274  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20905394 removed from the list
07-28 12:31:16.274  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:31:16.274  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.274  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.274  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.275  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:16.275  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:16.275  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.275  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20905394 not in the list
07-28 12:31:16.275  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.275  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.277  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:16.278  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:31:16.278  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stop,ped
07-28 12:31:16.278  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:16.278  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.278  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39b3ef83 removed from the list
07-28 12:31:16.278  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:16.278  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.278  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.278  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:16.278  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfd6632 removed from the list
07-28 12:31:16.279  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:16.279  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a17b37e added. We now have 2 listener(s)
07-28 12:31:16.279  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:31:16.283  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:31:16.283  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:16.283  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:16.283  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:16.283  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163c00df added. We now have 9 listener(s)
07-28 12:31:16.283  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:16.286  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:31:16.288  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:31:16.292  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:31:16.292  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:16.292  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:16.292  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:16.292  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:16.292  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:31:16.292  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:31:16.292  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:31:16.294  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:31:16.295  5840  5958 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:31:16.296  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:31:16.296  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@161c97f5 added. We now have 3 listener(s)
07-28 12:31:16.299  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:16.300  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:16.352  1036  1578 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7065 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-28 12:31:16.357  1036  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:16.361  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:31:16.361  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
07-28 12:31:16.361  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:16.361  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:16.361  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf7898a added. We now have 10 listener(s)
07-28 12:31:16.361  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:16.362  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:31:16.362  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:31:16.362  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:31:16.362  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:31:16.363  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:31:16.363  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:31:16.367  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:31:16.367  1036  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:31:16.372  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:31:16.372  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:31:16.374  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:31:16.375  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:16.378  5840  5958 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:31:16.378  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:31:16.378   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 434us total 19.592ms
07-28 12:31:16.378  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:16.378  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:31:16.379  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:16.379  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:31:16.379  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:31:16.379  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:16.379  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a17b37e removed from the list
07-28 12:31:16.379  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.379  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163c00df removed from the list
07-28 12:31:16.379  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:31:16.379  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.380  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.380  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:16.383  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:16.383  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:16.383  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.383  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163c00df not in the list
07-28 12:31:16.383  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.383  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.384  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:16.385  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:31:16.385  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:31:16.385  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:16.385  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.385  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf7898a removed from the list
07-28 12:31:16.385  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:16.385  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.385  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.385  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:16.385  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@161c97f5 removed from the list
07-28 12:31:16.386  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:16.386  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@136bbe71 added. We now have 2 listener(s)
07-28 12:31:16.387  1036  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:16.390  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:31:16.390  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:16.390  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:16.390  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:16.390  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154cb456 added. We now have 9 listener(s)
07-28 12:31:16.390  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:16.391  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:31:16.396   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) All,ocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 382us total 17.079ms
07-28 12:31:16.397  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:31:16.400  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:31:16.400  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:16.400  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:16.400  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:16.400  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:16.400  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:31:16.400  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:31:16.400  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:31:16.403  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:31:16.403  5840  5958 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:31:16.403  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:16.403  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f39c9c4 added. We now have 3 listener(s)
,07-28 12:31:16.404  1036  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:16.405  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:16.407  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:16.410  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:31:16.410  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:16.410  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:16.410  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:16.410  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18acd0ad added. We now have 10 listener(s)
07-28 12:31:16.410  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:16.410  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:31:16.410  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,07-28 12:31:16.410  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:31:16.410  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:31:16.410  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:31:16.411   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 297us total 13.806ms
07-28 12:31:16.413  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:31:16.417  1036  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:16.420  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:31:16.421  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:31:16.421  7065  7065 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-28 12:31:16.422  7065  7065 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-28 12:31:16.424  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:31:16.424  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:16.426  5840  5958 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:31:16.427  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:31:16.427  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:16.427  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:31:16.428  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:16.428  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.428  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:16.428  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:16.428  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@136bbe71 removed from the list
07-28 12:31:16.428  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.428  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154cb456 removed from the list
07-28 12:31:16.428  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:31:16.428  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.428  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.428  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.429  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:16.429  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:16.429  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.429  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154cb456 not in the list
07-28 12:31:16.429  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.429  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.429  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:16.430  5840  5958 D BluetoothLeScanner: could not find callback wrapper
07-28 12:31:16.430  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:31:16.430  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:16.430  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.430  5840  5958 V org.thaliproject.,p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18acd0ad removed from the list
07-28 12:31:16.430  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:16.430  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.430  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.430  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:16.430  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f39c9c4 removed from the list
07-28 12:31:16.431  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:16.431  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26ebbe30 added. We now have 2 listener(s)
07-28 12:31:16.431  1036  2021 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:16.433  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:31:16.433  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:16.433  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:16.433  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:16.433  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f72caa9 added. We now have 9 listener(s)
07-28 12:31:16.433  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:16.434  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:31:16.435  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:31:16.438  5840  5958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:31:16.438  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:16.438  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:16.438  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:16.438  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:16.438  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:31:16.438  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:31:16.438  5840  5958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:31:16.439  5840  5958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:31:16.439  5840  5958 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:31:16.440  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:16.440  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28ccdfcf added. We now have 3 listener(s)
07-28 12:31:16.440  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:31:16.441  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:16.443  5840  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:16.444  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:31:16.444  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:16.444  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:16.444  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:16.444  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34868d5c added. We now have 10 listener(s)
07-28 12:31:16.444  5840  5958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:16.444  5840  5958 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:31:16.444  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:16.444  5840  5958 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:31:16.444  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:16.444  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.445  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:16.445  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:16.445  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26ebbe30 removed from the list
07-28 12:31:16.445  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.445  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f72caa9 removed from the list
07-28 12:31:16.445  5840  5958 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:31:16.445  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.446  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.446  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.446  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:31:16.446  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:16.446  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.446  5840  5958 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f72caa9 not in the list
07-28 12:31:16.446  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.446  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.449  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:16.449  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:16.449  5840  5958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:16.449  5840  5958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34868d5c removed from the list
07-28 12:31:16.449  5840  5958 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:16.449  5840  5958 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:16.449  5840  5958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:16.449  5840  5958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:16.449  5840  5958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28ccdfcf removed from the list
07-28 12:31:16.450  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 12:31:16.450  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-28 12:31:16.450  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-28 12:31:16.450  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:31:16.450  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-28 12:31:16.450  5840  5958 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:16.458  5840  7093 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 785, name: My test thread name)
07-28 12:31:16.458  5840  7093 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 785, thread name: My test thread name)
07-28 12:31:16.458  5840  7093 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 785, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,07-28 12:31:16.463  7065  7065 I MultiDex: VM with version 2.1.0 has multidex support
07-28 12:31:16.463  7065  7065 I MultiDex: install
07-28 12:31:16.463  7065  7065 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-28 12:31:16.464  5840  7094 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 787, name: My test thread name)
07-28 12:31:16.464  5840  7094 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 787, thread name: My test thread name)
07-28 12:31:16.464  5840  7094 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 787, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
07-28 12:31:16.466  5840  5958 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
07-28 12:31:16.466  5840  5958 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
07-28 12:31:16.466  5840  5958 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-28 12:31:16.466  5840  5958 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-28 12:31:16.466  5840  5958 D com.test.thalitest.ThaliTestRunner: Total duration: 22768 ms
07-28 12:31:16.467  5840  5958 I jxcore-log: Total number of executed tests:  80
07-28 12:31:16.467  5840  5958 I jxcore-log: 
07-28 12:31:16.468  5840  5958 I jxcore-log: Number of passed tests:  80
07-28 12:31:16.468  5840  5958 I jxcore-log: 
07-28 12:31:16.468  5840  5958 I jxcore-log: Number of failed tests:  0
07-28 12:31:16.468  5840  5958 I jxcore-log: 
07-28 12:31:16.468  5840  5958 I jxcore-log: Number of ignored tests:  0
07-28 12:31:16.468  5840  5958 I jxcore-log: 
07-28 12:31:16.468  5840  5958 I jxcore-log: Total duration:  22768
07-28 12:31:16.468  5840  5958 I jxcore-log: 
07-28 12:31:16.468  5840  5958 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-28 12:31:16.468  5840  5958 I jxcore-log: 
07-28 12:31:16.470  5840  5958 I jxcore-log: Unit Test app is loaded
07-28 12:31:16.470  5840  5958 I jxcore-log: 
,07-28 12:31:16.473  7065  7065 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
07-28 12:31:16.476  2193  2193 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-28 12:31:16.480  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:16.480  5840  5958 I jxcore-log: 
07-28 12:31:16.483  5840  5840 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-28 12:31:16.484  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:16.484  5840  5958 I jxcore-log: 
07-28 12:31:16.484  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:16.484  5840  5958 I jxcore-log: 
07-28 12:31:16.486  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:16.486  5840  5958 I jxcore-log: 
07-28 12:31:16.487  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:16.487  5840  5958 I jxcore-log: 
07-28 12:31:16.488  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:16.488  5840  5958 I jxcore-log: 
07-28 12:31:16.489  2193  2193 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
07-28 12:31:16.489  2193  2193 D c       : Getting all permits...
07-28 12:31:16.489  2193  2193 D a       : Opening database...
07-28 12:31:16.490  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:16.490  5840  5958 I jxcore-log: 
07-28 12:31:16.492  2193  2193 D a       : Opening database auth.proximity.permit_store...
07-28 12:31:16.492  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:31:16.492  5840  5958 I jxcore-log: 
07-28 12:31:16.492  2193  2193 D a       : Closing database...
07-28 12:31:16.492  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:31:16.492  5840  5958 I jxcore-log: 
07-28 12:31:16.493  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:31:16.493  5840  5958 I jxcore-log: 
07-28 12:31:16.494  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:31:16.494  5840  5958 I jxcore-log: 
07-28 12:31:16.497  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:16.497  5840  5958 I jxcore-log: 
07-28 12:31:16.497  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:16.497  5840  5958 I jxcore-log: 
,07-28 12:31:16.498  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:31:16.498  5840  5958 I jxcore-log: 
07-28 12:31:16.499  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:31:16.499  5840  5958 I jxcore-log: 
07-28 12:31:16.499  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:16.499  5840  5958 I jxcore-log: 
07-28 12:31:16.500  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:16.500  5840  5958 I jxcore-log: 
07-28 12:31:16.500  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:31:16.500  5840  5958 I jxcore-log: 
07-28 12:31:16.501  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:31:16.501  5840  5958 I jxcore-log: 
07-28 12:31:16.501  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:16.501  5840  5958 I jxcore-log: 
07-28 12:31:16.502  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:16.502  5840  5958 I jxcore-log: 
07-28 12:31:16.503  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:31:16.503  5840  5958 I jxcore-log: 
07-28 12:31:16.504  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:31:16.504  5840  5958 I jxcore-log: 
07-28 12:31:16.504  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:31:16.504  5840  5958 I jxcore-log: 
07-28 12:31:16.505  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:31:16.505  5840  5958 I jxcore-log: 
07-28 12:31:16.505  5840  5958 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:31:16.505  5840  5958 I jxcore-log: 
07-28 12:31:16.508  5840  5958 I jxcore-log: My device name is: LGE-LG-D855
07-28 12:31:16.508  5840  5958 I jxcore-log: 
07-28 12:31:16.509  5840  5958 I jxcore-log: WARN testUtils: myNameCallback not set!
07-28 12:31:16.509  5840  5958 I jxcore-log: 
07-28 12:31:16.553  1036  7030 D DhcpStateMachine: DHCPV4 succeeded on wlan0
07-28 12:31:16.555  1036  7030 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-28 12:31:16.555  1036  7030 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:31:16.555  1036  7030 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-28 12:31:16.555  1036  7030 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-28 12:31:16.555  1036  7030 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:31:16.555  1036  7030 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-28 12:31:16.555  1036  7030 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-28 12:31:16.555  1036  7030 D DhcpStateMachine: RunningState
,07-28 12:31:16.869  7100  7100 D AndroidRuntime: 
07-28 12:31:16.869  7100  7100 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 12:31:16.872  7100  7100 D AndroidRuntime: CheckJNI is OFF
,07-28 12:31:16.897  7065  7084 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:31:16.897  7065  7084 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:31:16.974  7115  7115 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
07-28 12:31:16.993  7100  7100 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-28 12:31:17.009  1036  1099 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
07-28 12:31:17.009  1036  1099 I ActivityManager: Killing 5840:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,07-28 12:31:17.032  7115  7115 I dex2oat : dex2oat took 58.140ms (threads: 4)
,07-28 12:31:17.042  7065  7084 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:31:17.042  7065  7084 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:31:17.042  7065  7084 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:31:17.042  7065  7084 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:31:17.042  7065  7084 I Adreno-EGL: Remote Branch: 
07-28 12:31:17.042  7065  7084 I Adreno-EGL: Local Patches: 
07-28 12:31:17.042  7065  7084 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:31:17.062  1036  1578 I WindowState: WIN DEATH: Window{264a2425 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-28 12:31:17.068  1036  1528 D WifiService: Client connection lost with reason: 4
07-28 12:31:17.069  1036  1578 D InputDispatcher: Window went away: Window{264a2425 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-28 12:31:17.129  7065  7084 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:31:17.129  7065  7084 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:31:17.129  7065  7084 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:31:17.129  7065  7084 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:31:17.129  7065  7084 I Adreno-EGL: Remote Branch: 
07-28 12:31:17.129  7065  7084 I Adreno-EGL: Local Patches: 
07-28 12:31:17.129  7065  7084 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:31:17.223  1036  1099 I ActivityManager:   Force finishing activity ActivityRecord{85bf266 u0 com.test.thalitest/.MainActivity t40}
,07-28 12:31:17.277   335   349 E GBMv2   : DFP En is all cleared set to be enabled
07-28 12:31:17.279  1036  1763 W ActivityManager: Spurious death for ProcessRecord{250cd3db 5840:com.test.thalitest/u0a118}, curProc for 5840: null
,07-28 12:31:17.281  1036  1127 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
07-28 12:31:17.286  1036  1127 I ActivityManager:   Force finishing activity ActivityRecord{85bf266 u0 com.test.thalitest/.MainActivity t40 f}
07-28 12:31:17.286  1036  1127 W ActivityManager: Duplicate finish request for ActivityRecord{85bf266 u0 com.test.thalitest/.MainActivity t40 f}
,07-28 12:31:17.302  2018  2018 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
07-28 12:31:17.303  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
07-28 12:31:17.303  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3319d442 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-28 12:31:17.304  2018  2018 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
07-28 12:31:17.305  1927  3882 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
07-28 12:31:17.305  1927  3882 D SplitWindowPolicy: topRunningActivity=ActivityInfo{db7ac53 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
,07-28 12:31:17.307  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
07-28 12:31:17.309  2018  2090 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
07-28 12:31:17.312  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-28 12:31:17.318  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-28 12:31:17.318  3724  3724 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
07-28 12:31:17.320  6795  6795 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
07-28 12:31:17.320  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,07-28 12:31:17.331  1036  1098 W InputMethodInfo: Duplicated subtype definition found: , voice
07-28 12:31:17.332  3627  3627 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
07-28 12:31:17.343  4376  4376 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-28 12:31:17.344  4376  4376 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-28 12:31:17.344  4376  4376 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
,07-28 12:31:17.344  4376  4376 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
07-28 12:31:17.344  4376  4376 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:31:17.344  4376  4376 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:31:17.344  4376  4376 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:31:17.344  4376  4376 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:31:17.344  4376  4376 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:17.344  4376  4376 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:17.344  4376  4376 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:31:17.344  4376  4376 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:31:17.362  4509  4509 I art     : Explicit concurrent mark sweep GC freed 738(41KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 659us total 67.253ms
,07-28 12:31:17.385  1036  1763 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7130 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-28 12:31:17.395  7065  7084 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:31:17.395  7065  7084 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:31:17.395  7065  7084 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:31:17.395  7065  7084 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:31:17.395  7065  7084 I Adreno-EGL: Remote Branch: 
07-28 12:31:17.395  7065  7084 I Adreno-EGL: Local Patches: 
07-28 12:31:17.395  7065  7084 I Adreno-EGL: Reconstruct Branch: 
07-28 12:31:17.407  1892  1892 D ActionManagerService: notifyUserLog: 1000003
07-28 12:31:17.407  1803  1803 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,07-28 12:31:17.408  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
07-28 12:31:17.410  2018  2018 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-28 12:31:17.412  2018  2018 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
07-28 12:31:17.413  2494  2632 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-28 12:31:17.414  3724  4402 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
07-28 12:31:17.415  2018  2018 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
07-28 12:31:17.416  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-28 12:31:17.418  2193  2193 I ConfigService: onCreate
,07-28 12:31:17.419  2193  2193 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-28 12:31:17.419  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,07-28 12:31:17.421  1892  1892 D ActionManagerService: notifyUserLog: 1000004
07-28 12:31:17.423  3724  3739 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:31:17.424  3724  4402 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
07-28 12:31:17.427  2193  2193 I ConfigService: onBind returning update interface
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262123
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , expire_time: 0
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , display: false
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , animation: false }
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262287
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , expire_time: 0
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , display: false
07-28 12:31:17.432  2018  2018 I GBoardWebViewUtils: , animation: false }
07-28 12:31:17.433  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469186101390
07-28 12:31:17.433  2018  2018 I GBoardWebViewUtils: , create_time: 1469186101943
07-28 12:31:17.433  2018  2018 I GBoardWebViewUtils: , expire_time: 0
07-28 12:31:17.433  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-28 12:31:17.433  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-28 12:31:17.433  2018  2018 I GBoardWebViewUtils: , display: false
07-28 12:31:17.433  2018  2018 I GBoardWebViewUtils: , animation: false }
,07-28 12:31:17.437  2193  2193 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-28 12:31:17.437  2193  2193 I ConfigService: onBind returning config service
07-28 12:31:17.440  1803  1803 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-28 12:31:17.442  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-28 12:31:17.442  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-28 12:31:17.452  2018  7148 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,07-28 12:31:17.457  1856  1856 D SplitUIManager: split_name #11 / not available #0
07-28 12:31:17.457  1036  1890 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:31:17.457  1856  1856 D SplitUIService: removed split : 
07-28 12:31:17.460  1803  1803 I ConfigFetchService: service connected
07-28 12:31:17.461  1803  1803 I ConfigClient: service connected
07-28 12:31:17.471  1036  1960 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:31:17.471  1036  1960 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:31:17.474  2193  2193 I ConfigService: onDestroy
07-28 12:31:17.498  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-28 12:31:17.498  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,07-28 12:31:17.511  1803  7150 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-28 12:31:17.521  1856  1856 D SplitUIManager: split_name #11 / not available #0
07-28 12:31:17.521  1856  1856 I SplitUIService: split app #11
,07-28 12:31:17.528  1036  1414 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-28 12:31:17.553  1036  1578 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7154 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-28 12:31:17.554  1036  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-28 12:31:17.554  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-28 12:31:17.554  7130  7130 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
07-28 12:31:17.555  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:31:17.555  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 12:31:17.555  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:31:17.555  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:31:17.555  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:31:17.555  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:31:17.555  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 12:31:17.555  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:31:17.555  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:31:17.555  6795  6795 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 12:31:17.558  1036  1036 D administrator: Handling package changes for user 0
07-28 12:31:17.567  1588  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-28 12:31:17.567  1588  1641 D KeyguardModel: createShortcutInfo...
,07-28 12:31:17.568  1588  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-28 12:31:17.568  1588  1641 D KeyguardModel: createShortcutInfo...
07-28 12:31:17.572  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-28 12:31:17.572  1588  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:31:17.572  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-28 12:31:17.573  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:31:17.587  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:31:17.588  1588  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,07-28 12:31:17.591  1588  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-28 12:31:17.591  1588  1641 D KeyguardModel: createShortcutInfo...
07-28 12:31:17.593  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-28 12:31:17.593  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:31:17.598  1036  1522 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:31:17.598  1036  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:31:17.599  1036  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:31:17.599  1036  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:31:17.599  1036  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:31:17.600  1036  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,07-28 12:31:17.600  1036  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
07-28 12:31:17.600  1036  1529 D ConnectivityService: identical MTU - not setting
07-28 12:31:17.600   328   415 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-28 12:31:17.600  1036  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:31:17.600  1036  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-28 12:31:17.600  1036  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:17.600  3226  7174 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-28 12:31:17.600  1036  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:17.601  1036  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:17.602  5445  7171 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
07-28 12:31:17.603  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:31:17.603  1588  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-28 12:31:17.604  1588  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-28 12:31:17.610  1588  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-28 12:31:17.610  1588  1641 D KeyguardModel: createShortcutInfo...
07-28 12:31:17.612  1036  2033 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:31:17.614  1588  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:31:17.614  1588  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-28 12:31:17.614  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-28 12:31:17.614  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:31:17.616  1803  7153 I art     : Explicit concurrent mark sweep GC freed 19712(1378KB) AllocSpace objects, 18(288KB) LOS objects, 51% free, 29MB/61MB, paused 7.518ms total 59.315ms
,07-28 12:31:17.621  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:31:17.621  1588  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-28 12:31:17.622  1588  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-28 12:31:17.622  1588  1641 D KeyguardModel: createShortcutInfo...
07-28 12:31:17.630  1803  7176 I PeopleContactsSync: CP2 sync disabled
,07-28 12:31:17.635  1588  1588 D KeyguardModel: handleShortcutListChanged...
07-28 12:31:17.635  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-28 12:31:17.644  1588  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-28 12:31:17.644  1588  1641 D KeyguardModel: createShortcutInfo...
07-28 12:31:17.648  1588  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,07-28 12:31:17.648  1588  1641 D KeyguardModel: createShortcutInfo...
,07-28 12:31:17.651  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:31:17.651  1588  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-28 12:31:17.652  1588  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-28 12:31:17.652  1588  1641 D KeyguardModel: createShortcutInfo...
07-28 12:31:17.653  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:31:17.653  1588  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-28 12:31:17.654  1588  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-28 12:31:17.654  1588  1641 D KeyguardModel: createShortcutInfo...
07-28 12:31:17.655  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:31:17.655  1588  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-28 12:31:17.658  1588  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
,07-28 12:31:17.658  1588  1641 D KeyguardModel: createShortcutInfo...
07-28 12:31:17.659  1803  7175 W GmsApplication: Using Auth Proxy for data requests.
07-28 12:31:17.663  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-28 12:31:17.664  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-28 12:31:17.664  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-28 12:31:17.665  1803  7175 W GmsApplication: Using Auth Proxy for data requests.
,07-28 12:31:17.667  1803  4629 I Icing   : doRemovePackageData com.test.thalitest
07-28 12:31:17.677  1036  1562 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
,07-28 12:31:17.688  1036  1763 I ActivityManager: Killing 6492:com.lge.email/u0a23 (adj 15): empty #17
07-28 12:31:17.705  7154  7154 I AppUp4:AppBoxCP: onCreate
07-28 12:31:17.706  7154  7154 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-28 12:31:17.712  7154  7154 I AppUp4:DB:  setFingerPrint start
07-28 12:31:17.712  7154  7154 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,07-28 12:31:17.717  7154  7154 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-28 12:31:17.717  7154  7154 I AppUp4:DB:  SDK version = 21
07-28 12:31:17.717  7154  7154 I AppUp4:DB:  beforefinger == newfinger no write in DB
,07-28 12:31:17.731  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,07-28 12:31:17.735  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 12:31:17.736  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
07-28 12:31:17.737  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-28 12:31:17.738  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-28 12:31:17.740  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
07-28 12:31:17.756  2018  2018 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,07-28 12:31:17.767  1036  1127 I art     : Explicit concurrent mark sweep GC freed 86748(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 1.909ms total 446.085ms
07-28 12:31:17.768  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
07-28 12:31:17.768  2018  2760 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
07-28 12:31:17.768  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:31:17.768  2018  2760 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
07-28 12:31:17.772  1588  1588 D KeyguardModel: handleShortcutListChanged...
07-28 12:31:17.772  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-28 12:31:17.772  1036  1993 W libprocessgroup: failed to open /acct/uid_10023/pid_6492/cgroup.procs: No such file or directory
07-28 12:31:17.775  1036  1109 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36d2a6fa u0 com.lge.launcher2/.Launcher t39} time:159167
07-28 12:31:17.787  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
07-28 12:31:17.788  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-28 12:31:17.788  7154  7154 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,07-28 12:31:17.789  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:31:17.802  2018  2018 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
07-28 12:31:17.804  2608  2608 D [Concierge]Service: onStartCommand(). Type : 8
07-28 12:31:17.804  2608  2608 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
07-28 12:31:17.805  2608  2608 D [Concierge]Service: Update widget ID : 11
07-28 12:31:17.806  2018  2018 D [Concierge]WidgetView: change position of spinner
07-28 12:31:17.808  2608  2608 D [Concierge]Service: onStartCommand(). Type : 0
07-28 12:31:17.809  2018  2018 I [Concierge]WidgetView: initWebView(). Time : 1469701877809
07-28 12:31:17.814  7100  7100 D AndroidRuntime: Shutting down VM
,07-28 12:31:17.837  1036  1098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:31:17.843  7154  7154 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
07-28 12:31:17.845  1036  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-28 12:31:17.863  1036  1127 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7181 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-28 12:31:17.894  1036  2033 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7198 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,07-28 12:31:17.896  1036  2033 I ActivityManager: Killing 6548:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,07-28 12:31:17.970  1036  2021 W libprocessgroup: failed to open /acct/uid_10046/pid_6548/cgroup.procs: No such file or directory
,07-28 12:31:17.972  2018  2018 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 974027466
07-28 12:31:17.972  2018  2018 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
07-28 12:31:17.972  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-28 12:31:17.975  2018  2018 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@994f42
07-28 12:31:17.975  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
07-28 12:31:17.976  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-28 12:31:17.976  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:31:17.982  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-28 12:31:17.983  2018  2018 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,07-28 12:31:17.983  2018  2018 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1469701746738, New one : 1469701877809
07-28 12:31:17.983  2018  2018 D [Concierge]WidgetView: Unregister all receivers
07-28 12:31:17.983  2018  2018 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-28 12:31:17.984  2018  2018 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
07-28 12:31:17.984  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-28 12:31:17.985  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:31:17.987  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-28 12:31:17.988  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
07-28 12:31:17.990  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
07-28 12:31:17.991  1036  1051 I ActivityManager: Killing 6578:com.android.chrome/u0a57 (adj 15): empty #17
07-28 12:31:17.991  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
07-28 12:31:17.992  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
07-28 12:31:17.993  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:31:17.993  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:31:17.995  7198  7198 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:31:18.000  7198  7198 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:31:18.000  7198  7198 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-28 12:31:18.001  7198  7198 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-28 12:31:18.001  7198  7198 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 12:31:18.026  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,07-28 12:31:18.033  2018  2018 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-28 12:31:18.033  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
07-28 12:31:18.035  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 12:31:18.039  1036  2021 W libprocessgroup: failed to open /acct/uid_10057/pid_6578/cgroup.procs: No such file or directory
07-28 12:31:18.054  2018  2018 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@11fcf873 time:159446
,07-28 12:31:18.056  2193  2340 I art     : Explicit concurrent mark sweep GC freed 4191(237KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 28MB/60MB, paused 831us total 16.246ms
07-28 12:31:18.066   310  7218 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-28 12:31:18.066   310  7218 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,07-28 12:31:18.072  7198  7198 I SystemConfig: BUILD Country: EU
07-28 12:31:18.072  7198  7198 I SystemConfig: BUILD Operator: OPEN
07-28 12:31:18.104   310  7218 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-28 12:31:18.106  1036  1560 I ActivityManager: Killing 6611:com.lge.drmservice/u0a62 (adj 15): empty #17
,07-28 12:31:18.187  2018  2018 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)

```
