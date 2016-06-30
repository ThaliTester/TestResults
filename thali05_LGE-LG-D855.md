#### Test 72145431fdae11f_thali05_LGE-LG-D855 Logs


```
--------- beginning of system
06-30 10:35:10.660  1033  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=77432620, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
--------- beginning of main
06-30 10:35:10.669  5688  5688 D LgDataFeature: LgDataFeature() Constructor: none
06-30 10:35:10.670  5688  5688 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 10:35:10.707  2574  2574 D [Concierge]Service: onStartCommand(). Type : 9
06-30 10:35:10.748  5688  5688 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
06-30 10:35:10.767  5688  5688 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-30 10:35:10.768  5688  5688 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-30 10:35:10.783  5688  5688 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
06-30 10:35:10.783  5688  5688 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
06-30 10:35:10.797  1033  1048 I ActivityManager: Killing 5112:com.google.android.setupwizard/u0a46 (adj 15): empty #17
06-30 10:35:10.866  1033  1983 W libprocessgroup: failed to open /acct/uid_10046/pid_5112/cgroup.procs: No such file or directory
06-30 10:35:10.881  4289  5730 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
06-30 10:35:10.887  3447  5368 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
06-30 10:35:10.896  3447  5368 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2c44aac6 on behalf of 5688
06-30 10:35:10.934  1033  1983 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5731 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 10:35:10.971  5688  5688 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
06-30 10:35:11.017  5688  5688 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
06-30 10:35:11.231  5731  5731 D DocsApplication: Installing DEX configuration.
06-30 10:35:11.257  5731  5731 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
06-30 10:35:11.263  5731  5731 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{31605a45 com.google.android.apps.docs}
06-30 10:35:11.280  5731  5731 D TAG     : onCreate()
06-30 10:35:11.294  4611  4611 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
06-30 10:35:11.294  4611  4611 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
06-30 10:35:11.300  1033  1744 I ActivityManager: Killing 5142:com.lge.clock/u0a10 (adj 15): empty #17
06-30 10:35:11.306  5731  5731 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
06-30 10:35:11.375  1033  1581 W libprocessgroup: failed to open /acct/uid_10010/pid_5142/cgroup.procs: No such file or directory
,06-30 10:35:11.545  1033  1744 V SIM_STK : Menu title from STK is T-Mobile
06-30 10:35:11.620  4289  5730 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 739 ms] updated apps [took 739 ms] 
06-30 10:35:11.723  5772  5772 D AndroidRuntime: 
06-30 10:35:11.723  5772  5772 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 10:35:11.728  5772  5772 D AndroidRuntime: CheckJNI is OFF
06-30 10:35:11.953  5772  5772 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 10:35:11.959  1033  1911 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 10:35:11.977  1949  2870 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
06-30 10:35:11.982  1033  1911 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
06-30 10:35:11.984  1033  1911 D ActivityManager: setTaskToReturnTo : TaskRecord{2ac813e1 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 10:35:11.984  1033  1911 D ActivityManager: setTaskToReturnTo : TaskRecord{2ac813e1 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 10:35:11.986  1033  1911 D WindowStateEx: AppWindowTokenEx init.. 
06-30 10:35:11.987   339   362 E GBMv2   : DFP En is all cleared set to be enabled
06-30 10:35:12.023  1033  1911 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5800 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 10:35:12.024  5772  5772 D AndroidRuntime: Shutting down VM
06-30 10:35:12.069  1949  1964 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
06-30 10:35:12.069  1949  1964 D SplitWindowPolicy: topRunningActivity=ActivityInfo{e4ac75e co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
06-30 10:35:12.070  1949  1965 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
06-30 10:35:12.071  1949  1965 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f49b73f co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
06-30 10:35:12.121  1563  1563 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:35:12.121  1563  1563 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:35:12.135  5800  5800 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
06-30 10:35:12.235  5800  5800 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,06-30 10:35:12.245  5800  5800 I LibraryLoader: Loading: webviewchromium
06-30 10:35:12.248  5800  5800 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4907-4911)
06-30 10:35:12.248  5800  5800 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 10:35:12.281  5800  5800 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {39d05ca7}
,06-30 10:35:12.282  5800  5800 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:12.283  5800  5800 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 10:35:12.293  5800  5800 I BrowserStartupController: Initializing chromium process, renderers=0
,06-30 10:35:12.294  5800  5800 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:12.302  5800  5825 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
06-30 10:35:12.307  5800  5800 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,06-30 10:35:12.308  5800  5800 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
06-30 10:35:12.308  5800  5800 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
06-30 10:35:12.310   319   319 V AudioPolicyService: registerClient() client 0xb558a220, uid 10118
06-30 10:35:12.314  1033  1115 D BluetoothManagerService: Message: 20
06-30 10:35:12.315  1033  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25d7e963:true
06-30 10:35:12.318  5800  5829 D BluetoothAdapter: 706512212: getState() :  mService = null. Returning STATE_OFF
06-30 10:35:12.338  5800  5800 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:35:12.338  5800  5800 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:35:12.338  5800  5800 I Adreno-EGL: Build Date: 12/12/14 금
06-30 10:35:12.338  5800  5800 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-30 10:35:12.338  5800  5800 I Adreno-EGL: Remote Branch: 
06-30 10:35:12.338  5800  5800 I Adreno-EGL: Local Patches: 
06-30 10:35:12.338  5800  5800 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:35:12.407  5800  5835 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,06-30 10:35:12.414  5800  5800 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
06-30 10:35:12.427  5800  5800 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:12.431  5800  5800 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 10:35:12.434  5800  5800 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-30 10:35:12.436  5800  5800 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
06-30 10:35:12.436  5800  5800 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
06-30 10:35:12.448  5800  5800 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,06-30 10:35:12.454  5800  5800 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:12.454  5800  5800 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:12.490  5800  5847 D OpenGLRenderer: Render dirty regions requested: true
06-30 10:35:12.491  5800  5847 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 10:35:12.500  5800  5847 D OpenGLRenderer: Enabling debug mode 0
,06-30 10:35:12.514  5800  5800 D Atlas   : Validating map...
,06-30 10:35:12.523  1033  1983 D SplitWindow: check instance of lgWin Window{227e0b45 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,06-30 10:35:12.589  5800  5845 D LgDataFeature: LgDataFeature() Constructor: none
06-30 10:35:12.589  5800  5845 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 10:35:12.619  1802  4469 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,06-30 10:35:12.624  1033  1116 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +556ms (total +637ms)
06-30 10:35:12.624  1033  1116 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2e453506 u0 com.test.thalitest/.MainActivity t12} time:85287
06-30 10:35:12.629  5800  5800 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16ec9c33 time:85292
06-30 10:35:12.663  1802  4469 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,06-30 10:35:12.724  1802  4469 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,06-30 10:35:12.736  5800  5800 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
06-30 10:35:12.736  5800  5800 I chromium: 
,06-30 10:35:12.742  5800  5800 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 10:35:12.835  5800  5859 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435052544
,06-30 10:35:12.847  5800  5859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:35:12.847  5800  5859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:35:12.847  5800  5859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:35:12.847  5800  5859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:35:12.847  5800  5859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 10:35:12.848  5800  5859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20693a87 added. We now have 1 listener(s)
,06-30 10:35:12.849  1033  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:12.853  5800  5859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
06-30 10:35:12.856  5800  5859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
06-30 10:35:12.858  5800  5859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 10:35:12.858  5800  5859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 10:35:12.865  5800  5859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c50ad52 added. We now have 1 listener(s)
06-30 10:35:12.866  5800  5859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 10:35:12.871  1033  1527 D WifiService: New client listening to asynchronous messages
06-30 10:35:12.871  5800  5859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:12.872  5800  5859 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 10:35:12.875  5800  5859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 10:35:12.875  5800  5859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:35:12.877  5800  5859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:35:12.877  5800  5859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 10:35:12.880  5800  5859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 10:35:12.881  1033  1581 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:12.881  5800  5859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
06-30 10:35:12.886  5800  5859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:12.887  5800  5859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:35:12.887  5800  5859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:12.887  5800  5859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:12.887  5800  5859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:12.887  5800  5859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:12.887  5800  5859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:12.887  5800  5859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:12.887  5800  5859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:12.887  5800  5859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:35:12.887  5800  5859 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:35:12.889  5800  5859 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 10:35:12.930  5800  5800 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:35:12.941  5800  5845 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
06-30 10:35:12.941  5800  5845 I chromium: 
06-30 10:35:13.051   339   364 E GBMv2   : DFP En is all cleared set to be enabled
06-30 10:35:13.052   339   364 E GBMv2   : Set value is all cleared set the max
,06-30 10:35:13.052   339   364 I GBMv2   : DFP Enabled. Ignore VFP set
,06-30 10:35:13.198  5731  5731 D LgDataFeature: LgDataFeature() Constructor: none
06-30 10:35:13.198  5731  5731 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 10:35:13.440  1033  2056 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5870 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
06-30 10:35:13.441  1033  2056 I ActivityManager: Killing 4714:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,06-30 10:35:13.568  1033  1582 W libprocessgroup: failed to open /acct/uid_10085/pid_4714/cgroup.procs: No such file or directory
,06-30 10:35:13.601  5731  5731 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,06-30 10:35:13.624  5870  5870 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,06-30 10:35:13.648  5870  5870 I LockScreenSettings: New app installed broadcast received ..
,06-30 10:35:13.654  5870  5870 I LockScreenSettings: Number of installed packages  1
06-30 10:35:13.714  1033  1983 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5895 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:13.785  5895  5895 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:35:14.130  5800  5862 W jxcore-log: Initializing JXcore engine
06-30 10:35:14.130  5800  5862 W jxcore-log: JXcore engine is ready
,06-30 10:35:14.208  5862  5862 W Thread-647: type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[9407]" dev="sockfs" ino=9407 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,06-30 10:35:14.208  5862  5862 W Thread-647: type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
06-30 10:35:14.208  5862  5862 W Thread-647: type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9567]" dev="sockfs" ino=9567 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
06-30 10:35:14.208  5862  5862 W Thread-647: type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
06-30 10:35:14.208  5862  5862 W Thread-647: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[28290]" dev="sockfs" ino=28290 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
06-30 10:35:14.236  5800  5862 W jxcore-log: Starting JXcore engine
,06-30 10:35:14.320  1033  1983 V SIM_STK : Menu title from STK is T-Mobile
,06-30 10:35:14.379  1033  2077 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5933 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,06-30 10:35:14.433  5800  5862 W jxcore-log: Platform android
06-30 10:35:14.433  5800  5862 W jxcore-log: 
06-30 10:35:14.433  5800  5862 W jxcore-log: Process ARCH arm
06-30 10:35:14.433  5800  5862 W jxcore-log: 
,06-30 10:35:14.472  5933  5933 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
06-30 10:35:14.472  5933  5933 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,06-30 10:35:14.476  4833  4833 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
06-30 10:35:14.489  1033  2056 I ActivityManager: Killing 4891:com.android.calendar/u0a13 (adj 15): empty #17
,06-30 10:35:14.490   314  5953 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
06-30 10:35:14.491  1033  1113 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
06-30 10:35:14.624  1033  1033 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.calendar/com.android.calendar.alerts.AlertReceiver}
06-30 10:35:14.624  1033  1033 W BroadcastQueue: android.os.DeadObjectException
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:252)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:939)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16582)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at android.content.BroadcastReceiver$PendingResult.sendFinished(BroadcastReceiver.java:419)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at android.content.BroadcastReceiver$PendingResult.finish(BroadcastReceiver.java:395)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:973)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at com.android.server.SystemServer.run(SystemServer.java:288)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at com.android.server.SystemServer.main(SystemServer.java:189)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 10:35:14.624  1033  1033 W BroadcastQueue: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,06-30 10:35:14.624  1033  1033 W libprocessgroup: failed to open /acct/uid_10013/pid_4891/cgroup.procs: No such file or directory
06-30 10:35:14.699  1033  1033 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5954 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,06-30 10:35:14.700  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=77432620 [*alarm*], flags=0x0
06-30 10:35:14.700  1033  1948 W ActivityManager: Spurious death for ProcessRecord{1ba6464a 5954:com.android.calendar/u0a13}, curProc for 4891: null
06-30 10:35:14.724  5800  5862 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:35:14.724  5800  5862 I jxcore-log: 
,06-30 10:35:14.724  5800  5862 W jxcore-log: JXcore engine is started
06-30 10:35:14.732  5800  5859 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 10:35:14.738  5800  5800 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 10:35:14.880  1033  1744 I art     : Explicit concurrent mark sweep GC freed 24248(1173KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.849ms total 127.958ms
,06-30 10:35:14.924  5954  5954 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:35:14.953  5954  5954 D CalendarApplication: CalendarApplication.onCreate()
,06-30 10:35:14.973  5954  5954 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
,06-30 10:35:14.977  5954  5954 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@34589ecb, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@261fa6a8, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2e3155c1, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@7688166, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@39d05ca7, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2a1c8554, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@11bc8cfd, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@8eb4df2, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@391c1c43, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@66a2c0, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@11c9fbf9, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@395c573e, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@6da399f, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@18732aec, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1ea55eb5, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2442a94a, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3932d0bb, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1de09d8, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@279a3131, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@148a1016, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@16b3bd97, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2815eb84, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2b2faf6d, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@60f17a2, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@16ec9c33, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1cc83bf0, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@f24d569, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@23eb0bee, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@10cac88f, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1d0d271c, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3c2c5f25, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1f7ff8fa, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@32b55eab, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3d539908, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3968c8a1, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2c44aac6, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@20693a87, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@280d3db4, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3a84ddd, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2c50ad52, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1294f823, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$Key,Data@1b1a812
06-30 10:35:14.984  5954  5954 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
06-30 10:35:15.001  5954  5954 D Config  : [init]
,06-30 10:35:15.002  5954  5954 I Config  : LGCalendar ver.4.40.16
06-30 10:35:15.002  5954  5954 I Config  : start check model
06-30 10:35:15.002  5954  5954 I Config  : start check native_ca
06-30 10:35:15.003  5954  5954 I Config  : Config Operator=OPEN, Country=EU
06-30 10:35:15.004  5954  5954 D Config  : [setDefaultValuesToPref]
06-30 10:35:15.004  5954  5954 D Config  : [parseProfiles]
06-30 10:35:15.008  5954  5954 D ProfilesParser: [debug_displayParseInfos] profile.country = null
06-30 10:35:15.008  5954  5954 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
06-30 10:35:15.008  5954  5954 D Config  : [updateProfiletoCountryInfo]
06-30 10:35:15.009  5954  5954 D GeneralPreference: [checkAndMigrateOldPreference]
06-30 10:35:15.016  5954  5954 D AlertReceiver: onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,06-30 10:35:15.027  5954  5976 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
,06-30 10:35:15.029  5954  5976 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
06-30 10:35:15.045  5954  5976 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
06-30 10:35:15.049  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
,06-30 10:35:15.052  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
06-30 10:35:15.055  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
06-30 10:35:15.057  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
06-30 10:35:15.060  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
06-30 10:35:15.062  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
06-30 10:35:15.064  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,06-30 10:35:15.067  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
06-30 10:35:15.070  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
06-30 10:35:15.072  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
06-30 10:35:15.075  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
06-30 10:35:15.087  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,06-30 10:35:15.090  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
06-30 10:35:15.093  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
06-30 10:35:15.095  5954  5976 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
06-30 10:35:15.095  5954  5976 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
06-30 10:35:15.097  5954  5976 I AlertUtils: set default noti to content://media/internal/audio/media/41
06-30 10:35:15.100  5954  5976 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
,06-30 10:35:15.138  5954  5979 W HolidayIntentService: onHandleIntent
,06-30 10:35:15.140  5954  5979 D HolidayDataLoader: readJsonAsset : holiday.json
06-30 10:35:15.152  5954  5980 D AlertService: 0 Action = android.intent.action.PROVIDER_CHANGED
,06-30 10:35:15.156  5954  5954 E AgendaWidgetManager: [updateWidgets] 
06-30 10:35:15.160  5954  5954 D MonthWidgetProvider: [onReceive]
06-30 10:35:15.160  5954  5954 D CalendarWidgetProvider: [onReceive]
06-30 10:35:15.161  5954  5954 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
06-30 10:35:15.164  5954  5954 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
06-30 10:35:15.167  5954  5954 D WeekWidgetProvider: [onReceive]
06-30 10:35:15.167  5954  5954 D CalendarWidgetProvider: [onReceive]
06-30 10:35:15.167  5954  5954 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,06-30 10:35:15.170  5954  5954 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
06-30 10:35:15.214  5954  5979 E HolidayIntentService: onHandleIntent:holiday data empty
,06-30 10:35:15.294  4611  4611 D CalendarProviderBroadcastReceiver: Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,06-30 10:35:15.294  4611  4611 D CalendarProviderBroadcastReceiver: [IntentService] WakeLock acquire, start IntentSerivce
06-30 10:35:15.294  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{23fdf669 type 2 when 87939 com.android.providers.calendar} when 87939
,06-30 10:35:15.305  4611  4611 D CalendarProvider2: CalendarProviderIntentService.onCreate()
06-30 10:35:15.309  4611  5984 D CalendarProvider2: Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
06-30 10:35:15.310  4611  5984 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
,06-30 10:35:15.328  4611  5984 D CalendarProvider2: [IntentService] Release Lock
,06-30 10:35:15.330  4611  4611 D CalendarProvider2: CalendarProviderIntentService.onDestroy()
06-30 10:35:17.308  5731  5731 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,06-30 10:35:17.311  1033  2077 I ActivityManager: Killing 5225:com.google.android.gm/u0a64 (adj 15): empty #17
,06-30 10:35:17.469  1033  1947 W libprocessgroup: failed to open /acct/uid_10064/pid_5225/cgroup.procs: No such file or directory
,06-30 10:35:18.422  5731  5866 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,06-30 10:35:18.627  1802  5551 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,06-30 10:35:18.632   314  6044 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
06-30 10:35:18.632  1033  1113 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
06-30 10:35:18.632  1802  5551 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
06-30 10:35:18.634  1802  1802 I ConfigFetchService: fetch service done; releasing wakelock
06-30 10:35:18.635  1802  1802 I ConfigFetchService: stopping self
06-30 10:35:18.641  2140  2140 I ConfigService: onDestroy
,06-30 10:35:19.114   333   333 E ThermalEngine: out low battery limit. 
,06-30 10:35:19.320  1033  2077 I ActivityManager: Killing 4984:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,06-30 10:35:19.348  4959  4959 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
06-30 10:35:19.348  4959  4959 W System.err: android.os.DeadObjectException
06-30 10:35:19.348  4959  4959 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-30 10:35:19.348  4959  4959 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-30 10:35:19.348  4959  4959 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
06-30 10:35:19.348  4959  4959 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
06-30 10:35:19.348  4959  4959 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
06-30 10:35:19.348  4959  4959 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
06-30 10:35:19.348  4959  4959 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:35:19.349  4959  4959 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:35:19.349  4959  4959 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:35:19.349  4959  4959 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-30 10:35:19.349  4959  4959 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:19.349  4959  4959 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:19.349  4959  4959 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 10:35:19.349  4959  4959 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-30 10:35:19.349  4959  4959 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
06-30 10:35:19.349  4959  4959 W System.err: android.os.DeadObjectException
06-30 10:35:19.349  4959  4959 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-30 10:35:19.349  4959  4959 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-30 10:35:19.349  4959  4959 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
06-30 10:35:19.350  4959  4959 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
06-30 10:35:19.350  4959  4959 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
06-30 10:35:19.350  4959  4959 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
06-30 10:35:19.350  4959  4959 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:35:19.350  4959  4959 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:35:19.350  4959  4959 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:35:19.350  4959  4959 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-30 10:35:19.350  4959  4959 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:19.350  4959  4959 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:19.350  4959  4959 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 10:35:19.350  4959  4959 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-30 10:35:19.350  4959  4959 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
06-30 10:35:19.350  4959  4959 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,06-30 10:35:19.558  1033  1049 W libprocessgroup: failed to open /acct/uid_1000/pid_4984/cgroup.procs: No such file or directory
06-30 10:35:19.559  1033  1049 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,06-30 10:35:19.572  4959  4959 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
06-30 10:35:19.572  4959  4959 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,06-30 10:35:19.637  1033  1983 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6052 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,06-30 10:35:19.640  4959  4959 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,06-30 10:35:19.720  6052  6052 D UEI.SmartControl: Quickset Services start...
06-30 10:35:19.722  6052  6052 I UEI.SmartControl: Manufacture = LGE
06-30 10:35:19.722  6052  6052 D UEI.SmartControl: Id = LGNevo
06-30 10:35:19.723  6052  6052 D UEI.SmartControl: File observer start...
06-30 10:35:19.724  6052  6052 E UEI.SmartControl: IR Port is disabled: false
06-30 10:35:19.724  6052  6052 D UEI.SmartControl: Starting file observer...
06-30 10:35:19.724  6052  6052 D UEI.SmartControl: Extracting JNI libs...
06-30 10:35:19.724  6052  6052 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,06-30 10:35:19.814  6052  6052 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,06-30 10:35:19.814  6052  6052 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
06-30 10:35:19.814  6052  6052 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,06-30 10:35:19.850  6052  6052 I UEI.SmartControl: --- Selecting new region: 6
,06-30 10:35:19.852  6052  6052 I UEI.SmartControl: Model = LG-D855
06-30 10:35:19.853  6052  6052 D UEI.SmartControl: QS Service created
,06-30 10:35:19.867  6052  6052 I UEI.SmartControl: Service initServices...
,06-30 10:35:19.871  6052  6052 D UEI.SmartControl: QS start get config
,06-30 10:35:19.940  6052  6052 D UEI.SmartControl: Loading JNI Libs...
,06-30 10:35:20.155  5954  5980 D AlertService: Beginning updateAlertNotification
,06-30 10:35:20.179  5954  5980 D AlertService: No fired or scheduled alerts
,06-30 10:35:20.196  5954  5980 D AlertService: Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,06-30 10:35:20.209  5954  5980 D AlarmScheduler: No events found starting within 1 week.
06-30 10:35:20.216  1033  1983 I ActivityManager: Killing 4959:com.lge.qremote/u0a112 (adj 15): empty #17
06-30 10:35:20.240  6052  6052 I UEI.SmartControl: Supports setup maps: true
,06-30 10:35:20.243  6052  6052 D UEI.SmartControl: QS start statue = true Error code = 0
06-30 10:35:20.243  6052  6052 I UEI.SmartControl: QS version = v2.7.10.1_RC1
06-30 10:35:20.243  6052  6052 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
06-30 10:35:20.243  6052  6052 I UEI.SmartControl: ### init IR Blaster...
06-30 10:35:20.248  6052  6052 D serial_port: Configuring serial port
06-30 10:35:20.258  6052  6052 E UEI.SmartControl: UEIBLaster setting for 616
06-30 10:35:20.258  6052  6052 I UEI.SmartControl: Setting serial record hearder size = 2
06-30 10:35:20.258  6052  6052 I UEI.SmartControl: configuring settings for MAXQ616
06-30 10:35:20.259  6052  6052 I UEI.SmartControl: Get version...
,06-30 10:35:20.276  6052  6076 D UEI.SmartControl: serial port data available: 21
,06-30 10:35:20.304  6052  6052 D UEI.SmartControl: MAXQ616 A2-X4 software.
06-30 10:35:20.304  6052  6052 I UEI.SmartControl: IR Blaster version: 256702256704300002
06-30 10:35:20.304  6052  6052 I UEI.SmartControl: QS saving settings...
,06-30 10:35:20.306  6052  6052 D UEI.SmartControl: IR Blaster version: 25672567
06-30 10:35:20.323  6052  6076 D UEI.SmartControl: serial port data available: 4
,06-30 10:35:20.328  1033  1559 W libprocessgroup: failed to open /acct/uid_10112/pid_4959/cgroup.procs: No such file or directory
06-30 10:35:20.361  6052  6084 I UEI.SmartControl: Device manager: loading config....
,06-30 10:35:20.363  6052  6084 D UEI.SmartControl: ----------- loading internal config...
06-30 10:35:20.369  6052  6052 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
06-30 10:35:20.379  6052  6052 E UEI.SmartControl: Services init done
06-30 10:35:20.379  6052  6052 D UEI.SmartControl: QS Service init finished
06-30 10:35:20.380  6052  6052 D UEI.SmartControl: QS Service version name: 2.1.91
06-30 10:35:20.380  6052  6052 D UEI.SmartControl: QS Service version code: 201091
,06-30 10:35:20.381  6052  6052 D UEI.SmartControl: Service requested: Control
06-30 10:35:20.384  6052  6084 E UEI.SmartControl: Loading SETTINGS...
06-30 10:35:20.387  6052  6052 D UEI.SmartControl: Request IControl service: devices are loaded...
06-30 10:35:20.388  6052  6052 D UEI.SmartControl: Service.onUnbind: IControl
06-30 10:35:20.392  6052  6052 D UEI.SmartControl: Service.onDestroy
06-30 10:35:20.392  6052  6052 D UEI.SmartControl: Lock is in USE false
06-30 10:35:20.392  6052  6052 D UEI.SmartControl: unbind internal service
06-30 10:35:20.394  6052  6052 D serial_port: close(fd = 25)
,06-30 10:35:20.395  6052  6084 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
06-30 10:35:20.398  6052  6083 I UEI.SmartControl: Notify AllClients services are ready: 0
06-30 10:35:20.398  6052  6083 D UEI.SmartControl: -----service ready thread exits
06-30 10:35:20.399  6052  6052 I UEI.SmartControl: Serial port is closed.
06-30 10:35:20.399  6052  6052 I UEI.SmartControl: Serial port is closed.
06-30 10:35:20.399  6052  6052 D UEI.SmartControl: Blaster closed
06-30 10:35:20.399  6052  6052 D UEI.SmartControl: Shut down QS...
06-30 10:35:20.399  6052  6052 D UEI.SmartControl: Stopping QS lib
06-30 10:35:20.400  6052  6052 D UEI.SmartControl: QS lib stop result = true
06-30 10:35:20.400  6052  6052 D UEI.SmartControl: Stopped QS lib
06-30 10:35:20.400  6052  6052 D UEI.SmartControl: Stopped file observer...
06-30 10:35:20.400  6052  6052 D UEI.SmartControl: QS shutdown complete
06-30 10:35:20.401  6052  6052 D UEI.SmartControl: QS Service created
,06-30 10:35:20.417  6052  6052 I UEI.SmartControl: Service initServices...
06-30 10:35:20.417  6052  6052 D UEI.SmartControl: QS start get config
06-30 10:35:20.835  6052  6052 I UEI.SmartControl: Supports setup maps: true
,06-30 10:35:20.842  6052  6052 D UEI.SmartControl: QS start statue = true Error code = 0
06-30 10:35:20.842  6052  6052 I UEI.SmartControl: QS version = v2.7.10.1_RC1
06-30 10:35:20.842  6052  6052 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
06-30 10:35:20.842  6052  6052 I UEI.SmartControl: ### init IR Blaster...
06-30 10:35:20.847  6052  6052 D serial_port: Configuring serial port
06-30 10:35:20.847  6052  6052 E UEI.SmartControl: UEIBLaster setting for 616
06-30 10:35:20.847  6052  6052 I UEI.SmartControl: Setting serial record hearder size = 2
06-30 10:35:20.847  6052  6052 I UEI.SmartControl: configuring settings for MAXQ616
06-30 10:35:20.847  6052  6052 I UEI.SmartControl: Get version...
06-30 10:35:20.864  6052  6094 D UEI.SmartControl: serial port data available: 21
,06-30 10:35:20.891  6052  6052 D UEI.SmartControl: MAXQ616 A2-X4 software.
06-30 10:35:20.891  6052  6052 I UEI.SmartControl: IR Blaster version: 256702256704300002
06-30 10:35:20.891  6052  6052 I UEI.SmartControl: QS saving settings...
06-30 10:35:20.892  6052  6052 D UEI.SmartControl: IR Blaster version: 25672567
,06-30 10:35:20.906  6052  6094 D UEI.SmartControl: serial port data available: 4
,06-30 10:35:20.936  6052  6052 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,06-30 10:35:20.941  6052  6052 E UEI.SmartControl: Services init done
06-30 10:35:20.941  6052  6052 D UEI.SmartControl: QS Service init finished
06-30 10:35:20.945  6052  6052 D UEI.SmartControl: QS Service version name: 2.1.91
06-30 10:35:20.946  6052  6052 D UEI.SmartControl: QS Service version code: 201091
06-30 10:35:20.948  6052  6097 I UEI.SmartControl: Device manager: loading config....
06-30 10:35:20.949  6052  6097 D UEI.SmartControl: ----------- loading internal config...
,06-30 10:35:20.957  6052  6052 D UEI.SmartControl: Service requested: Control
06-30 10:35:20.960  6052  6097 E UEI.SmartControl: Loading SETTINGS...
06-30 10:35:20.962  6052  6052 D UEI.SmartControl: Request IControl service: devices are loaded...
06-30 10:35:20.965  1033  1582 I ActivityManager: Killing 5266:com.google.android.talk/u0a72 (adj 15): empty #17
,06-30 10:35:20.986  6052  6097 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,06-30 10:35:20.998  6052  6096 I UEI.SmartControl: Notify AllClients services are ready: 0
06-30 10:35:20.998  6052  6096 D UEI.SmartControl: -----service ready thread exits
,06-30 10:35:21.047  1033  1581 W libprocessgroup: failed to open /acct/uid_10072/pid_5266/cgroup.procs: No such file or directory
,06-30 10:35:21.052  6052  6052 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@391c1c43 that was originally bound here
06-30 10:35:21.052  6052  6052 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@391c1c43 that was originally bound here
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 10:35:21.052  6052  6052 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-30 10:35:21.053  6052  6052 D UEI.SmartControl: Internal service binding...
06-30 10:35:21.397  6052  6086 D UEI.SmartControl: Internal timer expired: 2
,06-30 10:35:23.710  1033  1105 I ActivityManager: Waited long enough for: ServiceRecord{189d2a3b u0 com.google.android.gms/.wearable.service.WearableService}
,06-30 10:35:24.731  6052  6063 E UEI.SmartControl: file observer is disposed!
,06-30 10:35:25.935  6052  6098 D UEI.SmartControl: Internal timer expired: 3
,06-30 10:35:25.936  6052  6098 D UEI.SmartControl: unbind internal service
,06-30 10:35:25.951  6052  6052 D UEI.SmartControl: Service.onUnbind: IControl
06-30 10:35:25.952  6052  6052 D UEI.SmartControl: Service.onDestroy
06-30 10:35:25.952  6052  6052 D UEI.SmartControl: Lock is in USE false
06-30 10:35:25.952  6052  6052 D UEI.SmartControl: unbind internal service
06-30 10:35:25.953  6052  6052 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2442a94a
06-30 10:35:25.954  6052  6052 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
06-30 10:35:25.954  6052  6052 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
,06-30 10:35:25.958  6052  6052 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
06-30 10:35:25.958  6052  6052 W System.err: 	at com.uei.control.Service.c(Unknown Source)
06-30 10:35:25.958  6052  6052 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
06-30 10:35:25.958  6052  6052 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
,06-30 10:35:25.958  6052  6052 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
06-30 10:35:25.959  6052  6052 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
06-30 10:35:25.959  6052  6052 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:25.959  6052  6052 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:35:25.959  6052  6052 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-30 10:35:25.959  6052  6052 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:25.959  6052  6052 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:25.959  6052  6052 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 10:35:25.959  6052  6052 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-30 10:35:25.959  6052  6052 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2442a94a
06-30 10:35:25.960  6052  6052 D serial_port: close(fd = 24)
06-30 10:35:25.963  6052  6052 I UEI.SmartControl: Serial port is closed.
06-30 10:35:25.963  6052  6052 I UEI.SmartControl: Serial port is closed.
06-30 10:35:25.963  6052  6052 D UEI.SmartControl: Blaster closed
06-30 10:35:25.963  6052  6052 D UEI.SmartControl: Shut down QS...
06-30 10:35:25.963  6052  6052 D UEI.SmartControl: Stopping QS lib
06-30 10:35:25.963  6052  6052 D UEI.SmartControl: QS lib stop result = true
06-30 10:35:25.963  6052  6052 D UEI.SmartControl: Stopped QS lib
06-30 10:35:25.963  6052  6052 D UEI.SmartControl: QS shutdown complete
06-30 10:35:27.511   306   306 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
06-30 10:35:27.511   306   306 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
06-30 10:35:27.511   306   306 I rmt_storage: wakelock acquired: 1, error no: 42
06-30 10:35:27.512   306   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,06-30 10:35:27.629   306   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
06-30 10:35:27.629   306   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
06-30 10:35:27.629   306   902 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
06-30 10:35:27.629   306   902 I rmt_storage: 
,06-30 10:35:27.632   306   306 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
06-30 10:35:27.632   903   913 E Diag_Lib: [IMS_FATAL]| 3347 | 913 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
06-30 10:35:28.068  5800  5862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-30 10:35:28.068  5800  5862 I jxcore-log: 
,06-30 10:35:28.070  5800  5862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-30 10:35:28.070  5800  5862 I jxcore-log: 
06-30 10:35:28.072  5800  5862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:28.072  5800  5862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:35:28.072  5800  5862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:28.072  5800  5862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:28.072  5800  5862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:28.072  5800  5862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:28.072  5800  5862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:28.072  5800  5862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:28.072  5800  5862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:28.072  5800  5862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:28.073  5800  5862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 10:35:28.074  5800  5862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-30 10:35:28.074  5800  5862 I jxcore-log: 
06-30 10:35:28.076  5800  5862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-30 10:35:28.076  5800  5862 I jxcore-log: 
06-30 10:35:28.402  5800  5862 I jxcore-log: Unit Test app is loaded
06-30 10:35:28.402  5800  5862 I jxcore-log: 
,06-30 10:35:28.407  5800  5862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
,06-30 10:35:28.407  5800  5862 I jxcore-log: 
06-30 10:35:28.420  1033  1048 D WifiServiceImplEx: setWifiEnabled: true pid=5800, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
06-30 10:35:28.420  1033  1048 D WifiService: setWifiEnabled: true pid=5800, uid=10118
06-30 10:35:28.420  1033  1048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,06-30 10:35:28.425  5800  5800 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,06-30 10:35:28.442  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 10:35:28.443  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 10:35:28.443  1033  1033 D Ulp_jni : JNI:system_update. Event-4
06-30 10:35:28.443  1033  2030 D WifiServiceImplEx: disconnect pid=5800, uid=10118, packageName=com.test.thalitest
06-30 10:35:28.444  1033  1948 D WifiServiceImplEx: reconnect pid=5800, uid=10118, packageName=com.test.thalitest
06-30 10:35:28.444  1033  1521 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
06-30 10:35:28.444  1033  1521 I LGFTMITEM: [GET_FTM][id=6], offset=12288
06-30 10:35:28.445  1033  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:28.445  1033  1947 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
06-30 10:35:28.446  1033  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
06-30 10:35:28.446  1033  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
06-30 10:35:28.446  1033  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
06-30 10:35:28.446  1033  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
06-30 10:35:28.447  1033  1521 I WifiUtil: Intf0MacAddress=C49A027FFB5D
06-30 10:35:28.447  1033  1521 E WifiHW  : unknown target_country: EU , set to default
06-30 10:35:28.447  1033  1521 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
06-30 10:35:28.447  1033  1521 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
06-30 10:35:28.447  1033  1521 I WifiUtil: gEnableBmps=1
,06-30 10:35:28.460  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 10:35:28.460  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 10:35:28.461  1033  1033 D Ulp_jni : JNI:system_update. Event-4
06-30 10:35:28.461  1033  1115 D BluetoothManagerService: Message: 1
06-30 10:35:28.461  1033  1115 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
06-30 10:35:28.464  5800  5862 I jxcore-log: My device name is: LGE-LG-D855
06-30 10:35:28.464  5800  5862 I jxcore-log: 
06-30 10:35:28.467  5800  5862 I jxcore-log: WARN testUtils: myNameCallback not set!
06-30 10:35:28.467  5800  5862 I jxcore-log: 
06-30 10:35:28.511  1033  1115 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6120 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,06-30 10:35:28.560  6120  6120 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
06-30 10:35:28.561  6120  6120 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:35:28.561  6120  6120 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,06-30 10:35:28.561  6120  6120 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
06-30 10:35:28.638  6120  6120 D BluetoothAdapterApp: Loading JNI Library
06-30 10:35:28.640  1033  1115 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,06-30 10:35:28.647   314  6139 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
06-30 10:35:28.658  1033  1115 D Tethering: InitialState.processMessage what=4
06-30 10:35:28.658   314   891 D SoftapController: Softap fwReload - Ok
06-30 10:35:28.661  1033  1113 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,06-30 10:35:28.667   314   891 D CommandListener: Setting iface cfg
06-30 10:35:28.667   314   891 D CommandListener: Trying to bring down wlan0
06-30 10:35:28.677   314   891 D CommandListener: Clearing all IP addresses on wlan0
06-30 10:35:28.696  1033  1105 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6141 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,06-30 10:35:28.697  1033  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,06-30 10:35:28.715   343   343 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 390us total 21.661ms
06-30 10:35:28.729  1033  1521 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
06-30 10:35:28.730  1033  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
06-30 10:35:28.730  1033  1521 E WifiStateMachine: useWiFiOffloading() : false
06-30 10:35:28.730  1033  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,06-30 10:35:28.731  1033  1521 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
06-30 10:35:28.731  1033  1521 D WifiMonitor: connecting to supplicant
06-30 10:35:28.718  6162  6162 W wpa_supplicant: type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:28.718  6162  6162 W wpa_supplicant: type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:28.734  1949  1949 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
06-30 10:35:28.734  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:28.741   343   343 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 25.134ms
06-30 10:35:28.744  5800  5800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 10:35:28.745  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,06-30 10:35:28.756   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 14.277ms
06-30 10:35:28.757  6162  6162 I wpa_supplicant: Successfully initialized wpa_supplicant
06-30 10:35:28.774  6162  6162 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-30 10:35:28.774  6162  6162 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,06-30 10:35:28.789  6141  6141 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:35:28.789  6141  6141 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
06-30 10:35:28.789  6141  6141 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:35:28.789  6141  6141 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
06-30 10:35:28.790  6141  6141 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 10:35:28.790  6141  6141 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,06-30 10:35:28.804  1563  1579 I art     : Background sticky concurrent mark sweep GC freed 18897(1074KB) AllocSpace objects, 20(19MB) LOS objects, 10% free, 131MB/147MB, paused 7.342ms total 32.298ms
,06-30 10:35:28.811  6120  6120 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@31605a45 Instance Count = 1
06-30 10:35:28.817  6120  6120 D BluetoothAdapterApp: onCreate
,06-30 10:35:28.831  6120  6120 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,06-30 10:35:28.831  6120  6120 D ProfileConfigQcom: Adding HeadsetService
06-30 10:35:28.831  6120  6120 D ProfileConfigQcom: [BTUI] A2dpService is supported
06-30 10:35:28.831  6120  6120 D ProfileConfigQcom: Adding A2dpService
06-30 10:35:28.831  6120  6120 D ProfileConfigQcom: [BTUI] HidService is supported
06-30 10:35:28.831  6120  6120 D ProfileConfigQcom: Adding HidService
06-30 10:35:28.832  6120  6120 D ProfileConfigQcom: [BTUI] HealthService is supported
06-30 10:35:28.832  6120  6120 D ProfileConfigQcom: Adding HealthService
06-30 10:35:28.832  6120  6120 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
06-30 10:35:28.833  6120  6120 D ProfileConfigQcom: [BTUI] PanService is supported
06-30 10:35:28.833  6120  6120 D ProfileConfigQcom: Adding PanService
06-30 10:35:28.833  6120  6120 D ProfileConfigQcom: [BTUI] GattService is supported
06-30 10:35:28.833  6120  6120 D ProfileConfigQcom: Adding GattService
06-30 10:35:28.833  6120  6120 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
06-30 10:35:28.833  6120  6120 D ProfileConfigQcom: Adding BluetoothMapService
06-30 10:35:28.833  6120  6120 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
06-30 10:35:28.843  6162  6162 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-30 10:35:28.854  1033  1115 D BluetoothManagerService: Message: 20
06-30 10:35:28.855  1033  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a98c36f:true
06-30 10:35:28.855  6120  6120 D BluetoothAdapterState: make
06-30 10:35:28.857  6120  6120 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
06-30 10:35:28.858  6120  6120 I bluedroid-qcom: init
06-30 10:35:28.858  6120  6166 I BluetoothAdapterState: Entering OffState
,06-30 10:35:28.861  6120  6120 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
06-30 10:35:28.861  6120  6120 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
06-30 10:35:28.861  6120  6120 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
06-30 10:35:28.861  6120  6120 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
06-30 10:35:28.861  6120  6120 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
06-30 10:35:28.862  6120  6120 I bluedroid-qcom: get_profile_interface socket
06-30 10:35:28.862  6120  6169 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
06-30 10:35:28.862  6120  6120 I bluedroid-qcom: get_profile_interface map_client
06-30 10:35:28.848  6170  6170 W bdaddr_loader: type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:28.848  6170  6170 W bdaddr_loader: type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:28.863  6120  6169 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
06-30 10:35:28.864  6120  6169 D BluetoothAdapterProperties: Name is: G3
06-30 10:35:28.864  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
06-30 10:35:28.864  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
06-30 10:35:28.867  6170  6170 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
06-30 10:35:28.867  6170  6170 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
06-30 10:35:28.867  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
06-30 10:35:28.867  6170  6170 I LGFTMITEM: [GET_FTM][id=8], offset=16384
06-30 10:35:28.867  1033  1115 D BluetoothManagerService: Message: 40
06-30 10:35:28.867  1033  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
06-30 10:35:28.867  6170  6170 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
06-30 10:35:28.868  6120  6136 I bluedroid-qcom: config_hci_snoop_log
06-30 10:35:28.869  1033  1115 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
,06-30 10:35:28.869  1033  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
06-30 10:35:28.874  6170  6170 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
06-30 10:35:28.874  6170  6170 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
06-30 10:35:28.874  6120  6137 V LGMDMManagerInternal: Create singleton instance
06-30 10:35:28.898  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 10:35:28.898  6141  6141 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 10:35:28.898  6141  6141 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 10:35:28.899  6141  6141 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 10:35:28.899  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-30 10:35:28.905  6141  6141 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 10:35:28.905  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
06-30 10:35:28.905  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 10:35:28.905  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,06-30 10:35:28.905  6141  6141 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-30 10:35:28.905  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
06-30 10:35:28.906  6141  6141 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,06-30 10:35:28.908  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 10:35:28.908  6141  6141 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 10:35:28.908  6141  6141 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 10:35:28.908  6141  6141 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 10:35:28.908  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-30 10:35:28.909  6141  6141 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 10:35:28.909  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
06-30 10:35:28.909  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 10:35:28.909  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 10:35:28.909  6141  6141 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-30 10:35:28.909  6141  6141 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-30 10:35:28.916  6120  6166 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
06-30 10:35:28.916  6120  6166 D BluetoothAdapterProperties: Setting state to 11
06-30 10:35:28.916  6120  6166 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
06-30 10:35:28.917  1033  1115 D BluetoothManagerService: Message: 60
06-30 10:35:28.917  1033  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
06-30 10:35:28.917  1033  1115 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
06-30 10:35:28.917  6120  6166 I LGBluetoothServiceJni: classInitNative: succeeds
,06-30 10:35:28.934  6162  6162 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,06-30 10:35:28.944  1033  2030 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6172 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
06-30 10:35:28.944  1033  2030 I ActivityManager: Killing 5555:com.google.android.partnersetup/u0a8 (adj 15): empty #17
06-30 10:35:28.947  6162  6162 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
06-30 10:35:28.947  6162  6162 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
06-30 10:35:28.950  1033  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
06-30 10:35:28.950  1033  1521 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
06-30 10:35:28.951  1033  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
06-30 10:35:28.951  1033  1521 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
06-30 10:35:28.951  1033  1521 E WifiStateMachine:  SupplicantStartingState CMD_DISCONNECT 0 0
06-30 10:35:28.951  1033  1521 E WifiStateMachine:  DefaultState CMD_DISCONNECT 0 0
06-30 10:35:28.952  1033  1521 E WifiStateMachine:  SupplicantStartingState CMD_RECONNECT 0 0
06-30 10:35:28.952  1033  1521 E WifiStateMachine:  DefaultState CMD_RECONNECT 0 0
06-30 10:35:28.952  1033  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,06-30 10:35:28.953  1033  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-30 10:35:28.953  1033  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
06-30 10:35:28.953  1033  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-30 10:35:28.953  1033  1521 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
06-30 10:35:28.954  1033  1521 D WifiNative-wlan0: doString: [DRIVER MACADDR]
06-30 10:35:28.955  1033  6178 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
06-30 10:35:28.955  1033  6178 D WifiMonitor: Dropping event because (p2p0) is stopped
06-30 10:35:28.955  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
06-30 10:35:28.955  1033  1521 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
06-30 10:35:28.956  1033  1521 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
06-30 10:35:28.956  1033  1521 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
06-30 10:35:28.956  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
06-30 10:35:28.956  1033  6178 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
06-30 10:35:28.957  1033  6178 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
06-30 10:35:29.050  1033  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
06-30 10:35:29.050  1033  1521 E WifiStateMachine: useWiFiOffloading() : false
06-30 10:35:29.050  1033  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
06-30 10:35:29.050  1033  1911 W libprocessgroup: failed to open /acct/uid_10008/pid_5555/cgroup.procs: No such file or directory
,06-30 10:35:29.058  6120  6166 D BluetoothBondStateMachine: make
,06-30 10:35:29.064  6120  6190 I BluetoothBondStateMachine: StableState(): Entering Off State
06-30 10:35:29.064  6120  6166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
,06-30 10:35:29.064  6120  6166 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
06-30 10:35:29.065  6120  6166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:29.065  6120  6166 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
06-30 10:35:29.065  1033  1521 D WifiNative-wlan0: doBoolean: SET update_config 1
06-30 10:35:29.067  1033  1521 D WifiNative-wlan0: SET update_config 1: returned true
06-30 10:35:29.067  1033  1521 D WifiConfigStore: Loading config and enabling all networks 
06-30 10:35:29.067  1033  1521 D WifiNative-wlan0: doString: [LIST_NETWORKS]
06-30 10:35:29.069  1033  1521 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
06-30 10:35:29.069  6120  6166 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
06-30 10:35:29.069  1949  1949 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:29.077  1563  1563 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
06-30 10:35:29.083  6120  6166 E BluetoothAdapterService: File transfer profiles supported!!
,06-30 10:35:29.084  1033  1521 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
06-30 10:35:29.088  6120  6120 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 10:35:29.088  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.089  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.089  6120  6120 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:29.089  6120  6120 V BluetoothPbapReceiver: ***********state = 11
06-30 10:35:29.090  1949  1949 D WfdService: Waiting for WifiP2p enabling
06-30 10:35:29.094  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
06-30 10:35:29.095  1033  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
06-30 10:35:29.095  1033  1521 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
06-30 10:35:29.096  1033  1521 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
06-30 10:35:29.096  5800  5800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:29.096  5800  5800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 10:35:29.096  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:29.096  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:29.096  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 10:35:29.096  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:29.096  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:29.096  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:29.096  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 10:35:29.098  5800  5800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:29.098  5800  5800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 10:35:29.099  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 10:35:29.099  1033  1033 D BluetoothHeadset: Proxy object connected
06-30 10:35:29.100  6120  6120 D HeadsetService: Received start request. Starting profile...
06-30 10:35:29.100  1860  1860 D BluetoothHeadset: Proxy object connected
06-30 10:35:29.100  6120  6120 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
06-30 10:35:29.100  6120  6166 E BluetoothAdapterService: File transfer profiles supported!!
06-30 10:35:29.100  6120  6120 D LGBluetoothHfpAdapter: Version 1.6
06-30 10:35:29.100  1860  1860 D BluetoothHeadset: Proxy object connected
06-30 10:35:29.101  1860  1860 D BluetoothHeadset: Proxy object connected
06-30 10:35:29.102  6120  6120 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 10:35:29.102  6120  6120 I BluetoothHeadsetServiceJni: classInitNative: succeeds
06-30 10:35:29.103  6120  6120 D HeadsetStateMachine: make
06-30 10:35:29.123  6120  6120 D LgDataFeature: LgDataFeature() Constructor: none
06-30 10:35:29.123  6120  6120 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 10:35:29.138  1033  1744 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6193 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:29.140  6120  6120 D HeadsetStateMachine: max_hf_connections = 1
06-30 10:35:29.140  6120  6120 I bluedroid-qcom: get_profile_interface handsfree
06-30 10:35:29.141  1033  1521 D WifiStateMachine: enableVerboseLogging : level 2
06-30 10:35:29.142  6120  6120 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
06-30 10:35:29.142   319  1366 V AudioPolicyService: registerClient() client 0xb1021e00, uid 1002
06-30 10:35:29.143   319  1366 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
06-30 10:35:29.143   319  1366 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 10:35:29.143   319  1366 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 10:35:29.143  6120  6120 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
06-30 10:35:29.143  1033  1521 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
06-30 10:35:29.143   319   319 V AudioFlinger: registerClient() client 0xb55815e0, pid 6120
06-30 10:35:29.143   319  1360 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:29.143  1033  1521 D WifiNative-wlan0: SET device_name g3_global_com: returned true
06-30 10:35:29.143   319  1360 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:29.143  1033  1521 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
06-30 10:35:29.143  2206  2223 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:29.143  2206  2223 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:29.144  1033  1983 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:29.144  1033  1983 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:29.144   319  1361 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:29.144   319  1361 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:29.144  1033  1521 D WifiNative-wlan0: SET manufacturer LGE: returned true
06-30 10:35:29.144  6120  6191 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:29.144  6120  6191 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
06-30 10:35:29.144  6120  6191 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:29.144  6120  6191 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
06-30 10:35:29.144  1033  1521 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
06-30 10:35:29.144  1033  2077 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:29.144  1033  2077 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:29.144  2206  2222 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:29.144  1563  1583 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:29.144  1563  1583 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:29.144  1563  1583 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:29.144  1563  1583 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:29.144  2206  2222 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:29.144  1860  1875 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:29.144  1860  1875 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:29.144  1860  1875 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:29.144  6120  6120 V ToneGenerator: Create Track: 0xb4928a80
06-30 10:35:29.144  1860  1875 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:29.144  6120  6120 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
06-30 10:35:29.144  6120  6120 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameC,ount 0, flags 0004
06-30 10:35:29.144  3412  3428 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:29.144  3412  3428 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:29.144  3412  3428 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:29.144  3412  3428 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:29.144  1033  1521 D WifiNative-wlan0: SET model_name LG-D855: returned true
06-30 10:35:29.145  1033  1521 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
06-30 10:35:29.145  6120  6166 E BluetoothAdapterService: File transfer profiles supported!!
06-30 10:35:29.145   319  1367 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-30 10:35:29.145   319  1367 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
06-30 10:35:29.145   319  1367 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 10:35:29.145   319  1367 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 10:35:29.145   319   319 I AudioFlinger: isAudioPlaybackHookOn() false
06-30 10:35:29.145  1033  1521 D WifiNative-wlan0: SET model_number LG-D855: returned true
06-30 10:35:29.145  1033  1521 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
06-30 10:35:29.145   319  1366 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-30 10:35:29.145   319  1366 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
06-30 10:35:29.145   319  1366 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 10:35:29.145   319  1366 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 10:35:29.146  6120  6120 V AudioSystem: getLatency() output 2, latency 50
06-30 10:35:29.146  6120  6120 V AudioSystem: getFrameCount() output 2, frameCount 960
06-30 10:35:29.146  6120  6120 V AudioTrack: createTrack_l() output 2 afLatency 50
06-30 10:35:29.146   319  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
06-30 10:35:29.146   319  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
06-30 10:35:29.146   319  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
06-30 10:35:29.146   319  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
06-30 10:35:29.146   319  1367 V AudioFlinger: createTrack() lSessionId: 21
06-30 10:35:29.147  1033  1521 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
06-30 10:35:29.147  1033  1521 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
06-30 10:35:29.147  1033  1521 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
06-30 10:35:29.147  1033  1521 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
06-30 10:35:29.148  6120  6120 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
06-30 10:35:29.148  1033  1521 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
06-30 10:35:29.148   319  1366 V AudioFlinger: acquiring 21 from 6120, for 6120
06-30 10:35:29.148   319  1366 V AudioFlinger:  added new entry for 21
06-30 10:35:29.148  6120  6120 V ToneGenerator: ToneGenerator INIT OK, time: 101811
06-30 10:35:29.148  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:29.149  1949  1949 D WfdsService: Supplicant Connection state is changed : true
06-30 10:35:29.149  6120  6192 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
06-30 10:35:29.149  1949  2275 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
06-30 10:35:29.149  6120  6192 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 10:35:29.149  1949  2275 D WfdsService: Set the WFDS Monitor: true
06-30 10:35:29.149  6120  6192 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 10:35:29.149  6120  6192 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
06-30 10:35:29.149  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:29.150   319  1367 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6120
06-30 10:35:29.150   319  1367 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
06-30 10:35:29.150   319  1367 V voice   : voice_set_parameters: enter: bt_samplerate=8000
06-30 10:35:29.150   319  1367 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
06-30 10:35:29.150   319  1367 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-30 10:35:29.150   319  1367 V voice   : voice_set_parameters: exit with code(0)
06-30 10:35:29.150   319  1367 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
06-30 10:35:29.150   319  1367 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
06-30 10:35:29.150   319  1367 V msm8974_platform: platform_set_parameters: exit with code(0)
06-30 10:35:29.150   319  1367 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-30 10:35:29.150   319  1367 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-30 10:35:29.150   319  1367 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
06-30 10:35:29.151  6120  6192 V ToneGenerator: ToneGenerator destructor
06-30 10:35:29.151  6120  6192 V ToneGenerator: stopTone
06-30 10:35:29.151  6120  6192 V ToneGenerator: Delete Track: 0xb4928a80
06-30 10:35:29.151  1949  2275 D WfdsMonitor: WfdsMonitorThread create
06-30 10:35:29.151  1949  2275 D WfdsMonitor: WFDS Monitor is created and started
06-30 10:35:29.151  1949  2275 D WfdsService: WiFi: Supplicant connection re-established
06-30 10:35:29.152  1033  1033 D BluetoothA2dp: Proxy object connected
06-30 10:35:29.152  6120  6120 D A2dpService: Received start request. Starting profile...
06-30 10:35:29.153  6120  6120 I BluetoothAvrcpServiceJni: classInitNative: succeeds
06-30 10:35:29.153  6120  6166 E BluetoothAdapterService: File transfer profiles supported!!
06-30 10:35:29.154  6120  6120 V Avrcp   : make
06-30 10:35:29.154  6120  6120 D Avrcp   : [BTUI] Use Native AVRCP : init jni
06-30 10:35:29.154  6120  6120 I bluedroid-qcom: get_profile_interface avrcp
06-30 10:35:29.154  1949  6209 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
06-30 10:35:29.155  1949  6209 E CtrlSupplicant: Succeed to open control connection
06-30 10:35:29.155  1949  6209 E CtrlSupplicant: Succeed to open monitor connection
06-30 10:35:29.155  1949  6209 D WfdsMonitor: Supplicant connection established
06-30 10:35:29.155  1949  2275 D WfdsService: Connected to the supplicant for wfds
06-30 10:35:29.156  6120  6192 V AudioTrack: ~AudioTrack, releasing session id from 6120 on behalf of 6120
06-30 10:35:29.156   319   319 V AudioFlinger: releasing 21 from 6120 for 6120
06-30 10:35:29.156   319   319 V AudioFlinger:  decremented refcount to 0
06-30 10:35:29.156   319   319 V AudioFlinger: purging stale effects
06-30 10:35:29.156   319   319 V AudioPolicyService: AudioCommandThread() adding release output 2
06-30 10:35:29.156   319   319 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
06-30 10:35:29.156   319  1259 V AudioPolicyService: AudioCommandThread() waking up
06-30 10:35:29.157   319  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
06-30 10:35:29.157   319  1259 V AudioPolicyManager: releaseOutput() 2
06-30 10:35:29.157   319  1259 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 10:35:29.157   319   319 V AudioFlinger: PlaybackThread::Track destructor
06-30 10:35:29.157   319   319 V AudioFlinger: removeClient_l() pid 6120, calling pid 319
06-30 10:35:29.157  1033  1521 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 10:35:29.157  1033  1521 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
06-30 10:35:29.161  6120  6120 V AudioManager: registerRemoteController: size of Media player list: 0
06-30 10:35:29.161  1033  1521 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
06-30 10:35:29.161  1033  1521 D WifiNative-HAL: Setting external_sim to 1
06-30 10:35:29.162  1033  1521 D WifiNative-wlan0: doBoolean: SET external_sim 1
06-30 10:35:29.165  6120  6120 E AudioManager: No RCC entry present to update
06-30 10:35:29.165  6120  6120 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
06-30 10:35:29.167  6120  6120 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
06-30 10:35:29.168  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
06-30 10:35:29.168  6120  6120 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
06-30 10:35:29.169  6120  6166 E BluetoothAdapterService: File transfer profiles supported!!
06-30 10:35:29.169  1033  1521 D WifiNative-wlan0: SET external_sim 1: returned true
06-30 10:35:29.169  1033  1521 I WifiNative-HAL: startHal
06-30 10:35:29.170  1033  1521 E wifi    : getStaticLongField sWifiHalHandle 0x987dd8dc
06-30 10:35:29.170  1033  1521 E WifiHAL : Could not connect handle
06-30 10:35:29.170  1033  1521 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301942
06-30 10:35:29.170  1033  1521 I WifiNative-HAL: Could not start hal
06-30 10:35:29.170  1033  1521 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 10:35:29.170  1033  1521 I WifiNative-HAL: startHal
06-30 10:35:29.170  1033  1521 E wifi    : getStaticLongField sWifiHalHandle 0x987dd85c
06-30 10:35:29.170  1033  1521 E WifiHAL : Could not connect handle
06-30 10:35:29.170  1033  1521 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x50193e
06-30 10:35:29.170  1033  1521 I WifiNative-HAL: Could not start hal
06-30 10:35:29.170  1033  1521 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
06-30 10:35:29.171  1033  1521 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
06-30 10:35:29.171  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
06-30 10:35:29.171  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
,06-30 10:35:29.174  1033  1521 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
06-30 10:35:29.182  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:29.191  1033  1947 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6217 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
06-30 10:35:29.193  1033  1033 D WifiHS20: hidePasspointNotification off =false
06-30 10:35:29.194  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
06-30 10:35:29.194  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
06-30 10:35:29.194  1033  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
06-30 10:35:29.194  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
06-30 10:35:29.194  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
06-30 10:35:29.194  1033  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
06-30 10:35:29.194  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
06-30 10:35:29.195  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
06-30 10:35:29.195  1033  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
06-30 10:35:29.195  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
06-30 10:35:29.195  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
06-30 10:35:29.195  1033  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
06-30 10:35:29.195  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
06-30 10:35:29.195  6162  6162 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
06-30 10:35:29.195  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.195  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.195  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 10:35:29.195  1033  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
06-30 10:35:29.195  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
06-30 10:35:29.195  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
06-30 10:35:29.196  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
06-30 10:35:29.196  1033  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
06-30 10:35:29.196  1033  1521 E WifiNative: : [101,846,071 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
06-30 10:35:29.196  1033  1521 D WifiNative-wlan0: doBoolean: RECONNECT
06-30 10:35:29.197  1033  1521 D WifiNative-wlan0: RECONNECT: returned true
06-30 10:35:29.197  1033  1521 D WifiNative-wlan0: doString: [STATUS]
06-30 10:35:29.197  1033  1521 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
06-30 10:35:29.197  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
06-30 10:35:29.197  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
06-30 10:35:29.198  1033  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
06-30 10:35:29.198  1033  1521 D WifiNative-wlan0: doBoolean: SET ps 1
06-30 10:35:29.198  1033  1521 D WifiNative-wlan0: SET ps 1: returned true
06-30 10:35:29.199  6120  6166 E BluetoothAdapterService: File transfer profiles supported!!
06-30 10:35:29.200  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
06-30 10:35:29.200  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
06-30 10:35:29.201  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.201  1563  1563 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:29.201  1033  1520 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.202   314   891 D CommandListener: Setting iface cfg
06-30 10:35:29.202   314   891 D CommandListener: Trying to bring up p2p0
06-30 10:35:29.204  1033  1520 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-30 10:35:29.204  1033  1520 D LGWifiP2pService: P2pEnablingState
06-30 10:35:29.204  1033  1520 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.204  1033  1520 D LGWifiP2pService: P2p socket connection successful
06-30 10:35:29.204  1033  1520 D LGWifiP2pService: P2pEnabledState
06-30 10:35:29.216  1033  1527 D WifiService: New client listening to asynchronous messages
,06-30 10:35:29.235  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:29.236  6172  6215 W FormManager: Network not available. Please check & try again.
,06-30 10:35:29.236  1033  1521 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
06-30 10:35:29.237  1033  1520 D LGWifiP2pService: sending p2p connection changed broadcast
06-30 10:35:29.237  1033  1521 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
06-30 10:35:29.237  1033  1521 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
06-30 10:35:29.238  1033  1520 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
06-30 10:35:29.239  1949  1949 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
06-30 10:35:29.239  1949  1949 D WfdsService: WifiP2pState is changed : true
06-30 10:35:29.240  1949  2275 D WfdsService: Receive the WFDS_ENABLE Method
06-30 10:35:29.240  1949  2275 D WfdsService: Set the WFDS Monitor: true
06-30 10:35:29.240  1949  2275 D WfdsService: Connected to the supplicant for wfds
06-30 10:35:29.240  1949  2275 D WfdsJNI : doCommand: WFDS_SET TRUE
06-30 10:35:29.240  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
06-30 10:35:29.240  6162  6162 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
06-30 10:35:29.240  1033  1033 D RttService: SCAN_AVAILABLE : 3
06-30 10:35:29.240  1033  1540 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.240  1033  1539 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.240  1033  1539 I WifiNative-HAL: startHal
06-30 10:35:29.240  1949  2275 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
06-30 10:35:29.240  6162  6162 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
06-30 10:35:29.241  6120  6166 E BluetoothAdapterService: File transfer profiles supported!!
06-30 10:35:29.242  1033  1520 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
06-30 10:35:29.242  1033  1520 D WifiNative-p2p0: doBoolean: SET device_name G3
06-30 10:35:29.242  1949  1949 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
06-30 10:35:29.242  1033  1521 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
06-30 10:35:29.243  1033  1521 E WifiStateMachine:  DisconnectedState what:132106 1 0
06-30 10:35:29.243  1949  1949 D WfdsService: isConnected: false
06-30 10:35:29.243  1949  2275 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
06-30 10:35:29.243  1033  1521 E WifiStateMachine:  ConnectModeState what:132106 1 0
06-30 10:35:29.243  1033  1521 E WifiStateMachine:  DriverStartedState what:132106 1 0
06-30 10:35:29.244  1033  1521 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
06-30 10:35:29.244  6162  6162 E wpa_supplicant: nWIFIDualbandAPConnection: 1
06-30 10:35:29.244  1033  1521 E WifiStateMachine:  DisconnectedState what:132096 -100 0
06-30 10:35:29.244  1033  1521 E WifiStateMachine:  ConnectModeState what:132096 -100 0
06-30 10:35:29.244  1033  1521 E WifiStateMachine:  DriverStartedState what:132096 -100 0
06-30 10:35:29.244  1949  2275 D WfdsService: selectPreferredScanChannel [36]
06-30 10:35:29.244  1949  2275 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
06-30 10:35:29.245  1033  1521 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
06-30 10:35:29.245  6162  6162 E wpa_supplicant: disconnect_rssi_lvl: -100
06-30 10:35:29.245  1033  1521 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
06-30 10:35:29.245  1033  1521 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
06-30 10:35:29.245  1033  1521 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
06-30 10:35:29.246  1033  1520 D WifiNative-p2p0: SET device_name G3: returned true
06-30 10:35:29.246  1033  1520 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
06-30 10:35:29.246  1033  1520 D LGWifiP2pService: before postfix = G3
06-30 10:35:29.246  1033  1520 D WifiServerServiceExt: postfix byte check : 2
06-30 10:35:29.246  1033  1520 D LGWifiP2pService: after postfix = G3
06-30 10:35:2,9.246  1033  1520 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
06-30 10:35:29.247  1033  1520 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
06-30 10:35:29.247  1033  1539 E wifi    : getStaticLongField sWifiHalHandle 0x94b8799c
06-30 10:35:29.247  1033  1539 E WifiHAL : Could not connect handle
06-30 10:35:29.247  1033  1539 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x6012ee
06-30 10:35:29.247  1033  1539 I WifiNative-HAL: Could not start hal
06-30 10:35:29.247  1033  1539 E WifiScanningService: could not start HAL
06-30 10:35:29.247  1033  1520 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
,06-30 10:35:29.248  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
06-30 10:35:29.252  1033  1520 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
06-30 10:35:29.252  1033  1520 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
06-30 10:35:29.252  1033  1520 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
06-30 10:35:29.252  1033  1520 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
06-30 10:35:29.253  1033  1520 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
06-30 10:35:29.253  1033  1520 D WifiNative-HAL: p2pGetDeviceAddress
06-30 10:35:29.253  1033  1520 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
06-30 10:35:29.253  1033  1520 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
06-30 10:35:29.253  1033  1520 D WifiNative-p2p0: doBoolean: P2P_FLUSH
06-30 10:35:29.253  1033  1520 D WifiNative-p2p0: P2P_FLUSH: returned true
06-30 10:35:29.254  1033  1520 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
06-30 10:35:29.254  1033  1520 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
06-30 10:35:29.254  1033  1520 D WifiNative-p2p0: doString: [LIST_NETWORKS]
06-30 10:35:29.254  6120  6166 V LGMDMManager: Create singleton instance
06-30 10:35:29.255  1949  1949 I WfdStateTracker: handleP2pThisDeviceChanged
06-30 10:35:29.255  1949  1949 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
06-30 10:35:29.255  1949  1949 D WfdsService: Update P2p Interface State: 3
06-30 10:35:29.256  6172  6227 V FormManager: Network unavailable.
06-30 10:35:29.256  1033  1520 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
06-30 10:35:29.256  1033  1520 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
06-30 10:35:29.257  6120  6166 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
06-30 10:35:29.263  1033  1520 D WifiNative-p2p0: SAVE_CONFIG: returned true
,06-30 10:35:29.263  1033  1520 D LGWifiP2pService: sending p2p persistent groups changed broadcast
06-30 10:35:29.263  1033  1520 D LGWifiP2pService: InactiveState
06-30 10:35:29.264  1033  1520 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.264  1033  1520 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.264  1033  1520 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
06-30 10:35:29.264  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,06-30 10:35:29.265  6162  6162 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 10:35:29.265  6162  6162 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
06-30 10:35:29.265  6162  6162 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.265  6162  6162 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.266  1949  6209 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
06-30 10:35:29.266  1949  6209 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 10:35:29.266  1949  6209 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 10:35:29.266  1033  6178 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
06-30 10:35:29.266  1033  6178 E WifiMonitor: WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 10:35:29.266  1033  6178 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 10:35:29.266  1033  6178 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 10:35:29.266  1033  6178 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 10:35:29.266  1033  6178 E WifiMonitor: WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.266  1033  6178 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.266  1033  6178 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.266  1033  6178 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 10:35:29.266  1033  6178 E WifiMonitor: WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.266  1033  1520 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
06-30 10:35:29.266  1033  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.267  1033  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.267  1033  1520 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.266  1033  6178 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.267  1033  6178 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.267  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
06-30 10:35:29.267  6162  6162 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 10:35:29.268  1033  1520 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.268  1033  1520 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.268  1033  1520 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.268  6162  6162 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
06-30 10:35:29.268  6162  6162 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.268  1033  1520 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.268  1033  1520 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.268  1033  1520 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.268 , 1033  1520 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.268  1033  1520 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.268  1033  1520 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.268  6162  6162 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.268  1033  1033 E WifiServerServiceExt: No p2p device connected
06-30 10:35:29.268  1033  1521 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
06-30 10:35:29.269  1949  2275 W WfdsService: DefaultState - msg [9441285] is not handled
06-30 10:35:29.269  1033  1520 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.269  1033  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.269  1033  1521 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
06-30 10:35:29.269  1033  1521 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
06-30 10:35:29.269  1033  1521 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
06-30 10:35:29.269  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
06-30 10:35:29.269  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
06-30 10:35:29.269  6162  6162 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-30 10:35:29.270  1949  6209 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 10:35:29.270  1949  6209 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 10:35:29.270  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
06-30 10:35:29.270  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 10:35:29.270  1033  6178 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 10:35:29.270  1033  6178 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 10:35:29.270  1033  6178 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 10:35:29.270  1033  6178 E WifiMonitor: WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.270  1033  6178 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.270  1033  6178 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.270  1033  6178 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 10:35:29.270  1033  6178 E WifiMonitor: WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.270  1033  6178 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.270  1033  6178 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 10:35:29.270  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
06-30 10:35:29.270  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-30 10:35:29.270  1033  6178 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-30 10:35:29.270  1033  6178 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-30 10:35:29.270  1033  1521 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
06-30 10:35:29.270  1033  1521 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
06-30 10:35:29.271  1033  1521 D WifiNative-wlan0: BSS_FLUSH 0: ret,urned true
06-30 10:35:29.271  1033  1521 D WifiNative-wlan0: doBoolean: SCAN
06-30 10:35:29.271  1033  1521 D WifiNative-wlan0: SCAN: returned false
06-30 10:35:29.271  1033  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=101921  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
06-30 10:35:29.272  1033  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=101922  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
06-30 10:35:29.273  1033  1521 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 10:35:29.273  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.273  1033  1521 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 10:35:29.273  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.273  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-30 10:35:29.273  1033  1521 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 10:35:29.273  1033  1521 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 10:35:29.273  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.273  1033  1521 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 10:35:29.273  1563  1563 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:29.274  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 10:35:29.274  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
06-30 10:35:29.280  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:29.286  6193  6193 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
06-30 10:35:29.287  6193  6193 W LG Account v2.2: No ProfileInfo entries
06-30 10:35:29.287  6193  6193 I LG Account v2.2: isEnabled: false
06-30 10:35:29.287  6193  6193 I Feature : [Lifetracker]ver: 4.21.112(40211120)
06-30 10:35:29.287  6193  6193 I Feature : [Lifetracker]Country: EU
06-30 10:35:29.287  6193  6193 I Feature : [Lifetracker]Operator: OPEN
06-30 10:35:29.287  6193  6193 I Feature : [Lifetracker]Ranking support: false
06-30 10:35:29.287  6193  6193 I Feature : [Lifetracker]Comfort support: false
06-30 10:35:29.287  6193  6193 I Feature : [Lifetracker]Accessory: true
06-30 10:35:29.287  6193  6193 I Feature : [Lifetracker]Health device: true
06-30 10:35:29.287  6193  6193 I Feature : [Lifetracker]Extra Pedometer: false
06-30 10:35:29.287  6193  6193 I Feature : [Lifetracker]Blood glucose device: false
06-30 10:35:29.287  6193  6193 I Feature : [Lifetracker]Device Number: 3
06-30 10:35:29.291  1033  1983 V SIM_STK : Menu title from STK is T-Mobile
06-30 10:35:29.291  1033  1983 V SIM_STK : Menu title from STK is T-Mobile
06-30 10:35:29.296  6172  6227 V FormManager: Network unavailable.
06-30 10:35:29.299  6141  6141 D BluetoothPermissionRequest: onReceive
06-30 10:35:29.299  6141  6141 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
06-30 10:35:29.311  1033  1115 D BluetoothManagerService: Message: 20
06-30 10:35:29.311  1033  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a7e0cba:true
,06-30 10:35:29.312  1033  2056 I ActivityManager: Killing 5582:com.lge.appbox.client/u0a11 (adj 15): empty #17
06-30 10:35:29.324  6217  6217 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,06-30 10:35:29.399  1033  2030 W libprocessgroup: failed to open /acct/uid_10011/pid_5582/cgroup.procs: No such file or directory
,06-30 10:35:29.405  1033  1048 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
06-30 10:35:29.416  1033  2056 I ActivityManager: Killing 5604:com.android.contacts/u0a19 (adj 15): empty #17
06-30 10:35:29.416  6141  6141 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,06-30 10:35:29.427  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
06-30 10:35:29.433  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
06-30 10:35:29.434  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
06-30 10:35:29.434  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
06-30 10:35:29.434  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
06-30 10:35:29.435  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-30 10:35:29.435  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
06-30 10:35:29.435  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
06-30 10:35:29.435  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
06-30 10:35:29.435  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-30 10:35:29.435  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,06-30 10:35:29.437  6120  6120 I BluetoothA2dpServiceJni: classInitNative
06-30 10:35:29.437  6120  6120 I BluetoothA2dpServiceJni: classInitNative: succeeds
06-30 10:35:29.437  6120  6120 D A2dpStateMachine: make
06-30 10:35:29.438  6120  6120 I bluedroid-qcom: get_profile_interface a2dp
06-30 10:35:29.438  6120  6244 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
06-30 10:35:29.440  6120  6120 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
06-30 10:35:29.441  6120  6120 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
06-30 10:35:29.442  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:29.442  6120  6243 D A2dpStateMachine: Enter Disconnected: -2
,06-30 10:35:29.442  6120  6120 D HeadsetStateMachine: Proxy object connected
06-30 10:35:29.443  6120  6120 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
06-30 10:35:29.443  6120  6120 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
06-30 10:35:29.444  1860  1860 D BluetoothPhoneService.BluetoothLTECall:  call mBluetoothHeadset.phoneStateChanged()
06-30 10:35:29.445  1860  1860 W BluetoothHeadset: Proxy not attached to service
06-30 10:35:29.445  6120  6120 I BluetoothHidServiceJni: classInitNative: succeeds
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: java.lang.Throwable
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 10:35:29.445  1860  1860 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-30 10:35:29.447  6120  6120 D HidService: Received start request. Starting profile...
06-30 10:35:29.447  6120  6120 I bluedroid-qcom: get_profile_interface hidhost
06-30 10:35:29.447  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
,06-30 10:35:29.451  6120  6120 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 10:35:29.451  6120  6192 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:35:29.451  6120  6120 I BluetoothHealthServiceJni: classInitNative: succeeds
06-30 10:35:29.452  6120  6192 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-30 10:35:29.453  6120  6120 D HealthService: Received start request. Starting profile...
06-30 10:35:29.453  6120  6192 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-30 10:35:29.455  6120  6120 I bluedroid-qcom: get_profile_interface health
06-30 10:35:29.455  6120  6120 I LGBluetoothHealthServiceJni: classInitNative: succeeds
06-30 10:35:29.455  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:29.456  6120  6120 I BluetoothPanServiceJni: classInitNative(L105): succeeds
06-30 10:35:29.458  6120  6120 D PanService: Received start request. Starting profile...
06-30 10:35:29.458  6120  6120 D BluetoothPanServiceJni: initializeNative(L110): pan
06-30 10:35:29.458  6120  6120 I bluedroid-qcom: get_profile_interface pan
,06-30 10:35:29.520  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
06-30 10:35:29.520  1033  6178 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,06-30 10:35:29.521  1033  1521 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
06-30 10:35:29.521  1033  1521 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
06-30 10:35:29.521  6162  6162 E wpa_supplicant: USIM:  scard_init function
06-30 10:35:29.521  1033  1521 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
06-30 10:35:29.522  1033  1521 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
06-30 10:35:29.522  1033  1521 I WifiNative-HAL: startHal
06-30 10:35:29.522  1033  1521 E wifi    : getStaticLongField sWifiHalHandle 0x987dd8cc
06-30 10:35:29.522  1033  1521 E WifiHAL : Could not connect handle
06-30 10:35:29.522  1033  1521 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501dde
06-30 10:35:29.522  1033  1521 I WifiNative-HAL: Could not start hal
06-30 10:35:29.522  1033  1521 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
06-30 10:35:29.522  6162  6162 I wpa_supplicant: Trying to associate with SSID 'NG700'
06-30 10:35:29.522  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
06-30 10:35:29.522  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
06-30 10:35:29.523  1033  6178 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
06-30 10:35:29.523  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
06-30 10:35:29.523  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
06-30 10:35:29.553  1033  1984 W libprocessgroup: failed to open /acct/uid_10019/pid_5604/cgroup.procs: No such file or directory
,06-30 10:35:29.562  6120  6120 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
06-30 10:35:29.562  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:29.562  1033  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=102212  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
06-30 10:35:29.565  6120  6120 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
06-30 10:35:29.567  1033  2056 I ActivityManager: Killing 5456:com.android.defcontainer/u0a4 (adj 15): empty #17
06-30 10:35:29.568  1033  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=102218  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,06-30 10:35:29.572  6120  6120 D BtGatt.DebugUtils: handleDebugAction() action=null
06-30 10:35:29.572  6120  6120 D BtGatt.GattService: Received start request. Starting profile...
06-30 10:35:29.573  6120  6120 D BtGatt.GattService: start()
06-30 10:35:29.573  6120  6120 I bluedroid-qcom: get_profile_interface gatt
06-30 10:35:29.573  6120  6120 D BtGatt.AdvertiseManager: advertise manager created
06-30 10:35:29.581  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-30 10:35:29.587  1033  1527 D WifiService: New client listening to asynchronous messages
,06-30 10:35:29.614  6141  6141 D LgDataFeature: LgDataFeature() Constructor: none
,06-30 10:35:29.614  6141  6141 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 10:35:29.620  6141  6141 D WiFiOffLoadUpdatePriority: remove : truetruetrue
06-30 10:35:29.632  6162  6162 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,06-30 10:35:29.634  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
06-30 10:35:29.634  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
06-30 10:35:29.635  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
06-30 10:35:29.635  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with f4:f2:6d:22:99:3e
06-30 10:35:29.635  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-30 10:35:29.635  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-30 10:35:29.642  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-30 10:35:29.642  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-30 10:35:29.643  6162  6162 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-30 10:35:29.643  6162  6162 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,06-30 10:35:29.646  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
06-30 10:35:29.647  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-30 10:35:29.647  1033  6178 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-30 10:35:29.647  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
06-30 10:35:29.647  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-30 10:35:29.647  1033  6178 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-30 10:35:29.647  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-30 10:35:29.647  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-30 10:35:29.717  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.717  1563  1563 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-30 10:35:29.720  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.721  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.721  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-30 10:35:29.722  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:29.728  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:35:29.728  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.728  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
06-30 10:35:29.729  1033  1911 W libprocessgroup: failed to open /acct/uid_10004/pid_5456/cgroup.procs: No such file or directory
06-30 10:35:29.733  1033  1115 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,06-30 10:35:29.747  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.747  1563  1563 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-30 10:35:29.748  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:29.750  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 10:35:29.750  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
06-30 10:35:29.750  1033  1521 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
06-30 10:35:29.750  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:29.751  1033  1521 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
06-30 10:35:29.752  1033  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=102401  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
06-30 10:35:29.752  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:29.752  6120  6120 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
06-30 10:35:29.752  1033  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=102402  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
06-30 10:35:29.753  1033  1521 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102403
06-30 10:35:29.753  6120  6120 V BluetoothMapService: BluetoothMapBinder()
06-30 10:35:29.753  1033  1521 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102403
06-30 10:35:29.753  6120  6120 D BluetoothMapService: Received start request. Starting profile...
06-30 10:35:29.753  6120  6120 D BluetoothMapService: start()
,06-30 10:35:29.754  1033  1521 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102403
06-30 10:35:29.754  1033  1521 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102404
06-30 10:35:29.754  1033  1521 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102404
06-30 10:35:29.755  1033  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=102405  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
06-30 10:35:29.756  6120  6120 D BluetoothMapEmailSettingsLoader: Found 0 applications
06-30 10:35:29.756  6120  6120 D BluetoothMapEmailAppObserver: createReceiver()
06-30 10:35:29.757  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.757  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.757  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
06-30 10:35:29.757  6120  6120 D BluetoothMapEmailAppObserver: initObservers()
06-30 10:35:29.758  6120  6120 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
06-30 10:35:29.758  1033  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=102408  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
06-30 10:35:29.759  1033  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=102409  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
06-30 10:35:29.760  1033  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=102409  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
06-30 10:35:29.761  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.761  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.761  1033  1521 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=102410
06-30 10:35:29.761  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
06-30 10:35:29.761  1033  1521 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=102411
06-30 10:35:29.762  1033  1521 D WifiNative-wlan0: doString: [STATUS]
06-30 10:35:29.762  1033  6178 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-30 10:35:29.762  1033  6178 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-30 10:35:29.763  1033  1521 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
06-30 10:35:29.766  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:29.767  1033  1521 I WifiServiceExtension: setVHTCapabilityType  : false
,06-30 10:35:29.769  6120  6120 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 10:35:29.771  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.771  1563  1563 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:29.772  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:29.772  6120  6120 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 10:35:29.773  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.773  1563  1563 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:29.774  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:29.776  6120  6120 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 10:35:29.778  1033  1521 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
06-30 10:35:29.778  1033  1521 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
06-30 10:35:29.779  6120  6120 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 10:35:29.780  6120  6120 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
06-30 10:35:29.781  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.781  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.781  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
06-30 10:35:29.782  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.782  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:29.782  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,06-30 10:35:29.784  6120  6120 V PanService: [BTUI] SIM Extra State :ABSENT
06-30 10:35:29.787  6120  6120 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
06-30 10:35:29.787  6120  6120 V BluetoothMapService: Handler(): got msg=1
06-30 10:35:29.788  6120  6166 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
06-30 10:35:29.788  6120  6166 I bluedroid-qcom: enable
06-30 10:35:29.788  6120  6254 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
06-30 10:35:29.788  6120  6254 I bt-btu  : btu_task pending for preload complete event
06-30 10:35:29.788  6120  6166 I bt_hci_bdroid: init
06-30 10:35:29.789  1033  1381 V AlarmManager: RTC_WAKEUP set : Alarm{267f3837 type 0 when 1467275725788 com.android.vending} when 1467275725788
06-30 10:35:29.791  6120  6120 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:29.792  6120  6166 I bt_vendor: bt-vendor : init
06-30 10:35:29.792  6120  6166 I bt_vendor: bt-vendor : get_bt_soc_type
06-30 10:35:29.792  6120  6166 E bt_vendor: get_bt_soc_type: Failed to get soc type
06-30 10:35:29.792  6120  6166 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
06-30 10:35:29.792  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.792  6120  6166 D bt_userial_mct: userial_init
06-30 10:35:29.792  1563  1563 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:29.792  6120  6166 D bt_hci_bdroid: set_power 1
06-30 10:35:29.792  6120  6166 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
06-30 10:35:29.792  6120  6166 I bt_vendor: Starting hciattach daemon
06-30 10:35:29.792  6120  6166 I bt_vendor: try to set true
,06-30 10:35:29.778  6258  6258 W sh      : type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:29.778  6258  6258 W sh      : type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:29.794  6120  6120 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 10:35:29.795  6120  6120 V BluetoothSapReceiver: [BTUI] region:EU country:EU
06-30 10:35:29.795  6120  6120 V BluetoothSapReceiver: SapReceiver onReceive 
06-30 10:35:29.795  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:29.797  6120  6120 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:29.797  6120  6120 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
06-30 10:35:29.804  6259  6259 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,06-30 10:35:29.808  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.808  1563  1563 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:29.808  1033  1521 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
06-30 10:35:29.809  1033  1528 D ConnectivityService: Got NetworkAgent Messenger
06-30 10:35:29.810  1033  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
06-30 10:35:29.810  1033  1528 D ConnectivityService: NetworkAgent connected
06-30 10:35:29.810  1033  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-30 10:35:29.810  1033  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
06-30 10:35:29.811  1033  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
06-30 10:35:29.811  1033  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
06-30 10:35:29.814  1033  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
06-30 10:35:29.814  1033  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-30 10:35:29.814  1033  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
06-30 10:35:29.815  1033  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
06-30 10:35:29.815  1033  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
06-30 10:35:29.817  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:29.818  1033  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
,06-30 10:35:29.820   314   891 D CommandListener: Setting iface cfg
06-30 10:35:29.840  1033  2030 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6266 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,06-30 10:35:29.842  1033  6262 D DhcpStateMachine: StoppedState
06-30 10:35:29.842  1033  1521 E WifiStateMachine: Start Dhcp Watchdog 1
06-30 10:35:29.842  1033  6262 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.842  1033  6262 D DhcpStateMachine: WaitBeforeStartState
06-30 10:35:29.842  6268  6268 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
06-30 10:35:29.842  1033  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=102492  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 10:35:29.843  1033  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=102493  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 10:35:29.843  1033  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=102493  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 10:35:29.844  1033  1521 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
06-30 10:35:29.844  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
06-30 10:35:29.844  1033  1521 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
06-30 10:35:29.845  1033  1521 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
06-30 10:35:29.845  1033  1521 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
06-30 10:35:29.845  1033  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-30 10:35:29.847  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 10:35:29.847  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
06-30 10:35:29.847  1033  1521 E WifiStateMachine:  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
06-30 10:35:29.848  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
06-30 10:35:29.848  1033  1521 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
06-30 10:35:29.848  1033  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
06-30 10:35:29.853  1033  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
06-30 10:35:29.853  6276  6276 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
06-30 10:35:29.853  6141  6141 D WiFiOffLoadUpdatePriority: remove1
06-30 10:35:29.853  6141  6141 V WiFiOffLoadSharedPrefsUtils: save remove
,06-30 10:35:29.854  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 10:35:29.854  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
06-30 10:35:29.856  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 10:35:29.856  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
06-30 10:35:29.856  1033  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=102506  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 10:35:29.857  1033  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=102506  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 10:35:29.857  1033  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=102507  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 10:35:29.858  1033  1521 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1603085374] from screen [on:0 period:-1603085374]
06-30 10:35:29.859  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1603085373]
06-30 10:35:29.859  1033  1521 I WifiNative-HAL: startHal
06-30 10:35:29.859  1033  1521 E wifi    : getStaticLongField sWifiHalHandle 0x987dd8bc
06-30 10:35:29.859  1033  1521 E WifiHAL : Could not connect handle
06-30 10:35:29.859  1033  1521 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x20222e
06-30 10:35:29.859  1033  1521 I WifiNative-HAL: Could not start hal
06-30 10:35:29.860  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:35:29.866  1033  1528 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
06-30 10:35:29.866  1033  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:29.866  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:29.866  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-30 10:35:29.867  6280  6280 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
06-30 10:35:29.867  1033  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:29.867  1033  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:29.867  1033  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:29.868  1033  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:29.868  1033  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-30 10:35:29.868  1033  1521 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
06-30 10:35:29.869  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
06-30 10:35:29.869  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
06-30 10:35:29.874  6286  6286 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
06-30 10:35:29.876  6141  6141 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
06-30 10:35:29.876  6141  6141 D WiFiOffLoadBroadcast: S: false, R: false
06-30 10:35:29.881  6288  6288 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
06-30 10:35:29.885  1033  1947 V SIM_STK : Menu title from STK is T-Mobile
,06-30 10:35:29.889  6289  6289 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
06-30 10:35:29.893  6266  6266 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:35:29.902  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,06-30 10:35:29.902  1033  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
06-30 10:35:29.903  1033  1521 D WifiNative-wlan0: doBoolean: SET ps 0
06-30 10:35:29.903  6291  6291 I libmdmdetect: ESOC framework not supported
06-30 10:35:29.903  6291  6291 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
06-30 10:35:29.904  1033  1521 D WifiNative-wlan0: SET ps 0: returned true
06-30 10:35:29.904  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
06-30 10:35:29.904  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
06-30 10:35:29.905  1033  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
06-30 10:35:29.905  1033  1521 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
06-30 10:35:29.905  1033  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26ef19be target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.905  1033  1521 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-30 10:35:29.905  1033  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26ef19be target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.905  1033  6262 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:29.905  1033  1521 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-30 10:35:29.905  1033  1521 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
06-30 10:35:29.905  1033  6262 D DhcpStateMachine: DHCP Start wake lock is acquired.
06-30 10:35:29.908  6291  6291 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
06-30 10:35:29.908  6291  6291 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
06-30 10:35:29.908  6291  6291 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
06-30 10:35:29.908  6291  6291 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
06-30 10:35:29.908  6291  6291 D bthci_qcomm_common: [BTUI]     LE: Class 2
06-30 10:35:29.908  6291  6291 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
06-30 10:35:29.908  6291  6291 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
06-30 10:35:29.908  1033  1521 E WifiStateMachine:  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
06-30 10:35:29.908  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
06-30 10:35:29.908  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 10:35:29.908  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
06-30 10:35:29.908  1033  1521 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
06-30 10:35:29.909  6141  6141 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
06-30 10:35:29.910  6141  6141 D WiFiOffLoadUpdatePriority: connected SSID: null
06-30 10:35:29.910  6141  6141 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
06-30 10:35:29.911  1033  1983 D WifiServiceImplEx: addOrUpdateNetwork pid=6141, uid=1000, packageName=android.uid.system:1000
,06-30 10:35:29.911  1033  1983 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
06-30 10:35:29.912  1033  1521 E WifiStateMachine:  ObtainingIpState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
06-30 10:35:29.912  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
06-30 10:35:29.912  1033  1521 E WifiStateMachine:  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
06-30 10:35:29.912  1033  1521 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
06-30 10:35:29.912  1033  1521 D WifiServerServiceExt: addOrUpdateNetwork: mThisIsFirstEnableing = false
06-30 10:35:29.913  1033  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 ssid 4e47373030
06-30 10:35:29.931  1033  1521 D WifiNative-wlan0: SET_NETWORK 0 ssid 4e47373030: returned true
06-30 10:35:29.931  1033  1521 E WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
06-30 10:35:29.931  1033  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
06-30 10:35:29.931  1033  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
06-30 10:35:29.931  1033  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
06-30 10:35:29.932  1033  1521 D WifiNative-wlan0: SET_NETWORK 0 key_mgmt WPA-PSK: returned true
06-30 10:35:29.932  1033  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 proto WPA RSN
06-30 10:35:29.932  1033  1521 D WifiNative-wlan0: SET_NETWORK 0 proto WPA RSN: returned true
06-30 10:35:29.932  1033  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
06-30 10:35:29.932  1033  1521 D WifiNative-wlan0: SET_NETWORK 0 pairwise TKIP CCMP: returned true
06-30 10:35:29.933  1033  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
,06-30 10:35:29.933  1033  1521 D WifiNative-wlan0: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
06-30 10:35:29.933  1033  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 priority 300
06-30 10:35:29.933  1033  1521 D WifiNative-wlan0: SET_NETWORK 0 priority 300: returned true
06-30 10:35:29.934  1033  1521 E WifiConfigStore: will read network variables netId=0
06-30 10:35:29.938  1033  1521 E WifiConfigStore: writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
06-30 10:35:29.938  1033  1521 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
06-30 10:35:29.939  6141  6141 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
06-30 10:35:29.939  6141  6141 D WiFiOffLoadUpdatePriority: configuration updated: 0
06-30 10:35:29.939  1033  1521 E WifiStateMachine:  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
06-30 10:35:29.939  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
06-30 10:35:29.940  1033  1521 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
06-30 10:35:29.940  1033  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
06-30 10:35:29.945  1033  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
,06-30 10:35:29.945  6141  6141 D WiFiOffLoadUpdatePriority: configuration saved: true
06-30 10:35:29.956  6217  6217 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,06-30 10:35:29.959  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-30 10:35:29.961  6172  6294 W FormManager: Network not available. Please check & try again.
06-30 10:35:29.963  6172  6295 V FormManager: Network unavailable.
06-30 10:35:29.964  6172  6295 V FormManager: Network unavailable.
,06-30 10:35:29.971  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:29.979  3266  3266 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,06-30 10:35:29.979  3266  3266 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 10:35:29.980  3266  3266 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 10:35:29.982  3266  3266 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 10:35:29.986  3266  6296 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 10:35:29.986  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 10:35:29.991  3266  6297 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 10:35:29.991  3266  6297 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,06-30 10:35:29.992  6217  6217 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
06-30 10:35:29.995  6217  6217 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 10:35:29.995  6217  6217 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 10:35:29.997  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:35:30.001  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.014  5688  5688 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,06-30 10:35:30.047  1033  1048 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6300 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
06-30 10:35:30.054  1033  1048 I ActivityManager: Killing 5631:com.lge.email/u0a23 (adj 15): empty #17
06-30 10:35:30.106  1033  6262 D DhcpStateMachine: DHCPV4 request on wlan0
,06-30 10:35:30.107  1033  6262 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
06-30 10:35:30.107  1033  6262 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
06-30 10:35:30.098  6317  6317 W dhcpcd  : type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:30.098  6317  6317 W dhcpcd  : type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:30.140  6317  6317 I dhcpcd  : version 5.5.6 starting
,06-30 10:35:30.143  6317  6317 E dhcpcd  : get_duid: m
06-30 10:35:30.143  6317  6317 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
06-30 10:35:30.143  6317  6317 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,06-30 10:35:30.184  1033  1984 W libprocessgroup: failed to open /acct/uid_10023/pid_5631/cgroup.procs: No such file or directory
06-30 10:35:30.220  6300  6300 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-30 10:35:30.245  6300  6300 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,06-30 10:35:30.256  6317  6317 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
06-30 10:35:30.257  6317  6317 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
06-30 10:35:30.257  6317  6317 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,06-30 10:35:30.265  6317  6317 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
06-30 10:35:30.265  6317  6317 D dhcpcd  : wlan0: sending REQUEST (xid 0x811fc3eb), next in 4.52 seconds
06-30 10:35:30.275  6300  6300 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
06-30 10:35:30.275  6300  6300 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
06-30 10:35:30.275  6300  6300 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
06-30 10:35:30.276  6300  6300 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
06-30 10:35:30.276  6300  6300 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,06-30 10:35:30.277  6300  6300 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
06-30 10:35:30.281  6300  6300 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
06-30 10:35:30.287  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 10:35:30.290  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,06-30 10:35:30.314  6300  6300 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,06-30 10:35:30.317  4833  4833 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
06-30 10:35:30.317  4833  4833 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
06-30 10:35:30.319  6300  6300 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
06-30 10:35:30.319  4833  4833 V [BNRBootReceiver]: Boot Receiver Return
06-30 10:35:30.322  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 10:35:30.322  6300  6300 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
06-30 10:35:30.329  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:30.331  6317  6317 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
06-30 10:35:30.337  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.343  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 10:35:30.344  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,06-30 10:35:30.345  6300  6300 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
06-30 10:35:30.347  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
06-30 10:35:30.350  6141  6141 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
06-30 10:35:30.354  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 10:35:30.361  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:30.366  6317  6317 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
06-30 10:35:30.366  6317  6317 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
06-30 10:35:30.367  6317  6317 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
06-30 10:35:30.367  6317  6317 D dhcpcd  : wlan0: adding default route via 192.168.1.1
06-30 10:35:30.367  6317  6317 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
06-30 10:35:30.368  6317  6317 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
06-30 10:35:30.368  6317  6317 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
06-30 10:35:30.368  6317  6317 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
06-30 10:35:30.369  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.371  1033  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:30.372  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:30.373  1033  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:30.375  1033  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:30.376  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 10:35:30.376  1033  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:30.376  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 10:35:30.378  6300  6300 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,06-30 10:35:30.379  1033  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 10:35:30.380  1033  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-30 10:35:30.383  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 10:35:30.392  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:30.397  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.406  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 10:35:30.407  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 10:35:30.407  6300  6300 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,06-30 10:35:30.418  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 10:35:30.418  6141  6141 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,06-30 10:35:30.418  6141  6141 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 10:35:30.418  6141  6141 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 10:35:30.419  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-30 10:35:30.419  6141  6141 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 10:35:30.419  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
06-30 10:35:30.419  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 10:35:30.419  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 10:35:30.419  6141  6141 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-30 10:35:30.419  6141  6141 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
06-30 10:35:30.420  6141  6141 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-30 10:35:30.423  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 10:35:30.430  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:30.438  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.443  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,06-30 10:35:30.444  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 10:35:30.445  6300  6300 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-30 10:35:30.448  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 10:35:30.455  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:30.458  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.464  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 10:35:30.464  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 10:35:30.464  6300  6300 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-30 10:35:30.467  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,06-30 10:35:30.474  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:30.487  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.502  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,06-30 10:35:30.504  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 10:35:30.504  6300  6300 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-30 10:35:30.507  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 10:35:30.528  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:30.532  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.537  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 10:35:30.537  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 10:35:30.537  6300  6300 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-30 10:35:30.539  6300  6300 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,06-30 10:35:30.540  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
06-30 10:35:30.540  6300  6300 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
06-30 10:35:30.560  6300  6300 D LgDataFeature: LgDataFeature() Constructor: none
06-30 10:35:30.560  6300  6300 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 10:35:30.566  6300  6300 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
06-30 10:35:30.568  6300  6300 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
06-30 10:35:30.568  6300  6300 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
06-30 10:35:30.568  6300  6300 V SoundPool: doLoad: loading sample sampleID=1
06-30 10:35:30.569  6300  6300 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
06-30 10:35:30.569  6300  6349 V SoundPool: Start decode
06-30 10:35:30.569  6300  6349 V MediaPlayer[Native]: decode(31, 10857164, 17813)
06-30 10:35:30.569   319   319 V MediaPlayerService: decode(23, 10857164, 17813)
06-30 10:35:30.569   319   319 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
06-30 10:35:30.569   319   319 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
06-30 10:35:30.569   319   319 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
06-30 10:35:30.570   319   319 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
06-30 10:35:30.570   319   319 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
06-30 10:35:30.570   319   319 V MediaPlayerService: player type = 3
06-30 10:35:30.570   319   319 V AwesomePlayer: AwesomePlayer create()
06-30 10:35:30.570   319   319 V AwesomePlayer: reset_l() 
06-30 10:35:30.570   319   319 V AwesomePlayer: cancelPlayerEvents
06-30 10:35:30.570   319   319 V AwesomePlayer: setAudioSink() 
06-30 10:35:30.570   319   319 V AwesomePlayer: reset_l() 
06-30 10:35:30.570   319   319 V AudioCache: notify(0xb1432440, 8, 0, 0)
06-30 10:35:30.570   319   319 V AudioCache: ignored
06-30 10:35:30.570   319   319 V AwesomePlayer: cancelPlayerEvents
06-30 10:35:30.570   319   319 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
06-30 10:35:30.570   319   319 V AwesomePlayer: setDataSource_l dataSource
06-30 10:35:30.570   319   319 V LGParserOSAL: SniffLGParser start
06-30 10:35:30.570   319   319 V LGParserOSAL: MainType:5, SubType=0
06-30 10:35:30.571   319   319 V LGParserOSAL: #### check Mime : application/ogg
06-30 10:35:30.571   319   319 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
06-30 10:35:30.571   319   319 E MediaExtractor: Use LGExtractor :application/ogg 
06-30 10:35:30.573  6052  6052 D UEI.SmartControl: QS Service created
,06-30 10:35:30.579  6052  6052 I UEI.SmartControl: Service initServices...
06-30 10:35:30.579  6052  6052 D UEI.SmartControl: QS start get config
06-30 10:35:30.580  6300  6300 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
06-30 10:35:30.581  6300  6300 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-30 10:35:30.582  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
06-30 10:35:30.594  6300  6300 V LGMDMManager: Create singleton instance
06-30 10:35:30.613   319   319 V LGParserOSAL: supported mime: application/ogg
06-30 10:35:30.613   319   319 V AwesomePlayer: setDataSource_l() extractor countTracks=1
06-30 10:35:30.614   319   319 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
06-30 10:35:30.614   319   319 V AwesomePlayer: mBitrate = -1 bits/sec
06-30 10:35:30.614   319   319 V AwesomePlayer: AudioTrack Setting
06-30 10:35:30.614   319   319 V AwesomePlayer: AudioTrack Setting channelCount = 2
06-30 10:35:30.614   319   319 V AwesomePlayer: setAudioSource() 
06-30 10:35:30.614   319   319 V MediaPlayerService: prepare
06-30 10:35:30.614   319   319 V AwesomePlayer: prepareAsync_l() 
06-30 10:35:30.614   319   319 V MediaPlayerService: wait for prepare
,06-30 10:35:30.614   319  6350 V AwesomePlayer: onPrepareAsyncEvent() 
06-30 10:35:30.614   319  6350 V AwesomePlayer: initAudioDecoder() 
06-30 10:35:30.614   319  6350 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
06-30 10:35:30.614   319  6350 V AudioSystem: isOffloadSupported()
06-30 10:35:30.614   319  6350 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
06-30 10:35:30.614   319  6350 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
06-30 10:35:30.614   319  6350 I AudioFlinger: isAudioPlaybackHookOn() false
06-30 10:35:30.614   319  6350 V AwesomePlayer: getUseOffload() = 0 
06-30 10:35:30.614   319  6350 V OMXCodec: OMXCodec::Create
06-30 10:35:30.614   319  6350 V OMXCodec: findMatchingCodecs()
06-30 10:35:30.614   319  6350 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
06-30 10:35:30.614   319  6350 V OMXCodec: matchingCodecs.size()=1
06-30 10:35:30.614   319  6350 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
06-30 10:35:30.616   319  6350 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
06-30 10:35:30.616   319  6350 V LGCodecAdapter: LG Codec Adapter start
06-30 10:35:30.616   319  6350 V OMXCodec: OMXCodec Createtor
06-30 10:35:30.616   319  6350 V OMXCodec: setComponentRole
06-30 10:35:30.616   319  6350 V OMXCodec: configureCodec protected=0
06-30 10:35:30.616   319  6350 V LGCodecAdapter: called getLGCodecSpecificData
06-30 10:35:30.616   319  6350 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
06-30 10:35:30.616   319  6350 V LGCodecOSAL: Called LGconfigureCodecMETA
06-30 10:35:30.616   319  6350 V LGCodecOSAL: Called LGconfigureCodecMSG
06-30 10:35:30.616   319  6350 V LGCodecOSAL: Not support LGCodec
06-30 10:35:30.616   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
06-30 10:35:30.616   319  6350 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
06-30 10:35:30.616   319  6350 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
06-30 10:35:30.617   319  6350 I AwesomePlayer: Could not offload audio decode, try pcm offload
06-30 10:35:30.617   319  6350 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
06-30 10:35:30.617   319  6350 V AudioSystem: isOffloadSupported()
06-30 10:35:30.617   319  6350 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
06-30 10:35:30.617   319  6350 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
06-30 10:35:30.617   319  6350 V OMXCodec: init()
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
06-30 10:35:30.617   319  6350 V OMXCodec: allocateBuffers
06-30 10:35:30.617   319  6350 V OMXCodec: allocateBuffersOnPort portIndex=0
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
06-30 10:35:30.617   31,9  6350 V OMXCodec: allocateBuffersOnPort portIndex=1
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
06-30 10:35:30.617   319  6350 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fa3d0 on output port
06-30 10:35:30.617   319  6350 V OMXCodec: init() mAsyncCompletion wait!!! 
06-30 10:35:30.618   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
06-30 10:35:30.618   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
06-30 10:35:30.618   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
06-30 10:35:30.618   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
06-30 10:35:30.618   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
06-30 10:35:30.618   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
06-30 10:35:30.618   319  6350 V OMXCodec: init() mAsyncCompletion wait free! 
06-30 10:35:30.619   319  6350 V AwesomePlayer: finishAsyncPrepare_l() 
06-30 10:35:30.619   319  6350 V AudioCache: notify(0xb1432440, 5, 0, 0)
06-30 10:35:30.619   319  6350 V AudioCache: ignored
06-30 10:35:30.619   319  6350 V AudioCache: notify(0xb1432440, 1, 0, 0)
06-30 10:35:30.619   319  6350 V AudioCache: prepared
06-30 10:35:30.619   319   319 V AudioCache: wait - success
06-30 10:35:30.619   319   319 V MediaPlayerService: start
06-30 10:35:30.619   319   319 V AwesomePlayer: play_l() 
06-30 10:35:30.619   319   319 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
06-30 10:35:30.619   319   319 V AwesomePlayer: createAudioPlayer_l
06-30 10:35:30.619   319   319 V AwesomePlayer: seekAudioIfNecessary_l() 
06-30 10:35:30.619   319   319 V AwesomePlayer: startAudioPlayer_l() 
06-30 10:35:30.619   319   319 D AudioPlayer: start of Playback, useOffload 0
06-30 10:35:30.619   319   319 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
06-30 10:35:30.619   319   319 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
06-30 10:35:30.622   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
06-30 10:35:30.622   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
06-30 10:35:30.622   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
06-30 10:35:30.622   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
06-30 10:35:30.622   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
06-30 10:35:30.622   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045041104
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
06-30 10:35:30.623   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
06-30 10:35:30.623   319  6352 V OMXCodec: allocateBuffersOnPort portIndex=1
06-30 10:35:30.624   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
06-30 10:35:30.624   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
06-30 10:35:30.624   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
06-30 10:35:30.624   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
06-30 10:35:30.624   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
06-30 10:35:30.624   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
06-30 10:35:30.624   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
06-30 10:35:30.625   319   319 V AudioCache: open(48000, 2, 0x0, 1, 4)
06-30 10:35:30.625   319   319 V AudioCache: notify(0xb1432440, 6, 0, 0)
06-30 10:35:30.625   319   319 V AudioCache: ignored
06-30 10:35:30.626   319   319 V MediaPlayerService: wait for playback complete
06-30 10:35:30.626   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.626   319  6353 V AudioCache: memcpy(0xac300000, 0xb17fc000, 4096)
06-30 10:35:30.626   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.627   319  6353 V AudioCache: memcpy(0xac301000, 0xb17fc000, 4096)
06-30 10:35:30.627   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.627   319  6353 V AudioCache: memcpy(0xac302000, 0xb17fc000, 4096)
06-30 10:35:30.627   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.627   319  6353 V AudioCache: memcpy(0xac303000, 0xb17fc000, 4096)
06-30 10:35:30.627   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.627   319  6353 V AudioCache: memcpy(0xac304000, 0xb17fc000, 4096)
06-30 10:35:30.627   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.627   319  6353 V AudioCache: memcpy(0xac305000, 0xb17fc000, 4096)
06-30 10:35:30.628   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.628   319  6353 V AudioCache: memcpy(0xac306000, 0xb17fc000, 4096)
06-30 10:35:30.628   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.628   319  6353 V AudioCache: memcpy(0xac307000, 0xb17fc000, 4096)
06-30 10:35:30.628   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.628   319  6353 V AudioCache: memcpy(0xac308000, 0xb17fc000, 4096)
06-30 10:35:30.628   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.628   319  6353 V AudioCache: memcpy(0xac309000, 0xb17fc000, 4096)
06-30 10:35:30.629   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.629   319  6353 V AudioCache: memcpy(0xac30a000, 0xb17fc000, 4096)
06-30 10:35:30.629   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.629   319  6353 V AudioCache: memcpy(0xac30b000, 0xb17fc000, 4096)
06-30 10:35:30.629   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.629   319  6353 V AudioCache: memcpy(0xac30c000, 0xb17fc000, 4096)
06-30 10:35:30.630   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.630   319  6353 V AudioCache: memcpy(0xac30d000, 0xb17fc000, 4096)
06-30 10:35:30.630   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.630   319  6353 V AudioCache: memcpy(0xac30e000, 0xb17fc000, 4096)
06-30 10:35:30.630   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.630   319  6353 V AudioCache: memcpy(0xac30f000, 0xb17fc000, 4096)
06-30 10:35:30.631   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.631   319  6353 V AudioCache: memcpy(0xac310000, 0xb17fc000, 4096)
06-30 10:35:30.631   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.631   319  6353 V AudioCache: memcpy(0xac311000, 0xb17fc000, 4096)
06-30 10:35:30.632   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.632   319  6353 V AudioCache: memcpy(0xac312000, 0xb17fc000, 4096)
06-30 10:35:30.632   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.632   319  6353 V AudioCache: memcpy(0xac313000, 0xb17fc000, 4096)
06-30 10:35:30.632   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.632   319  6353 V AudioCache: memcpy(0xac314000, 0xb17fc000, 4096)
06-30 10:35:30.632   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.632   319  6353 V AudioCache: memcpy(0xac315000, 0xb17fc000, 4096)
06-30 10:35:30.633   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.633   319  6353 V AudioCache: memcpy(0xac316000, 0xb17fc000, 4096)
06-30 10:35:30.633   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.633   319  6353 V AudioCache: memcpy(0xac317000, 0xb17fc000, 4096)
06-30 10:35:30.633   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.633   319  6353 V AudioCache: memcpy(0xac318000, 0xb17fc000, 4096)
06-30 10:35:30.633   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.633   319  6353 V AudioCache: memcpy(0xac319000, 0xb17fc000, 4096)
06-30 10:35:30.634   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.634   319  6353 V AudioCache: memcpy(0xac31a000, 0xb17fc000, 4096)
06-30 10:35:30.634   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.634   319  6353 V AudioCache: memcpy(0xac31b000, 0xb17fc000, 4096)
06-30 10:35:30.634   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.634   319  6353 V AudioCache: memcpy(0xac31c000, 0xb17fc000, 4096)
06-30 10:35:30.635   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.635   319  6353 V AudioCache: memcpy(0xac31d000, 0xb17fc000, 4096)
06-30 10:35:30.635   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.635   319  6353 V AudioCache: memcpy(0xac31e000, 0xb17fc000, 4096)
06-30 10:35:30.635   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.635   319  6353 V AudioCache: memcpy(0xac31f000, 0xb17fc000, 4096)
06-30 10:35:30.635   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.635   319  6353 V AudioCache: memcpy(0xac320000, 0xb17fc000, 4096)
06-30 10:35:30.636   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.636   319  6353 V AudioCache: memcpy(0xac321000, 0xb17fc000, 4096)
06-30 10:35:30.636   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.636   319  6353 V AudioCache: memcpy(0xac322000, 0xb17fc000, 4096)
06-30 10:35:30.636   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.636   319  6353 V AudioCache: memcpy(0xac323000, 0xb17fc000, 4096)
06-30 10:35:30.637   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.637   319  6353 V AudioCache: memcpy(0xac324000, 0xb17fc000, 4096)
06-30 10:35:30.637   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.637   319  6353 V AudioCache: memcpy(0xac325000, 0xb17fc000, 4096)
06-30 10:35:30.637   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.637   319  6353 V AudioCache: memcpy(0xac326000, 0xb17fc000, 4096)
06-30 10:35:30.637   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.637   319  6353 V AudioCache: memcpy(0xac327000, 0xb17fc000, 4096)
06-30 10:35:30.638   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.638   319  6353 V AudioCache: memcpy(0xac328000, 0xb17fc000, 4096)
06-30 10:35:30.638   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.638   319  6353 V AudioCache: memcpy(0xac329000, 0xb17fc000, 4096)
06-30 10:35:30.638   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.638   319  6353 V AudioCache: memcpy(0xac32a000, 0xb17fc000, 4096)
06-30 10:35:30.638   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.638   319  6353 V AudioCache: memcpy(0xac32b000, 0xb17fc000, 4096)
06-30 10:35:30.638   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.638   319  6353 V AudioCache: memcpy(0xac32c000, 0xb17fc000, 4096)
06-30 10:35:30.641   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.641   319  6353 V AudioCache: memcpy(0xac32d000, 0xb17fc000, 4096)
06-30 10:35:30.641   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.641   319  6353 V AudioCache: memcpy(0xac32e000, 0xb17fc000, 4096)
06-30 10:35:30.641   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.641   319  6353 V AudioCache: memcpy(0xac32f000, 0xb17fc000, 4096)
06-30 10:35:30.641   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.641   319  6353 V AudioCache: memcpy(0xac330000, 0xb17fc000, 4096)
06-30 10:35:30.641   319  6353 V AudioCache: write(0xb17fc000, 4096)
06-30 10:35:30.641   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
06-30 10:35:30.641   319  6353 V AudioCache: memcpy(0xac331000, 0xb17fc000, 4096)
06-30 10:35:30.641   319  6353 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
06-30 10:35:30.641   319  6353 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
06-30 10:35:30.641   319  6353 V AwesomePlayer: postAudioEOS() 
06-30 10:35:30.642   319  6353 V AudioCache: write(0xb17fc000, 280)
06-30 10:35:30.642   319  6353 V AudioCache: memcpy(0xac332000, 0xb17fc000, 280)
06-30 10:35:30.643   319  6350 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
06-30 10:35:30.643   319  6350 V AwesomePlayer: onStreamDone
06-30 10:35:30.643   319  6350 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
06-30 10:35:30.643   319  6350 V AudioCache: notify(0xb1432440, 2, 0, 0)
06-30 10:35:30.643   319  6350 V AudioCache: playback complete
06-30 10:35:30.643   319  6350 V AwesomePlayer: pause_l() 
06-30 10:35:30.643   319   319 V AudioCache: wait - success
06-30 10:35:30.643   319  6350 V AudioCache: notify(0xb1432440, 7, 0, 0)
06-30 10:35:30.643   319  6350 V AudioCache: ignored
06-30 10:35:30.643   319   319 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
06-30 10:35:30.643   319  6350 V AwesomePlayer: cancelPlayerEvents
06-30 10:35:30.644   319  6350 D AudioPlayer: Pause Playback at 1068125
,06-30 10:35:30.644   319   319 V AwesomePlayer: reset_l() 
06-30 10:35:30.644   319   319 V AudioCache: notify(0xb1432440, 8, 0, 0)
06-30 10:35:30.644   319   319 V AudioCache: ignored
06-30 10:35:30.644   319   319 V AwesomePlayer: cancelPlayerEvents
06-30 10:35:30.644   319   319 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
06-30 10:35:30.644   319   319 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
06-30 10:35:30.644   319   319 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
06-30 10:35:30.644   319   319 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
06-30 10:35:30.644   319   319 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
06-30 10:35:30.645   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-30 10:35:30.646   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
06-30 10:35:30.646   319   319 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
06-30 10:35:30.646   319   319 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
06-30 10:35:30.646   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
06-30 10:35:30.646   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
06-30 10:35:30.646   319  6352 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
06-30 10:35:30.646   319   319 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
06-30 10:35:30.646   319   319 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
06-30 10:35:30.646   319   319 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
06-30 10:35:30.647   319   319 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
06-30 10:35:30.647   319   319 D AudioPlayer: AudioPlayer releasing audio source
06-30 10:35:30.647   319   319 D AudioPlayer: AudioPlayer done releasing audio source
06-30 10:35:30.647   319   319 V AwesomePlayer: reset_l() 
06-30 10:35:30.647   319   319 V AwesomePlayer: cancelPlayerEvents
06-30 10:35:30.647   319   319 V AwesomePlayer: ~AwesomePlayer call
06-30 10:35:30.647   319   319 V AwesomePlayer: reset_l() 
06-30 10:35:30.647   319   319 V AwesomePlayer: cancelPlayerEvents
06-30 10:35:30.648  6300  6349 V SoundPool: close(31)
06-30 10:35:30.648  6300  6349 V SoundPool: pointer = 0x9fe78000, size = 205080, sampleRate = 48000, numChannels = 2
06-30 10:35:30.674  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
06-30 10:35:30.674  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
06-30 10:35:30.676  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8109
,06-30 10:35:30.707  2753  2753 I MusicWidget: mDelayedStopHandler : unbind
,06-30 10:35:30.709  1033  6262 D DhcpStateMachine: DHCPV4 succeeded on wlan0
06-30 10:35:30.709  2206  2206 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
06-30 10:35:30.709  2206  2206 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
06-30 10:35:30.709  1033  6262 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
06-30 10:35:30.709  2206  2206 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
06-30 10:35:30.709  1033  6262 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-30 10:35:30.709  1033  6262 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
06-30 10:35:30.709  1033  6262 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
06-30 10:35:30.710  1033  6262 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-30 10:35:30.710  1033  6262 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
06-30 10:35:30.710  1033  6262 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
06-30 10:35:30.710  1033  6262 D DhcpStateMachine: RunningState
06-30 10:35:30.710  1033  1521 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
06-30 10:35:30.710  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
06-30 10:35:30.710  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
06-30 10:35:30.711  1033  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:30.711  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
06-30 10:35:30.711  1033  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:30.711  1033  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
06-30 10:35:30.711  1033  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
06-30 10:35:30.711  6162  6162 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
06-30 10:35:30.711  1033  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
06-30 10:35:30.711  1033  1521 D WifiNative-wlan0: doBoolean: SET ps 1
06-30 10:35:30.713  2206  2206 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
06-30 10:35:30.713  2206  2206 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
06-30 10:35:30.713  2206  2206 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
06-30 10:35:30.715  2206  2206 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
06-30 10:35:30.715  2206  2206 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
06-30 10:35:30.716  1033  2077 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2815eb84com.lge.music.MediaPlaybackService$5@2b2faf6d
06-30 10:35:30.717  2206  2206 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
06-30 10:35:30.718  2206  2206 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,06-30 10:35:30.719  2206  2206 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-30 10:35:30.719  2206  2206 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-30 10:35:30.720  2206  2206 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@391c1c43
06-30 10:35:30.720  2206  2206 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-30 10:35:30.721  2206  2206 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
06-30 10:35:30.721  2206  2206 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-30 10:35:30.721  2206  2206 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
06-30 10:35:30.722  2206  2206 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
06-30 10:35:30.722  2206  2206 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-30 10:35:30.722  2206  2206 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-30 10:35:30.723  2206  2206 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-30 10:35:30.723  2206  2206 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-30 10:35:30.724  2206  2206 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-30 10:35:30.725  2206  2206 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
06-30 10:35:30.727  2206  2206 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
06-30 10:35:30.727  2206  2206 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
06-30 10:35:30.727  2206  2206 V MediaPlayer[Native]: reset
06-30 10:35:30.728  1033  1521 D WifiNative-wlan0: SET ps 1: returned true
06-30 10:35:30.728  1033  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-30 10:35:30.729  1033  1521 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,06-30 10:35:30.729  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
06-30 10:35:30.729  1033  1521 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
06-30 10:35:30.730  1033  1528 D ConnectivityService: ignoring duplicate network state non-change
06-30 10:35:30.734  2206  2206 V MediaPlayer[Native]: setListener
06-30 10:35:30.734  2206  2206 V MediaPlayer[Native]: disconnect
06-30 10:35:30.734  2206  2206 V MediaPlayer[Native]: destructor
06-30 10:35:30.735   319  1366 V AudioFlinger: releasing 18 from 2206 for -1
06-30 10:35:30.735   319  1366 V AudioFlinger:  decremented refcount to 0
06-30 10:35:30.735   319  1366 V AudioFlinger: purging stale effects
06-30 10:35:30.735  2206  2206 V MediaPlayer[Native]: disconnect
06-30 10:35:30.735  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:30.735  1563  1563 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:30.736  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:30.737  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:30.738  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:30.738  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
06-30 10:35:30.744  2206  2206 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,06-30 10:35:30.745  1033  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
06-30 10:35:30.746  1033  1528 D ConnectivityService: Adding iface wlan0 to network 100
06-30 10:35:30.748  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:35:30.749  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 10:35:30.749  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:30.749  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
06-30 10:35:30.752  1949  1949 V WfdStateTracker: handleWifiStateChangedEvent: 1
06-30 10:35:30.754  2206  2206 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
06-30 10:35:30.755  2206  2206 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
06-30 10:35:30.756  2206  2206 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
06-30 10:35:30.756  2206  2206 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
06-30 10:35:30.756  2206  2206 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
06-30 10:35:30.756  2206  2206 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 101652386
06-30 10:35:30.756  2206  2206 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 101652386
06-30 10:35:30.757  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
06-30 10:35:30.757  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:30.757  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:30.757  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
06-30 10:35:30.757  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
06-30 10:35:30.762  2206  2206 I SmartShareClient: [SmartShareManagerClient] terminate service: 2206/MediaPlaybackService/774985153
06-30 10:35:30.762  1033  1521 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
06-30 10:35:30.763  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:30.763  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:30.763  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
06-30 10:35:30.766  1033  1528 E ConnectivityService: Unexpected mtu value: 0, wlan0
06-30 10:35:30.766  1033  1528 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
06-30 10:35:30.767  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:30.767  1563  1563 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:30.767  1033  1528 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
06-30 10:35:30.768  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:30.768  1033  1528 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,06-30 10:35:30.769  1033  1528 D ConnectivityService: addLocalRoutetoDefaultNetwork
06-30 10:35:30.769  1033  1528 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
06-30 10:35:30.769  1033  1528 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
06-30 10:35:30.769  2206  2206 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
06-30 10:35:30.769  2206  2206 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@16ec9c33
06-30 10:35:30.770  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:30.771  2206  2206 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
,06-30 10:35:30.771  2206  2206 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
06-30 10:35:30.772  2206  2206 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
06-30 10:35:30.772  2206  2206 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
06-30 10:35:30.774  1033  1528 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
06-30 10:35:30.775  1033  1528 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
06-30 10:35:30.775  1563  1563 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
06-30 10:35:30.775  1033  1528 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
06-30 10:35:30.775  1033  1528 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-30 10:35:30.775  1033  1528 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:35:30.775  1033  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:30.775  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:30.775  1033  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-30 10:35:30.776  1033  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:30.776  1033  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
06-30 10:35:30.776  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:35:30.776  1033  1528 D ConnectivityService: currentScore = 0, newScore = 20
06-30 10:35:30.776  1033  1528 D ConnectivityService:    accepting network in place of null
06-30 10:35:30.776  1033  1528 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:30.776  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:30.776  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
06-30 10:35:30.776  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:30.777  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-30 10:35:30.778  2206  2206 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
06-30 10:35:30.780   314  6357 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
06-30 10:35:30.781  1033  1521 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:30.781  1033  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-30 10:35:30.781  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.782  1860  1860 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:30.782  1860  1860 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
06-30 10:35:30.782  1033  1528 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
06-30 10:35:30.785  1563  1563 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:30.785  1563  1563 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
06-30 10:35:30.785  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:30.785  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 10:35:30.786  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 10:35:30.789  6300  6300 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-30 10:35:30.791  1033  1528 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
06-30 10:35:30.791  1033  1528 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
06-30 10:35:30.791  1033  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-30 10:35:30.792  1033  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
06-30 10:35:30.792  1033  1528 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
06-30 10:35:30.792  1033  1528 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,06-30 10:35:30.794  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
06-30 10:35:30.794  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
06-30 10:35:30.794  1033  1528 D ConnectivityService: validation of new default Network = false
06-30 10:35:30.794  1033  1528 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
06-30 10:35:30.794  1033  1528 D DSQN    : enableDataServiceNotify 
06-30 10:35:30.795  1033  1528 D DSQN    : start dsqn bin
06-30 10:35:30.795  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
06-30 10:35:30.795  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
06-30 10:35:30.795  1033  1033 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
06-30 10:35:30.796   314  6358 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:35:30.796   314  6358 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
06-30 10:35:30.796  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 10:35:30.798   314  6360 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:35:30.799   314  6360 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
06-30 10:35:30.803  1033  1528 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-30 10:35:30.803  1033  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:30.803  1033  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:30.803  1033  1528 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:30.804  1563  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 10:35:30.788  6361  6361 W dsqn    : type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,06-30 10:35:30.788  6361  6361 W dsqn    : type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:30.807  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:35:30.813  1563  1563 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
06-30 10:35:30.813  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:30.814  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:30.817  6291  6292 E QC-QMI  : qmi_client [6291] 13: failed to locate client data
,06-30 10:35:30.817   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
06-30 10:35:30.817   469   469 E QC-QMI  : QMUX qmux_client_id=13 not found in qmux client list, unable to remove
06-30 10:35:30.819  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.823  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 10:35:30.824  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 10:35:30.824  6300  6300 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-30 10:35:30.826  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 10:35:30.828  6217  6217 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,06-30 10:35:30.832  6217  6217 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
06-30 10:35:30.834  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:35:30.837  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.840  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,06-30 10:35:30.841  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 10:35:30.841  6300  6300 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
06-30 10:35:30.842  6300  6300 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
06-30 10:35:30.842  6300  6300 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
06-30 10:35:30.845  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 10:35:30.848  6217  6217 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
06-30 10:35:30.849  6217  6217 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
06-30 10:35:30.851  6141  6141 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:30.855  6141  6141 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:30.861  6300  6300 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 10:35:30.861  6300  6300 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 10:35:30.862  6300  6300 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
06-30 10:35:30.862  6300  6300 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,06-30 10:35:30.863  6300  6300 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
06-30 10:35:30.923  6052  6052 I UEI.SmartControl: Supports setup maps: true
06-30 10:35:30.926  6052  6052 D UEI.SmartControl: QS start statue = true Error code = 0
06-30 10:35:30.926  6052  6052 I UEI.SmartControl: QS version = v2.7.10.1_RC1
06-30 10:35:30.926  6052  6052 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
06-30 10:35:30.926  6052  6052 I UEI.SmartControl: ### init IR Blaster...
06-30 10:35:30.927  6361  6361 E DSQN    : DSQN ssw
,06-30 10:35:30.932  6052  6052 D serial_port: Configuring serial port
06-30 10:35:30.932  6052  6052 E UEI.SmartControl: UEIBLaster setting for 616
06-30 10:35:30.932  6052  6052 I UEI.SmartControl: Setting serial record hearder size = 2
06-30 10:35:30.932  6052  6052 I UEI.SmartControl: configuring settings for MAXQ616
06-30 10:35:30.932  6052  6052 I UEI.SmartControl: Get version...
06-30 10:35:30.946  6052  6365 D UEI.SmartControl: serial port data available: 21
,06-30 10:35:30.953  6366  6366 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
06-30 10:35:30.969  6367  6367 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,06-30 10:35:30.973  6052  6052 D UEI.SmartControl: MAXQ616 A2-X4 software.
06-30 10:35:30.973  6052  6052 I UEI.SmartControl: IR Blaster version: 256702256704300002
06-30 10:35:30.973  6052  6052 I UEI.SmartControl: QS saving settings...
06-30 10:35:30.974  6052  6052 D UEI.SmartControl: IR Blaster version: 25672567
06-30 10:35:30.990  6052  6365 D UEI.SmartControl: serial port data available: 4
,06-30 10:35:30.997  6120  6166 I bt_vendor: bluetooth satus is on
06-30 10:35:30.998  6120  6166 D bt_hci_bdroid: preload
06-30 10:35:30.998  6120  6257 D bt_userial_mct: userial_open(port:0)
06-30 10:35:30.998  6120  6257 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
06-30 10:35:30.998  6120  6257 I bt_vendor: Done intiailizing UART
06-30 10:35:30.999  6120  6257 I bt_vendor: Done intiailizing UART
06-30 10:35:30.999  6120  6257 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
06-30 10:35:30.999  6120  6257 I bt_vendor: Bluetooth Firmware and transport layer are initialized
06-30 10:35:30.999  6120  6254 I bt-btu  : btu_task received preload complete event
06-30 10:35:30.999  6120  6370 D bt_userial_mct: Entering userial_read_thread()
06-30 10:35:31.000  6120  6254 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
06-30 10:35:31.000  6120  6254 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
06-30 10:35:31.002  6120  6254 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_HCI
06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_L2CAP
06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_RFCOMM
06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_AVDT
06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_AVRC
06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_A2D
06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_BNEP
06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_BTM
06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_HID_HOST
06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_GAP
06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_PAN
06-30 10:35:31.004  6120  6254 I         : BTE_InitTraceLevels -- TRC_SDP
06-30 10:35:31.005  6120  6254 I         : BTE_InitTraceLevels -- TRC_GATT
06-30 10:35:31.005  6120  6254 I         : BTE_InitTraceLevels -- TRC_SMP
06-30 10:35:31.005  6120  6254 I         : BTE_InitTraceLevels -- TRC_BTAPP
06-30 10:35:31.005  6120  6254 I         : BTE_InitTraceLevels -- TRC_BTIF
06-30 10:35:31.018  6052  6372 I UEI.SmartControl: Device manager: loading config....
,06-30 10:35:31.021  6052  6372 D UEI.SmartControl: ----------- loading internal config...
06-30 10:35:31.025  6052  6052 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
06-30 10:35:31.027  6052  6052 E UEI.SmartControl: Services init done
06-30 10:35:31.027  6052  6052 D UEI.SmartControl: QS Service init finished
06-30 10:35:31.030  6052  6052 D UEI.SmartControl: QS Service version name: 2.1.91
06-30 10:35:31.030  6052  6052 D UEI.SmartControl: QS Service version code: 201091
06-30 10:35:31.032  6052  6052 D UEI.SmartControl: Service requested: Control
,06-30 10:35:31.033  6052  6372 E UEI.SmartControl: Loading SETTINGS...
06-30 10:35:31.037  6052  6052 D UEI.SmartControl: Request IControl service: devices are loaded...
06-30 10:35:31.040   314  6357 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
06-30 10:35:31.042  6052  6052 D UEI.SmartControl: Internal service binding...
06-30 10:35:31.042  6300  6300 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
06-30 10:35:31.045  6120  6254 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
06-30 10:35:31.045  6120  6254 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa018e061 
06-30 10:35:31.045  6120  6254 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa018e061 
,06-30 10:35:31.047  6052  6068 I UEI.SmartControl: ------ IControl API: 11
06-30 10:35:31.048  6052  6068 D UEI.SmartControl: File observer start...
06-30 10:35:31.049   314  6358 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
06-30 10:35:31.050  6052  6068 E UEI.SmartControl: IR Port is disabled: false
06-30 10:35:31.050  6052  6068 D UEI.SmartControl: Starting file observer...
06-30 10:35:31.052  6052  6068 I UEI.SmartControl: Registering callback...
06-30 10:35:31.053  6120  6169 E bt-btif : Calling BTA_HhEnable
06-30 10:35:31.053  6120  6169 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
06-30 10:35:31.054  6120  6169 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
06-30 10:35:31.054  6120  6254 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
06-30 10:35:31.054  6052  6067 I UEI.SmartControl: ------ IControl API: 19
06-30 10:35:31.054  6120  6254 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
06-30 10:35:31.054  6120  6254 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
06-30 10:35:31.055  6120  6254 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
06-30 10:35:31.055  6120  6254 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
06-30 10:35:31.055  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,06-30 10:35:31.056  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
,06-30 10:35:31.056  6052  6067 I UEI.SmartControl: Registering Services Ready callback...
06-30 10:35:31.057  6052  6372 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
06-30 10:35:31.057  6120  6169 D BluetoothAdapterProperties: Name is: G3
06-30 10:35:31.058  6120  6169 D BluetoothAdapterProperties: Scan Mode:20
06-30 10:35:31.059  6120  6169 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 10:35:31.059  6120  6169 D bt_hci_bdroid: postload
06-30 10:35:31.059  6120  6257 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 10:35:31.060  6120  6254 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
06-30 10:35:31.062  6120  6254 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 10:35:31.062  6120  6254 W bt-smp  : Plain text(LSB ~ MSB) = 4d 61 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 10:35:31.062  6120  6254 W bt-smp  : Encrypted text(LSB ~ MSB) = 05 50 99 1b 43 6e f2 f6 cd ee de 76 d8 83 dc c7 
06-30 10:35:31.062  6120  6254 W bt-btm  : Stopping oneshot timer
06-30 10:35:31.062  6120  6169 D bte_conf: Device ID record 1 : primary
06-30 10:35:31.062  6120  6169 D bte_conf:   vendorId            = 00c4
06-30 10:35:31.062  6120  6169 D bte_conf:   vendorIdSource      = 0001
06-30 10:35:31.062  6120  6169 D bte_conf:   product             = 13a1
06-30 10:35:31.062  6120  6169 D bte_conf:   version             = 1000
06-30 10:35:31.062  6120  6169 D bte_conf:   clientExecutableURL = 
06-30 10:35:31.062  6120  6169 D bte_conf:   serviceDescription  = 
06-30 10:35:31.062  6120  6169 D bte_conf:   documentationURL    = 
06-30 10:35:31.062  6120  6257 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 10:35:31.063  6120  6169 D bte_conf: bte_load_did_conf no section named DID2.
,06-30 10:35:31.063  6120  6257 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 10:35:31.064  6120  6257 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 10:35:31.064  6120  6169 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
06-30 10:35:31.064  6120  6166 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
06-30 10:35:31.064  6120  6166 D BluetoothAdapterProperties: ScanMode =  20
06-30 10:35:31.064  6120  6166 D BluetoothAdapterProperties: State =  11
06-30 10:35:31.064  6120  6370 E bt_mct  : hci lib postload completed
06-30 10:35:31.064  6120  6166 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
06-30 10:35:31.064  6120  6166 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
06-30 10:35:31.064  6120  6166 D BluetoothAdapterProperties: Setting state to 12
06-30 10:35:31.064  6120  6166 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
06-30 10:35:31.065  6120  6169 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
06-30 10:35:31.065  1033  1115 D BluetoothManagerService: Message: 60
06-30 10:35:31.065  1033  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
06-30 10:35:31.065  1033  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 5 receivers.
06-30 10:35:31.066  6120  6166 I BluetoothAdapterState: Entering On State
06-30 10:35:31.067  6120  6166 D LGBluetoothServiceAdapter: [BTUI] OnState
06-30 10:35:31.067  6120  6166 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
06-30 10:35:31.067  6120  6166 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
06-30 10:35:31.068  6120  6166 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
06-30 10:35:31.058  6375  6375 W sh      : type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:31.058  6375  6375 W sh      : type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:31.071  1860  4087 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 10:35:31.071  1033  1115 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 10:35:31.072  1033  1115 D BluetoothA2dp: onBluetoothStateChange: up=true
06-30 10:35:31.072  1860  1876 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 10:35:31.072  1860  4082 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 10:35:31.073  1033  1115 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
06-30 10:35:31.073  1033  1115 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,06-30 10:35:31.076   314  6357 D libc-netbsd: res_queryN name = clients3.google.com succeed
06-30 10:35:31.081  1563  1563 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
06-30 10:35:31.082  5800  5800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
06-30 10:35:31.082  5800  5800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 10:35:31.082  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:31.082  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 10:35:31.082  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 10:35:31.082  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 10:35:31.082  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 10:35:31.082  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 10:35:31.082  5800  5800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 10:35:31.084  6120  6254 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 10:35:31.084  6120  6254 W bt-smp  : Plain text(LSB ~ MSB) = b3 18 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 10:35:31.084  6120  6254 W bt-smp  : Encrypted text(LSB ~ MSB) = 1c f3 a0 84 a6 95 ec 8e 98 cd e2 51 21 02 1d 0c 
06-30 10:35:31.084  6120  6254 W bt-btm  : Stopping oneshot timer
06-30 10:35:31.084  5800  5800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
06-30 10:35:31.084  1949  1949 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:31.085  1949  2128 D LGBluetoothAPIService: Message: 1
06-30 10:35:31.085  1949  2128 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,06-30 10:35:31.094  6120  6254 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 10:35:31.094  6120  6254 W bt-smp  : Plain text(LSB ~ MSB) = 5f 30 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 10:35:31.094  6120  6254 W bt-smp  : Encrypted text(LSB ~ MSB) = 03 f0 a1 e0 93 43 39 96 c5 cd ec 3a 7a 7c 38 67 
06-30 10:35:31.094  6120  6254 W bt-btm  : Stopping oneshot timer
06-30 10:35:31.095  6052  6371 I UEI.SmartControl: Notify AllClients services are ready: 0
06-30 10:35:31.095  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
06-30 10:35:31.096  6052  6371 D UEI.SmartControl: -----service ready thread exits
06-30 10:35:31.098  1033  1115 D BluetoothManagerService: Message: 40
06-30 10:35:31.098  1033  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
06-30 10:35:31.101  6300  6315 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
06-30 10:35:31.101  6120  6120 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:31.102  1949  2128 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
06-30 10:35:31.102  6120  6120 D BluetoothMapService: STATE_ON
06-30 10:35:31.102  6120  6120 V BluetoothMapService: Handler(): got msg=1
06-30 10:35:31.102  6120  6120 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
06-30 10:35:31.103  6120  6254 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 10:35:31.103  6120  6254 W bt-smp  : Plain text(LSB ~ MSB) = 86 71 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
,06-30 10:35:31.103  6120  6254 W bt-smp  : Encrypted text(LSB ~ MSB) = da ba 63 3a 3e 75 85 32 b3 f1 17 be 8e 59 72 ae 
06-30 10:35:31.103  6120  6254 W bt-btm  : Stopping oneshot timer
06-30 10:35:31.103  6120  6380 D BluetoothMapMasInstance: MAS initSocket()
06-30 10:35:31.104  6120  6380 D BluetoothMapMasInstance:   masId = 00
06-30 10:35:31.104  6120  6380 D BluetoothMapMasInstance:   msgTypes = 0e
06-30 10:35:31.104  6120  6380 D BluetoothMapMasInstance:   masName = SMS/MMS
06-30 10:35:31.104  6120  6380 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
06-30 10:35:31.104  1033  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:31.105  6120  6380 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 10:35:31.107  6300  6347 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
06-30 10:35:31.108  6300  6347 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
06-30 10:35:31.108  1033  1519 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
06-30 10:35:31.109  6120  6120 D LGBluetoothAPIServer: [BTUI] onCreate()
06-30 10:35:31.109  6120  6120 D LGBluetoothAPIServer: [BTUI] onBind()
06-30 10:35:31.110  6300  6300 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
06-30 10:35:31.110  6300  6300 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
06-30 10:35:31.112  6120  6380 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
06-30 10:35:31.112  6120  6380 V BluetoothMapMasInstance: Succeed to create listening socket 
06-30 10:35:31.112  6120  6380 D BluetoothMapMasInstance: Accepting socket connection...
06-30 10:35:31.112  1949  1949 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
06-30 10:35:31.113  6052  6068 I UEI.SmartControl: ------ IControl API: 8
06-30 10:35:31.113  1949  2128 D LGBluetoothAPIService: Message: 100
06-30 10:35:31.114  1949  2128 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
06-30 10:35:31.114   314   890 D LGDataListener: argv[0]=dsqncommand
06-30 10:35:31.114   314   890 D LGDataListener: argv[1]=wlan0
06-30 10:35:31.114   314   890 D LGDataListener: argv[2]=1
06-30 10:35:31.114   314   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,06-30 10:35:31.118  6120  6254 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 10:35:31.118  6120  6254 W bt-smp  : Plain text(LSB ~ MSB) = a4 ce 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 10:35:31.118  6120  6254 W bt-smp  : Encrypted text(LSB ~ MSB) = 40 84 98 d9 01 2d d8 09 be 8a 1c 2f 4b a0 fd d1 
06-30 10:35:31.118  6120  6166 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
06-30 10:35:31.118  6120  6254 W bt-btm  : Stopping oneshot timer
06-30 10:35:31.118  1033  1113 D DSQN    : DSQM DsqnNotification wlan0  1
06-30 10:35:31.119  6141  6141 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-30 10:35:31.120  1033  1113 D DSQN    : start to monitor internet connection
06-30 10:35:31.125  6384  6384 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
06-30 10:35:31.127  6120  6169 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 10:35:31.127  6120  6169 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,06-30 10:35:31.129  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:31.129  6120  6120 V BluetoothPbapService: Pbap Service onCreate
06-30 10:35:31.129  6120  6120 V BluetoothPbapService: Starting PBAP service
06-30 10:35:31.130  6120  6120 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
06-30 10:35:31.130  6120  6120 V BluetoothPbapService: Handler(): got msg=1
06-30 10:35:31.130  6300  6300 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
06-30 10:35:31.131  6120  6120 V BluetoothPbapService: Pbap Service startRfcommSocketListener
06-30 10:35:31.131  6120  6169 D BluetoothAdapterProperties: Scan Mode:21
06-30 10:35:31.131  6120  6169 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
06-30 10:35:31.131  6120  6120 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:31.131  6300  6300 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
06-30 10:35:31.131  6120  6120 V BluetoothPbapService: state: 12
06-30 10:35:31.131  6300  6300 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
06-30 10:35:31.132  6300  6300 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
06-30 10:35:31.132  6120  6385 V BluetoothPbapService: Pbap Service initSocket
06-30 10:35:31.132  1033  2056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:31.132  6300  6300 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
06-30 10:35:31.133  6120  6385 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 10:35:31.133  6120  6385 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
06-30 10:35:31.134  6120  6385 V BluetoothPbapService: Succeed to create listening socket 
06-30 10:35:31.134  6120  6385 V BluetoothPbapService: Accepting socket connection...
06-30 10:35:31.134  6300  6300 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
06-30 10:35:31.134  6120  6120 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 10:35:31.134  6120  6120 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:31.134  6120  6120 V BluetoothPbapReceiver: ***********state = 12
06-30 10:35:31.135  5800  5800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 10:35:31.137  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 10:35:31.138  2140  2140 D c       : Getting all permits...
06-30 10:35:31.138  2140  2140 D a       : Opening database...
,06-30 10:35:31.135  6300  6300 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
06-30 10:35:31.142  6300  6300 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
06-30 10:35:31.142  2140  2140 D a       : Opening database auth.proximity.permit_store...
06-30 10:35:31.143  6141  6141 D LocalBluetoothProfileManager: Adding local A2DP profile
06-30 10:35:31.143  2140  2140 D a       : Closing database...
06-30 10:35:31.146  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
06-30 10:35:31.146  1033  1115 D BluetoothManagerService: Message: 30
06-30 10:35:31.147  6300  6300 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-30 10:35:31.147  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
06-30 10:35:31.149  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
06-30 10:35:31.149  6141  6141 D LocalBluetoothProfileManager: Adding local HEADSET profile
,06-30 10:35:31.150  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
06-30 10:35:31.150  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
06-30 10:35:31.150  6300  6300 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1467275731150]
06-30 10:35:31.151  1033  1115 D BluetoothManagerService: Message: 30
06-30 10:35:31.151  6300  6300 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
06-30 10:35:31.158  1033  1984 I ActivityManager: Killing 5664:com.android.gallery3d/u0a27 (adj 15): empty #17
06-30 10:35:31.162  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 30 Jun 2016 08:35:31 GMT], X-Android-Received-Millis=[1467275731161], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467275731115]}
06-30 10:35:31.162  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-30 10:35:31.162  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
06-30 10:35:31.162  1033  1528 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
06-30 10:35:31.162  1033  1528 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-30 10:35:31.162  1033  1528 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:35:31.163  1033  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:31.163  1033  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-30 10:35:31.163  1033  1528 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
06-30 10:35:31.163  1033  1528 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-30 10:35:31.163  1033  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:31.163  1033  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:31.163  1033  1528 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:31.163  1033  1528 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:31.164  1033  1521 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:31.164  1033  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:35:31.164  1033  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
06-30 10:35:31.165  1563  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 10:35:31.165  1860  1860 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:31.165  1860  1860 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,06-30 10:35:31.176  6300  6386 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
06-30 10:35:31.240  1033  1115 I art     : Explicit concurrent mark sweep GC freed 75426(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.737ms total 85.119ms
,06-30 10:35:31.258  1033  1948 W libprocessgroup: failed to open /acct/uid_10027/pid_5664/cgroup.procs: No such file or directory
,06-30 10:35:31.264  6300  6300 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
06-30 10:35:31.264  1033  1115 D BluetoothManagerService: Message: 30
06-30 10:35:31.266  1033  1115 D BluetoothManagerService: Message: 30
06-30 10:35:31.268  6300  6300 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-30 10:35:31.269  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
06-30 10:35:31.269  6141  6141 D LocalBluetoothProfileManager: Adding local MAP profile
06-30 10:35:31.269  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
06-30 10:35:31.270  6141  6141 D BluetoothMap: Create BluetoothMap proxy object
06-30 10:35:31.270  1033  1115 D BluetoothManagerService: Message: 30
06-30 10:35:31.270  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
06-30 10:35:31.271  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
06-30 10:35:31.272  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,06-30 10:35:31.277  1033  1115 D BluetoothManagerService: Message: 30
06-30 10:35:31.280  6120  6120 V BluetoothPbapService: Pbap Service onBind
06-30 10:35:31.280  6141  6141 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
06-30 10:35:31.281  1563  1563 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
06-30 10:35:31.282  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:31.283  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 10:35:31.287  6141  6141 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,06-30 10:35:31.289  6141  6141 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
06-30 10:35:31.292  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
06-30 10:35:31.296  6141  6141 D DockEventReceiver: finishStartingService: stopping service
06-30 10:35:31.298  6141  6141 D BluetoothA2dp: Proxy object connected
06-30 10:35:31.298  6141  6141 D A2dpProfile: Bluetooth service connected
06-30 10:35:31.302  6141  6141 D BluetoothHeadset: Proxy object connected
,06-30 10:35:31.302  6141  6141 D HeadsetProfile: Bluetooth service connected
06-30 10:35:31.304  6141  6141 D BluetoothInputDevice: Proxy object connected
06-30 10:35:31.304  6141  6141 D HidProfile: Bluetooth service connected
06-30 10:35:31.305  6141  6141 D BluetoothPan: BluetoothPAN Proxy object connected
06-30 10:35:31.306  6141  6141 D PanProfile: Bluetooth service connected
06-30 10:35:31.308  6141  6141 D BluetoothMap: Proxy object connected
06-30 10:35:31.308  6141  6141 D MapProfile: Bluetooth service connected
06-30 10:35:31.308  6141  6141 D BluetoothMap: getConnectedDevices()
06-30 10:35:31.309  6120  6137 V BluetoothMapService: getConnectedDevices()
06-30 10:35:31.309  6141  6141 D BluetoothPbap: Proxy object connected
06-30 10:35:31.310  6141  6141 D PbapServerProfile: Bluetooth service connected
06-30 10:35:31.310  6141  6141 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
06-30 10:35:31.313  6141  6141 D BluetoothPermissionRequest: onReceive
,06-30 10:35:31.314  6141  6141 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 10:35:31.315  6141  6141 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
06-30 10:35:31.326  6141  6141 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,06-30 10:35:31.329  1033  1948 I ActivityManager: Killing 5731:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,06-30 10:35:31.348  1033  1521 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-30 10:35:31.348  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-30 10:35:31.349  1033  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,06-30 10:35:31.349  1033  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-30 10:35:31.349  1033  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-30 10:35:31.350  1033  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-30 10:35:31.350  1033  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
06-30 10:35:31.351  1033  1528 D ConnectivityService: identical MTU - not setting
06-30 10:35:31.351  1033  1528 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
06-30 10:35:31.351  1033  1528 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
06-30 10:35:31.352  1033  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:31.352  1033  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:31.353  1033  1528 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:31.355  1563  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-30 10:35:31.419  1033  1559 W libprocessgroup: failed to open /acct/uid_10061/pid_5731/cgroup.procs: No such file or directory
06-30 10:35:31.420  6120  6120 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,06-30 10:35:31.423  6120  6120 I LGBluetoothOppAdapter: [BTUI] startOppService()
06-30 10:35:31.434  6120  6120 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,06-30 10:35:31.468  6120  6120 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,06-30 10:35:31.468  6120  6120 V BtOppService: onCreate
06-30 10:35:31.472  6120  6120 V BluetoothOppNotification: send message
06-30 10:35:31.474  6120  6120 V BtOppService: Starting RfcommListener
06-30 10:35:31.477  6120  6120 D BluetoothOppPreference: Dumping Names:  
06-30 10:35:31.478  6120  6120 D BluetoothOppPreference: {}
06-30 10:35:31.478  6120  6120 D BluetoothOppPreference: Dumping Channels:  
06-30 10:35:31.478  6120  6120 D BluetoothOppPreference: {}
06-30 10:35:31.478  6120  6120 V BtOppService: onStartCommand
06-30 10:35:31.479  6120  6399 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
06-30 10:35:31.481  6120  6120 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:31.481  6120  6120 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,06-30 10:35:31.484  6120  6120 V BluetoothOppNotification: new notify threadi!
06-30 10:35:31.484  6120  6120 V BluetoothOppNotification: send delay message
06-30 10:35:31.485  6120  6120 V BtOppService: start RfcommListener
06-30 10:35:31.488  6120  6120 V BtOppService: RfcommListener started
06-30 10:35:31.488  6120  6401 V BtOppRfcommListener: Starting RFCOMM listener....
06-30 10:35:31.489  1033  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:31.489  6120  6401 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 10:35:31.490  6120  6401 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
06-30 10:35:31.490  6120  6401 V BtOppRfcommListener: Started RFCOMM listener....
06-30 10:35:31.490  6120  6401 I BtOppRfcommListener: Accept thread started.
06-30 10:35:31.490  6120  6401 V BtOppRfcommListener: Accepting connection...
06-30 10:35:31.491  6120  6396 V BtOppService: Deleted complete outbound shares, number =  0
06-30 10:35:31.492  6120  6400 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
06-30 10:35:31.493  6120  6396 V BtOppService: Deleted complete inbound failed shares, number = 0
06-30 10:35:31.494  6120  6396 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
06-30 10:35:31.494  6120  6396 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@394f194e on behalf of 
06-30 10:35:31.496  6120  6400 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20b7ba6f on behalf of 
06-30 10:35:31.496  6120  6400 V BluetoothOppNotification: mUpdateCompleteNotification = true
,06-30 10:35:31.497  6120  6400 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,06-30 10:35:31.498  6120  6400 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9e2637c on behalf of 
06-30 10:35:31.499  6120  6400 V BluetoothOppNotification: outbound: succ-0  fail-0
06-30 10:35:31.500  6120  6400 V BluetoothOppNotification: outbound notification was removed.
06-30 10:35:31.501  6120  6400 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
06-30 10:35:31.501  6120  6400 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d9c5405 on behalf of 
06-30 10:35:31.502  6120  6400 V BluetoothOppNotification: inbound: succ-0  fail-0
06-30 10:35:31.502  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:31.502  6120  6399 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-30 10:35:31.503  6120  6120 V BluetoothFtpService: Ftp Service onCreate
06-30 10:35:31.503  6120  6120 I BluetoothFtpService: Ftp Service onCreate
06-30 10:35:31.503  6120  6120 V BluetoothFtpService: Ftp Service onStartCommand
06-30 10:35:31.503  6120  6120 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:31.503  6120  6400 V BluetoothOppNotification: inbound notification was removed.
06-30 10:35:31.503  6120  6120 V BluetoothFtpService: Starting Listening on sockets
06-30 10:35:31.503  6120  6400 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
06-30 10:35:31.503  6120  6120 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 10:35:31.503  6120  6120 V BluetoothSapReceiver: [BTUI] region:EU country:EU
06-30 10:35:31.503  6120  6120 V BluetoothSapReceiver: SapReceiver onReceive 
06-30 10:35:31.504  6120  6120 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:31.504  6120  6120 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
06-30 10:35:31.504  6120  6120 V BluetoothSapReceiver: Calling SAP service start service with action = null
06-30 10:35:31.504  6120  6399 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38af8e8b on behalf of 
06-30 10:35:31.505  6120  6400 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ab03b68 on behalf of 
06-30 10:35:31.505  6120  6120 V BtOppService: ContentObserver received notification
06-30 10:35:31.506  6120  6120 V BtOppService: ContentObserver received notification
06-30 10:35:31.506  6120  6120 V BluetoothFtpService: Handler(): got msg=1
06-30 10:35:31.506  6120  6120 V BluetoothFtpService: Ftp Service startRfcommSocketListener
06-30 10:35:31.506  6120  6120 V BluetoothFtpService: Ftp Service initSocket
06-30 10:35:31.507  6120  6399 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
06-30 10:35:31.507  6120  6399 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-30 10:35:31.508  1033  1948 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,06-30 10:35:31.510  6120  6120 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 10:35:31.510  6120  6399 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39932b81 on behalf of 
06-30 10:35:31.511  6120  6120 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
06-30 10:35:31.511  6120  6120 V BluetoothFtpService: Succeed to create listening socket on channel 20
06-30 10:35:31.513  6120  6402 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
06-30 10:35:31.517  6120  6399 V BluetoothOppNotification: update too frequent, put in queue
06-30 10:35:31.517  6120  6399 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
06-30 10:35:31.527  6120  6120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a1c8554
06-30 10:35:31.527  6120  6120 V BluetoothSapService: Sap Service onCreate
,06-30 10:35:31.529  6120  6120 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:31.529  6120  6120 V BluetoothSapService: state: 12
06-30 10:35:31.529  6120  6120 V BluetoothSapService: Starting SAP server process
06-30 10:35:31.532  6120  6120 V BluetoothSapService: SAP Service startRfcommListenerThread
06-30 10:35:31.533  6120  6404 V BluetoothSapService: Sap Service initRfcommSocket
06-30 10:35:31.533  1033  1582 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:31.534  6120  6404 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 10:35:31.534  6120  6404 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
06-30 10:35:31.534  6120  6404 V BluetoothSapService: Succeed to create listening socket 
06-30 10:35:31.535  6120  6404 V BluetoothSapService: Accepting socket connection...
06-30 10:35:31.528  6403  6403 W sapd    : type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 10:35:31.528  6403  6403 W sapd    : type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,06-30 10:35:31.547  6403  6403 V BT_SAP  : Event pipe created
,06-30 10:35:31.547  6403  6403 V BT_SAP  : create_server_socket qcom.sap.server
06-30 10:35:31.548  6403  6403 V BT_SAP  : created socket fd 6
06-30 10:35:32.487  6120  6120 V BluetoothOppNotification: new notify threadi!
,06-30 10:35:32.488  6120  6120 V BluetoothOppNotification: send delay message
06-30 10:35:32.491  6120  6411 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
06-30 10:35:32.493  6120  6411 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ec5febd on behalf of 
06-30 10:35:32.494  6120  6411 V BluetoothOppNotification: mUpdateCompleteNotification = true
06-30 10:35:32.495  6120  6411 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-30 10:35:32.496  6120  6411 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31193cb2 on behalf of 
06-30 10:35:32.496  6120  6411 V BluetoothOppNotification: outbound: succ-0  fail-0
06-30 10:35:32.497  6120  6411 V BluetoothOppNotification: outbound notification was removed.
06-30 10:35:32.497  6120  6411 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
06-30 10:35:32.498  6120  6411 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3be94403 on behalf of 
06-30 10:35:32.498  6120  6411 V BluetoothOppNotification: inbound: succ-0  fail-0
06-30 10:35:32.500  6120  6411 V BluetoothOppNotification: inbound notification was removed.
06-30 10:35:32.500  6120  6411 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,06-30 10:35:32.502  6120  6411 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@325d0f80 on behalf of 
,06-30 10:35:32.685   314  6360 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
,06-30 10:35:32.741  1033  6359 D LocSvc_java: NTP server : europe.pool.ntp.org
,06-30 10:35:32.742  1033  6359 D LocSvc_java: NTP server returned: 1467275733368 (Thu Jun 30 10:35:33 GMT+02:00 2016) reference: 105390 certainty: 26 system time offset: 627
,06-30 10:35:32.746  1033  6359 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
,06-30 10:35:32.867  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1603082365] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:35:32.868  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1603082364] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:35:32.868  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:35:32.877  1563  1563 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-30 10:35:33.449  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-30 10:35:33.449  5800  5862 I jxcore-log: 
,06-30 10:35:33.754  1033  1523 V WifiInternetCheck: Single check msg out of sync, ignoring.
,06-30 10:35:33.794  1033  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
06-30 10:35:33.795  1033  1103 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,06-30 10:35:33.797  1033  1115 D Tethering: MasterInitialState.processMessage what=3
06-30 10:35:33.801  1033  1813 D AlarmManagerService: Setting time of day to sec=1467275734
06-30 10:35:34.421  1033  1813 W AlarmManagerService: Unable to set rtc to 1467275734: Invalid argument
06-30 10:35:34.421  5800  5800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 10:35:34.436  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,06-30 10:35:34.443  5056  5094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
06-30 10:35:34.455  5168  5168 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-30 10:35:34.469  2689  2689 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
06-30 10:35:34.470  2689  2689 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-06-30 10:35:34...... Request
06-30 10:35:34.470  2689  2689 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 2, total count : 10, new day : false...... Request
06-30 10:35:34.470  2689  2689 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 10
06-30 10:35:34.470  2689  2689 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 2
06-30 10:35:34.471  2689  2689 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-06-30 10:35:34
,06-30 10:35:34.475  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:35:34.476  1563  1563 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
06-30 10:35:34.476  1949  1949 I SecureClockService: Intent.ACTION_TIME_CHANGED 
06-30 10:35:34.477  1033  2077 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
06-30 10:35:34.478  1563  1563 I LgeClockWidgetControlView: time changed, timezoneChanged : false
06-30 10:35:34.478  2060  2060 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=30 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
06-30 10:35:34.480  2060  2060 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 30
06-30 10:35:34.481  4611  4611 I CalendarProvider2: onReceive() android.intent.action.TIME_SET
06-30 10:35:34.481  4611  4611 D CalendarProvider2: Scheduling check of next Alarm
06-30 10:35:34.483  2060  2060 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 30
06-30 10:35:34.483  2060  2060 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 10:35:34.492  2574  2574 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 10:35:34.503  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-30 10:35:34.503  5800  5862 I jxcore-log: 
06-30 10:35:34.505  1033  1103 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:34.518  1802  6422 I CheckinService: active receiver: enabled
06-30 10:35:34.519  1802  6422 I CheckinService: Preparing to send checkin request
06-30 10:35:34.519  1802  6422 I EventLogService: Accumulating logs since 1467274336503
06-30 10:35:34.523  1033  1103 E GpsLocationProvider: No APN found to select.
06-30 10:35:34.528  2140  2140 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,06-30 10:35:34.533  1033  1744 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
06-30 10:35:34.533  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:34.534  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:34.534  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
06-30 10:35:34.534  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:34.534  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-30 10:35:34.537   314  6426 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:35:34.537   314  6426 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,06-30 10:35:34.550  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-30 10:35:34.550  5800  5862 I jxcore-log: 
06-30 10:35:34.557  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-30 10:35:34.557  5800  5862 I jxcore-log: 
,06-30 10:35:34.577  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 30 Jun 2016 08:35:34 GMT], X-Android-Received-Millis=[1467275734577], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467275734534]}
,06-30 10:35:34.577  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-30 10:35:34.577  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
06-30 10:35:34.578  1033  1528 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
06-30 10:35:34.578  1033  1528 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-30 10:35:34.578  1033  1528 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:35:34.578  1033  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:34.578  1033  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-30 10:35:34.578  1033  1528 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
06-30 10:35:34.578  1033  1528 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-30 10:35:34.578  1033  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:34.578  1033  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:34.578  1033  2077 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6429 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
06-30 10:35:34.578  1033  1528 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:34.580  1563  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 10:35:34.583  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-30 10:35:34.583  5800  5862 I jxcore-log: 
06-30 10:35:34.585   314  6426 D libc-netbsd: res_queryN name = mtalk.google.com succeed
06-30 10:35:34.589  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-30 10:35:34.589  5800  5862 I jxcore-log: 
,06-30 10:35:34.625  1802  6422 W EventLogAggregator: Unknown tag: snet_gcore
06-30 10:35:34.625  1802  6422 W EventLogAggregator: Unknown tag: snet_launch_service
,06-30 10:35:34.631  6429  6429 I AppUp4:AppBoxCP: onCreate
06-30 10:35:34.631  6429  6429 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
06-30 10:35:34.636  6429  6429 I AppUp4:DB:  setFingerPrint start
06-30 10:35:34.636  6429  6429 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
06-30 10:35:34.640  6429  6429 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
06-30 10:35:34.641  6429  6429 I AppUp4:DB:  SDK version = 21
06-30 10:35:34.641  6429  6429 I AppUp4:DB:  beforefinger == newfinger no write in DB
06-30 10:35:34.642  6429  6429 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
06-30 10:35:34.642  6429  6429 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
06-30 10:35:34.642  6429  6429 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
06-30 10:35:34.644  6429  6429 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
06-30 10:35:34.644  6429  6429 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,06-30 10:35:34.647  6429  6429 I AppUp4:CustModeStarterReceiver: onReceive
06-30 10:35:34.675  6429  6429 D LgDataFeature: LgDataFeature() Constructor: none
,06-30 10:35:34.675  6429  6429 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 10:35:34.679  1802  6422 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
06-30 10:35:34.681  6429  6429 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@39d05ca7
06-30 10:35:34.681  6429  6429 D AppUp4:CustFacade: isCustomizationCompleted : false
06-30 10:35:34.681  6429  6429 D AppUp4:CustFacade: isPhone : true
06-30 10:35:34.682  6429  6429 D AppUp4:CustModeStarterReceiver: begin check event
06-30 10:35:34.682  6429  6429 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
06-30 10:35:34.683  6429  6429 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
06-30 10:35:34.685  1033  1527 D WifiService: New client listening to asynchronous messages
06-30 10:35:34.688  6429  6447 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
06-30 10:35:34.688  6429  6447 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
06-30 10:35:34.688  6429  6447 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
06-30 10:35:34.689  1033  2077 I ActivityManager: Killing 5870:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,06-30 10:35:34.696  2140  6425 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
06-30 10:35:34.778  3266  3266 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
06-30 10:35:34.778  3266  3266 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 10:35:34.779  1033  1948 W libprocessgroup: failed to open /acct/uid_10080/pid_5870/cgroup.procs: No such file or directory
,06-30 10:35:34.782  3266  3266 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 10:35:34.791  3266  3266 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 10:35:34.802  3447  3447 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,06-30 10:35:34.806  3447  3447 V DownloadManager: DownloadService onCreate
06-30 10:35:34.808  3266  6453 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 10:35:34.811  3447  6455 I DownloadManager: in removeSpuriousFiles
06-30 10:35:34.813  3447  6455 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
06-30 10:35:34.814  3266  6453 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
06-30 10:35:34.815  3447  6455 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2c50ad52 on behalf of 3447
06-30 10:35:34.815  3447  6455 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
06-30 10:35:34.815  3447  6455 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
06-30 10:35:34.815  3447  6455 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
06-30 10:35:34.815  3447  6455 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
06-30 10:35:34.815  3447  6455 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
06-30 10:35:34.815  3447  6455 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
06-30 10:35:34.816  3447  6455 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
06-30 10:35:34.816  3447  6455 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
06-30 10:35:34.816  3447  6455 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
06-30 10:35:34.816  3447  6455 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
06-30 10:35:34.818  3447  6455 I DownloadManager: in trimDatabase
,06-30 10:35:34.819  3447  6455 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
06-30 10:35:34.823  3447  6455 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1294f823 on behalf of 3447
06-30 10:35:34.824  3266  6454 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
06-30 10:35:34.825  3266  6454 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-30 10:35:34.844  1033  1581 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6460 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,06-30 10:35:34.846  3447  3447 V DownloadManager: DownloadService onStartCommand
06-30 10:35:34.846  3447  6456 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
06-30 10:35:34.847  3266  6453 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
06-30 10:35:34.851  3447  6456 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@19a84c9e on behalf of 3447
06-30 10:35:34.852  3447  6456 V DownloadManager: processing inserted download 1
06-30 10:35:34.854  3447  6456 V DownloadManager: processing inserted download 4
06-30 10:35:34.855  3447  6456 V DownloadManager: processing inserted download 7
06-30 10:35:34.867  3266  3266 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,06-30 10:35:34.869  3266  3266 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
06-30 10:35:34.870  3266  3266 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
06-30 10:35:34.872  3266  3266 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
06-30 10:35:34.874  3447  6456 V DownloadManager: processing inserted download 8
06-30 10:35:34.875  3447  6456 V DownloadManager: processing inserted download 9
06-30 10:35:34.876  3447  6456 V DownloadManager: processing inserted download 10
06-30 10:35:34.877  3447  6456 V DownloadManager: processing inserted download 11
06-30 10:35:34.878  3447  6456 V DownloadManager: processing inserted download 12
,06-30 10:35:34.879  3447  6456 V DownloadManager: processing inserted download 13
06-30 10:35:34.879  3266  3266 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
06-30 10:35:34.880  3447  6456 V DownloadManager: processing inserted download 14
,06-30 10:35:34.889  3447  3447 V DownloadManager: DownloadService onDestroy
06-30 10:35:34.902  6460  6460 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:35:34.902  6460  6460 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:35:34.903  6460  6460 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 10:35:34.903  6460  6460 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
06-30 10:35:34.964  6460  6460 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,06-30 10:35:34.973  6460  6460 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
06-30 10:35:35.012  1033  1911 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6478 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,06-30 10:35:35.018  6460  6460 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:35:35.041  6460  6460 D LgDataFeature: LgDataFeature() Constructor: none
06-30 10:35:35.041  6460  6460 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 10:35:35.086  6478  6478 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 10:35:35.086  6478  6478 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-30 10:35:35.102  6460  6460 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,06-30 10:35:35.115  6478  6478 I MultiDex: VM with version 2.1.0 has multidex support
06-30 10:35:35.115  6478  6478 I MultiDex: install
06-30 10:35:35.115  6478  6478 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 10:35:35.125  6460  6460 I HubEmail: JNI_OnLoad()
06-30 10:35:35.125  6460  6460 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 10:35:35.125  6460  6460 I HubEmail: registerNatives()
06-30 10:35:35.125  6460  6460 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 10:35:35.125  6460  6460 I HubEmail: registerNativeMethods()
06-30 10:35:35.125  6460  6460 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 10:35:35.125  6460  6460 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
06-30 10:35:35.125  6478  6478 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
06-30 10:35:35.126  3412  3412 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
06-30 10:35:35.129  3412  3412 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
06-30 10:35:35.131  3412  3412 I LgeMiscReceiver: networkInfo.isConnected() = true
06-30 10:35:35.131  3412  3412 D PhoneState: setPdpRejectCasuse : false
,06-30 10:35:35.167  1033  1559 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6504 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,06-30 10:35:35.180  6460  6501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:35:35.227   314  6522 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:35:35.227   314  6522 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,06-30 10:35:35.258  6504  6504 D LgDataFeature: LgDataFeature() Constructor: none
06-30 10:35:35.258  6504  6504 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 10:35:35.260  6504  6504 D PhoneMonitor: Register our PhoneStateListener
,06-30 10:35:35.269  6504  6504 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
06-30 10:35:35.271  6504  6504 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,06-30 10:35:35.279  6504  6504 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
06-30 10:35:35.279  6504  6504 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
06-30 10:35:35.280  6504  6504 D TelephonyAutoProfiling: [parse] Load xml
06-30 10:35:35.282  6504  6504 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
06-30 10:35:35.282  6504  6504 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
06-30 10:35:35.283  6504  6504 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
06-30 10:35:35.288  6504  6504 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
06-30 10:35:35.290   314  6522 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,06-30 10:35:35.299  1033  1581 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6525 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 10:35:35.300  1033  1581 I ActivityManager: Killing 5895:com.google.android.apps.plus/u0a97 (adj 15): empty #17
06-30 10:35:35.331  6172  6503 V FormManager: There are no updated forms. The schedule will be deleted.
,06-30 10:35:35.333  6172  6503 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
06-30 10:35:35.372  1033  1911 W libprocessgroup: failed to open /acct/uid_10097/pid_5895/cgroup.procs: No such file or directory
,06-30 10:35:35.400  1033  1582 I ActivityManager: Killing 5933:com.lge.eula/1000 (adj 15): empty #17
,06-30 10:35:35.427  6542  6542 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-30 10:35:35.487  1033  2077 W libprocessgroup: failed to open /acct/uid_1000/pid_5933/cgroup.procs: No such file or directory
,06-30 10:35:35.564  6542  6542 I dex2oat : dex2oat took 136.392ms (threads: 4)
,06-30 10:35:35.578  6478  6494 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:35:35.578  6478  6494 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:35:35.578  6478  6494 I Adreno-EGL: Build Date: 12/12/14 금
06-30 10:35:35.578  6478  6494 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-30 10:35:35.578  6478  6494 I Adreno-EGL: Remote Branch: 
06-30 10:35:35.578  6478  6494 I Adreno-EGL: Local Patches: 
06-30 10:35:35.578  6478  6494 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:35:35.582   314  6549 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:35:35.583   314  6549 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
06-30 10:35:35.618   314  6549 D libc-netbsd: res_queryN name = www.google.com succeed
,06-30 10:35:35.631   314  6552 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-30 10:35:35.633   314  6552 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
06-30 10:35:35.633   314  6552 D libc-netbsd: res_queryN name = clients3.google.com succeed
06-30 10:35:35.674  1033  1581 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6553 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,06-30 10:35:35.677  1033  1581 I ActivityManager: Killing 5954:com.android.calendar/u0a13 (adj 15): empty #17
06-30 10:35:35.679  6478  6494 D LgDataFeature: LgDataFeature() Constructor: none
06-30 10:35:35.679  6478  6494 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 10:35:35.682   343   343 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 544us total 10.608ms
06-30 10:35:35.691   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.786ms
,06-30 10:35:35.700   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 8.965ms
06-30 10:35:35.703  1033  1524 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,06-30 10:35:35.770  1033  1048 W libprocessgroup: failed to open /acct/uid_10013/pid_5954/cgroup.procs: No such file or directory
,06-30 10:35:35.803  6553  6553 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,06-30 10:35:35.804  6553  6553 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
06-30 10:35:35.820  6553  6553 V DrmService: Service onCreate
06-30 10:35:35.821  6553  6553 D DrmService: Received new request = 2
,06-30 10:35:35.825  6553  6570 I DrmSntpClient: Start Sync process
06-30 10:35:35.825  6553  6570 D DrmSntpClient: Server : 0
06-30 10:35:35.828   314  6571 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:35:35.828   314  6571 D libc-netbsd: res_queryN name = pool.ntp.org, class = 1, type = 1
06-30 10:35:35.857  1033  1744 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6572 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:35.863   314  6571 D libc-netbsd: res_queryN name = pool.ntp.org succeed
06-30 10:35:35.877  6553  6570 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
06-30 10:35:35.878   325   899 V ILGDrmService: eDRM_SetDRMTime +++
06-30 10:35:35.878   325   899 I LGDRM   : [DRM] SET TIME : YR=2016, MON=6, DAY=30
06-30 10:35:35.878   325   899 I LGDRM   : [DRM] SET TIME : HR=8, MIN=35, SEC=34
,06-30 10:35:35.889   325   899 V ILGDrmService: eDRM_SetDRMTime ---
06-30 10:35:35.889  6553  6570 I DrmSntpClient: Synched
06-30 10:35:35.890  6553  6553 D DrmService: Completed !! request = 2
06-30 10:35:35.890  6553  6553 D DrmService: Request count = 0
06-30 10:35:35.891  6553  6553 V DrmService: Service onDestroy
06-30 10:35:35.893  1033  1048 I ActivityManager: Killing 4611:com.android.providers.calendar/u0a14 (adj 15): empty #17
,06-30 10:35:35.899  6572  6572 I art     : Almond Protected OAT
,06-30 10:35:36.009  1033  1582 W libprocessgroup: failed to open /acct/uid_10014/pid_4611/cgroup.procs: No such file or directory
,06-30 10:35:36.017  6572  6572 D WeatherApplication: removeAccount
06-30 10:35:36.019  6572  6572 D WeatherApplication: Account.length = 0
06-30 10:35:36.020  6572  6572 E WeatherApplication: OPERATOR:OPEN
06-30 10:35:36.028  6572  6572 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:35:36
,06-30 10:35:36.035  6572  6572 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
06-30 10:35:36.035  6572  6572 D Weather.Utils: 2 : All the weather widget is gone.
06-30 10:35:36.037  6572  6572 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-30 10:35:36.040  6572  6572 D WeatherAncestor: connectivity changed - connection : true
06-30 10:35:36.041  6572  6572 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,06-30 10:35:36.054  6572  6572 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
06-30 10:35:36.054  6572  6572 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,06-30 10:35:36.054  6572  6572 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
06-30 10:35:36.082  6572  6572 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-30 10:35:36.082  6572  6572 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:35:36
,06-30 10:35:36.107  1033  2030 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6590 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 10:35:36.108  1033  2030 I ActivityManager: Killing 5688:com.android.vending/u0a44 (adj 15): empty #17
,06-30 10:35:36.215  6478  6494 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:35:36.215  6478  6494 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:35:36.215  6478  6494 I Adreno-EGL: Build Date: 12/12/14 금
06-30 10:35:36.215  6478  6494 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-30 10:35:36.215  6478  6494 I Adreno-EGL: Remote Branch: 
06-30 10:35:36.215  6478  6494 I Adreno-EGL: Local Patches: 
06-30 10:35:36.215  6478  6494 I Adreno-EGL: Reconstruct Branch: 
06-30 10:35:36.246  1033  1581 W libprocessgroup: failed to open /acct/uid_10044/pid_5688/cgroup.procs: No such file or directory
,06-30 10:35:36.276  6478  6494 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:35:36.276  6478  6494 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:35:36.276  6478  6494 I Adreno-EGL: Build Date: 12/12/14 금
06-30 10:35:36.276  6478  6494 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-30 10:35:36.276  6478  6494 I Adreno-EGL: Remote Branch: 
06-30 10:35:36.276  6478  6494 I Adreno-EGL: Local Patches: 
06-30 10:35:36.276  6478  6494 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:35:36.358   279   416 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:35:36.358   279   416 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-30 10:35:36.358   279   416 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:35:36.358  6590  6608 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,06-30 10:35:36.361   279   416 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:35:36.361   279   416 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-30 10:35:36.361   279   416 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:35:36.361  6590  6608 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-30 10:35:36.368   314  6613 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:35:36.368   314  6613 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
06-30 10:35:36.371   279   416 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,06-30 10:35:36.371   279   416 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-30 10:35:36.371   279   416 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:35:36.372  6590  6610 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
06-30 10:35:36.374   279   416 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:35:36.374   279   416 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-30 10:35:36.374   279   416 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:35:36.375  6590  6610 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-30 10:35:36.412   314  6613 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-30 10:35:36.478  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3f707245 type 2 when 108509 com.google.android.gms} when 108509
,06-30 10:35:36.497  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3621] from screen [on:0 period:-1603078736] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 10:35:36.497  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1603078735] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 10:35:36.497  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:35:36.525  6590  6590 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,06-30 10:35:36.531  6590  6590 I LibraryLoader: Loading: webviewchromium
06-30 10:35:36.533  6590  6590 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8575-8577)
06-30 10:35:36.534  6590  6590 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:36.544  6590  6590 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23eb0bee}
06-30 10:35:36.545  6590  6590 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:36.545  6590  6590 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 10:35:36.553  6590  6590 I BrowserStartupController: Initializing chromium process, renderers=0
06-30 10:35:36.553  6590  6590 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:36.568  6590  6590 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
06-30 10:35:36.569   319  1367 V AudioPolicyService: registerClient() client 0xb558a540, uid 10093
,06-30 10:35:36.569  6590  6590 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
06-30 10:35:36.570  6590  6590 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
06-30 10:35:36.572  6590  6642 W AudioManagerAndroid: Requires BLUETOOTH permission
06-30 10:35:36.583  6590  6590 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:35:36.583  6590  6590 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:35:36.583  6590  6590 I Adreno-EGL: Build Date: 12/12/14 금
06-30 10:35:36.583  6590  6590 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-30 10:35:36.583  6590  6590 I Adreno-EGL: Remote Branch: 
06-30 10:35:36.583  6590  6590 I Adreno-EGL: Local Patches: 
06-30 10:35:36.583  6590  6590 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:35:36.638  6052  6373 D UEI.SmartControl: Internal timer expired: 4
06-30 10:35:36.638  6052  6373 D UEI.SmartControl: unbind internal service
,06-30 10:35:36.657  6590  6590 I NSApplication: Starting up...
,06-30 10:35:36.691  1802  6422 I CheckinTask: Sending checkin request (7758 bytes)
,06-30 10:35:36.693  6052  6369 D serial_port: close(fd = 24)
06-30 10:35:36.698  6052  6369 I UEI.SmartControl: Serial port is closed.
06-30 10:35:36.720  1033  2077 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6656 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:36.722  1033  2077 I ActivityManager: Killing 4833:com.lge.bnr/1000 (adj 15): empty #17
06-30 10:35:36.809  1033  1911 W libprocessgroup: failed to open /acct/uid_1000/pid_4833/cgroup.procs: No such file or directory
,06-30 10:35:36.842  6656  6656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:35:36.848  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-30 10:35:36.848  5800  5862 I jxcore-log: 
06-30 10:35:36.858  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-30 10:35:36.858  5800  5862 I jxcore-log: 
,06-30 10:35:36.866  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-30 10:35:36.866  5800  5862 I jxcore-log: 
06-30 10:35:36.945  1033  1559 I art     : Explicit concurrent mark sweep GC freed 22346(1163KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.762ms total 107.018ms
,06-30 10:35:36.946  1033  1046 I art     : WaitForGcToComplete blocked for 90.775ms for cause HeapTrim
,06-30 10:35:37.017  1802  6422 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,06-30 10:35:37.024  1802  6422 I CheckinService: active receiver: disabled
06-30 10:35:37.027  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-30 10:35:37.027  5800  5862 I jxcore-log: 
,06-30 10:35:37.054  1802  6681 I CheckinService: active receiver: disabled
,06-30 10:35:37.060  5056  5056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,06-30 10:35:37.092  1033  1582 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6685 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,06-30 10:35:37.097  1802  6684 I CheckinService: active receiver: disabled
06-30 10:35:37.115  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-30 10:35:37.115  5800  5862 I jxcore-log: 
,06-30 10:35:37.160  6685  6709 D ALBootInit: ====action==>android.intent.action.TIME_SET
,06-30 10:35:37.163  6685  6709 D ALBootInit: Alarm ALBootInit: TIME_SET
06-30 10:35:37.166  6685  6709 D Alarms  : [setNextAlert] start
06-30 10:35:37.173  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-30 10:35:37.173  5800  5862 I jxcore-log: 
,06-30 10:35:37.177  6685  6709 D Alarms  : [setNextAlert] (1)
06-30 10:35:37.179  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-30 10:35:37.179  5800  5862 I jxcore-log: 
06-30 10:35:37.179  6685  6709 D Alarms  :  minTime  = 0
06-30 10:35:37.180  6685  6709 D Alarms  :  -- OK multi -- 0
06-30 10:35:37.181  6685  6709 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
06-30 10:35:37.181  6685  6709 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
06-30 10:35:37.202  6685  6709 I CommonUtil: BUILD Country: EU
,06-30 10:35:37.203  6685  6709 D Alarms  : broadcastToWidgetProvider : false
06-30 10:35:37.207  6685  6709 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
06-30 10:35:37.217  1033  1048 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,06-30 10:35:37.220  6685  6685 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
06-30 10:35:37.222  6685  6685 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2a1c8554
06-30 10:35:37.223  6685  6685 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2a1c8554
06-30 10:35:37.225  6685  6685 D QuickCoverProvider: onReceiver
06-30 10:35:37.240  1541  1541 I indal   : SmartCoverWidgetContext createApplicationContext
,06-30 10:35:37.240  1541  1541 I indal   : SmartCoverWidgetContext createApplicationContext
06-30 10:35:37.251  6572  6572 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 10:35:37
,06-30 10:35:37.256  6572  6572 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
06-30 10:35:37.256  6572  6572 D Weather.Utils: 2 : All the weather widget is gone.
06-30 10:35:37.256  6572  6572 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-30 10:35:37.259  6572  6572 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@11bc8cfd
06-30 10:35:37.259  6572  6572 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
06-30 10:35:37.259  6572  6572 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
06-30 10:35:37.259  6572  6572 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
06-30 10:35:37.261  6572  6572 D Weather_cast: 2 : set auto-update time : 6/30 13:35
06-30 10:35:37.266  6572  6572 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 10:35:37
,06-30 10:35:37.327  1033  1582 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6719 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
06-30 10:35:37.329  1033  1582 I ActivityManager: Killing 2206:com.lge.music/u0a34 (adj 15): empty #17
,06-30 10:35:37.366   319  1366 V AudioFlinger: 2206 died, releasing its sessions
06-30 10:35:37.366   319  1366 V AudioFlinger:  pid 1860 @ 0
06-30 10:35:37.366   319  1366 V AudioFlinger:  pid 3412 @ 1
,06-30 10:35:37.366   319  1366 V AudioFlinger:  pid 3412 @ 2
06-30 10:35:37.401  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-30 10:35:37.401  5800  5862 I jxcore-log: 
,06-30 10:35:37.421  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-30 10:35:37.421  5800  5862 I jxcore-log: 
,06-30 10:35:37.425  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-30 10:35:37.425  5800  5862 I jxcore-log: 
06-30 10:35:37.430  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-30 10:35:37.430  5800  5862 I jxcore-log: 
06-30 10:35:37.445  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-30 10:35:37.445  5800  5862 I jxcore-log: 
,06-30 10:35:37.463  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-30 10:35:37.463  5800  5862 I jxcore-log: 
,06-30 10:35:37.507  1033  1911 W libprocessgroup: failed to open /acct/uid_10034/pid_2206/cgroup.procs: No such file or directory
,06-30 10:35:37.561  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-30 10:35:37.561  5800  5862 I jxcore-log: 
,06-30 10:35:37.566  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-30 10:35:37.566  5800  5862 I jxcore-log: 
06-30 10:35:37.573  6719  6719 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1467275737573
06-30 10:35:37.573  6719  6719 D         : TimeServiceNative: User Time to be set is 1467275737573
06-30 10:35:37.573  6719  6719 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
06-30 10:35:37.573  6719  6719 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
06-30 10:35:37.573  6719  6719 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1467275737573
06-30 10:35:37.573   360  1032 D QC-time-services: Daemon: Connection accepted:time_genoff
06-30 10:35:37.574  6719  6719 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
06-30 10:35:37.574   360  6739 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1467275737573
06-30 10:35:37.574   360  6739 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1467275737573, operation = 0
06-30 10:35:37.574   360  6739 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/10/70 3:3:32
06-30 10:35:37.574   360  6739 D QC-time-services: Daemon:Value read from RTC seconds = 788612000
06-30 10:35:37.575   360  6739 D QC-time-services: Daemon:new time 1467275737573 
06-30 10:35:37.575   360  6739 D QC-time-services: Daemon: delta 1466487125573 genoff 1466487125573 
06-30 10:35:37.575   360  6739 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487125573 to memory
06-30 10:35:37.575   360  6739 D QC-time-services: Daemon:Opening File: /data/time/ats_2
06-30 10:35:37.575   360  6739 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
06-30 10:35:37.581   360  6739 D QC-time-services: Updating the TOD offset
06-30 10:35:37.581   360  6739 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487125573 to memory
06-30 10:35:37.581   360  6739 D QC-time-services: Daemon:Opening File: /data/time/ats_1
06-30 10:35:37.581   360  6739 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,06-30 10:35:37.586   360  6739 E QC-time-services: Daemon:Update to modem bit set,
06-30 10:35:37.586   360  6739 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
06-30 10:35:37.586   360  6739 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522325573
06-30 10:35:37.586  6719  6719 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
06-30 10:35:37.588   360  1030 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
06-30 10:35:37.588   360  1032 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
06-30 10:35:37.592  5800  5862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-30 10:35:37.592  5800  5862 I jxcore-log: 
06-30 10:35:37.601  5800  5862 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,06-30 10:35:37.602  5800  5862 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-30 10:35:37.602  5800  5862 I jxcore-log: 
,06-30 10:35:37.649  1033  1048 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6740 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
06-30 10:35:37.650  1033  1048 I ActivityManager: Killing 6217:com.lge.sync/1000 (adj 15): empty #17
06-30 10:35:37.654  5800  5862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 10:35:37.654  5800  5862 I jxcore-log: 
06-30 10:35:37.655  5800  5862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 10:35:37.655  5800  5862 I jxcore-log: 
06-30 10:35:37.697  1033  1947 W libprocessgroup: failed to open /acct/uid_1000/pid_6217/cgroup.procs: No such file or directory
,06-30 10:35:37.770  6740  6740 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
,06-30 10:35:37.779  6740  6740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
06-30 10:35:37.792  6740  6740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
,06-30 10:35:37.794  6740  6740 V [BNRBootReceiver]: Boot Receiver Return
06-30 10:35:37.796  1563  1563 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
06-30 10:35:37.796  1563  1563 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
06-30 10:35:37.796  1563  1563 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
06-30 10:35:37.797  6740  6740 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 10:35:37.840  1033  2077 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6758 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,06-30 10:35:37.841  1033  2077 I ActivityManager: Killing 6193:com.lge.lifetracker/u0a37 (adj 15): empty #17
,06-30 10:35:37.891  1033  1984 W libprocessgroup: failed to open /acct/uid_10037/pid_6193/cgroup.procs: No such file or directory
06-30 10:35:37.923  6758  6758 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:35:37.960  6758  6758 D CalendarApplication: CalendarApplication.onCreate()
,06-30 10:35:37.975  6758  6758 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
,06-30 10:35:37.976  6758  6758 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@34589ecb, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@261fa6a8, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2e3155c1, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@7688166, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@39d05ca7, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2a1c8554, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@11bc8cfd, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@8eb4df2, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@391c1c43, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@66a2c0, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@11c9fbf9, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@395c573e, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@6da399f, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@18732aec, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1ea55eb5, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2442a94a, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3932d0bb, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1de09d8, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@279a3131, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@148a1016, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@16b3bd97, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2815eb84, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2b2faf6d, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@60f17a2, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@16ec9c33, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1cc83bf0, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@f24d569, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@23eb0bee, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@10cac88f, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1d0d271c, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3c2c5f25, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1f7ff8fa, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@32b55eab, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3d539908, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3968c8a1, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2c44aac6, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@20693a87, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@280d3db4, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3a84ddd, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2c50ad52, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1294f823, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$Key,Data@1b1a812
06-30 10:35:37.981  6758  6758 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
06-30 10:35:38.005  6758  6758 D Config  : [init]
,06-30 10:35:38.007  6758  6758 I Config  : LGCalendar ver.4.40.16
,06-30 10:35:38.008  6758  6758 I Config  : start check model
06-30 10:35:38.008  6758  6758 I Config  : start check native_ca
,06-30 10:35:38.010  6758  6758 I Config  : Config Operator=OPEN, Country=EU
06-30 10:35:38.011  6758  6758 D Config  : [setDefaultValuesToPref]
06-30 10:35:38.011  6758  6758 D Config  : [parseProfiles]
,06-30 10:35:38.022  6758  6758 D ProfilesParser: [debug_displayParseInfos] profile.country = null
06-30 10:35:38.023  6758  6758 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
06-30 10:35:38.023  6758  6758 D Config  : [updateProfiletoCountryInfo]
06-30 10:35:38.025  6758  6758 D GeneralPreference: [checkAndMigrateOldPreference]
,06-30 10:35:38.042  6758  6758 E AgendaWidgetManager: [updateWidgets] 
,06-30 10:35:38.055  6758  6777 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
06-30 10:35:38.059  6758  6777 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,06-30 10:35:38.097  6758  6777 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,06-30 10:35:38.105  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
06-30 10:35:38.110  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,06-30 10:35:38.115  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
06-30 10:35:38.119  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
06-30 10:35:38.123  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,06-30 10:35:38.129  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
06-30 10:35:38.134  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
06-30 10:35:38.138  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,06-30 10:35:38.144  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
06-30 10:35:38.149  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
06-30 10:35:38.154  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,06-30 10:35:38.160  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
06-30 10:35:38.200  3447  3463 I art     : Explicit concurrent mark sweep GC freed 4286(271KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 569us total 36.830ms
,06-30 10:35:38.203  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
06-30 10:35:38.211  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
06-30 10:35:38.216  6758  6777 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
06-30 10:35:38.217  6758  6777 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,06-30 10:35:38.220  6758  6777 I AlertUtils: set default noti to content://media/internal/audio/media/41
06-30 10:35:38.230  6758  6780 W HolidayIntentService: onHandleIntent
,06-30 10:35:38.231  6758  6758 D MonthWidgetProvider: [onReceive]
06-30 10:35:38.231  6758  6777 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
06-30 10:35:38.231  6758  6758 D CalendarWidgetProvider: [onReceive]
06-30 10:35:38.232  6758  6758 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
06-30 10:35:38.234  6758  6780 D HolidayDataLoader: readJsonAsset : holiday.json
06-30 10:35:38.237  6758  6758 D CalendarTypeController: [onUpdateAndInitCalendarTime]
06-30 10:35:38.250  6758  6758 D WeekWidgetProvider: [onReceive]
06-30 10:35:38.250  6758  6758 D CalendarWidgetProvider: [onReceive]
,06-30 10:35:38.250  6758  6758 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
06-30 10:35:38.251  6758  6758 D CalendarTypeController: [onUpdateAndInitCalendarTime]
06-30 10:35:38.260  2140  2140 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
06-30 10:35:38.270  2140  2140 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-30 10:35:38.272  2140  2140 D c       : Getting all permits...
06-30 10:35:38.272  2140  2140 D a       : Opening database...
06-30 10:35:38.277  2140  2140 D a       : Opening database auth.proximity.permit_store...
06-30 10:35:38.278  2140  2140 D a       : Closing database...
06-30 10:35:38.292   314  6787 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:35:38.292  6300  6300 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
06-30 10:35:38.292   314  6787 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
06-30 10:35:38.292   314  6787 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,06-30 10:35:38.294  6300  6300 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8109
06-30 10:35:38.296  4198  6781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
06-30 10:35:38.301  2140  2140 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
06-30 10:35:38.320  2140  2140 I GCM     : GCM config loaded
06-30 10:35:38.325  6758  6780 E HolidayIntentService: onHandleIntent:holiday data empty
,06-30 10:35:38.327  1033  1581 I ActivityManager: Killing 6141:com.android.settings/1000 (adj 15): empty #17
06-30 10:35:38.343  1033  1527 D WifiService: Client connection lost with reason: 4
,06-30 10:35:38.427  1033  1983 W libprocessgroup: failed to open /acct/uid_1000/pid_6141/cgroup.procs: No such file or directory
,06-30 10:35:38.462  6504  6504 V SetupWizard: Connected to Gservices successfully
,06-30 10:35:38.487  1802  1802 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 10:35:38.492  1802  6803 I ConfigFetchService: running network task: configservice_periodic
06-30 10:35:38.493  1802  6803 I ConfigFetchService: launchTask
06-30 10:35:38.504  2140  2140 I ConfigService: onCreate
,06-30 10:35:38.504  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 10:35:38.511  2140  2140 I ConfigService: onBind returning update interface
,06-30 10:35:38.516  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 10:35:38.516  2140  2140 I ConfigService: onBind returning config service
,06-30 10:35:38.525  2140  2140 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
06-30 10:35:38.537  6685  6685 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,06-30 10:35:38.541  6572  6572 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:35:38
06-30 10:35:38.543  6572  6572 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
06-30 10:35:38.543  6572  6572 D Weather.Utils: 2 : All the weather widget is gone.
06-30 10:35:38.544  6572  6572 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-30 10:35:38.546  6572  6572 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
06-30 10:35:38.546  6572  6572 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:35:38
06-30 10:35:38.551  2060  2060 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,06-30 10:35:38.555  6740  6740 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
06-30 10:35:38.555  6740  6740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
06-30 10:35:38.557  2060  2800 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
06-30 10:35:38.558  1563  1563 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
06-30 10:35:38.558  1563  1563 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
06-30 10:35:38.558  1563  1563 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
06-30 10:35:38.559  2060  2800 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
06-30 10:35:38.559  6740  6740 V [BNRBootReceiver]: Boot Receiver Return
06-30 10:35:38.563  2060  2800 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
06-30 10:35:38.564  2060  2060 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
06-30 10:35:38.565  2060  2800 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
,06-30 10:35:38.567  2060  2800 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
06-30 10:35:38.574  1802  4827 I art     : Explicit concurrent mark sweep GC freed 29991(2026KB) AllocSpace objects, 16(279KB) LOS objects, 51% free, 29MB/61MB, paused 1.725ms total 61.426ms
06-30 10:35:38.575  1802  1802 I ConfigClient: service connected
06-30 10:35:38.575  1802  1802 I ConfigFetchService: service connected
06-30 10:35:38.581  2140  6801 D GCM     : Connected
,06-30 10:35:38.607  2140  6801 D GCM     : Message class com.google.e.a.a.q
,06-30 10:35:39.518  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=15.6, 0.0, 0.0  rx=12.2 bcn=0 [on:0 tx:0 rx:0 period:3016] from screen [on:0 period:-1603075714] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 10:35:39.519  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=15.6, 0.0, 0.0  rx=12.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1603075713] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 10:35:39.519  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:35:39.523  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{10e60a1 type 2 when 111516 com.android.providers.calendar} when 111516
06-30 10:35:39.560  1033  1105 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6818 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,06-30 10:35:39.654  6818  6818 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,06-30 10:35:39.707  6818  6818 D CalendarProvider2: [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@31605a45
,06-30 10:35:39.723  6818  6818 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
,06-30 10:35:39.725  6818  6818 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@7688166(com.android.providers.calendar.CalendarProvider2@31605a45)
06-30 10:35:39.729  6818  6818 D CalendarProviderBroadcastReceiver: Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
06-30 10:35:39.729  6818  6818 D CalendarProviderBroadcastReceiver: [IntentService] WakeLock acquire, start IntentSerivce
06-30 10:35:39.736  6818  6818 D CalendarProvider2: CalendarProviderIntentService.onCreate()
,06-30 10:35:39.737  6818  6841 D CalendarProvider2: Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
06-30 10:35:39.738  6818  6841 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
06-30 10:35:39.743  6818  6841 E SQLiteLog: (284) automatic index on view_events(_id)
06-30 10:35:39.767  6818  6841 D CalendarProvider2: [IntentService] Release Lock
,06-30 10:35:39.769  6818  6818 D CalendarProvider2: CalendarProviderIntentService.onDestroy()
06-30 10:35:39.770  1033  1948 I ActivityManager: Killing 6266:com.lge.settings.easy/1000 (adj 15): empty #17
06-30 10:35:39.799  1033  1984 W libprocessgroup: failed to open /acct/uid_1000/pid_6266/cgroup.procs: No such file or directory
,06-30 10:35:40.570  2060  5216 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,06-30 10:35:40.578  2060  5216 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
06-30 10:35:40.579  2060  5216 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
06-30 10:35:40.582  2060  5216 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
06-30 10:35:40.582  2060  5216 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
06-30 10:35:41.329  1033  2030 I ActivityManager: Killing 6429:com.lge.appbox.client/u0a11 (adj 15): empty #17
,06-30 10:35:41.389  1033  1049 W libprocessgroup: failed to open /acct/uid_10011/pid_6429/cgroup.procs: No such file or directory
,06-30 10:35:41.412  6590  6611 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,06-30 10:35:42.083  1033  2056 I ActivityManager: Killing 6172:com.lge.formmanager/u0a26 (adj 15): empty #17
,06-30 10:35:42.117  1033  1049 W libprocessgroup: failed to open /acct/uid_10026/pid_6172/cgroup.procs: No such file or directory
,06-30 10:35:42.133  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{19a34b7f type 2 when 114163 com.google.android.gms} when 114163
,06-30 10:35:42.540  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=19.3, 0.0, 0.0  rx=16.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1603072692] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:35:42.543  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=19.3, 0.0, 0.0  rx=16.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1603072689] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:35:42.543  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:35:45.565  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=11.7, 0.0, 0.0  rx=8.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1603069667] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:35:45.594  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=11.7, 0.0, 0.0  rx=8.6 bcn=0 [on:0 tx:0 rx:0 period:29] from screen [on:0 period:-1603069638] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 10:35:45.594  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:35:47.124  1563  1563 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,06-30 10:35:47.157  1033  1446 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-30 10:35:47.197  2060  2060 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,06-30 10:35:47.221  1033  1105 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6849 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-30 10:35:47.240  1563  1563 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,06-30 10:35:47.244  1563  1563 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,06-30 10:35:47.315  2060  2060 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,06-30 10:35:47.329  1033  1033 D administrator: Handling package changes for user 0
,06-30 10:35:47.332  6849  6849 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 10:35:47.407  6849  6849 D LgDataFeature: LgDataFeature() Constructor: none
06-30 10:35:47.407  6849  6849 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 10:35:47.411  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
06-30 10:35:47.411  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,06-30 10:35:47.426  1033  1103 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:35:47.431  1033  1103 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
06-30 10:35:47.437  2060  2060 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
06-30 10:35:47.437  2459  2459 V GmsNetworkLocationProvi: DISABLE
06-30 10:35:47.468  2459  2459 E GCoreFlp: Bound FusedProviderService with LocationManager
,06-30 10:35:47.512  2140  2331 I art     : Explicit concurrent mark sweep GC freed 8846(534KB) AllocSpace objects, 8(128KB) LOS objects, 52% free, 29MB/61MB, paused 1.047ms total 36.006ms
,06-30 10:35:47.533  1033  1984 I art     : Explicit concurrent mark sweep GC freed 22773(1138KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.441ms total 63.698ms
,06-30 10:35:47.546  1033  1103 D LocationProviderProxy: applying state to connected service
06-30 10:35:47.546  6849  6894 I Babel   : MmsConfig: mnc/mcc: 0/0
06-30 10:35:47.546  6849  6894 I Babel   : MmsConfig.loadMmsSettings
,06-30 10:35:47.551  6849  6894 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
06-30 10:35:47.551  6849  6894 I Babel   : MmsConfig.loadFromDatabase
,06-30 10:35:47.560  6849  6894 E Babel   : canonicalizeMccMnc: invalid mccmnc 
06-30 10:35:47.560  6849  6894 I Babel   : MmsConfig.loadFromResources
06-30 10:35:47.562  6849  6894 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
06-30 10:35:47.563  6849  6894 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
06-30 10:35:47.569  6849  6892 W AudioCapabilities: Unsupported mime audio/evrc
,06-30 10:35:47.570  6849  6892 W AudioCapabilities: Unsupported mime audio/qcelp
06-30 10:35:47.570  6849  6849 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:47.576  6849  6892 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-30 10:35:47.585  6849  6892 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
06-30 10:35:47.586  6849  6892 W AudioCapabilities: Unsupported mime audio/qcelp
06-30 10:35:47.591  6849  6892 W AudioCapabilities: Unsupported mime audio/evrc
06-30 10:35:47.592  1802  6898 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
06-30 10:35:47.593  1802  6898 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
06-30 10:35:47.599  6849  6892 W VideoCapabilities: Unsupported mime video/x-ms-wmv
06-30 10:35:47.600  6849  6892 W VideoCapabilities: Unsupported mime video/divx
,06-30 10:35:47.601  6849  6892 W VideoCapabilities: Unsupported mime video/divx311
06-30 10:35:47.602  6849  6892 W VideoCapabilities: Unsupported mime video/divx4
06-30 10:35:47.607  6849  6892 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,06-30 10:35:47.619  6849  6892 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
06-30 10:35:47.621  6849  6892 W AudioCapabilities: Unsupported mime audio/eac3
06-30 10:35:47.621  6849  6892 W AudioCapabilities: Unsupported mime audio/ac3
06-30 10:35:47.622  6849  6892 W AudioCapabilities: Unsupported mime audio/g726
06-30 10:35:47.622  6849  6892 W AudioCapabilities: Unsupported mime audio/wma-voice
,06-30 10:35:47.623  6849  6892 W AudioCapabilities: Unsupported mime audio/x-ms-wma
06-30 10:35:47.624  6849  6892 W AudioCapabilities: Unsupported mime audio/adpcm
06-30 10:35:47.625  6849  6892 W VideoCapabilities: Unsupported mime video/theora
06-30 10:35:47.627  6849  6892 W VideoCapabilities: Unsupported mime video/mjpg
06-30 10:35:47.628  1033  1048 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6901 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
06-30 10:35:47.637  1802  4469 I Icing   : updateResources: need to parse e{com.google.android.gms}
,06-30 10:35:47.658  1033  2056 I ActivityManager: Killing 6525:com.android.chrome/u0a57 (adj 15): empty #17
06-30 10:35:47.677  6901  6901 I AppUp4:AppBoxCP: onCreate
06-30 10:35:47.677  6901  6901 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,06-30 10:35:47.682  6901  6901 I AppUp4:DB:  setFingerPrint start
06-30 10:35:47.682  6901  6901 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
06-30 10:35:47.687  6901  6901 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
06-30 10:35:47.687  6901  6901 I AppUp4:DB:  SDK version = 21
06-30 10:35:47.687  6901  6901 I AppUp4:DB:  beforefinger == newfinger no write in DB
06-30 10:35:47.820  1033  1582 W libprocessgroup: failed to open /acct/uid_10057/pid_6525/cgroup.procs: No such file or directory
,06-30 10:35:47.828  6901  6901 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,06-30 10:35:47.844  6901  6901 I AppUp4:CustModeStarterReceiver: onReceive
,06-30 10:35:47.904  6901  6901 D LgDataFeature: LgDataFeature() Constructor: none
,06-30 10:35:47.904  6901  6901 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 10:35:47.915  6901  6901 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@261fa6a8
06-30 10:35:47.916  6901  6901 D AppUp4:CustFacade: isCustomizationCompleted : false
06-30 10:35:47.916  6901  6901 D AppUp4:CustFacade: isPhone : true
06-30 10:35:47.917  6901  6901 D AppUp4:CustModeStarterReceiver: begin check event
,06-30 10:35:47.918  6901  6901 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
06-30 10:35:48.000  1033  1948 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6924 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,06-30 10:35:48.004  1033  1948 I ActivityManager: Killing 6553:com.lge.drmservice/u0a62 (adj 15): empty #17
06-30 10:35:48.009   343   343 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 9.685ms
06-30 10:35:48.019   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 9.154ms
,06-30 10:35:48.029   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 9.204ms
,06-30 10:35:48.041  1033  1559 W libprocessgroup: failed to open /acct/uid_10062/pid_6553/cgroup.procs: No such file or directory
,06-30 10:35:48.057  6924  6924 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:35:48.058  6924  6924 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:35:48.058  6924  6924 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,06-30 10:35:48.059  6924  6924 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
06-30 10:35:48.060  6924  6924 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,06-30 10:35:48.148  6924  6924 I SystemConfig: BUILD Country: EU
06-30 10:35:48.148  6924  6924 I SystemConfig: BUILD Operator: OPEN
,06-30 10:35:48.210  1033  1559 I ActivityManager: Killing 6590:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,06-30 10:35:48.429  1033  2056 W libprocessgroup: failed to open /acct/uid_10093/pid_6590/cgroup.procs: No such file or directory
,06-30 10:35:48.508  1033  1048 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6949 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,06-30 10:35:48.574  6924  6941 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
06-30 10:35:48.574  6924  6941 I SystemConfig: existFile = false
,06-30 10:35:48.583  6924  6941 I SystemConfig: canReadFile = false
06-30 10:35:48.584  6924  6941 I SystemConfig: systemFeature RCS result false
06-30 10:35:48.584  6924  6941 D SystemConfig: refreshRcsSupport() :false
06-30 10:35:48.608  6949  6949 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:35:48.609  6949  6949 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 10:35:48.610  6949  6949 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,06-30 10:35:48.611  6949  6949 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
06-30 10:35:48.613  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1603066619] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 10:35:48.614  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1603066618] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 10:35:48.614  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:35:48.637  1033  2056 V SIM_STK : Menu title from STK is T-Mobile
,06-30 10:35:48.648  1802  6804 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
06-30 10:35:48.650   314  6982 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:35:48.650   314  6982 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
06-30 10:35:48.650   314  6982 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-30 10:35:48.706  6949  6949 I AppConfig: Total System Memory = 2995761152
,06-30 10:35:48.714  6949  6949 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
06-30 10:35:48.804  1033  1983 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6985 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 10:35:48.804  1033  1983 I ActivityManager: Killing 6656:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,06-30 10:35:48.858  1033  2077 W libprocessgroup: failed to open /acct/uid_10097/pid_6656/cgroup.procs: No such file or directory
,06-30 10:35:48.894  1802  6804 W ConfigFetchTask: bad response from server: 401 Unauthorized
,06-30 10:35:48.897  1802  1802 I ConfigFetchService: fetch service done; releasing wakelock
06-30 10:35:48.899  1802  1802 I ConfigFetchService: stopping self
06-30 10:35:48.950  2140  2140 I ConfigService: onDestroy
,06-30 10:35:49.016  6985  6985 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,06-30 10:35:49.066  1563  1563 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:35:49.067  1563  1563 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 10:35:49.077  1033  1527 D WifiController: battery changed pluggedType: 2
06-30 10:35:49.079  1563  1563 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
06-30 10:35:49.080  1563  1563 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:35:49.084  1949  2118 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:35:49.084  1949  2118 D LEDHandler: Battery Level Remaining: 100%
,06-30 10:35:49.084  1949  2118 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
06-30 10:35:49.089  1563  1563 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:35:49.090  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:49.090  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:49.090  6120  6192 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:35:49.091  6740  6740 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 10:35:49.133  6985  6985 D LgDataFeature: LgDataFeature() Constructor: none
06-30 10:35:49.133  6985  6985 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 10:35:49.198  6985  6985 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,06-30 10:35:49.221  6985  6985 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,06-30 10:35:49.222  6985  6985 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,06-30 10:35:49.240  6985  6985 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,06-30 10:35:49.240  6985  6985 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,06-30 10:35:49.281  3447  5368 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,06-30 10:35:49.283  1033  2077 I ActivityManager: Killing 6460:com.lge.email/u0a23 (adj 15): empty #17
06-30 10:35:49.285  3447  5368 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@ff68f4c on behalf of 6985
06-30 10:35:49.314  1033  1911 W libprocessgroup: failed to open /acct/uid_10023/pid_6460/cgroup.procs: No such file or directory
,06-30 10:35:49.323  4289  7027 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
06-30 10:35:49.326  6985  6985 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,06-30 10:35:49.365  1033  1744 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7029 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
06-30 10:35:49.401  6985  6985 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,06-30 10:35:49.443  7029  7029 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,06-30 10:35:49.466  7029  7029 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,06-30 10:35:49.466  7029  7029 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
06-30 10:35:49.466  7029  7029 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
06-30 10:35:49.466  7029  7029 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
06-30 10:35:49.466  7029  7029 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
06-30 10:35:49.466  7029  7029 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,06-30 10:35:49.525  1033  1744 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7048 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:49.526  1033  1744 I ActivityManager: Killing 5056:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,06-30 10:35:49.601  1033  1911 W libprocessgroup: failed to open /acct/uid_1000/pid_5056/cgroup.procs: No such file or directory
,06-30 10:35:49.628  7048  7048 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:35:49.809  1033  2056 V SIM_STK : Menu title from STK is T-Mobile
,06-30 10:35:49.835  4289  7027 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 511 ms] updated apps [took 511 ms] 
,06-30 10:35:51.630  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1603063602] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:35:51.633  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1603063599] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:35:51.633  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:35:54.650  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1603060582] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 10:35:54.651  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1603060581] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 10:35:54.651  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:35:54.878  1033  1559 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,06-30 10:35:54.880  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.880  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.880  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
06-30 10:35:54.881  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.881  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,06-30 10:35:54.937  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 30 Jun 2016 08:35:54 GMT], X-Android-Received-Millis=[1467275754936], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467275754901]}
06-30 10:35:54.937  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-30 10:35:54.937  1033  6256 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,06-30 10:35:54.940  1033  1528 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
06-30 10:35:54.940  1033  1528 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
,06-30 10:35:54.940  1033  1528 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:35:54.941  1033  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:54.941  1033  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-30 10:35:54.941  1033  1528 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
06-30 10:35:54.941  1033  1528 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-30 10:35:54.941  1033  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:54.941  1033  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:54.942  1033  1528 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:54.943  1563  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 10:35:54.954  1033  1048 I ActivityManager: Killing 6719:com.qualcomm.timeservice/1000 (adj 15): empty #17
,06-30 10:35:55.017  1033  2077 W libprocessgroup: failed to open /acct/uid_1000/pid_6719/cgroup.procs: No such file or directory
,06-30 10:35:57.669  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1603057563] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:35:57.672  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1603057560] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:35:57.672  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:00.659  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:36:00.659  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 10:36:00.659  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-30 10:36:00.660  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:36:00.675  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:36:00.675  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:36:00.678  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:36:00.684  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:36:00.693  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1603054539] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:00.694  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1603054538] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:00.694  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:02.357  1033  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=77432620, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,06-30 10:36:02.396  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1d86ba1e type 2 when 134384 com.google.android.gms} when 134384
,06-30 10:36:02.408   314  7086 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-30 10:36:02.410   314  7086 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
06-30 10:36:02.411   314  7086 D libc-netbsd: res_queryN name = mtalk.google.com succeed
06-30 10:36:02.433  2574  2574 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 10:36:02.471  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=77432620 [*alarm*], flags=0x0
,06-30 10:36:02.726  2140  7087 D GCM     : Connected
,06-30 10:36:02.760  2140  7087 D GCM     : Message class com.google.e.a.a.q
,06-30 10:36:03.711  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1603051521] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:03.714  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1603051518] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:03.714  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:06.738  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1603048494] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:36:06.741  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1603048491] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:36:06.741  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:09.769  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1603045463] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:09.778  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1603045454] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:09.778  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:10.463  1033  1521 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,06-30 10:36:10.465  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,06-30 10:36:10.477  1033  1521 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
06-30 10:36:10.478  1033  1521 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
06-30 10:36:10.479  1033  1521 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
06-30 10:36:10.481  1033  1521 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
06-30 10:36:12.798  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1603042434] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:36:12.799  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1603042433] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:36:12.799  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:15.817  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1603039415] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:15.820  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1603039412] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:15.820  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:18.845  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1603036387] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:18.849  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1603036383] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:18.850  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:21.876  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1603033357] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:21.879  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1603033353] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:21.880  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:24.904  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1603030328] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:24.914  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1603030319] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:24.915  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:27.933  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1603027300] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:27.945  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1603027287] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:27.945  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:30.965  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1603024268] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:30.978  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1603024254] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:30.978  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:32.778  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{304692ff type 2 when 164801 com.google.android.gms} when 164801
,06-30 10:36:32.851  1802  1802 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 10:36:32.858  2140  2140 I ConfigService: onCreate
06-30 10:36:32.858  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 10:36:32.862  1802  7105 I ConfigFetchService: running network task: configservice_periodic
06-30 10:36:32.864  1802  7105 I ConfigFetchService: launchTask
,06-30 10:36:32.873  2140  2140 I ConfigService: onBind returning update interface
,06-30 10:36:32.874  1802  1802 I ConfigFetchService: service connected
06-30 10:36:32.875  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 10:36:32.875  2140  2140 I ConfigService: onBind returning config service
06-30 10:36:32.876  1802  1802 I ConfigClient: service connected
06-30 10:36:32.959  1033  1947 V SIM_STK : Menu title from STK is T-Mobile
,06-30 10:36:32.975  1802  2352 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,06-30 10:36:32.980   314  7117 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-30 10:36:32.981   314  7117 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
06-30 10:36:32.981   314  7117 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-30 10:36:33.180  1802  2352 W ConfigFetchTask: bad response from server: 401 Unauthorized
06-30 10:36:33.183  1802  1802 I ConfigFetchService: fetch service done; releasing wakelock
,06-30 10:36:33.187  1802  1802 I ConfigFetchService: stopping self
,06-30 10:36:33.228  2140  2140 I ConfigService: onDestroy
,06-30 10:36:33.999  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1603021233] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:34.002  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1603021230] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:34.002  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:37.027  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1603018206] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:36:37.030  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1603018203] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:36:37.030  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:40.055  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1603015177] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:40.065  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1603015167] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:40.066  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:36:43.085  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1603012147] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:43.092  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:7] from screen [on:0 period:-1603012140] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:43.092  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:36:46.109  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1603009123] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:46.112  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1603009120] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:36:46.112  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:49.135  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1603006097] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:49.145  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1603006087] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:49.145  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:36:52.165  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1603003067] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:52.177  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1603003055] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:52.177  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:55.199  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1603000033] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:36:55.202  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1603000030] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:36:55.202  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:36:58.225  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602997007] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:36:58.263  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:38] from screen [on:0 period:-1602996969] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:36:58.263  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:00.059  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:37:00.059  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:37:00.059  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-30 10:37:00.060  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:37:00.074  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:37:00.075  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:37:00.078  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:37:00.081  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:37:01.282  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602993951] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:01.285  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602993948] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:37:01.285  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:04.305  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602990928] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:04.315  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602990917] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:04.315  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:07.338  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602987895] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:37:07.341  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602987892] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:07.341  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:10.365  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602984867] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:10.375  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1602984858] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:10.375  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:37:13.395  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602981837] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:13.407  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602981825] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:13.408  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:16.430  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602978803] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:37:16.433  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602978800] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:16.433  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:19.460  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602975773] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:19.463  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602975770] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:19.463  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:22.487  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602972745] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:22.490  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602972742] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:22.491  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:25.519  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602969713] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:25.522  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602969710] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:37:25.522  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:28.544  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602966688] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:28.555  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602966678] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:28.555  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:37:31.575  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602963657] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:31.587  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602963646] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:31.587  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:34.607  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602960626] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:34.610  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602960623] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:34.610  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:37.164  1033  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=77432620, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,06-30 10:37:37.174  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{663e6ce type 2 when 203897 android} when 203897
06-30 10:37:37.177  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3a3039ef type 2 when 225229 com.google.android.gms} when 225229
06-30 10:37:37.229  2574  2574 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 10:37:37.281  1802  1802 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 10:37:37.290  2140  2140 I ConfigService: onCreate
06-30 10:37:37.290  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 10:37:37.294  1802  7125 I ConfigFetchService: running network task: configservice_periodic
,06-30 10:37:37.308  1802  7125 I ConfigFetchService: launchTask
,06-30 10:37:37.315  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=77432620 [*alarm*], flags=0x0
06-30 10:37:37.319  2140  2140 I ConfigService: onBind returning update interface
06-30 10:37:37.321  1802  1802 I ConfigFetchService: service connected
,06-30 10:37:37.323  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 10:37:37.323  2140  2140 I ConfigService: onBind returning config service
06-30 10:37:37.324  1802  1802 I ConfigClient: service connected
06-30 10:37:37.394  1033  2077 V SIM_STK : Menu title from STK is T-Mobile
,06-30 10:37:37.404  1802  2379 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
06-30 10:37:37.407   314  7142 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:37:37.408   314  7142 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,06-30 10:37:37.453   314  7142 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-30 10:37:37.640  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602957592] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:37.645  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1602957587] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:37.645  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:37:37.733  1802  2379 W ConfigFetchTask: bad response from server: 401 Unauthorized
06-30 10:37:37.738  1802  1802 I ConfigFetchService: fetch service done; releasing wakelock
,06-30 10:37:37.742  1802  1802 I ConfigFetchService: stopping self
06-30 10:37:37.777  2140  2140 I ConfigService: onDestroy
,06-30 10:37:40.653  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602954579] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:37:40.654  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1602954578] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 10:37:40.654  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:43.675  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602951557] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:37:43.686  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602951546] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:37:43.689  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:46.709  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602948523] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:37:46.712  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602948520] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:46.712  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:49.732  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602945500] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:49.741  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602945497] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:49.741  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:37:52.763  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602942469] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:52.775  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602942458] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:52.775  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:37:55.797  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602939435] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:55.800  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602939432] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:37:55.800  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:37:56.476  1563  1563 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:37:56.476  1563  1563 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 10:37:56.488  1949  2118 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:37:56.488  1949  2118 D LEDHandler: Battery Level Remaining: 100%
06-30 10:37:56.488  1949  2118 D LEDHandler: Battery Temp: 283, mChargingStatus=5, mChargingStop=false
,06-30 10:37:56.490  1563  1563 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
06-30 10:37:56.490  1563  1563 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:37:56.492  1033  1527 D WifiController: battery changed pluggedType: 2
06-30 10:37:56.494  1563  1563 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:37:56.499  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:37:56.499  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:37:56.502  6120  6192 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-30 10:37:56.506  6740  6740 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 10:37:58.823  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602936409] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:58.835  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602936398] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:37:58.835  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:38:00.055  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:38:00.056  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:38:00.056  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-30 10:38:00.057  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:38:00.073  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:38:00.073  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:38:00.075  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:38:00.081  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:38:01.855  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602933377] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:01.866  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602933366] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:01.867  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:04.889  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602930343] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:38:04.892  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602930340] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:38:04.892  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL],
,06-30 10:38:07.915  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602927317] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:07.925  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602927307] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:07.925  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:10.947  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602924287] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:38:10.950  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1602924282] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:10.950  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:13.975  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602921258] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:13.985  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602921247] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:13.985  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:17.007  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602918225] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:38:17.010  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602918222] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:17.010  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:20.032  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602915200] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:20.035  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602915197] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:38:20.035  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:23.060  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602912172] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:23.063  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602912169] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:23.063  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:26.088  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602909144] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:26.091  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602909141] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:26.091  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:29.117  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602906115] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:29.120  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602906112] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:29.120  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:32.145  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602903087] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:32.156  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602903077] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:32.156  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:38:35.175  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602900057] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:35.189  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1602900044] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:35.189  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:38.210  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602897022] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:38:38.213  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602897019] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:38.213  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:41.233  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602893999] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:41.248  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1602893984] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:41.249  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:44.267  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602890965] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:38:44.270  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602890962] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:38:44.271  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:47.295  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602887937] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:47.299  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602887933] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:47.299  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:50.321  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602884911] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:50.324  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602884908] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:38:50.324  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:53.349  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602881883] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:53.352  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602881880] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:53.353  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:38:56.373  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602878860] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:56.382  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602878857] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:56.383  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:38:59.401  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602875832] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:38:59.404  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602875829] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:38:59.404  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:00.059  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:39:00.059  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 10:39:00.060  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:39:00.060  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:39:00.074  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:39:00.074  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:39:00.077  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:39:00.083  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:39:02.430  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602872802] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:02.433  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602872799] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:02.433  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:05.453  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602869780] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:05.461  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602869777] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:05.461  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:08.482  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602866751] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:39:08.485  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602866748] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:08.485  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:11.509  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602863723] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:11.512  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602863720] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:39:11.512  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:14.536  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602860697] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:14.539  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602860693] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:14.540  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:17.565  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602857667] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:17.576  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602857657] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:17.576  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:39:20.598  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602854634] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:20.601  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602854631] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:39:20.601  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:22.924  1033  3482 I LocationManagerService: remove 14c150cf
,06-30 10:39:22.932  1033  3482 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
06-30 10:39:22.932  1033  3482 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 10:39:22.934  1033  3482 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-30 10:39:22.937  1033  3482 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
06-30 10:39:22.938  1033  3482 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,06-30 10:39:23.626  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602851606] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:23.630  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602851603] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:23.630  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:26.655  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602848577] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:26.665  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602848567] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:26.665  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:39:29.683  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602845549] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:29.696  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602845537] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:29.696  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:39:32.018  1033  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=77432620, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,06-30 10:39:32.070  2574  2574 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 10:39:32.102  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=77432620 [*alarm*], flags=0x0
,06-30 10:39:32.388  1033  2056 I art     : Explicit concurrent mark sweep GC freed 79538(3MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.877ms total 96.700ms
,06-30 10:39:32.719  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602842513] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:39:32.720  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1602842512] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:39:32.720  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:35.740  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1602839492] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:35.743  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602839489] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:35.743  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:37.758  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{6fd9f7e type 2 when 349781 com.google.android.gms} when 349781
,06-30 10:39:37.815  1802  1802 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 10:39:37.821  2140  2140 I ConfigService: onCreate
06-30 10:39:37.822  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 10:39:37.824  1802  7169 I ConfigFetchService: running network task: configservice_periodic
06-30 10:39:37.827  1802  7169 I ConfigFetchService: launchTask
06-30 10:39:37.833  2140  2140 I ConfigService: onBind returning update interface
,06-30 10:39:37.837  1802  1802 I ConfigFetchService: service connected
06-30 10:39:37.837  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 10:39:37.837  2140  2140 I ConfigService: onBind returning config service
06-30 10:39:37.838  1802  1802 I ConfigClient: service connected
06-30 10:39:37.927  1033  2056 V SIM_STK : Menu title from STK is T-Mobile
,06-30 10:39:37.943  1802  3790 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
06-30 10:39:37.948   314  7177 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:39:37.948   314  7177 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,06-30 10:39:37.992   314  7177 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-30 10:39:38.311  1802  3790 W ConfigFetchTask: bad response from server: 401 Unauthorized
,06-30 10:39:38.321  1802  1802 I ConfigFetchService: fetch service done; releasing wakelock
06-30 10:39:38.324  1802  1802 I ConfigFetchService: stopping self
06-30 10:39:38.358  2140  2140 I ConfigService: onDestroy
,06-30 10:39:38.764  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602836468] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:38.775  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602836457] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:38.775  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:41.798  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=8.5, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602833434] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 10:39:41.801  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=8.5, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602833431] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:39:41.801  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:44.828  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602830405] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:44.831  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602830401] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:44.831  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:47.857  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602827376] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:47.860  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602827372] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:47.860  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:50.888  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602824344] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:50.891  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602824341] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:39:50.891  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:53.917  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602821316] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:53.919  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602821313] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:53.920  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:56.947  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602818286] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:56.950  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602818283] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:56.950  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:39:59.972  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602815260] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:59.975  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602815257] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:39:59.975  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:00.058  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:40:00.058  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:40:00.058  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:40:00.059  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:40:00.072  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:40:00.072  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:40:00.074  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:40:00.078  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:40:03.006  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602812226] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:03.009  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602812223] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:03.009  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:06.031  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602809201] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:06.034  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602809198] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:06.034  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:09.058  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602806174] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,06-30 10:40:09.061  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602806171] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:40:09.062  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:12.089  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602803143] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:12.092  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602803140] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:12.092  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:15.113  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602800119] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:15.124  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602800108] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:15.124  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:40:18.142  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602797090] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:18.145  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602797087] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:40:18.145  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:21.172  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602794060] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:21.175  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602794057] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:40:21.175  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:24.201  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602791031] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:24.204  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1602791029] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:24.204  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:27.229  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602788003] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:27.232  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602788000] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:27.232  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:30.252  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602784981] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:30.255  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602784978] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:40:30.255  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:33.281  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602781951] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:33.285  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602781948] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:33.285  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:36.309  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602778924] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:36.312  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602778921] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:36.312  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:39.338  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602775895] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:39.341  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602775892] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:40:39.341  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:42.362  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602772870] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:42.365  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602772867] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:40:42.365  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:45.392  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602769840] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:45.395  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602769837] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:40:45.395  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:48.421  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602766812] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:48.424  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602766809] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:48.424  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:51.449  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602763783] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:51.452  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602763780] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:40:51.452  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:54.478  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602760754] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,06-30 10:40:54.481  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602760751] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:40:54.482  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:40:57.509  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602757723] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:57.512  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602757720] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:40:57.512  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:00.054  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:41:00.054  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:41:00.054  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:41:00.055  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:41:00.069  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:41:00.069  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:41:00.071  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:41:00.073  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:41:00.535  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602754697] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:00.549  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1602754683] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:41:00.549  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:41:03.569  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602751663] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:41:03.572  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602751660] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:41:03.572  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:06.592  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602748640] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:06.595  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602748637] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:06.603  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:09.620  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602745612] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:09.623  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602745609] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:41:09.624  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:12.648  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602742584] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:12.651  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602742581] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:12.651  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:15.677  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602739555] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:15.680  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602739552] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:15.681  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:18.708  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602736524] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:18.711  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602736521] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:18.711  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:21.737  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602733496] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:21.740  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602733492] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:21.740  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:24.767  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602730465] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:24.770  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602730462] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:24.770  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:27.795  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602727437] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:27.807  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602727426] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:27.807  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:41:30.826  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602724406] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:30.829  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602724403] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:41:30.830  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:33.852  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602721380] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:33.862  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602721377] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:33.862  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:41:36.882  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602718350] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:36.885  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602718347] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:36.895  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:39.915  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602715318] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:39.926  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602715306] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,06-30 10:41:39.926  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:41:42.948  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602712284] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:42.951  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602712281] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:41:42.952  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:45.975  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602709257] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:45.984  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1602709248] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:45.984  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:49.007  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602706225] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:41:49.010  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602706222] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:49.010  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:52.033  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602703200] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:52.041  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602703197] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:52.042  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:41:55.062  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602700170] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:55.065  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602700167] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:41:55.065  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:41:58.095  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602697138] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:58.105  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602697127] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:41:58.105  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:42:00.053  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:42:00.053  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:42:00.054  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:42:00.054  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:42:00.070  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:42:00.070  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:42:00.072  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:42:00.074  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:42:01.124  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602694108] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:01.138  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1602694094] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:01.139  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:04.159  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602691073] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:42:04.162  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602691070] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:04.162  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:07.187  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602688045] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:42:07.188  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1602688044] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:42:07.189  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:10.209  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602685023] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:10.212  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602685020] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:10.213  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:13.235  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602681997] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:13.245  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602681987] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:13.245  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:42:16.266  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602678967] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:16.269  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602678964] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:42:16.269  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:19.294  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602675938] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:19.304  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602675928] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:19.305  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:42:22.323  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602672909] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:22.332  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1602672900] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:22.332  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:42:25.351  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602669881] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:25.354  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602669878] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:42:25.354  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:28.382  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602666850] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:28.385  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602666847] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:28.385  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:31.408  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602663824] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:31.411  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602663821] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:42:31.411  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:34.438  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602660794] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:34.441  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602660791] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:34.441  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:37.468  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602657765] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:37.470  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602657762] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:37.471  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:40.496  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602654736] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:40.499  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602654733] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:40.499  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:43.523  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602651709] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:43.533  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602651699] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:43.533  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:42:46.553  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602648679] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:46.564  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602648668] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:46.565  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:49.587  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602645645] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:42:49.590  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602645642] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:49.590  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:52.612  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602642620] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:52.615  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602642617] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:42:52.615  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:42:55.644  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602639588] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:55.654  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602639578] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:42:55.655  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:42:58.675  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602636557] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:58.690  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1602636542] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:42:58.690  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:00.054  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:43:00.054  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:43:00.055  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:43:00.055  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:43:00.070  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:43:00.070  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:43:00.072  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:43:00.074  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:43:01.710  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602633522] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,06-30 10:43:01.713  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602633519] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:43:01.714  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:04.735  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602630497] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:04.745  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602630487] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,06-30 10:43:04.746  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:07.769  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602627464] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:07.772  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602627461] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
06-30 10:43:07.772  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL],
,06-30 10:43:10.795  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602624438] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:10.802  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1602624430] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:10.802  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:13.821  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602621411] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:13.824  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602621408] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:13.824  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL],
,06-30 10:43:16.848  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602618385] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:16.851  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602618382] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:16.851  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:19.877  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602615355] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:19.880  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602615352] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:19.880  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:22.906  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602612327] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:22.909  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602612323] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:22.909  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:25.933  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602609299] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:25.942  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1602609290] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:25.942  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:43:28.963  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602606269] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:28.975  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602606257] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:28.975  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:43:31.998  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602603234] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:32.001  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602603231] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:43:32.001  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:35.027  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602600205] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:35.030  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602600202] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:35.030  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:38.054  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602597178] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:38.065  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602597167] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:38.067  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:43:38.337  1033  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=77432620, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,06-30 10:43:38.361  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1a8be6a9 type 2 when 590364 com.google.android.gms} when 590364
,06-30 10:43:38.412  2574  2574 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 10:43:38.441  1802  1802 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 10:43:38.447  2140  2140 I ConfigService: onCreate
06-30 10:43:38.448  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 10:43:38.456  1802  7184 I ConfigFetchService: running network task: configservice_periodic
,06-30 10:43:38.467  1802  7184 I ConfigFetchService: launchTask
06-30 10:43:38.469  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=77432620 [*alarm*], flags=0x0
,06-30 10:43:38.477  2140  2140 I ConfigService: onBind returning update interface
06-30 10:43:38.478  1802  1802 I ConfigFetchService: service connected
06-30 10:43:38.479  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 10:43:38.479  2140  2140 I ConfigService: onBind returning config service
06-30 10:43:38.480  1802  1802 I ConfigClient: service connected
06-30 10:43:38.559  1033  1984 V SIM_STK : Menu title from STK is T-Mobile
,06-30 10:43:38.570  1802  5551 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,06-30 10:43:38.574   314  7202 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:43:38.574   314  7202 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,06-30 10:43:38.609   314  7202 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-30 10:43:38.904  1802  5551 W ConfigFetchTask: bad response from server: 401 Unauthorized
,06-30 10:43:38.911  1802  1802 I ConfigFetchService: fetch service done; releasing wakelock
06-30 10:43:38.914  1802  1802 I ConfigFetchService: stopping self
06-30 10:43:38.943  2140  2140 I ConfigService: onDestroy
,06-30 10:43:41.086  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602594146] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:41.089  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602594143] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:43:41.089  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:44.113  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=8.5, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602591119] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:43:44.123  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=8.5, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602591109] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:43:44.123  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:43:47.143  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602588089] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:47.155  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602588077] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:47.155  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:50.178  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602585055] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:43:50.181  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602585051] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:50.181  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:53.204  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602582028] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:53.215  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602582017] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:53.215  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:56.237  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602578995] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:56.240  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602578992] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:56.240  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:43:59.264  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602575968] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:59.274  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602575958] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:43:59.275  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:44:00.071  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:44:00.071  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:44:00.071  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:44:00.072  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:44:00.085  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:44:00.085  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:44:00.087  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:44:00.089  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:44:02.295  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602572937] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:02.309  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1602572923] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:02.309  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:05.331  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602569901] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:05.347  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:16] from screen [on:0 period:-1602569885] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:05.347  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:08.368  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602566864] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:44:08.371  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602566861] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:44:08.371  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:11.395  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602563837] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:11.404  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1602563828] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:11.405  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:44:14.424  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602560809] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:14.436  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602560797] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:14.436  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:44:17.458  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602557774] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:17.461  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602557771] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:44:17.461  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:20.301  1033  1911 I ActivityManager: Killing 6758:com.android.calendar/u0a13 (adj 15): empty #17
,06-30 10:44:20.337  1033  1947 W libprocessgroup: failed to open /acct/uid_10013/pid_6758/cgroup.procs: No such file or directory
,06-30 10:44:20.486  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602554746] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:20.489  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602554743] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:44:20.489  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:23.519  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602551713] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:23.522  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602551710] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:23.523  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:26.548  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602548684] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:26.551  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602548681] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:26.551  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:29.575  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602545658] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:29.585  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602545647] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:29.586  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:32.608  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602542625] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:44:32.611  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602542622] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:44:32.611  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:35.637  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602539596] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:35.640  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602539592] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:35.640  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:38.664  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602536568] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:38.675  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602536558] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:38.675  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:44:41.695  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602533537] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:41.707  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602533526] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:41.707  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:44.728  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602530504] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:44:44.731  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602530501] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:44.731  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:47.755  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602527478] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:47.758  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602527475] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:47.758  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:50.783  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602524449] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:50.793  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602524439] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:50.794  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:44:53.814  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602521418] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:53.826  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602521406] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:53.826  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:55.171  1033  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=77432620, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,06-30 10:44:55.191  1033  1381 V AlarmManager: RTC_WAKEUP set : Alarm{19fa1f60 type 0 when 1467276136549 com.google.android.gms} when 1467276136549
,06-30 10:44:55.222  1802  6804 I EventLogService: Aggregate from 1467275734625 (log), 1467274336503 (data)
,06-30 10:44:55.237  2574  2574 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 10:44:55.263  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=77432620 [*alarm*], flags=0x0
,06-30 10:44:56.847  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602518386] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:56.850  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602518383] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:56.850  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:44:59.875  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602515358] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:59.885  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602515347] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:44:59.886  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:45:00.051  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:45:00.052  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:45:00.052  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:45:00.052  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:45:00.065  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:45:00.066  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:45:00.068  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:45:00.070  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:45:01.224  1033  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=77432620, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,06-30 10:45:01.253  6685  6685 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,06-30 10:45:01.261  6685  6685 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2a1c8554
06-30 10:45:01.279  2574  2574 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 10:45:01.311  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=77432620 [*alarm*], flags=0x0
,06-30 10:45:02.907  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602512325] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:02.910  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602512322] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:45:02.910  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:45:05.937  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602509296] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:05.940  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602509292] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:05.940  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:45:08.965  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602506268] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:08.975  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602506257] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:08.976  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:45:12.004  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3009] from screen [on:0 period:-1602503228] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:12.017  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1602503215] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:12.017  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:45:15.032  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602500200] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:15.035  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602500197] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:15.044  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:45:18.064  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602497168] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:18.076  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602497156] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:18.076  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:45:21.097  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602494135] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:21.100  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602494132] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:45:21.100  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:45:24.125  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602491107] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:24.135  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602491097] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:24.136  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:45:27.158  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602488075] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:45:27.161  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602488072] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:45:27.161  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:45:30.188  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602485044] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:30.191  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602485041] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:30.191  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:45:33.214  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602482019] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:33.223  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602482009] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:33.223  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:45:36.244  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602478989] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:36.257  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1602478975] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:36.258  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:45:39.278  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602475954] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:45:39.281  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602475951] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:39.282  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:45:42.305  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602472928] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:42.315  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602472917] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:42.316  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:45:45.336  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602469896] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:45.339  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602469893] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:45:45.339  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:45:48.364  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602466868] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:48.373  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1602466859] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:48.373  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:45:51.394  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602463839] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:51.405  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602463827] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
06-30 10:45:51.405  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:45:54.425  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602460807] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:54.438  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1602460794] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:45:54.438  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:45:57.456  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602457777] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:45:57.460  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602457773] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:45:57.460  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:00.052  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:46:00.052  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 10:46:00.052  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:46:00.053  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:46:00.067  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:46:00.068  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:46:00.070  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:46:00.073  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:46:00.485  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602454747] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:00.495  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602454737] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:00.495  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:46:03.519  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602451713] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:46:03.521  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1602451711] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:46:03.521  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:06.543  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602448689] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:06.553  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602448679] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:06.554  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:09.578  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602445655] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:46:09.581  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602445652] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:09.581  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:12.603  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602442629] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:12.613  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602442619] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:12.613  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:46:15.634  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602439598] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:15.646  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602439586] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:15.646  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:18.667  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602436565] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:18.670  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602436562] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:46:18.670  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:21.696  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602433536] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:21.699  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602433533] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:21.699  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:24.725  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602430507] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:24.735  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602430497] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:24.736  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:46:27.758  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602427474] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:27.761  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602427471] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:46:27.761  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:30.788  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602424444] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:30.791  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602424441] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:46:30.791  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:33.820  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602421412] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:33.823  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602421409] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:33.823  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:36.842  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602418390] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:36.845  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602418387] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:36.853  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:39.874  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602415358] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:39.887  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602415346] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:39.887  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:46:42.907  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602412325] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:42.910  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602412322] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:46:42.910  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:45.935  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602409298] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:45.945  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602409287] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:45.946  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:48.968  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602406265] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:48.971  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602406262] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:46:48.971  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:51.997  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602403235] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:52.000  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602403232] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:46:52.000  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:55.027  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602400205] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:55.030  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602400202] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:55.030  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:46:57.920  1563  1563 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,06-30 10:46:57.920  1563  1563 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 10:46:57.944  1033  1527 D WifiController: battery changed pluggedType: 2
,06-30 10:46:57.948  1949  2118 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:46:57.948  1949  2118 D LEDHandler: Battery Level Remaining: 100%
06-30 10:46:57.948  1949  2118 D LEDHandler: Battery Temp: 277, mChargingStatus=5, mChargingStop=false
06-30 10:46:57.951  1563  1563 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
06-30 10:46:57.951  1563  1563 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:46:57.952  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:46:57.952  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:46:57.953  6120  6192 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:46:57.954  1563  1563 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:46:57.957  6740  6740 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,06-30 10:46:58.055  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602397178] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:58.065  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602397168] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:46:58.065  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:00.055  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:47:00.055  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 10:47:00.055  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:47:00.056  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:47:00.072  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:47:00.073  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:47:00.075  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:47:00.079  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:47:01.084  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602394149] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:01.093  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602394139] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:01.094  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:47:04.114  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602391118] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:04.128  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1602391105] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:04.128  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:07.149  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602388083] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:47:07.152  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602388080] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:47:07.152  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:10.178  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602385054] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:10.181  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602385051] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:10.181  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:13.210  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602382023] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:13.213  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602382019] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:13.213  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:16.240  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602378992] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:16.243  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602378989] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:16.243  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:19.264  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602375968] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:19.274  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602375958] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:19.274  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:47:22.294  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602372938] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:22.305  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602372927] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:22.305  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:47:25.324  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602369909] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:25.336  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602369897] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:25.336  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:47:28.358  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602366874] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:47:28.361  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602366871] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:47:28.361  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:31.386  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602363847] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:31.389  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602363843] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:31.389  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:34.415  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602360818] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:34.425  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602360807] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:34.426  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:47:37.445  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602357788] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:37.457  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1602357775] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:37.457  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:40.480  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602354752] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:47:40.483  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602354749] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:40.483  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:43.503  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602351729] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:43.511  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1602351721] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:43.512  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:47:46.532  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602348700] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:46.535  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602348697] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:46.545  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:49.565  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602345667] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:49.577  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602345655] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:49.578  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:52.598  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602342634] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:47:52.601  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602342631] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:47:52.601  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:55.627  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602339606] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:55.630  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602339603] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:55.630  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:47:58.654  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602336579] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:58.663  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602336569] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:47:58.664  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:00.059  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:48:00.059  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:48:00.059  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:48:00.060  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:48:00.073  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:48:00.074  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:48:00.078  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:48:00.084  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:48:01.683  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602333549] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:01.694  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602333539] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:01.694  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:48:04.717  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602330515] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:04.720  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602330512] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:48:04.720  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:07.744  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602327488] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:07.754  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602327478] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:07.754  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:48:10.774  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602324459] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:10.786  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1602324446] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:10.786  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:13.806  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602321427] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:48:13.810  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602321423] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:48:13.810  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:16.837  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602318397] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:16.840  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602318393] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:16.840  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:19.864  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602315368] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:19.875  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602315358] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:19.875  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:48:22.895  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602312337] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:22.906  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602312326] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:22.907  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:48:25.926  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602309306] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:25.929  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602309303] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:48:25.929  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:28.954  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602306278] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:28.965  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602306268] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:28.965  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:48:31.987  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602303245] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:31.990  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602303242] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:48:31.990  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:35.015  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602300217] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:35.025  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602300207] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:35.025  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:48:38.046  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602297186] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:38.049  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602297183] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:48:38.049  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:41.075  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602294158] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:41.085  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602294147] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:41.086  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:44.106  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602291127] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:48:44.109  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602291123] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:48:44.109  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:47.135  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602288098] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:47.145  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602288087] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:47.145  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:48:50.166  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602285066] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:50.169  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602285063] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:48:50.170  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:53.196  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602282037] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:53.200  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602282033] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:53.200  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:48:56.226  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602279007] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:56.229  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602279003] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:56.229  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:48:59.259  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602275973] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:48:59.262  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602275970] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:48:59.263  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:00.059  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:49:00.059  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:49:00.059  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-30 10:49:00.060  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:49:00.074  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:49:00.074  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:49:00.078  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:49:00.082  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:49:02.284  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602272948] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:02.294  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602272938] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:02.295  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:49:05.315  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602269917] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:05.327  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602269905] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:05.328  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:49:08.349  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602266884] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:08.352  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602266881] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:08.352  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:11.378  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602263854] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:11.381  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602263851] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:11.381  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:14.406  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602260827] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:14.409  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602260823] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:14.410  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:17.434  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602257798] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:17.444  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602257788] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:17.444  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:49:20.464  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602254768] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:20.477  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602254756] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:20.477  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:23.497  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602251736] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:23.500  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602251733] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:23.500  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:26.526  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602248707] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:26.529  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602248703] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:26.529  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:29.554  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602245678] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:29.564  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602245668] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:29.565  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:32.584  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602242648] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:32.597  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1602242635] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:32.597  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:35.618  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602239614] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:35.621  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602239611] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:35.621  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:38.646  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602236586] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:38.649  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602236583] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:38.650  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:41.677  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602233555] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:41.680  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602233552] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:41.680  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:44.705  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602230527] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:44.715  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602230517] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:44.715  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:49:47.735  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602227497] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:47.747  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602227485] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:47.747  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:49:50.768  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602224464] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:50.771  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602224461] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:50.771  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:53.797  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602221437] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:53.806  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602221427] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:53.806  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:56.828  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602218404] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:56.831  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602218401] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:56.832  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:49:59.858  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602215374] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:49:59.860  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1602215372] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:49:59.860  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:00.057  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:50:00.057  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:50:00.058  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:50:00.058  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:50:00.071  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:50:00.071  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:50:00.073  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:50:00.075  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:50:02.883  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602212349] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:02.893  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602212339] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:02.893  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:50:05.915  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602209318] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:05.927  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1602209305] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:05.927  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:50:08.948  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602206284] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:08.951  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602206281] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:08.951  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:11.979  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602203253] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:11.983  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602203250] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:11.983  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:15.007  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602200225] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:15.011  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602200222] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:15.011  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:18.037  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602197196] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:18.040  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602197193] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:18.040  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:21.067  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602194167] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:21.070  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602194163] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:21.070  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:24.095  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602191137] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:24.105  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602191127] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:24.105  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:50:27.126  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602188106] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:27.129  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602188103] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:27.129  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:30.164  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602185068] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:30.174  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602185058] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:30.174  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:50:31.629  1033  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=77432620, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,06-30 10:50:31.653  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{d12b4de type 2 when 1003656 com.android.bluetooth} when 1003656
,06-30 10:50:31.659  6120  6254 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 10:50:31.659  6120  6254 W bt-smp  : Plain text(LSB ~ MSB) = 64 80 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 10:50:31.659  6120  6254 W bt-smp  : Encrypted text(LSB ~ MSB) = 03 7d 10 6d a2 2d fa d1 50 0b 60 ad ed 62 63 b7 
06-30 10:50:31.659  6120  6254 W bt-btm  : Stopping oneshot timer
06-30 10:50:31.694  2574  2574 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 10:50:31.722  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=77432620 [*alarm*], flags=0x0
,06-30 10:50:33.194  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602182038] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:33.205  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602182028] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:33.205  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:36.227  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602179005] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:36.231  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602179002] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:36.231  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:39.258  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602175974] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:39.262  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602175971] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:39.262  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:42.287  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602172945] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:42.290  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602172942] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:42.290  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:45.317  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602169916] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:45.320  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602169912] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:45.320  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:48.347  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602166886] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:48.350  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602166883] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:48.350  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:51.377  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602163855] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:51.380  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602163852] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:51.380  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:50:54.405  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602160827] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:50:54.414  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1602160818] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:54.415  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:50:57.437  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602157795] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:57.438  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1602157794] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:50:57.438  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:00.052  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:51:00.052  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 10:51:00.052  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:51:00.053  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:51:00.067  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:51:00.067  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:51:00.069  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:51:00.071  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:51:00.457  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602154776] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:00.460  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602154772] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
06-30 10:51:00.460  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:03.482  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602151750] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:03.485  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602151747] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:03.485  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:06.511  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602148721] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:06.514  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602148718] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:06.514  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:09.539  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602145693] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:09.542  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602145690] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:09.542  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:12.568  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602142664] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:12.571  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602142661] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:12.571  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:15.599  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602139633] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:15.602  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602139630] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:15.602  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:18.223  1033  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=77432620, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,06-30 10:51:18.244  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{5c6d6bf type 2 when 1034799 com.google.android.gms} when 1034799
,06-30 10:51:18.292  2574  2574 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 10:51:18.319  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=77432620 [*alarm*], flags=0x0
,06-30 10:51:18.359  2140  7087 D GCM     : Message class com.google.e.a.a.h
,06-30 10:51:18.622  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602136610] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:18.623  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1602136609] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:18.623  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:21.633  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602133599] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:21.643  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602133589] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:21.643  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:51:24.664  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602130568] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:24.676  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602130556] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:24.677  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:51:27.697  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602127535] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:27.700  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602127532] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:27.700  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:30.727  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602124506] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:30.730  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602124502] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:30.730  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:33.759  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602121473] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:33.762  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602121470] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:33.762  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:36.789  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602118443] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:36.793  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602118440] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:36.793  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:39.819  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1602115413] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:39.822  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602115410] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:39.822  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:42.849  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602112383] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:42.853  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602112380] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:42.853  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:45.877  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602109356] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:45.880  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602109352] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:45.880  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:48.381  1033  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{21d1d18c type 2 when 1080399 com.google.android.gms} when 1080399
,06-30 10:51:48.432  1802  1802 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 10:51:48.438  2140  2140 I ConfigService: onCreate
06-30 10:51:48.438  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 10:51:48.440  1802  7259 I ConfigFetchService: running network task: configservice_periodic
06-30 10:51:48.443  1802  7259 I ConfigFetchService: launchTask
06-30 10:51:48.452  2140  2140 I ConfigService: onBind returning update interface
,06-30 10:51:48.456  1802  1802 I ConfigFetchService: service connected
06-30 10:51:48.456  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 10:51:48.456  2140  2140 I ConfigService: onBind returning config service
06-30 10:51:48.458  1802  1802 I ConfigClient: service connected
06-30 10:51:48.526  1033  1947 V SIM_STK : Menu title from STK is T-Mobile
,06-30 10:51:48.551  1802  2352 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,06-30 10:51:48.569   314  7268 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 10:51:48.569   314  7268 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,06-30 10:51:48.612   314  7268 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-30 10:51:48.891  1802  2352 W ConfigFetchTask: bad response from server: 401 Unauthorized
,06-30 10:51:48.893  1802  1802 I ConfigFetchService: fetch service done; releasing wakelock
06-30 10:51:48.894  1802  1802 I ConfigFetchService: stopping self
,06-30 10:51:48.905  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602106327] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:48.906  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1602106326] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:48.906  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:51:48.922  2140  2140 I ConfigService: onDestroy
,06-30 10:51:51.912  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602103320] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:51:51.922  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1602103311] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 10:51:51.923  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:51:54.942  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602100290] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:54.945  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602100287] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:51:54.945  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:51:57.972  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602097260] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:57.975  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602097257] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:51:57.975  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:00.053  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:52:00.053  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 10:52:00.053  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:52:00.054  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:52:00.068  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:52:00.068  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:52:00.070  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:52:00.072  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:52:01.003  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602094230] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:01.015  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602094227] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:01.017  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:04.037  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602091196] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:52:04.040  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602091192] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:52:04.040  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:07.065  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602088167] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:07.076  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602088157] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:07.076  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:10.096  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602085136] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:10.099  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602085133] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:52:10.099  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:13.124  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602082108] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:13.135  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602082098] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:13.135  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:52:16.156  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602079076] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:52:16.159  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602079073] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:52:16.160  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:19.183  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602076049] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:19.193  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602076039] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:19.193  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:22.214  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602073019] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:22.228  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1602073005] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:22.228  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:25.246  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602069986] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:52:25.249  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602069983] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:52:25.249  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:28.275  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602066957] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:28.285  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602066947] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:28.285  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:52:31.305  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602063927] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:31.317  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602063915] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:31.317  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:52:34.334  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602060898] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:34.345  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602060887] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:34.345  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:37.366  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602057866] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:52:37.369  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602057863] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:37.369  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:40.393  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602054839] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:40.401  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1602054831] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:40.402  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:52:43.424  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602051808] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:43.436  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1602051797] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:43.436  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:52:46.457  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602048775] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:46.460  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602048772] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:52:46.460  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:49.485  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602045747] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:49.499  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1602045733] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:49.499  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:52.519  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602042713] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:52:52.523  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602042710] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:52.523  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:55.549  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602039683] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:55.552  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602039680] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:52:55.552  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:52:58.580  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1602036652] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:58.583  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602036649] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:52:58.583  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:00.053  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:53:00.053  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:53:00.053  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-30 10:53:00.054  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:53:00.068  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:53:00.068  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:53:00.070  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:53:00.072  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:53:01.604  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602033628] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:01.617  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1602033615] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:01.618  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:04.639  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602030593] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:53:04.642  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602030590] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:53:04.642  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:07.668  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602027564] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:07.671  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602027561] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:07.671  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:10.695  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602024538] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:10.705  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1602024528] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:10.705  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:13.728  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602021505] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:53:13.731  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1602021501] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:13.731  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:16.755  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602018477] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:16.765  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1602018468] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:16.765  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:53:19.783  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1602015449] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:19.795  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1602015437] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:19.796  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:53:22.817  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602012415] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:22.820  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602012412] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:53:22.820  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:25.847  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1602009386] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:25.850  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602009383] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:25.850  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:28.879  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1602006353] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:28.882  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602006350] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:28.882  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:31.908  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1602003324] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:31.911  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602003321] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:31.912  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:34.937  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1602000295] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:34.940  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1602000292] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:53:34.941  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:37.967  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601997267] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:37.970  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1601997262] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:37.970  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:40.998  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1601994235] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:41.001  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601994231] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:53:41.001  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:44.024  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1601991208] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:44.033  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1601991199] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:44.034  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:53:47.054  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1601988179] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:47.066  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1601988167] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:47.066  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:50.087  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601985146] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:53:50.090  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601985143] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:53:50.090  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:53.114  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601982119] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:53.124  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1601982109] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:53.124  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:56.147  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1601979085] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:53:56.150  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601979082] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:56.150  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:53:59.175  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601976058] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:59.185  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1601976048] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:53:59.185  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:54:00.052  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:54:00.052  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:54:00.053  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:54:00.053  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:54:00.068  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:54:00.068  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:54:00.071  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:54:00.073  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:54:02.207  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601973025] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:02.210  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601973022] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:02.210  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:05.232  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601970000] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:05.240  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601969997] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:05.241  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:07.937  1033  1103 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 10:54:08.260  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1601966972] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:08.263  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1601966970] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:08.263  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:11.287  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601963945] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:11.290  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601963942] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:11.290  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:14.317  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601960917] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:14.320  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1601960912] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:14.320  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:17.347  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601957885] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:17.350  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601957882] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:17.350  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:20.374  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601954859] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:20.383  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1601954849] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:20.383  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:54:23.404  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1601951829] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:23.416  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1601951817] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:23.416  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:26.438  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601948795] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:26.441  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601948791] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:26.441  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:29.464  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601945768] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:29.473  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1601945759] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:29.473  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:54:32.487  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601942747] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:32.490  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1601942742] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:32.490  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:35.517  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1601939715] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:35.520  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601939712] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:35.521  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:38.545  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601936688] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:38.555  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1601936677] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:38.555  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:54:41.575  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601933657] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:41.588  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1601933644] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:41.588  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:54:44.609  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601930623] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:44.612  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1601930621] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:44.612  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:47.638  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601927595] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:47.641  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601927592] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:47.641  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:50.665  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601924567] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:50.674  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1601924558] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:50.674  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:54:53.696  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601921537] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:53.700  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601921533] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:53.700  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:56.727  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601918506] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:56.730  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601918502] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:54:56.730  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:54:59.756  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601915477] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:59.760  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601915473] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:54:59.760  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:00.056  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:55:00.056  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:55:00.057  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:55:00.057  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:55:00.070  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:55:00.071  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:55:00.073  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:55:00.075  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:55:02.784  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601912448] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:02.798  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1601912434] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:02.798  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:55:05.818  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601909414] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:05.821  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601909411] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:05.822  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:08.849  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1601906383] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:08.852  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601906380] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:08.852  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:11.877  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601903355] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:11.880  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601903352] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:11.880  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:14.906  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601900326] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:14.910  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601900323] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:14.910  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:17.935  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601897297] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:17.945  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1601897287] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:17.945  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:20.966  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601894267] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:20.970  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601894263] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:20.970  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:23.994  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601891238] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:24.005  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1601891227] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:24.005  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:55:27.027  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601888205] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:27.030  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601888202] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:27.030  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:30.054  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601885178] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:30.064  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1601885169] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:30.064  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:55:33.085  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601882147] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:33.097  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1601882135] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:33.097  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:36.118  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601879114] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:36.122  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601879111] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:36.122  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:39.149  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601876084] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:39.152  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601876080] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:39.152  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:42.177  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601873055] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:42.180  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601873052] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:42.180  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:45.207  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601870027] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:45.210  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1601870022] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:45.210  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:48.235  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601866997] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:48.252  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:17] from screen [on:0 period:-1601866980] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:48.252  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:55:51.274  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601863959] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:51.284  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1601863948] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:51.289  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:54.309  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601860923] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:54.312  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601860920] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:54.312  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:55:57.331  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601857902] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:55:57.334  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601857898] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:55:57.334  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:00.053  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:56:00.053  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:56:00.053  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:56:00.054  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:56:00.067  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:56:00.067  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:56:00.069  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:56:00.071  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:56:00.355  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601854877] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:00.369  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1601854863] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:00.369  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:03.389  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601851843] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:56:03.392  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601851840] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:03.392  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:06.413  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601848819] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:06.422  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1601848810] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:06.422  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:09.443  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601845789] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:09.456  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1601845776] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:09.456  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:12.476  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601842757] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:56:12.479  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601842753] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:56:12.479  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:15.507  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601839726] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:15.510  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601839723] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:15.510  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:18.536  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601836696] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:18.539  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601836693] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:56:18.539  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:21.566  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601833666] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:21.569  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601833663] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:21.570  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:24.594  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601830638] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:24.604  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1601830628] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:24.605  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:56:27.627  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601827607] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:27.630  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1601827602] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:56:27.630  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:30.655  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601824577] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:30.665  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1601824567] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:30.665  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:33.683  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601821549] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:33.696  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1601821537] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:33.696  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:56:36.717  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601818515] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:36.720  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601818512] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:56:36.720  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:39.745  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601815487] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:39.755  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1601815478] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:39.755  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:56:42.776  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601812457] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:42.779  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601812453] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:56:42.779  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:45.804  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601809428] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:45.814  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1601809418] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:45.815  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:48.837  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601806396] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:56:48.840  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601806392] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:48.840  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:56:51.864  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601803368] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:51.874  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1601803358] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:51.874  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:56:54.894  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1601800339] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:54.906  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1601800327] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:54.906  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:56:57.927  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601797305] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:56:57.931  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601797302] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:56:57.931  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:00.052  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:57:00.052  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 10:57:00.052  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:57:00.053  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:57:00.067  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:57:00.067  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:57:00.069  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:57:00.071  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:57:00.957  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601794275] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:57:00.960  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601794272] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:57:00.960  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:03.985  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601791247] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:03.995  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1601791237] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:03.995  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:57:07.012  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601788220] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:57:07.015  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601788217] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:57:07.015  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:10.041  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601785192] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:57:10.044  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601785189] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:57:10.044  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:13.073  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601782160] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:13.082  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1601782151] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:13.083  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:57:16.103  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1601779129] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:16.115  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1601779117] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:16.115  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:19.136  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601776097] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:57:19.139  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601776093] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:19.139  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:22.166  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601773066] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:22.169  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601773063] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:57:22.169  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:25.195  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601770037] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:25.205  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1601770028] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:25.205  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:28.225  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601767007] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:28.245  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:20] from screen [on:0 period:-1601766987] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:57:28.245  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:31.265  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601763968] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:31.274  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1601763958] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:31.274  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:34.296  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601760936] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:34.299  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601760933] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:57:34.299  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:37.329  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1601757903] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:37.331  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1601757901] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:37.331  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:40.352  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601754880] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:40.362  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601754877] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:40.362  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:43.384  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601751849] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:43.397  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1601751836] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:43.397  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:46.418  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601748814] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:46.421  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601748811] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:57:46.421  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:49.448  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601745784] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:49.451  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601745781] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:49.451  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:52.472  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1601742760] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:52.475  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601742757] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:52.475  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:55.498  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601739734] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:55.502  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601739731] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:55.502  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:57:58.528  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601736704] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:58.531  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601736701] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:57:58.531  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:58:00.071  1563  1563 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 10:58:00.071  1563  1563 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 10:58:00.071  1563  1563 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 10:58:00.072  1563  1563 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:58:00.087  1563  1563 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 10:58:00.087  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
,06-30 10:58:00.088  1563  1563 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:58:00.088  1563  1563 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:58:01.557  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601733676] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:58:01.560  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601733672] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:58:01.560  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL],
,06-30 10:58:04.587  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601730646] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:04.590  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1601730642] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:04.590  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:58:07.618  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1601727614] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:07.621  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601727611] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:07.621  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:58:10.648  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601724585] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:10.651  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601724582] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:10.651  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:58:13.672  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1601721560] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:13.675  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601721557] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:58:13.675  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:58:16.702  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601718531] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:16.705  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601718528] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:16.705  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:58:19.732  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601715500] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:19.735  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601715497] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:58:19.735  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:58:22.762  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601712470] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:22.765  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601712467] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:22.774  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:58:25.795  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601709438] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:25.806  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1601709427] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:25.806  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:58:28.827  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601706405] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:28.830  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601706402] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:58:28.831  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:58:31.856  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1601703376] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:31.860  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601703373] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:31.860  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:58:34.885  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1601700347] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:34.896  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1601700336] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:34.896  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:58:37.917  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601697315] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 10:58:37.920  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601697312] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:58:37.920  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 10:58:40.944  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1601694288] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,TIME-OUT KILL (timeout was 1400000ms),06-30 10:58:40.954  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1601694278] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:58:40.955  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:58:43.977  1033  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1601691255] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:58:43.980  1033  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1601691252] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 10:58:43.992  1033  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 10:58:45.345  7278  7278 D AndroidRuntime: 
06-30 10:58:45.345  7278  7278 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 10:58:45.351  7278  7278 D AndroidRuntime: CheckJNI is OFF
06-30 10:58:45.480  7278  7278 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 10:58:45.490  1033  1105 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
06-30 10:58:45.491  1033  1105 I ActivityManager: Killing 5800:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
06-30 10:58:45.551  1033  1744 I WindowState: WIN DEATH: Window{227e0b45 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 10:58:45.551  1033  1527 D WifiService: Client connection lost with reason: 4
06-30 10:58:45.559  1033  1744 D InputDispatcher: Window went away: Window{227e0b45 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 10:58:45.626  1033  1105 I ActivityManager:   Force finishing activity ActivityRecord{2e453506 u0 com.test.thalitest/.MainActivity t12}
06-30 10:58:45.650   339   362 E GBMv2   : DFP En is all cleared set to be enabled
06-30 10:58:45.652  1033  1048 W ActivityManager: Spurious death for ProcessRecord{528edaf 5800:com.test.thalitest/u0a118}, curProc for 5800: null
06-30 10:58:45.653  1033  1121 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
06-30 10:58:45.654  1033  1121 I ActivityManager:   Force finishing activity ActivityRecord{2e453506 u0 com.test.thalitest/.MainActivity t12 f}
06-30 10:58:45.654  1033  1121 W ActivityManager: Duplicate finish request for ActivityRecord{2e453506 u0 com.test.thalitest/.MainActivity t12 f}
06-30 10:58:45.690  2060  2060 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
06-30 10:58:45.691  2060  2060 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
06-30 10:58:45.693  1949  1964 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
06-30 10:58:45.693  1949  1964 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ea14f37 co.....Launcher}, taskId=11, activityType=1, bIsSplit=false
06-30 10:58:45.693  1949  1965 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
06-30 10:58:45.694  1949  1965 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c5baca4 co.....Launcher}, taskId=11, activityType=1, bIsSplit=false
06-30 10:58:45.697  2060  2060 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
06-30 10:58:45.698  2060  2138 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
06-30 10:58:45.700  1912  1912 D ActionManagerService: notifyUserLog: 1000003
06-30 10:58:45.703  2689  4156 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
06-30 10:58:45.703  2689  2689 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
06-30 10:58:45.704  2060  2060 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
06-30 10:58:45.706  1563  1563 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
06-30 10:58:45.707  1033  1446 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 10:58:45.710  2011  2011 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
06-30 10:58:45.711  2459  2635 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 10:58:45.712  4289  4289 I art     : Explicit concurrent mark sweep GC freed 7906(461KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 260us total 40.377ms
06-30 10:58:45.716  6120  6120 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
06-30 10:58:45.716  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
06-30 10:58:45.768  1033  1105 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7299 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
06-30 10:58:45.775  2060  2060 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
06-30 10:58:45.787  4198  4198 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 10:58:45.787  4198  4198 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
06-30 10:58:45.787  4198  4198 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
06-30 10:58:45.787  4198  4198 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
06-30 10:58:45.787  4198  4198 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:58:45.787  4198  4198 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:58:45.787  4198  4198 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:58:45.787  4198  4198 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-30 10:58:45.788  4198  4198 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:58:45.788  4198  4198 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:58:45.788  4198  4198 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 10:58:45.788  4198  4198 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-30 10:58:45.791  2060  2060 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
06-30 10:58:45.792  1563  1633 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-30 10:58:45.792  1563  1633 D KeyguardModel: createShortcutInfo...
06-30 10:58:45.793  2060  2060 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
06-30 10:58:45.794  1563  1563 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
06-30 10:58:45.798  1563  1633 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-30 10:58:45.798  1563  1633 D KeyguardModel: createShortcutInfo...
06-30 10:58:45.799  1912  1912 D ActionManagerService: notifyUserLog: 1000004
06-30 10:58:45.799  2689  4156 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
06-30 10:58:45.800  2060  2060 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
06-30 10:58:45.805  2689  2705 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , create_time: 1430832262123
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , expire_time: 0
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , display: false
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , animation: false }
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , create_time: 1430832262287
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , expire_time: 0
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , display: false
06-30 10:58:45.809  2060  2060 I GBoardWebViewUtils: , animation: false }
06-30 10:58:45.810  2060  2060 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1467198142274
06-30 10:58:45.810  2060  2060 I GBoardWebViewUtils: , create_time: 1467198143124
06-30 10:58:45.810  2060  2060 I GBoardWebViewUtils: , expire_time: 0
06-30 10:58:45.810  2060  2060 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1467198142274&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
06-30 10:58:45.810  2060  2060 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
06-30 10:58:45.810  2060  2060 I GBoardWebViewUtils: , display: false
06-30 10:58:45.810  2060  2060 I GBoardWebViewUtils: , animation: false }
06-30 10:58:45.826  1563  1633 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
06-30 10:58:45.828  1033  1911 V SIM_STK : Menu title from STK is T-Mobile
06-30 10:58:45.830  1563  1633 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:58:45.830  1563  1633 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
06-30 10:58:45.831  1563  1633 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
06-30 10:58:45.831  2060  2060 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 10:58:45.832  2060  7326 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
06-30 10:58:45.832  2060  2060 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
06-30 10:58:45.833  1563  1563 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
06-30 10:58:45.836  1033  1984 V SIM_STK : Menu title from STK is T-Mobile
06-30 10:58:45.836  1033  1984 V SIM_STK : Menu title from STK is T-Mobile
06-30 10:58:45.839  1563  1633 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:58:45.839  1563  1633 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-30 10:58:45.845  1563  1633 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-30 10:58:45.845  1563  1633 D KeyguardModel: createShortcutInfo...
06-30 10:58:45.849  1563  1633 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
06-30 10:58:45.849  1563  1633 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:58:45.856  1563  1633 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:58:45.856  1563  1633 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-30 10:58:45.857  1563  1633 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-30 10:58:45.857  1563  1633 D KeyguardModel: createShortcutInfo...
06-30 10:58:45.861  1563  1633 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:58:45.861  1563  1633 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 10:58:45.862  1563  1633 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
06-30 10:58:45.862  1563  1633 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
06-30 10:58:45.863  1563  1633 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:58:45.864  1563  1633 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-30 10:58:45.876  1563  1633 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-30 10:58:45.877  1563  1633 D KeyguardModel: createShortcutInfo...
06-30 10:58:45.884  1563  1563 D KeyguardModel: handleShortcutListChanged...
06-30 10:58:45.884  1563  1563 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
06-30 10:58:45.888  1033  1948 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
06-30 10:58:45.889  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
06-30 10:58:45.889  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
06-30 10:58:45.889  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
06-30 10:58:45.889  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
06-30 10:58:45.889  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
06-30 10:58:45.889  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-30 10:58:45.889  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
06-30 10:58:45.889  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
06-30 10:58:45.889  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
06-30 10:58:45.889  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-30 10:58:45.889  6120  6120 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
06-30 10:58:45.902  7299  7299 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:58:45.913  2060  2088 I art     : Background partial concurrent mark sweep GC freed 7018(306KB) AllocSpace objects, 4(468KB) LOS objects, 28% free, 79MB/111MB, paused 12.358ms total 25.310ms
06-30 10:58:45.914  2060  2060 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
06-30 10:58:45.932  1877  1877 D SplitUIManager: split_name #11 / not available #0
06-30 10:58:45.932  1877  1877 D SplitUIService: removed split : 
06-30 10:58:45.941  1563  1563 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
06-30 10:58:45.942  1033  1033 I art     : Explicit concurrent mark sweep GC freed 307406(14MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 44MB/66MB, paused 2.940ms total 252.804ms
06-30 10:58:45.942  1033  1121 I art     : WaitForGcToComplete blocked for 32.892ms for cause Explicit
06-30 10:58:45.948  1033  1744 V SIM_STK : Menu title from STK is T-Mobile
06-30 10:58:45.951  1877  1877 D SplitUIManager: split_name #11 / not available #0
06-30 10:58:45.951  1877  1877 I SplitUIService: split app #11
06-30 10:58:45.953  1563  1633 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-30 10:58:45.953  1563  1633 D KeyguardModel: createShortcutInfo...
06-30 10:58:45.954  7299  7299 D PluginManager: init()
06-30 10:58:45.966   333   429 I ThermalEngine: Thermal-Server: Thermal received msg from  override
06-30 10:58:45.967  3090  7330 I Thermal-Lib: Thermal-Lib-Client: Client request sent
06-30 10:58:45.968  1563  1633 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-30 10:58:45.968  1563  1633 D KeyguardModel: createShortcutInfo...
06-30 10:58:45.972  1563  1633 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:58:45.972  1563  1633 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-30 10:58:45.974  1563  1633 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-30 10:58:45.974  1563  1633 D KeyguardModel: createShortcutInfo...
06-30 10:58:45.977  1563  1633 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:58:45.977  1563  1633 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-30 10:58:45.979  1563  1633 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-30 10:58:45.979  1563  1633 D KeyguardModel: createShortcutInfo...
06-30 10:58:45.982  1563  1633 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:58:45.982  1563  1633 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-30 10:58:45.983  1033  1033 D administrator: Handling package changes for user 0
06-30 10:58:45.986  1563  1633 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-30 10:58:45.986  1563  1633 D KeyguardModel: createShortcutInfo...
06-30 10:58:45.994  2060  2060 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
06-30 10:58:46.006  1563  1563 D KeyguardModel: handleShortcutListChanged...
06-30 10:58:46.006  1563  1563 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
06-30 10:58:46.007  2060  2060 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 10:58:46.008  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
06-30 10:58:46.009  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
06-30 10:58:46.010  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
06-30 10:58:46.011  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
06-30 10:58:46.027  2060  2060 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
06-30 10:58:46.027  2060  2060 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 10:58:46.033  2060  2196 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
06-30 10:58:46.033  2060  2196 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
06-30 10:58:46.042  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
06-30 10:58:46.042  2060  2060 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
06-30 10:58:46.042  2060  2060 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 10:58:46.048  1033  1116 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1bcf720f u0 com.lge.launcher2/.Launcher t11} time:1498092
06-30 10:58:46.050  2060  2060 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
06-30 10:58:46.051  2574  2574 D [Concierge]Service: onStartCommand(). Type : 8
06-30 10:58:46.051  2574  2574 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
06-30 10:58:46.053  2060  2060 D [Concierge]WidgetView: change position of spinner
06-30 10:58:46.054  2574  2574 D [Concierge]Service: Update widget ID : 11
06-30 10:58:46.055  2574  2574 D [Concierge]Service: onStartCommand(). Type : 0
06-30 10:58:46.055  2060  2060 I [Concierge]WidgetView: initWebView(). Time : 1467277126055
06-30 10:58:46.066  2060  2060 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 568950938
06-30 10:58:46.066  2060  2060 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
06-30 10:58:46.067  2060  2060 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
06-30 10:58:46.070  2060  2060 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@111106d3
06-30 10:58:46.071  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
06-30 10:58:46.071  2060  2060 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
06-30 10:58:46.071  2060  2060 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 10:58:46.077  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
06-30 10:58:46.077  2060  2060 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
06-30 10:58:46.078  2060  2060 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1467275654836, New one : 1467277126055
06-30 10:58:46.078  2060  2060 D [Concierge]WidgetView: Unregister all receivers
06-30 10:58:46.078  2060  2060 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
06-30 10:58:46.078  2060  2060 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 10:58:46.080  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
06-30 10:58:46.081  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
06-30 10:58:46.082  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
06-30 10:58:46.083  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
06-30 10:58:46.084  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
06-30 10:58:46.087  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
06-30 10:58:46.088  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 10:58:46.088  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 10:58:46.088  2060  2060 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 10:58:46.088  2060  2060 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 10:58:46.089  1033  1562 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
06-30 10:58:46.123  2060  2060 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
06-30 10:58:46.131  2060  2060 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
06-30 10:58:46.131  2060  2060 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
06-30 10:58:46.131  2060  2060 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
06-30 10:58:46.132  2060  2060 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 10:58:46.159  2060  2060 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ac5957 time:1498203
06-30 10:58:46.167  1033  1121 I art     : Explicit concurrent mark sweep GC freed 19063(1182KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.641ms total 214.773ms
06-30 10:58:46.218  7278  7278 D AndroidRuntime: Shutting down VM
06-30 10:58:46.260  2060  2060 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
06-30 10:58:46.297  2060  2846 I GBoardtInterface: onReloaded()
06-30 10:58:46.298  2060  2060 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
06-30 10:58:46.299  2689  2742 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
06-30 10:58:46.301  2689  2706 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
06-30 10:58:46.306  1912  1912 D ActionManagerService: notifyUserLog: 1000001
06-30 10:58:46.306  7299  7299 W ExternalStrings: load override strings
06-30 10:58:46.306  7299  7299 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 10:58:46.306  7299  7299 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-30 10:58:46.307  2689  4156 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
06-30 10:58:46.307  2689  4156 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
06-30 10:58:46.307  7299  7299 D StatusProvider: onCreate
06-30 10:58:46.309  1912  1912 D ActionManagerService: notifyUserLog: 1000001
06-30 10:58:46.311  2689  4156 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
06-30 10:58:46.311  2689  4156 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
06-30 10:58:46.311  2689  4156 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
06-30 10:58:46.311  2689  2706 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
06-30 10:58:46.311  2689  4156 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
06-30 10:58:46.313  2060  2060 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
06-30 10:58:46.313  2060  2060 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
06-30 10:58:46.314  2060  2060 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
06-30 10:58:46.314  2060  2060 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
06-30 10:58:46.316  2060  2060 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1467198142274&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
06-30 10:58:46.316  2060  2060 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1467198142274&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
06-30 10:58:46.339  7299  7299 V Signer  : override build config not found
06-30 10:58:46.340  7299  7299 D Signer  : value of property debug is false
06-30 10:58:46.341  1033  1103 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:58:46.345  1033  1103 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
06-30 10:58:46.346  2060  2060 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
06-30 10:58:46.362  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
06-30 10:58:46.362  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
06-30 10:58:46.362  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
06-30 10:58:46.363  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
06-30 10:58:46.363  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
06-30 10:58:46.363  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
06-30 10:58:46.363  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
06-30 10:58:46.363  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
06-30 10:58:46.363  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
06-30 10:58:46.363  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
06-30 10:58:46.363  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
06-30 10:58:46.364  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
06-30 10:58:46.364  7299  7299 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
06-30 10:58:46.372  7299  7299 V LGMDMManager: Create singleton instance
06-30 10:58:46.412  7299  7299 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
06-30 10:58:46.442  7299  7299 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
06-30 10:58:46.446  7299  7337 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
06-30 10:58:46.446  1033  1121 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7338 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
06-30 10:58:46.450  1802  1802 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
06-30 10:58:46.466  2140  2140 I ConfigService: onCreate
06-30 10:58:46.470  1802  1802 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
06-30 10:58:46.470  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 10:58:46.479  2140  2140 I ConfigService: onBind returning update interface
06-30 10:58:46.480  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 10:58:46.480  2140  2140 I ConfigService: onBind returning config service
06-30 10:58:46.482  1033  1983 I ActivityManager: Killing 6052:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
06-30 10:58:46.495  6300  6300 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
06-30 10:58:46.495  6300  6300 W System.err: android.os.DeadObjectException
06-30 10:58:46.495  6300  6300 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-30 10:58:46.495  6300  6300 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-30 10:58:46.495  6300  6300 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
06-30 10:58:46.496  6300  6300 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-30 10:58:46.496  6300  6300 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:58:46.496  6300  6300 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:58:46.496  6300  6300 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 10:58:46.496  6300  6300 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-30 10:58:46.496  6300  6300 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
06-30 10:58:46.496  6300  6300 W System.err: android.os.DeadObjectException
06-30 10:58:46.496  6300  6300 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-30 10:58:46.496  6300  6300 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
06-30 10:58:46.496  6300  6300 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:58:46.496  6300  6300 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-30 10:58:46.496  6300  6300 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:58:46.496  6300  6300 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:58:46.496  6300  6300 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 10:58:46.496  6300  6300 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-30 10:58:46.497  6300  6300 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
06-30 10:58:46.497  6300  6300 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
06-30 10:58:46.564  7299  7336 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());

```
