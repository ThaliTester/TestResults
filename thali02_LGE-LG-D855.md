#### Test 81418577b213184_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-29 11:25:21.620  5863  5863 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:25:21.620  5863  5863 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:25:21.686  5863  5863 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-29 11:25:21.705  5863  5863 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 11:25:21.706  5863  5863 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 11:25:21.723  5863  5863 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 11:25:21.723  5863  5863 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
08-29 11:25:21.740  1031  1955 I ActivityManager: Killing 5297:com.lge.clock/u0a10 (adj 15): empty #17
08-29 11:25:21.773  1031  1588 W libprocessgroup: failed to open /acct/uid_10010/pid_5297/cgroup.procs: No such file or directory
08-29 11:25:21.789  4513  5912 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-29 11:25:21.797  3335  3354 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-29 11:25:21.799  3335  3354 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@37975b8f on behalf of 5863
08-29 11:25:21.840  1031  1919 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5913 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 11:25:21.876  5863  5863 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-29 11:25:21.906  5863  5863 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-29 11:25:22.126  5913  5913 D DocsApplication: Installing DEX configuration.
08-29 11:25:22.141  5913  5913 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-29 11:25:22.144  5913  5913 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{348bdf42 com.google.android.apps.docs}
08-29 11:25:22.159  5913  5913 D TAG     : onCreate()
08-29 11:25:22.176  5913  5913 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-29 11:25:22.275  1031  2028 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:25:22.342  4513  5912 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 551 ms] updated apps [took 551 ms] 
,08-29 11:25:22.655  5951  5951 D AndroidRuntime: 
08-29 11:25:22.655  5951  5951 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 11:25:22.658  5951  5951 D AndroidRuntime: CheckJNI is OFF
08-29 11:25:22.760  5951  5951 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 11:25:22.764  1031  1046 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 11:25:22.774  1938  1953 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-29 11:25:22.777  1031  1046 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-29 11:25:22.779  1031  1046 D ActivityManager: setTaskToReturnTo : TaskRecord{3419a155 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 11:25:22.779  1031  1046 D ActivityManager: setTaskToReturnTo : TaskRecord{3419a155 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 11:25:22.780  1031  1046 D WindowStateEx: AppWindowTokenEx init.. 
08-29 11:25:22.781   339   345 E GBMv2   : DFP En is all cleared set to be enabled
08-29 11:25:22.804  1031  1046 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5966 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 11:25:22.805  5951  5951 D AndroidRuntime: Shutting down VM
08-29 11:25:22.843  1938  1953 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-29 11:25:22.844  1938  1953 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a1634e0 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 11:25:22.844  1938  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-29 11:25:22.845  1938  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{4d0f399 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 11:25:22.895  5966  5966 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-29 11:25:22.957  5966  5966 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-29 11:25:22.963  5966  5966 I LibraryLoader: Loading: webviewchromium
08-29 11:25:22.965  5966  5966 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3275-3277)
08-29 11:25:22.965  5966  5966 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:25:22.977  5966  5966 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {29c2b1bc}
08-29 11:25:22.978  5966  5966 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:25:22.978  5966  5966 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 11:25:22.986  5966  5966 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 11:25:22.987  5966  5966 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 11:25:22.998  5966  5991 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,08-29 11:25:23.000   313  1383 V AudioPolicyService: registerClient() client 0xb1427ec0, uid 10118
08-29 11:25:23.003  1031  1093 D BluetoothManagerService: Message: 20
08-29 11:25:23.003  1031  1093 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18eceb37:true
08-29 11:25:23.006  5966  5966 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 11:25:23.007  5966  5966 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-29 11:25:23.007  5966  5966 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-29 11:25:23.027  5966  5966 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 11:25:23.027  5966  5966 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 11:25:23.027  5966  5966 I Adreno-EGL: Build Date: 12/12/14 금
08-29 11:25:23.027  5966  5966 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 11:25:23.027  5966  5966 I Adreno-EGL: Remote Branch: 
08-29 11:25:23.027  5966  5966 I Adreno-EGL: Local Patches: 
08-29 11:25:23.027  5966  5966 I Adreno-EGL: Reconstruct Branch: 
,08-29 11:25:23.072  5966  6001 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-29 11:25:23.074  5966  5966 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-29 11:25:23.085  5966  5966 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 11:25:23.088  5966  5966 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 11:25:23.090  5966  5966 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-29 11:25:23.092  5966  5966 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-29 11:25:23.092  5966  5966 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-29 11:25:23.102  5966  5966 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-29 11:25:23.107  5966  5966 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 11:25:23.107  5966  5966 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 11:25:23.138  5966  6013 D OpenGLRenderer: Render dirty regions requested: true
08-29 11:25:23.138  5966  6013 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 11:25:23.149  5966  6013 D OpenGLRenderer: Enabling debug mode 0
,08-29 11:25:23.154  5966  5966 D Atlas   : Validating map...
08-29 11:25:23.157  1031  1780 D SplitWindow: check instance of lgWin Window{38011379 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 11:25:23.215  5966  6011 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 11:25:23.215  5966  6011 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:25:23.268  1031  1094 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +426ms (total +487ms)
08-29 11:25:23.268  1031  1094 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1acfc76a u0 com.test.thalitest/.MainActivity t6} time:103581
,08-29 11:25:23.270  5966  5966 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@272ed3bb time:103583
08-29 11:25:23.342  1815  4663 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-29 11:25:23.379  5966  5966 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-29 11:25:23.379  5966  5966 I chromium: 
,08-29 11:25:23.385  1815  4663 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-29 11:25:23.411  5966  5966 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 11:25:23.422  1815  4663 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-29 11:25:23.561  5966  6024 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435164160
,08-29 11:25:23.578  5966  6024 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 11:25:23.578  5966  6024 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 11:25:23.578  5966  6024 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 11:25:23.578  5966  6024 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 11:25:23.578  5966  6024 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 11:25:23.578  5966  6024 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37975b8f added. We now have 1 listener(s)
08-29 11:25:23.583  1031  1955 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:25:23.590  5966  6024 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-29 11:25:23.595  5966  6024 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:25:23.598  5966  6024 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:25:23.600  5966  6024 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:23.609  5913  5913 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:25:23.609  5913  5913 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 11:25:23.610  5966  6024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1117e7fa added. We now have 1 listener(s)
08-29 11:25:23.610  5966  6024 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:23.617  1031  1540 D WifiService: New client listening to asynchronous messages
08-29 11:25:23.621  5966  6024 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:25:23.621  5966  6024 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 11:25:23.621  5966  6024 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 11:25:23.622  5966  6024 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 11:25:23.622  5966  6024 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 11:25:23.629  5966  6024 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:25:23.631  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:23.632  5966  6024 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-29 11:25:23.640  5966  6024 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 11:25:23.640  5966  6024 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:23.640  5966  6024 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:23.640  5966  6024 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:23.640  5966  6024 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:23.640  5966  6024 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:23.640  5966  6024 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:23.640  5966  6024 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:23.640  5966  6024 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:23.640  5966  6024 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 11:25:23.641  5966  6024 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:23.641  5966  6024 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 11:25:23.642  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:23.688  5966  6011 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-29 11:25:23.688  5966  6011 I chromium: 
,08-29 11:25:23.746  5966  5966 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 11:25:23.838  5913  5913 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-29 11:25:23.855  1031  2028 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6036 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 11:25:23.916  6036  6036 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-29 11:25:23.928  6036  6036 I LockScreenSettings: New app installed broadcast received ..
,08-29 11:25:23.931  6036  6036 I LockScreenSettings: Number of installed packages  1
08-29 11:25:23.984  1031  2047 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6058 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-29 11:25:23.985  1031  2047 I ActivityManager: Killing 4925:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-29 11:25:24.016   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 383us total 32.570ms
,08-29 11:25:24.036   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 472us total 18.762ms
,08-29 11:25:24.054   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 358us total 18.084ms
,08-29 11:25:24.088  1031  1919 W libprocessgroup: failed to open /acct/uid_10085/pid_4925/cgroup.procs: No such file or directory
,08-29 11:25:24.131  6058  6058 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 11:25:24.317  2774  2774 I MusicWidget: mDelayedStopHandler : unbind
,08-29 11:25:24.321  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-29 11:25:24.321  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-29 11:25:24.322  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-29 11:25:24.324  2127  2127 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-29 11:25:24.324  2127  2127 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-29 11:25:24.324  2127  2127 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-29 11:25:24.325  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-29 11:25:24.325  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-29 11:25:24.329  1031  1779 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@a70d84acom.lge.music.MediaPlaybackService$5@272ed3bb
08-29 11:25:24.332  2127  2127 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-29 11:25:24.332  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-29 11:25:24.333  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:25:24.337  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:25:24.338  2127  2127 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@24e72da8
08-29 11:25:24.338  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:25:24.339  2127  2127 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-29 11:25:24.339  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:25:24.339  2127  2127 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-29 11:25:24.339  2127  2127 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-29 11:25:24.339  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:25:24.340  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:25:24.340  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:25:24.340  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:25:24.341  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:25:24.346  2127  2127 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,08-29 11:25:24.348  2127  2127 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-29 11:25:24.349  2127  2127 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-29 11:25:24.349  2127  2127 V MediaPlayer[Native]: reset
08-29 11:25:24.352  2127  2127 V MediaPlayer[Native]: setListener
08-29 11:25:24.352  2127  2127 V MediaPlayer[Native]: disconnect
08-29 11:25:24.352  2127  2127 V MediaPlayer[Native]: destructor
08-29 11:25:24.352   313  1381 V AudioFlinger: releasing 18 from 2127 for -1
08-29 11:25:24.352   313  1381 V AudioFlinger:  decremented refcount to 0
08-29 11:25:24.352   313  1381 V AudioFlinger: purging stale effects
08-29 11:25:24.353  2127  2127 V MediaPlayer[Native]: disconnect
08-29 11:25:24.353  2127  2127 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-29 11:25:24.354  2127  2127 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-29 11:25:24.354  2127  2127 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-29 11:25:24.355  2127  2127 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-29 11:25:24.355  2127  2127 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-29 11:25:24.355  2127  2127 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-29 11:25:24.355  2127  2127 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 823480536
08-29 11:25:24.355  2127  2127 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 823480536
08-29 11:25:24.357  2127  2127 I SmartShareClient: [SmartShareManagerClient] terminate service: 2127/MediaPlaybackService/251440526
08-29 11:25:24.359  2127  2127 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-29 11:25:24.359  2127  2127 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3c56c31
,08-29 11:25:24.361  2127  2127 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-29 11:25:24.362  2127  2127 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-29 11:25:24.362  2127  2127 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-29 11:25:24.362  2127  2127 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-29 11:25:24.363  1031  1588 I ActivityManager: Killing 5043:com.lge.bnr/1000 (adj 15): empty #17
08-29 11:25:24.371  2127  2127 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
,08-29 11:25:24.410  1031  2008 W libprocessgroup: failed to open /acct/uid_1000/pid_5043/cgroup.procs: No such file or directory
,08-29 11:25:24.488   339   347 E GBMv2   : DFP En is all cleared set to be enabled
,08-29 11:25:24.489   339   347 E GBMv2   : Set value is all cleared set the max
08-29 11:25:24.489   339   347 I GBMv2   : DFP Enabled. Ignore VFP set
08-29 11:25:24.506  5966  6027 W jxcore-log: Initializing JXcore engine
08-29 11:25:24.506  5966  6027 W jxcore-log: JXcore engine is ready
,08-29 11:25:24.535  6027  6027 W Thread-672: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[8525]" dev="sockfs" ino=8525 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 11:25:24.535  6027  6027 W Thread-672: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-29 11:25:24.535  6027  6027 W Thread-672: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7444]" dev="sockfs" ino=7444 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-29 11:25:24.535  6027  6027 W Thread-672: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-29 11:25:24.535  6027  6027 W Thread-672: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[28355]" dev="sockfs" ino=28355 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-29 11:25:24.557  5966  6027 W jxcore-log: Starting JXcore engine
08-29 11:25:24.634  1031  1919 V SIM_STK : Menu title from STK is T-Mobile
,08-29 11:25:24.651  5966  6027 W jxcore-log: Platform android
08-29 11:25:24.651  5966  6027 W jxcore-log: 
,08-29 11:25:24.651  5966  6027 W jxcore-log: Process ARCH arm
08-29 11:25:24.651  5966  6027 W jxcore-log: 
08-29 11:25:24.678  1031  1588 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6097 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 11:25:24.744  6097  6097 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-29 11:25:24.744  6097  6097 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-29 11:25:24.785  1031  1956 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6116 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 11:25:24.787  1031  1956 I ActivityManager: Killing 5353:com.google.android.gm/u0a64 (adj 15): empty #17
08-29 11:25:24.852  5966  6027 I jxcore-log: JXcore Cordova bridge is ready!
08-29 11:25:24.852  5966  6027 I jxcore-log: 
08-29 11:25:24.852  5966  6027 W jxcore-log: JXcore engine is started
,08-29 11:25:24.860  1031  1047 W libprocessgroup: failed to open /acct/uid_10064/pid_5353/cgroup.procs: No such file or directory
,08-29 11:25:24.866  5966  6024 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-29 11:25:24.870  5966  5966 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-29 11:25:24.935  6116  6116 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-29 11:25:24.954  1031  1955 I ActivityManager: Killing 5401:com.google.android.talk/u0a72 (adj 15): empty #17
08-29 11:25:24.955  6116  6116 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-29 11:25:25.119  1031  1588 W libprocessgroup: failed to open /acct/uid_10072/pid_5401/cgroup.procs: No such file or directory
,08-29 11:25:27.739  5913  5913 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-29 11:25:27.749  1031  2029 I ActivityManager: Killing 5171:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-29 11:25:27.770  5150  5150 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-29 11:25:27.772  5150  5150 W System.err: android.os.DeadObjectException
08-29 11:25:27.772  5150  5150 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 11:25:27.772  5150  5150 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 11:25:27.772  5150  5150 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 11:25:27.772  5150  5150 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 11:25:27.772  5150  5150 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 11:25:27.772  5150  5150 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 11:25:27.772  5150  5150 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:25:27.772  5150  5150 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 11:25:27.773  5150  5150 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 11:25:27.773  5150  5150 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 11:25:27.773  5150  5150 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:27.773  5150  5150 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:27.773  5150  5150 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 11:25:27.773  5150  5150 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 11:25:27.774  5150  5150 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 11:25:27.774  5150  5150 W System.err: android.os.DeadObjectException
08-29 11:25:27.774  5150  5150 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 11:25:27.774  5150  5150 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 11:25:27.774  5150  5150 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 11:25:27.774  5150  5150 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 11:25:27.774  5150  5150 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 11:25:27.774  5150  5150 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 11:25:27.774  5150  5150 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:25:27.774  5150  5150 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 11:25:27.774  5150  5150 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 11:25:27.774  5150  5150 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 11:25:27.774  5150  5150 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:27.774  5150  5150 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-29 11:25:27.774  5150  5150 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909),
08-29 11:25:27.774  5150  5150 W System.err: ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 11:25:27.775  5150  5150 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 11:25:27.775  5150  5150 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.,
08-29 11:25:27.979  1031  1919 W libprocessgroup: failed to open /acct/uid_1000/pid_5171/cgroup.procs: No such file or directory
,08-29 11:25:27.980  1031  1919 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-29 11:25:27.992  5150  5150 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,08-29 11:25:27.992  5150  5150 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-29 11:25:28.040  1031  1588 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6140 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 11:25:28.042  5150  5150 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 11:25:28.204  1031  2047 I art     : Explicit concurrent mark sweep GC freed 26372(1225KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.514ms total 119.551ms
,08-29 11:25:28.234  6140  6140 D UEI.SmartControl: Quickset Services start...
08-29 11:25:28.235  6140  6140 I UEI.SmartControl: Manufacture = LGE
08-29 11:25:28.236  6140  6140 D UEI.SmartControl: Id = LGNevo
08-29 11:25:28.236  6140  6140 D UEI.SmartControl: File observer start...
08-29 11:25:28.237  6140  6140 E UEI.SmartControl: IR Port is disabled: false
,08-29 11:25:28.247  6140  6140 D UEI.SmartControl: Starting file observer...
08-29 11:25:28.247  6140  6140 D UEI.SmartControl: Extracting JNI libs...
08-29 11:25:28.247  6140  6140 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-29 11:25:28.318  6140  6140 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 11:25:28.318  6140  6140 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 11:25:28.318  6140  6140 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 11:25:28.349  6140  6140 I UEI.SmartControl: --- Selecting new region: 6
08-29 11:25:28.351  6140  6140 I UEI.SmartControl: Model = LG-D855
08-29 11:25:28.352  6140  6140 D UEI.SmartControl: QS Service created
,08-29 11:25:28.369  6140  6140 I UEI.SmartControl: Service initServices...
08-29 11:25:28.373  6140  6140 D UEI.SmartControl: QS start get config
,08-29 11:25:28.411  6140  6140 D UEI.SmartControl: Loading JNI Libs...
,08-29 11:25:28.683  6140  6140 I UEI.SmartControl: Supports setup maps: true
08-29 11:25:28.686  6140  6140 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 11:25:28.686  6140  6140 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 11:25:28.686  6140  6140 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 11:25:28.687  6140  6140 I UEI.SmartControl: ### init IR Blaster...
,08-29 11:25:28.698  6140  6140 D serial_port: Configuring serial port
08-29 11:25:28.702  6140  6140 E UEI.SmartControl: UEIBLaster setting for 616
,08-29 11:25:28.702  6140  6140 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 11:25:28.703  6140  6140 I UEI.SmartControl: configuring settings for MAXQ616
08-29 11:25:28.703  6140  6140 I UEI.SmartControl: Get version...
08-29 11:25:28.707  5913  6028 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
08-29 11:25:28.719  6140  6166 D UEI.SmartControl: serial port data available: 21
,08-29 11:25:28.745  6140  6140 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 11:25:28.745  6140  6140 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 11:25:28.745  6140  6140 I UEI.SmartControl: QS saving settings...
08-29 11:25:28.746  6140  6140 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 11:25:28.761  6140  6166 D UEI.SmartControl: serial port data available: 4
,08-29 11:25:28.797  6140  6169 I UEI.SmartControl: Device manager: loading config....
,08-29 11:25:28.803  6140  6140 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 11:25:28.805  6140  6169 D UEI.SmartControl: ----------- loading internal config...
08-29 11:25:28.806  6140  6140 E UEI.SmartControl: Services init done
08-29 11:25:28.806  6140  6140 D UEI.SmartControl: QS Service init finished
08-29 11:25:28.808  6140  6140 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 11:25:28.808  6140  6140 D UEI.SmartControl: QS Service version code: 201091
08-29 11:25:28.809  6140  6140 D UEI.SmartControl: Service requested: Control
08-29 11:25:28.821  6140  6169 E UEI.SmartControl: Loading SETTINGS...
,08-29 11:25:28.825  6140  6140 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 11:25:28.827  5150  5150 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 11:25:28.827  6140  6156 I UEI.SmartControl: ------ IControl API: 11
08-29 11:25:28.828  6140  6156 I UEI.SmartControl: Registering callback...
08-29 11:25:28.829  1031  2008 I ActivityManager: Killing 5150:com.lge.qremote/u0a112 (adj 15): empty #17
08-29 11:25:28.831  6140  6169 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 11:25:28.855  6140  6168 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 11:25:28.855  6140  6168 D UEI.SmartControl: -----service ready thread exits
,08-29 11:25:28.969  1031  1777 W libprocessgroup: failed to open /acct/uid_10112/pid_5150/cgroup.procs: No such file or directory
08-29 11:25:28.970  6140  6140 D UEI.SmartControl: Internal service binding...
,08-29 11:25:29.628  1031  1991 I ActivityManager: Killing 5083:com.android.calendar/u0a13 (adj 15): empty #17
,08-29 11:25:29.768  1031  1919 W libprocessgroup: failed to open /acct/uid_10013/pid_5083/cgroup.procs: No such file or directory
,08-29 11:25:29.776  1815  5724 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-29 11:25:29.779   309  6175 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-29 11:25:29.779  1031  1091 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 11:25:29.779  1815  5724 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-29 11:25:29.781  1815  1815 I ConfigFetchService: fetch service done; releasing wakelock
08-29 11:25:29.782  1815  1815 I ConfigFetchService: stopping self
08-29 11:25:29.785  2222  2222 I ConfigService: onDestroy
,08-29 11:25:33.805  6140  6170 D UEI.SmartControl: Internal timer expired: 1
08-29 11:25:33.806  6140  6170 D UEI.SmartControl: unbind internal service
,08-29 11:25:33.810  6140  6140 D UEI.SmartControl: Service.onUnbind: IControl
,08-29 11:25:33.811  6140  6140 D UEI.SmartControl: Service.onDestroy
08-29 11:25:33.812  6140  6140 D UEI.SmartControl: Lock is in USE false
08-29 11:25:33.812  6140  6140 D UEI.SmartControl: unbind internal service
08-29 11:25:33.812  6140  6140 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@24e72da8
08-29 11:25:33.812  6140  6140 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-29 11:25:33.812  6140  6140 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-29 11:25:33.812  6140  6140 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
,08-29 11:25:33.812  6140  6140 W System.err: ,	at com.uei.control.Service.c(Unknown Source)
08-29 11:25:33.812  6140  6140 W System.err: ,	at com.uei.control.Service.onDestroy(Unknown Source)
08-29 11:25:33.812  6140  6140 W System.err: ,	,at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-29 11:25:33.812  6140  6140 W System.err: ,	,at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-29 11:25:33.812  6140  6140 W System.err: 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
,08-29 11:25:33.812  6140  6140 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-29 11:25:33.812  6140  6140 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-29 11:25:33.812  6140  6140 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 11:25:33.812  6140  6140 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:33.812  6140  6140 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:33.812  6140  6140 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-29 11:25:33.812  6140  6140 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 11:25:33.813  6140  6140 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@24e72da8
08-29 11:25:33.813  6140  6140 D serial_port: close(fd = 25)
08-29 11:25:33.816  6140  6140 I UEI.SmartControl: Serial port is closed.
08-29 11:25:33.816  6140  6140 I UEI.SmartControl: Serial port is closed.
08-29 11:25:33.816  6140  6140 D UEI.SmartControl: Blaster closed
,08-29 11:25:33.817  6140  6140 D UEI.SmartControl: Shut down QS...
08-29 11:25:33.817  6140  6140 D UEI.SmartControl: Stopping QS lib
08-29 11:25:33.817  6140  6140 D UEI.SmartControl: QS lib stop result = true
08-29 11:25:33.817  6140  6140 D UEI.SmartControl: Stopped QS lib
08-29 11:25:33.817  6140  6140 D UEI.SmartControl: Stopped file observer...
08-29 11:25:33.817  6140  6140 D UEI.SmartControl: QS shutdown complete
,08-29 11:25:34.382  2127  2127 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19981
,08-29 11:25:34.857  1031  1089 I ActivityManager: Waited long enough for: ServiceRecord{396636c6 u0 com.google.android.gms/.wearable.service.WearableService}
,08-29 11:25:34.964  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 11:25:34.964  5966  6027 I jxcore-log: 
,08-29 11:25:34.967  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 11:25:34.967  5966  6027 I jxcore-log: 
08-29 11:25:34.970  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:34.970  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:34.970  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:34.970  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:34.970  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:34.970  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:34.970  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:34.970  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:34.973  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:34.976  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 11:25:34.976  5966  6027 I jxcore-log: 
08-29 11:25:34.977  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 11:25:34.977  5966  6027 I jxcore-log: 
,08-29 11:25:35.479  5966  6027 D executeNativeTests: Running unit tests
,08-29 11:25:35.561  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:25:35.561  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 added. We now have 2 listener(s)
,08-29 11:25:35.562  1031  2008 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:35.564  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-29 11:25:35.564  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:35.564  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-29 11:25:35.564  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:25:35.564  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e added. We now have 2 listener(s)
08-29 11:25:35.564  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:35.564  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:25:35.566  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:25:35.568  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:35.568  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:35.568  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:35.568  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:35.568  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-29 11:25:35.568  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:35.568  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:35.568  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:35.569  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-29 11:25:35.570  5966  6027 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-29 11:25:35.570  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:35.573  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 11:25:35.575  5966  6027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:25:35.575  5966  6027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 11:25:35.577  5966  6027 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 11:25:35.578  5966  6027 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 11:25:35.578  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
08-29 11:25:35.578  5966  6027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 11:25:35.578  5966  6027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 11:25:35.578  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:25:35.579  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-29 11:25:35.579  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:25:35.581  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-29 11:25:35.581  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.581  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:35.581  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:35.581  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 removed from the list
,08-29 11:25:35.581  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.581  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e removed from the list
08-29 11:25:35.581  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.581  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:35.582  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.582  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.583  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.583  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.583  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.583  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list,
08-29 11:25:35.585  5966  6027 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 11:25:35.585  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.585  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.585  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.585  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:25:35.585  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.585  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.585  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.585  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.585  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
,08-29 11:25:35.585  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.585  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.585  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.586  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.586  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:35.586  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.586  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.586  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.586  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 11:25:35.591  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 11:25:35.592  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 11:25:35.592  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 11:25:35.592  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 11:25:35.592  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 11:25:35.592  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 11:25:35.592  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 11:25:35.592  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-29 11:25:35.592  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 11:25:35.592  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 11:25:35.592  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.592  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.592  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.593  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-29 11:25:35.593  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.593  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.593  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.593  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.594  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.594  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 11:25:35.594  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.594  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.594  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.594  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.594  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.594  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:25:35.594  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.594  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.595  5966  6027 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 11:25:35.596  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:35.599  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:35.599  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:35.599  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
08-29 11:25:35.599  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:35.599  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:35.599  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:35.599  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:35.599  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:35.600  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:35.600  5966  6027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:35.600  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:35.601  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:35.601  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:35.601  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:25:35.601  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:35.601  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:25:35.604  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:25:35.605  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-29 11:25:35.608  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 11:25:35.612  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 11:25:35.613  5966  6027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 11:25:35.614  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:25:35.614  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:35.615  5966  6027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-29 11:25:35.616  5966  6027 I io.jxcore.node.ConnectionHelper: start: OK,
08-29 11:25:35.618  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.618  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.618  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.618  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.618  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:35.618  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:35.618  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.618  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.618  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.618  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.618  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:35.619  5966  6027 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 11:25:35.620  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:35.621  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:35.621  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:35.621  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:35.621  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:35.621  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:35.621  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:35.621  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:35.621  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
08-29 11:25:35.622  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:35.622  5966  6027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:35.623  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:35.623  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:35.623  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:35.623  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-29 11:25:35.623  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:35.623  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:25:35.626  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 11:25:35.627  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-29 11:25:35.628  5966  6027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 11:25:35.628  5966  6027 I io.jxcore.node.ConnectionHelper: start: OK
08-29 11:25:35.629  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.629  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.629  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:25:35.629  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.629  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.629  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:35.629  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.629  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.629  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
,08-29 11:25:35.629  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.629  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.630  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.630  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.630  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.630  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:25:35.631  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:35.631  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.631  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.632  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.632  5966  6027 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 11:25:35.633  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:25:35.634  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:35.634  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:35.634  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:35.634  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:35.634  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:35.634  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:35.634  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:35.634  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:35.635  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:35.635  5966  6027 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-29 11:25:35.636  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:35.636  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:35.636  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:35.636  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:25:35.636  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:35.636  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
08-29 11:25:35.639  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:25:35.639  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:25:35.640  5966  6027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager,
08-29 11:25:35.640  5966  6027 I io.jxcore.node.ConnectionHelper: start: OK
08-29 11:25:35.640  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.640  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.640  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.641  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.641  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:25:35.641  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.641  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.641  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.641  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:35.641  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
,08-29 11:25:35.641  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.641  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.641  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.641  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.641  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.641  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:35.642  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.642  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.642  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:35.642  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.642  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.642  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list,
08-29 11:25:35.643  5966  6027 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 11:25:35.643  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.643  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.643  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.643  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:25:35.643  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.643  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.643  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.643  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.643  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.643  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:25:35.643  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.643  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.643  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 11:25:35.643  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.644  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.644  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.644  5966  6027 D BluetoothLeScanner: could not find callback wrapper
,08-29 11:25:35.644  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.644  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.644  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.645  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 11:25:35.645  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:25:35.645  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.645  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.645  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.646  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:35.646  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.646  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.646  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.646  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list,
08-29 11:25:35.646  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:25:35.646  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.646  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.646  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.646  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.646  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 11:25:35.646  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.647  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:35.647  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.647  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 11:25:35.647  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.647  5966  6027 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 11:25:35.647  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:25:35.647  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.647  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.648  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.648  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.648  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:35.648  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.648  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.648  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
,08-29 11:25:35.648  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.648  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.648  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.648  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:35.648  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.649  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.649  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.649  5966  6027 D BluetoothLeScanner: could not find callback wrapper
,08-29 11:25:35.649  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.649  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.649  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.649  5966  6027 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 11:25:35.650  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-29 11:25:35.650  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.650  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.650  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.650  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:35.650  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.650  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.650  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.650  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.650  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:25:35.650  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.650  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.650  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.650  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.650  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:25:35.650  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.651  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:35.651  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.651  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.651  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
,08-29 11:25:35.651  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 11:25:35.652  5966  6027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:25:35.652  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 11:25:35.653  5966  6027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 11:25:35.653  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 11:25:35.653  5966  6027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,08-29 11:25:35.653  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.653  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.653  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.653  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.653  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 11:25:35.653  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.653  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.653  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.653  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list,
08-29 11:25:35.653  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop,
,08-29 11:25:35.653  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.653  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.653  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 11:25:35.653  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.654  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.654  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 11:25:35.654  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:35.654  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.654  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 11:25:35.654  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.655  5966  6027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:25:35.655  5966  6027 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-29 11:25:35.655  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 11:25:35.657  5966  6027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 11:25:35.657  5966  6027 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110],
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910],
,08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-29 11:25:35.657  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 11:25:35.658  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 11:25:35.658  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-29 11:25:35.658  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 11:25:35.658  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 11:25:35.658  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 11:25:35.658  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 11:25:35.658  5966  6027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 11:25:35.658  5966  6027 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:25:35.658  5966  6027 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-29 11:25:35.658  5966  6027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:25:35.658  5966  6027 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-29 11:25:35.658  5966  6027 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 11:25:35.658  5966  6027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:25:35.658  5966  6027 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-29 11:25:35.658  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 11:25:35.659  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 11:25:35.660  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1,
08-29 11:25:35.660  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 11:25:35.661  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 11:25:35.661  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 11:25:35.661  5966  6027 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 11:25:35.661  5966  6027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:25:35.661  5966  6027 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 11:25:35.661  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.661  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.661  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.662  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.662  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.662  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.662  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 11:25:35.662  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
,08-29 11:25:35.662  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.662  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.662  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:25:35.662  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.662  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.662  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.662  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.663  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.663  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.663  5966  6177 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 736
08-29 11:25:35.663  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:35.663  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.663  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.663  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.664  5966  6027 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 11:25:35.664  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.664  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.664  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.664  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.664  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.664  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.665  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.665  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.665  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.665  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.665  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.665  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.665  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.665  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.665  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.665  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.666  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:35.666  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.666  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.666  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.667  5966  6027 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 11:25:35.668  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.668  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.668  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.669  5966  6176 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 736)
08-29 11:25:35.669  5966  6176 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 736)
08-29 11:25:35.669  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.669  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.669  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.669  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.670  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.670  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.670  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.670  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.670  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.670  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.670  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.670  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.670  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.671  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:35.671  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.671  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.671  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.672  5966  6027 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 11:25:35.672  5966  6027 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 11:25:35.673  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:25:35.673  5966  6027 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 11:25:35.673  5966  6027 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 11:25:35.673  5966  6027 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 11:25:35.673  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:25:35.673  5966  6027 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 11:25:35.673  5966  6027 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 11:25:35.673  5966  6027 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 11:25:35.673  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:25:35.673  5966  6027 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 11:25:35.673  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:25:35.673  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.673  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.674  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.674  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.674  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.674  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.674  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.674  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.674  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.674  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.674  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.674  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.674  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.675  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.675  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.675  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:35.675  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.675  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.675  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.676  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.676  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.676  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.676  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.676  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.676  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.676  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.676  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.676  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.676  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.676  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.676  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.676  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.676  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.676  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.676  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.676  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.676  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.676  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.676  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.676  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.676  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.676  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.676  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.676  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.676  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.676  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.676  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.676  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.678  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.678  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.678  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:35.678  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.678  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.678  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.679  5966  6027 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 11:25:35.679  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:35.680  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 11:25:35.680  5966  6027 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 11:25:35.680  5966  6027 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 11:25:35.681  5966  5966 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 11:25:35.681  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 11:25:35.681  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:25:35.682  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.682  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 11:25:35.682  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 11:25:35.682  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 11:25:35.682  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.682  5966  6027 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 11:25:35.682  5966  5966 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 11:25:35.682  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.682  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.682  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:25:35.683  5966  6027 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:25:35.683  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:25:35.683  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:25:35.684  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:35.684  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:35.687  5966  6027 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:25:35.687  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.687  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.688  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:35.688  5966  6027 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:25:35.689  5966  6178 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:35.690  3759  3877 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-29 11:25:35.690  5966  5966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:35.690  5966  5966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:35.690  5966  5966 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:25:35.691  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.691  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.691  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.691  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.691  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.691  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.691  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.691  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.691  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.691  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.691  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.691  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.691  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.691  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.691  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.692  5966  6178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 11:25:35.692  5966  6178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 11:25:35.692  5966  6178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 11:25:35.693  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.693  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.693  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.693  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.693  5966  6027 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 11:25:35.694  5966  5966 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 11:25:35.695  5966  6027 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 11:25:35.695  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 11:25:35.695  5966  6027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:25:35.695  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.695  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.695  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.695  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.695  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.695  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.695  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.695  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.695  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.695  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.695  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.695  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.695  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.695  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.696  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.696  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.696  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.696  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.697  1031  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:35.698  1031  1755 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:35.699  1031  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:35.699  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.699  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.700  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.700  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.700  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.700  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.700  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.700  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.700  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.700  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.700  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.700  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.700  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.700  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.701  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.701  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.701  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.701  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.702  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:35.702  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:35.702  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:35.702  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:35.702  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.702  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.702  5966  6027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dacdaf9 not in the list
08-29 11:25:35.702  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.702  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.702  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:35.702  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.702  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.702  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:35.702  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:35.703  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:35.703  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:35.703  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:35.703  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e74a3e not in the list
08-29 11:25:35.705  5966  6027 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 11:25:35.705  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:25:35.705  5966  6027 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 11:25:35.705  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:25:35.705  5966  6027 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 11:25:35.705  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:25:35.707  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 11:25:35.707  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 11:25:35.708  5966  6027 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 11:25:35.708  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 11:25:35.708  5966  6027 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 11:25:35.708  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 11:25:35.708  5966  6027 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 11:25:35.708  5966  6027 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 11:25:35.709  5966  6027 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 11:25:35.709  5966  6027 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 11:25:35.710  5966  6027 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 11:25:35.710  5966  6027 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 11:25:35.710  5966  6027 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 11:25:35.710  5966  6027 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 11:25:35.711  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:35.711  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34ff1497 added. We now have 2 listener(s)
08-29 11:25:35.711  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:35.712  5966  6027 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 11:25:35.713  1031  1779 D WifiServiceImplEx: setWifiEnabled: true pid=5966, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 11:25:35.714  1031  1779 D WifiService: setWifiEnabled: true pid=5966, uid=10118
08-29 11:25:35.714  1031  1779 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 11:25:35.715  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:35.715  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cabf684 added. We now have 3 listener(s)
08-29 11:25:35.715  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:35.718  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:35.718  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@386c5e6d added. We now have 4 listener(s)
08-29 11:25:35.718  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:35.720  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:35.720  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@379aa2 added. We now have 5 listener(s)
08-29 11:25:35.720  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:35.721  1031  1779 D WifiServiceImplEx: setWifiEnabled: false pid=5966, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 11:25:35.722  1031  1779 D WifiService: setWifiEnabled: false pid=5966, uid=10118
08-29 11:25:35.722  1031  1779 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 11:25:35.738  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:25:35.739  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:25:35.739  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-29 11:25:35.740  1031  1535 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-29 11:25:35.740  1031  1535 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 11:25:35.740  1031  1535 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 11:25:35.740  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 11:25:35.741  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:35.741  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:35.741  1031  1533 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3a905cba
08-29 11:25:35.741  1031  1533 D LGWifiP2pService: P2pDisablingState
08-29 11:25:35.741  1031  1533 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:35.741  1031  1533 D LGWifiP2pService: p2p socket connection lost
08-29 11:25:35.741  1031  1533 D LGWifiP2pService: P2pDisabledState
08-29 11:25:35.743  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 11:25:35.743  1938  1938 D WfdsService: WifiP2pState is changed : false
08-29 11:25:35.743  1938  2334 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 11:25:35.743  1938  2334 D WfdsService: Set the WFDS Monitor: false
08-29 11:25:35.744  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 11:25:35.744  1031  1031 D RttService: SCAN_AVAILABLE : 1
08-29 11:25:35.744  1031  1552 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:35.744  1031  1535 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 11:25:35.745   309   890 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:25:35.745  1938  2334 D WfdsMonitor: WFDS Monitor is stopped
08-29 11:25:35.745  1938  2334 D WfdsService: STATE : WfdsDisabledState - enter
08-29 11:25:35.745  1938  2845 D CtrlSupplicant: Received on exit socket, terminate
08-29 11:25:35.745  1938  2845 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 11:25:35.745  1938  2845 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 11:25:35.745  1938  2845 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 11:25:35.746  1031  1553 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:35.746  1031  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:35.746  1938  2337 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 11:25:35.746  1938  2334 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 11:25:35.747  1031  1918 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@25e350e8 mBinding = false
08-29 11:25:35.749  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-29 11:25:35.749  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 11:25:35.749  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:35.750  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:35.750  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:35.750  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:25:35.751  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:35.752  1031  1535 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 11:25:35.752  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:35.752  1031  1535 D WifiNative-p2p0: TERMINATE: returned true
08-29 11:25:35.752  1031  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:25:35.752  1031  1535 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:25:35.752  1031  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-29 11:25:35.755  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-29 11:25:35.757  1031  1093 D BluetoothManagerService: Message: 2
08-29 11:25:35.760  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:25:35.760  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:25:35.760  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-29 11:25:35.761  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:35.761  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:35.762  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:25:35.764  1031  1093 D BluetoothManagerService: Sending off request.
08-29 11:25:35.764  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 11:25:35.766  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:35.767  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 11:25:35.768  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:35.768  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:35.768  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:35.768  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:35.768  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:35.768  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:35.768  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:35.768  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:35.768  3759  3877 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 11:25:35.768  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:35.768  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 11:25:35.768  3759  3839 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 11:25:35.768  3759  3839 D BluetoothAdapterProperties: Setting state to 13
08-29 11:25:35.768  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:35.768  3759  3839 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 11:25:35.769  3759  3839 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 11:25:35.769  3759  3839 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 11:25:35.772  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:35.772  1031  1093 D BluetoothManagerService: Message: 60
08-29 11:25:35.772  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:35.772  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:35.772  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:35.772  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:35.772  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:35.772  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:35.772  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:35.772  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:35.772  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 11:25:35.772  1031  1093 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 11:25:35.773  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:35.773  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:35.773  5966  6027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:35.774  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:35.793  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 11:25:35.793  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 11:25:35.794  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:35.795  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:35.817  1031  2047 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6192 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 11:25:35.820  3759  3848 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:25:35.820  3759  3839 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 11:25:35.821  3759  3839 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 11:25:35.821  3759  4071 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 11:25:35.821  3759  4071 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:25:35.821  3759  4071 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 11:25:35.821  3759  4071 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 11:25:35.821  3759  4071 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 11:25:35.821  3759  4071 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 11:25:35.821  3759  4071 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 11:25:35.821  3759  4071 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-29 11:25:35.822  3759  4072 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:25:35.822  3759  4095 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:25:35.822  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 11:25:35.823  3759  3949 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 11:25:35.823  3759  4093 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:25:35.824  3759  4097 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:25:35.825  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:25:35.825  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:25:35.825  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:25:35.825  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:25:35.825  3759  3949 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:35.825  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:25:35.825  3759  3949 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:35.825  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:25:35.825  3759  3949 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:35.825  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 11:25:35.825  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 11:25:35.825  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:35.825  3759  3949 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 11:25:35.826  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:25:35.828  3759  3759 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:35.828  3759  3759 D BluetoothMapService: STATE_TURNING_OFF
08-29 11:25:35.828  3759  3759 V BluetoothMapService: Handler(): got msg=4
08-29 11:25:35.828  3759  3759 D BluetoothMapService: MAP Service closeService in
08-29 11:25:35.829  3759  3759 D BluetoothMapMasInstance: MAP Service shutdown
08-29 11:25:35.829  3759  3759 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:25:35.829  3759  3759 V BluetoothMapService: MAP Service closeService out
08-29 11:25:35.829  3759  3759 V BtOppService: Receiver DISABLED_ACTION 
08-29 11:25:35.830  3759  3759 I BtOppRfcommListener: stopping Accept Thread
08-29 11:25:35.830  3759  3759 V BtOppRfcommListener: close mBtServerSocket
08-29 11:25:35.830  3759  3759 V BtOppRfcommListener: waiting for thread to terminate
08-29 11:25:35.830  3759  4093 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 11:25:35.830  3759  3759 V BtOppRfcommListener: done waiting for thread to terminate
,08-29 11:25:35.833  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:35.833  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:35.833  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:35.833  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:35.833  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:35.833  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:35.833  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:35.833  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:35.833  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:35.834  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:35.834  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:35.836  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:35.848  2681  2681 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 11:25:35.848  2681  2681 I wpa_supplicant: monitor socket send errors count : 1
08-29 11:25:35.848  2681  2681 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1938-2\x00 that cannot receive messages
08-29 11:25:35.849  1031  2843 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 11:25:35.867  1031  2843 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-29 11:25:35.879  1031  1089 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6210 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 11:25:35.881  2681  2681 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 11:25:35.881  1031  2843 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 11:25:35.881  1031  2843 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 11:25:35.881  1031  2843 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 11:25:35.881  1031  2843 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 11:25:35.881  2681  2681 W wpa_supplicant: USIM:  scard_deinit function
08-29 11:25:35.882  1031  2843 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:25:35.882  1031  2843 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:25:35.883  3759  3759 V BtOppService: onDestroy
08-29 11:25:35.883  1031  1535 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116183
08-29 11:25:35.883  1031  1093 D Tethering: InitialState.processMessage what=4
08-29 11:25:35.883  1031  1535 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116183
08-29 11:25:35.884  1031  1535 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=116184  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 11:25:35.885  1031  1535 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=116185  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 11:25:35.886  3759  3759 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 11:25:35.886  1031  1093 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 11:25:35.886  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:35.887  1031  1535 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:35.888  1031  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:35.888  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:35.888   309  6220 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 11:25:35.889  1031  1091 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-29 11:25:35.921  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 11:25:35.924  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:25:35.925  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:35.927  1031  1780 I ActivityManager: Killing 4833:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-29 11:25:35.944  6210  6210 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:25:35.944  6210  6210 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-29 11:25:35.945  6210  6210 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 11:25:35.945  6210  6210 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-29 11:25:35.946  6210  6210 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-29 11:25:35.947  6210  6210 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 11:25:35.970  2681  2681 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 11:25:35.971  1031  2843 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 11:25:35.971  1031  2843 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 11:25:35.971  1031  2843 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 11:25:35.972  1031  1535 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
,08-29 11:25:35.989  1031  2008 W libprocessgroup: failed to open /acct/uid_10014/pid_4833/cgroup.procs: No such file or directory
,08-29 11:25:36.074  1031  1535 D WifiOffDelayIfNotUsed: stopMonitoring
,08-29 11:25:36.074  1031  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:25:36.074  1031  1535 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:25:36.074  1031  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:25:36.074  1938  1938 D WfdsService: Supplicant Connection state is changed : false
08-29 11:25:36.075  1938  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 11:25:36.075  1938  2334 D WfdsService: Set the WFDS Monitor: false
08-29 11:25:36.075  1938  2334 D WfdsMonitor: WFDS Monitor is stopped
,08-29 11:25:36.078  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:36.079  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 11:25:36.079  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 11:25:36.080  1031  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 11:25:36.080  1031  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 11:25:36.080  2501  2501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:36.083  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:36.086  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:36.114  6210  6210 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 11:25:36.119  3759  3759 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:25:36.119  3759  3759 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:36.119  3759  3759 V BluetoothPbapReceiver: ***********state = 13
08-29 11:25:36.121  3759  3759 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 11:25:36.122  3759  3759 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:36.122  3759  3759 V BluetoothPbapService: state: 13
08-29 11:25:36.122  3759  3759 V BluetoothPbapService: Pbap Service closeService in
08-29 11:25:36.124  3759  3759 V BluetoothPbapService: successfully stopped pbap service
08-29 11:25:36.124  3759  3759 V BluetoothPbapService: Pbap Service closeService out
08-29 11:25:36.124  3759  3759 V BluetoothPbapService: Pbap Service onDestroy
08-29 11:25:36.124  3759  3759 V BluetoothPbapService: Pbap Service closeService in
08-29 11:25:36.125  3759  3759 V BluetoothPbapService: Pbap Service closeService out
08-29 11:25:36.125  3759  3759 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 11:25:36.126  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:25:36.137  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:36.181  6210  6210 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:25:36.181  6210  6210 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:25:36.190  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:36.191  5966  5966 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 11:25:36.197  1031  1093 D BluetoothManagerService: Message: 20
08-29 11:25:36.197  1031  1093 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c17a632:true
08-29 11:25:36.199  1031  2008 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6232 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-29 11:25:36.221  1031  1093 D BluetoothManagerService: Message: 30
,08-29 11:25:36.225  1031  1093 D BluetoothManagerService: Message: 30
08-29 11:25:36.230  6210  6210 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 11:25:36.231  6210  6210 D BluetoothMap: Create BluetoothMap proxy object
08-29 11:25:36.232  1031  1093 D BluetoothManagerService: Message: 30
08-29 11:25:36.237  1031  1093 D BluetoothManagerService: Message: 30
,08-29 11:25:36.239  6210  6210 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 11:25:36.240  6210  6210 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-29 11:25:36.256  6210  6210 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-29 11:25:36.263  6210  6210 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-29 11:25:36.274  6210  6210 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:25:36.296  6210  6210 D BluetoothInputDevice: Proxy object connected
,08-29 11:25:36.298  6210  6210 D HidProfile: Bluetooth service connected
08-29 11:25:36.299  6210  6210 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:25:36.301  6210  6210 D PanProfile: Bluetooth service connected
08-29 11:25:36.302  6210  6210 D BluetoothMap: Proxy object connected
08-29 11:25:36.302  6210  6210 D MapProfile: Bluetooth service connected
08-29 11:25:36.303  6210  6210 D BluetoothMap: getConnectedDevices()
08-29 11:25:36.304  6210  6210 D BluetoothMap: Bluetooth is Not enabled
08-29 11:25:36.304  6210  6210 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 11:25:36.361  1031  2028 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6256 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-29 11:25:36.369  1031  2028 I ActivityManager: Killing 5629:com.android.defcontainer/u0a4 (adj 15): empty #17
08-29 11:25:36.484  1031  2008 W libprocessgroup: failed to open /acct/uid_10004/pid_5629/cgroup.procs: No such file or directory
08-29 11:25:36.484  6232  6232 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-29 11:25:36.485  6232  6232 W LG Account v2.2: No ProfileInfo entries
08-29 11:25:36.486  6232  6232 I LG Account v2.2: isEnabled: false
08-29 11:25:36.486  6232  6232 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 11:25:36.487  6232  6232 I Feature : [Lifetracker]Country: EU
08-29 11:25:36.488  6232  6232 I Feature : [Lifetracker]Operator: OPEN
08-29 11:25:36.489  6232  6232 I Feature : [Lifetracker]Ranking support: false
08-29 11:25:36.489  6232  6232 I Feature : [Lifetracker]Comfort support: false
08-29 11:25:36.490  6232  6232 I Feature : [Lifetracker]Accessory: true
08-29 11:25:36.490  6232  6232 I Feature : [Lifetracker]Health device: true
08-29 11:25:36.491  6232  6232 I Feature : [Lifetracker]Extra Pedometer: false
08-29 11:25:36.491  6232  6232 I Feature : [Lifetracker]Blood glucose device: false
08-29 11:25:36.491  6232  6232 I Feature : [Lifetracker]Device Number: 3
08-29 11:25:36.527  6210  6210 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 11:25:36.538  6210  6210 D BluetoothPermissionRequest: onReceive
08-29 11:25:36.538  6256  6256 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 11:25:36.543  6210  6210 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 11:25:36.564  6210  6210 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 11:25:36.570  1031  1991 I ActivityManager: Killing 5728:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-29 11:25:36.629  3759  3759 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 11:25:36.629  3759  3759 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-29 11:25:36.630  3759  3759 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-29 11:25:36.633  1031  1956 W libprocessgroup: failed to open /acct/uid_10008/pid_5728/cgroup.procs: No such file or directory
08-29 11:25:36.643  3759  3759 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:36.643  3759  3759 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 11:25:36.644  6256  6256 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-29 11:25:36.647  3759  3759 V BluetoothFtpService: Ftp Service onStartCommand
08-29 11:25:36.647  3759  3759 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:36.648  3759  3759 V BluetoothFtpService: Ftp Service closeService
08-29 11:25:36.648  3759  3759 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 11:25:36.656  3759  3759 V BluetoothFtpService: successfully stopped ftp service
08-29 11:25:36.658  3759  3759 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-29 11:25:36.659  3759  3759 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:25:36.659  3759  3759 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:25:36.659  3759  3759 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:36.660  3759  3759 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 11:25:36.660  3759  3759 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 11:25:36.667  3759  3759 V BluetoothFtpService: Ftp Service onDestroy
08-29 11:25:36.667  3759  3759 V BluetoothFtpService: Ftp Service closeService
08-29 11:25:36.704  6256  6256 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-29 11:25:36.705  6256  6256 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-29 11:25:36.705  6256  6256 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-29 11:25:36.706  6256  6256 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 11:25:36.706  6256  6256 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-29 11:25:36.709  6256  6256 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 11:25:36.716  6256  6256 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-29 11:25:36.730  1031  1918 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6275 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 11:25:36.731  3759  3759 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:36.731  3759  3759 V BluetoothSapService: state: 13
08-29 11:25:36.732  3759  3759 V BluetoothSapService: Stopping SAP server process
08-29 11:25:36.734  3759  3759 V BluetoothSapService: Sap Service closeSapService in
08-29 11:25:36.734  3759  3759 V BluetoothSapService: Close listen Socket : 
08-29 11:25:36.734  3759  3759 V BluetoothSapService: Close rfcomm Socket : 
08-29 11:25:36.734  3759  3759 V BluetoothSapService: Close sapd  Socket : 
08-29 11:25:36.736  3759  3759 V BluetoothSapService: Sap Service closeSapService out
08-29 11:25:36.736  3759  3759 V BluetoothSapService: Sap Service onDestroy
08-29 11:25:36.736  3759  3759 V BluetoothSapService: Sap Service closeSapService in
08-29 11:25:36.736  3759  3759 V BluetoothSapService: Close listen Socket : 
08-29 11:25:36.736  3759  3759 V BluetoothSapService: Close rfcomm Socket : 
08-29 11:25:36.736  3759  3759 V BluetoothSapService: Close sapd  Socket : 
08-29 11:25:36.737  3759  3759 V BluetoothSapService: Sap Service closeSapService out
08-29 11:25:36.738  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:36.743  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:25:36.782  6256  6256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:25:36.784  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:36.788  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 11:25:36.788  6256  6256 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 11:25:36.789  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:25:36.789  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:25:36.791  6256  6256 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-29 11:25:36.797  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:36.806  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:36.806  6275  6275 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 11:25:36.812  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:36.813  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:25:36.814  6256  6256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:25:36.827  3759  3949 W bt-btif : ag scb idx 1 not allocated
08-29 11:25:36.827  3759  3848 D bt_hci_bdroid: cleanup
,08-29 11:25:36.827  3759  3949 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 11:25:36.828  3759  3951 I bt_lpm  : LPM is already off!!!
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:36.828  3759  4037 I bt_userial_mct: exiting userial_read_thread
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:25:36.828  3759  4037 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:25:36.828  3759  3949 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:36.828  3759  3949 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 11:25:36.828  3759  3848 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 11:25:36.828  3759  3951 I bt_vendor: hw_epilog_process
08-29 11:25:36.828  3759  3848 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 11:25:36.828  3759  3848 D bt_userial_mct: userial_close
08-29 11:25:36.828  3759  3848 E bt_userial_mct: pthread_join() FAILED result:3
08-29 11:25:36.828  3759  3848 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-29 11:25:36.868  1031  1046 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6296 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 11:25:36.871  1031  1046 I ActivityManager: Killing 5760:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-29 11:25:36.928  3759  3848 D bt_hci_bdroid: set_power 0
08-29 11:25:36.929  3759  3848 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 11:25:36.929  3759  3848 I bt_vendor: bluetooth satus is on
08-29 11:25:36.929  3759  3848 I bt_vendor: bt-vendor : resetting BT status
08-29 11:25:36.929  3759  3848 I bt_vendor: Starting hciattach daemon
08-29 11:25:36.929  3759  3848 I bt_vendor: try to set false
08-29 11:25:36.930  3759  3848 I bt_vendor: Starting hciattach daemon
08-29 11:25:36.930  3759  3848 I bt_vendor: try to set false
08-29 11:25:36.930  3759  3848 I bt_vendor: cleanup
08-29 11:25:36.931  3759  3949 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-29 11:25:36.989  1031  1047 W libprocessgroup: failed to open /acct/uid_10011/pid_5760/cgroup.procs: No such file or directory
,08-29 11:25:37.016  1031  1375 V AlarmManager: RTC_WAKEUP set : Alarm{202f1f06 type 0 when 1472462736729 com.android.vending} when 1472462736729
,08-29 11:25:37.024  3759  3848 I GKI_LINUX: GKI_exit_task 0 done
08-29 11:25:37.024  3759  3848 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 11:25:37.027  3759  3839 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 11:25:37.032  3759  3759 D HeadsetService: Received stop request...Stopping profile...
,08-29 11:25:37.034  3759  3759 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 11:25:37.034  3759  3869 D HeadsetStateMachine: Exit Disconnected: -1
08-29 11:25:37.034  3759  3759 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:25:37.034  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d752545
08-29 11:25:37.035  1031  1031 D BluetoothHeadset: Proxy object disconnected
08-29 11:25:37.036  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 11:25:37.036  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-29 11:25:37.036  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-29 11:25:37.037  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-29 11:25:37.038  3759  3759 D A2dpService: Received stop request...Stopping profile...
08-29 11:25:37.039  3759  3759 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 11:25:37.040  3759  3935 D A2dpStateMachine: Exit Disconnected: -1
08-29 11:25:37.043  3759  3839 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 11:25:37.043  3759  3759 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 11:25:37.043  3759  3759 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:25:37.043  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d752545
08-29 11:25:37.044  1031  1031 D BluetoothA2dp: Proxy object disconnected
08-29 11:25:37.044  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 11:25:37.046  3759  3759 D HidService: Received stop request...Stopping profile...
08-29 11:25:37.046  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d752545
,08-29 11:25:37.050  3759  3759 D HeadsetStateMachine: Unbinding service...
08-29 11:25:37.050  3759  3759 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:25:37.050  3759  3759 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:25:37.050  3759  3759 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:25:37.050  3759  3759 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:25:37.051  3759  3759 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 11:25:37.051  3759  3759 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:25:37.051  3759  3759 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 11:25:37.051  3759  3759 D HealthService: Received stop request...Stopping profile...
08-29 11:25:37.051  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d752545
08-29 11:25:37.052  6210  6210 D BluetoothInputDevice: Proxy object disconnected
08-29 11:25:37.053  3759  3759 D PanService: Received stop request...Stopping profile...
08-29 11:25:37.053  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d752545
08-29 11:25:37.054  6210  6210 D HidProfile: Bluetooth service disconnected
08-29 11:25:37.054  6210  6210 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 11:25:37.054  6210  6210 D PanProfile: Bluetooth service disconnected
08-29 11:25:37.054  3759  3759 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 11:25:37.055  3759  3759 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 11:25:37.055  3759  3759 D BtGatt.GattService: stop()
08-29 11:25:37.055  3759  3759 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 11:25:37.056  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d752545
08-29 11:25:37.057  3759  3759 D BluetoothMapService: Received stop request...Stopping profile...
08-29 11:25:37.057  3759  3759 D BluetoothMapService: stop()
08-29 11:25:37.058  3759  3759 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 11:25:37.058  3759  3759 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 11:25:37.058  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d752545
08-29 11:25:37.059  6210  6210 D BluetoothMap: Proxy object disconnected
08-29 11:25:37.059  3759  3759 I BluetoothA2dpServiceJni: cleanupNative
08-29 11:25:37.060  3759  3936 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-29 11:25:37.060  3759  3759 I GKI_LINUX: GKI_exit_task 2 done
08-29 11:25:37.060  3759  3759 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 11:25:37.060  3759  3759 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 11:25:37.060  3759  3759 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 11:25:37.061  3759  3759 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 11:25:37.061  3759  3759 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 11:25:37.061  3759  3759 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 11:25:37.061  3759  3759 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 11:25:37.061  3759  3759 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 11:25:37.062  3759  3759 V BluetoothMapService: Handler(): got msg=4
08-29 11:25:37.062  3759  3759 D BluetoothMapService: MAP Service closeService in
08-29 11:25:37.062  3759  3759 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:25:37.062  3759  3759 V BluetoothMapService: MAP Service closeService out
08-29 11:25:37.063  3759  3839 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 11:25:37.063  3759  3839 D BluetoothAdapterProperties: Setting state to 10
08-29 11:25:37.063  3759  3839 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 11:25:37.064  3759  3839 I BluetoothAdapterState: Entering OffState
08-29 11:25:37.064  3759  3759 D BluetoothMapService: cleanup()
08-29 11:25:37.064  3759  3759 D BluetoothMapService: MAP Service closeService in
08-29 11:25:37.064  3759  3759 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:25:37.064  3759  3759 V BluetoothMapService: MAP Service closeService out
08-29 11:25:37.067  6210  6210 D MapProfile: Bluetooth service disconnected
08-29 11:25:37.067  1031  1093 D BluetoothManagerService: Message: 60
08-29 11:25:37.067  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 11:25:37.067  1031  1093 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-29 11:25:37.068  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:25:37.068  6210  6226 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 11:25:37.069  1031  1093 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 11:25:37.069  6210  6227 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 11:25:37.070  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:25:37.070  6210  6226 D BluetoothMap: onBluetoothStateChange: up=false
08-29 11:25:37.071  6210  6227 D BluetoothPan: onBluetoothStateChange on: false
08-29 11:25:37.072  1031  1093 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:25:37.072  1850  2652 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:25:37.073  1031  1093 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 11:25:37.073  1031  1093 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-29 11:25:37.078  1031  1093 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 11:25:37.078  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:37.078  1031  1093 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 11:25:37.078  1031  1093 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@25e350e8 mBinding = false
08-29 11:25:37.080  1031  1093 D BluetoothManagerService: Sending unbind request.
08-29 11:25:37.080  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:37.082  1031  1093 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 11:25:37.084  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:25:37.084  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:37.085  1938  2125 D LGBluetoothAPIService: Message: 2
08-29 11:25:37.085  1938  2125 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3886865e mBinding = false
08-29 11:25:37.085  1938  2125 D LGBluetoothAPIService: Sending unbind request.
08-29 11:25:37.085  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:37.086  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:37.089  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:37.090  6210  6210 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 11:25:37.091  6210  6210 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 11:25:37.091  6210  6210 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 11:25:37.092  1598  1598 D BluetoothAdapter: 689873533: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:37.092  1598  1598 D BluetoothAdapter: 689873533: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:37.093  3759  3848 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 11:25:37.094  3759  3759 I GKI_LINUX: GKI_exit_task 1 done
08-29 11:25:37.094  3759  3759 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 11:25:37.094  3759  3759 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 11:25:37.094  3759  3759 I art     : --- WEIRD: removing null entry 246
08-29 11:25:37.094  3759  3759 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-29 11:25:37.094  3759  3759 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 11:25:37.097  3759  3759 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 11:25:37.097  6210  6210 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 11:25:37.099  3759  3759 I art     : System.exit called, status: 0
08-29 11:25:37.099  3759  3759 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 11:25:37.115  6210  6210 D DockEventReceiver: finishStartingService: stopping service
08-29 11:25:37.116   313  1381 V AudioFlinger: 3759 died, releasing its sessions
08-29 11:25:37.116   313  1381 V AudioFlinger:  pid 1850 @ 0
08-29 11:25:37.116   313  1381 V AudioFlinger:  pid 3157 @ 1
,08-29 11:25:37.116   313  1381 V AudioFlinger:  pid 3157 @ 2
08-29 11:25:37.117  6210  6210 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 11:25:37.122  1031  1991 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:25:37.137  1031  2047 I ActivityManager: Process com.android.bluetooth (pid 3759) has died
,08-29 11:25:37.137  1031  2047 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-29 11:25:37.142  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:25:37.145  6296  6317 W FormManager: Network not available. Please check & try again.
08-29 11:25:37.152  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:37.152  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:25:37.152  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:25:37.152  6210  6210 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-29 11:25:37.154  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:25:37.156  6296  6318 V FormManager: Network unavailable.
08-29 11:25:37.158  6296  6318 V FormManager: Network unavailable.
,08-29 11:25:37.164  6210  6210 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:25:37.165  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 11:25:37.165  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:25:37.165  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:25:37.165  6210  6210 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:25:37.165  6210  6210 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 11:25:37.172  6210  6210 D BluetoothPermissionRequest: onReceive
08-29 11:25:37.174  6210  6210 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 11:25:37.174  6210  6210 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 11:25:37.178  6210  6210 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 11:25:37.226  1031  1046 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6321 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 11:25:37.234  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:25:37.235  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:25:37.238  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 11:25:37.243  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:25:37.255  4234  6336 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 11:25:37.256  4234  6339 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:25:37.257  6192  6192 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 11:25:37.258  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:25:37.258  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:37.258  4234  6339 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:25:37.263  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:37.271  6296  6342 W FormManager: Network not available. Please check & try again.
08-29 11:25:37.273  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:37.282  6296  6343 V FormManager: Network unavailable.
,08-29 11:25:37.285  6296  6343 V FormManager: Network unavailable.
08-29 11:25:37.293  6256  6256 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-29 11:25:37.294  6321  6321 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 11:25:37.294  6321  6321 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 11:25:37.295  6321  6321 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 11:25:37.295  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 11:25:37.296  6321  6321 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 11:25:37.296  6256  6256 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-29 11:25:37.310  6321  6321 D BluetoothAdapterApp: Loading JNI Library
,08-29 11:25:37.336  6321  6321 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@348bdf42 Instance Count = 1
,08-29 11:25:37.339  6321  6321 D BluetoothAdapterApp: onCreate
08-29 11:25:37.342  6256  6256 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:25:37.342  6256  6256 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:25:37.344  5863  5863 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-29 11:25:37.348  1031  1046 I ActivityManager: Killing 5778:com.android.contacts/u0a19 (adj 15): empty #17
08-29 11:25:37.349  6256  6256 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-29 11:25:37.349  6256  6256 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 11:25:37.350  6256  6256 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-29 11:25:37.350  6256  6256 V SoundPool: doLoad: loading sample sampleID=1
08-29 11:25:37.350  6256  6256 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 11:25:37.352  6256  6347 V SoundPool: Start decode
08-29 11:25:37.352  6256  6347 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-29 11:25:37.352   313  1383 V MediaPlayerService: decode(22, 10857164, 17813)
08-29 11:25:37.353   313  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-29 11:25:37.353   313  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 11:25:37.353   313  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 11:25:37.353   313  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 11:25:37.353   313  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 11:25:37.353   313  1383 V MediaPlayerService: player type = 3
08-29 11:25:37.353   313  1383 V AwesomePlayer: AwesomePlayer create()
08-29 11:25:37.354   313  1383 V AwesomePlayer: reset_l() 
08-29 11:25:37.354   313  1383 V AwesomePlayer: cancelPlayerEvents
08-29 11:25:37.354   313  1383 V AwesomePlayer: setAudioSink() 
08-29 11:25:37.354   313  1383 V AwesomePlayer: reset_l() 
08-29 11:25:37.354   313  1383 V AudioCache: notify(0xb1432400, 8, 0, 0)
08-29 11:25:37.354   313  1383 V AudioCache: ignored
08-29 11:25:37.354   313  1383 V AwesomePlayer: cancelPlayerEvents
08-29 11:25:37.354   313  1383 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 11:25:37.354   313  1383 V AwesomePlayer: setDataSource_l dataSource
08-29 11:25:37.355   313  1383 V LGParserOSAL: SniffLGParser start
08-29 11:25:37.355   313  1383 V LGParserOSAL: MainType:5, SubType=0
08-29 11:25:37.355   313  1383 V LGParserOSAL: #### check Mime : application/ogg
08-29 11:25:37.355   313  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 11:25:37.355   313  1383 E MediaExtractor: Use LGExtractor :application/ogg 
08-29 11:25:37.355  6321  6321 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 11:25:37.355  6321  6321 D ProfileConfigQcom: Adding HeadsetService
08-29 11:25:37.355  6321  6321 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 11:25:37.356  6321  6321 D ProfileConfigQcom: Adding A2dpService
08-29 11:25:37.356  6321  6321 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 11:25:37.356  6321  6321 D ProfileConfigQcom: Adding HidService
08-29 11:25:37.356  6321  6321 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 11:25:37.356  6321  6321 D ProfileConfigQcom: Adding HealthService
08-29 11:25:37.356  6321  6321 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 11:25:37.357  6321  6321 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 11:25:37.357  6321  6321 D ProfileConfigQcom: Adding PanService
08-29 11:25:37.357  6321  6321 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 11:25:37.357  6321  6321 D ProfileConfigQcom: Adding GattService
08-29 11:25:37.357  6321  6321 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 11:25:37.357  6321  6321 D ProfileConfigQcom: Adding BluetoothMapService
08-29 11:25:37.358  6321  6321 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 11:25:37.359  6321  6321 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 11:25:37.402   313  1383 V LGParserOSAL: supported mime: application/ogg
08-29 11:25:37.402   313  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 11:25:37.402   313  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 11:25:37.402   313  1383 V AwesomePlayer: mBitrate = -1 bits/sec
08-29 11:25:37.402   313  1383 V AwesomePlayer: AudioTrack Setting
08-29 ,11:25:37.402   313  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 11:25:37.402   313  1383 V AwesomePlayer: setAudioSource() 
08-29 11:25:37.402   313  1383 V MediaPlayerService: prepare
08-29 11:25:37.402   313  1383 V AwesomePlayer: prepareAsync_l() 
08-29 11:25:37.402   313  1383 V MediaPlayerService: wait for prepare
08-29 11:25:37.402   313  6349 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 11:25:37.402   313  6349 V AwesomePlayer: initAudioDecoder() 
08-29 11:25:37.402   313  6349 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
,08-29 11:25:37.402   313  6349 V AudioSystem: isOffloadSupported()
08-29 11:25:37.403   313  6349 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 11:25:37.403   313  6349 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 11:25:37.403   313  6349 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 11:25:37.403   313  6349 V AwesomePlayer: getUseOffload() = 0 
08-29 11:25:37.403   313  6349 V OMXCodec: OMXCodec::Create
08-29 11:25:37.403   313  6349 V OMXCodec: findMatchingCodecs()
08-29 11:25:37.403   313  6349 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 11:25:37.403   313  6349 V OMXCodec: matchingCodecs.size()=1
08-29 11:25:37.403   313  6349 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-29 11:25:37.408   313  6349 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 11:25:37.408   313  6349 V LGCodecAdapter: LG Codec Adapter start
08-29 11:25:37.408   313  6349 V OMXCodec: OMXCodec Createtor
08-29 11:25:37.408   313  6349 V OMXCodec: setComponentRole
08-29 11:25:37.408   313  6349 V OMXCodec: configureCodec protected=0
08-29 11:25:37.408   313  6349 V LGCodecAdapter: called getLGCodecSpecificData
08-29 11:25:37.408   313  6349 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 11:25:37.408   313  6349 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 11:25:37.408   313  6349 V LGCodecOSAL: Called LGconfigureCodecMSG
08-29 11:25:37.408   313  6349 V LGCodecOSAL: Not support LGCodec
08-29 11:25:37.408   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 11:25:37.408   313  6349 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 11:25:37.409   313  6349 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 11:25:37.409   313  6349 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 11:25:37.409   313  6349 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 11:25:37.409   313  6349 V AudioSystem: isOffloadSupported()
08-29 11:25:37.409   313  6349 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 11:25:37.409   313  6349 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,08-29 11:25:37.409   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-29 11:25:37.409   313  6349 V OMXCodec: init()
08-29 11:25:37.409   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-29 11:25:37.409   313  6349 V OMXCodec: allocateBuffers
08-29 11:25:37.410   313  6349 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 11:25:37.410   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 11:25:37.410   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on input port
,08-29 11:25:37.411   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on input port
08-29 11:25:37.411   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on input port
08-29 11:25:37.411   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on input port
08-29 11:25:37.411   313  6349 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 11:25:37.411   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 11:25:37.411   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
08-29 11:25:37.411   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on output port
08-29 11:25:37.411   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434970 on output port
08-29 11:25:37.412   313  6349 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14349c0 on output port
08-29 11:25:37.412   313  6349 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 11:25:37.412   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 11:25:37.412   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
,08-29 11:25:37.412   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 11:25:37.412   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 11:25:37.412   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 11:25:37.412   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 11:25:37.412   313  6349 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 11:25:37.412   313  6349 V AwesomePlayer: finishAsyncPrepare_l() 
,08-29 11:25:37.412   313  6349 V AudioCache: notify(0xb1432400, 5, 0, 0)
08-29 11:25:37.412   313  6349 V AudioCache: ignored
08-29 11:25:37.412   313  6349 V AudioCache: notify(0xb1432400, 1, 0, 0)
,08-29 11:25:37.412   313  6349 V AudioCache: prepared
08-29 11:25:37.412   313  1383 V AudioCache: wait - success
08-29 11:25:37.412   313  1383 V MediaPlayerService: start
08-29 11:25:37.412   313  1383 V AwesomePlayer: play_l() 
08-29 11:25:37.412   313  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
,08-29 11:25:37.412   313  1383 V AwesomePlayer: createAudioPlayer_l
08-29 11:25:37.412   313  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
08-29 11:25:37.412   313  1383 V AwesomePlayer: startAudioPlayer_l() 
08-29 11:25:37.412   313  1383 D AudioPlayer: start of Playback, useOffload 0
08-29 11:25:37.412   313  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-29 11:25:37.413   313  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 11:25:37.416   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 11:25:37.416   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 11:25:37.416   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-29 11:25:37.416   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,08-29 11:25:37.416   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-29 11:25:37.416   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 11:25:37.417   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976144
08-29 11:25:37.417   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 11:25:37.417   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976464
08-29 11:25:37.417   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 11:25:37.417   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976944
08-29 11:25:37.417   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0,
08-29 11:25:37.417   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977024
08-29 11:25:37.417   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 11:25:37.417   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-29 11:25:37.417   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 11:25:37.418   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
,08-29 11:25:37.418   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 11:25:37.418   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-29 11:25:37.418   313  6351 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 11:25:37.418   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 11:25:37.418   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434970 on output port
08-29 11:25:37.418   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on output port
,08-29 11:25:37.418   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
08-29 11:25:37.418   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1006790 on output port
08-29 11:25:37.418   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-29 11:25:37.418   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-29 11:25:37.419   313  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
,08-29 11:25:37.421   313  1383 V AudioCache: notify(0xb1432400, 6, 0, 0)
08-29 11:25:37.421   313  1383 V AudioCache: ignored
08-29 11:25:37.421  1031  1991 W libprocessgroup: failed to open /acct/uid_10019/pid_5778/cgroup.procs: No such file or directory
08-29 11:25:37.421  6210  6210 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 11:25:37.422   313  1383 V MediaPlayerService: wait for playback complete
,08-29 11:25:37.423   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.423   313  6352 V AudioCache: memcpy(0xaf202000, 0xb57f8000, 4096)
,08-29 11:25:37.425   313  6352 V AudioCache: write(0xb57f8000, 4096)
,08-29 11:25:37.425   313  6352 V AudioCache: memcpy(0xaf203000, 0xb57f8000, 4096)
08-29 11:25:37.426   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.426   313  6352 V AudioCache: memcpy(0xaf204000, 0xb57f8000, 4096)
,08-29 11:25:37.427   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.427   313  6352 V AudioCache: memcpy(0xaf205000, 0xb57f8000, 4096)
08-29 11:25:37.427   313  6352 V AudioCache: write(0xb57f8000, 4096)
,08-29 11:25:37.427   313  6352 V AudioCache: memcpy(0xaf206000, 0xb57f8000, 4096)
08-29 11:25:37.427   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.427   313  6352 V AudioCache: memcpy(0xaf207000, 0xb57f8000, 4096)
08-29 11:25:37.433   313  6352 V AudioCache: write(0xb57f8000, 4096)
,08-29 11:25:37.434   313  6352 V AudioCache: memcpy(0xaf208000, 0xb57f8000, 4096)
08-29 11:25:37.434   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.434   313  6352 V AudioCache: memcpy(0xaf209000, 0xb57f8000, 4096)
,08-29 11:25:37.434   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.434   313  6352 V AudioCache: memcpy(0xaf20a000, 0xb57f8000, 4096)
08-29 11:25:37.434   313  6352 V AudioCache: write(0xb57f8000, 4096)
,08-29 11:25:37.434   313  6352 V AudioCache: memcpy(0xaf20b000, 0xb57f8000, 4096)
08-29 11:25:37.437   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.437   313  6352 V AudioCache: memcpy(0xaf20c000, 0xb57f8000, 4096)
08-29 11:25:37.437  6321  6321 V LGMDMManagerInternal: Create singleton instance
,08-29 11:25:37.438   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.438   313  6352 V AudioCache: memcpy(0xaf20d000, 0xb57f8000, 4096)
08-29 11:25:37.439   313  6352 V AudioCache: write(0xb57f8000, 4096)
,08-29 11:25:37.439   313  6352 V AudioCache: memcpy(0xaf20e000, 0xb57f8000, 4096)
,08-29 11:25:37.439   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.439   313  6352 V AudioCache: memcpy(0xaf20f000, 0xb57f8000, 4096)
08-29 11:25:37.440   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.440   313  6352 V AudioCache: memcpy(0xaf210000, 0xb57f8000, 4096)
08-29 11:25:37.441   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.441   313  6352 V AudioCache: memcpy(0xaf211000, 0xb57f8000, 4096)
08-29 11:25:37.442   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.442   313  6352 V AudioCache: memcpy(0xaf212000, 0xb57f8000, 4096)
08-29 11:25:37.442  6140  6140 D UEI.SmartControl: QS Service created
08-29 11:25:37.442   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.442   313  6352 V AudioCache: memcpy(0xaf213000, 0xb57f8000, 4096)
08-29 11:25:37.443   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.443   313  6352 V AudioCache: memcpy(0xaf214000, 0xb57f8000, 4096)
08-29 11:25:37.444   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.444   313  6352 V AudioCache: memcpy(0xaf215000, 0xb57f8000, 4096)
08-29 11:25:37.445   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.445   313  6352 V AudioCache: memcpy(0xaf216000, 0xb57f8000, 4096)
08-29 11:25:37.446   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.446   313  6352 V AudioCache: memcpy(0xaf217000, 0xb57f8000, 4096)
08-29 11:25:37.447   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.447   313  6352 V AudioCache: memcpy(0xaf218000, 0xb57f8000, 4096)
08-29 11:25:37.447  6256  6256 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 11:25:37.448   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.448   313  6352 V AudioCache: memcpy(0xaf219000, 0xb57f8000, 4096)
08-29 11:25:37.448   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.448   313  6352 V AudioCache: memcpy(0xaf21a000, 0xb57f8000, 4096)
08-29 11:25:37.449  6256  6256 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 11:25:37.449  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 11:25:37.449   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.449   313  6352 V AudioCache: memcpy(0xaf21b000, 0xb57f8000, 4096)
08-29 11:25:37.450   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.450   313  6352 V AudioCache: memcpy(0xaf21c000, 0xb57f8000, 4096)
08-29 11:25:37.451   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.451   313  6352 V AudioCache: memcpy(0xaf21d000, 0xb57f8000, 4096)
08-29 11:25:37.452   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.452   313  6352 V AudioCache: memcpy(0xaf21e000, 0xb57f8000, 4096)
08-29 11:25:37.453   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.453   313  6352 V AudioCache: memcpy(0xaf21f000, 0xb57f8000, 4096)
08-29 11:25:37.453   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.453   313  6352 V AudioCache: memcpy(0xaf220000, 0xb57f8000, 4096)
08-29 11:25:37.454   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.454   313  6352 V AudioCache: memcpy(0xaf221000, 0xb57f8000, 4096)
08-29 11:25:37.455   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.455   313  6352 V AudioCache: memcpy(0xaf222000, 0xb57f8000, 4096)
08-29 11:25:37.456   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.456   313  6352 V AudioCache: memcpy(0xaf223000, 0xb57f8000, 4096)
08-29 11:25:37.456   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.457   313  6352 V AudioCache: memcpy(0xaf224000, 0xb57f8000, 4096)
08-29 11:25:37.457   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.457   313  6352 V AudioCache: memcpy(0xaf225000, 0xb57f8000, 4096)
08-29 11:25:37.458   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.458   313  6352 V AudioCache: memcpy(0xaf226000, 0xb57f,8000, 4096)
08-29 11:25:37.459  6140  6140 I UEI.SmartControl: Service initServices...
08-29 11:25:37.459  6140  6140 D UEI.SmartControl: QS start get config
08-29 11:25:37.459   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.459   313  6352 V AudioCache: memcpy(0xaf227000, 0xb57f8000, 4096)
08-29 11:25:37.460   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.460   313  6352 V AudioCache: memcpy(0xaf228000, 0xb57f8000, 4096)
08-29 11:25:37.461   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.461   313  6352 V AudioCache: memcpy(0xaf229000, 0xb57f8000, 4096)
08-29 11:25:37.461   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.461   313  6352 V AudioCache: memcpy(0xaf22a000, 0xb57f8000, 4096)
08-29 11:25:37.462   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.462   313  6352 V AudioCache: memcpy(0xaf22b000, 0xb57f8000, 4096)
08-29 11:25:37.463   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.463   313  6352 V AudioCache: memcpy(0xaf22c000, 0xb57f8000, 4096)
08-29 11:25:37.464   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.464   313  6352 V AudioCache: memcpy(0xaf22d000, 0xb57f8000, 4096)
08-29 11:25:37.464   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.464   313  6352 V AudioCache: memcpy(0xaf22e000, 0xb57f8000, 4096)
08-29 11:25:37.465   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.465   313  6352 V AudioCache: memcpy(0xaf22f000, 0xb57f8000, 4096)
08-29 11:25:37.466   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.466   313  6352 V AudioCache: memcpy(0xaf230000, 0xb57f8000, 4096)
08-29 11:25:37.466   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.466   313  6352 V AudioCache: memcpy(0xaf231000, 0xb57f8000, 4096)
08-29 11:25:37.467   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.467   313  6352 V AudioCache: memcpy(0xaf232000, 0xb57f8000, 4096)
08-29 11:25:37.468   313  6352 V AudioCache: write(0xb57f8000, 4096)
08-29 11:25:37.468   313  6352 V AudioCache: memcpy(0xaf233000, 0xb57f8000, 4096)
08-29 11:25:37.469   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,08-29 11:25:37.469   313  6352 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 11:25:37.469   313  6352 V AwesomePlayer: postAudioEOS() 
08-29 11:25:37.469   313  6352 V AudioCache: write(0xb57f8000, 280)
08-29 11:25:37.469   313  6352 V AudioCache: memcpy(0xaf234000, 0xb57f8000, 280)
08-29 11:25:37.475  6256  6256 V LGMDMManager: Create singleton instance
08-29 11:25:37.477   313  6349 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 11:25:37.477   313  6349 V AwesomePlayer: onStreamDone
08-29 11:25:37.477   313  6349 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 11:25:37.477   313  6349 V AudioCache: notify(0xb1432400, 2, 0, 0)
08-29 11:25:37.477   313  6349 V AudioCache: playback complete
08-29 11:25:37.477   313  6349 V AwesomePlayer: pause_l() 
08-29 11:25:37.477   313  6349 V AudioCache: notify(0xb1432400, 7, 0, 0)
08-29 11:25:37.477   313  6349 V AudioCache: ignored
08-29 11:25:37.477   313  6349 V AwesomePlayer: cancelPlayerEvents
08-29 11:25:37.477   313  1383 V AudioCache: wait - success
08-29 11:25:37.477   313  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-29 11:25:37.478   313  6349 D AudioPlayer: Pause Playback at 1068125
08-29 11:25:37.478   313  1383 V AwesomePlayer: reset_l() 
08-29 11:25:37.478   313  1383 V AudioCache: notify(0xb1432400, 8, 0, 0)
08-29 11:25:37.478   313  1383 V AudioCache: ignored
08-29 11:25:37.478   313  1383 V AwesomePlayer: cancelPlayerEvents
08-29 11:25:37.478   313  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 11:25:37.478   313  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 11:25:37.478   313  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 11:25:37.478   313  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 11:25:37.478   313  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 11:25:37.478   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 11:25:37.478   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 11:25:37.478   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 11:25:37.478   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 0
08-29 11:25:37.478   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 0
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 0
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 0
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1006790 on port 1
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 1
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434790 on port 1
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434970 on port 1
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] fr,eeBuffer portIndex=1,bufIndex=0
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 11:25:37.479   313  6351 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 11:25:37.479   313  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,08-29 11:25:37.479   313  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 11:25:37.479   313  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,08-29 11:25:37.481   313  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 11:25:37.481   313  1383 D AudioPlayer: AudioPlayer releasing audio source
08-29 11:25:37.481   313  1383 D AudioPlayer: AudioPlayer done releasing audio source
08-29 11:25:37.481   313  1383 V AwesomePlayer: reset_l() 
08-29 11:25:37.481   313  1383 V AwesomePlayer: cancelPlayerEvents
08-29 11:25:37.481   313  1383 V AwesomePlayer: ~AwesomePlayer call
08-29 11:25:37.481   313  1383 V AwesomePlayer: reset_l() 
08-29 11:25:37.481   313  1383 V AwesomePlayer: cancelPlayerEvents
08-29 11:25:37.482  6256  6347 V SoundPool: close(31)
08-29 11:25:37.482  6256  6347 V SoundPool: pointer = 0x9fe70000, size = 205080, sampleRate = 48000, numChannels = 2
08-29 11:25:37.513  6321  6321 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:37.517  6321  6321 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:25:37.517  6321  6321 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:25:37.517  6321  6321 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:25:37.518  6321  6321 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:37.519  6321  6321 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 11:25:37.529  6275  6275 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 11:25:37.538  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 11:25:37.538  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-29 11:25:37.540  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4966
08-29 11:25:37.560  4381  6354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-29 11:25:37.755  6140  6140 I UEI.SmartControl: Supports setup maps: true
,08-29 11:25:37.758  6140  6140 D UEI.SmartControl: QS start statue = true Error code = 0
,08-29 11:25:37.758  6140  6140 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 11:25:37.758  6140  6140 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 11:25:37.758  6140  6140 I UEI.SmartControl: ### init IR Blaster...
08-29 11:25:37.761  6140  6140 D serial_port: Configuring serial port
08-29 11:25:37.762  6140  6140 E UEI.SmartControl: UEIBLaster setting for 616
08-29 11:25:37.762  6140  6140 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 11:25:37.762  6140  6140 I UEI.SmartControl: configuring settings for MAXQ616
08-29 11:25:37.762  6140  6140 I UEI.SmartControl: Get version...
08-29 11:25:37.780  6140  6362 D UEI.SmartControl: serial port data available: 21
,08-29 11:25:37.807  6140  6140 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 11:25:37.807  6140  6140 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 11:25:37.807  6140  6140 I UEI.SmartControl: QS saving settings...
08-29 11:25:37.810  6140  6140 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 11:25:37.825  6140  6362 D UEI.SmartControl: serial port data available: 4
,08-29 11:25:37.857  6140  6368 I UEI.SmartControl: Device manager: loading config....
08-29 11:25:37.859  6140  6368 D UEI.SmartControl: ----------- loading internal config...
08-29 11:25:37.859  6140  6140 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 11:25:37.863  6140  6140 E UEI.SmartControl: Services init done
08-29 11:25:37.863  6140  6140 D UEI.SmartControl: QS Service init finished
08-29 11:25:37.866  6140  6140 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 11:25:37.866  6140  6140 D UEI.SmartControl: QS Service version code: 201091
08-29 11:25:37.867  6140  6140 D UEI.SmartControl: Service requested: Control
08-29 11:25:37.871  6140  6368 E UEI.SmartControl: Loading SETTINGS...
08-29 11:25:37.872  6140  6140 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-29 11:25:37.878  6256  6256 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-29 11:25:37.881  6140  6156 I UEI.SmartControl: ------ IControl API: 11
08-29 11:25:37.882  6140  6156 D UEI.SmartControl: File observer start...
08-29 11:25:37.882  6140  6156 E UEI.SmartControl: IR Port is disabled: false
08-29 11:25:37.883  6140  6156 D UEI.SmartControl: Starting file observer...
08-29 11:25:37.883  6140  6156 I UEI.SmartControl: Registering callback...
08-29 11:25:37.884  6140  6155 I UEI.SmartControl: ------ IControl API: 19
08-29 11:25:37.886  6140  6155 I UEI.SmartControl: Registering Services Ready callback...
,08-29 11:25:37.891  6140  6140 D UEI.SmartControl: Internal service binding...
08-29 11:25:37.899  6140  6368 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-29 11:25:37.917  6140  6367 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 11:25:37.917  6140  6367 D UEI.SmartControl: -----service ready thread exits
08-29 11:25:37.918  6256  6271 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-29 11:25:37.918  6256  6345 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 11:25:37.919  6256  6345 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 11:25:37.919  6256  6256 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 11:25:37.920  6256  6256 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 11:25:37.920  6140  6156 I UEI.SmartControl: ------ IControl API: 8
08-29 11:25:37.922  6256  6256 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 11:25:37.922  6256  6256 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 11:25:37.922  6256  6256 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 11:25:37.923  6256  6256 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 11:25:37.924  6256  6256 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 11:25:37.924  6256  6256 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-29 11:25:37.926  6256  6256 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 11:25:37.930  6256  6256 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 11:25:37.931  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-29 11:25:37.933  6256  6256 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 11:25:37.934  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 11:25:37.935  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 11:25:37.937  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-29 11:25:37.939  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 11:25:37.941  6256  6256 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472462737940]
08-29 11:25:37.943  6256  6256 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-29 11:25:37.946  1031  2008 I ActivityManager: Killing 5835:com.android.gallery3d/u0a27 (adj 15): empty #17
08-29 11:25:37.968  6256  6373 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-29 11:25:37.987  1031  2008 I ActivityManager: Killing 5799:com.lge.email/u0a23 (adj 15): empty #18
,08-29 11:25:38.038  1031  1588 W libprocessgroup: failed to open /acct/uid_10027/pid_5835/cgroup.procs: No such file or directory
,08-29 11:25:38.042  1031  1955 W libprocessgroup: failed to open /acct/uid_10023/pid_5799/cgroup.procs: No such file or directory
08-29 11:25:38.050  6256  6256 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-29 11:25:38.051  6256  6256 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-29 11:25:38.051  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-29 11:25:38.051  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-29 11:25:38.052  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,08-29 11:25:38.052  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-29 11:25:38.052  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-29 11:25:38.062  6256  6256 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-29 11:25:38.778  1031  1918 D WifiServiceImplEx: setWifiEnabled: true pid=5966, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 11:25:38.780  1031  1918 D WifiService: setWifiEnabled: true pid=5966, uid=10118
08-29 11:25:38.780  1031  1918 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:25:38.808  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:25:38.808  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:25:38.808  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-29 11:25:38.810  1031  1535 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 11:25:38.810  1031  1535 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-29 11:25:38.813  1031  1535 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 11:25:38.813  1031  1535 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 11:25:38.813  1031  1535 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 11:25:38.813  1031  1535 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 11:25:38.813  1031  1535 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 11:25:38.813  1031  1535 E WifiHW  : unknown target_country: EU , set to default
08-29 11:25:38.813  1031  1535 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 11:25:38.813  1031  1535 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 11:25:38.813  1031  1535 I WifiUtil: gEnableBmps=1
08-29 11:25:39.412   309   890 D SoftapController: Softap fwReload - Ok
,08-29 11:25:39.415  1031  1093 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 11:25:39.419  1031  1535 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (600ms)
08-29 11:25:39.428   309   890 D CommandListener: Setting iface cfg
08-29 11:25:39.428   309   890 D CommandListener: Trying to bring down wlan0
,08-29 11:25:39.433   309  6401 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 11:25:39.449  1031  1093 D Tethering: InitialState.processMessage what=4
08-29 11:25:39.449  1031  1093 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 11:25:39.452   309   890 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:25:39.455  1031  1535 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 11:25:39.456  1031  1091 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 11:25:39.460  1031  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:25:39.460  1031  1535 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:25:39.460  1031  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:25:39.455  6402  6402 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 11:25:39.471  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 11:25:39.465  6402  6402 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:39.480  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:25:39.497  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:39.501  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:39.501  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 11:25:39.507  1031  1535 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 11:25:39.507  1031  1535 D WifiMonitor: connecting to supplicant
08-29 11:25:39.524  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:39.525  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:25:39.525  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-29 11:25:39.525  6210  6210 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:25:39.527  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:25:39.534  6402  6402 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 11:25:39.535  6210  6210 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:25:39.536  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 11:25:39.536  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:25:39.536  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:25:39.536  6210  6210 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:25:39.536  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 11:25:39.538  6210  6210 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-29 11:25:39.544  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:39.545  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:25:39.545  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:25:39.545  6210  6210 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:25:39.548  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:25:39.548  6210  6210 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:25:39.548  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 11:25:39.548  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:25:39.548  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:25:39.548  6210  6210 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:25:39.548  6210  6210 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 11:25:39.554  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:25:39.556  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:39.561  6402  6402 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 11:25:39.561  6402  6402 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 11:25:39.568  6296  6421 W FormManager: Network not available. Please check & try again.
08-29 11:25:39.570  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:39.576  6296  6422 V FormManager: Network unavailable.
,08-29 11:25:39.582  6296  6422 V FormManager: Network unavailable.
08-29 11:25:39.640  6402  6402 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 11:25:39.711  6402  6402 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 11:25:39.722  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-29 11:25:39.723  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 11:25:39.724  1031  1535 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 11:25:39.725  1031  1535 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 11:25:39.725  1031  1535 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 11:25:39.726  1031  1535 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 11:25:39.726  1031  1535 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:39.726  1031  6424 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,08-29 11:25:39.727  1031  6424 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 11:25:39.727  1031  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:39.727  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 11:25:39.727  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 11:25:39.727  1031  1535 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:39.727  1031  6424 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 11:25:39.727  1031  6424 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 11:25:39.728  1031  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:39.728  1031  1535 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 11:25:39.728  1031  1535 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 11:25:39.730  1031  1535 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 11:25:39.730  1031  1535 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 11:25:39.730  1031  1535 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 11:25:39.731  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:39.731  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:39.732  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:39.732  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:39.732  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:25:39.732  1031  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:25:39.732  1031  1535 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:25:39.732  1031  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:25:39.736  1938  1938 D WfdService: Waiting for WifiP2p enabling
08-29 11:25:39.737  1031  1535 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 11:25:39.738  1031  1535 D WifiNative-wlan0: SET update_config 1: returned true
08-29 11:25:39.738  1031  1535 D WifiConfigStore: Loading config and enabling all networks 
08-29 11:25:39.738  1031  1535 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 11:25:39.739  1031  1535 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 11:25:39.739  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:39.741  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 11:25:39.742  1031  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-29 11:25:39.743  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:39.744  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:39.744  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:39.744  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:39.744  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:39.744  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:39.744  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:39.744  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:39.744  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:39.744  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:39.744  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:39.746  1031  1535 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 11:25:39.749  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:39.749  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:39.749  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:39.749  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:39.749  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:39.749  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:39.749  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:39.749  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:39.749  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:39.749  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:39.749  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:39.754  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:25:39.757  1031  1535 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 11:25:39.757  1031  1535 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 11:25:39.759  1031  1535 D WifiStateMachine: enableVerboseLogging : level 2
08-29 11:25:39.759  1031  1535 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 11:25:39.760  1031  1535 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 11:25:39.760  1031  1535 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 11:25:39.760  1031  1535 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 11:25:39.760  1031  1535 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 11:25:39.760  1031  1535 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 11:25:39.761  1031  1535 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 11:25:39.761  1031  1535 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 11:25:39.761  1031  1535 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 11:25:39.761  1031  1535 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 11:25:39.762  1031  1535 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 11:25:39.762  1031  1535 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 11:25:39.762  1031  1535 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 11:25:39.762  1031  1535 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 11:25:39.764  1031  1535 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 11:25:39.764  1031  1535 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 11:25:39.764  1938  1938 D WfdsService: Supplicant Connection state is changed : true
08-29 11:25:39.764  1938  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 11:25:39.764  1938  2334 D WfdsService: Set the WFDS Monitor: true
08-29 11:25:39.764  1938  2334 D WfdsMonitor: WfdsMonitorThread create
08-29 11:25:39.764  1031  1535 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 11:25:39.764  1031  1535 D WifiNative-HAL: Setting external_sim to 1
08-29 11:25:39.764  1031  1535 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 11:25:39.764  1938  2334 D WfdsMonitor: WFDS Monitor is created and started
08-29 11:25:39.765  1938  2334 D WfdsService: WiFi: Supplicant connection re-established
08-29 11:25:39.765  1031  1535 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 11:25:39.765  1031  1535 I WifiNative-HAL: startHal
08-29 11:25:39.765  1031  1535 D wifi    : setting scan oui 0x95278fe0
08-29 11:25:39.765  1938  6427 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 11:25:39.765  1031  1535 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 11:25:39.766  1031  1535 I WifiNative-HAL: startHal
08-29 11:25:39.766  1031  1535 D wifi    : setting scan oui 0x95278fe0
08-29 11:25:39.766  1031  1535 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 11:25:39.766  1938  6427 E CtrlSupplicant: Succeed to open control connection
08-29 11:25:39.766  1938  6427 E CtrlSupplicant: Succeed to open monitor connection
08-29 11:25:39.766  1938  6427 D WfdsMonitor: Supplicant connection established
,08-29 11:25:39.766  1938  2334 D WfdsService: Connected to the supplicant for wfds
08-29 11:25:39.767  1031  1535 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 11:25:39.767  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 11:25:39.767  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 11:25:39.767  1031  1535 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 11:25:39.767  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 11:25:39.768  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 11:25:39.768  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 11:25:39.768  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 11:25:39.768  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 11:25:39.768  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 11:25:39.768  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 11:25:39.769  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 11:25:39.769  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 11:25:39.769  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 11:25:39.769  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 11:25:39.769  6296  6426 W FormManager: Network not available. Please check & try again.
08-29 11:25:39.769  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 11:25:39.769  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 11:25:39.769  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:39.770  6402  6402 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 11:25:39.770  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 11:25:39.770  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 11:25:39.770  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 11:25:39.770  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 11:25:39.771  1031  1535 E WifiNative: : [120,070,928 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 11:25:39.771  1031  1535 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 11:25:39.772  1031  1535 D WifiNative-wlan0: RECONNECT: returned true
08-29 11:25:39.772  1031  1535 D WifiNative-wlan0: doString: [STATUS]
08-29 11:25:39.773  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 11:25:39.773  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 11:25:39.773  1031  1535 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 11:25:39.773  1031  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:25:39.774  1031  1535 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:25:39.774  1031  1533 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.776   309   890 D CommandListener: Setting iface cfg
08-29 11:25:39.776   309   890 D CommandListener: Trying to bring up p2p0
08-29 11:25:39.776  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:39.776  1031  1533 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 11:25:39.776  1031  1533 D LGWifiP2pService: P2pEnablingState
,08-29 11:25:39.777  1031  1535 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 11:25:39.777  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 11:25:39.777  1031  1031 D RttService: SCAN_AVAILABLE : 3
08-29 11:25:39.777  1031  1552 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.777  1031  1552 I WifiNative-HAL: startHal
08-29 11:25:39.777  1031  1552 D wifi    : getting scan capabilities on interface[1] = 0x95278fe0
08-29 11:25:39.777  1031  1552 D wifi    : failed to get capabilities : -3
08-29 11:25:39.777  1031  1535 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 11:25:39.777  1031  1552 E WifiScanningService: could not get scan capabilities
08-29 11:25:39.777  1031  1553 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.778  1031  1535 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 11:25:39.778  1031  1535 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 11:25:39.779  1031  1535 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 11:25:39.779  1031  1533 D LGWifiP2pService: P2pEnablingState{ when=-3ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.779  1031  1533 D LGWifiP2pService: P2p socket connection successful
08-29 11:25:39.779  1031  1533 D LGWifiP2pService: P2pEnabledState
08-29 11:25:39.779  1031  1535 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 11:25:39.780  1031  1535 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 11:25:39.780  1031  1535 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 11:25:39.780  6402  6402 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 11:25:39.780  1031  1533 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 11:25:39.781  1031  1535 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 11:25:39.781  1031  1535 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 11:25:39.781  1031  1535 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 11:25:39.781  1031  1535 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 11:25:39.782  6402  6402 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 11:25:39.783  1031  1535 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 11:25:39.784  1031  1533 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 11:25:39.784  1031  1535 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 11:25:39.785  1031  1535 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 11:25:39.785  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 11:25:39.786  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 11:25:39.786  1938  1938 D WfdsService: WifiP2pState is changed : true
08-29 11:25:39.786  1938  1938 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 11:25:39.786  1031  1533 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 11:25:39.787  1031  1533 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 11:25:39.787  1938  1938 D WfdsService: isConnected: false
08-29 11:25:39.787  1938  2334 D WfdsService: Receive the WFDS_ENABLE Method
08-29 11:25:39.787  1031  1533 D WifiNative-p2p0: SET device_name G3: returned true
08-29 11:25:39.787  1938  2334 D WfdsService: Set the WFDS Monitor: true
08-29 11:25:39.787  1031  1533 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 11:25:39.787  1031  1533 D LGWifiP2pService: before postfix = G3
08-29 11:25:39.787  1938  2334 D WfdsService: Connected to the supplicant for wfds
08-29 11:25:39.787  1031  1533 D WifiServerServiceExt: postfix byte check : 2
08-29 11:25:39.787  1938  2334 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 11:25:39.787  1031  1533 D LGWifiP2pService: after postfix = G3
08-29 11:25:39.787  6402,  6402 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 11:25:39.788  1938  2334 D WfdsService: selectPreferredScanChannel [36]
08-29 11:25:39.788  1938  2334 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 11:25:39.788  1031  1533 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 11:25:39.788  1031  1533 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 11:25:39.788  1031  1533 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 11:25:39.789  1031  1533 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 11:25:39.789  1031  1533 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 11:25:39.789  1031  1533 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 11:25:39.789  1031  1533 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 11:25:39.790  1031  1533 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 11:25:39.790  1031  1533 D WifiNative-HAL: p2pGetDeviceAddress
08-29 11:25:39.791  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 11:25:39.791  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:39.791  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:25:39.791  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:39.792  1031  6424 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:39.792  1031  6424 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:39.792  6402  6402 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 11:25:39.792  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.792  1031  1535 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 11:25:39.792  1938  6427 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:39.792  1031  6424 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:39.792  1031  6424 E WifiMonitor: WifiMonitor:p2p0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.792  1031  6424 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.792  1031  6424 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.793  1031  1535 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:25:39.793  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.793  1938  6427 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:39.793  1031  6424 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:39.793  1031  6424 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.793  1031  6424 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.793  1031  1535 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:25:39.793  1031  6424 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.793  1031  1535 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:25:39.793  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 11:25:39.794  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 11:25:39.794  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:25:39.795  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE ini,t=CORE type=UNKNOWN]
08-29 11:25:39.795  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:25:39.795  1031  6424 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:25:39.795  1031  6424 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:25:39.795  1031  1535 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 11:25:39.795  1031  1535 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 11:25:39.796  1031  1535 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 11:25:39.796  1031  1535 D WifiNative-wlan0: doBoolean: SCAN
08-29 11:25:39.796  1031  1535 D WifiNative-wlan0: SCAN: returned false
08-29 11:25:39.797  1031  1533 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 11:25:39.797  1031  1533 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 11:25:39.797  1031  1533 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 11:25:39.798  1031  1533 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 11:25:39.798  1031  1533 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 11:25:39.799  1031  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=120099  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 11:25:39.799  1938  1938 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 11:25:39.799  1938  1938 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 11:25:39.799  1938  1938 D WfdsService: Update P2p Interface State: 3
08-29 11:25:39.799  1031  1533 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 11:25:39.799  1031  1533 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 11:25:39.800  1031  1533 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 11:25:39.800  1031  1533 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 11:25:39.802  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:25:39.802  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:25:39.805  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:39.805  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:39.806  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:39.806  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:39.806  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:39.806  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 11:25:39.807  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=120104  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 11:25:39.807  1031  1533 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 11:25:39.807  1031  1533 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 11:25:39.808  1031  1533 D LGWifiP2pService: InactiveState
08-29 11:25:39.808  1031  1533 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.808  1031  1535 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:25:39.808  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.808  1031  1533 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 11:25:39.808  1031  1535 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:25:39.808  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 11:25:39.809  1031  1535 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:25:39.809  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:39.809  1938  6427 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:25:39.809  1031  1535 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:25:39.809  1031  1535 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:25:39.809  6402  6402 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 11:25:39.809  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.810  1938  6427 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:39.810  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.810  1938  6427 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:39.810  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:25:39.811  1031  6424 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:25:39.811  1031  6424 E WifiMonitor: WifiMonitor:p2p0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:39.811  1031  6424 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:39.811  1031  6424 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:39.811  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:39.811  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 11:25:39.811  1031  6424 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:39.811  1031  6424 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.811  1031  6424 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.811  1031  6424 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.811  1031  6424 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:39.811  1031  6424 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.811  1031  6424 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.811  1031  6424 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:39.811  1031  1533 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 11:25:39.811  1031  1533 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1031  1533 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:39.812  1938  2334 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 11:25:39.814  1031  1031 E WifiServerServiceExt: No p2p device connected
08-29 11:25:39.814  6296  6428 V FormManager: Network unavailable.
08-29 11:25:39.815  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:25:39.816  6296  6428 V FormManager: Network unavailable.
08-29 11:25:39.818  6116  6116 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 11:25:39.819  6116  6116 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-29 11:25:39.819  4234  6429 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 11:25:39.822  6116  6116 V [BNRBootReceiver]: Boot Receiver Return
08-29 11:25:39.826  4234  6430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:25:39.826  4234  6430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:25:39.827  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:39.831  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:39.837  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:39.841  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:39.841  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:39.842  6256  6256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:25:40.392  6402  6402 E wpa_supplicant: USIM:  scard_init function
08-29 11:25:40.394  6402  6402 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-29 11:25:40.401  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 11:25:40.402  1031  6424 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 11:25:40.402  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 11:25:40.402  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: WPS-AP-AVAILABLE 
08-29 11:25:40.402  1031  6424 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 11:25:40.403  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 11:25:40.403  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 11:25:40.404  1031  1535 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-29 11:25:40.404  1031  1535 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-29 11:25:40.404  1031  1535 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-29 11:25:40.405  1031  1535 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-29 11:25:40.405  1031  1535 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 11:25:40.425  1031  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=120725  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 11:25:40.431  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 11:25:40.434  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.434  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.434  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 11:25:40.435  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=120735  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 11:25:40.436  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:40.436  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 11:25:40.443  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.443  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.443  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 11:25:40.444  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:40.444  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 11:25:40.449  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:25:40.453  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:40.453  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:40.454  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:25:40.463  6210  6210 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 11:25:40.474  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:25:40.485  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:40.495  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:40.506  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:40.506  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:25:40.510  6256  6256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:25:40.514  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:40.524  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:40.531  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:40.538  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:40.538  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:40.539  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 11:25:40.549  6402  6402 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-29 11:25:40.554  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 11:25:40.554  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 11:25:40.554  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 11:25:40.554  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 11:25:40.555  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:25:40.555  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-29 11:25:40.563  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:25:40.563  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:25:40.564  6402  6402 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:25:40.566  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:25:40.570  1031  1093 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 11:25:40.574  1031  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=120874  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 11:25:40.577  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,08-29 11:25:40.577  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:25:40.578  1031  6424 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:25:40.578  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 11:25:40.578  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:25:40.578  1031  6424 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:25:40.578  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:25:40.578  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:25:40.579  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=120875  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 11:25:40.580  1031  1535 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120880
08-29 11:25:40.581  1031  1535 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120881
08-29 11:25:40.581  1031  1535 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120881
08-29 11:25:40.582  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120881
08-29 11:25:40.582  1031  1535 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120882
08-29 11:25:40.582  1031  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=120882  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-29 11:25:40.590  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:40.590  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:25:40.590  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:25:40.590  6210  6210 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:25:40.592  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.592  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.592  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 11:25:40.593  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:40.593  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:40.594  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=120893  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 11:25:40.594  1031  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=120894  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 11:25:40.595  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=120895  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 11:25:40.595  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:25:40.596  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.596  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.596  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 11:25:40.596  1031  1535 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=120896
08-29 11:25:40.596  1031  1535 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=120896
08-29 11:25:40.597  1031  1535 D WifiNative-wlan0: doString: [STATUS]
08-29 11:25:40.598  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:25:40.598  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:25:40.598  1031  1535 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 11:25:40.600  1031  1535 I WifiServiceExtension: setVHTCapabilityType  : false
,08-29 11:25:40.602  6210  6210 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:25:40.602  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 11:25:40.602  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:25:40.602  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:25:40.602  6210  6210 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:25:40.602  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 11:25:40.603  6210  6210 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 11:25:40.605  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:40.608  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:40.608  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:40.608  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:40.609  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:40.612  1031  1535 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 11:25:40.612  1031  1535 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 11:25:40.614  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:40.619  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.619  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.620  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 11:25:40.621  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.621  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:40.621  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 11:25:40.624  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:40.624  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:40.624  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:40.625  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:25:40.627  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:40.627  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:40.630  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:40.634  1031  1535 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 11:25:40.634  1031  1541 D ConnectivityService: Got NetworkAgent Messenger
08-29 11:25:40.634  1031  1535 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:25:40.634  1031  1535 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 11:25:40.634  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:40.634  1031  1535 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 11:25:40.634  1031  1535 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 11:25:40.635  1031  1541 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 11:25:40.635  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:40.635  1031  1541 D ConnectivityService: NetworkAgent connected
08-29 11:25:40.635  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:25:40.638  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:25:40.638  1031  1535 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 11:25:40.638  1031  1535 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:25:40.638  1031  1535 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 11:25:40.638  1031  1535 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 11:25:40.638  1031  1535 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 11:25:40.642  1031  1535 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 11:25:40.645  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 11:25:40.645   309   890 D CommandListener: Setting iface cfg
,08-29 11:25:40.649  1031  1535 E WifiStateMachine: Start Dhcp Watchdog 1
08-29 11:25:40.649  1031  6460 D DhcpStateMachine: StoppedState
08-29 11:25:40.649  1031  6460 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:40.649  1031  6460 D DhcpStateMachine: WaitBeforeStartState
08-29 11:25:40.649  1031  1535 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=120949  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-29 11:25:40.650  1031  1535 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=120950  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:25:40.650  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=120950  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:25:40.651  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:40.651  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:40.651  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:40.652  1031  1535 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:40.652  1031  1535 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:40.652  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:40.653  1031  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:40.655  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:40.655  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:40.656  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:25:40.656  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:40.656  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 11:25:40.659  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:40.660  1031  1535 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=120959  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:25:40.660  1031  1535 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=120960  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:25:40.660  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:40.660  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 11:25:40.661  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=120961  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-29 11:25:40.663  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-711041865] from screen [on:0 period:-711041865]
08-29 11:25:40.664  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-711041864]
08-29 11:25:40.664  1031  1535 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 11:25:40.665  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 11:25:40.668  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:40.670  1031  1541 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
08-29 11:25:40.670  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:40.670  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:40.670  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:40.671  1031  1535 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:40.671  1031  1535 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:40.671  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:40.672  1031  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:40.672  1031  1541 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-29 11:25:40.672  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-29 11:25:40.673  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-29 11:25:40.673  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 11:25:40.673  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 11:25:40.673  1031  1535 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
,08-29 11:25:40.673  1031  1535 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 11:25:40.674  1031  1535 D WifiNative-wlan0: SET ps 0: returned true
08-29 11:25:40.674  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 11:25:40.674  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 11:25:40.675  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:40.675  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:40.675  1031  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
,08-29 11:25:40.675  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:25:40.676  1031  1535 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 11:25:40.676  1031  1535 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 11:25:40.676  1031  1533 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2be70869 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:40.676  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2be70869 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:40.676  1031  6460 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:40.676  1031  1535 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 11:25:40.676  1031  1535 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-29 11:25:40.677  1031  6460 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 11:25:40.679  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:40.680  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:40.680  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 11:25:40.680  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:40.680  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 11:25:40.687  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:40.692  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:40.698  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:40.698  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:40.699  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 11:25:40.742  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:40.742  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:25:40.743  1031  1533 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:40.753  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 11:25:40.754  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 11:25:40.755  1031  1535 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 11:25:40.755  1031  1535 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-29 11:25:40.756  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 11:25:40.757  1031  1535 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 11:25:40.879  1031  6460 D DhcpStateMachine: DHCPV4 request on wlan0
,08-29 11:25:40.880  1031  6460 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-29 11:25:40.880  1031  6460 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 11:25:40.895  6461  6461 W dhcpcd  : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 11:25:40.895  6461  6461 W dhcpcd  : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:40.928  6461  6461 I dhcpcd  : version 5.5.6 starting
,08-29 11:25:40.930  6461  6461 E dhcpcd  : get_duid: m
,08-29 11:25:40.930  6461  6461 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 11:25:40.930  6461  6461 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 11:25:40.999  6461  6461 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 11:25:40.999  6461  6461 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 11:25:40.999  6461  6461 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-29 11:25:41.001  6461  6461 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 11:25:41.002  6461  6461 D dhcpcd  : wlan0: sending REQUEST (xid 0xa4104fcb), next in 3.36 seconds
08-29 11:25:41.029  6461  6461 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-29 11:25:41.037  6461  6461 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 11:25:41.037  6461  6461 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 11:25:41.038  6461  6461 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 11:25:41.038  6461  6461 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 11:25:41.038  6461  6461 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 11:25:41.039  6461  6461 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 11:25:41.039  6461  6461 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 11:25:41.039  6461  6461 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 11:25:41.041  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:41.042  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:41.042  1031  1535 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:41.043  1031  1535 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 11:25:41.044  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:41.044  1031  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:41.045  1031  1541 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-29 11:25:41.491  1031  6460 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-29 11:25:41.494  1031  6460 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 11:25:41.494  1031  6460 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 11:25:41.495  1031  6460 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 11:25:41.495  1031  6460 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 11:25:41.495  1031  6460 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 11:25:41.495  1031  6460 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-29 11:25:41.496  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 11:25:41.497  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 11:25:41.497  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 11:25:41.497  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 11:25:41.498  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.498  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.498  1031  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 11:25:41.498  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 11:25:41.498  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 11:25:41.499  1031  1535 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 11:25:41.499  1031  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:25:41.499  1031  6460 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 11:25:41.500  1031  6460 D DhcpStateMachine: RunningState
08-29 11:25:41.515  1031  1535 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:25:41.516  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 11:25:41.517  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-29 11:25:41.521  1031  1541 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-29 11:25:41.521  1031  1535 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 11:25:41.522  1031  1541 D ConnectivityService: ignoring duplicate network state non-change
,08-29 11:25:41.543  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.543  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.543  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-29 11:25:41.553  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:41.553  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:41.557  1031  1541 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 11:25:41.558  1031  1541 D ConnectivityService: Adding iface wlan0 to network 100
08-29 11:25:41.571  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.571  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.571  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-29 11:25:41.598  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:41.600  1938  1938 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-29 11:25:41.603  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 11:25:41.605  1031  1535 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 11:25:41.619  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.619  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.619  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 11:25:41.628  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-29 11:25:41.638  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:41.638  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:41.646  1031  1541 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 11:25:41.649  1031  1541 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-29 11:25:41.651  1031  1541 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-29 11:25:41.652  1031  1541 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-29 11:25:41.653  1031  1541 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 11:25:41.653  1031  1541 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-29 11:25:41.653  1031  1541 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-29 11:25:41.661  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:25:41.670  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:41.673  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.673  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.673  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-29 11:25:41.676  1031  1541 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 11:25:41.676  1031  1541 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 11:25:41.676  1031  1541 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-29 11:25:41.676  1031  1541 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-29 11:25:41.676  1031  1541 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:25:41.676  1031  1541 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:25:41.676  1031  1541 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 11:25:41.676  1031  1541 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:41.677  1031  1541 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 11:25:41.677  1031  1541 D ConnectivityService: currentScore = 0, newScore = 20
08-29 11:25:41.677  1031  1541 D ConnectivityService:    accepting network in place of null
08-29 11:25:41.689  1031  6458 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-13ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.689  1031  6458 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 11:25:41.689  1031  6458 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:25:41.694  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:41.698  1031  1541 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:41.698  1031  1535 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:41.698  1031  1535 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:25:41.698  1031  6458 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 11:25:41.699  1031  1541 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-29 11:25:41.704  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:41.704  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-29 11:25:41.706  1031  1541 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 11:25:41.706  1031  1541 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 11:25:41.706  1031  1541 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 11:25:41.707   309  6509 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 11:25:41.708  1598  1598 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 11:25:41.709  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:41.711  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 11:25:41.711  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 11:25:41.711  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 11:25:41.711  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 11:25:41.711  1031  1031 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-29 11:25:41.712  1031  1541 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:41.713  1031  1541 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 11:25:41.714   309  6510 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 11:25:41.714   309  6510 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-29 11:25:41.715   309  6510 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
08-29 11:25:41.715  1031  1541 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 11:25:41.717  1031  1091 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-29 11:25:41.731  1031  1541 D ConnectivityService: validation of new default Network = false
08-29 11:25:41.731  1031  1541 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
,08-29 11:25:41.731  1031  1541 D DSQN    : enableDataServiceNotify 
08-29 11:25:41.731  1031  1541 D DSQN    : start dsqn bin
08-29 11:25:41.733   309  6517 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 11:25:41.734   309  6517 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-29 11:25:41.738  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:41.738  1598  1598 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 11:25:41.738  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:25:41.748  1031  1541 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-29 11:25:41.748  1031  1541 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:41.748  1031  1541 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:25:41.745  6520  6520 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:41.745  6520  6520 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:41.749  1031  1541 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:25:41.750  1031  1532 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 11:25:41.755  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:41.755  1598  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 11:25:41.762  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:41.764  6520  6520 E DSQN    : DSQN ssw
08-29 11:25:41.773  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:25:41.773  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:41.776  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 11:25:41.778  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:41.778  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:25:41.779  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:41.782  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:41.789  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:41.794  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:41.800  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:25:41.801  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:41.802  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 11:25:41.806  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:41.810  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 11:25:41.813  1031  1955 D WifiServiceImplEx: setWifiEnabled: false pid=5966, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 11:25:41.813  1031  1955 D WifiService: setWifiEnabled: false pid=5966, uid=10118
08-29 11:25:41.813  1031  1955 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 11:25:41.814  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:25:41.817  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 11:25:41.821  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:41.827  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:25:41.828  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:25:41.828  6256  6256 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 11:25:41.829  6256  6256 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 11:25:41.830  6256  6256 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 11:25:41.833  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:25:41.833  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:25:41.833  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-29 11:25:41.834  1031  1535 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 11:25:41.834  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 11:25:41.835  1031  1535 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 11:25:41.836  1031  1535 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 11:25:41.837  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 11:25:41.837  1031  1535 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 11:25:41.837  1031  1535 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:25:41.838  1031  1535 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 11:25:41.838  1031  1535 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 11:25:41.838  1031  1535 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 11:25:41.839  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:25:41.842  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 11:25:41.843  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:41.847  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:41.851  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:41.852  1031  1535 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 11:25:41.853  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 11:25:41.853  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 11:25:41.853  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.853  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.853  1031  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 11:25:41.853  1031  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:25:41.853  1031  1535 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:25:41.854  1031  6460 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.854   309   890 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:25:41.859  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:41.860  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:41.861  6256  6256 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 11:25:41.862  6256  6256 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 11:25:41.862  6256  6256 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-29 11:25:41.880  1031  1541 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 11:25:41.880  1031  1541 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-29 11:25:41.884  1938  1938 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 11:25:41.884  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-29 11:25:41.884  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.884  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.884  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:25:41.884  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-29 11:25:41.885  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:41.885  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:41.887  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:41.888  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.888  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.888  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:25:41.892  1031  1535 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:41.892  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:41.892  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:41.892  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:41.893  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.893  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:25:41.893  1031  1533 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3a905cba
08-29 11:25:41.893  1031  1533 D LGWifiP2pService: P2pDisablingState
08-29 11:25:41.894  1031  1533 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.894  1031  1533 D LGWifiP2pService: p2p socket connection lost
08-29 11:25:41.894  1031  1533 D LGWifiP2pService: P2pDisabledState
08-29 11:25:41.894  1031  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:41.894  1031  1535 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 11:25:41.895  1031  1535 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 11:25:41.895  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-29 11:25:41.895  6402  6402 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 11:25:41.896  1031  1533 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.896  1031  1533 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.896  1031  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 11:25:41.896  1031  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:25:41.897  1031  1535 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:25:41.897  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 11:25:41.898  1031  1552 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.898  1031  1031 D RttService: SCAN_AVAILABLE : 1
08-29 11:25:41.899  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:41.900  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 11:25:41.901  1938  1938 D WfdsService: WifiP2pState is changed : false
08-29 11:25:41.901  1031  1553 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:41.901  1938  2334 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 11:25:41.901  1938  2334 D WfdsService: Set the WFDS Monitor: false
08-29 11:25:41.902  1938  2334 D WfdsMonitor: WFDS Monitor is stopped
08-29 11:25:41.902  1938  2334 D WfdsService: STATE : WfdsDisabledState - enter
08-29 11:25:41.902  1938  6427 D CtrlSupplicant: Received on exit socket, terminate
08-29 11:25:41.902  1938  6427 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 11:25:41.902  1938  6427 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 11:25:41.902  1938  6427 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 11:25:41.903  1938  2337 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,08-29 11:25:41.903  1938  2334 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 11:25:41.904  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:25:41.913  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 11:25:41.913  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:25:41.913  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:41.917  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:41.921  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:41.926   309   890 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:25:41.927  1031  1541 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 11:25:41.927  1031  1541 D DSQN    : disableDataServiceNotify
08-29 11:25:41.927  1031  1541 D DSQN    : stop dsqn bin
08-29 11:25:41.928  1031  1535 D WifiNative-p2p0: doBoolean: TERMINATE
,08-29 11:25:41.930  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-29 11:25:41.930  1031  1535 D WifiNative-p2p0: TERMINATE: returned true
08-29 11:25:41.930  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.930  1031  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:25:41.930  1031  1535 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:25:41.930  1031  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:25:41.930  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.930  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:25:41.934  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 11:25:41.934  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:41.934  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 11:25:41.935  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:41.935  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:41.935  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:41.935  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:41.935  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:41.935  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:41.935  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:41.935  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:41.935  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:41.935  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:25:41.935  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 11:25:41.935  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:41.935  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:41.935  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:41.936  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 11:25:41.936  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:41.936  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:41.936  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:41.936  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:41.936  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:41.936  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:41.936  5966 , 5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:41.936  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:41.936  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:41.936  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:25:41.936  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:41.936  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:41.936  6256  6256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:25:41.937  1031  1541 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 11:25:41.937  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:41.937  1031  1541 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:41.937  1031  1541 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:25:41.937  1031  1541 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:25:41.938  1031  1541 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 11:25:41.938  1598  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 11:25:41.938  1031  1541 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 11:25:41.938  1031  1541 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 11:25:41.938  1031  1541 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 11:25:41.938  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:41.939  1031  1541 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:41.939  1031  1541 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 11:25:41.939  1031  1541 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:41.940  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 11:25:41.940  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
,08-29 11:25:41.940  1031  1541 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:41.940  1031  1541 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:41.940  1031  1532 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 11:25:41.940  1031  1532 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 11:25:41.940  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 11:25:41.940  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 11:25:41.940  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 11:25:41.940  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 11:25:41.940  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 11:25:41.940  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 11:25:41.941  1031  1535 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:41.941  1031  1535 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:25:41.942  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:41.942  1031  1541 D NetworkManagementService: Removing idletimer
08-29 11:25:41.942  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 11:25:41.942  1031  1541 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:41.942  1031  1541 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 11:25:41.944  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:41.947  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 11:25:41.947  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:25:41.947  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:41.950  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:41.956  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:41.964  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:25:41.965  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:25:41.967  6256  6256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:25:41.969  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:41.973  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 11:25:41.973  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-29 11:25:41.973  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:41.980  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:41.987  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-29 11:25:41.987  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 11:25:41.988  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:41.989  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:41.994  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:41.994  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:25:41.995  6256  6256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 11:25:41.998  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 11:25:41.998  6402  6402 I wpa_supplicant: monitor socket send errors count : 1
08-29 11:25:41.998  6402  6402 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1938-4\x00 that cannot receive messages
08-29 11:25:41.999  1031  6424 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 11:25:41.999  1031  6424 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 11:25:42.005  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:42.008  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:42.015  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:42.028  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 11:25:42.029  6402  6402 W wpa_supplicant: USIM:  scard_deinit function
08-29 11:25:42.030  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 11:25:42.030  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 11:25:42.030  1031  6424 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 11:25:42.030  1031  6424 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 11:25:42.031  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:25:42.031  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:25:42.031  1031  1535 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122331
08-29 11:25:42.032  1031  1535 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122332
08-29 11:25:42.032  1031  1093 D Tethering: InitialState.processMessage what=4
08-29 11:25:42.032  1031  1535 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=122332  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 11:25:42.033  1031  1535 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=122333  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 11:25:42.033  1031  1093 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 11:25:42.034  1031  1535 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:42.035  1031  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:42.036  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:42.037  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:25:42.037  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:25:42.037  6210  6210 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:25:42.038  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 11:25:42.040  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:42.040  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:25:42.040  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:25:42.045  6210  6210 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:25:42.045  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 11:25:42.045  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:25:42.045  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:25:42.045  6210  6210 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:25:42.045  6210  6210 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 11:25:42.051  6296  6532 W FormManager: Network not available. Please check & try again.
08-29 11:25:42.053  6296  6533 V FormManager: Network unavailable.
,08-29 11:25:42.055  6296  6533 V FormManager: Network unavailable.
,08-29 11:25:42.060  1031  6460 D DhcpStateMachine: StoppedState
08-29 11:25:42.060  1031  6460 D DhcpStateMachine: StoppedState{ when=-164ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:42.061  1031  1535 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 11:25:42.061  1031  1535 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 11:25:42.079  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 11:25:42.079  1031  6424 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 11:25:42.079  1031  6424 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 11:25:42.079  1031  6424 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 11:25:42.080  1031  1535 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 36 0
,08-29 11:25:42.183  1938  1938 D WfdsService: Supplicant Connection state is changed : false
,08-29 11:25:42.184  1938  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 11:25:42.184  1938  2334 D WfdsService: Set the WFDS Monitor: false
08-29 11:25:42.184  1938  2334 D WfdsMonitor: WFDS Monitor is stopped
08-29 11:25:42.188  1031  1535 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 11:25:42.189  1031  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:25:42.189  1031  1535 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:25:42.189  1031  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:25:42.191  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:25:42.193  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:42.193  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:25:42.194  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 11:25:42.200  2501  2501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:42.200  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:25:42.200  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:42.200  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:42.200  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:42.200  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:42.200  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:42.200  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:42.200  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:42.200  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:42.201  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-29 11:25:42.201  1031  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 11:25:42.202  1031  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 11:25:42.203  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:42.203  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:42.203  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:42.203  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:42.203  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:42.203  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:42.203  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:42.203  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:42.203  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:42.205  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:25:42.214  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:25:42.221  4234  6535 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 11:25:42.223  6192  6192 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 11:25:42.223  6192  6192 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:25:42.223  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:42.226  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:42.227  4234  6536 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:25:42.227  4234  6536 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:25:42.234  6296  6538 W FormManager: Network not available. Please check & try again.
,08-29 11:25:42.235  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 11:25:42.242  6296  6539 V FormManager: Network unavailable.
08-29 11:25:42.244  6296  6539 V FormManager: Network unavailable.
,08-29 11:25:42.859  6140  6369 D UEI.SmartControl: Internal timer expired: 2
,08-29 11:25:42.859  6140  6369 D UEI.SmartControl: unbind internal service
,08-29 11:25:43.129  6140  6363 D serial_port: close(fd = 24)
,08-29 11:25:43.137  6140  6363 I UEI.SmartControl: Serial port is closed.
,08-29 11:25:43.673  1031  1535 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-711038855] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-29 11:25:43.675  1031  1535 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-711038853] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-29 11:25:44.716  1031  1541 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:44.729  1031  1093 D Tethering: MasterInitialState.processMessage what=3
08-29 11:25:44.739  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:44.744  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:44.746  1031  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:44.751  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 11:25:44.755  3662  3696 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 11:25:44.768  5314  5314 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 11:25:44.836  1031  2008 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:44.836  1031  2008 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 11:25:44.841  2222  2222 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:44.857  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:25:44.858  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:25:44.858  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,08-29 11:25:44.860  1031  1093 D BluetoothManagerService: Message: 1
08-29 11:25:44.860  1031  1093 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-29 11:25:44.894  1031  1093 D BluetoothManagerService: Message: 20
08-29 11:25:44.894  1031  1093 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@176410dd:true
08-29 11:25:44.895  6321  6321 D BluetoothAdapterState: make
08-29 11:25:44.909  6321  6321 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 11:25:44.909  6321  6321 I bluedroid-qcom: init
,08-29 11:25:44.910  6321  6556 I BluetoothAdapterState: Entering OffState
08-29 11:25:44.922  6321  6321 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 11:25:44.923  6321  6321 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 11:25:44.923  6321  6321 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 11:25:44.923  6321  6321 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 11:25:44.923  6321  6321 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 11:25:44.915  6567  6567 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:44.915  6567  6567 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:44.929  6321  6321 I bluedroid-qcom: get_profile_interface socket
08-29 11:25:44.929  6321  6321 I bluedroid-qcom: get_profile_interface map_client
08-29 11:25:44.932  6567  6567 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 11:25:44.932  6567  6567 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 11:25:44.932  6567  6567 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 11:25:44.935  6321  6568 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-29 11:25:44.939  6321  6568 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 11:25:44.939  6567  6567 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 11:25:44.939  1031  1541 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:44.940  1031  1955 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6569 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-29 11:25:44.943  1031  1541 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:44.944  1031  1093 D Tethering: MasterInitialState.processMessage what=3
08-29 11:25:44.944  6321  6568 D BluetoothAdapterProperties: Name is: G3
08-29 11:25:44.947  6567  6567 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 11:25:44.947  6567  6567 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 11:25:44.948  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 11:25:44.948  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 11:25:44.950  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:44.951  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:44.956  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:44.956  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:44.956  1031  1093 D Tethering: MasterInitialState.processMessage what=3
08-29 11:25:44.960   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 20.008ms
08-29 11:25:44.961  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 11:25:44.961  1031  1093 D BluetoothManagerService: Message: 40
08-29 11:25:44.961  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 11:25:44.961  5314  5314 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 11:25:44.962  6321  6337 I bluedroid-qcom: config_hci_snoop_log
08-29 11:25:44.963  1031  1093 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 11:25:44.963  1031  1093 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 11:25:44.967  6321  6556 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 11:25:44.967  6321  6556 D BluetoothAdapterProperties: Setting state to 11
,08-29 11:25:44.967  6321  6556 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 11:25:44.968  6321  6556 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 11:25:44.971  6321  6556 D BluetoothBondStateMachine: make
08-29 11:25:44.971  1031  1093 D BluetoothManagerService: Message: 60
08-29 11:25:44.971  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 11:25:44.971  1031  1093 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 11:25:44.973  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:44.977  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:25:44.979  6210  6210 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 11:25:44.979  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:44.979   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 430us total 19.130ms
08-29 11:25:44.980  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:44.981  6321  6587 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 11:25:44.982  6321  6556 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:44.986  6321  6556 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 11:25:44.986  6321  6556 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:44.986  6321  6556 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,08-29 11:25:44.987  6321  6556 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 11:25:44.990  6321  6321 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:25:44.990  6321  6321 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:44.991  6321  6321 V BluetoothPbapReceiver: ***********state = 11
08-29 11:25:44.992  1031  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:44.992  5314  5314 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 11:25:44.993  6321  6556 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:44.994  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:25:44.998   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 18.450ms
,08-29 11:25:45.005  6321  6321 D HeadsetService: Received start request. Starting profile...
08-29 11:25:45.005  6321  6321 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 11:25:45.006  6321  6321 D LGBluetoothHfpAdapter: Version 1.6
08-29 11:25:45.006  6321  6556 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:45.008  6321  6321 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 11:25:45.008  6321  6321 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 11:25:45.009  6321  6321 D HeadsetStateMachine: make
08-29 11:25:45.011  6321  6556 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:45.012  1031  1088 E GpsLocationProvider: No APN found to select.
,08-29 11:25:45.016  6321  6556 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:45.016  6210  6210 D BluetoothPermissionRequest: onReceive
08-29 11:25:45.022  6321  6556 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:45.023  6210  6210 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:25:45.025  1031  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:45.028  1031  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:45.028  1031  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:45.028  1031  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:45.028  6321  6556 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:45.031  6321  6321 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:25:45.031  6321  6321 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:25:45.032  6321  6556 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:45.034  6321  6321 D HeadsetStateMachine: max_hf_connections = 1
08-29 11:25:45.034  6321  6321 I bluedroid-qcom: get_profile_interface handsfree
08-29 11:25:45.035  6321  6321 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 11:25:45.036   313   313 V AudioPolicyService: registerClient() client 0xb14b7560, uid 1002
08-29 11:25:45.036   313  1382 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 11:25:45.036   313  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 11:25:45.036   313  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:25:45.036  6321  6321 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 11:25:45.036   313  1381 V AudioFlinger: registerClient() client 0xb1188148, pid 6321
08-29 11:25:45.036  6569  6569 I AppUp4:AppBoxCP: onCreate
08-29 11:25:45.037   313  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:45.037   313  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:25:45.037   313  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:45.037   313  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-29 11:25:45.038  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:45.038  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:25:45.038  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:45.038  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:25:45.038  1031  1919 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:45.038  1031  1919 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:25:45.038  1031  1919 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:45.038  1031  1919 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:25:45.038  2127  4460 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:45.038  2127  4460 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:25:45.038  2127  4460 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:45.038  2127  4460 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:25:45.038  1598  1615 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:45.038  1598  1615 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:25:45.038  1598  1615 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:45.038  1598  1615 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:25:45.038  6321  6588 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:45.038  6321  6588 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 11:25:45.038  6321  6588 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:45.038  6321  6588 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 11:25:45.038  6569  6569 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-29 11:25:45.039  6321  6321 V ToneGenerator: Create Track: 0xb4928a80
08-29 11:25:45.039  6321  6321 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 11:25:45.039  6321  6321 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 11:25:45.039   313   313 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 11:25:45.039   313   313 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 11:25:45.039   313   313 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-29 11:25:45.039   313   313 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:25:45.039   313  1382 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 11:25:45.039   313  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 11:25:45.039   313  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 11:25:45.039   313  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 11:25:45.039   313  1381 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:25:45.039  6321  6321 V AudioSystem: getLatency() output 2, latency 50
08-29 11:25:45.039  6321  6321 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 11:25:45.039  6321  6321 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 11:25:45.040   313  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 11:25:45.040   313  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 11:25:45.040   313  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 11:25:45.040   313  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 11:25:45.040   313  1383 V AudioFlinger: createTrack() lSessionId: 22
08-29 11:25:45.040  6321  6321 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 11:25:45.040   313   313 V AudioFlinger: acquiring 22 from 6321, for 6321
08-29 11:25:45.040   313   313 V AudioFlinger:  added new entry for 22
08-29 11:25:45.040  6321  6321 V ToneGenerator: ToneGenerator INIT OK, time: 125353
08-29 11:25:45.041  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:45.041  6321  6593 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 11:25:45.041  6321  6593 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:25:45.042  6321  6593 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:25:45.042  6321  6593 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 11:25:45.042   313  1382 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6321
08-29 11:25:45.042   313  1382 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 11:25:45.042   313  1382 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 11:25:45.042   313  1382 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 11:25:45.042   313  1382 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 11:25:45.042   313  1382 V voice   : voice_set_parameters: exit with code(0)
08-29 11:25:45.042   313  1382 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 11:25:45.042   313  1382 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 11:25:45.042   313  1382 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 11:25:45.042   313  1382 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 11:25:45.042   313  1382 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 11:25:45.042   313  1382 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 11:25:45.043  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:45.043  6321  6593 V ToneGenerator: ToneGenerator destructor
08-29 11:25:45.043  6321  6593 V ToneGenerator: stopTone
08-29 11:25:45.043  6321  6593 V ToneGenerator: Delete Track: 0xb4928a80
08-29 11:25:45.043  3157  4792 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:45.043  3157  4792 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:25:45.043  3157  4792 V AudioSystem: ioConfigChanged(), event 0, ioHandle 4
08-29 11:25:45.043  3157  4792 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:25:45.044  6321  6593 V AudioTrack: ~AudioTrack, releasing session id from 6321 on behalf of 6321
08-29 11:25:45.044   313  1381 V AudioFlinger: releasing 22 from 6321 for 6321
08-29 11:25:45.044   313  1381 V AudioFlinger:  decremented refcount to 0
08-29 11:25:45.044   313  1381 V AudioFlinger: purging stale effects
08-29 11:25:45.044  6321  6321 D A2dpService: Received start request. Starting profile...
08-29 11:25:45.044   313  1381 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 11:25:45.044   313  1381 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 11:25:45.044  6569  6569 I AppUp4:DB:  setFingerPrint start
08-29 11:25:45.044   313  1255 V AudioPolicyService: AudioCommandThread() waking up
08-29 11:25:45.044   313  1255 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 11:25:45.044   313  1255 V AudioPolicyManager: releaseOutput() 2
08-29 11:25:45.044   313  1255 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 11:25:45.045   313  1381 V AudioFlinger: PlaybackThread::Track destructor
08-29 11:25:45.045   313  1381 V AudioFlinger: removeClient_l() pid 6321, calling pid 313
08-29 11:25:45.045  6569  6569 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 11:25:45.045  6321  6321 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 11:25:45.046  6321  6321 V Avrcp   : make
08-29 11:25:45.046  6321  6321 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 11:25:45.046  6321  6321 I bluedroid-qcom: get_profile_interface avrcp
08-29 11:25:45.047  6321  6556 V LGMDMManager: Create singleton instance
08-29 11:25:45.048  1031  1779 W Process : Unable to open /proc/6595/status
08-29 11:25:45.049  6321  6556 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 11:25:45.051  6569  6569 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 11:25:45.051  6569  6569 I AppUp4:DB:  SDK version = 21
08-29 11:25:45.051  6569  6569 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-29 11:25:45.054  6569  6569 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-29 11:25:45.054  6321  6321 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 11:25:45.055  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 11:25:45.055  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:45.056  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 11:25:45.056  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 11:25:45.058  6321  6321 E AudioManager: No RCC entry present to update
08-29 11:25:45.058  6321  6321 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 11:25:45.060  6569  6569 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 11:25:45.061  6321  6321 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-29 11:25:45.062  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 11:25:45.062  6321  6321 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 11:25:45.065  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 11:25:45.088  6569  6569 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:25:45.088  6569  6569 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:25:45.092  6569  6569 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29c2b1bc
08-29 11:25:45.092  6569  6569 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 11:25:45.092  6569  6569 D AppUp4:CustFacade: isPhone : true
08-29 11:25:45.094  6569  6569 D AppUp4:CustModeStarterReceiver: begin check event
08-29 11:25:45.094  6569  6569 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-29 11:25:45.094  6569  6569 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-29 11:25:45.112  6569  6597 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-29 11:25:45.112  6569  6597 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
,08-29 11:25:45.112  6569  6597 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-29 11:25:45.116  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:45.117  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:25:45.120  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:25:45.127  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 11:25:45.144  4234  6600 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 11:25:45.149  1031  1777 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:25:45.149  1031  1777 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:25:45.151  4234  6601 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:45.151  4234  6601 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:25:45.177  1031  1956 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6602 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 11:25:45.246  1031  1955 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 11:25:45.246  6602  6602 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:25:45.247  6602  6602 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 11:25:45.248  6602  6602 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 11:25:45.249  6602  6602 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 11:25:45.253  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 11:25:45.257  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 11:25:45.258  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 11:25:45.258  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 11:25:45.258  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 11:25:45.258  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 11:25:45.258  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 11:25:45.258  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 11:25:45.258  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 11:25:45.258  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-29 11:25:45.258  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 11:25:45.259  6321  6321 I BluetoothA2dpServiceJni: classInitNative
08-29 11:25:45.259  6321  6321 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:25:45.259  6321  6321 D A2dpStateMachine: make
08-29 11:25:45.260  6321  6321 I bluedroid-qcom: get_profile_interface a2dp
08-29 11:25:45.261  6321  6620 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 11:25:45.263  6321  6321 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:25:45.263  6321  6321 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 11:25:45.264  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:45.264  6321  6619 D A2dpStateMachine: Enter Disconnected: -2
08-29 11:25:45.265  6321  6321 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 11:25:45.266  6321  6321 D HidService: Received start request. Starting profile...
08-29 11:25:45.266  6321  6321 I bluedroid-qcom: get_profile_interface hidhost
08-29 11:25:45.266  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:45.267  6321  6321 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 11:25:45.268  6321  6321 D HealthService: Received start request. Starting profile...
08-29 11:25:45.270  6321  6321 I bluedroid-qcom: get_profile_interface health
08-29 11:25:45.270  6321  6321 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 11:25:45.271  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:45.271  6321  6321 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 11:25:45.273  6321  6321 D PanService: Received start request. Starting profile...
08-29 11:25:45.273  6321  6321 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 11:25:45.273  6321  6321 I bluedroid-qcom: get_profile_interface pan
,08-29 11:25:45.277  6321  6321 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 11:25:45.277  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:45.278  6321  6321 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 11:25:45.282  6321  6321 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 11:25:45.283  6321  6321 D BtGatt.GattService: Received start request. Starting profile...
08-29 11:25:45.283  6321  6321 D BtGatt.GattService: start()
08-29 11:25:45.283  6321  6321 I bluedroid-qcom: get_profile_interface gatt
08-29 11:25:45.283  6321  6321 D BtGatt.AdvertiseManager: advertise manager created
08-29 11:25:45.289  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:45.289  6321  6321 D HeadsetStateMachine: Proxy object connected
08-29 11:25:45.290  6321  6321 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 11:25:45.290  6321  6321 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-29 11:25:45.292  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:45.292  6321  6321 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 11:25:45.293  6321  6321 V BluetoothMapService: BluetoothMapBinder()
08-29 11:25:45.293  6321  6321 D BluetoothMapService: Received start request. Starting profile...
08-29 11:25:45.294  6321  6321 D BluetoothMapService: start()
08-29 11:25:45.296  6321  6321 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 11:25:45.296  6321  6321 D BluetoothMapEmailAppObserver: createReceiver()
08-29 11:25:45.298  6321  6321 D BluetoothMapEmailAppObserver: initObservers()
08-29 11:25:45.298  6321  6321 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 11:25:45.303  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:45.304  6321  6593 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 11:25:45.305  6321  6593 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 11:25:45.305  6321  6593 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 11:25:45.306  6321  6321 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 11:25:45.310  6321  6321 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:25:45.313  6321  6321 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:25:45.315  6321  6321 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:25:45.317  6321  6321 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:45.320  6321  6321 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:25:45.320  6321  6321 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 11:25:45.323  6321  6321 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 11:25:45.323  6321  6321 V BluetoothMapService: Handler(): got msg=1
08-29 11:25:45.324  6321  6321 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:25:45.324  6321  6321 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:25:45.324  6321  6321 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:25:45.325  6321  6321 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:45.325  6321  6321 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 11:25:45.325  6321  6556 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 11:25:45.325  6321  6556 I bluedroid-qcom: enable
08-29 11:25:45.326  6321  6556 I bt_hci_bdroid: init
08-29 11:25:45.326  6321  6627 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 11:25:45.327  6321  6627 I bt-btu  : btu_task pending for preload complete event
08-29 11:25:45.329  6321  6556 I bt_vendor: bt-vendor : init
08-29 11:25:45.329  6321  6556 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 11:25:45.329  6321  6556 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 11:25:45.329  6321  6556 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 11:25:45.329  6321  6556 D bt_userial_mct: userial_init
08-29 11:25:45.330  6321  6556 D bt_hci_bdroid: set_power 1
,08-29 11:25:45.330  6321  6556 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 11:25:45.330  6321  6556 I bt_vendor: Starting hciattach daemon
08-29 11:25:45.330  6321  6556 I bt_vendor: try to set true
08-29 11:25:45.325  6630  6630 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:45.325  6630  6630 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:45.347  6602  6602 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-29 11:25:45.349  6631  6631 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 11:25:45.362  6602  6602 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-29 11:25:45.395  6602  6602 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 11:25:45.419  6638  6638 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 11:25:45.432  6639  6639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 11:25:45.445  6602  6602 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 11:25:45.445  6602  6602 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:25:45.459  6641  6641 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 11:25:45.470  6643  6643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 11:25:45.482  6644  6644 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-29 11:25:45.505  6645  6645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 11:25:45.531  6649  6649 I libmdmdetect: ESOC framework not supported
,08-29 11:25:45.532  6649  6649 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 11:25:45.545  6649  6649 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-29 11:25:45.545  6649  6649 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 11:25:45.545  6649  6649 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 11:25:45.545  6649  6649 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 11:25:45.545  6649  6649 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 11:25:45.545  6649  6649 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 11:25:45.545  6649  6649 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-29 11:25:45.582  6649  6650 E QC-QMI  : qmi_client [6649] 14: failed to locate client data
,08-29 11:25:45.583   473   473 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 11:25:45.583   473   473 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-29 11:25:45.645  6654  6654 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
08-29 11:25:45.645  6602  6602 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 11:25:45.661  6655  6655 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 11:25:45.710  3157  3157 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-29 11:25:45.710  3157  3157 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:45.712  3157  3157 I LgeMiscReceiver: networkInfo.isConnected() = true
08-29 11:25:45.712  3157  3157 D PhoneState: setPdpRejectCasuse : false
,08-29 11:25:45.721  6602  6602 I HubEmail: JNI_OnLoad()
08-29 11:25:45.721  6602  6602 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 11:25:45.721  6602  6602 I HubEmail: registerNatives()
08-29 11:25:45.721  6602  6602 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 11:25:45.721  6602  6602 I HubEmail: registerNativeMethods()
08-29 11:25:45.721  6602  6602 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 11:25:45.721  6602  6602 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-29 11:25:45.732  6321  6556 I bt_vendor: bluetooth satus is on
08-29 11:25:45.732  6321  6556 D bt_hci_bdroid: preload
08-29 11:25:45.733  6321  6629 D bt_userial_mct: userial_open(port:0)
08-29 11:25:45.733  6321  6629 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 11:25:45.736  6321  6629 I bt_vendor: Done intiailizing UART
08-29 11:25:45.737  6321  6629 I bt_vendor: Done intiailizing UART
08-29 11:25:45.737  6321  6629 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 11:25:45.737  6321  6629 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 11:25:45.738  6321  6662 D bt_userial_mct: Entering userial_read_thread()
08-29 11:25:45.738  6321  6627 I bt-btu  : btu_task received preload complete event
08-29 11:25:45.738  6321  6627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 11:25:45.738  6321  6627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 11:25:45.741  6321  6627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 11:25:45.743  6321  6627 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 11:25:45.743  6321  6627 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 11:25:45.743  6321  6627 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 11:25:45.743  6321  6627 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 11:25:45.743  6321  6627 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 11:25:45.743  6321  6627 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 11:25:45.743  6321  6627 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 11:25:45.744  6321  6627 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 11:25:45.744  6321  6627 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 11:25:45.744  6321  6627 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 11:25:45.744  6321  6627 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 11:25:45.744  6321  6627 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 11:25:45.744  6321  6627 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 11:25:45.744  6321  6627 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 11:25:45.744  6321  6627 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 11:25:45.744  6321  6627 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 11:25:45.766  1031  2029 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6663 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-29 11:25:45.772  6296  6659 W FormManager: Network not available. Please check & try again.
08-29 11:25:45.776  6296  6660 V FormManager: Network unavailable.
08-29 11:25:45.776  6602  6661 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:45.779  6296  6660 V FormManager: Network unavailable.
08-29 11:25:45.788  1031  2008 I ActivityManager: Killing 5913:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-29 11:25:45.799  6321  6627 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 11:25:45.799  6321  6627 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa017c061 
,08-29 11:25:45.799  6321  6627 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa017c061 
08-29 11:25:45.814  6321  6568 E bt-btif : Calling BTA_HhEnable
08-29 11:25:45.814  6321  6568 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 11:25:45.814  6321  6627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 11:25:45.814  6321  6627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 11:25:45.814  6321  6627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 11:25:45.815  6321  6568 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 11:25:45.815  6321  6627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 11:25:45.815  6321  6627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-29 11:25:45.820  1031  1777 W libprocessgroup: failed to open /acct/uid_10061/pid_5913/cgroup.procs: No such file or directory
08-29 11:25:45.826  6321  6627 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:25:45.826  6321  6627 W bt-smp  : Plain text(LSB ~ MSB) = 54 82 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-29 11:25:45.826  6321  6627 W bt-smp  : Encrypted text(LSB ~ MSB) = 8c 47 a6 36 28 a5 ec 35 93 3e 18 6b 90 44 22 71 
08-29 11:25:45.826  6321  6627 W bt-btm  : Stopping oneshot timer
08-29 11:25:45.826  6321  6568 D BluetoothAdapterProperties: Name is: G3
08-29 11:25:45.827  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 11:25:45.828  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 11:25:45.829  6321  6568 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:25:45.829  6321  6568 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:25:45.829  6321  6568 D bt_hci_bdroid: postload
08-29 11:25:45.829  6321  6629 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:25:45.830  6321  6627 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 11:25:45.830  6321  6568 D bte_conf: Device ID record 1 : primary
08-29 11:25:45.830  6321  6568 D bte_conf:   vendorId            = 00c4
08-29 11:25:45.830  6321  6568 D bte_conf:   vendorIdSource      = 0001
08-29 11:25:45.830  6321  6568 D bte_conf:   product             = 13a1
08-29 11:25:45.830  6321  6568 D bte_conf:   version             = 1000
08-29 11:25:45.830  6321  6568 D bte_conf:   clientExecutableURL = 
08-29 11:25:45.830  6321  6568 D bte_conf:   serviceDescription  = 
08-29 11:25:45.831  6321  6568 D bte_conf:   documentationURL    = 
08-29 11:25:45.831  6321  6568 D bte_conf: bte_load_did_conf no section named DID2.
08-29 11:25:45.832  6321  6629 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:25:45.836  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:45.836  6321  6629 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:25:45.836  6321  6629 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:25:45.838  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:45.839  6321  6556 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 11:25:45.839  6321  6556 D BluetoothAdapterProperties: ScanMode =  20
08-29 11:25:45.839  6321  6556 D BluetoothAdapterProperties: State =  11
08-29 11:25:45.839  6321  6556 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 11:25:45.840  6321  6556 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 11:25:45.840  6321  6556 D BluetoothAdapterProperties: Setting state to 12
08-29 11:25:45.840  6321  6556 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 11:25:45.840  6321  6629 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:25:45.841  1031  1093 D BluetoothManagerService: Message: 60
08-29 11:25:45.841  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 11:25:45.841  1031  1093 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-29 11:25:45.842  6321  6556 I BluetoothAdapterState: Entering On State
08-29 11:25:45.835  6685  6685 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:45.835  6685  6685 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:45.843  1850  2451 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:25:45.843  6321  6568 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 11:25:45.844  6321  6662 E bt_mct  : hci lib postload completed
08-29 11:25:45.844  6321  6568 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 11:25:45.847  6210  6227 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 11:25:45.850  1031  1093 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 11:25:45.853  6210  6226 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 11:25:45.854  6321  6556 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 11:25:45.854  6321  6556 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 11:25:45.854  6321  6556 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 11:25:45.855  6321  6556 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 11:25:45.856  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:25:45.859  1850  1850 D BluetoothHeadset: Proxy object connected
,08-29 11:25:45.865  1850  1850 D BluetoothHeadset: Proxy object connected
08-29 11:25:45.868  6210  6226 D BluetoothMap: onBluetoothStateChange: up=true
08-29 11:25:45.868  6210  6210 D BluetoothInputDevice: Proxy object connected
08-29 11:25:45.868  6210  6210 D HidProfile: Bluetooth service connected
08-29 11:25:45.877  6210  6227 D BluetoothPan: onBluetoothStateChange on: true
08-29 11:25:45.877  6210  6227 D BluetoothPan: onBluetoothStateChange call bindService
,08-29 11:25:45.879  6210  6210 D BluetoothMap: Proxy object connected
08-29 11:25:45.879  6210  6210 D MapProfile: Bluetooth service connected
08-29 11:25:45.879  6210  6210 D BluetoothMap: getConnectedDevices()
08-29 11:25:45.880  6321  6588 V BluetoothMapService: getConnectedDevices()
08-29 11:25:45.884  6321  6568 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:25:45.885  6321  6568 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 11:25:45.885  1031  1093 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:25:45.886  6210  6210 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:25:45.886  1850  2652 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:25:45.886  6210  6210 D PanProfile: Bluetooth service connected
08-29 11:25:45.889  1850  1850 D BluetoothHeadset: Proxy object connected
08-29 11:25:45.889  1031  1093 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 11:25:45.889  1031  1093 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-29 11:25:45.891  6321  6556 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 11:25:45.895  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:45.895  1938  2125 D LGBluetoothAPIService: Message: 1
08-29 11:25:45.895  1938  2125 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 11:25:45.900  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:25:45.905  6321  6321 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:45.905  6321  6321 D BluetoothMapService: STATE_ON
08-29 11:25:45.905  6321  6321 V BluetoothMapService: Handler(): got msg=1
,08-29 11:25:45.909  6321  6321 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 11:25:45.912  1938  2125 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-29 11:25:45.912  5966  5966 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 11:25:45.913  6321  6693 D BluetoothMapMasInstance: MAS initSocket()
08-29 11:25:45.914  6321  6693 D BluetoothMapMasInstance:   masId = 00
08-29 11:25:45.914  6321  6693 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 11:25:45.914  6321  6693 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 11:25:45.914  6321  6693 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 11:25:45.916  6210  6210 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 11:25:45.916  6692  6692 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 11:25:45.918  1031  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:25:45.921  1031  1093 D BluetoothManagerService: Message: 30
08-29 11:25:45.923  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:45.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:45.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:45.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:45.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:45.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:45.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:45.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:45.924  6321  6693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:45.925  6210  6210 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-29 11:25:45.927  1031  1093 D BluetoothManagerService: Message: 30
08-29 11:25:45.928  6321  6693 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 11:25:45.928  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:45.929  6321  6693 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 11:25:45.929  6321  6693 D BluetoothMapMasInstance: Accepting socket connection...
08-29 11:25:45.929  6321  6568 D BluetoothAdapterProperties: Scan Mode:21
08-29 11:25:45.929  6321  6568 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 11:25:45.930  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:45.930  6321  6321 V BluetoothPbapService: Pbap Service onCreate
08-29 11:25:45.930  6321  6321 V BluetoothPbapService: Starting PBAP service
08-29 11:25:45.931  6321  6321 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 11:25:45.932  6321  6321 V BluetoothPbapService: Pbap Service onBind
,08-29 11:25:45.932  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:45.932  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:45.932  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:45.932  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:45.932  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:45.932  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:45.932  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:45.932  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:45.933  6321  6321 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:45.933  6321  6321 V BluetoothPbapService: state: 12
08-29 11:25:45.935  6321  6321 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 11:25:45.935  6321  6321 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 11:25:45.936  6321  6321 V BluetoothPbapService: Handler(): got msg=1
08-29 11:25:45.937  6321  6321 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 11:25:45.937  1938  1938 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 11:25:45.937  1938  2125 D LGBluetoothAPIService: Message: 100
08-29 11:25:45.937  1938  2125 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 11:25:45.938  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:45.938  6210  6210 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 11:25:45.939  6321  6695 V BluetoothPbapService: Pbap Service initSocket
08-29 11:25:45.939  1031  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:45.940  6210  6210 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 11:25:45.940  6321  6695 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:45.942  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:45.943  6210  6210 D BluetoothA2dp: Proxy object connected
08-29 11:25:45.943  6210  6210 D A2dpProfile: Bluetooth service connected
,08-29 11:25:45.944  6321  6321 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:25:45.944  6321  6321 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:45.944  6321  6321 V BluetoothPbapReceiver: ***********state = 12
08-29 11:25:45.944  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:45.946  6321  6695 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 11:25:45.946  6321  6695 V BluetoothPbapService: Succeed to create listening socket 
08-29 11:25:45.946  6321  6695 V BluetoothPbapService: Accepting socket connection...
08-29 11:25:45.947  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:25:45.947  2222  2222 D c       : Getting all permits...
08-29 11:25:45.947  2222  2222 D a       : Opening database...
08-29 11:25:45.948  6210  6210 D BluetoothHeadset: Proxy object connected
08-29 11:25:45.948  6210  6210 D HeadsetProfile: Bluetooth service connected
08-29 11:25:45.950  2222  2222 D a       : Opening database auth.proximity.permit_store...
08-29 11:25:45.950  6210  6210 D BluetoothPbap: Proxy object connected
08-29 11:25:45.951  2222  2222 D a       : Closing database...
08-29 11:25:45.951  6210  6210 D PbapServerProfile: Bluetooth service connected
08-29 11:25:45.956  6210  6210 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:25:45.962  6210  6210 D BluetoothPermissionRequest: onReceive
08-29 11:25:45.963  6210  6210 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 11:25:45.964  6210  6210 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:25:45.966  6663  6663 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:25:45.967  6663  6663 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:25:45.967  6321  6321 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-29 11:25:45.968  6321  6321 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 11:25:45.969  6663  6663 D PhoneMonitor: Register our PhoneStateListener
08-29 11:25:45.973  6321  6321 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-29 11:25:45.978  6663  6663 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 11:25:45.980  6663  6663 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 11:25:45.987  6663  6663 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-29 11:25:45.988  6663  6663 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-29 11:25:45.988  6663  6663 D TelephonyAutoProfiling: [parse] Load xml
08-29 11:25:45.990  6663  6663 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-29 11:25:45.990  6663  6663 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-29 11:25:45.990  6663  6663 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-29 11:25:45.990  6321  6321 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 11:25:45.991  6321  6321 V BtOppService: onCreate
08-29 11:25:45.993  6321  6321 V BluetoothOppNotification: send message
08-29 11:25:46.001  6321  6702 V BtOppService: Deleted complete outbound shares, number =  0
08-29 11:25:46.001  1031  2047 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6703 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 11:25:46.003  6321  6702 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 11:25:46.004  6321  6702 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 11:25:46.005  1031  2047 I ,ActivityManager: Killing 6036:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-29 11:25:46.005  6321  6702 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16d0f076 on behalf of 
08-29 11:25:46.006  6663  6663 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-29 11:25:46.007  6321  6321 V BtOppService: Starting RfcommListener
08-29 11:25:46.009  6321  6321 D BluetoothOppPreference: Dumping Names:  
08-29 11:25:46.009  6321  6321 D BluetoothOppPreference: {}
08-29 11:25:46.009  6321  6321 D BluetoothOppPreference: Dumping Channels:  
,08-29 11:25:46.009  6321  6321 D BluetoothOppPreference: {}
08-29 11:25:46.009  6321  6321 V BtOppService: onStartCommand
08-29 11:25:46.010  6321  6714 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 11:25:46.010  6321  6714 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:25:46.015  6321  6714 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36e1b2e4 on behalf of 
08-29 11:25:46.016  6321  6714 V BluetoothOppNotification: update too frequent, put in queue
08-29 11:25:46.019  6321  6714 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 11:25:46.019  6321  6714 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:25:46.020  6321  6714 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22f2d34d on behalf of 
,08-29 11:25:46.021  6321  6714 V BluetoothOppNotification: update too frequent, put in queue
08-29 11:25:46.022  6321  6714 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-29 11:25:46.033  1031  1031 I art     : Explicit concurrent mark sweep GC freed 126712(6MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.732ms total 168.103ms
08-29 11:25:46.033  1031  1031 D BluetoothA2dp: Proxy object connected
,08-29 11:25:46.068  6321  6321 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:46.068  6321  6321 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-29 11:25:46.071  1031  1779 W libprocessgroup: failed to open /acct/uid_10080/pid_6036/cgroup.procs: No such file or directory
08-29 11:25:46.072  1031  1031 D BluetoothHeadset: Proxy object connected
08-29 11:25:46.074  6321  6321 V BluetoothOppNotification: new notify threadi!
08-29 11:25:46.074  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 11:25:46.074  1031  1093 D BluetoothManagerService: Message: 40
08-29 11:25:46.074  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 11:25:46.074  6321  6321 V BluetoothOppNotification: send delay message
08-29 11:25:46.074  6321  6321 V BtOppService: ContentObserver received notification
08-29 11:25:46.075  6321  6321 V BtOppService: ContentObserver received notification
08-29 11:25:46.075  6321  6321 V BtOppService: start RfcommListener
08-29 11:25:46.076  6321  6723 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 11:25:46.076  6321  6724 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 11:25:46.076  6321  6724 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:25:46.076  6321  6723 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18539e02 on behalf of 
08-29 11:25:46.077  6321  6724 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d4b1313 on behalf of 
08-29 11:25:46.077  6321  6723 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 11:25:46.078  6321  6723 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 11:25:46.078  6321  6321 V BtOppService: RfcommListener started
08-29 11:25:46.080  6321  6725 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 11:25:46.081  1031  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:25:46.082  6321  6724 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 11:25:46.082  6321  6723 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c791950 on behalf of 
08-29 11:25:46.083  6321  6725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:46.084  6321  6725 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-29 11:25:46.087  6321  6725 V BtOppRfcommListener: Started RFCOMM listener....
08-29 11:25:46.087  6321  6725 I BtOppRfcommListener: Accept thread started.
08-29 11:25:46.087  6321  6725 V BtOppRfcommListener: Accepting connection...
08-29 11:25:46.087  6321  6723 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 11:25:46.089  6321  6723 V BluetoothOppNotification: outbound notification was removed.
08-29 11:25:46.089  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:46.089  6321  6723 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 11:25:46.089  6321  6321 V BluetoothFtpService: Ftp Service onCreate
08-29 11:25:46.089  6321  6321 I BluetoothFtpService: Ftp Service onCreate
08-29 11:25:46.089  6321  6321 V BluetoothFtpService: Ftp Service onStartCommand
08-29 11:25:46.089  6321  6321 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:46.089  6321  6321 V BluetoothFtpService: Starting Listening on sockets
08-29 11:25:46.089  6321  6321 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:25:46.090  6321  6321 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:25:46.090  6321  6321 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:25:46.090  6321  6321 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:46.090  6321  6321 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 11:25:46.090  6321  6321 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 11:25:46.090  6321  6723 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f61984e on behalf of 
08-29 11:25:46.091  6321  6321 V BluetoothFtpService: Handler(): got msg=1
08-29 11:25:46.092  6321  6321 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 11:25:46.092  6321  6321 V BluetoothFtpService: Ftp Service initSocket
,08-29 11:25:46.095  1031  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:25:46.095  6321  6723 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 11:25:46.095  6321  6321 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:46.096  6321  6321 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-29 11:25:46.096  6321  6321 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 11:25:46.097  6321  6723 V BluetoothOppNotification: inbound notification was removed.
08-29 11:25:46.097  6321  6723 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 11:25:46.098  6321  6723 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1349cd6f on behalf of 
08-29 11:25:46.099  6321  6726 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 11:25:46.106  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:46.106  6321  6321 V BluetoothSapService: Sap Service onCreate
,08-29 11:25:46.108  6321  6321 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:46.108  6321  6321 V BluetoothSapService: state: 12
08-29 11:25:46.108  6321  6321 V BluetoothSapService: Starting SAP server process
08-29 11:25:46.109  6321  6321 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 11:25:46.105  6727  6727 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:46.105  6727  6727 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:46.110  6321  6728 V BluetoothSapService: Sap Service initRfcommSocket
08-29 11:25:46.110  1031  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:46.111  6321  6728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:46.111  6321  6728 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-29 11:25:46.111  6321  6728 V BluetoothSapService: Succeed to create listening socket 
08-29 11:25:46.111  6321  6728 V BluetoothSapService: Accepting socket connection...
08-29 11:25:46.116  6727  6727 V BT_SAP  : Event pipe created
08-29 11:25:46.116  6727  6727 V BT_SAP  : create_server_socket qcom.sap.server
08-29 11:25:46.116  6727  6727 V BT_SAP  : created socket fd 6
08-29 11:25:46.408  1031  2047 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6736 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-29 11:25:46.410  1031  2047 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
,08-29 11:25:46.438   313  1381 V AudioFlinger: 2127 died, releasing its sessions
,08-29 11:25:46.438   313  1381 V AudioFlinger:  pid 1850 @ 0
08-29 11:25:46.438   313  1381 V AudioFlinger:  pid 3157 @ 1
08-29 11:25:46.438   313  1381 V AudioFlinger:  pid 3157 @ 2
08-29 11:25:46.468  1031  2008 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
,08-29 11:25:46.509  6736  6736 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
08-29 11:25:46.512  6736  6736 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,08-29 11:25:46.522  6736  6736 V DrmService: Service onCreate
08-29 11:25:46.522  6736  6736 D DrmService: Received new request = 2
08-29 11:25:46.526  6736  6754 I DrmSntpClient: Start Sync process
08-29 11:25:46.526  6736  6754 D DrmSntpClient: Server : 0
08-29 11:25:46.564  1031  1588 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6755 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 11:25:46.571  6736  6754 D DrmSntpClient: Automatic sync but WiFi isn't enabled
08-29 11:25:46.572  6736  6736 D DrmService: Completed !! request = 2
08-29 11:25:46.572  6736  6736 D DrmService: Request count = 0
08-29 11:25:46.573  6736  6736 V DrmService: Service onDestroy
08-29 11:25:46.577  1031  1955 I ActivityManager: Killing 6058:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-29 11:25:46.639  1031  2028 W libprocessgroup: failed to open /acct/uid_10097/pid_6058/cgroup.procs: No such file or directory
,08-29 11:25:46.679  6755  6755 I art     : Almond Protected OAT
,08-29 11:25:46.713   309  6509 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 11:25:46.714   309  6509 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
08-29 11:25:46.715   309  6509 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
08-29 11:25:46.717  1031  1091 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 11:25:46.719  1031  6458 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-29 11:25:46.719  1031  6458 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s782ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:46.719  1031  6458 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s782ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:46.720  1031  6458 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-29 11:25:46.739   309  6517 D libc-netbsd: res_queryN name = europe.pool.ntp.org., class = 1, type = 1
08-29 11:25:46.741  1031  1091 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 11:25:46.742  1031  6511 D LocSvc_java: requestTime failed
08-29 11:25:46.742  1031  6511 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
,08-29 11:25:46.745  6755  6755 D WeatherApplication: removeAccount
08-29 11:25:46.747  6755  6755 D WeatherApplication: Account.length = 0
08-29 11:25:46.747  6755  6755 E WeatherApplication: OPERATOR:OPEN
08-29 11:25:46.753  6755  6755 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:46
08-29 11:25:46.757  6755  6755 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 11:25:46.758  6755  6755 D Weather.Utils: 2 : All the weather widget is gone.
,08-29 11:25:46.760  6755  6755 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-29 11:25:46.763  6755  6755 D WeatherAncestor: connectivity changed - connection : true
08-29 11:25:46.764  6755  6755 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-29 11:25:46.778  6755  6755 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 11:25:46.778  6755  6755 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-29 11:25:46.778  6755  6755 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-29 11:25:46.802  6755  6755 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-29 11:25:46.803  6755  6755 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:46
,08-29 11:25:46.868  1031  1991 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6785 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 11:25:46.870  1031  1991 I ActivityManager: Killing 6097:com.lge.eula/1000 (adj 15): empty #17
,08-29 11:25:46.899  1031  1533 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:46.899  1031  1533 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:25:46.934  1031  1535 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-29 11:25:46.935  1031  1535 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 11:25:46.938  1031  2029 W libprocessgroup: failed to open /acct/uid_1000/pid_6097/cgroup.procs: No such file or directory
08-29 11:25:47.076  6321  6321 V BluetoothOppNotification: new notify threadi!
08-29 11:25:47.077  6321  6321 V BluetoothOppNotification: send delay message
,08-29 11:25:47.078  6321  6812 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 11:25:47.083  6321  6812 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3dcfd18b on behalf of 
08-29 11:25:47.084  6321  6812 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 11:25:47.087  6321  6812 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 11:25:47.088   278   432 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 11:25:47.088   278   432 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 11:25:47.088   278   432 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 11:25:47.090  6785  6809 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 11:25:47.095   278   432 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 11:25:47.095   278   432 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 11:25:47.095   278   432 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 11:25:47.096  6785  6809 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 11:25:47.108  6321  6812 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fd6c268 on behalf of 
08-29 11:25:47.108  6321  6812 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-29 11:25:47.112  6321  6812 V BluetoothOppNotification: outbound notification was removed.
08-29 11:25:47.112  6321  6812 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 11:25:47.113  6321  6812 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@221ca681 on behalf of 
08-29 11:25:47.114  6321  6812 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 11:25:47.116  6321  6812 V BluetoothOppNotification: inbound notification was removed.
08-29 11:25:47.116  6321  6812 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 11:25:47.117  6321  6812 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9b46326 on behalf of 
08-29 11:25:47.138   278   432 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 11:25:47.139   278   432 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 11:25:47.139   278   432 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 11:25:47.140  6785  6814 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 11:25:47.142   278   432 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 11:25:47.142   278   432 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 11:25:47.142   278   432 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 11:25:47.142  6785  6814 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-29 11:25:47.345  6785  6785 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 11:25:47.358  6785  6785 I LibraryLoader: Loading: webviewchromium
08-29 11:25:47.362  6785  6785 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7669-7674)
08-29 11:25:47.362  6785  6785 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 11:25:47.371  6785  6785 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c56c31}
08-29 11:25:47.374  6785  6785 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:25:47.376  6785  6785 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 11:25:47.396  6785  6785 I BrowserStartupController: Initializing chromium process, renderers=0
,08-29 11:25:47.397  6785  6785 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 11:25:47.411  6785  6785 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-29 11:25:47.412   313  1383 V AudioPolicyService: registerClient() client 0xb14e93c0, uid 10093
08-29 11:25:47.414  6785  6834 W AudioManagerAndroid: Requires BLUETOOTH permission
08-29 11:25:47.415  6785  6785 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-29 11:25:47.416  6785  6785 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-29 11:25:47.432  6785  6785 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 11:25:47.432  6785  6785 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 11:25:47.432  6785  6785 I Adreno-EGL: Build Date: 12/12/14 금
08-29 11:25:47.432  6785  6785 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 11:25:47.432  6785  6785 I Adreno-EGL: Remote Branch: 
08-29 11:25:47.432  6785  6785 I Adreno-EGL: Local Patches: 
08-29 11:25:47.432  6785  6785 I Adreno-EGL: Reconstruct Branch: 
,08-29 11:25:47.514  6785  6785 I NSApplication: Starting up...
,08-29 11:25:47.565  1031  1588 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6847 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-29 11:25:47.567  1031  1588 I ActivityManager: Killing 5863:com.android.vending/u0a44 (adj 15): empty #17
08-29 11:25:47.619  1031  1780 W libprocessgroup: failed to open /acct/uid_10044/pid_5863/cgroup.procs: No such file or directory
,08-29 11:25:47.646  6847  6847 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 11:25:47.885  1031  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:47.885  1031  1919 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2086cfcc mBinding = false
,08-29 11:25:47.899  1031  1093 D BluetoothManagerService: Message: 2
,08-29 11:25:47.899  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:25:47.900  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:25:47.900  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-29 11:25:47.901  1031  1093 D BluetoothManagerService: Sending off request.
08-29 11:25:47.902  6321  6694 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 11:25:47.903  6321  6556 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 11:25:47.903  6321  6556 D BluetoothAdapterProperties: Setting state to 13
08-29 11:25:47.903  6321  6556 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 11:25:47.904  6321  6556 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 11:25:47.904  6321  6556 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 11:25:47.905  6321  6568 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:25:47.906  1031  1093 D BluetoothManagerService: Message: 60
08-29 11:25:47.906  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 11:25:47.906  1031  1093 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 11:25:47.906  6321  6556 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 11:25:47.907  6321  6726 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:25:47.907  6321  6556 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 11:25:47.908  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 11:25:47.908  6321  6627 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 11:25:47.909  6321  6728 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:25:47.909  6321  6695 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:25:47.910  6321  6725 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:25:47.910  6321  6693 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 11:25:47.910  6321  6693 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:25:47.910  6321  6693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 11:25:47.910  6321  6693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 11:25:47.910  6321  6693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 11:25:47.910  6321  6693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 11:25:47.910  6321  6693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 11:25:47.910  6321  6693 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 11:25:47.914  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:47.914  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:47.914  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: tru,e
08-29 11:25:47.914  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:47.914  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:47.914  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:47.914  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:47.914  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:47.914  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:47.914  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:47.915  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:47.917  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:25:47.917  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:25:47.917  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:25:47.917  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:25:47.917  6321  6627 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:47.917  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:25:47.917  6321  6627 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:47.917  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:25:47.917  6321  6627 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:47.917  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 11:25:47.917  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 11:25:47.917  6321  6627 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 11:25:47.923  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:47.923  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:47.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:47.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:47.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:47.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:47.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:47.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:47.923  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:47.923  5966  5966 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:47.923  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:47.927  6210  6210 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-29 11:25:47.928  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:47.931  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:25:47.932  6321  6321 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:47.932  6321  6321 D BluetoothMapService: STATE_TURNING_OFF
08-29 11:25:47.932  6321  6321 V BluetoothMapService: Handler(): got msg=4
08-29 11:25:47.933  6321  6321 D BluetoothMapService: MAP Service closeService in
08-29 11:25:47.933  6321  6321 D BluetoothMapMasInstance: MAP Service shutdown
08-29 11:25:47.933  6321  6321 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:25:47.933  6321  6321 V BluetoothMapService: MAP Service closeService out
08-29 11:25:47.934  6321  6321 V BtOppService: Receiver DISABLED_ACTION 
08-29 11:25:47.934  6321  6321 I BtOppRfcommListener: stopping Accept Thread
08-29 11:25:47.934  6321  6321 V BtOppRfcommListener: close mBtServerSocket
08-29 11:25:47.935  6321  6725 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 11:25:47.935  6321  6321 V BtOppRfcommListener: waiting for thread to terminate
08-29 11:25:47.935  6321  6321 V BtOppRfcommListener: done waiting for thread to terminate
08-29 11:25:47.938  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:47.941  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:47.945  6321  6321 V BtOppService: onDestroy
08-29 11:25:47.946  6210  6210 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 11:25:47.946  6321  6321 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 11:25:47.954  6321  6321 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:25:47.954  6321  6321 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:47.954  6321  6321 V BluetoothPbapReceiver: ***********state = 13
,08-29 11:25:47.957  6321  6321 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 11:25:47.960  6321  6321 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:47.960  6321  6321 V BluetoothPbapService: state: 13
08-29 11:25:47.960  6321  6321 V BluetoothPbapService: Pbap Service closeService in
08-29 11:25:47.960  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:25:47.971  6321  6321 V BluetoothPbapService: successfully stopped pbap service
08-29 11:25:47.971  6321  6321 V BluetoothPbapService: Pbap Service closeService out
08-29 11:25:47.972  6321  6321 V BluetoothPbapService: Pbap Service onDestroy
08-29 11:25:47.972  6321  6321 V BluetoothPbapService: Pbap Service closeService in
08-29 11:25:47.972  6321  6321 V BluetoothPbapService: Pbap Service closeService out
08-29 11:25:47.972  6321  6321 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-29 11:25:47.976  6210  6210 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:25:47.978  6210  6210 D BluetoothPbap: Proxy object disconnected
08-29 11:25:47.978  6210  6210 D PbapServerProfile: Bluetooth service disconnected
08-29 11:25:47.988  6210  6210 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 11:25:47.993  6210  6210 D BluetoothPermissionRequest: onReceive
08-29 11:25:47.993  6210  6210 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 11:25:47.999  6210  6210 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:25:48.002  6321  6321 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 11:25:48.003  6321  6321 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 11:25:48.003  6321  6321 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-29 11:25:48.008  6321  6321 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:48.008  6321  6321 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 11:25:48.010  6321  6321 V BluetoothFtpService: Ftp Service onStartCommand
08-29 11:25:48.010  6321  6321 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:48.010  6321  6321 V BluetoothFtpService: Ftp Service closeService
,08-29 11:25:48.010  6321  6321 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 11:25:48.014  6321  6321 V BluetoothFtpService: successfully stopped ftp service
08-29 11:25:48.015  6321  6321 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-29 11:25:48.015  6321  6321 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:25:48.015  6321  6321 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:25:48.015  6321  6321 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:48.015  6321  6321 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 11:25:48.015  6321  6321 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 11:25:48.017  6321  6321 V BluetoothFtpService: Ftp Service onDestroy
08-29 11:25:48.017  6321  6321 V BluetoothFtpService: Ftp Service closeService
08-29 11:25:48.021  6321  6321 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:48.021  6321  6321 V BluetoothSapService: state: 13
08-29 11:25:48.021  6321  6321 V BluetoothSapService: Stopping SAP server process
08-29 11:25:48.022  6321  6321 V BluetoothSapService: Sap Service closeSapService in
08-29 11:25:48.022  6321  6321 V BluetoothSapService: Close listen Socket : 
08-29 11:25:48.022  6321  6321 V BluetoothSapService: Close rfcomm Socket : 
08-29 11:25:48.022  6321  6321 V BluetoothSapService: Close sapd  Socket : 
08-29 11:25:48.024  6321  6321 V BluetoothSapService: Sap Service closeSapService out
08-29 11:25:48.024  6321  6321 V BluetoothSapService: Sap Service onDestroy
08-29 11:25:48.024  6321  6321 V BluetoothSapService: Sap Service closeSapService in
08-29 11:25:48.024  6321  6321 V BluetoothSapService: Close listen Socket : 
08-29 11:25:48.024  6321  6321 V BluetoothSapService: Close rfcomm Socket : 
08-29 11:25:48.024  6321  6321 V BluetoothSapService: Close sapd  Socket : 
08-29 11:25:48.025  6321  6321 V BluetoothSapService: Sap Service closeSapService out
08-29 11:25:48.041  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 11:25:48.046  3662  3696 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 11:25:48.056  2222  2222 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:48.066  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 11:25:48.066  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:48.067  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 11:25:48.067  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 11:25:48.069  6569  6569 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 11:25:48.072  6569  6569 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29c2b1bc
,08-29 11:25:48.072  6569  6569 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 11:25:48.072  6569  6569 D AppUp4:CustFacade: isPhone : true
08-29 11:25:48.072  6569  6569 D AppUp4:CustModeStarterReceiver: begin check event
08-29 11:25:48.073  6569  6569 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 11:25:48.077  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:48.078  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:25:48.079  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:25:48.082  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 11:25:48.089  6602  6602 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 11:25:48.090  4234  6886 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 11:25:48.096  4234  6888 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:48.097  4234  6888 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 11:25:48.108  6602  6891 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:25:48.124  6296  6893 W FormManager: Network not available. Please check & try again.
,08-29 11:25:48.128  3157  3157 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 11:25:48.128  3157  3157 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:48.128  3157  3157 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 11:25:48.130  6296  6894 V FormManager: Network unavailable.
08-29 11:25:48.132  6663  6663 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 11:25:48.132  6663  6663 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 11:25:48.146  6755  6755 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:48
,08-29 11:25:48.148  6296  6894 V FormManager: Network unavailable.
,08-29 11:25:48.150  6755  6755 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 11:25:48.150  6755  6755 D Weather.Utils: 2 : All the weather widget is gone.
08-29 11:25:48.151  6755  6755 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 11:25:48.151  6755  6755 D WeatherAncestor: connectivity changed - connection : true
08-29 11:25:48.151  6755  6755 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@49a149a
08-29 11:25:48.156  6755  6755 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 11:25:48.156  6755  6755 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 11:25:48.156  6755  6755 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 11:25:48.156  6755  6755 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 11:25:48.156  6755  6755 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:48
08-29 11:25:48.186  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 11:25:48.188  3662  3696 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 11:25:48.211  2222  2222 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:48.221  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 11:25:48.221  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:48.221  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 11:25:48.222  6569  6569 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 11:25:48.224  6569  6569 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 11:25:48.228  6569  6569 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29c2b1bc
08-29 11:25:48.228  6569  6569 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 11:25:48.228  6569  6569 D AppUp4:CustFacade: isPhone : true
08-29 11:25:48.228  6569  6569 D AppUp4:CustModeStarterReceiver: begin check event
08-29 11:25:48.228  6569  6569 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 11:25:48.233  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:48.233  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:25:48.235  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 11:25:48.237  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:25:48.242  4234  6897 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 11:25:48.244  6602  6602 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 11:25:48.245  4234  6898 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:48.246  4234  6898 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:25:48.267  6602  6899 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:25:48.271  3157  3157 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 11:25:48.271  3157  3157 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:48.271  3157  3157 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 11:25:48.273  6296  6901 W FormManager: Network not available. Please check & try again.
08-29 11:25:48.276  6663  6663 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 11:25:48.276  6663  6663 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 11:25:48.296  6755  6755 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:48
,08-29 11:25:48.299  6296  6902 V FormManager: Network unavailable.
,08-29 11:25:48.300  6755  6755 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 11:25:48.300  6755  6755 D Weather.Utils: 2 : All the weather widget is gone.
08-29 11:25:48.300  6755  6755 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 11:25:48.300  6755  6755 D WeatherAncestor: connectivity changed - connection : true
08-29 11:25:48.301  6755  6755 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@49a149a
08-29 11:25:48.302  6755  6755 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 11:25:48.302  6755  6755 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 11:25:48.302  6755  6755 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 11:25:48.302  6755  6755 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 11:25:48.302  6755  6755 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:48
08-29 11:25:48.310  6296  6902 V FormManager: Network unavailable.
,08-29 11:25:48.820  6321  6568 D bt_hci_bdroid: cleanup
,08-29 11:25:48.825  6321  6629 I bt_lpm  : LPM is already off!!!
08-29 11:25:48.826  6321  6662 I bt_userial_mct: exiting userial_read_thread
08-29 11:25:48.826  6321  6662 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 11:25:48.829  6321  6627 W bt-btif : ag scb idx 1 not allocated
08-29 11:25:48.829  6321  6627 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 11:25:48.829  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:25:48.829  6321  6627 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:48.829  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:25:48.829  6321  6627 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:48.829  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:25:48.829  6321  6627 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:25:48.830  6321  6627 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:48.830  6321  6627 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 11:25:48.830  6321  6568 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 11:25:48.831  6321  6629 I bt_vendor: hw_epilog_process
08-29 11:25:48.831  6321  6568 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 11:25:48.831  6321  6568 D bt_userial_mct: userial_close
08-29 11:25:48.831  6321  6568 E bt_userial_mct: pthread_join() FAILED result:3
08-29 11:25:48.831  6321  6568 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-29 11:25:48.838  6321  6568 D bt_hci_bdroid: set_power 0
08-29 11:25:48.838  6321  6568 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 11:25:48.838  6321  6568 I bt_vendor: bluetooth satus is on
08-29 11:25:48.838  6321  6568 I bt_vendor: bt-vendor : resetting BT status
08-29 11:25:48.838  6321  6568 I bt_vendor: Starting hciattach daemon
08-29 11:25:48.838  6321  6568 I bt_vendor: try to set false
,08-29 11:25:48.844  6321  6568 I bt_vendor: Starting hciattach daemon
08-29 11:25:48.844  6321  6568 I bt_vendor: try to set false
08-29 11:25:48.846  6321  6568 I bt_vendor: cleanup
08-29 11:25:48.847  6321  6627 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 11:25:48.847  6321  6568 I GKI_LINUX: GKI_exit_task 0 done
08-29 11:25:48.847  6321  6568 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 11:25:48.849  6321  6556 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 11:25:48.853  6321  6321 D HeadsetService: Received stop request...Stopping profile...
,08-29 11:25:48.859  6321  6321 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 11:25:48.859  6321  6321 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:25:48.859  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:48.860  6321  6593 D HeadsetStateMachine: Exit Disconnected: -1
08-29 11:25:48.864  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-29 11:25:48.864  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-29 11:25:48.864  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-29 11:25:48.864  1031  1031 D BluetoothHeadset: Proxy object disconnected
08-29 11:25:48.864  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 11:25:48.865  6321  6321 D A2dpService: Received stop request...Stopping profile...
,08-29 11:25:48.868  6321  6619 D A2dpStateMachine: Exit Disconnected: -1
08-29 11:25:48.872  6321  6321 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 11:25:48.874  6321  6556 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 11:25:48.875  6321  6321 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 11:25:48.875  6321  6321 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:25:48.875  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:48.877  1031  1031 D BluetoothA2dp: Proxy object disconnected
08-29 11:25:48.877  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 11:25:48.880  6321  6321 D HidService: Received stop request...Stopping profile...
08-29 11:25:48.880  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:48.883  6321  6321 D HealthService: Received stop request...Stopping profile...
08-29 11:25:48.883  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:48.886  6321  6321 D PanService: Received stop request...Stopping profile...
08-29 11:25:48.886  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:48.888  6321  6321 D HeadsetStateMachine: Unbinding service...
08-29 11:25:48.889  6321  6321 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:25:48.889  6321  6321 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:25:48.889  6321  6321 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:25:48.889  6321  6321 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:25:48.889  6321  6321 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 11:25:48.889  6321  6321 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:25:48.889  6321  6321 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 11:25:48.889  6321  6321 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 11:25:48.893  6321  6321 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 11:25:48.893  6321  6321 D BtGatt.GattService: stop()
08-29 11:25:48.893  6321  6321 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 11:25:48.895  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:48.896  6321  6321 D BluetoothMapService: Received stop request...Stopping profile...
08-29 11:25:48.896  6321  6321 D BluetoothMapService: stop()
08-29 11:25:48.897  6321  6321 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 11:25:48.897  6321  6321 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 11:25:48.898  6321  6321 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49a149a
08-29 11:25:48.899  6321  6321 I BluetoothA2dpServiceJni: cleanupNative
08-29 11:25:48.899  6321  6620 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 11:25:48.900  6321  6321 I GKI_LINUX: GKI_exit_task 2 done
08-29 11:25:48.900  6321  6321 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 11:25:48.900  6321  6321 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 11:25:48.900  6321  6321 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 11:25:48.900  6321  6321 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 11:25:48.901  6321  6321 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 11:25:48.901  6321  6321 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 11:25:48.901  6321  6321 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 11:25:48.901  6321  6321 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 11:25:48.904  6321  6321 V BluetoothMapService: Handler(): got msg=4
08-29 11:25:48.904  6321  6321 D BluetoothMapService: MAP Service closeService in
08-29 11:25:48.904  6321  6321 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:25:48.904  6321  6321 V BluetoothMapService: MAP Service closeService out
,08-29 11:25:48.907  6321  6556 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 11:25:48.907  6321  6556 D BluetoothAdapterProperties: Setting state to 10
08-29 11:25:48.908  6321  6556 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 11:25:48.909  6321  6321 D BluetoothMapService: cleanup()
08-29 11:25:48.909  6321  6321 D BluetoothMapService: MAP Service closeService in
08-29 11:25:48.909  6321  6321 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:25:48.909  6321  6321 V BluetoothMapService: MAP Service closeService out
08-29 11:25:48.910  1031  1093 D BluetoothManagerService: Message: 60
08-29 11:25:48.910  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 11:25:48.910  1031  1093 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-29 11:25:48.911  6321  6556 I BluetoothAdapterState: Entering OffState
08-29 11:25:48.911  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:25:48.912  6210  6226 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 11:25:48.912  6210  6226 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:25:48.913  1031  1093 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:25:48.913  6210  6226 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 11:25:48.914  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:25:48.914  6210  6226 D BluetoothMap: onBluetoothStateChange: up=false
08-29 11:25:48.915  6210  6226 D BluetoothPan: onBluetoothStateChange on: false
08-29 11:25:48.915  1031  1093 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:25:48.918  6210  6226 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 11:25:48.921  1850  2451 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:25:48.923  1031  1093 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 11:25:48.923  1031  1093 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 11:25:48.925  1031  1093 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 11:25:48.925  1031  1093 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 11:25:48.925  1031  1093 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2086cfcc mBinding = false
08-29 11:25:48.926  1031  1093 D BluetoothManagerService: Sending unbind request.
08-29 11:25:48.930  6321  6568 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 11:25:48.932  6321  6321 I GKI_LINUX: GKI_exit_task 1 done
08-29 11:25:48.933  6321  6321 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 11:25:48.933  6321  6321 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 11:25:48.934  6321  6321 I art     : --- WEIRD: removing null entry 248
08-29 11:25:48.934  6321  6321 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-29 11:25:48.934  6321  6321 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 11:25:48.935  6321  6321 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 11:25:48.936  1031  1093 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 11:25:48.938  6321  6321 I art     : System.exit called, status: 0
08-29 11:25:48.938  6321  6321 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 11:25:48.957   313  1381 V AudioFlinger: 6321 died, releasing its sessions
08-29 11:25:48.958   313  1381 V AudioFlinger:  pid 1850 @ 0
08-29 11:25:48.958   313  1381 V AudioFlinger:  pid 3157 @ 1
08-29 11:25:48.958   313  1381 V AudioFlinger:  pid 3157 @ 2
,08-29 11:25:48.961  1938  1938 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-29 11:25:48.961  1938  2125 D LGBluetoothAPIService: Message: 101
,08-29 11:25:48.961  1938  2125 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-29 11:25:48.962  1938  2125 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
,08-29 11:25:48.962  1938  2125 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-29 11:25:48.964  6210  6210 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 11:25:48.969  1031  1755 I ActivityManager: Process com.android.bluetooth (pid 6321) has died
,08-29 11:25:48.970  1031  1755 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-29 11:25:48.970  1031  1755 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
,08-29 11:25:48.983  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:48.983  1938  2125 D LGBluetoothAPIService: Message: 2
08-29 11:25:48.984  1938  2125 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-29 11:25:48.986  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:48.988  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:48.989  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 11:25:48.991  6210  6210 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-29 11:25:48.991  6210  6210 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 11:25:48.995  6210  6210 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 11:25:49.000  1598  1598 D BluetoothAdapter: 689873533: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:49.000  1598  1598 D BluetoothAdapter: 689873533: getState() :  mService = null. Returning STATE_OFF
,08-29 11:25:49.049  1031  1777 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6934 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 11:25:49.051  6210  6210 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:25:49.092  6934  6934 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 11:25:49.093  6934  6934 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 11:25:49.093  6934  6934 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 11:25:49.094  6934  6934 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 11:25:49.108  6934  6934 D BluetoothAdapterApp: Loading JNI Library
,08-29 11:25:49.132  6934  6934 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@348bdf42 Instance Count = 1
,08-29 11:25:49.137  6934  6934 D BluetoothAdapterApp: onCreate
,08-29 11:25:49.166  6934  6934 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-29 11:25:49.167  6934  6934 D ProfileConfigQcom: Adding HeadsetService
,08-29 11:25:49.168  6934  6934 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 11:25:49.168  6934  6934 D ProfileConfigQcom: Adding A2dpService
08-29 11:25:49.168  6934  6934 D ProfileConfigQcom: [BTUI] HidService is supported
,08-29 11:25:49.169  6934  6934 D ProfileConfigQcom: Adding HidService
08-29 11:25:49.169  6934  6934 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 11:25:49.170  6934  6934 D ProfileConfigQcom: Adding HealthService
08-29 11:25:49.170  6934  6934 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 11:25:49.171  6934  6934 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 11:25:49.172  6934  6934 D ProfileConfigQcom: Adding PanService
08-29 11:25:49.172  6934  6934 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 11:25:49.172  6934  6934 D ProfileConfigQcom: Adding GattService
08-29 11:25:49.173  6934  6934 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 11:25:49.173  6934  6934 D ProfileConfigQcom: Adding BluetoothMapService
08-29 11:25:49.174  6934  6934 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 11:25:49.175  6934  6934 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:25:49.177  6934  6934 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:49.178  6934  6934 V BluetoothPbapReceiver: ***********state = 10
08-29 11:25:49.181  6934  6934 V LGMDMManagerInternal: Create singleton instance
,08-29 11:25:49.265  6934  6934 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 11:25:49.265  6934  6934 D LGBluetoothAPIServer: [BTUI] onBind()
,08-29 11:25:49.268  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:25:49.274  1938  1938 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 11:25:49.274  1938  2125 D LGBluetoothAPIService: Message: 100
08-29 11:25:49.275  1938  2125 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 11:25:49.286  6210  6210 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-29 11:25:49.301  6210  6210 D BluetoothPermissionRequest: onReceive
,08-29 11:25:49.304  6210  6210 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-29 11:25:49.304  6210  6210 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 11:25:49.308  6210  6210 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:25:49.315  6934  6934 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-29 11:25:49.321  6934  6934 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:49.325  6934  6934 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:25:49.326  6934  6934 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:25:49.326  6934  6934 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:25:49.327  6934  6934 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:49.328  6934  6934 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-29 11:25:49.334  6275  6275 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 11:25:50.899  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:50.900  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:51.950  1031  1541 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-29 11:25:52.125  6785  6811 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-29 11:25:53.061  1031  1956 I ActivityManager: Killing 6116:com.lge.bnr/1000 (adj 15): empty #17
,08-29 11:25:53.093  1031  2047 W libprocessgroup: failed to open /acct/uid_1000/pid_6116/cgroup.procs: No such file or directory
,08-29 11:25:53.912  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:25:53.912  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b98beee added. We now have 6 listener(s)
,08-29 11:25:53.912  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:53.925  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:53.926  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3449ff8f added. We now have 7 listener(s)
08-29 11:25:53.926  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:53.928  5966  6027 I System.out: IsBluetoothEnabled
08-29 11:25:53.929  1031  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:53.930  1031  1991 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-29 11:25:53.931  1031  1093 D BluetoothManagerService: Message: 2
08-29 11:25:53.935  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:53.937  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:53.938  1031  1047 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 11:25:53.954  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:25:53.954  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:25:53.954  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-29 11:25:53.955  1031  1093 D BluetoothManagerService: Message: 1
08-29 11:25:53.955  1031  1093 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 11:25:53.980  1031  1093 D BluetoothManagerService: Message: 20
08-29 11:25:53.980  1031  1093 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ba4e132:true
,08-29 11:25:53.985  6934  6934 D BluetoothAdapterState: make
08-29 11:25:53.990  6934  6934 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 11:25:53.991  6934  6934 I bluedroid-qcom: init
08-29 11:25:53.992  6934  6966 I BluetoothAdapterState: Entering OffState
08-29 11:25:53.992  6934  6934 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 11:25:53.992  6934  6934 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 11:25:53.993  6934  6934 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 11:25:53.993  6934  6934 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 11:25:53.993  6934  6934 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
,08-29 11:25:53.997  6934  6934 I bluedroid-qcom: get_profile_interface socket
08-29 11:25:53.997  6934  6934 I bluedroid-qcom: get_profile_interface map_client
08-29 11:25:53.995  6969  6969 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:54.001  6934  6970 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 11:25:54.003  6934  6970 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 11:25:53.995  6969  6969 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:54.011  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 11:25:54.011  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
,08-29 11:25:54.018  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 11:25:54.018  1031  1093 D BluetoothManagerService: Message: 40
08-29 11:25:54.019  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 11:25:54.019  6934  6950 I bluedroid-qcom: config_hci_snoop_log
08-29 11:25:54.022  6969  6969 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 11:25:54.022  6969  6969 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 11:25:54.022  6969  6969 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 11:25:54.022  1031  1093 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 11:25:54.023  1031  1093 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 11:25:54.024  6934  6970 D BluetoothAdapterProperties: Name is: G3
,08-29 11:25:54.026  6969  6969 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 11:25:54.039  6934  6966 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-29 11:25:54.042  6934  6966 D BluetoothAdapterProperties: Setting state to 11
08-29 11:25:54.042  6934  6966 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 11:25:54.043  1031  1093 D BluetoothManagerService: Message: 60
08-29 11:25:54.043  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 11:25:54.043  1031  1093 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 11:25:54.045  6934  6966 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 11:25:54.050  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:54.051  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 11:25:54.056  6969  6969 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 11:25:54.056  6969  6969 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 11:25:54.059  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:54.061  6210  6210 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 11:25:54.068  6934  6934 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:25:54.068  6934  6934 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:54.068  6934  6934 V BluetoothPbapReceiver: ***********state = 11
,08-29 11:25:54.074  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:25:54.086  6934  6966 D BluetoothBondStateMachine: make
,08-29 11:25:54.096  6934  6966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
,08-29 11:25:54.096  6934  6966 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
,08-29 11:25:54.096  6934  6966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
08-29 11:25:54.096  6934  6966 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 11:25:54.100  6934  6971 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 11:25:54.103  6934  6966 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-29 11:25:54.110  6934  6966 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:54.114  6210  6210 D BluetoothPermissionRequest: onReceive
08-29 11:25:54.119  6934  6934 D HeadsetService: Received start request. Starting profile...
08-29 11:25:54.119  6210  6210 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:25:54.119  6934  6966 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 11:25:54.120  6934  6934 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 11:25:54.121  6934  6934 D LGBluetoothHfpAdapter: Version 1.6
08-29 11:25:54.123  6934  6934 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 11:25:54.124  6934  6934 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 11:25:54.125  6934  6966 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:54.125  6934  6934 D HeadsetStateMachine: make
08-29 11:25:54.130  6934  6966 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:54.135  6934  6966 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:54.139  6934  6966 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 11:25:54.144  6934  6966 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:25:54.151  6934  6934 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:25:54.152  6934  6934 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:25:54.155  6934  6934 D HeadsetStateMachine: max_hf_connections = 1
08-29 11:25:54.155  6934  6934 I bluedroid-qcom: get_profile_interface handsfree
,08-29 11:25:54.155  6934  6966 V LGMDMManager: Create singleton instance
08-29 11:25:54.157  6934  6966 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 11:25:54.157  6934  6934 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 11:25:54.158   313  1381 V AudioPolicyService: registerClient() client 0xb14b7460, uid 1002
08-29 11:25:54.158   313  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 11:25:54.158   313  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 11:25:54.158   313  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:25:54.158  6934  6934 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 11:25:54.159   313   313 V AudioFlinger: registerClient() client 0xb1188118, pid 6934
08-29 11:25:54.159   313  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:54.159   313  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:25:54.159  1598  1615 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:54.159  1598  1615 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:25:54.159  1850  2652 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:54.159  1850  2652 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:25:54.160  1031  1956 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:54.160  1031  1956 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:25:54.160  3157  3178 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:54.160  3157  3178 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:25:54.160  6934  6949 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:25:54.160   313  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:54.160   313  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:25:54.160  1598  1617 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:54.160  1598  1617 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:25:54.160  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:54.160  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:25:54.160  3157  3174 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:54.160  3157  3174 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:25:54.160  1031  1991 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:54.160  1031  1991 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:25:54.161  6934  6949 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 11:25:54.161  6934  6934 V ToneGenerator: Create Track: 0xb4928a80
08-29 11:25:54.161  6934  6949 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:25:54.161  6934  6934 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 11:25:54.161  6934  6934 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 11:25:54.161  6934  6949 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 11:25:54.161   313  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 11:25:54.161   313  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 11:25:54.161   313  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 11:25:54.161   313  1381 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:25:54.161   313  1383 I Aud,ioFlinger: isAudioPlaybackHookOn() false
08-29 11:25:54.161   313   313 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 11:25:54.161   313   313 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 11:25:54.161   313   313 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 11:25:54.161   313   313 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:25:54.162  6934  6934 V AudioSystem: getLatency() output 2, latency 50
08-29 11:25:54.162  6934  6934 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 11:25:54.162  6934  6934 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 11:25:54.162   313  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 11:25:54.162   313  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 11:25:54.162   313  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 11:25:54.162   313  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 11:25:54.162   313  1382 V AudioFlinger: createTrack() lSessionId: 23
08-29 11:25:54.164  6934  6934 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 11:25:54.164   313  1381 V AudioFlinger: acquiring 23 from 6934, for 6934
08-29 11:25:54.164   313  1381 V AudioFlinger:  added new entry for 23
08-29 11:25:54.164  6934  6934 V ToneGenerator: ToneGenerator INIT OK, time: 134477
08-29 11:25:54.164  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
08-29 11:25:54.165  6934  6987 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 11:25:54.165  6934  6987 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:25:54.165  6934  6987 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:25:54.165  6934  6987 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 11:25:54.165   313  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6934
08-29 11:25:54.166   313  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 11:25:54.166   313  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 11:25:54.166   313  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 11:25:54.166   313  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 11:25:54.166   313  1383 V voice   : voice_set_parameters: exit with code(0)
08-29 11:25:54.166  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
08-29 11:25:54.166   313  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 11:25:54.166   313  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 11:25:54.166   313  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 11:25:54.166   313  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 11:25:54.166   313  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 11:25:54.166   313  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 11:25:54.166  6934  6987 V ToneGenerator: ToneGenerator destructor
08-29 11:25:54.166  6934  6987 V ToneGenerator: stopTone
08-29 11:25:54.166  6934  6987 V ToneGenerator: Delete Track: 0xb4928a80
08-29 11:25:54.167  6934  6987 V AudioTrack: ~AudioTrack, releasing session id from 6934 on behalf of 6934
08-29 11:25:54.168   313  1382 V AudioFlinger: releasing 23 from 6934 for 6934
08-29 11:25:54.168   313  1382 V AudioFlinger:  decremented refcount to 0
08-29 11:25:54.168   313  1382 V AudioFlinger: purging stale effects
08-29 11:25:54.168   313  1382 V A,udioPolicyService: AudioCommandThread() adding release output 2
08-29 11:25:54.168   313  1382 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 11:25:54.168   313  1255 V AudioPolicyService: AudioCommandThread() waking up
08-29 11:25:54.168   313  1255 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 11:25:54.168   313  1255 V AudioPolicyManager: releaseOutput() 2
08-29 11:25:54.168   313  1255 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 11:25:54.168   313  1382 V AudioFlinger: PlaybackThread::Track destructor
08-29 11:25:54.168   313  1382 V AudioFlinger: removeClient_l() pid 6934, calling pid 313
08-29 11:25:54.169  6934  6934 D A2dpService: Received start request. Starting profile...
08-29 11:25:54.169  1031  1588 W Process : Unable to open /proc/6989/status
08-29 11:25:54.170  6934  6934 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 11:25:54.171  6934  6934 V Avrcp   : make
08-29 11:25:54.172  6934  6934 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 11:25:54.172  6934  6934 I bluedroid-qcom: get_profile_interface avrcp
08-29 11:25:54.178  6934  6934 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 11:25:54.180  6934  6934 E AudioManager: No RCC entry present to update
08-29 11:25:54.180  6934  6934 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 11:25:54.183  6934  6934 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-29 11:25:54.184  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 11:25:54.184  6934  6934 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 11:25:54.187  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 11:25:54.277  1031  1955 V SIM_STK : Menu title from STK is T-Mobile
,08-29 11:25:54.277  1031  1955 V SIM_STK : Menu title from STK is T-Mobile
,08-29 11:25:54.349  1031  1588 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 11:25:54.357  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 11:25:54.361  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 11:25:54.362  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 11:25:54.362  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 11:25:54.362  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 11:25:54.362  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 11:25:54.362  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 11:25:54.362  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 11:25:54.362  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 11:25:54.362  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 11:25:54.362  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 11:25:54.363  6934  6934 I BluetoothA2dpServiceJni: classInitNative
08-29 11:25:54.363  6934  6934 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:25:54.363  6934  6934 D A2dpStateMachine: make
08-29 11:25:54.366  6934  6934 I bluedroid-qcom: get_profile_interface a2dp
,08-29 11:25:54.366  6934  6994 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 11:25:54.371  6934  6934 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:25:54.371  6934  6934 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 11:25:54.372  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
08-29 11:25:54.372  6934  6993 D A2dpStateMachine: Enter Disconnected: -2
08-29 11:25:54.372  6934  6934 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 11:25:54.374  6934  6934 D HidService: Received start request. Starting profile...
08-29 11:25:54.374  6934  6934 I bluedroid-qcom: get_profile_interface hidhost
08-29 11:25:54.374  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
08-29 11:25:54.374  6934  6934 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 11:25:54.375  6934  6934 D HealthService: Received start request. Starting profile...
08-29 11:25:54.379  6934  6934 I bluedroid-qcom: get_profile_interface health
08-29 11:25:54.379  6934  6934 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 11:25:54.379  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
08-29 11:25:54.380  6934  6934 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 11:25:54.381  6934  6934 D PanService: Received start request. Starting profile...
,08-29 11:25:54.381  6934  6934 D BluetoothPanServiceJni: initializeNative(L110): pan,
08-29 11:25:54.381  6934  6934 I bluedroid-qcom: get_profile_interface pan,
,08-29 11:25:54.386  6934  6934 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter],
08-29 11:25:54.386  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
,08-29 11:25:54.387  6934  6934 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 11:25:54.391  6934  6934 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 11:25:54.391  6934  6934 D BtGatt.GattService: Received start request. Starting profile...
08-29 11:25:54.391  6934  6934 D BtGatt.GattService: start()
,08-29 11:25:54.391  6934  6934 I bluedroid-qcom: get_profile_interface gatt
08-29 11:25:54.391  6934  6934 D BtGatt.AdvertiseManager: advertise manager created
08-29 11:25:54.404  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
,08-29 11:25:54.407  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
08-29 11:25:54.408  6934  6934 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 11:25:54.411  6934  6934 V BluetoothMapService: BluetoothMapBinder()
08-29 11:25:54.412  6934  6934 D BluetoothMapService: Received start request. Starting profile...
08-29 11:25:54.412  6934  6934 D BluetoothMapService: start()
08-29 11:25:54.417  6934  6934 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 11:25:54.417  6934  6934 D BluetoothMapEmailAppObserver: createReceiver()
,08-29 11:25:54.419  6934  6934 D BluetoothMapEmailAppObserver: initObservers()
,08-29 11:25:54.419  6934  6934 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 11:25:54.431  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
08-29 11:25:54.432  6934  6934 D HeadsetStateMachine: Proxy object connected
08-29 11:25:54.433  6934  6934 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-29 11:25:54.433  6934  6934 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-29 11:25:54.437  6934  6987 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 11:25:54.438  6934  6987 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 11:25:54.440  6934  6987 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 11:25:54.441  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:25:54.447  6934  6934 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:54.458  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:25:54.463  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 11:25:54.467  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:25:54.468  6934  6934 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 11:25:54.472  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:25:54.475  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 11:25:54.476  6934  6934 V BluetoothMapService: Handler(): got msg=1
08-29 11:25:54.476  6934  6934 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:25:54.477  6934  6934 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-29 11:25:54.477  6934  6934 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:25:54.477  6934  6934 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:54.477  6934  6934 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 11:25:54.478  6934  6966 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 11:25:54.478  6934  6966 I bluedroid-qcom: enable
08-29 11:25:54.479  6934  6966 I bt_hci_bdroid: init
08-29 11:25:54.482  6934  6966 I bt_vendor: bt-vendor : init
08-29 11:25:54.482  6934  6966 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 11:25:54.482  6934  6966 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 11:25:54.482  6934  6966 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 11:25:54.482  6934  6966 D bt_userial_mct: userial_init
08-29 11:25:54.483  6934  7005 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 11:25:54.483  6934  6966 D bt_hci_bdroid: set_power 1
08-29 11:25:54.483  6934  6966 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 11:25:54.483  6934  6966 I bt_vendor: Starting hciattach daemon
08-29 11:25:54.483  6934  6966 I bt_vendor: try to set true
08-29 11:25:54.484  6934  7005 I bt-btu  : btu_task pending for preload complete event
08-29 11:25:54.485  7008  7008 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 11:25:54.485  7008  7008 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:54.534  7009  7009 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 11:25:54.647  7015  7015 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 11:25:54.662  7016  7016 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 11:25:54.691  7018  7018 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 11:25:54.721  7019  7019 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 11:25:54.734  7020  7020 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 11:25:54.747  7021  7021 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 11:25:54.771  7026  7026 I libmdmdetect: ESOC framework not supported
08-29 11:25:54.772  7026  7026 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 11:25:54.780  7026  7026 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-29 11:25:54.780  7026  7026 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 11:25:54.780  7026  7026 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 11:25:54.780  7026  7026 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 11:25:54.780  7026  7026 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 11:25:54.780  7026  7026 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 11:25:54.780  7026  7026 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 11:25:54.822  7026  7027 E QC-QMI  : qmi_client [7026] 15: failed to locate client data
08-29 11:25:54.823   473   473 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 11:25:54.823   473   473 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-29 11:25:54.884  7028  7028 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 11:25:54.900  7032  7032 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 11:25:54.949  6934  6966 I bt_vendor: bluetooth satus is on
,08-29 11:25:54.949  6934  6966 D bt_hci_bdroid: preload
,08-29 11:25:54.956  6934  7007 D bt_userial_mct: userial_open(port:0)
,08-29 11:25:54.957  6934  7007 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 11:25:54.962  6934  7007 I bt_vendor: Done intiailizing UART
,08-29 11:25:54.965  6934  7007 I bt_vendor: Done intiailizing UART
08-29 11:25:54.965  6934  7007 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 11:25:54.966  6934  7007 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 11:25:54.969  6934  7005 I bt-btu  : btu_task received preload complete event
08-29 11:25:54.970  6934  7005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-29 11:25:54.970  6934  7005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f,
,08-29 11:25:54.976  6934  7005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-29 11:25:54.992  6934  7034 D bt_userial_mct: Entering userial_read_thread()
08-29 11:25:55.001  6934  7005 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 11:25:55.001  6934  7005 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 11:25:55.001  6934  7005 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 11:25:55.001  6934  7005 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 11:25:55.001  6934  7005 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 11:25:55.001  6934  7005 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 11:25:55.001  6934  7005 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 11:25:55.002  6934  7005 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 11:25:55.002  6934  7005 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 11:25:55.002  6934  7005 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 11:25:55.002  6934  7005 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 11:25:55.002  6934  7005 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 11:25:55.002  6934  7005 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 11:25:55.002  6934  7005 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 11:25:55.002  6934  7005 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 11:25:55.002  6934  7005 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 11:25:55.108  6934  7005 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-29 11:25:55.109  6934  7005 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa017c061 
,08-29 11:25:55.109  6934  7005 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa017c061 
,08-29 11:25:55.165  6934  6970 E bt-btif : Calling BTA_HhEnable
,08-29 11:25:55.165  6934  6970 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-29 11:25:55.166  6934  6970 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 11:25:55.177  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-29 11:25:55.178  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
,08-29 11:25:55.179  6934  7005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-29 11:25:55.179  6934  7005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 11:25:55.179  6934  7005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 11:25:55.180  6934  7005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 11:25:55.180  6934  7005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 11:25:55.182  6934  6970 D BluetoothAdapterProperties: Name is: G3
08-29 11:25:55.190  6934  6970 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:25:55.190  6934  6970 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:25:55.191  6934  6970 D bt_hci_bdroid: postload
,08-29 11:25:55.199  6934  7007 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:25:55.201  6934  7005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 11:25:55.202  6934  6970 D bte_conf: Device ID record 1 : primary
08-29 11:25:55.202  6934  6970 D bte_conf:   vendorId            = 00c4
08-29 11:25:55.202  6934  6970 D bte_conf:   vendorIdSource      = 0001
08-29 11:25:55.202  6934  6970 D bte_conf:   product             = 13a1
08-29 11:25:55.202  6934  6970 D bte_conf:   version             = 1000
08-29 11:25:55.202  6934  6970 D bte_conf:   clientExecutableURL = 
08-29 11:25:55.202  6934  6970 D bte_conf:   serviceDescription  = 
08-29 11:25:55.202  6934  6970 D bte_conf:   documentationURL    = 
08-29 11:25:55.202  6934  6970 D bte_conf: bte_load_did_conf no section named DID2.
08-29 11:25:55.203  6934  7007 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:25:55.206  6934  6966 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 11:25:55.206  6934  6966 D BluetoothAdapterProperties: ScanMode =  20
08-29 11:25:55.206  6934  6966 D BluetoothAdapterProperties: State =  11
08-29 11:25:55.206  6934  6966 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 11:25:55.207  6934  6966 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 11:25:55.207  6934  6966 D BluetoothAdapterProperties: Setting state to 12
08-29 11:25:55.207  6934  6966 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 11:25:55.208  6934  6970 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 11:25:55.208  6934  6970 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 11:25:55.205  7036  7036 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 11:25:55.215  7036  7036 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:55.222  1031  1093 D BluetoothManagerService: Message: 60
08-29 11:25:55.222  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 11:25:55.222  1031  1093 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-29 11:25:55.222  6934  7007 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:25:55.231  6934  7005 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:25:55.231  6934  7005 W bt-smp  : Plain text(LSB ~ MSB) = 6d 98 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:25:55.231  6934  7005 W bt-smp  : Encrypted text(LSB ~ MSB) = 19 80 1d 24 c2 1f e3 09 01 51 f9 98 88 61 71 fe 
,08-29 11:25:55.236  6934  7007 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:25:55.237  6934  7005 W bt-btm  : Stopping oneshot timer
08-29 11:25:55.237  6934  7034 E bt_mct  : hci lib postload completed
08-29 11:25:55.240  6934  6966 I BluetoothAdapterState: Entering On State
08-29 11:25:55.241  1850  2451 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:25:55.245  6934  6966 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 11:25:55.245  6934  6966 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 11:25:55.245  6934  6966 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-29 11:25:55.257  6934  6966 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-29 11:25:55.275  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:55.275  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:55.275  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:55.275  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:55.275  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:55.275  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:55.275  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:55.275  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:55.283  6934  6970 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:25:55.283  6934  6970 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 11:25:55.285  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:55.290  6934  6966 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-29 11:25:55.297  6934  7005 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:25:55.297  6934  7005 W bt-smp  : Plain text(LSB ~ MSB) = ed 5f 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:25:55.297  6934  7005 W bt-smp  : Encrypted text(LSB ~ MSB) = b5 1a 23 f0 fe d8 03 87 ed b1 84 34 bd db f4 c5 
08-29 11:25:55.297  6934  7005 W bt-btm  : Stopping oneshot timer
08-29 11:25:55.309  1850  1850 D BluetoothHeadset: Proxy object connected
,08-29 11:25:55.319  6210  6226 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 11:25:55.329  7041  7041 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-29 11:25:55.337  6210  6226 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:25:55.339  1031  1093 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:25:55.341  1031  1031 D BluetoothA2dp: Proxy object connected
08-29 11:25:55.342  6934  7005 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:25:55.342  6934  7005 W bt-smp  : Plain text(LSB ~ MSB) = 96 cf 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:25:55.342  6934  7005 W bt-smp  : Encrypted text(LSB ~ MSB) = 43 0b 00 c6 54 98 e1 ac b7 9d 64 4e db 73 98 d0 
08-29 11:25:55.342  6934  7005 W bt-btm  : Stopping oneshot timer
08-29 11:25:55.343  6210  6227 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 11:25:55.348  6210  6210 D BluetoothInputDevice: Proxy object connected
08-29 11:25:55.348  6210  6210 D HidProfile: Bluetooth service connected
08-29 11:25:55.349  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:25:55.354  1850  1850 D BluetoothHeadset: Proxy object connected
08-29 11:25:55.354  6210  6226 D BluetoothMap: onBluetoothStateChange: up=true
08-29 11:25:55.357  6934  7005 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:25:55.357  6934  7005 W bt-smp  : Plain text(LSB ~ MSB) = 8f 37 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:25:55.357  6934  7005 W bt-smp  : Encrypted text(LSB ~ MSB) = 62 96 e3 8f 5f 78 71 1c c9 3a e2 cf b9 32 7b 06 
08-29 11:25:55.357  6934  7005 W bt-btm  : Stopping oneshot timer
,08-29 11:25:55.362  6210  6227 D BluetoothPan: onBluetoothStateChange on: true
08-29 11:25:55.362  6210  6227 D BluetoothPan: onBluetoothStateChange call bindService
08-29 11:25:55.366  1031  1093 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:25:55.373  1031  1031 D BluetoothHeadset: Proxy object connected
08-29 11:25:55.373  6934  7005 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:25:55.374  6934  7005 W bt-smp  : Plain text(LSB ~ MSB) = 0f c7 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:25:55.374  6934  7005 W bt-smp  : Encrypted text(LSB ~ MSB) = 30 83 65 36 b5 9a bb ce 8f 82 54 d5 49 a2 19 b6 
08-29 11:25:55.374  6934  7005 W bt-btm  : Stopping oneshot timer
08-29 11:25:55.377  6210  6226 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:25:55.378  6210  6210 D BluetoothHeadset: Proxy object connected
08-29 11:25:55.378  6210  6210 D HeadsetProfile: Bluetooth service connected
,08-29 11:25:55.384  1850  2652 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:25:55.385  6210  6210 D BluetoothMap: Proxy object connected
08-29 11:25:55.385  6210  6210 D MapProfile: Bluetooth service connected
08-29 11:25:55.385  6210  6210 D BluetoothMap: getConnectedDevices()
08-29 11:25:55.387  6934  7054 V BluetoothMapService: getConnectedDevices()
08-29 11:25:55.388  1850  1850 D BluetoothHeadset: Proxy object connected
08-29 11:25:55.388  6210  6210 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:25:55.389  6210  6210 D PanProfile: Bluetooth service connected
08-29 11:25:55.390  1031  1093 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,08-29 11:25:55.390  1031  1093 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 11:25:55.392  6210  6210 D BluetoothA2dp: Proxy object connected
08-29 11:25:55.392  6210  6210 D A2dpProfile: Bluetooth service connected
08-29 11:25:55.393  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:55.393  1938  2125 D LGBluetoothAPIService: Message: 1
08-29 11:25:55.393  1938  2125 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 11:25:55.393  1938  2125 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-29 11:25:55.393  1938  2125 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-29 11:25:55.399  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 11:25:55.405  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:55.486  1031  2047 I art     : Explicit concurrent mark sweep GC freed 33355(1652KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.364ms total 94.536ms
08-29 11:25:55.487  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 11:25:55.487  1031  1093 D BluetoothManagerService: Message: 40
08-29 11:25:55.487  1031  1093 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-29 11:25:55.489  6210  6210 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 11:25:55.490  6210  6210 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 11:25:55.491  6934  6934 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:55.491  6934  6934 D BluetoothMapService: STATE_ON
08-29 11:25:55.496  6210  6210 D DockEventReceiver: finishStartingService: stopping service
08-29 11:25:55.500  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
08-29 11:25:55.500  6934  6934 V BluetoothPbapService: Pbap Service onCreate
08-29 11:25:55.500  6934  6934 V BluetoothPbapService: Starting PBAP service
08-29 11:25:55.501  6934  6934 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 11:25:55.501  6934  6934 V BluetoothPbapService: Pbap Service onBind
08-29 11:25:55.503  6934  6934 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:55.503  6934  6934 V BluetoothPbapService: state: 12
08-29 11:25:55.503  6934  6934 V BluetoothMapService: Handler(): got msg=1
,08-29 11:25:55.504  6934  6934 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 11:25:55.505  6934  6934 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:25:55.505  6934  6934 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:55.505  6934  6934 V BluetoothPbapReceiver: ***********state = 12
08-29 11:25:55.506  6934  6934 V BluetoothPbapService: Handler(): got msg=1
08-29 11:25:55.506  6934  6934 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 11:25:55.507  6210  6210 D BluetoothPbap: Proxy object connected
08-29 11:25:55.507  6210  6210 D PbapServerProfile: Bluetooth service connected
08-29 11:25:55.507  6934  7060 D BluetoothMapMasInstance: MAS initSocket()
08-29 11:25:55.508  6934  7060 D BluetoothMapMasInstance:   masId = 00
08-29 11:25:55.508  6934  7060 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 11:25:55.508  6934  7060 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 11:25:55.508  6934  7060 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 11:25:55.509  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:25:55.509  1031  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:55.509  2222  2222 D c       : Getting all permits...
08-29 11:25:55.509  2222  2222 D a       : Opening database...
08-29 11:25:55.510  6934  7062 V BluetoothPbapService: Pbap Service initSocket
08-29 11:25:55.511  6934  7060 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:55.511  2222  2222 D a       : Opening database auth.proximity.permit_store...
08-29 11:25:55.512  1031  1755 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:55.512  6934  7060 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 11:25:55.512  6934  7060 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 11:25:55.512  6934  6970 D BluetoothAdapterProperties: Scan Mode:21
08-29 11:25:55.512  6934  7060 D BluetoothMapMasInstance: Accepting socket connection...
08-29 11:25:55.512  6934  6970 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 11:25:55.514  2222  2222 D a       : Closing database...
08-29 11:25:55.514  6934  7062 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:55.515  6934  7062 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 11:25:55.515  6934  7062 V BluetoothPbapService: Succeed to create listening socket 
08-29 11:25:55.515  6934  7062 V BluetoothPbapService: Accepting socket connection...
,08-29 11:25:55.517  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:55.529  6210  6210 D BluetoothPermissionRequest: onReceive
,08-29 11:25:55.532  6210  6210 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 11:25:55.534  6210  6210 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:25:55.537  6934  6934 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 11:25:55.541  6934  6934 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-29 11:25:55.552  6934  6934 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 11:25:55.575  6934  6934 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 11:25:55.576  6934  6934 V BtOppService: onCreate
,08-29 11:25:55.581  6934  6934 V BluetoothOppNotification: send message
08-29 11:25:55.584  6934  6934 V BtOppService: Starting RfcommListener
08-29 11:25:55.591  6934  6934 D BluetoothOppPreference: Dumping Names:  
,08-29 11:25:55.591  6934  6934 D BluetoothOppPreference: {}
08-29 11:25:55.591  6934  6934 D BluetoothOppPreference: Dumping Channels:  
08-29 11:25:55.591  6934  6934 D BluetoothOppPreference: {}
08-29 11:25:55.592  6934  6934 V BtOppService: onStartCommand
08-29 11:25:55.594  6934  7069 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 11:25:55.596  6934  6934 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:55.597  6934  6934 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 11:25:55.599  6934  6934 V BluetoothOppNotification: new notify threadi!
08-29 11:25:55.600  6934  6934 V BluetoothOppNotification: send delay message
08-29 11:25:55.601  6934  6934 V BtOppService: start RfcommListener
08-29 11:25:55.604  6934  6934 V BtOppService: RfcommListener started
,08-29 11:25:55.609  6934  7071 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 11:25:55.609  1031  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:55.610  6934  7069 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:25:55.611  6934  7066 V BtOppService: Deleted complete outbound shares, number =  0
08-29 11:25:55.612  6934  7070 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 11:25:55.612  6934  7071 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:55.613  6934  7071 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-29 11:25:55.614  6934  7071 V BtOppRfcommListener: Started RFCOMM listener....
08-29 11:25:55.614  6934  7071 I BtOppRfcommListener: Accept thread started.
08-29 11:25:55.614  6934  7071 V BtOppRfcommListener: Accepting connection...
08-29 11:25:55.615  6934  7069 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@117e8677 on behalf of 
08-29 11:25:55.618  6934  7066 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 11:25:55.618  6934  7066 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 11:25:55.619  6934  7069 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 11:25:55.619  6934  7070 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36e1b2e4 on behalf of 
,08-29 11:25:55.619  6934  7069 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:25:55.620  6934  7070 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 11:25:55.620  6934  7066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22f2d34d on behalf of 
08-29 11:25:55.622  6934  7070 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 11:25:55.623  6934  7069 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18539e02 on behalf of 
08-29 11:25:55.625  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
,08-29 11:25:55.625  6934  7069 V BluetoothOppNotification: update too frequent, put in queue
08-29 11:25:55.625  6934  6934 V BluetoothFtpService: Ftp Service onCreate
08-29 11:25:55.625  6934  6934 I BluetoothFtpService: Ftp Service onCreate
08-29 11:25:55.625  6934  6934 V BluetoothFtpService: Ftp Service onStartCommand
08-29 11:25:55.626  6934  6934 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:55.626  6934  6934 V BluetoothFtpService: Starting Listening on sockets
08-29 11:25:55.626  6934  6934 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:25:55.626  6934  6934 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:25:55.626  6934  6934 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:25:55.626  6934  7070 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c791950 on behalf of 
08-29 11:25:55.626  6934  6934 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:55.626  6934  6934 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 11:25:55.627  6934  6934 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 11:25:55.628  6934  7070 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 11:25:55.630  6934  6934 V BtOppService: ContentObserver received notification
08-29 11:25:55.630  6934  6934 V BtOppService: ContentObserver received notification
08-29 11:25:55.630  6934  6934 V BluetoothFtpService: Handler(): got msg=1
08-29 11:25:55.630  6934  6934 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 11:25:55.631  6934  7069 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 11:25:55.631  6934  6934 V BluetoothFtpService: Ftp Service initSocket
08-29 11:25:55.631  6934  7069 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:25:55.632  6934  7070 V BluetoothOppNotification: outbound notification was removed.
08-29 11:25:55.633  6934  7070 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 11:25:55.633  6934  7069 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29265749 on behalf of 
08-29 11:25:55.634  6934  7069 V BluetoothOppNotification: update too frequent, put in queue
08-29 11:25:55.635  6934  7070 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f61984e on behalf of 
08-29 11:25:55.635  6934  7069 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 11:25:55.636  6934  7070 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 11:25:55.638  1031  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:25:55.638  6934  7070 V BluetoothOppNotification: inbound notification was removed.
08-29 11:25:55.639  6934  7070 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 11:25:55.640  6934  7070 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1349cd6f on behalf of 
08-29 11:25:55.640  6934  6934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:55.642  6934  6934 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-29 11:25:55.642  6934  6934 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 11:25:55.644  6934  7072 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 11:25:55.656  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30fde1cb
08-29 11:25:55.656  6934  6934 V BluetoothSapService: Sap Service onCreate
,08-29 11:25:55.658  6934  6934 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:55.658  6934  6934 V BluetoothSapService: state: 12
08-29 11:25:55.658  6934  6934 V BluetoothSapService: Starting SAP server process
08-29 11:25:55.661  6934  6934 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 11:25:55.655  7073  7073 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:55.655  7073  7073 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:55.662  6934  7074 V BluetoothSapService: Sap Service initRfcommSocket
08-29 11:25:55.663  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:55.664  6934  7074 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:55.664  6934  7074 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-29 11:25:55.665  6934  7074 V BluetoothSapService: Succeed to create listening socket 
08-29 11:25:55.665  6934  7074 V BluetoothSapService: Accepting socket connection...
08-29 11:25:55.674  7073  7073 V BT_SAP  : Event pipe created
08-29 11:25:55.674  7073  7073 V BT_SAP  : create_server_socket qcom.sap.server
08-29 11:25:55.674  7073  7073 V BT_SAP  : created socket fd 6
,08-29 11:25:56.011  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:56.011  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:56.011  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:56.011  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:56.011  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:56.011  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:56.011  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:56.011  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:56.017  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:56.018  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:56.019  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6f9921c added. We now have 8 listener(s)
08-29 11:25:56.019  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:56.022  1031  1047 D WifiServiceImplEx: setWifiEnabled: false pid=5966, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 11:25:56.022  1031  1047 D WifiService: setWifiEnabled: false pid=5966, uid=10118
08-29 11:25:56.022  1031  1047 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 11:25:56.027  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:56.032  1031  1955 D WifiServiceImplEx: setWifiEnabled: true pid=5966, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 11:25:56.032  1031  1955 D WifiService: setWifiEnabled: true pid=5966, uid=10118
08-29 11:25:56.032  1031  1955 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:25:56.061  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-29 11:25:56.061  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-29 11:25:56.061  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,08-29 11:25:56.063  1031  1535 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-29 11:25:56.063  1031  1535 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-29 11:25:56.064  1031  1535 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-29 11:25:56.064  1031  1535 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 11:25:56.064  1031  1535 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 11:25:56.064  1031  1535 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 11:25:56.064  1031  1535 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 11:25:56.064  1031  1535 E WifiHW  : unknown target_country: EU , set to default
08-29 11:25:56.064  1031  1535 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 11:25:56.064  1031  1535 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
,08-29 11:25:56.065  1031  1535 I WifiUtil: gEnableBmps=1,
08-29 11:25:56.603  6934  6934 V BluetoothOppNotification: new notify threadi!,
,08-29 11:25:56.630  6934  6934 V BluetoothOppNotification: send delay message
,08-29 11:25:56.646  6934  7093 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-29 11:25:56.670   309   890 D SoftapController: Softap fwReload - Ok
,08-29 11:25:56.751  1031  1535 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (681ms)
,08-29 11:25:56.766   309   890 D CommandListener: Setting iface cfg
08-29 11:25:56.767   309   890 D CommandListener: Trying to bring down wlan0
,08-29 11:25:56.768  1031  1093 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 11:25:56.768  1031  1093 D Tethering: InitialState.processMessage what=4
08-29 11:25:56.770   309  7107 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 11:25:56.770   309   890 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:25:56.772  1031  1091 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 11:25:56.775  6934  7093 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3dcfd18b on behalf of 
08-29 11:25:56.776  1031  1535 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 11:25:56.776  6934  7093 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 11:25:56.779  1031  1093 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 11:25:56.779  6934  7093 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 11:25:56.780  6934  7093 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fd6c268 on behalf of 
,08-29 11:25:56.775  7112  7112 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:56.775  7112  7112 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:56.782  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:56.782  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:25:56.782  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:25:56.782  6210  6210 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:25:56.783  6934  7093 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 11:25:56.786  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:25:56.788  6210  6210 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:25:56.788  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 11:25:56.788  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:25:56.788  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:25:56.788  6210  6210 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:25:56.788  6210  6210 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 11:25:56.791  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:56.791  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:25:56.791  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:25:56.791  6210  6210 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:25:56.793  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-29 11:25:56.795  6210  6210 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:25:56.796  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 11:25:56.796  6934  7093 V BluetoothOppNotification: outbound notification was removed.
08-29 11:25:56.796  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:25:56.796  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:25:56.796  6210  6210 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:25:56.796  6934  7093 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 11:25:56.796  6210  6210 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 11:25:56.798  6934  7093 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@221ca681 on behalf of 
08-29 11:25:56.799  6934  7093 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 11:25:56.800  6934  7093 V BluetoothOppNotification: inbound notification was removed.
08-29 11:25:56.800  6934  7093 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 11:25:56.801  6934  7093 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9b46326 on behalf of 
08-29 11:25:56.806  7112  7112 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 11:25:56.838  7112  7112 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 11:25:56.838  7112  7112 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 11:25:56.865  7112  7112 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 11:25:56.877  1031  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:25:56.877  1031  1535 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:25:56.877  1031  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:25:56.878  1031  1535 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 11:25:56.878  1031  1535 D WifiMonitor: connecting to supplicant
08-29 11:25:56.880  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 11:25:56.880  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:25:56.885  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:56.886  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 11:25:56.891  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:56.896  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:56.906  7112  7112 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 11:25:56.914  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 11:25:56.919  6296  7115 W FormManager: Network not available. Please check & try again.
08-29 11:25:56.919  7112  7112 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-29 11:25:56.921  1031  1535 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-29 11:25:56.922  1031  1535 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 11:25:56.922  1031  7117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 11:25:56.922  1031  7117 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 11:25:56.922  1031  1535 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 11:25:56.923  1031  1535 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 11:25:56.923  1031  1535 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:56.924  1031  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:56.924  1031  1535 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:56.925  1031  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:56.925  1031  1535 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 11:25:56.925  1031  1535 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 11:25:56.926  1031  1535 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,08-29 11:25:56.926  1031  1535 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 11:25:56.926  1031  1535 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 11:25:56.927  1031  1535 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:25:56.927  1031  1535 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:25:56.927  1031  1535 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:25:56.928  1031  1535 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 11:25:56.928  1031  1535 D WifiNative-wlan0: SET update_config 1: returned true
08-29 11:25:56.928  1031  1535 D WifiConfigStore: Loading config and enabling all networks 
08-29 11:25:56.929  1031  1535 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 11:25:56.929  1031  1535 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 11:25:56.929  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:56.930  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:56.930  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:56.930  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:56.930  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:25:56.930  1938  1938 D WfdService: Waiting for WifiP2p enabling
08-29 11:25:56.930  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:56.933  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 11:25:56.933  1031  1539 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 11:25:56.935  1031  1535 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 11:25:56.939  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:56.939  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:56.939  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:56.939  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:56.939  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:56.939  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:56.939  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:56.939  5966  5966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:56.941  5966  5966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:56.945  1031  1535 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 11:25:56.946  1031  1535 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 11:25:56.946  1031  1535 D WifiStateMachine: enableVerboseLogging : level 2
,08-29 11:25:56.946  1031  1535 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 11:25:56.947  1031  1535 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 11:25:56.947  1031  1535 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 11:25:56.947  1031  1535 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 11:25:56.947  1031  1535 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 11:25:56.948  1031  1535 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 11:25:56.948  1031  1535 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 11:25:56.948  7112  7112 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-29 11:25:56.949  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 11:25:56.949  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 11:25:56.949  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 11:25:56.949  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 11:25:56.949  1031  7117 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 11:25:56.950  1031  7117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 11:25:56.950  1031  1535 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 11:25:56.950  1031  1535 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 11:25:56.950  1031  1535 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 11:25:56.950  1031  1535 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 11:25:56.950  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:56.951  1031  1535 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 11:25:56.951  1031  1535 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 11:25:56.951  1031  1535 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 11:25:56.954  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:56.954  6296  7116 V FormManager: Network unavailable.
08-29 11:25:56.956  1031  1535 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 11:25:56.956  1031  1535 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 11:25:56.956  6296  7116 V FormManager: Network unavailable.
08-29 11:25:56.956  1031  1535 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 11:25:56.956  1031  1535 D WifiNative-HAL: Setting external_sim to 1
08-29 11:25:56.956  1031  1535 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 11:25:56.957  1031  1535 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 11:25:56.957  1031  1535 I WifiNative-HAL: startHal
08-29 11:25:56.957  1031  1535 D wifi    : setting scan oui 0x95278fe0
08-29 11:25:56.957  1031  1535 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 11:25:56.957  1031  1535 I WifiNative-HAL: startHal
08-29 11:25:56.958  1031  1535 D wifi    : setting scan oui 0x95278fe0
08-29 11:25:56.958  1031  1535 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 11:25:56.958  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:56.959  1031  1535 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 11:25:56.959  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 11:25:56.959  1938  1938 D WfdsService: Supplicant Connection state is changed : true
08-29 11:25:56.959  1938  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 11:25:56.959  1938  2334 D WfdsService: Set the WFDS Monitor: true
08-29 11:25:56.959  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 11:25:56.959  1938  2334 D WfdsMonitor: WfdsMonitorThread create
08-29 11:25:56.959  1938  2334 D WfdsMonitor: WFDS Monitor is created and started
08-29 11:25:56.959  1938  2334 D WfdsService: WiFi: Supplicant connection re-established
08-29 11:25:56.959  1031  1535 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 11:25:56.959  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 11:25:56.960  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 11:25:56.960  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 11:25:56.960  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 11:25:56.960  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
0,8-29 11:25:56.960  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 11:25:56.960  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 11:25:56.960  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 11:25:56.961  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 11:25:56.961  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 11:25:56.962  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 11:25:56.963  1938  7118 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 11:25:56.964  1938  7118 E CtrlSupplicant: Succeed to open control connection
08-29 11:25:56.964  1938  7118 E CtrlSupplicant: Succeed to open monitor connection
08-29 11:25:56.964  1938  7118 D WfdsMonitor: Supplicant connection established
08-29 11:25:56.965  1938  2334 D WfdsService: Connected to the supplicant for wfds
08-29 11:25:56.966  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 11:25:56.966  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 11:25:56.966  7112  7112 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 11:25:56.966  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 11:25:56.966  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 11:25:56.966  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 11:25:56.967  1031  1535 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 11:25:56.967  1031  1535 E WifiNative: : [137,267,097 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 11:25:56.968  1031  1535 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 11:25:56.968  1031  1535 D WifiNative-wlan0: RECONNECT: returned true
08-29 11:25:56.968  1031  1535 D WifiNative-wlan0: doString: [STATUS]
08-29 11:25:56.968  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 11:25:56.968  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 11:25:56.969  1031  1535 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 11:25:56.969  1031  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:25:56.969  1031  1535 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:25:56.969  1031  1533 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:56.969  6296  7120 V FormManager: Network unavailable.
08-29 11:25:56.971   309   890 D CommandListener: Setting iface cfg
08-29 11:25:56.971   309   890 D CommandListener: Trying to bring up p2p0
08-29 11:25:56.971  1031  1533 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 11:25:56.971  1031  1533 D LGWifiP2pService: P2pEnablingState
08-29 11:25:56.971  1031  1533 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:56.971  1031  1533 D LGWifiP2pService: P2p socket connection successful
08-29 11:25:56.971  1031  1533 D LGWifiP2pService: P2pEnabledState
08-29 11:25:56.971  1031  1533 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 11:25:56.973  6296  7120 V FormManager: Network unavailable.
08-29 11:25:56.974  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 11:25:56.974  1938  1938 D WfdsService: WifiP2pState is changed : true
08-29 11:25:56.974  1938  2334 D WfdsService: Receive the WFDS_ENABLE Method
08-29 11:25:56.974  1938  2334 D WfdsService: Set the WFDS Monitor: true
08-29 11:25:56.974  1938  2334 D WfdsService: Connected to the supplicant for wfds
08-29 11:25:56.974  1938  2334 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 11:25:56.974  7112  7112 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 11:25:56.975  1938  2334 D WfdsService: selectPreferredScanChannel [36]
08-29 11:25:56.975  1938  2334 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 11:25:56.975  6296  7119 W FormManager: Network not available. Please check & try again.
08-29 11:25:56.976  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:25:56.976  4234  4234 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:25:56.977  1031  1533 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 11:25:56.977  1031  1533 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 11:25:56.978  1031  1533 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 11:25:56.978  1031  1533 D WifiNative-p2p0: SET device_name G3: returned true
08-29 11:25:56.978  1031  1535 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 11:25:56.979  1031  1533 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 11:25:56.979  1031  1533 D LGWifiP2pService: before postfix = G3
08-29 11:25:56.979  1031  1533 D WifiServerServiceExt: postfix byte check : 2
08-29 11:25:56.979  1031  1533 D LGWifiP2pService: after postfix = G3
08-29 11:25:56.979  1031  1533 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 11:25:56.979  1031  1535 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 11:25:56.979  1031  1535 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 11:25:56.979  1031  1533 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 11:25:56.979  1031  1533 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 11:25:56.980  1031  1535 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 11:25:56.980  1031  1533 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 11:25:56.980  1031  1533 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 11:25:56.980  1031  1535 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 11:25:56.980  1031  1533 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 11:25:56.980  1031  1533 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 11:25:56.980  1031  1535 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 11:25:56.981  1031  1535 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 11:25:56.981  1031  1533 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 11:25:56.981  1031  1533 D WifiNative-HAL: p2pGetDeviceAddress
08-29 11:25:56.981  1031  1535 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 11:25:56.981  7112  7112 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 11:25:56.981  1031  1533 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-29 11:25:56.981  1031  1535 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 11:25:56.981  1031  1533 D LGWifiP2pService: DeviceAddress: 
08-29 11:25:56.982  1031  1533 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 11:25:56.982  1031  1535 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 11:25:56.982  1031  1535 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 11:25:56.982  1031  1535 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 11:25:56.982  1031  1533 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 11:25:56.982  1031  1533 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 11:25:56.982  7112  7112 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 11:25:56.982  1031  1533 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 11:25:56.983  1031  1533 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 11:25:56.983  1031  1533 D WifiNative-p2p0:    returned OK
08-29 11:25:56.983  1031  1533 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 11:25:56.983  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:25:56.985  1031  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=137285  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 11:25:56.987  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=137287  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 11:25:56.988  4234  4234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:25:56.988  1031  1535 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 11:25:56.988  1031  1535 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 11:25:56.988  1031  1535 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 11:25:56.988  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-29 11:25:56.990  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 11:25:56.990  1031  1031 D RttService: SCAN_AVAILABLE : 3
08-29 11:25:56.990  1031  1552 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:56.990  1031  1552 I WifiNative-HAL: startHal
08-29 11:25:56.992  1031  1553 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:56.992  1938  1938 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 11:25:56.993  1938  1938 D WfdsService: isConnected: false
08-29 11:25:56.993  1938  1938 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 11:25:56.993  1938  1938 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 11:25:56.993  1938  1938 D WfdsService: Update P2p Interface State: 3
08-29 11:25:56.994  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:56.994  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:56.995  4234  7121 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 11:25:56.995  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:56.995  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:56.995  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:56.995  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 11:25:57.000  4234  7122 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:25:57.000  4234  7122 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:25:57.007  1031  1533 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 11:25:57.007  1031  1533 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 11:25:57.009  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 11:25:57.009  7112  7112 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:57.009  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:25:57.009  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:57.010  1031  7117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:57.010  1031  7117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:57.010  7112  7112 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 11:25:57.010  7112  7112 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.010  1031  7117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:57.010  1938  7118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:57.010  1031  7117 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.010  1031  7117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.010  1031  7117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.010  1031  1535 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 11:25:57.011  7112  7112 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.011  1031  7117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:57.011  1031  7117 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.011  1031  7117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.011  1031  7117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.011  1031  1535 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:25:57.011  1031  1535 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:25:57.011  1031  1535 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:25:57.011  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 11:25:57.012  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 11:25:57.012  7112  7112 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:25:57.012  1938  7118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:57.012  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 11:25:57.012  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:25:57.012  1031  7117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:25:57.012  1031  7117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:25:57.013  1031  1535 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 11:25:57.013  1031  1535 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 11:25:57.013  1031  1552 D wifi    : getting scan capabilities on interface[1] = 0x95278fe0
08-29 11:25:57.013  1031  1552 D wifi    : failed to get capabilities : -3
08-29 11:25:57.013  1031  1552 E WifiScanningService: could not get scan capabilities
08-29 11:25:57.013  1031  1535 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 11:25:57.013  1031  1535 D WifiNative-wlan0: doBoolean: SCAN
08-29 11:25:57.013  1031  1535 D WifiNative-wlan0: SCAN: returned false
08-29 11:25:57.014  1031  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=137314  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 11:25:57.025  1031  1956 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7123 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 11:25:57.028  1031  1533 D LGWifiP2pService: InactiveState
,08-29 11:25:57.028  1031  1533 D LGWifiP2pService: InactiveState{ when=-46ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.028  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-46ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.028  1031  1533 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 11:25:57.029  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 11:25:57.029  7112  7112 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:57.030  1031  7117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:25:57.030  7112  7112 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 11:25:57.030  1031  7117 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:57.030  1031  7117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:57.030  1031  7117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:25:57.030  7112  7112 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.031  1031  1533 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 11:25:57.031  7112  7112 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:25:57.031  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.031  1031  1031 E WifiServerServiceExt: No p2p device connected
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.031  1938  7118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:25:57.031  1938  7118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.031  1938  7118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:57.031  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.032  1031  1533 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.032  1031  7117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:57.032  1031  7117 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.032  1031  7117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.032  1031  7117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.032  1031  7117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:25:57.032  1031  7117 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.032  1031  7117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.032  1031  7117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:25:57.032  1938  2334 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 11:25:57.032  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=137329  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 11:25:57.033  1031  1535 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:25:57.033  1031  1535 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:25:57.034  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:57.034  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:57.034  1031  1535 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:25:57.034  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:57.035  1031  1535 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:25:57.035  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.035  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.035  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 11:25:57.035  1031  1535 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=,UNKNOWN/IDLE
08-29 11:25:57.036  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:57.036  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 11:25:57.036  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:57.036  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-29 11:25:57.076  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-29 11:25:57.076  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:57.076  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:57.076  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:57.076  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:57.076  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:57.076  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
08-29 11:25:57.076  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:57.078  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:57.083  5966  6027 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 11:25:57.084  5966  6027 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 11:25:57.086  5966  6027 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@19b5963e Bundle[{}]
08-29 11:25:57.086  5966  6027 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 11:25:57.087  5966  6027 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 11:25:57.087  5966  6027 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 11:25:57.089  5966  6027 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 11:25:57.089  5966  6027 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 11:25:57.090  5966  6027 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 11:25:57.096  5966  6027 I System.out: Running OutgoingSocketThread
08-29 11:25:57.099  5966  7140 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 766)
08-29 11:25:57.102  5966  7140 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60103
08-29 11:25:57.103  5966  7140 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 11:25:57.104  7123  7123 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 11:25:57.105  7123  7123 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-29 11:25:57.112  7123  7123 V [BNRBootReceiver]: Boot Receiver Return
08-29 11:25:57.113  7123  7123 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 11:25:57.115  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:25:57.124  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:57.129  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 11:25:57.136  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:25:57.139  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:25:57.142  6256  6256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:25:57.150  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:25:57.162  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:57.170  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:57.178  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:57.179  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:57.180  6256  6256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 11:25:57.183  1031  1755 I ActivityManager: Killing 6569:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-29 11:25:57.211  1031  1046 W libprocessgroup: failed to open /acct/uid_10011/pid_6569/cgroup.procs: No such file or directory
,08-29 11:25:57.654  7112  7112 E wpa_supplicant: USIM:  scard_init function
,08-29 11:25:57.655  7112  7112 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-29 11:25:57.665  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 11:25:57.665  1031  7117 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 11:25:57.665  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 11:25:57.666  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: WPS-AP-AVAILABLE 
08-29 11:25:57.666  1031  7117 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 11:25:57.672  1031  1535 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-29 11:25:57.672  1031  1535 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-29 11:25:57.672  1031  1535 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-29 11:25:57.673  1031  1535 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-29 11:25:57.673  1031  1535 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 11:25:57.678  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 11:25:57.678  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-29 11:25:57.696  1031  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=137996  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 11:25:57.705  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:57.706  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:57.708  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:57.713  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.713  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.713  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-29 11:25:57.720  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=138020  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 11:25:57.722  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:57.722  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 11:25:57.725  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-29 11:25:57.732  6210  6210 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 11:25:57.740  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:25:57.750  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:57.762  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:57.769  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:57.770  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:57.770  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 11:25:57.791  7112  7112 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 11:25:57.798  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 11:25:57.798  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 11:25:57.798  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 11:25:57.800  7112  7112 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:25:57.800  7112  7112 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:25:57.803  1031  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=138103  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 11:25:57.804  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=138103  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 11:25:57.806  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 11:25:57.806  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:25:57.806  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:25:57.807  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:25:57.807  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:25:57.807  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,08-29 11:25:57.818  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:57.818  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 11:25:57.818  1031  1535 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138118
08-29 11:25:57.819  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 11:25:57.819  1031  1535 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138119
08-29 11:25:57.819  1031  7117 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:25:57.819  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,08-29 11:25:57.820  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:25:57.820  1031  7117 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:25:57.820  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:25:57.820  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:25:57.820  1031  1535 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138120
,08-29 11:25:57.822  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138121
08-29 11:25:57.822  1031  1093 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 11:25:57.823  1031  1535 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138123
08-29 11:25:57.824  1031  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=138124  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 11:25:57.826  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:57.829  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:57.829  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:57.830  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.830  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.830  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 11:25:57.831  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=138131  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 11:25:57.831  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:25:57.831  6210  6210 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:25:57.831  6210  6210 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:25:57.832  1031  1535 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=138131  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 11:25:57.832  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:57.832  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=138132  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 11:25:57.833  1031  1535 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138133
08-29 11:25:57.833  1031  1535 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138133
08-29 11:25:57.834  1031  1535 D WifiNative-wlan0: doString: [STATUS]
08-29 11:25:57.834  1031  7117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:25:57.834  1031  7117 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-29 11:25:57.839  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:25:57.840  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.840  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.840  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 11:25:57.840  1031  1535 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 11:25:57.842  6210  6210 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:25:57.842  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 11:25:57.842  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:25:57.842  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:25:57.842  6210  6210 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:25:57.842  1031  1535 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 11:25:57.842  6210  6210 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 11:25:57.842  6210  6210 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 11:25:57.845  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:57.852  1031  1535 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 11:25:57.852  1031  1535 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 11:25:57.853  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:57.853  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 11:25:57.854  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:57.858  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.858  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.858  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 11:25:57.861  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.861  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.861  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 11:25:57.862  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:57.867  1031  1535 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 11:25:57.868  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:57.868  1031  1541 D ConnectivityService: Got NetworkAgent Messenger
08-29 11:25:57.868  1031  1541 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 11:25:57.868  1031  1541 D ConnectivityService: NetworkAgent connected
08-29 11:25:57.868  1031  1535 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:25:57.868  1031  1535 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 11:25:57.869  1031  1535 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 11:25:57.869  1031  1535 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 11:25:57.874  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:57.874  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:57.874  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:25:57.874  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:57.875  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:57.876  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:57.877  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:57.878  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:57.878  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 11:25:57.879  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:57.881  1031  1535 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 11:25:57.881  1031  1535 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:25:57.881  1031  1535 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 11:25:57.881  1031  1535 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 11:25:57.882  1031  1535 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 11:25:57.883  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 11:25:57.888  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:57.888  1031  1535 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 11:25:57.889   309   890 D CommandListener: Setting iface cfg
08-29 11:25:57.894  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:57.894  1031  1535 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 11:25:57.894  1031  7170 D DhcpStateMachine: StoppedState
08-29 11:25:57.894  1031  7170 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.894  1031  7170 D DhcpStateMachine: WaitBeforeStartState
08-29 11:25:57.895  1031  1535 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=138195  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-29 11:25:57.895  1031  1535 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=138195  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:25:57.896  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=138196  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:25:57.897  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:57.897  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:57.897  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:57.897  1031  1535 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:57.898  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:25:57.898  1031  1535 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:57.898  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:57.899  1031  1535 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:25:57.900  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:57.900  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 11:25:57.901  1031  1535 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138201  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:25:57.901  1031  1535 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138201  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:25:57.902  1031  1535 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138202  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:25:57.902  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:57.902  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14226] from screen [on:0 period:-711024626] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 11:25:57.903  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-711024625] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 11:25:57.903  1031  1535 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 11:25:57.904  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:57.904  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 11:25:57.907  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:25:57.909  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:57.909  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:57.910  1031  1535 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:57.910  1031  1535 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:57.910  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:57.910  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 11:25:57.911  1031  1541 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-29 11:25:57.911  1031  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:57.911  1031  1541 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 11:25:57.912  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=4,0,0
08-29 11:25:57.912  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=4,0,0
08-29 11:25:57.912  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 11:25:57.912  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 11:25:57.913  1031  1535 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 11:25:57.913  1031  1535 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 11:25:57.913  1031  1535 D WifiNative-wlan0: SET ps 0: returned true
08-29 11:25:57.913  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 11:25:57.913  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 11:25:57.914  1031  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 11:25:57.914  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2497fe5a target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.914  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2497fe5a target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.914  1031  1535 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 11:25:57.914  1031  1535 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 11:25:57.914  1031  1535 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 11:25:57.914  1031  7170 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.915  1031  7170 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 11:25:57.915   309   890 D CommandListener: Setting iface cfg
08-29 11:25:57.915  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:57.916   309   890 D CommandListener: Trying to bring up wlan0
08-29 11:25:57.916  1031  1535 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 11:25:57.918  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:57.918  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 11:25:57.918  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:25:57.918  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 11:25:57.918  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:57.919  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 11:25:57.919  1031  1535 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:57.920  1031  1535 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:57.920  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:57.920  1031  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:25:57.921  1031  1541 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 11:25:57.921  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:57.921  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:57.921  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 11:25:57.922  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:25:57.922  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 11:25:57.922  1031  1533 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.922  1031  1533 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.922  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 11:25:57.922  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 11:25:57.923  1031  1535 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 11:25:57.923  1031  1535 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 11:25:57.923  7112  7112 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 11:25:57.923  1031  1535 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 11:25:57.923  1031  1535 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:25:57.925  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:57.931  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:57.934  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:57.939  1031  1535 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:25:57.939  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:57.939  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:57.939  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:25:57.939  1031  1541 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 11:25:57.939  1031  1535 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 11:25:57.940  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-29 11:25:57.940  1031  1535 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 11:25:57.940  1031  1541 D ConnectivityService: ignoring duplicate network state non-change
08-29 11:25:57.945  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:57.945  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:57.945  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.946  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.946  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 11:25:57.946  1031  1541 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 11:25:57.946  1031  1541 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 11:25:57.947  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:57.949  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:57.949  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:25:57.950  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:57.953  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.954  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.954  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 11:25:57.957  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:25:57.960  1031  1535 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 11:25:57.961  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 11:25:57.962  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.963  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.963  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 11:25:57.963  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 11:25:57.963  1938  1938 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-29 11:25:57.969  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:57.969  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.969  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:57.969  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 11:25:57.969  1598  1598 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 11:25:57.970  1031  1541 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 11:25:57.970  1031  1541 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-29 11:25:57.970  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:57.971  1031  1541 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 11:25:57.972   309   890 E Netd    : netlink response contains error (File exists)
08-29 11:25:57.972  1031  1541 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 11:25:57.973  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:57.973  1598  1598 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 11:25:57.973  1031  1541 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 11:25:57.973  1031  1541 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-29 11:25:57.973  1031  1541 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-29 11:25:57.973  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:57.975  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 11:25:57.975  1031  1541 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 11:25:57.976  1031  1541 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 11:25:57.976  1031  1541 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 11:25:57.976  1031  1541 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 11:25:57.976  1031  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.976  1031  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 11:25:57.976  1031  1541 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:25:57.976  1031  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:57.976  1031  1541 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:25:57.976  1031  1541 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 11:25:57.976  1031  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-29 11:25:57.976  1031  1541 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:57.978  1031  1541 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 11:25:57.978  1031  1541 D ConnectivityService: currentScore = 0, newScore = 20
08-29 11:25:57.978  1031  1541 D ConnectivityService:    accepting network in place of null
08-29 11:25:57.978  1031  1541 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:57.978  1031  1535 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:57.978  1031  1535 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:25:57.979   309  7175 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 11:25:57.979  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:57.980  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 11:25:57.980  1031  1541 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 11:25:57.980  1031  1541 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 11:25:57.980  1031  1541 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 11:25:57.981  1031  1541 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:25:57.981  1031  1541 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 11:25:57.981  1031  1541 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 11:25:57.982  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 11:25:57.982  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
,08-29 11:25:57.982  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,08-29 11:25:57.982  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 11:25:57.985   309  7176 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 11:25:57.985   309  7176 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-29 11:25:57.986  1031  1541 D ConnectivityService: validation of new default Network = false
08-29 11:25:57.986  1031  1541 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 11:25:57.986  1031  1541 D DSQN    : enableDataServiceNotify 
08-29 11:25:57.986  1031  1541 D DSQN    : start dsqn bin
08-29 11:25:57.993  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:57.995  1031  1541 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 11:25:57.995  1031  1541 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:57.996  1031  1541 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:25:57.996  1031  1541 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:25:57.985  7178  7178 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:57.985  7178  7178 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 11:25:57.998  1598  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 11:25:58.003  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:58.003  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:58.004  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:25:58.009  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:58.011  1815  7177 I CheckinService: active receiver: enabled
,08-29 11:25:58.013  7178  7178 E DSQN    : DSQN ssw
08-29 11:25:58.022  1815  7177 I CheckinService: Preparing to send checkin request
08-29 11:25:58.022  1815  7177 I EventLogService: Accumulating logs since 1472461756854
08-29 11:25:58.023  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:58.029  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:58.032  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 11:25:58.033  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:58.034  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:25:58.034  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:58.035  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:58.035  6256  6256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 11:25:58.038  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:25:58.041  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 11:25:58.041  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:58.043  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:25:58.047  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:58.052  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:58.052  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:58.053  6256  6256 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 11:25:58.053  6256  6256 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 11:25:58.054  6256  6256 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 11:25:58.058  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:25:58.061  6192  6192 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 11:25:58.062  6192  6192 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:25:58.065  6210  6210 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 11:25:58.071  6210  6210 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:25:58.079  6256  6256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:25:58.079  6256  6256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:25:58.080  6256  6256 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 11:25:58.080  6256  6256 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-29 11:25:58.081  6256  6256 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-29 11:25:58.091  1815  7177 W EventLogAggregator: Unknown tag: snet_gcore
08-29 11:25:58.091  1815  7177 W EventLogAggregator: Unknown tag: snet_launch_service
08-29 11:25:58.097  5966  6027 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 767)
08-29 11:25:58.098  5966  6027 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 767)
08-29 11:25:58.102  5966  6027 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 772)
08-29 11:25:58.104  5966  6027 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 11:25:58.104  5966  6027 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 773)
,08-29 11:25:58.108  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:58.109  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@206fee25 added. We now have 2 listener(s)
08-29 11:25:58.109  1031  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:58.113  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:25:58.113  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:58.113  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:58.113  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:58.114  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fd5dbfa added. We now have 9 listener(s)
08-29 11:25:58.114  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:58.114  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:25:58.118  1031  7170 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 11:25:58.120  1031  7170 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 11:25:58.120  1031  7170 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 11:25:58.121  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:25:58.125  7183  7183 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:58.125  7183  7183 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:25:58.136  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:58.136  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:58.136  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:58.136  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:58.136  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:58.136  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:58.136  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:58.136  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:25:58.138  7183  7183 I dhcpcd  : version 5.5.6 starting
08-29 11:25:58.139  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:58.139  5966  6027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:58.140  7183  7183 E dhcpcd  : get_duid: m
,08-29 11:25:58.140  7183  7183 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 11:25:58.140  7183  7183 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 11:25:58.140  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:58.143  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:58.145  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@111bb408 added. We now have 3 listener(s)
08-29 11:25:58.145  1031  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:58.146  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:58.148  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:25:58.148  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:58.148  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:58.148  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:58.149  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fd647a1 added. We now have 10 listener(s)
08-29 11:25:58.149  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:58.149  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:58.149  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:58.149  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:58.149  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:58.149  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.149  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:58.149  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:58.149  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@206fee25 removed from the list
08-29 11:25:58.149  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.149  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fd5dbfa removed from the list
08-29 11:25:58.149  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:58.149  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.150  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.150  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMa,nager: release: 1 listener(s) left
08-29 11:25:58.151  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:58.151  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:58.151  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.151  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fd5dbfa not in the list
08-29 11:25:58.151  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.151  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:58.152  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:58.152  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:58.152  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.152  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fd647a1 removed from the list
08-29 11:25:58.152  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:58.152  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.152  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.152  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:58.152  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@111bb408 removed from the list
08-29 11:25:58.153  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:58.153  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f95bdc6 added. We now have 2 listener(s)
08-29 11:25:58.154  1031  1588 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:58.157  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:25:58.157  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:58.157  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:58.157  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:58.158  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fb85187 added. We now have 9 listener(s)
08-29 11:25:58.158  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:58.158  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:25:58.161  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:58.166  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:58.166  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:58.166  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:58.166  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:58.166  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:58.166  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:58.166  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:58.166  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:25:58.169  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:58.169  5966  6027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:58.169  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:58.169  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ceebcdd added. We now have 3 listener(s)
08-29 11:25:58.170  1031  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:58.173  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:25:58.173  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:58.173  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:58.173  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:58.173  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f1ff052 added. We now have 10 listener(s)
08-29 11:25:58.173  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:58.173  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:58.173  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:58.173  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:25:58.173  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:58.173  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:25:58.173  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:58.178  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 11:25:58.178  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:58.178  1031  1588 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:25:58.184  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 11:25:58.186  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 11:25:58.187  1815  7177 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-29 11:25:58.188  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:25:58.188  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:58.190  5966  6027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 11:25:58.190  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:58.190  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:58.192  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:58.192  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:25:58.192  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:58.193  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:58.193  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.193  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:58.193  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:58.193  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f95bdc6 removed from the list
08-29 11:25:58.193  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.193  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fb85187 removed from the list
08-29 11:25:58.193  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:58.193  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.194  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.194  1031  1540 D WifiService: New client listening to asynchronous messages
08-29 11:25:58.194  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.195  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:58.195  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:58.195  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.195  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fb85187 not in the list
08-29 11:25:58.195  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.195  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.198  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:25:58.203  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:58.203  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:58.203  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:58.203  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.203  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f1ff052 removed from the list
08-29 11:25:58.203  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:58.203  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.203  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.203  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:25:58.203  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ceebcdd removed from the list
08-29 11:25:58.204  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:58.204  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@351f49d9 added. We now have 2 listener(s)
08-29 11:25:58.205  1031  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:25:58.209  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:25:58.209  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:58.210  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:58.210  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:25:58.210  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da8bf9e added. We now have 9 listener(s)
08-29 11:25:58.210  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:58.210  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:25:58.212  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:58.216  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:58.216  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:58.216  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:58.216  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:58.216  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:58.216  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:58.216  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:58.216  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:25:58.216  7183  7183 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 11:25:58.216  7183  7183 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 11:25:58.216  7183  7183 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 11:25:58.216  7183  7183 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 11:25:58.217  7183  7183 D dhcpcd  : wlan0: sending REQUEST (xid 0x5d43b4a9), next in 4.47 seconds
08-29 11:25:58.217  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:58.217  5966  6027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:58.217  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:58.218  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f53ba4c added. We now have 3 listener(s)
08-29 11:25:58.218  1031  2008 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:25:58.220  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:58.220  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:25:58.220  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:25:58.220  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:58.220  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:58.221  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c31aa95 added. We now have 10 listener(s)
08-29 11:25:58.221  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:58.221  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:58.221  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:58.221  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:58.221  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:25:58.221  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:58.221  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:25:58.221  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:58.224  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 11:25:58.224  1031  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:58.228  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 11:25:58.229  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 11:25:58.230  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:25:58.230  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:25:58.232  5966  6027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 11:25:58.232  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:58.233  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:58.233  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:58.233  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:58.233  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.233  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:58.233  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:58.233  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@351f49d9 removed from the list
08-29 11:25:58.233  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.233  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da8bf9e removed from the list
08-29 11:25:58.233  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:58.233  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.233  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.234  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.236  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:58.236  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:58.236  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.236  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da8bf9e not in the list
08-29 11:25:58.236  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.236  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.237  7183  7183 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-29 11:25:58.238  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:58.239  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:58.239  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:58.239  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:58.239  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.239  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c31aa95 removed from the list
08-29 11:25:58.239  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:58.239  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoot,hManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.239  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.239  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:58.239  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f53ba4c removed from the list
08-29 11:25:58.240  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:58.240  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a282f38 added. We now have 2 listener(s)
08-29 11:25:58.241  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:58.243  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:25:58.243  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:58.243  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:58.243  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:58.243  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ecf5b11 added. We now have 9 listener(s)
08-29 11:25:58.243  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:58.244  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:25:58.247  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:58.251  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:58.251  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:58.251  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:58.251  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:58.251  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:58.251  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:58.251  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:58.251  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:25:58.253  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:58.253  5966  6027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:58.253  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:58.253  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3672aa77 added. We now have 3 listener(s)
08-29 11:25:58.253  1031  1955 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:58.256  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:25:58.256  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:25:58.256  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:58.256  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:58.256  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dcd06e4 added. We now have 10 listener(s)
08-29 11:25:58.256  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:58.256  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:58.256  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:58.256  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 11:25:58.256  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:58.256  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:58.256  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:25:58.257  7183  7183 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 11:25:58.257  7183  7183 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 11:25:58.257  7183  7183 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 11:25:58.258  7183  7183 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 11:25:58.258  7183  7183 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 11:25:58.258  7183  7183 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 11:25:58.258  7183  7183 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 11:25:58.258  7183  7183 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-29 11:25:58.260  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:58.263  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:25:58.264  1031  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:58.271  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 11:25:58.272  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:25:58.278  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:25:58.278  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:58.280  5966  6027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 11:25:58.282  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:58.282  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:58.282  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:58.282  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:58.282  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.282  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:58.282  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:58.282  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a282f38 removed from the list
08-29 11:25:58.282  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:25:58.282  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ecf5b11 removed from the list
08-29 11:25:58.282  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:58.283  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.283  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.283  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.284  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:58.284  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:58.284  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:25:58.284  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ecf5b11 not in the list
08-29 11:25:58.284  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.284  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.286  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:25:58.289  5966  6027 D BluetoothLeScanner: could not find callback wrapper
08-29 11:25:58.289  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 11:25:58.289  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:58.289  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.289  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dcd06e4 removed from the list
08-29 11:25:58.289  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:58.289  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.289  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.290  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:58.290  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3672aa77 removed from the list
08-29 11:25:58.290  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:58.290  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375d7713 added. We now have 2 listener(s)
08-29 11:25:58.291  1031  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:25:58.293  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:25:58.293  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:58.293  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:58.293  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:58.293  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c5ad50 added. We now have 9 listener(s)
08-29 11:25:58.293  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:58.294  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:25:58.297  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:58.300  5966  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:58.300  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:58.300  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:25:58.300  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:58.300  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:58.300  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:58.300  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:58.300  5966  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:25:58.308  5966  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:58.308  5966  6027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:58.308  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:58.308  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13d24c4e added. We now have 3 listener(s)
08-29 11:25:58.313  1031  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:25:58.314  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:58.315  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:25:58.315  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:58.315  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:58.316  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:58.316  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@161e716f added. We now have 10 listener(s)
08-29 11:25:58.316  5966  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:58.316  5966  5966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:58.316  5966  6027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:58.316  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:58.316  5966  6027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:58.316  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:58.317  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.317  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:58.317  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:58.317  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375d7713 removed from the list
08-29 11:25:58.317  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.317  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c5ad50 removed from the list
08-29 11:25:58.317  5966  6027 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:58.317  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.317  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.317  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.318  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:58.318  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:58.318  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.318  5966  6027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c5ad50 not in the list
08-29 11:25:58.318  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given liste,ner does not exist in the list - probably already removed
08-29 11:25:58.318  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.319  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:58.319  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:58.319  5966  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:58.319  5966  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@161e716f removed from the list
08-29 11:25:58.319  5966  6027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:58.319  5966  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:58.319  5966  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:58.320  5966  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:58.320  5966  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13d24c4e removed from the list
08-29 11:25:58.322  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 11:25:58.322  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 11:25:58.322  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 11:25:58.322  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:25:58.323  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 11:25:58.323  5966  6027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:58.335  5966  7197 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 780, name: My test thread name)
08-29 11:25:58.335  5966  7197 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 780, thread name: My test thread name)
08-29 11:25:58.335  5966  7197 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 780, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 11:25:58.339  5966  7199 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 782, name: My test thread name)
08-29 11:25:58.339  5966  7199 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 782, thread name: My test thread name)
08-29 11:25:58.340  5966  7199 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 782, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 11:25:58.342  5966  6027 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 11:25:58.342  5966  6027 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 11:25:58.342  5966  6027 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 11:25:58.342  5966  6027 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 11:25:58.343  5966  6027 D com.test.thalitest.ThaliTestRunner: Total duration: 22784 ms
08-29 11:25:58.344  5966  6027 I jxcore-log: Total number of executed tests:  80
08-29 11:25:58.344  5966  6027 I jxcore-log: 
08-29 11:25:58.344  5966  6027 I jxcore-log: Number of passed tests:  80
08-29 11:25:58.344  5966  6027 I jxcore-log: 
08-29 11:25:58.344  5966  6027 I jxcore-log: Number of failed tests:  0
08-29 11:25:58.344  5966  6027 I jxcore-log: 
08-29 11:25:58.345  5966  6027 I jxcore-log: Number of ignored tests:  0
08-29 11:25:58.345  5966  6027 I jxcore-log: 
08-29 11:25:58.345  5966  6027 I jxcore-log: Total duration:  22784
08-29 11:25:58.345  5966  6027 I jxcore-log: 
08-29 11:25:58.346  5966  6027 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 11:25:58.346  5966  6027 I jxcore-log: 
08-29 11:25:58.351  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:58.351  5966  6027 I jxcore-log: 
08-29 11:25:58.354  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:58.354  5966  6027 I jxcore-log: 
08-29 11:25:58.356  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:58.356  5966  6027 I jxcore-log: 
,08-29 11:25:58.357  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:58.357  5966  6027 I jxcore-log: 
08-29 11:25:58.358  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:58.358  5966  6027 I jxcore-log: 
08-29 11:25:58.360  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:25:58.360  5966  6027 I jxcore-log: 
08-29 11:25:58.363  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:58.363  5966  6027 I jxcore-log: 
08-29 11:25:58.366  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:58.366  5966  6027 I jxcore-log: 
08-29 11:25:58.367  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:25:58.367  5966  6027 I jxcore-log: 
,08-29 11:25:58.368  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:25:58.368  5966  6027 I jxcore-log: 
,08-29 11:25:58.370  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:25:58.370  5966  6027 I jxcore-log: 
08-29 11:25:58.371  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:58.371  5966  6027 I jxcore-log: 
08-29 11:25:58.372  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:58.372  5966  6027 I jxcore-log: 
08-29 11:25:58.373  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:25:58.373  5966  6027 I jxcore-log: 
08-29 11:25:58.374  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:25:58.374  5966  6027 I jxcore-log: 
08-29 11:25:58.374  5966  5966 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 11:25:58.375  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:58.375  5966  6027 I jxcore-log: 
08-29 11:25:58.376  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:58.376  5966  6027 I jxcore-log: 
08-29 11:25:58.377  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:25:58.377  5966  6027 I jxcore-log: 
08-29 11:25:58.378  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:25:58.378  5966  6027 I jxcore-log: 
08-29 11:25:58.379  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:58.379  5966  6027 I jxcore-log: 
08-29 11:25:58.380  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:58.380  5966  6027 I jxcore-log: 
08-29 11:25:58.381  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:58.381  5966  6027 I jxcore-log: 
08-29 11:25:58.382  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:58.382  5966  6027 I jxcore-log: 
08-29 11:25:58.383  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:58.383  5966  6027 I jxcore-log: 
08-29 11:25:58.384  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:58.384  5966  6027 I jxcore-log: 
08-29 11:25:58.385  5966  6027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:58.385  5966  6027 I jxcore-log: 
08-29 11:25:58.391  1031  1919 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService,: pid=7204 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-29 11:25:58.444  7204  7204 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 11:25:58.444  7204  7204 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 11:25:58.466  7204  7204 I MultiDex: VM with version 2.1.0 has multidex support
08-29 11:25:58.466  7204  7204 I MultiDex: install
08-29 11:25:58.466  7204  7204 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 11:25:58.475  7204  7204 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-29 11:25:58.480  2222  2222 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-29 11:25:58.492  2222  2222 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-29 11:25:58.493  2222  2222 D c       : Getting all permits...
08-29 11:25:58.493  2222  2222 D a       : Opening database...
08-29 11:25:58.498  2222  2222 D a       : Opening database auth.proximity.permit_store...
08-29 11:25:58.499  2222  2222 D a       : Closing database...
08-29 11:25:58.528  1031  7170 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-29 11:25:58.529  1031  7170 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 11:25:58.529  1031  7170 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 11:25:58.529  1031  7170 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 11:25:58.529  1031  7170 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 11:25:58.529  1031  7170 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 11:25:58.529  1031  7170 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 11:25:58.529  1031  7170 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 11:25:58.530  1031  7170 D DhcpStateMachine: RunningState
08-29 11:25:58.584  7226  7226 D AndroidRuntime: 
08-29 11:25:58.584  7226  7226 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 11:25:58.586  7226  7226 D AndroidRuntime: CheckJNI is OFF
,08-29 11:25:58.759  7226  7226 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 11:25:58.780  1031  1089 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-29 11:25:58.781  1031  1089 I ActivityManager: Killing 5966:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-29 11:25:58.823  1031  1955 I WindowState: WIN DEATH: Window{38011379 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 11:25:58.823  1031  1540 D WifiService: Client connection lost with reason: 4
,08-29 11:25:58.831  1031  1955 D InputDispatcher: Window went away: Window{38011379 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 11:25:59.041  1031  1089 I ActivityManager:   Force finishing activity ActivityRecord{1acfc76a u0 com.test.thalitest/.MainActivity t6}
,08-29 11:25:59.064   339   345 E GBMv2   : DFP En is all cleared set to be enabled
08-29 11:25:59.065  1031  1099 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-29 11:25:59.066  1031  1099 I ActivityManager:   Force finishing activity ActivityRecord{1acfc76a u0 com.test.thalitest/.MainActivity t6 f}
08-29 11:25:59.067  1031  1099 W ActivityManager: Duplicate finish request for ActivityRecord{1acfc76a u0 com.test.thalitest/.MainActivity t6 f}
08-29 11:25:59.070  7204  7222 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 11:25:59.071  7204  7222 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:25:59.093  1031  2008 W ActivityManager: Spurious death for ProcessRecord{197886b 5966:com.test.thalitest/u0a118}, curProc for 5966: null
08-29 11:25:59.094  1938  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-29 11:25:59.094  1938  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18ec0a3f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-29 11:25:59.096  2030  2030 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-29 11:25:59.096  1938  2292 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-29 11:25:59.097  1938  2292 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3359bf0c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 11:25:59.098  2030  2030 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-29 11:25:59.106  1598  1598 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-29 11:25:59.112  2501  2671 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 11:25:59.114  6934  6934 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-29 11:25:59.114  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 11:25:59.115  1992  1992 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-29 11:25:59.115  2712  2712 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-29 11:25:59.118  4381  4381 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-29 11:25:59.119  4381  4381 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-29 11:25:59.119  4381  4381 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-29 11:25:59.119  4381  4381 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-29 11:25:59.119  4381  4381 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:25:59.119  4381  4381 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 11:25:59.119  4381  4381 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 11:25:59.119  4381  4381 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 11:25:59.119  4381  4381 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:59.119  4381  4381 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:59.119  4381  4381 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 11:25:59.119  4381  4381 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-29 11:25:59.123  4513  4513 I art     : Explicit concurrent mark sweep GC freed 754(43KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 612us total 45.569ms
08-29 11:25:59.128  3662  3662 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-29 11:25:59.131  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-29 11:25:59.133  1031  1429 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 11:25:59.136  2030  2122 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-29 11:25:59.153  1031  1780 V SIM_STK : Menu title from STK is T-Mobile
,08-29 11:25:59.166  1031  1088 W InputMethodInfo: Duplicated subtype definition found: , voice
08-29 11:25:59.180  1031  1031 D administrator: Handling package changes for user 0
,08-29 11:25:59.225  1031  1919 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7255 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 11:25:59.230  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-29 11:25:59.232  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-29 11:25:59.233  1901  1901 D ActionManagerService: notifyUserLog: 1000003
08-29 11:25:59.233  2712  4406 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-29 11:25:59.234  2030  2030 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-29 11:25:59.241   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 258us total 15.150ms
08-29 11:25:59.241  1031  2029 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:25:59.241  1031  2029 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:25:59.247  2030  2030 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-29 11:25:59.249  1598  1598 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-29 11:25:59.253   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 260us total 12.006ms
08-29 11:25:59.259  2222  2222 I ConfigService: onCreate
08-29 11:25:59.260  2222  2222 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-29 11:25:59.265   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 226us total 11.045ms
,08-29 11:25:59.266  2030  2030 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-29 11:25:59.268  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-29 11:25:59.271  1901  1901 D ActionManagerService: notifyUserLog: 1000004
08-29 11:25:59.271  2712  4406 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-29 11:25:59.272  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-29 11:25:59.273  2712  2762 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , create_time: 1430832262123
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , display: false
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , animation: false }
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , create_time: 1430832262287
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , display: false
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , animation: false }
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , create_time: 1472216588858
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , display: false
08-29 11:25:59.275  2030  2030 I GBoardWebViewUtils: , animation: false }
08-29 11:25:59.276  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-29 11:25:59.276  1867  1867 D SplitUIService: removed split : 
,08-29 11:25:59.288  2030  7267 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-29 11:25:59.291  1598  1598 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-29 11:25:59.291  1598  1598 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-29 11:25:59.292  1031  2029 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 11:25:59.294  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 11:25:59.294  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 11:25:59.294  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 11:25:59.294  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 11:25:59.294  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 11:25:59.294  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 11:25:59.294  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 11:25:59.294  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 11:25:59.294  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 11:25:59.294  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 11:25:59.294  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 11:25:59.302  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 11:25:59.302  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-29 11:25:59.303  2222  2222 I ConfigService: onBind returning update interface
08-29 11:25:59.306  2222  2222 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-29 11:25:59.306  2222  2222 I ConfigService: onBind returning config service
08-29 11:25:59.310  2222  2222 I ConfigService: onDestroy
,08-29 11:25:59.321  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-29 11:25:59.321  1867  1867 I SplitUIService: split app #11
,08-29 11:25:59.334  7276  7276 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-29 11:25:59.342  7255  7255 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-29 11:25:59.345  1815  7277 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-29 11:25:59.362  1031  1780 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7284 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-29 11:25:59.370  2030  2030 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-29 11:25:59.377   333   413 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-29 11:25:59.378  3237  7297 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-29 11:25:59.388  1031  1535 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:25:59.388  1031  1535 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:25:59.388  1031  1535 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:25:59.388  1031  1535 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:25:59.389  1031  1535 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:25:59.389  1031  1535 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:25:59.389  1031  1541 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-29 11:25:59.389  1031  1541 D ConnectivityService: identical MTU - not setting
08-29 11:25:59.389  1031  1541 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 11:25:59.389  1031  1541 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 11:25:59.390  1031  1541 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:59.390  1031  1541 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:25:59.390  1031  1541 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:25:59.391  1598  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 11:25:59.392  1598  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 11:25:59.392  1598  1643 D KeyguardModel: createShortcutInfo...
08-29 11:25:59.393  1598  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 11:25:59.393  1598  1643 D KeyguardModel: createShortcutInfo...
08-29 11:25:59.397  1598  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 11:25:59.397  1598  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:25:59.397  1598  1643 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 11:25:59.398  1598  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 11:25:59.400  1031  2047 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:25:59.401  1598  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:25:59.401  1598  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-29 11:25:59.402  1598  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 11:25:59.402  1598  1643 D KeyguardModel: createShortcutInfo...
08-29 11:25:59.408  1598  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 11:25:59.408  1598  1643 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 11:25:59.410  1598  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:25:59.410  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-29 11:25:59.410  1598  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 11:25:59.410  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 11:25:59.411  1031  1031 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 11:25:59.413  1598  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 11:25:59.413  1598  1643 D KeyguardModel: createShortcutInfo...
08-29 11:25:59.414  7276  7276 I dex2oat : dex2oat took 79.804ms (threads: 4)
08-29 11:25:59.415  1031  1573 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-29 11:25:59.421  1598  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:25:59.421  1598  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 11:25:59.422  1598  1643 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 11:25:59.422  1598  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 11:25:59.422  7204  7222 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 11:25:59.422  7204  7222 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 11:25:59.422  7204  7222 I Adreno-EGL: Build Date: 12/12/14 금
08-29 11:25:59.422  7204  7222 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 11:25:59.422  7204  7222 I Adreno-EGL: Remote Branch: 
08-29 11:25:59.422  7204  7222 I Adreno-EGL: Local Patches: 
08-29 11:25:59.422  7204  7222 I Adreno-EGL: Reconstruct Branch: 
08-29 11:25:59.429  1598  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 11:25:59.429  1598  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 11:25:59.433  1598  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 11:25:59.433  1598  1643 D KeyguardModel: createShortcutInfo...
08-29 11:25:59.439  1031  1099 I art     : Explicit concurrent mark sweep GC freed 70058(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.453ms total 314.279ms
08-29 11:25:59.439  1031  2029 I ActivityManager: Killing 6602:com.lge.email/u0a23 (adj 15): empty #17
08-29 11:25:59.439  5474  7304 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-29 11:25:59.477  7284  7284 I AppUp4:AppBoxCP: onCreate
,08-29 11:25:59.477  7284  7284 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-29 11:25:59.484  7284  7284 I AppUp4:DB:  setFingerPrint start
08-29 11:25:59.484  7284  7284 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 11:25:59.497  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-29 11:25:59.500  1815  7307 I PeopleContactsSync: CP2 sync disabled
08-29 11:25:59.508  7284  7284 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 11:25:59.508  7284  7284 I AppUp4:DB:  SDK version = 21
08-29 11:25:59.508  7284  7284 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-29 11:25:59.509  7204  7222 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 11:25:59.509  7204  7222 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 11:25:59.509  7204  7222 I Adreno-EGL: Build Date: 12/12/14 금
08-29 11:25:59.509  7204  7222 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 11:25:59.509  7204  7222 I Adreno-EGL: Remote Branch: 
08-29 11:25:59.509  7204  7222 I Adreno-EGL: Local Patches: 
08-29 11:25:59.509  7204  7222 I Adreno-EGL: Reconstruct Branch: 
,08-29 11:25:59.520  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:25:59.522  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-29 11:25:59.523  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-29 11:25:59.524  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-29 11:25:59.525  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-29 11:25:59.541  1815  7306 I art     : Explicit concurrent mark sweep GC freed 21091(1481KB) AllocSpace objects, 20(320KB) LOS objects, 51% free, 29MB/61MB, paused 891us total 105.786ms
,08-29 11:25:59.548  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-29 11:25:59.548  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:25:59.551  2030  2842 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-29 11:25:59.551  2030  2842 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-29 11:25:59.556  7204  7222 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 11:25:59.556  7204  7222 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 11:25:59.556  7204  7222 I Adreno-EGL: Build Date: 12/12/14 금
08-29 11:25:59.556  7204  7222 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 11:25:59.556  7204  7222 I Adreno-EGL: Remote Branch: 
08-29 11:25:59.556  7204  7222 I Adreno-EGL: Local Patches: 
08-29 11:25:59.556  7204  7222 I Adreno-EGL: Reconstruct Branch: 
,08-29 11:25:59.561  1598  1598 D KeyguardModel: handleShortcutListChanged...
08-29 11:25:59.561  1598  1598 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 11:25:59.564  1031  1919 W libprocessgroup: failed to open /acct/uid_10023/pid_6602/cgroup.procs: No such file or directory
08-29 11:25:59.566  7226  7226 D AndroidRuntime: Shutting down VM
08-29 11:25:59.568   309  7176 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
08-29 11:25:59.569   309  7175 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 11:25:59.572  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-29 11:25:59.573  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 11:25:59.573  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 11:25:59.574  7284  7284 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-29 11:25:59.574  1815  4663 I Icing   : doRemovePackageData com.test.thalitest
08-29 11:25:59.582  2030  2030 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-29 11:25:59.591  7284  7284 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-29 11:25:59.614  1031  1099 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7314 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 11:25:59.614  1031  1094 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2a9c4d0e u0 com.lge.launcher2/.Launcher t5} time:139927
,08-29 11:25:59.615  1598  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 11:25:59.615  1598  1643 D KeyguardModel: createShortcutInfo...
08-29 11:25:59.618  2030  2030 D [Concierge]WidgetView: change position of spinner
08-29 11:25:59.620  1598  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 11:25:59.620  1598  1643 D KeyguardModel: createShortcutInfo...
08-29 11:25:59.620  2572  2572 D [Concierge]Service: onStartCommand(). Type : 8
08-29 11:25:59.620  2572  2572 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-29 11:25:59.621  2572  2572 D [Concierge]Service: Update widget ID : 11
08-29 11:25:59.622  1598  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:25:59.622  1598  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 11:25:59.623  1598  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 11:25:59.623  1598  1643 D KeyguardModel: createShortcutInfo...
08-29 11:25:59.624  1598  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:25:59.624  1598  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 11:25:59.625  1598  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 11:25:59.625  1598  1643 D KeyguardModel: createShortcutInfo...
08-29 11:25:59.626  1598  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:25:59.626  1598  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-29 11:25:59.628  1598  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 11:25:59.628  1598  1643 D KeyguardModel: createShortcutInfo...
08-29 11:25:59.637  1031  1779 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7330 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-29 11:25:59.640  2030  2030 I [Concierge]WidgetView: initWebView(). Time : 1472462759640
08-29 11:25:59.640  2572  2572 D [Concierge]Service: onStartCommand(). Type : 0
,08-29 11:25:59.643  1031  1777 I ActivityManager: Killing 6663:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-29 11:25:59.652  1031  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 11:25:59.657  1031  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-29 11:25:59.725  1598  1598 D KeyguardModel: handleShortcutListChanged...
08-29 11:25:59.725  1598  1598 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 11:25:59.727  1031  1919 W libprocessgroup: failed to open /acct/uid_10046/pid_6663/cgroup.procs: No such file or directory
,08-29 11:25:59.739  2030  2030 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 511556179
08-29 11:25:59.739  2030  2030 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-29 11:25:59.739  2030  2030 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-29 11:25:59.744  2030  2030 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1963f15e
08-29 11:25:59.744  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-29 11:25:59.745  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 11:25:59.745  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:25:59.749  1815  7306 W GmsApplication: Using Auth Proxy for data requests.
08-29 11:25:59.751  1815  7306 W GmsApplication: Using Auth Proxy for data requests.
08-29 11:25:59.752  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-29 11:25:59.752  2030  2030 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-29 11:25:59.752  2030  2030 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-29 11:25:59.753  2030  2030 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472462647768, New one : 1472462759640
08-29 11:25:59.753  2030  2030 D [Concierge]WidgetView: Unregister all receivers
08-29 11:25:59.753  2030  2030 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 11:25:59.754  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-29 11:25:59.758  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:25:59.760  7330  7330 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:25:59.760  7330  7330 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 11:25:59.760  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-29 11:25:59.760  7330  7330 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 11:25:59.761  7330  7330 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-29 11:25:59.761  7330  7330 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 11:25:59.762  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-29 11:25:59.764  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-29 11:25:59.765  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-29 11:25:59.766  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-29 11:25:59.769  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:25:59.769  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 11:25:59.793  1031  1780 I ActivityManager: Killing 6703:com.android.chrome/u0a57 (adj 15): empty #17
,08-29 11:25:59.815  2030  2030 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-29 11:25:59.823  2030  2030 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-29 11:25:59.823  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-29 11:25:59.825  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:25:59.844  2030  2030 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20f37aac time:140156
,08-29 11:25:59.878  1031  1779 W libprocessgroup: failed to open /acct/uid_10057/pid_6703/cgroup.procs: No such file or directory
,08-29 11:25:59.887  1815  7350 E SQLiteLog: (3850) statement aborts at 125: [DELETE FROM FileContent40 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
08-29 11:25:59.888  1815  7350 E DocListDatabase: Failed to delete from FileContent40
08-29 11:25:59.888  1815  7350 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:393)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at com.google.android.gms.drive.database.d.a(SourceFile:1017)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at com.google.android.gms.drive.b.c.run(SourceFile:58)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at com.google.android.gms.drive.g.an.run(SourceFile:51)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-29 11:25:59.888  1815  7350 E DocListDatabase: 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
08-29 11:25:59.893  1815  7350 E AndroidRuntime: FATAL EXCEPTION: pool-29-thread-1
08-29 11:25:59.893  1815  7350 E AndroidRuntime: Process: com.google.android.gms, PID: 1815
08-29 11:25:59.893  1815  7350 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:393)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.a(SourceFile:1017)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at com.google.android.gms.drive.b.c.run(SourceFile:58)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at com.google.android.gms.drive.g.an.run(SourceFile:51)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-29 11:25:59.893  1815  7350 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-29 11:25:59.898  1815  7350 I Process : Sending signal. PID: 1815 SIG: 9
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: Can't write: system_app_crash
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 11:25:59.900  1031  7352 E DropBoxManagerService: 	... 5 more
08-29 11:25:59.906  2222  2353 I art     : Explicit concurrent mark sweep GC freed 4284(241KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 28MB/60MB, paused 670us total 20.371ms

```
